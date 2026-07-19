# food-delivery-cleaning-validation
A data cleaning and validation pipeline for a multi-branch food delivery dataset, using graph algorithms (Djikstra) to cross-check whether reported delivery distances and fees were actually consistent with the provided road/location network information and delivery fee information..

## Overview

Delivery datasets often contain unreliable self-reported fields such as distances and fees that don't line up with the actual geography. This project cleans and validates a 3-branch food delivery dataset, and uses Dijkstra's algorithm as an independent check by computing shortest-path distances between delivery points and flagging records where the reported distance/fee didn't match what the network implied.

## What we did

- Cleaned, imputed, and validated data across 3 restaurant branches in Python
- Applied Dijkstra's algorithm to independently verify reported delivery distance and fee data against the actual location network
- Detected and removed outliers, and resolved data quality issues across multiple linked files (dirty data, missing value data, outliers data)

## Tools

- Python; pandas, numpy, matplotlib, folium (map), sklearn (prediction model)
- NetworkX (graph construction & Dijkstra's algorithm) ·

## Repository contents

- `notebooks/` — cleaning, imputation, and validation notebooks

## My contribution

This was a group assignment for the Data Wrangling unit at Monash University.
My role focused on handling dirty and outlier data file, recalculating distance, delivery fee, and customer loyality validation.

## Team

- Mutiara Hernowo
- Stefanus Felix
- Mutia Salsabila
- Ferina Damamain
- Catharina

## Academic context

Group assignment, Data Wrangling unit, Monash University, 2026. Shared here with
team consent for portfolio purposes.
