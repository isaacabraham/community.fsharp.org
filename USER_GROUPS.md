# community.fsharp.org User Groups

> All content is curated by the F# Software Community, and does not constitute an official endorsement by the F# Software Foundation.

The [User Groups](http://community.fsharp.org/user_groups) map and page are based off data stored here. If you manage a user group where F# talks are welcome, you are encouraged to add your group to the list managed by the F# Software Foundation.

The data is stored in a JSONP document at [https://github.com/fsharp/community.fsharp.org/blob/gh-pages/user_groups/groups.jsonp](https://github.com/fsharp/community.fsharp.org/blob/gh-pages/user_groups/groups.jsonp).  Pull requests against this data are welcome, though you may also email your information to [usergroups@fsharp.org](mailto:usergroups@fsharp.org) to have your group listed.

Please follow these guidelines when submitting a pull request:

- List your group alphabetically
- Fill in all information, following the format of existing entries
- Latitude and Longitude values are used to place the group using the Google Maps API.  
    - Google Maps is recommended to determine coordinate.
    - Visit [Google Maps](https://www.google.com/maps), Zoom to your location, and click on the map where your group most commonly meets.
    - Copy latitude and longtiude from white box at the bottom of the screen.
- The "contact" field is optional, and is the full name of the person whom should be listed as the contact for the group.
- Please verify that resulting data follows all JSON rules, including correctly handling (or avoiding) embedded quotation marks in the description, etc.
- If your group is an F# specific user group, please list the "fsharp_group" field as `true`.  If it is a general functional programming or other programming language group, but is open to having F# speakers, list it as `false`.


Here is an example entry (showing portions of the entry before and after):

```javascript
    "lng":-118.4661156
},
{
    "name":"Silicon Valley F#",
    "website":"http://www.meetup.com/Silicon-Valley-FSharp/",
    "location":"Mountain View, CA, United States",
    "contact":"Mathias Brandewinder",
    "fsharp_group":true,
    "description":"Silicon Valley F# is home for the F# language users community in the Bay Area / Silicon Valley. We love functional programming with F#, on .NET and Mono, and aim to create a fun community, where we can all learn from each other and grow together, in a respectful and inclusive manner! ",
    "lat":37.410483,
    "lng":-122.059758
},
{
    "name":"Singapore Functional Programmers Meetup",
    "website":"http://www.meetup.com/Singapore-Functional-Programmers-Meetup/",
```

Please duplicate this formatting style in your own group entry.
