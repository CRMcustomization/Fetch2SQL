# Fetch2SQL
Convert Fetch XML to SQL query

Some time we need to get SQL query for fetchxml. For MS CRM application you can get FetchXML‘s SQL query by running profiler on SQL server and find the query from profiler.
But if there are more users accessing CRM, then there are lot of queries are executing and we need to go through each query and need to relate to our fetchXML.
This tool converts existing entities system view FetchXML queries to SQL queries. Also you can enter directly fetch XML and it will convert to SQL query.

Convert System View FetchXML to SQL query

          a.First select Entity from drop down
          b.Select system view, FetchXML of selected view will be converted to SQL query.
          c.Click on Get FetchXML, FetchXML for selected view will be retrieved from CRM and displayed in Textbox
          d.If required you can modify fetch xml as per requirement
          e.Click on Get SQL query, your FetchXML will be converted to SQL query and shown in textbox.

http://1.bp.blogspot.com/-zXTjXLyPYNo/VUj2OC8JUKI/AAAAAAAATdM/m0OFHPGrBWw/s1600/1.png

Manual FetchXML to SQL
          a.      Enter FetchXML in first text box, you want to convert into SQL query
          b.      Click on Get SQL query, FetchXML converted and shown in textbox. 

http://4.bp.blogspot.com/-CN4e9cwm3N0/VUj2N7PBYDI/AAAAAAAATdE/PFs26Zq9J1c/s1600/2.png

User or Team filters
          a. Based on current user all conditions are shown.
          b. If any filter condition for user and/or userteam, then current user id and user teams will be retrieved and Id’s will be shown in SQL query.

http://1.bp.blogspot.com/-rc-C00QcMe0/VUj2OM6tkpI/AAAAAAAATdI/erz4r_7U29Y/s1600/3.png

Date time operator
          a. Most of the time showing CRM database functions in SQL query. Because date time is varying based on user settings.

http://1.bp.blogspot.com/-H6ASTdodG3o/VUj2OnnUnrI/AAAAAAAATdQ/yvGFlUxlp-w/s1600/4.png

         b.  For some of the date time operators it is very hard to find exact value. So just showing what will be the possible values.

        e.g. Operator  = last-x-fiscal-periods, every CRM might have different fiscal period setting, so user need to put those dates.
          
          http://2.bp.blogspot.com/-4P3LYGzp4DM/VUj2O0akPsI/AAAAAAAATdY/fR9WYpQq_DQ/s1600/5.png
          
MS CRM Managed Solution is aviable on codeplex to download

http://fetchxml2sql.codeplex.com/

Also similar details are on 
http://mahadeomatre.blogspot.com/2015/05/convert-fetchxml-to-sql-query.html
