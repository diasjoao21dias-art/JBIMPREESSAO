# JB Impressão Digital — site estático para Render

## Publicar no Render
1. Envie o conteúdo desta pasta para um repositório GitHub.
2. No Render, crie um **Static Site** e conecte o repositório.
3. Build Command: deixe vazio (ou `echo "Static site"`).
4. Publish Directory: `.`
5. Faça o deploy.

Também é possível usar o arquivo `render.yaml` como Blueprint.

## Personalizações importantes
- WhatsApp configurado a partir do link exibido no Instagram: `https://wa.me/556421415172`.
- Endereço informado no perfil: Av. 7, nº 794, Qd. 04, Lt. 08, B. Martins, Rio Verde - GO.
- E-mail do perfil: juniorborges80@hotmail.com.
- Instagram: https://www.instagram.com/jbimpressaodigital/.
- Catálogo e artes do catálogo são ilustrativos; confirme produtos, materiais e serviços efetivamente oferecidos antes de publicar.
- A imagem OG fica em `assets/og-jb-impressao.png`. Depois do deploy, confirme se a URL pública da imagem abre corretamente. Para prévias sociais, o ideal é trocar `/assets/og-jb-impressao.png` por uma URL absoluta com o domínio publicado nos metadados `og:image` e `twitter:image`.
- Atualize os metadados de compartilhamento com a URL final do site se desejar uma URL canônica.
