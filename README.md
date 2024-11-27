# Build Instructions

1. Build [DisplayShopsAPI](https://github.com/BalkerCraft/DisplayShopsAPI) first to maven local.
2. Compile versions 1.18.2, 1.20.4, 1.21.1, 1.21.3 using [BuildTools](https://www.spigotmc.org/wiki/buildtools/)  
  ➥ Make sure to enable adding to check "Generate Remapped Jars" in Options.
3. You can now build this plugin.

**[Wiki](https://github.com/XZot1K/DisplayShopsAPI/wiki) | [Commands](https://github.com/XZot1K/DisplayShopsAPI/wiki/commands) | [Permissions](https://github.com/XZot1K/DisplayShopsAPI/wiki/permissions)
| [How Does It Work?](https://github.com/XZot1K/DisplayShopsAPI/wiki/shop-guide) | [Developer API](https://github.com/XZot1K/DisplayShopsAPI/wiki/developer-api)
| [Java Docs](https://xzot1k.github.io/DisplayShopsAPI/) | [Usage statistics](https://bstats.org/plugin/bukkit/DisplayShops/23070)**

## v2.0+ code is under the "recode" branch while v1.7.x code (pre-2.0) is under the "master" branch

This is the core DisplayShops source code, which depends on the [DisplayShopsAPI](https://github.com/XZot1K/DisplayShopsAPI). Sicne the core depends on the API, the DisplayShopsAPI will need to be cloned, built, and installed to your local Maven respository. 

Alternatively, the Latest API found on GitHub can be swapped out in the POM files of the core using jitpack.

<img src="https://imgur.com/mkPfGtg.png" width="150px" height="150px">

# DisplayShops

Create immersive simplistic shops with animations, efficient transaction handling, and much more!
***

** NOTE: all major MC jar version releases will need to be built using BuildTools for the individual per-version modules up until 1.20.4 (you can remove or disable them, but code will need adjustments) 

** NOTE: Plugin is compatible from version 1.8 to 1.21.1

* To build DisplayShops core, clone the repository and open the project in Intellij IDE.
* Ensure the DisplayShopsAPI is installed and linked to the core as a seperate module.
* Run the "Build Jar" run configuration at the top-right of the IDE near the run/debug buttons. 
* If successful, the JAR will be located in the "target" folder under the "Core" module folder found in the project directory.
* 
