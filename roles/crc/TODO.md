# near-term todo
- [ ] if updating the crc binary, do we check for a running instance and stop it?
- [ ] do we include a way of providing configuration?
  - For sure, but by generating the json file ourselves, or using `crc config`? Is the file format stable?
- [ ] prompt for pull secret, or retrieve it from vault?
  - [ ] allow config file embedding or separate secret file (the latter is good if you `rm -r ~/.crc`)
- [ ] copy in the default HAProxy config?

# eventual TODO
- [ ] set up certificates in the cluster
- [ ] set up an ingresscontroller for globally reachable FQDNs
- [ ] configure HAProxy as an authenticating proxy (once I figure that out)
- [ ] dnsmasq setup for reaching the CRC cluster
- [ ]  package the crc binary so that we can cache the download?
  - (outside of repo but then integrate)