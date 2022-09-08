# Table of contents
1. [Description](#Description)
2. [System Analysis](#System_Analysis)
3. [System Design](#System_Design)
4. [Final Product](#Final_Product)
5. [Demo videos](#Demo_videos)
6. [Source codes](#Sourcecode)
# Description  <a name="Description"></a>
Two mobile apps, one for sellers and one for customers, that allow them to sell and buy groceries
# System Analysis <a name="System_Analysis"></a>
## System's detailed descriptions
This system will be designed as
below. The app serves 2 types of users:
- Seller: Users who want to sell grocery products. They need to have an seller
account and have to authenticate with the system.
- Customer: Users who want to buy grocery products. They need to authenticate
with the system using customer accounts.

For each type of users, the system provide them with features below:
- Seller: Sellers can manage their products, review, and orders. The app provides
the sellers with a user-friendly sale report feature with which they can track
their sale history. This business’s statistical information will be illustrated in
chart forms.
- Customer user: They can view all products in many different categories that
the vendor has listed on the app. If needed, the users can perform search
queries to find the products they want based on the product’s name or category’s name. They can also view detailed information about a product by
clicking on a specific product item. If a user like an item, they can add it to
the cart for later uses. They can also manage their products in the cart which
includes deleting products and adjusting the item quantity of a product. The
customers can buy products that require placing an order and issuing payment.
In addition, commenting and rating products are allowed after the user has received the order. They can also manage their address information as well as
their order history
## Business workflow
![alt text](figures/workflow.jpg "Logo Title Text 1")

## Use-case diagram
![alt text](figures/Overview%20UC%20diagram.jpg "Logo Title Text 1")
# System Design <a name="System_Design"></a>
## Technologies
![alt text](figures/technologies.png "Logo Title Text 1")
## System Architecture
![alt text](figures/System%20Architechture.jpg "Logo Title Text 1")

## Package diagram
![alt text](figures/Package%20diagram.drawio.png "Logo Title Text 1")

## Database diagram
![alt text](figures/Ecom%20Model%20diagram%20-%20Model5.png "Logo Title Text 1")
# Final Product <a name="Final_Product"></a>
## Seller app
| List products | Fork a product | List categories of shop |
| :-------------: |:-------------:| :-----:|
![](screenshots/seller.home.x.jpg)|![](screenshots/seller.fork.x.jpg) | ![](screenshots/seller.category.x.jpg) 

| List orders | List reviews | Sale results |
| :-------------: |:-------------:| :-----:|
![](screenshots/seller.order.x.jpg)|![](screenshots/seller.review.x.jpg) | ![](screenshots/seller.saleStatistics.x.jpg) 


## Customer app

| List products | List categories | Product details |
| :-------------: |:-------------:| :-----:|
![](screenshots/customer.home.x.jpg)|![](screenshots/customer.cate.x.jpg) | ![](screenshots/customer.productDetails.x.jpg) 

| Shop’s products | Shop’s categories | Shop Info|
| :-------------: |:-------------:| :-----:|
![](screenshots/customer.shop.x.jpg)|![](screenshots/customer.shop.cate.x.jpg)|![](screenshots/customer.shop.info.x.jpg) 

| Cart | Place order | Addresses |
| :-------------: |:-------------:| :-----:|
![](screenshots/customer.cart.x.jpg)|![](screenshots/customer.order.x.jpg) | ![](screenshots/customer.address.x.jpg) 

| List orders | Order details | Order operations |
| :-------------: |:-------------:| :-----:|
![](screenshots/customer.listOrders.x.jpg)|![](screenshots/customer.orderDetails.x.jpg) | ![](screenshots/customer.rebuy.x.jpg) 

| To review | Do review | List reviewed |
| :-------------: |:-------------:| :-----:|
![](screenshots/customer.toreview.x.jpg)|![](screenshots/customer.review.x.jpg) | ![](screenshots/customer.reviewed.x.jpg) 

# Demo videos <a name="Demo_videos"></a>
[Seller app](https://photos.app.goo.gl/bhpiCFPsJGQd3NG49)

[Customer app](https://photos.app.goo.gl/Y6F4dXS7B4CBhYjj7)

# Source codes <a name="Sourcecode"></a>
[Server](https://github.com/Compound-Z/ecom-server)

[Customer app](https://github.com/Compound-Z/eCom)

[Seller app](https://github.com/Compound-Z/ecom-sellerCenter)