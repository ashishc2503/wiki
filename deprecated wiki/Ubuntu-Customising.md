# Customising Ubuntu

This tutorial shows you how to add aliases to the terminal, tweaking unity and removing pre-installed bloatware.

## Steps:

### Removing Bloatware

To remove all pre-installed bloatware because of privacy concerns or to keep your operating system minimal, checkout [this](https://gist.github.com/ansell/61313400e26cd42289f8) gist.

### Aliases

You can create a temporary alias like this:

```bash
alias alias_name="command_to_run"
```

However, when you close your shell session, this alias will cease to exist.

To create a permanent alias you will need to create the `~/.bash_aliases` file using the command `touch ~/.bash_aliases`. Once you've opened this file with your text editor of choice, add a line at the bottom of the document, similar to the example above.

To find out more, DigitalOcean has a great tutorial that can be found [here](https://www.digitalocean.com/community/tutorials/an-introduction-to-useful-bash-aliases-and-functions).

### Unity Tweak Tool

The Unity Tweak Tool provides users with tons of configuration options for tweaking the Unity Desktop.

To install the Unity Tweak Tool type `sudo apt install unity-tweak-tool`, and to launch it, `unity-tweak-tool`.

[Here](http://www.techrepublic.com/blog/linux-and-open-source/six-must-have-ubuntu-unity-tweaks/) is a list of the six must-have Ubuntu Unity Tweaks.

:point_left: Previous | :book: Home :book: |  Next :point_right:
:---|:---:|---:
 [**Download and Install Ubuntu Desktop**](Ubuntu-Download-and-Install) | [**Table of Contents**](Setting-Up-Ubuntu-For-Programming) | [**Jazzing up the Terminal**](Ubuntu-Jazzing-up-the-Terminal)
