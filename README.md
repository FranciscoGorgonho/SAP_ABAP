# SAP ABAP — Exercícios

Repositório com exercícios desenvolvidos em **SAP ABAP**, com o objetivo de praticar conceitos básicos da linguagem, como declaração de variáveis, parâmetros, operações matemáticas, cálculos, estruturas condicionais e saída de dados.

## 📚 Exercícios

| Exercício      | Descrição                         | Conceitos praticados                                 |
| -------------- | --------------------------------- | ---------------------------------------------------- |
| **ZEXERC0001** | Cálculo de idade                  | Variáveis, parâmetros, datas e operações matemáticas |
| **ZEXERC0002** | Cálculo de metro quadrado         | Parâmetros e operações matemáticas                   |
| **ZEXERC0003** | Cálculo de porcentagem            | Operações matemáticas e porcentagem                  |
| **ZEXERC0004** | Custo de viagem                   | Cálculos, consumo de combustível e valor total       |
| **ZEXERC0005** | Cálculo de IMC                    | Operações matemáticas e estruturas condicionais      |
| **ZEXERC0006** | Desconto, acréscimo e valor total | Estruturas condicionais, porcentagem e cálculos      |

## 📁 Estrutura do projeto

```text
sap_abap/
└── Exercícios/
    ├── ZEXERC0001-Calculo-idade.txt
    ├── ZEXERC0002-Metro-quadrado.txt
    ├── ZEXERC0003-Porcentagem.txt
    ├── ZEXERC0004-Custo-viagem.txt
    ├── ZEXERC0005-Calculo-IMC.txt
    └── ZEXERC0006-Desconto-acrescimo-valor-total.txt
```

## 🧩 Exercícios

### ZEXERC0001 — Cálculo de idade

Recebe o nome e o ano de nascimento de uma pessoa e calcula sua idade com base no ano atual.

**Entrada:**

* Nome
* Ano de nascimento

**Saída:**

* Nome da pessoa
* Idade calculada

---

### ZEXERC0002 — Metro quadrado

Calcula a metragem quadrada de uma área utilizando duas medidas.

**Fórmula:**

```text
Área = medida 1 × medida 2
```

---

### ZEXERC0003 — Porcentagem

Calcula o valor correspondente a uma determinada porcentagem.

**Fórmula:**

```text
Resultado = (valor ÷ 100) × porcentagem
```

---

### ZEXERC0004 — Custo de viagem

Calcula a quantidade de combustível necessária para uma viagem e o custo total do combustível.

**Fórmulas:**

```text
Litros gastos = distância ÷ consumo (km/l)

Valor total = litros gastos × preço do litro
```

**Entrada:**

* Distância da viagem
* Valor do litro do combustível
* Consumo do veículo em km/l

**Saída:**

* Quantidade de combustível consumida
* Valor total gasto

---

### ZEXERC0005 — Cálculo de IMC

Calcula o Índice de Massa Corporal (IMC) utilizando o peso e a altura informados e classifica o resultado.

**Fórmula:**

```text
IMC = peso ÷ (altura × altura)
```

As classificações utilizadas no exercício são:

* Muito abaixo do peso
* Abaixo do peso
* Peso normal
* Acima do peso
* Obesidade I
* Obesidade II (severa)
* Obesidade III (mórbida)

---

### ZEXERC0006 — Desconto, acréscimo e valor total

Calcula descontos ou acréscimos de acordo com o valor do produto e a quantidade de parcelas.

O exercício utiliza estruturas condicionais para determinar o percentual aplicado.

**Cálculo:**

```text
Desconto/Acréscimo = (valor ÷ 100) × percentual

Valor final = valor original + desconto/acréscimo
```

O programa apresenta:

* Valor original
* Quantidade de parcelas
* Percentual de desconto/acréscimo
* Valor do desconto/acréscimo
* Valor final

## 🎯 Objetivo

Os exercícios têm como objetivo desenvolver a familiaridade com os fundamentos da linguagem **ABAP**, servindo como prática para conceitos básicos de programação aplicados ao ambiente SAP.

## 🛠️ Tecnologias

* **SAP ABAP**
* **ABAP Reports**
* Parâmetros de seleção
* Tipos de dados
* Operações matemáticas
* Estruturas condicionais (`IF`, `ELSEIF`)
* Saída de dados com `WRITE`

## 📌 Observação

Os arquivos estão armazenados em formato `.txt` para facilitar o versionamento e estudo do código ABAP.
