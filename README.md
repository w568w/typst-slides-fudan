**Language**: \[English\] [\[简体中文\]](README.zh-CN.md)

# Fudan Theme for Typst Slides
This project is a [Typst](https://typst.app/) slide template based on the [Polylux](https://andreaskroepelin.github.io/polylux/book/polylux.html) library and its official theme [Clean](https://github.com/andreasKroepelin/polylux/blob/9184eeff02c5d03368b21024486ad2a2b8f65e0c/themes/clean.typ).

## Preview
![Preview 1](images/demo-1.png)
![Preview 2](images/demo-2.png)
![Preview 3](images/demo-3.png)
![Preview 4](images/demo-4.png)
![Preview 5](images/demo-5.png)
![Preview 6](images/demo-6.png)

## Usage
### 1. Install Typst
Please refer to the [official documentation](https://github.com/typst/typst) to install Typst.

### 2. Download and import the template

If you use the `typst` command line tool, clone this repository:

```shell
# If you have installed Git:
git clone https://github.com/w568w/typst-slides-fudan.git
# Or, if you have installed GitHub CLI:
gh repo clone w568w/typst-slides-fudan
# Or, if you have configured Git over SSH:
git clone git@github.com:w568w/typst-slides-fudan.git
```

Additionally, you can click the `Code` button on the repository page, and then click `Download ZIP` to download a compressed version of this repository, and unzip it to use.

It is strongly recommended that you start with `demo.typ`, which is a simple example that demonstrates all the features of this template.

> **Note**
>
> Since `demo.typ` references the libraries and themes in the `themes` directory, please do NOT move `demo.typ` to other directories, otherwise Typst will fail to compile. However, the file name can be changed at will.

## To-do list
Check the [Chinese version](README.zh-CN.md) for more details.

## License
All code and documents in this repository are released under the [GNU General Public License v3.0](LICENSE).