# Smart Traffic Speed Violation Detection Platform on Google Cloud
## Overview

This project implements a cloud‑native, event‑driven IoT solution for detecting traffic speed violations in real time using Google Cloud Platform. The platform ingests data from roadside cameras and sensors, evaluates violations, stores evidence securely, and notifies vehicle owners.

#### Architecture Highlights

Serverless ingestion using Cloud Run

Event streaming with Google Cloud Pub/Sub

Real‑time processing via Cloud Functions

Immutable evidence storage in Cloud Storage

Analytics and reporting using BigQuery

#### Architecture Flow
![Architecture-Flow](architecture/architecture-diagram-(5).gif).


#### Technology Stack

Google Cloud Run

Google Cloud Pub/Sub

Cloud Functions (2nd Gen)

Google Cloud Storage

BigQuery

Firestore / Cloud SQL

#### High‑Level Flow

Traffic camera captures speed and image

Event sent to Cloud Run ingestion API

Event published to Pub/Sub

Cloud Function evaluates speed violation

Raw data stored in Cloud Storage

Processed data stored in BigQuery

Notification sent to vehicle owner


#### Deployment (High Level)

Deploy ingestion API to Cloud Run

Create Pub/Sub topics and subscriptions

Deploy Cloud Functions for processing

Configure Cloud Storage buckets

Create BigQuery datasets and tables

#### Use Cases

Smart city traffic enforcement

Road safety analytics

Public sector digital transformation

**Author**

Cloud Solutions Architect
