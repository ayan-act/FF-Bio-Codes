# FF Bio Code website components

Source fragments and public profile artwork for the [FF Bio Code website](https://ffbiocodes.com/). This repository covers the bio preview gallery, information pages, contact and partnership forms, reviews, and a developer section. The live website is the place to use these components.

**[Visit FF Bio Code](https://ffbiocodes.com/)** · [Browse the components](#components) · [Read integration notes](docs/INTEGRATION.md) · [Get the Android app](https://github.com/ayan-act/FF-Bio-Code/releases/latest)

## What this repository is

These files are HTML/CSS/JavaScript fragments and image assets intended for the existing site, including WordPress page or Custom HTML integration. They are not a complete standalone website and this repository does not contain the Android app source or APK. Android releases are available in the separate [FF-Bio-Code repository](https://github.com/ayan-act/FF-Bio-Code).

## Components

| Source | Live destination or role |
| --- | --- |
| [About-us.html](About-us.html) | [About Us](https://ffbiocodes.com/about-us/) |
| [Contact-Us.html](Contact-Us.html) | [Contact Us](https://ffbiocodes.com/contact-us/) and its inquiry form |
| [Disclaimer.html](Disclaimer.html) | [Disclaimer](https://ffbiocodes.com/disclaimer/) |
| [Privacy-Policy.html](Privacy-Policy.html) | [Privacy Policy](https://ffbiocodes.com/privacy-policy/) |
| [Terms-Conditions.html](Terms-Conditions.html) | [Terms & Conditions](https://ffbiocodes.com/terms-conditions/) |
| [FF Bio Code Advertise With Us](FF%20Bio%20Code%20Advertise%20With%20Us) | [Advertise With Us](https://ffbiocodes.com/advertise-with-us/) and its inquiry form |
| [FF Bio Code Rating Reviews](FF%20Bio%20Code%20Rating%20Reviews) | [User Reviews](https://ffbiocodes.com/reviews/) |
| [FF Bio Code Developer](FF%20Bio%20Code%20Developer) | Reusable developer/author section |
| [FF Bio Code Preview.html](FF%20Bio%20Code%20Preview.html) | Bio preview gallery component |

The six profile images in the repository root support the gallery and related profile visuals: Asraful, Ayan, Munna, Raj Boss, Saji, and San. Existing filenames and paths are preserved.

## Integration and maintenance

Read [the integration notes](docs/INTEGRATION.md) before placing a fragment into a live page. They cover page metadata, forms, external dependencies, accessibility, and release checks. A repository update does not automatically update the WordPress website.

The Contact and Advertise components use an external form processor. The Preview component loads external images and a Three.js module. Verify these integrations and the [privacy policy](https://ffbiocodes.com/privacy-policy/) against the live site before changing their behavior.

## Related tools and guides

- [FF Name Style generator](https://ffbiocodes.com/ff-name-style/) for styling a nickname rather than a profile bio.
- [Free Fire colour code list](https://ffbiocodes.com/free-fire-colour-code-list-2026/) for bio colour syntax.
- [FF Bio Code Android releases](https://github.com/ayan-act/FF-Bio-Code/releases/latest) for the separate mobile app.

## Support, rights, and attribution

For website questions, use [Contact Us](https://ffbiocodes.com/contact-us/). Repository issues can report source-component problems; do not post private information or account credentials in a public issue.

FF Bio Code is an independent fan-made project and is not affiliated with or endorsed by Garena or Free Fire. Third-party names and trademarks belong to their respective owners. No open-source license file is present; public visibility does not by itself grant reuse rights. Contact the project owner before using these components outside this project.

The intended GitHub description, homepage, and topics are recorded in [repository profile notes](docs/REPOSITORY_PROFILE.md).
