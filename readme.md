# Backend Lumen

Require : PHP: ">=7.1.3",
          laravel/lumen-framework: 5.8.*

# API URl

## Get User : GET http://localhost/user_management_backend/public/user

## ADD User : POST http://localhost/user_management_backend/public/adduser
	Content-Type:application/json
	{
	    "name": "Name",
	    "lastname": "Lastname",
	    "sex": "Sex",
	    "birthday": "2019-01-01",
	    "email": "test@test.com",
	    "address": "99/99",
	    "telnumber": "0999999999"
	}

## Del User : POST http://localhost/user_management_backend/public/deluser
	Content-Type:application/json
	{
	    "id": 7
	}

## UpdTE USER : POST http://localhost/user_management_backend/public/updateuser
	Content-Type:application/json
	{
		"id": "0",
	    "name": "Name",
	    "lastname": "Lastname",
	    "sex": "Sex",
	    "birthday": "2019-01-01",
	    "email": "test@test.com",
	    "address": "99/99",
	    "telnumber": "0999999999"
	}