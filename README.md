[TH20]: https://github.com/GTunuFu/Student2Startup/blob/master/TamuHacklogo.png "TAMUHACK 20 LOGO"
[S2S]: https://github.com/GTunuFu/Student2Startup/blob/master/www/sslogo.png "S2S Logo"
[SlackMockUp]: https://github.com/GTunuFu/Student2Startup/blob/master/MockUpSlackProfileScreenShot.png "Mock up Slack Profile Page"
(https://devpost.com/software/student2startup "Devpost")
![alt text][S2S]
# Student2Startup
A Hackathon project aimed to bridging the modern gap between startups and students.

###### Inspiration
There are tons of startups starting and terminating operation annually, that never get to live the life they deserved to live. This is because the lack of finances, which prevents them from having the same reach on talent as the titans of their industries. At the same time not only are start ups having trouble finding talent, but students are tired of searching forever, yet falling short, to find a company that truly is in tune in terms of interests. Thats why we reached out to make an app, that aids both parties, and finally brings light to the underdogs of the industry!

###### What it does
Instead of building it similar to all other recruiting websites, we decided to add something that would make conversation between start-ups and students way more comfortable. This is why we built this app more in terms to resonate a formal social media platform, be it an oxymoron, this serves well to our purpose. After the company and the student have built profile pages that explain a little bit about themselves through short text and video, they will be able to interact with each other. Students will be able to answer questions/prompts posted by the company to tackle the lack of huge HR events or visitation at career fairs. These prompts will allow the company to understand the EQ of the students facing possible hire, without the immense cost that usually comes with. For students, the same applies, we give them the same opportunity to learn about the start up, as the start up will be asked to answer a basic prompt developed by S2S. This will allow the both sides to get a clear understanding on whether or not they are a best fit for each other. Since S2S takes the bulk of the difficulty of sorting and interviewing, it eases the load for start-ups. Ultimately allowing for precise picks for outstanding talent.
## Version 1.0 ![alt text][TH20]






Since we started over at hackathon I will be writing this in as all in one version to explain all progress that was made at the TAMU HACKATHON for thew 2020 MLH season. 

**Quick Notes:**
- This was built mostly in native HTML,CSS, and JS with bootstrapper
- To create mobile interface, we used adobe phonegap to push to android 
- Has basic infrastrture from Google Firebase

```
  <div class="w3-overlay w3-animate-opacity" onclick="w3_close()" style="cursor:pointer" id="myOverlay"></div>
  <div>
    <button class="w3-button w3-white w3-xxlarge" onclick="w3_open()">&#9776;</button>
  </div>

  <div class="w3-sidebar w3-bar-block w3-animate-left" style="display:none;z-index:5" id="mySidebar">
      <button class="w3-bar-item w3-button w3-large" onclick="w3_close()">Close &times;</button>
      <a href="#" class="w3-bar-item w3-button">Search Startups</a>
      <a href="#" class="w3-bar-item w3-button"><a href="Home.html">My Profile</a></a>
      <a href="#" class="w3-bar-item w3-button"><a href="howto.html">How to S2S</a></a>
  </div>
  ```
  Above is code devoted for the sidebar that operated for navigational purposes amoung the entire page. Other than removing or adding different links to this, the basic code remains the same across all pages on the aplication. *Got the template for this from w3schools*
  

![alt text][SlackMockUp] 

