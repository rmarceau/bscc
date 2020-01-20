# Northern x Fanshawe Shopify Course

## Prerequisites
- Bash CLI
- [Docker](https://docs.docker.com/install/)

## Download Quick Start Package

To download the quick start package, clone this repository and remove the `.git` folder by running the following:

```console
$ git clone https://github.com/northernco/fanshawe-shopify-course.git <theme_name>
$ cd <theme_name>
$ rm -rf .git
```

Create a new repository and add this folder.

## Downloading the Theme

In the project, run the following to download the theme from your Shopify store using Theme Kit:

```console
$ chmod +x theme
$ ./theme get --list -p=[your-password] -s=[you-store.myshopify.com]
$ ./theme get -p=[your-password] -s=[you-store.myshopify.com] -t=[your-theme-id]
```

The password can be obtained by creating a private app in your Shopify store [[gif]](https://shopify.github.io/themekit/assets/images/shopify-local-theme-development-generate-api.gif). The theme ID can be obtained from the `./theme get --list` command.

Full instructions can be found [[here]](https://shopify.github.io/themekit/#configure-an-existing-theme).

## Using Theme Kit

Theme Kit can be run using the `./theme` script in the project's root directory. A full list of commands can be found [[here]](https://shopify.github.io/themekit/commands/).
