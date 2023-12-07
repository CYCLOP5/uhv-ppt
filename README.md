

Current Chromium version: `116.0.5845.190`


```
repositories {
    maven {
        url = uri('https://mcef-download.cinemamod.com/repositories/releases')
    }
    // Optional for snapshot versions
    maven {
        url = uri('https://mcef-download.cinemamod.com/repositories/snapshots')
    }
}
```

After cloning this repo, you will need to clone the java-cef git submodule. There is a gradle task for this: `./gradlew cloneJcef`.

To run the Forge client: `./gradlew forgeClient`

In-game, there is a demo browser if you press F10 after you're loaded into a world (the demo browser only exists when you're running from a development environment).
