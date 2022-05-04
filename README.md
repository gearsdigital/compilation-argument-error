# CompilationArgumentError

https://github.com/jscutlery/devkit/issues/170

Steps to reproduce:

1. Clone this repo
2. Run `npm install`
3. Run `ng run compilation-argument-error:ct`

Executed commands
```
ng new
  -> project name: compilation-argument-error
ng add @jscutlery/cypress-angular
ng g @jscutlery/cypress-angular:setup-ct --project compilation-argument-error
npx ngcc
ng run compilation-argument-error:ct
```
