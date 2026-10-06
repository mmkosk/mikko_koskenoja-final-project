# AI Synthesis, Product Health & Insights Summary (Module 2)

## Responses
- **Moment of misery / red flag #1 (e.g., “user gave up after 3 tries”):** The whole reason she uses BNPL is that the money only leaves once she has decided. Now she's out the cash and chasing the paper trail, which is exactly what she was trying to avoid. "I can return stuff without chasing refunds" has turned into chasing refunds.
- **Moment of misery / red flag #2:** The brand loses the in-store sale, Jonas loses time and dignity, and the one place a card was supposed to help is where it fails publicly.
- **Moment of misery / red flag #3:** She chose BNPL to feel in control and ended up as her own accountant. "I'm not broke, I just can't see everything in one place." The reminder fee turns the tool meant to protect her into a source of penalties, and Aylin's description of Riverty feeling like "an email from a collections department" shows why the tone matters too.
- **Product Health & Insights Summary (Claude's output):** Product Health & Insights Summary: Riverty Consumer Card Pilot

All inputs are synthetic (invented names, quotes, counts and ticket numbers). Label this summary as simulated wherever it appears in a deck.

Executive Summary

The pilot card is technically functional but fails at the moments that define its promise: paying in store, paying only after deciding, and seeing what is owed. Users value the "decide first, pay after" model and in-store reach, yet defects in declines, refund matching and spend visibility erode the trust that model depends on. Stability problems are therefore not a back-end concern; they are the main driver of weak differentiation against Klarna, PayPal and existing cards.

Thematic Synthesis
1. Core Payment Reliability (In-Store and Wallet)

The in-store use case is what pilot users want most (7 of 12 expect to use the card mainly in stores), and it is where the product is least dependable. Intermittent declines and wallet provisioning failures push users back to other cards, and public failures at the till cause lasting damage to confidence. Demand is also visible beyond the pilot: existing checkout users keep asking whether Riverty works in shops.

Intermittent "do not honour" declines on contactless payments under €20, reproducing in roughly 4 of 10 attempts: Critical
Apple Pay and Google Pay provisioning failing on Android 12 and below, leaving users on the physical card or not using the card at all: Medium
Low awareness of where Riverty can be used, shown by 90 "does it work in shops?" contacts in three months: Medium (signal, not a defect)
2. Pay-After-Decision Integrity (Returns and Refunds)

The central value proposition is that money leaves the account only once the user has decided to keep an item. Refunds that are not matched to the original purchase leave balances unchanged for up to 10 days, so users are charged for items they have already returned. This directly contradicts the promise users cite as their reason for choosing BNPL, and it is the issue most likely to matter to merchants, since returns affect their costs and customer relationships.

Returned-item refunds not reconciled to the original purchase, leaving open balances unchanged for up to 10 days: High
3. Financial Visibility and Control

Users who run several BNPL providers at once describe a need for a single view of what they owe, and several have built manual workarounds such as spreadsheets. The card widens the gap: spend appears late, due dates are split across separate screens, and some charges cannot be recognised. The result is real financial harm for some users, including reminder fees, and it reinforces a perception of Riverty as a collections-style experience rather than a tool for control.

Card spend delayed by up to 24 hours in the app, generating 210 support contacts this quarter: High
Due dates for card and checkout purchases split across two screens, with no combined view and 130+ tickets requesting one overview: High
Repayment notifications arriving after the due date in some time zones and after daylight saving changes: Medium
Transactions showing the processor name instead of the merchant name for about 8% of purchases: Low
4. Onboarding and Activation

Activation is a measurable leakage point. Nearly a third of approved pilot users abandon at identity re-verification, and the error message gives no explanation of what failed. Since the business case assumes 70% of approved users activate, this friction bears directly on its viability.

30% drop-off at the identity re-verification step with an uninformative error message: Medium
5. Value Proposition and Competitive Positioning

Beyond defects, interviews show an unresolved question of why someone would add a Riverty card. Users with debit, credit, Apple Pay and two BNPL apps describe a new card as clutter, and some ask what it offers over PayPal. Others anchor on price against instalment card banks. Brand preference is weak: lapsed users say Riverty is simply less present than Klarna, and they see no reason to prefer one. Interest is conditional rather than absent. Users respond positively if the card carries hassle-free returns into stores and lives in a digital wallet, and negatively if it behaves like another credit card.

No clear differentiation versus PayPal and existing cards (3 of 12 pilot participants asked what the card offers that PayPal does not): High
Preference for a digital wallet over a physical card, with card clutter as a barrier: Medium
Price pressure from instalment card banks, such as Santander, for revolving-credit use: Medium
Tone of the app perceived as collections-like compared with Klarna's: Medium
Weak brand recall, with lapsed users citing low presence at checkout: Medium
6. Merchant Alignment

Merchants are comfortable with Riverty at checkout and report good conversion, but they are wary of a card that sends customers elsewhere. Their stated conditions for support are clear: incremental customers or repeat orders, a transparent cost, and measurable gains in basket size or returns. Pilot participants did not mention merchant offers unprompted, so there is currently no evidence that the card strengthens merchant relationships.

Risk of customer leakage to other merchants through a card, raised by an SME owner: High
No evidence yet of incremental sales, larger baskets or fewer returns, which an enterprise retailer requires before engaging: High
Unanswered question of acceptance cost for SME merchants: Medium
7. Credit Risk and Governance

The segment most attractive to Riverty, heavy multi-provider users, is also where defaults are most likely to concentrate. Internal risk stakeholders are cautious that a card could make it easier to spend more across more merchants, and they signal that launch pace is constrained by credit policy requirements. This sets a boundary on how quickly the proposition can scale.

Default concentration risk among multi-provider heavy users: High
Credit policy readiness as a constraint on launch pace: High
Minor Technical Debt

Stretched card logo on tablet layouts (Low); credit limit display rounded down to the nearest €10 (Low).

Cross-Cutting Observation

Four of the seven themes (payment reliability, refund integrity, visibility and activation) concern whether the card delivers what it promises. The remaining three (positioning, merchants and risk) concern whether the promise is worth making and can be scaled. The data suggests the first set must hold before the second can be tested meaningfully.

Caveats: The pilot sample is 12 participants and the interview set is small, so counts indicate direction only. Severity ratings for non-bug items (positioning, merchants, risk) are my judgement, applied to keep one scale across the summary. Some findings conflict, notably the appetite for in-store use (Felix) versus card clutter (Kai), and I have presented both rather than resolving them.
- **Did the AI catch the specific moment of misery / pain point you found in Step 1?:** Partly but not fully.
- **Did it smooth over a critical frustration into a generic bullet point?:** generic bullet points
- **Did the AI try to suggest features or a roadmap despite the constraints?:** no
- **Logic leak / hallucination #1 (e.g., “AI suggested a new search bar feature, roadmap leak”):** _(not filled in)_
- **Logic leak / hallucination #2:** _(not filled in)_
