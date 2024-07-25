# Cadence Labs Shopify Developer Candidate Take Home Test

A light e-commerce store intended to showcase my ability to elevate the user experience on the product page of an existing Shopify store. Updates were made to utilize existing functionality to prevent redundancies and maintain format of codebase.

## Description

* PDP: On desktop, displays variant image swatches in a grid. On smaller screens, the variant image swatches are oprganized on a slider.

* PDP: name of the selected variant next to the “Flavor” label

* PDP: a total price based on the quantity added to the car

* PDP: On desktop, displays the product thumbnails vertically on the left of the main image. On smaller screens, they are positioned underneath the main product image.

## Getting Started

### Dependencies

* 


### Installing


1. Once you clone the repo you will need to ensure [Theme Kit](https://shopify.dev/tools/theme-kit/getting-started) is set up, in oder to run the `yarn` commands

2. Copy `config.sample.yml` to `config.yml` and update the password, theme_id, and store field (provided to you in a separate e-mail)

3. Install dependencies on local environment
```
yarn install
```

4. Get a copy of the most current code for your theme
```
yarn download:dev
```

### Deployment

1. To deploy the theme run:
```
npm start
```

2. To auto deploy any theme change
```
yarn watch
```
The website will automatically run on your browser



## Future Updates

* Finish sticky add to cart. Positioned at the top for desktop and at the bottom for mobile. WIll slide into viewport when main PDP form is not visible

* Bundle feature for variants

* Favorite Product: popup modal for marketing email capture. Favorited products added to customer object.

## Authors

* [@Daryl Blancaflor](djblanc360@gmail.com)

## Version History

* 0.1
    * Initial Release
    * 
