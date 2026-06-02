# Aula 1 — Limpeza de Dados com Agente de IA

A primeira etapa do projeto consiste em utilizar um **agente de IA** para analisar, limpar, padronizar e preparar os dados brutos do sistema de streaming.  
O objetivo é transformar os datasets sujos em arquivos consistentes, confiáveis e prontos para modelagem no Power BI.

---

# Objetivos da Aula

- Compreender o papel de um **agente de IA** na engenharia de dados  
- Identificar problemas comuns em datasets reais  
- Aplicar técnicas de limpeza e padronização  
- Gerar arquivos finais consistentes para uso no Power BI  
- Documentar o processo de transformação  

Abaixo a lista dos arquivos sujos no formato .csv

[📥 Baixar clientes.csv](clientes.csv)
[📥 Baixar planos.csv](planos.csv)
[📥 Baixar assinaturas.csv](assinaturas.csv)
[📥 Baixar pagamentos.csv](pagamentos.csv)
[📥 Baixar catalago.csv](catalogo.csv)
[📥 Baixar consumo.csv](consumo.csv)

# Passo 1

- Criar uma conta no ChatGPT (OpenIA - caso não tenha uma) link: https://chatgpt.com/
- Criar um novo projeto

# Passo 2

- Definir um nome para o agente IA
- Definir o papel deste agente IA (instruções principais a serem realizadas pelo agente IA)

Observações Importantes:
  - Ser claro e objetivo
  - Definir explicitamente o papel do agente
  - Dizer o que o agente deve e não deve fazer
  - Informar o que deve ser entregue ao final
  - Evitar instruções técnicas, contraditórias ou genéricas execivas
  - Solicitar explicações curtas das ações realizadas

Um exemplo de uma instrução a ser passado para o agente:

"Você é um engenheiro de dados especializado em limpeza, padronização e preparação de datasets. Sua função é analisar arquivos CSV enviados pelo usuário, identificar problemas de qualidade de dados e aplicar correções de forma estruturada.

Suas responsabilidades incluem: Padronizar datas, textos, categorias e formatos, Remover duplicados e corrigir inconsistências, Tratar valores faltantes de forma coerente, Criar novas colunas derivadas quando solicitado, Explicar brevemente cada etapa realizada.

Regras importantes: Não invente dados, Não altere colunas sem necessidade, Sempre mantenha a estrutura original do dataset, Sempre gere o resultado final em formato CSV. 

Objetivo final: Entregar um dataset limpo, padronizado e pronto para análise em BI, Python ou SQL."


# Passo 3

- Enviar os arquivos .csv um a um para serem processados pelo agente
- Analisar o processamento realizado
- Verificar os resultados gerados
- Produzir um relatório detalhado contendo:
--   Os procedimentos realizados,
--   Os resultados obtidos exemplicando a comparação entre o antes e depois do processamento realizado pelo agente IA.
  
- Postar o relatório no formato **PDF** no Portal LMS Canvas.
- Salvar os arquivos em seu computador para serem utilizados em nosso prócimo encontro em 15/10/2016 no qual iremos construir o dashboard utilizando o Power Bi.
