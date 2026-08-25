# Tabela de Correlação Fiscal de Serviço 🇧🇷
### Mapeamento prático entre Reforma Tributária (IBS/CBS), LC 116, CNAE, NBS, INSS e Simples Nacional

A **Tabela de Correlação Fiscal de Serviço** é uma base de dados estruturada em planilha que relaciona as regras tributárias atuais do setor de serviços com os novos campos e exigências da Reforma Tributária.

Ela organiza em um só lugar os cruzamentos entre a atividade econômica (**CNAE**), a lista municipal de serviços (**LC 116**), a nomenclatura nacional (**NBS**), os novos códigos de classificação tributária (**cClassTrib / INDOP**), as regras de retenção de **INSS** e o enquadramento no **Simples Nacional**.

---

## ⚠️ Aviso Importante: Consulte um Profissional

> **ESTE MATERIAL É APENAS UM MODELO DE REFERÊNCIA:**  
> Esta tabela foi desenvolvida para fins de estudo, análise e apoio à estruturação de sistemas. As regras tributárias no Brasil variam de acordo com o município, regime tributário e particularidades de cada empresa.
> 
> **O conteúdo desta planilha NÃO substitui a orientação e a validação de um profissional habilitado (Contador ou Advogado Tributarista).**  
> Antes de aplicar estas regras em emissão de notas fiscais, parametrização de sistemas ou recolhimento de impostos, consulte sempre o seu contador.

---

## 📊 Estrutura da Planilha

A tabela é dividida nas seguintes abas para facilitar a consulta:

| Aba | Volume Aprox. | Conteúdo e Finalidade |
| :--- | :--- | :--- |
| **Geral** | +23.600 linhas | Visão consolidada com o cruzamento ponta a ponta de todos os códigos fiscais. |
| **Correlação IBS-CBS** | +1.500 linhas | Mapeamento dos novos campos da Reforma Tributária (`LC 116` × `NBS` × `cClassTrib` × `INDOP`). |
| **CNAE x LC 116** | +1.800 linhas | Relação direta entre o código de atividade do CNPJ (CNAE) e o item de serviço da LC 116/2003. |
| **LC 116 vs INSS e EFD-Reinf** | ~200 linhas | Identificação de serviços sujeitos à retenção de INSS (11%), cessão de mão de obra e eventos Reinf. |
| **ISS Municipal** | +1.200 linhas | Exemplos de alíquotas e códigos de serviço municipais com base legal. |
| **Simples Nacional** | +400 linhas | Enquadramento por anexo (III ou V), indicação de incidência do Fator R e alíquotas nominais. |

---

## 🎯 Para que serve

* **Desenvolvedores e Empresas de Software:** Base para implementação de regras fiscais e "de-para" em emissores de NFS-e e sistemas de gestão (ERPs).
* **Prestadores de Serviços e Empreendedores:** Material de apoio para entender os códigos vinculados à sua atividade.
* **Profissionais da Área Fiscal e Contábil:** Consulta ágil e centralizada para o dia a dia.

---

## 🚀 Como Usar

1. Baixe o arquivo `.xlsx` disponível no repositório.
2. Abra no **Microsoft Excel**, **Google Planilhas** ou **LibreOffice Calc**.
3. Utilize os filtros de coluna para buscar pelo seu código **CNAE**, item da **LC 116** ou descrição do serviço.
4. Caso precise integrar com banco de dados, exporte as abas desejadas para formato `.csv`.

---

## 🤝 Contribuições

Sugestões de melhorias e correções baseadas em publicações oficiais da Receita Federal e legislações municipais são bem-vindas via *Pull Request* ou abertura de *Issues*.

---

## 📄 Licença

Projeto aberto e gratuito para consulta, estudo e desenvolvimento.
