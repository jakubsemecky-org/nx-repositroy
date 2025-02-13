# nx-repositroy
empty nx repo to test versioning and commitizen

Generated using commands:
```bash
npx nx@latest init
npm install @nrwl/react @nrwl/node --save-dev
npx nx g @nrwl/react:application my-react-app --style=css --routing
```

Show
`npx nx show projects`

Build
`npx nx build my-react-app`
`npx nx run-many -t build`

Test
`npx nx test my-react-app`
`npx nx run-many -t test`

...

