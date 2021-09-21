<div align="center">

![logo](./public/logo.png)

# **Gitscores - Compete with Github**

![Version](https://img.shields.io/github/package-json/v/Natain/Gitscores?color=2948ff&label=Version&style=flat-square) ![License](https://img.shields.io/github/license/Natain/Gitscores?color=2948ff&label=License&style=flat-square) ![Deployment](https://img.shields.io/github/deployments/Natain/Gitscores/Gitscores?color=2948ff&label=Deployment&style=flat-square) ![Repo Size](https://img.shields.io/github/repo-size/Natain/Gitscores?color=2948ff&label=Repo%20Size&style=flat-square)

## Website : https://gitscores.herokuapp.com/

---

</div>

<br />

# Gitscores WebApp

> ### Website :https://gitscores.herokuapp.com/

## Features

- Check your Github Score. Based on -
  - Your Public Repos
  - Stars on Public Repos
  - Forks on Public Repos
  - Github Followers
  - Joined Github Organisations
- Compete with Friends and Other Github Users
- View Trending Repos of 5 Different Languages


# Gitscores Score in README

> ### Add Gitscores Score to GitHub Profile README
> ### Badges are Powered by [Shield.io](https://shields.io/)
> ### Check [utils/calc.js](./utils/calc.js) to Know How Gitscores Score is Calculated

You need to add this in README.md file in your profile repository via Markdown syntax:

```markdown
![](https://Gitscores.herokuapp.com/badge?username=your-github-username)
```

> **NOTE**: Don't forget to replace example `your-github-username` parameter with real value.

## Make it personal

### Color

You can use any valid HEX color or pick from a predefined set of named colors (`blue` is the default).

| color         | demo                                                                                           |
| ------------- | ---------------------------------------------------------------------------------------------- |
| `brightgreen` | ![](https://img.shields.io/static/v1?label=Profile+views&message=1234567890&color=brightgreen) |
| `green`       | ![](https://img.shields.io/static/v1?label=Profile+views&message=1234567890&color=green)       |
| `yellow`      | ![](https://img.shields.io/static/v1?label=Profile+views&message=1234567890&color=yellow)      |
| `orange`      | ![](https://img.shields.io/static/v1?label=Profile+views&message=1234567890&color=orange)      |
| `red`         | ![](https://img.shields.io/static/v1?label=Profile+views&message=1234567890&color=red)         |
| `blue`        | ![](https://img.shields.io/static/v1?label=Profile+views&message=1234567890&color=blue)        |
| `grey`        | ![](https://img.shields.io/static/v1?label=Profile+views&message=1234567890&color=grey)        |
| `lightgrey`   | ![](https://img.shields.io/static/v1?label=Profile+views&message=1234567890&color=lightgrey)   |
| `blueviolet`  | ![](https://img.shields.io/static/v1?label=Profile+views&message=1234567890&color=blueviolet)  |
| `ff69b4`      | ![](https://img.shields.io/static/v1?label=Profile+views&message=1234567890&color=ff69b4)      |

**Named color**

```markdown
![](https://Gitscores.herokuapp.com/badge?username=your-github-username&color=green)
```

**Hex color**

```markdown
![](https://Gitscores.herokuapp.com/badge?username=your-github-username&color=dc143c)
```

> **NOTE**: HEX colors should be used without `#` symbol prefix.

### Styles

The following styles are available (`flat` is the default).

| style           | demo                                                                                                          |
| --------------- | ------------------------------------------------------------------------------------------------------------- |
| `plastic`       | ![](https://img.shields.io/static/v1?label=Profile+views&message=1234567890&color=007ec6&style=plastic)       |
| `flat`          | ![](https://img.shields.io/static/v1?label=Profile+views&message=1234567890&color=007ec6&style=flat)          |
| `flat-square`   | ![](https://img.shields.io/static/v1?label=Profile+views&message=1234567890&color=007ec6&style=flat-square)   |
| `for-the-badge` | ![](https://img.shields.io/static/v1?label=Profile+views&message=1234567890&color=007ec6&style=for-the-badge) |

```markdown
![](https://Gitscores.herokuapp.com/badge?username=your-github-username&style=flat-square)
```

### Label

You can overwrite default `Gitscores Score` text with your own label.

![](https://img.shields.io/static/v1?label=Gitscores+PROFILE+SCORE&message=1234567890&color=007ec6)

```markdown
![](https://komarev.com/ghpvc/?username=your-github-username&label=PROFILE+VIEWS)
```

> **NOTE**: Replace whitespace with `+` character in multi-word labels.

---

## Local Setup

```sh
# install dependencies
npm install

# serve at localhost:3000
npm start

# serve with hot reload at localhost:3000
npm run dev
```

## Tech Stack

- Expressjs (Nodejs)
- Axios (HTTP client)
- EJS (Template Engine)
- Github API
- Heroku for deployment

## API Credits

#### Special Thanks to [Huchenme](https://github.com/huchenme) for the [Github Trending Api](https://github.com/huchenme/github-trending-api)

## Deployment

#### Deploy it on your own Heroku Dyno to avoid downtime.

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

## Contributing

Feel free to dive in! [Open an issue](https://github.com/Natain/Gitscores/issues/new) or submit PRs

## License

[MIT](LICENSE) © Natain Bogdan

---

<div align="center">

### Show some ❤️ by starring 🌟 the repository!

</div>
