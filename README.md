# Hardhat Smart Contract Upgrades

<div id="top"></div>


[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]


<!-- ABOUT THE PROJECT -->
## About The Project

All the code was developed for learning purposes and is from [Learn Blockchain, Solidity, and Full Stack Web3 Development with JavaScript – 32-Hour Course](https://www.youtube.com/watch?v=gyMwXuJrbJQ&lis) by freeCodeCamp.org and Patrick Collins

The project represents an upgradable Smart Contract through a Proxy.

It implements the Openzeppelin Transparent Proxy Smart Contract as a Proxy.

Thanks to this proxy we can change the implementation (logic) of the smart contract.

This project demonstrates an advanced Hardhat use case, integrating other tools commonly used alongside Hardhat in the ecosystem.

<p align="right">(<a href="#top">back to top</a>)</p>



### Etherscan verification

This project also includes automatic verification of the contract for real networks. The verification is only executed when running on real networks

<p align="right">(<a href="#top">back to top</a>)</p>



### Built With

* [Node.js](https://nodejs.org/)
* [Solidity](https://docs.soliditylang.org/)
* [Hardhat](https://hardhat.org/)
* [Chainlink VRF & Price Feed](https://docs.chain.link/ethereum/)


<p align="right">(<a href="#top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

Make sure you have already installed Node.js in your device. Also make sure you have yarn installed, in case you don't, install it:

* yarn
  ```sh
  npm install --global yarn
  ```

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/alvaro-8a/hardhat-upgrades-fcc.git
   ```
2. Install YARN packages
   ```sh
   yarn install
   ```

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

You can use this code it as a template to develop your own upgradable smart contract, there are many improvements that can be done so feel free to make any change.

You can also use it to deploy your own upgradable smart contract to a Solidity supported Blockchain (Ethereum, Polygon, BSC...).

**Note: This project is a demo and I don't recommend using it without changes, there are many things that can be improved so take in consideration before using it.**


<p align="right">(<a href="#top">back to top</a>)</p>



<!-- ROADMAP -->
## Roadmap

1. Upgrade Box -> BoxV2
2. Proxy    Box
         -> BoxV2

3. Deploy a Proxy
   1. Manually --Subleson--
   2. hardhat-deploy's built-in proxies <-
   3. Openzeppelin upgrades plugin

- [✔️] Develop different contract implementations (Box & BoxV)
- [✔️] Develop ProxyAdmin contract (Admin of the proxy)
- [✔️] Deploy scripts
- [✔️] Upgrade script

See the [open issues](https://github.com/alvaro-8a/hardhat-upgrades-fcc/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion or an improvement that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Your Name - [@alvaro_8a_](https://twitter.com/alvaro_8a_) - alvaroblanco8a@gmail.com

Project Link: [https://github.com/alvaro-8a/hardhat-upgrades-fcc](https://github.com/alvaro-8a/hardhat-upgrades-fcc)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* [Learn Blockchain, Solidity, and Full Stack Web3 Development with JavaScript – 32-Hour Course](https://www.youtube.com/watch?v=gyMwXuJrbJQ&lis)
* [Patrick Collins](https://www.youtube.com/c/PatrickCollins)
* [FreeCodeCamp.org](https://www.youtube.com/c/Freecodecamp)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/alvaro-8a/hardhat-upgrades-fcc.svg?style=for-the-badge
[contributors-url]: https://github.com/alvaro-8a/hardhat-upgrades-fcc/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/alvaro-8a/hardhat-upgrades-fcc.svg?style=for-the-badge
[forks-url]: https://github.com/alvaro-8a/hardhat-upgrades-fcc/network/members
[stars-shield]: https://img.shields.io/github/stars/alvaro-8a/hardhat-upgrades-fcc.svg?style=for-the-badge
[stars-url]: https://github.com/alvaro-8a/hardhat-upgrades-fcc/stargazers
[issues-shield]: https://img.shields.io/github/issues/alvaro-8a/hardhat-upgrades-fcc.svg?style=for-the-badge
[issues-url]: https://github.com/alvaro-8a/hardhat-upgrades-fcc/issues
[license-shield]: https://img.shields.io/github/license/alvaro-8a/hardhat-upgrades-fcc.svg?style=for-the-badge
[license-url]: https://github.com/alvaro-8a/hardhat-upgrades-fcc/blob/main/LICENSE
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/alvaro-blanco-ochoa-9b14561a9
[product-screenshot]: images/screenshot.png
