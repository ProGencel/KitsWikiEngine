[![](https://jitpack.io/v/ProGencel/KitswikiEngine.svg)](https://jitpack.io/#ProGencel/KitswikiEngine)

# Installation

This library is available on [JitPack](https://jitpack.io).

## 1. Add Repository

In your root `settings.gradle` file at the end of repositories:

```groovy
dependencyResolutionManagement {
		repositoriesMode.set(RepositoriesMode.FAIL_ON_PROJECT_REPOS)
		repositories {
			mavenCentral()
			maven { url 'https://jitpack.io' }
		}
	}
```

## 2. Add Dependency

```groovy
dependencies {
	        implementation 'com.github.ProGencel:KitswikiEngine:Tag'
	}
```
