As you know, due to auth verification I couldn't complete the pull request to this repo. So I forked it and did a pull request to my main branch.

Probably this sonar cube report will print out <code>no code smells</code> despite 10 and show <code>no coverage info</code>. I think this is 
because of our already written tests which were uploaded to this repository beforehand. We just adjusted the 'yml' files, gemfile, and configured 
the fastlane folder. 

And while sonar is checking these changes, it doesn't find any added changes to our core project codes.

Here is the result:

<img width="945" alt="image" src="https://user-images.githubusercontent.com/61579338/185742194-68951056-e965-4242-a80a-40f33f43898d.png">
