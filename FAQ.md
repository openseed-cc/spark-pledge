# FAQ

Most of the questions below were put to us in person, by people who work on open source funding for a living and were not being polite about it. We have kept their framing rather than softening it.

**Where we do not have an answer, we say so.** A pledge framework that only publishes the questions it can answer is not worth signing.

---

## What this actually is

### Is this equity? Am I giving away part of my company?

No. **It is a conditional gift** — a donation with a condition attached, not an investment and not a security. Nobody acquires a claim on your company, a vote, or a seat.

The percentage works *like* equity in one narrow sense: it is a standing share of upside rather than a one-time payment. But the direction is reversed. An investor takes 5% and expects a return. Under SPARK you commit a share and the return goes to the commons.

### Is it a tax on revenue?

No — and this is the distinction that matters most.

The trigger is **captured value**, not revenue, and not activity. If you never commercialize, you owe nothing, forever. If you have a loss-making year, you owe nothing that year. There is a three-year grace period after commercialization before anything is due.

The closest analogy is **GPL applied to money instead of code**:

> Nobody is required to open their source. But if you distribute, you must. Under SPARK: if you never capture value, you owe nothing. If you do, you pay it forward.

### What happens if my project never makes money?

Nothing happens. That is the design. Most open source projects never commercialize, and the pledge costs them nothing but the line in their README.

### Why would anyone sign this?

Honestly: at v0.1, mostly because they already wanted to and had no vehicle. We are not claiming this is in a project's narrow financial self-interest — it plainly is not.

What we think it does offer is a **credible commitment device**. "We'll give back once we're successful" is something a great many projects have said and very few have done, because there was no moment at which it became concrete. SPARK makes it concrete at the point of signing, when it costs nothing, rather than at the point of success, when it costs real money and there is always a reason to wait.

---

## The hard questions

### The recipients won't understand what they're signing.

**This is the strongest objection we have received, and we do not have a complete answer.**

The exact form it was put to us: *signing a document is easy — the problem is that they don't know what's written on it.* Maintainers of small projects are frequently not people with financial or legal training, and a pledge that requires them to understand value capture, commercialization thresholds, and accrual is asking a lot.

What we can say:

- The obligations are designed to be dormant until the signatory has become an organization that *does* have finance and legal capacity. By the time the 4% is actually payable, there is a company or foundation with accountants.
- We intend to publish a plain-language summary alongside the legal text, and to refuse signatures from anyone who has not read it.

What we cannot say is that this solves the problem. **It does not.** Comprehension at signing time remains an open risk, and the failure mode — someone signs something they did not understand and resents it later — is exactly the failure mode that would discredit the whole model.

### Auditing this is expensive. Who pays for it?

The audit and verification cost is real, and it cannot sit on the recipient — a small project cannot absorb it, and a large one has no reason to.

**It sits on the institution.** This is a large part of why OpenSeed exists as an entity rather than as a document: it holds the agreements, reads the reports, and absorbs the overhead so that individual signatories don't have to.

How that institution is funded at scale is not solved. Today it is funded by initial backing that is enough to run a first round. **If it cannot eventually fund its own operations, the model does not scale** — that is a fair criticism and we do not have a projection that says otherwise.

### Someone has to actually read the financial reports. Who?

The institution, and yes, it needs to be a person with the relevant training rather than a script.

At the scale of a first cohort this is tractable. At the scale of hundreds of signatories it is not tractable manually, and the honest answer is that we are relying on two things that are not yet proven: that **on-chain value is far easier to verify than fiat** (where the allocation is visible by construction), and that automated attestation tooling will mature. For fiat-only, privately-held signatories, verification currently rests on contractual disclosure to the donor and nothing stronger.

### What stops a company from simply not disclosing?

The pledge agreement obliges the signatory to **disclose to the donor**. Without that clause the whole mechanism can be escaped by silence.

But we should be clear about what that is worth: it is a **contractual** obligation, enforceable in principle by the same means as any other contract, and enforcing contracts against an uncooperative party is slow and expensive. Realistically, at this stage the binding force is **reputational** — the pledge is public, the reports are public, and non-compliance is visible.

We think that is enough to start. We do not think it is enough at scale, and we would rather say so now.

### So this institution needs lawyers. Isn't that the whole problem again?

Yes, it needs legal capacity. The reference point we keep returning to is the **Software Freedom Law Center** in its early years: it employed people, took donations, paid salaries, and defended the GPL — and as the GPL became consensus, the defending became less and less necessary.

That is the shape of the bet. **If SPARK works, the institution should eventually have very little to do.** If it needs to grow indefinitely to keep functioning, that is evidence the norm never took hold.

### Founders don't understand this model, because there is no precedent for it.

Correct, and this was said to us by someone who supports the effort. There is no established category to file SPARK under, so every conversation starts from zero.

We are treating that as a communication problem to be worked on, not as a reason to add familiar-sounding features that would compromise the mechanism. The two analogies that have worked best in practice are **"GPL, but for money"** and **"seed round terms, but the return goes to the commons."**

### Isn't the real bottleneck picking the first project, not the mechanism?

**Yes. We think this is right, and it is the single most important open item.**

The criteria we have converged on for a first partner:

| Criterion | Why |
|---|---|
| **Small enough to move** | A large project has too many stakeholders to agree to something novel |
| **Healthy enough to survive** | A project that is desperate for money will not last to the point where paying forward is possible. Funding it is charity, not a test of the mechanism |
| **Genuinely growing** | If there is never upside, the pledge is never exercised and proves nothing |
| **A lead with real conviction** | Someone who will not abandon the commitment the moment a cleaner term sheet appears |

We have not picked one yet. **If you know a project that fits these criteria, telling us is more useful than anything else on this page.**

---

## Things we do not have answers to

We would rather list these than have you find them.

### Enforcement has no teeth yet

The pledge is contractual and reputational. It is not, today, backed by anything that makes non-compliance expensive at scale. We do not have a proposal we are confident in.

### Verification is much weaker for fiat than for on-chain value

Where value capture happens on-chain, allocation is visible and auditable by construction. Where it happens through a conventional private company, we are dependent on the signatory's own disclosure. This is an asymmetry, not a solved problem.

### Copyright-based mechanisms are weakening, and SPARK does not fix that

The broader context: **the enforceability of copyright-based open-source obligations is eroding.** Models trained on licensed code are routinely not treated as derivative works; "derivative work" is a genuinely ambiguous category across jurisdictions; and there is a serious argument that a model's weights are not a work at all — only its inputs and outputs are.

SPARK does not address this. It attaches obligations to **value capture** rather than to code distribution, which sidesteps the problem for signatories but does nothing about non-signatories who take from the commons and return nothing.

One direction we have explored is a `robots.txt`-style convention — a machine-readable file a project could publish stating the terms under which its code may be used for training. The objection to it is decisive and we have not answered it: **`robots.txt` is enforceable in practice only because web servers keep access logs.** For training data there is no access log and no way to prove a violation occurred.

We think there may still be value in establishing this as a **norm** rather than a legal instrument — social conventions do work without enforcement in some domains. But we cannot currently demonstrate that it would work in this one.

### The parameters are not validated

4%, 1%, and three years are **starting values, not findings**. Nobody has run this mechanism to completion, so nobody knows whether those numbers are too aggressive to sign or too small to matter. They are explicitly adjustable and we expect them to change.

### It might just not work

This is closer to a startup than to a foundation. We would put the odds of the mechanism becoming a genuine norm at somewhere well short of even — which, for something that has no existing category, we consider good enough to be worth running in public.

---

## Practical

### Can I adopt SPARK with different percentages?

When signing opens, yes. We are not asking projects to sign yet: the pledge text has not been published. Once it is, say which parameters you are using. The numbers are explicitly adjustable, and a signatory at different terms is far more useful to this effort than a non-signatory.

### Does the 1% to dependencies require them to sign too?

No. The 1% is **unilateral** — upstream dependencies receive support with no obligation attached. Only the 4% carries the recursive condition.

### Is this specific to crypto or to the Ethereum ecosystem?

No. SPARK originated in that context and on-chain value capture makes several parts of it dramatically easier to verify — but the mechanism is not blockchain-dependent, and making it work outside crypto is an explicit goal. A norm that only exists in one ecosystem is not a norm.

### Who is behind OpenSeed?

Richard Lin is the public lead. There are several co-founding partners who are not public yet.

<details>
<summary><b>Contact Richard Lin</b></summary>

- Email: [richard.openq@gmail.com](mailto:richard.openq@gmail.com)
- LinkedIn: [linkedin.com/in/richardlinq](https://www.linkedin.com/in/richardlinq)

</details>

### Is Vitalik Buterin funding this?

**No.** OpenSeed is an independent effort to implement SPARK. Funding comes from elsewhere and we do not speak for him or for the Ethereum Foundation.

### Has anyone actually funded open source this way before?

Not on these terms — the recursive condition is what is new.

There is, however, more precedent for investors and companies donating to open source than people assume. A publicly verifiable example: **Sequoia's $100,000 contribution to vLLM**, visible on Open Collective. Our read is that willingness is not the scarce resource. **Mechanism is.**

---

*Something missing, or an answer that does not hold up? [Open an issue](https://github.com/openseed-cc/spark-pledge/issues). Objections are more useful to us than endorsements right now.*
