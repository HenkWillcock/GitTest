### 4.4 Physical

<mxfile userAgent="Mozilla/5.0 (X11; Linux x86_64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/64.0.3282.119 Safari/537.36" version="8.5.15" editor="www.draw.io" type="github"><diagram id="bf212a89-b111-2ca9-afcf-8fabc0d67d5c" name="Page-1">7Vhdb5swFP01PK4KOKHpYwjN+rBJ1VKp7aMJN2DVwcw4X/v1s+HynVSp2qWblkoV+Pja9/qee+xgi0xXu6+SpvF3EQK3nEG4s4hvOY49dFz9MMi+QK6HwwKIJAvRqAbm7BcgOEB0zULIWoZKCK5Y2gYXIklgoVoYlVJs22ZLwdteUxpBD5gvKO+jjyxUMaK2e1N33AGLYnQ9Lhcc0MVLJMU6QX+WQ5b5X9G9ouVcuNAspqHYNiBya5GpFEIVb6vdFLjJbZm2YtzsSG8Vt4REnTLAKQZsKF9DGbHL9VAvZBsTn9pjTtyfaxOUp2CnvlDOosQiE0OB9gSy7tdvET7zeYISeAT9OpiD3OTmvDCaBd0BGst9t9EPD6cC5IEAzhTULVOxwQdU/3Oh608/hQH0BCCTvJ1hxgbrDEJTYnujhhhy04gmLKOKieTqWKhOK0RHz6WY9jQpwvOVSLUZButjpMTLUrpgSfRgev1xDXyDpSksp0Z+oAzsHItpahwt1gGYZqFsLWuTLKmlqiPVQCbWRgjeUiRqjrEZm1ituLEvu3B4wxv6XjLOp4LrXJlFkdnMn3kTY6WkeIFGD3HJDdHF7m1jpmCuJzEzbvW2VSXHZAR2RwVkV7LU2x2IFShpGMABIxQybnRVe1tvG84AsbixY9jlDkBxq4qqqWu56hdU7GH1kvOpd5KmXJdNzt9Fxa2g/KKqLvJ7TX4fIDXyqVobnk9rPlU0oBmcJLSDlf+/SO/4AUqT9ika1jm9nKN/4Tnqfqq4R+f+GeyZb5S3naCX+vuog6RTametNPdApXWYhSScmG9Y3UpEAq+nUy9Z7p+wM288Gw6uRqa5Y+oJGTHvdU/hE8LOV7CmUy6g9WWoqIxAtVRyQqIbqRwdyGSJSeB6z920gziUXfRwL5h2XPE47vB43eGnWA4Oan4Ed+axSWeiLtFFEnoT5VxXqz6J/use/XcPD/e9EjC7S5t3CVqDNKgUlppg8vBGnjXyD0m/u0OsWBia8R6nAXCvuqloqAzvKvpldlR1eAODkVX3Da0icV9V4+DKJoS0CLDfVx6liVguM3gvY+M/JVjUaCXZpmAr+T7jLCcIlvQF61wE+176b/4V+od9+smF/jfSr5v13WthXl9wk9vf</diagram></mxfile>





#### Assumptions:

The team is assuming that post-release support of the software will be minimal and the end-users will have all the necessary information to carry out use cases listed in the functions section of this document. This means that after the product is released there is no requirement for any manual support or Q/A system for users.

Another assumption of the product is that the client has to take care of all the information in the Content Management System (CMS). This means that when the product is ready to be released, the client will need to ensure that the appropriate information is available through the DSpace API.

The team is also assuming that there is a DSpace API already built and that it is well documented allowing team members to easily understand the API, its endpoints and responses within the limited time available.

The team is assuming the Arabic translation support for DSpace functions correctly. We were assured by Ali our client that DSpace provides excellent support for this so it seems like a sensible assumption.

The team is assuming our mockups in Sketch are just general guidelines, and our final design can be changed during development if issues arise or we come up with new ideas.

#### Dependencies:

The end-product will be connected to a Database Management System (DMS). If the connection to the database fails, user actions could fail as a result. These may include actions such as looking for a specific articles.

Another dependency of the product is that the frameworks and APIs need to be pre-loaded to ensure correct operation of the website. All JavaScript, HTML and CSS code must be loaded in order to make sure this occurs. Further to this, due to the nature of web-based applications requiring a connection to the internet, the team assumes that all end-users of the system will have a stable internet connection.
