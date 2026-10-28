# Md Sayed Alve

<p align="left">
  <b>Vibe Coder &nbsp;•&nbsp; AI-Assisted Builder &nbsp;•&nbsp; Civil Engineering Student at SUST</b><br>
  Turning ideas into working software through AI pair programming, rapid experimentation, and hands-on iteration.
</p>

<p align="left">
  <a href="https://github.com/sayedalve?tab=repositories"><img src="https://img.shields.io/badge/Repositories-Public%20Projects-0969da?style=flat-square" alt="Repositories"></a>
  <a href="https://github.com/sayedalve/Radium-Download-Manager"><img src="https://img.shields.io/badge/Featured-Radium%20v0.3.2-e03131?style=flat-square&logo=windows11&logoColor=white" alt="Featured Radium"></a>
  <img src="https://img.shields.io/badge/Approach-Vibe%20Coding%20%7C%20AI%20Iterated-8b5cf6?style=flat-square" alt="Vibe Coding">
  <img src="https://img.shields.io/badge/Focus-Windows%20Tools%20%7C%20AI%20Apps%20%7C%20Utilities-2ea44f?style=flat-square" alt="Focus">
</p>

---

## 💡 About Me & My Approach

Hey, I'm Sayed Alve. I am a **vibe coder and independent builder** who uses modern AI tools to bring software ideas to life. Rather than following traditional development paths, I pair with AI to architect, prototype, test, and relentlessly refine software until it works smoothly.

I love taking concepts—like a zero-bloat Windows download accelerator, an offline-first AI vocabulary companion, or a transparent taskbar speed monitor—and steering AI models through prompt engineering, code reviews, debugging sessions, and benchmark verification to turn them into real, usable software.

### How I Build
- **Idea to Architecture:** I define the product vision, core constraints, UI layout, and functional scope.
- **AI-Powered Implementation:** I leverage state-of-the-art language models and coding assistants to generate code, explore algorithmic designs, and solve technical roadblocks.
- **Hands-On Verification:** I compile, test edge cases, analyze runtime performance, and iteratively debug issues to ensure the applications actually deliver on their promises.
- **Engineering Mindset:** Studying Civil Engineering at Shahjalal University of Science and Technology (SUST) gives me a strong foundation in structural logic, computational thinking, and quantitative problem solving that directly informs how I structure and validate my software projects.

---

## 🚀 Featured Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>⚡ <a href="https://github.com/sayedalve/Radium-Download-Manager">Radium Download Manager</a></h3>
      <p><b>Lightweight native Windows 11 download manager with browser video sniffing.</b></p>
      <ul>
        <li><b>Technologies Explored:</b> ISO C++20, Win32, Direct2D/GDI, SQLite WAL, Manifest V3</li>
        <li><b>Multi-Worker Engine:</b> Segmented downloads (1–32 workers) with adaptive work-stealing, hysteresis range reuse, and RFC 9110/9112 resilience.</li>
        <li><b>Stream Pipeline:</b> Manifest sniffing (HLS/DASH) with isolated worker muxing via <code>N_m3u8DL-RE</code> and <code>FFmpeg</code>.</li>
        <li><b>BitTorrent:</b> Built-in BitTorrent v1 engine with metadata exchange (BEP 9) and piece verification.</li>
        <li><b>Result:</b> Instant startup with a minimal RAM footprint (~18–22 MB peak).</li>
      </ul>
      <p>
        <a href="https://github.com/sayedalve/Radium-Download-Manager"><img src="https://img.shields.io/badge/Repo-Radium-e03131?style=flat-square&logo=github" alt="Radium Repo"></a>
        <a href="https://github.com/sayedalve/Radium-Download-Manager/releases/latest"><img src="https://img.shields.io/badge/Release-v0.3.2%20Available-0078D4?style=flat-square&logo=windows11" alt="Radium v0.3.2"></a>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>📚 <a href="https://github.com/sayedalve/VocabNote">VocabNote</a></h3>
      <p><b>Fast, offline-first AI vocabulary notebook and knowledge organizer.</b></p>
      <ul>
        <li><b>Technologies Explored:</b> Flutter, Dart, SQLite (drift), Riverpod, Melos monorepo</li>
        <li><b>Quick Capture:</b> Instant single-keystroke capture (<code>Ctrl+N</code>) with background AI card enrichment.</li>
        <li><b>Universal AI:</b> Connects with OpenAI-compatible providers and Gemini; API keys stored in Windows Credential Manager.</li>
        <li><b>Interactive Cards:</b> Structured cards with IPA, Bangla translation, example sentences, and synced synonym highlights.</li>
        <li><b>Quizzes:</b> On-device and AI-generated multiple-choice quizzes with searchable attempt history.</li>
      </ul>
      <p>
        <a href="https://github.com/sayedalve/VocabNote"><img src="https://img.shields.io/badge/Repo-VocabNote-02569B?style=flat-square&logo=flutter" alt="VocabNote Repo"></a>
        <img src="https://img.shields.io/badge/Target-Windows%20%7C%20Cross--Platform-10B981?style=flat-square" alt="VocabNote Platform">
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>📊 <a href="https://github.com/sayedalve/netspeedmeter">NetSpeedMeter</a></h3>
      <p><b>Lightweight real-time network speed monitor for the Windows taskbar.</b></p>
      <ul>
        <li><b>Technologies Explored:</b> C++17, Qt 6, Windows SDK (<code>GetIfEntry2</code>)</li>
        <li><b>Taskbar Overlay:</b> Frameless, transparent overlay locked into the Windows taskbar with intelligent full-screen application detection.</li>
        <li><b>Precision Engine:</b> Background <code>QThread</code> calculation using <code>QElapsedTimer</code> for jitter-free rate tracking.</li>
        <li><b>Zero Bloat:</b> Standalone portable binary with single-instance protection via <code>QSharedMemory</code>.</li>
      </ul>
      <p>
        <a href="https://github.com/sayedalve/netspeedmeter"><img src="https://img.shields.io/badge/Repo-NetSpeedMeter-2ea44f?style=flat-square&logo=qt" alt="NetSpeedMeter Repo"></a>
        <a href="https://github.com/sayedalve/netspeedmeter/releases/latest"><img src="https://img.shields.io/badge/Release-Latest%20Available-success?style=flat-square" alt="NetSpeedMeter Release"></a>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>📈 <a href="https://github.com/sayedalve/netspeedmeter1">NetSpeedMeter (Python / PyQt6)</a></h3>
      <p><b>Taskbar network monitor with typography controls and live area graph.</b></p>
      <ul>
        <li><b>Technologies Explored:</b> Python 3.12+, PyQt6, Win32 API</li>
        <li><b>Live Visualization:</b> Real-time Upload (↑) and Download (↓) speeds with custom <code>QPainter</code> rendering.</li>
        <li><b>Customization:</b> Typography scaling, configurable mini-graph history, tray position locking, and adapter selection.</li>
      </ul>
      <p>
        <a href="https://github.com/sayedalve/netspeedmeter1"><img src="https://img.shields.io/badge/Repo-NetSpeedMeter%20Py-3776AB?style=flat-square&logo=python" alt="NetSpeedMeter1 Repo"></a>
      </p>
    </td>
  </tr>
</table>

---

## 🛠️ Technologies & Ecosystems Explored

Technologies and environments I have prompted, iterated on, and deployed across projects:

- **Languages & Frameworks:** C++ (C++20, C++17), Python, Dart / Flutter, TypeScript, SQL
- **Desktop Environments:** Win32 API, Direct2D, Qt 6, CustomTkinter, Tauri
- **AI Assisted Tooling:** LLM prompt-driven development, code synthesis, iterative debugging, automated refactoring
- **Protocols & Data:** HTTP segmented range requests, BitTorrent, HLS / DASH manifests, SQLite3 / Drift, Windows Credential Manager
- **Workflow & Build:** CMake, MSVC, Melos, Git, GitHub Actions CI/CD, Inno Setup

---

## 🏛️ Engineering & Academic Background

Alongside software exploration, I am a Civil Engineering undergraduate at **Shahjalal University of Science and Technology (SUST)**.
My academic interests center on:
- **Structural Analysis & Mechanics:** Finite element modeling, structural behavior, and dynamic load evaluation.
- **Earthquake Engineering:** Performance-based seismic assessment (PBSA), seismic fragility analysis, and low-cycle fatigue.
- **Computational Methods:** Applying numerical scripting (such as OpenSeesPy and scientific Python) to structural simulation and engineering challenges.

---

## 📊 GitHub Highlights

<p align="left">
  <img src="https://github-readme-stats-sigma-five.vercel.app/api?username=sayedalve&show_icons=true&theme=default&hide_border=true&title_color=0969da&icon_color=0969da&text_color=57606a" alt="GitHub Stats" height="150" />
  &nbsp;
  <img src="https://github-readme-stats-sigma-five.vercel.app/api/top-langs/?username=sayedalve&layout=compact&theme=default&hide_border=true&title_color=0969da&text_color=57606a" alt="Top Languages" height="150" />
</p>

---

## 📬 Connect

- **GitHub:** [@sayedalve](https://github.com/sayedalve)
- **Projects:** [Browse All Repositories](https://github.com/sayedalve?tab=repositories)
