# AI Usage & Judgment Report

## AI Tools Utilized

1.  **ChatGPT / Claude:** Rapid drafting of RICE prioritization matrix
    and stakeholder one-pagers.
2.  **Notion AI:** Structuring Markdown documentation and formatting
    user stories.

## Prompts & Iterations

### Prompt 1 --- Data Analysis

> Analyze a loan funnel where 12,400 are invited, 3,100 start, 2,050
> complete KYC, 1,890 get offers, 640 accept, 610 disburse, and default
> rate is 14% vs 6% target. Where is the problem?

**Output:** Highlighted onboarding drop-off and high default rate.

### Prompt 2 --- Backlog Prioritization

> Generate 10 backlog items for a micro-lending app and rank them using
> RICE.

**Output:** Provided standard generic features (e.g., UI redesign, dark
mode, chat support).

## Critical AI Errors Caught & Corrected

### 1. Misreading Funnel vs. Credit Risk Constraint

-   **The AI Error:** Initial AI drafts suggested launching a
    mass-marketing campaign and removing KYC friction to fix
    top-of-funnel conversion without addressing the default rate.
-   **The Catch:** Pushing more users through an uncalibrated
    underwriting engine with a 14% default rate would amplify financial
    losses exponentially.
-   **The Fix:** I re-anchored the prompt to prioritize underwriting
    risk control and collection mechanics over conversion volume until
    default rates hit the 6% target.

### 2. Recommending Illegal / Non-Compliant Features

-   **The AI Error:** AI suggested automatic balance sweeps from
    external bank accounts without requiring user mandate authorization.
-   **The Catch:** Unauthorized direct debit violates Central Bank of
    Nigeria (CBN) consumer protection regulations.
-   **The Fix:** Replaced the item with compliant NIBSS Direct Debit
    Mandates & Card Tokenization.
