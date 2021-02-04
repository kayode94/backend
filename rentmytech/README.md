WORKING END POINTS FOR USERS

GET http://localhost:2019/users/users

GET http://localhost:2019/users/user/{userid}

GET http://localhost:2019/users/user/name/{userName}

POST http://localhost:2019/users/user

PATCH http://localhost:2019/users/user/{id}

DELETE http://localhost:2019/users/user/{id}

//////////////////////////////////////////////////////////////

WORKING END POINTS FOR ITEMS

GET http://localhost:2019/items/items

GET http://localhost:2019/items/{itemid}

GET http://localhost:2019/items/item/name/{itemName}

GET http://localhost:2019/items/items/namelike{itemNameSubstring}

POST http://localhost:2019/items/item

PUT http://localhost:2019/items/item/{itemid}

DELETE http://localhost:2019/items/item/{itemid}

/////////////////////////////////////////////////////////////////////////////

WORKING END POINTS FOR USEREMAIL

GET http://localhost:2019/useremails/useremails

GET http://localhost:2019/useremails/useremail/{emailid}

DELETE http://localhost:2019/useremails/useremail/{emailid}

PUT http://localhost:2019/useremails//useremail/{emailid}/email/{emailaddress}

POST http://localhost:2019/useremails/user/{userid}/email/{emailaddress}

//////////////////////////////////////////////////////////////////////////////////////

WORKING END POINTS FOR ROLE

GET http://localhost:2019/roles/roles

GET http://localhost:2019/roles/role/name/{roleName}

POST http://localhost:2019/roles/role

PUT http://localhost:2019/roles/role/{roleid}

LOGOUT END POINT WORKS

GET http://localhost:2019/logout



SIGN IN END POINTS WORKING

PATCH http://localhost:2019/items/item/{itemid} WORKING

PUT http://localhost:2019/users/user/{userid} WORKING
