 
# Efetividade de Duas Estratégias de Ensino  
## Módulo 19 – Estatística Aplicada

Este projeto avalia se existe diferença significativa no desempenho médio dos alunos submetidos a duas estratégias de ensino de matemática, utilizando o **Teste Z**.

---

## 🎯 Hipóteses

- **Hipótese nula (H₀):** A média das notas dos alunos na Estratégia A é igual à média das notas dos alunos na Estratégia B.  
- **Hipótese alternativa (H₁):** A média das notas na Estratégia B é maior do que a média das notas na Estratégia A.

➡️ O teste é **unilateral à direita**, pois estamos interessados apenas em verificar se a Estratégia B resulta em notas significativamente maiores.

---

## 📊 Dados

- **Amostra A:** 50 alunos (Estratégia A).  
- **Amostra B:** 50 alunos (Estratégia B).  
- As notas foram simuladas com distribuição normal para fins de demonstração:

```python
np.random.seed(0)
amostra_A = np.random.normal(loc=70, scale=10, size=50)
amostra_B = np.random.normal(loc=75, scale=12, size=50)

---

## 🧮 Estatísticas Descritivas
Média Estratégia A: 71.41
Variância Estratégia A: 129.27
Média Estratégia B: 74.75
Variância Estratégia B: 110.47

---

## 🔧 Requisitos
Instale as dependências com:

bash
pip install -r requirements.txt

---
### 👩‍💻 Autoria
Projeto desenvolvido por Maria Santos como parte do curso de Data Science da EBAC.

