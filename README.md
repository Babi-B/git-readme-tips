# markdown-tips
[![Contributors](https://img.shields.io/badge/contributors-1-brightgreen.svg)](https://github.com/Babi-B/markdown-tips)

# Table of Content
<ol>
  <li><a href='#intro'>Introduction</a></li>
  <li><a href='#upload'>Uploading an image</a></li>
  <li><a href='#badges'>Badges</a></li>
  <li><a href='#nested-list'>Dropdown Lists</a></li>
  <li><a href='#font-awesome'>Using Font Awesome Icons</a></li>
  <li><a href='#contribute'>Contribute</a></li>
</ol>

# <span id='intro'>Introduction</span>

This is a simplified outline of a few tips that can be added to a git README.md markdown to spice up your documentation. 
# <span id='upload'>Uploading an image</span>

Uploading a picture is very simple. Just copy and paste. This works with png, jpg, and jpeg files.

# <span id='badges'>Badges</span>
The colors relay different messages<br>
![image](https://user-images.githubusercontent.com/66228179/153201992-db6b7802-a915-483f-a8d9-ca9f545c68c6.png) &emsp;![image](https://user-images.githubusercontent.com/66228179/153202236-c81a1ee0-2054-431b-9be8-3708fbcc1408.png)

On how to add badges check this detailed <a href=''>blog</a> for a step to step guide.

For more badges check <a href='https://shields.io/'>shields.io</a>

# <span id='nested-list'>Dropdown Lists</span>

Nested dropdown lists are made with the `details` html tag. By defaul the details tag is closed
<details><summary>Click to open</summary>
  Hello World!
</details>

```
<details><summary>Click to open</summary>
  Hello World!
</details>
```

But can be made open using the <code>open</code> attribute
 
<details open><summary>Click to close</summary>
  You left me open...
</details>

```
<details open><summary>Click to close</summary>
  You left me open...
</details>
```

# <span id='font-awesome'>Font-awesome</span>

Git markdown does not have support for inline CSS so the font-awesome icons themselves can't be used. However, there is a way to work around that:

<ul>
<li>First download or get a pic of the icon. It should be in a png, jpg, or jpeg format.</li>
<li>Upload the picture to the markdown. The link should be placed in a pair of square brackets []</li>
<li>Add the link to your site in round brackets</li>
</ul>

```
[![alt text](uploaded-file-link)](link-to-site)
```

### <ul>For example</ul>

```
[![image](https://user-images.githubusercontent.com/66228179/153211323-6e521f21-b21c-4883-ab46-71b3755d03d7.png)](https://dev.to/babib)

```


[![image](https://user-images.githubusercontent.com/66228179/153211323-6e521f21-b21c-4883-ab46-71b3755d03d7.png)](https://dev.to/babib)

```
[![twitter](https://user-images.githubusercontent.com/66228179/153213725-4c03dc46-1e33-4928-abb3-0d1cccb06420.png)](https://twitter.com/BTweets47)
```


[![twitter](https://user-images.githubusercontent.com/66228179/153213725-4c03dc46-1e33-4928-abb3-0d1cccb06420.png)](https://twitter.com/BTweets47)

# <span id='contribute'>Contribute</span>

Contributions are always welcome! Please read the <a href='https://github.com/Babi-B/markdown-tips/blob/main/CONTRIBUTION.md'>contribution</a> guidelines first.



I have written a detailed <a href='https://dev.to/babib/tips-and-tricks-to-add-to-your-github-readmemd-191i'>blog</a> on how each tip mentioned here can be implemented.

&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;Babi 💞 
      



