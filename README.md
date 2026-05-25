<div align="center">

<img src="assets/logo.svg" width="92" alt="Sawt logo" />

# Sawt &nbsp;·&nbsp; صوت

### Speak Arabic. Sawt writes you.

**تكلّم بالعربي، وصوت يكتب عنك.**

Hold a key, speak any dialect, and clean Arabic lands in whatever app you are in.<br/>
Everything runs on your Mac. Your voice is never uploaded.

<br/>

![macOS](https://img.shields.io/badge/macOS-Apple_Silicon-0E1513?logo=apple&logoColor=white)
![Signed & Notarized](https://img.shields.io/badge/Signed_%26_Notarized-Apple_Developer_ID-3C7A12)
![On-device](https://img.shields.io/badge/100%25-on--device-0E1513?labelColor=C6F24A)
![Cleanup by ALLaM](https://img.shields.io/badge/cleanup-ALLaM%20(HUMAIN)-3C7A12?labelColor=0E1513)
![Latest](https://img.shields.io/github/v/release/sunnybhara/sawt-app?color=3C7A12&label=latest)
![Downloads](https://img.shields.io/github/downloads/sunnybhara/sawt-app/total?color=0E1513&label=downloads)

<br/>

<a href="https://github.com/sunnybhara/sawt-app/releases/latest"><img alt="Download for Mac" src="https://img.shields.io/badge/⬇%20%20Download%20for%20Mac-Apple%20Silicon-0E1513?style=for-the-badge&logo=apple&logoColor=white" height="46" /></a>

<sub>Free during early access · no card</sub>

</div>

---

## Why Sawt

<table>
<tr>
<td width="33%" valign="top">

### 🔒 Private by design
Your speech is transcribed and cleaned on your own machine. Nothing is sent to a server. Privacy is the default here, not a toggle, which is what lets it fit sensitive and regulated work.

</td>
<td width="33%" valign="top">

### 🗣️ Arabic-first, not Arabic-also
Most tools bolt Arabic onto a hundred-language model and flatten your dialect into formal Arabic. Sawt is built for Arabic: Khaleeji, Egyptian, Levantine, Iraqi, Maghrebi and MSA, kept the way you actually talk, and it handles the English you mix in.

</td>
<td width="33%" valign="top">

### ✨ Learns your voice
Your corrections, names and style become Sawt's. The more you dictate, the more the writing sounds like you wrote it.

</td>
</tr>
</table>

## How it works

**01 · Hold** &nbsp;`fn`&nbsp; from any app to start listening.
**02 · Speak Arabic** naturally, in your dialect. Release when you are done.
**03 · It types for you**: clean, punctuated Arabic, right where your cursor is.

No menus, no setup tax. Hold, speak, done.

## Install

1. Download `Sawt-0.1.1-arm64.dmg` from the [latest release](https://github.com/sunnybhara/sawt-app/releases/latest).
2. Open the DMG and drag **Sawt** into your Applications folder.
3. Launch Sawt. It walks you through a quick setup and the macOS permissions it needs:
   - **Microphone**, so it can hear you.
   - **Accessibility**, so it can type the result into the app you are using.
   - **Input Monitoring**, so the `fn` hold-to-talk key works.
4. Finish the short sign-in and you are ready. Hold `fn` and speak.

The app is signed with an Apple Developer ID and notarized by Apple, so it opens cleanly with no security warnings.

## Built for the Gulf, and for privacy

Because everything stays on the device, Sawt fits where cloud dictation cannot: sensitive work, regulated industries, and anyone who would rather their voice stay theirs. No audio leaves your Mac, which keeps it friendly to PDPL and GDPR expectations by design, not by policy.

## Requirements

- **Apple Silicon Mac** (M1 or later). Intel Macs are not supported in this build.
- The speech model ships inside the app, so dictation works **fully offline**.

## Under the hood

Two stages, both running on your Mac:

- **Speech to text:** a fine-tuned Arabic Whisper model (whisper.cpp), accelerated with Metal.
- **Cleanup:** [**ALLaM**](https://huggingface.co/ALLaM-AI), HUMAIN's Arabic LLM, handles the dialect-aware cleanup: punctuation, restoring the English terms you mix in, and keeping your dialect intact rather than flattening it into formal Arabic.

Nothing is sent to a server. Both models ship inside the app.

## FAQ

<details>
<summary><b>Is my voice ever uploaded?</b></summary><br/>

No. Both the speech recognition and the cleanup run on your Mac. Your audio and your text never leave the device. The only thing Sawt ever sends is your email address, once, to sign you in.
</details>

<details>
<summary><b>Which dialects does it understand?</b></summary><br/>

Khaleeji, Egyptian, Levantine, Iraqi, Maghrebi and Modern Standard Arabic. It keeps your dialect rather than rewriting it into formal Arabic, and it handles the English words you naturally mix in.
</details>

<details>
<summary><b>Does it work without internet?</b></summary><br/>

Yes. The model is bundled inside the app, so dictation works fully offline. The only moment it touches the network is the one-time magic-link sign-in.
</details>

<details>
<summary><b>Will it run on an Intel Mac?</b></summary><br/>

Not this build. Sawt currently ships for Apple Silicon (M1 and later).
</details>

<details>
<summary><b>Is it really free?</b></summary><br/>

It is free during early access, with no card required. Pricing comes later, and early users will hear about it first.
</details>

<br/>

<div align="center">
<sub>On-device Arabic dictation · built for the Gulf, and for privacy.</sub>
</div>
