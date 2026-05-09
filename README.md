# 📊 Calculadora de IMC Profissional

## 📋 Resumo Executivo

Uma aplicação de linha de comando (CLI) em Python para cálculo e classificação do Índice de Massa Corporal (IMC). O projeto demonstra boas práticas de desenvolvimento, tratamento de erros robusto e código bem estruturado e documentado.

---

## 🎯 Objetivos do Projeto

Este projeto foi desenvolvido para:

- ✅ **Demonstrar conhecimentos fundamentais em Python** com código limpo e eficiente
- ✅ **Implementar validação robusta de entrada** de dados do usuário
- ✅ **Aplicar princípios SOLID** com funções de responsabilidade única
- ✅ **Usar boas práticas de desenvolvimento** como type hints e docstrings
- ✅ **Resolver um problema real** com uma solução funcional e intuitiva

---

## 🛠️ Tecnologias e Conceitos Aplicados

| Conceito | Descrição |
|----------|-----------|
| **Linguagem** | Python 3.x |
| **Type Hinting** | Anotação de tipos para melhor legibilidade e manutenção |
| **Modularização** | Funções com responsabilidades únicas (SRP) |
| **Documentação** | Docstrings descritivas em todas as funções |
| **Tratamento de Erros** | Blocos try-except para validação de entrada |
| **Validação de Dados** | Verificação de valores lógicos (não negativos) |

---

## 📐 Lógica e Fórmula Matemática

### Fórmula do IMC

```
IMC = Peso (kg) / Altura² (m²)
```

### Classificação de Resultados

| Intervalo | Classificação |
|-----------|---|
| IMC < 18,5 | Abaixo do peso |
| 18,5 ≤ IMC < 25,0 | Peso normal |
| 25,0 ≤ IMC < 30,0 | Sobrepeso |
| IMC ≥ 30,0 | Obesidade |

*Fonte: Padrões estabelecidos pela Organização Mundial da Saúde (OMS)*

---

## 🚀 Como Executar

### Pré-requisitos
- Python 3.6 ou superior

### Instalação
1. Clone o repositório:
```bash
git clone https://github.com/adrianoabc786-prog/Calculadora_de_IMC.py.git
cd Calculadora_de_IMC.py
```

2. Execute o programa:
```bash
python "Código"
```

### Exemplo de Uso
```
=== Calculadora de IMC ===
Digite o peso em KG (ex: 75.8): 70
Digite sua altura em metros (ex: 1.80): 1.75

Seu IMC é 22.9
Classificação: Peso normal
```

---

## 💡 Estrutura do Código

O projeto é organizado em **3 funções principais**:

### 1️⃣ `calcular_imc(peso: float, altura: float) -> float`
- Realiza o cálculo matemático do IMC
- Recebe peso em kg e altura em metros
- Retorna o valor do IMC

### 2️⃣ `obter_classificacao(imc: float) -> str`
- Classifica o IMC em categorias de saúde
- Utiliza lógica condicional eficiente
- Retorna a classificação em formato legível

### 3️⃣ `executar_calculadora() -> None`
- Gerencia a interface com o usuário
- Captura e valida entradas
- Orquestra o fluxo da aplicação

---

## 🔍 Recursos Implementados

- ✅ **Validação de Entrada**: Trata valores inválidos (letras, caracteres especiais)
- ✅ **Validação Lógica**: Rejeita valores zero ou negativos
- ✅ **Mensagens de Erro Claras**: Feedback útil ao usuário
- ✅ **Formatação de Saída**: Resultado com 1 casa decimal
- ✅ **Code Quality**: Type hints e documentação inline

---

## 📦 Arquivos do Projeto

```
Calculadora_de_IMC.py/
├── README.md          # Documentação do projeto
└── Código             # Código-fonte Python
```

---

## 🎓 O que Este Projeto Demonstra

Este projeto exemplifica competências essenciais para uma posição de estágio:

| Competência | Evidência |
|------------|-----------|
| **Lógica de Programação** | Implementação clara da fórmula matemática e fluxo condicional |
| **Python Fundamentals** | Funções, type hints, tratamento de exceções |
| **Boas Práticas** | Código limpo, modular e bem documentado |
| **User Experience** | Interface intuitiva com mensagens claras |
| **Versionamento** | Código no GitHub com histórico de commits |

---

## 📝 Possíveis Melhorias Futuras

- 🔄 Implementar interface gráfica (tkinter ou PySimpleGUI)
- 📊 Adicionar histórico de cálculos e gráficos
- 🌍 Suporte a múltiplas unidades (libras, polegadas, etc.)
- 🧪 Testes unitários com pytest
- 📱 Versão mobile com Flutter ou React Native

---

## 👨‍💻 Autor

**Adriano ABC**  
GitHub: [@adrianoabc786-prog](https://github.com/adrianoabc786-prog)

---

## 📄 Licença

Este projeto é de código aberto e disponível para fins educacionais.

---

## ✉️ Contato

Aberto a oportunidades de estágio em desenvolvimento Python e web.  
Entre em contato através do GitHub ou LinkedIn.

---

**Última atualização**: Maio de 2026
