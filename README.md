# Itembase's DataConnect API

## Bugs or feature requests
The purpose of this repository is to work as the public issue tracker for [itembase's DataConnect API](https://api.itembase.com/api). If you've found a bug in the API, or have ideas on how we could improve it, please [create an issue](https://github.com/itembase/data-connect-api/issues). It's greatly appreciated.

[Open bug tickets](https://github.com/itembase/data-connect-api/labels/bug) | [Open feature requests](https://github.com/itembase/data-connect-api/labels/enhancement) | [All](https://github.com/itembase/data-connect-api/issues) 

If you have ideas, bug reports, or any other type of feedback to us that doesn't relate to the DataConnect API, please submit these via an e-mail to support@itembase.biz.

## Stay tuned in

For API announcements, visit our [developers notes page](https://itembase.github.io/api-notes). We plan on setting up a newsletter soon.

## Bug report format
Please provide a **description** including when the bug occurred and the API endpoints involved. If you believe the bug is related to authentication or authorization, please also provide the scopes given to your application.

Also include necessary **steps to reproduce** the issue. Finally, please provide the difference between the **expected behaviour** and **actual behaviour** of the API.

## Example

>Cannot retrieve products for user with user ID "^"

>Issue found on February 19th 2015.

>Endpoint(s): /users/<user_id>/products
Scope(s): User.Minimal

>Steps to reproduce: Use curl as described in the guide http://itembase.github.io/api-guides/#getting-all-new-and-updated-products

>Expected behaviour: A set of products per connected platform of the user.

>Actual behaviour: 500 Server Error (consistently)

## Acknowledgement

This text is inspired by [Spotify's Web API repository](https://github.com/spotify/web-api).
