

#### Proviosining

Install sshpass using Homebrew:

https://formulae.brew.sh/formula/ansible

https://formulae.brew.sh/formula/sshpass


###  Here's a step-by-step guide

1. Create a configuration file named ansible.cfg in your project directory 
2. Create a hosts inventory file named hosts in your project directory
3. Create a playbook file named ios_show_commands.yml in your project directory
4. Run the playbook using the following command in the terminal:

   ansible-playbook -i hosts ios_show_commands.yml --user your_username --ask-pass

 The playbook will connect to each Cisco IOS device specified in the inventory file, run the show commands, and display the output in the terminal.


 ### Documentation

 https://docs.ansible.com/ansible/latest/collections/cisco/ios/index.html
 https://docs.ansible.com/ansible/latest/collections/cisco/ios/ios_command_module.html#ansible-collections-cisco-ios-ios-command-module
 https://docs.ansible.com/ansible/latest/collections/cisco/ios/ios_config_module.html#ansible-collections-cisco-ios-ios-config-module
 https://docs.ansible.com/ansible/latest/collections/cisco/ios/ios_config_module.html#ansible-collections-cisco-ios-ios-config-module
 






