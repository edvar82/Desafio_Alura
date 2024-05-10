# Desafio Alura - Projeto de Conclusão

## 🚀 Introdução

Este projeto foi desenvolvido como parte do desafio final da Imersão Inteligência Artificial da Alura e do Google.


## 🗒️ Descrição

Este projeto foi desenvolvido para facilitar o gerenciamento de formulários escolares, automatizando tarefas administrativas. Ao utilizar tecnologias de visão computacional e processamento de linguagem natural, o sistema extrai e organiza informações dos formulários preenchidos pelos responsáveis dos alunos. Isso simplifica o processo de coleta de dados, reduzindo erros e aumentando a eficiência do trabalho administrativo nas escolas.

## 💡 Ideia

A ideia por trás deste projeto é resolver um problema enfrentado na empresa, relacionado ao processamento de formulários escolares enviados pelos responsáveis dos alunos.

## ❗ Problema

Os formulários enviados são geralmente escaneados ou fotografados e convertidos em PDF, resultando em documentos de difícil processamento. Além disso, o preenchimento manual e a mesclagem dos arquivos geram dificuldades adicionais para a administração.

## ✅ Solução

A solução proposta divide os PDFs mesclados em páginas individuais, converte cada página em imagem e utiliza a API de visão computacional Gemini Pro Vision para processamento. Em seguida, são extraídas informações estruturadas dos formulários, enviadas à API de texto do Gemini para organização. Os dados são então estruturados em um dataframe para facilitar o acesso e revisão.

## 🎉 Benefício

Esta solução simplifica e acelera o trabalho da administração, substituindo processos manuais por automação. Apesar de possíveis erros na extração de informações, o processo de revisão é facilitado e os riscos de inserção de dados incorretos são reduzidos.

## 📚 Tecnologias Utilizadas

- Python
- Gemini Pro Vision API
- Gemini API de Texto
- Pandas
- Transformação de PDF em imagem (pdf2image)
- Bibliotecas de processamento de imagens (ex: Pillow)

## 🔗 Link

[Link do projeto no Google Colab](https://colab.research.google.com/drive/1sLJqdqnMNHBcQewbEltAU9jj-kw_43_m?usp=sharing6)