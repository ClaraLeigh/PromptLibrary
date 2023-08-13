# Prompt Library for LibreChat

This repository contains a collection of GPT prompts that can be used in LibreChat, an open-source alternative to ChatGPT. It is recommended to include this library in LibreChat using Git Submodules, this allows you to pull in changes and store your own prompts in a similar method. 

Please be aware that prompts in this library are not limited to a single source and include contributions from various projects. See the [References](#References) area for a list of where these prompts originate. Please be aware they may have been modified or improved upon based on experience.

## Installation

To include this prompts library in the external project "LibreChat" using Git Submodules, follow these steps:

1. Navigate to the root folder of your "LibreChat" project.
2. Add this repository as a submodule by running the following command:

   ```shell
   git submodule add git@github.com:ClaraLeigh/PromptLibrary.git prompts/General-Library
   ```

   This will clone the prompts library repository under the `/prompts/General-Library` folder of your "LibreChat" project.

## Usage

Once you have included the prompts library as a submodule in your "LibreChat" project, you can access the prompts from the `/prompts/General-Library` folder. Incorporate the prompts into the ChatGPT functionality of LibreChat according to your implementation.

Please note that this prompts library not only includes prompts from [AwesomePrompts](https://github.com/f/awesome-chatgpt-prompts), but also from other sources, making it a comprehensive collection of GPT prompts for LibreChat.

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

## License

This GPT Prompts Library for LibreChat is licensed under the [Creative Commons - CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/) license.