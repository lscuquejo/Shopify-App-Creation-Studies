
Shopify Apps * - *
=====
![Alt text](imgs/devsAreGods.jpg?raw=true "Title")
## Welcome to my Shopify App practice and study :)

*Guide* : Symfony Setup for shopify apps.
=====

# !!! Requirements !!!
- Composer installed [Composer Docs](https://getcomposer.org/doc/00-intro.md)
- Symfony installed [Symfony Docs](https://symfony.com/doc/current/best_practices/creating-the-project.html#installing-symfony)
- GitHub Account (Recommended: Link it to the Shopify account.)
- Create a Shopify developers account [here](https://partners.shopify.com/signup/developer)
- ngrok installed follow instructions down bellow [(official docs here)](https://developers.shopify.com/tutorials/build-a-shopify-app-with-node-and-react/embed-your-app-in-shopify)

1 - Ngrok Setup
=====
Install ngrok (Globally)
```
npm install ngrok -g
```
Set ngrok to use port 3000 or 300X (Recommended)
```
ngrok http 3000
```
### should look something like this.
![Alt text](imgs/likeThisBoy.png?raw=true)

2 - Get a Shopify API key and Shopify API secret key
=====

- Follow the steps from the second part from this [page](https://developers.shopify.com/tutorials/build-a-shopify-app-with-node-and-react/embed-your-app-in-shopify)

3 - Setup Symfony base skelton.
=====
Create skeleton
```
composer create-project symfony/skeleton appName
cd appName
```

4 - Add the Shopify API key and Shopify API secret key
=====

- Follow the steps from the third part from this [page](https://developers.shopify.com/tutorials/build-a-shopify-app-with-node-and-react/embed-your-app-in-shopify)

5 - Install and prepare oAuth symfony
