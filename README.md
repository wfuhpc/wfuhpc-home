# WFU HPC Website

This is the source code of the WFU HPC website available at [wfuhpc.org](https://wfuhpc.org).

## Development

Clone this repo

```bash
$ git clone git@github.com:wfuhpc/wfuhpc-home.git
```

Then install all the node modules

```bash
$ npm install
$ npm install -g gulp-cli
```

Now you can use gulp to execute the `dev` task, which monitors all the files and refresh
your browser automatically.

```bash
$ gulp dev
```

## Deployment

After you modified the website, run the following command

```bash
$ gulp
```

This minifies all the files. Now commit and push it.
