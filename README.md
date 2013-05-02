flexmojos-test
==============

Simple project using Flexmojos

Setup
-----
1. Currently requires private repo containing Apache Flex Development Kit 4.9.1 (published under Adobe groupId), and some hacked
Flex Development Kit 4.6 items (some 4.9.1 items republished as 4.6.0 items).
2. To build the project in IDEA, you must either define the M2_HOME environment variable, or open the project and override
the default location of maven home via File -> Settings -> Project Settings -> Maven ->  Maven home directory.
3. If you don't have a directory containing flashplayerdebugger on your path, you need to edit the pom.xml property:
*flex.flashPlayer.command* so it points to your flashplayerdebugger file.