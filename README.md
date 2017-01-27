# Ansible Role - Postfix as Smarthost

#### Variables

* postfix_relayhost: Destination mail server for relaying (required)
* postfix_destinations: Alternative destinations configuration (Default: {{ ansible_hostname }}, {{ansible_fqdn}}, localhost)
* postfix_mynetworks: Alternative mynetworks configuration (Default: 127.0.0.0/8 [::ffff:127.0.0.0]/104 [::1]/128)
