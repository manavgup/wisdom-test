# wisdom-test - Testing Watson Code Assistant VS Code Plugin for Ansible



1. Prerequisites
    In order to follow along in this tutorial you'll need the following:

    - Ansible installed
    - ansible[azure] pip packaged installed
    - Connection to Azure from Ansible setup
    - Install & configure Ansible VS Code Extension

2. Run manually created playbook

ansible-playbook main.yml

3. Clean all Azure resources

ansible-playbook cleanup.yml

4. Re-create Ansible playbook using VS Code Plugin

![Ansible Code Generation with Watson Code Assistant](./WatsonCodeAssistantCodegen.gif)




