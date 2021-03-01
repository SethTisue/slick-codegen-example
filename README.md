This code example shows how to setup sbt to use Slick's preconfigued code-generator
for working with an existing database schema.
`build.sbt` enables automatically as well as manually triggered (with `sbt slick`) code-generation.

`src/main/scala/Example.scala` uses the generated code.

The code is generated into file `target/scala-2.11/src_managed/slick/demo/Tables.scala`,
which can be changed in the sbt script.
It is usally wise to keep the generated Slick code under version control.

Use `sbt run` to run the demo.
