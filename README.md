# Agile Xperience

Site da Agile Xperience: workshops práticos de 4 horas em Agilidade, Scrum, Kanban, Facilitação, Gestão de Tempo e IA aplicada.

## Estrutura

```
index.html               página única do site (HTML, CSS e JS)
assets/favicon.png       ícone da aba do navegador
assets/apple-touch-icon.png  ícone ao salvar o site na tela do celular
netlify.toml             configuração de publicação no Netlify
```

## Publicação (Netlify)

1. No Netlify: **Add new site → Import an existing project → GitHub** e escolha este repositório.
2. Não há comando de build. A pasta publicada é a raiz (já definido no `netlify.toml`).
3. Em **Forms**, ative a detecção de formulários e faça um novo deploy.
4. Em **Forms → Notifications**, cadastre o e-mail que vai receber os contatos.

Cada push na branch principal atualiza o site automaticamente.

## Formulário de contato

O formulário usa o Netlify Forms. Ele envia apenas quando o site está em um endereço `*.netlify.app` ou em um domínio que contenha `agilexperience`. Para outro domínio, ajuste a variável `LIVE` no script no final do `index.html`.
