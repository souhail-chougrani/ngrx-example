# Outdated - check out https://github.com/ngrx/example-app
This example is outdated, using old versions of the lib, old file structure, before I update it, check out the official example at https://github.com/ngrx/example-app




.
.
.
.
.
.
.
.
.



# WIP: @nrgx example app(router, store, sagas, logger) 
Fully reactive, utilizing normalizr, showcasing handling of authentization, xhr requests as well as websockets. 

- clone 
- `npm install` to install dependencies
- `npm start` to run

# TODO
- [ ] reconsider folder naming with dots, finder thinks it's an extension
- [ ] move hardcoded api urls to constants
- [ ] add readme
- [ ] add html descriptions to components through whole app, explaining things, and links to their github counterparts
- [ ] add tests
- [ ] fix zone error `it takes like 10 seconds before this triggers https://github.com/fxck/ngrx-example/blob/master/src/app/_people/routes/people.list.route/people.list.route.ts#L62 and there are some Uncaught TypeError: Cannot read property 'unsubscribe' of undefined errors, which I suppose is caused by that ngOnDestroy`
- [ ] add loading indication
- [ ] add success notifications
