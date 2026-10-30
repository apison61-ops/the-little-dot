# SM Consultoria | Business Consulting

Website institucional responsivo em HTML, CSS e JavaScript, dentro da pasta `teste-1/`.

## Funcionalidades
- Navegação responsiva com menu mobile.
- Secções Início, Sobre Nós, Serviços, Multimédia, Consultorias e Contactos.
- Preços de consultoria presencial (35.000 Kz) e online (25.000 Kz).
- Formulário com validação do navegador que prepara a mensagem para o WhatsApp; não finge enviar para um servidor.
- Contacto pelo WhatsApp: +244 941 341 422.
- Galeria multimédia com visualizador modal e suporte a imagens ampliadas.
- Animações suaves e respeito pela preferência de movimento reduzido.
- Política de privacidade em `privacy.html`.

## Como visualizar
Abra `index.html` num navegador. A página utiliza algumas imagens ilustrativas externas na secção multimédia; estas estão identificadas como demonstração e devem ser substituídas pelas fotografias oficiais da SM Consultoria.

## Atualizar os vídeos
Na secção Multimédia de `index.html`, edite o atributo `data-video` dos cartões com um URL de incorporação do YouTube ou Vimeo (por exemplo, o formato `https://www.youtube-nocookie.com/embed/ID_DO_VIDEO`). A galeria de imagens pode ser atualizada editando os atributos `data-image`, `src` e os textos alternativos dos cartões.

## Publicação
Este commit atualiza o código no GitHub, mas não configura automaticamente um alojamento. Para disponibilizar um endereço público, ative o GitHub Pages nas definições do repositório e selecione a origem de publicação adequada. A publicação online deve ser verificada separadamente.

## Identidade visual
Azul institucional `#003780`, branco `#FFFFFF` e verde `#25A56A` apenas em pequenos detalhes.


## Publicação automática (GitHub Pages)

Foi adicionado o workflow `.github/workflows/deploy-sm-consultoria.yml`. Para publicar o site pela primeira vez:

1. Abra **Settings** do repositório.
2. Entre em **Pages**.
3. Em **Build and deployment**, selecione **GitHub Actions** como fonte.
4. Abra **Actions** e confirme que o workflow **Publish SM Consultoria website** terminou com sucesso.
5. Depois da primeira publicação, o endereço aparecerá no ambiente **github-pages** do workflow.

O workflow publica o conteúdo de `teste-1/` como raiz do site.

## Identidade visual e conteúdo real

O logótipo vetorial em `assets/sm-logo.svg` é uma versão gráfica simples criada para evitar que a marca fique sem imagem no cabeçalho. Substitua-o pelo ficheiro oficial da SM Consultoria quando disponível. As fotografias atuais da galeria são imagens ilustrativas e estão identificadas como tal; os cartões de vídeo estão preparados para receber links reais de incorporação. Não foram inventados vídeos ou fotografias da empresa.
