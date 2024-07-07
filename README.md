# Guía de Uso

## Tecnologías Base

* NextJS App Router
* Typescript
* Jest
* Cypress
* ESLint
* Prettier
* pnpm

## Scripts

```bash
pnpm dev # Run project on development mode
pnpm build # Build project
pnpm start # Run project on production mode
pnpm lint # Run ESLint
pnpm test # Run all test
pnpm test:watch # Run all test in watch mode
pnpm cypress:open # Run Cypress UI
pnpm prepare # Run husky
pnpm commit # Run conventional commit
``

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.
```

## Commits
Para hacer un commit se debe seguir los siguientes pasos:

1. Agregar al stage los archivos que quiere hacer "commit"
2. Ejecutar ```pnpm commit```, que inicializará un **cli** donde podrá escribir un commit siguiendo las pautas básicas del [conventional commit](https://www.conventionalcommits.org/en/v1.0.0/#summary)
* \<type>[optional scope]: \<description>