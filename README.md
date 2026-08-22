# Awesome MQTT with stars

> A curated list of MQTT related stuff.

MQTT is a lightweight client-server publish/subscribe messaging protocol, optimized for high-latency or unreliable networks. This protocol is a good choice for Internet of Things applications, Telemetry, Sensor Networks, Smart Metering, Home Automation, Messaging and Notification Services.

## Contents

<!--lint disable double-link-->

* [Community Resources](#community-resources)
* [Brokers](#brokers)
* [Cloud](#cloud)
* [Platforms](#platforms)
* [Tools](#tools)
* [Clients](#clients)
* [Scripting](#scripting)
* [Interfaces](#interfaces)
  * [Makers](#makers)
  * [Industry](#industry)
  * [Telephony, PBX](#telephony-pbx)
  * [Operating System](#operating-system)
  * [Monitoring](#monitoring)
  * [Location Tracking](#location-tracking)
  * [Logging](#logging)
  * [Smart Home Hardware Interfaces](#smart-home-hardware-interfaces)
  * [Smart Home Integration Software](#smart-home-integration-software)
  * [Lighting](#lighting)
  * [Home Entertainment](#home-entertainment)
  * [Smart Metering](#smart-metering)
  * [Messaging](#messaging)
  * [Misc](#misc)
* [Visualization, Dashboards](#visualization-dashboards)
* [Architecture, Convention](#architecture-convention)
* [Security, Encryption](#security-encryption)

<!--lint enable double-link-->

### Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

## Community Resources

* [mqtt.org](https://mqtt.org/)
* [MQTT community wiki](https://github.com/mqtt/mqtt.org/wiki) ⭐ 5,123 | 🐛 22 | 🌐 SCSS | 📅 2026-04-16
* [Google Groups: MQTT](https://groups.google.com/g/mqtt)
* [IRC channel #mqtt on the freenode network](irc://irc.freenode.net/mqtt)
* [A list of public brokers](https://moxd.io/2015/10/17/public-mqtt-brokers/)

### Blogs

* [Ben Hardill](https://www.hardill.me.uk/wordpress/tag/mqtt/)
* [Jan-Piet Mens](https://jpmens.net/)
* [Nick O'Leary](https://knolleary.net/)
* [HiveMQ](https://www.hivemq.com/blog/)
* [EMQ](https://www.emqx.com/en/blog)
* [Amazon AWS IoT Blog](https://aws.amazon.com/blogs/iot/tag/mqtt/)

### Talks

* [An Introduction to MQTT: Why HTTP isn't the King of the Internet of Things](https://www.youtube.com/watch?v=LKz1jYngpcU) - Shinji Kim, Robert Bird - Akamai, Samsung Developer Conference 2017.
* [Einführung in MQTT](https://www.youtube.com/watch?v=INYG4-xsa9c) - Dominik Obermaier & Jens Deters, [Building IoT](https://www.buildingiot.de/index.php) conference 2016 (German).

## Brokers

* [EMQ X](https://github.com/emqx/emqx) ⭐ 16,646 | 🐛 255 | 🌐 Erlang | 📅 2026-08-22 - Scalable and Reliable Real-time MQTT Messaging Engine for IoT in 5G Era.
* [Emitter](https://github.com/emitter-io/emitter) ⭐ 4,004 | 🐛 16 | 🌐 Go | 📅 2026-04-29 - A distributed, scalable and fault-tolerant publish-subscribe messaging platform based on MQTT protocol and featuring message storage.
* [Aedes](https://github.com/moscajs/aedes) ⭐ 1,967 | 🐛 102 | 🌐 JavaScript | 📅 2026-08-12 - Barebone MQTT broker that can run on any stream server, the node way.
* [comqtt](https://github.com/wind-c/comqtt) ⭐ 1,173 | 🐛 8 | 🌐 Go | 📅 2026-07-21 - A lightweight, high-performance go mqtt server(v3.0|v3.1.1|v5.0) supporting distributed cluster.
* [esp\_uMQTT\_broker](https://github.com/martin-ger/esp_mqtt) ⭐ 309 | 🐛 27 | 🌐 C | 📅 2023-04-15 - A basic MQTT Broker on the ESP8266.
* [Eclipse Amlen](https://github.com/eclipse/amlen) ⭐ 53 | 🐛 18 | 🌐 C | 📅 2026-07-26 - A scalable, secure, easy to use message broker that can be used for IoT, web and mobile use-cases. Open-sourced from IBM MessageSight.
* [Ably](https://www.ably.io/documentation/mqtt) - MQTT broker service and protocol adapter.
* [ActiveMQ](https://activemq.apache.org/) - A fast Java multiprotocol messaging and Integration Patterns server.
* [Bevywise MQTTRoute](https://www.bevywise.com/mqtt-broker/) - MQTTRoute is an extendable & Scalable MQTT Broker with customizable UI, flexible storage & security options for all IoT / IIoT Implementation.
* [BifroMQ](https://bifromq.apache.org) - Java-based high-performance MQTT broker with native multi-tenancy for large-scale IoT.

<!--lint disable double-link-->

* [hbmqtt Broker](https://github.com/beerfactory/hbmqtt) ⭐ 818 | 🐛 103 | 🌐 Python | 📅 2022-07-24 - Python MQTT broker using asyncio.

<!--lint enable double-link-->

* [Moquette](https://github.com/moquette-io/moquette) ⭐ 2,453 | 🐛 138 | 🌐 Java | 📅 2026-08-18 - Java MQTT lightweight broker.
* [KMQTT](https://github.com/davidepianca98/KMQTT) ⭐ 295 | 🐛 25 | 🌐 Kotlin | 📅 2025-06-23 - Kotlin Multiplatform MQTT broker, both embeddable and standalone.
* [hrotti](https://github.com/alsm/hrotti) ⭐ 125 | 🐛 9 | 🌐 Go | 📅 2020-12-09 - A MQTT broker written in Go.
* [Keel MQTT Gateway](https://github.com/keel-iot/keel-mqtt-gateway) ⭐ 5 | 🐛 11 | 🌐 Go | 📅 2026-08-10 - Distributed, cloud-native MQTT broker in Go built on mochi-mqtt, using Raft for strongly-consistent session ownership and ACL, with a gossip-backed routing table (Olric).
* [HiveMQ](https://www.hivemq.com/) - Java MQTT Broker that supports MQTT 3.1, 3.1.1 and 5.0. Commercial and open source editions available.
* [Mosca](https://www.mosca.io/) - Node.js MQTT broker, which can be used Standalone or Embedded in another Node.js application.
* [Mosquitto](https://mosquitto.org/) - *"*The"** Open Source MQTT Broker.

<!--lint disable double-link-->

* [mqtt5](https://github.com/LabOverWire/mqtt-lib) ⭐ 55 | 🐛 5 | 🌐 Rust | 📅 2026-08-19 - Async MQTT v5.0 broker in Rust with TCP, TLS, WebSocket, and QUIC transport, plus authentication, ACL, bridging, and session persistence.

<!--lint enable double-link-->

* [tbmq](https://github.com/thingsboard/tbmq) ⭐ 752 | 🐛 10 | 🌐 Java | 📅 2026-08-20 - Open-source, scalable, fault-tolerant and durable messaging broker for millions of IoT devices.
* [Mystique](https://github.com/TheThingsIndustries/mystique) ⭐ 23 | 🐛 9 | 🌐 Go | 📅 2023-03-07 - An extendable MQTT broker written in Go, with HTTP capabilities for observability. Implements MQTT v3.1.1.
* [TrailMQ](https://github.com/RainerGewalt/TrailMQ) ⭐ 4 | 🐛 11 | 🌐 Shell | 📅 2026-08-15 - Self-hosted MQTT broker with policy enforcement and a reviewable record of broker decisions, for regulated and industrial systems.
* [MyQttHub](https://myqtthub.com) - Cloud MQTT broker.
* [RabbitMQ](https://www.rabbitmq.com/mqtt.html) - High performance messaging broker with MQTT Adapter.
* [RobustMQ](http://robustmq.com) - Multi-protocol brokers written in Rust.
* [SurgeMQ](https://zhen.org/categories/surgemq/) - High Performance MQTT Server and Client Libraries in Go.
* [VerneMQ](https://vernemq.com/) - Apache2 licensed distributed MQTT broker, developed in Erlang.

<!--lint disable double-link-->

* [Vert.x MQTT Server](https://github.com/vert-x3/vertx-mqtt) ⭐ 214 | 🐛 47 | 🌐 Java | 📅 2026-08-11 - Vert.x component to handle connections, communication and messages exchange with remote MQTT clients.

<!--lint enable double-link-->

* [Waterstream](https://waterstream.io/) - MQTT broker leveraging Apache Kafka as its own storage and distribution engine.
* [NanoMQ](https://github.com/nanomq/nanomq) ⭐ 2,592 | 🐛 64 | 🌐 C | 📅 2026-08-21 - A light-weight and Blazing-fast MQTT Broker for IoT Edge platform.

## Cloud

* [Adafruit IO](https://io.adafruit.com) - Data-oriented IoT framework and libraries.
* [Alibaba Cloud IoT Platform](https://www.alibabacloud.com/product/iot) - Provides secure and reliable communication between devices and the IoT Platform which allows you to manage a large number of devices on a single IoT Platform.
* [AWS IoT Core](https://aws.amazon.com/iot-core/) - Managed cloud broker service supporting MQTT, MQTT over WSS, HTTPS and LoRaWAN.
* [Azure IoT Hub](https://azure.microsoft.com/en-us/services/iot-hub/) - Enable highly secure and reliable communication between your IoT application and the devices it manages. Azure IoT Hub provides a cloud-hosted solution backend to connect virtually any device. Extend your solution from the cloud to the edge with per-device authentication, built-in device management, and scaled provisioning.
* [CloudMQTT](https://www.cloudmqtt.com/) - Hosted message broker for the Internet of Things. Perfectly configured and optimized message queues for IoT, ready in seconds.
* [CloudAMQP](https://www.cloudamqp.com/docs/mqtt.html) - Hosted AMQP brokers with MQTT support.
* [CrystalMQ](https://www.bevywise.com/hosted-mqtt-server/) - Fully Managed Cloud MQTT Broker for large scale deployments.
* [flespi](https://flespi.com/mqtt-broker) - Free and secure cloud MQTT broker with private namespaces, MQTT 3.1.1 and MQTT 5.0 support and gorgeous limits.
* [Google Cloud IoT](https://cloud.google.com/solutions/iot/) - Cloud managed MQTT service.
* [HiveMQ Cloud](https://www.hivemq.com/cloud/) - Cloud managed MQȚT service.

## Platforms

* [IoT DC3](https://github.com/pnoker/iot-dc3) ⭐ 949 | 🐛 32 | 🌐 Java | 📅 2026-08-20 - Fully open-source, distributed industrial IoT platform built on Spring Cloud, with 28 built-in protocol drivers (including MQTT), AI-powered operations via Spring AI, and microservice architecture. ([Docs](https://docs.dc3.site))
* [ForestHub](https://foresthub.ai) - Edge AI agent platform; its open-source runtime [edge-agents](https://github.com/ForestHubAI/edge-agents) ⭐ 97 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-29 orchestrates AI agents on Linux edge gateways with MQTT as a first-class workflow transport, running offline with local SLMs alongside cloud LLMs.
* [Iotellect](https://iotellect.com/) - Low-code IoT/IIoT platform for industrial automation, SCADA, BMS and remote monitoring. Supports MQTT, OPC-UA, Modbus and 100+ protocols with visual development tools and edge-cloud integration.
* [mainflux](https://www.mainflux.com/) - Device management, data aggregation, data management, data analytics,connectivity and message routing and event management. Supported by Linux Software Foundation.
* [thingsboard](https://thingsboard.io/) - Device management, data collection, processing, event management, and visualization for your IoT projects.

## Tools

* [MQTTX](https://github.com/emqx/MQTTX) ⭐ 5,029 | 🐛 109 | 🌐 TypeScript | 📅 2026-08-17 - Cross-platform MQTT desktop client open sourced by EMQ, which supports macOS, Linux, and Windows.
* [MQTT TUI](https://github.com/EdJoPaTo/mqttui) ⭐ 717 | 🐛 10 | 🌐 Rust | 📅 2026-08-09 - Simple lightweight terminal based MQTT monitor and publisher.
* [hivemq-mqtt-web-client](https://github.com/hivemq/hivemq-mqtt-web-client) ⭐ 363 | 🐛 7 | 🌐 JavaScript | 📅 2023-07-27 - Browser-based MQTT client that utilizes MQTT over websockets. [Direct Link](https://www.hivemq.com/demos/websocket-client/)
* [MQTT CLI](https://github.com/hivemq/mqtt-cli) ⭐ 362 | 🐛 13 | 🌐 Java | 📅 2026-08-21 - A command line interface for connecting various MQTT clients supporting MQTT 5.0 and 3.1.1.
* [mqtt-malaria](https://github.com/etactica/mqtt-malaria) ⭐ 265 | 🐛 12 | 🌐 Python | 📅 2021-08-18 - Scalability and load testing utilities for MQTT environments.
* [mockd](https://github.com/getmockd/mockd) ⭐ 143 | 🐛 11 | 🌐 Go | 📅 2026-08-18 - Multi-protocol mock server with a built-in MQTT broker supporting QoS 0-2, retained messages, topic patterns, and device simulation for IoT development and testing.
* [mqtt-admin](https://github.com/hobbyquaker/mqtt-admin/) ⭐ 129 | 🐛 5 | 🌐 JavaScript | 📅 2021-06-29 - Web based MQTT frontend. [Direct Link](https://hobbyquaker.github.io/mqtt-admin/).
* [mqttcli](https://github.com/shirou/mqttcli) ⭐ 123 | 🐛 3 | 🌐 Go | 📅 2026-04-13 - MQTT Client for shell scripting.
* [mqtt-benchmark](https://github.com/chirino/mqtt-benchmark) ⭐ 121 | 🐛 2 | 🌐 JavaScript | 📅 2012-03-16 - A benchmarking tool for MQTT Servers.
* [MQTT Board](https://github.com/flespi-software/MQTT-Board) ⭐ 103 | 🐛 7 | 🌐 Vue | 📅 2026-06-21 - Open-source diagnostic-oriented MQTT client tool.
* [Wireshark-MQTT](https://github.com/menudoproblema/Wireshark-MQTT) ⭐ 95 | 🐛 2 | 🌐 Lua | 📅 2015-09-04 - MQTT dissector for Wireshark.
* [mqtt-fuzz](https://github.com/F-Secure/mqtt_fuzz) ⭐ 81 | 🐛 1 | 🌐 Python | 📅 2022-03-21 - A simple fuzzer for the MQTT protocol.
* [MQTTInspector](https://github.com/ckrey/MQTTInspector) ⚠️ Archived - A general MQTT testing app for iOS (iPhone and iPad).
* [Python MQTT Client Shell](https://github.com/bapowell/python-mqtt-client-shell) ⭐ 58 | 🐛 0 | 🌐 Python | 📅 2019-08-23 - Text console-based, interactive shell for exercising various tasks associated with MQTT client communications.
* [LazyMQTT](https://github.com/ScottFelder/lazymqtt) ⭐ 43 | 🐛 0 | 🌐 Rust | 📅 2026-08-12 - A fast, terminal-UI MQTT client written in Rust — inspired by MQTT Explorer, but keyboard-driven and living in your terminal.
* [mqtt-wall](https://github.com/bastlirna/mqtt-wall) ⭐ 43 | 🐛 9 | 🌐 JavaScript | 📅 2020-12-08 - Subscription only web-based client – like Twitter wall for MQTT.
* [mqtt-mirror](https://github.com/4nte/mqtt-mirror) ⭐ 42 | 🐛 5 | 🌐 Go | 📅 2026-06-19 - Mirror MQTT traffic from one broker to another. Available as a CLI tool, Helm chart or Docker image.
* [mqtt\_recorder](https://github.com/rpdswtk/mqtt_recorder) ⭐ 41 | 🐛 5 | 🌐 Python | 📅 2025-06-29 - Simple cli tool for recording and replaying MQTT messages.
* [moxy](https://github.com/jvermillard/moxy) ⚠️ Archived - A Golang MQTT proxy providing useful output traces to monitor and troubleshoot your MQTT communications.
* [imqtt](https://github.com/shafreeck/imqtt) ⭐ 21 | 🐛 0 | 🌐 Python | 📅 2016-08-05 - Interactive MQTT packet manipulation shell based on IPython.
* [mqtt-client](https://github.com/sdeancos/mqtt-client) ⭐ 17 | 🐛 0 | 🌐 Python | 📅 2025-08-01 - Simple MQTT Client command line (Python) (use paho lib).
* [mqtt-shell](https://github.com/pidster-dot-org/mqtt-shell) ⭐ 17 | 🐛 0 | 🌐 Java | 📅 2013-07-10 - A simple interactive shell for MQTT.
* [VSMQTT](https://github.com/rpdswtk/vsmqtt) ⭐ 17 | 🐛 3 | 🌐 TypeScript | 📅 2026-08-19 - Simple MQTT client integrated in Visual Studio Code.
* [Mer-cli](https://github.com/iotmertech/iot-data-generator) ⭐ 15 | 🐛 0 | 🌐 Rust | 📅 2026-07-03 - A high-performance IoT data generator written in Rust. Supports MQTT, HTTP, and TCP for simulating realistic sensor payloads with Handlebars templates.
* [mqtt-wildcard](https://github.com/hobbyquaker/mqtt-wildcard) ⭐ 13 | 🐛 0 | 🌐 JavaScript | 📅 2018-05-09 - Node.js Module to match a MQTT Topic against wildcards.
* [mqtt-utils](https://github.com/dsell/mqtt-utils) ⭐ 12 | 🐛 0 | 🌐 JavaScript | 📅 2013-10-20 - A collection of MQTT utilities.
* [mqtt-stats](https://github.com/gambitcomminc/mqtt-stats) ⭐ 11 | 🐛 0 | 🌐 Python | 📅 2023-07-13 - Subscriber client to monitor MQTT Topic Statistics.
* [mqtt\_monitor](https://github.com/filipsPL/mqtt-monitor) ⭐ 11 | 🐛 0 | 🌐 Python | 📅 2022-05-04 - Simple and lightweight console moniotor for mqtt topics, with eye-candies, in python 3.
* [mqtt-forget](https://github.com/hobbyquaker/mqtt-forget) ⭐ 10 | 🐛 0 | 🌐 JavaScript | 📅 2018-02-25 - Command line tool to remove retained MQTT topics by wildcard.
* [mqtt\_tree](https://github.com/poggenpower/mqtt_tree) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2025-11-10 - Displays all Topics in an expandable tree, helps to get an overview if you have a lot of clients publishing. (python, tkinter)
* [mqttkit](https://github.com/keyp-dev/mqttkit) ⭐ 4 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-27 - Elysia-style application framework for MQTT on Bun and TypeScript. Compose broker adapters, ordered middleware, typed topic routes, MQTT 5 RPC, and AsyncAPI 3.0 docs with `new MqttApp().use(...)`.
* [dsh-mqtt](https://github.com/UllrAI/dsh-mqtt) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-22 - MQTT protocol driver and long-running agent worker gateway for DeepSeek Harness, enabling remote clients to submit, steer, cancel, and observe agent work.
* [mqttcommander](https://github.com/vroomfondel/mqttcommander) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2026-02-26 - A console-based MQTT client and commander, especially useful for IoT, Tasmota, and Node-RED setups.
* [homie-home-assistant-discovery](https://github.com/labodj/homie-home-assistant-discovery) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-20 - Node.js CLI and library that maps Homie MQTT metadata to Home Assistant MQTT discovery payloads.
* [MQTTForge](https://github.com/ibrahimilkhan/mqtt-forge) ⭐ 0 | 🐛 5 | 🌐 TypeScript | 📅 2026-08-20 - Test console that builds a broker's topics into a live tree, shows every frame on the wire, and publishes by hand. Desktop app for macOS, Windows and Linux, or a single Docker image.
* [RunMQTT MQTT Topic ACL Linter](https://runmqtt.com/mqtt-acl-linter) - Browser-based, local-only validator for MQTT topic-filter ACLs that checks wildcard breadth, tenant boundaries, publish/subscribe direction, placeholders, and overlapping rules. [Source and method](https://github.com/visoar/mqtt-acl-linter) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-10.
* [IoT-Testware](https://projects.eclipse.org/projects/technology.iottestware) - The Eclipse IoT-Testware is a collection of conformance test suites for IoT protocols enriched with additional tools for fuzzing and performance testing.
* [LabOverWire](https://laboverwire.com/features) - Visual diagram editor for designing MQTT topologies, built with Rust (WebAssembly) and TypeScript. Features live in-browser simulation, code generation, and AsyncAPI export.
* [mqtt-spy](https://kamilfb.github.io/mqtt-spy/) - Java based MQTT frontend. Supports scripting.
* [mqtt-studio](https://www.mqttstudio.com) - A practical MQTT Tool with an innovative UI, designed for developers to efficiently create, test, and manage MQTT-based applications, enhancing their development and support workflows.
* [MQTT.fx](https://mqttfx.jensd.de/) - MQTT Client written in Java based on Eclipse Paho. Supports scripting.
* [MQTTLens](https://chrome.google.com/webstore/detail/mqttlens/hemojaaeigabkbcookmlgmdigohjobjm) - A Google Chrome application, which connects to a MQTT broker and is able to subscribe and publish to MQTT topics.
* [MQTT Explorer](https://mqtt-explorer.com/) - Tool to visualize your MQTT topics in a topic hierarchy, a MQTT swiss-army knife.
* [SimpleMQTT](https://simplemqtt.theoi.de/) - A Slack app to send messages from Slack to MQTT brokers with slash commands.
* [MIMIC MQTT Simulator](https://www.gambitcomm.com/site/mqttsimulator.php) - Simulate up to 100,000 MQTT clients per server for development/testing/deployment of IoT applications.

<!--lint disable double-link-->

* [mqttv5](https://github.com/LabOverWire/mqtt-lib) ⭐ 55 | 🐛 5 | 🌐 Rust | 📅 2026-08-19 - Unified MQTT v5.0 CLI for publishing, subscribing, running a broker, and benchmarking with multi-transport support.

<!--lint enable double-link-->

## Clients

### Multi-Platform

* [Paho](https://www.eclipse.org/paho/) - Open source client implementations for C,C++, Java, Python, JavaScript, GoLang, C#, Rust, Android and Embedded (Arduino/mbed).
* [mosquitto-clients](https://mosquitto.org/download/) - [mosquitto\_pub](https://mosquitto.org/man/mosquitto_pub-1.html) and [mosquitto\_sub](https://mosquitto.org/man/mosquitto_sub-1.html) CLI clients for most operating systems and [libmosquitto](https://mosquitto.org/man/libmosquitto-3.html) for integration.

### Python

* [aiomqtt](https://github.com/empicano/aiomqtt) ⭐ 571 | 🐛 14 | 🌐 Python | 📅 2026-04-23 - The idiomatic asyncio MQTT client.
* [gmqtt](https://github.com/wialon/gmqtt) ⭐ 450 | 🐛 28 | 🌐 Python | 📅 2026-06-14 - Python MQTT v5.0 client (asyncio-based).

<!--lint disable double-link-->

* [hbmqtt Client](https://github.com/beerfactory/hbmqtt) ⭐ 818 | 🐛 103 | 🌐 Python | 📅 2022-07-24 - Python MQTT client using asyncio.

<!--lint enable double-link-->

* [MiniMQTT](https://github.com/adafruit/Adafruit_CircuitPython_MiniMQTT) ⭐ 81 | 🐛 33 | 🌐 Python | 📅 2026-05-19 - MQTT Client Library for CircuitPython.

### JavaScript

* [MQTT.js](https://github.com/mqttjs) - MQTT client for Node.js.
* [mqtt-elements](https://github.com/mqttjs/mqtt-elements) ⭐ 27 | 🐛 8 | 🌐 JavaScript | 📅 2016-10-28 - Polymer elements for MQTT.
* [mqtt-wrapper](https://www.webcomponents.org/element/hobbyquaker/mqtt-wrapper/elements/mqtt-wrapper) - Polymer Element that wraps other Elements and links them to MQTT topics.

<!--lint disable double-link-->

* [Vert.x Client](https://github.com/vert-x3/vertx-mqtt) ⭐ 214 | 🐛 47 | 🌐 Java | 📅 2026-08-11 - Vert.x component that provides methods for connecting/disconnecting to a broker, publishing messages and subscribing to topics.

<!--lint enable double-link-->

### Java

* [hivemq-mqtt-client](https://github.com/hivemq/hivemq-mqtt-client) ⭐ 1,113 | 🐛 76 | 🌐 Java | 📅 2026-08-22 - High-performance Java MQTT client library with different API flavours for MQTT 5.0 and 3.1.1.

### Erlang or Elixir

* [emqttc](https://github.com/emqx/emqtt) ⭐ 439 | 🐛 39 | 🌐 Erlang | 📅 2026-08-21 - Asynchronous Erlang MQTT Client.
* [mqttex](https://github.com/alfert/mqttex) ⭐ 45 | 🐛 2 | 🌐 Elixir | 📅 2015-05-14 - MQTT implementation in Elixir.

### Ballerina

* [ballerina-mqtt](https://github.com/ballerina-platform/module-ballerina-mqtt) ⭐ 106 | 🐛 3 | 🌐 Java | 📅 2026-07-19 - Ballerina MQTT client based on paho-mqtt.

### C or C++

* [MQTT-C](https://github.com/LiamBindle/MQTT-C) ⭐ 895 | 🐛 42 | 🌐 C | 📅 2024-05-12 - A portable MQTT C client for embedded systems and PCs alike.
* [mqtt\_cpp](https://github.com/redboltz/mqtt_cpp) ⭐ 483 | 🐛 51 | 🌐 C++ | 📅 2026-02-12 - MQTT client for C++14 based on Boost.Asio.
* [wolfMQTT](https://www.wolfssl.com/products/wolfmqtt/) - A client implementation of the MQTT written in C for embedded use. It supports SSL/TLS via the wolfSSL library.

### Clojure

* [Machine Head](https://github.com/clojurewerkz/machine_head) ⭐ 81 | 🐛 0 | 🌐 Clojure | 📅 2023-10-14 - A Clojure MQTT Client.

### Dart

* [mqtt.dart](https://github.com/jnguillerme/mqtt.dart) ⭐ 51 | 🐛 3 | 🌐 Dart | 📅 2019-01-22 - Dart MQTT client.

### C# / .NET

* [MQTTnet](https://github.com/chkr1011/MQTTnet) ⭐ 5,061 | 🐛 190 | 🌐 C# | 📅 2026-08-09 - MQTT client and broker .NET implementations.
* [HiveMQtt](https://github.com/hivemq/hivemq-mqtt-client-dotnet) ⭐ 97 | 🐛 9 | 🌐 C# | 📅 2026-08-17 - MQTT 5.0 compliant secure client with automatic back pressure management and TCP & WebSocket transport support.

### Delphi

* [delphi-mqtt](https://github.com/pjde/delphi-mqtt) ⭐ 163 | 🐛 11 | 🌐 Pascal | 📅 2020-03-29 - MQTT server and client components.
* [TMQTTClient](https://github.com/jamiei/Delphi-TMQTT2) ⭐ 26 | 🐛 7 | 🌐 Pascal | 📅 2015-11-11 - MQTT Client Library for Delphi. Alpha and long term unmaintained.

### GoLang

* [MQTT for Go](https://github.com/jeffallen/mqtt) ⭐ 825 | 🐛 4 | 🌐 Go | 📅 2023-12-08 - MQTT Clients, Servers and Load Testers in Go.
* [go-mqtt](https://github.com/go-mqtt/mqtt) ⭐ 8 | 🐛 0 | 🌐 Go | 📅 2021-07-02 - MQTT client.

### Lua

* [luamqtt](https://github.com/xHasKx/luamqtt/) ⭐ 183 | 🐛 9 | 🌐 Lua | 📅 2026-07-05 - Pure-lua MQTT v3.1.1 and v5.0 client.
* [mqtt\_lua](https://geekscape.github.io/mqtt_lua/) - MQTT Client library for the Lua language.

### Objective-C

* [MQTT-Client-Framework](https://github.com/novastone-media/MQTT-Client-Framework) ⭐ 1,882 | 🐛 92 | 🌐 Objective-C | 📅 2023-09-12 - iOS, macOS, tvOS native ObjectiveC MQTT Client Framework.
* [MQTTKit](https://github.com/mobile-web-messaging/MQTTKit) ⭐ 461 | 🐛 29 | 🌐 C | 📅 2020-12-18 - MQTT Objective-C client for iOS.

### PHP

* [Mosquitto-PHP](https://github.com/mgdm/Mosquitto-PHP) ⭐ 541 | 🐛 53 | 🌐 C | 📅 2023-10-03 - A wrapper for the Mosquitto MQTT client library for PHP.

### Ruby

* [ruby-mqtt](https://github.com/njh/ruby-mqtt) ⭐ 560 | 🐛 31 | 🌐 Ruby | 📅 2026-05-08 - Pure Ruby gem that implements the MQTT protocol.

### Rust

* [rumqtt](https://github.com/AtherEnergy/rumqtt) ⚠️ Archived - A fast, lock free pure Rust MQTT client.
* [mqtt-rs](https://github.com/zonyitoo/mqtt-rs) ⭐ 186 | 🐛 6 | 🌐 Rust | 📅 2024-03-13 - MQTT protocol library for Rust.
* [mqtt-typed-client](https://github.com/holovskyi/mqtt-typed-client) ⭐ 10 | 🐛 7 | 🌐 Rust | 📅 2026-07-28 - Type-safe async MQTT client built on rumqttc, with derive macros for typed topics, automatic (de)serialization, and tree-based message routing.

<!--lint disable double-link-->

* [mqtt5](https://github.com/LabOverWire/mqtt-lib) ⭐ 55 | 🐛 5 | 🌐 Rust | 📅 2026-08-19 - Complete async MQTT v5.0 client and broker library for Rust with TCP, TLS, WebSocket, and QUIC support.

<!--lint enable double-link-->

### Swift

* [CocoaMQTT](https://github.com/emqx/CocoaMQTT) ⭐ 1,748 | 🐛 111 | 🌐 Swift | 📅 2026-07-31 - MQTT for iOS and macOS written with Swift.
* [Moscapsule](https://github.com/flightonary/Moscapsule) ⭐ 274 | 🐛 40 | 🌐 C | 📅 2026-08-14 - MQTT Client for iOS written in Swift.

### TCL

* [tcl-mqtt](https://github.com/Tingenek/tcl-mqtt) ⭐ 5 | 🐛 1 | 🌐 Tcl | 📅 2023-02-10 - Small library to connect to a MQTT broker. Very, very basic, and not maintained.

## Scripting

* [mqtt-scripts](https://github.com/hobbyquaker/mqtt-scripts/) ⚠️ Archived - Node.js based script runner.
* [logic4mqtt](https://github.com/owagner/logic4mqtt) ⭐ 17 | 🐛 1 | 🌐 Java | 📅 2016-02-29 - Java based Logic and scripting engine for use with MQTT. Uses Java's general scripting interface, so scripts can be written in a multitude of languages like JavaScript, Groovy etc.
* [Node-RED](https://nodered.org/) - A visual tool for wiring the Internet of Things.

## Interfaces

### Makers

* [Basecamp](https://github.com/ct-Open-Source/Basecamp) ⚠️ Archived - An Arduino library to ease the use of the ESP32 in IoT projects. See [c't Magazin 2'2018 (German)](https://www.heise.de/select/ct/2018/2/1515452111258448).
* [RFM69-MQTT-client](https://github.com/computourist/RFM69-MQTT-client) ⭐ 81 | 🐛 0 | 🌐 Arduino | 📅 2017-01-25 - Arduino RFM69 based sensors and MQTT gateway.
* [deskmate](https://github.com/rbaron/deskmate) ⚠️ Archived - A hackable & portable MQTT-powered mini dashboard and control center.
* [rpi2mqtt](https://github.com/hobbyquaker/rpi2mqtt) ⭐ 23 | 🐛 2 | 🌐 JavaScript | 📅 2018-01-05 - Connect a RaspberryPis GPIOs and 1-Wire Temperature Sensors to MQTT.
* [xbee2mqtt](https://github.com/xoseperez/xbee2mqtt) ⭐ 23 | 🐛 3 | 🌐 Python | 📅 2016-02-04 - XBee to MQTT gateway.
* [arduinoTemps2mqtt](https://github.com/matbor/arduinoTemps2mqtt) ⚠️ Archived - Arduino sketch, grab One-wire Temperature's and publish to a MQTT broker.
* [MySensors](https://www.mysensors.org/) - Arduino NRF24L01 based sensor network with support for an MQTT gateway.

#### ESP

* [pubsubclient](https://github.com/knolleary/pubsubclient) ⭐ 4,014 | 🐛 567 | 🌐 C++ | 📅 2026-06-10 - A client library for the Arduino Ethernet Shield that provides support for MQTT.
* [esp\_mqtt](https://github.com/tuanpmt/esp_mqtt) ⭐ 1,172 | 🐛 41 | 🌐 C | 📅 2020-12-22 - MQTT client library for ESP8266.
* [ESP32-BLE2MQTT](https://github.com/shmuelzon/esp32-ble2mqtt) ⭐ 775 | 🐛 56 | 🌐 C | 📅 2025-08-16 - BLE to MQTT bridge, exposes BLE GATT characteristics as MQTT topics for bidirectional communication.
* [ESP8266MQTTMesh](https://github.com/PhracturedBlue/ESP8266MQTTMesh) ⭐ 265 | 🐛 26 | 🌐 C++ | 📅 2025-02-22 - MQTT over mesh WiFi integrated library for ESP8266.
* [mqtt-ir-transceiver](https://github.com/piotrC4/mqtt-ir-transceiver) ⭐ 143 | 🐛 16 | 🌐 C++ | 📅 2020-11-17 - ESP8266 based bidirectional gateway between MQTT and IR. Use with PlatformIO.
* [nodemcu-gpiomqtt](https://github.com/hobbyquaker/nodemcu-gpiomqtt) ⭐ 10 | 🐛 1 | 🌐 Lua | 📅 2018-04-17 - Lua script to connect ESP8266 GPIOs to MQTT.
* [mqtt-with-micropython](https://docs.pycom.io/tutorials/networkprotocols/mqtt/) - Connect to MQTT with micropython and wipy/others (ESP32 inside).

#### Firmwares for ESP based Devices

There are many inexpensive smart home Wi-Fi devices based on inexpensive ESP8266 chip *(see: [1](https://templates.blakadder.com/index.html), [2](https://github.com/xoseperez/espurna/wiki/Hardware) ⭐ 3,053 | 🐛 303 | 🌐 C++ | 📅 2026-04-15, [3](https://www.letscontrolit.com/wiki/index.php?title=ESP_Hardware))*. Most of them can be reflashed with custom firmware.
Here are complete firmwares to turn them into MQTT-controlled smart home nodes:

* [ESPEasy](https://www.letscontrolit.com/wiki/index.php?title=ESPEasy) - Turns ESP into a multifunction sensor device for <abbr title="Home automation">HA</abbr> solutions with web-based configuration.
* [ESPHome](https://esphome.io/) - Builds ESP8266/ESP32 firmware from concise YAML descriptions, uploads to and manages flashed devices.
* [Espurna](https://github.com/xoseperez/espurna) ⭐ 3,053 | 🐛 303 | 🌐 C++ | 📅 2026-04-15 - <abbr title="Home automation">HA</abbr> firmware for ESP8266-based devices with rich web UI and ≈120 devices supported out of the box.

<!--lint disable double-link-->

* [HomeGenie Mini](https://homegenie.it/) - Smart device firmware for ESP8266/ESP32 supporting remote monitoring and controlling via MQTT with end-to-end encryption. The firmware is open source and it can be uploaded to the ESP device directly from the website.

<!--lint enable double-link-->

* [Sonoff-Tasmota](https://github.com/arendst/Tasmota) ⭐ 24,722 | 🐛 10 | 🌐 C | 📅 2026-08-22 - Firmware for ESP8266 devices with web-based configuration. ≈500 devices supported (not only Sonoffs).
* [OpenMQTTGateway](https://github.com/1technophile/OpenMQTTGateway) ⭐ 4,080 | 🐛 51 | 🌐 C++ | 📅 2026-08-20 - MQTT gateway for ESP8266, ESP32, Sonoff RF Bridge or Arduino with bidirectional 433mhz/315mhz/868mhz, Infrared communications, BLE, beacons detection, mi flora, mi jia, LYWSD02, LYWSD03MMC, Mi Scale compatibility, SMS & LORA.
* [WiFi-IoT](https://wifi-iot.com/p/wiki/) - ESP8266/ESP32 firmware builder. Partly in Russian. Free features are limited.

### Industry

* [CODESYS-MQTT](https://github.com/stefandreyer/CODESYS-MQTT) ⭐ 143 | 🐛 4 | 📅 2023-11-29 - A MQTT client for CODESYS PLC.
* [mqtt2opcua](https://github.com/nzfarmer1/mqtt2opcua) ⭐ 90 | 🐛 4 | 🌐 JavaScript | 📅 2022-01-14 - Bi Directional MQTT to OPCUA Bridge.
* [spicierModbus2mqtt](https://github.com/mbs38/spicierModbus2mqtt) ⭐ 68 | 🐛 2 | 🌐 Python | 📅 2025-07-24 - Modbus master which publishes register values via MQTT.
* [OPC Router](https://www.opc-router.com/4_1-mqtt-client-opc-router-plug-in-en/) - MQTT Gateway (publisher/subscriber) with various plug-ins (OPC UA Bridge, SQL Bridge, REST Bridge, SAP Bridge).

### Telephony, PBX

* [sms2mqtt](https://github.com/Domochip/sms2mqtt) ⭐ 67 | 🐛 5 | 🌐 Python | 📅 2025-11-24 - Docker Gateway to send/receive SMS through MQTT using an USB GSM dongle (gammu).
* [sip2mqtt](https://github.com/MartyTremblay/sip2mqtt) ⭐ 45 | 🐛 2 | 🌐 Python | 📅 2021-01-26 - A SIP monitoring script that publishes incoming calls with CallerID to MQTT.
* [agi-mqtt](https://github.com/zeha/agi-mqtt) ⭐ 34 | 🐛 1 | 📅 2014-04-28 - Interface between Asterisk and MQTT.
* [fritz2mqtt](https://github.com/akentner/fritz2mqtt) ⭐ 7 | 🐛 3 | 🌐 TypeScript | 📅 2026-08-20 - Connect FRITZ!Box to MQTT.

### Operating System

* [mqttlauncher](https://github.com/jpmens/mqtt-launcher) ⭐ 187 | 🐛 3 | 🌐 Python | 📅 2024-11-16 - Execute shell commands triggered by published MQTT messages.
* [psmqtt](https://github.com/eschava/psmqtt) ⭐ 184 | 🐛 8 | 🌐 Python | 📅 2026-03-25 - Utility reporting system health and status via MQTT.
* [WinThing](https://github.com/msiedlarek/winthing) ⚠️ Archived - Remotely control Windows through MQTT.
* [mqttwatchdir](https://github.com/jpmens/mqtt-watchdir) ⭐ 41 | 🐛 0 | 🌐 Python | 📅 2018-12-06 - Recursively watch a directory for modifications and publish file content to an MQTT broker.
* [mqtt-os-status](https://github.com/oskarhagberg/mqtt-os-status) ⭐ 19 | 🐛 1 | 🌐 Shell | 📅 2014-04-07 - Operating-system related data, published to an MQTT broker at fixed intervals.
* [mqttpc](https://github.com/hobbyquaker/mqttpc) ⭐ 9 | 🐛 1 | 🌐 JavaScript | 📅 2023-09-05 - Control processes via MQTT. Ability to send signals via MQTT and to publish stdout/stderr or pipe MQTT payloads into stdin.
* [updates2mqtt](https://updates2mqtt.rhizomatics.org.uk) - Check for Docker image updates and publish to MQTT, in structure to support Home Assistant's automated Updates and Discovery.

### Monitoring

* [check-mqtt](https://github.com/jpmens/check-mqtt) ⭐ 66 | 🐛 1 | 🌐 Python | 📅 2026-02-11 - A Nagios/Icinga plugin for checking connectivity to an MQTT broker.
* [notify-by-mqtt](https://github.com/jpmens/notify-by-mqtt) ⭐ 16 | 🐛 0 | 🌐 Python | 📅 2022-09-13 - A Nagios/Icinga notification module which wraps data into JSON and fires it off to an MQTT broker.
* [mqtt2notifysend](https://github.com/David-Lor/MQTT2NotifySend) ⭐ 13 | 🐛 0 | 🌐 Shell | 📅 2021-11-20 - Subscribe to a topic and show notifications from MQTT messages on Ubuntu & other notify-send compatible Linux distros.
* [nag2mqtt](https://github.com/DE-IBH/nag2mqtt) ⭐ 7 | 🐛 0 | 🌐 C | 📅 2017-10-01 - Nagios event broker to MQTT gateway.
* [ccusage-mqtt](https://github.com/george-vice/ccusage-mqtt) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2026-06-13 - Publishes Claude Code (Anthropic's AI coding agent) usage telemetry to MQTT with Home Assistant auto-discovery. 15 sensors, mood classifier.
* [mqttwarn](https://mqttwarn.readthedocs.io/en/latest/) - Route and transform MQTT notifications, with 70+ built-in adapters for databases, messaging and other notification sinks.
* [snmp2mqtt](https://c0d3.sh/andre/snmp2mqtt) - Python based SNMP v2 and v3 bridge to MQTT, active project in late 2025.

### Location Tracking

* [OwnTracks](https://owntracks.org/) - Location tracking and geofencing for MQTT.

### Logging

* [influx4mqtt](https://github.com/hobbyquaker/influx4mqtt) ⭐ 38 | 🐛 1 | 🌐 JavaScript | 📅 2021-05-02 - Subscribe to MQTT topics and insert into InfluxDB.
* [graylog-plugin-mqtt](https://github.com/graylog-labs/graylog-plugin-mqtt) ⭐ 13 | 🐛 10 | 🌐 Java | 📅 2024-05-06 - MQTT Input Plugin for Graylog.
* [mqtt2elasticsearch](https://github.com/hobbyquaker/mqtt2elasticsearch) ⭐ 3 | 🐛 0 | 🌐 JavaScript | 📅 2018-03-24 - Send MQTT messages to Elasticsearch.

<!--lint disable double-link-->

* [mqttwarn](https://github.com/jpmens/mqttwarn) ⭐ 978 | 🐛 40 | 🌐 Python | 📅 2026-07-22 - Use with [carbon](https://mqttwarn.readthedocs.io/en/latest/notifier-catalog.html#carbon) plugin.

<!--lint enable double-link-->

* [mqttcollect](https://github.com/jpmens/mqttcollect) ⚠️ Archived - A collectd "Exec" plugin for MQTT.
* [mqtthandler](https://github.com/changyuheng/MQTTHandler) ⭐ 22 | 🐛 1 | 🌐 Python | 📅 2022-07-25 - A Python logging handler module for MQTT.
* [mqtt2mongodb](https://github.com/David-Lor/MQTT2MongoDB) ⚠️ Archived - Subscribe to MQTT topics and insert into MongoDB.

### Smart Home Hardware Interfaces

* [Bambuddy](https://github.com/maziggy/bambuddy) ⭐ 2,835 | 🐛 159 | 🌐 Python | 📅 2026-08-22 - Self-hosted management tool for Bambu Lab 3D printers using MQTT, with real-time monitoring, scheduling, and Home Assistant integration.
* [amcrest2mqtt](https://github.com/dchesterton/amcrest2mqtt) ⭐ 154 | 🐛 16 | 🌐 Python | 📅 2023-04-22 - Amcrest doorbell to MQTT bridge. Uses Home Assistant's MQTT discovery protocol.
* [ble-scale-sync](https://github.com/KristianP26/ble-scale-sync) ⭐ 153 | 🐛 18 | 🌐 TypeScript | 📅 2026-08-21 - BLE-to-MQTT bridge for smart scales (23 brands) with Home Assistant auto-discovery. Reads weight + impedance, calculates body composition, publishes all 11 metrics with LWT and display precision. [Website](https://blescalesync.dev).
* [can2mqtt](https://github.com/c3re/can2mqtt) ⚠️ Archived - CAN-Bus - MQTT Bridge (also works vice versa).
* [aqara-mqtt](https://github.com/monster1025/aqara-mqtt) ⭐ 89 | 🐛 1 | 🌐 Python | 📅 2021-03-13 - Aqara (Xiaomi) Gateway to MQTT bridge.
* [knx2mqtt](https://github.com/owagner/knx2mqtt) ⭐ 50 | 🐛 4 | 🌐 Java | 📅 2015-09-16 - Interface between the KNX home automation standard and MQTT.
* [knx-mqtt-bridge](https://github.com/pakerfeldt/knx-mqtt-bridge) ⭐ 43 | 🐛 1 | 🌐 JavaScript | 📅 2026-08-11 - Bridges KNX and MQTT using the knx.js library.
* [ipcam2mqtt](https://github.com/svrooij/ipcam2mqtt) ⭐ 26 | 🐛 8 | 🌐 JavaScript | 📅 2022-04-08 - A small FTP server to receive movement images from ipcameras and turn them into MQTT alerts.
* [mqtt-unifi-protect-bridge](https://github.com/terafin/mqtt-unifi-protect-bridge) ⚠️ Archived - Adding motion-status from UniFi Protect Cameras to MQTT.
* [hm2mqtt.js](https://github.com/hobbyquaker/hm2mqtt.js) ⭐ 21 | 🐛 8 | 🌐 JavaScript | 📅 2019-01-06 - Interface between EQ-3's Homematic line of smarthome devices and MQTT. Supports Homematic IP.
* [HS100toMQTT](https://github.com/dersimn/HS100toMQTT) ⭐ 16 | 🐛 2 | 🌐 JavaScript | 📅 2021-04-25 - Gateway between TPLink HS100/HS110 and MQTT.
* [homeeToMqtt](https://github.com/odig/homeeToMqtt) ⭐ 13 | 🐛 4 | 🌐 JavaScript | 📅 2022-09-20 - Bidirectional Interface between homee and MQTT.
* [gardena2mqtt](https://github.com/Domochip/gardena2mqtt) ⭐ 12 | 🐛 3 | 🌐 Python | 📅 2025-11-24 - Docker Gateway to control GARDENA Smart system devices (Sileno mower, Irrigation Control, etc.) through MQTT.
* [eno2mqtt](https://github.com/owagner/eno2mqtt) ⭐ 10 | 🐛 4 | 🌐 Java | 📅 2016-05-20 - Interface between an Enocean USB300 (TCM310) adapter and MQTT.
* [cul2mqtt](https://github.com/hobbyquaker/cul2mqtt) ⭐ 9 | 🐛 0 | 🌐 JavaScript | 📅 2018-02-05 - Interface between [Busware CUL](https://shop.busware.de/product_info.php/cPath/1/products_id/29) (868MHz RF-Devices like ELV FS20, HMS, EM, etc.) and MQTT.
* [Evohome2mqtt](https://github.com/svrooij/evohome2mqtt) ⭐ 8 | 🐛 2 | 🌐 JavaScript | 📅 2021-03-17 - MQTT Interface for the Honeywell Evohome system.
* [helios2mqtt](https://github.com/mreschka/helios2mqtt) ⭐ 8 | 🐛 3 | 🌐 JavaScript | 📅 2026-02-28 - A daemon for syncing a helios easy controls system like my KWL EC 220D to MQTT.
* [huABus](https://github.com/arboeh/huABus) ⭐ 8 | 🐛 0 | 🌐 Python | 📅 2026-08-19 - Home Assistant application (Add-on) and MQTT bridge for Huawei solar inverters (SUN2000/3000/5000).
* [aqara2mqtt](https://github.com/hobbyquaker/aqara2mqtt) ⭐ 7 | 🐛 0 | 🌐 JavaScript | 📅 2018-09-28 - Attach [Aqara](https://www.aqara.com) Smart Hubs to MQTT.
* [mqtt-dss-bridge](https://github.com/cgHome/mqtt-dss-bridge) ⭐ 5 | 🐛 0 | 🌐 JavaScript | 📅 2015-09-24 - MQTT digitalSTROM-Server Bridge.
* [domiqtt](https://github.com/etobi/domiqtt) ⭐ 2 | 🐛 2 | 🌐 JavaScript | 📅 2026-05-28 - Connects to a Domiq Base (LCN) and translate from and to MQTT.
* [airrohr2mqtt](https://c0d3.sh/smarthome/airrohr2mqtt) - Air quality monitoring integration.
* [coe2mqtt](https://c0d3.sh/smarthome/coe2mqtt) - Bi-directional CAN Bus to MQTT.
* [fronius2mqtt](https://c0d3.sh/smarthome/fronius2mqtt) - MQTT integration for Fronius SolarAPI.
* [mcsMQTT](https://shop.homeseer.com/products/mcsmqtt-software-plug-in-for-hs3) - Plug-in for HS3 (HomeSeer).

<!--lint disable double-link-->

* [mqtt2homekit](https://github.com/forty2/mqtt2homekit) ⭐ 39 | 🐛 4 | 🌐 JavaScript | 📅 2018-01-05 - Roughly the opposite of [homekit2mqtt](https://github.com/hobbyquaker/homekit2mqtt) ⭐ 358 | 🐛 39 | 🌐 JavaScript | 📅 2022-02-04: Control your HomeKit-enabled devices with MQTT and without Siri or iPhone.

<!--lint enable double-link-->

* [zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt) ⭐ 15,515 | 🐛 452 | 🌐 TypeScript | 📅 2026-08-22 - Allows you to use your Zigbee devices without the vendors (Xiaomi/TRADFRI/Hue) bridge/gateway.
* [zwavejs2mqtt](https://github.com/zwave-js/zwavejs2mqtt) ⭐ 1,235 | 🐛 125 | 🌐 Vue | 📅 2026-08-14 - Zwave to Mqtt gateway and Control Panel Web UI.
* [smartthings-mqtt-bridge](https://github.com/stjohnjohnson/smartthings-mqtt-bridge) ⭐ 379 | 🐛 108 | 🌐 Groovy | 📅 2025-11-16 - Bridge between [SmartThings](https://www.smartthings.com/) and MQTT.
* [node-lox-mqtt-gateway](https://github.com/alladdin/node-lox-mqtt-gateway) ⭐ 27 | 🐛 4 | 🌐 JavaScript | 📅 2020-02-03 - Gateway for Loxone™ mini server to communicate with MQTT broker.
* [xiaomi2mqtt](https://github.com/svrooij/node-xiaomi2mqtt) ⚠️ Archived - Bridge between the Xiaomi Smart Home Gateway Aquara and a MQTT server.

### Smart Home Integration Software

* [Home Assistant](https://www.home-assistant.io) - Home Automation system with native MQTT support, and the world's largest non-commercial Open Source project.
* [Domoticz](https://www.domoticz.com/) - Home Automation system with MQTT support.
* [FHEM](https://fhem.de/fhem.html) - Includes a [MQTT module](https://fhem.de/commandref.html#MQTT) since V5.6.
* [Home.Pi](https://github.com/denschu/home.pi) ⭐ 191 | 🐛 6 | 🌐 JavaScript | 📅 2015-04-08 - Based on MQTT.
* [Homegear](https://homegear.eu/index.php/Main_Page) - Built in MQTT support.

<!--lint disable double-link-->

* [HomeGenie](https://homegenie.it/) - Supports remote controlling and monitoring via MQTT with end-to-end encryption.
* [homekit2mqtt](https://github.com/hobbyquaker/homekit2mqtt) ⭐ 358 | 🐛 39 | 🌐 JavaScript | 📅 2022-02-04 - Interface between [HAP-NodeJS](https://github.com/homebridge/HAP-NodeJS) ⭐ 2,722 | 🐛 3 | 🌐 TypeScript | 📅 2026-08-19 and MQTT. Control MQTT connected devices with Siri or HomeKit Apps.

<!--lint enable double-link-->

* [openHAB](https://github.com/openhab) - Includes a [MQTT binding](https://github.com/openhab/openhab1-addons/wiki/MQTT-Binding) ⚠️ Archived.
* [ioBroker](https://github.com/ioBroker) - Includes a [MQTT adapter](https://github.com/ioBroker/ioBroker.mqtt) ⭐ 58 | 🐛 58 | 🌐 TypeScript | 📅 2026-08-12.
* [openLuup](https://github.com/akbooer/openLuup) ⭐ 40 | 🐛 2 | 🌐 Lua | 📅 2025-02-02 - A pure-Lua open-source emulation of the Vera Luup home automation environment with MQTT.
* [she - smart home engine](https://github.com/hobbyquaker/she) ⭐ 9 | 🐛 0 | 🌐 Svelte | 📅 2026-08-17 - Scriptable smart home automation engine with AI assistance.
* [shopsavvy-mqtt](https://github.com/shopsavvy/shopsavvy-mqtt) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-03 - MQTT bridge that publishes product price data with Home Assistant MQTT discovery support.
* [pimatic](https://pimatic.org/) - MQTT plugin included.
* [knx2mqtt](https://c0d3.sh/smarthome/knx2mqtt) - Telegram bi-directional integration as alternative to HomeAssistant's built-in support.

### Lighting

* [Arilux\_AL-LC0X](https://github.com/mertenats/Arilux_AL-LC0X) ⚠️ Archived - This is an alternative firmware for Arilux LED controllers which uses MQTT.
* [TRADFRI2MQTT](https://github.com/hardillb/TRADFRI2MQTT) ⭐ 84 | 🐛 2 | 🌐 Java | 📅 2020-10-12 - MQTT Bridge for IKEA TRÅDFRI Light Gateway.
* [MQTT DMX Controller](https://github.com/hobbyquaker/mqtt-dmx-controller) ⭐ 70 | 🐛 8 | 🌐 JavaScript | 📅 2019-06-13 - DMX Controller with MQTT support.
* [hue2mqtt.js](https://github.com/hobbyquaker/hue2mqtt.js) ⭐ 30 | 🐛 8 | 🌐 JavaScript | 📅 2020-01-01 - Interface between the Philips Hue bridge and MQTT.
* [mqtt-dmx-sequencer](https://github.com/hobbyquaker/mqtt-dmx-sequencer) ⭐ 26 | 🐛 1 | 🌐 JavaScript | 📅 2018-01-05 - Headless counterpart to MQTT DMX Controller - use scenes and sequences exported from the MQTT DMX Controller and control them via MQTT.
* [sunricher-wifi-mqtt](https://github.com/magcode/sunricher-wifi-mqtt) ⚠️ Archived - Control Sunricher LED devices using MQTT.
* [chromoflex2mqtt](https://github.com/owagner/chromoflex2mqtt) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2015-12-05 - Control Chromoflex USP3 RGB LED modules via MQTT.

### Home Entertainment

* [harmony-api](https://github.com/maddox/harmony-api) ⭐ 401 | 🐛 39 | 🌐 JavaScript | 📅 2020-04-14 - A simple server allowing you to query/control multiple local Harmony Home Hubs over HTTP or MQTT.
* [broadlink-mqtt](https://github.com/eschava/broadlink-mqtt) ⭐ 238 | 🐛 20 | 🌐 Python | 📅 2024-05-27 - MQTT client to control BroadLink RM devices.
* [lgtv2mqtt](https://github.com/hobbyquaker/lgtv2mqtt) ⭐ 109 | 🐛 0 | 🌐 JavaScript | 📅 2026-08-22 - Interface between LG WebOS Smart TVs and MQTT.
* [kodi2mqtt](https://github.com/owagner/kodi2mqtt) ⭐ 88 | 🐛 20 | 🌐 Python | 📅 2021-03-07 - Interface between a Kodi media center instance and MQTT.
* [sonos2mqtt](https://github.com/svrooij/sonos2mqtt) ⭐ 84 | 🐛 3 | 🌐 TypeScript | 📅 2026-07-06 - A bridge between Sonos and MQTT.
* [airtunes2mqtt](https://github.com/hobbyquaker/airtunes2mqtt) ⭐ 52 | 🐛 2 | 🌐 JavaScript | 📅 2018-11-26 - MQTT controlled Multi-Room Audio with Airplay/Airtunes Devices.
* [chromecast-mqtt-connector](https://github.com/nohum/chromecast-mqtt-connector) ⭐ 46 | 🐛 2 | 🌐 Python | 📅 2024-03-15 - Control your Google Chromecast devices using MQTT.
* [onkyo2mqtt](https://github.com/owagner/onkyo2mqtt) ⭐ 39 | 🐛 2 | 🌐 Python | 📅 2021-03-30 - Interface between Onkyo AVR's EISCP network remote protocol and MQTT. Uses the onkyo-eiscp library.
* [lirc2mqtt](https://github.com/hobbyquaker/lirc2mqtt) ⭐ 23 | 🐛 3 | 🌐 JavaScript | 📅 2020-01-07 - Send and receive infrared via [LIRC](https://www.lirc.org).
* [mopidy-mqtt](https://github.com/magcode/mopidy-mqtt) ⭐ 23 | 🐛 1 | 🌐 Python | 📅 2023-12-14 - MQTT features for Mopidy.
* [bravia2mqtt](https://github.com/forty2/bravia2mqtt) ⭐ 15 | 🐛 18 | 📅 2023-01-12 - Control your Sony Bravia TV with MQTT.
* [yamaha-avr2mqtt](https://github.com/akentner/yamaha-avr2mqtt) ⭐ 10 | 🐛 1 | 🌐 JavaScript | 📅 2026-03-01 - A simple adapter for connection Yamaha AVR to MQTT.
* [MQTT-DashCast-Docker](https://github.com/mukowman/MQTT-DashCast-Docker) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2018-03-07 - MQTT Docker to launch DashCast session on Chromecast.
* [mqtt2tivoremote](https://github.com/forty2/mqtt2tivoremote) ⭐ 4 | 🐛 17 | 🌐 JavaScript | 📅 2020-06-02 - Make TiVo DVR remote control available through an MQTT smarthome style interface.
* [xbmc2mqtt](https://github.com/gordonjcp/xbmc-mqtt) ⭐ 4 | 🐛 1 | 🌐 Python | 📅 2015-03-17 - A simple plugin for XBMC to listen for a particular topic on an MQTT broker, and display a popup message.
* [htd2mqtt](https://github.com/TheOriginalAndrobot/htd2mqtt) ⭐ 3 | 🐛 3 | 🌐 JavaScript | 📅 2016-10-30 - Bridge between an HTD Lync audio system and MQTT.
* [mqtt2atlonamatrix](https://github.com/forty2/mqtt2atlonamatrix) ⭐ 0 | 🐛 1 | 🌐 JavaScript | 📅 2018-01-05 - Control Atlona HDMI matrix switches with MQTT.
* [VLC MQTT Module](https://wiki.videolan.org/Documentation:Modules/mqtt/) - Control VLC via MQTT.

### Smart Metering

* [rpi-mqtt-monitor](https://github.com/hjelev/rpi-mqtt-monitor) ⭐ 316 | 🐛 9 | 🌐 Python | 📅 2026-06-26 - The easiest way to track your Raspberry Pi or Ubuntu computer system health and performance in Home Assistant via MQTT.
* [bcontrol2mqtt](https://github.com/hobbyquaker/bcontrol2mqtt) ⭐ 3 | 🐛 0 | 🌐 JavaScript | 📅 2018-02-05 - Publish measurements from TQ Energy Manager / [Busch-Jäger Energy Monitor](https://www.busch-jaeger.de/files/files_ONLINE/Brosch%c3%bcre_EnergyMonitor_druck.pdf) to MQTT.

### Messaging

* [mqtt-irc-bot](https://github.com/dobermai/mqtt-irc-bot) ⭐ 24 | 🐛 0 | 🌐 Java | 📅 2015-11-01 - A MQTT to IRC / IRC to MQTT bridge or bot.

<!--lint disable double-link-->

* [mqttwarn](https://github.com/jpmens/mqttwarn) ⭐ 978 | 🐛 40 | 🌐 Python | 📅 2026-07-22 - Subscribe to MQTT topics (with wildcards) and notify pluggable services.

<!--lint enable double-link-->

* [twitter-to-mqtt](https://github.com/knolleary/twitter-to-mqtt) ⭐ 18 | 🐛 0 | 🌐 Python | 📅 2012-12-19 - A python daemon that uses the Twitter Streaming API to access tweets and republishes them to an MQTT topic.

### Misc

* [Valetudo](https://github.com/Hypfer/Valetudo) ⭐ 9,554 | 🐛 0 | 🌐 JavaScript | 📅 2026-08-19 - Xiaomi (Roborock) Vacuum Robots Firmware with MQTT and Webinterface.
* [miflora-mqtt-daemon](https://github.com/ThomDietrich/miflora-mqtt-daemon) ⭐ 623 | 🐛 73 | 🌐 Python | 📅 2024-05-23 - Linux service to send Xiaomi Mi Flora plant sensor data to an MQTT broker.
* [bt-mqtt-gateway](https://github.com/zewelor/bt-mqtt-gateway) ⚠️ Archived - Easily extensible Bluetooth to MQTT gateway, currently supports: EQ3 smart thermostat, Xiaomi Mi Scale, Linak Desk, MySensors and Xiaomi Mi Flora plant sensor.
* [mqtt-camera-streamer](https://github.com/robmarkcole/mqtt-camera-streamer) ⭐ 248 | 🐛 17 | 🌐 Python | 📅 2024-08-12 - Stream images from a connected camera over MQTT & view using Streamlit.
* [gBridge](https://github.com/kservices/gBridge) ⚠️ Archived - Control (almost) any smart home device, any smart home software, with Google Assistant. Therefore, it transforms actions received from Google by voice commands to MQTT messages.
* [serial2mqtt](https://github.com/vortex314/serial2mqtt) ⭐ 153 | 🐛 4 | 🌐 C++ | 📅 2025-09-22 - A Linux gateway to connect low-cost microcontrollers only with a serial port to MQTT.
* [mqttclpro](https://github.com/dc297/mqttclpro) ⭐ 111 | 🐛 24 | 🌐 Java | 📅 2020-03-14 - MQTT Client with tasker integration Android app.
* [AlexaMqttBridge](https://github.com/mhdawson/AlexaMqttBridge) ⭐ 109 | 🐛 0 | 🌐 JavaScript | 📅 2019-01-13 - Bridge between Amazon Alexa and MQTT.
* [unifi2mqtt](https://github.com/hobbyquaker/unifi2mqtt) ⭐ 78 | 🐛 14 | 🌐 JavaScript | 📅 2020-08-07 - Publish connected clients from Ubiquiti Unifi to MQTT.
* [node-mqtt-for-anki-overdrive](https://github.com/IBM-Cloud/node-mqtt-for-anki-overdrive) ⭐ 63 | 🐛 3 | 🌐 JavaScript | 📅 2018-09-10 - Node.js Controller and MQTT API for Anki Overdrive.
* [leaf-python-mqtt](https://github.com/glynhudson/leaf-python-mqtt) ⭐ 27 | 🐛 4 | 🌐 Python | 📅 2018-08-02 - Extract data from Nissan Leaf API and post to MQTT.
* [mqtt2ble](https://github.com/hardillb/mqtt2ble) ⭐ 27 | 🐛 0 | 🌐 JavaScript | 📅 2016-12-13 - A way to bridge MQTT topics to BLE Gatt characteristics.
* [mqttDB](https://github.com/hobbyquaker/mqttDB) ⭐ 26 | 🐛 0 | 🌐 JavaScript | 📅 2018-05-30 - A JSON store with MQTT interface.
* [chrome2mqtt](https://github.com/tbowmo/chrome2mqtt) ⭐ 22 | 🐛 1 | 🌐 Python | 📅 2025-09-20 - Python program to enable MQTT control endpoints for chromecasts (both audio and video).
* [buderus2mqtt](https://github.com/krambox/buderus2mqtt) ⭐ 18 | 🐛 12 | 🌐 JavaScript | 📅 2023-01-03 - Bridge between Buderus KM200 internet gateway and MQTT.
* [parrot-sample](https://github.com/IBM-Cloud/parrot-sample) ⚠️ Archived - Sample code which uses MQTT to control a Parrot AR Drone.
* [homely](https://github.com/baol/homely) ⭐ 17 | 🐛 2 | 🌐 Go | 📅 2021-11-11 - Collection of Go daemons for connecting Domoticz and other stuff.
* [dashbutton2mqtt](https://github.com/hobbyquaker/dashbutton2mqtt) ⭐ 16 | 🐛 0 | 🌐 JavaScript | 📅 2018-01-05 - Publish Amazon Dash Button presses to MQTT.
* [mqtt-transformer](https://github.com/tg44/mqtt-transformer) ⭐ 15 | 🐛 3 | 🌐 TypeScript | 📅 2026-07-24 - A simple service which consumes, transforms and periodically republish json messages on MQTT.
* [speedtest2mqtt](https://github.com/hobbyquaker/speedtest2mqtt) ⭐ 15 | 🐛 0 | 🌐 Shell | 📅 2018-02-09 - Run speedtest-cli and publish results via MQTT.
* [haiku2mqtt](https://github.com/forty2/haiku2mqtt) ⭐ 9 | 🐛 3 | 🌐 JavaScript | 📅 2018-01-05 - A bridge between Haiku smart fans and MQTT.
* [MQTT Joystick Controller](https://github.com/Vincenzo-Petrolo/MQTT-Joystick-Controller) ⭐ 8 | 🐛 3 | 🌐 Java | 📅 2020-04-27 - Open Source Android app that lets you control everything with your smartphone. Download it from Google Play.
* [QuIXI](https://github.com/ixian-platform/QuIXI) ⭐ 8 | 🐛 0 | 🌐 C# | 📅 2026-08-10 - Bridge between the Ixian decentralized P2P network and MQTT/REST. Enables encrypted peer-to-peer messaging for IoT devices with post-quantum security (ML-KEM + AES-256 + ChaCha20).
* [flowerpower2mqtt](https://github.com/hobbyquaker/flowerpower2mqtt) ⭐ 7 | 🐛 0 | 🌐 JavaScript | 📅 2018-01-05 - Publish measurements from Parrot Flower Power plant sensors to MQTT.
* [snowboy2mqtt](https://github.com/hobbyquaker/snowboy2mqtt) ⭐ 6 | 🐛 0 | 🌐 JavaScript | 📅 2018-10-25 - Publish MQTT Messages on Snowboy Hotword Detection.
* [kobold2mqtt](https://github.com/krambox/kobold2mqtt) ⭐ 2 | 🐛 11 | 🌐 JavaScript | 📅 2022-12-07 - Bridge between Vorwerk Kobold Vr200 internet gateway and MQTT.
* [mqtt-tasker](https://github.com/stesie/TaskerMqtt) ⭐ 2 | 🐛 1 | 🌐 Java | 📅 2016-12-29 - Android Tasker mqtt plugin.
* [MQTT2ETCD](https://github.com/David-Lor/MQTT2ETCD) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2019-11-08 - MQTT-ETCD gateway: PUT keys on ETCD through MQTT, and watch ETCD key changes on MQTT topics.
* [anpr2mqtt](https://anpr2mqtt.rhizomatics.org.uk) - Listen for images on file server, analyze and create Home Assistant entities via MQTT Discovery.
* [MQTT.Cool](https://mqtt.cool) - A web gateway that optimizes any MQTT broker when sending real-time data to web clients with automatic throttling.
* [wlan-thermo-mqtt-addon](https://bitbucket.org/IOcastor/wlan-thermo-mqtt-addon/) - Addon for a popular DIY barbecue thermometer.

## Visualization, Dashboards

* [PlotJuggler](https://github.com/facontidavide/PlotJuggler) ⭐ 6,124 | 🐛 159 | 🌐 C++ | 📅 2026-08-10 - Visualize time series (from sources such as: MQTT, Websockets, ZeroMQ, UDP, etc., supports data formats such as JSON, CBOR, BSON, Message Pack, etc.). It is a fast, powerful and intuitive cross-platform tool.
* [node-red-dashboard](https://github.com/node-red/node-red-dashboard) ⭐ 1,406 | 🐛 93 | 🌐 HTML | 📅 2025-08-07 - A dashboard UI for Node-RED.
* [mqtt-panel](https://github.com/fabaff/mqtt-panel) ⭐ 440 | 🐛 4 | 🌐 JavaScript | 📅 2026-04-11 - A web interface for MQTT.
* [Crouton](https://github.com/edfungus/Crouton) ⭐ 297 | 🐛 24 | 🌐 Python | 📅 2021-06-07 - A dashboard that taps into your IOT network, using only MQTT and JSON.
* [MQTT-Tiles](https://github.com/flespi-software/MQTT-Tiles) ⭐ 114 | 🐛 21 | 🌐 Vue | 📅 2026-06-23 - MQTT-based IoT dashboard visualization tool. Allows easy dashboards sharing. Works with any MQTT broker supporting the WSS protocol.
* [HelloIoT](https://github.com/adrianromero/helloiot) ⭐ 110 | 🐛 0 | 🌐 Java | 📅 2021-06-17 - MQTT client and dashboard application.
* [d3-MQTT-Topic-Tree](https://github.com/hardillb/d3-MQTT-Topic-Tree) ⭐ 97 | 🐛 2 | 🌐 JavaScript | 📅 2020-10-20 - A MQTT Topic Tree viewer using the d3 collapsible tree and MQTT over websockets.
* [mqtt-svg-dash](https://github.com/jpmens/mqtt-svg-dash) ⭐ 64 | 🐛 0 | 🌐 JavaScript | 📅 2013-04-22 - Subscribe to MQTT, extract JSON from a message and make lights blink on an SVG page.
* [mqtt2highcharts](https://github.com/matbor/mqtt2highcharts) ⚠️ Archived - Plotting live numbered data from a subscribed MQTT topic using Highcharts.
* [Linear MQTT Dashboard](https://github.com/ravendmaster/linear-mqtt-dashboard) ⭐ 56 | 🐛 18 | 🌐 Java | 📅 2020-08-31 - Easy, customizable control panel - MQTT-client.
* [mqtt-prometheus-message-exporter](https://github.com/tg44/mqtt-prometheus-message-exporter) ⭐ 21 | 🐛 0 | 🌐 Scala | 📅 2021-12-28 - A small service which will convert mqtt messages to prometheus metrics.
* [HOMR-REACT](https://github.com/klauserber/homr-react) ⭐ 18 | 🐛 1 | 🌐 JavaScript | 📅 2017-04-18 - A configurable MQTT Visualization.
* [MMM-mqtt](https://github.com/javiergayala/MMM-mqtt) ⭐ 16 | 🐛 8 | 🌐 JavaScript | 📅 2021-02-10 - This is an extension for the MagicMirror². It provides the ability to subscribe to MQTT topics and display them.
* [mqtt-dashboard](https://github.com/jmischler72/mqtt-dashboard) ⭐ 16 | 🐛 4 | 🌐 TypeScript | 📅 2026-08-20 - Self-hostable MQTT dashboard/explorer with drag-and-drop panels like cron, button, log and topic browser to help interact and monitor MQTT topics.
* [Feezal](https://github.com/feezal/feezal) ⭐ 11 | 🐛 0 | 🌐 JavaScript | 📅 2026-08-09 - Dashboard editor powered by Web Components and MQTT.
* [MQTT-Hyperdash](https://github.com/kollokollo/MQTT-Hyperdash) ⭐ 11 | 🐛 4 | 🌐 C | 📅 2022-02-09 - A universal independent MQTT Dashboard for Linux/Raspberry Pi.
* [awtSCADA](https://github.com/larionovavi-stack/awtscada) ⭐ 5 | 🐛 0 | 🌐 HTML | 📅 2026-06-08 - Industrial SCADA/HMI system with MQTT support (plus IEC 61850, OPC UA, Modbus TCP). Runs from a single HTML file in any browser, zero installation. 53 function blocks, 65 graphic elements, real-time trends.
* [MQTT Dash](https://play.google.com/store/apps/details?id=net.routix.mqttdash\&hl=de) - Android App: With the app you can create dashboards for your MQTT enabled IoT Smart Home devices and applications.
* [MQTT.Cool Test Client](https://testclient-cloud.mqtt.cool) - A web interface for testing interaction between MQTT.Cool and any MQTT broker.
* [MYHELLOIOT](https://adrianromero.github.io/myhelloiot/) - MQTT dashboard application.
* [ZigDash](https://gitlab.com/tamamg/zigdash) - Free, open-source Material 3 MQTT dashboard for Android, built for Zigbee2MQTT with automatic device discovery.

<!--lint disable double-link-->

Other tools that can be used to create Visualization/Dashboards can be found under [Platforms](#platforms) and [Smart Home Integration Software](#smart-home-integration-software).

<!--lint enable double-link-->

## Architecture, Convention

* [The Homie Convention](https://github.com/homieiot/convention) ⭐ 745 | 🐛 27 | 📅 2026-02-12 - A lightweight MQTT convention for the IoT.
* [mqtt-smarthome](https://github.com/mqtt-smarthome/mqtt-smarthome) ⭐ 453 | 🐛 9 | 📅 2022-02-04 - Smart home automation with MQTT as the central message bus - Architectural proposal.

## Security, Encryption

* [MQTT-PWN](https://github.com/akamai-threat-research/mqtt-pwn) ⭐ 451 | 🐛 16 | 🌐 Python | 📅 2024-08-09 - IoT Broker penetration-testing and security assessment operations.
* [mqttsa](https://github.com/stfbk/mqttsa) ⭐ 51 | 🐛 0 | 🌐 Python | 📅 2024-03-26 - Broker mis-configuration detection for cyber protection.
* [Let's Encrypt Mosquitto Docker Container](https://hub.docker.com/r/pythonlinks/letsencrypt-mosquitto) - Easier TLS certificate management for brokers.
* [Teserakt E4](https://teserakt.io/) - End-to-end encryption and key management for MQTT and other M2M protocols – Open-source and paid plans.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-22._
