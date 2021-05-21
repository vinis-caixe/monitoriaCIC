# Sprint 3 - Engenharia de Software
#### Grupo 9
#### UnB - 2020/2

## Grupo

João Pedro Silva de Andrade - 17/0013944  
Pedro Henriques Nogueira - 14/0065032  
Vinícius Caixeta de Souza - 18/0132199  
Gustavo Einstein Soares Oliveira - 17/0104630  
Cesar Augusto Vilela Borges - 16/0116341  

## Projeto

Envio dos emails de resultado de monitoria (professores/alunos monitores).  
Professores recebem um email listando os alunos monitores por turma.  
Alunos recebem um email para cada monitoria confirmada ou rejeitada.  

## Implementações

### RubyCritic

Teste do ABC Score de cada método, o que define a complexidade dos métodos.  
Pontuações de complexidade reduzidas para abaixo de 20 pontos com sucesso!  

### Cucumber BDD (happy path/sad path)

Checagem das orientações do BDD pelo Cucumber - ver se havia um happy e um sad path condizentes.  
Checagem feita com sucesso! Módulos todos passando!  

### RDoc

Documentação dinâmica do código através de comentários bem estruturados.  
Métodos gerados pelo nosso grupo documentados com sucesso!  

## Papéis

 - Scrum Master - Pedro Nogueira  
 - Product Owner - João Pedro  
 - Equipe de desenvolvimento - Vinícius, Gustavo, César  

### Modo de trabalho

Trabalho feito em Scrum durante a semana. Não fielmente seguido à risca pelos integrantes não terem o tempo necessário, mas com reuniões esporádicas com definições de funcionalidades.  
Também houve muita programação a par, o que justifica a falta de commits de alguns membros.  

### Funcionalidades

- Vinicius: Encarregado em otimizar a nota do RubyCritic através de refatoramento.  
- Pedro e César: Responsáveis pela documentação em RDoc.  
- João e Gustavo: Encarregados em testar as funcionalidades do Cucumber e do RSpec.  

## Branches

- envio-emails: branch principal desse grupo, feita para enviar todos os emails.  
- emails-professores: branch interna para a funcionalidade de envio dos emails dos professores.  
- emails-alunos: branch interna para a funcionalidade de envio dos emails dos candidatos a monitoria.  
- teste-rspec: branch com os testes rspec.  
- rdoc-grupo9: branch que contém as adições dos comentários do RDoc e as mudanças dos README's.  

## Observações

O teste rspec está na pasta "test". Para rodar, digite no comando ```rails test```  