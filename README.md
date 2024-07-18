No, its **_NOT_** a roBOT 🤖, its a 👜 <b>B</b>ag <b>o</b>f <b>T</b>ricks!✨

# **The Bag of Tricks** for Astro's **View Transitions**

The bag of tricks provides extensions & support around Astro's view transitions.

![Build Status](https://github.com/martrapp/astro-vtbot/actions/workflows/run-tests.yml/badge.svg)
[![npm version](https://img.shields.io/npm/v/astro-vtbot)](https://www.npmjs.com/package/astro-vtbot)

A current deployment of tech demos and the documentation can be found at https://events-3bg.pages.dev/

## !!! NEW TRICKS ✨ IN THE BAG 👜 !!!

Deep down at the bottom of the Bag of Tricks, in a hidden inner pocket, there is a secret passage to an ominous machine room. In the machine room stands the [inspection chamber](https://events-3bg.pages.dev/inspection-chamber-demo/first-page/), quietly humming to itself.

See your view transitions like never before: examine all details, reveal, debug, and optimize!

Summon the Inspection Chamber as a component ([&lt;InspectionChamber />](https://events-3bg.pages.dev/library/InspectionChamber/)) or [install The Bag as an integration!](hhttps://events-3bg.pages.dev/library/Installation/#installing-as-an-astro-integration)


## Recently Learned Tricks ##

> Starlight Support: Ever wanted to see what your Starlight site looks like with view transitions enabled? Follow [these steps](https://events-3bg.pages.dev/jotter/starlight/guide/) to get rid of full page loads and make your Starlight site look like a SPA!



## Reusable Components 🧩

- In need for extensions for view transitions because you have issues with iframes on your pages?
- Wanting support in understanding and debugging view transitions or simply want a second pair of eyes 👀 on your view transition settings?
- Looking for reusable animations or special transition effects?
- Want to use view transitions on your Starlight site?

The `astro-vtbot`package isn't a monolithic library. Use the components you need and only pay bandwidth for those.
|Component|Brotli bytes added|
|-------|-----------------|
Animation Style ✨| ~0.1k
AutoNameSelected 📛 | ~0.3k
BorderControl 🛂 | ~0.1k
BrakePad 🦥 | ~0.2k
Linter 🧹 | ~1.9k
LoadingIndicator ⏳ | ~0.4k
Move 🚟 | ~0.2k
NoScroll 📜 | ~0.1k
PageOffset 📄⇞ | ~0.1k
Portal 🚪 | ~0.2k
ReplacementSwap ↹ | ~0.5k
Starlight &hellip; 🌟 | ~3.0k
SwapSound 🔊 | -0.3k
Swing 🎷 | ~0.1k
VtBotDebug 🐛 | ~2.8k
Zoom 🔎 | ~0.1k

Visit [the documentation](https://events-3bg.pages.dev/components/) of the reusable components for detailed information.

- `<Linter/>`: A linter component that helps you identify problems when setting up transitions.

- `<VtBotDebug/>`: A Debugging component that logs the events and their data as they occur.

- `<ReplacementSwap/>`: An alterantive DOM swap(), which preserves elements in the original DOM to avoid reinitialization of iframes or CSS animations.

- `<LoadIndicator>`: Have you ever missed the visual feedback on sites with view transitions as to whether the app has noticed the click? You need a loading indicator! Here you go!

- `Zoom`, `<Move>` and `Swing` animations and the `<AnimationsStyle/>` component allows for extended styling options.

- `<Portal/>` component that forces all view transitions through a portal/loading page.

- `<NoScroll/>` keep the current vertical and horizontal scroll position when transitioning to the next page.

## Tech Demos 🔥

The bag of tricks currently contains [several technical demos](https://events-3bg.pages.dev/demos/) that show examples of the implementation of various effects using the view transition events.

The sources are in [this repository](https://github.com/martrapp/astro-vtbot-website).

## The Jotter 📓

Last but not least, the deployment also includes the [▶ Jotter ◀](https://events-3bg.pages.dev/jotter/) with a wealth of information on transition events as well as background information and valuable tips & tricks on view transitions in Astro.

Some of the contents are technical demos, some are useful tools, and some are reusable components that you can use in your own project to handle edge cases that go beyond Astro's standard features.

## Troubleshooting

For help, check out the `Discussions` tab on the [GitHub repo](https://github.com/martrapp/astro-vtbot/discussions).

## Contributing

This package is maintained by [martrapp](https://github.com/martrapp) independently from Astro. You're welcome to contribute by submitting an issue or opening a PR!

## Changelog

See [CHANGELOG.md](https://github.com/martrapp/astro-vtbot/blob/main/CHANGELOG.md) for a history of changes to this package.
