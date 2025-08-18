``` kotlin
val me = profile {
    name = "Erlanbek"
    expertise {
        mobile { android() + ios() }
        crossPlatform { flutter() + kmp() }
        backend { ktor() + springBoot() + vapor() }
        data { python() + sql() + jupyter() }
    }
    philosophy = "Clean code. Clean mind ✨"
}
```
