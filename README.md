# fortAnalytics — Fitness Data Analysis Web App

An interactive data analytics web application designed to explore and visualise personal fitness data. Built with Python, Plotly Dash and SQL, fortAnalytics turns first-person workout records into clear visualisations and trends, with the goal of supporting more data-driven training decisions. Future plans include expanding into an iOS application for real-time data entry.

---

## Overview

fortAnalytics was built to make collecting and understanding personal fitness data convenient from a first-person perspective. Rather than relying on intuition, the app surfaces workout patterns and progress over time so that training adjustments can be made on the basis of evidence rather than guesswork. The project also serves as a practical exercise in building a full data pipeline — from secure data access, through processing with pandas, to interactive visualisation in Dash.

---

## Usage and Context

### Workout Visualisation

The core of the app visualises workout patterns and trends over time, making it easy to see how training has evolved across sessions.

- **Charts** — Interactive Plotly visualisations of workout data.
- **Trends** — Patterns surfaced over time rather than read from raw records.

### Progress Tracking

Beyond individual sessions, the app tracks progress across key fitness metrics so improvement (or stagnation) is visible at a glance.

- **Metrics** — Progression followed across the fitness measures that matter.
- **Insight** — Designed to reduce human error in training by making decisions data-driven.

### Secure Data Access

Personal data is accessed securely rather than hard-coded, keeping credentials out of the codebase.

- **Environment variables** — Configuration and secrets managed via `dotenv`.
- **Database** — Data stored and queried through PostgreSQL.

---

## Technology Stack

### Frontend

The interface for exploring and visualising fitness data.

- **Dash (Plotly)** — Interactive dashboard and charting framework.
- **CSS** — Styling for the dashboard layout.

### Backend

Data storage and the processing pipeline behind the app.

- **Python** — Core application and data-processing logic.
- **PostgreSQL** — Relational database storing fitness records.

### Data Processing

Transforming raw records into analysis-ready data.

- **pandas** — Cleaning, shaping and aggregating fitness data.
- **sqlalchemy** — Database connection and query layer.

### Environment Management

- **dotenv** — Loads environment variables for secure configuration.

---

## Motivation

- Understanding how to make data collection convenient from a first-person perspective.
- Working with data that is interesting and relatable to personal hobbies.
- Reducing human error in training by making data-driven decisions.

