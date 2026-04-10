# ansible -i hosts.ini -m ansible.builtin.setup -a "filter=ansible_default_ipv4" test | grep "address" > info.txt
# ansible -i hosts.ini -m ansible.builtin.setup -a "filter=ansible_distribution" test | grep "ansible_distribution" >> info.txt
# ansible -i hosts.ini -m ansible.builtin.setup -a "filter=ansible_distribution_version" test | grep "ansible_distribution_version" >> info.txt
# ansible -i hosts.ini -m ansible.builtin.setup -a "filter=ansible_hostname" test | grep "ansible_hostname" >> info.txt
# ansible -i hosts.ini -m ansible.builtin.setup -a "filter=ansible_env" test >> info.txt