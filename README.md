
# The Writing is on the Wall: Analyzing the Boom of Inscriptions and its Impact on EVM-compatible Blockchains

This repository shares the scripts and data sets used in the following peer-reviewed academic publication:

* [The Writing is on the Wall: Analyzing the Boom of Inscriptions and its Impact on EVM-compatible Blockchains](./messias-caaw25-inscriptions-boom.pdf). Johnnatan Messias, Krzysztof Gogol, Maria Inês Silva, and Benjamin Livshits. In Proceedings of the 4th International Workshop on Cryptoasset Analytics (CAAW). 2025.


## Data sets
To enable scientific reproducibility of our results and other research areas to explore Ethereum, EVM-based rollups, and Inscriptions, we make our pre-processed **data set available for download [here](https://blockchain.mpi-sws.org/datasets/#files%2Finscriptions-boom)** 📥.

We believe this data set is key to any research group interested in understanding and providing insights into the Bitcoin ecosystem.

### Data set used to analyze inscription events on five blockchains.
| Chain        | Start Date         | End Date           | # of Issuers | # of Blocks | # of Inscriptions |
|-------------|------------------|------------------|-------------|------------|------------------|
| Arbitrum    | June 17th, 2023   | April 30th, 2024 | 118,544     | 3,575,299  | 16,309,035      |
| Base        | July 28th, 2023   | April 30th, 2024 | 79,573      | 780,770    | 2,020,661       |
| Ethereum    | June 14th, 2023   | April 30th, 2024 | 245,008     | 930,824    | 6,493,580       |
| Optimism    | June 18th, 2023   | April 30th, 2024 | 49,112      | 588,053    | 1,475,663       |
| ZKsync Era  | June 18th, 2023   | April 30th, 2024 | 481,687     | 2,809,054  | 17,161,306      |

### Inscription transactions per issuers.
| Protocol    | # of Issuers | Mean   | Std.   | Median | Min | Max   |
|------------|-------------|--------|--------|--------|-----|-------|
| Arbitrum   | 118,544     | 137.57 | 676.76 | 6      | 1   | 38,050  |
| Base       | 79,573      | 25.39  | 154.91 | 3      | 1   | 19,674  |
| Ethereum   | 245,008     | 26.50  | 245.60 | 3      | 1   | 67,713  |
| Optimism   | 49,112      | 30.04  | 168.05 | 3      | 1   | 19,612  |
| ZKsync Era | 481,687     | 35.62  | 245.35 | 3      | 1   | 40,770  |


### Inscription operations cost in GWei for major tokens.
| Chain       | Token            | Operation | Total (in ETH) | Mean      | Std.      | Median    | Min      | Max         |
|-------------|------------------|-----------|----------------|-----------|-----------|-----------|----------|-------------|
| Arbitrum    | fair-20 fair     | mint      | 0.77           | 74.10     | 305.72    | 60.87     | 0        | 488,849.89  |
| Arbitrum    | layer2-20 \$L2   | claim     | 0.03           | 40.12     | 18.83     | 34.77     | 0.57     | 500.85      |
| Base        | layer2-20 \$L2   | claim     | 0.0016         | 1.03      | 8.27      | 0.02      | 0        | 2,199.20    |
| Ethereum    | erc-20 nodes     | mint      | 0.19           | 176.70    | 7,015.97  | 99.32     | 0.01     | 1,351,757.78|
| Optimism    | layer2-20 \$L2   | claim     | 0.0009         | 0.78      | 3.04      | 0.11      | 0        | 1,617.84    |
| ZKsync Era  | zrc-20 sync      | mint      | 88.86          | 12,684.59 | 3,795.42  | 12,748.95 | 0        | 1,097,718.16|
| ZKsync Era  | era-20 bgnt      | mint      | 11.31          | 7,114.49  | 2,525.91  | 6,292.83  | 0.32     | 244,836.15  |
| ZKsync Era  | era-20 bgnt      | list      | 0.015          | 4,839.49  | 9,528.53  | 272.57    | 0        | 60,807.70   |
| ZKsync Era  | layer2-20 \$L2   | claim     | 0.017          | 29.63     | 6.90      | 28.38     | 0.42     | 2,001.14    |


## Ask a Question

---

* For reporting bugs please use the [research-inscriptions-boom/issues](https://github.com/johnnatan-messias/research-inscriptions-boom/issues) page.


## License

---

If you find it useful, please consider citing our academic peer-reviewed paper:

```
@inproceedings{Messias@CAAW25,
  author = {Johnnatan Messias and Krzysztof Gogol and Maria Inês Silva and Benjamin Livshits},
  title = {{The Writing is on the Wall: Analyzing the Boom of Inscriptions and its Impact on EVM-compatible Blockchains}},
  booktitle = {Proceedings of the 4th International Workshop on Cryptoasset Analytics (CAAW)},
  month = {April},
  year = {2025}
}
```