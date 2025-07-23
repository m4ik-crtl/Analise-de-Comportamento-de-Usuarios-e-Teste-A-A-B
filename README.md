# 📱 Análise de Comportamento de Usuários e Teste A/A/B

Este projeto analisa o comportamento dos usuários em um aplicativo de vendas de alimentos, com foco em um experimento A/A/B que avalia o impacto de uma mudança de design (alteração na fonte tipográfica).

## 🔍 Objetivos

- Entender o comportamento dos usuários dentro do funil de vendas do app.
- Avaliar a integridade e qualidade dos dados coletados.
- Realizar testes estatísticos para verificar diferenças significativas entre grupos.

## 📊 Etapas Realizadas

1. **Carregamento e limpeza dos dados**
   - Remoção de duplicatas e eventos inconsistentes.
   - Conversão de colunas e tratamento de valores ausentes.

2. **Análise Exploratória**
   - Frequência de eventos por grupo e por tipo.
   - Visualizações para entender o funil de conversão.

3. **Divisão dos grupos A/A/B**
   - Grupos: 246 (A), 247 (A), 248 (B)
   - Comparação da proporção de eventos em cada etapa do funil.

4. **Teste Estatístico (Teste de Proporções Z)**
   - Comparação entre grupos para os eventos: `MainScreenAppear`, `OffersScreenAppear`, `CartScreenAppear`, `PaymentScreenSuccessful`.

## 📌 Resultados

- Foram realizados 4 testes estatísticos com nível de significância de 0,05.
- Não foram encontradas diferenças significativas entre os grupos A e B.
- Conclusão: a mudança de fonte no app **não impactou** o comportamento dos usuários.


## 🛠️ Tecnologias Utilizadas

- Python
- Pandas
- Seaborn
- Matplotlib
- Scipy

## 📬 Contato

👤 Maikon Silva  
🔗 [LinkedIn](https://www.linkedin.com/in/maikon-silva-457b98181)  

