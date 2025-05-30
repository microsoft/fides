# Securing AI Agents with Information-Flow Control

This repository contains a Jupyter notebook to accompany the academic paper "Securing AI Agents with Information-Flow Control".
The notebook is structured as a tutorial to walk readers through the concepts introduced in the paper.
This illustrates a practical implementation of mechanisms to deterministically enforce security policies in agentic tasks and grounds the concepts into executable code that readers can experiment with.

## Setup Instructions

The notebook has been tested against GPT-4o and GPT-4.1 using the Azure OpenAI Chat Completions API, but could be easily adapted to use an OpenAI endpoint instead.
The code sets up the model endpoint in the client using a `.env` configuration file containing definitions for `AZURE_ENDPOINT`, `API_VERSION` and `AZURE_DEPLOYMENT`.
Please copy the provided `.env.example` file to `.env` and edit as appropriate.
The notebook authenticates to the Azure OpenAI Service using Microsoft Entra ID, but could be simply adapted to use key-based authentication if preferred.

For convenience, we provide a fully-evaluated notebook to illustrate the intended output, but we encourage readers to set up their own endpoint to experiment hands-on and reproduce our the outputs.

## Citation

If you use wish to cite this work, please cite it as follows

```BibTeX
@misc{securing_ai_agents_with_ifc,
  title         = {Securing {AI} Agents with Information-Flow Control},
  author        = {Costa, Manuel and 
                   K{\"o}pf, Boris and 
                   Kolluri, Aashish and 
                   Paverd, Andrew and 
                   Russinovich, Mark and 
                   Salem, Ahmed and 
                   Tople, Shruti and 
                   Wutschitz, Lukas and 
                   Zanella-B{\'e}guelin, Santiago},
  year          = {2025},
  eprint        = {2505.23643},
  archivePrefix = {arXiv},
  primaryClass  = {cs.CR},
  doi           = {10.48550/arXiv.2505.23643}
}
```

## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit [Contributor License Agreements](https://cla.opensource.microsoft.com).

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

## Trademarks

This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft
trademarks or logos is subject to and must follow
[Microsoft's Trademark & Brand Guidelines](https://www.microsoft.com/legal/intellectualproperty/trademarks/usage/general).
Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship.
Any use of third-party trademarks or logos are subject to those third-party's policies.