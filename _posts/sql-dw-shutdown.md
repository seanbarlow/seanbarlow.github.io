---
layout: post
title:  "Day 3: Using automation to shutdown Azure Synapse Analytics"
date:   2019-12-22 09:06:12 -0600
categories: [azure, automation, synapse analytics]
tags: [azure, azure synapse analytics, sql, automation]
---

## Overview

We are going to be creating a PowerShell script which will shutdown our Azure Synapse Analytics Data Warehouse. We will be automating the shutdown using Azure Automation and a RunBook. The RunBook will be scheduled to run every evening at 5:00 pm CST. This will allow us to save money when the warehouse is not in use.

## Steps

1. Set up automation account
2. Create script to shutdown the data warehouse
3. Set up and schedule the runbook
4. Test
