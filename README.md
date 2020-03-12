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

---

## References

* [A Guide to Building a PWA in Angular 8](https://levelup.gitconnected.com/a-guide-to-building-a-pwa-in-angular-acea27ae708d)
* [PWA “Add Button to Home Screen” and Remote Debugging in Android Devices with Angular 8](https://levelup.gitconnected.com/pwa-add-button-to-home-screen-and-remote-debugging-in-android-devices-with-angular-8-3dbaec772a1)
