karel-the-robot-learns-java
===========================

Karel the Robot resources and exercises (in Java)

This repository contains an Eclipse project for running Karel-the-Robot in Java. Karel is an educational programming language, targeting beginners and fun for everyone. The code comes from the Stanford [CS106A Programming Methodology][stanford-cs106a] course with an unknown license (I clearly do not claim any credit). Nowadays a GitHub repository is more convenient to share such resources, that's why I have created this project.

## Quick start

First of all, the karel ``.jar`` included is only compatible with Java 1.6, meaning JRE 1.6 should be installed on your computer.

> Note: Eclipse requires Java also, and the JRE used for Eclipse can be different from the JRE used for Karel. You will probably prefer to run Eclipse on the latest Java version. That may be confusing for beginners.

Java 1.6 is no longer officially supported. It has to be downloaded from the [Java archive page][java-archive]. Run the installer and add it to the Eclipse available JRE. Detailed installation instructions are available on my blog post about [Karel the Robot and Java][ab.io-karel-learns-java]. Note that you can also install ``openjdk-6-jre`` on Linux.

You can then clone this repository (or fork it) and import the project into Eclipse. Run configurations are available for each world from the Stanford assignments. There is also an empty ``test`` project that can be used as a template.

![Karel the robot stone mason assignment](https://raw.githubusercontent.com/Arn-O/karel-the-robot-learns-java/master/assets/img/karel-stone-mason.png "Karel the robot stone mason assignment")

You are now ready to play with Karel the robot!

## Contributing

Contributions are welcome. You can for example share new worlds or new exercises. Just fork this repository and push a merge request.

> Note: please do not push the solutions of the Stanford assignments!

## Bugs and feature requests

Any installation issues can be posted in the comments of my blog. Any bugs with the content of this project can be posted in the bug tracker. In case of doubt, use the bug tracker.

## Copyright and license

The main code comes from the Stanford CS106A Programming Methodology course without license of any kind. All credit goes to Stanford and probably to Eric Roberts.

Font credit to [Yuji Oshimoto][04] for exercise KarelFontArt.

[stanford-cs106a]: https://see.stanford.edu/Course/CS106A
[java-archive]: http://www.oracle.com/technetwork/java/javase/downloads/java-archive-downloads-javase6-419409.html
[ab.io-karel-learns-java]: http://arnaudbertrand.io/blog/2014/12/29/karel-the-robot-learns-java-and-git/
[04]:  http://www.04.jp.org/
