This is a web based REPL for [dyna3](https://github.com/argolab/dyna3).
This interfaces with the dyna3 implementation through use of the [dyna.WebDemoMain](https://github.com/argolab/dyna3/blob/master/src/java/dyna/WebDemoMain.java) class.
To compile the dyna3 runtime for use with the web app, run the `make` command from the dyna3 project.  Then copy the file `target/dyna-0.1.0-SNAPSHOT-standalone.jar` to `dyna-standalone.jar`.

This is using [Cheerpj](https://cheerpj.com/) to create a Java Virtual Machine that is used to run the Dyna3 implementation.

The UI (HTML and CSS) were written by the claude LLM using the [cline](https://github.com/cline/cline) plugin for VSCode.  