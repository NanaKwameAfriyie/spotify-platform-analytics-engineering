# Spotify Platform Analytics Engineering

A portfolio analytics engineering project inspired by Spotify's Analytics Engineer II role.

This project demonstrates how platform signals can be transformed into trusted analytical data products for understanding developer productivity, platform health, CI/CD reliability and ML/AI platform adoption.

## Project Scenario

In this scenario, I act as an Analytics Engineer supporting a platform organisation. The goal is to translate raw engineering, deployment, incident and ML platform usage data into reliable, well-modelled datasets that help technical and non-technical stakeholders make better decisions.

## Job Description Skills Demonstrated

- SQL-based analytics engineering
- dbt-style data modelling
- Cloud data warehouse thinking, using BigQuery-style modelling patterns
- Data quality testing and documentation
- CI/CD checks using GitHub Actions
- Developer productivity and platform health metrics
- Dashboard-ready data product design
- Stakeholder-focused communication

## Planned Data Model

The project will model raw platform signals into staging, intermediate and mart layers.

Planned source-style datasets:

- Pull request activity
- Deployment events
- CI build and test results
- Platform incidents
- Engineering team ownership metadata
- ML/AI platform usage events

Planned analytical outputs:

- Developer productivity metrics
- Platform health metrics
- CI/CD reliability metrics
- ML/AI platform adoption metrics
- Dashboard-ready summary tables

## Project Structure

```text
data/
  raw/
  processed/
models/
  staging/
  intermediate/
  marts/
scripts/
docs/
tests/
.github/workflows/