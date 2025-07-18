# Curso Python para Análise de Dados Agrícolas - UNICAMP

## 📚 Sobre o Curso

Este repositório contém o material completo do curso de Python voltado para análise de dados agrícolas brasileiros, desenvolvido especialmente para estudantes de engenharia da UNICAMP. O curso tem duração de 1h20 e foca na aplicação prática do Python para análise de dados reais do setor agrícola.

## 🎯 Objetivos do Curso

- Introduzir conceitos fundamentais de Python para análise de dados
- Demonstrar aplicações práticas em dados agrícolas brasileiros
- Capacitar estudantes para usar ferramentas de ciência de dados
- Apresentar técnicas de visualização e machine learning

## 📁 Estrutura do Repositório

```
├── Curso_Python_Analise_Agricola_Unicamp.ipynb    # Notebook principal do curso
├── dataset_colheita_cultura.csv.csv               # Dataset agrícola brasileiro
└── README.md                                       # Este arquivo
```

## 📊 Dataset Utilizado

O curso utiliza dados reais de produção agrícola brasileira:

- **Fonte**: IBGE (Instituto Brasileiro de Geografia e Estatística)
- **Período**: 2010-2023 (14 anos)
- **Estados**: 28 estados brasileiros + dados nacionais
- **Culturas**: Arroz, Cana-de-açúcar, Cevada, Feijão, Milho, Soja, Trigo
- **Total de registros**: 2.070 registros limpos

### Estrutura dos Dados
```
├── estados_brasileiros: Nome do estado
├── ano: Ano da produção (2010-2023)
├── arroz: Produção de arroz (toneladas)
├── cana_de_acucar: Produção de cana-de-açúcar (toneladas)
├── cevada: Produção de cevada (toneladas)
├── feijao: Produção de feijão (toneladas)
├── milho: Produção de milho (toneladas)
├── soja: Produção de soja (toneladas)
└── trigo: Produção de trigo (toneladas)
```

## 📖 Conteúdo do Curso

### 1. **Introdução ao Python e Mercado**
- Por que Python na engenharia?
- Estatísticas de uso do Python

### 2. **Configuração do Ambiente**
- Google Colab setup
- Importação de bibliotecas essenciais

### 3. **Carregamento e Exploração de Dados**
- Leitura de CSV com pandas
- Primeiras análises exploratórias
- Tipos de dados explicados em detalhes

### 4. **Limpeza e Preparação**
- Tratamento de valores ausentes
- Filtragem de dados
- Conversão de tipos

### 5. **Análise Estatística Básica**
- Estatísticas descritivas
- Identificação de outliers
- Análises por estado e cultura

### 6. **Visualização de Dados**
- Gráficos de linha temporal
- Heatmaps de correlação
- Gráficos de barras comparativos

### 7. **Análise Avançada**
- Rankings de produção por estado
- Análise de crescimento temporal
- Identificação de padrões

### 8. **Machine Learning Introdutório**
- Regressão linear para predição
- Clustering de estados similares
- Interpretação de resultados

### 9. **Casos de Uso Práticos**
- Análise de safras
- Comparação regional
- Tendências do agronegócio

### 10. **Conclusões e Próximos Passos**
- Recap dos conceitos aprendidos
- Recursos para aprofundamento

## 🚀 Como Executar

### Opção 1: Google Colab (Recomendado)
1. Acesse [Google Colab](https://colab.research.google.com/)
2. Faça upload do notebook `Curso_Python_Analise_Agricola_Unicamp.ipynb`
3. Faça upload do arquivo `dados_formato_long_sem_zeros.csv`
4. Execute as células sequencialmente

### Opção 2: Ambiente Local
```bash
# Clone o repositório
git clone https://github.com/MilaGabs/unicamp-python-agricultural-analysis.git

# Instale as dependências
pip install pandas matplotlib seaborn numpy scikit-learn jupyter

# Execute o Jupyter Notebook
jupyter notebook Curso_Python_Analise_Agricola_Unicamp.ipynb
```

## 📦 Dependências

```python
pandas>=1.3.0
matplotlib>=3.4.0
seaborn>=0.11.0
numpy>=1.21.0
scikit-learn>=1.0.0
```

## 👨‍🏫 Sobre o Instrutor

**Background Profissional:**
- Especialista em desenvolvimento mobile na John Deere
- Experiência com Cloud Computing (AWS)
- Desenvolvimento de APIs
- Aplicação de tecnologia no agronegócio

## 🌾 Por que Dados Agrícolas?

O agronegócio brasileiro representa:
- Principal setor exportador do país
- Campo fértil para aplicação de tecnologia e análise de dados
- Relevância direta para estudantes de engenharia

## 📈 Resultados de Aprendizagem

Ao final do curso, os estudantes serão capazes de:

✅ Configurar ambiente Python para análise de dados  
✅ Carregar e explorar datasets reais  
✅ Aplicar técnicas de limpeza de dados  
✅ Criar visualizações informativas  
✅ Realizar análises estatísticas básicas  
✅ Implementar algoritmos simples de machine learning  
✅ Interpretar resultados e gerar insights  

## 🔗 Recursos Adicionais

- [Documentação oficial do Pandas](https://pandas.pydata.org/docs/)
- [Matplotlib Gallery](https://matplotlib.org/stable/gallery/)
- [Seaborn Tutorial](https://seaborn.pydata.org/tutorial.html)
- [Scikit-learn User Guide](https://scikit-learn.org/stable/user_guide.html)

## 📄 Licença

Este material é disponibilizado para fins educacionais. Os dados utilizados são de domínio público (IBGE).

## 🤝 Contribuições

Sugestões e melhorias são bem-vindas! Abra uma issue ou envie um pull request.

---

**Desenvolvido para a UNICAMP | Análise de Dados Agrícolas com Python**
