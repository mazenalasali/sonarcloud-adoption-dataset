# SonarCloud Adoption Dataset

## Description

This dataset contains longitudinal monthly metrics collected from 82 open-source GitHub projects before and after adopting SonarCloud, an automated static analysis tool. The dataset was created to support empirical research on how SonarCloud adoption affects issue resolution efficiency, pull request processing, developer engagement, and workflow dynamics.

The dataset was used in the following study:

> [The Impact of Static Analysis on Open Source Software Development Practices]  
> [Mazen Al-Asali, Mohammed El-Ramly], [2025]  


---

## Dataset Structure

Each row represents aggregated monthly metrics for a single project over two observation periods:
- **Before adoption:** at least 12 months prior to SonarCloud adoption
- **After adoption:** at least 12 months following SonarCloud adoption

---

## Columns

| Column | Description |
|--------|-------------|
| `Project_Size` | Ordinal size category of the project (coded 1–5) |
| `Project_name` | Anonymized internal project ID |
| `Number_Of_Opened_Issues_Before` | Number of opened issues (before adoption) |
| `Number_Of_Closed_Issues_Before` | Number of closed issues (before adoption) |
| `Time_To-Closed_Issues_Before` | Average time to close issues (ms, before adoption) |
| `Number_Of_Opened_Pulls_Before` | Number of opened pull requests (before adoption) |
| `Number_Of_Closed_Pulls_Before` | Number of closed pull requests (before adoption) |
| `Time_To_Closed_Pulls_Before` | Average time to close pull requests (ms, before adoption) |
| `Number_Of_Merged_Pulls_Before` | Number of merged pull requests (before adoption) |
| `Time_To_Merged_Pulls_Before` | Average time to merge pull requests (ms, before adoption) |
| `Sonar_Cloud_Adoption_Date` | Date of SonarCloud adoption for the project |
| `STARS` | GitHub repository star count |
| `Project_Age` | Project age (months) at the time of adoption |
| `Programming_Language` | Primary programming language |
| `Number_Of_Closed_Issues_After` | Number of closed issues (after adoption) |
| `Number_Of_Opened_Issues_After` | Number of opened issues (after adoption) |
| `Time_To-Closed_Issues_After` | Average time to close issues (ms, after adoption) |
| `Number_Of_Opened_Pulls_After` | Number of opened pull requests (after adoption) |
| `Number_Of_Closed_Pulls_After` | Number of closed pull requests (after adoption) |
| `Time_To_Closed_Pulls_After` | Average time to close pull requests (ms, after adoption) |
| `Number_Of_Merged_Pulls_After` | Number of merged pull requests (after adoption) |
| `Time_To_Merged_Pulls_After` | Average time to merge pull requests (ms, after adoption) |
| `Month_Year_Before` | Month-year (pre-adoption period) |
| `Month_Year_After` | Month-year (post-adoption period) |

---

## Units

- **Time metrics** are measured in milliseconds.
- **Counts** represent monthly totals.
- **Date fields** follow the format `YYYY-MM-DD`.

---

## License

This dataset is provided for academic and research purposes.  


