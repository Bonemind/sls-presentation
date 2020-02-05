## In practice

---

## Overview

 - Thumbnail resizer
 - Architecture
 - What it looks like
 - Services
 - Code

---

## Thumbnail resizer

 - Upload image to a bucket
 - Run a lambda to resize
 - Store the resized thing and put metadata in DynamoDB
 - List the images using API Gateway

---

## Diagram

<img src="images/serverlessdemo.png" />

---

## Let's see it

---

## S3
<hr />

Simple Storage Service

 - Blob storage
 - Key-value store
 - Blobs up to 5TB
 - Can serve static sites

---

## DynamoDB
<hr />

NoSQL KV-Store

 - Serverless scaleable Nosql datastore
 - JSON based
 - Schemaless

---

## Lambda
<hr />

Serverless functions

 - This is where you put your code
 - Call a function, that's all
 - Runs trigger based

---

## API Gateway
<hr />

HTTP request handler

 - Maps HTTP requests to services
 - Supports auth
 - Built in throttling and monitoring

---

## To the code

---

## Getting your hands dirty

 - Register for an account
 - Focus on what you need, don't learn it all at once
 - The docs are good, read them
 - If your example isn't working, check your permissions
 - Understand your service's pricing models
 - Set up billing alarms

