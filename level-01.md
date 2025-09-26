## Exercício 1: Apresentação Pessoal
**Contexto:** Você está criando um sistema de cadastro para um clube de programação. Cada novo membro precisa se apresentar.

**Enunciado:** Crie um programa que peça ao usuário:
- Nome completo
- Idade
- Linguagem de programação favorita

O programa deve então exibir uma mensagem de boas-vindas como:
"Olá [nome], seja bem-vindo(a) ao clube! Com [idade] anos, você já está explorando [linguagem]. Que legal!"

## Exercício 2: Calculadora de Idade Futura
**Contexto:** Um viajante do tempo quer saber quantos anos ele terá em diferentes anos no futuro.

**Enunciado:** Peça ao usuário:
- Ano atual
- Ano de nascimento
- Ano futuro que deseja saber

Calcule e mostre:
- Idade atual
- Idade que terá no ano futuro especificado

**Exemplo de saída:**
"Você tem 25 anos atualmente. Em 2030, você terá 30 anos."

## Exercício 3: Conversor de Temperatura
**Contexto:** Um cientista precisa converter temperaturas entre Celsius e Fahrenheit para seus experimentos.

**Enunciado:** Crie um programa que:
1. Peça uma temperatura em Celsius
2. Converta para Fahrenheit usando a fórmula: F = (C × 9/5) + 32
3. Mostre o resultado formatado

**Exemplo:** "25°C equivalem a 77°F"

## Exercício 4: Calculadora de Área do Retângulo
**Contexto:** Um arquiteto precisa calcular áreas de cômodos para planejar reformas.

**Enunciado:** Peça ao usuário:
- Comprimento da sala (em metros)
- Largura da sala (em metros)

Calcule e mostre a área total.

**Exemplo:** "Uma sala de 5m × 3m tem área de 15m²"

## Exercício 5: Contador de Caracteres
**Contexto:** Um escritor quer saber quantos caracteres tem seu texto para ajustar ao limite de uma plataforma.

**Enunciado:** Peça ao usuário para digitar uma frase qualquer. Conte e mostre:
- Quantidade total de caracteres (incluindo espaços)
- Quantidade de caracteres sem espaços

**Dica:** Use `len()` e `replace()`

## Exercício 6: Gerador de Nickname
**Contexto:** Em um jogo online, cada jogador precisa criar um nickname único.

**Enunciado:** Peça ao usuário:
- Primeiro nome
- Último nome
- Ano de nascimento

Crie um nickname combinando as iniciais do nome com o último nome e ano, tudo em minúsculas.

**Exemplo:** "Maria Silva 1990" → "msilva1990"

## Exercício 7: Calculadora de IMC
**Contexto:** Uma nutricionista precisa calcular o Índice de Massa Corporal de seus pacientes.

**Enunciado:** Peça ao usuário:
- Peso (em kg)
- Altura (em metros)

Calcule o IMC usando: IMC = peso / (altura × altura)
Mostre o resultado com 2 casas decimais.

## Exercício 8: Conversor de Moeda
**Contexto:** Um turista brasileiro vai viajar para os EUA e quer converter reais em dólares.

**Enunciado:** Considere que 1 dólar = 5.50 reais (valor fixo para o exercício).
Peça ao usuário:
- Valor em reais que deseja converter

Calcule e mostre o valor equivalente em dólares.

## Exercício 9: Calculadora de Gorjeta
**Contexto:** Em um restaurante, os clientes querem calcular a gorjeta para o garçom.

**Enunciado:** Peça ao usuário:
- Valor total da conta
- Percentual de gorjeta desejado (ex: 10, 15, 20)

Calcule e mostre:
- Valor da gorjeta
- Valor total a pagar (conta + gorjeta)

## Exercício 10: Cronômetro de Estudo
**Contexto:** Um estudante quer controlar seu tempo de estudo usando a técnica Pomodoro.

**Enunciado:** Peça ao usuário:
- Tempo de estudo em minutos
- Tempo de intervalo em minutos

Calcule e mostre:
- Horário de início do estudo
- Horário de término do estudo
- Horário de término do intervalo

**Dica:** Use `datetime` para trabalhar com horas

## Exercício 11: Validador de E-mail Simples
**Contexto:** Um sistema de cadastro precisa validar se um e-mail contém o caractere "@".

**Enunciado:** Peça ao usuário para digitar um e-mail. Verifique se contém "@" e mostre:
- "E-mail válido" se contiver "@"
- "E-mail inválido" se não contiver

## Exercício 12: Gerador de Senha Aleatória
**Contexto:** Um usuário precisa criar uma senha temporária para acessar um sistema.

**Enunciado:** Peça ao usuário:
- Palavra favorita
- Ano de nascimento
- Mês de nascimento (número)

Combine esses dados para gerar uma senha no formato: palavra_anomes

**Exemplo:** "python199005"
