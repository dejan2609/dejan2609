## 👨‍💻 About Me
> Hi there, I'm Dejan 👋    
> build/release and DevOps engineer: Java, Scala, Android (and more) 🔀 desktop, web and mobile apps

## 👥 Open Source Contributions:
### ![Gradle](https://img.shields.io/badge/Gradle-02303A.svg?style=for-the-badge&logo=Gradle&logoColor=white)![Apache Kafka](https://img.shields.io/badge/Apache%20Kafka-000?style=for-the-badge&logo=apachekafka)
<p>
  <a href="https://github.com/apache/kafka/commits?author=dejan2609"><img src="https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Fsearch%2Fcommits%3Fq%3Drepo%3Aapache%2Fkafka%2Bauthor%3Adejan2609&query=%24.total_count&label=My%20Apache%20Kafka%20commits&color=blue&style=for-the-badge" alt="My Apache Kafka commits" align="absmiddle"></a>
  <a href="https://github.com/apache/kafka/commits?author=dejan2609">https://github.com/apache/kafka/commits?author=dejan2609</a>
</p>

<p>
  <a href="https://github.com/apache/kafka/commits?author=dejan2609"><img src="https://img.shields.io/badge/My%20Apache%20Kafka%20commits-37-blue?style=for-the-badge" alt="My Apache Kafka commits" align="absmiddle"></a>
  <a href="https://github.com/apache/kafka/commits?author=dejan2609">https://github.com/apache/kafka/commits?author=dejan2609</a>
</p>

- 🎯 **highlights** (notable Kafka Gradle pull requests):
    - **[Expand gradle build: include Scala 2.13](https://github.com/apache/kafka/pull/5454)**
    - **[Remove redundant build code (unblock Gradle version upgrade from 6 to 7)](https://github.com/apache/kafka/pull/10466)**
    - **[Upgrade Gradle version from 6 to 7](https://github.com/apache/kafka/pull/10606)**
    - **[Upgrade Gradle version from 7 to 8](https://github.com/apache/kafka/pull/13205)**
    - **[Switch Gradle Shadow plugin](https://github.com/apache/kafka/pull/18018)**
    - **[Upgrade Gradle version from 8 to 9](https://github.com/apache/kafka/pull/19513)**
    - **[Support building with Java 25 (LTS release)](https://github.com/apache/kafka/pull/20561)**

### ![Maven](https://img.shields.io/badge/apachemaven-C71A36.svg?style=for-the-badge&logo=apachemaven&logoColor=white)![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
| project name            | commits and PR's                                                                                                         |
|:------------------------|:-------------------------------------------------------------------------------------------------------------------------|
| Apache Maven            | https://github.com/apache/maven/commits?author=dejan2609                                                                 |
| OWASP dependency-check  | **[Maven build: enforce explicit Java 6 compatibility](https://github.com/dependency-check/DependencyCheck/issues/638)** |
| Yahoo Fili              | https://github.com/yahoo/fili/commits?author=dejan2609                                                                   |
| Google Lib Phone Number | **["animal-sniffer-maven" plugin: version upgrade](https://github.com/google/libphonenumber/pull/2349)**                  |
| Picocli                 | **[Solve build issues for Maven users](https://github.com/remkop/picocli/pull/1292)**                                    |

## 🤝 Collaborations:
### Kafka-CheckStyle collaboration: adding Kafka into CheckStyle regression test suite
Note: this was a joint effort with [@romani](https://github.com/romani) and [@stoyanK7](https://github.com/stoyanK7) from [Checkstyle](https://github.com/checkstyle/checkstyle) team:
 - https://github.com/apache/kafka/pull/10967
 - https://github.com/checkstyle/checkstyle/issues/16003
 - https://github.com/checkstyle/checkstyle/pull/16395
 - https://github.com/checkstyle/checkstyle/pull/18263
 - https://github.com/apache/kafka/pull/20726
 - https://github.com/checkstyle/checkstyle/issues/18272
 - https://github.com/checkstyle/checkstyle/pull/18294

### Collaboration with SpotBugs and Apache Commons BCEL:
Kafka project Java 25 build was dependent on new SpotBugs version that was dependent on Apache Commons Byte Code Engineering Library (BCEL).  
My role: I created few tickets and testing PR's in order to enable Kafka's Java 25 build.
 - https://issues.apache.org/jira/browse/KAFKA-19664 Support building with Java 25 (LTS release)
 - https://issues.apache.org/jira/browse/BCEL-377 Fix testing on Java 24 and up _(initial title: Could you please release Java 25 compatible version ?)_
 - https://github.com/spotbugs/spotbugs/pull/3763 Apache bcel version 6.11.0 and Java 25 build
 - https://github.com/apache/kafka/pull/20561 Support building with Java 25 (LTS release)

## 🐛 Issue reporting: 🪲
![Gradle](https://img.shields.io/badge/Gradle-02303A.svg?style=for-the-badge&logo=Gradle&logoColor=white)![Apache Kafka](https://img.shields.io/badge/Apache%20Kafka-000?style=for-the-badge&logo=apachekafka)[![IntelliJ IDEA](https://img.shields.io/badge/IntelliJIDEA-000000.svg?logo=intellij-idea&logoColor=white)](#)[![GitLab CI](https://img.shields.io/badge/GitLab%20CI-FC6D26?logo=gitlab&logoColor=fff)](#)
- **Gradle**: **[Regression in Gradle 8.0.1 (corner case for Scala 2.13 build)](https://github.com/gradle/gradle/issues/23962)**
- **gradle-versions-plugin**:
  - **[Jacoco current version defaults to a Gradle built-in version](https://github.com/ben-manes/gradle-versions-plugin/issues/1028)**
  - **[Checking does jacoco version resolution works as expected with plugin version 0.57.0](https://github.com/ben-manes/gradle-versions-plugin/issues/1032)**
- **Apache Software Foundation**:
  - <details>
        <summary> 💡 <ins>Click here</ins> to expand (or collapse) the list of 40+ issues I created in the ASF JIRA:</summary>

    - **[BCEL-377    Fix testing on Java 24 and up](https://issues.apache.org/jira/browse/BCEL-377)** (with follow-up: **[SpotBugs release: Apache bcel version 6.11.0 and Java 25 build](https://github.com/spotbugs/spotbugs/pull/3763)**)
    - **[MNG-6282    Console output has no colors in shell (both Git Bash and Cygwin) [regression in Jansi 1.16 / Maven 3.5.1]](https://issues.apache.org/jira/browse/MNG-6282)**
    - **[KAFKA-21126 Version updates for build and project dependencies;`gradle-versions-plugin` reference has been moved to `settings.gradle`](https://issues.apache.org/jira/browse/KAFKA-21126)**
    - **[KAFKA-21086 Drop GrGit dependency usage (in favor of existing Eclipse JGit)](https://issues.apache.org/jira/browse/KAFKA-21086)**
    - **[KAFKA-21064 Apache RAT Gradle plugin version upgrade: 0.8.1 --> 0.11.0](https://issues.apache.org/jira/browse/KAFKA-21064)**
    - **[RAT-575 [Regression] Slower RAT task execution with recent versions (0.17 and 0.18)](https://issues.apache.org/jira/browse/RAT-575)**
    - **[RAT-576 Add overall statistics about scanned file types](https://issues.apache.org/jira/browse/RAT-576)**
    - **[KAFKA-20943 Update Develocity related Gradle plugin versions](https://issues.apache.org/jira/browse/KAFKA-20943)**
    - **[KAFKA-20882 Reduce build time: use lazy creation for Gradle tasks (i.e. use `tasks.register` instead of `task` or `tasks.create`)](https://issues.apache.org/jira/browse/KAFKA-20882)**
    - **[KAFKA-20851 Version updates for build dependencies](https://issues.apache.org/jira/browse/KAFKA-20851)**
    - **[KAFKA-20323 Refactor test method to enable Mockito version upgrade](https://issues.apache.org/jira/browse/KAFKA-20323)**
    - **[KAFKA-20103 Properties should be assigned using the 'propName = value' syntax](https://issues.apache.org/jira/browse/KAFKA-20103)**
    - **[KAFKA-20092 Dependencies version updates (for Gradle buildscript and project)](https://issues.apache.org/jira/browse/KAFKA-20092)**
    - **[KAFKA-20062 [Suggestion] provide compatible CheckStyle version for a different Java versions](https://issues.apache.org/jira/browse/KAFKA-20062)**
    - **[KAFKA-20061 slf4j-api version upgrade: 1 -->> 2](https://issues.apache.org/jira/browse/KAFKA-20061)**
    - **[KAFKA-19809 CheckStyle version upgrade: 10 -->> 12](https://issues.apache.org/jira/browse/KAFKA-19809)**
    - **[KAFKA-19792 Gradle build fails after Swagger patch version update](https://issues.apache.org/jira/browse/KAFKA-19792)**
    - **[KAFKA-19783 Custom Gradle tasks (`unitTest` and `integrationTest`) are not executing tests in Gradle 9](https://issues.apache.org/jira/browse/KAFKA-19783)**
    - **[KAFKA-19771 Update SpotBugs version and enable Spotbugs Gradle tasks on Java 25](https://issues.apache.org/jira/browse/KAFKA-19771)**
    - **[KAFKA-19769 [Java 25] few tests are failling (class: clients/org.apache.kafka.common.network.SslTransportLayerTest)](https://issues.apache.org/jira/browse/KAFKA-19769)**
    - **[KAFKA-19762 Turn on Gradle reproducible builds feature](https://issues.apache.org/jira/browse/KAFKA-19762)**
    - **[KAFKA-19761 Reorder Gradle tasks (in order to bump Shadow plugin version)](https://issues.apache.org/jira/browse/KAFKA-19761)**
    - **[KAFKA-19707	Develocity Gradle plugin version can't be upgraded (CI build fails with error: "build scan failed to be published")](https://issues.apache.org/jira/browse/KAFKA-19707)**
    - **[KAFKA-19664	Support building with Java 25 (LTS release)](https://issues.apache.org/jira/browse/KAFKA-19664)**
    - **[KAFKA-19654	[Gradle 8 --> 9 upgrade] GitHub Actions build issues: JUnit tests parsing fails (for a new/flaky steps)](https://issues.apache.org/jira/browse/KAFKA-19654)**
    - **[KAFKA-19636 Exclude some files (like .gitkeep) from Rat checks ?](https://issues.apache.org/jira/browse/KAFKA-19636)**
    - **[KAFKA-19591	Fix `gradlew` content: add missing parts (old Groovy template version is being referenced)](https://issues.apache.org/jira/browse/KAFKA-19591)**
    - **[KAFKA-19174	Gradle version upgrade 8 -->> 9](https://issues.apache.org/jira/browse/KAFKA-19174)**
    - **[KAFKA-18970	[kafka-clients] Gradle module metadata publication should be enabled](https://issues.apache.org/jira/browse/KAFKA-18970)**
    - **[KAFKA-18142 Switch Kafka's Gradle build shadow plugin to `com.gradleup.shadow` (and upgrade version)](https://issues.apache.org/jira/browse/KAFKA-18142)**
    - **[KAFKA-14749 Re-enable 'spotlessScalaCheck' task (in Jenkinsfile)](https://issues.apache.org/jira/browse/KAFKA-14749)**
    - **[KAFKA-14728	Remove 'spotlessScalaCheck' task (out of Jenkinsfile)](https://issues.apache.org/jira/browse/KAFKA-14728)**
    - **[KAFKA-14680 Gradle version upgrade 7 -->> 8](https://issues.apache.org/jira/browse/KAFKA-14680)**
    - **[KAFKA-12771	CheckStyle attempted upgrade (8.36.2 -->> 8.41.1) summons a pack of 'Indentation' errors](https://issues.apache.org/jira/browse/KAFKA-12771)**
    - **[KAFKA-12770	Gradle build: allow the CheckStyle version to be specified via parameter](https://issues.apache.org/jira/browse/KAFKA-12770)**
    - **[KAFKA-12764	Expand Gradle build for Scala 3.0 ?](https://issues.apache.org/jira/browse/KAFKA-12764)**
    - **[KAFKA-12744	Dependency upgrade: "argparse4j" 0.7.0 -->> 0.9.0](https://issues.apache.org/jira/browse/KAFKA-12744)**
    - **[KAFKA-12728	Version upgrades: gradle (6.8.3 -->> 7.0.1) and gradle shadow plugin (6.1.0 -->> 7.0.0)](https://issues.apache.org/jira/browse/KAFKA-12728)**
    - **[KAFKA-12293	Remove JCenter and Bintray repositories mentions out of Gradle build (sunset is announced for those repositories)](https://issues.apache.org/jira/browse/KAFKA-12293)**
    - **[INFRA-18752	Can't login to lists.apache.org using Google account (error: "Key missing or invalid ! null" is shown)](https://issues.apache.org/jira/browse/INFRA-18752)**
    - **[KAFKA-8466 	Remove 'jackson-module-scala' dependency (and replace it with some code)](https://issues.apache.org/jira/browse/KAFKA-8466)**
    - **[KAFKA-8009 	Uppgrade Jenkins job Gradle version from 4.10.2 to 5.x](https://issues.apache.org/jira/browse/KAFKA-8009)**
    - **[KAFKA-5708 	Update Jackson dependencies (from 2.8.5 to 2.9.x)](https://issues.apache.org/jira/browse/KAFKA-5708)**
  </details>
- **IntelliJ Idea**: https://youtrack.jetbrains.com/issues?q=by:%20dejan2609
- **GitLab** [(note: link requires Google login)](https://gitlab.com/dashboard/issues?sort=created_date&state=all&author_username=dejan2609)


## 🛠️ Tech Stack ⚒️
### 🔨 Build related tools
- Ant (+ Ivy), Maven, Gradle, SBT
- Jenkins, Bamboo, Github Actions
- SonarQube, Nexus, Artifactory

### 🔩 Containers, cloud, etc.
- Linux
- AWS
- Kubernetes

### I also created build pipelines for languages outside JVM universe:
- Python
- Ryby
- Go
- Node.JS/ React
- iPhone mobile apps
- SQL (via [Flyway](https://github.com/flyway/flyway))


