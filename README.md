# Pelican Blog Template

This Pelican blog template is ready-to-use and provides you with a simple, lightweight, and flexible way to build your static website.
It's an easy-to-customize Pelican website skeleton that includes a set of files and directories to help you get started with Pelican quickly.

## Installation

To install Pelican-template, you can clone this repository using git:

```sh
git clone https://github.com/code-wizardry/pelican-template.git
```

Alternatively, you can download the repository as a ZIP file and extract it to your local machine.

## Getting Started

Once you have downloaded or cloned the repository, navigate to the root directory of the project and install the required dependencies using pip:

```sh
pip install -r requirements.txt
```

After that, you can generate the site by running the following command:

```sh
pelican content -s pelicanconf.py
```

This command will generate the site in the output directory.

You can customize the look and feel of your site by modifying the templates and stylesheets in the theme directory. You can also add or edit your content by modifying the files in the content directory.

## Deploying Your Site

To deploy your Pelican site to a web server, you can simply upload the contents of the output directory to your web server using FTP or SCP. Alternatively, you can use a hosting provider that supports static site hosting, such as GitHub Pages, Netlify, or Google Cloud Storage.

## License

This code is released under the MIT License.
