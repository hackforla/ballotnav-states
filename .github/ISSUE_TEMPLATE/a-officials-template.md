---
name: A Officials template
about: Describe this issue template's purpose here.
title: ''
labels: ''
assignees: ''

---

### Overview
The database or data has some formatting or other issues that need to be resolved before it can be imported.

### Action Items
- [ ] Add the following columns to you spreadsheet
   - [ ] display_notes
   - [ ] where
   - [ ] start_date
   - [ ] accessibility
- [ ] Delete the following fields
   - [ ] record_number
   - [ ] county_state
   - [ ] name
   - [ ] social
   - [ ] scraper
   - [ ] locations_copy
   - [ ] volunteers_scraper_copy
- [ ] Rename the following fields
   - [ ] ballot_dropoff_location to has_dropoff_location 
   - [ ] validate_url to source_data
- [ ] Remove all PO box locations (addresses only - not the row)
- [ ] Change the hour format from 
MON - FRI: 7:30 AM - 12:00 PM, 1:00 PM - 4:30 PM 
to following convention (removing any info about days they are closed e.g. closed sat and sun, unless it refers to a specific date they are closed):

Monday-Friday:7:00AM-12:00PM;MONDAY-FRIDAY:1:00 PM-4:30PM  or Monday-Friday:7:00-12:00;MONDAY-FRIDAY:13:00-16:30
