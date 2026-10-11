# Website component integration

This repository contains source fragments and images for the existing [FF Bio Code website](https://ffbiocodes.com/). It is not a standalone web application or the Android app repository. The [Android APK releases](https://github.com/ayan-act/FF-Bio-Code/releases/latest) are maintained separately.

## Component inventory

| File | Intended page or role |
| --- | --- |
| `About-us.html` | [About Us](https://ffbiocodes.com/about-us/) page component |
| `Contact-Us.html` | [Contact Us](https://ffbiocodes.com/contact-us/) page component and form |
| `Disclaimer.html` | [Disclaimer](https://ffbiocodes.com/disclaimer/) page component |
| `Privacy-Policy.html` | [Privacy Policy](https://ffbiocodes.com/privacy-policy/) page component |
| `Terms-Conditions.html` | [Terms & Conditions](https://ffbiocodes.com/terms-conditions/) page component |
| `FF Bio Code Advertise With Us` | [Advertise With Us](https://ffbiocodes.com/advertise-with-us/) page component and inquiry form |
| `FF Bio Code Rating Reviews` | [Reviews](https://ffbiocodes.com/reviews/) page component |
| `FF Bio Code Developer` | Reusable developer/author section |
| `FF Bio Code Preview.html` | Bio preview gallery component |
| Six `*Profile.png` files | Gallery/profile artwork kept in the root for existing references |

The filenames without extensions are retained to avoid breaking existing references. Do not rename or move these files without checking every consumer first.

## Integration boundaries

- Add each component only to its intended page or template. Preserve the site's existing header, footer, navigation, forms, and working interactions.
- Several fragments include `<title>`, description, and Open Graph tags. A WordPress theme or SEO plugin may also emit these tags. In the deployed HTML document, verify that there is one intended title, one canonical URL, one main heading, and consistent social metadata. Keep page-level metadata in the site's head-management system when possible.
- The Contact and Advertise forms submit to FormSubmit endpoints. Test successful submission, validation, spam controls, confirmation delivery, and privacy disclosures before deploying form changes. Do not put private credentials in public source.
- The preview gallery loads external images and a Three.js module from a CDN. Test its fallback, loading behavior, and mobile performance on the production page.
- Public profile images are source assets. Check image dimensions, alternative text in their rendered context, and usage rights before publishing new assets.

## Release checklist

1. Compare the repository fragment with the live page; a GitHub commit does not deploy the website.
2. Test narrow and wide screens, keyboard navigation, visible focus, form validation, and the site theme's light/dark behavior.
3. Confirm each form's real destination and user-facing success/error state.
4. Check the live page's title, description, canonical URL, structured data, and outbound links.
5. Verify that the privacy policy reflects actual form processors, analytics, advertising, and other third-party services.
6. Recheck the component after deployment and keep this repository in sync with the published version.

No application source, signing key, or Android build configuration should be added here unless this repository's scope is explicitly changed.
