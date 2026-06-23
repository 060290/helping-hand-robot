# Helping Hand Robot

An assistive wheeled robot that follows a wheelchair user, responds to voice commands, and helps retrieve objects.

---

## Hardware

- **Platform:** Yahboom ROSMASTER X3
- **Compute:** NVIDIA Jetson Orin NX

## Tech Stack

| Layer | Tools |
|---|---|
| Middleware | ROS2 Humble |
| Language | Python |
| Vision | OpenCV, MediaPipe, YOLO |
| Sensors | LiDAR, Depth Camera |

---

## Goals

- **Person/wheelchair following** — robot autonomously tracks and follows a wheelchair user at a safe distance
- **Obstacle avoidance** — detects and navigates around obstacles in real time using LiDAR + depth camera
- **Voice commands** — responds to spoken commands: `"follow me"`, `"stop"`, `"come here"`
- **Object carrying/retrieval** — assists user by fetching or transporting small objects on command

---

## Project Status

**Phase 1 — Setup** (June 2025)

Currently: hardware assembly, ROS2 environment configuration, and initial sensor testing.

---

## Build Log

Weekly notes on what's working, what's broken, and what's next.

→ [docs/build-log.md](docs/build-log.md)

---

## Demo Videos

Coming soon — check back after July 2025.

---

## User Research

Research with wheelchair users, disabled students, and caregivers to validate whether this problem is real and worth solving.

→ [docs/user-research.md](docs/user-research.md)
