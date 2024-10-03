# Classificação de Nível Herói (JavaScript)

Este projeto foi desenvolvido durante o **Bootcamp do Santander 2024 - Criando Jogos com Godot**. O objetivo do projeto é criar um programa em **JavaScript** que classifica o nível do herói com base em diferentes critérios.

## Funcionalidades

- **Classificação do Nível**: O programa avalia as características do herói e determina seu nível com base em critérios predefinidos.
- **Interatividade**: O código permite que os usuários interajam e obtenham resultados baseados nas entradas fornecidas.

## Tecnologias Utilizadas

- **JavaScript**: Linguagem de programação utilizada para implementar a lógica de classificação.
- **HTML/CSS**: Utilizados para a estruturação e estilização da interface do usuário.

## Instruções para Execução

### Executando o Código

A primeira tela do projeto mostra a execução do código JavaScript.

![Executando o código](https://github.com/luanalamonica/Nivel-Heroi/blob/main/primeira%20tela.png?raw=true)

#### Código Exemplo em JavaScript

```javascript
// Exemplo de código para classificar o nível do herói
function classificarHeroi(poder, experiencia) {
    if (poder > 80 && experiencia > 5) {
        return "Herói Lendário";
    } else if (poder > 50 && experiencia > 2) {
        return "Herói Experiente";
    } else {
        return "Herói Iniciante";
    }
}

// Exemplo de uso
const nivel = classificarHeroi(85, 6);
console.log(nivel); // Saída: Herói Lendário
```
## Como Executar o Projeto

Abra o arquivo HTML em um navegador web para executar o código JavaScript e visualizar a classificação do herói.

## Estrutura do Projeto

- **Scripts JavaScript**: Contém a lógica do programa para classificar o nível do herói.
- **HTML/CSS**: Estrutura e estilo da interface do usuário.

## Melhorias Futuras

- Implementar mais critérios de classificação para diversificar os níveis.
- Criar uma interface gráfica mais interativa para entrada de dados do usuário.
- Adicionar animações ou efeitos visuais para melhorar a experiência do usuário.

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para adicionar novas funcionalidades, melhorar o código ou ajustar a interface. Para contribuir:

1. Faça um _fork_ deste repositório.
2. Crie uma _branch_ com a nova funcionalidade (`git checkout -b feature/nova-funcionalidade`).
3. Envie suas alterações para o repositório (`git push origin feature/nova-funcionalidade`).
4. Abra um _pull request_ para revisão.
