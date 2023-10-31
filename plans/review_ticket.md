---
layout: post
title: Review Ticket
courses: { compsci: {week: 11} }
type: tangibles
---

## Key Contributions to our Passion Project

### Frontend
In my role on the frontend team, I played a crucial part in ensuring the quality and user experience of our web application. I actively contributed by meticulously testing the frontend and diligently pointing out issues and potential improvements. By conducting thorough tests, I identified various user interface inconsistencies, functional bugs, and performance issues that might have otherwise gone unnoticed. Through clear and detailed feedback, I enabled the team to address these issues promptly, enhancing the overall user experience. My commitment to ensuring a seamless and visually appealing interface helped create a more user-friendly environment, demonstrating my dedication to the project's success and the satisfaction of our users.

### Backend
In the initial stages of our project, I played a pivotal role in shaping the backend infrastructure. I took the initiative by creating the original repository and jumpstarting our API development. Leveraging the example APIs provided with Jason, I meticulously crafted the foundation of our backend operations. This involved not just copying and pasting but understanding the intricacies of each API, ensuring they seamlessly integrated into our system. My efforts laid the groundwork for our backend, establishing the fundamental pathways through which our application would operate.

As our project evolved, so did our backend requirements. We made a strategic decision to transition from our original API format to utilizing SQL databases. This shift was driven by the need for a more accessible and scalable solution. SQL databases provided us with a robust framework, offering enhanced data management capabilities and improved accessibility for both developers and end-users. Embracing this new technology allowed us to streamline our backend processes, ensuring a more efficient and reliable experience for everyone involved.

During the transition and subsequent testing phase, we encountered significant challenges. Testing the GET, POST, PUT, and DELETE functions is integral to ensuring the reliability and functionality of any backend system. We faced hurdles that tested our problem-solving skills and patience. Issues cropped up, and at times it seemed like a daunting task to get all these functions working seamlessly together. However, through relentless perseverance and collaborative teamwork, we overcame these difficulties. Through rigorous testing, debugging, and continuous refinement, we managed to resolve the issues, ensuring that our backend operations were not only functional but also optimized for performance. This experience not only strengthened our technical expertise but also underscored the importance of teamwork and determination in overcoming complex challenges in the world of backend development.

### DevOps and Deployment
As a dedicated backend programmer, I played a pivotal role in enhancing the synergy between our development teams. Working closely with Matthew, our skilled DevOps engineer, I collaborated on testing procedures and streamlined communication channels between the frontend and backend systems. My expertise in backend technologies allowed me to optimize the backend infrastructure, ensuring seamless data flow and efficient processing. Together with Matthew, we established robust protocols that facilitated effective communication between the frontend and backend teams.

### Important Commits
[Commit on 10/8](https://github.com/dino596/test_api/commit/c0d05f59d5c010da7ef3b0d3f81070030ebe9e5d) <br>
- This was my initial commit after creating a new repository to test the SQL database. This was a very simple API with only GET method.

[Commit on 10/9](https://github.com/dino596/test_api/commit/b6aebc4584c7f96ff06bc67d861122d77c37ef1c) <br>
- This was my commit where I added soulsList, which could function with GET to access the entire database rather than transmitting one object at a time.

[Commit on 10/13](https://github.com/dino596/test_api/commit/d8890635b5bf9836d158370d7f57c35e6b9e9af1) <br>
- This commit was very important, since I added the foundation to the (non functional at the time) POST, PUT, and DELETE methods. I would later test them and realize that POST and DELETE worked, but PUT did not work, prompting me to submit a Github Issue about the subject.

[Commit on 10/15](https://github.com/dino596/test_api/commit/20cf033878d91abfb74edd3a305ced8ea088942a) <br>
- I fixed the PUT method in this commit, meaning that the API was now fully functional.

[Commit on 10/16](https://github.com/dino596/JARMIRAMJI/commit/921328c6ee2007743b0838809c35a9181f2ec1b4) <br>
- I migrated my old API onto the new repository, and we worked on another API for characters instead of classes.

### Issues
[Issue on 10/15](https://github.com/dino596/test_api/issues/1) <br>
- This was the issue that I created in order to signal to myself that I needed to fix the PUT method. Later, I fixed the PUT method, and Jason confirmed it by testing it with Postman.

## College Board Quiz Notes

### Questions I Needed Help On

**Question 3:** Which of the following would be the best use of citizen science?
I had to search up what citizen science was, and Google gave me "the collection and analysis of data relating to the natural world by members of the general public, typically as part of a collaborative project with professional scientists."
Based on that knowledge, I chose C: "An experiment that requires data measurements to be taken in many different locations."

**Question 6:** Which of the following best describes the role of the Internet Engineering Task Force (IETF)?
I had to search up IETF, which led me to this: "The Internet Engineering Task Force (IETF) is a standards organization for the Internet and is responsible for the technical standards that make up the Internet protocol suite (TCP/IP)."
Based on this, I chose A, which is "Developing standards and protocols for Internet communication."

**Question 24:** Which of the following statements about pair encoding is true?
I did not know the difference between lossless and lossy transformation, and after searching it up, I have learned that the difference is that lossy reduces file size by permanently removing some of the original data, and lossless reduces file size by removing unnecessary metadata.
Because of that, I chose C: "Byte pair encoding is an example of a lossless transformation because an encoded string can be restored to its original version."

**Question 51:** Which of the following is an example of symmetric encryption?
Symmetric encryption is defined as "using a single key to encrypt and decrypt."
I used this information to pick B: "Finn and Gwen develop a system that maps each letter of the alphabet to a unique symbol using a secret key. Finn uses the key to write a message to Gwen where each letter is replaced corresponding symbol. Gwen uses the key to map each symbol back to the original letter."

**Question 64:** Which of the following statements describe how cloud computing has affected Internet communication?
I searched up cloud computing, which gave me "delivery of computing services-including servers, storage, databases, networking, software, analytics, and intelligence."
As a result, I picked B and C, which were "cloud computing has helped enhance collaboration," and "cloud computing has introduced new data-security concerns."

### Questions That I Got Wrong

**Question 35:** A musician is creating a song using audio samples. Which of the following actions will minimize the risk of a copyright violation when creating sample-based music?
I originally picked C: "using samples from nondigital sound sources (vinyl records, tapes, etc.)" because I thought this would reduce the risk of a copyright violation. However, the correct answer was D: "using samples published with a no-rights-reserved Creative Commons license," since Creative Commons licenses can be used by creators of digital music to specify how the samples can be used by others, and a no-rights-reserved license allows others to freely make use of the samples.

**Question 43:** An online retailer uses an algorithm to sort a list of n items by price. The table below shows the approximate number of steps the algorithm takes to sort lists of different sizes. Based on the values in the table, which of the following best characterizes the algorithm for very large values of n ?
I picked B: "the algorithm runs, but not in a reasonable time," because I thought n^2 was not efficient especially for very large values, but according to College Board it is A: "the algorithms runs in a reasonable time," since n^2 is a polynomial, meaning it is reasonable.

**Question 60:** Which of the following are ways in which a programmer can use abstraction to manage the complexity of a program?
Instead of picking D: "Replacing several lines of documentation with a single line of documentation name1, name2, name 3, and name 4 with a list of strings
called names," i picked "replacing longer variable names  with shorter variable names to reduce typing errors," since I thought shorter variable names would help reduce typos and the complexity of the program. However, the correct answer was D since creating data abstraction may make it easier for a programmer to manage the complexity.

## Trimester 1 Reflection

During trimester one, my collaboration with Jason, our other backend, on our passion project was an enriching experience that significantly enhanced my understanding of computer science and teamwork. Jason and I worked seamlessly together, leveraging our individual strengths to create a robust and efficient backend infrastructure for our project. Through countless hours of coding and problem-solving, I gained invaluable insights into backend development, learning about databases, server-side scripting, and optimizing performance. This collaboration not only enhanced my technical skills but also taught me the importance of communication and coordination in a team setting. Jason and I learned how to synchronize our efforts, ensuring that our backend systems seamlessly integrated with the frontend components developed by our talented colleagues.

Additionally, working collaboratively with Isabelle, Matthew, and Rayane on the frontend further expanded my knowledge during this trimester. Engaging with the frontend team allowed me to appreciate the intricacies of user interface design and user experience, highlighting the symbiotic relationship between frontend and backend development. Through active participation in group discussions and hands-on coding sessions, I grasped the significance of aligning frontend and backend functionalities to create a cohesive and user-friendly application. This experience not only honed my technical abilities but also emphasized the importance of empathy and understanding the end user's perspective. Overall, this trimester has been instrumental in broadening my horizons, fostering collaboration skills, and deepening my understanding of the dynamic interplay between frontend and backend aspects of computer science.