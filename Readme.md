This provides experimental language support for the PS2 Emotion Engine.
It's basically the MIPS code slimmed down with some of the EE specific instructions added.

To use, clone this repo into the Processors directory of the ghidra distribution.
You will need to rename the root directory to PS2EE from the default of ghidra-ps2ee.

To compile the java, open the directory as a project in IntelliJ Idea. From the build
menu, choose build artifacts and build the 'lib' artifact. This will cause a
ps2ee.jar to be created in the lib directory.


