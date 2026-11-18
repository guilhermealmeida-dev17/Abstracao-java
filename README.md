# Exercício de abstração e modelagem em Java

Aplicação de console para praticar modelagem de classes e objetos com exemplos de carros e profissões. O projeto organiza os exemplos nos pacotes `model` e `view` e usa menus interativos para explorar os comportamentos.

## O que o programa demonstra

- Cadastro e listagem de carros em uma `ArrayList`.
- Seleção de um carro para ligar, desligar, acelerar, frear ou buzinar.
- Exemplos de objetos de diferentes profissões, cada um com atributos e ações próprios.
- Leitura de opções pelo console com `Scanner`.

## Tecnologias e conceitos

- Java
- Classes, objetos, construtores e métodos
- Listas com `ArrayList`
- Separação simples entre modelos e interface de console

## Como executar

É necessário ter um JDK instalado. No PowerShell, execute na pasta do repositório:

```powershell
New-Item -ItemType Directory -Force out | Out-Null
$sources = Get-ChildItem -Filter *.java | ForEach-Object { $_.FullName }
javac -d out $sources
java -cp out br.edu.fatecpg.abstracao.view.Main
```

O projeto é um exercício de estudo e não possui persistência de dados.
