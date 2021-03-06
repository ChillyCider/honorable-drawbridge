# honorable-drawbridge

## How to use

Compilation can be done with Apache Maven:

```bash
mvn compile
```

Once it's compiled, you can run the compiled classes with Maven too:

```bash
mvn exec:exec
```

If you want to package the program into a self-contained JAR:

```bash
mvn package
```

(This will put a jar in the `target/` directory. Look
for `jar-with-dependencies` in the name)

## Helpful things for development

The ktlint linter is marked as a dependency in pom.xml. It can be run by
using this command:

```bash
mvn antrun:run@ktlint
```

There will be a lot of output. The good information starts with a line
that just has `ktlint:` by itself.

