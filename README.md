# Shopify ↔ Bol.com Price Sync Automation

## Problem
Managing prices manually across Bol.com and Shopify leads to errors, delays, and lost revenue.

## Solution
An automated workflow that synchronizes product prices and promotions from Bol.com to Shopify in real time.

## Automation Logic
- If a product has an active promotion on Bol.com:
  - Shopify price = promotion price
  - Shopify compare-at price = regular price
- If no promotion exists:
  - Shopify price = regular price
  - Shopify compare-at price cleared

## Tools Used
- Make.com
- Bol.com Retailer API
- Shopify Admin API

## Outcome
- Eliminated manual price updates
- Prevented pricing inconsistencies
- Scales across large product catalogs

## Notes
Client credentials and sensitive data have been removed.
