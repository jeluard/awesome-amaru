# Awesome Amaru

A curated list of the main [Amaru](https://github.com/pragma-org/amaru) project and the surrounding ecosystem of tools, demos, experiments, and adjacent research.

Amaru is a fully open source Cardano node client written in Rust. This list focuses on the official project plus the most relevant Amaru-related repositories, with links and media kept directly under each project.

## Contents

- [Operator tools and interfaces](#operator-tools-and-interfaces)
- [Mobile, desktop and device experiments](#mobile-desktop-and-device-experiments)
- [Experiments](#experiments)

## Operator tools and interfaces

- [jeluard/amaru-client](https://github.com/jeluard/amaru-client) - API and CLI for interacting with a remote Amaru node, especially over OTLP traces and metrics.

- [jeluard/amaru-doctor](https://github.com/jeluard/amaru-doctor) - Terminal UI for inspecting Amaru internals and browsing local chain and ledger databases.

    <a href="https://github.com/jeluard/amaru-doctor"><img src="https://raw.githubusercontent.com/jeluard/amaru-doctor/main/resources/demo.gif" width="480" alt="Amaru Doctor demo"></a>

- [jeluard/amaru-dashboard](https://github.com/jeluard/amaru-dashboard) - Web dashboard for monitoring an Amaru node over WebSocket, with real-time metrics rendered on an interactive globe. [Live demo](https://jeluard.github.io/amaru-dashboard)

## Mobile, desktop and device experiments

- [jeluard/icarus](https://github.com/jeluard/icarus) - An experiment to run Amaru on desktop and mobile, with Tauri-based demos.

    <video src="https://github.com/user-attachments/assets/a91c01d9-d570-4f31-bd33-cfe13a505c2b" width="480" controls></video>

- [jeluard/amaru-pi](https://github.com/jeluard/amaru-pi) - Notes, scripts, and SD image workflow for running Amaru on Raspberry Pi devices. [Project page](https://jeluard.github.io/amaru-pi/)

- [jeluard/amaru-wear](https://github.com/jeluard/amaru-wear) - WearOS app that shows the latest Cardano chain tip in real time using Amaru.

    <video src="https://github.com/user-attachments/assets/b52a01eb-843e-4f20-afc3-f5fecaa34fe3" width="240" controls></video>

## Experiments

- [jeluard/cardano-zkvms](https://github.com/jeluard/cardano-zkvms) - Experiments around ZKVMs and Cardano, with a goal of proving UPLC execution and verifying proofs in the browser. [Live demo](https://jeluard.github.io/cardano-zkvms/)
