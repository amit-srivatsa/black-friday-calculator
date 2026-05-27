# Black Friday Net-Revenue Calculators

An interactive suite of modeling tools designed for accommodations partners (such as Booking.com hosts) to evaluate the financial viability of running a Black Friday promotion. 

When offering steep promotions, partners are often hesitant due to the steep margins lost after stacking multiple discounts and commissions. These tools reframe the math to focus on **incrementality**—determining how many empty nights need to be filled to make the promotion net-positive.

## Live Demo
Check out the live deployment here: **[https://black-friday-revenue-calc.vercel.app](https://black-friday-revenue-calc.vercel.app)**

---

## What's Inside

### 1. Guided Calculator (`guided.html`)
A structured, step-by-step journey that calculates exactly where the revenue goes:
- **Your Numbers**: Input your rack rate, Black Friday discount percentage, standard commission, and Genius loyalty tier discount.
- **The Stacking Breakdown**: A clear, itemized ledger showing the progression of stacked discounts.
- **Break-Even Gauge**: A visual SVG meter showing the exact percentage of bookings that must be incremental (filling otherwise empty nights) to break even.
- **Revenue Impact**: A visual comparison of net revenue generated with vs. without the deal.

### 2. Side-by-Side Ledger (`editorial.html`)
An elegant, editorial-style presentation of the same math, contrasting two different ways to read the deal:
- **Left Panel (The Partner's Fear)**: Highlights the raw net payout per booked night, showing exactly how much margin is given up on a single transaction.
- **Right Panel (The Incrementality Flip)**: Reframes the equation across 100 room-nights, contrasting the revenue gained from empty nights with the margins given up on nights that would have sold anyway.

---

## Key Concepts Modeled
* **Stacked Promotions**: Visualizes how Vercel/OTA promotions stack (Rack Rate ➔ BF Discount ➔ Commission ➔ Genius).
* **Cannibalization vs. Incrementality**: Differentiates between nights you would have sold at full price anyway (cannibalization) and nights that would have remained empty (incremental).
* **Break-Even Threshold**: Calculates the percentage of new bookings required to cover the discount margin.

---

## Technical Details
- **Stack**: Self-contained HTML5, CSS3, and modern ES6 JavaScript.
- **Dependencies**: None. Pure vanilla implementation with SVG-based visualizations and responsive layout designs.
- **Fonts**: Outfit, Manrope, Hanken Grotesk, and Fraunces served via Google Fonts.

---

*Created by Amit Srivatsa as part of the interview process for Lead, Content Strategy in the DPE team.*
