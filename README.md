# 🎙️ SpeechCalc — Calculadora por Voz com Python e Whisper

SpeechCalc é uma calculadora controlada por voz que utiliza reconhecimento de fala para interpretar comandos matemáticos e executar operações básicas como soma, subtração, multiplicação e divisão.

O projeto utiliza o modelo Whisper para transcrição de áudio e processamento simples de linguagem natural para identificar a intenção do usuário.

---

## 🚀 Funcionalidades

- 🎤 Captura de áudio via microfone
- 🧠 Transcrição automática com Whisper
- 🔍 Extração de números usando Expressões Regulares
- ➕ Operações suportadas:
  - Soma
  - Subtração
  - Multiplicação
  - Divisão
- 🛑 Comando de saída por voz
- ⚠️ Tratamento de divisão por zero

---

## ▶️ Como usar no Google Colab

1. Acesse o Google Colab  
2. Faça upload do arquivo `Speech-Calc.ipynb`  
3. Execute as células na ordem apresentada  
4. Quando solicitado, fale a operação desejada (ex: `somar 5 e 3`)  
5. O resultado será exibido no output da célula  

Para encerrar, diga:
```sair```

---

## 🧠 Como Funciona

O fluxo do sistema segue a seguinte arquitetura:

Áudio → Transcrição (Whisper) → Identificação de intenção → Extração de números → Execução da operação → Resultado

1. O usuário fala uma operação matemática.
2. O áudio é gravado.
3. O modelo Whisper converte o áudio em texto.
4. O sistema identifica a operação desejada.
5. Os números são extraídos da frase.
6. O cálculo é executado e exibido no terminal.

Exemplo de comando:
```
Somar 5 e 3
```

Saída:
```
Você disse:  Somar 5 e 3.
Resultado: 8.0
```

---

## 🛠️ Tecnologias Utilizadas

- Colab
- Python 3
- OpenAI Whisper
- Expressões Regulares (re)
- Manipulação básica de áudio

---

## 📌 Observações

- É necessário permitir acesso ao microfone quando solicitado.
- O modelo Whisper será carregado automaticamente.
- Funciona melhor com números falados em formato numérico (ex: "5" em vez de "cinco").

---

## 👨‍💻 Autor

Marcos

Estudande de tecnologia
