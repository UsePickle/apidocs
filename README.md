# `GET` /contacts

*Get a list of contacts for an account.*

### Request:

+ Headers:
    + `x-access-token`: <YOUR ACCESS TOKEN>
    
    *For more information check [[Headers]]*

+ Url Params:
    + `account_id`: 1

+ Body:
    No specific body attributes needed.

***


### Response:

+ Status: **0**

+ Body:
```

```
***


# `POST` /contacts

*Create a contact for an account.*

### Request:

+ Headers:
    + `x-access-token`: <YOUR ACCESS TOKEN>
    
    *For more information check [[Headers]]*

+ Url Params:
    No specific query parameters needed.

+ Body:
```
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
```

***




