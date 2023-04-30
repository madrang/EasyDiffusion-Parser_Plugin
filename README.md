# EasyDiffusion-Parser_Plugin

Steps to use the parser plugin:

1. If it's missing, create a directory called 'server' inside the 'plugins' folder. For e.g. `D:\stable-diffusion-ui\plugins\server`.
2. Download the plugin from https://github.com/madrang/EasyDiffusion-Parser_Plugin/archive/refs/heads/main.zip.
3. Unzip and extract the files inside a new folder `plugins\server\parser_plugin` so it's like the following:

```
D:\stable-diffusion-ui\plugins\server\parser_plugin\.gitignore
D:\stable-diffusion-ui\plugins\server\parser_plugin\__init__.py
D:\stable-diffusion-ui\plugins\server\parser_plugin\prompt_parser.py
D:\stable-diffusion-ui\plugins\server\parser_plugin\README.md
D:\stable-diffusion-ui\plugins\server\parser_plugin\tokenizer_conditionings.py
```

Restart the program. It'll start using the new parser. You'll still need to start your prompts with an exclamation mark, e.g. `!photo of an (astronaut)` to use the advanced syntax. Without `!` it will send the text literally to the model.
