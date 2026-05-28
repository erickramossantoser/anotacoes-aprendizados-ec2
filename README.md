# Anotações e Aprendizados sobre Instâncias EC2 na AWS

## Objetivo

Este repositório foi criado como parte do desafio da DIO com o objetivo de registrar os principais conceitos aprendidos sobre gerenciamento de instâncias EC2 na AWS.

Durante as aulas consegui entender melhor como funcionam os serviços relacionados à criação de máquinas virtuais na nuvem, armazenamento EBS, snapshots e imagens AMI.

---

## Amazon EC2

O Amazon EC2 é um serviço da AWS utilizado para criar máquinas virtuais na nuvem.

Durante o laboratório, entendi o EC2 como um “computador virtual”, onde é possível escolher sistema operacional, memória RAM, armazenamento e processamento, dependendo da necessidade do projeto.

Essas instâncias podem ser utilizadas para hospedar aplicações, APIs, bancos de dados e diversos outros serviços.

![Instancia EC2](images/ec2.jpg)

---

## Amazon EBS

O Amazon EBS funciona como o armazenamento das instâncias EC2.

A forma mais fácil que encontrei para entender o EBS foi comparando com um HD/SSD de um computador normal, já que ele é responsável por armazenar o sistema operacional, arquivos e aplicações da instância.

---

## Snapshots EBS

Os snapshots funcionam como backups dos volumes EBS.

Aprendi que eles são muito importantes para recuperação de dados e segurança do ambiente, permitindo restaurar informações caso aconteça algum problema na instância.

![Snapshot EBS](images/snapshot.jpg)

---

## AMI

AMI significa Amazon Machine Image.

Entendi a AMI como uma “imagem pronta” de uma instância EC2 já configurada. Isso permite criar novas instâncias com as mesmas configurações, aplicações e sistema operacional da instância original.

![AMI AWS](images/ami.jpg)

---

## Diferença entre Snapshot e AMI

Durante o desafio, consegui entender que:

- Snapshot funciona como um backup do armazenamento (EBS);
- AMI funciona como um modelo completo da instância EC2.

Essa foi uma das partes mais importantes do laboratório para mim.

---

## Principais Aprendizados

- O EC2 funciona como uma máquina virtual na nuvem;
- O EBS é o armazenamento utilizado pela instância;
- Snapshots ajudam na recuperação e backup de dados;
- As AMIs permitem replicar instâncias já configuradas;
- A AWS oferece recursos de escalabilidade e alta disponibilidade;
- O GitHub pode ser utilizado para documentar estudos e projetos técnicos.

---

## Conclusão

Esse laboratório ajudou bastante no entendimento dos conceitos iniciais de computação em nuvem utilizando AWS.

Além da parte técnica, também foi importante para praticar documentação técnica utilizando GitHub e Markdown.