# Background Remover

[original source on huggingface](https://huggingface.co/spaces/Xenova/remove-background-web/tree/main)

Este projeto é uma aplicação web simples para remoção de fundo de imagens, utilizando o modelo RMBG V1.4 da BRIA AI e a biblioteca Transformers.js.

## Estrutura do Projeto

- `index.html`: Arquivo principal da aplicação.
- `assets/`: Contém os arquivos JavaScript e CSS necessários para o funcionamento da aplicação.
  - `index-E_M5nW8h.js`: Script principal.
  - `index-SojaDS6z.css`: Estilos da aplicação.

## Como Executar o Projeto

Para executar este projeto localmente, você pode usar um servidor HTTP simples. Aqui estão algumas opções:

### Opção 1: Usando Python

Se você tiver o Python instalado, execute o seguinte comando no terminal, dentro do diretório do projeto:

```bash
python3 -m http.server 8000
```

Isso iniciará um servidor em `http://localhost:8000`.

### Opção 2: Usando Node.js (http-server)

Se você tiver o Node.js instalado, instale o pacote `http-server` globalmente:

```bash
npm install -g http-server
```

Depois, execute o servidor no diretório do projeto:

```bash
http-server
```

O servidor será iniciado e exibirá a URL (por exemplo, `http://127.0.0.1:8080`).

### Opção 3: Usando a Extensão Live Server no VS Code

Se você estiver usando o Visual Studio Code, instale a extensão "Live Server". Após a instalação:
1. Clique com o botão direito no arquivo `index.html` no explorador de arquivos.
2. Selecione "Open with Live Server".

Isso abrirá o projeto no navegador e o servirá localmente.

## Tecnologias Utilizadas

- [Transformers.js](http://github.com/xenova/transformers.js)
- [RMBG V1.4 Model](https://huggingface.co/briaai/RMBG-1.4) da [BRIA AI](https://bria.ai/)

## Licença

Este projeto é apenas para fins educacionais e demonstração. Verifique as licenças das bibliotecas e modelos utilizados para mais informações.
