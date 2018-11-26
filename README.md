# Database-WebService
Database and Web Services

#As a project of Database and Web Services course, we are expected to create 
#a database and web application and a complete working system between them. The project
#is still going on. Now the ER diagram and SQL codes are available. The website part is incomplete
#but the first draft for it is available in zipped file. The idea of the project is summarized below.

Functionality of the web application
In the industry, water is used in several steps for cooling, cleaning and also to
be part of the different product formulas. The quality of the water throughout
the entire process and at every moment is obtained by the chemical treatment
of new and recycled water sources. Additionally closed cycles of cleaning, com-
monly known as CIP (Cleaning in place), fuel and geothermal wells need certain
additives to assure their optimal functionality.
Setting Group is a company that sales products from the XXXX Corporation.
Their portfolio is broad and contains chemical products in order to treat water
cycles, preventing corrosion, algae growth, incrustation processes, CIP cycles,
fuel bombs/deposits and geothermal wells. After this point Setting Group will
be referred as the “Analytic Company” and their industry-clients simply as the
“Clients”. Their products have to be dosed following equipment, product or
cycle requirements and the amount of chemicals and their concentration is also
dependant on the specific state of the water/fuel/steam at a certain time point.
This is achieved with rigorous and periodic water analysis that depend on each
specific water cycle. The quantitative and microbiological analysis are a added
value service to the industry, the stored values let the “Analytic Company” prove
the effectiveness of their products, while exposing important insights about the
industry equipment’s and chemical cycles.
The functionality of the web service is to store the analytic results through time,
organized by : Country, Company, Water cycle, Fuel, Well, Related equipment,
Nature of the analysis, Analysis Parameters, Analysis Intervals. The “Analytic
Company” has appointed a consultant for each “Client”, and each consultant
has a supervisor from the “Analytic Company”.
2
User interaction
The database has to perform the following cycles:
1• Information upload: Each consultant, after taking the samples from the
client installations, performs the chemical analysis in the companys labora-
tory. After receiving the results, the consultant has to upload the informa-
tion in the database. So every consultant will have a user-name/password
to access the database and store the information. The database has to
be able to deal with conflicts: Two (2) or more consultants/supervisors
updating or viewing information in the database, maintaining the proper
consistency.
• Information display: At different meetings with the client, the con-
sultants show the evolution of the water parameters for each cycle. In
this case, the database has to be able to project specific parameters and
their evolution in time per client, possibly relating the performance to the
average of other similar equipment or chemical cycles.
• Information download: Sometimes the company has to develop specific
evolution reports. For that purpose, the database needs the flexibility to
download certain predetermined databases arrangements, saving time and
assuring consistency in the original and downloaded database.
3
Information collection and storage
At the moment the company is storing all its information in fifty (58) Excel
Sheets, each with thirty (30) different attributes, in local drives and Google
Drive. Consistency and conflicts when several consultants update the database,
represent the biggest problems. Besides, now, the database has no capacity to
store data regarding the fuel and wells division. Every time, the company wishes
to elaborate a report, they take this rudimentary database and copy it, to make
the final graphs and conclusions for each client. Setting Group has already
delivered to us their most up to date database, in order to analyze it and design
the first ER Diagrams and details about the database and web service.
