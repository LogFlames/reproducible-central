[com.taobao.arthas:arthas-all](https://central.sonatype.com/artifact/com.taobao.arthas/arthas-all/versions) RB check
=======

[![Reproducible Builds](https://reproducible-builds.org/images/logos/rb.svg) an independently-verifiable path from source to binary code](https://reproducible-builds.org/)

## Project: [com.taobao.arthas:arthas-all](https://central.sonatype.com/artifact/com.taobao.arthas/arthas-all/versions) [![Reproducible Builds](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/jvm-repo-rebuild/reproducible-central/master/content/com/taobao/arthas/badge.json)](https://github.com/jvm-repo-rebuild/reproducible-central/blob/master/content/com/taobao/arthas/README.md)

Source code: [https://github.com/alibaba/arthas.git](https://github.com/alibaba/arthas.git)

<details><summary>This project defines 28 modules:</summary>

* [com.taobao.arthas:arthas-agent](https://central.sonatype.com/artifact/com.taobao.arthas/arthas-agent/overview)
* [com.taobao.arthas:arthas-agent-attach](https://central.sonatype.com/artifact/com.taobao.arthas/arthas-agent-attach/overview)
* [com.taobao.arthas:arthas-all](https://central.sonatype.com/artifact/com.taobao.arthas/arthas-all/overview)
* [com.taobao.arthas:arthas-boot](https://central.sonatype.com/artifact/com.taobao.arthas/arthas-boot/overview)
* [com.taobao.arthas:arthas-boot3](https://central.sonatype.com/artifact/com.taobao.arthas/arthas-boot3/overview)
* [com.taobao.arthas:arthas-bytekit](https://central.sonatype.com/artifact/com.taobao.arthas/arthas-bytekit/overview)
* [com.taobao.arthas:arthas-client](https://central.sonatype.com/artifact/com.taobao.arthas/arthas-client/overview)
* [com.taobao.arthas:arthas-common](https://central.sonatype.com/artifact/com.taobao.arthas/arthas-common/overview)
* [com.taobao.arthas:arthas-core](https://central.sonatype.com/artifact/com.taobao.arthas/arthas-core/overview)
* [com.taobao.arthas:arthas-demo](https://central.sonatype.com/artifact/com.taobao.arthas/arthas-demo/overview)
* [com.taobao.arthas:arthas-grpc-server](https://central.sonatype.com/artifact/com.taobao.arthas/arthas-grpc-server/overview)
* [com.taobao.arthas:arthas-grpc-web-proxy](https://central.sonatype.com/artifact/com.taobao.arthas/arthas-grpc-web-proxy/overview)
* [com.taobao.arthas:arthas-mcp-server](https://central.sonatype.com/artifact/com.taobao.arthas/arthas-mcp-server/overview)
* [com.taobao.arthas:arthas-memorycompiler](https://central.sonatype.com/artifact/com.taobao.arthas/arthas-memorycompiler/overview)
* [com.taobao.arthas:arthas-packaging](https://central.sonatype.com/artifact/com.taobao.arthas/arthas-packaging/overview)
* [com.taobao.arthas:arthas-site](https://central.sonatype.com/artifact/com.taobao.arthas/arthas-site/overview)
* [com.taobao.arthas:arthas-spring-boot-starter](https://central.sonatype.com/artifact/com.taobao.arthas/arthas-spring-boot-starter/overview)
* [com.taobao.arthas:arthas-spy](https://central.sonatype.com/artifact/com.taobao.arthas/arthas-spy/overview)
* [com.taobao.arthas:arthas-testcase](https://central.sonatype.com/artifact/com.taobao.arthas/arthas-testcase/overview)
* [com.taobao.arthas:arthas-tunnel-client](https://central.sonatype.com/artifact/com.taobao.arthas/arthas-tunnel-client/overview)
* [com.taobao.arthas:arthas-tunnel-common](https://central.sonatype.com/artifact/com.taobao.arthas/arthas-tunnel-common/overview)
* [com.taobao.arthas:arthas-tunnel-server](https://central.sonatype.com/artifact/com.taobao.arthas/arthas-tunnel-server/overview)
* [com.taobao.arthas:math-game](https://central.sonatype.com/artifact/com.taobao.arthas/math-game/overview)
* [com.taobao.arthas:native-agent](https://central.sonatype.com/artifact/com.taobao.arthas/native-agent/overview)
* [com.taobao.arthas:native-agent-common](https://central.sonatype.com/artifact/com.taobao.arthas/native-agent-common/overview)
* [com.taobao.arthas:native-agent-management-web](https://central.sonatype.com/artifact/com.taobao.arthas/native-agent-management-web/overview)
* [com.taobao.arthas:native-agent-proxy](https://central.sonatype.com/artifact/com.taobao.arthas/native-agent-proxy/overview)
* [com.taobao.arthas:web-ui](https://central.sonatype.com/artifact/com.taobao.arthas/web-ui/overview)
</details>

rebuilding **40 releases** of com.taobao.arthas:arthas-all:
- **0** releases were found successfully **fully reproducible** (100% reproducible artifacts :white_check_mark:),
- 40 had issues (some unreproducible artifacts :warning:, see eventual :mag: diffoscope and/or :memo: issue tracker links):
  - running [stabilize](doc/stabilize.md) on 1, 0 had all their differences removed :recycle:, 1 still had differences :rotating_light: or files not supported by stabilize :no_entry_sign:

| version | [build spec](/BUILDSPEC.md) | [result](https://reproducible-builds.org/docs/jvm/): reproducible? | [stabilize](https://github.com/google/oss-rebuild/blob/main/cmd/stabilize/README.md) | size |
| -- | --------- | ------ | ------ | -- |
| [4.1.1](https://central.sonatype.com/artifact/com.taobao.arthas/arthas-all/4.1.1/pom) | | | |
| [4.1.0](https://central.sonatype.com/artifact/com.taobao.arthas/arthas-all/4.1.0/pom) | [mvn jdk25](arthas-4.1.0.buildspec) | [result](arthas-all-4.1.0.buildinfo): [1 :white_check_mark:  75 :warning:](arthas-all-4.1.0.buildcompare) [:memo:](https://github.com/alibaba/arthas/pull/3001) | 47 :rotating_light: 23 :no_entry_sign: | 178M |
| [4.0.5](https://central.sonatype.com/artifact/com.taobao.arthas/arthas-all/4.0.5/pom) | [mvn jdk21](arthas-4.0.5.buildspec) | [result](arthas-all-4.0.5.buildinfo): [38 :white_check_mark:  35 :warning:](arthas-all-4.0.5.buildcompare) [:memo:](https://github.com/alibaba/arthas/pull/3001) | - | 168M |
| [4.0.4](https://central.sonatype.com/artifact/com.taobao.arthas/arthas-all/4.0.4/pom) | [mvn jdk21](arthas-4.0.4.buildspec) | [result](arthas-all-4.0.4.buildinfo): [38 :white_check_mark:  35 :warning:](arthas-all-4.0.4.buildcompare) [:memo:](https://github.com/alibaba/arthas/pull/3001) | - | 167M |
| [4.0.3](https://central.sonatype.com/artifact/com.taobao.arthas/arthas-all/4.0.3/pom) | [mvn jdk21](arthas-4.0.3.buildspec) | [result](arthas-all-4.0.3.buildinfo): [39 :white_check_mark:  34 :warning:](arthas-all-4.0.3.buildcompare) [:memo:](https://github.com/alibaba/arthas/pull/3001) | - | 174M |
| [4.0.2](https://central.sonatype.com/artifact/com.taobao.arthas/arthas-all/4.0.2/pom) | [mvn jdk21](arthas-4.0.2.buildspec) | [result](arthas-all-4.0.2.buildinfo): [31 :white_check_mark:  27 :warning:](arthas-all-4.0.2.buildcompare) [:memo:](https://github.com/alibaba/arthas/pull/3001) | - | 99M |
| [4.0.1](https://central.sonatype.com/artifact/com.taobao.arthas/arthas-all/4.0.1/pom) | [mvn jdk21](arthas-4.0.1.buildspec) | [result](arthas-all-4.0.1.buildinfo): [31 :white_check_mark:  27 :warning:](arthas-all-4.0.1.buildcompare) [:mag:](arthas-all-4.0.1.diffoscope) [:memo:](https://github.com/alibaba/arthas/pull/3001) | - | 113M |
| [4.0.0](https://central.sonatype.com/artifact/com.taobao.arthas/arthas-all/4.0.0/pom) | [mvn jdk8](arthas-4.0.0.buildspec) | [result](arthas-all-4.0.0.buildinfo): [4 :white_check_mark:  54 :warning:](arthas-all-4.0.0.buildcompare) [:mag:](arthas-all-4.0.0.diffoscope) [:memo:](https://github.com/alibaba/arthas/pull/3001) | - | 112M |
| [3.7.3](https://central.sonatype.com/artifact/com.taobao.arthas/arthas-all/3.7.3/pom) | [mvn jdk11](arthas-3.7.3.buildspec) | [result](arthas-all-3.7.3.buildinfo): [30 :white_check_mark:  24 :warning:](arthas-all-3.7.3.buildcompare) [:mag:](arthas-all-3.7.3.diffoscope) [:memo:](https://github.com/alibaba/arthas/pull/3001) | - | 100M |
| [3.7.2](https://central.sonatype.com/artifact/com.taobao.arthas/arthas-all/3.7.2/pom) | [mvn jdk11](arthas-3.7.2.buildspec) | [result](arthas-all-3.7.2.buildinfo): [48 :white_check_mark:  6 :warning:](arthas-all-3.7.2.buildcompare) | - | 100M |
| [3.7.1](https://central.sonatype.com/artifact/com.taobao.arthas/arthas-all/3.7.1/pom) | [mvn jdk8](arthas-3.7.1.buildspec) | [result](arthas-all-3.7.1.buildinfo): [48 :white_check_mark:  6 :warning:](arthas-all-3.7.1.buildcompare) | - | 100M |
| [3.7.0](https://central.sonatype.com/artifact/com.taobao.arthas/arthas-all/3.7.0/pom) | [mvn jdk8](arthas-3.7.0.buildspec) | [result](arthas-all-3.7.0.buildinfo): [47 :white_check_mark:  7 :warning:](arthas-all-3.7.0.buildcompare) | - | 100M |
| [3.6.9](https://central.sonatype.com/artifact/com.taobao.arthas/arthas-all/3.6.9/pom) | [mvn jdk8](arthas-3.6.9.buildspec) | [result](arthas-all-3.6.9.buildinfo): [48 :white_check_mark:  6 :warning:](arthas-all-3.6.9.buildcompare) | - | 100M |
| [3.6.8](https://central.sonatype.com/artifact/com.taobao.arthas/arthas-all/3.6.8/pom) | [mvn jdk8](arthas-3.6.8.buildspec) | [result](arthas-all-3.6.8.buildinfo): [48 :white_check_mark:  6 :warning:](arthas-all-3.6.8.buildcompare) | - | 85M |
| [3.6.7](https://central.sonatype.com/artifact/com.taobao.arthas/arthas-all/3.6.7/pom) | [mvn jdk8](arthas-3.6.7.buildspec) | [result](arthas-all-3.6.7.buildinfo): [48 :white_check_mark:  6 :warning:](arthas-all-3.6.7.buildcompare) | - | 85M |
| [3.6.6](https://central.sonatype.com/artifact/com.taobao.arthas/arthas-all/3.6.6/pom) | [mvn jdk8](arthas-3.6.6.buildspec) | [result](arthas-all-3.6.6.buildinfo): [47 :white_check_mark:  6 :warning:](arthas-all-3.6.6.buildcompare) | - | 86M |
| [3.6.5](https://central.sonatype.com/artifact/com.taobao.arthas/arthas-all/3.6.5/pom) | [mvn jdk8](arthas-3.6.5.buildspec) | [result](arthas-all-3.6.5.buildinfo): [47 :white_check_mark:  6 :warning:](arthas-all-3.6.5.buildcompare) | - | 86M |
| [3.6.4](https://central.sonatype.com/artifact/com.taobao.arthas/arthas-all/3.6.4/pom) | [mvn jdk8](arthas-3.6.4.buildspec) | [result](arthas-all-3.6.4.buildinfo): [29 :white_check_mark:  22 :warning:](arthas-all-3.6.4.buildcompare) | - | 86M |
| [3.6.3](https://central.sonatype.com/artifact/com.taobao.arthas/arthas-all/3.6.3/pom) | [mvn jdk8](arthas-3.6.3.buildspec) | [result](arthas-all-3.6.3.buildinfo): [49 :white_check_mark:  4 :warning:](arthas-all-3.6.3.buildcompare) | - | 85M |
| [3.6.2](https://central.sonatype.com/artifact/com.taobao.arthas/arthas-all/3.6.2/pom) | [mvn jdk8](arthas-3.6.2.buildspec) | [result](arthas-all-3.6.2.buildinfo): [49 :white_check_mark:  4 :warning:](arthas-all-3.6.2.buildcompare) | - | 85M |
| [3.6.1](https://central.sonatype.com/artifact/com.taobao.arthas/arthas-all/3.6.1/pom) | [mvn jdk8](arthas-3.6.1.buildspec) | [result](arthas-all-3.6.1.buildinfo): [48 :white_check_mark:  5 :warning:](arthas-all-3.6.1.buildcompare) | - | 82M |
| [3.6.0](https://central.sonatype.com/artifact/com.taobao.arthas/arthas-all/3.6.0/pom) | [mvn jdk8](arthas-3.6.0.buildspec) | [result](arthas-all-3.6.0.buildinfo): [48 :white_check_mark:  5 :warning:](arthas-all-3.6.0.buildcompare) [:mag:](arthas-all-3.6.0.diffoscope) | - | 82M |
| [3.5.6](https://central.sonatype.com/artifact/com.taobao.arthas/arthas-all/3.5.6/pom) | [mvn jdk8](arthas-3.5.6.buildspec) | [result](arthas-all-3.5.6.buildinfo): [48 :white_check_mark:  5 :warning:](arthas-all-3.5.6.buildcompare) | - | 82M |
| [3.5.5](https://central.sonatype.com/artifact/com.taobao.arthas/arthas-all/3.5.5/pom) | [mvn jdk8](arthas-3.5.5.buildspec) | [result](arthas-all-3.5.5.buildinfo): [48 :white_check_mark:  5 :warning:](arthas-all-3.5.5.buildcompare) | - | 82M |
| [3.5.4](https://central.sonatype.com/artifact/com.taobao.arthas/arthas-all/3.5.4/pom) | [mvn jdk8](arthas-3.5.4.buildspec) | [result](arthas-all-3.5.4.buildinfo): [48 :white_check_mark:  5 :warning:](arthas-all-3.5.4.buildcompare) | - | 81M |
| [3.5.3](https://central.sonatype.com/artifact/com.taobao.arthas/arthas-all/3.5.3/pom) | [mvn jdk8](arthas-3.5.3.buildspec) | [result](arthas-all-3.5.3.buildinfo): [48 :white_check_mark:  5 :warning:](arthas-all-3.5.3.buildcompare) | - | 81M |
| [3.5.2](https://central.sonatype.com/artifact/com.taobao.arthas/arthas-all/3.5.2/pom) | [mvn jdk8](arthas-3.5.2.buildspec) | [result](arthas-all-3.5.2.buildinfo): [48 :white_check_mark:  5 :warning:](arthas-all-3.5.2.buildcompare) | - | 80M |
| [3.5.1](https://central.sonatype.com/artifact/com.taobao.arthas/arthas-all/3.5.1/pom) | [mvn jdk8](arthas-3.5.1.buildspec) | [result](arthas-all-3.5.1.buildinfo): [48 :white_check_mark:  5 :warning:](arthas-all-3.5.1.buildcompare) [:mag:](arthas-all-3.5.1.diffoscope) | - | 80M |
| [3.5.0](https://central.sonatype.com/artifact/com.taobao.arthas/arthas-all/3.5.0/pom) | [mvn jdk8](arthas-3.5.0.buildspec) | [result](arthas-all-3.5.0.buildinfo): [48 :white_check_mark:  5 :warning:](arthas-all-3.5.0.buildcompare) | - | 80M |
| [3.4.8](https://central.sonatype.com/artifact/com.taobao.arthas/arthas-all/3.4.8/pom) | [mvn jdk8](arthas-3.4.8.buildspec) | [result](arthas-all-3.4.8.buildinfo): [48 :white_check_mark:  5 :warning:](arthas-all-3.4.8.buildcompare) [:mag:](https://github.com/jvm-repo-rebuild/reproducible-central/blob/master/content/com/taobao/arthas/arthas-all-3.4.8.diffoscope) | - | 80M |
| [3.4.7](https://central.sonatype.com/artifact/com.taobao.arthas/arthas-all/3.4.7/pom) | [mvn jdk8](arthas-3.4.7.buildspec) | [result](arthas-all-3.4.7.buildinfo): [46 :white_check_mark:  7 :warning:](arthas-all-3.4.7.buildcompare) | - | 80M |
| [3.4.6](https://central.sonatype.com/artifact/com.taobao.arthas/arthas-all/3.4.6/pom) | [mvn jdk8](arthas-3.4.6.buildspec) | [result](arthas-all-3.4.6.buildinfo): [48 :white_check_mark:  5 :warning:](arthas-all-3.4.6.buildcompare) [:mag:](https://github.com/jvm-repo-rebuild/reproducible-central/blob/master/content/com/taobao/arthas/arthas-all-3.4.6.diffoscope) | - | 79M |
| [3.4.5](https://central.sonatype.com/artifact/com.taobao.arthas/arthas-all/3.4.5/pom) | [mvn jdk8](arthas-3.4.5.buildspec) | [result](arthas-all-3.4.5.buildinfo): [31 :white_check_mark:  22 :warning:](arthas-all-3.4.5.buildcompare) [:memo:](https://github.com/alibaba/arthas/pull/1604) | - | 79M |
| [3.4.4](https://central.sonatype.com/artifact/com.taobao.arthas/arthas-all/3.4.4/pom) | [mvn jdk8](arthas-3.4.4.buildspec) | [result](arthas-all-3.4.4.buildinfo): [30 :white_check_mark:  23 :warning:](arthas-all-3.4.4.buildcompare) [:memo:](https://github.com/alibaba/arthas/pull/1604) | - | 78M |
| [3.4.3](https://central.sonatype.com/artifact/com.taobao.arthas/arthas-all/3.4.3/pom) | [mvn jdk8](arthas-3.4.3.buildspec) | [result](arthas-tunnel-server-3.4.3.buildinfo): [31 :white_check_mark:  21 :warning:](arthas-tunnel-server-3.4.3.buildcompare) | - | 66M |
| [3.4.2](https://central.sonatype.com/artifact/com.taobao.arthas/arthas-all/3.4.2/pom) | [mvn jdk8](arthas-3.4.2.buildspec) | [result](arthas-tunnel-server-3.4.2.buildinfo): [31 :white_check_mark:  21 :warning:](arthas-tunnel-server-3.4.2.buildcompare) | - | 65M |
| [3.4.1](https://central.sonatype.com/artifact/com.taobao.arthas/arthas-all/3.4.1/pom) | [mvn jdk8](arthas-3.4.1.buildspec) | [result](arthas-tunnel-server-3.4.1.buildinfo): [31 :white_check_mark:  21 :warning:](arthas-tunnel-server-3.4.1.buildcompare) | - | 65M |
| [3.4.0](https://central.sonatype.com/artifact/com.taobao.arthas/arthas-all/3.4.0/pom) | [mvn jdk8](arthas-3.4.0.buildspec) | [result](arthas-tunnel-server-3.4.0.buildinfo): [31 :white_check_mark:  21 :warning:](arthas-tunnel-server-3.4.0.buildcompare) | - | 65M |
| [3.3.9](https://central.sonatype.com/artifact/com.taobao.arthas/arthas-all/3.3.9/pom) | [mvn jdk8](arthas-3.3.9.buildspec) | [result](arthas-tunnel-server-3.3.9.buildinfo): [31 :white_check_mark:  21 :warning:](arthas-tunnel-server-3.3.9.buildcompare) | - | 65M |
| [3.3.8](https://central.sonatype.com/artifact/com.taobao.arthas/arthas-all/3.3.8/pom) | [mvn jdk8](arthas-3.3.8.buildspec) | [result](arthas-tunnel-server-3.3.8.buildinfo): [31 :white_check_mark:  21 :warning:](arthas-tunnel-server-3.3.8.buildcompare) | - | 65M |
| [3.3.7](https://central.sonatype.com/artifact/com.taobao.arthas/arthas-all/3.3.7/pom) | [mvn jdk8](arthas-3.3.7.buildspec) | [result](arthas-tunnel-server-3.3.7.buildinfo): [31 :white_check_mark:  21 :warning:](arthas-tunnel-server-3.3.7.buildcompare) [:memo:](https://github.com/alibaba/arthas/commit/20f31d47f23b2ac79ea7cb335e335d5e7b1a552a) | - | 65M |

<i>(size is calculated without javadoc, that has been excluded from reproducibility checks)</i>
