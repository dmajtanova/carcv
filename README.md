==CarCV - Car recognizing and speed calculating platform
Copyright (C) 2012-2013, Ondrej Skopek
All rights reserved.

All licencing issues are addressed in file LICENCE.

Setup for eclipse project:

Old Setup for eclipse project:
1. Run: mvn versions:use-latest-releases
2. Run: mvn versions:update-child-modules
3. Run: mvn eclipse:eclipse
4. In eclipse, select: File > Import > Existing projects into workspace > path/to/carcv_gui > select project: carcv_gui
5. Enjoy!

To build, run: mvn package (optional: -DskipTests)
To clean, run: mvn clean