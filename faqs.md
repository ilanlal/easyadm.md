# FAQs
 
+ ## How can I access another user's Gmail account?
  This may be due to regulatory restrictions, I'm not sure why but it turns out that Google has not yet built any back-end support options for tracing Gmail messages within the G Suite administrator console

  If your organization needs access to another user's Gmail account or tracks Gmail messages, I Highly Recommend using the __Gmail Reader__, it's a verified %meta.gw% plugin, with a very user-friendly interface and a quick safe installation process directly from you %meta.gwm% administrator console.
 
  ### see at: [G Suite Marketplace](https://workspace.google.com/marketplace/app/ez_gmail_reader/1060242446754)

+ ## Who needs the Gmail Reader?
  If your organization needs access to another user's Gmail account or tracks Gmail messages, I Highly Recommend using the Gmail Reader, it's a verified Google Workspace plugin, with a very user-friendly interface and a quick safe installation process directly from your Google Workspace Marketplace administrator console.

+ ## Do I need to reset the user's password?
  __No,__ We use a Google Service account client, allows our back-server, calls Google APIs, on behalf of you, "Gmail Reader" calls Google APIs, on behalf of end-users, anonymously, and without knowing their passwords.
  
+ ## How to target messages sent during a certain time or by any other parameters?
  You can use words or symbols called search operators to filter your Gmail search results.
  Here is an example search for messages sent during a certain time:  `before:2021/04/18` or `after:04/16/2021`
  
  You can also combine operators to filter your results even more
  ### [More search options](apps/gmail-reader/advanced-search-operators.md)

+ ### How we access your data?
  When you install "Gmail Reader" from the %meta.gwm%, a page comes up asking you to agree to the terms of service of the application and to grant the application access to the data for their Google service. 
 
  When you grant access, it's recorded through a [2-legged OAuth](https://www.google.com/support/enterprise/static/gapps/art/admin/en/cpanel/2-legged-oauth-diagram.png) access token. 
 
  In that an administrator grants access to "Gmail Reader" application for the Google service for ALL users in their domain. 
 
  Data requested for access include: get Gmail content and get the Users list.
 
  this design scenario, in which the "Gmail Reader" app calls Google APIs, on behalf of you, anonymously, and without knowing user's passwords. 
 
  ### <a markdown="1" title="How %meta.gwm% apps access your data" href="https://support.google.com/a/answer/176367" target="_blank">Read more...</a>

+ ## What and When specific data we will access?
  1) Access to the Sensitive data scope of /auth/gmail.readonly to allow view user's email messages and settings. 
  2) Access to the Restricted data scope of /auth/admin.directory.user.readonly to allow list all domain users.
  
  That specific scopes are no more than the minimum required for application functionality.

+ ##  Is there anyway that the users in the domain does not see the application in the google app menu?
  App Launcher is an exclusive GCP (Google Cloud Platform) service.
  As a google third-party developer, I have no ability to interact with the App Launcher.
 
  So no, there is no way

+ ## Do I need to pay for user membership?
    
  We encourage you to test the trial version first, and only if the Application suits your requirements, proceed to establish a payment agreement.


  #### See: [Price](apps/gmail-reader/prices.md) 

+ ## [Contact me](mailto:ilan@easyadm.com)

  If you have any questions, just send an email message to address <a href="mailto:ilan@easyadm.com" target="_blank">ilan@easyadm.com</a>
  
  I will personally respond.