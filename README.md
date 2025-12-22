# seeboard

A visual tool to practise touch typing with comprehensive symbol support and custom keyboard layouts.

![Seeboard 0.0.1](doc/seeboard_001.gif)

> **Note:** This project started as a fork of the original [seeboard](https://github.com/mindrones/seeboard) and has been enhanced with new features for developer-focused typing practice.

Given a random text for you to type, highlights the current target key and the keys you type, so that if you miss the target you can see how far you are and adjust without looking at the keyboard.

It doesn't show symbols on keys intentionally, to help you remember their position.

Colors suggest the finger to use:

- green → index
- cyan → middle
- gold → ring
- pink → pinky (obviously :)
- brown → thumb

## What's New

This fork includes:

- **Comprehensive symbol support** – Practice typing all the special characters developers use daily (brackets, operators, punctuation)
- **ZSA Moonlander keyboard layout** – Integrated custom split ergonomic keyboard layout alongside the original Keyboard.io
- **Enhanced typing practice** – Developer-friendly text generation for programming symbols and syntax
- **Preserved features** – All original color-coded touch typing visualization remains intact

## Usage

- Press `Enter` when you have completed the text,
- Press `PageUp` or `PageDown` to update the text and restart,

It currently shows the [Keyboard.io](https://shop.keyboard.io/) with QWERTY layout.


## Personalization

To configure your own layout:

- run `npm run dev`
- open [localhost:3000](http://localhost:3000)
- modify `src/app/components/Keyboardio/keyToChar.json`
- the page will refresh automatically after a new build.


## Future Ideas

- **Dynamic keyboard layouts** – Allow users to upload their own firmware files and automatically render a virtual keyboard based on their custom layout
- **Layout auto-detection** – Parse QMK/ZSA firmware to generate keyboard mappings
- **More keyboard models** – Support for additional ergonomic and mechanical keyboards
- **Custom training modes** – Focused practice sessions for specific symbol groups or programming languages

## Contribute!

Contributions are welcome! You can help by:
- Opening issues or PRs for new features or bug fixes
- Submitting new keyboard layouts (PRs, gists, pastebins all work)
- Sharing keyboard drawings that could be converted to Svelte components
- Suggesting improvements to the typing practice experience

Thanks!
