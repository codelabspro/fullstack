fullstack
---------

Optimizing using gradle

cd fullstack

gradle assemble

-------------------------------

common : contains utility code and does not depend on 
         any of the other proejcts

api    : contains some API code and it depends on common project

app    : contains application code and it depends on api and common project
