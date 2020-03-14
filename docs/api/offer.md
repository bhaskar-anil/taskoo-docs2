---
id: offer
title: Offer APIs
hide_title: true
sidebar_label: Offer APIs
---

## Make an Offer

```json
POST api_endpoint/offers
```

**Request Body**

```json
{
  "user":{},
  "taskId":1,
  "amount":2000,
  "details":"This is a mandatory description of the offer, it is submitted by the person who is making the offer."
}
```
:::tip Notice
Please see the `user` object on [Post Task API](post-task.md)
:::

## Comment on an Offer

```json
POST api_endpoint/offers
```

**Request Body**

```json
{
  "offerId":1,
  "user":{},
  "comment":"this is the comment text for this offer and it can be multiple lines comments"
}
```