# rn-assignment5-11038463
 
app
app is a mobile application designed with a user-friendly interface, featuring a home screen, cards screen, statistics screen, and settings screen. The application supports a dark and light theme mode that can be toggled by the user.

Table of Contents
Features

Installation

Usage

File Structure

Screens
a. HomeScreen
b. MyCardsScreen
c. StatisticsScreen
d. SettingsScreen

Navigation

Theme Context

Custom Components

Dependencies

Contributing

License


Features
a. Home screen with user greeting and transaction overview.
b. Cards screen for viewing user's cards.
c. Statistics screen for viewing user's financial statistics.
d. Settings screen with options for navigating to various settings pages and toggling between light and dark themes.
e. Persistent theme setting using AsyncStorage.

Screens
a. HomeScreen
The HomeScreen displays a greeting, user profile picture, search button, a card image, action buttons (Send, Receive, Loan, Topup), and recent transactions.

b. MyCardsScreen
The MyCardsScreen displays a placeholder text for user's cards.

c. StatisticsScreen
The StatisticsScreen displays a placeholder text for user's financial statistics.

d. SettingsScreen
The SettingsScreen provides options to navigate to various settings pages and a toggle switch for changing the theme.

e. Navigation
The app uses a bottom tab navigator (react-navigation/bottom-tabs) to switch between the Home, My Cards, Statistics, and Settings screens.

f. Theme Context
The app uses a context provider to manage the theme state (light or dark). The current theme is stored in AsyncStorage to persist between sessions.


Screenshots of the app
![Screenshot 2024-06-26 211325](https://github.com/davidkandaaaa/rn-assignment5-11038463/assets/149037120/113f1431-2130-423c-ac9c-928a0f30a499)
![Screenshot 2024-06-26 211303](https://github.com/davidkandaaaa/rn-assignment5-11038463/assets/149037120/765fc5d8-78d8-4924-abef-d27e2ed47be3)
![Screenshot 2024-06-26 211214](https://github.com/davidkandaaaa/rn-assignment5-11038463/assets/149037120/affd02a9-3276-464e-9328-bf1c56b5b2f8)
![Screenshot 2024-06-26 211145](https://github.com/davidkandaaaa/rn-assignment5-11038463/assets/149037120/c9dc66bf-53fd-4bdd-b8ae-703f6e395051)


Assets
![loan](https://github.com/davidkandaaaa/rn-assignment5-11038463/assets/149037120/08aa00c8-df0a-4c34-87d4-06f1a60bdc7f)
![home](https://github.com/davidkandaaaa/rn-assignment5-11038463/assets/149037120/12d4f311-1b0c-4d96-a9bf-057c41a98d9f)
![grocery](https://github.com/davidkandaaaa/rn-assignment5-11038463/assets/149037120/3d0c3528-ac00-45a7-818d-eed0233c2d60)
![Card](https://github.com/davidkandaaaa/rn-assignment5-11038463/assets/149037120/9f22b393-884d-49b0-86e4-d836a3ed740e)
![apple](https://github.com/davidkandaaaa/rn-assignment5-11038463/assets/149037120/3eb0a563-6bc3-461b-a853-ec17496686ee)
![send](https://github.com/davidkandaaaa/rn-assignment5-11038463/assets/149037120/3e001507-5aaf-4eef-931a-c9002031872a)
![profile](https://github.com/davidkandaaaa/rn-assignment5-11038463/assets/149037120/082ae4e6-a653-404d-8495-beb425a39901)
![topUp](https://github.com/davidkandaaaa/rn-assignment5-11038463/assets/149037120/589cc72e-fefb-4b18-b02f-7746631aef30)
![statictics](https://github.com/davidkandaaaa/rn-assignment5-11038463/assets/149037120/025933e7-e923-4bc6-a1d2-456a22c8930d)
![spotify](https://github.com/davidkandaaaa/rn-assignment5-11038463/assets/149037120/fd8a8efc-4535-43fa-af90-e7ccb2b04809)
![settings](https://github.com/davidkandaaaa/rn-assignment5-11038463/assets/149037120/c5ddd81a-5916-4ebc-bcef-ef5b25f30e8e)
![search](https://github.com/davidkandaaaa/rn-assignment5-11038463/assets/149037120/a7f4e0ff-5596-4279-b769-b402391d32f2)
![recieve](https://github.com/davidkandaaaa/rn-assignment5-11038463/assets/149037120/86a18626-3762-4ee4-b709-87ef4e45c627)
![myCards](https://github.com/davidkandaaaa/rn-assignment5-11038463/assets/149037120/39070b05-4628-401b-affd-34db88c0021c)
![moneyTransfer](https://github.com/davidkandaaaa/rn-assignment5-11038463/assets/149037120/b6cd4510-f9de-44ed-864f-210db9cbc2b9)