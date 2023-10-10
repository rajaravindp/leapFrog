# leapFrogLinkedIn
**Automate you job search endeavors with leapFrogLinkedIn.** <br>

To those diligently navigating the challenging waters of pursuing internships or full-time opportunities amidst a demanding academic landscape, project commitments, and personal endeavors, this message is for you. If the demands of a hectic schedule hinder your job search and networking endeavors, please allow this post to serve as a beacon of encouragement and a source of practical guidance to alleviate your concerns.
The code is designed to simplify and expedite your job search and networking activities by automating the extraction of LinkedIn profile links for professionals working in specific roles at your chosen company. By leveraging this web scraping tool, you can effortlessly compile essential information for your job search without having to manually browse through LinkedIn profiles. This tool will help you automate the process of sending personalized connection requests with thoughtful notes, thereby enhancing the effectiveness of your networking efforts. This shall save you valuable time and effort, allowing you to focus on other important aspects of your academic and personal life.

**__init__(self, email, password)** <br>
This method initializes a new instance of the LinkedInBot class. It takes the user's email and password as arguments, sets up the Chrome webdriver, and logs in to LinkedIn with the provided credentials.

**locate_links(self)** <br>
This method locates the profile links of LinkedIn users based on specified search criteria. It extracts the 'href' attributes of the links found within the unordered list of LinkedIn profiles. This method returns a list of unique LinkedIn profile links.

**send_connection_requests(self, links, message)** <br>
This method sends connection requests to LinkedIn users with a personalized message. It takes a list of LinkedIn profile links and a message string as arguments. The method navigates to each profile in the list, sends a connection request, and includes the personalized message with each request.
