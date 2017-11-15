JACOB (Java-COM bridge) is hosted on Sourceforge http://sourceforge.net/project/jacob-project

Information about what's new in this release can be found in docs/ReleaseNotes.html

Instructions on building this project can be found in docs/BuildingJacobFromSource.html
Detailed instructions on creating a build configuration file are in build.xml

Put the appropriate DLL for your platform into your runtime library path.
jacob for 32 bit windows is located in /x86.

There is no good usage guide at this time.


因为原有的Dll加载非常麻烦，参考Sqlite-jdbc的加载方式，把Dll加载方式进行优化，目前合成在Jar包中，不用担心Dll没有加载成功。
