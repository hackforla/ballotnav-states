---
name: A Locations template
about: To help fix state data
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
   - [ ] latitude
   - [ ] longitude
   - [ ] social
   - [ ] state and counties and county reps copy
- [ ] Rename the following fields
   - [ ] Field 23 to location_name
   - [ ] validate_url to source_data
- [ ] Change the hour format from 
MON - FRI: 7:30 AM - 12:00 PM, 1:00 PM - 4:30 PM 
to following convention (removing any info about days they are closed e.g. closed sat and sun, unless it refers to a specific date they are closed):

Monday-Friday:7:00AM-12:00PM;MONDAY-FRIDAY:1:00 PM-4:30PM  or Monday-Friday:7:00-12:00;MONDAY-FRIDAY:13:00-16:30
Monday-Friday:7:00AM-4:00PM or Monday-Friday:7:00-16:00
Tuesday:9:00AM-3:00PM;Thursday:9:00AM-3:00PM or Tuesday:9:00-15:00;Thursday:9:00-15:00

### Resources/Instructions
[Google sheet]