AMBU360 — PUBLICAÇÃO NO COOLIFY / MODTRAX

Dominio principal: https://www.ambu360.com.br
WhatsApp: +55 (51) 99113-4545, configurado em index.html

ARQUIVOS: index.html, Dockerfile, nginx.conf

PUBLICAR:
1. Coloque os tres arquivos NA RAIZ de um repositorio Git privado (GitHub/GitLab) ou de um repositorio Git suportado pelo Coolify.
2. No Coolify crie NOVA Application no servidor da VPS Modtrax; Build: Dockerfile; Dockerfile path: /Dockerfile; porta interna: 80. Nao substitua o ERP.
3. No provedor DNS de ambu360.com.br crie/ajuste A para www apontando ao IP PUBLICO do servidor de destino no Coolify; nao use IP ficticio.
4. Coolify > Application > Domains: adicione https://www.ambu360.com.br com porta interna 80.
5. Confirme que o proxy da VPS esta ativo e 80/443 estao acessiveis; faca deploy e valide HTTPS.
6. Opcional: configure @ (ambu360.com.br) no DNS e no Coolify com redirecionamento permanente ao www sem criar conflito.
7. Teste hero, menu mobile, contato WhatsApp, pagina e certificado HTTPS.

PENDENCIA: O link de politica de privacidade foi ocultado ate ser fornecida uma URL verdadeira. Preparar/publicar politica adequada antes de coletar dados diretamente no site.
O HTML e estatico. O deploy nao altera o backend da plataforma Ambu360.
