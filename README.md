# Jornada Full Stack com IA — Astryx

Projeto React + Vite com Astryx. A trilha interativa original está em `public/trilha.html`, junto da imagem; a versão anterior permanece na pasta `cronograma`.

## Executar localmente

```sh
npm install
npm run dev
```

Abra o endereço indicado no terminal. Para gerar os arquivos de produção, execute `npm run build`; o resultado fica em `dist`.

## Vercel

Configure `cronograma/astryx` como diretório raiz do projeto, use o framework Vite, o comando `npm run build` e a pasta de saída `dist`. Não publique `node_modules` ou `.npm-cache`.

Os ícones das tecnologias do mapa são carregados pelo serviço externo Simple Icons e exigem conexão. A área do mapa é uma cópia isolada da versão anterior: alterações futuras em `cronograma/index.html` precisam ser aplicadas também em `public/trilha.html`.
