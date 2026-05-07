# FreshDine

FreshDine is a front-end web product prototype for personalized meal planning, recipe exploration, and checkout simulation.  
It is positioned as a practical concept for users who want healthier eating with less planning overhead.

The repository demonstrates how product thinking, UX flow design, and implementation can be combined into an end-to-end user journey: discover meals, personalize preferences, save favorites, manage basket, and place an order.

---

## Product Overview

FreshDine addresses a common user problem: planning meals consistently is difficult when users have limited time, dietary preferences, or low confidence in recipe selection.

The product experience is designed to reduce decision fatigue by offering:
- Curated recipes with ingredients, instructions, and nutrition details
- A meal calendar experience with daily selections
- User profile and preference capture to personalize the journey
- Favorites, basket management, and order flow simulation

Current implementation status: a static HTML/CSS/JavaScript prototype with interactive UI behavior on key pages.

---

## Problem Statement

Target users often struggle with:
- Deciding what to cook during busy weeks
- Matching meals to diet, goals, and restrictions
- Turning recipe inspiration into actionable shopping and checkout steps

FreshDine solves this by organizing meal discovery and planning into a guided flow that connects profile preferences to concrete meal and purchase actions.

---

## Target Audience

- Students managing time, budget, and nutrition
- Working professionals seeking low-friction weekly meal planning
- Users with dietary preferences (for example vegan, vegetarian, halal, gluten-free, dairy-free)
- Households that need a simple routine for recipe selection and repeat ordering

---

## Core Value Proposition

- **Personalized planning:** capture profile, dietary needs, and goals in one place
- **Actionable discovery:** move from recipe browsing to planning and cart actions
- **Simple weekly structure:** use a meal calendar view to reduce planning complexity
- **Conversion-oriented flow:** transition from favorites and basket to checkout with minimal friction

---

## Product Features (Implemented in Repository)

### 1. Marketing and Landing Experience
- Hero section with product promise and call-to-action
- “How It Works” sequence for user onboarding
- Popular meal plan cards and social proof/testimonials
- Timed support/help prompts and special-offer banner logic

Primary file:
- `Homepage.html`

### 2. Account Entry and Profile Capture
- Registration and login form entry page
- Profile setup page with extensive user data fields:
  - personal details
  - dietary preferences
  - goals
  - box type
  - allergies/restrictions
  - optional bio

Primary files:
- `user.html`
- `profile.html`
- `profile setting.html`

### 3. Recipe Discovery and Content Detail
- Multi-card recipe catalog
- Expand/collapse details per recipe
- Structured recipe information:
  - ingredients
  - cooking steps
  - nutrition metrics

Primary file:
- `recipe discovery.html`

### 4. Meal Planning and Recommendation View
- Weekly meal calendar cards
- Per-meal macro information and nutrition highlights
- “Add to Favorite” actions
- Supporting “For You” recommendation carousel

Primary file:
- `meal planning.html`

### 5. Favorites and Basket Workflow
- Favorites grid with filtering controls (sort/category/status)
- Add-to-basket interactions
- Basket page with:
  - quantity adjustments
  - item removal
  - subtotal/discount/total summary
  - checkout entry point

Primary files:
- `favourite.html`
- `shopping basket.html`

### 6. Checkout and Order History Simulation
- Four-step checkout flow:
  1. shipping address
  2. shipping method
  3. payment
  4. review and place order
- Promo code input and support panel
- Order history page with reorder actions and delivery/pickup context

Primary files:
- `checkout.html`
- `order history.html`

### 7. Support and Brand Context
- Contact form with success-state interaction
- About page with mission, quick facts, and team presentation

Primary files:
- `Contact us page.html`
- `About Us.html`

---

## User Journey at a Glance

1. User lands on `Homepage.html`
2. User signs up or logs in (`user.html`) and configures profile (`profile.html`)
3. User explores recipes (`recipe discovery.html`)
4. User plans meals (`meal planning.html`) and saves favorites (`favourite.html`)
5. User reviews basket (`shopping basket.html`)
6. User completes checkout (`checkout.html`)
7. User revisits previous orders (`order history.html`)

---

## Repository Structure

This project is organized as a static front-end prototype.

- Core pages: top-level `.html` files
- Shared styles: `freshdine.css` plus page-local style blocks
- Visual assets: `Pictures/` and image files in repository root
- No backend services or API integrations in current version

---

## Technology Stack

- HTML5
- CSS3
- Vanilla JavaScript (DOM interaction and UI behavior)
- Git/GitHub for version control and collaboration

---

## How to Run Locally

1. Clone the repository
2. Open the project folder
3. Start by opening `Homepage.html` in your browser
4. Navigate through linked pages to test the product flow

No build step or dependency installation is required for the current prototype.

---

## Product Management Perspective

This prototype demonstrates core product communication capabilities:

- Clear value articulation (from problem to feature set)
- End-to-end user flow definition across multiple touchpoints
- Feature decomposition by lifecycle stage (acquisition, engagement, conversion, retention)
- Practical UX implementation aligned to a target audience with distinct dietary needs

It can serve as:
- a portfolio-ready product case artifact
- a basis for stakeholder demos
- a specification baseline for future engineering expansion

---

## Current Limitations

- Static prototype: no persistent authentication, database, or order backend
- Some navigation references are inconsistent (for example `contact.html`, `about.html`, `favorite.html`, and `recipe-discovery.html` appear in specific files)
- No automated tests or CI checks are defined for this prototype
- Payment and checkout are simulation-only

---

## Suggested Next Product Iteration

- Normalize navigation routes and naming across all pages
- Add backend services for authentication, profile storage, and order persistence
- Introduce recommendation logic based on profile and behavior
- Add analytics instrumentation for key funnel events
- Add responsive QA, accessibility audit, and production-grade validation

---

## Visuals

Use this section to insert product screenshots for portfolio and stakeholder communication.

- [Image Placeholder: Homepage experience screenshot]
- [Image Placeholder: Meal planning experience screenshot]
- [Image Placeholder: Checkout flow screenshot]

Replace each placeholder with final image links when assets are ready.

---

## License

No license file is currently defined in this repository.  
Add a project license if you intend to distribute or reuse this work publicly.
