# Lingxing Yao Personal Site Redesign Design

## Goal

Redesign `YaoLingxing.github.io` as a simple, academic, educational personal website for Lingxing Yao. The new site will incorporate durable content from the legacy University of Akron pages at `www.math.uakron.edu/~lyao`, while removing placeholder material from the current untracked `index.html`.

## Approved Direction

Use a single-page academic profile with section anchors:

- About
- Research
- Selected Publications
- Teaching
- Contact

The site should be static, easy to maintain, and appropriate for GitHub Pages. It should avoid framework dependencies and use plain HTML, local CSS, and a small amount of optional vanilla JavaScript only if needed.

## Content

The page will use verified and legacy content:

- Name: Lingxing Yao.
- Role: Associate Professor, Department of Mathematics, The University of Akron.
- Research themes: mathematical modeling, numerical simulation, scientific computation, biological systems, material sciences, liquid crystal and viscoelastic materials.
- Legacy research project areas: cell motility, polyelectrolyte hydrogels, numerical algorithms and simulation, blood clotting transport methods, and complex fluids.
- Selected publications from the legacy research page:
  - "On the energy efficiency of cell migration in diverse physical environments", PNAS, 2019.
  - "Rhythmomimetic Drug Delivery: Modeling, Analysis, and Numerical Simulation", SIAM Journal on Applied Mathematics, 2017.
  - "A numerical method for osmotic water flow and solute diffusion with deformable membrane boundaries in two spatial dimension", Journal of Computational Physics, 2017.
  - "Simulations of Chemical Transport and Reaction in a Suspension of Cells I: An Augmented Forcing Point Method for the Stationary Case", International Journal for Numerical Methods in Fluids, 2012.
- Teaching history from the legacy teaching page: Introduction to ODE, Advanced Engineering Mathematics I, and Calculus I.
- Contact details from the legacy contact page:
  - Email: lyao@uakron.edu
  - Phone: 330-972-7402
  - Office: CAS 256
  - Mailing address: The University of Akron, Department of Mathematics, Akron, OH 44325-4002

## Visual Design

The design should be restrained and educational:

- Light background with white content regions.
- Serif headings for an academic tone.
- Sans-serif body text for clarity.
- Muted navy and slate accents, with limited color use.
- No decorative gradients, animations, or marketing-style hero treatment.
- Compact cards for research areas and publications, with enough whitespace for readability.
- Header navigation should be simple text links to page sections.

## Responsive Behavior

The page must work on desktop and mobile:

- Header navigation wraps cleanly on narrow screens.
- Hero/about and contact content stack on mobile.
- Research and publication cards collapse to one column on mobile.
- Text must not overflow buttons, cards, or narrow columns.

## Accessibility and Maintenance

- Use semantic HTML sections, headings, and labels.
- Provide visible keyboard focus states.
- Use descriptive link text.
- Keep all styles in the page or local assets so GitHub Pages can serve the site without a build step.
- Do not publish preview helper files from `.superpowers/`.

## Verification

Before completion:

- Preview locally in a browser.
- Verify anchor navigation and responsive layout.
- Check that the page contains no placeholder names such as "Evelyn Reed" or generated-template language.
- Confirm `index.html` is tracked for GitHub Pages publishing.
