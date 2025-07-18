# Index
My name is Carlos Murga!
I am currently Masters of Analytics student at Georgia Institute of Technology.

# Projects
### Attendance and lead report
https://github.com/cmurga95/chapelhillbjj

This project automates the extraction, transformation, and reporting of member attendance data from a PushPress Looker dashboard.
It demonstrates how to build a full-stack data pipeline, leveraging automation, cloud database engineering, and interactive dashboards to generate actionable business insights. I originally used fastAPI to manage CRUD operations, but since I am hosting the app in render's free tier I had to use 2 services, which caused a delay. I opted to use SupaBase-py and keep everything in a single service.

### Bar path tracker
https://github.com/cmurga95/sports-performance

Bar path tracker using machine learning vision tools. Designed to analyze performance and results over time from weight training.

This is a project to track the path of a barbell during a lift to analyse technique and performance. For now I took a model from RoboFlow, but my intention is to train a model on my own. I tried Training a YOLO v9 model on my computer but it would take too long. Next I tried to use EC2 instance on AWS but free version was too limited. Next I tried Google Collab but it was limited as well.
Next steps involves training a NN on keras framework or installing Linux and using ROCm, pytorch supports gpu processing for nn training, that will let me leverage my GPU.