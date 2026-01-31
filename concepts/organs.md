# Organs

*Collections of teams that perform a related function.*

---

## What Is an Organ?

An organ is a collection of cells (teams) that together perform a critical function within the larger organism (organisation).

If you're familiar with the Spotify model, think of organs as similar to tribes. In traditional org structures, they map roughly to departments or divisions. But where those terms often describe reporting lines, organs in ATD describe functional purpose.

An organ exists because:
- The function is too large or complex for a single cell
- Multiple cells need to collaborate closely on related work
- There's value in shared direction, standards, or capabilities across cells

Not every organisation needs explicit organs. Smaller organisations — where a handful of cells constitute the whole organism — might skip this layer entirely. Organs become relevant as scale creates the need for coordination without centralisation.

---

## When Organs Make Sense

Organs emerge when:

**Scale exceeds single-cell capacity**

A single team can't handle all of "platform infrastructure." You need multiple cells — one for compute, one for data, one for developer experience — that collectively fulfil the platform function.

**Related cells need coordination**

Multiple product cells serving the same customer segment benefit from shared context, aligned priorities, and consistent approaches. An organ provides this without merging the cells.

**Capability needs to be shared but not centralised**

Some capabilities — architecture, security, design — benefit from community-level coordination. An organ can house enabling cells that support other cells within it.

---

## Organ Purpose

Like cells, organs should have a clear purpose. But organ purposes are broader — they describe a function that spans multiple teams.

Examples:

| Organ | Purpose |
|-------|---------|
| **Platform** | Enable product teams to build and operate services without deep infrastructure expertise |
| **Consumer Products** | Deliver valuable experiences to retail customers |
| **Payments** | Process and reconcile all financial transactions reliably and compliantly |
| **Data** | Make organisational data accessible, trustworthy, and useful |

The organ's purpose guides decisions about which cells belong, how they should interact, and what shared capabilities matter across them.

---

## Organs and Capability Distribution

At the organ level, capability analysis shifts from "does this team have what it needs" to "does this collection of teams have what it needs."

Questions become:

**Coverage across the organ:**
- Are critical capabilities present somewhere in the organ?
- Does every cell have to be self-sufficient, or can cells specialise and support each other?
- Where are the organ-wide single points of failure?

**Shared vs. distributed capability:**
- Which capabilities should be concentrated in specialist cells (enabling teams)?
- Which should be distributed across all cells?
- Which are better provided as a platform service than a human capability?

**Movement within the organ:**
- Can people move between cells to address temporary gaps?
- Is there enough overlap in atoms that cells can support each other?
- Are there development pathways for growing capability within the organ?

Organs provide a natural boundary for this kind of analysis. It's often more useful to ensure capability coverage at the organ level than to insist every cell be independently complete.

---

## Organ Boundaries

Deciding what's inside and outside an organ matters.

**Good boundaries:**
- Align with business domains or clear functional areas
- Minimise dependencies that cross organ boundaries
- Match natural communication and collaboration patterns
- Respect cognitive load — an organ shouldn't be so large that no one understands the whole

**Warning signs of poor boundaries:**
- Cells in the organ rarely interact with each other
- Most dependencies cross organ boundaries rather than staying within
- The organ's purpose is vague or contested
- Leadership can't articulate what ties the cells together

Organ boundaries should enable autonomy within and clear interfaces without. If cells within an organ are constantly blocked by cells in other organs, the boundaries might be wrong.

---

## Organs and Reporting Structure

Organs often align with management structure — a Head of Platform, a VP of Consumer Products — but they don't have to.

ATD treats organs as functional groupings, not reporting hierarchies. The same person might lead an organ that contains cells with different reporting lines. Or an organ might be led collectively by the leaders of its constituent cells.

What matters is:
- Clear ownership of the organ's purpose
- Ability to make decisions about capability and composition at the organ level
- Accountability for the organ's function within the larger organism

How that maps to your org chart is a separate question. ATD describes the functional reality; your management structure is a political and operational choice.

---

## Not Every Organisation Needs Organs

For smaller organisations, organs might be unnecessary overhead.

**Consider skipping organs if:**
- You have fewer than 5-6 cells
- All cells interact relatively equally — there are no natural clusters
- Adding an organ layer would just be re-labelling existing structure
- Coordination happens naturally without formal grouping

**Consider adding organs if:**
- You have 8+ cells and groupings are emerging informally
- Some cells naturally cluster around shared work or customers
- Cross-cell coordination is becoming a bottleneck
- You're struggling to reason about capability at the whole-org level

Organs should earn their existence by providing useful coordination. If they're just a layer of management, they're not serving an ATD purpose.

---

## Common Mistakes

### Organs as empire-building

Organs shouldn't exist to give someone a bigger title. If the function doesn't require multiple coordinated cells, a single cell is fine.

### Too many cells per organ

If an organ contains 15 cells, the organ leader can't meaningfully understand them all. Consider whether the organ should split, or whether some cells should consolidate.

### Ignoring cross-organ dependencies

Optimising within organs while ignoring dependencies between them creates silos. The organism-level view matters.

### Treating organ boundaries as permanent

Business domains shift. Technology changes. An organ that made sense three years ago might not make sense now. Boundaries should evolve.

---

## Practical Questions

**Defining the organ:**
- What function does this organ perform for the organisation?
- Which cells belong, and why?
- What ties these cells together beyond reporting lines?

**Capability at the organ level:**
- What capabilities need to exist somewhere in the organ?
- Which should be concentrated vs. distributed?
- Are there organ-wide gaps or single points of failure?

**Coordination:**
- How do cells within the organ collaborate?
- What decisions should be made at the organ level vs. cell level?
- Are the boundaries enabling autonomy or creating silos?

---

## Next

Organs combine to form the [Organism](./organisms.md) — the organisation as a whole and how it evolves.
