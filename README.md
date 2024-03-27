Team Name: Team Dominguez (Team #2)

TravelSphere, a travel forum deployed on phpBB to facilitate connections between like-minded individuals who wish to connect on different topics related to travel.


**Screenshot of our program in its current state**
![image](https://github.com/ethedge/1TravelSphere/assets/158501435/f0fb891b-355f-43e3-9511-aa99f748b877)


**Website Domain**
http://travelsphere.lol/phpBB3/index.php?sid=bf81a7edb87b2d749cf3a445270bc886

**Completed features by end of second sprint**
- Purchased, configured and set up Ubuntu based VPS with DigitalOcean
- Installed LAMP stack on VPS
- Installed phpBB forun software on VPS
- Created and added company logo to website
- Gathered all images/assets that will be used on website
- Recolored any images/assets to fit black/gold color scheme
- Create a new phpBB style called "TravelSphere", based on prosilver style (phpBB default style)
- Made continuous edits to colors.css within new style, using pre-existing infrastructure from prosilver.
- Modified multiple .css files within TravelSphere style
- Purchased a domain and configured the domain with DigitalOcean
- Established Git on the VPS for better development
- Added usermap extension to the forum
- Added user flag functionality to the forum
- Populateed forum with general information, rules, TOS
- Populated forum with overall infrastructure.

**Not Completed Features**
Integrate HTTPS (Hypertext Transfer Protocol Secure)

**Product Goal**
Objective: To create a functioning travel forum.
Target Audience: Travel enthusiasts.
Purpose: Facilitate connections and discussions among travel enthusiasts.

**Sprint Goal**
Objective: Update the styling and add additional functionality towards our website
Collaboration: Enable the team to work on and collaborate on the project.
Development Environment: Ensure the domain is set up for collaborative development

**Definition of done**
Our definition of done is defined as:
- All features committed to the sprint are implemented and the the acceptance criteria has been met. 
- Code changes have been reviewed by at least 1  team members
- Code that has passed through the linter

**How to deploy the website?**
This GitHub repository contains phpBB source files. Modified source files have been merged into the main branch. This repository is a replication of what is currently being run on the VPS, which is hosting our domain. Here is a step-by-step guide on how to deploy the website on your own system:

1. **Download phpBB:** Go to the phpBB website and download the latest version of the forum software.
2. **Setup a local server enviornment:** A local server environment is required to run Apache and MySQL. XAMPP can be used. 
3. **Create database:** Once Apache and MySQL are configured and running, open your web browser and go to http://localhost/phpmyadmin/. Here, you can create a new MySQL database for phpBB to use. 
4. **Access phpBB installer:** Open your web browser and navigate to http://localhost/phpbb/install/.
5. **Follow the installer:** The phpBB installer will guide you through the installation process step by step. You'll be prompted to enter database connection details, administrator account information, and other configuration settings.
6. **Database configuration:** During the installation process, provide the requested database details (from the database you made earlier), including the database name, username, password, and database server (localhost).
7. **Remove the install directory:** After the installation is complete, for security reasons, delete the install/ directory from your phpBB installation directory.
8. **Access your phpBB forum:** You can now access your phpBB forum by going to http://localhost/phpbb/ in your web browser.
9. **Integrate our changes to the forum:** You can now download this Github respository, and replaces the default files generated upon phpBB deployment. This will allow you to run the forum, with all our changes.
10. **Activate TravelSphere style:** After porting our files over, navigate to ACP, and activate the TravelSphere style. 
