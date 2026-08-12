# 👋 Hi, I'm Jens Duttke

I'm a **Software Developer and AI Engineer** from Germany. What drives me isn't writing code, it's making something other people find useful.

---

## 🚀 About Me

- 💻 **Profession:** AI Engineer, after more than two decades of frontend development in JavaScript, TypeScript and React
- 🛠️ **Core Skills:** TypeScript, JavaScript, React, Web Development
- 🤖 **AI Work:** depth estimation and ONNX model optimization, RAG pipelines built from scratch down to embeddings and vector database, custom skills and tooling for Claude Code, plus experiments with diffusion models, TTS and audio recognition
- 🎯 **Current Interests:** 3D printing, laser cutting, 3D photography, and learning to play the E-Bass
- 🧠 **Motto:** _I'm not a programmer who makes things. I'm a maker who happens to program._

## 🌟 Featured Projects

### Flagship Tools & Apps

The tools and apps that found an audience of their own.

- [**Usage Monitor for Claude**](https://github.com/jens-duttke/usage-monitor-for-claude) | [**Agent Monitor for Claude**](https://github.com/jens-duttke/agent-monitor-for-claude)  
  Two Windows tray apps for Claude Code. One tracks your session and weekly rate limits, the other watches running agents with live status, model and estimated cost. Both run locally and read-only, with nothing to configure.
- [**Oku3D**](https://oku3d.com/)  
  Media player with real time AI 2D-to-3D conversion. Turns any video or image into stereoscopic 3D for 3D displays and VR headsets.
- [**HexEd.it**](https://hexed.it/)  
  Hex editor for binary files, running entirely in your browser.
- [**Stereo Photo Optimizer**](https://forums.leialoft.com/t/stereo-photo-optimizer-new-app-for-sbs-3d-image-correction/6181)  
  Android app for correcting side-by-side 3D photos: convergence, colour temperature, noise and sharpness. Built for the Leia LumePad 2 and adopted by its community.
- [**PhotoME**](https://www.photome.de/)  
  Viewer and editor for digital photo metadata, used around the world.
- [**JSQR**](https://jsqr.de)  
  QR code generator, and the first written in JavaScript when it was released.
- [**Garmin Watch Apps**](https://apps.garmin.com/de-DE/developer/8cb871b5-2a6c-4a75-a350-99f1945f3d36/apps)  
  Apps for Garmin watches, including a data field that talks to WalkingPad treadmills.

### AI Models

Depth estimation models converted to ONNX and tuned for speed, published on [**Hugging Face**](https://huggingface.co/Jens-Duttke). They are what makes the real time 2D-to-3D conversion in Oku3D possible.

- [**Depth Anything 3 MONO ONNX**](https://huggingface.co/Jens-Duttke/Depth-Anything-3-MONO-ONNX)  
  ByteDance's Depth Anything V3 with sky-aware disparity baked into the graph. Five input resolutions, FP16 and 4-bit variants, no postprocessing needed.
- [**Lotus Depth D ONNX**](https://huggingface.co/Jens-Duttke/Lotus-Depth-D-ONNX)  
  A whole diffusion pipeline (VAE encoder, UNet, VAE decoder) collapsed into one ONNX graph with a single input and output. Deterministic single-pass inference, no scheduler, no ensembling.
- [**DepthPro ONNX HighPerf**](https://huggingface.co/Jens-Duttke/DepthPro-ONNX-HighPerf)  
  Apple's DepthPro reduced to a depth-only export and aggressively optimized, reaching up to 50x the throughput of the reference implementation.

### Side Projects

The groundwork the projects above are built on, plus tools that each solve a single problem.

- [**edge264-mvc**](https://github.com/jens-duttke/edge264-mvc) | [**mvc-source**](https://github.com/jens-duttke/mvc-source)  
  H.264/AVC decoder with full MVC support, the stereoscopic format of 3D Blu-rays that FFmpeg only ever decodes half of. Multithreaded, bit-exact, validated against the JVT conformance corpus, with dependency-free AviSynth+ and VapourSynth plugins on top.
- [**npx check-outdated**](https://www.npmjs.com/package/check-outdated)  
  Checks npm dependencies for outdated packages and exits with an error, so a CI run can fail on them.
- [**mcp-popup-ui**](https://github.com/jens-duttke/mcp-popup-ui)  
  MCP server that lets an AI assistant ask its questions through a clickable browser popup instead of a numbered list in the terminal.
- [**Semantic Document Search**](https://www.duttke.de/semantic-search/)  
  Searches your documents by meaning rather than keywords, across PDF, Word, Excel and more. The transformer model runs in the browser, so no file leaves your computer.
- [**LIF Decoder**](https://www.duttke.de/en/lif/)  
  Decoder for the Leia Image Format behind LumePad 2 photos. It became the basis for LIF support in Oku3D and the Stereo Photo Optimizer.
- [**Base64 Encoder & Decoder**](https://www.duttke.de/en/base64/) | [**Outlook Attachment Extractor**](https://www.duttke.de/en/outlook-email-attachment-extractor/) | [**Bass Workout Generator**](https://www.duttke.de/bass-workout-generator/) | [**WalkingPad Bluetooth Tool**](https://www.duttke.de/en/walkingpad/)  
  Base64 conversion, bulk attachment extraction from Outlook messages, custom bass practice routines, and access to the hidden settings of a KingSmith WalkingPad over Web Bluetooth. All of them run in the browser, nothing is uploaded.

### Games

Games I built for the browser over the years, all of them still online.

- [**Oxyd extra v2**](https://de.wikipedia.org/wiki/Oxyd#Remake_von_Oxyd_Extra)  
  Originally a fan remake, later officially supported by the original Oxyd developer.
- [**Macuro**](https://macuro.de/) | [**DiceRolling**](https://www.duttke.de/projects/dicerolling/) | [**Kakuro**](https://kakuro.duttke.de/) | [**CrazyMovin**](https://www.duttke.de/projects/crazymovin/) | [**Nine Men's Morris**](https://www.duttke.de/projects/nmm/)  
  Puzzle, dice and board games.

### Emulator Tools

Where it started: my first published software appeared in 1999, in the PlayStation emulation scene.

- [**PSX Emulation Cheater**](https://pec.duttke.de/)  
  Advanced cheating tool for PlayStation emulators.
- [**CyberPad**](https://cyberpad.duttke.de/)  
  Play PSX games online with friends.
- [**Blini!**](https://blini.duttke.de/)  
  Configuration editor for the PlayStation emulator Bleem!

---

## 🌐 Find Me Online

- 🌍 [duttke.de](https://www.duttke.de/)
- 💼 [LinkedIn](https://www.linkedin.com/in/jensduttke/)
- 🤗 [Hugging Face](https://huggingface.co/Jens-Duttke) - ONNX depth models
- 📦 [npm](https://www.npmjs.com/~jens-duttke) - published packages
- 🖨️ [MakerWorld](https://makerworld.com/en/@jens_duttke) - 3D printing models
- ✂️ [Atomm](https://www.atomm.com/profile/550757) - laser cutting projects
- 🥾 [Komoot](https://www.komoot.com/user/136351783644) - hiking routes

---

## 🧰 Tools & Technologies

What the projects on this page are built with. TypeScript and JavaScript are home ground, the rest I picked up as far as each project needed.

**Languages**  
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?logo=typescript&logoColor=fff)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?logo=javascript&logoColor=222)
![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=fff)
![Rust](https://img.shields.io/badge/-Rust-000000?logo=rust&logoColor=fff)
![C](https://img.shields.io/badge/-C-A8B9CC?logo=c&logoColor=222)

**AI**  
![Claude Code](https://img.shields.io/badge/-Claude%20Code-D97757?logo=claude&logoColor=fff)
![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?logo=pytorch&logoColor=fff)
![ONNX](https://img.shields.io/badge/-ONNX-005CED?logo=onnx&logoColor=fff)
![Hugging Face](https://img.shields.io/badge/-Hugging%20Face-FFD21E?logo=huggingface&logoColor=222)
![OpenCV](https://img.shields.io/badge/-OpenCV-5C3EE8?logo=opencv&logoColor=fff)
![Ollama](https://img.shields.io/badge/-Ollama-000000?logo=ollama&logoColor=fff)

**Frontend**  
![React](https://img.shields.io/badge/-React-20232A?logo=react&logoColor=61DAFB)
![Redux](https://img.shields.io/badge/-Redux-764ABC?logo=redux&logoColor=fff)
![Next.js](https://img.shields.io/badge/-Next.js-000000?logo=next.js&logoColor=fff)
![Astro](https://img.shields.io/badge/-Astro-BC52EE?logo=astro&logoColor=fff)
![Gatsby](https://img.shields.io/badge/-Gatsby-663399?logo=gatsby&logoColor=fff)
![GraphQL](https://img.shields.io/badge/-GraphQL-E10098?logo=graphql&logoColor=fff)
![CSS](https://img.shields.io/badge/-CSS-1572B6?logo=css3&logoColor=fff)
![Tailwind CSS](https://img.shields.io/badge/-Tailwind%20CSS-06B6D4?logo=tailwindcss&logoColor=fff)
![Sass](https://img.shields.io/badge/-Sass-CC6699?logo=sass&logoColor=fff)

**Backend & Build**  
![Node.js](https://img.shields.io/badge/-Node.js-339933?logo=node.js&logoColor=fff)
![Webpack](https://img.shields.io/badge/-Webpack-8DD6F9?logo=webpack&logoColor=222)
![Docker](https://img.shields.io/badge/-Docker-2496ED?logo=docker&logoColor=fff)
![Git](https://img.shields.io/badge/-Git-F05032?logo=git&logoColor=fff)

**Quality & Testing**  
![ESLint](https://img.shields.io/badge/-ESLint-4B32C3?logo=eslint&logoColor=fff)
![Jest](https://img.shields.io/badge/-Jest-C21325?logo=jest&logoColor=fff)
![Cypress](https://img.shields.io/badge/-Cypress-17202C?logo=cypress&logoColor=fff)
![Playwright](https://img.shields.io/badge/-Playwright-2EAD33?logo=playwright&logoColor=fff)

---

## 🧑‍💻 More About Me

I wrote my first games in QBasic at the age of 12, and for most of my life I would have said that programming is my hobby. Working with AI taught me that this was never quite right: what I enjoy is making things, and programming was simply the medium I knew best. The same impulse produces 3D prints, laser-cut parts and photographs.

So when something I care about is missing a tool, I build it myself. Everything above started that way: hiking, 3D photography, bass practice, PlayStation emulation. AI hasn't changed what I want to build, only how much of it I can reach.

---

Thanks for stopping by! 🚀
