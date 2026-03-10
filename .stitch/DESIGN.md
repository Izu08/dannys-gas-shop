# Design System: Dannys Gas Shop Redesign
**Project ID:** [TBD]

## 1. Visual Theme & Atmosphere
The design is **Trustworthy & Modern**. It prioritizes clarity and ease of use for a service-based mobile app. The atmosphere is spacious and clean, using ample whitespace to reduce cognitive load. It feels like a premium utility service—reliable, fast, and accessible.

## 2. Color Palette & Roles
- **Royal Service Blue (#1d4ed8):** Primary brand color. Used for primary actions, branding, and key interface highlights. It evokes trust and professionalism.
- **Eco Trust Green (#10b981):** Secondary accent color. Used for refills, success states, and the WhatsApp button to signify growth and safety.
- **Cloud White (#ffffff):** Main background color. Keeps the interface clean and bright.
- **Slate Gray (#1f2937):** Primary text color. High contrast for readability.
- **Whisper Gray (#f3f4f6):** Surface/Section background color. Used to differentiate cards and sections softly.

## 3. Typography Rules
- **Sans-Serif Font Family:** Inter or Outfit.
- **Headers:** Bold (700) or Extra Bold (800). Large and impactful.
- **Body:** Regular (400) for clean, effortless reading.
- **Buttons:** Bold (600) for clear call-to-actions.

## 4. Component Stylings
* **Buttons:** 
    - **Primary:** Generously rounded (12px or pill-shaped). Bold blue background with white text.
    - **WhatsApp Button:** Pill-shaped with a vibrant green background and a white WhatsApp icon.
* **Cards/Containers:** 
    - **Geometry:** Rounded corners (16px).
    - **Shadows:** Soft, diffused shadows (4-8px blur) to create a sense of floating layers.
    - **Background:** White (#ffffff) against a light gray background.
* **Inputs/Forms:** 
    - **Geometry:** Rounded-lg (10px).
    - **Border:** Subtle 1px light gray, changing to blue on focus.

## 5. Layout Principles
- **Mobile-First:** Single column layout optimized for thumb-reach.
- **Spacing:** Large 24px-32px gutters between sections.
- **Hierarchy:** Clear headers followed by simple descriptions and large, tappable action areas.

## 6. Design System Notes for Stitch Generation
- Use a white background with a clean, modern royal blue (#1d4ed8) as the primary accent.
- Use rounded-2xl (16px) for cards and rounded-xl (12px) for buttons.
- Implement clear sections with spacious padding (py-12).
- Use soft shadows (shadow-sm or shadow-md) on product cards.
- Buttons should be large and easy to tap on mobile.
- Incorporate a floating WhatsApp button in the bottom right.
