
Deployment steps :
	1. Backup the War on the weblogic. 
	2. Run the Rollout scripts.
	3. Change the configuration file for the DB connection in the commons JAR inside the WAR with the one on the old WAR.
	4. Deploy the WAR on the weblogic.