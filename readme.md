# Ansible Code Examples

Este repositório contém exemplos de códigos para serem usados com o Ansible. Os exemplos cobrem uma variedade de casos de uso comuns e podem ser úteis para automatizar tarefas de configuração, implantação e gerenciamento de infraestrutura.

## Como Usar

Cada pasta neste repositório representa um cenário ou caso de uso específico. Dentro de cada pasta, você encontrará arquivos YAML e outros recursos relevantes para a automação com Ansible.

### Pré-requisitos

Antes de executar os exemplos, certifique-se de ter o Ansible instalado em sua máquina de controle. Você pode instalar o Ansible seguindo as [instruções oficiais](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html).

### Executando um Exemplo

1. Navegue até o diretório do exemplo desejado.

2. Execute o playbook do Ansible:

   ```bash
   ansible-playbook -i hosts  example_playbook.yml -u seu_user -k -K -b
