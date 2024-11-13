<h1 align="center">Hi 👋, I'm Minn Thway Khant</h1>
<h3 align="center">A website developer from Myanmar</h3>

<p align="left"> <img src="https://komarev.com/ghpvc/?username=minnthwaykhant&label=Profile%20views&color=0e75b6&style=flat" alt="minnthwaykhant" /> </p>

- 👨‍💻 All of my projects are available at [www.linkedin.com/in/minn-thway-khant-5a24422b8](www.linkedin.com/in/minn-thway-khant-5a24422b8)

- 💬 Ask me about **Html, Css, PHP, Bootsrap**

- 📫 How to reach me **minthwaykhant04@gmail.com**

- 📄 Know about my experiences [www.linkedin.com/in/minn-thway-khant-5a24422b8](www.linkedin.com/in/minn-thway-khant-5a24422b8)

- ⚡ Fun fact **Call me Kenn**

<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://twitter.com/minnthwaykhant" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg" alt="minnthwaykhant" height="30" width="40" /></a>
<a href="https://linkedin.com/in/minn thway khant" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="minn thway khant" height="30" width="40" /></a>
<a href="https://fb.com/minn thway khant" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/facebook.svg" alt="minn thway khant" height="30" width="40" /></a>
<a href="https://instagram.com/minn thway khant" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="minn thway khant" height="30" width="40" /></a>
</p>

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://getbootstrap.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/bootstrap/bootstrap-plain-wordmark.svg" alt="bootstrap" width="40" height="40"/> </a> <a href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/> </a> <a href="https://www.w3.org/html/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/> </a> <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/> </a>  <a href="https://www.mysql.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/> </a>  <a href="https://www.php.net" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/php/php-original.svg" alt="php" width="40" height="40"/> </a> <a href="https://reactjs.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="react" width="40" height="40"/> </a> </p>


# Top Languages use

[![Static Badge](https://img.shields.io/badge/PHP-8e188e?style=for-the-badge&logo=php&logoColor=white&labelColor=black)](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=PHP&logoColor=%23777BB4&labelColor=black
)![Static Badge](https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=%23FF2D20&labelColor=black)
![Static Badge](https://img.shields.io/badge/Javascript-F7DF1E?style=for-the-badge&logo=Javascript&logoColor=%23F7DF1E&labelColor=black)

![Static Badge](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=React&logoColor=%2361DAFB&labelColor=black)
![Static Badge](https://img.shields.io/badge/HTML-E34F26?style=for-the-badge&logo=HTML5&logoColor=%23E34F26&labelColor=black)
![Static Badge](https://img.shields.io/badge/CSS-%231572B6?style=for-the-badge&logo=CSS3&logoColor=%231572B6&labelColor=black)
![Static Badge](https://img.shields.io/badge/MYSQL-4479A1?style=for-the-badge&logo=MySQL&logoColor=%234479A1&labelColor=black&color=%234479A1)

# Steps represent a sequence of tasks that will be executed as part of the job
steps:

# Checks repo under $GITHUB_WORKSHOP, so your job can access it
  - uses: actions/checkout@v2

# Generates the snake  
  - uses: Platane/snk@master
    id: snake-gif
    with:
      github_user_name: mishmanners
      # these next 2 lines generate the files on a branch called "output". This keeps the main branch from cluttering up.
      gif_out_path: dist/github-contribution-grid-snake.gif
      svg_out_path: dist/github-contribution-grid-snake.svg

 # show the status of the build. Makes it easier for debugging (if there's any issues).
  - run: git status

  # Push the changes
  - name: Push changes
    uses: ad-m/github-push-action@master
    with:
      github_token: ${{ secrets.GITHUB_TOKEN }}
      branch: master
      force: true

  - uses: crazy-max/ghaction-github-pages@v2.1.3
    with:
      # the output branch we mentioned above
      target_branch: output
      build_dir: dist
    env:
      GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

