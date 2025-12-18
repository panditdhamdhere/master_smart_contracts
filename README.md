# Master Smart Contracts

The best smart contracts resources in one place.

This repo is meant to be a **single `README` you can live in** while you:
- **Read real production contracts**
- **Jump into docs / audits / talks** for each protocol
- **Discover libraries, security guides, and learning material**

PRs are very welcome – add anything you’ve personally found useful.

---

## Recommended learning paths

- **1. Smart contract developer path**
  - Start: [Solidity by Example](https://solidity-by-example.org/) → [CryptoZombies](https://cryptozombies.io/).
  - Then: [Solidity Docs](https://docs.soliditylang.org/en/latest/) + [Ethereum Developer Docs](https://ethereum.org/en/developers/docs/).
  - Build: [Speed Run Ethereum](https://speedrunethereum.com/) + [Scaffold-ETH](https://github.com/scaffold-eth/scaffold-eth-2).
  - Deepen: [EVM Handbook](https://noxx3xxon.notion.site/noxx3xxon/EVM-Handbook-bb38e175cc404111a391907c4975426d) + read real protocol repos from the table above.

- **2. Smart contract security / auditing path**
  - Start: [Cyfrin Updraft](https://updraft.cyfrin.io/) + [Secureum](https://secureum.xyz/).
  - Practice: [Damn Vulnerable DeFi](https://www.damnvulnerabledefi.xyz/) + [Ethernaut](https://ethernaut.openzeppelin.com/).
  - Read: [SWC Registry](https://swcregistry.io/) + [Rekt Leaderboard](https://rekt.news/leaderboard/).
  - Deepen: Pick an audit firm (Trail of Bits, OpenZeppelin, Consensys) and read full audit reports for 2–3 protocols from this README.

- **3. DeFi protocol designer path**
  - Theory: [Paradigm research posts](https://www.paradigm.xyz) + [DeFi Developer Roadmap](https://github.com/OffcierCia/DeFi-Developer-Road-Map).
  - Case studies: Uniswap v2/v3 whitepapers + Aave, MakerDAO, Curve docs and repos.
  - Practice: Model simple AMMs, lending, and stablecoin systems, then compare to real-world implementations linked above.

- **4. Zero-knowledge & ZK engineer path**
  - Start: [ZK Learning Path](https://learn.0xparc.org/) + [ZK Whiteboard Sessions](https://www.youtube.com/playlist?list=PLj80z0cJm8QFnY6VLVa84nr-21DNvjWH7).
  - Practice: [ZK Hack](https://www.zkhack.dev/) + basic [Circom](https://docs.circom.io/) circuits with [SnarkJS](https://github.com/iden3/snarkjs).
  - Deepen: Explore one zkEVM (zkSync, Polygon zkEVM, Scroll) and read their docs + contracts.

- **5. Full-stack Web3 / infra path**
  - Start: [Buildspace](https://buildspace.so/) or [LearnWeb3](https://learnweb3.io/).
  - Stack: pick `Foundry + Hardhat + Ethers.js + Wagmi + Next.js` and ship a small dApp using protocols listed above.
  - Infra: use [Alchemy](https://www.alchemy.com/), [Infura](https://www.infura.io/), or [QuickNode](https://www.quicknode.com/) + [The Graph](https://thegraph.com/).

---

## Battle‑tested protocol contracts

| Protocol         | Type             | Repository                                            | Documentation                                                   | The Bytecode Episode                                                            |
| ---------------- | ---------------- | ----------------------------------------------------- | --------------------------------------------------------------- | ------------------------------------------------------------------------------- |
| **Aave**         | Lending          | https://github.com/aave/protocol-v2                   | [Docs](https://docs.aave.com/)                                  | N/A                                                                             |
| **Ajna**         | Lending          | https://github.com/ajna-finance/ajna-core             | [Docs](https://docs.ajna.finance/)                              | N/A                                                                             |
| **Art Gobblers** | NFT              | https://github.com/artgobblers/art-gobblers           | [Docs](https://www.paradigm.xyz/2022/09/art-gobblers)           | N/A                                                                             |
| **Balancer V2**  | DEX              | https://github.com/balancer/balancer-v2-monorepo      | [Docs](https://docs.balancer.fi/)                               | N/A                                                                             |
| **Balancer V3**  | DEX              | https://github.com/balancer/balancer-v3-monorepo      | [Docs](https://docs-v3.balancer.fi/)                            | N/A                                                                             |
| **Compound**     | Lending          | https://github.com/compound-finance/compound-protocol | [Docs](https://compound.finance/docs)                           | N/A                                                                             |
| **Conditional Tokens**     | Token          | https://github.com/gnosis/conditional-tokens-contracts | [Docs](https://conditional-tokens.readthedocs.io/en/latest/index.html)                           | N/A                                                                             |
| **Curve**        | DEX              | https://github.com/curvefi/curve-contract             | [Docs](https://docs.curve.fi/)                                  | N/A                                                                             |
| **EigenLayer**   | Restaking        | https://github.com/Layr-Labs/eigenlayer-contracts     | [Docs](https://docs.eigenlayer.xyz)                             | N/A                                                                             |
| **MakerDAO**     | Stablecoin       | https://github.com/makerdao/dss                       | [Docs](https://docs.makerdao.com/)                              | N/A                                                                             |
| **Maple**        | Lending          | https://github.com/maple-labs/maple-core-v2           | [Docs](https://docs.maple.finance/)                             | [Youtube](https://www.youtube.com/watch?v=nG_QTMGVL3U&t=2358s&ab_channel=shafu) |
| **Merit**        | Escrow           | https://github.com/Merit-Systems/contracts            | [Docs](https://www.merit.systems/docs)                          | [Youtube](https://www.youtube.com/watch?v=-Lqn4mx8eRY&ab_channel=shafu)         |
| **Sablier V2**   | Streaming        | https://github.com/sablier-labs/v2-core               | [Docs](https://docs.sablier.com)                                | [Youtube](https://www.youtube.com/watch?v=Mh0akz5ybZ8&t=11s&ab_channel=shafu)   |
| **Seaport**      | NFT Marketplace  | https://github.com/ProjectOpenSea/seaport             | [Docs](https://docs.opensea.io/v2.0/reference/seaport-overview) | [Youtube](https://www.youtube.com/watch?v=mvRrRV_eNLQ&ab_channel=shafu)         |
| **🐍 snekmate**  | Library          | https://github.com/pcaversaccio/snekmate              | [Docs](https://github.com/pcaversaccio/snekmate#readme)         | N/A                                                                             |
| **Solady**       | Library          | https://github.com/Vectorized/solady                  | [Docs](https://github.com/Vectorized/solady#readme)             | N/A                                                                             |
| **Solmate**      | Library          | https://github.com/transmissions11/solmate            | [Docs](https://github.com/transmissions11/solmate#readme)       | N/A                                                                             |
| **Synthetix**    | Derivatives      | https://github.com/Synthetixio/synthetix              | [Docs](https://docs.synthetix.io/)                              | N/A                                                                             |
| **Uniswap V2**   | DEX              | https://github.com/Uniswap/uniswap-v2-core            | [Docs](https://docs.uniswap.org/)                               | N/A                                                                             |
| **Uniswap V3**   | DEX              | https://github.com/Uniswap/v3-core                    | [Docs](https://docs.uniswap.org/protocol/V3/introduction)       | N/A                                                                             |
| **Uniswap V4**   | DEX              | https://github.com/Uniswap/v4-core                    | [Docs](https://docs.uniswap.org/contracts/v4/overview)          | N/A                                                                             |
| **Yearn V3**     | Yield Farming    | https://github.com/yearn/yearn-vaults-v3              | [Docs](https://docs.yearn.fi/developers/v3/overview)            | N/A                                                                             |
| **Morpho Blue**  | Lending          | https://github.com/morpho-org/morpho-blue             | [Docs](https://docs.morpho.org/)                                | N/A                                                                             |
| **Lido**         | Liquid Staking   | https://github.com/lidofinance/lido-dao               | [Docs](https://docs.lido.fi/)                                   | N/A                                                                             |
| **Rocket Pool**  | Liquid Staking   | https://github.com/rocket-pool/rocketpool             | [Docs](https://docs.rocketpool.net/)                            | N/A                                                                             |
| **Pendle V2**    | Yield Trading    | https://github.com/pendle-finance/pendle-core-v2-public | [Docs](https://docs.pendle.finance/)                          | N/A                                                                             |
| **GMX**          | Perps / DEX      | https://github.com/gmx-io/gmx-contracts               | [Docs](https://gmxio.gitbook.io/gmx/)                           | N/A                                                                             |
| **Lyra**         | Options AMM      | https://github.com/lyra-finance/lyra-protocol         | [Docs](https://docs.lyra.finance/)                              | N/A                                                                             |
| **Notional**     | Fixed-Rate Lending | https://github.com/notional-finance/contracts-v2    | [Docs](https://docs.notional.finance/)                          | N/A                                                                             |
| **Gearbox**      | Leveraged DeFi   | https://github.com/Gearbox-protocol/core-v2           | [Docs](https://docs.gearbox.fi/)                                | N/A                                                                             |
| **Frax**         | Stablecoin / LSD | https://github.com/FraxFinance/frax-solidity          | [Docs](https://docs.frax.finance/)                              | N/A                                                                             |

---

## Learn smart contracts (code, courses, and books)

- **Solid fundamentals**
  - [Solidity by Example](https://solidity-by-example.org/) – short, focused examples.
  - [CryptoZombies](https://cryptozombies.io/) – gamified intro to Solidity.
  - [Solidity Docs](https://docs.soliditylang.org/en/latest/) – the actual language spec.
  - [Ethereum Developer Docs](https://ethereum.org/en/developers/docs/) – broader EVM background.
  - [Learn Solidity](https://www.learnsolidity.io/) – interactive Solidity course.
  - [Ethereum.org Learn](https://ethereum.org/en/developers/learning-tools/) – curated learning paths.
  - [Speed Run Ethereum](https://speedrunethereum.com/) – build DeFi dApps step-by-step.

- **DeFi / advanced patterns**
  - [Paradigm research posts](https://www.paradigm.xyz) – design‑level thinking about DeFi protocols.
  - [Uniswap v3 whitepaper](https://uniswap.org/whitepaper-v3.pdf) – concentrated liquidity design.
  - [OpenZeppelin Contracts Wizard](https://wizard.openzeppelin.com/) – scaffold common patterns safely.
  - [DeFi Developer Roadmap](https://github.com/OffcierCia/DeFi-Developer-Road-Map) – comprehensive DeFi learning path.
  - [DeFiLlama Learn](https://defillama.com/learn) – DeFi protocol explanations.
  - [RareSkills Solidity Bootcamp](https://www.rareskills.io/) – advanced Solidity training.

- **Long‑form content**
  - *Mastering Ethereum* (G. Wood, A. Antonopoulos) – good EVM / protocol background.
  - *DeFi and the Future of Finance* – more on the finance side of DeFi protocols.
  - *Building Ethereum DApps* – practical dApp development guide.
  - [EVM Handbook](https://noxx3xxon.notion.site/noxx3xxon/EVM-Handbook-bb38e175cc404111a391907c4975426d) – deep dive into EVM internals.

---

## Fresh DeFi research, newsletters & channels

- **Newsletters / written**
  - [The Defiant](https://thedefiant.io) – daily DeFi news + explainers.
  - [Bankless](https://bankless.com) – DeFi, restaking, L2s, and broader crypto.
  - [Blockworks Research](https://blockworks.co/research) – deep dives on newer protocols.

- **Code‑first content**
  - [Smart Contract Programmer](https://www.youtube.com/@smartcontractprogrammer) – Solidity patterns and walkthroughs.
  - [Cyfrin / Patrick Collins](https://www.youtube.com/@CyfrinAudits) – security‑minded Solidity + audits.
  - [OpenZeppelin YouTube](https://www.youtube.com/@OpenZeppelin) – security, audits, and protocol breakdowns.
  - [Dapp University](https://www.youtube.com/@DappUniversity) – full-stack dApp tutorials.
  - [Eat The Blocks](https://www.youtube.com/@EatTheBlocks) – Solidity and Web3 development.
  - [Austin Griffith](https://www.youtube.com/@austingriffith) – scaffold-eth and builder content.
  - [Finematics](https://www.youtube.com/@Finematics) – DeFi concepts explained simply.

---

## Security & auditing resources

- **Must‑read**
  - [SWC Registry](https://swcregistry.io/) – catalog of common smart contract vulns.
  - [Damn Vulnerable DeFi](https://www.damnvulnerabledefi.xyz/) – hands‑on hacking challenges.
  - [Consensys Smart Contract Best Practices](https://consensys.github.io/smart-contract-best-practices/) – classic checklist.
  - [OpenZeppelin Security Audits](https://blog.openzeppelin.com/security-audits) – read real audit reports.
  - [Trail of Bits Security Practices](https://github.com/crytic/building-secure-contracts) – comprehensive security guide.
  - [Rekt Leaderboard](https://rekt.news/leaderboard/) – learn from past exploits.
  - [Immunefi Bug Bounties](https://immunefi.com/) – see real bug reports and fixes.
  - [DeFi Threat Matrix](https://github.com/0xKitsune/DeFi-Threat-Matrix) – comprehensive threat model.
  - [Smart Contract Security Best Practices](https://consensys.github.io/smart-contract-best-practices/) – security guidelines.
  - [Secureum](https://secureum.xyz/) – security education and resources.
  - [Ethereum Security](https://ethereum.org/en/developers/docs/security/) – official security docs.

- **Vulnerability databases & incident tracking**
  - [SWC Registry](https://swcregistry.io/) – Smart Contract Weakness Classification.
  - [CWE List](https://cwe.mitre.org/) – Common Weakness Enumeration.
  - [Rekt News](https://rekt.news/) – post-mortems of major exploits.
  - [DeFi Pulse Risk](https://defipulse.com/risk) – protocol risk assessments.
  - [HackenProof](https://hackenproof.com/) – bug bounty platform with reports.
  - [Code4rena](https://code4rena.com/) – competitive audit platform.

- **Security courses & certifications**
  - [Secureum Bootcamp](https://secureum.xyz/bootcamp) – comprehensive security training.
  - [Cyfrin Updraft](https://updraft.cyfrin.io/) – security-focused Solidity course.
  - [RareSkills Security Course](https://www.rareskills.io/security) – advanced security training.
  - [Consensys Academy](https://consensys.net/academy/) – blockchain security courses.
  - [Blockchain Security Alliance](https://blockchainsecurityalliance.org/) – security resources.
  - [Encode Club Auditing Bootcamps](https://www.encode.club/) – security and auditing bootcamps.
  - [OpenZeppelin University](https://university.openzeppelin.com/) – security and smart contract courses.
  - [Immunefi Academy](https://www.immunefi.com/academy/) – Web3 security and bug bounty education.
  - [Secureum Epoch CTFs](https://secureum.xyz/) – CTF-style security training.

- **Audit firms & reports**
  - [OpenZeppelin Audits](https://blog.openzeppelin.com/security-audits/) – audit reports.
  - [Trail of Bits Audits](https://github.com/trailofbits/publications) – security research.
  - [Consensys Diligence](https://consensys.io/diligence/audits/) – audit reports.
  - [CertiK](https://www.certik.com/) – security audits and monitoring.
  - [Quantstamp](https://quantstamp.com/) – automated and manual audits.
  - [MixBytes](https://mixbytes.io/) – security audits.
  - [ChainSecurity](https://chainsecurity.com/) – formal verification and audits.
  - [Least Authority](https://leastauthority.com/) – security audits.

- **Security tools**
  - [Slither](https://github.com/crytic/slither) – static analysis.
  - [Echidna](https://github.com/crytic/echidna) – property‑based / fuzz testing.
  - [Foundry](https://github.com/foundry-rs/foundry) – fast testing, fuzzing, and deployment.
  - [Mythril](https://github.com/Consensys/mythril) – security analysis framework.
  - [Manticore](https://github.com/trailofbits/manticore) – symbolic execution tool.
  - [Medusa](https://github.com/crytic/medusa) – fuzzing framework.
  - [Halmos](https://github.com/a16z/halmos) – symbolic testing for Foundry.
  - [Certora](https://www.certora.com/) – formal verification (commercial).
  - [Tenderly](https://tenderly.co/) – debugging and monitoring.
  - [4naly3er](https://github.com/Picodes/4naly3er) – gas optimization analyzer.
  - [Scribble](https://github.com/Consensys/scribble) – specification language for fuzzing.
  - [Diligence Fuzzing](https://github.com/crytic/building-secure-contracts) – fuzzing guide.
  - [Surya](https://github.com/Consensys/surya) – contract analysis tool.
  - [MythX](https://mythx.io/) – security analysis API.
  - [Securify](https://securify.chainsecurity.com/) – security scanner.
  - [Oyente](https://github.com/melonproject/oyente) – static analysis tool.

- **Security monitoring & incident response**
  - [Forta](https://forta.org/) – decentralized security monitoring.
  - [Tenderly Alerts](https://tenderly.co/alerts) – transaction monitoring.
  - [OpenZeppelin Defender](https://defender.openzeppelin.com/) – security operations.
  - [Pashov's Security Checklist](https://pashovkrum.medium.com/audit-smart-contracts-checklist-2023-677b63cfe0a3) – pre-audit checklist.
  - [Incident Response Plan](https://github.com/ethereum/ethereum-org-website/blob/dev/src/content/developers/docs/security/incident-response/index.md) – incident handling.

- **Security research & papers**
  - [Trail of Bits Research](https://blog.trailofbits.com/) – security research blog.
  - [Consensys Research](https://consensys.net/research/) – blockchain research.
  - [a16z Crypto Security](https://a16zcrypto.com/tag/security/) – security insights.
  - [Paradigm Security](https://www.paradigm.xyz/security) – security research.
  - [IACR Cryptology ePrint](https://eprint.iacr.org/) – cryptography papers.
  - [Security Research Papers](https://github.com/pcaversaccio/security-research-papers) – curated security papers.

- **Formal verification**
  - [Certora Prover](https://www.certora.com/) – formal verification tool.
  - [K Framework](https://kframework.org/) – formal verification framework.
  - [KEVM](https://github.com/runtimeverification/evm-semantics) – formal semantics of EVM.
  - [Act](https://github.com/ethereum/act) – specification language for smart contracts.
  - [Dafny](https://github.com/dafny-lang/dafny) – verification-aware programming language.
  - [Why3](https://why3.lri.fr/) – platform for deductive program verification.

- **Security checklists & guides**
  - [Smart Contract Security Checklist](https://github.com/sigp/smart-contract-security-checklist) – comprehensive checklist.
  - [Security Best Practices](https://consensys.github.io/smart-contract-best-practices/) – Consensys guide.
  - [Pre-Audit Checklist](https://github.com/nascentxyz/simple-security-toolkit) – pre-audit preparation.
  - [Security Standards](https://github.com/ConsenSys/smart-contract-best-practices) – best practices.
  - [DeFi Security Best Practices](https://github.com/nascentxyz/simple-security-toolkit) – DeFi-specific security.

- **Bug bounty platforms**
  - [Immunefi](https://immunefi.com/) – Web3 bug bounty platform.
  - [HackerOne](https://www.hackerone.com/) – security platform.
  - [Code4rena](https://code4rena.com/) – competitive audit platform.
  - [Sherlock](https://www.sherlock.xyz/) – audit contests.
  - [Cantina](https://cantina.xyz/) – security marketplace.

- **Security communities**
  - [Ethereum Security Discord](https://discord.gg/ethereum) – security discussions.
  - [Secureum Discord](https://discord.gg/secureum) – security community.
  - [Trail of Bits Discord](https://discord.gg/trailofbits) – security tooling community.

---

## Deep dives by theme

- **Restaking / AVS**
  - [EigenLayer Docs](https://docs.eigenlayer.xyz/) – core restaking + AVS model.
  - [EigenLayer whitepaper](https://www.eigenlayer.xyz/whitepaper) – design + threat model.

- **Perps, options & leverage**
  - [GMX Docs](https://gmxio.gitbook.io/gmx/) – perp DEX design and tokenomics.
  - [Lyra Docs](https://docs.lyra.finance/) – options AMM mechanics.
  - [Synthetix Docs](https://docs.synthetix.io/) – perps + synthetic assets infra.

- **RWA & stablecoins**
  - [MakerDAO Docs](https://docs.makerdao.com/) – DAI, vaults, RWA collateral.
  - [Frax Docs](https://docs.frax.finance/) – FRAX, frxETH, sfrxETH, Fraxlend.

- **Account abstraction & intents**
  - [ERC‑4337 spec](https://eips.ethereum.org/EIPS/eip-4337)
  - [StackUp ERC‑4337 docs](https://docs.stackup.sh/docs) – practical AA dev guide.

- **L2s & rollups**
  - [Optimism Docs](https://community.optimism.io/docs/) – OP Stack architecture.
  - [Arbitrum Docs](https://docs.arbitrum.io/) – Nitro rollup design.
  - [zkSync Docs](https://docs.zksync.io/) – zk rollup contracts & architecture.

---

## Zero Knowledge (ZK) resources

- **Learning ZK fundamentals**
  - [ZK Proofs Explained](https://www.zkproof.org/reference/main.html) – comprehensive ZK proof guide.
  - [Why and How zk-SNARK Works](https://arxiv.org/abs/1906.07221) – mathematical deep dive.
  - [ZK Whiteboard Sessions](https://www.youtube.com/playlist?list=PLj80z0cJm8QFnY6VLVa84nr-21DNvjWH7) – ZK concepts explained visually.
  - [ZK Proofs: A Primer](https://www.cryptologie.net/article/450/zk-proofs-a-primer/) – beginner-friendly introduction.
  - [ZK Learning Path](https://learn.0xparc.org/) – 0xPARC's structured ZK course.
  - [ZK Hack](https://www.zkhack.dev/) – ZK puzzles and challenges.
  - [ZK Podcast](https://zeroknowledge.fm/) – interviews with ZK researchers and builders.

- **ZK proof systems**
  - [Circom](https://docs.circom.io/) – circuit language for zkSNARKs.
  - [SnarkJS](https://github.com/iden3/snarkjs) – JavaScript zkSNARK implementation.
  - [Groth16](https://eprint.iacr.org/2016/260) – efficient zkSNARK construction.
  - [PLONK](https://eprint.iacr.org/2019/953) – universal SNARK with trusted setup.
  - [STARKs](https://starkware.co/stark/) – transparent proofs (no trusted setup).
  - [Halo2](https://zcash.github.io/halo2/) – PLONKish proving system.
  - [Nova](https://eprint.iacr.org/2021/370) – recursive SNARKs.

- **ZK libraries & frameworks**
  - [Circom](https://github.com/iden3/circom) – circuit compiler.
  - [SnarkJS](https://github.com/iden3/snarkjs) – JavaScript zkSNARK toolkit.
  - [Arkworks](https://arkworks.rs/) – Rust ZK proof libraries.
  - [Bellman](https://github.com/zcash/bellman) – Rust zkSNARK library.
  - [gnark](https://github.com/Consensys/gnark) – Go ZK proof library.
  - [Noir](https://noir-lang.org/) – ZK DSL by Aztec.
  - [Leo](https://www.aleo.org/post/leo) – ZK programming language.
  - [Risc0](https://www.risczero.com/) – ZK virtual machine.

- **zkEVMs & zk-rollups**
  - [zkSync Era](https://docs.zksync.io/) – zkEVM rollup.
  - [Polygon zkEVM](https://docs.polygon.technology/zkEVM/) – EVM-equivalent zk-rollup.
  - [Scroll](https://docs.scroll.io/) – zkEVM rollup.
  - [Linea](https://docs.linea.build/) – zkEVM by Consensys.
  - [Taiko](https://docs.taiko.xyz/) – based rollup with zk proofs.
  - [Starknet](https://docs.starknet.io/) – STARK-based L2.
  - [Aztec](https://docs.aztec.network/) – private smart contracts.

- **Privacy-preserving smart contracts**
  - [Aztec Protocol](https://docs.aztec.network/) – private DeFi on Ethereum.
  - [Tornado Cash](https://github.com/tornadocash/tornado-core) – private transactions (reference only).
  - [Semaphore](https://semaphore.appliedzkp.org/) – anonymous signaling.
  - [Zexe](https://eprint.iacr.org/2018/962) – decentralized private computation.
  - [Zcash](https://z.cash/technology/) – privacy-focused cryptocurrency.

- **ZK development tools**
  - [Circom Compiler](https://github.com/iden3/circom) – compile circuits.
  - [Circomlib](https://github.com/iden3/circomlib) – circuit templates.
  - [Powers of Tau](https://github.com/weijiekoh/perpetualpowersoftau) – trusted setup ceremony.
  - [Circom Snarkjs Template](https://github.com/iden3/circom-starter) – starter project.
  - [Hardhat Circom](https://github.com/projectsophon/hardhat-circom) – Hardhat plugin for Circom.
  - [Circomkit](https://github.com/erhant/circomkit) – Circom development toolkit.

- **ZK research & papers**
  - [Zcash Protocol Spec](https://zips.z.cash/protocol/protocol.pdf) – Zcash technical spec.
  - [ZK Proofs Research](https://zkproof.org/) – academic ZK research hub.
  - [IACR ePrint](https://eprint.iacr.org/) – cryptography research papers.
  - [ZK Research Papers](https://github.com/matter-labs/awesome-zero-knowledge-proofs) – curated ZK papers.
  - [Vitalik's ZK Posts](https://vitalik.ca/general/2022/06/15/using_snarks.html) – ZK explanations.

- **ZK in production**
  - [zkSync Contracts](https://github.com/matter-labs/zksync) – zkSync smart contracts.
  - [Polygon zkEVM Contracts](https://github.com/0xPolygonHermez/zkevm-contracts) – Polygon zkEVM.
  - [Starknet Contracts](https://github.com/starknet-edu/starknet-cairo-101) – Cairo smart contracts.
  - [Aztec Contracts](https://github.com/AztecProtocol/aztec-packages) – Aztec Noir contracts.

---

## Standards, libraries & tooling

- **Standards**
  - [EIPs](https://eips.ethereum.org/) – ERC‑20, ERC‑721, ERC‑1155, ERC‑4626, ERC‑4337, etc.
  - [OpenZeppelin Contracts](https://github.com/OpenZeppelin/openzeppelin-contracts) – reference implementations.

- **Libraries**
  - [Solmate](https://github.com/transmissions11/solmate) – gas-optimized building blocks.
  - [Solady](https://github.com/Vectorized/solady) – optimized utilities.
  - [🐍 snekmate](https://github.com/pcaversaccio/snekmate) – gas-optimized library.
  - [PRBMath](https://github.com/PaulRBerg/prb-math) – fixed-point math library.
  - [ABDK Math](https://github.com/abdk-consulting/abdk-libraries-solidity) – advanced math.
  - [String Utils](https://github.com/Arachnid/solidity-stringutils) – string manipulation.
  - [DateTime Library](https://github.com/bokkypoobah/BokkyPooBahsDateTimeLibrary) – date/time utilities.
  - [Merkle Tree](https://github.com/OpenZeppelin/merkle-tree) – Merkle proof verification.
  - [Enumerable Set](https://github.com/OpenZeppelin/openzeppelin-contracts/blob/master/contracts/utils/structs/EnumerableSet.sol) – efficient set operations.

- **Tooling**
  - [Foundry](https://github.com/foundry-rs/foundry) – forge/cast/anvil.
  - [Hardhat](https://github.com/NomicFoundation/hardhat) – development environment.
  - [Brownie](https://github.com/eth-brownie/brownie) – Python-based framework.
  - [Truffle](https://github.com/trufflesuite/truffle) – legacy but still used.
  - [Scaffold-ETH](https://github.com/scaffold-eth/scaffold-eth-2) – quickstart dApp template.
  - [Scaffold-ETH Hardhat](https://github.com/scaffold-eth/scaffold-eth) – Hardhat version.
  - [Waffle](https://github.com/EthWorks/Waffle) – testing framework.
  - [DappTools](https://github.com/dapphub/dapptools) – Unix-style dev tools.

- **Testing & debugging**
  - [Foundry Book](https://book.getfoundry.sh/) – comprehensive Foundry guide.
  - [Hardhat Docs](https://hardhat.org/docs) – official Hardhat documentation.
  - [Forge Std](https://github.com/foundry-rs/forge-std) – standard library for Foundry.
  - [Tenderly Debugger](https://docs.tenderly.co/debugger) – transaction debugging.
  - [Hardhat Console](https://hardhat.org/hardhat-runner/docs/guides/debugging) – interactive debugging.
  - [Ethereum Debugging](https://ethereum.org/en/developers/tutorials/debugging-transactions/) – debugging guide.

- **Gas optimization**
  - [Gas Optimization Techniques](https://github.com/0xKitsune/gas-optimization) – comprehensive guide.
  - [Gas Golfing Guide](https://github.com/0xKitsune/gas-golfing) – extreme optimization.
  - [Gas Station Network](https://www.opengsn.org/) – meta-transactions for gasless UX.
  - [4naly3er](https://github.com/Picodes/4naly3er) – automated gas reports.

- **Deployment & infrastructure**
  - [OpenZeppelin Defender](https://defender.openzeppelin.com/) – secure operations platform.
  - [Hardhat Deploy](https://github.com/wighawag/hardhat-deploy) – deployment plugin.
  - [Hardhat Upgrades](https://docs.openzeppelin.com/upgrades-plugins/1.x/) – upgradeable contracts.
  - [Multicall](https://github.com/makerdao/multicall) – batch multiple calls.
  - [Create2](https://eips.ethereum.org/EIPS/eip-1014) – deterministic contract addresses.
  - [Etherscan Verify](https://docs.etherscan.io/) – contract verification.

- **Design patterns & best practices**
  - [Solidity Patterns](https://github.com/fravoll/solidity-patterns) – common design patterns.
  - [Proxy Patterns](https://docs.openzeppelin.com/upgrades-plugins/1.x/proxies) – upgradeability patterns.
  - [Diamond Pattern](https://eips.ethereum.org/EIPS/eip-2535) – modular upgradeable contracts.
  - [Minimal Proxy (EIP-1167)](https://eips.ethereum.org/EIPS/eip-1167) – gas-efficient clones.
  - [Reentrancy Patterns](https://consensys.github.io/smart-contract-best-practices/attacks/reentrancy/) – prevention strategies.
  - [Access Control Patterns](https://docs.openzeppelin.com/contracts/4.x/access-control) – role-based access.

---

## Additional resources

- **Community & forums**
  - [Ethereum Stack Exchange](https://ethereum.stackexchange.com/) – Q&A for Ethereum devs.
  - [Solidity Forum](https://forum.soliditylang.org/) – official Solidity discussions.
  - [r/ethdev](https://www.reddit.com/r/ethdev/) – Ethereum development subreddit.
  - [Ethereum Research](https://ethresear.ch/) – research discussions.
  - [CryptoDevHub](https://cryptodevhub.io/) – community and resources.

- **Newsletters & blogs**
  - [Week in Ethereum News](https://weekinethereumnews.com/) – weekly Ethereum updates.
  - [Ethereum Foundation Blog](https://blog.ethereum.org/) – official updates.
  - [Vitalik's Blog](https://vitalik.ca/) – Ethereum co-founder's thoughts.
  - [0xResearch](https://0xresearch.substack.com/) – DeFi research and analysis.

- **Code examples & templates**
  - [OpenZeppelin Contracts](https://github.com/OpenZeppelin/openzeppelin-contracts) – battle-tested contracts.
  - [Scaffold-ETH Examples](https://github.com/scaffold-eth/scaffold-eth-examples) – dApp templates.
  - [Solidity Examples](https://github.com/ethereum/solidity-examples) – official examples.
  - [Awesome Solidity](https://github.com/bkrem/awesome-solidity) – curated Solidity resources.

- **EVM & low-level**
  - [EVM Opcodes](https://www.evm.codes/) – interactive opcode reference.
  - [EVM Playground](https://www.evm.codes/playground) – test EVM bytecode.
  - [Yellow Paper](https://ethereum.github.io/yellowpaper/paper.pdf) – Ethereum protocol spec.
  - [EVM Deep Dives](https://noxx3xxon.notion.site/noxx3xxon/EVM-Deep-Dives-b76f1c3d14764a20995e4a4e8a4fbc1a) – EVM internals.

---

## Blockchain development resources

- **Blockchain fundamentals**
  - [Ethereum Whitepaper](https://ethereum.org/en/whitepaper/) – original Ethereum vision.
  - [Bitcoin Whitepaper](https://bitcoin.org/bitcoin.pdf) – foundational blockchain paper.
  - [Mastering Bitcoin](https://github.com/bitcoinbook/bitcoinbook) – comprehensive Bitcoin guide.
  - [Blockchain Basics](https://ethereum.org/en/developers/docs/intro-to-ethereum/) – Ethereum intro.
  - [How Ethereum Works](https://ethereum.org/en/developers/docs/ethereum-stack/) – Ethereum stack.
  - [Blockchain Explained](https://www.investopedia.com/terms/b/blockchain.asp) – basic concepts.

- **Consensus mechanisms**
  - [Proof of Stake](https://ethereum.org/en/developers/docs/consensus-mechanisms/pos/) – PoS explained.
  - [Proof of Work](https://ethereum.org/en/developers/docs/consensus-mechanisms/pow/) – PoW explained.
  - [Byzantine Fault Tolerance](https://en.wikipedia.org/wiki/Byzantine_fault) – BFT concepts.
  - [Casper FFG](https://arxiv.org/abs/1710.09437) – Ethereum's PoS protocol.
  - [Tendermint](https://docs.tendermint.com/) – BFT consensus engine.
  - [HotStuff](https://arxiv.org/abs/1803.05069) – BFT consensus algorithm.

- **Cryptography fundamentals**
  - [Applied Cryptography](https://www.schneier.com/books/applied-cryptography/) – classic crypto book by Bruce Schneier.
  - [Cryptography I (Coursera)](https://www.coursera.org/learn/crypto) – Stanford crypto course by Dan Boneh.
  - [Cryptography II (Coursera)](https://www.coursera.org/learn/crypto2) – advanced Stanford crypto course.
  - [Introduction to Cryptography](https://www.coursera.org/learn/cryptography) – cryptography basics.
  - [Crypto101](https://www.crypto101.io/) – free cryptography course.
  - [Cryptography Stack Exchange](https://crypto.stackexchange.com/) – Q&A for cryptography.
  - [IACR](https://www.iacr.org/) – International Association for Cryptologic Research.

- **Hash functions & hashing**
  - [Hash Functions](https://ethereum.org/en/developers/docs/ethereum-stack/hashing/) – hashing in blockchain.
  - [SHA-256](https://en.wikipedia.org/wiki/SHA-2) – Secure Hash Algorithm 256.
  - [Keccak-256](https://keccak.team/) – Ethereum's hash function.
  - [Blake2](https://www.blake2.net/) – fast cryptographic hash function.
  - [Poseidon Hash](https://www.poseidon-hash.info/) – ZK-friendly hash function.
  - [Merkle Trees](https://ethereum.org/en/developers/docs/data-structures-and-encoding/merkle-patricia-trie/) – Merkle tree structures.
  - [Merkle Proofs](https://ethereum.org/en/developers/tutorials/merkle-proofs-for-offline-data-integrity/) – Merkle proof tutorial.
  - [Patricia Trie](https://ethereum.org/en/developers/docs/data-structures-and-encoding/patricia-merkle-trie/) – Ethereum's state tree.

- **Digital signatures & ECDSA**
  - [Digital Signatures](https://ethereum.org/en/developers/docs/transactions/) – ECDSA and signatures.
  - [ECDSA Explained](https://en.wikipedia.org/wiki/Elliptic_Curve_Digital_Signature_Algorithm) – ECDSA overview.
  - [ECDSA in Ethereum](https://ethereum.org/en/developers/docs/transactions/#digital-signatures) – Ethereum signatures.
  - [BLS Signatures](https://en.wikipedia.org/wiki/BLS_digital_signature) – Boneh-Lynn-Shacham signatures.
  - [Schnorr Signatures](https://en.wikipedia.org/wiki/Schnorr_signature) – Schnorr signature scheme.
  - [EdDSA](https://en.wikipedia.org/wiki/EdDSA) – Edwards-curve Digital Signature Algorithm.
  - [Signature Aggregation](https://ethresearch.ch/t/aggregated-signatures-for-eth2/484) – signature aggregation.

- **Elliptic curve cryptography**
  - [Elliptic Curve Cryptography](https://en.wikipedia.org/wiki/Elliptic-curve_cryptography) – ECC basics.
  - [ECC Explained](https://blog.cloudflare.com/a-relatively-easy-to-understand-primer-on-elliptic-curve-cryptography/) – ECC primer.
  - [Secp256k1](https://en.bitcoin.it/wiki/Secp256k1) – Bitcoin/Ethereum curve.
  - [Curve25519](https://en.wikipedia.org/wiki/Curve25519) – high-speed ECC curve.
  - [BN254](https://hackmd.io/@jpw/bn254) – pairing-friendly curve.
  - [BLS12-381](https://hackmd.io/@benjaminion/bls12-381) – ZK-friendly curve.
  - [Elliptic Curve Visualizer](https://www.desmos.com/calculator/ialhd71we3) – interactive ECC visualization.

- **Encryption & symmetric cryptography**
  - [AES (Advanced Encryption Standard)](https://en.wikipedia.org/wiki/Advanced_Encryption_Standard) – symmetric encryption.
  - [ChaCha20](https://en.wikipedia.org/wiki/Salsa20) – stream cipher.
  - [Poly1305](https://en.wikipedia.org/wiki/Poly1305) – message authentication code.
  - [ChaCha20-Poly1305](https://tools.ietf.org/html/rfc8439) – authenticated encryption.
  - [Encryption Modes](https://en.wikipedia.org/wiki/Block_cipher_mode_of_operation) – block cipher modes.

- **Public key cryptography**
  - [RSA](https://en.wikipedia.org/wiki/RSA_(cryptosystem)) – Rivest-Shamir-Adleman.
  - [Diffie-Hellman](https://en.wikipedia.org/wiki/Diffie%E2%80%93Hellman_key_exchange) – key exchange protocol.
  - [ECDH](https://en.wikipedia.org/wiki/Elliptic-curve_Diffie%E2%80%93Hellman) – Elliptic Curve Diffie-Hellman.
  - [Public Key Infrastructure](https://en.wikipedia.org/wiki/Public_key_infrastructure) – PKI concepts.

- **Zero-knowledge proofs (see ZK section)**
  - [ZK Proofs Explained](https://www.zkproof.org/reference/main.html) – comprehensive ZK guide.
  - [Why and How zk-SNARK Works](https://arxiv.org/abs/1906.07221) – mathematical deep dive.
  - [ZK Learning Path](https://learn.0xparc.org/) – structured ZK course.
  - See "Zero Knowledge (ZK) resources" section for more.

- **Cryptographic libraries**
  - [OpenSSL](https://www.openssl.org/) – cryptographic library.
  - [Libsodium](https://libsodium.org/) – modern crypto library.
  - [Bouncy Castle](https://www.bouncycastle.org/) – Java/C# crypto library.
  - [Crypto++](https://www.cryptopp.com/) – C++ crypto library.
  - [TweetNaCl](https://tweetnacl.cr.yp.to/) – minimal crypto library.
  - [Noble](https://github.com/paulmillr/noble) – JavaScript crypto library.
  - [secp256k1](https://github.com/bitcoin-core/secp256k1) – Bitcoin's crypto library.
  - [Circom](https://github.com/iden3/circom) – ZK circuit compiler.

- **Cryptography in blockchain**
  - [Ethereum Cryptography](https://ethereum.org/en/developers/docs/ethereum-stack/) – crypto in Ethereum.
  - [Bitcoin Cryptography](https://en.bitcoin.it/wiki/Cryptography) – crypto in Bitcoin.
  - [Cryptographic Primitives](https://ethereum.org/en/developers/docs/ethereum-stack/) – blockchain crypto primitives.
  - [Random Number Generation](https://ethereum.org/en/developers/docs/consensus-mechanisms/pos/) – randomness in PoS.
  - [VRF (Verifiable Random Function)](https://en.wikipedia.org/wiki/Verifiable_random_function) – verifiable randomness.
  - [Commitment Schemes](https://en.wikipedia.org/wiki/Commitment_scheme) – cryptographic commitments.

- **Cryptography research & papers**
  - [IACR ePrint Archive](https://eprint.iacr.org/) – cryptography research papers.
  - [Crypto Conference](https://www.iacr.org/conferences/) – IACR conferences.
  - [CRYPTO](https://www.iacr.org/meetings/crypto/) – annual crypto conference.
  - [EUROCRYPT](https://www.iacr.org/meetings/eurocrypt/) – European crypto conference.
  - [ASIACRYPT](https://www.iacr.org/meetings/asiacrypt/) – Asian crypto conference.
  - [Real World Crypto](https://rwc.iacr.org/) – applied cryptography conference.

- **Cryptography books**
  - *Applied Cryptography* by Bruce Schneier – comprehensive crypto book.
  - *Introduction to Modern Cryptography* by Katz & Lindell – modern crypto theory.
  - *Cryptography Engineering* by Ferguson, Schneier, Kohno – practical crypto.
  - *The Code Book* by Simon Singh – history of cryptography.
  - *Understanding Cryptography* by Paar & Pelzl – crypto textbook.

- **Cryptography tools & implementations**
  - [Hash Calculator](https://emn178.github.io/online-tools/sha256.html) – online hash calculator.
  - [ECDSA Signature Tool](https://www.bitaddress.org/) – signature generation.
  - [Elliptic Curve Calculator](https://www.desmos.com/calculator/ialhd71we3) – ECC calculator.
  - [Crypto Playground](https://cryptopals.com/) – crypto challenges.
  - [Cryptohack](https://cryptohack.org/) – cryptography challenges.
  - [Factoring Challenge](https://en.wikipedia.org/wiki/RSA_Factoring_Challenge) – RSA factoring.

- **Post-quantum cryptography**
  - [NIST Post-Quantum Crypto](https://csrc.nist.gov/projects/post-quantum-cryptography) – PQC standardization.
  - [Post-Quantum Cryptography](https://en.wikipedia.org/wiki/Post-quantum_cryptography) – PQC overview.
  - [Lattice-Based Crypto](https://en.wikipedia.org/wiki/Lattice-based_cryptography) – lattice cryptography.
  - [Hash-Based Signatures](https://en.wikipedia.org/wiki/Hash-based_signatures) – hash-based crypto.
  - [Code-Based Crypto](https://en.wikipedia.org/wiki/Code-based_cryptography) – code-based cryptography.

- **Network protocols & P2P**
  - [Ethereum P2P](https://github.com/ethereum/devp2p) – Ethereum networking protocol.
  - [LibP2P](https://libp2p.io/) – modular P2P networking stack.
  - [Gossip Protocols](https://en.wikipedia.org/wiki/Gossip_protocol) – gossip protocol basics.
  - [Kademlia DHT](https://en.wikipedia.org/wiki/Kademlia) – distributed hash table.
  - [Ethereum Wire Protocol](https://github.com/ethereum/devp2p/blob/master/caps/eth.md) – ETH protocol spec.

- **Node operation & infrastructure**
  - [Running an Ethereum Node](https://ethereum.org/en/developers/docs/nodes-and-clients/) – node setup.
  - [Geth](https://geth.ethereum.org/) – Go Ethereum client.
  - [Erigon](https://github.com/ledgerwatch/erigon) – efficient Ethereum client.
  - [Nethermind](https://nethermind.io/) – .NET Ethereum client.
  - [Besu](https://besu.hyperledger.org/) – Java Ethereum client.
  - [Node Monitoring](https://ethereum.org/en/developers/docs/nodes-and-clients/node-monitoring/) – monitoring guides.
  - [MEV-Boost](https://boost.flashbots.net/) – MEV infrastructure.

- **Blockchain architecture**
  - [Ethereum Architecture](https://ethereum.org/en/developers/docs/ethereum-stack/) – system architecture.
  - [State Management](https://ethereum.org/en/developers/docs/state/) – blockchain state.
  - [Transaction Lifecycle](https://ethereum.org/en/developers/docs/transactions/) – tx processing.
  - [Block Structure](https://ethereum.org/en/developers/docs/blocks/) – block anatomy.
  - [Gas & Fees](https://ethereum.org/en/developers/docs/gas/) – gas mechanism.
  - [Storage](https://ethereum.org/en/developers/docs/storage/) – contract storage.

- **Cross-chain & interoperability**
  - [Chainlink CCIP](https://chain.link/cross-chain) – cross-chain infrastructure.
  - [Wormhole](https://docs.wormhole.com/) – cross-chain messaging.
  - [LayerZero](https://docs.layerzero.network/) – omnichain interoperability.
  - [Axelar](https://docs.axelar.dev/) – cross-chain communication.
  - [IBC Protocol](https://ibc.cosmos.network/) – Inter-Blockchain Communication.
  - [Polkadot XCM](https://wiki.polkadot.network/docs/xcm-overview) – cross-consensus messaging.

- **MEV (Maximal Extractable Value)**
  - [Flashbots](https://docs.flashbots.net/) – MEV research and infrastructure.
  - [MEV-Boost](https://boost.flashbots.net/) – MEV infrastructure for validators.
  - [MEV Research](https://ethereum.org/en/developers/docs/mev/) – MEV explained.
  - [MEV-Share](https://docs.flashbots.net/flashbots-mev-share/overview) – MEV sharing protocol.
  - [EigenPhi](https://eigenphi.io/) – MEV analytics.
  - [MEV-Boost Relay List](https://boost.flashbots.net/) – relay infrastructure.

- **Oracles & data feeds**
  - [Chainlink](https://docs.chain.link/) – decentralized oracle network.
  - [Pyth Network](https://docs.pyth.network/) – price oracle network.
  - [UMA](https://docs.umaproject.org/) – optimistic oracle.
  - [API3](https://docs.api3.org/) – first-party oracles.
  - [Band Protocol](https://docs.bandchain.org/) – cross-chain oracle.
  - [Tellor](https://docs.tellor.io/tellor/) – decentralized oracle.

- **Blockchain research & papers**
  - [Ethereum Research](https://ethresear.ch/) – research forum.
  - [Vitalik's Blog](https://vitalik.ca/) – Ethereum co-founder's research.
  - [a16z Crypto Research](https://a16zcrypto.com/research/) – crypto research.
  - [Paradigm Research](https://www.paradigm.xyz/writing) – protocol research.
  - [ArXiv Cryptography](https://arxiv.org/list/cs.CR/recent) – latest crypto papers.
  - [Blockchain Research Papers](https://github.com/decrypto-org/blockchain-papers) – curated papers.

- **Blockchain infrastructure & APIs**
  - [Alchemy](https://www.alchemy.com/) – blockchain API and infrastructure.
  - [Infura](https://www.infura.io/) – Ethereum API service.
  - [QuickNode](https://www.quicknode.com/) – blockchain infrastructure.
  - [Ankr](https://www.ankr.com/) – Web3 infrastructure.
  - [Moralis](https://moralis.io/) – Web3 development platform.
  - [Thirdweb](https://thirdweb.com/) – Web3 development framework.
  - [Pinata](https://www.pinata.cloud/) – IPFS pinning service.
  - [The Graph](https://thegraph.com/) – decentralized indexing protocol.

- **Blockchain explorers & analytics**
  - [Etherscan](https://etherscan.io/) – Ethereum block explorer.
  - [Blockscout](https://blockscout.com/) – open-source explorer.
  - [Dune Analytics](https://dune.com/) – blockchain analytics platform.
  - [Nansen](https://www.nansen.ai/) – on-chain analytics.
  - [Etherscan API](https://docs.etherscan.io/) – blockchain data API.
  - [Tenderly](https://tenderly.co/) – transaction simulation and monitoring.
  - [OpenChain](https://openchain.xyz/) – on-chain analytics.

- **Blockchain testing & simulation**
  - [Ganache](https://trufflesuite.com/ganache/) – personal blockchain for testing.
  - [Hardhat Network](https://hardhat.org/hardhat-network/docs/overview) – local Ethereum network.
  - [Anvil](https://book.getfoundry.sh/anvil/) – local testnet node.
  - [Foundry Cheatcodes](https://book.getfoundry.sh/cheatcodes/) – testing utilities.
  - [Tenderly Forks](https://docs.tenderly.co/simulations-and-forks) – fork mainnet for testing.
  - [Alchemy Fork](https://docs.alchemy.com/reference/fork-mainnet) – fork mainnet.

- **Blockchain monitoring & alerting**
  - [OpenZeppelin Defender](https://defender.openzeppelin.com/) – security operations.
  - [Forta](https://forta.org/) – decentralized security monitoring.
  - [Tenderly Alerts](https://tenderly.co/alerts) – transaction monitoring.
  - [PagerDuty for Blockchain](https://www.pagerduty.com/) – incident management.
  - [Grafana Blockchain Dashboards](https://grafana.com/grafana/dashboards/) – monitoring dashboards.

- **Multi-chain development**
  - [Chainlink CCIP](https://chain.link/cross-chain) – cross-chain infrastructure.
  - [Wormhole](https://docs.wormhole.com/) – cross-chain messaging.
  - [LayerZero](https://docs.layerzero.network/) – omnichain interoperability.
  - [Axelar](https://docs.axelar.dev/) – cross-chain communication.
  - [Hyperlane](https://docs.hyperlane.xyz/) – permissionless interoperability.
  - [Multichain](https://docs.multichain.org/) – cross-chain router.
  - [Socket](https://docs.socket.tech/) – cross-chain infrastructure.

- **Blockchain data & indexing**
  - [The Graph](https://thegraph.com/) – decentralized indexing.
  - [Subgraph Studio](https://thegraph.com/studio/) – subgraph development.
  - [Alchemy SDK](https://docs.alchemy.com/reference/alchemy-sdk-quickstart) – blockchain SDK.
  - [Ethers.js](https://docs.ethers.org/) – Ethereum library.
  - [Web3.js](https://web3js.readthedocs.io/) – Ethereum JavaScript API.
  - [Viem](https://viem.sh/) – TypeScript Ethereum library.
  - [Wagmi](https://wagmi.sh/) – React Hooks for Ethereum.

- **Blockchain wallets & key management**
  - [MetaMask](https://docs.metamask.io/) – browser wallet.
  - [WalletConnect](https://docs.walletconnect.com/) – wallet connection protocol.
  - [Web3Auth](https://web3auth.io/docs/) – authentication infrastructure.
  - [Safe (Gnosis Safe)](https://docs.safe.global/) – smart contract wallet.
  - [Ledger](https://www.ledger.com/) – hardware wallet.
  - [Trezor](https://trezor.io/) – hardware wallet.
  - [Key Management](https://ethereum.org/en/developers/docs/accounts/) – account management.

- **Blockchain scaling solutions**
  - [Polygon](https://docs.polygon.technology/) – scaling solution.
  - [Arbitrum](https://docs.arbitrum.io/) – optimistic rollup.
  - [Optimism](https://docs.optimism.io/) – optimistic rollup.
  - [Base](https://docs.base.org/) – OP Stack L2.
  - [zkSync](https://docs.zksync.io/) – zk-rollup.
  - [Starknet](https://docs.starknet.io/) – STARK-based L2.
  - [Scroll](https://docs.scroll.io/) – zkEVM rollup.

- **Blockchain governance**
  - [OpenZeppelin Governor](https://docs.openzeppelin.com/contracts/4.x/api/governance) – governance contracts.
  - [Compound Governor](https://compound.finance/docs/governance) – governance system.
  - [Aragon](https://aragon.org/) – DAO framework.
  - [Snapshot](https://docs.snapshot.org/) – off-chain voting.
  - [Tally](https://www.tally.xyz/) – on-chain governance platform.

- **Blockchain standards & specifications**
  - [EIPs](https://eips.ethereum.org/) – Ethereum Improvement Proposals.
  - [ERC Standards](https://eips.ethereum.org/erc) – token and contract standards.
  - [BIPs](https://github.com/bitcoin/bips) – Bitcoin Improvement Proposals.
  - [Ethereum JSON-RPC](https://ethereum.org/en/developers/docs/apis/json-rpc/) – RPC specification.
  - [Ethereum ABI](https://docs.soliditylang.org/en/latest/abi-spec.html) – Application Binary Interface.

- **Alternative blockchain ecosystems**
  - [Solana](https://docs.solana.com/) – high-performance blockchain.
  - [Cosmos](https://docs.cosmos.network/) – internet of blockchains.
  - [Polkadot](https://docs.polkadot.network/) – heterogeneous multi-chain.
  - [Avalanche](https://docs.avax.network/) – platform for custom blockchains.
  - [Near Protocol](https://docs.near.org/) – developer-friendly blockchain.
  - [Sui](https://docs.sui.io/) – next-gen blockchain platform.
  - [Aptos](https://aptos.dev/) – Move-based blockchain.
  - [Cardano](https://docs.cardano.org/) – research-driven blockchain.
  - [Tezos](https://tezos.com/learn/) – self-amending blockchain.
  - [BNB Chain](https://docs.bnbchain.org/) – BSC and BNB Greenfield.

- **Tokenomics & economics**
  - [Token Engineering](https://tokenengineering.net/) – token design framework.
  - [Tokenomics Design](https://www.tokenomics.com/) – token economics guide.
  - [Mechanism Design](https://www.paradigm.xyz/2020/08/mechanism-design) – protocol design.
  - [Token Distribution](https://www.paradigm.xyz/2020/10/token-distribution) – distribution strategies.
  - [Vesting Schedules](https://github.com/OpenZeppelin/openzeppelin-contracts/blob/master/contracts/finance/VestingWallet.sol) – vesting implementations.
  - [Token Standards Comparison](https://ethereum.org/en/developers/docs/standards/tokens/) – token standard overview.

- **Blockchain storage solutions**
  - [IPFS](https://docs.ipfs.tech/) – InterPlanetary File System.
  - [Arweave](https://docs.arweave.org/) – permanent storage.
  - [Filecoin](https://docs.filecoin.io/) – decentralized storage network.
  - [Storj](https://docs.storj.io/) – decentralized cloud storage.
  - [Swarm](https://docs.ethswarm.org/) – Ethereum storage.
  - [Pinata](https://docs.pinata.cloud/) – IPFS pinning service.
  - [NFT.Storage](https://nft.storage/) – NFT storage service.

- **Blockchain identity & reputation**
  - [ENS (Ethereum Name Service)](https://docs.ens.domains/) – decentralized naming.
  - [Unstoppable Domains](https://docs.unstoppabledomains.com/) – blockchain domains.
  - [Ceramic](https://developers.ceramic.network/) – decentralized identity.
  - [Spruce ID](https://docs.spruceid.com/) – self-sovereign identity.
  - [BrightID](https://www.brightid.org/) – proof of unique humanity.
  - [Worldcoin](https://worldcoin.org/) – proof of personhood.
  - [Gitcoin Passport](https://docs.passport.xyz/) – identity verification.

- **Blockchain gaming & NFTs**
  - [ERC-721](https://eips.ethereum.org/EIPS/eip-721) – NFT standard.
  - [ERC-1155](https://eips.ethereum.org/EIPS/eip-1155) – multi-token standard.
  - [OpenSea API](https://docs.opensea.io/) – NFT marketplace API.
  - [Rarible Protocol](https://docs.rarible.org/) – NFT protocol.
  - [Immutable X](https://docs.immutable.com/) – NFT scaling solution.
  - [Enjin](https://docs.enjin.io/) – blockchain gaming platform.
  - [Polygon Gaming](https://docs.polygon.technology/docs/develop/gaming/) – gaming on Polygon.

- **Blockchain education & courses**
  - [Ethereum.org Learn](https://ethereum.org/en/learn/) – Ethereum learning hub.
  - [CryptoZombies](https://cryptozombies.io/) – Solidity course.
  - [Buildspace](https://buildspace.so/) – Web3 project-based learning.
  - [Pointer](https://www.pointer.gg/) – Web3 development courses.
  - [LearnWeb3](https://learnweb3.io/) – Web3 developer education.
  - [Questbook](https://www.questbook.app/) – Web3 learning platform.
  - [Alchemy University](https://university.alchemy.com/) – blockchain education.
  - [Consensys Academy](https://consensys.net/academy/) – blockchain courses.

- **Blockchain events & conferences**
  - [ETHGlobal](https://ethglobal.com/) – Ethereum hackathons.
  - [Devcon](https://devcon.org/) – Ethereum developer conference.
  - [ETHDenver](https://www.ethdenver.com/) – Ethereum conference.
  - [Consensus](https://consensus2024.coindesk.com/) – blockchain conference.
  - [Ethereum Community Conference](https://ethcc.io/) – European Ethereum conference.
  - [Solana Breakpoint](https://solana.com/breakpoint) – Solana conference.
  - [Polkadot Decoded](https://decoded.polkadot.network/) – Polkadot conference.

- **Blockchain metrics & analytics**
  - [DeFiLlama](https://defillama.com/) – DeFi TVL and analytics.
  - [DeFiPulse](https://defipulse.com/) – DeFi analytics.
  - [Token Terminal](https://tokenterminal.com/) – crypto fundamentals.
  - [Glassnode](https://glassnode.com/) – on-chain analytics.
  - [Santiment](https://santiment.net/) – crypto market intelligence.
  - [Messari](https://messari.io/) – crypto research and data.
  - [CoinGecko](https://www.coingecko.com/) – cryptocurrency data.
  - [CoinMarketCap](https://coinmarketcap.com/) – crypto market data.

- **Blockchain compliance & regulation**
  - [Chainalysis](https://www.chainalysis.com/) – blockchain compliance.
  - [Elliptic](https://www.elliptic.co/) – crypto compliance.
  - [TRM Labs](https://www.trmlabs.com/) – blockchain intelligence.
  - [CipherTrace](https://ciphertrace.com/) – crypto compliance.
  - [OFAC Sanctions](https://ofac.treasury.gov/) – sanctions compliance.
  - [FATF Guidance](https://www.fatf-gafi.org/) – crypto regulation guidance.
  - [SEC Crypto Framework](https://www.sec.gov/cryptoassets) – SEC guidance.

- **Blockchain performance & optimization**
  - [EVM Performance](https://ethereum.org/en/developers/docs/evm/) – EVM optimization.
  - [Gas Optimization](https://github.com/0xKitsune/gas-optimization) – gas saving techniques.
  - [Storage Optimization](https://ethereum.org/en/developers/docs/storage/) – storage efficiency.
  - [Batch Operations](https://ethereum.org/en/developers/docs/transactions/) – transaction batching.
  - [State Channels](https://ethereum.org/en/developers/docs/scaling/state-channels/) – off-chain scaling.
  - [Sidechains](https://ethereum.org/en/developers/docs/scaling/sidechains/) – sidechain solutions.

- **Blockchain development frameworks**
  - [Truffle Suite](https://trufflesuite.com/) – development framework.
  - [Embark](https://framework.embarklabs.io/) – dApp framework.
  - [Buidler](https://buidler.dev/) – task runner (now Hardhat).
  - [Scribe](https://scribe.codes/) – smart contract documentation.
  - [Sourcify](https://sourcify.dev/) – contract verification.
  - [Ethernal](https://www.tryethernal.com/) – blockchain explorer for devs.

- **Blockchain testing strategies**
  - [Testing Best Practices](https://ethereum.org/en/developers/docs/smart-contracts/testing/) – testing guide.
  - [Property-Based Testing](https://github.com/crytic/building-secure-contracts) – property testing.
  - [Integration Testing](https://ethereum.org/en/developers/docs/smart-contracts/testing/) – integration tests.
  - [Fork Testing](https://book.getfoundry.sh/cheatcodes/fork-testing) – fork-based testing.
  - [Invariant Testing](https://book.getfoundry.sh/invariant-testing) – invariant testing.
  - [Differential Testing](https://github.com/crytic/building-secure-contracts) – differential fuzzing.

- **Blockchain documentation tools**
  - [NatSpec](https://docs.soliditylang.org/en/latest/natspec-format.html) – Solidity documentation.
  - [Docusaurus](https://docusaurus.io/) – documentation framework.
  - [GitBook](https://www.gitbook.com/) – documentation platform.
  - [Mintlify](https://mintlify.com/) – documentation builder.
  - [Scribe](https://scribe.codes/) – smart contract docs generator.

- **Blockchain communities & forums**
  - [Ethereum Discord](https://discord.gg/ethereum) – Ethereum community.
  - [Solidity Discord](https://discord.gg/solidity) – Solidity community.
  - [Foundry Discord](https://discord.gg/foundry) – Foundry community.
  - [Hardhat Discord](https://discord.gg/hardhat) – Hardhat community.
  - [Web3 Builders](https://web3builders.dev/) – builder community.
  - [Developer DAO](https://www.developerdao.com/) – developer community.

- **Blockchain podcasts & media**
  - [Bankless](https://banklesshq.com/) – DeFi and crypto podcast.
  - [Unchained](https://unchainedpodcast.com/) – crypto podcast.
  - [The Defiant](https://thedefiant.io/podcasts) – DeFi podcast.
  - [Epicenter](https://epicenter.tv/) – blockchain podcast.
  - [Zero Knowledge](https://zeroknowledge.fm/) – ZK podcast.
  - [a16z Crypto](https://a16zcrypto.com/podcasts/) – crypto podcast.

- **Blockchain job boards & careers**
  - [Crypto Jobs List](https://cryptojobslist.com/) – crypto job board.
  - [Web3.career](https://web3.career/) – Web3 jobs.
  - [Crypto Jobs](https://crypto.jobs/) – blockchain jobs.
  - [Remote3](https://remote3.co/) – remote Web3 jobs.
  - [CryptoJobs](https://cryptojobs.com/) – blockchain careers.

## How to use this repo

- **Browsing**: scroll through the protocol table, pick a protocol, and deep‑dive into its repo + docs.
- **Learning**: pair a learning resource with a protocol implementation (e.g. read lending docs + Aave code).
- **Security practice**: pick a vuln from SWC, find it in real audits, then look at the actual protocol code.
- **Building**: use the tooling section to set up your dev environment, then reference design patterns and libraries.

If you have a favorite link, thread, paper, or repo – add it here.

---

## Contributing

- **Open a PR**: add a row, setion, or resource you’ve actually used and recommend.
- **Keep it high signal**: no SEO spam, no random Medium posts.
- **Format**: keep tables and headings consistent with the current style.

## License

do whatever you want ser – but stars and PRs are appreciated :)
