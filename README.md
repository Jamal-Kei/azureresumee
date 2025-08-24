Custom Domain : https://jamalsresume.uk/

Azure link : https://azureresumeacgg.z35.web.core.windows.net/

Hello , to whoever reads this . This will just be a summary of how I got on with this projects , things i realised on this project and any obstacles I came across and how i resolved them .

1. Building the front end

This was part of the project was the most enjoyable especially as someone who was just starting there tech journey . I focused on creating a clean and responsive design using HTML for the structure and CSS for styling. HTML was used to lay out the basic elements like headers, paragraphs, and images, while CSS brought the site to life with colors, fonts, and layout adjustments. This process was a great learning experience, helping me understand the importance of semantic HTML and the power of CSS in enhancing user experience. Additionally, I created a GitHub repository to manage the project's codebase, which helped in version control . This step introduced me to the basics of Git and GitHub, allowing me to track changes that I had made in the project .

Obstacles 

Obstacles in this area were minimal, primarily involving basic syntax errors and ensuring consistency with class names in the code. These challenges were manageable and served as valuable learning opportunities. Overcoming them helped reinforce good coding practices, such as attention to detail and consistency, which are crucial in web development. Reflecting on the experience, these minor hurdles contributed significantly to my understanding of HTML and CSS, and they improved my overall coding skills.

2. Building the Back end

This part of the project was somewhat challenging, but I was thrilled when I successfully implemented it. My goal was to create a "visitor counter" using a cloud-based API to interact with our website. First, I set up an Azure Cosmos DB account to access the Table API and created a simple API endpoint to update and retrieve the visitor count. Then, I developed an Azure Function to link the Cosmos DB account with the function, enabling us to view the counter data through this function. This integration enhanced my understanding of cloud services and backend development.

3. integrated frontend with backend

This was one of the easiest parts of the project. I simply wrote a bit of code locally in my "getResumeCounter" file and included Cross-Origin Resource Sharing (CORS) in this code. CORS is a security feature implemented by web browsers that allows controlled access to resources located outside of a given domain. By configuring CORS, I enabled mywebsite to securely make requests to the API from different origins, ensuring that the visitor counter data could be accessed and displayed without security issues.

4. Deploying to azure

After writing the code , I used the extension Visual studio code which is the azure function app to deploy eveyrthing we have done locally to azure via the function app . This allowed our visitor counter to be stored on azure via an app. After this was done i deployed my website to an azure storage via the extension so that I could enable the static website on azure . This part was also fairly convienet as I managed to do the hard parts earlier on and this section was just bringing everything together . 

Obstacles 
I had an issue in azure which was my images were not showing when i pasted the azure url into google . This was due to an error in the file path for my images . After endlessly searching the web to discover this issue , this issue was a lot minor than I had imagined . 

5. Building CI/CD Pipeline

This allowed me to automate the software development process, from code integration to deployment. In this section, I created unit tests to test my Azure function code as part of its deployment workflow. These tests ensured that the functions performed as expected before they were deployed, catching potential issues early in the development cycle. Implementing unit tests as part of the CI/CD pipeline not only improved the reliability and quality of the code but also facilitated quicker iterations and updates, enhancing overall project efficiency.


