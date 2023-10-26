# Race-Timer-Application

## Introduction

Athlete Race Manager is a Windows Forms application built using Visual Basic.NET. This application is designed to help you manage and display information about athletes, their races, and the results of those races. It provides features for defining the number of lanes for a race, inputting athlete information, recording race times, and displaying the results, including medals and national flags.

## Features

### Lane Definition

- Select the number of lanes for a race using radio buttons.
- Input athlete information, including name and country, in the Athlete Tab.
- Utilizes LaneDefinitionControl to store athlete information for each lane.
- The Athlete Tab displays labels, text boxes for athlete names, and country selection in combo boxes.

### Race Definition

- The Race Tab displays athlete information (name and country) based on the number of lanes selected.
- Information from the Athlete Tab is transferred to the Race Tab for each lane.
- RaceDefinitionLane is used to store race information for each lane, including athlete names and country flags.

### Race Timing

- The program includes a timing feature in the Race Tab that allows users to start and stop a timer for each lane.
- The time is displayed in the format HH:MM:S and is updated in real-time.
- Users can assign random timings to athletes, simulating a race.
- The athletes' times are sorted, and medals are awarded based on the results.

### Medal Assignment

- Medals (Gold, Silver, Bronze) are assigned to the top three athletes in the results tab.
- National flags of athletes are displayed along with their names.
- The program plays the national anthem for the second-place athlete based on their country.

### Country Flags

- The program supports displaying national flags for athletes based on their selected countries.
- Country flags are displayed using PictureBox controls.
- Flags are displayed for the top three athletes in the results tab.

## Usage

To use the program, follow these steps:

1. Select the number of lanes using the radio buttons in the Athlete Tab.

2. Enter athlete information, including names and countries, for each lane.

3. Switch to the Race Tab to display athlete information and start the timer.

4. Click the "Start" button to start the timer for each lane.

5. Click the "Stop" button for each lane to record their times.

6. The program will automatically assign random times to athletes for demonstration purposes.

7. Switch to the Results Tab to view the sorted results and medal assignments.

8. National flags are displayed along with athlete names for the top three athletes.

9. The program will play the national anthem for the second-place athlete.

## Customization

You can customize the program by adding more countries and their respective national anthems. You can also modify the appearance of the user interface to match your preferences.

## Dependencies

This project uses the System.Media library for playing audio and the Windows Forms framework for the graphical user interface. It also includes embedded resources for country flags and national anthems.

## Author

Jasmeet Salh
