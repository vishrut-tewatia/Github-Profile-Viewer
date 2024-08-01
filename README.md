-- Github User Profile Viewer --

1. This is a small iOS app which I took up when i started my iOS journey at my first company.
2. This utilises 3 primary github repositories to list down the details of the user:
   . "https://api.github.com/users/" + user -> This fetches the necessary details of the user to show the user details on homescreen
   . "https://api.github.com/users/" + user + "/repos" -> This fetches the various repos of the specific user
   . "https://api.github.com/repos/" + user + "/contributors" -> This fetches the various contributors for the repos of the users.
3. The above APIs were utilised to fetch and display user details, repository information and contributors.
4. Moreover, if you click a specific repostiory and there is a contributor other than the user itself, that contributor can be clicked on and the details for this new user will be listed.

~ Vishrut Tewatia, 22'
