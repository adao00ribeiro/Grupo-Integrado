# Desafio

É um diferencial para nossos futuros alunos a utilização de processos digitais para se matrícularem em nossa instituição. Isso trás agilidade para o processo e melhora a experiência dos nossos usuários.
Você deverá desenvolver uma solução permita que futuros alunos se matrículem em cursos de diversas modalidades e tipos.
A aplicação deverá apresentar os cursos disponíveis e permitir a realização de filtros para facilitar a escolha. Após a escolha, o futuro aluno deverá preencher um cadastro com as seguintes etapas:


- Primeira etapa

  - Nome
  - E-mail
  - Telefone



- Segunda etapa

  - CEP
  - CPF
  - Nascimento



- Terceira etapa

  - Envio do documento de identificação


Alguns detalhes importantes

- Cursos

  - Podem ser ofetados nas modalidades Presencial e EAD;
  - Podem ser dos tipos Graduação e Pós-graduaçã  o;
  - Valor do investimento e número de parcelas de vem estar presentes;


Acadêmico

  - Deve possuir um endereço com CEP válido;
  - E-mail e número de celular são indispensáveis;
  - Mostrar os campos de acordo com as etapas e salvá-los assim que concluídas é importante para usabilidade/ - captura de oportunidades de negócio.


Documentos

  - Deve ser enviado um Documento de Identificação (CNH ou RG)

## Decisões Tomadas

- **Tecnologia:** 

Ao iniciar o projeto, optei por trabalhar com o framework Nuxt + Nestjs, mesmo sendo minha primeira experiência com o Nuxt. A decisão de adotar o Nuxt, foi motivada pela minha familiaridade prévia com o framework NestJS.

Devido à minha falta de conhecimento prévio em Nuxt, dediquei considerável tempo ao estudo, concentrando-me especialmente na documentação para adquirir proficiência na tecnologia. Essa imersão no material disponível foi crucial para minha compreensão dos conceitos fundamentais e para superar a curva de aprendizado associada ao Nuxt. Embora tenha exigido um investimento significativo de tempo, essa abordagem me permitiu ganhar confiança e conhecimento prático, consolidando assim as bases necessárias para enfrentar os desafios do projeto de maneira eficaz.

## Ferramentas Utilizadas

- **Backend:**
  - NestJS
  - Prisma
  - Banco de Dados: SQLITE 
    - Motivação da Escolha: Optei por utilizar o SQLite para o banco de dados,  principalmente devido à sua simplicidade e facilidade de incorporação. A decisão foi tomada visando evitar a complexidade de configurar um servidor separado, uma vez que o SQLite não exige essa infraestrutura adicional. Essa escolha proporciona uma implementação mais direta e eficiente, economizando tempo e recursos, especialmente em contextos em que não há necessidade de um sistema de banco de dados mais robusto.
  

- **Frontend:**
  - Nuxt
  - Estilização:
    - Bootstrap (juntamente com suas funcionalidades de design e componentes)
    - CSS puro (para personalizações específicas e estilos adicionais)
       
## Como Rodar o Projeto Backend

1. Clone o repositório: 
```bash
git clone https://github.com/adao00ribeiro/digital-matricula-api.git
```
2. Navegue até a pasta do digital-matricula-api:
```bash
cd digital-matricula-api
```
3. Instale as dependências: npm install ou yarn install ou pnpm install
```bash
pnpm install
```
4. Iniciar o prisma
```bash
npx prisma migrate dev --name Initial
```
5. Iniciar o prisma
```bash
pnpm seed
```
6. Inicie o servidor: npm start ou yarn start
```bash
pnpm start
```
7. Backend rodando
```bash
start http://localhost:5000/api
```
## Como Rodar o Projeto FrontEnd

1. Clone o repositório: 
```bash
git clone https://github.com/adao00ribeiro/frontend.git
```
2. Navegue até a pasta frontend:
```bash
cd frontend
```
3. Instale as dependências: npm install ou yarn install ou pnpm install
```bash
npm install
```
4. Instale as dependências: npm install ou yarn install ou pnpm install
```bash
npm run build
```
5. Instale as dependências: npm install ou yarn install ou pnpm install
```bash
npm run start
```
6. FrontEnd rodando
```bash
start http://localhost:3000
```
