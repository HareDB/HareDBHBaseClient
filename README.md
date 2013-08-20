HareDBHBaseClient
=================
Most people are not familiar with command mode. However, there is only command mode in the world of Hadoop and HBase.
 
For the reason above, we are focusing on developing a set of tools, “HBase Client”, which can be used more easily and having a more friendly interface.

**After downloading the zip file, please unzip the file.
The file structure is as fellows.**

**lib directory:**
Here is the folder for all jars of Hadoop and HBase.
Hadoop is version 1.0.3 and HBase is version 0.94.0 .
Of course, you can switch it to different version by replacing the correct jars.

**udflib directory:**
Here is the folder for all jars of Pig UDH.
Pig is version 0.10.0.
You can put any UDH jar in this folder, then you can use it in pig panel.

**HareDB_HBaseClient_UI_1.3.0_SNAPSHOT.jar:**
This is the main program. It is an executable jar.
You can run a common "Java –jar HareDB_HBaseClient_UI-1.3.0-SNAPSHOT.jar" or just double click this jar.

**connection.xml:**
This is a file for storing the connection information of HBase.

**haredbClientUI.log:**
If system has any error, the exception message will be appended to this file.
If there is any thing goes wrong, please sent this file to us.

Currently, we are not full ready for gitHub
Please go to Sourceforge to download this tool.
https://sourceforge.net/projects/haredbhbaseclie/?source=directory

Thanks a lot.
