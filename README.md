

### Overview

## Chiwatch: 
Reporting police misconduct in the city of Chicago from 2017-2020 with data sourced from The Thurgood Marshall Institute, the objective of this project is to inform, educate and enlighten concerned citizens on a growing problem in American cities today, by focusing on one of America's capital of the Midwest and a city rampant with violence. This project utilizes Airtable, ReactJS, and React-Chart
<br>

#### My Airtable 
https://airtable.com/invite/l?inviteId=invBQvXuin6ZNqKYZ&inviteToken=b9c86d6b637c9b3e366396fc2abbf4bb76b89b6be42e4820ffe538e8b3d27341

#### Wireframes

> Use the Wireframes section to display desktop, tablet and mobile views.



- Desktop Landing
https://framer.com/share/Chi-Watch-9jAeOakiweCeazOtpcn9



#### MVP

> _The ChiWatch Minimum Viable Product of this project is to simply receive the user input, based on selected dataset filters (Year Of Complaint, Ethnicity of Complaintant, Category of Offense,etc) and output the visualization of that data in simple web application that emulates a social media post


<br>

#### Goals

- _Render the info about the incident in a  front end visual format that looks similar to Facebook status with a graph and portion of the table underneath
- _Have a graph or chart feature that shows the # of incidents by category vs the year._



<br>

#### Libraries

> Use this section to list all supporting libraries and their role in the project.

|     Library      | Description                                |
| :--------------: | :----------------------------------------- |
|   React Router   | _Import data via AirTable using ReactRouter._ |
|   React Table    | _Render the parts of the table relevant to the query_ |
|   React JSON Graph  |Render a graph of complaint category in last three years._ |

<br>

#### Data

> Use the Data Section to define the API(s) you will be consuming for your project, inluding sample URL queries.

|    API     | Quality Docs? | Website       | Sample Query                            |
| :--------: | :-----------: | :------------ | :-------------------------------------- |
| AirtableAPI |      yes      | https://airtable.com/shr31XXeMsvYa6yqI |     |

<br>

#### Component Hierarchy

```
src
|__ TheData/
      |__ Airtable
      |_Chart.js
      
|__ components/
      |__ Header.jsx
      |__ Nav. jsx
      |__ TheData.jsx
      |__ CSVReader.jsx
      |___ React-Graph.jsx
      |__ Footer.jsx
```

<br>

#### Component Breakdown

> Use this section to go into further depth regarding your components, including breaking down the components as stateless or stateful, and considering the passing of data between those components.

|  Component   |    Type    | state | props | Description                                                      |
| :----------: | :--------: | :---: | :---: | :--------------------------------------------------------------- |
|  HTML, CSS, JS| functional |   yes  |   n   | Building the structure              |
|    Data      | functional |   yes  |   n   | _Working with the Airtable  API_               |
|    Status    | functional |   yes  |  yes  | _Will use a facebook status format to display officer name as username, and then information regarding the incident as status._ 
|  The Chart   | functional  |   y   |   y    |_Chart the total number of complaints in that category_
|    Footer    | functional |   n   |   n   | _The footer will show info about me and the sources (Thurgood Marshall Institute of the data |

<br>

#### Component Estimates

> Use this section to estimate the time necessary to build out each of the components you've described above. 
>
> Time frames are key to the development cycle. You have limited time to code your app, and your estimates can then be used to evalute possibilities of your MVP and post-MVP based on time needed. It's best you assume an additional hour for each component, as well as a few hours added to the total time, to play it safe.

| Task                | Priority | Estimated Time | Time Invested | Actual Time |
| ------------------- | :------: | :------------: | :-----------: | :---------: |
| Structure           |    M     |     2.5 hrs      |    3hrs     |    TBD       |
| React-Table         |    M     |     2 hrs      |     2hrs     |    TBD       |
| React-Graph         |    L     |     2 hrs      |     2hrs     |    TBD       |
|   The Report /CRUD  |    H     |     4 hrs      |     5hrs     |     TBD      |
| TOTAL               |          |     16.5 hrs      |     3 hrs     |     TBD     |

<br>

#### Helper Functions

> Use this section to document all helper functions– generic functions that can be reused in other applications.

|  Function  | Description                                |
| :--------: | :----------------------------------------- |
| Capitalize | _                                       ._ |

<br>

### Post-MVP

> _How do I allow users to add to this data by reporting their own incidents themselves, rather than rely on The Thurgood database?
> _Increase functionality by also allowing neighborhood watch feature to allow concernced citizen to report on false complaints or incidents of abuse of this tool, such as local trouble makers, burgulars or gang memebers who may file false or exaggertated complaints.
> _Add  a feature to contact legislation in the city of Chicago with a contact form or digital suggestion box where citizens can suggest policies they would like to see implemented


<br>

***

## Project Delivery

### Code Showcase

> Code that I am proud of while working on this project
### Code Issues & Resolutions

> Use this section to list of all major issues encountered and their resolution, if you'd like.
