# :wave: Say hi to Elizabeth :wave:

[![Generic badge](https://img.shields.io/badge/course%20available%3F-yes-green.svg)](https://shields.io/)

This is [Shopify Theme Development – Online Store 2.0 + TailwindCSS course](https://weeklyhow.com/courses/)

## Lessons covered

| Status             | Lectures                     |
| ------------------ | ---------------------------- |
| :heavy_check_mark: | Installing Development Tools |
| :heavy_check_mark: | Navigational Bar             |
| :heavy_check_mark: | 404 Page                     |
| :heavy_check_mark: | Article Page                 |
| :heavy_check_mark: | Blog Page                    |
| :heavy_check_mark: | Cart Page                    |
| :heavy_check_mark: | Product Collection Page      |
| :heavy_check_mark: | Collections Page             |
| :heavy_check_mark: | Homepage (Index)             |
| :heavy_check_mark: | Pages (About & Contact)      |
| :heavy_check_mark: | Advanced Product Page        |
| :heavy_check_mark: | Search Page                  |

Before you begin, ensure you have the following installed:

- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/) or [Yarn](https://yarnpkg.com/)
- [Shopify Developer Account](https://developers.shopify.com/)

## How to use

To use this repository for making Shopify themes, use the following command of Shopify CLI.

```sh
shopify theme init [ NAME OF YOUR THEME ] --clone-url git@github.com:akhror-valiev/Elizabeth_Store_For_Shopify.git
```

If you don't have Shopify CLI installed to your computer, navigate to the [installation page of Shopify CLI](https://shopify.dev/themes/tools/cli/installation).

## Usage

npm install

run shopify theme dev

in separate terminal run

npx tailwindcss -i ./src/tailwind.css -o .\assets\application.css --watch
