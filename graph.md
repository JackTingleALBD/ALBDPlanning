:::mermaid
graph TD;
   WorkFlow[Projects] --> OnsiteJT
   WorkFlow[Projects] --- B{FreelanceJT}
   OnsiteJT --> ThamesWater
   OnsiteJT --> SevernTrentWater
   OnsiteJT --> FlowSurveys
   OnsiteJT --> FlowApp
   OnsiteJT --> Map16
   FlowApp --- Map16

   B{FreelanceJT} --> GameDev
   GameDev -- demo[1] --> GetToWork
   GameDev -- demo[2] --> Hailz
   B{FreelanceJT} --> PGMOLCaseFiles
   B{FreelanceJT} --> ALBD2.0
   PGMOLCaseFiles --> NewFeatures
   NewFeatures -- feature[1] --> MonthlyBlog
:::
