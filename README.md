# 🔊 Simulação de Terapia Sonodinâmica com k-Wave

Este projeto realiza simulações em MATLAB utilizando a toolbox **k-Wave** para investigar a viabilidade da **terapia sonodinâmica**. Através da modelagem da propagação de ondas ultrassônicas em diferentes condutores, busca-se entender **a área e a profundidade de atuação do som na pele**, o que pode impactar diretamente a eficácia da terapia.

---

## 🎯 Objetivo

Analisar o impacto de diferentes **materiais condutores** na propagação de ondas ultrassônicas aplicadas sobre a pele, com o foco em:

- Avaliar a **viabilidade da terapia sonodinâmica**
- Estudar a **profundidade de penetração** e **área de atuação**
- Comparar os efeitos com e sem o uso de **gel de acoplamento**
- Investigar o comportamento de **condutores com diferentes geometrias** (cônicos e cúbicos)

---

## 🧰 Ferramentas Utilizadas

- **MATLAB**
- [**k-Wave Toolbox**](https://www.k-wave.org/) (simulações de propagação acústica no domínio do tempo)

---

## 📂 Scripts incluídos

- `conico_com_gel.m`  
  Simulação com condutor **cônico** e aplicação de **gel de acoplamento**.

- `Teste_condutor_conico.m`  
  Simulação com condutor **cônico**, **sem gel**.

- `Teste_condutor_cubico.m`  
  Simulação com condutor **cúbico**, para fins de comparação.

---

## ⚙️ Requisitos

- MATLAB R2021a ou superior
- k-Wave Toolbox instalado
- Recomenda-se também:
  - Signal Processing Toolbox
  - Image Processing Toolbox

---

## 🚀 Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   cd seu-repositorio
