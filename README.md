<div align="center">
	<div>
		<img width="180" src="/awesome-logo.png" alt="Awesome Bigtable">
	</div>
    <br />
	<p>
		:zap: Delightful list of <a href="https://cloud.google.com/bigtable/">Google Bigtable</a> resources, packages and interesting finds.
	</p>
	<br>
	<img src="https://awesome.re/badge.svg" alt="Awesome List">
</div>

***

# Awesome Bigtable with stars

[Bigtable](https://cloud.google.com/bigtable) is a fully managed, scalable NoSQL database service for large analytical and operational workloads, built and managed by Google.

## Contents

* [Tools](#tools)
  * [Official Client Libraries](#official-client-libraries)
  * [Other Client Libraries](#other-client-libraries)
  * [Command-line](#command-line)
  * [GUI](#gui)
  * [Emulators](#emulators)
  * [Databases](#databases)
* [Resources](#resources)
  * [Articles & Blogs](#articles--blogs)
  * [Tutorials](#tutorials)
* [Cool Stuff](#cool-stuff)
  * [Inspired by Bigtable](#inspired-by-bigtable)
  * [Interesting Projects](#interesting-projects)

***

If you are new to Bigtable I'd recommend checking out the [Bigtable Documentation](https://cloud.google.com/bigtable/docs/). The docs are a great place to start, as you can view a full list of integrations, tutorials and other treats. This list is meant to be a curated list of awesome Bigtable "things" to supplement any official documentation.

## Tools

A curated list of tools that will help you when working with or building on-top of Bigtable.

### Official Client Libraries

* [Go](https://github.com/googleapis/google-cloud-go/tree/master/bigtable) ⭐ 4,494 | 🐛 421 | 🌐 Go | 📅 2026-08-14 - Official implementation of the Google Cloud Bigtable Go client.
* [C#](https://github.com/googleapis/google-cloud-dotnet) ⭐ 1,090 | 🐛 17 | 🌐 C# | 📅 2026-08-14 - Official implementation of the Google Cloud Bigtable .NET client.
* [C++](https://github.com/GoogleCloudPlatform/google-cloud-cpp/tree/master/google/cloud/bigtable) ⭐ 657 | 🐛 208 | 🌐 C++ | 📅 2026-08-14 - Official implementation of the Google Cloud Bigtable C++ client.
* [HBase Java](https://github.com/GoogleCloudPlatform/cloud-bigtable-client) ⭐ 184 | 🐛 211 | 🌐 Java | 📅 2026-08-14 - Official Java libraries and HBase client extensions for accessing Google Cloud Bigtable.
* [Node.js](https://github.com/googleapis/nodejs-bigtable) ⚠️ Archived - Official implementation of the Google Cloud Bigtable Node.js client.
* [Java](https://github.com/googleapis/java-bigtable) ⚠️ Archived - Official implementation of the Google Cloud Bigtable Java client.
* [Python](https://github.com/googleapis/python-bigtable) ⚠️ Archived - Official implementation of the Google Cloud Bigtable python client.
* [HappyBase](https://github.com/googleapis/google-cloud-python-happybase) ⚠️ Archived - Official client which uses a HappyBase emulation layer which uses Bigtable as the underlying storage layer.
* [PHP](https://github.com/googleapis/google-cloud-php-bigtable) ⭐ 13 | 🐛 1 | 🌐 PHP | 📅 2026-08-10 - Official implementation of the Google Cloud Bigtable PHP client.

### Other Client Libraries

* [Rust Bigtable](https://github.com/durch/rust-bigtable) ⭐ 23 | 🐛 0 | 🌐 Rust | 📅 2025-12-09 - Rust library for working with Google Bigtable Data API.
* [AsyncBigtable](https://github.com/OpenTSDB/asyncbigtable) ⭐ 23 | 🐛 7 | 🌐 Java | 📅 2021-07-29 - Implementation of AsyncHBase but on top of Google's Cloud Bigtable service.

### Command-line

* [cbt](https://cloud.google.com/bigtable/docs/cbt-overview) - Official command-line interface for performing several different operations on Cloud Bigtable.
* [btcli](https://github.com/takashabe/btcli) ⭐ 21 | 🐛 4 | 🌐 Go | 📅 2023-02-25 - CLI client for the Bigtable with auto-completion.

### GUI

* [vscode-bigtable](https://github.com/a7ul/vscode-bigtable) ⭐ 6 | 🐛 0 | 🌐 TypeScript | 📅 2022-05-26 - VSCode extension that provides an easy to use GUI for querying bigtable instances.

### Emulators

* [Spotify Docker Bigtable](https://github.com/spotify/docker-bigtable) ⚠️ Archived - Docker container with an in memory implementation of Google Cloud Bigtable.
* [Shopify Bigtable Emulator](https://github.com/Shopify/bigtable-emulator) ⚠️ Archived - In memory Go implementation of Bigtable.
* [LittleTable](https://github.com/steveniemitz/littletable) ⭐ 13 | 🐛 3 | 🌐 Java | 📅 2022-07-27 - In-memory JVM-based emulator for Bigtable.
* [Google Emulator](https://cloud.google.com/bigtable/docs/emulator) - Official in-memory emulator for Cloud Bigtable, included with the Google Cloud SDK.

### Databases

* [Janusgraph](https://github.com/JanusGraph/janusgraph) ⭐ 5,828 | 🐛 598 | 🌐 Java | 📅 2026-07-23 - Open-source, distributed graph database that can use Bigtable as its storage layer.
* [GeoMesa](https://github.com/locationtech/geomesa) ⭐ 1,492 | 🐛 199 | 🌐 Scala | 📅 2026-08-14 - Suite of tools for working with big geo-spatial data in a distributed fashion, that can leverage Bigtable as its backend.
* [Heroic](https://github.com/spotify/heroic) ⚠️ Archived - Scalable time series database based on Bigtable, Cassandra, and Elasticsearch.
* [GeoWave](https://github.com/locationtech/geowave) ⭐ 527 | 🐛 91 | 🌐 Java | 📅 2025-09-29 - Tool that provides geospatial and temporal indexing on top of Accumulo, HBase, Bigtable, Cassandra, and DynamoDB.
* [HGraphDB](https://github.com/rayokota/hgraphdb) ⭐ 264 | 🐛 12 | 🌐 Java | 📅 2026-04-29 - Client layer for using HBase (Bigtable) as a graph database.
* [OpenTSDB](https://github.com/GoogleCloudPlatform/opentsdb-bigtable) ⚠️ Archived - An Open Source Time Series Data Base that can levearge Bigtable as its storage layer.
* [YildizDB](https://github.com/yildizdb/yildiz) ⭐ 26 | 🐛 13 | 🌐 TypeScript | 📅 2022-12-10 - Graph database layer on top of Bigtable.
* [Cattle DB](https://github.com/wuttem/cattledb) ⭐ 1 | 🐛 1 | 🌐 Python | 📅 2022-11-24 - Timeseries store built on top of Bigtable.

## Resources

A curated list of resources to help you get off the ground with Bigtable.

### Articles & Blogs

* [Bigtable: A Distributed Storage System for Structured Data](https://static.googleusercontent.com/media/research.google.com/en//archive/bigtable-osdi06.pdf) - Published on 2006.
* [A NoSQL massively parallel table](https://www.cs.rutgers.edu/~pxk/417/notes/content/bigtable.html) - Published on 2011-11.
* [How we moved our Historical Stats from MySQL to Bigtable with zero downtime](https://www.fastly.com/blog/how-we-moved-our-historical-stats-from-mysql-bigtable-zero-downtime) - Published on 2017-07.
* [Medium @duhroach](https://medium.com/@duhroach) - Bigtable centric posts by Colt McAnlis, DA @ Google.
  * [Cloud Bigtable Performance 101](https://medium.com/@duhroach/cloud-bigtable-performance-101-8bf884bc1d1c) - Published on 2018-11.
  * [The right Cloud Bigtable index makes all the difference.](https://medium.com/@duhroach/the-right-cloud-bigtable-index-makes-all-the-difference-3bcabe9bd65a) - Published on 2019-1.
  * [Cloud Bigtable : Getting the geography right](https://medium.com/@duhroach/cloud-bigtable-getting-the-geography-right-645577216516) - Published on 2019-1.
  * [Using Cloud Bigtable Monitoring UI](https://medium.com/@duhroach/using-cloud-bigtable-monitoring-ui-40d3f4c726d6) - Published on 2019-1.
* [Bigtable: storing Protobuf bytes in one column vs splitting the content into column families/qualifiers](https://tech.travelaudience.com/bigtable-storing-protobuf-bytes-in-one-column-vs-splitting-the-content-into-column-families-c231bdff8db7) - Published on 2018-1.
* [Using Google Cloud Emulators in Integration Tests](https://medium.com/google-cloud/using-google-cloud-emulators-for-integration-tests-7812890ebe0d) - Published on 2017-6.
* [The Joy and Pain of using Google Bigtable](https://syslog.ravelin.com/the-joy-and-pain-of-using-google-bigtable-4210604c75be) - Published on 2019-1.

### Tutorials

* [Google Tutorials for Bigtable](https://cloud.google.com/bigtable/docs/tutorials) - List of official tutorials related to Bigtable.
* [Cloud Bigtable Examples](https://github.com/GoogleCloudPlatform/cloud-bigtable-examples) ⭐ 236 | 🐛 14 | 🌐 Java | 📅 2026-03-25 - Repo containing official examples of using Bigtable.
* [Introduction to Google Cloud Bigtable](https://cloudacademy.com/course/introduction-to-google-cloud-bigtable/) - CloudAcademy provided intro tutorial to Bigtable (membership required).

## Cool Stuff

A list of cool things related to Bigtable.

### Inspired by Bigtable

* [Tera](https://github.com/baidu/tera) ⭐ 1,902 | 🐛 172 | 🌐 C++ | 📅 2024-06-05 - High performance distributed NoSQL database.
* [Apache Accumulo](https://github.com/apache/accumulo) ⭐ 1,159 | 🐛 346 | 🌐 Java | 📅 2026-08-11 - Sorted, distributed key/value store that provides robust, scalable data storage and retrieval.
* [obigstore](https://github.com/mfp/obigstore) ⭐ 44 | 🐛 0 | 🌐 OCaml | 📅 2017-09-26 - Database with Bigtable-like data model atop LevelDB.
* [Apache Cassandra](http://cassandra.apache.org/) - Highly-scalable partitioned row store.
* [Apache HBase](https://hbase.apache.org/) - The Hadoop database, a distributed, scalable, big data store.

### Interesting Projects

* [Bigtable Autoscaler](https://github.com/spotify/bigtable-autoscaler) ⚠️ Archived - Service that autoscales Bigtable clusters based on CPU load.
* [YildizDB Bigtable](https://github.com/yildizdb/bigtable) ⭐ 12 | 🐛 10 | 🌐 TypeScript | 📅 2022-12-03 - TypeScript Bigtable Client with 🔋🔋 included.

<!--lint ignore no-emphasis-as-heading-->

**Awesome mentioned badge**

If your package or repository is mentioned in this list feel free to add the Awesome mentioned badge to your README.md.

```md
[![Mentioned in Awesome Bigtable](https://awesome.re/mentioned-badge-flat.svg)](https://github.com/zrosenbauer/awesome-bigtable)
```

***

**Logo Source:** <https://logomakr.com/4gLK5l>

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-14._
