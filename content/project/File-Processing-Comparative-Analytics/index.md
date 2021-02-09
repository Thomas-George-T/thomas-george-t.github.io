---
title: File Processing Comparative Analytics
summary: Determining which programming languages and execution engines are the quickest or the slowest at processing files
tags:
- Big Data Analytics
- Hadoop
- Spark
- Python
date: "2020-04-01T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: https://github.com/Thomas-George-T/File-Processing-Comparative-Analytics

image:
  caption: '[Photo by Luke Chesser on Unsplash](https://unsplash.com/s/photos/data?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText")'
  focal_point: Smart
---
We conduct a Data Science experiment *(of sorts)* where we compare and benchmark popular languages and execution engines. We find out which languages among **Java**, **Scala** and **Python** is the quickest or slowest. Similarly, we compare and benchmark execution engines like **Hadoop** and **Spark**.

**Observations**

For programming languages, we observe that Python has the least execution time for small and large files while Scala has the largest execution time. Interestingly, Scala takes 7 seconds more for processing the small file rather than the larger file.

For execution engines, we observe that the Spark engine has the least execution time while Hadoop’s Mapreduce engine has the highest execution time. This is in line with the claim that Spark is 100 times quicker than Hadoop.