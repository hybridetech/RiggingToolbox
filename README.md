RiggingToolbox
==============
The Rigging Toolbox provides a collection of production relevant tools that can be used directly, or as references when building character pipelines using Fabric Engine.

Currently the Rigging Toolbox provides a small collection of Math and Kinematics helpers, but this list will be expanded over the coming months. 

We will provide new math types, kinematics and deformers based on production uses cases given to us by our user base. 

Interfaces
--------------
One of the goals of the rigging toolbox is to define clear interfaces that solvers and deformers can support, enabling custom tools to be integrated into a common framework. 

Performance
-----------------
Another primary goal of the Rigging Toolbox is to provide examples that effectively leverage the KL language. The Deformers will provide good examples of how GPU compute can be used on production problems to improve character rig performance.


Usage
=====

Simply clone or fork the Rigging Toolbox repo and add the path to the RiggingToolbox/Exts folder to your FABRIC_EXTS_PATH environment variable. 

Pushing Changes
------------------------

there will always be a branch on the Rigging Toolbox correlating with a version of Fabric Engine. These branches are integration branches and should not be modified directly. 

If you would like to contribute a new feature to the rigging toolbox, create a new branch where you can make your changes. When you are finished with your changes, set up a pull request on GitHub, and give the github name of a reviewer to review your changes. 

If possible, provide a simple kl unit test, and sample scene that can be used to validate your new feature. 

For private work that you do not wish to share with the community, please setup a fork of the repository and keep your changes there. 

Send questions regarding the rigging toolbox to the Fabric Engine discussion list. 

Phil