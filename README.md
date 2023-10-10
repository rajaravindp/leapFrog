# leapFrogLinkedIn
**Automate you job search endeavors with leapFrogLinkedIn.** <br>

**__init__(self, email, password)** <br>
This method initializes a new instance of the LinkedInBot class. It takes the user's email and password as arguments, sets up the Chrome webdriver, and logs in to LinkedIn with the provided credentials.

**locate_links(self)** <br>
This method locates the profile links of LinkedIn users based on specified search criteria. It extracts the 'href' attributes of the links found within the unordered list of LinkedIn profiles. This method returns a list of unique LinkedIn profile links.

**send_connection_requests(self, links, message)** <br>
This method sends connection requests to LinkedIn users with a personalized message. It takes a list of LinkedIn profile links and a message string as arguments. The method navigates to each profile in the list, sends a connection request, and includes the personalized message with each request.
