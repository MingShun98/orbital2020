# orbital2020
Our SmartTrack Expense Tracker Github.

![SmartTrack UI](/assets/images/UI1.png)
![SmartTrack UI2](/assets/images/UI2.png)
![SmartTrack UI3](/assets/images/UI3.png)


## SmartTrack Expenses Tracker

Mobile Application that allows the user to track their expenses with extended functionalities such as having a shared budget plan and splitting of expenses.
Based entirely in React-Native it is compatible with ios and android devices.

Current status of development as of 23 July 2020:

Mobile Application has been fully set-up


## Technical Information

The app is run entirely on react native. 
The backend, which consists of the authentication methods and the database, is stored on firebase

## Requirements

You need [Expo](https://expo.io/) pre-installed and you’re good to go.
Expo-Cli Version that we used: 3.20.9
Make sure you network connection is private and not public.

## Setup

1. Clone Repository
2. `cd orbital2020`
3. `npm install -g expo-cli` (If you already have Expo installed, you do not need to do this step)
3. `npm i`
4. `expo start`

If expo start fails with error: (Uncaught error: java.net.SocketTimeoutException: connect timed out.), try run with `expo start --tunnel`

## Features

- Add budget plan
- Add expense
- Delete expense
- Sort expense
- Edit budget
- Count percentage costs
- View past portfolio
- "Couple" plan (Shared budget plan)
- Splitting of Expenses

