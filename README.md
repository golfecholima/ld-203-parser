# LD-203 Parser

A project to generate a CSV from the House lobbying disclosure bulk .xml files.

*Created by George LeVines (<george.levines@gmail.com>)*

## Project goal

*TK: Briefly describe this project*

## Project notes

### Staff involved

*TK: List people & contact info for people involved in the project*

### Data sources

* [House lobbying disclosure](https://disclosurespreview.house.gov/?index=%22lobbying-disclosures%22&size=10&sort=[{%22_score%22:true},{%22field%22:%22registrant.name%22,%22order%22:%22asc%22}])
* Base URL example for each .xml file: `https://disclosurespreview.house.gov/ld/ldxmlrelease/2013/Q4/300630152.xml`

## Technical

*TK: Instructions on how to bootstrap project, run ETL processes, etc.*

### Project setup instructions

After cloning the git repo:

`datakit data pull` to rerieve the data files.

Open `ld-203-parser.Rproj` in RStudio.

*TK: For more complex or unusual projects additional directions follow*

## Data notes

*Add important caveats, limitations, and source contact info here.*
