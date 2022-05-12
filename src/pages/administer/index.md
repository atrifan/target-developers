---
description: Find Adobe Target APIs, including the Admin, Delivery, Reporting, and Profile APIs.
title: Where Can I Find Target API and SDK Documentation?
feature: APIs/SDKs
role: Developer
exl-id: 2a0232cc-9a6a-42f4-afb6-4b3e2b13939c
---
# Adobe Target API overview
 
Adobe Target APIs can be grouped according to type: Admin, Delivery, Reporting, and Profile APIs. That being said, in terms of APIs used to **administer** Adobe Target, the Admin and Profile APIs are often grouped together or referred to as a single API ("Admin & Profile API," "Admin/Profile API"), and the Reporting and Recommendations APIs may be considered to be types of Admin API. By contrast, the Delivery API is the one API used to **implement** Adobe Target.
 
|API type|What it enables you to do|Download link|Other helpful links|
| --- | --- | --- |--- |
|Admin|Create, modify, and delete activities, audiences, offers, and other objects (including Recommendations entities, criteria, designs, and so on. The Recommendations APIs are a type of admin API.)|<UL><li>[Target Admin API Postman Collection](https://developers.adobetarget.com/api/#admin-postman-collection)</li><li>[Recommendations API Postman Collection](https://developers.adobetarget.com/api/recommendations/#section/Postman)</li></UL>|[Use Recommendations APIs - Tutorial](api-guides/recs-api/)|
|Delivery|Retrieve optimized and personalized content from Target for delivery to an end user.|[Target Delivery API](implement/delivery-api/)||
|Reporting|Export activity results and other reporting results.|Reporting APIs are included within the [Target Admin API Postman collection](https://developers.adobetarget.com/api/#admin-postman-collection).||
|Profile|Retrieve and modify user profiles stored in Adobe Target.|[Target Profile API Postman Collection](https://developers.adobetarget.com/api/#profiles)||

<InlineAlert variant="info" slots="text"/>

There are important distinctions between Target Admin APIs (including the Recommendations APIs) and Target Delivery APIs:

* Admin APIs let you configure various aspects of Target that you could also configure in the Target UI. Admin APIs require authentication.

* Delivery APIs let you retrieve content. Delivery APIs do not require authentication.

To use Target Admin APIs, you first need to configure authentication using Adobe I/O. For more information, see [How to Configure Authentication](../guides/index.md).