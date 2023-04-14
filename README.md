# fpdl.github.io
Personal page of fpdl, small fast project. 

The philosophy of this development is to have a MVP built in such a way that can be updated and changed every X amount of time without having to re-familiarize with some obscure technology that I no longer use in my day to day.

## Specs
- Built with [Hugo](https://gohugo.io/), theme [Hermit](https://github.com/Track3/hermit).
- Deployed through [Github Actions](https://gohugo.io/hosting-and-deployment/hosting-on-github/), configured using this guide.
- Favicon made (quick and dirty) in [favicon.io](https://favicon.io/)

## To update
When a commit is pushed to `main` deployment process starts (rebuilds and deploys Hugo, no need to touch anything).

________________________________________
## To do:
- [X] Readme skeleton
- [X] Update favicon
- [X] v1 content `/about` (ctr+c, ctr+v linkedin)
- [X] Remove unused `/posts`
- [X] Fix deployment error 
  - (docs)[https://discourse.gohugo.io/t/tocss-failed-to-transform-style-scss/42096/6] pointed at the `#extended: true` in the config of the gh actions; removal of comment solved issue.
- [ ] v2 content `/about` 
