[![](https://jitpack.io/v/Phyrone/brigardier-kotlin.svg)](https://jitpack.io/#Phyrone/brigardier-kotlin) [![Build Status](https://travis-ci.com/Phyrone/brigardier-kotlin.svg?branch=master)](https://travis-ci.com/Phyrone/brigardier-kotlin)

# brigardier-kotlin
## This is a Wrapper for Mojangs Brigardier with Kotlin
Example with "String" as source
```kotlin
val dispatcher = CommandDispatcher<String>()
dispatcher.command("printString") {
   executes {
      println(this)
      return@executes 0
   }
}
```
