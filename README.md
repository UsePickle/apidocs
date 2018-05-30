# `GET` /contacts?account_id=1

+ Request

    + Headers

            x-api-access-token: <YOUR API TOKEN HERE>

+ Response 200 (application/json; charset=utf-8)

    + Body

            {
                "contacts": [
                    {
                        "email_hash": "",
                        "nickname": "Testing New Contact last name!",
                        "id": 7,
                        "first_name": "James",
                        "last_name": "Bond",
                        "email": "james@007.com",
                        "background_info": "Prefers his martinis shaken, not stirred.",
                        "website_url": "http://007.com",
                        "facebook_url": null,
                        "twitter_username": null,
                        "linkedin_url": null,
                        "phone_number": null,
                        "user_id": 7,
                        "account_id": 1,
                        "tags": null,
                        "updated_at": "2018-04-30T02:14:51.195Z",
                        "created_at": "2018-04-30T02:14:51.195Z",
                        "Addresses": []
                    }
                ],
                "meta": {
                    "total": 1
                }
            }


*
# `POST` /contacts

+ Request (application/json; charset=utf-8)

    + Headers

            x-access-token: <YOUR ACCESS TOKEN>

    + Body

            {
                "contact": {
                    "first_name": "James",
                    "last_name": "Bond",
                    "email": "james@007.com",
                    "background_info": "Prefers his martini's shaken, not stirred.",
                    "twitter_username": "007",
                    "website_url": "http://007.com"
                }
            }

+ Response 200 (application/json; charset=utf-8)

    + Body

            {
                "contact": {
                    "email_hash": "87a8e3cdc3c7a51feb0cc1ddf62294c2",
                    "nickname": "James Bond",
                    "id": 13312,
                    "first_name": "James",
                    "last_name": "Bond",
                    "email": "james@007.com",
                    "background_info": "Prefers his martinis shaken, not stirred.",
                    "twitter_username": "007",
                    "facebook_url": null,
                    "linkedin_url": null,
                    "website_url": "http://007.com",
                    "phone_number": null,
                    "account_id": 1,
                    "user_id": 7,
                    "updated_at": "2018-05-30T18:21:07.463Z",
                    "created_at": "2018-05-30T18:21:07.463Z",
                    "tags": null
                }
            }

***




