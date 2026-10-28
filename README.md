# PrecisionCore website

A responsive, four-page website based on the approved PrecisionCore wireframe. Written exclusively in HTML5, CSS, and local SVG, JPEG, and WebP image assets. No JavaScript, build tools, dependencies, external fonts, or installation required.

## Open the website

Extract the ZIP, then open `precisioncore-website/index.html` in any modern browser. Keep the folder structure intact. All four pages work directly from disk. You can also upload the contents of this folder to any static web host.

## Files

- `index.html` — full-screen hero, CSS-only carousel, scroll cue, company introduction.
- `about.html` — company overview, mission, vision, main goal, four uploaded team portraits with name and role placeholders.
- `products.html` — six component/application cards and reliability section.
- `contact.html` — contact placeholders and a demo enquiry form.
- `assets/css/styles.css` — shared responsive layout, carousel, form, mobile and print styles.
- `assets/images/precisioncore-logo.png` — supplied horizontal PrecisionCore logo, used in every header and footer.
- `assets/images/precisioncore-emblem.png` — supplied blue microchip emblem, used on the homepage and as the favicon.
- `assets/css/theme.css` — shared gray, blue, and white brand theme.
- `assets/images/integrated-circuit.svg` — original component illustration.
- `assets/images/sensor.svg` — original sensor illustration.
- `assets/images/team-member-01-circle.svg` through `team-member-04-circle.svg` — circular portrait assets used on About Us.
- `assets/images/team-member-01.jpg` through `team-member-04.jpg` — four uploaded team photographs, in upload order.
- `assets/images/team-placeholder.svg` — optional generic fallback portrait.
- `README.md` — these instructions.

## Editing

All four pages contain the same header and footer HTML. Update both in every HTML file to keep them consistent. Colours, spacing, and container width are defined as variables at the top of the stylesheet. Update team names and roles, contact details, and product illustrations when final assets are available. Portraits use self-contained circular SVG image assets with transparent corners and embedded original photographs. The circle is clipped inside each SVG, independently of CSS. Original JPEG files are preserved.

The three social icons currently link to the LinkedIn, Facebook, and Instagram homepages. Replace their URLs with PrecisionCore's actual social profiles; their accessible labels identify them as placeholder links.

## CSS-only carousel

The homepage uses three native radio inputs and CSS sibling selectors. Click the dots or arrows to change slides; keyboard users can Tab to the radio group and use arrow keys. Slides do not move automatically. The scroll cue links to the next section on the same page. No scripts are used.

## Enquiry form

The form is explicitly a static demo. Required fields and email syntax use native HTML validation. The preview button navigates to a CSS `:target` notice saying no enquiry was sent. Inputs intentionally have no `name` attributes, so their values are not submitted or included in the URL. No values are saved. Navigation may clear entered fields.

Before enabling real enquiries, supply a form-service or server endpoint, add appropriate `name` attributes, use `method="post"`, and update the demo notice and button. HTML and CSS alone cannot send email or securely store submissions.

## Content

Mission: Manufacture dependable integrated circuits and sensors for industrial equipment.

Vision: Help industries operate with greater precision, safety, and efficiency.

Goal: Deliver durable components that minimize equipment failures and downtime.

Product cards represent supplied component categories and application areas, not verified product models or technical specifications. No certification, performance, customer, or manufacturing claims have been added.

## Brand theme

The theme follows the supplied gray, blue, and white palette. Dark gray headers and footers display the supplied transparent horizontal logo. Blue buttons, links, and accent rules pair with white content surfaces and pale gray backgrounds. Uploaded logo files are used without altering their pixels. The team portraits remain circular SVG assets. The site remains HTML5 and CSS only.

## Generated website media

Six AI-generated WebP images replace the product-category placeholders. The Home page has a approximately seven-second silicon wafer inspection film, and Products has a approximately seven-second industrial sensor film. Videos use native HTML controls with poster images and do not autoplay. They are streamed from their supplied HeyGen hosted playback URLs; the images are stored in this repository. Playback depends on those external URLs remaining accessible. The generated scenes are illustrative and do not document actual PrecisionCore products or facilities. No imagery or footage was copied from the reference websites.

References for subject direction: https://www.a-star.edu.sg/ime and https://continental.sg/ .

Additional CSS applies user-select restrictions to all descendants; versioned stylesheet links refresh cached styles. HTML/CSS can discourage ordinary selection and dragging but cannot enforce complete copy protection.
