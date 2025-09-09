🤖 Automação de Publicação no Instagram com n8n

Este fluxo em n8n automatiza a criação e publicação de conteúdos no Instagram a partir de ideias recebidas via WhatsApp.
Ele utiliza IA (OpenAI GPT) para gerar textos e imagens, armazena os resultados no Supabase e organiza o ciclo de execução de forma totalmente automatizada.

----------------------------------------------------------------------------------------------------------------

🚀 Funcionalidades

📲 Entrada via WhatsApp: o usuário envia o tema/assunto da publicação.

🧠 Geração de Ideias: o fluxo usa GPT para criar diferentes ideias de conteúdo.

✍️ Criação de Publicações: a IA desenvolve textos prontos para postagens.

🖼️ Geração de Imagens: criação automática de imagens com base no conteúdo.

☁️ Upload em Bucket: os arquivos são enviados para armazenamento.

🗄️ Registro no Supabase: cada publicação é salva com metadados.

🔄 Loop Automático: controle de execução com intervalos configurados.

----------------------------------------------------------------------------------------------------------------

📂 Estrutura do Fluxo

WhatsApp Trigger → Recebe o tema da publicação.

Criar Ideias (GPT) → Sugere ideias de conteúdo.

Split Out + Loop → Processa cada ideia individualmente.

Criar Publicações (GPT) → Gera textos prontos para uso.

Geração de Imagem (OpenAI) → Produz artes para a publicação.

Upload em Bucket → Envia as imagens para armazenamento.

Supabase → Registra título, texto e imagem.

Intervalo → Aguarda antes de continuar o ciclo.

----------------------------------------------------------------------------------------------------------------

🛠️ Tecnologias

Tecnologia	Função

n8n	Orquestração de automações

OpenAI GPT	Geração de ideias e textos

OpenAI Image API	Criação de imagens personalizadas

Supabase	Armazenamento e banco de dados

WhatsApp	Canal de entrada dos temas

----------------------------------------------------------------------------------------------------------------

▶️ Como Usar

Importe o arquivo Automação_Publicação_Instagram.json no seu n8n.

Configure as credenciais necessárias:

OpenAI API Key

WhatsApp Trigger

Supabase

Bucket/Storage

Ative o fluxo no n8n.

Envie uma mensagem no WhatsApp com o tema da publicação.

O fluxo vai:

Gerar ideias

Criar textos

Produzir imagens

Salvar no banco

Deixar pronto para publicação no Instagram

----------------------------------------------------------------------------------------------------------------

📊 Exemplo de Saída

Texto Gerado:
"Descubra como a automação pode transformar sua produtividade!"

Imagem:
Criada automaticamente com base no texto.
