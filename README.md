# Schumacher Itagiba (schumaz)

4th-semester Information Systems student at the Federal University of Uberlândia (UFU), currently looking for a software engineering internship in backend, systems, or full-stack development.

Contact: [schumaz.business@gmail.com](mailto:schumaz.business@gmail.com)

## About

I got into programming through hardware and OS tuning. Understanding how the system handles memory, CPU scheduling, and I/O bottlenecks naturally led me to care about low-level performance and how software behaves under the hood.

Outside of code and university classes, I spend a lot of time squeezing performance out of my own hardware and network. That usually means dialing in overclock, undervolting, tightening RAM timings, stripping down my OS.

## Stack

- **Systems & Low-Level:** C, C++, Rust
- **Backend & Data:** Java (Spring Boot, JPA), Python, PostgreSQL
- **Frontend & Desktop:** TypeScript, React, Tauri, CSS
- **Tools:** Git, GitHub, Maven, VS Code

## Projects

### [schumaz.gg](https://github.com/schumaz/schumaz.gg)
Desktop companion app for League of Legends built with Rust, Tauri, and React/TypeScript. I chose Tauri over Electron to keep memory usage and background CPU overhead as low as possible while the game runs. It connects directly to the League Client (LCU API) via local WebSockets and REST to detect Champion Select in real time, then scrapes and injects OP.GG rune pages, summoner spells, and item builds automatically. It also includes Ranked tier lists, ARAM builds, and summoner profile history.

### [League_stats_analyzer](https://github.com/schumaz/League_stats_analyzer)
Python tool that pulls match history from the Riot Games API, parses the JSON payloads, and calculates player performance metrics across multiple games.

### [gestao-lixo-eletronico](https://github.com/schumaz/gestao-lixo-eletronico)
REST API built for the Software Development Process course at UFU to track electronic waste disposal, recycling logistics, and mass balance control. Written in Java 17 with Spring Boot, Spring Data JPA, and PostgreSQL.

### [ds2-huffman-compression](https://github.com/schumaz/ds2-huffman-compression)
File compression and decompression tool in C, developed for Data Structures II at UFU. Uses binary trees, priority queues, and bitwise file I/O to implement Huffman coding from scratch.
