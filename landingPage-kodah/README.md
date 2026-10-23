# Kodah — Landing page

Landing page estática em HTML, CSS e JavaScript puro. Não requer build nem instalação de dependências.

## Executar localmente

Abra `index.html` no navegador ou sirva a pasta com um servidor HTTP local. Para validar caminhos e comportamento, prefira um servidor local em vez de abrir o arquivo diretamente.

## Publicação

Envie o conteúdo desta pasta para a raiz pública da hospedagem (por exemplo, `public_html` em hospedagem compartilhada ou a pasta publicada pelo provedor estático). Preserve a estrutura `assets/` e `src/`.

## Antes de publicar

- Confirme os dados reais de contato e substitua o link genérico do Instagram pelo perfil oficial.
- Confirme que as imagens dos projetos correspondem aos títulos e descrições exibidos.
- Confirme as métricas da seção hero (anos de experiência e projetos entregues).
- Adicione domínio/canonical e sitemap quando o domínio definitivo estiver configurado.
- Teste os formulários/canais de contato se forem adicionados posteriormente.

## Observações técnicas

- JavaScript sem dependências para menu mobile, ano automático e animações discretas de entrada.
- As animações respeitam `prefers-reduced-motion` e são progressivas: sem JavaScript, o conteúdo continua visível.
- O projeto utiliza Bootstrap Icons via CDN. Para operação sem dependência externa, hospede localmente a folha de ícones antes da publicação.
