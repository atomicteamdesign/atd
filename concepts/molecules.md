# Molecules

_People and services as compositions of capability._

---

## What Is a Molecule?

A molecule is a composition of atoms bonded together to form something more complex.

In ATD, molecules represent two things:

1. **People** — individuals with their unique combination of capabilities
2. **Services** — products, systems, or domains that require certain capabilities to operate

The relationship between these two types is where ATD becomes useful: people _have_ capabilities, services _require_ them. The gap between the two is your organisational risk.

---

## People as Molecules

Every person is a unique molecule — a combination of skills, experience, depth, and potential that no one else exactly shares.

This is obvious when you say it out loud, but organisations routinely ignore it. Job titles flatten people into interchangeable labels. Headcount planning treats humans as units. "We need three senior engineers" assumes those engineers are fungible. They're not.

A person's molecule includes:

- The atoms they possess (their capabilities)
- The proficiency level of each atom
- How those atoms relate and reinforce each other
- The potential for adjacent atoms to develop

Two "Senior Backend Engineers" might share a title but have almost no overlap in their actual molecules. One might be deep in distributed systems and Kafka. The other might be strong in API design and PostgreSQL. Treating them as equivalent leads to bad decisions.

---

## Services as Molecules

Services, products, and systems also have a molecular structure — but instead of _possessing_ atoms, they _require_ them.

A service molecule describes:

- The capabilities needed to build it
- The capabilities needed to run it
- The capabilities needed to change it safely
- The criticality of each requirement

For example, a payments service might require:

- Java (critical) — it's written in Java
- AWS (critical) — it runs on AWS infrastructure
- Compliance (critical) — it handles regulated transactions
- Kubernetes (important) — it's deployed on K8s
- Terraform (useful) — infrastructure is codified

Not every requirement is equal. Some are critical — without them, the service can't function or change safely. Others are important but not essential. This distinction matters when analysing coverage.

---

## The Gap Between People and Services

This is the core insight of ATD at the molecule level:

**Your team's capability = the atoms your people have.**  
**Your team's requirements = the atoms your services need.**  
**Your team's risk = the gap between them.**

Three types of risk emerge:

### 1. Gaps

A required atom that no one on the team has.

_Your service needs Terraform expertise. No one on the team knows Terraform. Every infrastructure change is a risk._

### 2. Single Points of Failure

A required atom that only one person has.

_Only one person understands the payments reconciliation logic. If they leave, get sick, or go on holiday, that knowledge walks out the door._

### 3. Shallow Coverage

A critical requirement covered only at low proficiency.

_Someone is "learning" Kubernetes, but no one is competent. The service runs on Kubernetes. This is not actually covered._

Making these gaps visible is the first step to addressing them.

---

## What About Roles?

You might wonder where job roles fit in.

A role is not a molecule. It's a _template_ — a description of what atoms a person _should_ have to fulfil certain responsibilities. Roles are useful for hiring and setting expectations, but they don't tell you what capability actually exists.

The distinction matters:

- **Role**: "Senior Frontend Developer" — implies React, TypeScript, testing, accessibility...
- **Person**: Alice — actually has React (5), TypeScript (4), testing (3), accessibility (2), design (3), UX (2), web performance (3), public speaking (3)
- **Gap**: The role implied accessibility expertise. Alice is still learning it.

ATD focuses on the actual molecules (people), not the intended templates (roles). Roles can inform what you're looking for, but they don't substitute for understanding what you have.

Looking beyond roles and at the actual capabilities of your teams not only identifies gaps but highlights unseen opportunities.

---

## Molecules Change Over Time

Unlike chemistry, organisational molecules aren't stable.

**People change:**

- Learn new atoms through practice and training
- Deepen existing atoms through experience
- Lose atoms through lack of use
- Move between teams, taking their molecules with them

**Services change:**

- Add new requirements as they evolve
- Shed requirements when components are replaced
- Shift criticality as the business changes

This means capability mapping isn't a one-time exercise. The relationship between people and services drifts over time. Regular review catches drift before it becomes crisis.

---

## Practical Questions

When analysing molecules, useful questions include:

**For people:**

- What atoms does this person actually have (not what their title implies)?
- At what proficiency level?
- What adjacent atoms could they develop quickly?
- What atoms are they actively growing?

**For services:**

- What atoms does this service require to operate?
- What atoms does it require to change safely?
- Which requirements are critical vs. nice-to-have?
- Have requirements changed since we last looked?

**For the gap:**

- Which required atoms have no coverage?
- Which have only single-person coverage?
- Which critical requirements are covered only at low proficiency?
- What's our plan for each gap?

---

## Next

Molecules don't exist in isolation. They're grouped into [Cells](./cells.md) — teams designed around a shared purpose.
