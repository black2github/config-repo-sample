# config-repo-sample
This is a Spring Cloud Config git repository sample.

application.properties --> this is common for all config clients reading this repository and shared between all client applications.<br/><br/> 
application-cluster1.properties --> common configuration data; specific for cluster1 profile<br/>
application-cluster2.properties --> common configuration data; specific for cluster2 profile<br/>

myconfig-client-app --> this is default config data for the config client application named myconfig-client-app<br/>
myconfig-client-app-cluster1 --> specific config data for the config client application named myconfig-client-app with cluster1 profile
