# Desafio backend

<p align="center">
  <img src="https://media.giphy.com/media/3o72EX5QZ9N9d51dqo/giphy.gif" alt="gatos em cima de um toca disco"/>
</p>

Queremos que você use o teste para conhecer mais sobre algumas pessoas da Escale. Por isso ele foi baseado nas preferências musicais de diversas pessoas que trabalham com a gente. O seu desafio é construir uma API que se integre com outra API, uma coisa bem comum no dia a dia da ESCALE.

A sua API construida deve consumir uma API interna da escale que possui duas rotas:

Lista de músicas: https://recruitment.staging.escale.com.br/musics
Lista de usuários: https://recruitment.staging.escale.com.br/users

## 📜 Requisitos

**Requisito 1:** Informada uma pessoa, exibir todas as músicas que ela ouviu

**Requisito 2:** Informada uma pessoa, mostrar a música favorita dela

**Requisito 3:** Informada uma pessoa, listar todos estilos musicais que ela ouviu

**Requisito 4:** Informada uma música, exibir as 10 primeiras pessoas que mais ouviram a mesma

## Requisitos Extras

É um desafio **EXTRA** se a sua API atender aos seguintes requisitos:

**EXTRA 1:** Agrupar pessoas por tipo de música mais ouvida, ou seja, descobrir grupos que existem na Escale: Galera do Metal? Galera do Funk? K-Popers? MPBistas?

_Exemplo_:

- Se Marisa ouviu 20 vezes `metal` mas 1000 vezes `k-pop` o estilo mais ouvido de Marisa é `k-pop`
- Se João ouviu 1000 vezes `k-pop` e 1001 vezes metal o estilo de musica mais ouvido de João é metal
- Se Pedro ouviu 2 vezes metal e 3 vezes `k-pop` o estilo de música mais ouvido de Pedro é `k-pop`

Então ao agrupar por metal somente João estaria nesta lista, mas ao agrupar por `k-pop` a lista deveria conter Pedro e Marisa.

**EXTRA 2:** Faça automação de testes.

Achamos que testes podem ajudar a entender melhor seu código e que se pudéssemos executar todos os testes com uma única linha de comando seria perfeito, porém a escolha é sua. Só precisamos que você documente como executá-los.

**EXTRA 3:** Use Docker e crie uma imagem para a sua aplicação.

Muito dos nossos serviços usam uma ou várias imagens Docker para rodar, então se seu serviço subisse com apenas uma linha de comando como `docker-compose up app` gostaremos ainda mais do seu teste.

**EXTRA 4:** Faça o deploy da sua aplicação.
Você pode se sentir a vontade para deixar a sua aplicação rodando localmente através do download do repositório ou subir em um serviço de nuvem gratuito como o [Heroku](https://www.heroku.com/) ou [Vercel](https://vercel.com/).




### ✨ Detalhes

Gostamos de um README.md bem escrito que nos diga como executar a sua API, [exemplo](https://github.com/escaletech/tog-node), invista um tempo nisso e nos ajudará bastante.

Gostamos e usamos [convencional commits](https://www.conventionalcommits.org/en/v1.0.0/), mas fica a seu critério utilizá-lo.

### 💻 Linguagem utilizada

Utilizamos muito JavaScript, Go e as vezes Python, mas existem pessoas que programam nas mais diversas linguagens dentro do nosso time e muitas não tinham nenhuma proficiência nestas linguagens antes de entrar aqui, portanto escreva utilizando a linguagem que se sentir mais confortável.

### 🤔 Dúvidas

A gente sempre ensina e aprende uns com os outros, então qualquer dúvida abra uma [issue](https://docs.github.com/pt/issues/tracking-your-work-with-issues/creating-issues/creating-an-issue) aqui no github que ficaremos muito felizes em ajudar! Caso você não se sinta confortável em criar uma issue, você pode mandar a sua dúvida anonimamente [aqui nesse form](https://forms.gle/BaRcgKkCKYDvLMqw9)

### 🗂 Entrega

Se possível entregue o código em um repositório público, caso contrário mande um arquivo compactado com seu código dentro dele.

### 🕵🏾‍♀️ Como faremos a análise  

Seu código será analisado por algumas das pessoas engenheiras da Escale e observaremos a sua solução de acordo com alguns critérios como:

- Fundamentos de programação, como o uso de condicionais, estruturas de repetição, etc.
- Leitura e interpretação dos requisitos.
- Solução dos problemas propostos.
- Boas práticas de código
- Código de fácil leitura

Caso tenha entregue requisitos extras, observaremos critérios como:

- Automação de testes.
- Escolhas tecnológicas.

Assim que nós analisarmos o que você entregou marcaremos uma conversa para revisarmos todo o código junto com você. A nossa expectativa é que você nos entregue a sua solução em uma semana, porém use o tempo que for necessário para desenvolver esse desafio! 