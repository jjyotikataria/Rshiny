# Rshiny


Some new "keep in mind" points I learnt while doing this course from Linkedin


- Include libraries in both ui.R and server.R for example, htmlwidgets 

- New packages introduced:- 
  - leaflet 
  - rfigshare 
  - shinycustomloader
  - rhandsontable
  - rsconnect

- Isolate the reactive variables if the action button should update the plot only when all inputs are changed acc. to need 

- Whatever files are uploaded with input file widget, the files are temp. stored on the R shiny server and gets deleted when the shiny app is stopped. 

- Using rhandsontable to take the inputs from the user 

- Debugging Issues
   - shinjys:runcodeUI()
   - shinyjs::runcodeserver()
   - shiny::reactLog()
   - useShinyjs() : Refer 08_03 project
 
- Deployment Issues
   - Include all codes in server.R
   - Could be due to time zone as well
   - Ensure tokens are sent to the server when you are using datapackages which talk via the API
 
- Shiny apps convert the inputs into strings to avoid nefarious content, prone to hacking if not done so
   - Example - select input numeric values will be treated as string
 
- Adjusting css elements refer 09_01

- Deploying shiny apps
   - shinyapps.io is not GDPR compliant and unlikely to be in future
   - Refer 10_02 Project
   - Refer 10_04 for rsconnect 


