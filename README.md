# Powershell-Script-QoS-Skype-for-Business-Online
Activate Quality of Service on your (local) Workstation.

This powershell script will setup some QoS rules and will activate QoS via Registry.

It will add the following rules:

*SkypeOnlineClientAudio Port: 50000-50019 DSCP Value: 46

*SkypeOnlineClientVideo Port: 50020-50039 DSCP Value: 34

*SkypeOnlineClientSharing Port: 50040-50059 DSCP Value: 24

*SkypeOnlineClientFileTransfer 50040-50059 DCSP Value: 24

Make sure your network is also QoS enabled.
