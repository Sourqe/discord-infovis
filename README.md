# Discord InfoVis

Information visualization of direct messages between two users on Discord. An IPython notebook document is used so that the infographics can easily be modified and extended.

## Visualizations

The following types of visualization are presented in the project:

- Number of messages sent per person (pie chart)
- Number of messages sent per day (scatter plot)
- Number of messages sent per month (bar plot)
- Number of messages sent per month per person (bar plot)
- Number of messages sent per day (bar plot)
- Number of messages sent per day per person (bar plot)
- Number of messages sent per hour (bar plot)
- Number of messages sent per hour per person at different times (e.g., GMT+2 and GMT+12) (bar plot)
- Message length per person (< 50 characters)
- Message length per date (scatter plot)
- Type of message sent (pie chart)
- Most used words per person
- Most common used words
- Word usage by absolute frequency of use (possible to add a limit to number of occurrences)
- Word usage by relative frequency of use (possible to add a limit to number of occurrences)
- Word usage by frequency in percentages of use

## Getting Started

These instructions will inform you about the prerequisites and how a data set containing direct messages between two users can be obtained.

### Prerequisites

The following packages are needed and can be installed with e.g. pip:

- pandas
- matplotlib
- numpy
- seaborn
- adjustText

### Data Set

It is possible to use (this)[https://github.com/Tyrrrz/DiscordChatExporter] tool to obtain a data set that captures all direct messages between two users. One can get the a data set containing the following columns using this tool: 

- author (e.g., “EXAMPLE#0000”)
- date (e.g., “15-Dec-17 11:33 AM”)
- content (e.g., “Hello”)
- attachments (e.g., “https://cdn.discordapp.com/attachments/“)
- reactions

## Running

The project can be run with e.g. a Jupyter Notebook or Google Collaboratory.