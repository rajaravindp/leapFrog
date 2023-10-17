# leapFrog
**Automate you job search endeavors with leapFrogLinkedIn.** <br>

To those diligently navigating the challenging waters of pursuing internships or full-time opportunities amidst a demanding academic landscape, project commitments, and personal endeavors, this message is for you. If the demands of a hectic schedule hinder your job search and networking endeavors, please allow this post to serve as a beacon of encouragement and a source of practical guidance to alleviate your concerns.

The tool is designed to simplify and expedite your job search and networking activities. By leveraging this tool, you can effortlessly compile essential information for your job search without having to manually browse through LinkedIn profiles. This tool will help you automate the process of sending personalized connection requests with thoughtful notes, thereby enhancing the effectiveness of your networking efforts. I hope this tool saves you valuable time and effort, allowing you to focus on other important aspects of your academic and personal life.

LeapFrog is an automation tool engineered to optimize the job search and networking process on LinkedIn. It operates by programmatically interfacing with LinkedIn's web interface using Selenium WebDriver to simulate user interactions. Here's a more technical description:

**Authentication**: LeapFrog starts by logging into LinkedIn using the provided email and password credentials.

**Profile Search and Link Extraction**: Based on the input parameters for the company and position, LeapFrog constructs a specific search URL and navigates to it. It then locates and extracts the unique profile links of LinkedIn users associated with the specified company and position.

**Connection Requests**: The tool iterates through each extracted profile link, navigating to the individual user's LinkedIn profile. It utilizes Selenium to identify and interact with the "Connect" button. If the "Connect" button is not immediately visible, it may check for the presence of additional UI elements (e.g., a "More" dropdown) to find the connection option.

**Personalized Messages**: LeapFrog supports the option of sending a personalized connection request message. It interacts with the UI elements to input the message text into the appropriate field before submitting the connection request.

**Error Handling and Logging**: The tool incorporates exception handling mechanisms to manage common issues such as missing elements, page load timeouts, or failed connections. It may also include logging functionalities to record the progress and any encountered issues.

**Session Management**: After processing all the profile links, the tool gracefully terminates the Selenium WebDriver session, ensuring all browser windows are closed.

By automating these repetitive and time-consuming tasks, LeapFrog empowers users to efficiently connect with potential employers and network contacts, significantly reducing the manual effort required in the job search process.
