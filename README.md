## hello-webpart-sp-library-deployment

A sample Hello World SharePoint Framework web part to demonstrate build, run and deploy (to a SP Library). Clone or download the zip. And then all you have to do is: Change CDN path to a SP library folder path (in manifest.json)
### Building and running the code on workbench

```bash
git clone the repo
npm i
npm i -g gulp
gulp serve
```

This package produces the following:

* lib/* - intermediate-stage commonjs build artifacts
* dist/* - the bundled script, along with other resources
* deploy/* - all resources which should be uploaded to a SP Library folder (as mentioned in manifest.json).

### Deploy options

gulp clean - TODO
gulp bundle - TODO
gulp package-solution - TODO

Upload .sppkg file to App Catalog
Upload deploy files to SP Library folder

For detailed working of the solution visit - https://vedmishra.net/2018/12/10/build-run-and-deploy-your-first-sharepoint-framework-web-part/
