# turu
turu monorepository

based on:
[Javascript monorepository template.](https://github.com/erzhtor/javascript-monorepo-with-lerna)


## Get Started
Follow instructions to clone and run project

#### Prerequisites
- Node.js: 16.16.0
- [Lerna](https://github.com/lerna/lerna): installed globally. `npm i lerna -g`

### Clone repository
`git clone https://github.com/kemasm/lerna_turu.git`

### Install dependencies using lerna
`lerna bootstrap`

### Run project
- **API backend**
`npm start --prefix apps/api`
- **frontend**
`npm start --prefix apps/frontend`
