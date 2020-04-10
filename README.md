<p align="center">
<img src="http://cimarron.io/assets/images/logo.png" width="500" alt="Cimarrón IO"><br>
<a href="https://www.cimarron.io]/" target="_blank"><img src="https://img.shields.io/badge/website-Cimarr%C3%B3n%20IO-cd0d7a.svg"></a>
<a href="http://tacosdedatos.slack.com/" target="_blank"><img src="https://img.shields.io/badge/slack-tacosdedatos-19267c.svg"></a>
</p>


# Announcements

**tl;dr:** Imaginemos cosas chingonas.


## Table of Contents

- [About the project](#about-the-project)
- [Contribute](#contribute)
- [Attributions](#Attributions)


## About the project

Cimarrón is a group of creative and skilled individuals looking to solve every day problems in the most efficient and creative way using technology.

We believe technology has the potential to empower anyone regardless of one’s status. We focus our efforts in creating high-quality open-sourced data and technology products.

[Website](https://cimarron.io/).

If you would like to contribute, keep reading.

## Contribute

All contributions are welcome!

If you need help, create an issue on the repo [cimarron-io/cimarron-io.github.io/](https://github.com/cimarron-io/cimarron-io.github.io/issues) or join us on the tacosdedatos slack at [tacosdedatos.slack.com](https://tacosdedatos.slack.com)

### Add a project

1. Fork the repository to your GitHub account.

2. Clone the fork of your repo:
   ```bash
   git clone https://github.com/<YOUR-USERNAME>/cimarron-io/cimarron.io-github.io.git
   cd cimarron-io.github.io/
   ```

3. Create a branch with the name of the project you wish to add:
   ```bash
   git checkout -b project-name  # this creates a brand new branch and switches to it
   ```

4. Create the file with the project information. This file must be saved on the folder [`_posts`](https://github.com/cimarron-io/cimarron-io.github.io/tree/master/_posts) with the name format `YYYY-MM-DD-project-name.md`, where `YYYY`, `MM`, and `DD` are the Year, Month and Day you're adding the project to the folder. You can use the template file [template.md](https://github.com/cimarron-io/cimarron-io.github.io/blob/master/_posts/2020-01-22-template.md).

5. Create a Pull Request (PR) from your branch to the `master` branch of the orginal repo and add **@chekos** as a reviewer.

**NOTE:** Please use one PR per project.



### Modifying the site

Please open an issue where you mention the changes you would like to make and mention **@chekos**. You will be assigned the issue and we will await your PR where we ask that you add **@chekos** as a reviewer.

If you wish to run the site locally, execute the following commands:

1. Install requirements:
   ```bash
   bundle install
   ```

2. Run the server:
   ```bash
   bundle exec jekyll serve
   ```

3. Open <http://localhost:4000/cimarron-io.github.io> in your browser.

The command in step 2 allows you to make changes and visualize them in real time on your browser.


## Attributions

- This website is based on Codeando México's Awesome Civic Tech site found at https://codeandomexico.github.io/awesome-civic-tech/

Below are their attributions from the original repo:

- Sitio web basado en [Pintereso Jekyll Theme](https://www.wowthemes.net/pintereso-free-bootstrap-jekyll-theme/)
- Gracias a [Richard](https://github.com/ricardomiron) y [Rodo](https://github.com/RodolfoFerro) por las contribuciones iniciales
- `{}` y contenidos con ❤️ por la [comunidad de Codeando México](http://slack.codeandomexico.org/)

---
