# Build.Gradle-Error-Resolve
Reolve the build.gradle all errors in Android studio , Either java or Kotli

```
pluginManagement {
    repositories {
        google {
            content {
                includeGroupByRegex("com\\.android.*")
                includeGroupByRegex("com\\.google.*")
                includeGroupByRegex("androidx.*")
            }
        }
        mavenCentral()
        gradlePluginPortal()
        jcenter()
        maven { url 'https://jitpack.io' }
        maven { url 'https://maven.fabric.io/public' }
        maven { url = "https://repo1.maven.org/maven2/" }
        maven { url "https://repo.spring.io/release" }
        maven { url "https://repository.jboss.org/maven2" }
        maven { url 'https://repo.jenkins-ci.org/public/' }
        maven { url 'https://maven.aliyun.com/repository/public' }
        maven { url 'https://maven.aliyun.com/repository/central' }
        maven { url 'https://maven.aliyun.com/repository/google' }
        maven { url 'https://maven.aliyun.com/repository/gradle-plugin' }
        maven { url 'https://maven.aliyun.com/repository/apache-snapshots' }
    }
}
dependencyResolutionManagement {
    repositoriesMode.set(RepositoriesMode.FAIL_ON_PROJECT_REPOS)
    repositories {
        google()
        mavenCentral()
        jcenter()
        maven { url 'https://jitpack.io' }
        maven { url 'https://maven.fabric.io/public' }
        maven { url = "https://repo1.maven.org/maven2/" }
        maven { url "https://repo.spring.io/release" }
        maven { url "https://repository.jboss.org/maven2" }
        maven { url 'https://repo.jenkins-ci.org/public/' }
        maven { url 'https://maven.aliyun.com/repository/public' }
        maven { url 'https://maven.aliyun.com/repository/central' }
        maven { url 'https://maven.aliyun.com/repository/google' }
        maven { url 'https://maven.aliyun.com/repository/gradle-plugin' }
        maven { url 'https://maven.aliyun.com/repository/apache-snapshots' }
    }
}

rootProject.name = "E Fitness App"
include ':app'

```
