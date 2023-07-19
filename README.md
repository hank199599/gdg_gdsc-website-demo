# GDG GDSC Website Example 

## Structure
* FrontStage : [Demo Web Page](https://hank199599.web.app)  
  * main page
  * activity
  * annual_activity
  * team
  * partners
* BackStage : [Demo Web Page](https://hank199599.web.app/backstage)
  * DashBoard with Calender
  * Full customization in annual_activity
  * Full customization in team
  * Full customization in partners
  * Full customization in social Media

## Adjust
  You can find the `commend_setting.js` file in the `public` folder.  
  In here you can adjust the source to GDG / GDSC.

 ### How to get the Bevy Chapter ID?
  Query your chapter in   
  https://gdg.community.dev/api/search/chapter?q=<Your Chapter Name>  
  OR  
  https://gdsc.community.dev/api/search/chapter?q=<Your Chapter Name>  
  
  you'll find the id shown in the result list, like this:
  ```
  results: [
    {
      id: 748,
      title: "GDG Taipei",
      city: "Taipei",
      state: "",
      chapter_location: "Taipei (TW)",
      ...
    }
  ]
  ```
 