AirBnB Clone Project - Version 4 README
General Information
Requirements
Editors Allowed: vi, vim, emacs.
Browser Compatibility: All files will be interpreted on Google Chrome (version 57.0 or later).
Code Standards: All code must be semistandard compliant. Use the command semistandard *.js --global $ to check your files.
File Structure: All JavaScript files must be placed in the scripts folder. Do not use var keyword.
jQuery: Only version 3.x of jQuery is allowed and should be included in your HTML files.
Non-Reloading: HTML should not reload for any DOM manipulation, updates, or data fetching.
New Line: Every file should end with a new line.
GitHub Usage
Repository: There should be one project repository per group. Avoid duplicating project repositories with the same name after the second deadline to prevent scoring issues.
More Info
JQuery Import:
html
Copy code
<head>
    <script src="https://code.jquery.com/jquery-3.2.1.min.js"></script>
</head>
Local Setup:
Before starting, ensure you have Flask and Flasgger installed:
bash
Copy code
sudo apt-get install -y python3-lxml
sudo pip3 install flask_cors flasgger
Troubleshoot potential dependencies as required (e.g., jsonschema, pathlib2).
Vagrant Port Forwarding
To access the application locally, forward the required ports in your Vagrantfile:
ruby
Copy code
config.vm.network :forwarded_port, guest: 5001, host: 5001
Task Overview
0. Last Clone
Fork and set up a new codebase, ensuring all dependencies and standards are met. Update README.md to reflect new contributions.

1. Cash Only
Migrate Flask application to a dynamic setting without reloading the HTML for any actions. Implement cache busting for static assets.

2. Select some Amenities to be Comfortable
Make the filter section dynamic, allowing for amenities to be selected and displayed without page reloads.

3. API Status
Implement CORS correctly to handle requests from all origins and provide API status feedback in the UI.

4. Fetch Places
Modify the application to fetch and display places dynamically from a backend API using AJAX.

5. Filter Places by Amenity
Enhance the dynamic filtering by allowing users to filter displayed places based on selected amenities.

6. States and Cities
Implement filtering based on states and cities in addition to amenities.

7. Reviews
Add functionality to show and hide reviews dynamically, fetching data as needed without reloading the page.

Author
Wendwesen TEFERA - Initial work and additional contributions to the AirBnB_clone_v4 project.
For a detailed guide on each task and further information, please refer to individual files and code comments within the repository.
