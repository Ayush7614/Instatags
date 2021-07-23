# Instatags

Instatags is a tool that generates random tags for your profile picture, photos and post[DCP '21]

 <p align="center">
    <a href="https://github.com/Ayush7614"><img src="https://github.com/Ayush7614/Instatags/blob/master/instatags.png" width=1000px, height=900px 
 </a> 
</p>

## Open Source Programs 
<img src="https://github.com/Ayush7614/Instatags/blob/master/devincept.gif" alt="DevIncept" />

[![Instatags](https://img.shields.io/badge/Instatags-dodgerblue.svg?style=flat&logo=instagram&logoColor=white)](https://github.com/Ayush7614/Instatags) [![Google Vision](https://img.shields.io/badge/Vision-API-critical.svg?style=flat&logo=google&logoColor=white)](https://cloud.google.com/vision/docs/quickstart) [![Imgur API](https://img.shields.io/badge/Imgur-API-critical.svg?style=flat&logo=highly&logoColor=white)](https://api.imgur.com/)


### APIs Used

- [Google Vision API](https://cloud.google.com/vision/docs/quickstart) - Google Cloud’s Vision API offers powerful pre-trained machine learning models through REST and RPC APIs.

- [Imgur API](https://api.imgur.com/) - Imgur's API exposes the entire Imgur infrastructure via a standardized programmatic interface. Using Imgur's API, you can do just about anything you can do on imgur.com, while using your programming language of choice.

### Getting Started

- Get your own imgur clientID [here](https://api.imgur.com/endpoints/image).
- Replace `XXXXXXXXX` with your clientID in `js/upload.js`.

```javascript
new Imgur({ 
    clientid: 'XXXXXXXXX', // replace this 
    callback: feedback 
});
```
- Get API keys for [Google Cloud Vision API](https://cloud.google.com/vision/docs/quickstart).

- Replace `XXXXXXXX` with your API keys in `js/upload.js`
```javascript

var settings = {
      "async": true,
      "crossDomain": true,
      // change the key below
      "url": "https://vision.googleapis.com/v1/images:annotate?key=XXXXXXXXXXXXXXXXXXX",
      "method": "POST",
      "headers": {
        "Content-Type": "application/json",
        "cache-control": "no-cache"
      },
      "processData": false,
      "data": str
    }

```

- Now open `index.html`
 
 

## 💥 How to Contribute

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
[![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.png?v=103)](https://github.com/ellerbrock/open-source-badges/)

- Take a look at the Existing [Issues](https://github.com/Ayush7614/Instatags.git) or create your own Issues!
- Wait for the Issue to be assigned to you after which you can start working on it.
- Fork the Repo and create a Branch for any Issue that you are working upon.
- Read the [Code of Conduct](https://github.com/Ayush7614/Instatags.git)
- Create a Pull Request which will be promptly reviewed and suggestions would be added to improve it.
- Add Screenshots to help us know what this Script is all about.

# How to make a Pull Request

If you think that you can add a new feature or want to fix a bug. We invite you to contribute to Instatags and make this project better. To start contributing, follow the below instructions:

1. Create a folder at your desire location (usually at your desktop).

2. Open Git Bash Here

3. Create a Git repository.

   Run command `git init`

4. Fork the [repository](https://github.com/Ayush7614/Instatags).

5. Clone your forked repository of project.

```git clone
git clone https://github.com/<your_username>/Instatags.git
```

6. Navigate to the project directory.

```
cd Instatags
```

7. Add a reference(remote) to the original repository.

```
git remote add upstream https://github.com/Ayush7614/Instatags.git
```

8. Check the remotes for this repository.

```
git remote -v
```

9. Always take a pull from the upstream repository to your main branch to keep it updated as per the main project repository.

```
git pull upstream main
```

10. Create a new branch(prefer a branch name that relates to your assigned issue).

```
git checkout -b <YOUR_BRANCH_NAME>
```

11. Perform your desired changes to the code base.

<p align="center"><img width=35% src="https://media2.giphy.com/media/L1R1tvI9svkIWwpVYr/giphy.gif?cid=ecf05e47pzi2rpig0vc8pjusra8hiai1b91zgiywvbubu9vu&rid=giphy.gif"></p>

12. Check your changes.

```
git status
```

```
git  diff
```

13. Stage your changes.

```
git add . <\files_that_you_made_changes>
```

14. Commit your changes.

```
git commit -m "relavant message"
```

15. Push the committed changes in your feature branch to your remote repository.

```
git push -u origin <your_branch_name>
```

16. To create a pull request, click on `compare and pull requests`.

17. Add appropriate title and description to your PR explaining your changes.

18. Click on `Create pull request`.

<p align="center"><img src="https://media.tenor.com/images/b562ddcfb131e962f9dfa01bd32a30d1/tenor.gif" width=30%></p>

Congratulations🎉, you have made a PR to the Instatags.
Wait for your submission to be accepted and your PR to be merged by a maintainer.

---

## Open Source Programs we have been associated with:

<p align="center">
<a href="https://devincept.tech/" ><img src="https://user-images.githubusercontent.com/56088741/123548852-1ef59d00-d784-11eb-8e39-255e0c3e97d5.gif" width="35%" ></a>

</p>
 
---
 
## Project Maintainers

## 🌟 Contributors:

Thanks to these wonderful people ✨✨:

<table>
	<tr>
		 <td>
  <a href="https://github.com/Ayush7614/Instatags/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=Ayush7614/Instatags" />
  </a>
		</td>
	</tr>
</table>
