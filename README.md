# Daily Task Time Block Scheduler — Built with Amazon PartyRock

A no-code generative-AI application that turns a plain list of daily tasks into a realistic, prioritized, time-blocked schedule. 
Built on **Amazon PartyRock** (powered by Amazon Bedrock foundation models) — no code, pure prompt engineering and widget design.


##  Overview

This project demonstrates how to design, build, and publish a functional generative-AI app **without writing any code**, while applying real prompt-engineering discipline.

The user enters their tasks, available hours, start time, fixed commitments, and priorities. A Bedrock model generates a clean, time-blocked daily schedule that respects fixed appointments, orders work by priority, inserts breaks, and flags anything that won't fit. An interactive chatbot then lets the user adjust the plan conversationally.

The purpose of this repository is to document the **design decisions and prompt engineering** behind the app — PartyRock hosts the app itself.

<img width="1853" height="917" alt="01-app-overview" src="https://github.com/user-attachments/assets/6dc3a40d-3858-4633-bee2-111d8410ba85" />

##  How It's Built 

| Widget | PartyRock Type | Purpose |
|--------|----------------|---------|
| Today's Tasks | Text Input | The day's tasks, one per line |
| Fixed Commitments | Text Input (optional) | Appointments with set times (meetings, school runs) |
| Start Time | Text Input | When the day begins |
| Available Hours | Text Input | Total hours available |
| Priorities | Text Input (optional) | Which tasks matter most |
| Daily Schedule | AI Output | Generates the time-blocked plan |
| Schedule Assistant | Chat Box | Adjusts the plan conversationally |

## Example Output

**Inputs:** Gym, cook food, drop kid, work on AWS projects, lunch, pickup kid, dinner · Start 5:00 AM · 10 hrs available · Priority: AWS projects · Fixed: 5 AM gym, 10 AM drop kid, 4 PM pick kid

**Generated schedule :**

> **Focus of the Day:** Deep work on AWS projects while managing family commitments around school drop-off and pick-up.

## Generated Schedule screenshot

<img width="1531" height="667" alt="02-generated-schedule" src="https://github.com/user-attachments/assets/94919e66-f5f2-4499-9d36-55484f1eb47a" />

## Chatbot for assistance

<img width="1525" height="775" alt="03-chatbot" src="https://github.com/user-attachments/assets/78303914-a821-4c91-aa3d-bae91cd463d6" />

## Widget prompt

<img width="1724" height="873" alt="04-widget-prompt" src="https://github.com/user-attachments/assets/a6130a6c-4362-4cbc-9298-2d37351c2c81" />






