# Assinaturas de e-mail — Truffle Hunters

Oito colaboradores, quatro modelos por pessoa, em PNG e HTML. PNGs exportados do Figma; fotos coloridas e frase “A caçada acontece aqui.”.

## Acesso

Site publicado: https://h4nds-lab.github.io/truffle-e-mails/

Ed: https://h4nds-lab.github.io/truffle-e-mails/Ed%20Ribeiro/

Cada pasta mantém os quatro PNGs de assinatura, os quatro HTMLs, a foto original colorida em `foto-de-perfil.png` (750 × 750 px), os recursos e um LEIA-ME. O arquivo index.html da pasta reúne as prévias e os downloads, incluindo o botão “Baixar foto de perfil”.

## Gmail

As versões completas em PNG preservam a aparência do Figma. Para cadastrá-las no Gmail, crie duas assinaturas e insira a imagem pela URL HTTPS do Pages. Os contatos dentro do PNG não são links separados.

Os HTMLs usam tabelas, texto selecionável, links de contato e recursos HTTPS. Fundos e fontes personalizadas podem ser removidos por clientes de e-mail; valide no cliente de destino. O Gmail não preserva a imagem de fundo dos modelos completos ao copiar o HTML.

## Desenvolvimento local

```sh
python3 -m http.server 8769
```

Acesse http://localhost:8769/. Localhost atende apenas o computador em que o servidor está rodando; para compartilhar use o GitHub Pages.

## Publicação

GitHub Pages: branch main, diretório / (raiz). Em organizações no plano Free, o repositório precisa ser público para ativar Pages. As assinaturas publicadas ficam acessíveis a qualquer pessoa com os links; robots.txt e noindex apenas solicitam que buscadores não indexem o conteúdo.

Fonte: https://www.figma.com/design/ZeNFUrLZKT6rAnqXCJ0C2t
