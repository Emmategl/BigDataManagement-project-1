# Big Data Management , MSc (Fall 2021)

Assignment 1: Data Pipelines

3.1 Systemrequirements
For this assignment you should create the data preproccesing pipeline using sklearn in a sys- tem that:
• ReadsthelatestdatafromtheInfluxDB
• Preparesthedataformodeltraining,including
  – Aligningthetimestampsofthetwodatasources(e.g.throughresampling)
  – Handlingmissingdata
  – Alteringthewinddirectiontobeausablefeature(bymappingtoradiansorencod-
    ing as categorical)
   – Scalingthedatatobewithinasetrange
• Trainsalinearregressionmodel
• Usesthemodeltoforecastwindpowerproduction

Much of the scaffolding for this is provided in template.py, so you primarily need to focus on the pipeline.

3.2 Hand-in
You should hand in a report describing your solution, including which design choices and trade-offs you made. Which steps does your pipeline include? What is the format of the data once it reaches the model? How could the pipeline/system be improved?
