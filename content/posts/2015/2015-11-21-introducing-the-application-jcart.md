---
title: Introducing the application JCart
author: Siva
type: post
date: 2015-11-21T02:28:23+00:00
url: /2015/11/introducing-the-application-jcart/
post_views_count:
  - 33
categories:
  - Java
  - Spring
tags:
  - E-Commerce

---
As I promised in my article 
[Developing a simple e-commerce application from scratch to production using SpringBoot]({{< relref "2015-11-20-developing-a-simple-e-commerce-application-from-scratch-to-production-using-springboot.md" >}})
, I am starting first post by introducing the application **JCart** that we are going to build.

One of my friend makes quilling toys and she sell them by advertising on Facebook or through word of mouth. Now she is getting more and more customers and she wants to expand her business by going online. So, she asked me to help in setting up a simple e-commerce website. After having some conversations on whether to leverage any existing e-commerce platforms or building a new application, we decided to build a new one with the features we just needed for our need.

> **ATTENTION:** There are so many well established open source e-commerce platforms such as BroadleafCommerce, OpenCart, Drupal Commerce etc. But these systems provide so many features that you may probably don&#8217;t need and hence looks a bit overwhelming. But think twice before building your own. Don&#8217;t Repeat Yourself.

For those of you who are not familiar with what Quilling Art is, have a loot at the following pictures.
These toys are made of some kind of colour paper and other stuff.

<img class="alignnone size-full" src="/images/quilling-6.jpg?resize=225%2C225" alt="quilling (6)" />
<img class="alignnone size-full" src="/images/quilling-14.jpg?resize=190%2C266" alt="quilling (14)" />
<img class="alignnone size-full" src="/images/quilling-4.jpg?resize=195%2C243" alt="quilling (4)" />

<img class="alignnone size-full" src="/images/quilling-5.jpg?resize=184%2C274" alt="quilling (5)" data-recalc-dims="1" />
<img class="alignnone size-full" src="/images/quilling-2.jpg?resize=195%2C243" alt="quilling (2)" data-recalc-dims="1" />
<img class="alignnone size-full" src="/images/quilling-1.jpg?resize=195%2C243" alt="quilling (1)" data-recalc-dims="1" />

Note: These sample images are downloaded from internet and all rights belongs to their respective owners.

## High Level Requirements

After having a brief discussion with our client, following are the high level requirements:

  1. A public facing Shopping Cart website with features: 
      * Customers can browse through products by category or by searching
      * Customers can place orders using CreditCard or Cash On Delivery
      * Customers can login and view order history
      * Customers will receive confirmation emails when order is placed or order status changed
  2. An Administration website which has the following features: 
      * Ability to manage Categories and Products
      * Ability to create one or more users for Administration website
      * Ability to restrict access to certain features based on roles
      * Ability to view customer orders and update the status
  3. A mobile (Android/iOS) application for ShoppinngCart 
      * Not an immediate requirement, but in future we may need it.


### Overview of System Architecture

<img class="alignnone size-medium" src="/images/JCart.png?resize=300%2C197" alt="jcart" />

These are very high-level requirements and design only. In our next post we will go through all these requirement in detail.
