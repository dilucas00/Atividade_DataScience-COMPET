# Análise de Salários Docentes no Brasil (2020)

Este repositório contém uma análise detalhada dos salários de docentes brasileiros em 2020, com foco em diferenças por região, dependência administrativa (estadual, privada, pública) e escolaridade. O objetivo é explorar padrões salariais, disparidades regionais e o impacto da formação superior na remuneração.

---

## 📋 Conteúdo
- **Dados**: Dataset tratado contendo informações sobre salários, carga horária, número de docentes e mais.
- **Análises**: Comparações por estado, região, rede de ensino e nível de escolaridade.
- **Visualizações**: Insights gerados a partir de estatísticas descritivas e agregações.

---

## ⚙️ Instalação
1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/salarios-docentes-2020.git
   ```
2. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```

---

## 🚀 Como Usar
1. Execute o Jupyter Notebook `main.ipynb` para reproduzir a análise completa.
2. Explore o dataset tratado em `salarios_docentes_tratados.xlsx`.
3. Principais análises incluem:
   - Salário médio por estado.
   - Remuneração para 40 horas semanais por região e dependência.
   - Impacto da formação superior nos salários.
   - Correlação entre carga horária e remuneração.

---

---

## 🔍 Principais Resultados
1. **Salário Médio por UF**  
   - **Maior salário**: DF (R$ 5.300,25)  
   - **Menor salário**: AL (R$ 2.007,63)

2. **Impacto da Escolaridade**  
   - Professores com ensino superior ganham até **46.9% mais** que os sem superior na rede pública.

3. **Disparidades Regionais**  
   - Região Sudeste possui a maior remuneração média para 40h (R$ 4.806,60), enquanto o Nordeste tem a menor (R$ 4.147,72).

4. **Relação Carga Horária x Remuneração**  
   - Correlação negativa (-0.36): cargas horárias menores estão associadas a salários/hora mais altos.

---

## 📊 Métricas Chave (Exemplo)
| Região       | Salário Médio (R$) | % Com Superior |
|--------------|--------------------|----------------|
| Sudeste      | 4.513,08           | 45.0%          |
| Nordeste     | 2.081,69           | 39.8%          |
| Centro-Oeste | 5.471,74           | 48.3%          |

---



**Nota**: Os dados brutos originais não estão incluídos por questões de licenciamento. Contate o mantenedor para mais detalhes.
