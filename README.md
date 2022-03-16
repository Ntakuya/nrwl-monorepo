https://blog.nrwl.io/server-side-rendering-ssr-with-angular-for-nx-workspaces-14e2414ca532

```
yarn create nx-workspace happynrwl --preset=angular --appName=tuskdesk
yarn add @nguniversal/express-engine
yarn add --dev @nguniversal/builders

yarn nx generate @schematics/angular:universal --project=tuskdesk

touch apps/tuskdesk/src/ssr.server.ts
```
