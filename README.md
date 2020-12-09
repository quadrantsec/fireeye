# Fireeye "Hacking Tools" (Red Team) Suricata & Snort signatures. 

These Suricata/Snort signatures are modified version supplied by the Fireeye Team. 
The original signatures are at https://github.com/fireeye/red_team_tool_countermeasures/tree/master/rules

Modifications:

* Signature ID do not interfere with Cisco Talos or Emerging Threats IDs.
* Fireeye signatures lacked a "classtype".  A class type of "trojan-activity".
* Added "reference" data. 

It appears that the Proofpoint Emerging Threat team has also included the Fireeye signatures into
there "current events" signature set.

