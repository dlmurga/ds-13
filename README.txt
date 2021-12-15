parameters added to ansible.cfg

[defaults]
host_key_checking = false
remote_user = ubuntu
ask_pass = false
private_key_file = /root/keys/my-key13.pem
roles_path = /root/ds-13

[privilege_escalation]
become=True
become_method=sudo
become_user=root
become_ask_pass=False