# STEWARD

**An engineering ethics decision instrument**

STEWARD helps engineers, project teams, reviewers, and public interest practitioners examine difficult technical decisions without reducing ethics to a single score.

It maps stakeholders, benefits, burdens, consent, safety effects, environmental consequences, privacy risks, reversibility, evidence, professional duties, alternatives, safeguards, dissent, monitoring, and decision history.

The instrument is local first, browser based, and contained in a single HTML file.

**Current version:** 2.1  
**Primary artifact:** `steward-v2.1.html`

---

## Core Principle

STEWARD refuses to compress ethical reasoning into one number.

A single score can hide who receives the benefits, who carries the burdens, which duties conflict, where evidence is weak, and which concerns remain unresolved.

Instead, STEWARD preserves:

* Competing obligations
* Unequal distributions of benefit and burden
* Missing or constrained consent
* Uncertainty and disputed evidence
* Minority opinions and dissent
* Unverified safeguards
* Review triggers
* Conditions for proceeding
* Reasons to pause, redesign, escalate, or refuse

Completion of a form does not mean a decision is ethically acceptable.

---

## What STEWARD Produces

STEWARD can generate:

* Executive ethics briefs
* Full ethics assessments
* Stakeholder maps
* Evidence registers
* Claims and assumption inventories
* Professional obligation registers
* Duty conflict records
* Alternatives comparisons
* Safeguard verification plans
* Deliberation records
* Dissent statements
* Approval and checkpoint records
* Monitoring reports
* Incident and complaint logs
* Decision baselines
* Decision lineage
* Public transparency summaries
* Redacted external briefs
* Complete JSON decision packages
* Markdown, HTML, CSV, and Word compatible exports
* Presentation outlines
* Print and PDF output

---

## Workflow

STEWARD organizes ethical review into a continuing lifecycle:

**Frame → Map → Engage → Investigate → Compare → Safeguard → Deliberate → Approve → Monitor → Reconsider → Baseline → Publish**

### 1. Frame

Define the actual decision.

Record:

* Decision statement
* Purpose and context
* Scope and boundaries
* Constraints
* Known facts
* Assumptions and unknowns
* Professional judgment
* Decision authority
* Review dates
* Current governance state

### 2. Map

Identify everyone and everything affected by the decision.

Stakeholders may include:

* Direct users
* Workers
* Maintainers
* Bystanders
* Communities
* Institutions
* The public
* Future stakeholders
* Ecosystems and environmental interests
* Groups with no practical voice

STEWARD pays particular attention to stakeholders with high exposure and little influence.

### 3. Engage

Document how stakeholders participate in the process.

STEWARD distinguishes between:

* Consent
* Consultation
* Notification
* Representation
* Compliance

These are not interchangeable.

Engagement records may include:

* Meetings
* Interviews
* Listening sessions
* Testimony
* Questions
* Concerns
* Commitments
* Accessibility needs
* Communication needs
* Recourse and appeal mechanisms
* Exclusion from the process

### 4. Investigate

Separate observations from assumptions and claims from evidence.

Evidence can be classified as:

* Observation
* Measurement
* Test result
* Stakeholder testimony
* Published evidence
* Expert judgment
* Incident history
* Standard or regulation
* Assumption
* Disputed claim
* Unknown

Claims can link to both supporting and contradictory evidence.

STEWARD surfaces:

* Unsupported claims
* Evidence gaps
* Stale evidence
* Assumption driven impacts
* Unequal evidence standards
* Contradictions
* Unresolved uncertainty

### 5. Compare

Consider meaningful alternatives.

STEWARD encourages teams to include:

* Proceed as proposed
* Redesign
* Reduced scope
* Limited pilot
* Delay
* Independent review
* Substitute technology
* Nontechnical alternatives
* Do not proceed

Alternatives are compared qualitatively. STEWARD does not calculate a weighted ethics total.

### 6. Safeguard

Document controls and test whether they are strong enough.

Safeguards are classified using a hierarchy:

1. Eliminate the hazard or burden
2. Substitute a safer approach
3. Redesign the system
4. Add technical controls
5. Add procedural controls
6. Train or warn
7. Rely on individual behavior

Each safeguard can include:

* Owner
* Status
* Verification method
* Verification evidence
* Dependencies
* Failure consequences
* Residual burdens
* Review triggers
* Linked options, impacts, and monitoring indicators

STEWARD warns when a decision depends mainly on policy, warnings, training, or individual vigilance.

### 7. Deliberate

Record how the decision was discussed and challenged.

The deliberation workspace supports:

* Review sessions
* Participants and roles
* Decision authority
* Conflict disclosures
* Recusals
* Independent reviewers
* Objections
* Minority opinions
* Follow up actions
* Conditional approval
* Approval expiration
* Signoffs and checkpoints

An objection can remain visible even when the decision proceeds.

### 8. Monitor

Ethical review continues after implementation.

Monitoring records can track:

* Ethical performance indicators
* Complaints
* Incidents
* Unexpected consequences
* Stakeholder feedback
* Scope expansion
* Secondary uses
* Safeguard weakening
* Pilot to permanent transitions
* Review thresholds
* Required responses
* Reconsideration events

A decision can be explicitly reopened when circumstances change.

### 9. Baseline

Create frozen records of important decision states.

Baselines preserve:

* Decision framing
* Stakeholders
* Evidence and claims
* Impacts
* Duties
* Alternatives
* Safeguards
* Deliberation
* Approvals
* Monitoring
* Incidents
* Open objections
* Decision rationale

Baselines can be compared, exported, restored, or marked as superseded.

### 10. Publish

Build the appropriate record for the intended audience.

Available report profiles include:

* Executive ethics brief
* Full ethics assessment
* Deliberation record
* Monitoring report
* Public transparency summary
* Redacted external brief

---

## STEWARD v2.1 Features

### Integrated Ethics Workbench

The interface is organized into five workflow groups:

#### Define

* Overview
* Decision frame
* Stakeholders
* Engagement

#### Investigate

* Evidence
* Claims
* Impacts
* Professional duties

#### Decide

* Options
* Safeguards
* Deliberation
* Approvals

#### Operate

* Monitoring
* Incidents
* Change control
* Review triggers

#### Document

* Relationships
* Archive
* Baselines
* Decision lineage
* Stakeholder maps
* Ethics brief
* Templates
* Settings

### Decision Readiness

STEWARD uses named readiness conditions rather than a score.

It checks whether:

* The decision is clearly framed
* Material stakeholders are represented
* Consequential claims have evidence
* Serious impacts have safeguards
* Professional obligations have owners
* Meaningful alternatives were considered
* Dissent has been documented
* Approval conditions are assigned
* Monitoring and review triggers exist
* Blocking obligations are explained

Possible states include:

* Not ready
* Ready for review
* Ready only with exceptions
* Approved with conditions
* Implemented under monitoring
* Reopened

Every state explains what is blocking progress.

### Explainable Ethical Tensions

Detected tensions may include:

* High exposure with low influence
* Benefits and burdens assigned to different groups
* Missing or constrained consent
* High consequence impacts
* Difficult or irreversible effects
* Weak evidence
* Unowned obligations
* Unverified safeguards
* Hidden duty conflicts
* Missing alternatives
* Unrecorded dissent
* Monitoring without action thresholds
* Temporary practices becoming permanent

Each tension can record:

* Why it was raised
* Related records
* Helpful evidence
* Accountable owner
* Whether it blocks readiness
* Response or rationale
* Current disposition

Accepted unresolved concerns remain visible.

### Relationship Inspector

Every record can reveal its connections.

Examples include:

* Stakeholders linked to engagements and commitments
* Evidence linked to claims
* Claims linked to impacts
* Impacts linked to safeguards
* Obligations linked to competing duties
* Options linked to safeguards
* Safeguards linked to monitoring indicators
* Review sessions linked to objections
* Monitoring events linked to reconsideration

The workbench also detects broken and orphaned links.

### Ethical Pattern Library

STEWARD v2.1 includes contextual patterns for:

* Artificial intelligence deployment
* Workplace monitoring
* Public safety systems
* Environmental releases
* Safety critical software
* Autonomous equipment
* Medical and assistive devices
* Data collection systems
* Community infrastructure
* Dual use technology
* Product safety
* Experimental pilots
* Cybersecurity disclosure
* Algorithmic allocation
* Maintenance deferral
* Manipulative interfaces
* Accessibility critical interfaces
* Climate adaptation
* Human subject field testing
* Supply chain labor
* Public procurement
* Emergency deployment
* Legacy system retirement
* Repairability
* Predictive enforcement
* Critical communications

Multiple patterns can be active at the same time.

Patterns provide prompts and warning signs. They do not provide conclusions.

### Custom Pattern Builder

Users can create local project specific patterns with:

* Scope and purpose
* Stakeholders to consider
* Duties to investigate
* Review prompts
* Warning signs
* Stronger safeguards
* Monitoring prompts
* Reconsideration prompts

Custom patterns can be edited, activated, exported, imported, and deleted.

### Ethical Failure Mode Scanner

STEWARD includes heuristic prompts for common reasoning failures.

Examples include:

* Legal compliance treated as ethical sufficiency
* Schedule pressure presented as necessity
* Technology defining the problem
* Benefits described more specifically than burdens
* Aggregate benefit hiding unequal distribution
* Consent theater
* Consultation mistaken for consent
* Data collected because it is available
* No evidence of harm treated as evidence of no harm
* Stronger evidence required for harms than benefits
* Reversibility asserted but not demonstrated
* Responsibility outsourced to a vendor
* Competing duties hidden
* Dissent removed from the rationale
* Independent review omitted
* Policy or training substituted for safer design
* Safeguard dependencies ignored
* Monitoring without action thresholds
* Pilots quietly becoming permanent
* Temporary exceptions becoming normal practice
* Lifecycle burdens transferred to maintainers

A scanner signal is not a finding, violation, or automated moral conclusion.

Every signal requires human review and can be classified as:

* Unreviewed
* Investigating
* Mitigating
* Accepted unresolved
* Not applicable
* Resolved
* Rejected signal

---

## Stakeholder Maps

STEWARD includes three visual stakeholder map modes.

### Influence and Exposure

Shows who can influence the decision and who is exposed to its consequences.

The upper left region identifies the ethical blind spot:

**High exposure with low influence**

### Benefits and Burdens

Shows how expected benefits and burdens are distributed.

This view helps reveal decisions where one group receives the benefit while another group carries the cost or risk.

### Representation and Exposure

Shows whether highly exposed stakeholders have meaningful representation in the decision process.

Accessible table alternatives are provided for map content.

---

## Local First Data

STEWARD runs entirely in the browser.

By default:

* No account is required
* No server is required
* No project data is uploaded
* No external database is used
* Work is saved to browser local storage
* The application remains usable offline after download
* Data leaves the browser only when the user intentionally exports it

Because browser storage can be cleared, important work should be exported regularly.

---

## Installation

No installation process is required.

1. Download `steward-v2.1.html`
2. Open it in a modern browser
3. Begin a new decision or load the demonstration
4. Export the workspace JSON regularly

For a web deployment, upload the file to any static web host.

Example:

```text
https://example.com/steward/
```

The file may be renamed to `index.html`.

---

## Updating

STEWARD includes schema migration for earlier workspace versions.

Recommended update process:

1. Open the older STEWARD release
2. Export the complete JSON workspace
3. Open the new STEWARD release
4. Import the JSON workspace
5. Review migration notices and diagnostics
6. Export a new safety copy

Do not delete the previous export until the migrated workspace has been inspected.

---

## Import and Export

### Workspace Data

* Complete JSON workspace
* Decision package
* Baseline JSON
* Archive index
* Diagnostics report

### Written Outputs

* Markdown
* HTML
* Word compatible document
* Print
* PDF through the browser print dialog

### Registers

* CSV register exports
* Evidence register
* Claims register
* Stakeholder register
* Obligation register
* Safeguard register
* Monitoring register
* Pattern review register
* Failure mode review register

### Presentation Support

* Presentation outline export
* Executive decision summary
* Review findings
* Conditions and next actions

---

## Autosave and Recovery

STEWARD automatically saves changes to browser local storage.

The interface displays the current save state.

Recovery features include:

* Automatic safety backups
* Backup restoration
* Import validation
* Schema migration
* Broken relationship detection
* Orphaned link repair
* Baseline restoration
* Automatic reopening after restoring an earlier decision state

Restoring a backup or baseline should be treated as a controlled decision change.

---

## Archive Behavior

Archiving removes a record from active analysis without erasing its history.

Archived records are excluded from:

* Active dashboard metrics
* Stakeholder maps
* Deliberation option lists
* Readiness analysis
* Active reports

The global archive supports:

* Search
* Filtering
* Sorting
* Relationship counts
* Restoration
* Permanent deletion
* Archive index export

Permanent deletion should be used only when retention is inappropriate.

---

## Accessibility

STEWARD includes:

* Keyboard navigation
* Visible focus states
* High contrast mode
* Reduced motion mode
* Adjustable interface density
* Larger interface text
* Accessible map tables
* Large touch targets
* Mobile navigation
* Print layouts designed for grayscale
* Labels that do not rely on color alone

Press `/` to move focus to search where supported.

---

## Demonstration Workspace

The built in demonstration examines a proposed wearable proximity monitoring pilot in a fabrication laboratory.

It includes:

* Worker safety benefits
* Location privacy risks
* Constrained workplace consent
* Electronic waste concerns
* Professional duties
* Worker consultation
* Competing alternatives
* Privacy preserving safeguards
* Objections and minority views
* Conditional approval
* Monitoring thresholds
* Decision baselines
* Pattern reviews
* Failure mode investigations

Loading the demonstration replaces the active workspace, so export current work first.

---

## Suggested Uses

STEWARD is suitable for decisions involving:

* Product safety
* Workplace technology
* Artificial intelligence
* Data collection
* Surveillance
* Public infrastructure
* Environmental risk
* Safety critical software
* Autonomous systems
* Medical and assistive devices
* Cybersecurity
* Maintenance deferral
* Accessibility
* Experimental pilots
* Community planning
* Dual use technology
* Public procurement
* Engineering changes with significant human consequences

---

## What STEWARD Does Not Do

STEWARD does not:

* Produce an ethics score
* Decide whether a project is morally acceptable
* Replace professional judgment
* Replace stakeholder participation
* Replace legal advice
* Replace safety engineering
* Replace environmental review
* Guarantee regulatory compliance
* Prove that a safeguard will work
* Treat documentation as resolution
* Convert consultation into consent
* Hide dissent after approval

It is a decision instrument, not an automated authority.

---

## Recommended Review Practice

A strong STEWARD review should include:

* The engineers responsible for the system
* Safety and reliability specialists
* Maintainers and operators
* People exposed to the consequences
* Stakeholder representatives
* Privacy, security, environmental, or accessibility expertise where relevant
* Someone independent from delivery pressure
* A clearly identified decision authority
* A documented path for escalation and refusal

For consequential decisions, the person facilitating the ethical review should not be the only person responsible for delivery approval.

---

## Privacy and Security Notes

STEWARD stores potentially sensitive decision information locally.

Users should consider:

* Whether names should be entered
* Whether confidential or regulated information belongs in the workspace
* Whether exported files require encryption
* Where backups are stored
* Who is authorized to receive reports
* Whether external reports should use redaction
* Whether browser extensions or shared devices create additional risk

Use the redacted external brief for public or broadly distributed reporting.

---

## Browser Support

STEWARD is designed for current versions of:

* Google Chrome
* Microsoft Edge
* Mozilla Firefox
* Apple Safari

A desktop browser is recommended for complex reviews. Mobile layouts are intended for viewing, field notes, and limited editing.

---

## Project Structure

STEWARD is currently distributed as one self contained file:

```text
steward-v2.1.html
```

The file contains:

* HTML
* CSS
* JavaScript
* Templates
* Data migration logic
* Report generation
* Demonstration data

No build system or external dependency is required.

---

## Version History

### 2.1

* Multi-pattern ethical review
* Expanded contextual pattern library
* Custom pattern builder
* Structured prompt review
* Ethical failure mode scanner
* Human dispositions for scanner signals
* Dashboard and report integration

### 2.0

* Integrated workbench navigation
* Decision dashboard
* Named readiness gates
* Explainable ethical tensions
* Relationship inspector
* Global archive
* Pattern templates
* Accessibility and recovery improvements
* Data migration and diagnostics

### 1.9

* Ethics brief builder
* Multiple report profiles
* Redacted external reports
* Expanded export formats

### 1.8

* Decision baselines
* Decision lineage
* Snapshot comparison
* Restore workflow

### 1.7

* Monitoring plans
* Indicators
* Incidents and complaints
* Ethical change control
* Decision reopening

### 1.6

* Deliberation sessions
* Objections and minority opinions
* Signoffs and checkpoints
* Conditional approval

### 1.5

* Structured alternatives
* Safeguard hierarchy
* Safeguard verification

### 1.4

* Professional duty frameworks
* Competing obligation records
* Duty conflict view

### 1.3

* Stakeholder engagement
* Commitments ledger
* Representation analysis
* Additional stakeholder maps

### 1.2

* Evidence and claim traceability
* Contradictory evidence
* Evidence gaps and assumption inventories

### 1.1

* Guided workflow
* Ethical tensions panel
* Archive and undo
* Improved onboarding

### 1.0

* Decision framing
* Stakeholders
* Impacts
* Professional obligations
* Alternatives
* Deliberation
* Stakeholder map
* Ethics brief
* Local autosave
* JSON and Markdown export

---

## Future Development

Potential future releases may include:

* Cross instrument exchange with Trace, Handshake, Makefile, Reliquary, and Decision Ledger
* Portable ethical pattern packages
* Decision portfolio analysis
* Shared review packages
* Additional public sector and engineering discipline templates
* More advanced report layouts
* Optional encrypted workspace exports
* Controlled collaborative review workflows

Future additions should preserve STEWARD’s central design rule:

**Do not turn ethical complexity into a single score.**

---

## License

No license has been assigned in this release.

Add an appropriate license before redistributing, modifying, or incorporating STEWARD into another product.

---

## Project Philosophy

Engineering decisions shape more than technical performance.

They distribute safety, privacy, access, cost, power, maintenance work, environmental burden, and future constraints. Those effects are rarely experienced equally.

STEWARD exists to make that distribution visible.

It does not promise clean answers. It helps teams build decisions that are more explicit, more reviewable, more accountable, and easier to reconsider when reality changes.
