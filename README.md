# Index
Hi, nice to meet you I am Carlos!
Detail-oriented Data Analyst  experienced in building automated data pipelines, dashboards and reports. Experienced in SQL, Tableau and Python.

#### Work in Progress
AWS - Data Engineer certification

Masters of Analytics student at Georgia Institute of Technology (2025-2027)

# Projects

| Name                       | Description                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | Skills                                 | More info                                 |
| -------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | -------------------------------------- | ----------------------------------------- |
| Attendance and lead report | This project automates the extraction, transformation, and reporting of member attendance data from a PushPress Looker dashboard.<br>It demonstrates how to build a full-stack data pipeline, leveraging automation, cloud database engineering, and interactive dashboards to generate actionable business insights. I originally used fastAPI to manage CRUD operations, but since I am hosting the app in render's free tier I had to use 2 services, which caused a delay. I opted to use SupaBase-py and keep everything in a single service.                                                                                                     | Python, SQL, DataBase design(SupaBase) | https://github.com/cmurga95/chapelhillbjj |
| Confie - Tableau Dashboard | This dashboard tracks **Key Performance Indicators** (Average Handle Time, Average Calls per Agent, Total Calls, Average Idle Time, etc) used in a call center <br>This Dashboard was used by the **debt collections department**. The goal was to identify areas of opportunity to optimize operations by tracking **Key Performance Indicators** (Average Handle Time, Average Calls per Agent, Total Calls, Average Idle Time, etc).<br>It involved orchestrating the ingestion of data from several sources (SQL) to make it usable to design a Tableau dashboard. Ultimately leading to optimizing resources and improving overall operation.<br> |                                        |                                           |

### Confie - Tableau Dashboard
This dashboard tracks **Key Performance Indicators** (Average Handle Time, Average Calls per Agent, Total Calls, Average Idle Time, etc) used in a call center 
This Dashboard was used by the **debt collections department**. The goal was to identify areas of opportunity to optimize operations by tracking **Key Performance Indicators** (Average Handle Time, Average Calls per Agent, Total Calls, Average Idle Time, etc).
It involved orchestrating the ingestion of data from several sources (SQL) to make it usable to design a Tableau dashboard. Ultimately leading to optimizing resources and improving overall operation.

### Bar path tracker
https://github.com/cmurga95/sports-performance

Bar path tracker using machine learning vision tools. Designed to analyze performance and results over time from weight training.

This is a project to track the path of a barbell during a lift to analyze technique and performance. For now I took a model from RoboFlow, but my intention is to train a model on my own. I tried Training a YOLO v9 model on my computer but it would take too long. Next I tried to use EC2 instance on AWS but free version was too limited. Next I tried Google Collab but it was limited as well.
Next steps involves training a NN on Keras framework or installing Linux and using ROCm, pytorch supports GPU processing for Neural Network training, that will let me leverage my GPU.
