# Desafio backend

<p align="center">
  <img src="https://media.giphy.com/media/3o72EX5QZ9N9d51dqo/giphy.gif" alt="gatos em cima de um toca disco"/>
</p>

Queremos que você use o teste para conhecer mais sobre algumas pessoas da Escale. Por isso ele foi baseado nas preferências musicais de diversas pessoas que trabalham com a gente. O seu desafio é construir uma API que se integre com outra API, uma coisa bem comum no dia a dia da ESCALE.

A sua API construida deve consumir uma API interna da escale que possui duas rotas:

Lista de músicas: https://recruitment.staging.escale.com.br/musics
Lista de usuários: https://recruitment.staging.escale.com.br/users

### 📜 Requisitos
* 1 - Informada uma pessoa, informar todas as músicas que ela ouviu
* 2 - Informada uma pessoa, informar a música favorita dela
* 3 - Informada uma pessoa, listar todos estilos musicais que ela ouviu
* 4 - Informada uma música, listar as 10 primeiras pessoas que mais ouviram a mesma

### Requisito Opcional
É um desafio extra se a sua API atender a esse requisito:

* 5 - Agrupar pessoas por tipo de música mais ouvida, ou seja, descobrir grupos que existem na Escale: Galera do Metal? Galera do Funk? K-Popers? MPBistas?

*Exemplo*:

Se Marisa ouviu 20 vezes `metal` mas 1000 vezes `k-pop` o estilo mais ouvido de Marisa é `k-pop`

Se João ouviu 1000 vezes `k-pop` e 1001 vezes metal o estilo de musica mais ouvido de João é metal

Se Pedro ouviu 2 vezes metal e 3 vezes `k-pop` o estilo de música mais ouvido de Pedro é `k-pop`

Então ao agrupar por metal somente João estaria nesta lista, mas ao agrupar por `k-pop` a lista deveria conter Pedro e Marisa.

### ✨ Detalhes

Testes de unidade podem nos ajudar a entender melhor seu código. Se pudéssemos executar todos os testes com uma única linha de comando seria perfeito.

Muito dos nossos serviços usam uma ou várias imagens Docker para rodar, então se seu serviço subisse com apenas uma linha de comando gostaremos ainda mais do seu teste, [docker-compose](https://docs.docker.com/compose/) pode ser uma boa.

Você pode se sentir a vontade para deixar a sua aplicação rodando localmente através do download do repositório ou subir em um serviço de nuvem gratuito como o [Heroku](https://www.heroku.com/) ou [Vercel](https://vercel.com/).

Gostamos de um README.md bem escrito que nos diga como executar a sua API, [exemplo](https://github.com/escaletech/tog-node), invista um tempo nisso e nos ajudará bastante.

Gostamos e usamos [convencional commits](https://www.conventionalcommits.org/en/v1.0.0/), mas fica a seu critério utilizá-lo. 

### 💻 Linguagem utilizada

Utilizamos muito JavaScript, Go e as vezes Python, mas existem pessoas que programam nas mais diversas linguagens dentro do nosso time e muitas não tinham nenhuma proficiência nestas linguagens antes de entrar aqui, portanto escreva utilizando a linguagem que se sentir mais confortável. 

### 🤔 Dúvidas
A gente sempre ensina e aprende uns com os outros, então qualquer dúvida abra uma [issue](https://docs.github.com/pt/issues/tracking-your-work-with-issues/creating-issues/creating-an-issue) aqui no github que ficaremos muito felizes em ajudar!

### 🗂 Entrega
Se possível entregue o código em um repositório público, caso contrário mande um arquivo compactado com seu código dentro dele.

### 🕵🏾‍♀️ Como faremos a análise
Seu código será analisado por algumas das pessoas engenheiras da Escale e observaremos a sua solução de acordo com algumas métricas como:

* Funcionalidade: Capacidade de prover funcionalidades que satisfaçam as necessidades declaradas e implícitas

* Confiabilidade: Capacidade de manter um nível de entrega estável em condições especificadas

* Eficiência: Tempo e recursos envolvidos são compatíveis com o nível de desempenho 

* Manutenibilidade: Facilidade de ser modificado, incluindo extensões de funcionalidade e correções de defeitos

* Portabilidade: Capacidade do sistema ser transferido de ambiente
