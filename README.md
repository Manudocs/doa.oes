# Gerenciador de Doações (Java)

Programa em Java que registra doações e calcula o total arrecadado, usando orientação a objetos.

## O que ele faz
- Cria doações com tipo (ex.: alimentos, roupas), quantidade e data
- Guarda as doações em uma lista
- Calcula o total de itens doados e mostra no console

## Estrutura
- `Doacao`: representa uma doação (tipo, quantidade e data, com getters e setters)
- `GerenciadorDoacoes`: guarda a lista de doações, adiciona novas e calcula o total
- `Main`: exemplo de uso, que cadastra duas doações e imprime o total

## Tecnologias e conceitos
- Java
- Orientação a objetos (classes, atributos privados, construtor, getters e setters)
- Coleções (`List` / `ArrayList`)
- Laço `for-each`

## Como rodar
```
javac Main.java
java Main
```

Saída esperada:
```
Total de doações: 15
```

## Ideias de melhoria
- Receber as doações digitadas pelo usuário
- Mostrar o total por tipo de doação
- Listar todas as doações registradas
- Trocar `Date` por `LocalDate`, que é a forma mais atual de trabalhar com datas em Java
