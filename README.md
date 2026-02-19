# Simulador de Investimento Real

Este projeto consiste em um simulador financeiro simples para análise de investimentos de longo prazo, considerando juros compostos e perda de poder de compra causada pela inflação.

O objetivo principal é oferecer uma ferramenta educacional para compreender a diferença entre crescimento nominal e crescimento real do dinheiro ao longo do tempo.

---
Link de acesso:  https://irae-cesar-brandao.github.io/simular_investimento_financeiro/ 
## Funcionalidades

- Simulação de investimentos mensais.
- Cálculo automático para:
  - 5, 10, 15, 20, 25 e 30 anos.
- Exibição de:
  - Total investido.
  - Valor nominal acumulado.
  - Valor real (descontando inflação).
  - Percentual de ganho ou perda real.
- Bloco de orientações didáticas para interpretação dos resultados.

---

## Tecnologias utilizadas

O projeto foi desenvolvido utilizando apenas tecnologias web padrão:

- **HTML5**  
  Estrutura da página e dos componentes.

- **CSS3**  
  Estilização visual, layout e responsividade básica.

- **JavaScript (Vanilla JS)**  
  Lógica matemática, cálculos financeiros e interação com o usuário.

Não há uso de frameworks ou bibliotecas externas.

---

## Base matemática

O simulador utiliza principalmente:

### Juros compostos (aportes mensais)

FV = PMT × ((1 + r)ⁿ − 1) / r

Onde:
- FV = valor final acumulado  
- PMT = valor mensal investido  
- r = taxa de juros mensal  
- n = número de meses  

### Ajuste inflacionário

Valor real = FV / (1 + inflação)ᵗ

Onde:
- t = número de anos  

---

## Finalidade do projeto

Este projeto é destinado exclusivamente para:

- Uso educacional.
- Estudo de matemática financeira.
- Simulações conceituais.
- Testes de desenvolvimento web.

Não deve ser utilizado como recomendação financeira real ou consultoria de investimentos.

---

## Aviso importante

Os resultados apresentados são apenas estimativas matemáticas baseadas nos valores informados pelo usuário.

O simulador não considera:
- Impostos.
- Taxas de administração.
- Riscos de mercado.
- Variações reais de ativos.

---

## Licença

Uso livre para fins educacionais e experimentais.
