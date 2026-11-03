# 📊 Cálculo de Métricas de Avaliação de Aprendizado

Projeto desenvolvido para o desafio de projeto da **DIO (Digital Innovation One)** no módulo de avaliação de modelos de Machine Learning.

---

## 📌 Descrição do Desafio

O propósito deste projeto é implementar em Python as fórmulas matemáticas fundamentais para mensurar o desempenho de modelos preditivos de classificação com base nos dados obtidos a partir de uma Matriz de Confusão.

### Métricas Implementadas

| Métrica | Conceito | Fórmula |
| :--- | :--- | :--- |
| **Sensibilidade (*Recall*)** | Capacidade de identificar instâncias positivas reais. | $$\text{Sensibilidade} = \frac{\text{VP}}{\text{VP} + \text{FN}}$$ |
| **Especificidade** | Capacidade de identificar instâncias negativas reais. | $$\text{Especificidade} = \frac{\text{VN}}{\text{FP} + \text{VN}}$$ |
| **Acurácia** | Taxa global de acertos do modelo sobre todas as classes. | $$\text{Acurácia} = \frac{\text{VP} + \text{VN}}{N}$$ |
| **Precisão** | Proporção de predições positivas que foram corretas. | $$\text{Precisão} = \frac{\text{VP}}{\text{VP} + \text{FP}}$$ |
| **F-score (*F1-Score*)** | Média harmónica balanceando Precisão e Sensibilidade. | $$\text{F-score} = 2 \times \frac{P \times S}{P + S}$$ |

> **Legenda:**  
> - $\text{VP}$: Verdadeiros Positivos  
> - $\text{VN}$: Verdadeiros Negativos  
> - $\text{FP}$: Falsos Positivos  
> - $\text{FN}$: Falsos Negativos  
> - $N$: Total de amostras ($\text{VP} + \text{VN} + \text{FP} + \text{FN}$)
