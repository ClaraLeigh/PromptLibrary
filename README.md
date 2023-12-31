# Prompt Library for LibreChat

This repository contains a collection of GPT prompts that can be used in LibreChat, an open-source alternative to ChatGPT. It is recommended to include this library in LibreChat using Git, this allows you to pull in changes and store your own prompts in a similar method. 

Please be aware that prompts in this library are not limited to a single source and include contributions from various projects. See the [References](#references) area for a list of where these prompts originate. Please be aware they may have been modified or improved upon based on experience.

## Installation

To include this prompts library in the external project "LibreChat" using Git, follow these steps:

1. Navigate to the root folder of your "LibreChat" project.
2. Add this repository as a subdirectory by running the following command:

   ```shell
   git clone git@github.com:ClaraLeigh/PromptLibrary.git prompts/General-Library
   ```

   This will clone the prompts library repository under the `/prompts/General-Library` folder of your "LibreChat" project.

Alternatively you can always download a zip of the repository and extract it into the `/prompts/General-Library` folder of your "LibreChat" project.

## Updating

To update the prompts library in your "LibreChat" project, follow these steps:

1. Navigate to the `/prompts/General-Library` folder of your "LibreChat" project.
2. Pull the latest changes from the prompts library repository by running the following command:

   ```shell
   git pull
   ```

## Contributing

We welcome contributions to the GPT Prompts Library for LibreChat! If you have new prompts or want to improve the existing ones, please follow these steps:

1. Fork this repository.
2. Create a new branch for your contribution.
3. Create a folder for the prompts if one does not already exist.
4. Make the necessary changes and commit them.
5. Push your branch to your forked repository.
6. Submit a pull request to the main repository.

Your contribution will be reviewed, and once accepted, it will be merged into the main library for others to use.

## References

- [LibreChat](https://github.com/danny-avila/LibreChat/): The main repository of LibreChat, an open-source version of ChatGPT.
- [AwesomePrompts](https://github.com/f/awesome-chatgpt-prompts): A major source of prompts for this library.

## Legal

### About

The authors of this repository is not accountable for any misuse of content within this library. Prompts may be offensive or unsuitable for certain audiences, and usage of these prompts may contravene the terms of the service you are using by third party providers. By using any content of this repo, you assume all responsibility. The author is not liable for the inclusion of prompts from third-party sources and will remove them upon request.

### Removal of Prompts

If you are the author of a prompt and would like it removed from this library, please follow these steps:

1. Open an issue in this repository.
2. Provide the name of the prompt and the reason for removal.
3. Include a link to the original source of the prompt and any relevant licensing.
4. The prompt will be removed from the library upon review.

### License

This Prompts Library for LibreChat is licensed under the [Creative Commons - CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/) license. The Terms of the service you are using. By using anything included in this repo, you are taking full responsibly for your actions. The author is also not responsible for the inclusion of prompts from other sources, and will remove them upon request.
