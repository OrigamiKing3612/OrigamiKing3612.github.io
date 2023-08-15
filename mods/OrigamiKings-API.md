# Origamikings-API

This is an API mod that my mods use. This mod will not change gameplay. This mod will be embedded in most of my mods

## List of mods that use this API/Library Mod

- [OrigamiKings Enhancement Mod](https://modrinth.com/mod/origamikings-enhancement-mod)
- [OrigamiKings Robotics Armor Mod](https://modrinth.com/mod/origamikings-robotics-armor-mod)

## How to use this API/Library Mod

### Add this to your `gradle.properties`

The `version_id` is found on [Modrinth](https://modrinth.com/mod/origamikings-api/versions)

```gradle
origamikings_api=(version_id)
```

### Add this to your `build.gradle`

 ```gradle
 repositories {
    maven {
       name = "Modrinth"
       url = "https://api.modrinth.com/maven"
    }
}
dependencies {
    modImplementation "maven.modrinth:P3sjMa3U:${origamikings_api}"
}
 ```
