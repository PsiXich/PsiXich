# Artyom Shvidchenko

**C++ Software Engineer | Desktop applications, networking and concurrent programming**

I develop C++ applications with a focus on network communication, desktop tooling and data processing. My projects explore Qt application architecture, asynchronous I/O, multithreading and practical algorithms.

## Technical skills

| Area | Technologies |
| --- | --- |
| Languages | C++ (14/17/20/23), Python, C#, SQL |
| Desktop development | Qt 5/6, Widgets, Model/View |
| Networking | TCP/IP, UDP, WebSockets, MQTT, Boost.Asio |
| Concurrency and data processing | C++ coroutines, threads, mutexes, condition variables, producer-consumer architecture, Boost.Accumulators |
| Libraries and tools | STL, spdlog, toml++, CMake, Git, Qt Test, GCC/Clang, GDB |
| Platforms | Windows, Linux |

## Selected projects

### [NetScope Debug](https://github.com/PsiXich/NetScope_D_bug)

A desktop tool for developing and debugging TCP, WebSocket, UDP and MQTT applications.

- TCP and WebSocket clients and servers, UDP endpoints, and an MQTT 3.1.1 client.
- Multiple connections, live traffic logging, text and hexadecimal payloads, and journal filters.
- Automated Qt tests and a Windows x64 installer with bundled runtime dependencies.

**Stack:** C++, Qt Widgets, Qt Network, Qt WebSockets, Qt MQTT, CMake, Qt Test. The project targets C++14 with Qt 5; Qt 6 requires C++17.

[Latest release](https://github.com/PsiXich/NetScope_D_bug/releases/latest) · [Build and usage documentation](https://github.com/PsiXich/NetScope_D_bug#readme)

### [CSV Median Calculator](https://github.com/PsiXich/csv_median_calculator)

A command-line application for calculating running price-median estimates from CSV market data.

- Single-threaded, multithreaded and batched-reading modes, with a producer-consumer processing pipeline.
- P² median estimation through Boost.Accumulators, TOML configuration and CSV output.
- Test-data generation and a benchmark mode for comparing execution modes.

**Stack:** C++23, Boost.Accumulators, Boost.Program_options, spdlog, toml++, CMake.

### [TCP Logging Server](https://github.com/PsiXich/Server)

A C++20 networking project using Boost.Asio coroutines to receive line-based log records from TCP clients and write per-client log files. Includes configuration parsing and a Python client test script.

### [Linked List Serialization](https://github.com/PsiXich/Serialization-of-a-Doubly-Linked-List-with-Random-Pointers)

A C++17 implementation of binary serialization and deserialization for a doubly linked list with arbitrary node references. Demonstrates pointer-to-index mapping and reconstruction of linked data structures.

## Contact

- Email: [drovin.asm@gmail.com](mailto:drovin.asm@gmail.com)
- Telegram: [@CitraSSS](https://t.me/CitraSSS)
- Habr Career: [career.habr.com/moytracitrus](https://career.habr.com/moytracitrus)
