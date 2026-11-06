# CONCEPT-IDEA: Sustainable Product Innovation Decision-Support Tool

> **Purpose of this document:** capture *what* you want to exist and *why it matters* —
> before anyone argues about *how* to build it.
> **Written by:** you (with an AI assistant as a thinking partner).
> **Reviewed by:** a human, before you move on to `SPECIFICATION.md`.

| Field | Value |
| --- | --- |
| Status | Draft — revised; pending approval |
| Author | <your name> |
| Reviewer(s) | <name(s)> |
| Created | 2026-11-04 |
| Last updated | 2026-11-04 |

---

## 1. One-sentence pitch

> Sustainable Product Innovation Decision-Support Tool helps product innovation, brand strategy, and sustainability teams at consumer goods companies compare sustainable beauty and personal care product ideas so they can balance customer demand, commercial viability, and environmental impact before investing further.

## 2. The problem

Consumer product teams struggle to evaluate whether a sustainable product innovation is likely to attract customers while also meeting environmental, performance, cost, and profitability requirements.

They currently cope by using a combination of:

- Traditional market research and consumer surveys
- Focus groups
- Competitor benchmarking
- Trend analysis
- Financial modeling
- Internal product development processes
- Separate sustainability assessments covering sourcing, packaging, materials, and regulations

The proposed project is based on preliminary evidence that this evaluation process is challenging. Consumer goods companies must balance competing considerations, and products with environmental benefits may still perform poorly commercially if consumers perceive them as expensive, inconvenient, or inferior.

The extent and cost of the resulting delays, repeated work, missed opportunities, and decision-making inefficiencies are not yet established. The user has reported that information and decisions may be fragmented across marketing, R&D, finance, and sustainability teams, but the significance of these issues in practice must be validated through research.

Available evidence has been only preliminary. The user has not conducted direct primary research yet and does not have direct evidence that teams lack effective tools, that specific AI recommendations would convert into purchases, or that the proposed AI approach will outperform existing processes.

## 3. Who it is for

| Audience | What they care about | How they'd find us |
| --- | --- | --- |
| Primary user | Product innovation, brand strategy, and sustainability professionals evaluating sustainable product opportunities | Discovered through SPUR research, industry interviews, professional networks, or academic project channels |
| Secondary user | Marketing, R&D, and finance colleagues contributing demand, feasibility, cost, and profitability evidence | Through internal teams working with the primary users |
| Person who decides / pays | Internal leaders responsible for product innovation and investment decisions, as explored during research | Existing organizational product and sustainability governance processes |

The initial required category is beauty and personal care. Household care and packaged food are possible later extensions.

## 4. The idea

The first version is an interactive, AI-assisted dashboard for evaluating sustainable product innovations in beauty and personal care. The dashboard brings together structured research on consumer demand, competitor positioning, financial feasibility, and environmental indicators, helping teams compare ideas and examine trade-offs rather than relying on disconnected assessments.

The prototype should not use a custom sales prediction model. Instead, it should organize available evidence, support AI-assisted research, apply transparent evaluation criteria, and make limitations visible.

**Day in the life (Version 1):**

1. A user enters or uploads information about a sustainable beauty or personal care product concept.
2. The system helps the user compare consumer demand, competitor positioning, estimated profitability, and relevant environmental indicators.
3. The team reviews the evidence behind a comparison, examines trade-offs, and prioritizes concepts for additional testing rather than treating the output as a guaranteed prediction of success.

The prototype should be adaptable to another FMCG category later, but the evaluated framework will initially be built around beauty and personal care.

## 5. What success looks like

| Signal | How we measure it | Target | By when |
| --- | --- | --- | --- |
| Number of concepts evaluated | Count concepts assessed using the same four dimensions in the prototype | 5 documented public-data beauty and personal care concepts; 10 concepts are an optional stretch target | By the end of prototype testing |
| Evaluation comparison | Compare AI-assisted and manual evaluations on the same public evidence | Record the process for the completed concepts, without assuming a required accuracy or time target | By the end of prototype testing |
| Accuracy evidence | Compare outcomes only with independently verifiable public reference data | Record an accuracy observation when reliable ground truth exists; otherwise record “No ground truth available” | During the semester |
| Research usefulness | Document usefulness, limitations, and responsible AI considerations for both approaches | Record observations for each completed comparison | During the semester |
| Sustainability coverage | Check that every concept record contains available environmental indicators alongside commercial considerations | 100% of evaluated concepts | By the end of prototype testing |

These targets are proposed research benchmarks supplied by the user, not established results. Optional feedback from professors or industry professionals may be collected for qualitative insight, but it is not required and will not be treated as proof of accuracy, prediction quality, or commercial viability.

## 6. Explicitly out of scope (for now)

- **Not building:** Live integrations with proprietary consumer databases, retail sales platforms, or paid market intelligence services.
- **Not building:** Custom machine-learning models trained to predict product sales or commercial success.
- **Not building:** Full life-cycle assessments or precise carbon-footprint calculations for individual products.
- **Not building:** Required support for any category other than beauty and personal care in Version 1. Any expansion to household care or packaged food is an optional stretch goal only.
- **Not building:** Generated product formulations, packaging designs, or manufacturing specifications.
- **Not building:** User accounts, team collaboration, complex databases, proprietary-system integrations, or enterprise-grade security.
- **Not building:** Commercial deployment, customer acquisition, paid subscriptions, or a scalable business version during the semester.
- **Not building:** Guaranteed purchase predictions, claims of commercial success, or definitive environmental impact conclusions.

## 7. Constraints and realities

- **Time:** Exactly 3 focused hours per week for 12–15 weeks, subject to academic availability.
- **Money:** Strict $0 budget. Development, data collection, testing, hosting, APIs, and subscriptions must remain free.
- **Tools:** Prefer tools and resources already available through NYU or existing accounts, including free tiers, open-source resources, public datasets, VS Code, GitHub, GitHub Copilot, Codex, and MCP tools.
- **Skills:** The user's background is primarily in business, finance, sustainability, and consumer market research, rather than programming. They are currently learning to use VS Code, GitHub, GitHub Copilot, Codex, and MCP tools.
- **Technical approach:** Prefer AI-assisted development and beginner-friendly technologies over complex frameworks.
- **Data:** Publicly accessible consumer research, product information, sustainability reports, and public datasets are expected sources. Proprietary sales data and detailed environmental assessments may not be available.

## 7A. Evidence and claim discipline

| Class | Meaning | Display rule |
| --- | --- | --- |
| Observed fact | A value or statement supported by a cited public source and its capture context | Show source provenance, capture date, and limitations. |
| Hypothesis | An unconfirmed project assumption, such as a team-workflow difficulty or likely AI benefit | Label “Hypothesis—not validated”; do not present it as a finding. |
| AI-generated interpretation | A summary, comparison, or synthesis produced with AI assistance | Label the producing method and treat it separately from observed public evidence. |
| Unverified claim | A statement without adequate source support | Keep it out of the evaluation or show it clearly as unverified and missing evidence. |

No predictive-accuracy or commercial-success claim is made unless independently verifiable public reference data supports it.

## 8. Alternatives considered

| Option | Why not (yet) |
| --- | --- |
| Do nothing / status quo | Current teams use fragmented research, surveys, finance models, and separate sustainability assessments, which may create slow analysis and inconsistent trade-offs. These limitations are hypotheses until industry research validates them. |
| Existing market research, survey, and consumer insight tools | These tools are already part of the current process but do not, according to the user's hypothesis, integrate commercial, sustainability, and competitive evaluation in one decision-support workflow. This must be verified through interviews and tool review. |
| Separate internal analyses by marketing, R&D, finance, and sustainability | This is how teams may work today, but it can keep information and decision criteria in separate functions, making integrated trade-offs harder. |
| A simpler spreadsheet or manual comparison framework | A manual framework may be a useful baseline, but the project is exploring whether AI-assisted research and an accessible dashboard can reduce effort and improve consistency. |

## 9. Open questions

- [ ] Which parts of the current sustainable innovation evaluation process are the most difficult, slow, or error-prone in practice?
- [ ] Which teams already have effective tools, and where does each tool fall short?
- [ ] Which sources and metrics can establish consumer demand without overstating intent-to-buy claims?
- [ ] What environmental indicators are available for public beauty and personal care products without conducting full life-cycle assessments?
- [ ] Which financial and pricing inputs are realistic and legally available under the $0 budget constraint?
- [ ] What independently verifiable public reference data, if any, is suitable for measuring accuracy?
- [ ] How should time and usefulness be compared between AI-assisted and manual evaluation if those measurements are feasible?
- [ ] If no reliable public ground truth is available, how should the research document the absence of an accuracy claim?
- [ ] Is historical sales or product-outcome data available publicly for suitable test concepts?
- [ ] Would an adaptable framework produce useful results if tested beyond beauty and personal care, if time permits?
- [ ] What existing consumer research supports the attitude–behavior gap claim for the selected beauty and personal care categories, and what are its limits?

## 10. Assumptions

- 🔴 The project assumes that disconnected consumer, financial, competitive, and sustainability evidence can make sustainable innovation decisions slower or less consistent. This has not yet been validated through primary research and could change the project significantly.
- 🔴 The project assumes that an AI-assisted structured comparison can help teams make better early-stage decisions. The improvement is not yet proven.
- 🔴 Hypothesis: publicly available data may be sufficient for documenting the required five beauty and personal care concept records. This cannot be assumed; source eligibility and available ground truth must be tested early.
- 🟡 The project assumes that beauty and personal care are suitable initial research categories because they offer opportunities across packaging, ingredients, formulations, and consumer preferences.
- 🟡 The project assumes that a simple dashboard can make trade-offs visible enough to be useful without enterprise integrations.
- 🟢 The project can be kept within a 12–15-week semester, 3 hours per week, and a $0 budget. The final scope may need adjustment if this proves infeasible.

---

## Reviewer sign-off

Reviewer: fill this in. Do **not** proceed to specification until the boxes are checked.

- [ ] The problem is real and clearly stated, independent of the solution
- [ ] The audience is specific (not "everyone")
- [ ] Success criteria are measurable
- [ ] Out-of-scope list is honest and meaningfully limits v1
- [ ] Risky assumptions are identified
- [ ] Open questions are captured, not hidden

**Verdict:** `Draft` / `Needs rework`

**Reviewer notes:**

>
