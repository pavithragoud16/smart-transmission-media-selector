# Smart Transmission Media Selector & Network Planning Assistant

## Overview

NetMedia is a browser-based network planning and learning tool for comparing transmission media from the Computer Networks Physical Layer. Its light, screen-based interface provides guided and wireless media profiles, requirement-based analysis, comparison charts, scenario planning, and visual signal simulation.

## Features

- Seven JavaScript-switched screens with a responsive light sidebar
- Six media profiles with detailed characteristics, applications, advantages, and limitations
- Rule-based compatibility scoring with a recommended option and ranked alternatives
- Dynamic media comparison table, profile cards, radar chart, and relative cost chart
- Six scenario presets with selectable assumptions and a separate Analyze Scenario action
- Visual simulations for copper, fiber optics, radio waves, microwave, and infrared
- Simulation Start, Pause, and Reset controls
- Responsive desktop, tablet, and mobile layouts

## Transmission Media

### Guided

- Twisted Pair
- Coaxial Cable
- Fiber Optics

### Wireless

- Radio Waves
- Microwave
- Infrared

## Technologies

- HTML5
- CSS3
- JavaScript
- Chart.js from jsDelivr CDN

There is no backend, database, authentication, hardware, or API-key requirement. Google Fonts and Chart.js use external CDNs; application logic runs in the browser.

## Analyzer Model

Each medium has qualitative values for speed, distance, cost, interference, and security, plus a wired/wireless type. JavaScript compares those predefined values with the user's selections, applies the existing weighted scoring rules, calculates suitability percentages, explains matches and trade-offs, and sorts the results.

Scores are educational compatibility estimates, not measured performance or absolute real-world recommendations. Reliability labels in the comparison and recommendation views are qualitative summaries.

## Scenario Presets

- Home network
- Office building
- City-to-city connection
- University campus
- Industrial area
- Data center

## Project Structure

```text
transmission-media-selector/
├── index.html
├── style.css
├── script.js
├── README.md
└── LICENSE
```

## Run

Open `index.html` in a modern browser, or open the folder in VS Code and run it with the Live Server extension. Internet access is needed for hosted fonts and Chart.js.

## Syllabus Connection

**Computer Networks → Physical Layer → Transmission Media**

The project covers guided transmission, twisted pair, coaxial cable, fiber optics, wireless transmission, radio, microwave, infrared, and the electromagnetic spectrum.

## Limitations

- Signal movement is a visual educational simulation; the app does not physically transmit data.
- Scores use predefined qualitative rules and are not measured benchmarks.
- Real network design depends on standards, equipment, topology, installation, regulations, and environmental conditions.

## Future Enhancements

- Additional scenarios and transmission parameters
- More detailed signal propagation models
- Topology visualization and standards-based profiles

## License

MIT. See [LICENSE](LICENSE).
