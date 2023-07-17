# Chatbot usando Next, AI SDK, OpenAI e Shadcn/UI

Chatbot criado em conjunto com o vídeo tutorial [Chatbot do ZERO com Next, AI SDK, OpenAI e Shadcn/UI](https://www.youtube.com/watch?v=CPRx_WVkJ8g)

## Pré-requisitos

Antes de começar, você precisará ter o seguinte instalado em sua máquina:

- Node.js
- npm (gerenciador de pacotes do Node.js)

## Instalação

Siga as etapas abaixo para configurar o projeto em sua máquina local:

1. Clone este repositório para o seu diretório de trabalho:

   ```bash
   git clone https://github.com/seu-usuario/nome-do-repositorio.git
   ```

2. Navegue até o diretório do projeto:

   ```bash
   cd nome-do-repositorio
   ```

3. Instale as dependências do projeto:

   ```bash
   npm install
   ```

4. Crie um arquivo `.env.local` na raiz do diretório do projeto e adicione as seguintes variáveis de ambiente:

   ```plaintext
   OPENAI_API_KEY=your_openai_api_key
   ```

   Certifique-se de substituir `your_openai_api_key` pela sua chave de API da OpenAI.

## Uso

Para iniciar o servidor de desenvolvimento e executar o chatbot, execute o seguinte comando:

```bash
npm run dev
```

Isso iniciará o servidor local na porta 3000. Abra o navegador e acesse `http://localhost:3000` para ver o chatbot em ação.

## Personalização

Você pode personalizar o comportamento do chatbot ajustando os arquivos no diretório `src/`. Com o tempo irei personalizar o projeto e subir as modificações.

## Contribuição

Contribuições são bem-vindas! Se você deseja contribuir para este projeto, siga as etapas abaixo:

1. Crie um fork deste repositório.

2. Crie uma nova branch para suas alterações:

   ```bash
   git checkout -b minha-branch
   ```

3. Faça suas modificações e adicione os arquivos alterados:

   ```bash
   git add .
   ```

4. Faça o commit das suas alterações:

   ```bash
   git commit -m "Minhas alterações"
   ```

5. Envie suas alterações para o repositório remoto:

   ```bash
   git push origin minha-branch
   ```

6. Abra um pull request no repositório original.

## Agradecimentos

- [Next.js](https://nextjs.org/)
- [OpenAI](https://openai.com/)
- [Shadcn/UI](https://github.com/shadcn/ui)