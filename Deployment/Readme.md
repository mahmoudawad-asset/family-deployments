
Depolyment Steps:
	1. in case the FamilyPlatformInterface:
		1. Change the configuration file on the commons JAR inside the WAR with the old one on the old deployement.
		2. Deploy the new WAR on weblogic.
	2. in case the engines :
		1. if there is a config folder on the deployment path contains the config files remove the below files from the jars if found :
			1. datasource.properties
			2. logback.xml
			3. application.properties
			4. c3p0.properties
		2. if there is no config folder and the files are inside the JARS replace it with the old ones.