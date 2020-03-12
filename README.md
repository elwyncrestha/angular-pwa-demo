# angular-pwa-demo

Steps to deploy PWA using GitHub Pages.

- Create new Angular application.

```ANGULAR
ng new angular-pwa-demo
```

- Add PWA dependency

```ANGULAR
ng add @angular/pwa
```

- Build the app

```ANGULAR
ng build --prod --output-path docs --base-href=/angular-pwa-demo/
```

- Add docs directory to GIT and push

- Build GitHub Pages from the /docs folder in the master branch

