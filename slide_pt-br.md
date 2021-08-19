# Desapegue

---

## DESAPEGUE-SE DOS SEUS SERVIDORES

### Uma história sobre infra-estrutura de TI

#### E o porque você precisa se desapegar dos seus servidores

##### Diego Neves

###### diego@diegoneves.eti.br

---

## $ whoami

* Atualmente sou DevOps Engineer;
* Trabalhando na área de Infra-estrutura de TI desde 2007;
* Especialista em Redes de Computadores;
* Bacharel em Sistemas de Informação.

---

## Tópicos

* Linha do Tempo;
  * Mais um pouco de história;
* Como fazemos hoje;
  * Algumas Tecnologias
* Exemplos.

---

## Linha do Tempo

* 1964 - O primeiro mainframe;
* 1987 - Andrew Tanenbaum desenvolve o Minix;
* 1991 - Linus Torvalds desenvolve o Linux;
* 2008 - Primeira release do LXC;
* 2012 - Primeira release do Ansible;
* 2013 - Primeira release do Docker;

---

### Mais um pouco de história

* No passado
  * Mainframes

* Não tão passado assim
  * Bare Metal: *Muitos servidores físicos, cada um responsável por algum serviço*.

* O início da "Revolução da Núvem"
  * Maquinas Virtuais;
  * Gerencia de Configurações.

---

### Como faziamos no passado

#### E não deveria ser o padrão hoje em nenhum lugar

* "Base de conhecimento", mas não tanto assim;
* Scripts;
* Snapshots e templates.

---

### Os maiores problemas da equipe de Infraestrutura

* Manter os servidores atualizados.
* Manter tudo com as mesmas configurações e versões;
* "Na minha máquina funciona";
* `Escolher o nome do servidor/maquina virtual`.

---

## Como fazemos hoje

### Ou deveriamos

* Atualmente:
  * Containers;
  * Infraestrutura Imutável.d

---

### Algumas Tecnologias

* Gerencia de Configurações
  * Puppet
  * Ansible

* Provisionamento
  * Ansible
  * Terraform

* "Templates"
  * Packer

* Pipelines
  * GitLab CI
  * GitHub Actions
  * Azure DevOps

---

## Exemplos

[Site Estático](https://github.com/diegoaceneves/iac-software)
[Ansible Role](https://github.com/diegoaceneves/iac-ansible-role)
[Terraform Module](https://github.com/diegoaceneves/iac-terraform)
[Packer Image](https://github.com/diegoaceneves/iac-packer)

---

## O que eu estava ouvindo enquanto fazia a palestra

* Iron Maiden
* Megadeath
* Queen
* Raul Seixas
* Slayer
