# Cells

*Teams designed from purpose, not headcount.*

---

## What Is a Cell?

A cell is a team — a group of people working together toward a shared purpose.

In ATD, cells are the primary unit of organisational structure. They're where capability meets work. A cell's purpose defines what it needs to do, which defines the capabilities it requires, which defines the people who should be part of it.

This is the opposite of how most teams form. Typically, teams inherit a headcount, accumulate responsibilities, and hope the people they have can handle whatever comes. ATD inverts this: start with purpose, derive requirements, then compose the team.

---

## Purpose Defines the Cell

Every cell should have a clear purpose — a statement of what it exists to do.

Good purposes are:
- **Specific enough** to guide decisions about what's in and out of scope
- **Stable enough** to persist beyond any single project or quarter
- **Outcome-oriented** rather than activity-oriented

Examples:

| Weak Purpose | Stronger Purpose |
|--------------|------------------|
| "The platform team" | "Enable product teams to ship safely without infrastructure expertise" |
| "Work on payments" | "Process transactions reliably and compliantly" |
| "Support the business" | "Ensure customers can resolve issues without human intervention" |

A clear purpose makes capability requirements obvious. If you can't articulate why the team exists, you can't reason about what it needs.

---

## From Purpose to Requirements

Once you know the purpose, you can derive what the cell needs to fulfil it.

This includes:
- **Services owned**: What products, systems, or domains does this cell operate?
- **Capabilities required**: What atoms do those services need? (See [Molecules](./molecules.md))
- **Interactions**: What other cells does this one depend on or serve?
- **Constraints**: What regulations, SLAs, or limits shape how the cell works?

The services a cell owns determine its capability requirements. A cell that owns a Kotlin-based payments service needs Kotlin expertise. A cell that owns a customer-facing portal needs frontend skills and likely some UX awareness.

This sounds obvious, but many teams don't explicitly map it. They assume capability requirements from job titles, or inherit them from history, or simply don't think about it until something breaks.

---

## Composing the Cell

With requirements clear, you can assess whether the current team composition makes sense.

**Questions to ask:**
- Do the people in this cell cover the required atoms?
- Are any critical requirements single points of failure?
- Are there capability gaps we need to address?
- Are there people whose atoms don't match what this cell needs?

Sometimes the answer is uncomfortable. You might find:
- A critical requirement covered only by someone who's "learning"
- A person whose skills don't fit what the cell actually needs
- A service that probably shouldn't be owned by this cell

ATD doesn't make these problems go away. It makes them visible so you can address them deliberately rather than discovering them in a crisis.

---

## Cells Are Not Static

Teams change. People join, leave, and develop. Services evolve. Business priorities shift.

A cell that was well-composed six months ago might have drifted into a risky state. Regular review — quarterly is a reasonable cadence — helps catch this.

**Signs a cell needs attention:**
- A key person left and their atoms weren't replaced
- A new service was added without reviewing capability requirements
- The purpose has quietly shifted but the composition hasn't
- Coverage gaps that were "temporary" have become permanent

Recomposition — adjusting who's in the cell and what it owns — should be a normal part of how teams evolve. It's less disruptive than periodic reorganisation and more responsive to actual needs.

---

## Cell Size and Cognitive Load

Cells have limits. Team Topologies emphasises cognitive load as a constraint — there's only so much complexity a team can effectively handle.

ATD reinforces this. A cell with:
- Too many services has too many capability requirements
- Too many capability requirements needs too many atoms
- Too many atoms either means too many people or too much expected of each person

If a cell is struggling despite having skilled people, the problem might be scope, not capability. The cell owns too much. Splitting the cell — dividing services and people into smaller units with clearer purposes — may be the right move.

There's no universal "right size" for a cell. But if you can't articulate the purpose in one sentence, or the capability requirements span dozens of atoms, or the team regularly context-switches across unrelated domains, those are warning signs.

---

## Cells and Interaction Patterns

Cells don't operate in isolation. They interact with other cells — consuming services, providing platforms, collaborating on shared goals.

ATD focuses on what's *inside* the cell, but interaction patterns matter for understanding capability requirements.

For example:
- A **platform cell** provides capabilities that other cells consume. Its purpose is to make other teams more effective.
- A **stream-aligned cell** delivers value to customers. It might depend on platform cells for infrastructure or enabling cells for specialist support.
- An **enabling cell** helps other cells acquire capabilities they need but don't have.

These patterns (borrowed from Team Topologies) influence what a cell needs. A platform cell needs different atoms than a stream-aligned cell, even if both work on similar technology. The interaction model shapes the requirements.

---

## Common Mistakes

### Designing cells around people instead of purpose

"We have Alice and Bob, so let's make a team" puts people before purpose. The result is often a team that doesn't make sense — a grab-bag of skills looking for a reason to exist.

Start with purpose. Then figure out if Alice and Bob are the right fit.

### Assuming job titles equal capability

"We have a senior engineer, so we're covered" ignores that titles don't guarantee atoms. Check what capability actually exists, not what the org chart implies.

### Ignoring services when assessing cells

A team's capability requirements come from what it owns. If you assess the team without assessing the services, you're guessing at requirements.

### Treating cell composition as fixed

People grow, leave, and move. Services change. Cells should recompose regularly, not wait for annual reorganisations.

---

## Practical Questions

**Defining the cell:**
- What is this cell's purpose in one sentence?
- What services or domains does it own?
- What other cells does it interact with, and how?

**Assessing composition:**
- What atoms do the owned services require?
- Which atoms are covered, and by whom?
- Where are the gaps and single points of failure?
- Are there people whose atoms don't match the requirements?

**Evolving the cell:**
- Has the purpose shifted since the cell was formed?
- Have services been added without reviewing capability needs?
- Is the scope appropriate, or is the cell overloaded?
- What recomposition would improve fitness for purpose?

---

## Next

Cells often group together into [Organs](./organs.md) — collections of teams that perform a related function within the organisation.
