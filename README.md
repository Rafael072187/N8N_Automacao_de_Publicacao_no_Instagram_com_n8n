<center>
  <h1 style="font-size:2.4em; margin-bottom:0.1em;">📸 N8N — Automação de Publicação no Instagram</h1>
  <p style="margin-top:0.2em; font-size:1.05em; color:#555;">
    Automação inteligente que cria e publica conteúdos no Instagram a partir de ideias recebidas via WhatsApp, integrando IA, Supabase e geração de imagens com OpenAI.
  </p>
  <p>
    <a href="https://github.com/Rafael072187/N8N_Automacao_de_Publicacao_no_Instagram_com_n8n" style="background:#24292F;color:#fff;padding:8px 14px;border-radius:8px;text-decoration:none;font-weight:600;">
      🔗 Repositório no GitHub
    </a>
  </p>
</center>

<hr>

## 🧭 **Tabela de Conteúdos**
- Descrição  
- Instalação  
- Uso  
- Tecnologias  
- Como contribuir  
- Autor  
- Observações  

---

## 📘 **Descrição**
<details>
  <summary><b>Resumo</b></summary>
  Este projeto é um fluxo criado no **n8n** que automatiza a criação e publicação de conteúdos no **Instagram** com o apoio de **Inteligência Artificial (OpenAI GPT)**.  
  Ele recebe temas via **WhatsApp**, gera textos e imagens automaticamente, armazena os resultados no **Supabase** e organiza o processo completo até a publicação.  
  Ideal para **criadores de conteúdo, equipes de marketing e empresas** que desejam manter consistência e produtividade nas redes sociais.
</details>

---

## ⚙️ **Instalação**
<details>
  <summary><b>Passo a passo (Linux / macOS / Windows)</b></summary>

1. Clone o repositório:
   ```bash
   git clone https://github.com/Rafael072187/N8N_Automacao_de_Publicacao_no_Instagram_com_n8n.git
   cd N8N_Automacao_de_Publicacao_no_Instagram_com_n8n
Instale o n8n:

bash
Copiar código
npm install -g n8n
Inicie o n8n:

bash
Copiar código
n8n start
Importe o fluxo principal:

Arquivo: Automação_Publicação_Instagram.json

No painel do n8n, acesse Import Workflow e selecione o arquivo.

Configure as credenciais:

OpenAI API Key

Supabase (URL e Chave API)

WhatsApp Trigger (Webhook)

Bucket/Storage

Ative o fluxo e teste com uma mensagem de tema via WhatsApp.

</details>
🖥️ Uso
<details> <summary><b>Como usar o projeto</b></summary>
O usuário envia uma mensagem no WhatsApp com o tema da publicação.

O n8n aciona o fluxo que:

Gera ideias de postagens via GPT;

Cria textos e descrições otimizadas;

Gera automaticamente as imagens correspondentes;

Salva o conteúdo no Supabase;

Prepara o material para postagem no Instagram.

O sistema organiza o ciclo de execução de forma autônoma, com intervalos configuráveis.

</details> <p align="center" style="margin-top:14px;"> <img src="https://cdn-icons-png.flaticon.com/512/1384/1384063.png" width="90" alt="ícone ilustrativo"> <br> <i>Fluxo automatizado para criação e publicação de postagens com IA.</i> </p>
🛠️ Tecnologias
<details> <summary><b>Stack principal</b></summary>
n8n → Orquestração da automação

OpenAI GPT → Geração de ideias e textos

OpenAI Image API → Criação automática de imagens

Supabase → Armazenamento e banco de dados

WhatsApp API → Canal de entrada para temas

</details>
🤝 Como contribuir
<details> <summary><b>Guia rápido</b></summary>
Faça um fork do repositório

Crie uma branch:

bash
Copiar código
git checkout -b feature/nova-feature
Realize suas alterações e commit:

bash
Copiar código
git commit -m "feat: adiciona nova automação de publicação"
git push origin feature/nova-feature
Abra um Pull Request descrevendo as melhorias.

</details>
👤 Autor
<details> <summary><b>Contatos</b></summary> <p> <b>Rafael Bittencourt de Araújo</b> — desenvolvedor do projeto.<br> GitHub: <a href="https://github.com/Rafael072187" target="_blank">github.com/Rafael072187</a> </p> </details>
📝 Observações
✅ Projeto voltado à automação criativa e empresarial para marketing digital.
🔧 Pode ser expandido para integração com outras redes (TikTok, LinkedIn).
⚠️ Garanta a configuração correta das chaves de API e permissões antes da execução.

<p align="center" style="margin-top:18px;"> <a href="https://github.com/Rafael072187/N8N_Automacao_de_Publicacao_no_Instagram_com_n8n" style="background:#0b5fff;color:#fff;padding:10px 18px;border-radius:8px;text-decoration:none;font-weight:600;"> Ver repositório </a> </p> <p align="center" style="margin-top:14px;color:#666;"> Estrutura gerada automaticamente com base no repositório analisado. </p> ```






