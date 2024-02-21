# Rshiny


Some new "keep in mind" points I learnt while doing this course from Linkedin


> Include libraries in both ui.R and server.R for example, htmlwidgets \

> New packages introduced:- \
  > leaflet \
  > rfigshare \

> Isolate the reactive variables if the action button should update the plot only when all inputs are changed acc. to need \

> Whatever files are uploaded with input file widget, the files are temp. stored on the R shiny server and gets deleted when the shiny app is stopped. \

> Using rhandsontable to take the inputs from the user \

> Debugging Issues
 - shinjys:runcodeUI()
 - shinyjs::runcodeserver()
 - shiny::reactLog() 
