# LabFSG Backups — páginas públicas

Site estático de apresentação e privacidade do aplicativo OAuth LabFSG Backups.
Não contém credenciais, backups, código operacional, inventário ou dados de usuários.

## Publicar no GitHub Pages

1. Criar um repositório exclusivo `LabFSG-UFSC/labfsg-backups`, público para utilizar GitHub Free.
2. Enviar somente os arquivos deste diretório para a raiz do repositório.
3. Em Settings → Pages, escolher Deploy from a branch → main → /(root) → Save.
4. Aguardar o deploy e conferir os dois links pelo navegador sem login.

Não enviar o repositório proxmox-admin, `.env`, `.runtime` ou qualquer pasta operacional.

## Endereços para o Google Auth Platform

Endereços previstos para a organização indicada pelo operador; usar somente após verificar a publicação:

- Application home page: `https://labfsg-ufsc.github.io/labfsg-backups/`
- Application privacy policy link: `https://labfsg-ufsc.github.io/labfsg-backups/privacidade.html`
- Authorized domains: `labfsg-ufsc.github.io` (sem protocolo ou caminho).

O endereço definitivo é o informado em Settings → Pages. A publicação do site não muda
o status OAuth automaticamente nem garante aprovação do Google. Caso seja exigida prova
de domínio, usar a verificação de propriedade disponível no Google Search Console,
sem inserir tokens de verificação fictícios.

Conferir o nome do aplicativo e o contato antes de publicar. A política distingue OAuth
de criptografia do backup; não afirma que a rotina de backup já foi implantada.

## Manutenção

Editar os HTML e o CSS diretamente; não há build, dependências ou JavaScript.
Manter apresentação, permissões, práticas reais e data da política consistentes.
