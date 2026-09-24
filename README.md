<a href="https://detailing016.rs/"><img src="media/cover.jpg" alt="Detailing 016, home page on a laptop and a phone" width="100%"></a>

# Detailing 016

One-page site for a car detailing studio in Leskovac, with the full price list for eight vehicle classes.

**[detailing016.rs](https://detailing016.rs/)** · [Case study (in Serbian)](https://svilenkovic.com/radovi/detailing-016) · [Srpski](README.sr.md)

> [!NOTE]
> Client project. The source code belongs to the client and stays in a private repository. This page describes what I built and how.

<table>
  <tr><td><b>Client</b></td><td>Detailing 016</td></tr>
  <tr><td><b>Industry</b></td><td>Car detailing and one-on-one detailing courses</td></tr>
  <tr><td><b>Location</b></td><td>Leskovac, Serbia</td></tr>
  <tr><td><b>Type</b></td><td>One-page website</td></tr>
  <tr><td><b>My role</b></td><td>Design, development, SEO, hosting and maintenance</td></tr>
  <tr><td><b>Stack</b></td><td>PHP, nginx, JSON-LD, AVIF/WebP</td></tr>
</table>

## About the project

Detailing 016 polishes, coats and deep-cleans cars in Leskovac, and the owner also teaches detailing one on one. He wanted a single page that answers what customers usually ask on the phone: what the studio does, what it costs and how to book.

Most of the work went into the price list. It has seven service groups and eight vehicle classes, each with example models, and the polishing table shows two prices per row (with and without ceramic coating). Under 575 px the table turns into labelled price chips stacked under each class, so nothing scrolls sideways on a phone.

## What I built

- The complete price list with a vehicle class guide, readable on a 360 px screen
- A training section with three course packages, also marked up as `Course` structured data
- A contact form that really delivers: SMTP over STARTTLS from a mailbox on the client's domain, with SPF, DKIM and DMARC in place
- Analytics that waits for consent, plus a privacy policy and terms written for this business
- Structured data for the business, services, FAQ and courses; the HTML validator reports zero errors
- Logo in AVIF, WebP and JPEG, with nginx picking the format each browser accepts

## Results

| | Performance | Accessibility | Best practices | SEO |
| :-- | :-: | :-: | :-: | :-: |
| Mobile | 89 | 100 | 100 | 100 |
| Desktop | 99 | 100 | 100 | 100 |

PageSpeed Insights, lab test of the live site, September 2026. Security headers: 6 of 6. HTML validator: no errors. axe accessibility check: no violations. Structured data: `AutomotiveBusiness`, `Course`, `FAQPage`, `Service`.

## Screenshots

<table>
  <tr>
    <td width="68%" valign="top"><img src="media/desktop.webp" alt="Detailing 016, home page on a 1440 px screen"></td>
    <td width="32%" valign="top"><img src="media/mobile.webp" alt="Detailing 016, home page on a phone"></td>
  </tr>
</table>

<img src="media/inner-1.webp" alt="The start of the price list and a guide to vehicle categories">
<sub>The start of the price list and a guide to vehicle categories</sub>

<img src="media/inner-2.webp" alt="Regular maintenance and paint correction with clear coat protection">
<sub>Regular maintenance and paint correction with clear coat protection</sub>

---

<sub>Built by [D. Svilenković](https://svilenkovic.com).</sub>
