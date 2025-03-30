# README for RoundUpX

## Overview

**RoundUpX** is a financial savings application designed to help users save effortlessly by rounding up spare change from their UPI transactions. The app transforms everyday spending into structured savings, enabling users to achieve their financial goals without altering their daily habits. RoundUpX consists of two repositories: **RoundUp-Backend** and **RoundUp-Frontend**, leveraging Go for backend development and Expo for the frontend.

This app was created as a part of Inspirathon '25, an all-india 24-hour hackathon conducted as a part of [INIZIO](www.inzio.org.in). This project was among the top 5 projects out of 150+ teams and 500+ participants from all over India. More details can be found [here](https://github.com/RoundUpX/.github/blob/main/Inspirathon%20'25%20-%20Team%20RoundUp.pdf)

---

## Features

### Key Features:
- **Automatic Rounding:** Automatically rounds up every UPI transaction and saves the spare change.
- **Savings Wallet:** Transfers rounded-up amounts into a dedicated savings wallet.
- **Goal Tracking:** Allows users to set savings goals and track progress visually through a dashboard.
- **Customizable Preferences:** Users can edit preferences for categories, goals, and target dates.

### Benefits:
- Effortless savings without disrupting daily spending habits.
- Smart micro-investments that grow over time.
- Reduces impulse spending by making every transaction contribute to savings.
- Easy-to-use interface for tracking savings progress.

---

## Tech Stack

### Backend:
- **Language:** Go
- **Database:** PostgreSQL

### Frontend:
- **Framework:** React
- **Platform:** Expo (for cross-platform mobile development)

---

## Installation and Setup

### Backend (RoundUp-Backend):
1. Clone the repository:
   ```bash
   git clone https://github.com/your-org/RoundUp-Backend.git
   ```
2. Navigate to the project directory:
   ```bash
   cd RoundUp-Backend
   ```
3. Install dependencies:
   ```bash
   go mod tidy
   ```
4. Set up the PostgreSQL database and configure the connection in the `.env` file.
5. Run the server:
   ```bash
   go run main.go
   ```

### Frontend (RoundUp-Frontend):
1. Clone the repository:
   ```bash
   git clone https://github.com/your-org/RoundUp-Frontend.git
   ```
2. Navigate to the project directory:
   ```bash
   cd RoundUp-Frontend
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Start the Expo development server:
   ```bash
   npm expo start
   ```

---

## How It Works

1. **Link UPI Account:** Users connect their UPI account through the app.
2. **Automatic Rounding:** Every transaction is analyzed, rounded up, and saved.
3. **Savings Wallet:** Spare change is transferred automatically into a wallet.
4. **Track Progress:** Users can monitor their savings growth and progress toward goals via an intuitive dashboard.

---

## Target Audience

RoundUpX is tailored for:
- Millennials and Gen Z individuals.
- School and college students.
- First-time investors.
- Freelancers looking for effortless saving solutions.

---

## Why RoundUpX?

With rising digital payment adoption, RoundUpX provides a seamless solution for passive savings by leveraging micro-investing strategies. It empowers users to build wealth over time while reducing impulse spending.

---
