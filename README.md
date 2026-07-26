# qeen-maven

Public Maven repository for Qeen's Android SDK. **No credentials required.**

Add to your `settings.gradle.kts` and pull the SDK:

```kotlin
dependencyResolutionManagement {
    repositories {
        google()
        mavenCentral()
        maven { url = uri("https://raw.githubusercontent.com/fodoole/qeen-maven/main") }
    }
}
```

```kotlin
// app/build.gradle.kts
implementation("ai.qeen:qeensdk:0.1.0")
```

Your `host` and API key are shared privately by email — contact tech@qeen.ai.
