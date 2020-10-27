# Choice-Dialog-Sketchware
Choice dialog com temas | Sketchware
## Criando choice dialog com temas e salvando no shared preference pelo Sketchware
![Print 1](https://github.com/Gabriel-True/Choice-Dialog-Sketchware/blob/main/Screenshot_20201026-172716.png)

### Antes de começarmos o tutorial, pesquise na comunidade do sketchware pelo seguinte MoreBlock: "choice dialog". Como na imagem abaixo:
![Print 2](https://github.com/Gabriel-True/Choice-Dialog-Sketchware/blob/main/Screenshot_20201026-151025.png)

### Agora que você adicionou o bloco, vamos adicionar os componentes
1. Shared Preferences

![Print 3](https://github.com/Gabriel-True/Choice-Dialog-Sketchware/blob/main/Screenshot_20201026-151316.png)

(obs: o nome do shared preferences tem que ser o mesmo para todas as telas que você criar.)

2. Dialogo

![Print 4](https://github.com/Gabriel-True/Choice-Dialog-Sketchware/blob/main/Screenshot_20201026-151810.png)

(obs: coloque o mesmo nome no diálogo "d" para evitar erros. Se você quiser você pode colocar outro nome, mas terá que alterar no código do bloco "choice dialog".

### Agora na parte de Tela, adicione uma linear e um button. Como na imagem abaixo:

![Print 5](https://github.com/Gabriel-True/Choice-Dialog-Sketchware/blob/main/Screenshot_20201026-174232.png)

### Feito isso, na parte de evento › onCreate, criaremos uma lista string. Como na imagem abaixo:

![Print 6](https://github.com/Gabriel-True/Choice-Dialog-Sketchware/blob/main/Screenshot_20201026-171733.png)

### Continuando na onCreate, vamos colocar os seguintes blocos:

1. Adicionar para list string.
2. Definir number Position para 0.

### Como na imagem abaixo:

![Print 7](https://github.com/Gabriel-True/Choice-Dialog-Sketchware/blob/main/Screenshot_20201026-182015.png)

Coloque Escuro para o primeiro bloco e Claro para o segundo bloco e marque as list string. Depois marque a variável para Position 0 como mostra na imagem.

### Feito isso, agora vamos para a onClick do Button

### Iremos colocar os seguintes blocos:

1. Diálogo Definir Título (no título coloque escolher tema)
2. Coloque o bloco choice dialog (aquele que você baixou)
3. Botão OK (no botão coloque salvar/ok/definir o que você preferir)
4. Diálogo mostrar (servirá para mostrar o diálogo)

### Agora dentro do bloco Botão OK colocaremos os seguintes blocos:

1. Dois blocos Se Então (if then) um embaixo do outro
2. Dois blocos operadores igual ( = )

### Agora coloque o operador = dentro do bloco If Then. Feito isso, vá para a parte de variáveis e pegue bloco Position e adicione dentro do bloco operador. No primeiro If coloque Position = 0. e no segundo If coloque Position = 1. 

### Faça como na imagem abaixo:

![Print 8](https://github.com/Gabriel-True/Choice-Dialog-Sketchware/blob/main/Screenshot_20201026-182118.png)

Marque todos os blocos e strings.

Seu diálogo já está pronto, você pode fazer sua lógica dentro dos ifs. Mas para completar o tutorial vamos fazer os temas para o app (Escuro e Claro)

## Salvando os dados com Shared Preferences

### Agora você precisará dos seguintes blocos:

1. SharedPreferences DefinirDados Chaves Valor
2. Bloco Definir Cor de Fundo

### Em cada If adicione um bloco DefinirDados Chaves valor e o bloco Definir Cor de Fundo.

### No primeiro if você colocará uma chave "a" e o valor "escuro". E vai definir como cor Preto.

### No segundo If você colocará uma chave "a" e o valor "claro". e vai definir como cor Branco.

Agora marque os blocos.

### Faça como na imagem abaixo:

![Print 9](https://github.com/Gabriel-True/Choice-Dialog-Sketchware/blob/main/Screenshot_20201026-223337.png)

### Agora vamos voltar para a onCreate
