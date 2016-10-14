## What is this?

The scripts contained in this page are for testing the following 2 components of CAS (Central Authentication Service): https://apereo.github.io/cas  
1. CAS REST API: https://apereo.github.io/cas/development/protocol/REST-Protocol.html   
2. CAS User Interface   

Note: The scripts were tested against CAS 5.0 Release Candidate 4.

## How to run:

1. Download Apache JMeter: http://jmeter.apache.org/download_jmeter.cgi (Note: Version 3.0 r1743807 used in this example)  
2. Open cas-users.csv and edit the comma-separated list of users accordingly.  These are the users you will login with in the test.   
3. To run JMeter in a non-GUI mode: <JMETER_HOME>/bin/jmeter -n -t ./rest-api.jmx -Jserver=please.replace.this.value.with.your.application.host.local -l ./log.jtl  

Please note that Thread-Group.jmx was an original script used in earlier versions of CAS.  Thread-Group.jmx is here for archive purposes only and may be deleted later.  
