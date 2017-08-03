# [NHS Primer Database and API] Project Requirements


## Participants

    - Product owner: Geoff Woodward and Marc Wadsley
    - Team: NHS Bioinformatics
    - Stakeholders: NHS Genetics Laboratories - including: Bioinformatics, GTs and Scientists.

## Current Status

_Requirements gathering_

## Purpose
_To deliver an API and database capable of serving and storing Sanger sequencing primers with all associated metadata including the design parameters, laboratory conditions and performance_

## Project Goals & Objectives

_Briefly describe the goals for the project_

_Identify limits to the scope of the solution by defining goals and non goals. This is particularly an ideal place to specify what is not in scope, what will not be addressed._

    - Goals
        Requirement gathering to develop a data model capable of storing all required primer information
        Requirement gathering to develop an API specification able to provide a platform to curate primer information
        Define a primer data model
        Define an API specification to interact with the database
        Development of the primer database
        Development of an API
    - Out of scope / non goals
        Development of a tool to design primers

## Requirements



| Requirement | Description | Acceptance Criteria | Priority | GitHub Issue(s) |
|-------------|-------------|---------------------|----------|-----------------|
|             |             |                     |          |                 |
|             |             |                     |          |                 |
|             |             |                     |          |                 |

### Functional
- _specification of API calls (as informed by the requirements gathering)_
- _specification of the database (as informed by the requirements gathering)_
- Call to return a specific primer set
- Call to upload a primer set
- Call to modify a primer set
- Call to return primers for a specific genomic position (GRCH37 / GRCH38)
- Call to return primers covering an exon(s) (RefSeq / Ensembl)
- Calls include filters by lab conditions and performance
- Multi-centre review/rate primer performance
- Call to return unsuccessful primers

### Technical
- Multiple user groups; including admin and user
- Each lab curates their own primer dataset and users through admin
- Labs have read-only access to see all laboratories primer designs

### Usability
- Must be accessible to all NHS laboratories
- Must be accessible at all times
- Must be version controlled on git for peer review by NHS bioinformatics community
