# Avaliação Sprint 2 - Programa de Bolsas Compass UOL / AWS e Univesp

Avaliação da segunda sprint do programa de bolsas Compass UOL para formação em machine learning para AWS.

***

## Execução (Código Fonte)

Exposição na web do projeto da Sprint 1, com a utilização da AWS Cloud.

**Especificações**:

Passos de execução do projeto em uma conta AWS disponibilizada no Programa de Bolsas:

1. Criar uma VPC.
2. Criar um Internet Gateway, associando-o à VPC criada.
3. Criar as rotas públicas e privadas.
4. Criar um NAT Gateway para ligação da rota pública com um IP elástico.
5. Concluir a configuração da rota privada.
6. Criar ou editar o Security Group com as regras entrada e saída.
7. Criar uma instância t2.micro.
8. Instalar um servidor nginx na instância.
9. Trocar ou acrescentar a porta 9000 para acesso através do nginx.
10. Subir ao servidor a aplicação da Sprint 1.
11. Na página html disponibilizada com o código da Sprint 1, colocar a identificação do grupo e os nomes dos componenentes.
12. Permitir o acesso da porta 9000 à pasta com a aplicação, para visualização da página de forma online.

O seguinte esquema sintetiza a arquitetura proposta nesta avaliação:

<img src='assets/aws_web_server.jpg' width='50%'>


***

## O que será avaliado?

- Uso do código JavaScript da Sprint 1
- Seguir as atividades na ordem proposta
- Subir códigos no git ao longo do desenvolvimento
- Organização geral do código fonte
  - Estrutura de pastas
  - Estrutura da logica de negócio
  - Divisão de responsabilidades em arquivos/pastas distintos
  - Otimização do código fonte (evitar duplicações de código)
- Objetividade do README.md
- Modelo de organização da equipe para o desenvolvimento do projeto
- Página criada com acesso online.

***

## Entrega

- Aceitar o convite do repositório da sprint-2-pb-aws-univesp;
- **O trabalho deve ser feito em grupos de quatro pessoas**;
  - Evitar repetições de grupos da sprint anterior;
- Criar uma branch no repositório com o formato grupo-número (Exemplo: grupo-1);
- Subir o trabalho na branch com um [Readme.md](README.md)
  - documentar detalhes sobre como a avaliação foi desenvolvida
  - dificuldades conhecidas
  - como utilizar o sistema
  - 🔨 código fonte desenvolvido (Sugestão: pasta `src`)
  - configuração nginx
  - URL para acesso à página
- O prazo de entrega é até às 12h do dia 06/03/2023 no repositório do github ([https://github.com/Compass-pb-aws-2023-Univesp/sprint-2-pb-aws-univesp](https://github.com/Compass-pb-aws-2023-Univesp/sprint-2-pb-aws-univesp)).


#**<font color="blue">Eplicando a nossa Solução para a atividade acima</font>**
O Grupo reunui-se pelo Teams, para dividir suas tarefas. 
As tarefas foram organizadas no Trello.
    - Se imagens:



O contato contante durante a contrução da Sprinte foi feita pelo WhahtsApp.
📚Muitas discurssões, pesquisa e esclarecimento de dúvidas mutuas.

##A seguir a relação do que foi pedido e criado na Sprint_2

Criamos:<br>
    ✅uma uma VPC.<br>
    ✅um Internet Gateway, associando-o à VPC criada.<br>
    ✅as rotas públicas e privadas.<br>
    ✅um NAT Gateway para ligação da rota pública com um IP elástico.<br>
    ✅configuramos uma rota privada.<br>
    ✅o Security Group com as regras entrada e saída.<br>
    ✅uma instância t2.micro.<br>
Instalamos:<br>
    ✅servidor nginx na instância.<br>
acrescentamos: a porta 9000 para acesso através do nginx.<br>
Subimos no servidor:<br>
    ✅a aplicação da Sprint 1.<br>
Disponibilizamos:<br>
    ✅em uma página html o código da Sprint 1, colocar a identificação do grupo e os nomes dos componenentes.<br>
Permitimos:<br>
    ✅o acesso da porta 9000 à pasta com a aplicação, para visualização da página de forma online.<br>

Foi Usado o código da pasta src na página que foi feito o deploy no servidor web AWS.<br>
Segue o link da página 👉http/

