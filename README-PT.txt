ROSSANO AVENTURA FICHIS — ATUALIZAÇÃO (versão 2.0.0)

COMO TESTAR NO COMPUTADOR
1. Instala o Node.js 18 ou mais recente.
2. Abre uma janela de comandos nesta pasta e escreve:  npm install   e depois:  npm start
3. Abre http://localhost:3000 no navegador.
   (No Windows podes usar INICIAR_SERVIDOR_WINDOWS.bat.)

COMO PUBLICAR (sem mudar os endereços)
- Servidor (Render): substitui index.html, server.js e package.json no teu repositório do GitHub
  ligado ao serviço "rossano-aventura-fichis". O Render publica sozinho. O render.yaml não mudou.
  Endereço mantido: https://rossano-aventuras-fichis.onrender.com
- Site (Netlify): carrega o novo index.html no site manicreft-aventuras. Endereço mantido.
- No menu "Multijogador" do jogo o endereço do servidor já vem preenchido.

O QUE MUDOU NESTA VERSÃO
- Blocos: corrigida a confusão de números de blocos (a lava aparecia como água, o "Escudo" era
  água, tochas/carvão/ferro tinham texturas trocadas, receitas davam itens errados).
- Água: uma fonte retirada volta só uma vez, só no mesmo sítio e nunca por cima de construções.
  Nadar: dentro de água andas mais devagar e sobes com o salto.
- Minerais: diamante, ouro, cobre, vibranium (fundo), mármore, basalto, pedra musgosa, cristais
  roxos e quartzo. Bloco Negro só dentro de grutas/minas. Minerais minerados regressam ao amanhecer.
- 11 dimensões com terreno, céu, luz, criaturas, recursos e missões próprios (Mundo Pré-Histórico
  foi trocado por Mundo das Ruínas Antigas). Plataforma de chegada segura, portal de regresso,
  botão "Regressar" sempre visível e resgate automático se caíres no vazio.
- Multijogador: servidor Render mantido; reconexão automática; mais blocos por sala; alturas das
  dimensões aceites; gravação do mundo menos pesada.

LIMITES CONHECIDOS (ver mensagem final do assistente)
