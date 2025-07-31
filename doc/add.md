New Releases To Add
===================

<!-- BEGIN GENERATED ADD OK -->
| artifactId | from | to | command |
| ---------- | ---- | -- | ------- |
| <!-- 20250731185344 --> [maven-lockfile](../content/io/github/chains-project/maven-lockfile/README.md) | [5.6.0](../content/io/github/chains-project/maven-lockfile/maven-lockfile-5.6.0.buildspec) :white_check_mark: | [5.6.1](../content/io/github/chains-project/maven-lockfile/maven-lockfile-5.6.1.buildspec) | `bin/add-new-release.sh content/io/github/chains-project/maven-lockfile/maven-lockfile-5.6.0.buildspec 5.6.1` |
| <!-- 20250731093617 --> [jackrabbit-filevault](../content/org/apache/jackrabbit/filevault/README.md) | [3.8.4](../content/org/apache/jackrabbit/filevault/jackrabbit-filevault-3.8.4.buildspec) :white_check_mark: | [4.0.0](../content/org/apache/jackrabbit/filevault/jackrabbit-filevault-4.0.0.buildspec) | `bin/add-new-release.sh content/org/apache/jackrabbit/filevault/jackrabbit-filevault-3.8.4.buildspec 4.0.0` |
| <!-- 20250730222607 --> [hibernate-core](../content/org/hibernate/orm/hibernate-core/README.md) | [7.0.8.Final](../content/org/hibernate/orm/hibernate-core/hibernate-core-7.0.8.Final.buildspec) :white_check_mark: | [7.1.0.CR1](../content/org/hibernate/orm/hibernate-core/hibernate-core-7.1.0.CR1.buildspec) | `bin/add-new-release.sh content/org/hibernate/orm/hibernate-core/hibernate-core-7.0.8.Final.buildspec 7.1.0.CR1` |
| <!-- 20250730200130 --> [avaje-jsonb-parent](../content/io/avaje/jsonb/README.md) | [3.6](../content/io/avaje/jsonb/avaje-jsonb-3.6.buildspec) :white_check_mark: | [3.7-RC1](../content/io/avaje/jsonb/avaje-jsonb-3.7-RC1.buildspec) | `bin/add-new-release.sh content/io/avaje/jsonb/avaje-jsonb-3.6.buildspec 3.7-RC1` |
| <!-- 20250730060145 --> [orc](../content/org/apache/orc/README.md) | [2.1.3](../content/org/apache/orc/orc-2.1.3.buildspec) :white_check_mark: | [2.2.0](../content/org/apache/orc/orc-2.2.0.buildspec) | `bin/add-new-release.sh content/org/apache/orc/orc-2.1.3.buildspec 2.2.0` |
<!-- END GENERATED ADD OK -->

### Unexpected Diffoscope in Buildspec
`buildcompare` says `ko=0` but `buildspec` configures a `diffoscope` value in following releases:
<!-- BEGIN GENERATED UNEXPECTED DIFFOSCOPE -->
<!-- END GENERATED UNEXPECTED DIFFOSCOPE -->

### Missing Diffoscope in Buildspec
`buildspec` configures a `diffoscope` value to missing file in following releases:
<!-- BEGIN GENERATED MISSING DIFFOSCOPE -->
<!-- END GENERATED MISSING DIFFOSCOPE -->

## Apache Release Candidate in Staging

<!-- BEGIN GENERATED ADD STAGING -->
|    | artifactId | from | to | command |
| -- | ---------- | ---- | -- | ------- |
| <!-- 20250218094231 --> [:mailbox:](https://lists.apache.org/list?dev@wayang.apache.org:lte=1M:VOTE) | [wayang](../content/org/apache/wayang/README.md) | [1.0.0](../content/org/apache/wayang/wayang-1.0.0.buildspec) :warning: [:memo:](https://github.com/apache/incubator-wayang/pull/503) | [1.1.0](../content/org/apache/wayang/wayang-1.1.0.buildspec)  | `bin/add-new-release.sh content/org/apache/wayang/wayang-1.0.0.buildspec 1.1.0 staging` |
| <!-- 20250213085016 --> [:mailbox:](https://lists.apache.org/list?dev@ignite.apache.org:lte=1M:VOTE) | [apache-ignite](../content/org/apache/ignite/README.md) | [2.17.0](../content/org/apache/ignite/ignite-2.17.0.buildspec) :warning: | [3.0.0-alpha5](../content/org/apache/ignite/ignite-3.0.0-alpha5.buildspec)  | `bin/add-new-release.sh content/org/apache/ignite/ignite-2.17.0.buildspec 3.0.0-alpha5 staging` |
| <!-- 20250124102848 --> [:mailbox:](https://lists.apache.org/list?dev@karaf.apache.org:lte=1M:VOTE) | [karaf](../content/org/apache/karaf/karaf/README.md) | [4.4.7](../content/org/apache/karaf/karaf/karaf-4.4.7.buildspec) :warning: [:memo:](https://issues.apache.org/jira/browse/KARAF-7797) | [4.4.8](../content/org/apache/karaf/karaf/karaf-4.4.8.buildspec)  | `bin/add-new-release.sh content/org/apache/karaf/karaf/karaf-4.4.7.buildspec 4.4.8 staging` |
| <!-- 20241102080410 --> [:mailbox:](https://lists.apache.org/list?dev@tomee.apache.org:lte=1M:VOTE) | [jakartaee-api-parent](../content/org/apache/tomee/jakartaee-api/README.md) | [10.0](../content/org/apache/tomee/jakartaee-api/jakartaee-api-10.0.buildspec) :white_check_mark: | [10.0.1](../content/org/apache/tomee/jakartaee-api/jakartaee-api-10.0.1.buildspec)  | `bin/add-new-release.sh content/org/apache/tomee/jakartaee-api/jakartaee-api-10.0.buildspec 10.0.1 staging` |
| <!-- 20241024173436 --> [:mailbox:](https://lists.apache.org/list?dev@zookeeper.apache.org:lte=1M:VOTE) | [parent](../content/org/apache/zookeeper/README.md) | [3.9.3](../content/org/apache/zookeeper/zookeeper-3.9.3.buildspec) :warning: | [3.9.4](../content/org/apache/zookeeper/zookeeper-3.9.4.buildspec)  | `bin/add-new-release.sh content/org/apache/zookeeper/zookeeper-3.9.3.buildspec 3.9.4 staging` |
<!-- END GENERATED ADD STAGING -->

## New Release of non-Reproducible Previous

<!-- BEGIN GENERATED ADD KO -->
| artifactId | from | to | command |
| ---------- | ---- | -- | ------- |
| <!-- 20250731142932 --> [pulsar](../content/org/apache/pulsar/README.md) | [4.0.5](../content/org/apache/pulsar/pulsar-4.0.5.buildspec) :warning: | [4.0.6](../content/org/apache/pulsar/pulsar-4.0.6.buildspec) | `bin/add-new-release.sh content/org/apache/pulsar/pulsar-4.0.5.buildspec 4.0.6` |
| <!-- 20250731130343 --> [com.io7m.primogenitor](../content/com/io7m/primogenitor/README.md) | [8.5.0](../content/com/io7m/primogenitor/com.io7m.primogenitor-8.5.0.buildspec) :warning: | [9.0.0-beta0003](../content/com/io7m/primogenitor/com.io7m.primogenitor-9.0.0-beta0003.buildspec) | `bin/add-new-release.sh content/com/io7m/primogenitor/com.io7m.primogenitor-8.5.0.buildspec 9.0.0-beta0003` |
| <!-- 20250731112446 --> [hive](../content/org/apache/hive/README.md) | [4.0.1](../content/org/apache/hive/hive-4.0.1.buildspec) :warning: [:memo:](https://issues.apache.org/jira/browse/HIVE-28186) | [4.1.0](../content/org/apache/hive/hive-4.1.0.buildspec) | `bin/add-new-release.sh content/org/apache/hive/hive-4.0.1.buildspec 4.1.0` |
| <!-- 20250729192532 --> [plotsquared-bukkit](../content/com/intellectualsites/plotsquared/plotsquared-bukkit/README.md) | [7.5.4](../content/com/intellectualsites/plotsquared/plotsquared-bukkit/plotsquared-7.5.4.buildspec) :x: | [7.5.6](../content/com/intellectualsites/plotsquared/plotsquared-bukkit/plotsquared-7.5.6.buildspec) | `bin/add-new-release.sh content/com/intellectualsites/plotsquared/plotsquared-bukkit/plotsquared-7.5.4.buildspec 7.5.6` |
| <!-- 20250729143132 --> [langchain4j](../content/dev/langchain4j/README.md) | [1.1.0](../content/dev/langchain4j/langchain4j-1.1.0.buildspec) :warning: | [1.2.0](../content/dev/langchain4j/langchain4j-1.2.0.buildspec) | `bin/add-new-release.sh content/dev/langchain4j/langchain4j-1.1.0.buildspec 1.2.0` |
| <!-- 20250728233257 --> [swagger-ui](../content/org/webjars/swagger-ui/README.md) | [5.15.2](../content/org/webjars/swagger-ui/swagger-ui-5.15.2.buildspec) :x: | [5.27.0](../content/org/webjars/swagger-ui/swagger-ui-5.27.0.buildspec) | `bin/add-new-release.sh content/org/webjars/swagger-ui/swagger-ui-5.15.2.buildspec 5.27.0` |
| <!-- 20250724204546 --> [legend-engine](../content/org/finos/legend/engine/README.md) | [4.71.1](../content/org/finos/legend/engine/legend-engine-4.71.1.buildspec) :warning: [:memo:](https://github.com/finos/legend-engine/pull/1337#issuecomment-1508509457) | [4.93.0](../content/org/finos/legend/engine/legend-engine-4.93.0.buildspec) | `bin/add-new-release.sh content/org/finos/legend/engine/legend-engine-4.71.1.buildspec 4.93.0` |
| <!-- 20250721122729 --> [flexmonster](../content/org/webjars/flexmonster/README.md) | [2.9.107](../content/org/webjars/flexmonster/flexmonster-2.9.107.buildspec) :x: | [2.9.108](../content/org/webjars/flexmonster/flexmonster-2.9.108.buildspec) | `bin/add-new-release.sh content/org/webjars/flexmonster/flexmonster-2.9.107.buildspec 2.9.108` |
| <!-- 20250708102140 --> [camel](../content/org/apache/camel/camel/README.md) | [4.10.0](../content/org/apache/camel/camel/camel-4.10.0.buildspec) :x: | [4.13.0](../content/org/apache/camel/camel/camel-4.13.0.buildspec) | `bin/add-new-release.sh content/org/apache/camel/camel/camel-4.10.0.buildspec 4.13.0` |
| <!-- 20250624040809 --> [openfasttrace](../content/org/itsallcode/openfasttrace/README.md) | [4.1.0](../content/org/itsallcode/openfasttrace/openfasttrace-4.1.0.buildspec) :warning: | [4.2.0](../content/org/itsallcode/openfasttrace/openfasttrace-4.2.0.buildspec) | `bin/add-new-release.sh content/org/itsallcode/openfasttrace/openfasttrace-4.1.0.buildspec 4.2.0` |
| <!-- 20250531230706 --> [glassfish-parent](../content/org/glassfish/main/README.md) | [8.0.0-JDK17-M10](../content/org/glassfish/main/glassfish-8.0.0-JDK17-M10.buildspec) :warning: | [8.0.0-JDK17-M12](../content/org/glassfish/main/glassfish-8.0.0-JDK17-M12.buildspec) | `bin/add-new-release.sh content/org/glassfish/main/glassfish-8.0.0-JDK17-M10.buildspec 8.0.0-JDK17-M12` |
| <!-- 20250522192025 --> [git-commit-id-maven-plugin](../content/io/github/git-commit-id/README.md) | [9.0.0](../content/io/github/git-commit-id/git-commit-id-maven-plugin-9.0.0.buildspec) :x: | [9.0.2](../content/io/github/git-commit-id/git-commit-id-maven-plugin-9.0.2.buildspec) | `bin/add-new-release.sh content/io/github/git-commit-id/git-commit-id-maven-plugin-9.0.0.buildspec 9.0.2` |
| <!-- 20250304091455 --> [io.wcm.wcm.ui.granite](../content/io/wcm/io.wcm.wcm/ui/granite/README.md) | [1.9.12](../content/io/wcm/io.wcm.wcm/ui/granite/wcm-ui-granite-1.9.12.buildspec) :warning: | [1.10.6](../content/io/wcm/io.wcm.wcm/ui/granite/wcm-ui-granite-1.10.6.buildspec) | `bin/add-new-release.sh content/io/wcm/io.wcm.wcm/ui/granite/wcm-ui-granite-1.9.12.buildspec 1.10.6` |
| <!-- 20240313094557 --> [io.wcm.wcm.parsys](../content/io/wcm/io.wcm.wcm/parsys/README.md) | [1.6.4](../content/io/wcm/io.wcm.wcm/parsys/wcm-parsys-1.6.4.buildspec) :warning: | [1.7.4](../content/io/wcm/io.wcm.wcm/parsys/wcm-parsys-1.7.4.buildspec) | `bin/add-new-release.sh content/io/wcm/io.wcm.wcm/parsys/wcm-parsys-1.6.4.buildspec 1.7.4` |
| <!-- 20231012160021 --> [parent](../content/org/apache/sis/README.md) | [1.3](../content/org/apache/sis/parent-1.3.buildspec) :warning: [:memo:](https://github.com/apache/sis/pull/36) | [1.4](../content/org/apache/sis/parent-1.4.buildspec) | `bin/add-new-release.sh content/org/apache/sis/parent-1.3.buildspec 1.4` |
<!-- END GENERATED ADD KO -->

## Newest not reproducible

<!-- BEGIN GENERATED NEWEST NOT REPRODUCIBLE -->
| artifactId | newest |
| ---------- | ------ |
| <!-- 20250730122750 --> [efx-toolkit-java](../content/eu/europa/ted/eforms/efx-toolkit-java/README.md) | 2.0.0-alpha.5 :warning: |
| <!-- 20250730045733 --> [avaje-inject-parent](../content/io/avaje/inject/README.md) | 12.0-RC3 :warning: |
| <!-- 20250729150327 --> [hibernate-search-bom](../content/org/hibernate/search/hibernate-search-bom/README.md) | 8.1.0.Alpha1 :warning: |
| <!-- 20250729142844 --> [jspwiki-builder](../content/org/apache/jspwiki/README.md) | 2.12.3 :warning: |
| <!-- 20250729093812 --> [jakarta.mail-api](../content/jakarta/mail/jakarta.mail-api/README.md) | 2.1.3 :warning: |
| <!-- 20250724131938 --> [jdplus-sdmx](../content/com/github/nbbrd/jdplus-sdmx/README.md) | 3.3.1 :warning: |
| <!-- 20250723095941 --> [quarkus-project](../content/io/quarkus/README.md) | 3.25.0 :warning: |
| <!-- 20250722205732 --> [nifi](../content/org/apache/nifi/nifi/README.md) | 2.5.0 :warning: |
| <!-- 20250721190010 --> [opentelemetry-instrumentation-api](../content/io/opentelemetry/instrumentation/README.md) | 2.18.1 :warning: |
| <!-- 20250721114932 --> [yupiik-tools-maven-plugin-parent](../content/io/yupiik/maven/plugin/README.md) | 1.2.11 :warning: |
| <!-- 20250721081159 --> [jandex-parent](../content/io/smallrye/jandex/README.md) | 3.4.0 :warning: |
| <!-- 20250719013935 --> [jackson-datatype-joda](../content/tools/jackson/datatype/jackson-datatype-joda/README.md) | 3.0.0-rc6 :warning: |
| <!-- 20250719013530 --> [jackson-datatypes-misc-parent](../content/tools/jackson/datatype/jackson-datatypes-misc-parent/README.md) | 3.0.0-rc6 :warning: |
| <!-- 20250719013135 --> [jackson-datatypes-collections](../content/tools/jackson/datatype/jackson-datatypes-collections/README.md) | 3.0.0-rc6 :warning: |
| <!-- 20250719012735 --> [jackson-dataformat-xml](../content/tools/jackson/dataformat/jackson-dataformat-xml/README.md) | 3.0.0-rc6 :warning: |
| <!-- 20250719012336 --> [jackson-dataformats-text](../content/tools/jackson/dataformat/jackson-dataformats-text/README.md) | 3.0.0-rc6 :warning: |
| <!-- 20250719012336 --> [jackson-dataformats-binary](../content/tools/jackson/dataformat/jackson-dataformats-binary/README.md) | 3.0.0-rc6 :warning: |
| <!-- 20250719011135 --> [jackson-jr-parent](../content/tools/jackson/jr/README.md) | 3.0.0-rc6 :warning: |
| <!-- 20250719011135 --> [jackson-databind](../content/tools/jackson/core/jackson-databind/README.md) | 3.0.0-rc6 :warning: |
| <!-- 20250718201255 --> [jetty-project](../content/org/eclipse/jetty/jetty-project/README.md) | 12.1.0.beta2 :warning: |
| <!-- 20250718182930 --> [jackson-datatype-joda](../content/com/fasterxml/jackson/datatype/jackson-datatype-joda/README.md) | 2.19.2 :warning: |
| <!-- 20250718182340 --> [jackson-datatypes-misc-parent](../content/com/fasterxml/jackson/datatype/jackson-datatypes-misc-parent/README.md) | 2.19.2 :warning: |
| <!-- 20250718182334 --> [jackson-datatypes-collections](../content/com/fasterxml/jackson/datatype/jackson-datatypes-collections/README.md) | 2.19.2 :warning: |
| <!-- 20250718181535 --> [jackson-dataformat-xml](../content/com/fasterxml/jackson/dataformat/jackson-dataformat-xml/README.md) | 2.19.2 :warning: |
| <!-- 20250718180738 --> [jackson-dataformats-binary](../content/com/fasterxml/jackson/dataformat/jackson-dataformats-binary/README.md) | 2.19.2 :warning: |
| <!-- 20250718180532 --> [jackson-dataformats-text](../content/com/fasterxml/jackson/dataformat/jackson-dataformats-text/README.md) | 2.19.2 :warning: |
| <!-- 20250718175735 --> [jackson-jr-parent](../content/com/fasterxml/jackson/jr/README.md) | 2.19.2 :warning: |
| <!-- 20250718175536 --> [jackson-databind](../content/com/fasterxml/jackson/databind/README.md) | 2.19.2 :warning: |
| <!-- 20250718171323 --> [jena](../content/org/apache/jena/jena/README.md) | 5.5.0 :warning: |
| <!-- 20250717183535 --> [gwt-commons-validator](../content/de/knightsoft-net/gwt-commons-validator/README.md) | 1.10.0-0 :warning: |
| <!-- 20250715162154 --> [acs-aem-commons](../content/com/adobe/acs/aem-commons/README.md) | 6.14.0 :warning: |
| <!-- 20250715144131 --> [parent](../content/org/phoebus/README.md) | 5.0.2 :warning: |
| <!-- 20250713194124 --> [jpmml-transpiler](../content/org/jpmml/jpmml-transpiler/README.md) | 1.4.3 :warning: |
| <!-- 20250713182451 --> [jpmml-converter](../content/org/jpmml/jpmml-converter/README.md) | 1.6.3 :warning: |
| <!-- 20250713090734 --> [jpmml-evaluator](../content/org/jpmml/jpmml-evaluator/README.md) | 1.7.4 :warning: |
| <!-- 20250711185310 --> [mybatis-spring-boot](../content/org/mybatis/spring/boot/mybatis-spring-boot/README.md) | 3.0.5 :warning: |
| <!-- 20250711185310 --> [mybatis-spring-boot](../content/org/mybatis/spring/boot/README.md) | 3.0.5 :warning: |
| <!-- 20250709204236 --> [tika](../content/org/apache/tika/README.md) | 3.2.1 :warning: |
| <!-- 20250709095534 --> [flink-kubernetes-operator-parent](../content/org/apache/flink/flink-kubernetes-operator/README.md) | 1.12.1 :warning: |
| <!-- 20250707172817 --> [shiro-root](../content/org/apache/shiro/README.md) | 2.0.5 :warning: |
| <!-- 20250707085541 --> [java-sql-parent](../content/com/github/nbbrd/java-sql-util/README.md) | 1.0.7 :warning: |
| <!-- 20250704040735 --> [jpmml-model](../content/org/jpmml/jpmml-model/README.md) | 1.7.4 :warning: [:memo:](https://github.com/jpmml/jpmml-model/issues/42) |
| <!-- 20250702142639 --> [rainbowgum-maven-parent](../content/io/jstach/rainbowgum/README.md) | 0.8.2 :warning: |
| <!-- 20250702080353 --> [jackrabbit-oak](../content/org/apache/jackrabbit/oak/README.md) | 1.82.0 :warning: [:memo:](https://issues.apache.org/jira/browse/OAK-10662) |
| <!-- 20250630063427 --> [jpmml-sklearn](../content/org/jpmml/jpmml-sklearn/README.md) | 1.9.13 :warning: |
| <!-- 20250628075449 --> [drill-root](../content/org/apache/drill/README.md) | 1.22.0 :warning: |
| <!-- 20250622062141 --> [activemq-parent](../content/org/apache/activemq/README.md) | 6.1.7 :warning: |
| <!-- 20250621194142 --> [jpmml-statsmodels](../content/org/jpmml/jpmml-statsmodels/README.md) | 1.3.2 :warning: |
| <!-- 20250621182201 --> [jpmml-python](../content/org/jpmml/jpmml-python/README.md) | 1.3.5 :warning: |
| <!-- 20250619093642 --> [org.apache.sling.feature.launcher](../content/org/apache/sling/org.apache.sling.feature.launcher/README.md) | 1.3.4 :warning: |
| <!-- 20250616112425 --> [commons-fileupload2](../content/org/apache/commons/commons-fileupload2/README.md) | 2.0.0-M4 :warning: |
| <!-- 20250612131605 --> [jdplus-main](../content/eu/europa/ec/joinup/sat/jdplus-main/README.md) | 3.5.1 :warning: |
| <!-- 20250610114945 --> [kubernetes-client-project](../content/io/fabric8/kubernetes-client/README.md) | 7.3.1 :warning: |
| <!-- 20250606044217 --> [trino-root](../content/io/trino/README.md) | 476 :warning: |
| <!-- 20250603145335 --> [io.takari.incrementalbuild](../content/io/takari/incrementalbuild/README.md) | 1.0.4 :warning: |
| <!-- 20250528173039 --> [syncope](../content/org/apache/syncope/README.md) | 4.0.0 :warning: |
| <!-- 20250522194000 --> [com.io7m.gtyrell](../content/com/io7m/gtyrell/README.md) | 4.0.1 :warning: |
| <!-- 20250520192141 --> [mockito-core](../content/org/mockito/mockito-core/README.md) | 5.18.0 :warning: [:memo:](https://github.com/mockito/mockito/issues/3563) |
| <!-- 20250519085748 --> [org.apache.sling.feature.cpconverter](../content/org/apache/sling/org.apache.sling.feature.cpconverter/README.md) | 1.3.10 :warning: |
| <!-- 20250519063835 --> [org.apache.sling.distribution.core](../content/org/apache/sling/org.apache.sling.distribution.core/README.md) | 0.7.4 :warning: |
| <!-- 20250512091503 --> [jdplus-benchmarking](../content/eu/europa/ec/joinup/sat/jdplus-benchmarking/README.md) | 2.0.1 :warning: |
| <!-- 20250509151950 --> [com.io7m.quarrel](../content/com/io7m/quarrel/README.md) | 1.8.0 :warning: |
| <!-- 20250509125658 --> [org.apache.sling.commons.log](../content/org/apache/sling/org.apache.sling.commons.log/README.md) | 6.0.0 :warning: |
| <!-- 20250508083646 --> [org.apache.sling.scripting.sightly.testing](../content/org/apache/sling/org.apache.sling.scripting.sightly.testing/README.md) | 1.0.40-1.4.0 :warning: |
| <!-- 20250507175507 --> [com.io7m.mime2045](../content/com/io7m/mime2045/README.md) | 1.2.0 :warning: |
| <!-- 20250506120219 --> [com.io7m.seltzer](../content/com/io7m/seltzer/README.md) | 1.2.0 :warning: |
| <!-- 20250504172405 --> [com.io7m.jbssio](../content/com/io7m/jbssio/README.md) | 3.0.0 :warning: |
| <!-- 20250503162925 --> [com.io7m.trasco](../content/com/io7m/trasco/README.md) | 3.1.1 :warning: |
| <!-- 20250502051147 --> [ratis-thirdparty](../content/org/apache/ratis/ratis-thirdparty/README.md) | 1.0.9 :warning: |
| <!-- 20250430084041 --> [com.io7m.certusine](../content/com/io7m/certusine/README.md) | 3.2.0 :warning: |
| <!-- 20250429144840 --> [jpmml-r](../content/org/jpmml/jpmml-r/README.md) | 1.7.2 :warning: |
| <!-- 20250429063039 --> [jansi](../content/org/fusesource/jansi/jansi/README.md) | 2.4.2 :warning: [:memo:](https://github.com/fusesource/jansi/pull/303) |
| <!-- 20250428131544 --> [commons-configuration2](../content/org/apache/commons/configuration2/README.md) | 2.12.0 :warning: |
| <!-- 20250427011857 --> [klass](../content/cool/klass/README.md) | 0.5.0 :warning: [:memo:](https://github.com/liftwizard/klass/issues/425) |
| <!-- 20250423191555 --> [bitcoin-commons](../content/net/osslabz/bitcoin-commons/README.md) | 0.3.0 :warning: |
| <!-- 20250423122320 --> [turnstile-siteverify-client](../content/net/osslabz/turnstile-siteverify-client/README.md) | 0.4.0 :warning: |
| <!-- 20250422082642 --> [crypto-commons](../content/net/osslabz/crypto-commons/README.md) | 0.6.4 :warning: [:memo:](https://github.com/osslabz/crypto-commons/pull/54) |
| <!-- 20250419204402 --> [htmlcompressor](../content/com/github/hazendaz/htmlcompressor/README.md) | 1.11.0 :warning: |
| <!-- 20250419183023 --> [ServerLib](../content/dev/notmyfault/serverlib/ServerLib/README.md) | 2.3.7 :x: |
| <!-- 20250418115815 --> [systemds](../content/org/apache/systemds/README.md) | 3.3.0 :warning: [:memo:](https://github.com/apache/systemds/pull/2257) |
| <!-- 20250416123530 --> [commons-jexl3](../content/org/apache/commons/commons-jexl3/README.md) | 3.5.0 :warning: |
| <!-- 20250412064600 --> [jpmml-lightgbm](../content/org/jpmml/jpmml-lightgbm/README.md) | 1.6.1 :warning: |
| <!-- 20250411062112 --> [jpmml-h2o](../content/org/jpmml/jpmml-h2o/README.md) | 1.3.1 :warning: |
| <!-- 20250410085949 --> [fediz](../content/org/apache/cxf/fediz/README.md) | 1.7.1 :warning: |
| <!-- 20250410055157 --> [jpmml-xgboost](../content/org/jpmml/jpmml-xgboost/README.md) | 1.9.1 :warning: |
| <!-- 20250409102346 --> [jdplus-incubator](../content/eu/europa/ec/joinup/sat/jdplus-incubator/README.md) | 2.3.0 :warning: |
| <!-- 20250403121924 --> [winrm-java](../content/org/metricshub/winrm-java/README.md) | 1.1.02 :warning: |
| <!-- 20250329100934 --> [com.io7m.looseleaf](../content/com/io7m/looseleaf/README.md) | 3.0.0 :warning: [:memo:](https://github.com/mojohaus/buildnumber-maven-plugin/issues/229) |
| <!-- 20250325094930 --> [camel-k-runtime-project](../content/org/apache/camel/camel-k-runtime/README.md) | 3.15.3 :warning: |
| <!-- 20250323131510 --> [packager-maven-plugin](../content/org/jpmml/packager-maven-plugin/README.md) | 1.1.0 :warning: |
| <!-- 20250314101946 --> [dbus-java-parent](../content/com/github/hypfvieh/dbus-java/README.md) | 5.1.1 :warning: [:memo:](https://github.com/hypfvieh/dbus-java/pull/279) |
| <!-- 20250311162322 --> [arthas-all](../content/com/taobao/arthas/README.md) | 4.0.5 :warning: [:memo:](https://github.com/alibaba/arthas/pull/3001) |
| <!-- 20250310171441 --> [axis2](../content/org/apache/axis2/README.md) | 2.0.0 :warning: [:memo:](https://github.com/apache/axis-axis2-java-core/pull/879) |
| <!-- 20250303160124 --> [eforms-sdk-analyzer](../content/eu/europa/ted/eforms/eforms-sdk-analyzer/README.md) | 1.13.1 :warning: |
| <!-- 20250226101218 --> [baremaps](../content/org/apache/baremaps/README.md) | 0.8.2 :warning: [:memo:](https://github.com/apache/incubator-baremaps/pull/951) |
| <!-- 20250225165035 --> [slf4j-parent](../content/org/slf4j/README.md) | 2.1.0-alpha1 :warning: |
| <!-- 20250224140054 --> [sdmx-dl-parent](../content/com/github/nbbrd/sdmx-dl/README.md) | 3.0.0-beta.14 :warning: |
| <!-- 20250224085936 --> [sshd](../content/org/apache/sshd/README.md) | 2.15.0 :warning: [:memo:](https://github.com/apache/mina-sshd/pull/695) |
| <!-- 20250218094231 --> [wayang](../content/org/apache/wayang/README.md) | 1.0.0 :warning: [:memo:](https://github.com/apache/incubator-wayang/pull/503) |
| <!-- 20250217124403 --> [winrm](../content/org/sentrysoftware/winrm/README.md) | 1.1.01 :warning: |
| <!-- 20250214204823 --> [jpmml-sparkml](../content/org/jpmml/jpmml-sparkml/README.md) | 3.1.0 :warning: |
| <!-- 20250214132638 --> [commons-vfs2](../content/org/apache/commons/commons-vfs2/README.md) | 2.10.0 :warning: |
| <!-- 20250213085016 --> [apache-ignite](../content/org/apache/ignite/README.md) | 2.17.0 :warning: |
| <!-- 20250205091217 --> [maven-resolver-ant-tasks](../content/org/apache/maven/resolver/maven-resolver-ant-tasks/README.md) | 1.5.2 :warning: |
| <!-- 20250203233329 --> [axiom](../content/org/apache/ws/commons/axiom/README.md) | 2.0.0 :warning: |
| <!-- 20250202185956 --> [jpmml-codemodel](../content/org/jpmml/jpmml-codemodel/README.md) | 1.2.0 :warning: |
| <!-- 20250201215052 --> [ftpserver-parent](../content/org/apache/mina/ftpserver/README.md) | 1.2.1 :warning: |
| <!-- 20250126122810 --> [org.apache.sling.xss](../content/org/apache/sling/org.apache.sling.xss/README.md) | 2.4.6 :warning: |
| <!-- 20250124102848 --> [karaf](../content/org/apache/karaf/karaf/README.md) | 4.4.7 :warning: [:memo:](https://issues.apache.org/jira/browse/KARAF-7797) |
| <!-- 20250117094427 --> [org.apache.sling.starter](../content/org/apache/sling/org.apache.sling.starter/README.md) | 13 :warning: |
| <!-- 20250114121312 --> [commons-daemon](../content/org/apache/commons/commons-daemon/README.md) | 1.4.1 :warning: |
| <!-- 20250103195806 --> [ldapchai](../content/com/github/ldapchai/README.md) | 0.8.7 :warning: |
| <!-- 20241220140033 --> [org.apache.sling.models.impl](../content/org/apache/sling/org.apache.sling.models.impl/README.md) | 1.7.8 :warning: [:memo:](https://github.com/apache/sling-org-apache-sling-models-impl/pull/62) |
| <!-- 20241216105905 --> [org.apache.sling.commons.log.webconsole](../content/org/apache/sling/org.apache.sling.commons.log.webconsole/README.md) | 1.0.2 :warning: |
| <!-- 20241215214119 --> [plexus-utils](../content/org/codehaus/plexus/plexus-utils/README.md) | 4.0.2 :warning: |
| <!-- 20241215170740 --> [reload4j](../content/ch/qos/reload4j/README.md) | 1.2.26 :warning: |
| <!-- 20241207223709 --> [royale-typedefs-parent](../content/org/apache/royale/typedefs/README.md) | 0.9.12 :warning: |
| <!-- 20241207223516 --> [royale-framework-parent](../content/org/apache/royale/framework/README.md) | 0.9.12 :warning: |
| <!-- 20241207221427 --> [compiler](../content/org/apache/royale/compiler/README.md) | 0.9.12 :warning: |
| <!-- 20241207202534 --> [com.io7m.cardant](../content/com/io7m/cardant/README.md) | 1.0.0-beta0001 :warning: |
| <!-- 20241202181948 --> [commons-dbcp2](../content/org/apache/commons/commons-dbcp2/README.md) | 2.13.0 :warning: |
| <!-- 20241112125327 --> [coingecko-java](../content/net/osslabz/coingecko-java/README.md) | 1.2.0 :warning: |
| <!-- 20241112082354 --> [evm-abi-decoder](../content/net/osslabz/evm-abi-decode/README.md) | 0.1.0 :warning: |
| <!-- 20241106160454 --> [tomcat-authnz-spnego-ad](../content/net/sf/michael-o/tomcat/tomcat-authnz-spnego-ad/README.md) | 4.2.4 :warning: [:memo:](https://github.com/michael-o/tomcatspnegoad/issues/32) |
| <!-- 20241105103840 --> [atom-jaxb-parent](../content/fr/vidal/oss/README.md) | 2.0.0 :x: |
| <!-- 20241024173436 --> [parent](../content/org/apache/zookeeper/README.md) | 3.9.3 :warning: |
| <!-- 20241018172054 --> [org.apache.sling.commons.metrics](../content/org/apache/sling/org.apache.sling.commons.metrics/README.md) | 1.2.14 :warning: |
| <!-- 20240930082825 --> [io.wcm.caconfig.editor.root](../content/io/wcm/io.wcm.caconfig/README.md) | 1.16.6 :warning: |
| <!-- 20240916091231 --> [io.wcm.wcm.ui.clientlibs](../content/io/wcm/io.wcm.wcm/ui/clientlibs/README.md) | 1.4.0 :warning: |
| <!-- 20240817210045 --> [mybatis-2-spring](../content/org/mybatis/mybatis-2-spring/README.md) | 1.2.1 :warning: |
| <!-- 20240814231054 --> [commons-cli](../content/org/apache/commons/commons-cli/README.md) | 1.9.0 :warning: |
| <!-- 20240812093803 --> [commons-numbers-parent](../content/org/apache/commons/numbers/README.md) | 1.2 :warning: |
| <!-- 20240723191850 --> [bcel](../content/org/apache/commons/bcel/README.md) | 6.10.0 :warning: |
| <!-- 20240715085906 --> [commons-rng-parent](../content/org/apache/commons/rng/README.md) | 1.6 :warning: |
| <!-- 20240708084644 --> [io.wcm.wcm.commons](../content/io/wcm/io.wcm.wcm/commons/README.md) | 1.11.0 :warning: |
| <!-- 20240704232838 --> [hk2-parent](../content/org/glassfish/hk2/README.md) | 4.0.0-M3 :warning: [:memo:](https://github.com/eclipse-ee4j/glassfish-hk2/pull/1071) |
| <!-- 20240627192818 --> [commons-email2-parent](../content/org/apache/commons/email2/README.md) | 2.0.0-M1 :warning: |
| <!-- 20240609233725 --> [javacan](../content/tel/schich/javacan/README.md) | 3.4.0 :x: |
| <!-- 20240603092651 --> [commons-jcs3](../content/org/apache/commons/commons-jcs3/README.md) | 3.2.1 :warning: [:memo:](https://github.com/apache/commons-jcs/commit/61661616d8cb586bc41c0bea5cd3a206ba0ec94d) |
| <!-- 20240524153720 --> [com.io7m.sunburst](../content/com/io7m/sunburst/README.md) | 0.0.7 :warning: |
| <!-- 20240522202533 --> [com.io7m.idstore](../content/com/io7m/idstore/README.md) | 2.0.1 :warning: |
| <!-- 20240510194112 --> [com.io7m.cedarbridge](../content/com/io7m/cedarbridge/README.md) | 2.0.0 :warning: [:memo:](https://github.com/io7m-com/cedarbridge/issues/62) |
| <!-- 20240510171359 --> [com.io7m.jsx](../content/com/io7m/jsx/README.md) | 4.0.0 :warning: |
| <!-- 20240509124549 --> [paimon-shade](../content/org/apache/paimon/shade/README.md) | 0.8.0 :warning: [:memo:](https://github.com/apache/incubator-paimon-shade/pull/18) |
| <!-- 20240506065040 --> [batchee](../content/org/apache/batchee/README.md) | 2.0.0 :warning: |
| <!-- 20240503123932 --> [org.apache.sling.rewriter](../content/org/apache/sling/org.apache.sling.rewriter/README.md) | 1.4.4 :warning: [:memo:](https://github.com/apache/sling-org-apache-sling-rewriter/pull/14) |
| <!-- 20240501164724 --> [turbine-webapp-6.0](../content/org/apache/turbine/turbine-webapp-6.0/README.md) | 3.0.0 :warning: |
| <!-- 20240420172655 --> [unexepack](../content/io/github/albertus82/unexepack/README.md) | 0.3.1 :warning: |
| <!-- 20240414093609 --> [maven-scm](../content/org/apache/maven/scm/README.md) | 2.1.0 :warning: |
| <!-- 20240312215350 --> [cdevents-sdk-java](../content/dev/cdevents/cdevents-sdk-java/README.md) | 0.3.1 :x: |
| <!-- 20240229131606 --> [angus-activation-project](../content/org/eclipse/angus/activation/README.md) | 2.0.2 :warning: |
| <!-- 20240219171831 --> [plc4x-parent](../content/org/apache/plc4x/plc4x/README.md) | 0.12.0 :x: |
| <!-- 20240126192007 --> [io.wcm.handler.richtext](../content/io/wcm/io.wcm.handler/richtext/README.md) | 2.0.0 :warning: |
| <!-- 20240122143033 --> [org.apache.sling.feature.extension.unpack](../content/org/apache/sling/org.apache.sling.feature.extension.unpack/README.md) | 0.4.0 :warning: |
| <!-- 20240118001405 --> [scimple](../content/org/apache/directory/scimple/README.md) | 1.0.0-M1 :warning: |
| <!-- 20231109041226 --> [org.apache.sling.cms](../content/org/apache/sling/org.apache.sling.cms/README.md) | 1.1.8 :warning: |
| <!-- 20230818102937 --> [microservice-security-autoconfiguration](../content/io/dwpbank/movewp3/microservice-security-autoconfiguration/README.md) | 3.0.2 :warning: [:memo:](https://github.com/movewp3/microservice-security-autoconfiguration/pull/19) |
| <!-- 20230721020416 --> [auto-record](../content/pl/com/labaj/auto-record/README.md) | 2.1.0 :x: |
| <!-- 20230713001648 --> [org.apache.sling.scripting.groovy](../content/org/apache/sling/org.apache.sling.scripting.groovy/README.md) | 1.3.0 :warning: |
| <!-- 20230620223800 --> [xml-maven-plugin](../content/org/codehaus/mojo/xml-maven-plugin/README.md) | 1.1.0 :warning: |
| <!-- 20230510171047 --> [Apache-Synapse](../content/org/apache/synapse/README.md) | 3.0.2 :warning: [:memo:](https://issues.apache.org/jira/browse/SYNAPSE-1128) |
| <!-- 20230305132220 --> [jarviz-core](../content/org/kordamp/jarviz/README.md) | 0.3.0 :warning: |
| <!-- 20230219230122 --> [mybatis-generator](../content/org/mybatis/generator/README.md) | 1.4.2 :warning: |
| <!-- 20230215195813 --> [com.io7m.chione](../content/com/io7m/chione/README.md) | 0.0.2 :warning: |
| <!-- 20230213091325 --> [org.apache.sling.jcr.contentloader](../content/org/apache/sling/org.apache.sling.jcr.contentloader/README.md) | 2.6.0 :warning: [:memo:](https://github.com/apache/sling-org-apache-sling-jcr-contentloader/pull/21) |
| <!-- 20230204020210 --> [xmlchai](../content/org/jrivard/xmlchai/README.md) | 0.1.3 :warning: |
| <!-- 20221209232334 --> [watset](../content/org/nlpub/watset/README.md) | 2.8.2 :warning: |
| <!-- 20221123032956 --> [org.apache.sling.hc.support](../content/org/apache/sling/org.apache.sling.hc.support/README.md) | 1.0.10 :warning: |
| <!-- 20221107220203 --> [quick-perf-live](../content/org/quickperf/quick-perf-live/README.md) | 0.12 :warning: |
| <!-- 20221021224206 --> [quick-sql-test-data](../content/org/quickperf/quick-sql-test-data/README.md) | 0.1 :warning: |
| <!-- 20220916141422 --> [gemLibPki](../content/de/gematik/pki/gemlibpki-old/README.md) | 0.9.3 :warning: |
| <!-- 20220821195753 --> [org.apache.sling.pipes](../content/org/apache/sling/org.apache.sling.pipes/README.md) | 4.5.0 :warning: [:memo:](https://github.com/apache/sling-org-apache-sling-pipes/pull/20) |
| <!-- 20220525193321 --> [jdo](../content/org/apache/jdo/README.md) | 3.2.1 :warning: [:memo:](https://github.com/apache/db-jdo/pull/49) |
| <!-- 20220420183148 --> [logback-parent-db](../content/ch/qos/logback/db/README.md) | 1.2.11.1 :warning: [:memo:](https://github.com/qos-ch/logback-db/pull/2) |
| <!-- 20220314110853 --> [org.apache.sling.launchpad.testing](../content/org/apache/sling/org.apache.sling.launchpad.testing/README.md) | 12 :warning: |
| <!-- 20220303223913 --> [apache-any23](../content/org/apache/any23/README.md) | 2.7 :warning: [:memo:](https://github.com/apache/any23/pull/270) |
| <!-- 20220228062841 --> [isis-parent](../content/org/apache/isis/README.md) | 2.0.0-M7 :warning: |
| <!-- 20211221090833 --> [scriptingbundle-maven-plugin](../content/org/apache/sling/scriptingbundle-maven-plugin/README.md) | 0.5.2 :warning: |
| <!-- 20211212220158 --> [org.apache.sling.commons.messaging.mail](../content/org/apache/sling/org.apache.sling.commons.messaging.mail/README.md) | 2.0.0 :warning: |
| <!-- 20211018122406 --> [org.apache.sling.commons.crypto](../content/org/apache/sling/org.apache.sling.commons.crypto/README.md) | 1.1.0 :warning: [:memo:](https://issues.apache.org/jira/browse/SLING-11907) |
| <!-- 20201226140242 --> [maven-artifact-transfer](../content/org/apache/maven/shared/maven-artifact-transfer/README.md) | 0.13.1 :warning: [:memo:](https://github.com/apache/maven-artifact-transfer/commit/c2106c0500cc7c70c27581f117bf86e6185073c6) |
| <!-- 20200511133844 --> [org.apache.sling.installer.factory.packages](../content/org/apache/sling/org.apache.sling.installer.factory.packages/README.md) | 1.0.4 :warning: |
<!-- END GENERATED NEWEST NOT REPRODUCIBLE -->
