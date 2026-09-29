# Varanda do Espeto — landing page

Site estático em HTML, CSS e JavaScript. Não precisa de Node.js, instalação de pacotes ou etapa de build.

## Estrutura

```text
.
├── index.html                   Página e conteúdo
├── css/
│   └── styles.css              Aparência e responsividade
├── js/
│   └── main.js                 Animações ao rolar
└── assets/
    └── images/
        ├── fotos/              Fotos fornecidas do estabelecimento
        │   ├── prato.png
        │   ├── espetinhos.png
        │   ├── chope.png
        │   └── drink.png
        └── ilustracoes/        Imagens geradas, identificadas na página
            ├── picanha.png
            └── feijao-tropeiro.png
```

## Ver no computador

Abra `index.html` no navegador. Para testar como a Vercel serve os arquivos, também pode iniciar um servidor na raiz desta pasta com `python -m http.server 8000` e abrir `http://localhost:8000`.

## Publicar no GitHub e na Vercel

1. Crie um repositório no GitHub e envie **o conteúdo desta pasta** para a raiz dele. O `index.html` deve aparecer na raiz do repositório, não dentro de outra pasta.
2. Na Vercel, importe esse repositório.
3. Selecione o preset **Other**, deixe o comando de build vazio e use a raiz do repositório como diretório de saída (`.`). Não é preciso criar `package.json`.
4. Depois da publicação, confira as imagens e os links de WhatsApp e Google Maps.

## Editar

- Textos, telefone, endereço e links: `index.html`.
- Cores, layout e tamanhos: `css/styles.css`.
- Animação de entrada ao rolar: `js/main.js`.
- Para trocar uma foto, substitua o arquivo correspondente em `assets/images/` mantendo o nome, ou ajuste o caminho em `index.html`/`css/styles.css`.

As imagens de picanha e feijão tropeiro são **ilustrativas**. Nota e quantidade de avaliações vieram das informações enviadas para o projeto e podem mudar. Confirme dados e horários antes de usar a página como site oficial do estabelecimento.
