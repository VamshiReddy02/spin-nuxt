# A simple Nuxt SSG, running on Spin

This is a template for building and statically exporting your
[Nuxt](https://nuxt.com/) application and running it on
[`Fermyon Spin`](https://developer.fermyon.com/spin).

## Using the template

First, you need to tell the Spin CLI where to get the template:

```console
$ spin templates install --git https://github.com/VamshiReddy02/spin-nuxt
Copying remote template source
Installing template Nuxt...
Installed 1 template
+-------------------------------------------------------------------------+
| Name         Description                                                |
+=========================================================================+
| Nuxt   Build your front-end application using Nuxt and Spin |
+-------------------------------------------------------------------------+
```


## Building and running your application

Before you can build your nuxt application, make sure to run `npm install` in
the target directory. You are now ready to start building your front-end. Run
`npm run dev` and start editing your application. Alternatively, you can run
`spin build` and `spin up` to build and run your application.


## Deploy your application to Fermyon Cloud

Using a free [Fermyon Cloud](https://cloud.fermyon.com) account, you can deploy
your WebAssembly applications and get a public URL:

```console
$ spin deploy
# your application will now be available at a *.fermyon.app URL
```

## Credits

The Nuxt template is based on the
[official Nuxt template](https://nuxt.com/docs/getting-started/introduction).

