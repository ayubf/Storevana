# Storevana

An online store with buyers and shoppers 

## Features

- List new product (stock, product image(s), price, description, reviews) 
- Purchase product 
- Rate product (Leave a review, stars)
- CRUD User
- Dark mode

## Pages

- Login
- Update user info 
- Product page
- Create product
- Update product
- Cart 
- Past purchases
- User shop 
- Search users and products 

## Models 

- Users { password, username } <- Figure out images
- Products { name, description, price, user_id  } <- Figure out images
- Purchases { user_id, product_id, timestamp, cost }
- Review { user_id, product_id, timestamp, stars, timestamp }

## Stack
- Frontend: Typescript, React, Redux, Jest
- Backend: Ruby, Rails, RSpec
- Database: PostgreSQL