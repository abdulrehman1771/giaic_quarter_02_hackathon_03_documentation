# Technical Plan

## This documentation describes the flow and Technical Architecture of the marketplace

First of all, we will create a user-friendly UI of our general e-commerce marketplace (Which we created in Hackathon 2). We will use our backend as Headless CMS and for this, we will use a Headless CMS named Sanity, which is a powerful tool for ready-made backend as it provides complete backend package with built-in database which uses GROK queries to fetch data.

## Data Fetching

For data fetching, we will create a schema for our products and will create an Api for that. This will be used for fetching data in Sanity.

## Api Specification

Our Api endpoints will include /products (For fetching all products), /orders (Creating a new order), shipment (For tracking order through third party shipment Api)

.
