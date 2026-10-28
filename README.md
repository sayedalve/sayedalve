# Md Sayed Alve

<p align="left">
  <b>Civil Engineering Student at SUST &nbsp;•&nbsp; Software Developer</b><br>
  Building high-performance Windows desktop software, developer tools, and offline-first applications.
</p>

<p align="left">
  <a href="https://github.com/sayedalve?tab=repositories"><img src="https://img.shields.io/badge/Repositories-Public%20Projects-0969da?style=flat-square" alt="Repositories"></a>
  <a href="https://github.com/sayedalve/Radium-Download-Manager"><img src="https://img.shields.io/badge/Featured-Radium%20v0.3.2-e03131?style=flat-square&logo=windows11&logoColor=white" alt="Featured Radium"></a>
  <img src="https://img.shields.io/badge/Focus-C%2B%2B%20%7C%20Win32%20%7C%20Flutter%20%7C%20Python-2ea44f?style=flat-square" alt="Primary Focus">
  <img src="https://img.shields.io/badge/Domain-Structural%20%26%20Earthquake%20Eng-6f42c1?style=flat-square" alt="Civil Engineering">
</p>

---

## 👨‍💻 About Me

I am a Civil Engineering undergraduate at **Shahjalal University of Science and Technology (SUST)**, Department of Civil and Environmental Engineering. Alongside my academic work in structural analysis and seismic engineering, I design and build native desktop applications, system utilities, and developer software.

My development work emphasizes:
- **Native performance and low memory overhead** — building lightweight C++20/Win32 tools rather than heavy web-wrapped frameworks.
- **Resilient systems engineering** — multi-connection HTTP range architectures, I/O completion mechanisms, and offline-first local storage.
- **Practical user interfaces** — clean, keyboard-friendly Windows taskbar utilities and focused desktop workflows.
- **Computational engineering** — exploring computational structural modeling, earthquake engineering, and fragility analysis.

---

## 🚀 Featured Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>⚡ <a href="https://github.com/sayedalve/Radium-Download-Manager">Radium Download Manager</a></h3>
      <p><b>High-performance native Windows 11 download manager with browser video sniffing.</b></p>
      <ul>
        <li><b>Stack:</b> ISO C++20, Win32, Direct2D/GDI, SQLite WAL, Manifest V3</li>
        <li><b>Engine:</b> Segmented downloads (1–32 workers) with adaptive work-stealing and RFC 9110/9112 resilience.</li>
        <li><b>Stream Pipeline:</b> Manifest sniffing (HLS/DASH) with isolated worker muxing via <code>N_m3u8DL-RE</code> and <code>FFmpeg</code>.</li>
        <li><b>BitTorrent:</b> Integrated BitTorrent engine with metadata exchange (BEP 9) and piece verification.</li>
        <li><b>Footprint:</b> Instant launch and tiny memory usage (~18–22 MB RAM peak).</li>
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
        <li><b>Stack:</b> Flutter, Dart, SQLite (drift), Riverpod, Melos monorepo</li>
        <li><b>Capture:</b> Instant single-keystroke word capture (<code>Ctrl+N</code>) with background enrichment.</li>
        <li><b>Universal AI:</b> Supports OpenAI-compatible providers and Gemini; keys stored securely in Windows Credential Manager.</li>
        <li><b>Interactive Cards:</b> Rich cards with IPA, Bangla translation, examples, and synced synonym highlighting.</li>
        <li><b>Offline Quizzes:</b> Local FTS5 full-text search, multiple-choice quiz engine, and full attempt tracking.</li>
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
        <li><b>Stack:</b> C++17, Qt 6, Windows SDK (<code>GetIfEntry2</code>)</li>
        <li><b>Taskbar Integration:</b> Frameless, transparent overlay locked into the Windows taskbar with intelligent full-screen app detection.</li>
        <li><b>Precision Engine:</b> Dedicated background <code>QThread</code> calculation using <code>QElapsedTimer</code> for jitter-free rate tracking.</li>
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
        <li><b>Stack:</b> Python 3.12+, PyQt6, Win32 API</li>
        <li><b>Display:</b> Real-time Upload (↑) and Download (↓) speeds with custom <code>QPainter</code> rendering.</li>
        <li><b>Customization:</b> Typography scaling, configurable mini-graph history, tray position locking, and adapter selection.</li>
      </ul>
      <p>
        <a href="https://github.com/sayedalve/netspeedmeter1"><img src="https://img.shields.io/badge/Repo-NetSpeedMeter%20Py-3776AB?style=flat-square&logo=python" alt="NetSpeedMeter1 Repo"></a>
      </p>
    </td>
  </tr>
</table>

---

## 🛠️ Technical Stack & Tools

Based on actively built and maintained codebases:

- **Languages:** C++ (C++20, C++17), Python, Dart, TypeScript, SQL
- **Windows & Desktop:** Win32 API, Direct2D, GDI, Qt 6, CustomTkinter, Tauri
- **Application Frameworks:** Flutter (Riverpod, Drift SQLite, Melos)
- **Networking & Protocols:** HTTP/1.1 & RFC 9110/9112 Segmented Transfers, BitTorrent v1, HLS / DASH manifest detection, Windows Named Pipes IPC
- **Data & Storage:** SQLite3, Drift FTS5, Windows Credential Manager
- **Build Systems & Tooling:** CMake, MSVC, Git, GitHub Actions CI/CD, Inno Setup

---

## 🏗️ Engineering & Research Background

In addition to software engineering, I study Civil Engineering at SUST with primary academic interests in:
- **Structural Engineering:** Finite element modeling, dynamic structural response, and structural analysis.
- **Earthquake Engineering:** Performance-based seismic assessment (PBSA), seismic hazard evaluation, and fragility analysis.
- **Computational Methods:** Numerical simulation, low-cycle fatigue evaluation, and structural scripting using tools such as OpenSeesPy and scientific Python.

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
