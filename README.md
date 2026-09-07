# Robotic Astro Integrated With Agentforce & Slack Via Headless360

## Project Overview

This project demonstrates an intelligent automation solution that integrates
Salesforce Agentforce and Slack with Robotic Astro through Headless360.

The solution allows users to initiate robotic processes using a conversational
interface. Agentforce understands the request, Salesforce validates and
orchestrates the process, Headless360 invokes Robotic Astro, and the execution
result is returned to Salesforce and communicated to the user.

## Main Components

- Salesforce
- Agentforce
- Slack
- Headless360
- Robotic Astro
- Salesforce Flow and/or Apex
- Integration APIs or webhooks

## High-Level Workflow

User
  -> Slack or Salesforce
  -> Agentforce
  -> Salesforce Flow/Apex
  -> Headless360
  -> Robotic Astro
  -> Target Application
  -> Headless360
  -> Salesforce
  -> Slack or Agentforce

## Key Features

- Conversational request initiation
- AI-based intent understanding
- Salesforce-based validation and orchestration
- Robotic process execution
- Process status tracking
- Success and failure notifications
- Integration between Salesforce, Headless360, and Robotic Astro

## AI Usage

Agentforce is used to understand natural-language requests, collect missing
information, select the appropriate action, and communicate results.

Deterministic tasks such as validation, record updates, routing, logging,
and integration processing are handled by Salesforce Flow and/or Apex.

## Repository Contents

- Salesforce implementation and metadata
- Integration payload examples
- Robotic Astro process description
- Architecture diagrams
- Screenshots and test evidence
- Setup and demonstration instructions

## Demonstration

A user submits a request through Slack or Salesforce. Agentforce interprets
the request and invokes the relevant Salesforce action. Salesforce sends the
request to Headless360, which triggers Robotic Astro. The result is returned
to Salesforce and displayed to the user.

## Security Notice

This repository does not contain passwords, security tokens, API keys,
OAuth tokens, Slack tokens, private webhook URLs, or other confidential
credentials.

## Documentation

Detailed project documentation is available here:

https://docs.google.com/document/d/1Jgte77Xu8YAn2J3zVe3oDhsyvx-gRNPEjaAUbIElD3w/edit?hl=en&tab=t.0

## Demo Video

https://drive.google.com/file/d/1UbiHEZxaqz6rzLAeXwASLMNMEvos18Wt/view?usp=drive_link
