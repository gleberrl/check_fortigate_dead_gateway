# check_fortigate_dead_gateway
Check SNMP dead Gateway on Fortigate Firewall

Usage: check_fortigate_dead_gateway -H [IP ADDRESS] -C [COMMUNITY] -v [SNMP_Version - 2|3]

-H --&gt; IP ADDRESS
<br />-C --&gt; COMMUNITY SNMP_V2
<br />-v --&gt; SNMP Version
<br />--wl|--warning_loss --&gt; WARNING PACKET LOSS VALUE - (%) [OPTIONAL]
<br />--cl|--critical_loss --&gt; CRITICAL PACKET LOSS VALUE - (%) [OPTIONAL]
<br />--wr|--warning_rtt --&gt; WARNING RTT VALUE - (ms) [OPTIONAL]
<br />--cr|--critical_rtt --&gt; CRITICAL RTT VALUE - (ms) [OPTIONAL]
<br />=====If SNMP_V3=====
<br />-a --&gt; protocol (MD5/SHA)
<br />-A --&gt; Authentication PASSPHRASE
<br />-l --&gt; security level (noAuthNoPriv|authNoPriv|authPriv)
<br />-x --&gt; Protocol (DES|AES)
<br />-X --&gt; Protocol PASSPHRASE
<br />-u --&gt; Username (Security Username)
