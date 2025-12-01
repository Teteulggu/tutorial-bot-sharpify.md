################################################################################
#                                                                              #
#      ████████╗██╗  ██╗███████╗██╗  ██╗██╗███████╗██╗   ██╗██╗   ██╗          #
#      ╚══██╔══╝██║  ██║██╔════╝██║  ██║██║██╔════╝██║   ██║██║   ██║          #
#         ██║   ███████║█████╗  ███████║██║█████╗  ██║   ██║██║   ██║          #
#         ██║   ██╔══██║██╔══╝  ██╔══██║██║██╔══╝  ██║   ██║██║   ██║          #
#         ██║   ██║  ██║███████╗██║  ██║██║██║     ╚██████╔╝╚██████╔╝          #
#         ╚═╝   ╚═╝  ╚═╝╚══════╝╚═╝  ╚═╝╚═╝╚═╝      ╚═════╝  ╚═════╝           #
#                                                                              #
#                 BOT OFICIAL — INTEGRAÇÃO SHARPIFY + DISCORD                  #
################################################################################


# 📘 SOBRE O PROJETO
# Este é o bot oficial que integra sua loja da Sharpify ao seu servidor Discord.
# Ele permite gerenciar checkouts, logs, integrações e funcionalidades automáticas.


################################################################################
# 🖼 ONDE ENCONTRAR O ID DA LOJA E O TOKEN DA API                              #
################################################################################

# Para obter suas credenciais:
# 1. Entre no painel da Sharpify.
# 2. Vá em “Configurações”.
# 3. Clique em “Bot do Discord”.
# 4. Copie:
#    - ID da Loja
#    - Token da API
#
# Esses dados serão usados no arquivo .env.



################################################################################
# 📦 1. INSTALAR DEPENDÊNCIAS                                                  #
################################################################################

# Use um dos comandos abaixo:

npm install
# ou
yarn
# ou
pnpm install



################################################################################
# 📝 2. CONFIGURAR O ARQUIVO .env                                              #
################################################################################

# O projeto vem com:
#   .env.exemple
#
# Renomeie para:
#   .env
#
# E preencha os dados:

DISCORD_TOKEN=sua_token_do_bot_aqui
DISCORD_GUILD_ID=seu_id_do_servidor_aqui
STORE_ID=seu_id_da_loja_aqui
CHECKOUT_CATEGORY_ID=seu_id_da_categoria_de_checkout_aqui
LOG_CHANNEL_ID=seu_id_do_canal_de_logs_aqui
API_TOKEN=seu_token_da_api_da_sharpify_aqui
DEFAULT_COLOR=#0051ff   # Cor HEX com 6 caracteres



################################################################################
# 💾 3. ESCOLHENDO ENTRE dist E out                                            #
################################################################################

# Você DEVE apagar UMA das pastas antes de rodar ou hospedar.

############################
# 🔵 OPÇÃO A — Usar dist   #
############################
# - A pasta dist contém a versão TypeScript.
# - Delete a pasta: out
# - O arquivo principal será:
#       dist/main.ts

############################
# 🔵 OPÇÃO B — Usar out    #
############################
# - A pasta out contém a versão JavaScript (discord.js).
# - Delete a pasta: dist
# - O arquivo principal será:
#       main.js

# ➜ Se sua hospedagem pedir "start file", informe o arquivo principal da opção escolhida.



################################################################################
# ▶️ 4. RODAR O BOT                                                            #
################################################################################

# Modo desenvolvimento:
npm run dev

# Modo produção:
npm run start



################################################################################
# ☁️ 5. HOSPEDAGEM                                                             #
################################################################################

# Suporta qualquer plataforma Node.js, como:
# - Railway
# - VPS
# - Render
# - Replit
# - Host próprio
#
# Passos:
# 1. Envie os arquivos
# 2. Configure o .env
# 3. Escolha dist ou out
# 4. Informe o arquivo principal (dist/main.ts ou main.js)
# 5. Execute:
npm start



################################################################################
# 🔗 LINKS ÚTEIS                                                               #
################################################################################

# Painel Sharpify: https://sharpify.com
# Suporte: adicione o link se quiser

################################################################################
#                           DOCUMENTAÇÃO PREMIUM                               #
################################################################################
