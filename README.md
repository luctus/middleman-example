[![Netlify Status](https://api.netlify.com/api/v1/badges/688fa051-91d7-4f1d-8c64-24d37e753bef/deploy-status)](https://app.netlify.com/sites/middleman-tailwind-example/deploys)

# Middleman Example

I'm trying to build a working project using the following technologies (based on [this](https://dev.to/lxxxvi/middleman-tailwindcss-webpack-ap3) article):

1) [Middleman](https://middlemanapp.com/): A very cool static sites generator
2) [Tailwind CSS](https://tailwindcss.com/): A very cool CSS framework
3) [Webpack](https://webpack.js.org/): A very common assets bundler

I used [this template](https://tailwindcomponents.com/component/application-header-with-clip-path) for this example, from tailwindcomponents.com 

## Developement

```
$ cd middleman-example
middleman-example$ bundle install
middleman-example$ middleman serve
```

## Deployment

```
$ cd middleman-example
middleman-example$ middleman build
```
The idea is to try out the Netlify platform so this mini site is being deployed automatically every time a push a commit to master. You can see the result here: https://middleman-tailwind-example.netlify.com/
