### **Title: India General Election Results 2024 – Power BI Dashboard** ###


### **PROBLEM STATEMENT** ##

### DASHBOARD 1: OVERVIEW ANALYSIS ###
The India General Election Results – 2024 dashboard aims to provide a comprehensive overview of the election outcomes with a focus on seat distribution among key alliances and independent candidates. The dashboard will help political analysts, researchers, and the general public gain insights into the election performance of major political groups.

### **Used Datasets Links** ###:
1. ### statewise_results.csv ###: https://drive.google.com/file/d/19fWSK9krLhRMZfx6LtrnnGQVxY66sv0x/view
2. ### states.csv ###: https://drive.google.com/file/d/1mUOal-ILCIpdIUlIs3lImRSo1Erp4aeu/view
3. ### partwise_results.csv ###: https://drive.google.com/file/d/1MwN1prYRzTQGC5xQ_E5P0QuJE2EI2KhM/view
4. ### constituencywise_results.csv ###: https://drive.google.com/file/d/14TxzD2fnFlYZUCD4Lke2rPB0o-vLjtKu/view
5. ### constituencywise_details.csv ###: https://drive.google.com/file/d/1ptx6MkMW2Lk8E2NqdDbTlIHrQdX_ZWE5/view



### **KPI’s** ### 

### **1.NDA Performanc** ###
    - Total seats won by the NDA alliance.
    - Percentage of total seats secured by NDA.
    - Bookmark: A grid matrix details table showing all seats won by the NDA Alliance.
### **2.I.N.D.I.A. Performance** ###
    - Total seats won by the I.N.D.I.A. alliance.
    - Percentage of total seats secured by I.N.D.I.A.
    - Bookmark: A grid matrix details table showing all seats won by the I.N.D.I.A. Alliance.

### **3.Independent & Other Parties Performance** ###
    - Total seats won by independent candidates and smaller parties.
    - Percentage of total seats won by this group.
    - Bookmark: A grid matrix details table showing all seats won by Independent and Other Parties.

### **4.NDA Alliance Analysis** ###
    - Identify all parties within NDA that won seats.
    - Display each party's seat count along with their party logos.

### **5.I.N.D.I.A. Alliance Analysis** ###
    - Identify all parties within I.N.D.I.A. that won seats.
    - Display each party's seat count along with their party logos.

  Dashboard 1 Image: ![Overview Analysis Dashboard 2](https://github.com/user-attachments/assets/cd5614c2-52b4-4307-82fe-760b8bf5178e)





### **DASHBOARD 2: STATE DEMOGRAPHIC ANALYSIS** ###
The India General Election Results – 2024 dashboard provides an in-depth state-wise and constituency-wise analysis of the election outcomes. It offers a geographical breakdown of seat distributions, winning parties, and candidates, helping analysts, policymakers, and citizens understand the political landscape at different levels.


### **1.Total Seats, Alliance with Majority Seats, NDA Seats and I.N.D.I.A. Seats by State** ###
    - Displays Total Seats, Alliance with Majority Seats, NDA Seats, and I.N.D.I.A. Seats at the state level.
    - Visual Representation:
                   - Map Chart by State
                   - Tooltip includes Total Seats, Majority Alliance, NDA Seats, and I.N.D.I.A.
                   - Seats per state.
                   - Drill-through to a grid details table showing all underlying data per state.

### **2. Winning Candidate & Party by Constituency** ###
    - Displays Winning Candidate, Winning Party, Total Votes, and Total Margin per constituency.
    - Visual Representation:
                     - Bubble Map Chart
                     - Each Bubbles represent a constituency.
                     - Color-coded bubbles to distinguish NDA, I.N.D.I.A., and OTHER seats.
                     - Drill-through to a grid details table showing all underlying constituency data. Identifies the state where either NDA or I.N.D.I.A. won the most seats.
                     
### **3. State with the Maximum Seats won by either the NDA Alliance or the I.N.D.I.A. Alliance** ###
    - Identifies the state where either NDA or I.N.D.I.A. won the most seats.
    - Visual Representation:
                   - State-wise Map Chart
                   - Color-coded states based on the majority alliance in each state.
                   - Drill-through to a grid details table showing all underlying seat data for that state.


Dashboard 2 Image: ![State Demographic Analysis Dashboard 3](https://github.com/user-attachments/assets/b8a43f59-27dc-4163-9f9c-294f463f01f6)






### **DASHBOARD 3: POLITICAL LANDSCAPE BY STATE** ##
The State Analysis dashboard provides a state-wise breakdown of the India General Election 2024 results. It enables users to analyze the performance of different political alliances and parties within a selected state, helping with comparative analysis, decision-making, and trend identification.

### **KPI’s** ##

### **Dynamic Selection: Users can select a specific state from a filter.** ### 
    - Key Metrics Display:
        - Seats won by I.N.D.I.A. Alliance
        - Seats won by NDA Alliance
        - Seats won by Independent & Other Parties

### **Charts & Visualizations** ###
1. State Map Chart:
   - Displays the selected state with its constituency boundaries.
   -  Highlights the distribution of seats across constituencies.
2. Party-wise Result (Grid View):
   - Displays all parties that won seats in the selected state.
   - Includes the alliance affiliation of each party (NDA, I.N.D.I.A., or Independent).
3. Party-wise Seat Share (Donut Chart):
   - Represents the percentage share of total seats won by each party in the selected state.
   - Provides a visual comparison of party dominance within the state.


Dashboard 3 Image: ![Political Landscape by State Dashboard 4](https://github.com/user-attachments/assets/9d122e03-f284-4d8a-b783-477c3847fd53)









DASHBOARD 4: CONSTITUENCY ANALYSIS
The Constituency Analysis dashboard provides an in-depth analysis of election results for a selected constituency, allowing users to examine voter turnout, candidate performance, and seat outcomes. This dashboard helps political analysts, researchers, and citizens gain insights into the competitive landscape at the constituency level.

KPI’s - Primary (Overall Election Metrics for the Selected Constituency)
    - Total Votes cast in the constituency.
    - Total EVM Votes recorded.
    - Total Postal Votes counted.
    - Total Candidates participating in the elections for that constituency.

KPI’s - Secondary (Candidate Performance Overview)

1.Winning Candidate:
    - State
    - Winning Candidate Name
    - Party Name
    - Total Votes Secured
    - Vote Share (%)

2. Runner-up Candidate:
    - State
    - Candidate Name
    - Party Name
    - Total Votes Secured
    - Vote Share (%)

3. 2nd Runner-up Candidate:
    - State
    - Candidate Name
    - Party Name
    - Total Votes Secured
    - Vote Share (%)


Dashboard 4 Image: ![Constituency Analysis Dashboard 5](https://github.com/user-attachments/assets/bb632aa8-0708-4b23-ac6d-f34c55eb562f)










### **DASHBOARD 5: DETAILS GRID** ###
The Details Grid dashboard provides a comprehensive tabular view of the election results at the constituency level. It serves as a data exploration tool, allowing users to drill through from other dashboards and export election data for further analysis.

Grid View Fields: 

    - The grid will display the following fields:
    - Constituency Name
    - Winning Candidate
    - Runner-Up Candidate
    - Party Name (Winning Party)
    - Party Alliance (NDA, I.N.D.I.A., or Independent)
    - EVM Votes (Electronic Voting Machine Votes)
    - Postal Votes (Postal Ballots Counted)
    - Total Votes (Sum of EVM + Postal Votes)
    - Margin (Vote difference between Winner & Runner-Up)

Functionalities

1.Drill-Through Capability

     - Users can drill through from other dashboards (State Analysis, Constituency Analysis, etc.) to view the detailed underlying data for a specific state or constituency.
2.Data Export Option
  
    - The grid should allow users to export the data as an Excel file for further external analysis.
3.Show All Data Button (Using Bookmark)
   
    - A button will be provided to refresh the grid and display all relevant data after filters are applied and drill-through actions are performed.


Dashboard 5 Image: ![Details Grid Dashboard 6](https://github.com/user-attachments/assets/3a930d80-26e1-484f-88e3-868b83773d22)










### **DASHBOARD 6: LANDING PAGE** ###
The Landing Page serves as the central navigation hub for the India General Election Results 2024 dashboard. It allows users to seamlessly navigate between different analytica dashboards and ensures a user
friendly experience with easy access to all key insights.

1. Dashboard Navigation Menu
The landing page will provide clickable buttons/cards to navigate to the following dashboards:
    - Overview Analysis
    - State Demographics
    - Political Landscape by State
    - Constituency Analysis
Each button will be designed to provide quick access to the respective dashboard with a clear label and relevant icon.

2. Home Button on Each Dashboard
    - Each dashboard will include a Home Button that allows users to quickly return to the
    - Landing Page with a single click.
3. Interactive UI Elements
    - Minimalist & Clean Design for easy readability.
    - Icons & Color Coding for better visualization and quick recognition.
    - Hover Effects to highlight active selections.
4. Responsive Layout
    - The landing page will be optimized for different screen sizes, ensuring a smooth experience on desktops, tablets, and large screens.

Dashboard 6 Image: ![Landing Page Dashboard 1](https://github.com/user-attachments/assets/cae65044-2b31-4801-bca1-aa0ec6c84a3a)


### **Conclusion**##
The India General Election Results 2024 Power BI Dashboard successfully transforms complex electoral data into a set of clear, interactive visualizations. By breaking down the results at national, state, and constituency levels, the dashboard provides valuable insights into party performances, voter behavior, and regional dynamics.

Through the use of filters, drill-through functionality, and well-structured KPIs, users can analyze data from multiple perspectives—be it alliance-level overviews, party-wise dominance, or candidate-specific performance. The responsive and user-friendly design ensures accessibility for a broad audience including political analysts, journalists, policymakers, and engaged citizens.

Overall, this project demonstrates the power of data visualization in democratic transparency and electoral analysis, enabling evidence-based understanding and decision-making in a large-scale political context.
