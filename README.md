# 📱 Android Apps Scraper/Downloader
<a href="https://github.com/harismuneer"><img alt="views" title="Github views" src="https://komarev.com/ghpvc/?username=harismuneer&style=flat-square" width="125"/></a>
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.2537131.svg)](https://doi.org/10.5281/zenodo.2537131)

[![Open Source Love svg1](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](#)
[![GitHub Forks](https://img.shields.io/github/forks/harismuneer/Android-Apps-Downloader.svg?style=social&label=Fork&maxAge=2592000)](https://www.github.com/harismuneer/Android-Apps-Downloader/fork)
[![GitHub Issues](https://img.shields.io/github/issues/harismuneer/Android-Apps-Downloader.svg?style=flat&label=Issues&maxAge=2592000)](https://www.github.com/harismuneer/Android-Apps-Downloader/issues)
[![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat&label=Contributions&colorA=red&colorB=black	)](#)



We did a research project on comparison of Official Play Store Apps and their 3rd Party App Stores counterparts to analyze what modifications are done to the 3rd Party versions of an app. For this purpose, we wrote this script to download pairs of an app from Google Play Store and Xiaomi App Store (a famous 3rd Party Chinese App Store). It downloads an app from Xiaomi and Google Play store only when that app is available on both stores. This way it creates a dataset of pairs of an app.

We are open-sourcing this tool so that it can be utilized by the research community for research in Android Security. 

Moroever, to compare two Android Apps we wrote another tool named [AndroCompare](https://github.com/harismuneer/AndroCompare). We have open-sourced it as well.

For details regarding **citing/referencing** this tool for your research, check the 'Citation' section below.


## Approach
The download URL of an app on Xiaomi App Store is like http://app.mi.com/download/23 
The number at the end of the URL can be incremented to download as many apps as you want. So, theoretically you can download each and every app on the Xiaomi App Store. Hence there's a variable named 'target' in the tool. If target = 1000 then the tool will scan first 1000 urls for the apps. You can change the target to any number you want.


## Features
* download all apps from the famous Xiaomi App Store
* download pairs of an app from Play Store and Xiaomi App Store
* the record of all downloaded apps is maintained in a SQLite database
* if the code is interrupted using CTRL + Z then the current progress is saved so that next time the code resumes downloading from where it left previously
* incase the script is running and there occurs some internet connectivity issue then all current progress is saved and the script waits until the internet is connected again and resumes from where it left

## How to Run Code
The code is in ready to run condition. It can be run on both Windows/Ubuntu Linux. 
Its written in Python 3. Moreover it uses [gplaycli](https://github.com/matlink/gplaycli), so install it using pip.

You can use [DB Browser for SQLite](http://sqlitebrowser.org/) to view the database.

----------------------------------------------------------------------------------------------------------------------------------------
## Note
This script can be easily modified to meet your specific needs e.g currently it first checks whether an app is present on both stores and if yes then it downloads it from each store. You can remove this constraint to download every possible app from Xiaomi App Store.

This code is for research purposes only.

----------------------------------------------------------------------------------------------------------------------------------------

## Citation

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.2537131.svg)](https://doi.org/10.5281/zenodo.2537131)

If you use this tool for your research, then kindly cite it. Click the above badge for more information regarding the complete citation for this tool and diffferent citation formats like IEEE, APA etc.

---------------------------------------------------------------------------------------------------------------------------------------

<hr>

## Authors
You can get in touch with us on our LinkedIn profiles:

#### Haris Muneer

[![LinkedIn Link](https://img.shields.io/badge/Connect-harismuneer-blue.svg?logo=linkedin&longCache=true&style=social&label=Follow
)](https://www.linkedin.com/in/harismuneer) 

To stay updated about my latest projects: [![GitHub Follow](https://img.shields.io/badge/Connect-harismuneer-blue.svg?logo=Github&longCache=true&style=social&label=Follow)](https://github.com/harismuneer)

#### Hussam Habib

[![LinkedIn Link](https://img.shields.io/badge/Connect-hussam--habib-blue.svg?logo=linkedin&longCache=true&style=social&label=Connect)](https://www.linkedin.com/in/hussam-habib-0bb098104/)

To stay updated about my latest projects: [![GitHub Follow](https://img.shields.io/badge/Connect-hussam--habib-blue.svg?logo=Github&longCache=true&style=social&label=Follow)](https://github.com/hussamh10)


---
If you liked the repo then kindly support it by giving it a star ⭐ and share in your circles so more people can benefit from the effort.

## Contributions Welcome
[![GitHub Issues](https://img.shields.io/github/issues/harismuneer/Android-Apps-Downloader.svg?style=flat&label=Issues&maxAge=2592000)](https://www.github.com/harismuneer/Android-Apps-Downloader/issues)

If you find any bugs, have suggestions, or face issues:

- Open an Issue in the Issues Tab to discuss them.
- Submit a Pull Request to propose fixes or improvements.
- Review Pull Requests from other contributors to help maintain the project's quality and progress.

This project thrives on community collaboration! Members are encouraged to take the initiative, support one another, and actively engage in all aspects of the project. Whether it’s debugging, fixing issues, or brainstorming new ideas, your contributions are what keep this project moving forward.

With modern AI tools like ChatGPT, solving challenges and contributing effectively is easier than ever. Let’s work together to make this project the best it can be! 🚀

## License
[![MIT](https://img.shields.io/cocoapods/l/AFNetworking.svg?style=style&label=License&maxAge=2592000)](../master/LICENSE)

Copyright (c) 2018-present, harismuneer, hussamh10                                                        

<!-- PROFILE_INTRO_START -->

<hr>

<h1> <a href="#"><img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" alt="Waving hand" width="28"></a>
Hey there, I'm <a href="https://www.linkedin.com/in/harismuneer/">Haris Muneer</a> 👨🏻‍💻
</h1>


<a href="https://github.com/harismuneer"><img src="https://img.shields.io/github/stars/harismuneer" alt="Total Github Stars"></a>
<a href="https://github.com/harismuneer?tab=followers"><img src="https://img.shields.io/github/followers/harismuneer" alt="Total Github Followers"></a>

<hr>

- <b>🛠️ Product Builder:</b> Agile Product Manager with 5+ years of hands-on experience delivering SaaS solutions across sales, recruiting, AI, social media, and public sector domains. Background in Computer Science, with a proven track record of scaling products from inception to $XXM+ ARR, launching 3 top-ranking tools on Product Hunt, and developing solutions adopted by 250+ B2B clients in 40+ countries.  
 
- <b>🌟 Open Source Advocate:</b> Passionate about making technology accessible, I’ve developed and open-sourced several software projects for web, mobile, desktop, and AI on my <a href="https://github.com/harismuneer">GitHub profile</a>. These projects have been used by thousands of learners worldwide to enhance their skills and knowledge.

- <b>📫 How to Reach Me:</b> To learn more about my skills and work, visit my <a href="https://www.linkedin.com/in/harismuneer">LinkedIn profile</a>. For collaboration or inquiries, feel free to reach out via <a href="mailto:haris.muneer5@gmail.com">email</a>. For Cyfy Labs related queries, please contact us through our <a href="https://www.cyfylabs.com">company website</a>.

<hr>

<h2 align="left">🤝 Follow my journey</h2>
<p align="left">
  <a href="https://www.linkedin.com/in/harismuneer"><img title="Follow Haris Muneer on LinkedIn" src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="https://github.com/harismuneer"><img title="Follow Haris Muneer on GitHub" src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"/></a>
  <a href="https://www.youtube.com/@haris_muneer?sub_confirmation=1"><img title="Subscribe on YouTube" src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white"/></a> 
  <a href="mailto:haris.muneer5@gmail.com"><img title="Email" src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
</p>



<!-- PROFILE_INTRO_END -->




