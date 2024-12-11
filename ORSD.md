# Documento de Especificação de Requisitos da Ontologia (ORS-D)

## 1. Introdução

### 1.1 Objetivo
Este documento descreve os requisitos necessários para o desenvolvimento de uma ontologia voltada para a computação afetiva no ensino, com o objetivo de modelar interações entre estudantes, professores, objetos digitais de aprendizagem e as emoções dos alunos. A ontologia visa adaptar atividades de aprendizagem com base no estado emocional dos alunos, monitorar suas emoções durante o processo educacional e fornecer feedback emocional.

### 1.2 Escopo
O escopo da ontologia abrange:
- A modelagem de conceitos e relações no contexto de educação e computação afetiva.
- A adaptação das atividades de aprendizado de acordo com as emoções capturadas dos alunos.
- O fornecimento de feedback emocional aos alunos com base nas interações com o sistema.

## 2. Requisitos Funcionais

Os requisitos funcionais da ontologia são formulados como questões de competência. Essas questões devem ser respondidas pelo processo de modelagem da ontologia. Abaixo estão as principais questões de competência que a ontologia precisa responder:

### 2.1 Questões de Competência

#### 2.1.1 Qual é o papel de um Professor no processo de ensino usando Objetos Digitais de Aprendizado?
A ontologia deve modelar o conceito de **Teacher (Professor)** e como ele utiliza o **DigitalLearningObject (Objeto Digital de Aprendizado)** para ensinar e interagir com os alunos. A questão é respondida por uma associação entre **Teacher** e **DigitalLearningObject**.

#### 2.1.2 Como a emoção de um aluno afeta sua interação com as atividades de aprendizado?
A ontologia precisa descrever como as emoções dos estudantes (**Emotion**) influenciam a adaptação das atividades educacionais (**Activity**) através do **DigitalLearningObject**. A questão é respondida pela modelagem da associação **adaptActivitiesBasedOnEmotion**, que liga **Emotion** a **Activity**.

#### 2.1.3 Como as emoções dos alunos são capturadas e associadas ao aprendizado?
A ontologia deve incluir mecanismos para modelar a captura das emoções dos alunos, representadas pela associação **capturesEmotionFrom**, que relaciona **DigitalLearningObject** com **Student** e **Emotion**.

#### 2.1.4 Qual é a relação entre os estudantes e o feedback emocional durante o processo de aprendizado?
A ontologia deve modelar o relacionamento entre o **EmotionDetectionSystem** e o **SoftwareWeb**, sendo este o processo de fornecimento de feedback emocional através da associação **providesEmotionFeedbackTo**.

### 2.2 Respostas Esperadas no Processo de Modelagem
A modelagem deve responder a essas questões, utilizando a definição de entidades, relacionamentos, papéis e estereótipos como elementos centrais para representar:
- A adaptação dinâmica do conteúdo educacional com base nas emoções dos alunos.
- A interação entre estudantes e professores através de objetos digitais de aprendizado.
- O monitoramento contínuo das emoções dos estudantes durante o processo de ensino e a retroalimentação emocional gerada.

## 3. Requisitos Não Funcionais

Os requisitos não funcionais são essenciais para a aplicação, utilização e disseminação da ontologia, e abrangem aspectos técnicos e organizacionais.

### 3.1 Idiomas de Publicação da Ontologia
A ontologia será publicada usando o **OWL (Web Ontology Language)**, um formato padrão para representação de ontologias na web. A ontologia pode ser complementada com **OWLDoc** para fornecer documentação acessível.

### 3.2 Disponibilidade de Documentação Adicional
A documentação adicional estará disponível em plataformas como **GitHub**, permitindo colaboração, controle de versão e contribuições da comunidade.

### 3.3 Facilidade de Uso e Adoção
A ontologia será estruturada de forma a ser intuitiva e de fácil compreensão para desenvolvedores de sistemas educacionais, pesquisadores em computação afetiva e educadores. A ontologia será projetada para fácil integração com outras ontologias educacionais existentes e ferramentas de aprendizado. A plataforma **GitHub** permitirá que a comunidade contribua para a evolução da ontologia, aumentando sua aceitação e aplicação prática.


## 4. Conclusão
Este Documento de Especificação de Requisitos da Ontologia (ORS-D) descreve os requisitos funcionais e não funcionais necessários para a criação de uma ontologia voltada para a computação afetiva no contexto educacional. A ontologia permitirá a adaptação das atividades de aprendizado com base nas emoções dos alunos, a captura de emoções durante o processo educacional e o fornecimento de feedback emocional.

A implementação dessa ontologia ajudará a construir sistemas educacionais mais dinâmicos e sensíveis ao estado emocional dos estudantes, promovendo um aprendizado mais personalizado e eficaz.
