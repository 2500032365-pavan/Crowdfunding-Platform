# FundFlow — Crowdfunding Platform (Hackathon Prototype)

A responsive crowdfunding frontend concept built with HTML, CSS and vanilla JavaScript.

## Run the project
1. Extract the ZIP.
2. Open the `FundFlow_Hackathon` folder.
3. Double-click `index.html` or use VS Code Live Server.
4. Internet is required for Google Fonts and the Unsplash campaign photos.

## Features
- Responsive landing page with visual storytelling and motivational quote.
- Explore campaigns with live search and category filters.
- Campaign cards with goals, raised amounts, supporter counts and progress bars.
- Simulated contributions that update campaign totals.
- Create and publish a demo campaign.
- Demo login interaction.
- Local Storage persistence in the browser.
- Real-world inspiration section with links to published Milaap stories.

## Important prototype limitations
This is a frontend-only hackathon prototype. It does not process real payments, verify identities or documents, or provide production authentication. Contributions and new campaigns are simulated and stored in the current browser using Local Storage. For a production build, add a secure backend, database, identity/KYC checks, campaign review, audit trail, payment gateway (for example Razorpay/Stripe where supported), refund/dispute workflows, privacy controls and legal/compliance review.

## Suggested hackathon pitch
**Problem:** People with meaningful causes often struggle to reach supporters and communicate how funds will be used.

**Solution:** FundFlow brings campaign storytelling, discovery, contribution tracking and progress updates into one accessible platform.

**Differentiator to pitch:** Trust-first fundraising — verified organizer identity, document review, transparent fund-use updates and milestone-based reporting (these are proposed next-stage features, not implemented in this frontend demo).

## Real-life inspiration
The Impact section references publicly published Milaap stories:
- Devansh's campaign: Milaap reports that more than 4,700 supporters came together to raise around ₹90 lakh for treatment, rehabilitation and prosthetics.
- A Hyderabad campaign: Milaap's review page describes Vishnu Bodapati raising more than ₹30 lakh from over 1,200 donors for his teacher's family during COVID-19.

These stories are examples of real crowdfunding impact, not FundFlow campaigns. All campaign cards and platform statistics shown on the homepage are illustrative demo data.

## Suggested next upgrades
1. React frontend and Node.js/Express API.
2. MongoDB or PostgreSQL for users, campaigns and donations.
3. Razorpay test-mode payment integration.
4. Organizer verification and admin approval dashboard.
5. Donor receipts, campaign updates and analytics.
6. Fraud reporting, refund flow and audit logs.
