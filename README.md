# LinkedIn Student Network Analysis (Python)

## What this project does
This project analyzes LinkedIn connection data of students to understand
how people are connected to each other in a large network.

Each person is treated as a point, and each connection is treated as a link
between two people.

## Why I built this
I wanted to learn how large datasets are handled and how relationships
between people can be represented using data.

This project helped me understand how connections grow and how some people
are more connected than others.

## Dataset used
- Student LinkedIn connection data
- Around 28,000 people and 1,99,000 connections
- Data was provided in JSON format

## What analysis I did
- Cleaned the data by removing duplicates and incorrect entries
- Built a connection structure from the raw data
- Counted how many connections each person has
- Studied overall connection patterns in the network
- Followed connection chains to see how people are linked

## Key observations
- Most students had very few connections
- A small number of students had many connections
- These highly connected students act as important links in the network

## Tech used
- Python
- Pandas and NumPy
- NetworkX
- Matplotlib

## What I learned
- How to work with large datasets
- How to represent real-world connections using data
- How to extract simple insights from raw data
- How to visualize data for better understanding

## Future improvements
- Add more visual summaries
- Analyze data over time
- Compare different student networks
