### 4.5 Scenarios

#### Overall Use Case Diagram

![alt Deployment Diagram](https://github.com/ADRI-Institute/Dspace-Amber/blob/master/M2_Architecture/UML%20Diagrams/Use%20Case%20Diagram.png)

#### Critical Scenario: Search and Find an Item

This is likely the most commonly completed use case of the entire system. As such, it is critical that this use case has a good UX, and works quickly and reliably on the system side. For an activity diagram describing this process see section 4.3.

This process involves all the physical components of the system, these being the user's browser, the web server, the application server, and the database server. When the user searches for an item in their browser, the web server will rec



2 References



#### Bootstrap - https://getbootstrap.com/

Bootstrap is an excellent web development library, and provides easy to add aesthetic features to webpages. In particular it is useful for adding cards, and card related widgets to the page.



### 4.4 Physical

<mxfile userAgent="Mozilla/5.0 (X11; Linux x86_64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/64.0.3282.119 Safari/537.36" version="8.5.15" editor="www.draw.io" type="github"><diagram id="bf212a89-b111-2ca9-afcf-8fabc0d67d5c" name="Page-1">7Vhdb5swFP01PK4KOKHpYwjN+rBJ1VKp7aMJN2DVwcw4X/v1s+HynVSp2qWblkoV+Pja9/qee+xgi0xXu6+SpvF3EQK3nEG4s4hvOY49dFz9MMi+QK6HwwKIJAvRqAbm7BcgOEB0zULIWoZKCK5Y2gYXIklgoVoYlVJs22ZLwdteUxpBD5gvKO+jjyxUMaK2e1N33AGLYnQ9Lhcc0MVLJMU6QX+WQ5b5X9G9ouVcuNAspqHYNiBya5GpFEIVb6vdFLjJbZm2YtzsSG8Vt4REnTLAKQZsKF9DGbHL9VAvZBsTn9pjTtyfaxOUp2CnvlDOosQiE0OB9gSy7tdvET7zeYISeAT9OpiD3OTmvDCaBd0BGst9t9EPD6cC5IEAzhTULVOxwQdU/3Oh608/hQH0BCCTvJ1hxgbrDEJTYnujhhhy04gmLKOKieTqWKhOK0RHz6WY9jQpwvOVSLUZButjpMTLUrpgSfRgev1xDXyDpSksp0Z+oAzsHItpahwt1gGYZqFsLWuTLKmlqiPVQCbWRgjeUiRqjrEZm1ituLEvu3B4wxv6XjLOp4LrXJlFkdnMn3kTY6WkeIFGD3HJDdHF7m1jpmCuJzEzbvW2VSXHZAR2RwVkV7LU2x2IFShpGMABIxQybnRVe1tvG84AsbixY9jlDkBxq4qqqWu56hdU7GH1kvOpd5KmXJdNzt9Fxa2g/KKqLvJ7TX4fIDXyqVobnk9rPlU0oBmcJLSDlf+/SO/4AUqT9ika1jm9nKN/4Tnqfqq4R+f+GeyZb5S3naCX+vuog6RTametNPdApXWYhSScmG9Y3UpEAq+nUy9Z7p+wM288Gw6uRqa5Y+oJGTHvdU/hE8LOV7CmUy6g9WWoqIxAtVRyQqIbqRwdyGSJSeB6z920gziUXfRwL5h2XPE47vB43eGnWA4Oan4Ed+axSWeiLtFFEnoT5VxXqz6J/use/XcPD/e9EjC7S5t3CVqDNKgUlppg8vBGnjXyD0m/u0OsWBia8R6nAXCvuqloqAzvKvpldlR1eAODkVX3Da0icV9V4+DKJoS0CLDfVx6liVguM3gvY+M/JVjUaCXZpmAr+T7jLCcIlvQF61wE+176b/4V+od9+smF/jfSr5v13WthXl9wk9vf</diagram></mxfile>



<!DOCTYPE html>
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
<title>Draw.io Diagram</title>
<meta http-equiv="refresh" content="0;URL='https://www.draw.io/#HHenkWillcock%2FGitTest%2Fmaster%2FUse%20Case%20Diagram.html'"/>
<meta charset="utf-8"/>
</head>
<body>
<div class="mxgraph" style="max-width:100%;border:1px solid transparent;" data-mxgraph="{&quot;highlight&quot;:&quot;#0000ff&quot;,&quot;nav&quot;:true,&quot;resize&quot;:true,&quot;xml&quot;:&quot;&lt;mxfile userAgent=\&quot;Mozilla/5.0 (X11; Linux x86_64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/64.0.3282.119 Safari/537.36\&quot; version=\&quot;8.5.15\&quot; editor=\&quot;www.draw.io\&quot; type=\&quot;github\&quot;&gt;&lt;diagram id=\&quot;cd70c551-0c8d-7477-6860-b23e6f07e7f4\&quot; name=\&quot;Page-1\&quot;&gt;7Vpdb+MoFP01edyR8VfaxyRuZlbqStVUszv7SG3qoMHGi0mT7q/fi40/ME6UzibWKIofWnOBC5xzzwXczrxVtv8scLH5gyeEzVwn2c+8aOa6yHdD+KUs77UlvA9qQypooht1hmf6L9FGR1u3NCGl0VByziQtTGPM85zE0rBhIfjObPbKmTlqgVNiGZ5jzGzrXzSRG21F4X1X8YXQdKOHvmsW/ILjH6ng21yPN3O91+qpqzPc+NILLTc44bueyXuYeSvBuazfsv2KMIVtA1vdb32gtp23ILk8pYNbd3jDbKuX/gBTd51vJRF6hvK9QQUmW6jXbcYWseRi5i3fiJAUcHvEL4Q98ZJKynNo8sKl5Bk0YKpi2aKy4kz1izpcOh8LRlPVV/ICrBuZMSggeOVbyWhOVi3ZDhhfKWM9b+t1tF4ulJ3nUgcUAjiXWHuNARGipmxDpFFT8yD7nklD9pnwjEjxDk107VxHs45u5OnyrosVTxO86UVJqG1YR2faOu4YghdN0jhhc4uwR56mRHH2ew4/bvR9mD7PnY6+O1tve0nypLTYAuNCZTLFBuPxD1g6mBpowrq4pmqkCtAe4EMMD0JGEiMN2oD1EEHN8gVhWNI3M1OOYaLdPXEKw7bg3zsm+CgwPZR8K2KiO/Uz13E/rjvwI7FIibT8VAS1KzyJs3uLs6+kJFjEm5vIThZZgKYTWXOKuKmsRd85j8r8oVrPpzKELNIWSUZzWkqBlZBuSjugtBCZUms4m0Jp9vlx5oYMRli+wEsqqxXWBgWFwWD4z5Y3Fb+VFUgLaICCYt9VNl6i5wLHpPEF86rdmUOAuTfsIF760v0gW4y8yoOhUcLEaJ4+Vm0i5JyHVHQ32CdtUn1njNXgHLR6B2k9mUVnjMXnatusbmRCnVglyQ5SOszUjMHtDwrL3YZKUoeDF+3gAjrIy0Ny1TORFF3HZG1us4bcEdbOQpo/Qtrh7S7nOTm+oQEM4v27TnBV4W9V+BSo4p7K77qfeq9rvMGjK5+IoLAcBXJ0VB71rjTr30zrDcYMy49sqMERtP/nHouQSTbyByyeusmi+XjUXGCTDawY+ZOSHXSL+C5nHCetKi8pP2ci+aGRrHk5/YUWtnA11/fyq0Bz5GBxOTTtDx3Xls2C68xmcP0yoPPvTL9O8AmF3TP3L5bs7I8t1xZC4ZWGkHs8hNBkIWR/+1kJgiVcRNYPCZVXtVu2YTBFfm/8nkWcTk+AjiHAoC9bZMp2TJyq9qfU2URKX57zX0qd/uCQOWTx5NPqQOWed7HjahMTvSD5VlzdKdVDU+ruUlf7NQWjE20LRuMqQTpfScyF+uZ6RRd8PxioaErqxi74N+p+lrpLXg6h2P0Nv0583T9KeA//AQ==&lt;/diagram&gt;&lt;/mxfile&gt;&quot;,&quot;toolbar&quot;:&quot;pages zoom layers lightbox&quot;,&quot;page&quot;:0}"></div>
<a style="position:absolute;top:50%;left:50%;margin-top:-128px;margin-left:-64px;" href="https://www.draw.io/#HHenkWillcock%2FGitTest%2Fmaster%2FUse%20Case%20Diagram.html" target="_blank"><img border="0" src="https://www.draw.io/images/drawlogo128.png"/></a>
</body>
</html>


#### Assumptions:

The team is assuming that post-release support of the software will be minimal and the end-users will have all the necessary information to carry out use cases listed in the functions section of this document. This means that after the product is released there is no requirement for any manual support or Q/A system for users.

Another assumption of the product is that the client has to take care of all the information in the Content Management System (CMS). This means that when the product is ready to be released, the client will need to ensure that the appropriate information is available through the DSpace API.

The team is also assuming that there is a DSpace API already built and that it is well documented allowing team members to easily understand the API, its endpoints and responses within the limited time available.

The team is assuming the Arabic translation support for DSpace functions correctly. We were assured by Ali our client that DSpace provides excellent support for this so it seems like a sensible assumption.

The team is assuming our mockups in Sketch are just general guidelines, and our final design can be changed during development if issues arise or we come up with new ideas.

#### Dependencies:

The end-product will be connected to a Database Management System (DMS). If the connection to the database fails, user actions could fail as a result. These may include actions such as looking for a specific articles.

Another dependency of the product is that the frameworks and APIs need to be pre-loaded to ensure correct operation of the website. All JavaScript, HTML and CSS code must be loaded in order to make sure this occurs. Further to this, due to the nature of web-based applications requiring a connection to the internet, the team assumes that all end-users of the system will have a stable internet connection.

                                                                                         |


<table>
  <tr>
    <th>Risk</th>
    <th>Mitigation Strategy</th>
    <th>Likelihood</th>
    <th>Potiential Impact</th>
  </tr>
  
  <tr>
    <td>Changes to requirements that require major design rework are proposed.</td>
    <td>Propose a compromise with the new requirement that will have the same effect but may be built on top of the current design. Alternatively, a compromise that requires minor changes.</td>
    <td>Low</td>
    <td>Tolerable</td>
  </tr>
   
   <tr>
    <td>Faults in reusable software components have to be repaired before these components are reused.</td>
    <td>Depending on the size of the component, and the number of modules that depend on it. Just repair the faults. If the     module is highly coupled, arrange a meeting with affected group members and see if there is time to fix the fault on a new branch.</td>
    <td>Low</td>
    <td>Serious</td>
  </tr>
  
  <tr>
    <td>Required training for staff is not available.</td>
    <td>Identify what training is needed and research solutions. Utilise online resources and assistance.</td>
    <td>Low</td>
    <td>Tolerable</td>
  </tr>
  
  <tr>
    <td>Key staff are ill at critical times in the project.</td>
    <td>All team members have signed an agreement that specifies that early notice is required in times of absence before times that need the whole team present. Depending on the reason of absence, no action will need to be taken.</td>
    <td>Moderate</td>
    <td>Serious</td>
  </tr>
  
  <tr>
    <td>The organisation is restructured so that different management are responsible for the project.</td>
    <td>There is already one team member leaving in August. The organisation has already been notified of this and will plan how to mitigate this. At present, it will have no major impact that is measurable. There may however be other team members which either join or leave, these cases will need to be dealt with separately.</td>
    <td>Moderate</td>
    <td>Insignificant</td>
  </tr>
  
  <tr>
    <td>Software tools cannot be integrated.</td>
    <td>This is a low likelihood risk. Many of the team members have used the software tools required, specifically Ember.js and are sure it can be integrated. If it cannot there are available alternatives such as Angular.js and Angular 5.</td>
    <td>Low</td>
    <td>Serious</td>
  </tr>
  
  <tr>
    <td>A critical section of the project is unavailable to team members. Impact is dependant on that section.</td>
    <td>All members are apart of the same GitHub repository. If there is a section that is inaccessible, members of the team have all exchange contact details. To mitigate the issue, members would contact the person in charge of the unavailable module and get them to push it to GitHub.</td>
    <td>Low</td>
    <td>Serious</td>
  </tr>
  
  <tr>
    <td>Broken code is included in the final product and released.</td>
    <td>Create a new branch on GitHub for the purpose of fixing the issue and then push it once the fix is complete and shown to not cause any other errors.</td>
    <td>Low</td>
    <td>Serious</td>
  </tr>
  
  <tr>
    <td>Team does not meet critical deadline.</td>
    <td>Meet with the client to arrange a solution.</td>
    <td>Moderate</td>
    <td>Catastrophic</td>
  </tr>
</table>
  
      
### 5.1 Schedule

The project commenced on Thursday 15th March 2018, and will conclude on Friday 19th October 2018. During this timeframe key milestones and deadlines need to be met, ensuring that deliverables are sent to the client on time. Weekly or bi-weekly meetings will be established to assist in communication between the client and the team and to make sure that both parties are on track with any aspects of the project required by the other. The following section will outline the key dates for the project described in this document. Some of these dates are subject to change and may depend on external factors. The team will endeavour to meet all deadlines and reach set milestones within a reasonable timeframe.

#### 04/05/2018 - Project Architecture Review
This Architecture document will be reviewed by both the team and client in a meeting on Friday 4th May to make any necessary amendments or make changes to the vision and scope of the project. This will be an opportunity for both parties to raise any questions or concerns relating to both the functional and non-function aspects of the project. Also, if there are going to be new expectations for any party of the project the deadlines need to be push due to the new expectations.

#### 27/04/2018 - Design Audit Completed
The team will audit both the UI and UX of the existing DSpace and report to ADRI where the team believes improvements can be made, as well as what aspects of the existing design should remain in the new front end design. An audit report will be provided to ADRI and a meeting set up to discuss the team’s findings. Also, there would be a Sketch and pdf file provided for the client to have a brief idea of the visual front-end design.

#### 04/05/2018 - Initial UI and UX Designs Completed 
The front end of ADRI’s DSpace repository will first be designed and wire-framed with an interactive prototyping tool allowing ADRI to both see the UI the team has designed in accordance with ADRI’s branding, and perform UX interactions with the prototype. This initial design will likely need to be reviewed multiple times, so the team will make regular contact to ensure that ADRI’s vision is preserved throughout all aspects of the design.

#### 11/05/2018 - UI and UX Designs Finalised 
Upon completion of all changes to the UI and UX of the front end, both parties will agree on a design that reflects the technical possibilities of the frameworks to be used, as well as ADRI’s vision for the visual aspects of the end product. At this stage of the progress, we have multiple designs and architectures for the solution that we are going to develop and all the designs and architectures have been approved by the client and the team members.

#### 14/05/2018 - Architecture Framework Completed 
A basic framework consisting of all necessary requirements will be delivered to ADRI to demonstrate the basic architecture of the Ember.js framework in use within the DSpace environment. This date cannot be changed.

#### 04/06/2018 - Repository Integration Completed 
At this stage, the architectural prototype will be integrated and working with all necessary repository and database services. This will also include any required connections to third-party services including APIs and resource sharing.

#### 14/06/2018 - Minimum Viable Product Completed
An MVP will be completed by this date, ready for presentation the next day on the 15th. The MVP will consist of a basic Ember.js frontend for the DSpace database system. It will have most of the pages of the final product, but these pages will be subject to change. It will have some design features but not on every page. It will have some functionality but not all the features of the final product. This date cannot be changed.

#### 19/10/2018 - Final Delivery Deadline
This is the final deadline to deliver our product to the client. This date cannot be changed.
