# Amazon Vine Analysis

## Overview
SellBy stakeholders requested an analysis of Amazon reviews written by members of the paid Amazon Vine program, to determine if there was any bias in the reviews. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.

A Shoes dataset was chosen to analyze, containing reviews of various shoe products. PySpark was used to perform the ETL process to extract the shoes dataset, transform the shoes data, connect to an AWS RDS instance, and load the transformed shoes data into pgAdmin. Next, PySpark was used to determine if there is any bias toward favorable reviews from Vine members in the shoes dataset.

This new assignment consisted of two technical analysis deliverables:
- Deliverable 1: Perform ETL on Amazon Product Reviews of shoes products
- Deliverable 2: Determine Bias of Vine Reviews of shoes products

## Results
