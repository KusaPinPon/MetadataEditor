# Metadata Editor

This tool allows you to edit image metadata, such as checkpoints, LORAs. So far windows only, working on more options.
![Image of the UI](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/dfe6ce9f-755d-461a-86fc-ca352174d9a2/width=525/dfe6ce9f-755d-461a-86fc-ca352174d9a2.jpeg) 

1. Clone or download the repo
2. Install the libraris with `pip install -r /path/to/requirements.txt.` There are just two, so I don't think you would need a virtual environment
3. Run `pyton main_ui.py`


## Features

- **Image Preview:** Load and preview images for metadata editing.
- **Metadata Extraction:** Extract existing metadata from PNG/JPG images.
- **LORA Management:** Add, remove, and edit multiple LORAs and their hashes for proper metadata formatting.
- **Civitai-Compatible Metadata:** Insert metadata in a format that Civitai recognizes, including prompts, samplers, and more.
- **Model Selection:** Select a model file, and the tool automatically extracts its hash and name.
- **Editable Metadata Preview:** See the full metadata structure and modify it if necessary.
