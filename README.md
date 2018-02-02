# England Netball Open Data
Documentation, Changelog and Issues related to the England Netball endpoint
## Open Data Endpoint
https://api.englandnetball.co.uk/api/openactive/sessions.json - feed for England Netball Sessions running across England
## Standards
The data is published to conform to [Openactive Realtime Paged Data Exchange 0.2.3](https://www.openactive.io/realtime-paged-data-exchange/0.2.3/).
## Issues, Questions and Comments
Please raise any issues, questions or comments as a [new issue in this repository](https://github.com/england-netball/opendata/issues)
## Data Fields

| Data Field  | Example Value | Description | 
| ------------- | ------------- | ------------- |
| "programme_id"  | Content Cell  |  England Netball programme reference  |
| "programme_type"  |  "BackToNetball"  |  The England Netball programme type - Back To Netball, Netball Now, NYC, Walking Netball |
| "start_time" | "2016-06-16T15:00:00Z" | Start date and time of individual session |
| "end_time" | "2016-06-16T15:00:00Z" | End date and time of individual session |
| "age_group" | text | Applies to NYC only: defined age group 9-11 or 11-16 |
| "num_of_days" | text | Applies NYC only: duration of NYC camp - 1, 3, 5 days |
| "day_duration" | text | Applies to NYC only: duration of day 9am - 5pm or 10am - 3pm |
| "staff_role" | text |  |
| "contact_number" | "01462 442344" |  |
| "venue_name" | "England Netball HQ" | Name of the venue |
| "venue_address_1" | "Netball House" | Venue address line 1 |
| "venue_address_2" | "1-12 Old Park Road" | Venue address line 2 |
| "venue_address_3" | "" | Venue address line 3 |
| "venue_address_town" | "Hitchin" | City/Town venue located in |
| "venue_address_county" | "Hertfordshire" | County venue located in |
| "venue_address_postcode" | "SG5 2JR" | Venue postcode |
| "last_programme_session_date" | "2017-05-31" | Last session running for specific programme  |
| "overview" | "Line one\nSecond line" | Summary description about the programme type  |
| "booking_url" | "https://www.test.url" | Booking url for session  |
| "distance" | 2.5 | Distance in miles from venue |
| "latitude" | 51.947899 | Latitude of venue  |
| "longitude" | -0.282528 | Longitude of venue |
| "cancelled" | false | Whether the individual session has been cancelled.  Default = false |
| "costs" | "" | Full price cost - standard fee for session Custom costs - up to 3 custom costs with custom labels NYC only: Member cost and non member cost |
| "discounts" | "" | NYC only: Early bird and General discount free text fields to provide discount info.  Both have valid until dates dd/mm/yyyy |




## Changelog

| Date  | Changes |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
