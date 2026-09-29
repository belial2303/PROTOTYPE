# PONTO DE COLETA — QR

Ferramenta local para importar códigos de rastreio, gerar um QR Code por código e exibir a fila em um celular enquanto outro celular faz a leitura.

Os dados ficam no navegador (IndexedDB e localStorage). O QR contém somente o texto original do código.

```bash
npm install
npm run dev
```

Abra o endereço de rede mostrado pelo Vite no celular que vai exibir os QR Codes. O outro celular apenas lê a imagem.

```bash
npm test
npm run build
```
