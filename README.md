# IT-Ticketing-Dashboard

Hello! Welcome to my IT Ticketing Dashboard project using Power BI. This dashboard aims to showcase my capabilities and skillset in Power BI. The project uses AI-generated data from the "tickets" table, which can be found in the /Data/tickets.csv directory.

## Dashboard Examples:
### Light Mode Main Page
![image](https://github.com/Dfria/IT-Ticketing-Dashboard/assets/90019629/d61d8e63-8f9e-4dc4-8feb-28ff4cfba5e3)

### Dark Mode Main Page
![image](https://github.com/Dfria/IT-Ticketing-Dashboard/assets/90019629/16720993-96bc-4886-99bf-5e205e72ebbf)

### Filter Implementations:
- Filtering page by the Closed Tickets on specific month of Closed Tickets Line Graph (Example shows Sept 2023):
![image](https://github.com/Dfria/IT-Ticketing-Dashboard/assets/90019629/e1ed877d-dc7f-4d77-8786-be32b66b00d6)
- Filtering page by the Average Completion Time (CT) on specific month of AVG CT Line Graph (Example shows Nov 2023):
![image](https://github.com/Dfria/IT-Ticketing-Dashboard/assets/90019629/787bcf27-3b86-4cc7-ae2d-94cfee601405)

### Drill Through Implementation - Closed Tickets Line Graph:
- Drill through for the Closed Tickets Line Graph allows to investigate the data further:
![image](https://github.com/Dfria/IT-Ticketing-Dashboard/assets/90019629/1f3e4e30-7b8c-4981-a220-ae09ddafc2c1)
- Closed Tickets Drill Through Page example:
![image](https://github.com/Dfria/IT-Ticketing-Dashboard/assets/90019629/aa5f220a-708e-4203-aaa3-d9a216e2c65e)
- The Line Graph now investigates the months by week. Clicking a marker filters the Table on the left.
![image](https://github.com/Dfria/IT-Ticketing-Dashboard/assets/90019629/e2e64512-ee99-4f4d-8aff-c9ca59059740)
- Data for Week 3, Nov 2023:
![image](https://github.com/Dfria/IT-Ticketing-Dashboard/assets/90019629/0c187405-b389-4e4e-9918-39bec3b29669)

## Dashboard Functionalities

### Tables and Columns

- **Created New Tables:**
  - **DateTable:** Used for date-related functionalities.

- **Created New Columns:**
  - **CountClosedTickets**
  - **AverageCompletionTime (Column name is Avg CT (Hours))**
  
- **Dynamic Table Titles:**
  - "Closed Tickets by Week Title"
  - "Closed Tickets Table Title"
  
- **Drill Through Functionality:**
  - Implemented for "Closed Tickets By Week" Pages.

### Bar Charts

- **# of Closed Tickets by Category:**
  - Can be filtered by month if Line Graph data is selected.

- **Avg Completion Time by Category:**
  - Can be filtered by month if Line Graph data is selected.

### Dark Mode and Light Mode

- Toggle between Dark Mode and Light Mode for a personalized dashboard appearance.

### Cards

- **Filterable Cards:**
  - Completion %
  - Outsourced %
  - Total Avg Completion Time
  - Total In-progress tickets

  *(Note: Can be filtered by month if Line Graph data is selected)*

- **Non-Filterable Cards:**
  - Number of closed tickets in the past 14 days, relative to the current date.
  - Number of closed tickets in the past 30 days, relative to the current date.
  - Number of closed tickets in the past year.
  - Total # of closed tickets.

### Other Features

- **Line Graph Filtering:**
  - Filter the page by Closed Tickets on a specific month or Average Completion Time (CT) on a specific month of AVG CT Line Graph.

- **Drill Through Implementation - Closed Tickets Line Graph:**
  - Allows for in-depth investigation of data.
  
  *(Example: Drill through to Closed Tickets Line Graph with months displayed by week. Clicking a marker filters the Table on the left.)*

  - **Closed Tickets Drill Through Page example:**
    - The Line Graph now investigates the months by week. Clicking a marker filters the Table on the left.

    *(Example: Data for Week 3, Nov 2023)*












