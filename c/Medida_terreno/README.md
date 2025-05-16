```markdown
# 🏡 Cálculo da Área de um Terreno em C

Este programa em linguagem C solicita as medidas de frente
e laterais de um terreno retangular e calcula sua área em metros quadrados.

## 📌 Funcionalidades

- Entrada das medidas da frente e das laterais do terreno (em metros)
- Cálculo da área total do terreno
- Impressão do resultado no terminal

## 🧮 Fórmula utilizada

```

área = frente × laterais

````

## 📂 Estrutura do código

```c
float frente, laterais, area;
area = frente * laterais;
````

## 🖥️ Exemplo de uso

```
Informe a medida da frente do terreno em metros: 10
Informe o a medida das laterais do terreno em metros: 25
A medida da area do terreno, em metros, e de: 250.000000
```

## ▶️ Como compilar e executar

### No Linux/macOS:

```bash
gcc terreno.c -o terreno -lm
./terreno
```

### No Windows (com MinGW instalado):

```bash
gcc terreno.c -o terreno.exe -lm
terreno.exe
```

> ⚠️ A flag `-lm` é necessária para vincular a biblioteca `math.h`, mesmo que ela não esteja sendo usada diretamente aqui.

## 🧠 Observações

* O programa considera terrenos **retangulares**.
* Pode ser facilmente adaptado para outros formatos geométricos.
* Ideal para iniciantes que estão aprendendo **entrada de dados**, **variáveis**, **operações matemáticas** e **uso de `printf` e `scanf`**.

## 📄 Licença

Este projeto está sob a [Licença MIT](../LICENSE).
