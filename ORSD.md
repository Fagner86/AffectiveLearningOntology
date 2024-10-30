# Documento de Especificação de Requisitos da Ontologia (ORSD)

## 1. Introdução

A computação afetiva no contexto educacional digital visa otimizar o processo de ensino-aprendizagem, explorando emoções dos alunos para personalizar a experiência. Esta ontologia modela essa interação, focando em como objetos de aprendizagem digital influenciam os estados emocionais dos estudantes.

## 2. Objetivo

Definir uma ontologia para representar o impacto de objetos de aprendizagem digital sobre os estados emocionais dos estudantes, promovendo uma abordagem personalizada e emocionalmente inteligente.

## 3. Escopo

Aplicável ao ambiente educacional digital, a ontologia será usada para desenvolver sistemas de aprendizagem afetiva que reconheçam e ajustem-se às emoções dos alunos.

## 4. Requisitos da Ontologia

### 4.1 Requisitos Funcionais
- **RF1**: Representar estados emocionais, incluindo tipos como motivação e engajamento.
- **RF2**: Modelar objetos de aprendizagem e associá-los aos estados emocionais.
- **RF3**: Estabelecer relações de interação entre estudantes, seus estados emocionais e objetos de aprendizagem.

### 4.2 Requisitos Não Funcionais
- **RNF1**: Compatibilidade com a ferramenta Protégé e exportação OWL.
- **RNF2**: A ontologia deve ser documentada em um repositório GitHub.

## 5. Conceitos e Classes Principais

1. **Estudante**
   - *Propriedades*: `nome` (string), `idade` (integer), `nívelEscolaridade` (string).
   
2. **ObjetoAprendizagem**
   - *Propriedades*: `tipo` (string), `dificuldade` (integer), `tema` (string).
   
3. **EstadoEmocional**
   - *Propriedades*: `tipoEmocional` (string), `intensidade` (integer), `duracao` (time).

## 6. Relações

- **interageCom**: Relaciona `Estudante` e `ObjetoAprendizagem`.
- **temEstado**: Define os estados emocionais de `Estudante` enquanto interage com `ObjetoAprendizagem`.

---
