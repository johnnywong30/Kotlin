# Kotlin
Learning Kotlin for Android work

## How to Compile
In terminal:
`$ kotlinc <file>.kt -include-runtime -d <file>.jar`

The `-include-runtime` makes the resulting .jar file self-contained and runnable by including the Kotlin runtime library in it.
The `-d` indicates what we want the output to be called.

## How to Run
`$ java -jar <file>.jar`
