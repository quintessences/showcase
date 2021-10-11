# showcase
How to contribute?
Follow the instructions in order:

Fork this repository.

Clone your fork, using git clone URL

Change Directory using cd

Create a branch named feature-{github-username}, using git checkout -b feature-{github-username}

Open the current directory in your editor.

Fill this block with necessary info of yourself.

{
  "name": {YOUR_NAME},
  "batch": {YOUR_BATCH_COMMENCEMENT_YEAR},
  "picture_url": {PICTURE_CDN_URL},
  "twitter": {TWITTER_HANDLE_LINK},
  "github": {YOUR_GITHUB_PROFILE_LINK},
  "linkedin": {YOUR_LINKEDIN_PROFILE_LINK},
  "quote": {QUOTE_WHICH_DEFINES_YOU}
}
To get your PICTURE_CDN_URL head over to https://imgbb.com/ and upload one of your nice looking image and get's it's url.

Now add the above filled block to the data array in data.json file

Stage your changes with commend git add data.json

Now commit the changes with comment message, git commit -m "Add {YOUR_GITHUB_USERNAME} information"

Push the changes using, git push --set-upstream origin {CURRENT_ACTIVE_BRANCH_NAME}

Open a pull request: As soon as the changes will be pushed, GUI of repository's main page will show a yellow banner saying you too open a Pull request, just click on it and you are done.

Happy Hacking ✌️