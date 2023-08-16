# Jupyter datascience Dev Container template

🚀 Get started with a Jupyter datascience template

<p align=center>
  <img src="">
</p>

## Usage

![Codespaces](https://img.shields.io/static/v1?style=for-the-badge&message=Codespaces&color=181717&logo=GitHub&logoColor=FFFFFF&label=)
![Devcontainers](https://img.shields.io/static/v1?style=for-the-badge&message=Devcontainers&color=2496ED&logo=Docker&logoColor=FFFFFF&label=)

After creating a GitHub Codespace (or a devcontainer in VS Code), open the
Command Palette to find the <kbd>Dev Containers: Add Dev Container Configuration
Files...</kbd> command. After you run it, VS Code will guide you through the
creation of a `.devcontainer/devcontainer.json` file!

Make sure you click the <kbd>Show All Definitions...</kbd> option to see our
unofficial templates!

### Choosing a base image

You can choose from many base images to tailor the container to your project's needs.
If you don't know what this means, that's OK! Just choose the `datascience-notebook` option.
It has many packages for data science from the Julia, Python, and R communities. 🚀

📚 You can learn more about what each of these base images is and what features each of them
in [the Jupyter Docker Stacks reference page].

### Default command

The default command of the base image is set to start the Jupyter server.
If you do not use the Jupyter server, comment out `"overrideCommand": false` of the devcontainer.json.

## Credits

This template was originally created by [@nathancarter]
and other contributors in the [microsoft/vscode-dev-containers] repository.
It has since landed here. 🌠

<!-- prettier-ignore-start -->
[@nathancarter]: https://github.com/nathancarter
[the Jupyter Docker Stacks reference page]: https://jupyter-docker-stacks.readthedocs.io/en/latest/using/selecting.html
[microsoft/vscode-dev-containers]: https://github.com/microsoft/vscode-dev-containers
<!-- prettier-ignore-end -->
