![Project Logo][project_logo]
---

<h4 align="center">Analyzing & Visualizing Patient Waitlist Data with <a href="https://en.wikipedia.org/wiki/Microsoft_Power_BI" target="_blank">Power BI</a></h4>


<p align="center">
  <a href="#overview">Overview</a> •
  <a href="#prerequisites">Prerequisites</a> •
  <a href="#architecture">Architecture</a> •
  <a href="#demo">Demo</a> •
  <a href="#support">Support</a> •
  <a href="#license">License</a>
</p>

## Overview

This project aims to create a dashboard that tracks and analyzes patient waitlists in healthcare settings, specifically for inpatient and outpatient categories. The dashboard will provide insights into current waiting lists, historical trends, and a detailed analysis at the specialty and age-profile levels.

## Key Components

**Requirement Gathering:**

**Identify Stakeholders**: Establish a point of contact with relevant stakeholders to understand project goals and define the scope.

**Understand Business Objectives:** Define the objectives that the dashboard needs to meet for efficient tracking and analysis.

**High-Level Data Study:** Perform an initial analysis of available data to identify patterns and trends.

**Define Scope:** Clearly define the data range and metrics required for the analysis.

## Overall Objectives

**Project Goals:**

Track the current status of the patient waiting list.

Analyze the monthly trends in waiting lists for inpatient and outpatient categories.

Provide a detailed specialty-level and age-profile analysis.

**Data Scope:**

The dashboard covers data from 2018 to 2021, providing an extensive range for analysis.
**Metrics Required:**

Average and median waiting list times.
Current total waiting list.
**Views Required:**

A summary page to offer a high-level overview.

A detailed page for granular analysis to drill down into specifics.


## Architecture

The project architecture is quite straight forward and can be explained through the below image:

![Process_Architecture].[process_workflow]

This architecture illustrates how Power BI Desktop connects to multiple Excel files, enabling seamless data import. After loading, the data is transformed in Power Query, allowing for efficient cleaning, shaping, and aggregation before visualizing it in Power BI reports.

## Demo

The interactive Power BI dashboard can be viewed here:

[![Power BI Dashboard][dashboard_image]][dashboard_link]

<!-- Image Links -->

[project_logo]: Project_logo.png
[process_workflow]: Workflow.png
[dashboard_image]: https://github.com/YashwanthNomula/Healthcare-Dashboard/blob/main/Summary_Page.png

<!-- Profile Links -->
