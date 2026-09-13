# Autonomous Impact Threshold

## Defining When an AI Tool Becomes a High-Impact Autonomous System Requiring Stronger Governance

### Abstract

AI governance requires a practical boundary.

Not every AI system should be regulated as a high-risk autonomous system.

A local coding assistant, an offline research model, a document summarizer, and an autonomous agent controlling production infrastructure should not face the same governance requirements.

At the same time, waiting until a system qualifies as Artificial General Intelligence is too late and conceptually unnecessary.

The relevant transition occurs when an AI system gains enough autonomy, access, persistence, scale, and operational authority to produce significant external consequences without continuous case-by-case human authorization.

This paper defines that transition as the **Autonomous Impact Threshold (AIT)**.

The central proposition is:

> **An AI system crosses the Autonomous Impact Threshold when its effective capacity for consequential external action becomes large enough that ordinary user-level controls are no longer sufficient.**

AIT is not defined by model size, benchmark performance, company identity, or whether the system is labeled AGI.

It is determined primarily by the system's **action surface**.

The framework evaluates seven major dimensions:

1. autonomy,
2. permission and authority,
3. external action capability,
4. scale and parallelism,
5. persistence and looping,
6. consequence and reversibility,
7. verification and human control.

The objective is proportional governance:

> **Low-impact AI should remain easy to use. High-impact autonomous action should become progressively more controlled as operational consequence increases.**

---

# 1. Why AI Governance Needs a Threshold

Any governance system eventually encounters a practical question:

> When do stronger controls begin?

If the threshold is too low, ordinary AI use becomes unnecessarily restricted.

If the threshold is too high, dangerous autonomous systems may operate freely until after serious harm becomes possible.

The problem is therefore not merely identifying dangerous AI.

It is defining a transition from:

```text
Ordinary AI Tool
        ↓
Agentic AI
        ↓
Autonomous Operational System
        ↓
High-Impact Autonomous System
```

The **Autonomous Impact Threshold** identifies the point at which stronger governance becomes justified.

---

# 2. The Wrong Threshold: AGI

A tempting approach is:

```text
If AI < AGI
    → ordinary regulation

If AI ≥ AGI
    → strong regulation
```

This is structurally weak.

First, there is no universally accepted operational definition of AGI.

Second, model intelligence does not directly determine external consequence.

Third, dangerous action may occur well before AGI.

Fourth, highly capable systems may remain low-risk when isolated from consequential authority.

Therefore:

> **AGI is neither necessary nor sufficient as the primary operational threshold for AI action governance.**

---

# 3. Model Capability Is Not Action Capability

Consider two systems.

### System A

A highly capable frontier model operates:

```text
Offline
+
Read-Only
+
No External Tools
+
No Credentials
+
No Persistent Execution
```

### System B

A weaker model operates with:

```text
Network Access
+
Shell
+
Cloud Credentials
+
Persistent Looping
+
Thousands of Parallel Agents
+
Production Write Access
```

System B may present substantially greater immediate operational risk.

Therefore governance should distinguish:

```text
Model Capability
```

from:

```text
Action Capability
```

and especially:

```text
Consequential Action Capability
```

---

# 4. The Autonomous Impact Threshold

The Autonomous Impact Threshold can be defined as follows:

> **An AI system crosses the Autonomous Impact Threshold when the combination of autonomy, authority, access, scale, persistence, and consequence enables it to produce significant external effects without continuous case-by-case human authorization, such that ordinary user-level safeguards are no longer sufficient.**

The threshold therefore concerns the whole deployed system.

Not merely the model.

---

# 5. The AIT Principle

A compact formulation is:

```text
Autonomy
×
Authority
×
Access
×
Scale
×
Persistence
×
Consequence
────────────────
Verification
+
Human Control
```

This is a conceptual model rather than a literal mathematical formula.

The numerator represents **impact amplification**.

The denominator represents **control capacity**.

Risk increases when machine action capacity grows faster than governance capacity.

---

# 6. The Seven AIT Dimensions

A practical AIT assessment should examine at least seven dimensions.

```text
A — Autonomy
P — Permission / Authority
E — External Action
S — Scale / Parallelism
L — Looping / Persistence
C — Consequence / Reversibility
V — Verification / Human Control
```

Together they describe the system's operational action surface.

---

# 7. Dimension A — Autonomy

Autonomy measures how independently the system selects and executes actions.

A useful progression is:

```text
A0 — Advisory Only
      ↓
A1 — Suggests Actions
      ↓
A2 — Executes Explicit Human Commands
      ↓
A3 — Chooses Among Authorized Actions
      ↓
A4 — Plans and Executes Multi-Step Tasks
      ↓
A5 — Persistent Goal-Directed Autonomy
```

The difference between A1 and A5 is profound.

A chatbot suggesting a shell command is not equivalent to an agent independently executing thousands of shell commands overnight.

---

# 8. Dimension P — Permission and Authority

Permission measures what the system is authorized to control.

Possible levels include:

```text
P0 — No External Permission

P1 — Read-Only Access

P2 — Limited Write Access

P3 — Production / Operational Access

P4 — Privileged Administrative Access

P5 — Critical or Irreversible Authority
```

Permission is one of the strongest risk multipliers.

A highly intelligent system without authority may remain contained.

A moderately intelligent system with root-level authority may not.

---

# 9. Dimension E — External Action Capability

External action measures whether the AI can affect systems beyond its reasoning environment.

Examples include:

```text
File Modification
Code Commit
API Invocation
Network Connection
Email / Messaging
Financial Transaction
Cloud Deployment
Database Modification
Hardware Control
Laboratory Equipment
```

A critical distinction is:

```text
Can Recommend
```

versus:

```text
Can Execute
```

Governance should become stronger when AI moves from recommendation into direct execution.

---

# 10. Dimension S — Scale and Parallelism

Scale measures how much action the system can perform.

Relevant variables include:

```text
Requests per minute
Targets per hour
Agents running simultaneously
Compute budget
API volume
Transaction volume
Generated artifacts
External interactions
```

One action and one million actions are not equivalent.

Therefore:

> **Scale is itself a capability.**

---

# 11. Dimension L — Looping and Persistence

Persistence measures how long and how repeatedly the system can operate without renewed human authorization.

A useful progression is:

```text
L0 — One-Shot Response

L1 — Short Interactive Session

L2 — Bounded Multi-Step Task

L3 — Extended Autonomous Loop

L4 — Persistent Background Agent

L5 — Self-Continuing / Self-Delegating Runtime
```

Persistence converts isolated capability into cumulative capability.

---

# 12. Dimension C — Consequence and Reversibility

Not all actions have equal consequences.

A useful distinction is:

```text
C0 — Informational

C1 — Easily Reversible

C2 — Limited Operational Consequence

C3 — Significant Organizational Consequence

C4 — Major External Consequence

C5 — Critical / Potentially Catastrophic Consequence
```

Reversibility is particularly important.

Deleting a temporary file is not equivalent to:

* transferring irreversible funds,
* disabling critical infrastructure,
* publishing sensitive information,
* executing destructive production changes.

---

# 13. Dimension V — Verification and Human Control

Verification reduces effective autonomous risk.

Relevant controls include:

```text
Independent Tests
Policy Engine
Sandbox
Human Approval
Counter-Evidence Search
Rate Limit
Audit
Kill Switch
Rollback
```

A system with strong controls may safely perform operations that would be unacceptable in an uncontrolled system.

Thus AIT should measure not merely raw capability, but:

> **Capability relative to control.**

---

# 14. AIT Is Not a Single Benchmark Score

The framework should not become:

```text
AIT Score = 73
Therefore Dangerous
```

with false mathematical precision.

Different combinations produce qualitatively different risks.

For example:

```text
High Autonomy
+
No External Access
```

may remain manageable.

But:

```text
Moderate Autonomy
+
High Permission
+
Massive Scale
```

may require strong governance.

AIT should therefore combine scoring with structural rules.

---

# 15. Threshold Triggers

Certain capabilities should trigger stronger review even if the aggregate score appears moderate.

Possible triggers include:

```text
Privileged Production Access

Critical Infrastructure Control

Large Financial Authority

Mass Autonomous External Interaction

Persistent Unauthorized-Surface Exploration

Self-Delegating Agent Swarms

Ability to Modify Its Own Permission Boundary

Ability to Disable Audit or Safety Controls
```

These are **structural triggers**.

---

# 16. The Four AIT Governance Zones

A practical implementation can divide systems into four zones.

```text
AIT-0 — Tool

AIT-1 — Bounded Agent

AIT-2 — Consequential Autonomous System

AIT-3 — High-Impact Autonomous System
```

The objective is progressive governance.

---

# 17. AIT-0 — Ordinary AI Tool

Typical characteristics:

```text
Human Initiates Each Task
Read-Only or Local Context
No Persistent Autonomy
No High-Impact External Action
Low Scale
Easy Reversibility
```

Examples include:

* document summarization,
* offline analysis,
* ordinary conversational assistance,
* local code explanation,
* drafting.

Governance should remain lightweight.

---

# 18. AIT-1 — Bounded Agent

Typical characteristics:

```text
Limited Multi-Step Autonomy
Bounded Tool Access
Defined Task
Limited Duration
Limited External Scope
Human Recoverability
```

Examples may include:

* coding agent inside a sandbox,
* research agent browsing approved sources,
* internal workflow automation,
* test-generation agent.

Controls may include:

```text
Agent Identity
Basic Audit
Permission Scope
Resource Limit
Task Boundary
```

---

# 19. AIT-2 — Consequential Autonomous System

Typical characteristics:

```text
Persistent or Extended Autonomy
External Write Capability
Production Interaction
Meaningful Scale
Potential Organizational Consequence
```

Examples may include:

* autonomous production deployment,
* customer-facing operational agents,
* financial workflow agents,
* infrastructure management agents.

Stronger requirements should appear:

```text
Explicit Responsible Principal
Independent Verification
Policy Enforcement
Detailed Audit
Rate Limits
Escalation
Kill Mechanism
```

---

# 20. AIT-3 — High-Impact Autonomous System

Typical characteristics include combinations of:

```text
Persistent Autonomy
+
Privileged Authority
+
Large Scale
+
External Targets
+
High-Consequence Domain
```

These systems may require:

```text
Strong Identity
Multi-Party Authorization
Least Privilege
Independent Evaluators
Continuous Monitoring
Counter-Evidence
Tamper-Resistant Audit
Strict Scale Limits
Mandatory Escalation
Emergency Shutdown
Incident Reporting
```

The defining feature is not model intelligence.

It is high-impact autonomous authority.

---

# 21. The Governance Ladder

The framework therefore creates:

```text
AIT-0
Ordinary Tool
   │
   ▼
AIT-1
Bounded Agent
   │
   ▼
AIT-2
Consequential Autonomous System
   │
   ▼
AIT-3
High-Impact Autonomous System
```

Governance intensity rises with operational consequence.

---

# 22. AIT Should Be Deployment-Specific

The same model can belong to different AIT classes.

For example:

```text
Model X
  │
  ├── Offline Chat
  │      → AIT-0
  │
  ├── Sandbox Coding
  │      → AIT-1
  │
  ├── Production Deployment Agent
  │      → AIT-2
  │
  └── Critical Infrastructure Controller
         → AIT-3
```

This is a crucial principle.

> **Risk belongs to the model-runtime-permission-action configuration, not merely to the model.**

---

# 23. AIT Should Be Dynamic

A system's AIT classification can change.

Suppose an agent begins as:

```text
Read-Only
+
Sandboxed
+
Human Supervised
```

Later it receives:

```text
Production Credentials
+
Persistent Runtime
+
Parallel Workers
```

The system has changed risk class even though the model weights remain identical.

Therefore AIT should be continuously reassessed when:

* permissions change,
* tools change,
* scale changes,
* deployment environment changes,
* autonomy changes,
* consequences change.

---

# 24. Permission Escalation Is an AIT Event

A particularly important trigger is permission escalation.

For example:

```text
Read Repository
        ↓
Write Repository
        ↓
Merge Code
        ↓
Deploy Production
        ↓
Modify Infrastructure
```

Each transition expands the action surface.

AIT assessment should therefore be integrated with permission management.

---

# 25. Scale Escalation Is Also an AIT Event

Likewise:

```text
1 Agent
        ↓
10 Agents
        ↓
1,000 Agents
        ↓
100,000 Parallel Actions
```

can change the risk class without changing the model.

Scale escalation should trigger reassessment.

---

# 26. Loop Escalation Is an AIT Event

A one-shot system can become a persistent autonomous system through a small architectural change.

For example:

```text
Run Once
```

becomes:

```text
while objective_not_met:
    observe()
    plan()
    act()
    evaluate()
```

That change may be more important for risk than a modest model upgrade.

---

# 27. Self-Delegation Is a Special Trigger

An agent capable of creating or directing sub-agents can expand its effective scale.

```text
Agent A
   ↓
creates
   ├── Agent B
   ├── Agent C
   ├── Agent D
   └── ...
```

Self-delegation therefore requires explicit governance.

The parent should not be able to create unlimited new authority merely by creating new agents.

---

# 28. Authority Must Not Grow Automatically With Intelligence

Suppose a model upgrade improves reasoning by 30%.

That should not automatically imply:

```text
30% More Permission
```

Capability evaluation and authorization should remain separate processes.

This preserves the principle:

> **Intelligence does not imply authority.**

---

# 29. The AI Coding Example

Consider four coding configurations.

### Configuration A

```text
AI suggests code
Human copies it
```

Likely:

> AIT-0

### Configuration B

```text
AI edits sandbox repository
Runs tests
Human approves merge
```

Likely:

> AIT-1

### Configuration C

```text
AI edits repository
Opens PR
Runs CI
Merges approved classes of changes
```

Potentially:

> AIT-2

### Configuration D

```text
AI modifies production
Changes infrastructure
Creates credentials
Runs persistently
```

Potentially:

> AIT-3

The model may be identical in all four cases.

The governance requirements should not be.

---

# 30. Delta Intelligence Can Control AIT Escalation

AI coding also demonstrates why structural delta matters.

A change may appear textually small while causing:

```text
Large CallingGraph Delta
Large Permission Delta
Large Behavior Delta
Large Blast Radius
```

Therefore AIT should consider the consequence of proposed changes, not merely the nominal task.

A system can dynamically escalate a particular action for stronger review.

---

# 31. Action-Level AIT

AIT need not classify only whole systems.

Individual actions can also receive an impact level.

For example:

```text
Agent = AIT-2

Read log
    → Action Level 0

Modify test
    → Action Level 1

Deploy service
    → Action Level 2

Rotate production root credentials
    → Action Level 3
```

This enables fine-grained governance.

---

# 32. Dynamic Policy Gating

Action-level classification enables:

```text
Agent proposes action
        ↓
Determine Action Impact
        ↓
Low
 → Execute

Medium
 → Verify

High
 → Human / Multi-Party Approval

Critical
 → Restricted or Prohibited
```

This is more flexible than globally disabling autonomous agents.

---

# 33. AIT and Scale Looping

Scale Looping makes AIT especially important.

A low-impact action repeated millions of times may become high-impact.

Therefore:

```text
Impact Per Action
×
Number of Actions
×
Adaptivity
```

must be considered.

Repeated action can cross the threshold even when individual actions do not.

---

# 34. Aggregate Impact

This produces the concept of **Aggregate Autonomous Impact**.

For example:

```text
One personalized message
→ low impact

Millions of adaptive personalized messages
→ potentially high aggregate impact
```

Likewise:

```text
One network request
→ ordinary

Millions of adaptive probes
→ potentially consequential
```

Scale can change the governance class.

---

# 35. AIT and the Evaluator

A system with a strong independent evaluator can safely operate with greater autonomy than one relying on self-evaluation.

Compare:

```text
Generate
↓
Self-Approve
↓
Execute
```

with:

```text
Generate
↓
Independent Test
↓
Counter-Evidence
↓
Policy
↓
Execute
```

Evaluator independence should therefore influence threshold assessment.

---

# 36. AIT and Reversibility

Reversibility can serve as an important control variable.

A system may be allowed greater autonomy when actions are:

```text
Sandboxed
Reversible
Versioned
Rollback-Capable
Low Blast Radius
```

Stronger authorization is justified when actions are:

```text
Irreversible
Externally Propagating
Safety-Critical
High Blast Radius
```

This creates a practical engineering path for increasing useful autonomy safely.

---

# 37. Sandboxing Can Lower Effective AIT

A capable agent operating inside a strong sandbox may have low external impact.

Thus containment can reduce effective risk without reducing intelligence.

This illustrates an important principle:

> **Governance can reduce action power without reducing reasoning power.**

That is preferable to suppressing useful intelligence.

---

# 38. AIT and Human Oversight

Human involvement should also be evaluated structurally.

Nominal oversight:

```text
AI produces 50,000 decisions
        ↓
Human clicks Approve All
```

provides little meaningful reduction in autonomy.

Therefore AIT should ask:

> Does the human have sufficient information, time, authority, and realistic ability to reject the action?

Only meaningful intervention counts as strong human control.

---

# 39. Human-at-the-Right-Decision-Point

For scalable systems:

```text
Routine Low-Risk Action
        ↓
Machine

Ambiguous Action
        ↓
Verification

High-Risk Delta
        ↓
Human

Critical Action
        ↓
Multi-Party Authorization
```

This provides more meaningful oversight than universal manual approval.

---

# 40. AIT and Counter-Evidence

As impact rises, counter-evidence requirements should also rise.

For low-risk actions:

```text
Positive Evidence
→ sufficient
```

For high-impact actions:

```text
Evidence For
+
Evidence Against
+
Alternative Explanations
+
Policy Check
→ Decision
```

This reduces the chance that a powerful search loop simply finds justification for its preferred action.

---

# 41. AIT and Accountability

Crossing AIT should automatically strengthen accountability requirements.

For example:

```text
AIT-0
→ ordinary user responsibility

AIT-1
→ identified agent + owner

AIT-2
→ responsible principal + detailed audit

AIT-3
→ institutional accountability + strong authorization
```

Thus AIT connects directly to the **AI Action Accountability Stack**.

---

# 42. AIT and Platform Duty of Care

Platforms should not treat every workload identically.

A platform may classify:

```text
Low-AIT Workload
→ ordinary service

Elevated-AIT Workload
→ stronger monitoring

High-AIT Workload
→ identity + policy + scale controls

Critical-AIT Workload
→ restricted execution environment
```

This provides a practical basis for proportional platform responsibility.

---

# 43. AIT and Regulatory Neutrality

AIT should apply independently of company identity.

The rule should not be:

```text
Big AI Company
→ regulated

Small AI Company
→ unregulated
```

Nor:

```text
Closed Model
→ dangerous

Open Model
→ safe
```

Instead:

```text
Consequential Autonomous Action
→ stronger governance
```

This reduces opportunities for regulatory capture.

---

# 44. Open Models and AIT

An open-weight model stored on a researcher's computer may be:

```text
AIT-0
```

The same model integrated with:

```text
Persistent Agent
+
Cloud Credentials
+
External Targets
+
Massive Parallelism
```

may become:

```text
AIT-2 or AIT-3
```

The model did not change.

The action architecture did.

---

# 45. Frontier Models and AIT

Likewise, a frontier model used only for:

```text
Offline Analysis
Read-Only Research
Sandbox Simulation
```

may remain below the high-impact threshold.

This avoids the mistake of treating intelligence itself as the regulated substance.

---

# 46. The Regulatory Target Should Be the Deployment Configuration

The relevant governance object is therefore:

```text
Model
+
Agent Runtime
+
Tools
+
Permissions
+
Scale
+
Persistence
+
Target Environment
+
Control Structure
```

This complete object can be called the:

> **AI Action Configuration**

AIT applies primarily to this configuration.

---

# 47. AIT as a Runtime Property

An important consequence follows:

> **AIT is partly a runtime property.**

It cannot always be determined once during model release.

Runtime telemetry may reveal:

* increasing action rate,
* increasing delegation,
* permission expansion,
* unusual targets,
* persistent looping,
* evaluator degradation.

Therefore high-impact systems require continuous AIT monitoring.

---

# 48. Dynamic AIT Escalation

A runtime control plane could implement:

```text
Current AIT Level
       ↓
Observe Runtime
       ↓
Permission Change?
Scale Increase?
New Tool?
New Target?
Longer Loop?
Higher Consequence?
       ↓
Recalculate
       ↓
Maintain / Escalate / Restrict
```

This makes governance adaptive.

---

# 49. AIT Should Also De-Escalate

Governance should not only become stricter.

If:

```text
Permissions Reduced
Scale Reduced
Sandbox Added
External Access Removed
Human Gate Added
```

then the effective AIT may decrease.

This provides incentives for safer system design.

---

# 50. The AIT Control Plane

A practical implementation may look like:

```text
┌───────────────────────────────────────┐
│        RESPONSIBLE PRINCIPAL          │
├───────────────────────────────────────┤
│         AIT CLASSIFICATION            │
├───────────────────────────────────────┤
│       POLICY / AUTHORIZATION           │
├───────────────────────────────────────┤
│        PERMISSION BOUNDARY             │
├───────────────────────────────────────┤
│      SCALE / LOOP / RATE BOUND         │
├───────────────────────────────────────┤
│      STRUCTURAL DELTA ANALYSIS         │
├───────────────────────────────────────┤
│      VERIFICATION / COUNTER-EVIDENCE   │
├───────────────────────────────────────┤
│          HUMAN ESCALATION              │
├───────────────────────────────────────┤
│       STOP / REVOKE / ROLLBACK         │
├───────────────────────────────────────┤
│             AUDIT TRACE                │
└───────────────────────────────────────┘
```

AIT therefore becomes part of the AI control plane.

---

# 51. What Should Happen When AIT Is Crossed?

Crossing the threshold should not automatically mean:

> Ban the system.

Instead it should mean:

> **Upgrade the governance regime.**

Possible requirements include:

```text
Named Responsible Principal
Explicit Authorization
Stronger Identity
Least Privilege
Scale Limits
Independent Verification
Counter-Evidence
Detailed Audit
Human Escalation
Incident Response
Kill Mechanism
```

AIT is therefore a governance trigger, not necessarily a prohibition trigger.

---

# 52. AIT and Innovation

This distinction protects innovation.

Ordinary AI remains lightweight.

High-impact AI remains possible.

But stronger authority requires stronger responsibility.

The progression becomes:

```text
More Autonomous Power
        ↓
More Control Requirements
```

rather than:

```text
More Intelligence
        ↓
More Prohibition
```

---

# 53. AIT and the Prisoner's Dilemma

AIT may also help address competitive pressure.

Without shared rules:

```text
Company A adds more autonomy
Company B responds
Company C responds
        ↓
Competitive Escalation
```

With action-based thresholds:

```text
Cross AIT
        ↓
Shared Governance Requirements
```

the external cost of unsafe autonomy becomes harder to ignore.

This can partially reduce incentives for uncontrolled escalation.

---

# 54. International Advantages of AIT

Countries may disagree about:

* AGI definitions,
* frontier-model thresholds,
* model openness,
* acceptable research trajectories.

They may find greater agreement around actions.

For example:

```text
Unauthorized autonomous cyber attack
```

is easier to identify than:

```text
System has achieved AGI
```

AIT therefore provides a more practical foundation for international coordination.

---

# 55. AIT Does Not Eliminate Long-Term AGI Governance

AIT should not be interpreted as claiming that future AGI or superintelligence poses no additional governance problems.

Instead:

```text
Pre-AGI Action Governance
```

and:

```text
Future AGI / ASI Governance
```

are complementary.

AIT addresses what can be governed now without waiting for the second problem to be solved.

---

# 56. AIT and the Pre-AGI Governance Framework

The relationship among the major concepts is:

```text
Scale-Looping Power
        ↓
Effective System Power
        ↓
Autonomous Impact
        ↓
AIT Crossing
        ↓
AI Action Accountability Stack
        ↓
Stronger Governance
```

This creates a complete logical chain.

---

# 57. A Practical AIT Assessment

Before deployment, ask:

### Autonomy

Can the system initiate or choose actions without case-by-case approval?

### Authority

What permissions does it possess?

### External Action

Can it modify real systems?

### Scale

How many actions, targets, or agents can it operate?

### Persistence

How long can it continue without renewed authorization?

### Consequence

What is the maximum credible blast radius?

### Verification

What independent controls can stop incorrect action?

If several dimensions are high, stronger governance is justified.

---

# 58. The Maximum Credible Action Test

A useful shortcut is:

> **What is the most consequential action this system could plausibly perform using its currently available permissions and resources?**

This is often more informative than:

> What is the system intended to do?

Security engineering should consider capability, not merely intention.

AIT should do the same.

---

# 59. The Failure-at-Scale Test

A second useful question is:

> **What happens if this system makes the same class of mistake at maximum permitted scale?**

A mistake harmless at one execution may become severe at one million executions.

This test captures Scale-Looping risk.

---

# 60. The Compromise Test

A third question is:

> **What could an adversary do if they gained control of this agent without changing its existing permissions?**

If the answer includes catastrophic actions, the agent already possesses a dangerous authority surface.

---

# 61. The Human-Absent Test

Ask:

> **What can this system accomplish if the responsible human disappears for 24 hours?**

This reveals actual autonomy more clearly than marketing terminology.

A system that stops immediately is different from one that continues:

```text
Observe
Plan
Delegate
Execute
Evaluate
Repeat
```

for an entire day.

---

# 62. The Evaluator-Failure Test

Ask:

> **What happens if the evaluator becomes systematically wrong?**

If incorrect evaluation can directly produce irreversible external action, stronger independent verification is needed.

---

# 63. The Permission-Failure Test

Ask:

> **Can the agent expand, bypass, delegate, or rewrite its own authority boundary?**

If yes, this should be treated as a major AIT trigger.

The intelligence plane should not control its own permission plane.

---

# 64. Five Operational Rules

The AIT framework can be reduced to five operational rules.

### Rule 1

> **No high-impact autonomy without an identifiable responsible principal.**

### Rule 2

> **No high-impact action without bounded permission and scale.**

### Rule 3

> **No irreversible action based solely on self-evaluation.**

### Rule 4

> **No persistent critical loop without an independent stop mechanism.**

### Rule 5

> **No meaningful authority escalation without AIT reassessment.**

These rules are understandable by engineers, regulators, executives, and users.

---

# 65. From Intelligence Threshold to Impact Threshold

The conceptual shift can be summarized as:

```text
Old Question

How intelligent is the model?
        ↓
Is it AGI?
        ↓
Should we regulate it?
```

versus:

```text
AIT Question

What can the system do?
        ↓
With what authority?
        ↓
At what scale?
        ↓
For how long?
        ↓
With what consequence?
        ↓
Under what controls?
```

The second sequence is far more operational.

---

# 66. A Minimal Regulatory Principle

If only one rule could be adopted, it should be:

> **Governance requirements should increase with the maximum credible autonomous impact of the deployed AI system.**

This avoids dependence on speculative intelligence labels.

It also preserves low-risk innovation.

---

# 67. The Deeper Principle

AIT rests on a broader idea:

> **Society does not need to restrict intelligence merely because intelligence is powerful. Society must govern the authority through which intelligence becomes consequential action.**

This principle already exists throughout human institutions.

AI makes it newly urgent.

---

# 68. Conclusion

The transition from ordinary AI tool to high-impact autonomous system should not be defined by model prestige, parameter count, benchmark score, or speculative AGI status.

It should be defined by **autonomous impact**.

The critical variables are:

```text
Autonomy
Authority
External Access
Scale
Persistence
Consequence
Verification
```

Together they determine whether an AI system remains an ordinary tool or becomes an operational actor requiring stronger governance.

The Autonomous Impact Threshold therefore establishes a practical boundary:

> **An AI system crosses AIT when its capacity for consequential autonomous external action exceeds what ordinary user-level safeguards can responsibly govern.**

Crossing AIT should not automatically prohibit deployment.

It should trigger stronger controls:

```text
Identity
Authorization
Least Privilege
Scale Limits
Independent Verification
Counter-Evidence
Audit
Human Escalation
Interruptibility
Accountability
```

This produces a proportional governance principle:

> **More autonomous impact requires more structural control.**

Most importantly, AIT allows society to address serious AI risk without first resolving the AGI debate.

A system does not need to be generally intelligent to become consequential.

It only needs enough:

```text
Capability
×
Autonomy
×
Scale
×
Tools
×
Authority
```

to affect the world faster than existing institutions can reliably control it.

That is the boundary that matters.

That is the **Autonomous Impact Threshold**.
