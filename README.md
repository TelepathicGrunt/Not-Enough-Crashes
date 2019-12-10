# Not Enough Crashes
[![Discord](https://img.shields.io/discord/219787567262859264.svg)](https://discord.gg/CFaCu97)
[![CurseForge](http://cf.way2muchnoise.eu/not-enough-crashes.svg)](https://minecraft.curseforge.com/projects/not-enough-crashes)

Not Enough Crashes is a fork of TooManyCrashes, a port of VanillaFix's crash improvements to Fabric, for Minecraft 1.15+.
The original license is available at LICENSE_TMC. 

Features: 
- Special crash screen when game fails to start (not in dev).
- Deobfuscates stack trace (not in dev).
- Allows going back to the title screen after crashing in game (in dev too).
- Additional NBT information of entities and block entities in crash reports (in dev too).

The mod is useful in development environments too:

# Gradle Usage
```groovy
repositories {
    // [...]
    jcenter()
}
```

```groovy
dependencies {
    modRuntime "com.lettuce.fudge:notenoughcrashes:1.0.9+1.15"
}
```
