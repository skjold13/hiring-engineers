Your answers to the questions go here.
Since I do not have access to lab facilities I conducted this exercise using Azure and my Mac
For testing the Firewall rules and the basic functionalities I initially installed a Windows server an validated that I could get a host configured and communicating against my DataDog account.

1.	Created a windows server 2019 WDog3 and installed agent using the 
https://app.datadoghq.com/account/settings#agent/windows 
Instructions.
Added tags to the installation
  msiexec /qn /i datadog-agent-6-latest.amd64.msi APIKEY="4e2177053a094d261c10e610b8ca8cdd" HOSTNAME="WDog3" TAGS="Windows, Test,Azure,W2K19"

I found out that the Datadog Agent ver 6 has its own bundled Python Environment and its management interface on localhost port 5002

