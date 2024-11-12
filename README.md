MERN AUCTION PLATFORM BACKEND

TECHSTACKS:
1.Express
2. node.js
3.Mongodb

Testing :
1.postman
﻿

USER ROUTES
﻿

POST
REGISTER
http://localhost:3000/api/v1/user/register


·
﻿

Body
form-data
profileImage
/C:/Users/DELL/Downloads/john-wick-4-poster.webp
userName
jhon Wick
email
jhon@gmail.com
phone
6369420588
password
12345678
role
Bidder
address
USA
bankAccountName
Jhon Wick
bankAccountNumber
652540775545
bankName
Western Union
easypaisaAccountNumber
0333331235666
paypalEmail
jhon@gmail.com
POST
LOGIN
http://localhost:3000/api/v1/user/login


·
﻿


GET PROFILE
http://localhost:3000/api/v1/user/me


·
﻿

GET
LOGOUT
http://localhost:3000/api/v1/user/logout


·
﻿

GET
FETCH LEADERBOARD
http://localhost:3000/api/v1/user/leaderboard


·
﻿

AUCTION ROUTES
﻿

POST
ADD NEW AUCTION ITEM
http://localhost:3000/api/v1/auctionitem/create


·
﻿

Body
form-data
image
/C:/Users/DELL/Downloads/item.jpeg
title
PS5 Controller
endTime
Sun 11 Nov 2024 21:54:48 GMT+05:30(Indian Standard Time)
startTime
Sun 10 Nov 2024 21:54:48 GMT+05:30(Indian Standard Time)
startingBid
15000
condition
Used
category
Electronics
description
A Very good PS5 controller in white color
GET
GET ALL AUCTION ITEMS
http://localhost:3000/api/v1/auctionitem/allitems


·
﻿

GET
AUCTION ITEM DETAILS
http://localhost:3000/api/v1/auctionitem/auction/:id


·
﻿

Path Variables
id
GET
GET MY AUCTIONS
http://localhost:3000/api/v1/auctionitem/myitems


·
﻿

DELETE
DELETE AUCTION ITEM
http://localhost:3000/api/v1/auctionitem/delete/6730a2dae9bb8ff57eeb2705
Add description

·
﻿

PUT
REPUBLISHITEM
http://localhost:3000/api/v1/auctionitem/item/republish/6730c26b927f3b16ee7e359f


·
﻿

Body
form-data
startTime
Sun 11 Nov 2024 21:54:48 GMT+05:30(Indian Standard Time)
endTime
Sun 13 Nov 2024 21:54:48 GMT+05:30(Indian Standard Time)
BID ROUTES
﻿

POST
PLACE BID
http://localhost:3000/api/v1/bid/place/6730c26b927f3b16ee7e359f
Add description

·
﻿

COMMISSION ROUTES
﻿

POST
POST COMMISSION
http://localhost:3000/api/v1/commission/proof
Add description

·
﻿

SUPER ADMIN ROUTES
﻿

DELETE
DELETE AUCTION ITEM
http://localhost:3000/api/v1/superadmin/auctionitem/delete/6730c26b927f3b16ee7e359f
Add description

·
﻿

GET
GET ALL PAYMENT PROOFS
http://localhost:3000/api/v1/superadmin/paymentproofs/getall


·
﻿

GET
GET PAYMENT PROOF DETAILS
http://localhost:3000/api/v1/superadmin/paymentproof/6730c26b927f3b16ee7e359f


·
﻿

PUT
UPDATE PAYMENT PROOF
http://localhost:3000/api/v1/superadmin/paymentproof/status/update/6730c26b927f3b16ee7e359f
Add description

·
﻿

DELETE
DELETE PAYMENT PROOF
http://localhost:3000/api/v1/superadmin/paymentproof/delete/6730c26b927f3b16ee7e359f
Add description

·
﻿

GET
FETCH ALL FILTERED USERS
http://localhost:3000/api/v1/superadmin/users/getall
Add description

·
﻿

GET
GET MONTHLY REVENUE
http://localhost:3000/api/v1/superadmin/monthlyincome
