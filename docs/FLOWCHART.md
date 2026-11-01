# Master decision flowchart — 2024 CLE 300 Cabriolet cover

**As of:** 2026-11-01 · **Owner:** vehicle owner · **Goal:** buy an outdoor cover only if it clears fit, roof/paint safety and real returnability gates.

## End-to-end flow: arrows show sequential dependencies; branches run in parallel

\`\`\`mermaid
flowchart LR
  A([Start: CLE A236 cover search]) --> B[Confirm 2024 CLE 300 4MATIC Cabriolet A236, parking type, outdoor exposure]
  B --> C[Record mandatory 15+ days used outdoors / FULL refund with no fees]
  C --> S{Launch 5 streams IN PARALLEL}

  subgraph P1["Parallel 1 — Seller refund terms"]
    direction TB
    R1[Contact Coverland / iCarCover / Amazon listing seller / Coverking / other shortlisted sellers]
    R2[Ask in writing: can it be fitted and used outdoors 15+ days, then returned for 100% of total paid?]
    R3[Get fee, shipping, packaging, deadline and exception terms in writing]
    R1 --> R2 --> R3
  end

  subgraph P2["Parallel 2 — Fit and top safety"]
    direction TB
    F1[Ask each maker: exact A236 Cabriolet pattern? NOT C236 Coupe]
    F2[Ask about fabric soft-top contact, paint liner, mirror pockets, straps and trim]
    F3[Confirm roof closed, AIRCAP stowed; measurement & fit photos]
    F1 --> F2 --> F3
  end

  subgraph P3["Parallel 3 — Quality and protection"]
    direction TB
    Q1[Compare abrasion risk, breathability, water resistance, UV protection]
    Q2[Check wind retention, winter suitability, drying and cleaning instructions]
    Q3[Read independent owner reviews; flag generic rating claims]
    Q1 --> Q2 --> Q3
  end

  subgraph P4["Parallel 4 — Pricing and speed"]
    direction TB
    P1A[Price direct seller, marketplace and eligible local stores]
    P2A[Check stock, delivery in NJ, taxes, returns freight, discounts]
    P3A[Compute full landed cost + expected return loss]
    P1A --> P2A --> P3A
  end

  subgraph P5["Parallel 5 — Real-world parking constraints"]
    direction TB
    O1[Check driveway/street permission to cover car, plate visibility and access]
    O2[Ask parking host or local parking authority only if applicable]
    O3[Compare no-cover / better parking alternative by dollars and damage risk]
    O1 --> O2 --> O3
  end

  S --> R1
  S --> F1
  S --> Q1
  S --> P1A
  S --> O1

  R3 --> G{All written evidence collected?}
  F3 --> G
  Q3 --> G
  P3A --> G
  O3 --> G

  G -- No --> HOLD[Pending: log unanswered questions and follow up; do not purchase]
  HOLD --> G
  G -- Yes --> H{A236 fit, exterior safety and parking permission confirmed?}
  H -- No --> X[Reject cover or resolve fit/parking blocker]
  X --> S
  H -- Yes --> I{Seller explicitly allows 15+ days REAL use and FULL refund without deductions?}
  I -- No --> J{Relax return requirement?}
  J -- No --> K[No qualifying purchase: keep searching / use alternative parking]
  K --> S
  J -- Yes --> V[Record conscious return-cost exception and compare expected cost]
  I -- Yes --> V
  V --> W[Score products: return certainty, fit, protection, cost, speed]
  W --> Y{One candidate clears minimums and wins on value?}
  Y -- No --> S
  Y -- Yes --> Z[Save listing, written approval, policy screenshot and final total BEFORE order]
  Z --> AA[Order; record payment, delivery and return-by dates]
  AA --> AB[On arrival: inspect condition, SKU, size, straps, liner; photograph]
  AB --> AC{Right product and acceptable before use?}
  AC -- No --> AD[Initiate wrong/defective item remedy immediately]
  AC -- Yes --> AE[Install only on clean, dry, cool vehicle; secure in low wind]
  AE --> AF[Test fit, roof contact, wind motion, water behavior; inspect paint]
  AF --> AG{Safe and worth keeping?}
  AG -- Yes --> AH([Keep cover and log maintenance intervals])
  AG -- No --> AI[Initiate return within confirmed written deadline]
  AI --> AJ[Track label, carrier scan, refund, deductions]
  AJ --> AK{Full agreed refund received?}
  AK -- Yes --> AL([Close: refundable test completed])
  AK -- No --> AM[Escalate to merchant support with written terms, then marketplace/payment dispute if warranted]
  AM --> AJ
\`\`\`

## Priority path
1. **Today:** confirm vehicle variant and where the car will actually sit. Send the same fit + used-return questions to merchants simultaneously.
2. **When replies arrive:** eliminate any seller that will not unequivocally confirm full refund after **15+ days of outdoor use**. Listing-level policy beats a broad marketing statement.
3. **Only if an exception is approved:** separately consider unused-return-only custom covers.
4. **Before payment:** document final cart and return terms; confirm delivery timeline and buyer protection.
5. **After delivery:** perform safe staged inspection and monitor exact refund deadline.

**Important:** A waterproof claim alone does not establish breathability or suitability against a convertible fabric roof; verify both. Do not claim scratches or roof damage are insured or warranted without written confirmation.
