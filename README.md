# Kolide Fleet App for Splunk

The Splunk app can be found on Splunkbase here:
https://splunkbase.splunk.com/app/4518/

Details regarding Kolide Fleet + Splunk integration can be found in the following blog series:
Part I - Local Agent Interaction:  http://securitysynapse.blogspot.com/2019/05/osquery-part-i-local-agent-interaction.html
Part II - Kolide Centralized Management:  http://securitysynapse.blogspot.com/2019/05/osquery-part-ii-kolide-centralized.html
Part III - Queries and Packs:  http://securitysynapse.blogspot.com/2019/05/osquery-part-iii-queries-and-packs.html
Part IV - Fleet Control Using fleetctl - http://securitysynapse.blogspot.com/2019/05/osquery-part-iv-fleet-control-using-fleetctl.html

To import the file on this github repo into Kolide Fleet, perform the following:

  fleetctl apply -f kolide_splunk_app.yaml 
  [+] applied 4 queries 
  [+] applied 4 packs
