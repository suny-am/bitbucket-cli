<a name="readme-top"></a>

<!-- PROJECT SHIELDS -->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/suny-am/bitbucket-cli">
    <img src=".docs/images/logo.png" alt="Logo" width="80" height="80">
  </a>

<h3 align="center">bitbucket-cli</h3>

  <p align="center">
    CLI For Bitbucket Cloud
    <br />
    <!-- <a href="https://github.com/suny-am/bitbucket-cli"><strong>Explore the docs »</strong></a> -->
    <!-- <br /> -->
    <br />
    <a href="https://github.com/suny-am/bitbucket-cli/issues/new?labels=bug&template=bug-report---.md">Report Bug</a>
    ·
    <a href="https://github.com/suny-am/bitbucket-cli/issues/new?labels=enhancement&template=feature-request---.md">Request Feature</a>
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
        <li><a href="#status">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <!-- <li><a href="#acknowledgments">Acknowledgments</a></li> -->
    <li><a href="#references">References</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->
## About The Project

<!-- [![Product Name Screen Shot][product-screenshot]](https://example.com) -->

A Bitbucket Cloud compatible CLI that let's you interact with your Bitbucket resources without leaving your terminal.

<p align="right"><a href="#readme-top">🔝</a></p>

### Built With

[![go][go]][go-url]

<p align="right"><a href="#readme-top">🔝</a></p>

### Status

[![FOSSA Status](https://app.fossa.com/api/projects/custom%2B45338%2Fgithub.com%2Fsuny-am%2Fbitbucket-cli.svg?type=shield&issueType=license)](https://app.fossa.com/projects/custom%2B45338%2Fgithub.com%2Fsuny-am%2Fbitbucket-cli?ref=badge_shield&issueType=license)

<p align="right"><a href="#readme-top">🔝</a></p>

<!-- GETTING STARTED -->
## Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

### Prerequisites

Testing and developing the application locally requires **go1.22.7** to be available (the latest release to be tested for now.

#### Go

  ```sh
  # MacOS example
  brew install go
  go version
  # example output: 
  # go version go1.22.7 linux/amd64  
  ```

### Installation

#### 1. Clone the repo

   ```sh
   git clone https://github.com/suny-am/bitbucket-cli.git
   ```

#### 2. TBD

##### 2.a Docker

   ```sh
   docker build . -t "bitbucket-cli"
   docker run bitbucket-cli
   docker-exec -it bitbucket-cli zsh
   ```

<p align="right"><a href="#readme-top">🔝</a></p>

<!-- USAGE EXAMPLES -->
## Usage

Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.

_For more examples, please refer to the [Documentation](https://example.com)_

<p align="right"><a href="#readme-top">🔝</a></p>

<!-- ROADMAP -->
## Feature Roadmap

- [ ] Core commands
  - [x] Root
  - [ ] Workspace
  - [ ] Repository
    - [ ] Branch restrictions
    - [ ] Branching model
    - [x] Commits
    - [ ] Deploy Keys
    - [ ] Downloads
    - [ ] Environments
    - [x] Repositories
    - [x] Pullrequests
    - [ ] Refs
    - [ ] Reports
    - [ ] Source
  - [ ] Project
    - [ ] Branch restrictions
    - [ ] Branching model
    - [ ] Deploy Keys
    - [ ] Issue tracker
    - [ ] Pipelines
    - [ ] Projects
  - [ ] User
    - [x] Pullrequests
  - [ ] Snippets
- [ ] Flags
- [ ] Help Topics
- [ ] Config
- [ ] Auth
- [ ] TBD

See the [open issues](https://github.com/suny-am/bitbucket-cli/issues) for a full list of proposed features (and known issues).

<p align="right"><a href="#readme-top">🔝</a></p>

<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

### 1. Fork the Project

```sh
gh repo fork suny-am/bitbucket-cli --clone
cd bitbucket-cli
```

### 2. Create your Feature Branch

```sh
git checkout -b feature/aNewCoolFeature
```

### 3. Commit your Changes

```sh
`git commit -m 'Add a new cool feature'
```

### 4. Push to the Branch

```sh
git push origin feature/aNewCoolFeature
```

### 5. Open a Pull Request

```sh
gh pr create 
```

<p align="right"><a href="#readme-top">🔝</a></p>

<!-- LICENSE -->
## License

Distributed under the MIT License. See [LICENCE.txt](LICENCE.txt) for more information.

<p align="right"><a href="#readme-top">🔝</a></p>

<!-- CONTACT -->
## Contact

Your Name - [@bsky_handle](https://bsky.app/profile/bsky_handle) - <visualarea.1@gmail.com>

Project Link: [https://github.com/suny-am/bitbucket-cli](https://github.com/suny-am/bitbucket-cli)

<p align="right"><a href="#readme-top">🔝</a></p>

## References

- [Atlassian Bitbucket Cloud REST API Documentation](https://developer.atlassian.com/cloud/bitbucket/rest/)

<p align="right"><a href="#readme-top">🔝</a></p>

<!-- ACKNOWLEDGMENTS -->

<!-- 
## Acknowledgments

<div style="padding:10px; border-radius: 5px;">

I would like to thank the following people for their contributions and support:

<div style="padding:10px; border-radius: 5px; margin: 10px 0;">

### [@contributor1](https://github.com/contributor1) - for providing helpful feedback and suggestions

</div>

<div style="padding:10px; border-radius: 5px; margin: 10px 0;">

### [@contributor2](https://github.com/contributor2) - for contributing code and bug fixes

</div>

<div style="padding:10px; border-radius: 5px; margin: 10px 0;">

### [@contributor3](https://github.com/contributor3) - for helping with documentation and testing

</div>

Thank you all for your time and effort in making this project better!

</div> 
-->
  
<br>
<p align="right"><a href="#readme-top">🔝</a></p>

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/suny-am/bitbucket-cli.svg?style=for-the-badge
[contributors-url]: https://github.com/suny-am/bitbucket-cli/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/suny-am/bitbucket-cli?style=for-the-badge
[forks-url]: https://github.com/suny-am/bitbucket-cli/network/members
[stars-shield]: https://img.shields.io/github/stars/suny-am/bitbucket-cli.svg?style=for-the-badge
[stars-url]: https://github.com/suny-am/bitbucket-cli/stargazers
[issues-shield]: https://img.shields.io/github/issues/suny-am/bitbucket-cli.svg?style=for-the-badge
[issues-url]: https://github.com/suny-am/bitbucket-cli/issues
[license-shield]: https://img.shields.io/github/license/suny-am/bitbucket-cli.svg?style=for-the-badge
[license-url]: https://github.com/suny-am/bitbucket-cli/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/carl-sandberg-01070a2b6/
[product-screenshot]: .docs/images/screenshot.png
[go]: https://img.shields.io/badge/go-%2300ADD8?style=for-the-badge&logo=go&logoColor=white&logoSize=auto
[go-url]: https://go.dev/
