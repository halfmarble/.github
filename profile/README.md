# halfmarble

**halfmarble** is an independent maker of open-source software and hardware, run by two
people in Charlottesville, Virginia. We build local-first tools for living with Parkinson's
disease, and we build them for ourselves first.

Gerard Ziemski spent fifteen years working on the JVM at Sun and Oracle, and has had
Parkinson's for over a decade. Anya Ziemski is a nurse with fourteen years in geriatric care.
What is here comes out of that pair of vantage points.

## How we build

- **On-device by default.** Health data belongs to the person it came from. Our apps compute
  locally, and by default nothing leaves the device.
- **Glass Box.** The algorithms are deterministic and traceable to published science rather
  than opaque models. If we cannot explain why a number moved, we do not ship the number.
- **Open where it counts.** Hardware designs and the pieces other people can reuse are
  published under open licences.
- **Prior art, published.** Methods we work out are lodged as defensive publications in the
  [Technical Disclosure Commons](https://www.tdcommons.org/), so they stay usable by anyone.

## Projects

| Project | What it is |
|---|---|
| [hm-panelizer](https://github.com/halfmarble/hm-panelizer) | A GUI PCB panelizer and Gerber viewer for KiCad users. Python and Kivy. |
| [SteadyHandTool](https://github.com/halfmarble/SteadyHandTool) | An open-hardware SMD assembly stabilizer for precision work when hand tremor makes it difficult. CERN-OHL-S-2.0. |
| [HalfmarbleKit](https://github.com/halfmarble/HalfmarbleKit) | The shared iOS and tvOS layer behind our apps: audio host, StoreKit unlock, menu chrome, brand. |
| [SteadyHeartBeat](https://github.com/halfmarble/SteadyHeartBeat) | Speaks your live heart rate aloud through AirPods, entirely on-device. |
| [cpuTopBars](https://github.com/halfmarble/cpuTopBars) | A small CPU and process monitor for macOS. |
| [NEAToBOARD](https://github.com/halfmarble/NEAToBOARD) | An open-hardware ESP32-WROOM-32 development board, breadboard-friendly, designed in KiCad. CERN-OHL-P-2.0. |
| [MathLexicon](https://github.com/halfmarble/MathLexicon) | Reads written math aloud for text-to-speech: rewrites an expression such as `E=mc²` into what a person would say. Swift. |
| [ascii-diagrams](https://github.com/halfmarble/ascii-diagrams) | A Claude Code plugin that draws and checks text diagrams, so boxes and tables stay aligned. |
| [mods](https://github.com/halfmarble/mods) | A marketplace for our Claude Code mods. |
| [halfmarble.com](https://github.com/halfmarble/halfmarble.com) | The source of our website. |

Also public: forks we keep of [kokoro-ios](https://github.com/halfmarble/kokoro-ios),
[MisakiSwift](https://github.com/halfmarble/MisakiSwift) and [SwiftMonkey](https://github.com/halfmarble/SwiftMonkey),
and SteadyHandTool's archived v1 models in
[SteadyHandTool-v1-models](https://github.com/halfmarble/SteadyHandTool-v1-models).

More at **[halfmarble.com](https://halfmarble.com)**.

---

*Our health apps are general wellness tools. They are not medical devices.*
