<img src="assets/banner-terminal.png" alt="Terminal: whoami prints Hi, I'm Arjun, a software engineer in London building emulators, kernels and low-level tools" width="100%" />

I'm a software engineer in London. These days I spend most of my time on emulators, a hobby kernel and other projects that sit close to the hardware, but I build web apps too. Away from the keyboard I lift, play games, and I've traveled to 20+ countries, so ask me about those.

## Projects

<table>
<tr>
<td width="50%" valign="top">
<a href="https://github.com/amyanger/gba-emulator"><img src="assets/gba-emulator.png" alt="gba-emulator running Pokemon Emerald with the Emerald Companion battle panel" /></a>
<h3><a href="https://github.com/amyanger/gba-emulator">gba-emulator</a></h3>
A Game Boy Advance emulator in C, built around Pokémon Emerald. The Emerald Companion panel reads the game live and shows battle damage, catch odds, party stats, encounters and a Nuzlocke tracker, and Hardware X-Ray lets you watch the CPU, PPU and audio at work.
<br /><br />
<img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black" alt="C" />
<img src="https://img.shields.io/badge/SDL2-1D4F8C?style=flat-square" alt="SDL2" />
<img src="https://img.shields.io/github/v/release/amyanger/gba-emulator?style=flat-square&label=release&color=34d399" alt="Latest release" />
</td>
<td width="50%" valign="top">
<a href="https://github.com/amyanger/ds-emulator"><img src="assets/ds-emulator.png" alt="ds-emulator test suite passing" /></a>
<h3><a href="https://github.com/amyanger/ds-emulator">ds-emulator</a></h3>
A Nintendo DS emulator written from scratch in C++20, aimed at the Gen 4 and Gen 5 Pokémon games with HeartGold and SoulSilver first. Two CPUs on separate buses driven by one event scheduler. Still early, with the CPUs and core hardware coming first.
<br /><br />
<img src="https://img.shields.io/badge/C++20-00599C?style=flat-square&logo=cplusplus&logoColor=white" alt="C++20" />
<img src="https://img.shields.io/badge/SDL2-1D4F8C?style=flat-square" alt="SDL2" />
<img src="https://img.shields.io/badge/Apple_Silicon-000000?style=flat-square&logo=apple&logoColor=white" alt="Apple Silicon" />
</td>
</tr>
<tr>
<td width="50%" valign="top">
<a href="https://github.com/amyanger/rust-kernel"><img src="assets/rust-kernel.png" alt="RustKernel shell running in QEMU" /></a>
<h3><a href="https://github.com/amyanger/rust-kernel">rust-kernel</a></h3>
A bare-metal x86_64 kernel in Rust. It has interrupts, 4-level paging, a heap allocator, framebuffer graphics with a bitmap font, and an interactive shell, and it boots in QEMU.
<br /><br />
<img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white" alt="Rust" />
<img src="https://img.shields.io/badge/x86__64-555555?style=flat-square" alt="x86_64" />
<img src="https://img.shields.io/badge/QEMU-FF6600?style=flat-square&logo=qemu&logoColor=white" alt="QEMU" />
</td>
<td width="50%" valign="top">
<a href="https://github.com/amyanger/sentinel"><img src="assets/sentinel.png" alt="Sentinel driver code that flags FPGA PCIe vendors" /></a>
<h3><a href="https://github.com/amyanger/sentinel">sentinel</a></h3>
A Windows anticheat aimed at DMA cheat hardware. A kernel driver checks PCIe devices and memory timing for FPGA boards, a C++ service watches processes and loaded modules, and a web dashboard shows what it finds.
<br /><br />
<img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white" alt="C++" />
<img src="https://img.shields.io/badge/Windows_Kernel-0078D6?style=flat-square&logo=windows&logoColor=white" alt="Windows kernel" />
<img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js" />
</td>
</tr>
<tr>
<td width="50%" valign="top">
<a href="https://github.com/amyanger/local-llm-project"><img src="assets/local-llm-project.png" alt="QLoRA training config from local-llm-project" /></a>
<h3><a href="https://github.com/amyanger/local-llm-project">local-llm-project</a></h3>
QLoRA fine-tuning for 7B models on one consumer GPU. 4-bit quantization keeps training to about 16 GB of VRAM, and it supports the RTX 5090 (Blackwell).
<br /><br />
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch" />
<img src="https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white" alt="CUDA" />
</td>
<td width="50%" valign="top">
<a href="https://github.com/amyanger/pokeheartgold"><img src="assets/pokeheartgold.png" alt="Decompiled Pokeathlon course code" /></a>
<h3><a href="https://github.com/amyanger/pokeheartgold">pokeheartgold</a></h3>
My fork of the pret HeartGold/SoulSilver decompilation. I'm turning the Pokéathlon course code (overlay 96) back into C that compiles to the original bytes.
<br /><br />
<img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black" alt="C" />
<img src="https://img.shields.io/badge/ARM_Assembly-6E4C13?style=flat-square" alt="ARM assembly" />
<img src="https://img.shields.io/badge/Nintendo_DS-D12228?style=flat-square" alt="Nintendo DS" />
</td>
</tr>
</table>

## Tech stack

<p>
<img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black" alt="C" />
<img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white" alt="C++" />
<img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white" alt="Rust" />
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript" />
<img src="https://img.shields.io/badge/Solidity-363636?style=flat-square&logo=solidity&logoColor=white" alt="Solidity" />
<img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" alt="HTML5" />
<img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white" alt="CSS3" />
<br />
<img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React" />
<img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js" />
<img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js" />
<img src="https://img.shields.io/badge/TailwindCSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" alt="TailwindCSS" />
<img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white" alt="MongoDB" />
<img src="https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black" alt="Firebase" />
<img src="https://img.shields.io/badge/SDL2-1D4F8C?style=flat-square" alt="SDL2" />
<img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git" />
<img src="https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white" alt="Figma" />
</p>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/amyanger/amyanger/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/amyanger/amyanger/output/github-snake.svg" />
  <img alt="A snake eating Arjun's GitHub contribution graph" src="https://raw.githubusercontent.com/amyanger/amyanger/output/github-snake.svg" width="100%" />
</picture>
