## hello-webpart-sp-library-deployment

A sample Hello World SharePoint Framework web part to demonstrate build, run and deploy (to a SP Library). Clone or download the zip. And then all you have to do is: Change CDN path to a SP library folder path (in manifest.json)
### Building the code

```bash
git clone the repo
npm i
npm i -g gulp
gulp
```

This package produces the following:

* lib/* - intermediate-stage commonjs build artifacts
* dist/* - the bundled script, along with other resources
* deploy/* - all resources which should be uploaded to a CDN.

### Build options

gulp clean - TODO
gulp test - TODO
gulp serve - TODO
gulp bundle - TODO
gulp package-solution - TODO
