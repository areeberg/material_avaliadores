# Painel de Especialistas - AI Lifecycle Framework (Material para Avaliadores)

Este repositório contém o material de apoio para a avaliação técnica do **AI Lifecycle Framework**.

O conteúdo está estruturado em uma página web estática, contendo vídeos informativos, o resumo do framework e dossiês de cenários reais para auxiliar os especialistas na resposta ao instrumento de avaliação.

## 🚀 Visualizar Página do Projeto (GitHub Pages)

Uma vez ativado o GitHub Pages para este repositório, a página poderá ser acessada através do link:
👉 **`https://<seu-usuario-github>.github.io/material_avaliadores/`**

---

## 📊 Como gerar o Formulário de Avaliação no Google Forms

Para facilitar a criação do questionário estruturado de forma idêntica ao arquivo `03_Instrumento_Avaliacao_v2_30.md`, criamos um script de automação usando o **Google Apps Script**.

### Passo a passo para criar o Formulário automaticamente:

1. Abra o arquivo [03_Instrumento_Avaliacao_GoogleAppsScript.gs](file:///C:/Users/alexandre.mello/Repos/material_avaliadores/03_Instrumento_Avaliacao_GoogleAppsScript.gs) e copie todo o seu código.
2. Acesse o seu Google Drive (https://drive.google.com).
3. Clique em **Novo (New)** > **Mais (More)** > **Google Apps Script** (ou acesse diretamente https://script.google.com).
4. Apague qualquer código gerado automaticamente no editor de código e cole o código que você copiou do arquivo `.gs`.
5. Salve o projeto clicando no ícone do disquete (ou pressione `Ctrl + S`). Dê um nome ao seu projeto (ex: *Gerador de Formulário TRL*).
6. Clique no botão **Executar (Run)** (ícone de play ▶️).
7. Na primeira execução, o Google solicitará permissões de acesso ao seu Drive e Google Forms. Clique em "Revisar permissões", selecione sua conta e autorize (se aparecer um aviso de segurança, clique em "Avançado" e depois em "Acessar (unsafe)").
8. Após a execução terminar, os links do formulário gerado serão exibidos no console de execução (**Execution Log**) na parte inferior da tela:
   - **Link de Edição**: Use para gerenciar as respostas e alterar o visual.
   - **Link de Envio**: Use para compartilhar com os respondentes do painel de especialistas.

---

## 🛠️ Como configurar o GitHub Pages

Para publicar esta página no GitHub Pages, siga os passos abaixo:

1. Faça o **push** deste repositório para o seu GitHub.
2. No GitHub, acesse a aba **Settings** (Configurações) do repositório.
3. No menu lateral esquerdo, clique em **Pages** (sob a seção *Code and automation*).
4. Em **Build and deployment**:
   - Sob **Source**, selecione **Deploy from a branch**.
   - Sob **Branch**, selecione a branch principal (ex: `main` ou `master`) e a pasta raiz `/ (root)`.
   - Clique em **Save**.
5. Aguarde alguns instantes. O link de publicação aparecerá no topo da página de configurações do GitHub Pages.

---

## 📁 Estrutura de Arquivos

* `index.html`: A página principal do Painel de Especialistas (cópia de `guia_avaliador.html` para compatibilidade com o GitHub Pages).
* `guia_avaliador.html`: O arquivo HTML original da página de avaliação.
* `.nojekyll`: Arquivo de configuração para desativar o Jekyll no GitHub Pages, garantindo que todos os arquivos sejam servidos de forma rápida e direta.
* `DESIGN.md`: Documentação de referência visual e identidade de design do painel.
* `03_Instrumento_Avaliacao_v2_30.md`: O arquivo Markdown contendo a estrutura textual da avaliação.
* `03_Instrumento_Avaliacao_GoogleAppsScript.gs`: O script de automação para geração do formulário no Google Forms.