# TheRizzenator3000
Get Rizzed up with The Rizzenator 3000, a free online generator of pick up lines to swoon your crush. 

This project came to be by participating in the Brainrot Hackathon 2024 hosted by Audrey Chen (@/jia.seed) from 11/27 to 12/1.

# INSPIRATION:
Our inspiration for ‘The Rizzenator 3000’ was reminiscing about the show, “Phineas and Ferb” and reflecting on our social anxiety. Thus, we wanted to find a way where we can create a fun and modern way for people to approach others, specifically people they have a crush on. With inspiration from Dr. Doof’s ability to name his inventions with ‘-nator’, ‘The Rizzenator 3000’ was born! 

# WHAT IT DOES:
‘The Rizzenator 3000’ generates different pick up lines when the user clicks on the “Get Rizz Now” button. As the user clicks the button, different pick up lines will appear. 

# HOW WE BUILT IT:
First we started with a simple HTML (Hyper Text Markup Language) file (index.html) and put a test phrase of “hewwo wowold”. From there the CSS (Cascading Style Sheet) named styles.css was created. This would consist of the font, Comic Sans MS, and the background (brainrot.png). The final file (of the languages used to create a website) was the JS (JavaScript) file (script.js).\
**HTML:** The Head of the website consisted of the favicon (favico.ico) which was an edited image of Doctor Doofenshmirtz from Disney’s Phineas and Ferb edited over a toilet. This is meant to represent the “Skibidi Toilet” craze that is popular among the younger folks. Using a favico generator, the original image (doof.jpg) was converted to a favicon, or the icon in the upper right corner of a tab. 
	The body of the website consists of the button that, when clicked, a new brainrot pick up is pulled from a JavaScript array. Initially there was a video of Subway Surfers gameplay playing, this was to mimic the attention span grabber usually found on TikTok, or other social media platforms. The remaining files were the CSS and the JS files linked so they could properly function.\
**CSS:** The CSS consists of 4 different sections. The first one being the font face, which for this project was Comic Sans (ComicNeueSansID.ttf). The second was the properties of the body, this includes brainrot.png which is the main background image of the website. The second background image (which is not visible, but is there in case the other image does not load) is nugget.png, an image of the Gegagedigedagedago nugget, a character found in Max Design Pro’s series, a series popular among younger folk. The third section is the Rizzponse button, which is the section where the pickup lines appear, with over 20 pickup lines being written, each thought out without the use of external sources. Last, but not least, is the button which is styled simply and uses the margin to space it from the top.\
**JavaScript:** The JS function works by getting a value within the array when the user clicks on the button. Each line consists of the phrase inside of quotation marks, separated by a comma. To ensure some form of randomness within the lines, and to prevent the same line from being repeated too much, allowing for other lines to show up for the user. Since randomness is difficult to implement, the variable random consists of the array of pickup lines, the floor function in math which dictates a number like 3.6 would become 3,Math.random() * myarray.length to ensure a unique number most of the time, once again, to prevent the same line from appearing too frequently.  document.getElementById("Rizzponse").innerHTML=random; } returns what is under the value of “Rizzponse”, in our case the pickup lines.


# CHALLENGES:
**Security Issues:** original extension used (great-site.net) on the website would be blocked by our Wifi providers as it was deemed “insecure”\ 
**Lack of experience:** We are both fairly new to using HTML, CSS and Javascript, thus implementing our ideas was a bit of a learning curve\ 
**Unfamiliarity to Brainrot:** Although we encounter brain rot through doomscrolling on social media, we don’t typically use brain rot terms in real life. Thus, implementing brain rot into our project didn’t come to us easily. 

# ACCOMPLISHMENT 
**Implementation of Brainrot:** using references and memes seen in social media into project\
**Website Building:** being able to create and release a website within a short time frame and with limited experience 

# WHAT WE LEARNED
**Improvement in the following languages:** HTML, CSS, JavaScript\ 
**Research:** Being able to effectively research in a topic we’re unfamiliar with (brain rot) in order to portray it in an authentic manner\ 
**Patience:** Through the challenges we’ve faced throughout the project, we were able to be level headed and continue to perservere 

# What's next for The Rizzemetor 3000? 
**AI Chat Bot:** Implement an AI chat feature so that users are able to roleplay what they would say to their crush in order to prevent embarrassing encounters\ 
**Pick up Line Post:** Implement a feature where users are able to submit pick up lines to website\ 
**Subway Surfer Gameplay:** Implement a subway surf gameplay so that players are able be focused while using the website 
**Forum:** Have users put anecdotes on their experiences using our website

# BUILT WITH
HTML, CSS, JavaScript 

# TRY NOW
http://therizzenator3000.infinityfreeapp.com/

