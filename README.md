# 📌 Chat Inteligente com PDFs - Azure AI Foundry

## 📖 Visão Geral
Este projeto tem como objetivo criar um **chat interativo** que responde com base no conteúdo de arquivos PDF. Utilizando conceitos de **IA generativa**, **embeddings** e **buscas vetorizadas**, desenvolvemos um sistema que **entende, processa e responde perguntas** a partir de documentos específicos.

Com essa abordagem, é possível criar um **modelo personalizado de assistência virtual**, focado em um conjunto de informações proprietárias, sem depender unicamente do conhecimento geral de modelos pré-treinados.

## 🎯 Cenário
Imagine que você é um estudante de **Engenharia de Software**, prestes a escrever seu **Trabalho de Conclusão de Curso (TCC)**. Para isso, você precisa revisar e correlacionar diversos **artigos científicos**.

Entretanto, à medida que acumula mais documentos, torna-se cada vez mais difícil **extrair informações relevantes** e conectar ideias entre diferentes textos. Para solucionar esse problema, decidimos utilizar **inteligência artificial** para criar um sistema de busca inteligente que:

✔️ **Interprete PDFs** automaticamente.
✔️ **Organize informações** de forma estruturada.
✔️ **Gere respostas contextuais** fundamentadas nos arquivos carregados.

## 🎯 Objetivo
O projeto tem os seguintes objetivos:

✅ **Carregar arquivos PDF** contendo informações relevantes para estudo ou pesquisa.
✅ **Implementar um sistema de busca vetorial** para indexação e recuperação de informações dos PDFs.
✅ **Utilizar IA generativa** para gerar respostas baseadas no conteúdo dos documentos carregados.
✅ **Desenvolver um chat interativo** onde seja possível realizar perguntas e obter respostas precisas e contextualizadas.

## 🏗️ Ferramentas Utilizadas
Para construir o chat inteligente, utilizamos:

🔹 **Azure AI Search** → Para indexação e busca vetorizada nos documentos PDF.
🔹 **Azure OpenAI Foundry** → Para geração de respostas contextuais com IA generativa.
🔹 **Python** → Para integração entre os serviços e manipulação dos arquivos.
🔹 **Streamlit** → Para criar a interface interativa do chat.

## 🚀 Como Configurar o Projeto

1️⃣ Clone este repositório:
```bash
    git clone https://github.com/seu-usuario/chat-inteligente-pdf.git
```

2️⃣ Instale as dependências:
```bash
    pip install -r requirements.txt
```

3️⃣ Configure suas credenciais do **Azure AI Search** e **Azure OpenAI Foundry** no arquivo `.env`:
```env
    AZURE_SEARCH_ENDPOINT= "URL_DO_AZURE_SEARCH"
    AZURE_SEARCH_KEY= "SUA_CHAVE_DO_AZURE_SEARCH"
    AZURE_OPENAI_ENDPOINT= "URL_DO_AZURE_OPENAI"
    AZURE_OPENAI_KEY= "SUA_CHAVE_DO_AZURE_OPENAI"
```

4️⃣ Execute a aplicação:
```bash
    streamlit run app.py
```

## 📌 Resultados e Insights
Após implementar esse projeto, aprendemos que:

🔹 A **busca vetorial** torna a recuperação de informações mais eficiente e precisa.
🔹 Modelos de **IA generativa** podem fornecer respostas contextuais com base em documentos específicos.
🔹 A combinação de **Azure AI Search + OpenAI Foundry** permite criar assistentes personalizados para diferentes domínios.

## 📷 Prints da Aplicação
*(Adicione aqui prints do seu chat em funcionamento)*

## 🏆 Conclusão
Este projeto mostra como podemos aplicar **IA Generativa** e **busca vetorial** para resolver problemas reais. A possibilidade de extrair conhecimento de documentos de forma automatizada pode ser aplicada em diversas áreas, como educação, jurídico e pesquisa acadêmica.

Fique à vontade para contribuir e melhorar este projeto! 🚀
