# Monorepo
## Installation

Activate `venv`

```shell
. venv/bin/activate
```

Install dependencies

```shell
pip3 install -r requirements.txt
```

## Adding packages

Activate `venv`

```shell
. venv/bin/activate
```

Upgrade `pip3`

```shell
pip3 install --upgrade pip
```

Install your package

```shell
pip3 install <package-name>
```

Freeze

```shell
pip3 freeze > requirements.txt
```

## Useful Nikola commands
TODO: Put this in website README

Initialize a site

```shell
nikola init <website-dir>
```

Create new post (already in website-dir)

```shell
nikola new_post -e -f markdown
```

Build the website

```shell
nikola build
```

Development

```shell
nikola auto --browser
```







## Installation

1. create python virtual env
python3 -m venv venv

2. Activate

. venv/bin/activate
. venv/bin/activate.fish
pip3 install --upgrade pip

3. Install jupyter

ipython kernel install --user --name=.venv
pip3 install nbconvert

4. Run jupyter

5. From the top right, select New and choose .venv kernel

jupyter nbconvert --to html someshit.ipynb




## For pelican

1. activate venv

2. pip3 install "pelican[markdown]"

3. start

pelican-quickstart

## For Nikola

pip3 install "Nikola[extras]"





## Github pages

1. Follow this
https://docs.github.com/en/pages/quickstart

2. Wait 10 minutes

3. Visit Exegetech.github.io


## TODO

How to run jupyter markdown from venv?

To freeze

pip3 freeze > requirements.txt

To install

pip3 install -r requirements.txt
