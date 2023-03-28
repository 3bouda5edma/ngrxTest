# ngrxTest
https://www.learmoreseekmore.com/2022/06/angular-14-statemanagement-crud-example-with-rxjs14.html

commands:
npm install -g json-server
ng add @ngrx/store@latest
ng add @ngrx/effects@latest
ng add @ngrx/store-devtools@latest


npm run json-run
ng generate module books --routing
ng generate component books/home
ng generate interface books/store/books
ng generate class books/store/books.reducer
ng generate class books/store/books.selector
ng generate class books/store/books.action
ng generate class books/store/books.effect
ng generate service books/books
ng generate component books/add


ng generate interface shared/store/appstate
ng generate class shared/store/app.action
ng generate class shared/store/app.reducer
