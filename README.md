<p align="center">
  <a href="https://github.com/mpieczaba/civic">
    <img alt="Civic" height="125" src="https://raw.githubusercontent.com/mpieczaba/civic/main/assets/logo.png">
  </a>
</p>

# civic 🚙
**CV/resume generator built on top of [Zola](https://www.getzola.org/)**

## 🚀 Running the preview
1. Make sure that you have installed [Zola](https://www.getzola.org/).
2. Clone this repository:
```shell
$ git clone https://github.com/mpieczaba/civic && cd civic
```
3. Fulfill `content/cv.toml` with your data.
4. Run the Zola server:
```shell
$ zola serve
```

## 🤖 Deploying your CV/resume as a static website
1. Make sure that `config.toml` contains your website's url
2. Build static website with Zola:
```shell
$ zola build
```
3. Copy the `public` directory to your server.

## 🔥 Features
- Generating CV/resume as a static website
- Printing/saving to PDF
- ~~Changing colors/theme~~

## 👽 Examples
Example `cv.toml` file is already in `content` directory for presentation purposes.

Example PDF file can be found [there](https://raw.githubusercontent.com/mpieczaba/civic/main/assets/Civic.pdf).