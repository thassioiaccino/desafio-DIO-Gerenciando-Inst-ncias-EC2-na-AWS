# Desafio AWS EC2 - DIO

# Objetivo do Desafio

Este exercicio teve como objetivo praticar o gerenciamento de instâncias EC2 na AWS, tambem compreender integrações entre serviços da plataforma, armazenamento e automações.

---

# Conceitos Aplicados

Durante a atividade foram utilizados conceitos importantes da AWS, como:

- Criação e gerenciamento de instâncias EC2
- Utilização de volumes EBS
- Criação de snapshots
- Armazenamento com Amazon S3
- Arquivamento utilizando S3 Glacier
- Funções serverless com AWS Lambda
- Comunicação entre serviços
- Controle de acesso e conectividade

---

# Arquitetura Desenvolvida

O diagrama abaixo representa a arquitetura criada durante o desafio.

# Fluxo da aplicação

1. O usuário acessa o sistema SaaS.
2. O SaaS realiza comunicação com a instância EC2.
3. A EC2 também realiza integração com banco Oracle.
4. Os dados são persistidos em volumes EBS.
5. Rotinas automatizadas com Lambda realizam snapshots e envio de arquivos.
6. Os dados são armazenados no Amazon S3.
7. Arquivos de longo prazo são enviados para o S3 Glacier para arquivamento.

---

# Estrutura do Repositório

```bash
/desafio-DIO-Gerenciando-Inst-ncias-EC2-na-AWS
│
├── README.md
├── desafioDIO.drawio
│
├── /images
│   ├── diagrama.png
│   ├── ec2.png
│   ├── security-group.png
│   ├── USERS.png
```

---

# Capturas de Tela

As imagens utilizadas durante o laboratório estão disponíveis na pasta `/images`.

Exemplos:
- Instância EC2 criada
- Configuração de segurança
- Usuarios configurados

---

# Aprendizados

Durante o desenvolvimento deste desafio consegui aprofundar conhecimentos sobre:

- Estruturação de ambientes na AWS
- Relação entre EC2, EBS e S3
- Estratégias de backup utilizando snapshots
- Organização de arquitetura em nuvem
- Documentação técnica utilizando GitHub

---

# Ferramentas Utilizadas

- AWS EC2
- Amazon S3
- Amazon S3 Glacier
- Amazon EBS
- Oracle Database
- Draw.io
- GitHub

---

# Conclusão

Este desafio permitiu aplicar na prática conceitos fundamentais de computação em nuvem utilizando a AWS, além de reforçar conhecimentos sobre documentação técnica, arquitetura de serviços e versionamento com GitHub.
