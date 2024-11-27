# gam3r.store
gam3r.store é um projeto de e-commerce desenvolvido com o objetivo de fornecer uma plataforma completa para a venda de produtos relacionados a jogos. Este repositório utiliza o Turborepo para gerenciar um monorepo que engloba múltiplos aplicativos e pacotes.

## 📂 Estrutura do Projeto
A estrutura do monorepo é organizada da seguinte forma:

### Aplicativos (apps/):
<ul>
  <li><b>docs:</b> Aplicação Next.js destinada à documentação.</li>
  <li><b>web:</b> Aplicação Next.js principal do e-commerce.</li>
</ul>

### Pacotes (packages/):
<ul>
  <li><b>@repo/ui:</b> Biblioteca de componentes React compartilhada entre os aplicativos web e docs.</li> 
  <li><b>@repo/eslint-config:</b> Configurações do ESLint que incluem eslint-config-next e eslint-config-prettier.</li>
  <li><b>@repo/typescript-config:</b> Arquivos tsconfig.json utilizados em todo o monorepo.</li>
</ul>

Cada aplicativo e pacote é desenvolvido 100% em TypeScript.

## ✨ Funcionalidades
<ul>
  <li><b>E-commerce Completo:</b> Plataforma para venda de produtos relacionados a jogos.</li>
  <li><b>Documentação Integrada:</b> Seção dedicada à documentação do projeto.</li>
  <li><b>Componentes Reutilizáveis:</b> Biblioteca de componentes React para uso consistente em diferentes partes da aplicação.</li>
</ul>


## 🛠 Tecnologias Utilizadas
<ul>
  <li><b>Next.js:</b> Framework React para desenvolvimento de aplicações web.</li>
  <li><b>TypeScript:</b> Superset do JavaScript que adiciona tipagem estática.</li>
  <li><b>ESLint:</b> Ferramenta de linting para identificar e corrigir problemas no código.</li>
  <li><b>Prettier:</b> Formatador de código para manter um estilo consistente.</li>
  <li><b>Turborepo:</b> Ferramenta para gerenciamento de monorepos.</li>
</ul>


## 🚀 Como Iniciar

### 1. Clonar o Repositório:
```bash
git clone https://github.com/Gisele-Nuness/gam3r.store.git
```
### 2. Instalar Dependências:
Navegue até o diretório do projeto e instale as dependências utilizando o gerenciador de pacotes de sua preferência (por exemplo, npm):

```bash
cd gam3r.store

npm install
```
### 3. Desenvolvimento:
Para iniciar o ambiente de desenvolvimento para todos os aplicativos e pacotes:

```bash
npm run dev
```
### 4. Build:
Para construir todos os aplicativos e pacotes para produção:

```bash
npm run build
```
## 🤝 Contribuição
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e pull requests para melhorias, correções de bugs ou novas funcionalidades.

## 📄 Licença
Este projeto está licenciado sob a Licença MIT. Consulte o arquivo LICENSE para mais detalhes.
