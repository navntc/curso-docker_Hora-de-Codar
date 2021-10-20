# O que é o Docker ?
- Docker é um software que simplifica o uso de diferentes aplicações que serão usadas no mesmo projeto. <br>
- Reduz a complexidade de setup. (Setup: seriam tudo aquilo que será utilizado, por exemplo: MongoDB e MySQL)
- Aumentando assim, a performance do projeto.

# Por quê o Docker ?
- Você não precisa fazer manutenção em, por exemplo, 10 computadores diferentes e com SO's diferentes.
  - Basta você utilizar o Docker, e configurar um ÚNICO container que irá fazer a aplicação nos PC's
- Ele nos livra da 'Matriz from Hell'
  - Esse termo é a definição do problema de anterior: quando você precisa configurar diversos computadores

# Testando o Docker
- Para rodar os containers utilizamos o comando `docker run`
  - Neste comando podemos passar diversos parâmetros. Exemplos: o parâmetro `docker/whalesay`(que é o nome da imagem) e `cowsay` que vai ativar a aexibição de uma mensagem de texto.
  - Por fim, fica assim: `docker run docker/whalesay cowsay Hellow_World` 
