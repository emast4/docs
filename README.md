# Prior Labs Docs

Welcome to the **Prior Labs documentation repository!**
This repo contains the source files for [docs.priorlabs.ai](https://docs.priorlabs.ai), powered by [Mintlify](https://mintlify.com).

## About Prior Labs

**Prior Labs** develops foundation models for tabular data. Our flagship model, **TabPFN**, provides a pre-trained option for structured datasets when retraining a model for every task is impractical.
TabPFN is trained on large collections of synthetic datasets so that it can reuse statistical patterns across problems. Instead of optimizing weights for every new dataset, it encodes inductive biases, priors, and optimization strategies that traditional models must rediscover each time. When you run it on your data, TabPFN performs zero-shot inference by using the provided context window to generate predictions in a single forward pass.

## Getting Started

To view or edit the documentation locally:

### Prerequisites

* [Node.js](https://nodejs.org/) (version 18 or higher)
* [Mintlify CLI](https://mintlify.com/docs/cli)

### Installation

```bash
npm install -g mintlify
# or
yarn global add mintlify
```

Clone this repository and start the Mintlify dev server:

```bash
git clone https://github.com/priorlabs/docs.git
cd docs
mintlify dev
```

Then open **[http://localhost:3000](http://localhost:3000)** in your browser to preview the docs.

## Contributing 🤝

We welcome contributions to improve the Prior Labs documentation!

* Open an **issue** for feedback, bugs, or suggestions.
* Submit a **pull request** with edits or new content.
* Keep writing **clear, concise, and consistent** with the existing style.
* Always test your changes locally before submitting.

## Contact

For questions or support, reach us at **[hello@priorlabs.ai](mailto:hello@priorlabs.ai)** or via our official [Discord server](https://discord.com/invite/VJRuU3bSxt).
Learn more at [priorlabs.ai](https://priorlabs.ai).