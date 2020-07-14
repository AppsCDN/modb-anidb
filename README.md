![Build](https://github.com/manami-project/modb-anidb/workflows/Build/badge.svg)
# modb-anidb
_modb_ stands for _**M**anami **O**ffline **D**ata**B**ase_. Repositories prefixed with this acronym are used to create the [manami-project/anime-offline-database](https://github.com/manami-project/anime-offline-database).

# What does this lib do?
This lib contains downloader and converter for downloading raw data from anidb.net and convert it to an `Anime` object.
Don't use this lib to crawl the website entirely. Instead check whether [manami-project/anime-offline-database](https://github.com/manami-project/anime-offline-database) already offers the data that you need.

# Usage
Add the repository and dependency to your build file
```kotlin
repositories {
    maven {
        url = uri("https://dl.bintray.com/manami-project/maven")
    }
}

dependencies {
    testImplementation("io.github.manamiproject:modb-anidb:$version")
}
```