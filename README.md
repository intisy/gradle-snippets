# Gradle Snippets

## Usage

```groovy
plugins {
    id "io.github.intisy.intisy/online-gradle" version "1.4.1"
}

online {
    presets = [
            "https://raw.githubusercontent.com/intisy/gradle-snippets/main/default.preset",
            "https://raw.githubusercontent.com/intisy/gradle-snippets/main/executable.preset",
            "https://raw.githubusercontent.com/intisy/gradle-snippets/main/publish.preset"
    ]
    urls = [
            "https://raw.githubusercontent.com/intisy/gradle-snippets/main/base.gradle",
            "https://raw.githubusercontent.com/intisy/gradle-snippets/main/createExeStandalone.gradle",
            "https://raw.githubusercontent.com/intisy/gradle-snippets/main/jar.gradle",
            "https://raw.githubusercontent.com/intisy/gradle-snippets/main/java.gradle:1.8",
            "https://raw.githubusercontent.com/intisy/gradle-snippets/main/java.gradle:11",
            "https://raw.githubusercontent.com/intisy/gradle-snippets/main/java.gradle:17",
            "https://raw.githubusercontent.com/intisy/gradle-snippets/main/java.gradle:21",
            "https://raw.githubusercontent.com/intisy/gradle-snippets/main/javadoc.gradle",
            "https://raw.githubusercontent.com/intisy/gradle-snippets/main/javafx.gradle",
            "https://raw.githubusercontent.com/intisy/gradle-snippets/main/launch4j.gradle",
            "https://raw.githubusercontent.com/intisy/gradle-snippets/main/properties.gradle",
            "https://raw.githubusercontent.com/intisy/gradle-snippets/main/publishing.gradle",
            "https://raw.githubusercontent.com/intisy/gradle-snippets/main/repositories.gradle",
            "https://raw.githubusercontent.com/intisy/gradle-snippets/main/shadowJar.gradle",
            "https://raw.githubusercontent.com/intisy/gradle-snippets/main/test.gradle",
            "https://raw.githubusercontent.com/intisy/gradle-snippets/main/wrapper.gradle"
    ]
}
```

## License

[![Apache License 2.0](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](LICENSE)
