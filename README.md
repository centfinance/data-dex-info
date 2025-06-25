# DataDex Info: VANA Dashboard

An open-source analytics interface for **VANA** token markets, forked and adapted from Uniswap V3 Info.

📊 Live dashboard: [info.datadex.com/#/vana](https://info.datadex.com/#/vana)

---
🔧 Development

1. Clone the Repo
   ```bash
   git clone https://github.com/vanadatadex/data-dex-info.git
   cd data-dex-info
  

3. Install Dependencies
   ```bash
   yarn

3. Run the App
   ```bash
   yarn start
  (The app should now be running at http://localhost:3000)

---
📁 Structure

This project is based on Uniswap V3’s analytics frontend but customized to support VANA pair data via our CMS and subgraph.

src/pages/vana/ – Custom VANA dashboard components

src/lib/sanity/ – CMS integration for DataDex

src/lib/subgraph/ – GraphQL queries for on-chain analytics

---
🤝 Contributions

Please open all pull requests against the main branch.

CI checks will automatically run for all PRs. Ensure your changes pass before requesting a review.

---

🛡 License

This project is licensed under GPL-3.0.

🙌 Acknowledgements

This interface is based on the amazing work of Uniswap Labs. We thank them for making the original version open source.

---

🌐 Learn More

Main Site: https://datadex.com

Analytics Dashboard: https://info.datadex.com/#/vana

Tokenlist Repo: https://github.com/vanadatadex/tokenlist

DataDex is building a unified interface to explore data-backed tokens across decentralized networks. The VANA dashboard is one of the first modules powered by both on-chain and off-chain data.

For questions, reach out via https://datadex.com or open an issue.

   
