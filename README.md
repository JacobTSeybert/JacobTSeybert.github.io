<a href="https://jekyll-themes.com">
<img src="https://img.shields.io/badge/featured%20on-JT-red.svg" height="20" alt="Jekyll Themes Shield" >
</a>

# Orbit
> This repo is created and used by Jacob Seybert with the theme created by Xiaoying Riley. 
> Visit me at my [website](https://JTSeybert.com/) here.

I have made this into a Jekyll Theme. Checkout the live demo [here](https://online-cv.webjeda.com).

<table>
  <tr>
    <th>Desktop</th>
    <th>Mobile</th>
  </tr>
  <tr>
    <td>
        <img src="https://online-cv.webjeda.com/assets/images/desktop.png?raw=true" width="600"/>
    </td>
    <td>
        <img src="https://online-cv.webjeda.com/assets/images/mobile.png?raw=true" width="250"/>
    </td>
  </tr>
</table>

## Installation

* [Fork](https://github.com/sharu725/online-cv/fork) the repository
* Go to settings and set master branch as Github Pages source.
* Your new site should be ready at `https://<username>.github.io/online-cv/`
* Printable version of the site can be found at `https://<username>.github.io/online-cv/print`. Use a third party link https://pdflayer.com/, https://www.web2pdfconvert.com/ etc to get the printable PDF.


## To preview/edit locally with docker

```sh
docker-compose up
```

*docker-compose.yml* file is used to create a container that is reachable under http://localhost:4000.
Changes *_data/data.yml* will be visible after a while.

### Local machine

* Get the repo into your machine 
```bash
git clone https://github.com/JacobTSeybert/JacobTSeybert.github.io
```
* Install required ruby gems
```bash
bundle install
```
* Serve the site locally
```bash
bundle exec jekyll serve
```
* Navigate to `http://localhost:4000`


## Skins

There are 6 color schemes available:

| Blue | Turquoise | Green |
|---------|---------|---------|
| <img src="https://online-cv.webjeda.com/assets/images/blue.jpg" width="300"/> | <img src="https://online-cv.webjeda.com/assets/images/turquoise.jpg" width="300"/> | <img src="https://online-cv.webjeda.com/assets/images/green.jpg" width="300"/> |

| Berry | Orange | Ceramic |
|---------|---------|---------|
| <img src="https://online-cv.webjeda.com/assets/images/berry.jpg" width="300"/> | <img src="https://online-cv.webjeda.com/assets/images/orange.jpg" width="300"/> | <img src="https://online-cv.webjeda.com/assets/images/ceramic.jpg" width="300"/> |

##test with caddy 07/06/2023

