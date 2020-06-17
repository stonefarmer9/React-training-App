# React-training-App
A series of user stories to test peoples learning of react. The idea is simple, give beginners to react a series of user stories to test and exercise their new found skills


## The Brief

The great Elminster Aumar has given up his life of adventuring and wants to settle in Baldurs gate and start an online shop. He has contacted you, via magical mean, to create the shop for him. He wants shoppers to be able to land on his site and see a welcome message. He wants to see a button saying start shopping the user clicks to go to a catalogue of items. He has listed his inventory and the prices below and wants them all to show. 

Each item should show the name, the thumbnail and the price. When the user clicks the items he wants something to drop down below and show more information. In this div he wants there to be an add to basket button. 

On the right hand side of the page he wants the current basket to show as a list showing the name, the quantity, the thumbnail and the price in a list. With the current total displayed at the bottom. 

Fortunately Baldurs gate government doesn't tax online shops so theres no tax to worry about. 

At the bottom on the basket he wants a checkout button. When click it takes the user to a checkout screen where they see the full list again. Here they can remove items or edit the quantity. As well as cancel the order or confirm and pay. 

Once they pay he wants a screen to show thanking the user for their purchase and advising them how long his small army of delivery pixies will take to get it to them. 

## IMPORTANT NOTES - READ BEFORE STARTING

- The aim of this exercise is to stretch your react skills and get comfortable with the ideas of state, props and lifecycle methods. 
- There is no need to create an actual payment service (unless you feel brave) We can assume Elminster magically takes their money on a successfuly order.
- I have made a list of items to sell in JSON. It can be found in this repo - inventory.JSON

- Remember this is about solidifying knowledge and learning a couple of new concepts, it is important to have fun doing this and to keep positive! If you are truely stuck reach out to your local FE developer on slack, teams or DPN. We are all here to help you out


## User Stories

```
As a User
So I know what page I am on
I want to see a welcome screen confirming I am on Elminsters shop
```

```
As a User
So I can look at the catalogue of Items
I want there to be a clear button to click to take me to the cataglogue
```

```
As a User
So I know what is available to buy
I want to see a grid of available items
```

```
As a user
So I know what each item is
I want each item card to show a name, price and thumbnail
```

```
As a user
So I can understand what each item does
I want to be able to click on it and see more information about the product
```

```
As a user
So I can buy an item
I want there to be an Add to basket button below the description
```

```
As a user
So I know the item is selected
I want to see it appear in a basket bar on the right side of the screen
```

```
As a user
So I can buy multiple items
I want to be able to add many items to the basket and see them in the basket bar
```

```
As a user
So I know I have not gone over budget
I want the basket bar to display the individual prices, quantity and total price of the items in the basket
```

```
As a user
So I can complete my purchase
I want to see a checkout button in the basket bar
```

```
As a user
So I can easily fix mistakes
I want to be able to edit the quanity of items in the basket
```

```
As a user
So I can easily fix mistakes
I want to be able to delete things from the basket
```

```
As a user
so I can buy the products I have chose
I want to see a confirm purchase button on the checkout screen
```

```
As a store manager
So I can manage expectations
I want an delivery estimate to be given after checking out
```

```
As a store manager
So my customers feel valued
I want them to see a thank you page after checking out
```
## Note on styling

- This exercise is about react functionality more than styling. That being said it would be a good idea to try and style this page for your own learing. Please feel free to go crazy and style it as much as you would like!


I hope this exercise has been helpful and if you can think of any feedback feel free to post comments or open a PR, we are always looking to expand and improve our learning process
