##Data Visualization of US school donations

The goal of this project was to expand on the skillsets and tools for creating a 
meaningful interactive data visualization learned throughout Streams 1 & 2 . 

###Data source

To do this, I used a dataset from DonorsChoose.org to build a data visualization that
represents school donations broken down by different attributes over a timeline.

###Background

DonorsChoose.org is a US based nonprofit organization that allows individuals to
donate money directly to public school classroom projects. Public school teachers
post classroom project requests on the platform, and individuals have the option to
donate money directly to fund these projects. The classroom projects range from
pencils and books to computers and other expensive equipments for classrooms. In
more than 10 years of existence, this platform helped teachers in all US states to
post more than 7700,000 classroom project requests and raise more than
$280,000,000. DonorsChoose.org has made the platform data open and available
for making discoveries and building applications.

###The components of the project and their function:
1. D3.js: A JavaScript based visualization engine, which renders interactive
charts and graphs based on the data.

2. Dc.js: A JavaScript based wrapper library for D3.js, which makes plotting the
charts a lot easier.

3. Crossfilter.js: A JavaScript based data manipulation library that enables two
way data binding.

4. Queue.js: An asynchronous helper library for JavaScript.

5. Mongo DB: NoSQL Database used to convert and present our data in JSON
format.

6. Flask: A Python based micro - framework used to serve our data from the
server to our web based interface.

###Hosting

The project is hosted on Heroku at https://desolate-plains-65582.herokuapp.com/
