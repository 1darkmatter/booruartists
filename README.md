# BooruArtists

**BooruArtists** is a lightweight tool designed for creating and managing text-based wildcards for use with Stable Diffusion WebUI and ComfyUI. This tool streamlines the process of handling artist metadata, generating dynamic prompts, and facilitating creative workflows. Specifically optimized for `Illustrious-XL`, it supports seamless integration with both Stable Diffusion's wildcard extension and ComfyUI's ImpactWildcard extension.

---

## Features

- **Wildcard Management**: Easily create, edit, and organize wildcard files for use with Stable Diffusion WebUI and ComfyUI.
- **Dynamic Prompting**: Enable more varied and creative generations through text wildcards.
- **Customizable Workflows**: Optimized for integration with Stable Diffusion models like `Illustrious-XL` and ComfyUI pipelines.
- **Streamlined Workflow**: Minimal setup and lightweight implementation for high performance.

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/1darkmatter/booruartists.git
   ```
2. Navigate to the project directory:
   ```bash
   cd booruartists
   ```

### For Stable Diffusion WebUI

1. Install the Stable Diffusion WebUI Wildcards extension (if not already installed):
   - Open the Extensions tab in your WebUI.
   - Go to the "Install from URL" section.
   - Enter the URL for the Wildcards extension: `https://github.com/AUTOMATIC1111/stable-diffusion-webui-wildcards`
   - Click "Install" and restart the WebUI.

2. Copy or symlink your wildcard files:
   - Place your wildcard files from BooruArtists into the appropriate `wildcards/` directory used by the extension.

### For ComfyUI

1. Install the ComfyUI ImpactWildcard extension:
   - Follow the tutorial: [ImpactWildcard Documentation](https://github.com/ltdrdata/ComfyUI-extension-tutorials/blob/Main/ComfyUI-Impact-Pack/tutorial/ImpactWildcard.md)

2. Place your wildcard files in the designated directory used by the ImpactWildcard extension.

---

## Usage

### Creating Wildcards

1. **Generate Wildcards:**
   - Edit or create wildcard files within the repository's `wildcards/` directory.
   - Each line in a wildcard file represents a possible replacement for the wildcard tag.

2. **Use in Prompts:**
   - Reference wildcards in your prompts using the syntax:
     ```
     __wildcard_name__
     ```
   - For example, if you have a wildcard file named `artists.txt`, use `__artists__` in your prompt.

### Examples

- **Basic Prompt Example:**
  ```
  A portrait of a __artists__, in a futuristic style.
  ```

- **Dynamic Outputs:**
  Using the wildcard, the tool will randomly select a value from the `artists.txt` file.

---

## License

This project is licensed under the [MIT License](LICENSE).

---

## Acknowledgements

- Inspired by the art community and tailored for `Illustrious-XL`.
- Special thanks to contributors and the developers of the Stable Diffusion WebUI Wildcards and ComfyUI ImpactWildcard extensions.

---

## Contact

For questions or suggestions, feel free to open an issue or reach out via GitHub.

---

2025 © 1darkmatter // Midnight1111 - CC BY-NC 4.0
