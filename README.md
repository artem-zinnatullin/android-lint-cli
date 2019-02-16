# Android Lint CLI

`-cli` releases of Android Lint tool in form of executable jar that can be run with `java -jar lint-cli.jar …`.

## Releases

Releases follow versioning of `com.android.tools.lint:lint:someversion` on `maven.google.com`.

Project is set up to deploy `lint-cli.jar` to [GitHub releases](https://github.com/artem-zinnatullin/android-lint-cli/releases), each release contains:

- `lint-cli.jar`: executable jar
- `lint-cli.jar.sha256`: sha256 of the jar
- `lint-cli.jar.sha512`: sha512 of the jar
- `dependencies.txt` dependencies used to build the jar
- `dependencies.txt.sha256`: sha256 of dependencies.txt
- `dependencies.txt.sha512`: sha512 of dependencies.txt

See also: [NOTICE](lint-cli/src/main/resources/META-INF/NOTICE).
