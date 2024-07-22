# SentinelOne-Agent-Installation

# Steps to install SentinelOne on Ubuntu
1. sudo dpkg -i SentinelAgent_linux_x86_64_v23_3_2_12.deb
2. Associate the Agent with the Management Console with the Group or Site Token. Run sudo /opt/sentinelone/bin/sentinelctl management token set <eyJ1cmwiOiAiaHR0cHM6Ly91c2VhMS1hdHQtY3liZXJzZWN1cml0eS0ydGllci1tc3NwLnNlbnRpbmVsb25lLm5ldCIsICJzaXRlX2tleSI6ICIyMDcxNTQ4YjZkZmYzYWRmIn0=>
3. Start the Agent services. Run 'sudo /opt/sentinelone/bin/sentinelctl control start'.
4.  Run 'sudo /opt/sentinelone/bin/sentinelctl control status'.

# Steps to install SentinelOne on CentOS
1. sudo rpm -i SentinelAgent_linux_x86_64_v23_3_2_12.rpm
2. Associate the Agent with the Management Console with the Group or Site Token. Run sudo /opt/sentinelone/bin/sentinelctl management token set <eyJ1cmwiOiAiaHR0cHM6Ly91c2VhMS1hdHQtY3liZXJzZWN1cml0eS0ydGllci1tc3NwLnNlbnRpbmVsb25lLm5ldCIsICJzaXRlX2tleSI6ICIyMDcxNTQ4YjZkZmYzYWRmIn0=>
3. Start the Agent services. Run 'sudo /opt/sentinelone/bin/sentinelctl control start'.
4.  Run 'sudo /opt/sentinelone/bin/sentinelctl control status'.
