# Buscador de localidades – DCV/COVEP

Página de acesso ao Buscador de localidades do Reconhecimento Geográfico
(localidades do SisPNCD × bairros e distritos sanitários do INCID), da
Divisão de Controle Vetorial (DCV/COVEP/SVES/SEMUS – São Luís).

- Endereço: https://covep-sves.github.io/buscador-localidades/
- O buscador roda no Google Apps Script da conta da COVEP e lê a planilha
  "Reconhecimento Geográfico – Localidades SisPNCD x INCID" a cada acesso.
- Esta página só abre o buscador em tela cheia e guarda o ícone, o atalho de
  celular e a imagem da prévia do WhatsApp.

Para trocar o endereço do app: edite `index.html`, linha `var APP_URL = '...'`.
