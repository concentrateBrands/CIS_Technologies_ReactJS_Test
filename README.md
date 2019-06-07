
# Test Overview 
**You will have 48 hours after pulling this repo to complete the assignment. Although this should be easy to accomplish for any senior developer, we put a timeline on it to see your time management skills. If you need more time please reach out to me @ +1 (303) 513-5571 day or night.**

As you are well aware, while working remote, we will be asking you to create something from our experiences and ideas. This is not an easy task to do, so first we must see that you have the ability to take our ideas and put them into good coding practices. 

This is a test to see how well you can create something from a concept. **Utilize whatever free tier technologies you wish, but please use whatever you will be using on the larger project. Any JavaScript written should be utilizing ES6+ features**. Please be aware of licensing terms if using npm packages, this is just good practice for any developer. 

**I have also included a demo link to a visual reference for you to see the skills and knowledge we are looking for on the styling end. 
That demo can be found [here](https://hackerbox.me).**  


## Core Task Overviews
### Auth Task Overview
For this task, you are to give the web app the ability to sign up a client using google account and create another one with a manual entry form. We want you to create a basic landing page with a working authentication. I recommend using OAuth 2.0 as we will be working with google API's in the long run for this app and want to make sure you have a working knowledge of how to integrate tokens and sessions into the architecture. I would also recommend signing up a new gmail account for this task with John/Jane Doe information, this is for your personal protection.
### API Task Overview
Another key point to this test, is to be able to demonstrate the ability to create API routes to retrieve, push, and manipulate the data from a http or preferably https address via that API call. This API does not require security for this test just an open channel to grab generic information. The information that must be returned from the DB call are name, DOB, email, and last login. Once the data is returned either render the information or log it in the console.

### Bonus Reporting Task!!!!!!!!
If you completed the tasks listed above and below and still have some time before the deadline, please try to utilize the included sales_data.csv to be entered into your DB. The real task will be to run reports on this data to see if you have an effective way to grab and process data from DB call.

# Guidelines
Once again you may use whatever stack of free tier technologies you wish in conjunction with React to complete this test, but the stack must be what you will use to work on the bigger project.

**Meaning do not build a easy app just to suite the needs of this simple app. 
Think about the app we discussed, and try to create this app in a similar environment.**
### Test Guidelines: Auth Task
 You may use create-react-app, if using react, or self made templates at your disposal to complete this task. 
 **No purchased templates will be allowed**
   * You must be able to create, sign in, and sign out a account.
  * You must be able to create 2 accounts to push to your DB: 
    * One user created with google sign up
    * Another user created from form, with a non gmail address.
  * Once successfully logged in you should have a generic page to say you have successfully logged in and console.log('Auth Task Complete);
  * Next you should be able to click a sign out button/link to end the user session and then returning to the landing page. 
  * That is all that is needed for this task.
 
### Test Guidelines: API Task
 This task is to make sure you have a solid background in API construction.
  
  * Have a API call to handle a GET request for all the consumers you signed up in your DB earlier. It needs to return the name, DOB, email, and last login.
  * The returned results need to be console logged or displayed on a web page.
  * Address should be something intuitive like https://{yourHostedAddress}/api/consumers/all
  * The next will be to have an API call to get one of the users information using URL parameters
  * Address should be something intuitive like https://{yourHostedAddress}/api/consumers/${id}
  * That is all that is needed for this task.
 
### Test Guidelines: Bonus Reporting Task
  This task is to show a understanding of reporting functions using DB information

 * Upload sample data from CVS into your desired DB of choice.
 * Create simple buttons on a page for each report that runs report script onclick. Results can just be console logged.
 * Run a report to find who the largest buyer is based off of total invoice price with the result being something like an array of client objects with the client name, and totalPriceInvoiced, ordered from most to least.
 * Run a report to find who the largest buyer is based off of total sent units with the result being something like an array of client objects with the client name, and totalUnitsInvoiced, ordered from most to least.
 * That is all that is needed for this task.
### Test Guidelines: Completion
* Your completed code should be pushed up to a personal repo and inside a properly labeled branch.   Example: CIS_Test_-_Development
* Your code should also be hosted somewhere even if it is on its own github page, but the code must be hosted.
* If you are unable to host your own demo website please contact me as there a number of ways to do this for free.
* Once everything is completed please reach out to me via email saying you are done with the assignment along with all URL's you have for both the API and hosted website.

# Reminders
Do not worry about writing perfect code, if such a thing exists, this test is more to see what coding practices you normally use while dealing with a deadline and a concept that we give you.

We are looking for React knowledge and skills of the senior level, so we want to see the use of the new webhooks, if possible, and/or the use of redux for state management, if applicable.