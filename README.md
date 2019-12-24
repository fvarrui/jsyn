JSyn
====

**JSyn** is a modular audio synthesizer for Java by *Phil Burk*.

You can use JSyn to create unit generators, such as oscillators, filters, and envelopes. Units can be connected together and controlled in real-time from a Java program.

| Description                | Link                                                  |
| -------------------------- | ----------------------------------------------------- |
| Documentation              | http://www.softsynth.com/jsyn/                        |
| Pre-compiled JSyn JAR file | http://www.softsynth.com/jsyn/developers/download.php |
| Original JSyn source code  | https://github.com/philburk/jsyn                      |

## How to use the library

Add the following `repository` tag to your `pom.xml`:

```xml
<repository>
	<id>jsyn-repo</id>
	<url>https://github.com/fvarrui/jsyn/raw/master/repository</url>
</repository>
```

And the following `dependency`:

```xml
<dependency>
	<groupId>com.jsyn</groupId>
	<artifactId>JSyn</artifactId>
	<version>16.8.0</version>
</dependency>
```

## How to build and install the plugin

Execute next commands in BASH (GNU/Linux or macOS) or CMD (Windows):

1. Download source code and change to the project directory:

```bash
git clone https://github.com/fvarrui/jsyn.git
cd jsyn
```

2. Compile, package and install the plugin in your local repository and in the project's `repository` folder:

```bash
mvn install
```

## How to run built-in test app

Run next command:

```bash
java -jar target/JSyn-16.8.0.jar
```

---

JSyn - Copyright 1997-2014 Mobileer Inc