# 🏠 Análise de Dados do Airbnb - Rio de Janeiro

## 📌 Visão Geral do Projeto
Este projeto tem como objetivo **limpar, transformar e analisar dados de anúncios do Airbnb no Rio de Janeiro**, visando entender melhor o mercado de hospedagem na cidade.  
A análise busca **identificar padrões, tendências e insights relevantes** que podem auxiliar tanto hóspedes quanto anfitriões.

---

## 🔎 Principais Análises Realizadas

### 1. Exploração dos Dados
- Distribuição de preços dos imóveis por bairro
- Identificação de outliers em valores de diária
- Categorias mais comuns de hospedagem (quartos, casas, apartamentos, etc.)
- Estatísticas descritivas dos anúncios

### 2. Correlações e Tendências
| Variáveis                  | Observação |
|-----------------------------|------------|
| Preço vs Localização        | Diferença significativa entre bairros turísticos e periféricos |
| Preço vs Tipo de Imóvel     | Casas inteiras tendem a ser mais caras que quartos privados |
| Número de avaliações vs Preço | Anúncios mais baratos possuem maior número de avaliações |

### 3. Insights por Bairros
| Bairro           | Preço Médio (R$) | Tipo Mais Comum |
|------------------|------------------|-----------------|
| Copacabana       | 350              | Apartamento     |
| Ipanema          | 420              | Apartamento     |
| Barra da Tijuca  | 300              | Casa inteira    |
| Centro           | 180              | Quarto privado  |

---

## 📊 Principais Resultados

✅ **Bairros mais caros**: Ipanema e Copacabana concentram os maiores valores médios de diárias.  
📉 **Preços acessíveis**: Centro e Tijuca apresentam opções mais baratas.  
⭐ **Hospedagens populares**: Apartamentos dominam o mercado carioca.  
📈 **Tendência**: imóveis próximos à orla possuem maior demanda e avaliações mais altas.  

---

## 🛠️ Como Executar o Projeto

### 1. Instalação
Clone o repositório e instale as bibliotecas necessárias:

```bash
pip install pandas numpy matplotlib seaborn
