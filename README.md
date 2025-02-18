LuxDoc website. 

To contribute, either fork the project and contribute through a Pull Request or log in directly with LuxDoc credetials and edit the website from the UI.

## How To
- **add/remove a team member**: If you want to modify the team members, just follow the blueprint in the ‵teams.yml‵ page; please notice that the size of the images needs to be squared and with a predefined size(100x100 px). You can use any tool you choose to crop and resize your image.

- **Add an event**: Adding an event to the [list of events](content/portfolio) is easy, albeit a bit cumbersome the first time. You can inspire yourself by looking at the [list of previous events](content/portfolio) and reproducing the structure of the event. Please notice that the event cover needs to be a specific size in order to be displayed properly.
Note that the order of display of the pages is decided by the timestamp associated with the single post, not with the date of the event. Events that have a timestamp in the future won't be published in the website.

- **Modify the registration form**: In order to modify the registration form, log in with the LuxDoc credentials the following website: [YouForm](https://app.youform.com/dashboard) and browse on the desired form. Once the changes are complete, remember to embed the generated endpoint in the desired page. Data will be automatically saved on the typeform website.

## Testing 
Testing the edits in your local environment before committing changes is not mandatory but warmly encouraged. 
Working with GitHub website requires you to be familiar with Git and, in this specific case, with [Hugo](https://gohugo.io/). 
Explaining any of these two tools goes beyond the scope of this simple README, so I recommend you either contact the current the webmaster or take a quick online tutorial like [this one](https://github.com/alburycatalina/Personal-Research-Website).

For the installation of Hugo you can either refer to the [official documentation](https://gohugo.io/installation/windows/) or follow this instructive [step-by-step video](https://www.youtube.com/watch?v=8BrADPJgA-4).

Once your environment is set up, testing the changes will be as easy as typing 

`hugo server` 

from your local terminal. Happy coding!
