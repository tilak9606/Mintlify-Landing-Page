# Mintlify Landing Page (Clone)

This is implementation of a Mintlify-style landing page built using **HTML and CSS**.  

<img width="1919" height="993" alt="Screenshot 2026-02-03 000744" src="https://github.com/user-attachments/assets/57cef390-4330-49ce-8125-795b8f6fffad" />


## Page Structure & Sections

### 1. Navigation Bar (`<nav>`)
**Purpose:**  
Primary navigation and call-to-action entry point.

**Contents:**
- Logo (SVG)
- Navigation links: Resources, Documentation, Customers, Blog, Pricing
- Action buttons:
  - **Contact sales**
  - **Start for free**

**Behavior:**
- Designed to support blur / style change on scroll
- Uses flexbox for alignment


### 2. Hero Section (`.main-header`)
**Purpose:**  
First impression and value proposition.

**Elements:**
- “NEW” announcement pill
- Main headline: *The intelligent Knowledge Platform*
- Supporting subtitle
- Email input with “Start now” CTA

**Design Notes:**
- Large typography
- Centered layout
- High contrast for CTA


### 3. Hero Image & Trust Logos (`.img-section-start`)
**Purpose:**  
Visual credibility and brand trust.

**Contents:**
- Hero product illustration
- Logos of trusted companies (Anthropic, Coinbase, Microsoft, etc.)

### 4. AI Information Section (`.AI-info`)
**Purpose:**  
Explain product value in the AI era.

**Subsections:**
- Intro text (`.text-ai`)
- AI feature cards (`.card-ai`)
  - LLMs.txt & MCP
  - Self-updating knowledge agent


### 5. Assistant Section (`.assistant`)
**Purpose:**  
Highlight AI-powered user assistance.

**Design:**
- Dark background
- High-contrast white text
- Focused messaging


### 6. Enterprise Section (`.enterprice`)
**Purpose:**  
Target enterprise customers.

**Includes:**
- Enterprise headline
- CTA: *Explore for enterprise*
- Feature cards:
  - Partnership & migration
  - Compliance & security


### 7. Company Stories (`.company-stories`)
**Purpose:**  
Social proof from well-known companies.

**Elements:**
- Company logos
- Interactive company buttons


### 8. Customers Section (`.customers`)
**Purpose:**  
Case studies and real-world usage.

**Contents:**
- Section heading
- Customer cards
- Story links
- Slider navigation buttons


### 9. Get Started Section (`.get-started`)
**Purpose:**  
Final conversion section.

**Includes:**
- Strong CTA headline
- Buttons:
  - Get started for free
  - Get a demo
- Supporting cards:
  - Pricing
  - Quickstart


### 10. Footer (`.more`)
**Purpose:**  
Secondary navigation and branding.

**Contents:**
- Logo and social icons
- Footer link groups:
  - Explore
  - Resources
  - Documentation
  - Company
  - Legal
- System status
- Theme toggle buttons
- Copyright


## Fonts

This project uses **Google Fonts**:

```css
font-family: "Roboto", sans-serif;
font-family: "Open Sans", sans-serif;
