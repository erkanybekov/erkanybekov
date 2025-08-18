``` kotlin
val me = profile {
    name = "Erlanbek"

    val expertise = setOf(
    "Mobile Development" to listOf("Android", "iOS"),
    "Cross-Platform" to listOf("Flutter", "KMP"), 
    "Backend" to listOf("Ktor", "Spring Boot", "Vapor"),
    "Data Science" to listOf("Python", "SQL", "Jupyter")
    )

    philosophy = "Clean code. Clean mind ✨"
}
```
