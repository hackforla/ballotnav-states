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
- [ ] Data Quality
   - [ ] Review Secretary of State Website
   - [ ] Call First County
   - [ ] Update Location Validation Test Sheet
   - [ ] Edit the issue Action Items to reflect findings
- [ ] Data Scientist/Scrapers
- [ ] Add the following columns to your data schema
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
   - [ ] If Hours are available add them to the sheet by using the following convention (removing any info about days they are closed e.g. closed sat and sun, unless it refers to a specific date they are closed):
Monday-Friday:7:00AM-12:00PM;MONDAY-FRIDAY:1:00 PM-4:30PM  or Monday-Friday:7:00-12:00;MONDAY-FRIDAY:13:00-16:30
Monday-Friday:7:00AM-4:00PM or Monday-Friday:7:00-16:00
Tuesday:9:00AM-3:00PM;Thursday:9:00AM-3:00PM or Tuesday:9:00-15:00;Thursday:9:00-15:00
- [ ] Address fields needs to be broken up into individual components (address_1 and address_2) 
   - address_1 = Street name and address #
   - address_2 = suite # or room #, etc
   - city = city name
   - state_2 = two letter abbreviation for the address (for some states the location is in a different state than the voting district (crazy I know.  But this is why there is a state field seperate which is supposed to be the state spelled out and that is the jurisdiction not the physical location)


### Resources/Instructions
[Google sheet]
