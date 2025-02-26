# 🚀 Projeto CrewAI - Geração de Artigos Automática com Google Docs e Contagem de Tokens  

## 📖 Sobre o Projeto  

Este projeto utiliza o **CrewAI** para criar uma **equipe de agentes autônomos** que trabalham juntos para **pesquisar, escrever e editar artigos automaticamente**. Além disso, o sistema salva os artigos diretamente no **Google Docs** e realiza a **contagem de tokens** utilizados nas requisições para otimização dos custos.  

A interface interativa em **Google Colab** permite ao usuário **gerar artigos de forma intuitiva**, inserindo apenas o título desejado. O artigo final é salvo automaticamente no Google Docs e um link é gerado para acesso rápido.  

---

## 🔥 Funcionalidades  

### **✅ 1. Configuração de APIs**  
- Carregamento de chaves de API do **OpenAI** e **Serper** via Google Colab  
- Definição de variáveis de ambiente para autenticação segura  

### **✅ 2. Implementação do CrewAI**  
- Criação de **agentes autônomos** que desempenham funções específicas:  
  - **Buscador de Conteúdo** 🕵️‍♂️ → Pesquisa informações relevantes  
  - **Redator de Conteúdo** ✍️ → Escreve o artigo baseado na pesquisa  
  - **Editor de Conteúdo** 📝 → Ajusta o tom e corrige erros gramaticais  
- Definição de **tarefas sequenciais** para garantir um fluxo de trabalho organizado  

### **✅ 3. Contagem de Tokens**  
- Implementação de um **rastreamento de tokens utilizados** para cada requisição  
- Suporte para diferentes modelos da OpenAI (`gpt-3.5-turbo`, `gpt-4o`)  
- Exibição da contagem de tokens formatada em **Markdown**  

### **✅ 4. Interface Interativa no Google Colab**  
- **Entrada:** Campo de texto para inserir o título do artigo  
- **Botão "🚀 Gerar Artigo"** que inicia o processo automaticamente  
- Exibição do artigo final e contagem de tokens de forma organizada  
- O botão **permanece visível após cada artigo gerado** para facilitar novas execuções  

### **✅ 5. Integração com Google Docs**  
- Conversão do artigo gerado para **Markdown**  
- Criação automática de um **documento no Google Docs** com o conteúdo formatado  
- Geração de um **link de acesso direto** ao documento criado  

---

## 🎯 Habilidades Adquiridas  

Durante o desenvolvimento deste projeto, foram aplicadas e aprimoradas diversas habilidades técnicas:  

### **🛠️ Tecnologias Utilizadas**  
- **Python** 🐍 → Programação e manipulação de APIs  
- **CrewAI** 🤖 → Orquestração de agentes autônomos  
- **Google Colab** 🔥 → Desenvolvimento interativo na nuvem  
- **Google Docs API** 📝 → Automação de criação de documentos  
- **OpenAI API** 🤯 → Utilização de LLMs (`gpt-3.5-turbo`, `gpt-4o`)  
- **Serper API** 🌍 → Pesquisa automatizada de informações  

### **📌 Conceitos Aprendidos e Aplicados**  
✅ **Uso do CrewAI** para organizar agentes autônomos e executar tarefas sequenciais  
✅ **Integração de APIs externas** para buscas e geração de textos  
✅ **Otimização de requisições** com **contagem de tokens** para reduzir custos  
✅ **Uso de widgets interativos** no **Google Colab** para melhorar a experiência do usuário  
✅ **Automação com Google Docs** para armazenar os artigos gerados  

---

## 🚀 Como Usar  

### **1️⃣ Executando o Projeto no Google Colab**  
1. Abra o notebook no **Google Colab**  
2. Configure as chaves de API para **OpenAI** e **Serper**  
3. **Execute todas as células do notebook** para carregar os agentes e funções  
4. Digite o título do artigo na interface e clique em **"🚀 Gerar Artigo"**  
5. O artigo será criado e salvo automaticamente no **Google Docs**  
6. Um **link para o artigo** será exibido ao final do processo  

### **2️⃣ Enviando Atualizações para o GitHub**  
- Caso faça alterações no código, salve no GitHub via:  
  **`Arquivo` → `Salvar uma cópia no GitHub...`**  

---

## 🏆 Melhorias Futuras  

🔹 **Personalização do tom do artigo** (mais formal, técnico ou descontraído)  
🔹 **Escolha de modelos da OpenAI** diretamente na interface  
🔹 **Aprimoramento da pesquisa com filtros e fontes confiáveis**  
🔹 **Edição avançada do texto antes do envio ao Google Docs**  

---

## 📌 Exemplo de Uso  

🎯 **Entrada do usuário:**  
```txt
Título: "A importância da IA na Educação"
