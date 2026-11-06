MINHA MÚSICA — PROTÓTIPO PWA

O que é:
- Um protótipo de player instalável no iPhone pela opção "Adicionar à Tela de Início" do Safari.
- Busca arquivos de áudio publicados no Wikimedia Commons.
- Mostra artista/crédito, licença identificada e link para a página de detalhes.
- Reproduz o arquivo selecionado no player.

IMPORTANTE:
- Este protótipo NÃO é o Spotify e não contém o catálogo comercial do Spotify.
- Nem todo áudio encontrado é música comercial; cada arquivo tem sua própria licença.
- A integração com Alexa ainda NÃO está implementada. Uma Skill exige configuração no Amazon Developer Console, hospedagem de um backend e uma fonte de áudio compatível com as regras da Alexa.
- Para instalar como PWA, os arquivos precisam estar hospedados em um endereço HTTPS. Abrir index.html diretamente não instala o app.
- O iOS pode impor limitações a reprodução em segundo plano em experiências web; isso precisa ser testado no aparelho.

Como hospedar gratuitamente:
1. Crie uma conta em um serviço de hospedagem estática com plano gratuito, como GitHub Pages.
2. Publique todos os arquivos desta pasta no repositório.
3. Abra o endereço HTTPS no Safari do iPhone.
4. Toque em Compartilhar > Adicionar à Tela de Início.

Próximas etapas:
1. Hospedar e testar no iPhone.
2. Melhorar busca, biblioteca e playlists.
3. Definir uma fonte musical licenciada e compatível com Alexa.
4. Só então implementar e testar a Skill.
