# Product Requirements Document (PRD)

## Studioforma — Brand & Product Website

---

## 1. Project Overview

**Product:** Marketing and catalogue website for Studioforma  
**Client:** Abhiroop Agarwal, Director, Studioforma Industries  
**Builder:** Arav Agarwal  
**Goal:** Establish a premium digital brand presence for
Studioforma to drive awareness, showcase products, and
generate qualified leads from architects, designers,
builders, and homeowners.

**Brand statement (hero headline):**
"Precision-crafted surfaces, engineered for modern spaces."

---

## 2. Problem Statement

Studioforma currently has no standalone digital presence.
Potential clients including architects, interior designers,
builders, OEMs, and homeowners have no way to discover the
brand, explore the product range, or make contact online.
This website solves that by creating a first point of
contact that reflects the premium, precision-crafted
positioning of the brand.

---

## 3. Target Users

| User Type                       | Need                                                               |
| ------------------------------- | ------------------------------------------------------------------ |
| Architects & Interior Designers | Browse product range, download catalogues, assess fit for projects |
| Builders & OEMs                 | Understand manufacturing capability, request bulk inquiry          |
| Homeowners                      | Discover products, get inspired, contact for renovation            |

---

## 4. Goals and Success Metrics

**Primary goal:** Visitor explores catalogues and submits
contact information or reaches out directly.

**Success looks like:**

- Visitor lands on homepage and clicks into a product category
- Visitor downloads or views a catalogue
- Visitor submits the contact form or clicks the inquiry CTA
- Site loads and displays correctly on mobile devices
- Lighthouse accessibility score of 80+

---

## 5. Pages and Content

### 5.1 Home (index.html)

- Vertical navbar: Home, About Us, Catalogues, Experiences,
  Factory, Projects, Contact Us
- Full-width hero with product image and brand headline
- Product highlights row: Almonds, Textures, Pavilion
- Brief About section with link to About page
- Footer with contact link and copyright

### 5.2 About Us (about.html)

- Company story and founding vision
- What Studioforma makes: modular furniture surfaces
  and panels
- Manufacturing capability and precision engineering
- Link to Factory page

### 5.3 Catalogues (catalogues.html)

- Grid of product catalogues
- Each catalogue has cover image, name, and download
  or view button
- Content pending: catalogue PDFs from client

### 5.4 Experiences (experiences.html)

- Showcase of finishes, textures, and material stories
- Full-bleed imagery with labels
- Categories: Almonds, Textures, Pavilion and others

### 5.5 Factory / Plant (factory.html)

- Manufacturing facility showcase
- Images from mother company website
- Brief copy on production capability and quality standards

### 5.6 Case Studies / Projects (projects.html)

- Grid of completed installations
- Each project: image, location, product used
- Content pending: project photography from client

### 5.7 Contact Us (contact.html)

- Inquiry form: Name, Company, Role, Email, Phone, Message
- All fields required except Message
- Company location and details
- No backend required for MP1 -- form uses HTML
  validation attributes only

---

## 6. Design Requirements

| Property     | Specification                                   |
| ------------ | ----------------------------------------------- |
| Color scheme | Black and white only, no exceptions             |
| Typography   | Signature/editorial font, strong hierarchy      |
| Layout       | Minimalistic, generous whitespace, no clutter   |
| Imagery      | High-contrast, full-bleed where possible        |
| Feel         | Premium, modern, futuristic, technology-forward |

**Inspiration:**

- wesmarcdoors.com -- product depth, factory showcase,
  futuristic feel
- spacewood.in -- product-first navigation, image quality,
  smooth UX. Avoid: dense content, low premium appeal

---

## 7. Technical Requirements

- Semantic HTML5 only
- External CSS stylesheet: css/styles.css
- No inline styles, no JavaScript for MP1
- All images in images/ folder
- Responsive: mobile-friendly layout
- Deployed on GitHub Pages
- Favicon included
- Consistent navigation across all pages

---

## 8. Content Status

| Content                  | Status                          |
| ------------------------ | ------------------------------- |
| Factory and plant images | Available (mother company site) |
| Product catalogues       | Pending from client             |
| Project photography      | Pending from client             |
| Logo files               | Pending from client             |
| Brand copy               | To be written based on proposal |

---

## 9. Out of Scope (for MP1)

- Backend or database
- E-commerce or payment
- JavaScript interactivity
- CMS or content management
- User accounts or login

---

## 10. Timeline

| Milestone                 | Date      |
| ------------------------- | --------- |
| Proposal and PRD complete | 6/11      |
| HTML structure complete   | 6/11      |
| CSS and styling complete  | 6/11      |
| Deployed and live         | 6/12      |
| Final submission          | 6/12      |
| Client feedback + polish  | 6/13–6/14 |
| MP1 Showcase              | 6/15      |
