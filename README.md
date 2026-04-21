# 🌱 FarmTech - Irrigação Inteligente (Fase 2)

## 📌 Descrição do Projeto
Neste projeto desenvolvemos um sistema de irrigação inteligente utilizando ESP32, com o objetivo de simular um ambiente agrícola automatizado.

A ideia foi trabalhar com leitura de sensores e tomar decisões simples com base nesses dados, como seria feito em um cenário real de plantação.

---

## 🧠 Funcionamento do Sistema

O sistema utiliza alguns sensores para simular condições do solo:

- Temperatura  
- Umidade  
- Luminosidade (LDR)  

Como não temos um sensor de pH disponível no simulador, utilizamos o LDR para representar essa variável.  
Assim, ao alterar a luminosidade, conseguimos simular mudanças no pH do solo, o que influencia diretamente nos níveis de NPK.

---

## ⚙️ Tecnologias Utilizadas

- ESP32  
- Linguagem C/C++  
- Wokwi (simulador online)  
- GitHub  

---

## 🧪 Lógica do Projeto

O sistema faz a leitura dos sensores e, com base nesses valores, simula o comportamento de um sistema de irrigação.

Também relacionamos o valor do LDR com o pH do solo, apenas como forma de simulação, já que o sensor real não está disponível no ambiente.

---

## 📸 Simulação no Wokwi



---

## 🎥 Vídeo do Projeto



---

## 👨‍💻 Integrantes

- Heleno Madeira  

---

## 📁 Estrutura do Projeto

- `src/` → Código do ESP32  
- `assets/` → Imagens do projeto  
- `document/` → Documentação  

---

## 🚀 Status

Projeto desenvolvido para entrega da Fase 2.
