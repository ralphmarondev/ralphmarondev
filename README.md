# Hi N***a 👋

```kotlin
class Person {
    val name = "Ralph Maron Eda"
    val role = "Kotlin Developer"
    val email = "edaralphmaron@gmail.com"
    
    fun greet() = "Hi there! 👋 I'm $name, a $role. Feel free to reach me at $email!"
    
    fun funFact() = "I write Kotlin like it’s my favorite language… because it is. 😎"
    
    fun motto() = "Keep code cute, simple, and full of personality!"
}

val me = Person()

println(me.greet())
println(me.funFact())
println(me.motto())
