🚀 Automação de Disparo Inteligente no WhatsApp
📌 Descrição

Automação criada no n8n para envio de mensagens personalizadas no WhatsApp de forma escalável.

O sistema lê contatos de uma planilha, verifica se o número existe no WhatsApp, gera mensagens com IA e realiza o disparo com intervalos aleatórios para evitar bloqueios.

⚙️ Funcionalidades
Leitura de leads via Google Sheets
Validação de número no WhatsApp
Geração de mensagens com IA (personalizadas)
Disparo automático de mensagens
Delay inteligente entre envios
Controle de status (disparou, respondeu, interesse)
Registro em banco de dados (PostgreSQL)
🧠 Tecnologias utilizadas
n8n
OpenAI API
Evolution API (WhatsApp)
Google Sheets
PostgreSQL
Redis
🔄 Como funciona
Busca contatos na planilha
Filtra quem ainda não recebeu mensagem
Valida número no WhatsApp
Gera mensagem com IA
Envia mensagens com intervalos aleatórios
Atualiza status na planilha
Classifica respostas automaticamente
📈 Aplicação

Esse tipo de automação pode ser usado para:

Prospecção de clientes
Follow-up automático
Atendimento inicial
Recuperação de leads
⚠️ Observações
Necessário configurar credenciais (API, banco, etc.)
Recomendado uso de delays para evitar bloqueios
Uso voltado para automação comercial
