# Projeto Integrador I: Desenvolvimento de Sistemas Orientado a Objetos

Este repositório contém o desenvolvimento do Projeto Integrador I do curso de **Tecnologia em Análise e Desenvolvimento de Sistemas** do Centro Universitário Senac. O projeto utiliza conceitos de **Modelagem Orientada a Objetos (MOO)** para criar um sistema de **gestão acadêmica** de uma faculdade, com foco em cadastro e organização de dados.

---

## 📄 **Resumo**

Este projeto explora o funcionamento organizacional de uma faculdade, abordando as interações entre alunos, professores, fornecedores e a administração. O sistema modelado visa centralizar informações, facilitar o gerenciamento de dados e garantir a integridade das operações administrativas.

O sistema organiza dados relacionados a:
- **Alunos**: Matriculados em cursos e turmas específicas.
- **Professores**: Responsáveis por lecionar e avaliar os alunos.
- **Fornecedores**: Empresas que oferecem produtos e serviços essenciais.
- **Administração**: Coordena todos os processos acadêmicos e financeiros.

---

## 🎯 **Objetivo do Sistema**

O sistema busca otimizar e centralizar a gestão de dados de uma universidade. Suas principais metas incluem:
1. **Automatização de processos**: Cadastro e consulta de dados de forma eficiente.
2. **Gestão centralizada**: Unificação de informações de pessoas físicas e jurídicas.
3. **Validação e integridade de dados**: Redução de erros e duplicidades.
4. **Apoio à tomada de decisões**: Geração de relatórios gerenciais.

---

## 📌 **Diagrama de Caso de Uso**

O diagrama de caso de uso apresenta os principais atores e funcionalidades do sistema, como o cadastro de alunos, professores e fornecedores.  

![Diagrama de caso de uso](https://i.imgur.com/U8b12sv.png)

---

## ✍️ **Cenários de Caso de Uso**

### **Caso de Uso 1: Cadastro de Pessoa Física**
- **Descrição**: Cadastro de dados pessoais de pessoas físicas no sistema.
- **Pré-condições**: CPF válido e sistema online.
- **Pós-condições**: Cadastro concluído e vinculação como aluno ou professor.

#### **Cenários Alternativos**
1. **CPF inválido**: O sistema rejeita o cadastro e solicita um CPF válido.
2. **Sistema fora do ar**: Usuário notificado para tentar novamente mais tarde.

---

### **Caso de Uso 2: Matrícula de Aluno em Curso**
- **Descrição**: Aluno seleciona curso e turma desejados.
- **Pré-condições**: Aluno registrado no sistema e vagas disponíveis.
- **Pós-condições**: Matrícula concluída, permitindo o acesso às aulas.

#### **Cenários Alternativos**
1. **Sem vagas disponíveis**: Sistema sugere outras turmas.
2. **Aluno inadimplente**: Matrícula interrompida até regularização financeira.

---

### **Caso de Uso 3: Contratação de Fornecedor**
- **Descrição**: Cadastro e contratação de pessoa jurídica para prestação de serviços.
- **Pré-condições**: CNPJ válido e análise administrativa aprovada.
- **Pós-condições**: Fornecedor cadastrado e contrato estabelecido.

#### **Cenários Alternativos**
1. **CNPJ inválido**: Sistema solicita um CNPJ válido.
2. **Contrato não aprovado**: Notificação de rejeição ao fornecedor.

---

### **Caso de Uso 4: Cadastro de Professor e Alocação em Turma**
- **Descrição**: Cadastro de professores (PF ou PJ) e designação às turmas.
- **Pré-condições**: CPF ou CNPJ válido e turmas disponíveis.
- **Pós-condições**: Professor alocado e apto a lecionar.

#### **Cenários Alternativos**
1. **Dados incompletos**: Sistema solicita correção dos dados.
2. **Vínculo como PJ rejeitado**: Contrato não aprovado pela faculdade.

---

## 📂 **Diagrama de Classe**

O diagrama de classe detalha as relações e atributos entre entidades do sistema, como Aluno, Professor, e Fornecedor.  

![Diagrama de classe](https://i.imgur.com/y98ee6k.png)

---

## 🛠️ **Ferramentas Utilizadas**
- **[Lucidchart](https://www.lucidchart.com/)**: Para criação dos diagramas UML.
- **[Figma](https://www.figma.com/)**: Para o desenvolvimento do protótipo funcional.

---

## 🌐 **Protótipo Funcional**

O protótipo funcional foi desenvolvido com base no diagrama de caso de uso. Ele simula as jornadas de cadastro de:
- **Alunos**
- **Professores**
- **Fornecedores**

### **Acesse o protótipo no Figma**  
[🔗 Clique aqui para acessar o protótipo](https://www.figma.com/design/pkkBQVRADTYcfmO2tnlJQj/Projeto-Integrador-II?node-id=0-1&t=pEZ4a5mmYh5KkvhL-1)



## 📚 **Referências**
- **Lucidchart**: [Diagrama de caso de uso UML](https://www.lucidchart.com/pages/pt/diagrama-de-caso-de-uso-uml)
- **Creately**: [Tutorial de diagramas de classe UML](https://creately.com/blog/pt/diagrama/tutorial-diagrama-de-classes/)
- **Miro**: [O jeito mais fácil de criar diagramas de classe UML](https://miro.com/pt/diagrama/diagrama-classes-uml/)
