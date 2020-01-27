# twitter-bootstrap-sass-demo
A repository for demonstrating what a CSS framwork can give of the box. Further I investigate how to use the SASS version of the framwork.
A short description of how to setup the environment is also listed.

## Getting started
Start by installing the npm which is the package manager that I have decided to use in order to download and install the different tools and frameworks needed.
NPM is widely used and therefore the choice felt natrul.

* Instal npm by clicking the following link: https://nodejs.org/dist/v12.14.1/node-v12.14.1-x64.msi 
  * npm is a package-manager
* Open your favorite command prompt and verify that npm is installed by typing ***npm --version***

Now we need to install Sass in order to be able to compile the ***.scss*** files to ***.css*** that the browsers understands.
* Run ***npm install -g sass*** which installs sass compiler globally

Now it is time to download bootstrap
* Run ***npm install bootstrap*** which installs/downloads bootstrap in the latest version currently 4.4.1
* Create a folder called sass and copy the files from the folder ***node_modules/bootstrap/sass***.
  * The ***LICENSE***, ***README.md*** and ***package.json*** are not needed.