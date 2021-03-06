# Secor release notes

## v0.29
* [Javadoc Update: fix a few missing params and exclude a few packages](https://github.com/pinterest/secor/pull/1463)
* [Add native support for Prometheus](https://github.com/pinterest/secor/pull/1452)
* [Rework cleanup process on shutdown](https://github.com/pinterest/secor/pull/1449)
* [Add secor.max.active.files property to controll active file count](https://github.com/pinterest/secor/pull/1443)
* [Add max.poll.interval.ms kafka producer setting](https://github.com/pinterest/secor/pull/1408)
* [Fix various unit test failures related to powermock running in JDK 11](https://github.com/pinterest/secor/pull/1400)
* [Upgrade guava to 24.1.1 to address the following security issue](https://github.com/pinterest/secor/pull/1394)
* [Upgrade parquet version from 1.9.0 to 1.11.0](https://github.com/pinterest/secor/pull/1361)

## v0.28

* [Change default build profile to kafka-2.0.0 to work with kafka client library 2.0.0 and above](https://github.com/pinterest/secor/commit/556ca7838604e84ec3442173836551a5e8e6b807)
* [Add support to upload last seen offset onto ZK to solve the deterministic uploading](https://github.com/pinterest/secor/commit/31e7f20c26ac77f634ad48e8651661d76066144c)
* [Enhance secor's metrics monitoring library to integrate with more metrics backend](https://github.com/pinterest/secor/issues/1341)
* [ProgressMonitor: Handle failure of partition](https://github.com/pinterest/secor/pull/1346)
* [Add more metrics for uploader](https://github.com/pinterest/secor/commit/93c96e5a428d875d08493cbd9cc0f7bf76194c11)
* [Support Micrometer metrics facade to integrate with more metrics libraries](https://github.com/pinterest/secor/pull/1342)
* [JSON array ob object saved as ORC format](https://github.com/pinterest/secor/pull/1309)
* [docker-entrypoint.sh shouldn't use Bash if syntax](https://github.com/pinterest/secor/pull/1269)
* [Handle missing topic list config](https://github.com/pinterest/secor/pull/1232)
* [Tighten up the curator API](https://github.com/pinterest/secor/pull/1090)
* [Message offset adjust](https://github.com/pinterest/secor/pull/1017)
* [Support union types](https://github.com/pinterest/secor/pull/1011)
* [Reject non-string keys](https://github.com/pinterest/secor/pull/1004)
* [Failed to apply upload policy](https://github.com/pinterest/secor/pull/1001)
* [Handle map types](https://github.com/pinterest/secor/pull/982)
* [Test case for JsonORCFileReaderWriterFactory](https://github.com/pinterest/secor/pull/965)
* [Query Avro schema from schema registry if it is missing](https://github.com/pinterest/secor/pull/951)
* [Adding exec to the java command in the docker entrypoint](https://github.com/pinterest/secor/pull/884)
* [Changing shell in docker-entrypoint.sh from bash to sh](https://github.com/pinterest/secor/pull/881)
* [Added the ability to configure the topic-to-Avro-schema relationship manually (i.e. not using Confluent Schema Registry](https://github.com/pinterest/secor/pull/860)
* [Using duration to match configuration parameter](https://github.com/pinterest/secor/pull/842)
* [WIP avro field parser](https://github.com/pinterest/secor/pull/718)
* [Fix messagePack, try-with-resources](https://github.com/pinterest/secor/pull/686)
* [Send null messages to kafka avro deserializer](https://github.com/pinterest/secor/pull/672)
* [Add deterministic upload mode](https://github.com/pinterest/secor/pull/602)
* [Add message.timestamp.skew.max.ms to secor configuration](https://github.com/pinterest/secor/pull/597)
* [Fix deadlock when secor.upload.on.shutdown=true](https://github.com/pinterest/secor/pull/593)
