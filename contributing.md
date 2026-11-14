
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=venom&color=gradient&customColorList=4,11,18&height=260&section=header&text=STREAMIZ&fontSize=85&fontColor=ffffff&animation=twinkling&fontAlignY=42&desc=Apache%20Kafka%20Streams%20for%20.NET&descAlignY=68&descSize=24&descAlign=50" width="100%"/>

<br/>

<img src="https://readme-typing-svg.demolab.com?font=Orbitron&size=22&duration=2800&pause=1000&color=48CAE4&center=true&vCenter=true&width=750&lines=Real-Time+Stream+Processing.;Fully+Managed+for+C%23.;High+Throughput.+Low+Latency." alt="Typing SVG"/>

<br/><br/>

<a href="https://share.google/8qjTLAQzpRlMPpFB7">
  <img src="https://img.shields.io/badge/📥_INSTALL_NUGET-48CAE4?style=for-the-badge&logo=nuget&logoColor=white&labelColor=0077B6" height="50"/>
</a>
&nbsp;
<a href="https://share.google/8qjTLAQzpRlMPpFB7">
  <img src="https://img.shields.io/badge/📚_READ_DOCS-0077B6?style=for-the-badge&logo=readthedocs&logoColor=white&labelColor=023E8A" height="50"/>
</a>
&nbsp;
<a href="https://share.google/8qjTLAQzpRlMPpFB7">
  <img src="https://img.shields.io/badge/⭐_GITHUB_REPO-023E8A?style=for-the-badge&logo=github&logoColor=white&labelColor=03045E" height="50"/>
</a>

<br/><br/>

<img src="https://img.shields.io/badge/version-1.4.2-0077B6?style=flat-square&logo=semanticrelease&logoColor=white"/>
<img src="https://img.shields.io/badge/.NET-8.0+-512BD4?style=flat-square&logo=dotnet&logoColor=white"/>
<img src="https://img.shields.io/badge/license-Apache--2.0-48CAE4?style=flat-square&logo=apache&logoColor=white"/>
<img src="https://img.shields.io/badge/downloads-81K%2B-00B4D8?style=flat-square&logo=nuget&logoColor=white"/>
<img src="https://img.shields.io/badge/status-stable-06D6A0?style=flat-square&logo=checkmarx&logoColor=white"/>

</div>

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🌊 Enterprise Stream Processing for .NET

**Streamiz Kafka Streams** is a robust, high-performance .NET library that brings the power of **Apache Kafka Streams** to the C# ecosystem. For years, Java developers had exclusive access to Kafka's native stream processing capabilities. Streamiz bridges that gap, allowing .NET developers to build distributed, fault-tolerant, and scalable stream processing applications natively.

With Streamiz, you can consume, process, and produce data in real-time without needing to deploy heavy data-processing clusters like Apache Spark or Flink. It’s designed from the ground up to be idiomatic C#, utilizing LINQ-style syntax for stream transformations. If you're building microservices that need to react to events instantly, this is the library you've been waiting for.

> 💡 **Why use Streamiz?** Because the .NET ecosystem deserves first-class stream processing. Keep your entire architecture in C#, reduce operational complexity, and process millions of events per second with minimal latency.

<br/>

<table align="center" width="100%" style="border-collapse: collapse; border: 1px solid #48CAE4; border-radius: 10px;">
<tr style="background-color: #03045E; color: #48CAE4;">
<th align="center" width="25%" style="padding: 15px;">⚡ LINQ-Style API</th>
<th align="center" width="25%" style="padding: 15px;">🛡️ Fault Tolerant</th>
<th align="center" width="25%" style="padding: 15px;">📦 Exactly-Once</th>
<th align="center" width="25%" style="padding: 15px;">🚀 Auto Scaling</th>
</tr>
<tr>
<td align="center" style="padding: 15px; color: #ddd;">Express complex data transformations with familiar C# syntax.</td>
<td align="center" style="padding: 15px; color: #ddd;">State stores and automatic recovery ensure no data is ever lost.</td>
<td align="center" style="padding: 15px; color: #ddd;">Native support for Kafka transactions for precise data guarantees.</td>
<td align="center" style="padding: 15px; color: #ddd;">Dynamically scale your consumer groups as traffic grows.</td>
</tr>
</table>

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## ⚡ Why Streamiz Stands Out

<div align="center">

| 🧩 **The Challenge** | 💡 **Our Solution** | 📈 **The Result** |
|:---|:---|:---|
| Java-only stream processing tools | **Native .NET implementation** of the Kafka Streams DSL | Full C# support without JVM wrappers |
| Complex event-driven architectures | **High-level Streams DSL** with map, filter, join, and aggregate | Write less code, achieve more |
| Stateful processing is hard to manage | **Built-in State Stores** (RocksDB / In-Memory) | Local, fast, and resilient state management |
| Handling out-of-order events | **Windowed operations** with tumbling and hopping windows | Accurate time-series analytics |

</div>

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🎯 Core Features

<div align="center">

| 🔄 **Stream DSL** | 🗄️ **State Stores** | 🧩 **Topology Builder** |
|:---:|:---:|:---:|
| KStream, KTable, GlobalKTable, and KGroupedStream APIs | RocksDB and in-memory store integration for high-speed lookups | Connect multiple processors and topologies seamlessly |

| ⏱️ **Windowing** | 🛡️ **Error Handling** | 🎨 **Integration** |
|:---:|:---:|:---:|
| Tumbling, hopping, sliding, and session windows | Dead-letter queues and customizable deserialization handlers | Works with `Microsoft.Extensions.DependencyInjection` |

</div>

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🖼️ Architecture Preview

<div align="center">

<img width="862" height="664" alt="logo-kafka-stream-net" src="https://github.com/user-attachments/assets/88be8c1c-85e5-42ab-ac38-8ab151cb578a" />

</div>

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🚀 Quick Start

> **Three steps. Under two minutes. No complex setups required.**

### 1️⃣ Install via NuGet

```bash
dotnet add package Streamiz.Kafka.Net
```

### 2️⃣ Configure your topology

```csharp
var builder = new StreamBuilder();
builder.Stream<string, string>("input-topic")
       .Filter((k, v) => v.Contains("ERROR"))
       .To("error-topic");
```

### 3️⃣ Start the stream

```csharp
var config = new StreamConfig<StringSerDes, StringSerDes>();
config.ApplicationId = "my-app";
config.BootstrapServers = "localhost:9092";

var stream = new KafkaStream(builder.Build(), config);
stream.StartAsync();
```

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## ⚙️ How It Works

<div align="center">

| Layer | Responsibility | Tech |
|:---|:---|:---|
| 📥 **Consumers** | Polls messages from Kafka topics | `Confluent.Kafka` |
| ⚙️ **Topology Engine** | Routes messages through processors | Custom .NET Streams Core |
| 🗄️ **State Stores** | Caches local state for fast aggregations | `RocksDB` / `Memory` |
| 📤 **Producers** | Publishes results to downstream topics | `Confluent.Kafka` |

</div>

The library is built with performance and memory efficiency in mind. It leverages async/await and modern .NET memory primitives (`Span<T>`, `Memory<T>`) to minimize allocations and maximize throughput.

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🧠 Pro Tips

<table align="center" width="100%">
<tr>
<td width="50%">

**For production environments**
- 📊 Enable JMX metrics to monitor stream health
- 🗄️ Use RocksDB for large state stores (not just memory)
- 🛡️ Configure `NumStreamThreads` to match your partition count
- 🔄 Always enable `ExactlyOnce` if data accuracy is critical

</td>
<td width="50%">

**For local development**
- 🐳 Use Docker Compose to spin up Kafka + Zookeeper instantly
- 🧪 Write unit tests using the `TopologyTestDriver`
- 📝 Log your topologies on startup to debug flow issues
- ⚡ Use `InMemory` state stores for lightning-fast local tests

</td>
</tr>
</table>

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## ❓ Frequently Asked Questions

<details>
<summary><b>Is this a direct port of Java Kafka Streams?</b></summary>

While the architecture and API concepts are heavily inspired by the Java implementation, Streamiz is a complete rewrite designed specifically for .NET. It leverages C# idioms and async/await, rather than just wrapping the Java Virtual Machine.
</details>

<details>
<summary><b>Does it support Kafka exactly-once semantics?</b></summary>

Yes. Streamiz supports `EXACTLY_ONCE` processing guarantees by utilizing Kafka's transactional APIs under the hood.
</details>

<details>
<summary><b>Can I use it with .NET Framework?</b></summary>

Streamiz is built for modern .NET (Core 3.1, .NET 6, .NET 8+). We highly recommend using .NET 8 for the best performance and newest C# features.
</details>

<details>
<summary><b>How do I monitor a Streamiz application?</b></summary>

You can integrate it with standard .NET telemetry tools like OpenTelemetry, Prometheus, or just use the built-in metrics exposed via the `IMetricsReporter` interface.
</details>

<details>
<summary><b>How do I report a bug?</b></summary>

Open an issue on the GitHub repository. Include your .NET version, the Kafka version, and a minimal reproducible example of your topology.
</details>

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 📜 License & Disclaimer

Distributed under the **Apache 2.0 License**. See [`LICENSE`](LICENSE) for details.

<br/>

<div align="center">

<a href="https://share.google/8qjTLAQzpRlMPpFB7">
  <img src="https://img.shields.io/badge/⬇️_INSTALL_NUGET-48CAE4?style=for-the-badge&logo=nuget&logoColor=white&labelColor=0077B6" height="55"/>
</a>

<br/><br/>

**⭐ If this library empowered your .NET architecture — star the repo!**

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=4,11,18&height=140&section=footer&text=Process.+Transform.+Stream.&fontSize=22&fontColor=48CAE4" width="100%"/>

</div>

