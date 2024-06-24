# Ignite Timer

Ignite Timer é uma aplicação de cronômetro pomodoro construída com React, TypeScript, Vite e Styled Components. Ela permite que os usuários iniciem um ciclo de foco, interrompam e reiniciem o ciclo, além de visualizar o histórico de ciclos concluídos.

<br>

<a href="https://ignite-timer-ashy-kappa.vercel.app" target="_blank">
  <img alt="Deploy" src="https://img.shields.io/badge/deploy-Vercel-000?style=for-the-badge&logo=vercel&logoColor=white" />
</a>

## Requisitos

- Node.js (versão 18 ou superior)
- npm (gerenciador de pacotes do Node.js)

## Instalação

1. Clone este repositório:
```bash
git clone https://github.com/jsgarcia-dev/ignite-timer.git
```
2. Navegue até o diretório do projeto:
```bash
cd ignite-timer
```

3. Instale as dependências:
```bash 
npm install
```
Executando a aplicação

Para iniciar a aplicação em modo de desenvolvimento, execute o seguinte comando:
```bash 
npm run dev
```
Isso iniciará o servidor de desenvolvimento e abrirá a aplicação em http://localhost:5173 no seu navegador padrão.

### Stacks utilizadas
<p align="left">
  <img alt="React" src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
  <img alt="React Router" src="https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge&logo=react-router&logoColor=white" />
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" />
  <img alt="Vite" src="https://img.shields.io/badge/Vite-B73BFE?style=for-the-badge&logo=vite&logoColor=FFD62E" />
  <img alt="styled-components" src="https://img.shields.io/badge/styled--components-DB7093?style=for-the-badge&logo=styled-components&logoColor=white" />
</p>

Demais stacks:
- React Hook Form: O projeto utiliza a biblioteca React Hook Form para lidar com formulários de maneira mais simples e performática, aproveitando os recursos dos React Hooks.
- Zod: O Zod é uma biblioteca de validação de esquemas utilizada no projeto para validar os dados de entrada do formulário de criação de um novo ciclo.
- Immer: A biblioteca Immer é utilizada para trabalhar com a imutabilidade de estado no reducer do contexto de ciclos, facilitando a criação de atualizações imutáveis no estado.
- date-fns: O Ignite Timer utiliza a biblioteca date-fns para lidar com operações de data e hora, como calcular a diferença entre datas e formatar strings de data.
- Phosphor Icons: Os ícones utilizados na interface são fornecidos pela biblioteca Phosphor Icons, uma biblioteca de ícones vetoriais open-source.

### Finalidade da aplicação
O Ignite Timer é uma aplicação de cronômetro pomodoro que ajuda os usuários a gerenciar seus ciclos de foco e descanso. Ela oferece recursos como:

- Iniciar um novo ciclo de foco com duração personalizada.
- Interromper e reiniciar o ciclo atual.
- Visualizar o histórico de ciclos concluídos.
- Design moderno e intuitivo.
