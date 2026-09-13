# The Governance Target Selection Problem

## Choosing the Correct Object of AI Regulation Before Building the Regulatory System

### Abstract

Before regulating artificial intelligence, policymakers must answer a more fundamental question:

> **What exactly is the object being regulated?**

Possible answers include:

* the model,
* training compute,
* model capability,
* the agent,
* the deployment architecture,
* tools and access,
* autonomous authority,
* external action,
* or real-world consequence.

These are not equivalent regulatory targets.

Selecting the wrong target can produce a dangerous combination of outcomes:

* legitimate AI research may be unnecessarily constrained,
* open and smaller competitors may face disproportionate compliance burdens,
* regulatory concentration may favor incumbents,
* while genuinely dangerous autonomous deployments remain insufficiently controlled.

This paper defines this challenge as the **Governance Target Selection Problem**.

It argues that AI governance should distinguish three major layers:

```text
Model Capability
        ↓
Agentic Action System
        ↓
Consequential External Action
```

Model capability remains relevant for evaluation and risk forecasting.

Agentic deployment determines how intelligence becomes operational.

Consequential action determines when strong governance is justified.

The central framework is:

> **Model evaluation informs governance.**

> **Action capability triggers governance.**

> **Consequence determines governance intensity.**

The goal is neither unrestricted AI nor indiscriminate regulation.

It is to govern the right object.

---

# 1. Governance Begins Before Regulation

Public debate often begins with questions such as:

> How should AI be regulated?

But this question comes too late.

Before designing rules, regulators must determine:

> **What should those rules regulate?**

This is the **Governance Target Selection Problem**.

A sophisticated regulatory system built around the wrong target can be less effective than a simple system built around the correct one.

---

# 2. The Target Selection Problem

AI exists simultaneously at several layers.

```text
Research
   ↓
Training
   ↓
Model
   ↓
Agent Runtime
   ↓
Tools
   ↓
Permissions
   ↓
Looping / Scale
   ↓
External Action
   ↓
Real-World Consequence
```

A regulator can intervene at almost any point.

But interventions at different points have radically different effects.

For example:

```text
Regulate Training
```

is not equivalent to:

```text
Regulate Deployment
```

and neither is equivalent to:

```text
Regulate Consequential Action
```

The first task of governance is therefore architectural:

> **Locate the point in the system where regulation most directly corresponds to the risk being addressed.**

---

# 3. The Simplest Regulatory Shortcut

The easiest regulatory approach is often:

```text
More Powerful Model
        ↓
More Dangerous AI
        ↓
More Regulation
```

This is understandable.

Model capability is measurable.

Model developers are identifiable.

Training facilities may be identifiable.

Compute can sometimes be estimated.

Benchmarks can be constructed.

The resulting regulatory object is administratively convenient.

But administrative convenience does not guarantee correct risk localization.

---

# 4. Powerful Model Does Not Equal Dangerous Deployment

Consider:

### System A

```text
Very Powerful Model
+
Offline
+
Read-Only
+
No Credentials
+
No Persistent Runtime
+
No External Execution
```

and:

### System B

```text
Moderately Capable Model
+
Persistent Agent
+
Shell Access
+
Production Credentials
+
External Network
+
Massive Parallelism
+
Autonomous Retry Loop
```

Which system presents the greater immediate operational risk?

The answer may easily be System B.

Therefore:

> **Model capability and operational consequence are correlated only indirectly.**

The deployment architecture matters.

---

# 5. The Opposite Error

The reverse mistake is also possible:

```text
Not AGI
    ↓
Not Dangerous
    ↓
No Strong Governance Needed
```

This is equally weak.

A bounded model can produce substantial real-world effects when combined with:

```text
Agents
+
Tools
+
Scale
+
Looping
+
Persistence
+
Permissions
```

Therefore governance should avoid both errors:

> **Powerful model = automatically dangerous**

and:

> **Non-AGI model = automatically safe**

---

# 6. Three Primary Governance Objects

A practical framework should distinguish at least three major objects.

## Object A — Model Capability

What can the model reason about, generate, discover, or solve?

## Object B — Agentic Action System

How is the model embedded in a runtime capable of planning, looping, using tools, remembering, delegating, and executing?

## Object C — Consequential External Action

What can the complete system actually do to the external world, at what scale, under what authority, and with what consequences?

These objects require different governance mechanisms.

---

# 7. Object A — Model Capability

Model capability matters.

It can indicate:

* future deployment potential,
* cyber capability,
* scientific capability,
* autonomy potential,
* misuse potential,
* emerging operational risks.

Capability evaluation is therefore useful.

But capability evaluation should primarily answer:

> **What risks should we prepare for?**

It should not automatically answer:

> **What actions should be prohibited?**

That distinction is essential.

---

# 8. Model Evaluation as Early Warning

Model evaluation can function as an early-warning system.

For example:

```text
Capability Increase
        ↓
Potential Action Surface Expands
        ↓
Governance Preparation
```

This is valuable.

It allows platforms and governments to anticipate emerging risks.

Therefore:

> **Model evaluation informs governance.**

But information is not the same as regulatory trigger.

---

# 9. Why Model-Level Regulation Is Attractive

Model-level regulation offers several apparent advantages.

Models can have:

* identifiable developers,
* release dates,
* benchmark scores,
* training runs,
* documented architectures,
* measurable compute requirements.

This makes model regulation administratively attractive.

But it also creates several risks.

---

# 10. Risk 1 — Innovation Suppression

If regulation follows model intelligence too directly:

```text
Capability ↑
    ↓
Compliance Cost ↑
    ↓
Research Friction ↑
```

then society may unintentionally discourage useful advances in:

* science,
* medicine,
* engineering,
* education,
* software,
* accessibility,
* industrial optimization.

Intelligence itself is not necessarily the harmful act.

---

# 11. Risk 2 — Regulatory Concentration

Heavy fixed compliance costs can produce:

```text
Model Regulation
        ↓
Large Compliance Infrastructure
        ↓
Small Developers Exit
        ↓
Fewer Competitors
        ↓
Market Concentration
```

Large incumbents may be able to absorb these costs.

Small companies, academic groups, and open-source communities may not.

Safety regulation can therefore unintentionally become an industrial barrier.

---

# 12. Risk 3 — False Safety

Perhaps the most dangerous failure is:

```text
Model below regulated threshold
        ↓
Assumed low risk
```

while the model is deployed as:

```text
Persistent Agent
+
Powerful Tools
+
Broad Permissions
+
Massive Scale
```

The regulatory framework may then constrain research while missing dangerous action.

This produces:

> **Over-regulation of intelligence and under-regulation of authority.**

---

# 13. Object B — The Agentic Action System

A model becomes operationally different when embedded inside an agent runtime.

The runtime may add:

```text
Planning
Memory
Looping
Tool Use
Delegation
External Access
Persistence
Parallelism
```

This transforms:

```text
Model
```

into:

```text
Actor-Like System
```

without requiring AGI.

---

# 14. Agentic Architecture Is a Major Risk Transition

Consider:

```text
Model answers question
```

versus:

```text
Model receives objective
        ↓
Plans
        ↓
Uses tools
        ↓
Executes
        ↓
Observes
        ↓
Modifies plan
        ↓
Retries
        ↓
Continues autonomously
```

The second architecture creates a fundamentally different governance problem.

Therefore:

> **Agentic deployment deserves independent regulatory attention even when model capability remains unchanged.**

---

# 15. The Runtime Matters More Than the Model Alone

The relevant governance object increasingly becomes:

```text
Model
+
Agent Runtime
+
Memory
+
Tools
+
Permissions
+
Scale
+
Target Environment
```

This can be called the:

> **AI Action Configuration**

The same model can participate in radically different AI Action Configurations.

---

# 16. One Model, Four Risk Profiles

Consider one identical model.

### Configuration 1

```text
Offline Chat
```

Low operational impact.

### Configuration 2

```text
Sandbox Coding Agent
```

Bounded operational impact.

### Configuration 3

```text
Production Deployment Agent
```

Consequential operational impact.

### Configuration 4

```text
Persistent Critical-Infrastructure Agent
```

Potentially high operational impact.

The model is unchanged.

The governance target has changed.

---

# 17. Object C — Consequential External Action

The third object is the most important for strong governance.

The central question becomes:

> **What can this AI system actually cause to happen?**

Relevant variables include:

```text
Authority
Access
Target
Scale
Duration
Persistence
Reversibility
Blast Radius
```

This moves regulation from abstract intelligence toward concrete consequence.

---

# 18. Action Capability Should Trigger Governance

When an AI system gains meaningful external action capability, stronger governance becomes justified.

Therefore:

> **Action capability triggers governance.**

This does not mean every external API call requires government oversight.

Governance should remain proportional.

The critical transition is when external action becomes consequential.

---

# 19. Consequence Determines Governance Intensity

A useful progression is:

```text
Informational Action
        ↓
Reversible Local Action
        ↓
Organizational Action
        ↓
Production Action
        ↓
High-Impact External Action
        ↓
Critical / Irreversible Action
```

Governance requirements should increase along this progression.

Thus:

> **Consequence determines governance intensity.**

---

# 20. The Three-Part Governance Rule

The framework can therefore be summarized as:

> **Model evaluation informs governance.**

> **Action capability triggers governance.**

> **Consequence determines governance intensity.**

These three sentences establish distinct roles for capability, deployment, and consequence.

---

# 21. Capability Is Evidence, Not Automatic Guilt

A powerful model may justify:

* stronger evaluation,
* more careful deployment design,
* enhanced security,
* better misuse testing,
* preparation for new capabilities.

But model capability should not automatically be treated as evidence of harmful action.

This distinction resembles other technologies.

Knowledge and capability can create risk.

Authority and action create consequence.

---

# 22. Intelligence and Authority Must Be Separated

The deeper principle is:

> **Intelligence does not imply authority.**

A human expert does not automatically receive unrestricted authority because they are intelligent.

Likewise:

```text
AI Capability ↑
```

should not automatically produce:

```text
AI Permission ↑
```

Capability and authority should remain separate governance dimensions.

---

# 23. The Governance Target Should Follow the Risk Path

A useful method is to trace the actual path to harm.

For example:

```text
Model Capability
        ↓
Agent Runtime
        ↓
Tool Access
        ↓
Permission
        ↓
Scale Loop
        ↓
External Action
        ↓
Harm
```

Governance should ask:

> At which points can the risk most effectively and proportionally be controlled?

Often the answer will involve several layers.

But the strongest intervention should generally be closest to consequential action.

---

# 24. The Proximity-to-Consequence Principle

This suggests:

> **The closer a control point is to consequential external action, the more directly it can regulate actual operational risk.**

For example:

```text
Training Compute
```

is far from consequence.

```text
Production Credential Authorization
```

is much closer.

```text
Approval of an irreversible transaction
```

is closer still.

This does not make upstream controls useless.

It clarifies their roles.

---

# 25. Upstream Controls and Downstream Controls

A mature framework should distinguish:

### Upstream Controls

Used for:

```text
Research
Evaluation
Forecasting
Security Preparation
Capability Monitoring
```

### Downstream Controls

Used for:

```text
Authorization
Permission
Scale
Execution
Verification
Audit
Liability
```

Both matter.

But they solve different problems.

---

# 26. The Regulatory Gradient

Instead of one universal AI regulation, governance can follow a gradient:

```text
MODEL
│
├── Evaluation
├── Security Testing
└── Capability Monitoring

AGENT RUNTIME
│
├── Identity
├── Tool Boundaries
├── Persistence Limits
└── Delegation Controls

ACTION
│
├── Authorization
├── Scale Limits
├── Verification
└── Audit

CRITICAL ACTION
│
├── Multi-Party Approval
├── Independent Verification
├── Strong Accountability
└── Emergency Stop
```

This distributes governance to the correct layers.

---

# 27. The Autonomous Impact Threshold Connects the Layers

The **Autonomous Impact Threshold (AIT)** provides the transition point.

Conceptually:

```text
Model
   ↓
Agent
   ↓
Tools
   ↓
Authority
   ↓
Scale
   ↓
Autonomous Impact
   ↓
AIT Crossing
   ↓
Stronger Governance
```

AIT asks not:

> Is this AGI?

but:

> Has this deployment acquired enough autonomous external impact to require stronger controls?

---

# 28. AIT Is Deployment-Specific

The same model may be:

```text
AIT-0
as an offline assistant
```

and:

```text
AIT-3
as a persistent high-authority autonomous system
```

Therefore:

> **Regulatory intensity should follow the deployed action configuration rather than model identity alone.**

---

# 29. AIT Is Dynamic

A system can cross the threshold because of:

```text
New Tool
New Credential
More Agents
Longer Persistence
Higher Rate
New Target
Reduced Verification
Expanded Permission
```

No model retraining is required.

This is another reason model-level regulation alone is insufficient.

---

# 30. Scale Is a Governance Variable

AI introduces a particularly important dimension:

> **How much action can be automated?**

Traditional permission systems ask:

```text
Can X perform Y?
```

AI governance must increasingly ask:

```text
Can X perform Y
against Z
at rate R
for duration T
using budget B?
```

Scale transforms ordinary capability into potentially systemic capability.

---

# 31. Scale Looping Changes the Regulatory Target

A single AI action may be harmless.

But:

```text
Action
×
Looping
×
Massive Parallelism
```

can become consequential.

Therefore regulators should examine aggregate autonomous impact, not only individual transactions.

---

# 32. The Maximum Credible Action Test

One practical governance question is:

> **What is the most consequential action this deployed system could plausibly perform using its existing permissions and resources?**

This is more useful than asking only:

> What is the system intended to do?

Security engineering evaluates available capability.

AI governance should do the same.

---

# 33. The Maximum Credible Scale Test

A second question is:

> **What happens if the system exercises its authorized action at maximum available scale?**

For example:

```text
1 Action
```

may be safe.

```text
1,000,000 Adaptive Actions
```

may not be.

The governance target must therefore include scale.

---

# 34. The Human-Absent Test

A third question is:

> **What can this system do if its responsible human disappears for 24 hours?**

This exposes actual autonomy.

If the system continues:

```text
Observe
Plan
Delegate
Execute
Evaluate
Repeat
```

then it is no longer merely an interactive tool.

---

# 35. The Compromise Test

Ask:

> **What could an attacker accomplish by taking control of the deployed agent without acquiring any additional permissions?**

If the answer is catastrophic, the deployment already contains a dangerous authority surface.

The model's AGI status is irrelevant.

---

# 36. The Wrong Regulatory Target Can Create Perverse Incentives

Suppose regulation is based primarily on model size.

Developers may optimize around:

```text
Stay Below Model Threshold
        ↓
Add More Agent Scaffolding
        ↓
Add More Search
        ↓
Add More Tools
        ↓
Add More Scale
```

The system may become operationally stronger while remaining legally below the model threshold.

This is regulatory arbitrage.

---

# 37. Action-Based Governance Reduces Regulatory Arbitrage

If governance follows:

```text
Autonomy
Authority
Scale
Consequence
```

then architectural workarounds become harder.

The relevant question remains:

> What can the deployed system actually do?

---

# 38. The Open-Source Question

Open-source AI illustrates the importance of target selection.

An open model can exist as:

```text
Weights
+
Offline Research
```

with little direct external impact.

The same model can later become part of a high-impact autonomous deployment.

Therefore:

> **Open availability and high-impact action should not be treated as synonymous.**

Governance should focus strongly on the latter.

---

# 39. Protecting Open Research While Governing Harm

A well-designed system can simultaneously support:

```text
Open Research
Open Models
Academic Experimentation
Local AI
Small Developers
```

while strongly governing:

```text
Unauthorized Autonomous Attack
High-Scale Harmful Deployment
Critical Infrastructure Action
Dangerous Irreversible Operations
```

These objectives are not contradictory.

They require correct target selection.

---

# 40. The Incumbent Advantage Problem

Model-level regulation can disproportionately favor actors that already possess:

```text
Capital
Lawyers
Compliance Teams
Government Relationships
Large Compute Infrastructure
```

This creates the possibility of regulatory capture even when safety concerns are genuine.

Therefore governance design should minimize unnecessary fixed compliance costs unrelated to actual action risk.

---

# 41. Safety Concern and Commercial Incentive Can Coexist

The policy debate should avoid a false binary.

It is possible that:

```text
Safety Concerns Are Genuine
```

and simultaneously:

```text
Regulation Benefits Incumbents
```

and simultaneously:

```text
Capital Pressure Is Real
```

and simultaneously:

```text
Some AI Risks Are Real
```

These propositions do not cancel one another.

Good regulation should remain robust regardless of corporate motivation.

---

# 42. Governance Should Be Motive-Independent

A strong framework should not depend on answering:

> Is this CEO sincere?

or:

> Is this company seeking regulatory advantage?

Instead ask:

```text
What is the action?

Who authorized it?

What authority exists?

What is the scale?

What is the consequence?

What controls exist?

Who is accountable?
```

These are auditable questions.

---

# 43. The AI Action Accountability Stack

Once consequential action becomes the regulatory focus, accountability becomes clearer.

The chain can be represented as:

```text
Responsible Principal
        ↓
Agent Identity
        ↓
Authorization
        ↓
Permission
        ↓
Action
        ↓
Consequence
        ↓
Audit
```

Responsibility remains attached to the action path.

---

# 44. Regulation Should Not Create an AI Accountability Vacuum

A system should never be allowed to argue:

```text
The AI acted autonomously
        ↓
Therefore nobody is responsible
```

Autonomy should increase the importance of accountability, not eliminate it.

Thus:

> **AI autonomy must not break the chain of accountability.**

---

# 45. Platform Governance Should Follow Material Control

Platforms also occupy different positions.

A platform that merely distributes a general-purpose model is different from one that provides:

```text
Agent Orchestration
+
Credentials
+
Persistent Runtime
+
Massive Compute
+
External Execution
```

The second platform is much closer to the active control plane.

Its duty of care may therefore be stronger.

---

# 46. The Active Control Plane Principle

A useful accountability rule is:

> **Governance responsibility generally increases as an actor moves closer to the active control plane of consequential action.**

This may include:

```text
Model Developer
        ↓
Agent Platform
        ↓
Deployer
        ↓
Operator
        ↓
Action
```

The chain is not absolute.

Intent, knowledge, control, and material enablement still matter.

But operational proximity is highly relevant.

---

# 47. Critical Actions Deserve Action-Class Regulation

Certain actions may deserve strong controls regardless of which model performs them.

Examples may include high-consequence operations involving:

```text
Critical Infrastructure
Large Financial Authority
Dangerous Biological Workflows
Weapons Systems
Mass Unauthorized Cyber Activity
Irreversible Production Operations
```

The regulation attaches primarily to the action class.

This is conceptually cleaner than trying to determine whether the model is sufficiently intelligent to be dangerous.

---

# 48. The Same Principle Already Exists Elsewhere

Society routinely governs authority rather than intelligence.

A highly intelligent person does not automatically receive:

```text
Bank Transfer Authority
Nuclear Launch Authority
Root Access
Medical Prescription Authority
Aircraft Control Authority
```

These powers require separate authorization.

AI should not be treated differently.

---

# 49. Intelligence Can Remain Abundant

This produces an important positive vision.

Future society may contain abundant machine intelligence:

```text
Coding Intelligence
Scientific Intelligence
Medical Intelligence
Educational Intelligence
Engineering Intelligence
Personal Brain Units
```

The existence of abundant intelligence need not imply abundant uncontrolled authority.

This distinction can preserve both innovation and safety.

---

# 50. From Intelligence Scarcity to Authority Governance

Historically, intelligence itself was scarce.

AI may make intelligence increasingly abundant.

Governance therefore must adapt.

The scarce resource requiring control becomes less:

```text
Who can think?
```

and more:

```text
Who can act?
On what?
At what scale?
Under whose authority?
```

This is a major institutional transition.

---

# 51. The Core Policy Error

The greatest early mistake in AI regulation may therefore be:

> **Governing intelligence when the real governance target is autonomous authority.**

This does not mean intelligence evaluation is irrelevant.

It means intelligence should not be confused with authority.

---

# 52. A Better Regulatory Architecture

A mature regulatory structure may therefore look like:

```text
MODEL LAYER
    ↓
Evaluate Capability
    ↓
Forecast Emerging Risk

AGENT LAYER
    ↓
Identity
Tool Boundaries
Persistence Controls

AUTHORITY LAYER
    ↓
Permission
Scale
Target
Resource Limits

ACTION LAYER
    ↓
Verification
Counter-Evidence
Policy Gate

CONSEQUENCE LAYER
    ↓
Audit
Accountability
Incident Response
Enforcement
```

Each control sits close to the problem it is designed to solve.

---

# 53. Do Not Eliminate Upstream Safety Research

Action-based governance should not become an excuse to abandon:

* alignment research,
* capability evaluation,
* model security,
* interpretability,
* misuse testing,
* catastrophic-risk research.

These remain important.

The argument is narrower:

> **Strong regulatory intervention should be carefully matched to actual risk pathways rather than automatically attached to intelligence progress itself.**

---

# 54. Defense in Depth

The best governance system will likely use multiple layers:

```text
Model Safety
+
Agent Safety
+
Action Governance
+
Institutional Accountability
```

The Governance Target Selection Problem is therefore not solved by choosing only one target.

It is solved by assigning the correct regulatory function to each target.

---

# 55. Primary and Secondary Targets

This distinction is useful.

### Secondary / Informational Targets

```text
Training
Compute
Model Capability
Benchmark Performance
```

These can inform forecasting and preparation.

### Primary Operational Targets

```text
Agentic Autonomy
Authority
Access
Scale
External Action
Consequence
```

These should dominate operational governance.

---

# 56. A Minimal Decision Framework

Before proposing an AI regulation, policymakers should answer five questions.

### 1. What specific harm is being prevented?

Not merely:

> AI may become dangerous.

But:

> What action pathway creates the harm?

### 2. Where in the system does that harm become operationally possible?

Model?

Agent?

Tool?

Permission?

Action?

### 3. Which actor has practical control at that point?

Developer?

Platform?

Deployer?

Operator?

### 4. What is the least restrictive effective control?

Evaluation?

Sandbox?

Rate limit?

Authorization?

Audit?

Liability?

Prohibition?

### 5. What unintended effects will the regulation create?

Innovation loss?

Market concentration?

Regulatory arbitrage?

Open-source suppression?

These questions should precede major intervention.

---

# 57. The Least-Restrictive Effective Control Principle

Governance should seek:

> **The least restrictive control that reliably interrupts the relevant harm pathway.**

For example, if:

```text
Permission Boundary
```

can effectively prevent the harm, it may be unnecessary to prohibit:

```text
Model Research
```

This principle improves proportionality.

---

# 58. The Closest Effective Control Point

An even stronger engineering rule is:

> **Prefer the control point closest to consequential action that can reliably prevent the harm, while retaining upstream defense-in-depth where justified.**

This avoids unnecessary restrictions far upstream.

---

# 59. A Regulatory Example: AI Coding

Suppose policymakers worry that autonomous coding agents may damage production systems.

One approach is:

```text
Restrict Advanced Coding Models
```

Another is:

```text
Allow Advanced Coding
        ↓
Require Repository Identity
        ↓
Sandbox Generation
        ↓
Run Verification
        ↓
Analyze Structural Delta
        ↓
Require Authorization for High-Risk Merge
        ↓
Require Stronger Gate for Production
```

The second approach targets the risk pathway more precisely.

---

# 60. A Regulatory Example: Autonomous Cyber Activity

Suppose the concern is large-scale unauthorized cyber action.

A model-centered response is:

```text
Restrict Models Capable of Cyber Reasoning
```

An action-centered response focuses on:

```text
Unauthorized Targets
+
Persistent Autonomous Scanning
+
Exploit Execution
+
Credential Use
+
Massive Parallelism
```

The second is closer to the harmful act.

---

# 61. A Regulatory Example: Financial Agents

A financial assistant may analyze markets freely.

The governance boundary changes when it receives:

```text
Trading Authority
+
Large Capital
+
Persistent Execution
+
High Transaction Rate
```

Again:

> **Authority, not intelligence alone, creates the critical transition.**

---

# 62. A Regulatory Example: Scientific AI

A scientific model may generate hypotheses.

That should not automatically place it in the same governance category as a system capable of autonomously executing high-consequence physical experiments.

The transition is:

```text
Knowledge
        ↓
Design
        ↓
Authorization
        ↓
Physical Execution
```

Governance should become stronger near consequential execution.

---

# 63. The International Coordination Advantage

Countries may find it difficult to agree on:

```text
What is AGI?
How powerful may models become?
What compute level is acceptable?
```

But they may find it easier to agree on:

```text
Which autonomous actions are prohibited?
Which critical actions require attribution?
Which systems require human authorization?
Which incidents must be reported?
```

Action-based governance may therefore provide a more practical foundation for international coordination.

---

# 64. The Prisoner's Dilemma Does Not Disappear

AI competition remains real.

Companies and countries may still race toward greater capability.

Action-based governance does not eliminate this competition.

But it can constrain how capability is converted into uncontrolled external power.

That distinction matters.

---

# 65. From Capability Race to Governed Deployment

A desirable equilibrium is not necessarily:

```text
Nobody develops powerful AI.
```

It may instead be:

```text
Many actors develop powerful AI
        ↓
Powerful AI remains broadly available
        ↓
Consequential authority is bounded
        ↓
High-impact actions are accountable
```

This preserves competition while reducing dangerous externalities.

---

# 66. The Governance Target Selection Test

Before adopting any AI regulation, ask:

```text
Does this rule primarily restrict:

A. Intelligence?

B. Agentic autonomy?

C. Authority?

D. Action?

E. Consequence?
```

Then ask:

> **Is that the layer where the targeted harm actually arises?**

If not, reconsider the regulatory design.

---

# 67. The Governance Target Selection Matrix

| Governance Target      | Primary Value          | Primary Risk                         |
| ---------------------- | ---------------------- | ------------------------------------ |
| Training / Compute     | Early visibility       | Overbroad restriction                |
| Model Capability       | Risk forecasting       | Capability ≠ consequence             |
| Agent Runtime          | Controls autonomy      | May miss external authority          |
| Permission / Authority | Bounds power           | Requires infrastructure              |
| External Action        | Direct risk control    | Needs good attribution               |
| Consequence            | Strong proportionality | Often requires domain-specific rules |

No single layer solves everything.

But the table clarifies what each layer is actually good for.

---

# 68. A Canonical Governance Flow

The complete framework can be represented as:

```text
MODEL
  │
  │ evaluate
  ▼
CAPABILITY
  │
  │ configure
  ▼
AGENT
  │
  │ authorize
  ▼
AUTHORITY
  │
  │ scale
  ▼
AUTONOMOUS ACTION
  │
  │ assess
  ▼
CONSEQUENCE
  │
  │ classify
  ▼
AIT
  │
  │ govern
  ▼
ACCOUNTABILITY
```

This is the central architecture of Pre-AGI AI Action Governance.

---

# 69. The Three Canonical Principles

The entire argument can be compressed into three sentences:

> **Model evaluation informs governance.**

> **Action capability triggers governance.**

> **Consequence determines governance intensity.**

These principles preserve a role for model safety without making intelligence itself the primary regulated action.

---

# 70. A Fourth Principle

A fourth principle completes the framework:

> **Authority should never scale automatically with intelligence.**

As AI becomes more capable, society may deliberately grant more authority.

But that should be a separate, explicit, accountable decision.

---

# 71. A Fifth Principle

And finally:

> **The stronger the autonomous impact, the stronger the required accountability.**

This connects target selection to the Autonomous Impact Threshold and AI Action Accountability Stack.

---

# 72. Conclusion

AI governance begins with a target-selection problem.

Before writing rules, policymakers must determine what those rules are actually trying to control.

Possible targets include:

```text
Training
Model
Capability
Agent
Tool
Permission
Authority
Action
Consequence
```

These should not be collapsed into a single concept called “AI.”

Model capability matters.

It should be evaluated.

Agentic architectures matter.

They should be controlled.

But the strongest governance should increasingly follow the point at which machine intelligence acquires:

```text
Authority
+
Access
+
Autonomy
+
Scale
+
Persistence
```

and converts them into consequential external action.

The central policy architecture is therefore:

> **Model evaluation informs governance.**

> **Action capability triggers governance.**

> **Consequence determines governance intensity.**

This framework avoids two symmetric mistakes.

It avoids assuming that:

> powerful intelligence is automatically dangerous action.

And it avoids assuming that:

> non-AGI systems cannot become dangerous.

Most importantly, it identifies a practical regulatory objective:

> **Do not unnecessarily constrain intelligence when authority, access, scale, and action can be governed more directly.**

The challenge of the coming AI era may not be scarcity of intelligence.

It may be abundance of intelligence combined with poorly governed authority.

Therefore the foundational question for regulators should not merely be:

> **How powerful is this AI?**

It should be:

> **What authority has this AI been given, what can it do with that authority, at what scale, and who remains accountable for the consequences?**

That is the **Governance Target Selection Problem**.

Solve it correctly, and AI governance has a workable foundation.

Solve it incorrectly, and society may simultaneously restrict beneficial intelligence while failing to control dangerous action.
