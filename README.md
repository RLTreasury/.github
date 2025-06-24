# XRPL SingleAssetVault Explorer

[![Hackathon Winner](https://img.shields.io/badge/Ripple%20x%20EasyA%20Hackathon-1st%20Place%20Exploration%20Track-gold)](https://github.com/your-repo)
[![XLS-65d](https://img.shields.io/badge/XLS--65d-SingleAssetVault-blue)](https://github.com/XRPLF/XRPL-Standards/discussions/192)
[![Docker](https://img.shields.io/badge/Docker-Containerized-blue)](https://www.docker.com/)

**Winner of 1st Place in the Exploration Track at Ripple x EasyA Hackathon Singapore 2025**

An experimental implementation exploring the **SingleAssetVault amendment (XLS-65d)** on XRPL, focusing on on-chain yield generation and real-world asset (RWA) integration possibilities.

## 🎯 Project Overview

This project demonstrates the practical implementation and testing of XRPL's emerging **SingleAssetVault amendment (XLS-65d)** in a controlled environment. We successfully deployed a Dockerized `rippled` instance in standalone mode to enable this cutting-edge feature, exploring its potential for unlocking on-chain yield mechanisms and RWA protocols on the XRPL network.

## 🏗️ Technical Stack

- **XRPL**: Custom rippled build with experimental amendments
- **JavaScript**: Full-stack JavaScript implementation
- **Docker**: Containerized rippled deployment
- **XLS-65d**: SingleAssetVault amendment (under development) 
- **XLS-30d**: MPToken amendment support
- **Node.js**: Runtime environment and tooling

## 💡 Motivation

As **XRPL Commons interns**, we were initially tasked with testing the **MPToken amendment (XLS-30d)** two weeks prior to the hackathon. During this exploration, we discovered the **SingleAssetVault amendment (XLS-65d)**, which immediately caught our attention due to its promising potential for enabling **on-chain yield generation**.

Key motivations included:

- **Strategic Early Adoption**: Position ourselves as early contributors to emerging XRPL protocols
- **Real-World Testing**: Validate XLS-65d functionality in practical scenarios
- **RWA Exploration**: Investigate potential applications for U.S. Treasury-backed real-world assets
- **Protocol Understanding**: Gain deep insights into next-generation XRPL features

## 🏛️ Architecture

```
┌─────────────────┐    ┌──────────────────┐    ┌─────────────────┐
│   Client App    │───▶│  rippled Node    │───▶│  SingleAsset    │
│   (Frontend)    │    │  (Standalone)    │    │     Vault       │
└─────────────────┘    └──────────────────┘    └─────────────────┘
                                │
                                ▼
                       ┌──────────────────┐
                       │   MPToken        │
                       │   Support        │
                       └──────────────────┘
```

### Core Components

1. **Dockerized rippled**: Custom build enabling XLS-65d and XLS-30d (MPToken) amendments
2. **JavaScript Implementation**: Full client-side logic built in vanilla JavaScript
3. **SingleAssetVault Integration**: Core vault functionality and yield mechanisms
4. **Testing Framework**: Comprehensive JavaScript-based test suite
5. **Web Interface**: Browser-based interface for vault interactions


## 📋 Development Notes

### Key Discoveries

- **Amendment Activation**: Successfully enabled XLS-65d in standalone mode alongside XLS-30d (MPToken) support
- **JavaScript Integration**: Built comprehensive JavaScript tooling for interacting with SingleAssetVault transactions
- **Vault Mechanics**: Explored yield distribution mechanisms and asset management patterns through JS implementations
- **Protocol Interaction**: Developed JavaScript libraries for seamless vault operations

### Technical Insights

- XLS-65d shows significant promise for on-chain yield but requires additional infrastructure
- Integration with the upcoming **Lending/Borrowing protocol (XLS-66)** will be crucial
- Current implementation needs enhancement for U.S. Treasury-backed RWA scenarios

## 🚀 Future Improvements

### Short-term Goals

- [ ] Enhanced vault testing suite
- [ ] Integration with XLS-66 (Lending/Borrowing protocol)
- [ ] Improved client interface and UX
- [ ] Comprehensive documentation and tutorials

### Long-term Vision

- [ ] Production-ready RWA integration
- [ ] Advanced yield strategies implementation
- [ ] Cross-protocol interoperability
- [ ] Regulatory compliance framework

## 🔗 Relevant Links

- **XLS-65d Specification**: [SingleAssetVault Discussion](https://github.com/XRPLF/XRPL-Standards/discussions/192)
- **XLS-30d MPToken**: [MPToken Amendment Discussion](https://github.com/XRPLF/XRPL-Standards/discussions/190)
- **Rippled Implementation**: [SingleAssetVault PR]([https://github.com/XRPLF/rippled/pull/5444))
- **XLS-66 Lending Protocol**: [XRPL Standards Repository](https://github.com/XRPLF/XRPL-Standards)
- **XRPL Dev Portal**: [Official Documentation](https://xrpl.org/)
- **Hackathon Details**: [Ripple x EasyA Singapore](https://www.easya.io/)

## 🙏 Acknowledgments

We extend our sincere gratitude to the following individuals and organizations who made this project possible:

- **Broneck** - For invaluable technical guidance and Docker setup assistance
- **David Schwartz** - For insightful discussions at Apex and strategic direction
- **Vito** - XLS-65d author, for sharing deep technical insights and amendment vision  
- **XRPL Commons** - For providing the opportunity and initial testing mandate
- **Ripple & EasyA** - For hosting an incredible hackathon experience in Singapore
- **The XRPL Community** - For continuous support and collaboration

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

### Getting Involved

- Join discussions in the [XRPL Community](https://xrplcommunity.blog/)
- Follow development updates on Twitter: [Iv0ken](https://twitter.com/iv0ken) & [evamrza](https://twitter.com/evamrza) & [RomThpt](https://twitter.com/romthpt)

---

**Built with ❤️ for the XRPL ecosystem**
