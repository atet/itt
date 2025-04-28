# [atet](https://github.com/atet) / [**_itt_**](https://github.com/atet/itt/blob/main/README.md#atet--itt)

[![.img/itt_logo.png](.img/itt_logo.png)](#nolink)

# Images to Text

We're going to extract text-based meaning out of images here in <u><b>10 easy steps and less than 10 minutes</b></u>:

- Downloading and deploying a Python development environment
- Signing up for free access to Google language model API
- Code snippet to convert images to clean text

*This tutorial was developed in Windows 10 and will likely work with some minor changes in Windows 11, MacOS, and Linux.*

If you're looking to make images from text, see my quick tutorial here: [🚧 Under Construction 🚧](https://github.com/atet/tti)

----------------------------------------------------------------------------

## Standalone Python Environment

1. Set up Docker if you haven't already: [My Quick Linux+Docker for Windows Tutorial](https://github.com/atet/wsl)
2. Download and deploy a Python development environment with JupyterLab: [My One-Step JupyterLab for Windows Tutorial](https://github.com/atet/python)

[Back to Top](#table-of-contents)

----------------------------------------------------------------------------

## Free Google AI Studio API Key

3. Follow the instructions here for only the `Google Gemini Access` section to get an API key: [Getting started with free LLMs](https://github.com/atet/copilot?tab=readme-ov-file#google-gemini-access)
4. Copy down your new API key and **do not share it with anyone else**, paste it in the code snippet below where you see `<YOUR_GOOGLE_API_KEY>`

[Back to Top](#table-of-contents)

----------------------------------------------------------------------------

## Dependencies

5. With your new JupyterLab container up and running, access its terminal through your local Windows WSL terminal (i.e., `docker exec` into the container that we named `jupyterlab` in the instructions from the other tutorial):

```bash
$ docker exec -it jupyterlab /bin/bash
(base) jovyan@jupyterlab:~$ _
```

6. Install the Google `genai` Python library:

```bash
(base) jovyan@jupyterlab:~$ pip install google-genai
.
.
.
Successfully installed...
```

[Back to Top](#table-of-contents)

----------------------------------------------------------------------------

## Test Image

7. Right-click and save this image of a hand-written address to your desktop:

    [![.img/address.jpeg](.img/address.jpeg)](#nolink)

8. Note the location of where you saved this image and paste it in the code snippet below where you see `<IMAGE_FILEPATH>`

[Back to Top](#table-of-contents)

----------------------------------------------------------------------------

## Python Code

9. Log into your Docker JupyterLab environment from a web browser at `localhost:8888` and use the word "`token`" as the password/token:

    [![.img/itt_fig1_jupyterlab_login.jpeg](.img/itt_fig1_jupyterlab_login.jpeg)](#nolink)

10. Start a Jupyter Notebook, copy+paste the following code into the notebook, and run it:

```bash

```

[Back to Top](#table-of-contents)

----------------------------------------------------------------------------

## Next Steps

Wow, all that in just a few minutes of learning how to convert images into text:



Now you can try some other images and ask for various things like:
- Why is this meme funny?
- Describe the image in great detail.
- What do you think happened to result in this picture?

[Back to Top](#table-of-contents)

----------------------------------------------------------------------------

## Other Resources

**Description** | **URL Link**
--- | ---
Google `genai` Python library documentation | https://pypi.org/project/google-genai/

[Back to Top](#table-of-contents)

----------------------------------------------------------------------------

## Troubleshooting

Issue | Solution
--- | ---
**"It's not working!"** | This concise tutorial has distilled hours of sweat, tears, and troubleshooting; _it can't not work_

[Back to Top](#table-of-contents)

----------------------------------------------------------------------------

<p align="center">Copyright © 2025-∞ Athit Kao, <a href="http://www.athitkao.com/tos.html" target="_blank">Terms and Conditions</a></p>