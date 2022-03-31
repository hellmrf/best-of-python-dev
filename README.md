<!-- markdownlint-disable -->
<h1 align="center">
    Best-of Python Developer Tools
    <br>
</h1>

<p align="center">
    <strong>🏆&nbsp; A ranked list of awesome python developer tools and libraries. Updated weekly.</strong>
</p>

<p align="center">
    <a href="https://best-of.org" title="Best-of Badge"><img src="http://bit.ly/3o3EHNN"></a>
    <a href="#Contents" title="Project Count"><img src="https://img.shields.io/badge/projects-260-blue.svg?color=5ac4bf"></a>
    <a href="#Contribution" title="Contributions are welcome"><img src="https://img.shields.io/badge/contributions-welcome-green.svg"></a>
    <a href="https://github.com/ml-tooling/best-of-python-dev/releases" title="Best-of Updates"><img src="https://img.shields.io/github/release-date/ml-tooling/best-of-python-dev?color=green&label=updated"></a>
    <a href="https://mltooling.substack.com/subscribe" title="Subscribe to newsletter"><img src="http://bit.ly/2Md9rxM"></a>
    <a href="https://twitter.com/mltooling" title="Follow on Twitter"><img src="https://img.shields.io/twitter/follow/mltooling.svg?style=social&label=Follow"></a>
</p>

This curated list contains 260 awesome open-source projects with a total of 680K stars grouped into 15 categories. All projects are ranked by a project-quality score, which is calculated based on various metrics automatically collected from GitHub and different package managers. If you like to add or update projects, feel free to open an [issue](https://github.com/ml-tooling/best-of-python-dev/issues/new/choose), submit a [pull request](https://github.com/ml-tooling/best-of-python-dev/pulls), or directly edit the [projects.yaml](https://github.com/ml-tooling/best-of-python-dev/edit/main/projects.yaml). Contributions are very welcome!

---

<p align="center">
     🧙‍♂️&nbsp; Discover other <a href="https://best-of.org">best-of lists</a> or create <a href="https://github.com/best-of-lists/best-of/blob/main/create-best-of-list.md">your own</a>.<br>
    📫&nbsp; Subscribe to our <a href="https://mltooling.substack.com/subscribe">newsletter</a> for updates and trending projects.
</p>

---


## Contents

- [Linters & Style Checkers](#linters--style-checkers) _42 projects_
- [Code Formatters](#code-formatters) _6 projects_
- [Code Refactoring](#code-refactoring) _18 projects_
- [Code Security](#code-security) _8 projects_
- [Virtual Environments](#virtual-environments) _8 projects_
- [Dependency & Package Mangers](#dependency--package-mangers) _10 projects_
- [Code Metrics & Complexity](#code-metrics--complexity) _6 projects_
- [Logging](#logging) _21 projects_
- [Documentation](#documentation) _27 projects_
- [Debugging Tools](#debugging-tools) _13 projects_
- [Testing Tools](#testing-tools) _43 projects_
- [Code Packaging](#code-packaging) _16 projects_
- [Build Tools](#build-tools) _14 projects_
- [System Monitoring & Profiling](#system-monitoring--profiling) _17 projects_
- [AST Tools](#ast-tools) _5 projects_
- [Others](#others) _1 projects_

## Explanation
- 🥇🥈🥉&nbsp; Combined project-quality score
- ⭐️&nbsp; Star count from GitHub
- 🐣&nbsp; New project _(less than 6 months old)_
- 💤&nbsp; Inactive project _(6 months no activity)_
- 💀&nbsp; Dead project _(12 months no activity)_
- 📈📉&nbsp; Project is trending up or down
- ➕&nbsp; Project was recently added
- ❗️&nbsp; Warning _(e.g. missing/risky license)_
- 👨‍💻&nbsp; Contributors count from GitHub
- 🔀&nbsp; Fork count from GitHub
- 📋&nbsp; Issue count from GitHub
- ⏱️&nbsp; Last update timestamp on package manager
- 📥&nbsp; Download count from package manager
- 📦&nbsp; Number of dependent projects
- <img src="https://cdn.iconscout.com/icon/free/png-256/8-eight-digital-number-numerical-numbers-36025.png" style="display:inline;" width="13" height="13">&nbsp; Flake8 related project
- <img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13">&nbsp; Pytest related project
- <img src="https://www.pylint.org/ico/favicon.ico" style="display:inline;" width="13" height="13">&nbsp; Pylint related project
- <img src="https://www.sphinx-doc.org/en/master/_static/favicon.svg" style="display:inline;" width="13" height="13">&nbsp; Sphinx related project
- <img src="https://squidfunk.github.io/mkdocs-material/assets/favicon.png" style="display:inline;" width="13" height="13">&nbsp; MkDocs related project

<br>

## Linters & Style Checkers

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/python/mypy">mypy</a></b> (🥇42 ·  ⭐ 13K) - Optional static typing for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/python/mypy) (👨‍💻 560 · 🔀 2.1K · 📦 68K · 📋 7.6K - 28% open · ⏱️ 31.03.2022):

	```
	git clone https://github.com/python/mypy
	```
- [PyPi](https://pypi.org/project/mypy) (📥 11M / month · 📦 5.8K · ⏱️ 24.03.2022):
	```
	pip install mypy
	```
- [Conda](https://anaconda.org/conda-forge/mypy) (📥 1.7M · ⏱️ 24.03.2022):
	```
	conda install -c conda-forge mypy
	```
</details>
<details><summary><b><a href="https://github.com/PyCQA/flake8">flake8</a></b> (🥇41 ·  ⭐ 1.9K) - Flake8 is a wrapper around these tools: PyFlakes; pycodestyle; Ned.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/PyCQA/flake8) (👨‍💻 160 · 🔀 190 · 📦 240K · 📋 1.4K - 2% open · ⏱️ 28.03.2022):

	```
	git clone https://github.com/PyCQA/flake8
	```
- [PyPi](https://pypi.org/project/flake8) (📥 16M / month · 📦 41K · ⏱️ 11.10.2021):
	```
	pip install flake8
	```
- [Conda](https://anaconda.org/conda-forge/flake8) (📥 3.8M · ⏱️ 08.03.2022):
	```
	conda install -c conda-forge flake8
	```
</details>
<details><summary><b><a href="https://github.com/PyCQA/pylint">pylint</a></b> (🥇40 ·  ⭐ 3.9K) - Its not just a linter that annoys you!. <code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code></summary>

- [GitHub](https://github.com/PyCQA/pylint) (👨‍💻 440 · 🔀 820 · 📋 4.1K - 19% open · ⏱️ 31.03.2022):

	```
	git clone https://github.com/PyCQA/pylint
	```
- [PyPi](https://pypi.org/project/pylint) (📥 11M / month · 📦 21K · ⏱️ 31.03.2022):
	```
	pip install pylint
	```
- [Conda](https://anaconda.org/conda-forge/pylint) (📥 2.6M · ⏱️ 26.03.2022):
	```
	conda install -c conda-forge pylint
	```
</details>
<details><summary><b><a href="https://github.com/PyCQA/pycodestyle">pycodestyle</a></b> (🥇37 ·  ⭐ 4.5K) - Simple Python style checker in one Python file. <code><a href="https://tldrlegal.com/search?q=Saxpath">❗️Saxpath</a></code></summary>

- [GitHub](https://github.com/PyCQA/pycodestyle) (👨‍💻 130 · 🔀 610 · 📦 200K · 📋 670 - 16% open · ⏱️ 15.03.2022):

	```
	git clone https://github.com/PyCQA/pycodestyle
	```
- [PyPi](https://pypi.org/project/pycodestyle) (📥 23M / month · 📦 11K · ⏱️ 11.10.2021):
	```
	pip install pycodestyle
	```
- [Conda](https://anaconda.org/conda-forge/pycodestyle) (📥 4M · ⏱️ 11.10.2021):
	```
	conda install -c conda-forge pycodestyle
	```
</details>
<details><summary><b><a href="https://github.com/PyCQA/pyflakes">pyflakes</a></b> (🥇36 ·  ⭐ 1.1K) - A simple program which checks Python source files for errors. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/PyCQA/pyflakes) (👨‍💻 80 · 🔀 160 · 📦 130K · 📋 460 - 18% open · ⏱️ 25.03.2022):

	```
	git clone https://github.com/PyCQA/pyflakes
	```
- [PyPi](https://pypi.org/project/pyflakes) (📥 16M / month · 📦 14K · ⏱️ 06.10.2021):
	```
	pip install pyflakes
	```
- [Conda](https://anaconda.org/conda-forge/pyflakes) (📥 3.8M · ⏱️ 07.10.2021):
	```
	conda install -c conda-forge pyflakes
	```
</details>
<details><summary><b><a href="https://github.com/microsoft/pyright">pyright</a></b> (🥈35 ·  ⭐ 7.8K) - Static type checker for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/microsoft/pyright) (👨‍💻 74 · 🔀 430 · 📦 230 · 📋 2.7K - 0% open · ⏱️ 30.03.2022):

	```
	git clone https://github.com/Microsoft/pyright
	```
- [npm](https://www.npmjs.com/package/pyright) (📥 300K / month · 📦 3 · ⏱️ 30.03.2022):
	```
	npm install pyright
	```
</details>
<details><summary><b><a href="https://github.com/wemake-services/wemake-python-styleguide">wemake-python-styleguide</a></b> (🥈35 ·  ⭐ 1.8K) - The strictest and most opinionated python linter ever!. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/wemake-services/wemake-python-styleguide) (👨‍💻 160 · 🔀 330 · 📦 1.2K · 📋 1K - 8% open · ⏱️ 31.03.2022):

	```
	git clone https://github.com/wemake-services/wemake-python-styleguide
	```
- [PyPi](https://pypi.org/project/wemake-python-styleguide) (📥 120K / month · 📦 25 · ⏱️ 11.03.2022):
	```
	pip install wemake-python-styleguide
	```
</details>
<details><summary><b><a href="https://github.com/facebook/pyre-check">pyre-check</a></b> (🥈33 ·  ⭐ 5.8K) - Performant type-checking for python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/facebook/pyre-check) (👨‍💻 190 · 🔀 380 · 📋 310 - 30% open · ⏱️ 31.03.2022):

	```
	git clone https://github.com/facebook/pyre-check
	```
- [PyPi](https://pypi.org/project/pyre-check) (📥 39K / month · 📦 32 · ⏱️ 11.01.2022):
	```
	pip install pyre-check
	```
</details>
<details><summary><b><a href="https://github.com/google/pytype">pytype</a></b> (🥈33 ·  ⭐ 3.7K) - A static type analyzer for Python code. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/google/pytype) (👨‍💻 73 · 🔀 230 · 📋 510 - 20% open · ⏱️ 31.03.2022):

	```
	git clone https://github.com/google/pytype
	```
- [PyPi](https://pypi.org/project/pytype) (📥 140K / month · 📦 92 · ⏱️ 30.03.2022):
	```
	pip install pytype
	```
- [Conda](https://anaconda.org/conda-forge/pytype) (📥 69K · ⏱️ 30.03.2022):
	```
	conda install -c conda-forge pytype
	```
</details>
<details><summary><b><a href="https://github.com/davidhalter/parso">parso</a></b> (🥈32 ·  ⭐ 480) - A Python Parser. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/davidhalter/parso) (👨‍💻 44 · 🔀 82 · 📦 190K · 📋 100 - 6% open · ⏱️ 14.02.2022):

	```
	git clone https://github.com/davidhalter/parso
	```
- [PyPi](https://pypi.org/project/parso) (📥 15M / month · 📦 5.9K · ⏱️ 30.11.2021):
	```
	pip install parso
	```
- [Conda](https://anaconda.org/conda-forge/parso) (📥 6.8M · ⏱️ 01.12.2021):
	```
	conda install -c conda-forge parso
	```
</details>
<details><summary><b><a href="https://github.com/PyCQA/pydocstyle">pydocstyle</a></b> (🥈31 ·  ⭐ 870) - docstring style checker. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/PyCQA/pydocstyle) (👨‍💻 79 · 🔀 160 · 📥 56 · 📦 25K · 📋 290 - 29% open · ⏱️ 23.02.2022):

	```
	git clone https://github.com/PyCQA/pydocstyle
	```
- [PyPi](https://pypi.org/project/pydocstyle) (📥 2.2M / month · 📦 2.4K · ⏱️ 17.05.2021):
	```
	pip install pydocstyle
	```
- [Conda](https://anaconda.org/conda-forge/pydocstyle) (📥 580K · ⏱️ 18.05.2021):
	```
	conda install -c conda-forge pydocstyle
	```
</details>
<details><summary><b><a href="https://github.com/PyCQA/pylint-django">pylint-django</a></b> (🥈31 ·  ⭐ 500) - Pylint plugin for improving code analysis for when.. <code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code> <code><img src="https://www.pylint.org/ico/favicon.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PyCQA/pylint-django) (👨‍💻 64 · 🔀 110 · 📥 210 · 📦 17K · 📋 190 - 18% open · ⏱️ 25.03.2022):

	```
	git clone https://github.com/PyCQA/pylint-django
	```
- [PyPi](https://pypi.org/project/pylint-django) (📥 780K / month · 📦 1.2K · ⏱️ 25.03.2022):
	```
	pip install pylint-django
	```
- [Conda](https://anaconda.org/conda-forge/pylint-django) (📥 90K · ⏱️ 21.02.2022):
	```
	conda install -c conda-forge pylint-django
	```
</details>
<details><summary><b><a href="https://github.com/PyCQA/flake8-bugbear">flake8-bugbear</a></b> (🥈30 ·  ⭐ 710) - A plugin for Flake8 finding likely bugs and design problems.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://cdn.iconscout.com/icon/free/png-256/8-eight-digital-number-numerical-numbers-36025.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PyCQA/flake8-bugbear) (👨‍💻 53 · 🔀 61 · 📦 7.6K · 📋 130 - 27% open · ⏱️ 30.03.2022):

	```
	git clone https://github.com/PyCQA/flake8-bugbear
	```
- [PyPi](https://pypi.org/project/flake8-bugbear) (📥 1.5M / month · 📦 900 · ⏱️ 23.03.2022):
	```
	pip install flake8-bugbear
	```
- [Conda](https://anaconda.org/conda-forge/flake8-bugbear) (📥 560K · ⏱️ 24.03.2022):
	```
	conda install -c conda-forge flake8-bugbear
	```
</details>
<details><summary><b><a href="https://github.com/coala/coala">coala</a></b> (🥈29 ·  ⭐ 3.3K · 💤) - coala provides a unified command-line interface for linting and.. <code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code></summary>

- [GitHub](https://github.com/coala/coala) (👨‍💻 480 · 🔀 1.4K · 📥 150 · 📦 10 · 📋 3.2K - 26% open · ⏱️ 11.06.2021):

	```
	git clone https://github.com/coala/coala
	```
- [PyPi](https://pypi.org/project/coala-bears) (📥 19K / month · 📦 100 · ⏱️ 10.11.2017):
	```
	pip install coala-bears
	```
</details>
<details><summary><b><a href="https://github.com/klen/pylama">pylama</a></b> (🥈29 ·  ⭐ 870) - Code audit tool for python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/klen/pylama) (👨‍💻 48 · 🔀 91 · 📦 3.6K · 📋 130 - 28% open · ⏱️ 11.03.2022):

	```
	git clone https://github.com/klen/pylama
	```
- [PyPi](https://pypi.org/project/pylama) (📥 110K / month · 📦 590 · ⏱️ 11.03.2022):
	```
	pip install pylama
	```
</details>
<details><summary><b><a href="https://github.com/nipunn1313/mypy-protobuf">mypy-protobuf</a></b> (🥈28 ·  ⭐ 440) - open source tools to generate mypy stubs from protobufs. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/nipunn1313/mypy-protobuf) (👨‍💻 32 · 🔀 64 · 📋 100 - 5% open · ⏱️ 24.03.2022):

	```
	git clone https://github.com/dropbox/mypy-protobuf
	```
- [PyPi](https://pypi.org/project/mypy-protobuf) (📥 840K / month · 📦 50 · ⏱️ 23.01.2022):
	```
	pip install mypy-protobuf
	```
- [Conda](https://anaconda.org/conda-forge/mypy-protobuf) (📥 28K · ⏱️ 24.01.2022):
	```
	conda install -c conda-forge mypy-protobuf
	```
</details>
<details><summary><b><a href="https://github.com/openstack/hacking">hacking</a></b> (🥈28 ·  ⭐ 220) - OpenStack Hacking Style Checks. Mirror of code maintained at.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://cdn.iconscout.com/icon/free/png-256/8-eight-digital-number-numerical-numbers-36025.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/openstack/hacking) (👨‍💻 180 · 🔀 66 · ⏱️ 28.03.2022):

	```
	git clone https://github.com/openstack/hacking
	```
- [PyPi](https://pypi.org/project/hacking) (📥 240K / month · 📦 4.4K · ⏱️ 21.04.2021):
	```
	pip install hacking
	```
</details>
<details><summary><b><a href="https://github.com/terrencepreilly/darglint">darglint</a></b> (🥉27 ·  ⭐ 400) - A python documentation linter which checks that the docstring description.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/terrencepreilly/darglint) (👨‍💻 22 · 🔀 37 · 📦 2.1K · 📋 140 - 34% open · ⏱️ 18.10.2021):

	```
	git clone https://github.com/terrencepreilly/darglint
	```
- [PyPi](https://pypi.org/project/darglint) (📥 340K / month · 📦 53 · ⏱️ 18.10.2021):
	```
	pip install darglint
	```
- [Conda](https://anaconda.org/conda-forge/darglint) (📥 32K · ⏱️ 05.11.2021):
	```
	conda install -c conda-forge darglint
	```
</details>
<details><summary><b><a href="https://github.com/gforcada/flake8-isort">flake8-isort</a></b> (🥉27 ·  ⭐ 120) - flake8 plugin that integrates isort. <code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code> <code><img src="https://cdn.iconscout.com/icon/free/png-256/8-eight-digital-number-numerical-numbers-36025.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/gforcada/flake8-isort) (👨‍💻 32 · 🔀 44 · 📦 5.2K · 📋 52 - 21% open · ⏱️ 15.03.2022):

	```
	git clone https://github.com/gforcada/flake8-isort
	```
- [PyPi](https://pypi.org/project/flake8-isort) (📥 650K / month · 📦 610 · ⏱️ 14.10.2021):
	```
	pip install flake8-isort
	```
- [Conda](https://anaconda.org/conda-forge/flake8-isort) (📥 16K · ⏱️ 14.10.2021):
	```
	conda install -c conda-forge flake8-isort
	```
</details>
<details><summary><b><a href="https://github.com/adamchainz/flake8-comprehensions">flake8-comprehensions</a></b> (🥉26 ·  ⭐ 340) - A flake8 plugin to help you write better.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://cdn.iconscout.com/icon/free/png-256/8-eight-digital-number-numerical-numbers-36025.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/adamchainz/flake8-comprehensions) (👨‍💻 12 · 🔀 16 · 📋 42 - 19% open · ⏱️ 28.03.2022):

	```
	git clone https://github.com/adamchainz/flake8-comprehensions
	```
- [PyPi](https://pypi.org/project/flake8-comprehensions) (📥 710K / month · 📦 530 · ⏱️ 10.01.2022):
	```
	pip install flake8-comprehensions
	```
- [Conda](https://anaconda.org/conda-forge/flake8-comprehensions) (📥 520K · ⏱️ 10.01.2022):
	```
	conda install -c conda-forge flake8-comprehensions
	```
</details>
<details><summary><b><a href="https://github.com/zheller/flake8-quotes">flake8-quotes</a></b> (🥉26 ·  ⭐ 140) - Flake8 extension for checking quotes in python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://cdn.iconscout.com/icon/free/png-256/8-eight-digital-number-numerical-numbers-36025.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/zheller/flake8-quotes) (👨‍💻 30 · 🔀 33 · 📦 4.7K · 📋 43 - 6% open · ⏱️ 19.10.2021):

	```
	git clone https://github.com/zheller/flake8-quotes
	```
- [PyPi](https://pypi.org/project/flake8-quotes) (📥 650K / month · 📦 820 · ⏱️ 15.12.2021):
	```
	pip install flake8-quotes
	```
- [Conda](https://anaconda.org/conda-forge/flake8-quotes) (📥 600K · ⏱️ 19.10.2021):
	```
	conda install -c conda-forge flake8-quotes
	```
</details>
<details><summary><b><a href="https://github.com/beartype/beartype">beartype</a></b> (🥉25 ·  ⭐ 1.1K) - Unbearably fast O(1) runtime type-checking in pure Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/beartype/beartype) (👨‍💻 9 · 🔀 22 · 📋 89 - 16% open · ⏱️ 31.03.2022):

	```
	git clone https://github.com/beartype/beartype
	```
- [PyPi](https://pypi.org/project/beartype) (📥 89K / month · 📦 30 · ⏱️ 15.03.2022):
	```
	pip install beartype
	```
- [Conda](https://anaconda.org/conda-forge/beartype) (📥 11K · ⏱️ 15.03.2022):
	```
	conda install -c conda-forge beartype
	```
</details>
<details><summary><b><a href="https://github.com/mgedmin/check-manifest">check-manifest</a></b> (🥉25 ·  ⭐ 260) - Tool to check the completeness of MANIFEST.in for Python packages. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/mgedmin/check-manifest) (👨‍💻 20 · 🔀 33 · 📦 7.3K · 📋 92 - 20% open · ⏱️ 17.03.2022):

	```
	git clone https://github.com/mgedmin/check-manifest
	```
- [PyPi](https://pypi.org/project/check-manifest) (📥 180K / month · 📦 2.6K · ⏱️ 13.03.2022):
	```
	pip install check-manifest
	```
- [Conda](https://anaconda.org/conda-forge/check-manifest) (📥 41K · ⏱️ 13.03.2022):
	```
	conda install -c conda-forge check-manifest
	```
</details>
<details><summary><b><a href="https://github.com/wemake-services/flake8-eradicate">flake8-eradicate</a></b> (🥉24 ·  ⭐ 230) - Flake8 plugin to find commented out or dead code. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://cdn.iconscout.com/icon/free/png-256/8-eight-digital-number-numerical-numbers-36025.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/wemake-services/flake8-eradicate) (👨‍💻 13 · 🔀 6 · 📋 28 - 3% open · ⏱️ 25.03.2022):

	```
	git clone https://github.com/wemake-services/flake8-eradicate
	```
- [PyPi](https://pypi.org/project/flake8-eradicate) (📥 350K / month · 📦 65 · ⏱️ 19.10.2021):
	```
	pip install flake8-eradicate
	```
- [Conda](https://anaconda.org/conda-forge/flake8-eradicate) (📥 1.1K · ⏱️ 19.10.2021):
	```
	conda install -c conda-forge flake8-eradicate
	```
</details>
<details><summary><b><a href="https://github.com/PyCQA/flake8-commas">flake8-commas</a></b> (🥉24 ·  ⭐ 130) - Flake8 extension for enforcing trailing commas in python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://cdn.iconscout.com/icon/free/png-256/8-eight-digital-number-numerical-numbers-36025.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PyCQA/flake8-commas) (👨‍💻 12 · 🔀 23 · 📦 2.8K · 📋 31 - 16% open · ⏱️ 13.10.2021):

	```
	git clone https://github.com/PyCQA/flake8-commas
	```
- [PyPi](https://pypi.org/project/flake8-commas) (📥 310K / month · 📦 330 · ⏱️ 13.10.2021):
	```
	pip install flake8-commas
	```
</details>
<details><summary><b><a href="https://github.com/peterjc/flake8-black">flake8-black</a></b> (🥉24 ·  ⭐ 120) - flake8 plugin to run black for checking Python coding style. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://cdn.iconscout.com/icon/free/png-256/8-eight-digital-number-numerical-numbers-36025.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/peterjc/flake8-black) (👨‍💻 9 · 🔀 9 · 📦 2K · 📋 24 - 12% open · ⏱️ 18.03.2022):

	```
	git clone https://github.com/peterjc/flake8-black
	```
- [PyPi](https://pypi.org/project/flake8-black) (📥 570K / month · 📦 150 · ⏱️ 25.02.2022):
	```
	pip install flake8-black
	```
- [Conda](https://anaconda.org/conda-forge/flake8-black) (📥 220K · ⏱️ 25.02.2022):
	```
	conda install -c conda-forge flake8-black
	```
</details>
<details><summary><b><a href="https://github.com/tylerwince/flake8-bandit">flake8-bandit</a></b> (🥉23 ·  ⭐ 78 · 📈) - Automated security testing using bandit and flake8. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://cdn.iconscout.com/icon/free/png-256/8-eight-digital-number-numerical-numbers-36025.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tylerwince/flake8-bandit) (👨‍💻 8 · 🔀 22 · 📋 16 - 37% open · ⏱️ 11.03.2022):

	```
	git clone https://github.com/tylerwince/flake8-bandit
	```
- [PyPi](https://pypi.org/project/flake8-bandit) (📥 580K / month · 📦 130 · ⏱️ 11.03.2022):
	```
	pip install flake8-bandit
	```
</details>
<details><summary><b><a href="https://github.com/Instagram/Fixit">Fixit</a></b> (🥉22 ·  ⭐ 290) - Fixit is a Python Lint Framework based on LibCST. It comes with useful.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/Instagram/Fixit) (👨‍💻 29 · 🔀 43 · 📦 17 · 📋 57 - 56% open · ⏱️ 07.01.2022):

	```
	git clone https://github.com/Instagram/Fixit
	```
- [PyPi](https://pypi.org/project/fixit) (📥 9.9K / month · 📦 2 · ⏱️ 30.07.2021):
	```
	pip install fixit
	```
</details>
<details><summary><b><a href="https://github.com/andreoliwa/nitpick">nitpick</a></b> (🥉22 ·  ⭐ 240) - Enforce the same settings on multiple projects. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://cdn.iconscout.com/icon/free/png-256/8-eight-digital-number-numerical-numbers-36025.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/andreoliwa/nitpick) (👨‍💻 14 · 🔀 13 · 📥 4 · 📋 100 - 30% open · ⏱️ 28.03.2022):

	```
	git clone https://github.com/andreoliwa/nitpick
	```
- [PyPi](https://pypi.org/project/nitpick) (📥 11K / month · 📦 4 · ⏱️ 27.03.2022):
	```
	pip install nitpick
	```
</details>
<details><summary><b><a href="https://github.com/gforcada/flake8-builtins">flake8-builtins</a></b> (🥉22 ·  ⭐ 81) - Check for python builtins being used as variables or.. <code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code> <code><img src="https://cdn.iconscout.com/icon/free/png-256/8-eight-digital-number-numerical-numbers-36025.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/gforcada/flake8-builtins) (👨‍💻 15 · 🔀 18 · 📦 3.6K · 📋 36 - 11% open · ⏱️ 20.09.2021):

	```
	git clone https://github.com/gforcada/flake8-builtins
	```
- [PyPi](https://pypi.org/project/flake8-builtins) (📥 480K / month · 📦 300 · ⏱️ 14.05.2020):
	```
	pip install flake8-builtins
	```
- [Conda](https://anaconda.org/conda-forge/flake8-builtins) (📥 140K · ⏱️ 18.05.2020):
	```
	conda install -c conda-forge flake8-builtins
	```
</details>
<details><summary><b><a href="https://github.com/deppen8/pandas-vet">pandas-vet</a></b> (🥉21 ·  ⭐ 130) - A plugin for Flake8 that checks pandas code. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://cdn.iconscout.com/icon/free/png-256/8-eight-digital-number-numerical-numbers-36025.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/deppen8/pandas-vet) (👨‍💻 12 · 🔀 15 · 📥 44 · 📦 72 · 📋 49 - 38% open · ⏱️ 09.02.2022):

	```
	git clone https://github.com/deppen8/pandas-vet
	```
- [PyPi](https://pypi.org/project/pandas-vet) (📥 8.2K / month · 📦 9 · ⏱️ 09.02.2022):
	```
	pip install pandas-vet
	```
- [Conda](https://anaconda.org/conda-forge/pandas-vet) (📥 8.6K · ⏱️ 10.02.2022):
	```
	conda install -c conda-forge pandas-vet
	```
</details>
<details><summary><b><a href="https://github.com/justinabrahms/imhotep">imhotep</a></b> (🥉20 ·  ⭐ 220) - A static-analysis bot for Github. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/justinabrahms/imhotep) (👨‍💻 17 · 🔀 36 · 📦 9 · 📋 45 - 44% open · ⏱️ 26.03.2022):

	```
	git clone https://github.com/justinabrahms/imhotep
	```
- [PyPi](https://pypi.org/project/imhotep) (📥 130 / month · 📦 5 · ⏱️ 20.02.2022):
	```
	pip install imhotep
	```
</details>
<details><summary><b><a href="https://github.com/jschaf/pylint-flask">pylint-flask</a></b> (🥉19 ·  ⭐ 60 · 💤) - A Pylint plugin to analyze Flask applications. <code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code> <code><img src="https://www.pylint.org/ico/favicon.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/jschaf/pylint-flask) (👨‍💻 7 · 🔀 9 · 📦 5.9K · 📋 10 - 50% open · ⏱️ 10.03.2021):

	```
	git clone https://github.com/jschaf/pylint-flask
	```
- [PyPi](https://pypi.org/project/pylint-flask) (📥 240K / month · 📦 360 · ⏱️ 30.01.2019):
	```
	pip install pylint-flask
	```
- [Conda](https://anaconda.org/conda-forge/pylint-flask) (📥 54K · ⏱️ 02.02.2019):
	```
	conda install -c conda-forge pylint-flask
	```
</details>
<details><summary><b><a href="https://github.com/hchasestevens/bellybutton">bellybutton</a></b> (🥉16 ·  ⭐ 230 · 💤) - Custom Python linting through AST expressions. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/hchasestevens/bellybutton) (👨‍💻 5 · 🔀 11 · 📦 18 · 📋 14 - 57% open · ⏱️ 15.07.2021):

	```
	git clone https://github.com/hchasestevens/bellybutton
	```
- [PyPi](https://pypi.org/project/bellybutton) (📥 5.8K / month · 📦 1 · ⏱️ 27.11.2020):
	```
	pip install bellybutton
	```
</details>
<details><summary>Show 8 hidden projects...</summary>

- <b><a href="https://github.com/PyCQA/pep8-naming">pep8-naming</a></b> (🥉26 ·  ⭐ 370) - Naming Convention checker for Python. <code><a href="https://tldrlegal.com/search?q=Saxpath">❗️Saxpath</a></code>
- <b><a href="https://github.com/PyCQA/flake8-import-order">flake8-import-order</a></b> (🥉24 ·  ⭐ 260 · 💀) - Flake8 plugin that checks import order against.. <code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code> <code><img src="https://cdn.iconscout.com/icon/free/png-256/8-eight-digital-number-numerical-numbers-36025.png" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/wearepal/data-science-types">data-science-types</a></b> (🥉23 ·  ⭐ 190 · 💀) - Mypy stubs, i.e., type information, for numpy, pandas.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/life4/flakehell">flakehell</a></b> (🥉19 ·  ⭐ 220 · 💀) - Flake8 wrapper to make it nice, legacy-friendly, configurable. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://cdn.iconscout.com/icon/free/png-256/8-eight-digital-number-numerical-numbers-36025.png" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/ambv/flake8-mypy">flake8-mypy</a></b> (🥉19 ·  ⭐ 100 · 💀) - A plugin for flake8 integrating Mypy. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://cdn.iconscout.com/icon/free/png-256/8-eight-digital-number-numerical-numbers-36025.png" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/bndr/pycycle">pycycle</a></b> (🥉16 ·  ⭐ 300 · 💀) - Tool for pinpointing circular imports in Python. Find cyclic imports.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/cemsbr/yala">yala</a></b> (🥉16 ·  ⭐ 13) - Yet Another Linter Aggregator. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://cdn.iconscout.com/icon/free/png-256/8-eight-digital-number-numerical-numbers-36025.png" style="display:inline;" width="13" height="13"></code> <code><img src="https://www.pylint.org/ico/favicon.ico" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/lyft/linty_fresh">linty_fresh</a></b> (🥉13 ·  ⭐ 180 · 💀) - Surface lint errors during code review. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://cdn.iconscout.com/icon/free/png-256/8-eight-digital-number-numerical-numbers-36025.png" style="display:inline;" width="13" height="13"></code> <code>mypy</code>
</details>
<br>

## Code Formatters

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/psf/black">black</a></b> (🥇44 ·  ⭐ 27K) - The uncompromising Python code formatter. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/psf/black) (👨‍💻 310 · 🔀 1.7K · 📥 21K · 📦 140K · 📋 1.9K - 17% open · ⏱️ 30.03.2022):

	```
	git clone https://github.com/psf/black
	```
- [PyPi](https://pypi.org/project/black) (📥 13M / month · 📦 7.1K · ⏱️ 28.03.2022):
	```
	pip install black
	```
- [Conda](https://anaconda.org/conda-forge/black) (📥 3.5M · ⏱️ 28.03.2022):
	```
	conda install -c conda-forge black
	```
</details>
<details><summary><b><a href="https://github.com/PyCQA/isort">isort</a></b> (🥈38 ·  ⭐ 4.7K) - A Python utility / library to sort imports. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/PyCQA/isort) (👨‍💻 250 · 🔀 440 · 📦 230K · 📋 1.1K - 5% open · ⏱️ 07.01.2022):

	```
	git clone https://github.com/PyCQA/isort
	```
- [PyPi](https://pypi.org/project/isort) (📥 20M / month · 📦 14K · ⏱️ 09.11.2021):
	```
	pip install isort
	```
- [Conda](https://anaconda.org/conda-forge/isort) (📥 2.9M · ⏱️ 09.11.2021):
	```
	conda install -c conda-forge isort
	```
</details>
<details><summary><b><a href="https://github.com/google/yapf">yapf</a></b> (🥈37 ·  ⭐ 12K) - A formatter for Python files. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/google/yapf) (👨‍💻 140 · 🔀 850 · 📦 31K · 📋 740 - 46% open · ⏱️ 01.03.2022):

	```
	git clone https://github.com/google/yapf
	```
- [PyPi](https://pypi.org/project/yapf) (📥 1.8M / month · 📦 2.1K · ⏱️ 26.12.2021):
	```
	pip install yapf
	```
- [Conda](https://anaconda.org/conda-forge/yapf) (📥 960K · ⏱️ 06.01.2022):
	```
	conda install -c conda-forge yapf
	```
</details>
<details><summary><b><a href="https://github.com/hhatto/autopep8">autopep8</a></b> (🥉36 ·  ⭐ 4K) - A tool that automatically formats Python code to conform to the PEP 8.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/hhatto/autopep8) (👨‍💻 52 · 🔀 260 · 📦 110K · 📋 430 - 21% open · ⏱️ 02.03.2022):

	```
	git clone https://github.com/hhatto/autopep8
	```
- [PyPi](https://pypi.org/project/autopep8) (📥 2.9M / month · 📦 5.6K · ⏱️ 24.10.2021):
	```
	pip install autopep8
	```
- [Conda](https://anaconda.org/conda-forge/autopep8) (📥 640K · ⏱️ 26.10.2021):
	```
	conda install -c conda-forge autopep8
	```
</details>
<details><summary><b><a href="https://github.com/PyCQA/docformatter">docformatter</a></b> (🥉24 ·  ⭐ 270) - Formats docstrings to follow PEP 257. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/PyCQA/docformatter) (👨‍💻 16 · 🔀 36 · 📦 910 · 📋 49 - 55% open · ⏱️ 11.02.2022):

	```
	git clone https://github.com/myint/docformatter
	```
- [PyPi](https://pypi.org/project/docformatter) (📥 130K / month · 📦 89 · ⏱️ 27.12.2020):
	```
	pip install docformatter
	```
- [Conda](https://anaconda.org/conda-forge/docformatter) (📥 16K · ⏱️ 29.12.2020):
	```
	conda install -c conda-forge docformatter
	```
</details>
<details><summary>Show 1 hidden projects...</summary>

- <b><a href="https://github.com/myint/pyformat">pyformat</a></b> (🥉17 ·  ⭐ 84 · 💀) - Formats Python code to follow a consistent style. <code><a href="https://tldrlegal.com/search?q=Saxpath">❗️Saxpath</a></code>
</details>
<br>

## Code Refactoring

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/davidhalter/jedi">jedi</a></b> (🥇40 ·  ⭐ 5.1K) - Awesome autocompletion, static analysis and refactoring library for python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/davidhalter/jedi) (👨‍💻 150 · 🔀 460 · 📦 190K · 📋 1.3K - 2% open · ⏱️ 25.12.2021):

	```
	git clone https://github.com/davidhalter/jedi
	```
- [PyPi](https://pypi.org/project/jedi) (📥 15M / month · 📦 8.3K · ⏱️ 17.11.2021):
	```
	pip install jedi
	```
- [Conda](https://anaconda.org/conda-forge/jedi) (📥 8.2M · ⏱️ 17.11.2021):
	```
	conda install -c conda-forge jedi
	```
</details>
<details><summary><b><a href="https://github.com/python-rope/rope">rope</a></b> (🥇34 ·  ⭐ 1.3K · 📉) - a python refactoring library. <code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code></summary>

- [GitHub](https://github.com/python-rope/rope) (👨‍💻 68 · 🔀 150 · 📦 36K · 📋 240 - 30% open · ⏱️ 16.03.2022):

	```
	git clone https://github.com/python-rope/rope
	```
- [PyPi](https://pypi.org/project/rope) (📥 640K / month · 📦 1.6K · ⏱️ 27.02.2022):
	```
	pip install rope
	```
- [Conda](https://anaconda.org/conda-forge/rope) (📥 650K · ⏱️ 27.02.2022):
	```
	conda install -c conda-forge rope
	```
</details>
<details><summary><b><a href="https://github.com/asottile/pyupgrade">pyupgrade</a></b> (🥈28 ·  ⭐ 1.6K) - A tool (and pre-commit hook) to automatically upgrade syntax for newer.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/asottile/pyupgrade) (👨‍💻 22 · 🔀 100 · 📋 270 - 4% open · ⏱️ 25.03.2022):

	```
	git clone https://github.com/asottile/pyupgrade
	```
- [PyPi](https://pypi.org/project/pyupgrade) (📥 250K / month · 📦 41 · ⏱️ 13.03.2022):
	```
	pip install pyupgrade
	```
- [Conda](https://anaconda.org/conda-forge/pyupgrade) (📥 330K · ⏱️ 14.03.2022):
	```
	conda install -c conda-forge pyupgrade
	```
</details>
<details><summary><b><a href="https://github.com/Instagram/MonkeyType">MonkeyType</a></b> (🥈26 ·  ⭐ 3.7K) - A Python library that generates static type annotations by.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/Instagram/MonkeyType) (👨‍💻 39 · 🔀 130 · 📋 150 - 25% open · ⏱️ 23.03.2022):

	```
	git clone https://github.com/Instagram/MonkeyType
	```
- [PyPi](https://pypi.org/project/monkeytype) (📥 47K / month · 📦 25 · ⏱️ 18.02.2022):
	```
	pip install monkeytype
	```
- [Conda](https://anaconda.org/conda-forge/monkeytype) (📥 38K · ⏱️ 19.02.2022):
	```
	conda install -c conda-forge monkeytype
	```
</details>
<details><summary><b><a href="https://github.com/jendrikseipp/vulture">vulture</a></b> (🥈25 ·  ⭐ 2.1K) - Find dead Python code. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jendrikseipp/vulture) (👨‍💻 30 · 🔀 97 · 📦 1.6K · 📋 160 - 11% open · ⏱️ 03.01.2022):

	```
	git clone https://github.com/jendrikseipp/vulture
	```
- [PyPi](https://pypi.org/project/vulture) (📥 260K / month · 📦 220 · ⏱️ 16.01.2021):
	```
	pip install vulture
	```
- [Conda](https://anaconda.org/conda-forge/vulture) (📥 52K · ⏱️ 11.08.2020):
	```
	conda install -c conda-forge vulture
	```
</details>
<details><summary><b><a href="https://github.com/PyCQA/redbaron">redbaron</a></b> (🥈25 ·  ⭐ 630) - Bottom-up approach to refactoring in python. <code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code></summary>

- [GitHub](https://github.com/PyCQA/redbaron) (👨‍💻 34 · 🔀 70 · 📦 370 · 📋 130 - 63% open · ⏱️ 09.12.2021):

	```
	git clone https://github.com/pycqa/redbaron
	```
- [PyPi](https://pypi.org/project/redbaron) (📥 32K / month · 📦 120 · ⏱️ 17.03.2019):
	```
	pip install redbaron
	```
</details>
<details><summary><b><a href="https://github.com/PyCQA/baron">baron</a></b> (🥉24 ·  ⭐ 270) - IDE allow you to refactor code, Baron allows you to write refactoring.. <code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code></summary>

- [GitHub](https://github.com/PyCQA/baron) (👨‍💻 33 · 🔀 52 · 📦 200 · 📋 75 - 61% open · ⏱️ 09.12.2021):

	```
	git clone https://github.com/PyCQA/baron
	```
- [PyPi](https://pypi.org/project/baron) (📥 33K / month · 📦 59 · ⏱️ 09.12.2021):
	```
	pip install baron
	```
</details>
<details><summary><b><a href="https://github.com/facebookincubator/Bowler">Bowler</a></b> (🥉22 ·  ⭐ 1.4K) - Safe code refactoring for modern Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/facebookincubator/Bowler) (👨‍💻 27 · 🔀 89 · 📋 80 - 57% open · ⏱️ 04.03.2022):

	```
	git clone https://github.com/facebookincubator/Bowler
	```
- [PyPi](https://pypi.org/project/bowler) (📥 31K / month · 📦 7 · ⏱️ 17.09.2020):
	```
	pip install bowler
	```
- [Conda](https://anaconda.org/conda-forge/bowler) (📥 12K · ⏱️ 12.06.2019):
	```
	conda install -c conda-forge bowler
	```
</details>
<details><summary><b><a href="https://github.com/asottile/add-trailing-comma">add-trailing-comma</a></b> (🥉22 ·  ⭐ 230) - A tool (and pre-commit hook) to automatically add trailing.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/asottile/add-trailing-comma) (👨‍💻 9 · 🔀 18 · 📋 42 - 2% open · ⏱️ 30.03.2022):

	```
	git clone https://github.com/asottile/add-trailing-comma
	```
- [PyPi](https://pypi.org/project/add-trailing-comma) (📥 20K / month · 📦 12 · ⏱️ 30.03.2022):
	```
	pip install add-trailing-comma
	```
</details>
<details><summary><b><a href="https://github.com/dropbox/pyannotate">pyannotate</a></b> (🥉21 ·  ⭐ 1.3K) - Auto-generate PEP-484 annotations. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/dropbox/pyannotate) (👨‍💻 17 · 🔀 54 · 📦 69 · 📋 59 - 44% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/dropbox/pyannotate
	```
- [PyPi](https://pypi.org/project/pyannotate) (📥 5.7K / month · 📦 18 · ⏱️ 16.09.2019):
	```
	pip install pyannotate
	```
</details>
<details><summary><b><a href="https://github.com/hakancelik96/unimport">unimport</a></b> (🥉20 ·  ⭐ 130) - A linter, formatter for finding and removing unused import statements. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/hakancelik96/unimport) (👨‍💻 13 · 🔀 12 · 📦 23 · 📋 79 - 13% open · ⏱️ 22.03.2022):

	```
	git clone https://github.com/hakancelik96/unimport
	```
- [PyPi](https://pypi.org/project/unimport) (📥 6.5K / month · ⏱️ 09.03.2022):
	```
	pip install unimport
	```
</details>
<details><summary><b><a href="https://github.com/ambv/retype">retype</a></b> (🥉16 ·  ⭐ 120) - Re-apply type annotations from .pyi stubs to your codebase. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ambv/retype) (👨‍💻 8 · 🔀 17 · 📋 15 - 46% open · ⏱️ 29.12.2021):

	```
	git clone https://github.com/ambv/retype
	```
- [PyPi](https://pypi.org/project/retype) (📥 1.2K / month · 📦 18 · ⏱️ 29.12.2021):
	```
	pip install retype
	```
- [Conda](https://anaconda.org/conda-forge/retype) (📥 16K · ⏱️ 29.12.2021):
	```
	conda install -c conda-forge retype
	```
</details>
<details><summary><b><a href="https://github.com/ilevkivskyi/com2ann">com2ann</a></b> (🥉16 ·  ⭐ 110 · 💤) - Tool for translation type comments to type annotations in Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ilevkivskyi/com2ann) (👨‍💻 4 · 🔀 7 · 📦 9 · 📋 20 - 25% open · ⏱️ 21.08.2021):

	```
	git clone https://github.com/ilevkivskyi/com2ann
	```
- [PyPi](https://pypi.org/project/com2ann) (📥 5.8K / month · 📦 1 · ⏱️ 21.08.2021):
	```
	pip install com2ann
	```
</details>
<details><summary>Show 5 hidden projects...</summary>

- <b><a href="https://github.com/PyCQA/autoflake">autoflake</a></b> (🥈26 ·  ⭐ 500 · 💀) - Removes unused imports and unused variables as reported by pyflakes. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/myint/eradicate">eradicate</a></b> (🥉20 ·  ⭐ 130 · 💀) - Removes commented-out code from Python files. <code><a href="https://tldrlegal.com/search?q=Saxpath">❗️Saxpath</a></code>
- <b><a href="https://github.com/myint/unify">unify</a></b> (🥉19 ·  ⭐ 69 · 💀) - Modifies strings to all use the same quote where possible. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/spulec/pep8ify">pep8ify</a></b> (🥉16 ·  ⭐ 120 · 💀) - A library that modifies python source code to conform to pep8. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/elmotec/massedit">massedit</a></b> (🥉15 ·  ⭐ 96 · 💀) - Programmatically edit text files with Python. Useful for source to.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>
<br>

## Code Security

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/PyCQA/bandit">bandit</a></b> (🥇36 ·  ⭐ 4K) - Bandit is a tool designed to find common security issues in Python code. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/PyCQA/bandit) (👨‍💻 150 · 🔀 410 · 📥 230 · 📦 12K · 📋 590 - 30% open · ⏱️ 28.03.2022):

	```
	git clone https://github.com/PyCQA/bandit
	```
- [PyPi](https://pypi.org/project/bandit) (📥 2.6M / month · 📦 1.5K · ⏱️ 04.03.2022):
	```
	pip install bandit
	```
- [Conda](https://anaconda.org/conda-forge/bandit) (📥 120K · ⏱️ 05.03.2022):
	```
	conda install -c conda-forge bandit
	```
</details>
<details><summary><b><a href="https://github.com/sqlmapproject/sqlmap">sqlmap</a></b> (🥈32 ·  ⭐ 23K) - Automatic SQL injection and database takeover tool. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/sqlmapproject/sqlmap) (👨‍💻 110 · 🔀 4.6K · 📋 4.6K - 1% open · ⏱️ 25.03.2022):

	```
	git clone https://github.com/sqlmapproject/sqlmap
	```
- [PyPi](https://pypi.org/project/sqlmap) (📥 6.9K / month · 📦 6 · ⏱️ 02.03.2022):
	```
	pip install sqlmap
	```
</details>
<details><summary><b><a href="https://github.com/Yelp/detect-secrets">detect-secrets</a></b> (🥉30 ·  ⭐ 2.2K) - An enterprise friendly way of detecting and preventing.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/Yelp/detect-secrets) (👨‍💻 56 · 🔀 270 · 📋 250 - 35% open · ⏱️ 16.02.2022):

	```
	git clone https://github.com/Yelp/detect-secrets
	```
- [PyPi](https://pypi.org/project/detect-secrets) (📥 370K / month · 📦 23 · ⏱️ 16.02.2022):
	```
	pip install detect-secrets
	```
</details>
<details><summary><b><a href="https://github.com/pyupio/safety">safety</a></b> (🥉30 ·  ⭐ 1.2K · 💤) - Safety checks your installed dependencies for known security.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pyupio/safety) (👨‍💻 35 · 🔀 100 · 📥 140K · 📦 3.9K · 📋 120 - 36% open · ⏱️ 28.04.2021):

	```
	git clone https://github.com/pyupio/safety
	```
- [PyPi](https://pypi.org/project/safety) (📥 950K / month · 📦 320 · ⏱️ 15.01.2021):
	```
	pip install safety
	```
- [Conda](https://anaconda.org/conda-forge/safety) (📥 28K · ⏱️ 15.01.2021):
	```
	conda install -c conda-forge safety
	```
</details>
<details><summary><b><a href="https://github.com/landscapeio/dodgy">dodgy</a></b> (🥉20 ·  ⭐ 100 · 💤) - Looks at Python code to search for things which look dodgy such as.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/landscapeio/dodgy) (👨‍💻 14 · 🔀 19 · 📦 1.6K · 📋 12 - 75% open · ⏱️ 21.03.2021):

	```
	git clone https://github.com/landscapeio/dodgy
	```
- [PyPi](https://pypi.org/project/dodgy) (📥 230K / month · 📦 280 · ⏱️ 31.12.2019):
	```
	pip install dodgy
	```
- [Conda](https://anaconda.org/conda-forge/dodgy) (📥 27K · ⏱️ 10.06.2020):
	```
	conda install -c conda-forge dodgy
	```
</details>
<details><summary><b><a href="https://github.com/dlint-py/dlint">dlint</a></b> (🥉19 ·  ⭐ 85) - Dlint is a tool for encouraging best coding practices and helping ensure.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/dlint-py/dlint) (👨‍💻 8 · 🔀 6 · 📋 34 - 58% open · ⏱️ 16.02.2022):

	```
	git clone https://github.com/dlint-py/dlint
	```
- [PyPi](https://pypi.org/project/dlint) (📥 81K / month · 📦 43 · ⏱️ 27.10.2021):
	```
	pip install dlint
	```
- [Conda](https://anaconda.org/conda-forge/dlint) (📥 150 · ⏱️ 09.11.2021):
	```
	conda install -c conda-forge dlint
	```
</details>
<details><summary>Show 2 hidden projects...</summary>

- <b><a href="https://github.com/dashingsoft/pyarmor">pyarmor</a></b> (🥈31 ·  ⭐ 1.4K) - A tool used to obfuscate python scripts, bind obfuscated scripts.. <code><a href="https://tldrlegal.com/search?q=SGI-B-2.0">❗️SGI-B-2.0</a></code>
- <b><a href="https://github.com/python-security/pyt">pyt</a></b> (🥉23 ·  ⭐ 2.1K · 💀) - A Static Analysis Tool for Detecting Security Vulnerabilities in.. <code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code>
</details>
<br>

## Virtual Environments

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/pypa/pipenv">pipenv</a></b> (🥇43 ·  ⭐ 23K) - Python Development Workflow for Humans. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pypa/pipenv) (👨‍💻 410 · 🔀 1.7K · 📦 26K · 📋 3.6K - 13% open · ⏱️ 30.03.2022):

	```
	git clone https://github.com/pypa/pipenv
	```
- [PyPi](https://pypi.org/project/pipenv) (📥 4.6M / month · 📦 1.2K · ⏱️ 28.03.2022):
	```
	pip install pipenv
	```
- [Conda](https://anaconda.org/conda-forge/pipenv) (📥 48K · ⏱️ 08.01.2022):
	```
	conda install -c conda-forge pipenv
	```
</details>
<details><summary><b><a href="https://github.com/pypa/virtualenv">virtualenv</a></b> (🥈40 ·  ⭐ 4.1K) - Virtual Python Environment builder. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pypa/virtualenv) (👨‍💻 220 · 🔀 940 · 📋 1.2K - 5% open · ⏱️ 25.03.2022):

	```
	git clone https://github.com/pypa/virtualenv
	```
- [PyPi](https://pypi.org/project/virtualenv) (📥 28M / month · 📦 18K · ⏱️ 25.03.2022):
	```
	pip install virtualenv
	```
- [Conda](https://anaconda.org/conda-forge/virtualenv) (📥 1.7M · ⏱️ 26.03.2022):
	```
	conda install -c conda-forge virtualenv
	```
</details>
<details><summary><b><a href="https://github.com/pyenv/pyenv">pyenv</a></b> (🥈31 ·  ⭐ 27K) - Simple Python version management. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pyenv/pyenv) (👨‍💻 360 · 🔀 2.3K · 📋 1.4K - 2% open · ⏱️ 31.03.2022):

	```
	git clone https://github.com/pyenv/pyenv
	```
- [PyPi](https://pypi.org/project/pyenv) (📥 7.6K / month · 📦 1 · ⏱️ 12.01.2019):
	```
	pip install pyenv
	```
</details>
<details><summary><b><a href="https://github.com/pyenv/pyenv-virtualenv">pyenv-virtualenv</a></b> (🥉20 ·  ⭐ 4.8K) - a pyenv plugin to manage virtualenv (a.k.a. python-virtualenv). <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pyenv/pyenv-virtualenv) (👨‍💻 48 · 🔀 310 · 📋 330 - 40% open · ⏱️ 26.02.2022):

	```
	git clone https://github.com/pyenv/pyenv-virtualenv
	```
</details>
<details><summary><b><a href="https://github.com/spotify/dh-virtualenv">dh-virtualenv</a></b> (🥉17 ·  ⭐ 1.5K) - Python virtualenvs in Debian packages. <code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code></summary>

- [GitHub](https://github.com/spotify/dh-virtualenv) (👨‍💻 58 · 🔀 170 · 📋 200 - 12% open · ⏱️ 10.11.2021):

	```
	git clone https://github.com/spotify/dh-virtualenv
	```
</details>
<details><summary><b><a href="https://github.com/pyenv/pyenv-installer">pyenv-installer</a></b> (🥉15 ·  ⭐ 3.1K) - This tool is used to install `pyenv` and friends. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pyenv/pyenv-installer) (👨‍💻 34 · 🔀 340 · 📋 69 - 7% open · ⏱️ 18.03.2022):

	```
	git clone https://github.com/pyenv/pyenv-installer
	```
</details>
<details><summary>Show 2 hidden projects...</summary>

- <b><a href="https://github.com/sashahart/vex">vex</a></b> (🥉19 ·  ⭐ 370 · 💀) - Run a command in the named virtualenv. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/gtalarico/pipenv-pipes">pipenv-pipes</a></b> (🥉13 ·  ⭐ 130 · 💀) - A PipEnv Environment Switcher. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>
<br>

## Dependency & Package Mangers

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/pypa/pip">pip</a></b> (🥇45 ·  ⭐ 7.9K · 📉) - The Python package installer. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pypa/pip) (👨‍💻 660 · 🔀 2.6K · 📦 77K · 📋 6.3K - 15% open · ⏱️ 28.03.2022):

	```
	git clone https://github.com/pypa/pip
	```
- [PyPi](https://pypi.org/project/pip) (📥 98M / month · 📦 11K · ⏱️ 07.03.2022):
	```
	pip install pip
	```
- [Conda](https://anaconda.org/conda-forge/pip) (📥 34M · ⏱️ 07.03.2022):
	```
	conda install -c conda-forge pip
	```
</details>
<details><summary><b><a href="https://github.com/conda/conda">conda</a></b> (🥈40 ·  ⭐ 4.6K) - OS-agnostic, system-level binary package manager and ecosystem. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/conda/conda) (👨‍💻 380 · 🔀 1.1K · 📋 8.5K - 20% open · ⏱️ 30.03.2022):

	```
	git clone https://github.com/conda/conda
	```
- [PyPi](https://pypi.org/project/conda) (📥 63K / month · 📦 1.1K · ⏱️ 22.04.2017):
	```
	pip install conda
	```
- [Conda](https://anaconda.org/conda-forge/conda) (📥 26M · ⏱️ 16.03.2022):
	```
	conda install -c conda-forge conda
	```
</details>
<details><summary><b><a href="https://github.com/python-poetry/poetry">poetry</a></b> (🥈39 ·  ⭐ 19K) - Python dependency management and packaging made easy. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/python-poetry/poetry) (👨‍💻 340 · 🔀 1.6K · 📥 11M · 📋 3.8K - 33% open · ⏱️ 30.03.2022):

	```
	git clone https://github.com/python-poetry/poetry
	```
- [PyPi](https://pypi.org/project/poetry) (📥 5.8M / month · 📦 130 · ⏱️ 17.03.2022):
	```
	pip install poetry
	```
- [Conda](https://anaconda.org/conda-forge/poetry) (📥 370K · ⏱️ 11.02.2022):
	```
	conda install -c conda-forge poetry
	```
</details>
<details><summary><b><a href="https://github.com/jazzband/pip-tools">pip-tools</a></b> (🥈36 ·  ⭐ 5.8K) - A set of tools to keep your pinned Python dependencies fresh. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jazzband/pip-tools) (👨‍💻 160 · 🔀 490 · 📋 830 - 17% open · ⏱️ 30.03.2022):

	```
	git clone https://github.com/jazzband/pip-tools
	```
- [PyPi](https://pypi.org/project/pip-tools) (📥 5M / month · 📦 1.8K · ⏱️ 08.02.2022):
	```
	pip install pip-tools
	```
- [Conda](https://anaconda.org/conda-forge/pip-tools) (📥 27K · ⏱️ 08.02.2022):
	```
	conda install -c conda-forge pip-tools
	```
</details>
<details><summary><b><a href="https://github.com/bndr/pipreqs">pipreqs</a></b> (🥉31 ·  ⭐ 4.1K) - pipreqs - Generate pip requirements.txt file based on imports of any.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/bndr/pipreqs) (👨‍💻 51 · 🔀 280 · 📦 9.7K · 📋 190 - 52% open · ⏱️ 23.10.2021):

	```
	git clone https://github.com/bndr/pipreqs
	```
- [PyPi](https://pypi.org/project/pipreqs) (📥 250K / month · 📦 320 · ⏱️ 23.10.2021):
	```
	pip install pipreqs
	```
- [Conda](https://anaconda.org/conda-forge/pipreqs) (📥 24K · ⏱️ 14.11.2019):
	```
	conda install -c conda-forge pipreqs
	```
</details>
<details><summary><b><a href="https://github.com/mamba-org/mamba">mamba</a></b> (🥉29 ·  ⭐ 2.9K) - The Fast Cross-Platform Package Manager. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/mamba-org/mamba) (👨‍💻 75 · 🔀 150 · 📋 800 - 30% open · ⏱️ 30.03.2022):

	```
	git clone https://github.com/mamba-org/mamba
	```
- [Conda](https://anaconda.org/conda-forge/mamba) (📥 2.3M · ⏱️ 01.03.2022):
	```
	conda install -c conda-forge mamba
	```
</details>
<details><summary><b><a href="https://github.com/pypa/pipx">pipx</a></b> (🥉28 ·  ⭐ 4.8K) - Install and Run Python Applications in Isolated Environments. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pypa/pipx) (👨‍💻 76 · 🔀 230 · 📋 470 - 23% open · ⏱️ 12.03.2022):

	```
	git clone https://github.com/pypa/pipx
	```
- [PyPi](https://pypi.org/project/pipx) (📥 280K / month · 📦 7 · ⏱️ 04.01.2022):
	```
	pip install pipx
	```
- [Conda](https://anaconda.org/conda-forge/pipx) (📥 310 · ⏱️ 04.01.2022):
	```
	conda install -c conda-forge pipx
	```
</details>
<details><summary><b><a href="https://github.com/David-OConnor/pyflow">pyflow</a></b> (🥉19 ·  ⭐ 1K) - An installation and dependency system for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/David-OConnor/pyflow) (👨‍💻 28 · 🔀 41 · 📥 4.1K · 📋 120 - 40% open · ⏱️ 11.03.2022):

	```
	git clone https://github.com/David-OConnor/pyflow
	```
- [PyPi](https://pypi.org/project/pyflow) (📥 350 / month · 📦 1 · ⏱️ 02.07.2021):
	```
	pip install pyflow
	```
</details>
<details><summary><b><a href="https://github.com/jaraco/pip-run">pip-run</a></b> (🥉18 ·  ⭐ 65) - pip-run - dynamic dependency loader for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jaraco/pip-run) (👨‍💻 11 · 🔀 10 · 📋 43 - 6% open · ⏱️ 23.01.2022):

	```
	git clone https://github.com/jaraco/pip-run
	```
- [PyPi](https://pypi.org/project/pip-run) (📥 11K / month · 📦 2 · ⏱️ 23.01.2022):
	```
	pip install pip-run
	```
</details>
<details><summary>Show 1 hidden projects...</summary>

- <b><a href="https://github.com/dephell/dephell">dephell</a></b> (🥉25 ·  ⭐ 1.7K · 💀) - Python project management. Manage packages: convert between formats,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>
<br>

## Code Metrics & Complexity

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/PyCQA/prospector">prospector</a></b> (🥇31 ·  ⭐ 1.6K) - Inspects Python source files and provides information about.. <code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code></summary>

- [GitHub](https://github.com/PyCQA/prospector) (👨‍💻 78 · 🔀 150 · 📋 310 - 11% open · ⏱️ 28.03.2022):

	```
	git clone https://github.com/PyCQA/prospector
	```
- [PyPi](https://pypi.org/project/prospector) (📥 240K / month · 📦 670 · ⏱️ 18.03.2022):
	```
	pip install prospector
	```
- [Conda](https://anaconda.org/conda-forge/prospector) (📥 28K · ⏱️ 10.03.2022):
	```
	conda install -c conda-forge prospector
	```
</details>
<details><summary><b><a href="https://github.com/PyCQA/mccabe">mccabe</a></b> (🥈29 ·  ⭐ 470) - McCabe complexity checker for Python. <code><a href="https://tldrlegal.com/search?q=Saxpath">❗️Saxpath</a></code></summary>

- [GitHub](https://github.com/PyCQA/mccabe) (👨‍💻 21 · 🔀 44 · 📦 260K · 📋 43 - 16% open · ⏱️ 24.01.2022):

	```
	git clone https://github.com/PyCQA/mccabe
	```
- [PyPi](https://pypi.org/project/mccabe) (📥 22M / month · 📦 16K · ⏱️ 24.01.2022):
	```
	pip install mccabe
	```
- [Conda](https://anaconda.org/conda-forge/mccabe) (📥 4.2M · ⏱️ 24.01.2022):
	```
	conda install -c conda-forge mccabe
	```
</details>
<details><summary><b><a href="https://github.com/rubik/radon">radon</a></b> (🥈28 ·  ⭐ 1.3K) - Various code metrics for Python code. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/rubik/radon) (👨‍💻 50 · 🔀 97 · 📦 2.4K · 📋 160 - 12% open · ⏱️ 23.02.2022):

	```
	git clone https://github.com/rubik/radon
	```
- [PyPi](https://pypi.org/project/radon) (📥 410K / month · 📦 600 · ⏱️ 15.12.2021):
	```
	pip install radon
	```
- [Conda](https://anaconda.org/conda-forge/radon) (📥 38K · ⏱️ 07.09.2021):
	```
	conda install -c conda-forge radon
	```
</details>
<details><summary><b><a href="https://github.com/rubik/xenon">xenon</a></b> (🥉22 ·  ⭐ 200) - Monitoring tool based on radon. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/rubik/xenon) (👨‍💻 9 · 🔀 18 · 📦 320 · 📋 33 - 18% open · ⏱️ 24.02.2022):

	```
	git clone https://github.com/rubik/xenon
	```
- [PyPi](https://pypi.org/project/xenon) (📥 68K / month · 📦 69 · ⏱️ 24.02.2022):
	```
	pip install xenon
	```
- [Conda](https://anaconda.org/conda-forge/xenon) (📥 15K · ⏱️ 12.10.2019):
	```
	conda install -c conda-forge xenon
	```
</details>
<details><summary><b><a href="https://github.com/tonybaloney/wily">wily</a></b> (🥉21 ·  ⭐ 880) - A Python application for tracking, reporting on timing and complexity in.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/tonybaloney/wily) (👨‍💻 18 · 🔀 46 · 📋 82 - 35% open · ⏱️ 18.02.2022):

	```
	git clone https://github.com/tonybaloney/wily
	```
- [PyPi](https://pypi.org/project/wily) (📥 29K / month · 📦 9 · ⏱️ 01.07.2021):
	```
	pip install wily
	```
</details>
<details><summary>Show 1 hidden projects...</summary>

- <b><a href="https://github.com/mschwager/cohesion">cohesion</a></b> (🥉12 ·  ⭐ 150 · 💀) - A tool for measuring Python class cohesion. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
</details>
<br>

## Logging

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/Textualize/rich">rich</a></b> (🥇42 ·  ⭐ 36K) - Rich is a Python library for rich text and beautiful formatting in the terminal. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/Textualize/rich) (👨‍💻 160 · 🔀 1.2K · 📦 14K · 📋 740 - 4% open · ⏱️ 30.03.2022):

	```
	git clone https://github.com/Textualize/rich
	```
- [PyPi](https://pypi.org/project/rich) (📥 5.2M / month · 📦 1.6K · ⏱️ 22.03.2022):
	```
	pip install rich
	```
- [Conda](https://anaconda.org/conda-forge/rich) (📥 720K · ⏱️ 22.03.2022):
	```
	conda install -c conda-forge rich
	```
</details>
<details><summary><b><a href="https://github.com/tqdm/tqdm">tqdm</a></b> (🥇42 ·  ⭐ 22K · 📈) - A Fast, Extensible Progress Bar for Python and CLI. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code></summary>

- [GitHub](https://github.com/tqdm/tqdm) (👨‍💻 110 · 🔀 1.1K · 📥 8.1K · 📦 270K · 📋 890 - 38% open · ⏱️ 23.03.2022):

	```
	git clone https://github.com/tqdm/tqdm
	```
- [PyPi](https://pypi.org/project/tqdm) (📥 37M / month · 📦 21K · ⏱️ 23.03.2022):
	```
	pip install tqdm
	```
- [Conda](https://anaconda.org/conda-forge/tqdm) (📥 11M · ⏱️ 24.03.2022):
	```
	conda install -c conda-forge tqdm
	```
- [Docker Hub](https://hub.docker.com/r/tqdm/tqdm) (📥 4K · ⭐ 2 · ⏱️ 26.03.2022):
	```
	docker pull tqdm/tqdm
	```
</details>
<details><summary><b><a href="https://github.com/getsentry/sentry-python">sentry-sdk</a></b> (🥇38 ·  ⭐ 1.2K) - The official Python SDK for Sentry.io. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/getsentry/sentry-python) (👨‍💻 120 · 🔀 280 · 📥 4.6K · 📦 19K · 📋 640 - 22% open · ⏱️ 28.03.2022):

	```
	git clone https://github.com/getsentry/sentry-python
	```
- [PyPi](https://pypi.org/project/sentry-sdk) (📥 14M / month · 📦 960 · ⏱️ 18.03.2022):
	```
	pip install sentry-sdk
	```
- [Conda](https://anaconda.org/conda-forge/sentry-sdk) (📥 140K · ⏱️ 18.03.2022):
	```
	conda install -c conda-forge sentry-sdk
	```
</details>
<details><summary><b><a href="https://github.com/Delgan/loguru">loguru</a></b> (🥈37 ·  ⭐ 11K · 📈) - Python logging made (stupidly) simple. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/Delgan/loguru) (👨‍💻 34 · 🔀 510 · 📦 16K · 📋 560 - 20% open · ⏱️ 15.03.2022):

	```
	git clone https://github.com/Delgan/loguru
	```
- [PyPi](https://pypi.org/project/loguru) (📥 3.6M / month · 📦 1.3K · ⏱️ 20.09.2020):
	```
	pip install loguru
	```
- [Conda](https://anaconda.org/conda-forge/loguru) (📥 410K · ⏱️ 02.11.2021):
	```
	conda install -c conda-forge loguru
	```
</details>
<details><summary><b><a href="https://github.com/hynek/structlog">structlog</a></b> (🥈34 ·  ⭐ 2K) - Structured Logging for Python. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/hynek/structlog) (👨‍💻 86 · 🔀 150 · 📋 210 - 12% open · ⏱️ 22.03.2022):

	```
	git clone https://github.com/hynek/structlog
	```
- [PyPi](https://pypi.org/project/structlog) (📥 4M / month · 📦 900 · ⏱️ 16.12.2021):
	```
	pip install structlog
	```
- [Conda](https://anaconda.org/conda-forge/structlog) (📥 180K · ⏱️ 06.01.2022):
	```
	conda install -c conda-forge structlog
	```
</details>
<details><summary><b><a href="https://github.com/madzak/python-json-logger">python-json-logger</a></b> (🥈34 ·  ⭐ 1.2K) - Json Formatter for the standard python logger. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/madzak/python-json-logger) (👨‍💻 50 · 🔀 170 · 📦 24K · 📋 76 - 38% open · ⏱️ 06.02.2022):

	```
	git clone https://github.com/madzak/python-json-logger
	```
- [PyPi](https://pypi.org/project/python-json-logger) (📥 5.9M / month · 📦 690 · ⏱️ 27.07.2021):
	```
	pip install python-json-logger
	```
- [Conda](https://anaconda.org/conda-forge/python-json-logger) (📥 1.1M · ⏱️ 12.10.2020):
	```
	conda install -c conda-forge python-json-logger
	```
</details>
<details><summary><b><a href="https://github.com/WoLpH/python-progressbar">progressbar2</a></b> (🥈34 ·  ⭐ 760) - Progressbar 2 - A progress bar for Python 2 and Python 3 - pip.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/WoLpH/python-progressbar) (👨‍💻 40 · 🔀 100 · 📥 1.7K · 📦 16K · 📋 200 - 6% open · ⏱️ 05.01.2022):

	```
	git clone https://github.com/WoLpH/python-progressbar
	```
- [PyPi](https://pypi.org/project/progressbar2) (📥 6.5M / month · 📦 1.5K · ⏱️ 05.01.2022):
	```
	pip install progressbar2
	```
- [Conda](https://anaconda.org/conda-forge/progressbar2) (📥 420K · ⏱️ 01.02.2022):
	```
	conda install -c conda-forge progressbar2
	```
</details>
<details><summary><b><a href="https://github.com/astanin/python-tabulate">tabulate</a></b> (🥈31 ·  ⭐ 1.2K) - Pretty-print tabular data in Python, a library and a command-line.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/astanin/python-tabulate) (👨‍💻 68 · 🔀 99 · 📦 70K · 📋 120 - 49% open · ⏱️ 07.01.2022):

	```
	git clone https://github.com/astanin/python-tabulate
	```
- [PyPi](https://pypi.org/project/tabulate) (📥 33M / month · 📦 6.3K · ⏱️ 22.02.2021):
	```
	pip install tabulate
	```
- [Conda](https://anaconda.org/conda-forge/tabulate) (📥 2M · ⏱️ 22.02.2021):
	```
	conda install -c conda-forge tabulate
	```
</details>
<details><summary><b><a href="https://github.com/borntyping/python-colorlog">colorlog</a></b> (🥉29 ·  ⭐ 740) - A colored formatter for the python logging module. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/borntyping/python-colorlog) (👨‍💻 30 · 🔀 76 · 📦 15K · ⏱️ 08.11.2021):

	```
	git clone https://github.com/borntyping/python-colorlog
	```
- [PyPi](https://pypi.org/project/colorlog) (📥 6.9M / month · 📦 2.4K · ⏱️ 08.11.2021):
	```
	pip install colorlog
	```
- [Conda](https://anaconda.org/conda-forge/colorlog) (📥 740K · ⏱️ 09.11.2021):
	```
	conda install -c conda-forge colorlog
	```
</details>
<details><summary><b><a href="https://github.com/ines/wasabi">wasabi</a></b> (🥉29 ·  ⭐ 330) - A lightweight console printing and formatting toolkit. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ines/wasabi) (👨‍💻 8 · 🔀 21 · 📦 17K · 📋 8 - 62% open · ⏱️ 30.03.2022):

	```
	git clone https://github.com/ines/wasabi
	```
- [PyPi](https://pypi.org/project/wasabi) (📥 4M / month · 📦 280 · ⏱️ 30.03.2022):
	```
	pip install wasabi
	```
- [Conda](https://anaconda.org/conda-forge/wasabi) (📥 610K · ⏱️ 30.03.2022):
	```
	conda install -c conda-forge wasabi
	```
</details>
<details><summary><b><a href="https://github.com/rsalmei/alive-progress">alive-progress</a></b> (🥉28 ·  ⭐ 3.2K) - A new kind of Progress Bar, with real-time throughput, ETA, and.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/rsalmei/alive-progress) (👨‍💻 5 · 🔀 130 · 📦 720 · 📋 120 - 18% open · ⏱️ 22.03.2022):

	```
	git clone https://github.com/rsalmei/alive-progress
	```
- [PyPi](https://pypi.org/project/alive-progress) (📥 47K / month · 📦 75 · ⏱️ 22.03.2022):
	```
	pip install alive-progress
	```
- [Conda](https://anaconda.org/conda-forge/alive-progress) (📥 13K · ⏱️ 08.01.2021):
	```
	conda install -c conda-forge alive-progress
	```
</details>
<details><summary><b><a href="https://github.com/liiight/notifiers">notifiers</a></b> (🥉27 ·  ⭐ 2.1K) - The easy way to send notifications. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/liiight/notifiers) (👨‍💻 18 · 🔀 84 · 📋 91 - 31% open · ⏱️ 18.02.2022):

	```
	git clone https://github.com/liiight/notifiers
	```
- [PyPi](https://pypi.org/project/notifiers) (📥 440K / month · 📦 17 · ⏱️ 10.02.2022):
	```
	pip install notifiers
	```
- [Conda](https://anaconda.org/conda-forge/notifiers) (📥 17K · ⏱️ 16.11.2021):
	```
	conda install -c conda-forge notifiers
	```
</details>
<details><summary><b><a href="https://github.com/xolox/python-coloredlogs">python-coloredlogs</a></b> (🥉27 ·  ⭐ 460 · 💤) - Colored terminal output for Pythons logging module. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/xolox/python-coloredlogs) (👨‍💻 16 · 🔀 38 · 📦 11K · 📋 74 - 33% open · ⏱️ 11.06.2021):

	```
	git clone https://github.com/xolox/python-coloredlogs
	```
- [PyPi](https://pypi.org/project/coloredlogs) (📥 2.8M / month · 📦 1.7K · ⏱️ 11.06.2021):
	```
	pip install coloredlogs
	```
- [Conda](https://anaconda.org/anaconda/coloredlogs) (📥 3.9K · ⏱️ 05.03.2022):
	```
	conda install -c anaconda coloredlogs
	```
</details>
<details><summary><b><a href="https://github.com/Qix-/better-exceptions">better-exceptions</a></b> (🥉23 ·  ⭐ 4.2K) - Pretty and useful exceptions in Python, automatically. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/Qix-/better-exceptions) (👨‍💻 15 · 🔀 200 · 📋 72 - 40% open · ⏱️ 19.10.2021):

	```
	git clone https://github.com/Qix-/better-exceptions
	```
- [PyPi](https://pypi.org/project/better-exceptions) (📥 32K / month · 📦 58 · ⏱️ 29.01.2021):
	```
	pip install better-exceptions
	```
</details>
<details><summary><b><a href="https://github.com/shobrook/rebound">rebound</a></b> (🥉23 ·  ⭐ 3.8K) - Command-line tool that instantly fetches Stack Overflow results when an.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/shobrook/rebound) (👨‍💻 16 · 🔀 360 · 📥 180 · 📦 22 · 📋 58 - 34% open · ⏱️ 16.02.2022):

	```
	git clone https://github.com/shobrook/rebound
	```
- [PyPi](https://pypi.org/project/rebound) (📥 2.7K / month · 📦 16 · ⏱️ 26.01.2022):
	```
	pip install rebound
	```
- [Conda](https://anaconda.org/conda-forge/rebound) (📥 170K · ⏱️ 26.01.2022):
	```
	conda install -c conda-forge rebound
	```
</details>
<details><summary><b><a href="https://github.com/onelivesleft/PrettyErrors">PrettyErrors</a></b> (🥉22 ·  ⭐ 2.5K) - Prettify Python exception output to make it legible. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/onelivesleft/PrettyErrors) (👨‍💻 5 · 🔀 77 · 📋 41 - 7% open · ⏱️ 24.11.2021):

	```
	git clone https://github.com/onelivesleft/PrettyErrors
	```
- [PyPi](https://pypi.org/project/pretty_errors) (📥 18K / month · 📦 39 · ⏱️ 24.11.2021):
	```
	pip install pretty_errors
	```
- [Conda](https://anaconda.org/conda-forge/pretty_errors) (📥 3.9K · ⏱️ 27.11.2021):
	```
	conda install -c conda-forge pretty_errors
	```
</details>
<details><summary><b><a href="https://github.com/samuelcolvin/python-devtools">python-devtools</a></b> (🥉20 ·  ⭐ 490) - Dev tools for python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/samuelcolvin/python-devtools) (👨‍💻 7 · 🔀 22 · 📦 620 · 📋 39 - 12% open · ⏱️ 08.09.2021):

	```
	git clone https://github.com/samuelcolvin/python-devtools
	```
- [PyPi](https://pypi.org/project/python-devtools) (📥 810 / month · 📦 1 · ⏱️ 21.08.2017):
	```
	pip install python-devtools
	```
- [Conda](https://anaconda.org/conda-forge/python-devtools) (📥 2K · ⏱️ 29.09.2021):
	```
	conda install -c conda-forge python-devtools
	```
</details>
<details><summary>Show 4 hidden projects...</summary>

- <b><a href="https://github.com/getlogbook/logbook">logbook</a></b> (🥈31 ·  ⭐ 1.4K · 💀) - A cool logging replacement for Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/jazzband/prettytable">prettytable</a></b> (🥉28 ·  ⭐ 730) - Display tabular data in a visually appealing ASCII table.. <code><a href="https://tldrlegal.com/search?q=BSD-1-Clause">❗️BSD-1-Clause</a></code>
- <b><a href="https://github.com/cknd/stackprinter">stackprinter</a></b> (🥉22 ·  ⭐ 1.2K · 💀) - Debugging-friendly exceptions for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/skorokithakis/tbvaccine">tbvaccine</a></b> (🥉16 ·  ⭐ 370 · 💀) - A small utility to pretty-print Python tracebacks. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>
<br>

## Documentation

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/sphinx-doc/sphinx">sphinx</a></b> (🥇44 ·  ⭐ 4.5K) - Main repository for the Sphinx documentation builder. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://www.sphinx-doc.org/en/master/_static/favicon.svg" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/sphinx-doc/sphinx) (👨‍💻 710 · 🔀 1.7K · 📦 190K · 📋 6K - 17% open · ⏱️ 27.03.2022):

	```
	git clone https://github.com/sphinx-doc/sphinx
	```
- [PyPi](https://pypi.org/project/sphinx) (📥 5.3M / month · 📦 59K · ⏱️ 27.03.2022):
	```
	pip install sphinx
	```
- [Conda](https://anaconda.org/conda-forge/sphinx) (📥 4.9M · ⏱️ 27.03.2022):
	```
	conda install -c conda-forge sphinx
	```
</details>
<details><summary><b><a href="https://github.com/mkdocs/mkdocs">mkdocs</a></b> (🥇41 ·  ⭐ 14K) - Project documentation with Markdown. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code> <code><img src="https://squidfunk.github.io/mkdocs-material/assets/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/mkdocs/mkdocs) (👨‍💻 220 · 🔀 2K · 📦 20K · 📋 1.7K - 7% open · ⏱️ 26.03.2022):

	```
	git clone https://github.com/mkdocs/mkdocs
	```
- [PyPi](https://pypi.org/project/mkdocs) (📥 940K / month · 📦 3.6K · ⏱️ 26.03.2022):
	```
	pip install mkdocs
	```
- [Conda](https://anaconda.org/conda-forge/mkdocs) (📥 170K · ⏱️ 30.03.2022):
	```
	conda install -c conda-forge mkdocs
	```
</details>
<details><summary><b><a href="https://github.com/squidfunk/mkdocs-material">mkdocs-material</a></b> (🥇41 ·  ⭐ 9.1K) - Technical documentation that just works. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://squidfunk.github.io/mkdocs-material/assets/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/squidfunk/mkdocs-material) (👨‍💻 150 · 🔀 2.1K · 📦 12K · 📋 1.3K - 0% open · ⏱️ 30.03.2022):

	```
	git clone https://github.com/squidfunk/mkdocs-material
	```
- [PyPi](https://pypi.org/project/mkdocs-material) (📥 1.1M / month · 📦 1.2K · ⏱️ 27.03.2022):
	```
	pip install mkdocs-material
	```
- [Conda](https://anaconda.org/conda-forge/mkdocs-material) (📥 86K · ⏱️ 28.03.2022):
	```
	conda install -c conda-forge mkdocs-material
	```
</details>
<details><summary><b><a href="https://github.com/numpy/numpydoc">numpydoc</a></b> (🥈35 ·  ⭐ 20K) - Numpys Sphinx extensions. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://www.sphinx-doc.org/en/master/_static/favicon.svg" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/numpy/numpydoc) (👨‍💻 70 · 🔀 6.7K · 📦 31K · 📋 170 - 36% open · ⏱️ 30.03.2022):

	```
	git clone https://github.com/numpy/numpydoc
	```
- [PyPi](https://pypi.org/project/numpydoc) (📥 310K / month · 📦 4.3K · ⏱️ 29.03.2022):
	```
	pip install numpydoc
	```
- [Conda](https://anaconda.org/conda-forge/numpydoc) (📥 990K · ⏱️ 31.03.2022):
	```
	conda install -c conda-forge numpydoc
	```
</details>
<details><summary><b><a href="https://github.com/readthedocs/sphinx_rtd_theme">sphinx_rtd_theme</a></b> (🥈35 ·  ⭐ 4K) - Sphinx theme for readthedocs.org. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://www.sphinx-doc.org/en/master/_static/favicon.svg" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/readthedocs/sphinx_rtd_theme) (👨‍💻 110 · 🔀 1.6K · 📦 16 · 📋 740 - 26% open · ⏱️ 19.10.2021):

	```
	git clone https://github.com/readthedocs/sphinx_rtd_theme
	```
- [PyPi](https://pypi.org/project/sphinx_rtd_theme) (📥 2.4M / month · 📦 12K · ⏱️ 05.10.2018):
	```
	pip install sphinx_rtd_theme
	```
- [Conda](https://anaconda.org/conda-forge/sphinx_rtd_theme) (📥 2.2M · ⏱️ 17.09.2021):
	```
	conda install -c conda-forge sphinx_rtd_theme
	```
</details>
<details><summary><b><a href="https://github.com/michaeljones/breathe">breathe</a></b> (🥈33 ·  ⭐ 590) - ReStructuredText and Sphinx bridge to Doxygen. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/michaeljones/breathe) (👨‍💻 100 · 🔀 160 · 📥 280 · 📦 6.2K · 📋 500 - 24% open · ⏱️ 03.03.2022):

	```
	git clone https://github.com/michaeljones/breathe
	```
- [PyPi](https://pypi.org/project/breathe) (📥 240K / month · 📦 1K · ⏱️ 14.02.2022):
	```
	pip install breathe
	```
- [Conda](https://anaconda.org/conda-forge/breathe) (📥 290K · ⏱️ 14.02.2022):
	```
	conda install -c conda-forge breathe
	```
</details>
<details><summary><b><a href="https://github.com/mitmproxy/pdoc">pdoc</a></b> (🥈31 ·  ⭐ 1.2K) - API Documentation for Python Projects. <code><a href="http://bit.ly/3rvuUlR">Unlicense</a></code></summary>

- [GitHub](https://github.com/mitmproxy/pdoc) (👨‍💻 35 · 🔀 130 · 📦 600 · 📋 240 - 3% open · ⏱️ 31.03.2022):

	```
	git clone https://github.com/mitmproxy/pdoc
	```
- [PyPi](https://pypi.org/project/pdoc) (📥 100K / month · 📦 190 · ⏱️ 23.03.2022):
	```
	pip install pdoc
	```
</details>
<details><summary><b><a href="https://github.com/bitprophet/alabaster">alabaster</a></b> (🥈31 ·  ⭐ 640) - Lightweight, configurable Sphinx theme. Now the Sphinx default!. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://www.sphinx-doc.org/en/master/_static/favicon.svg" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/bitprophet/alabaster) (👨‍💻 28 · 🔀 180 · 📦 61K · 📋 140 - 61% open · ⏱️ 24.09.2021):

	```
	git clone https://github.com/bitprophet/alabaster
	```
- [PyPi](https://pypi.org/project/alabaster) (📥 4.7M / month · 📦 7.7K · ⏱️ 03.10.2018):
	```
	pip install alabaster
	```
- [Conda](https://anaconda.org/conda-forge/alabaster) (📥 3.7M · ⏱️ 03.10.2018):
	```
	conda install -c conda-forge alabaster
	```
</details>
<details><summary><b><a href="https://github.com/tox-dev/sphinx-autodoc-typehints">sphinx-autodoc-typehints</a></b> (🥈29 ·  ⭐ 410) - Type hints support for the Sphinx autodoc extension. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://www.sphinx-doc.org/en/master/_static/favicon.svg" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tox-dev/sphinx-autodoc-typehints) (👨‍💻 39 · 🔀 81 · 📋 140 - 17% open · ⏱️ 18.03.2022):

	```
	git clone https://github.com/tox-dev/sphinx-autodoc-typehints
	```
- [PyPi](https://pypi.org/project/sphinx-autodoc-typehints) (📥 490K / month · 📦 1.3K · ⏱️ 11.02.2022):
	```
	pip install sphinx-autodoc-typehints
	```
- [Conda](https://anaconda.org/conda-forge/sphinx-autodoc-typehints) (📥 280K · ⏱️ 15.04.2021):
	```
	conda install -c conda-forge sphinx-autodoc-typehints
	```
</details>
<details><summary><b><a href="https://github.com/ryan-roemer/sphinx-bootstrap-theme">sphinx-bootstrap-theme</a></b> (🥈28 ·  ⭐ 580) - Sphinx Bootstrap Theme. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://www.sphinx-doc.org/en/master/_static/favicon.svg" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/ryan-roemer/sphinx-bootstrap-theme) (👨‍💻 39 · 🔀 210 · 📋 140 - 39% open · ⏱️ 03.02.2022):

	```
	git clone https://github.com/ryan-roemer/sphinx-bootstrap-theme
	```
- [PyPi](https://pypi.org/project/sphinx-bootstrap-theme) (📥 270K / month · 📦 600 · ⏱️ 03.02.2022):
	```
	pip install sphinx-bootstrap-theme
	```
</details>
<details><summary><b><a href="https://github.com/mkdocstrings/mkdocstrings">mkdocstrings</a></b> (🥈27 ·  ⭐ 650) - Automatic documentation from sources, for MkDocs. <code><a href="http://bit.ly/3hkKRql">ISC</a></code> <code><img src="https://squidfunk.github.io/mkdocs-material/assets/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/mkdocstrings/mkdocstrings) (👨‍💻 29 · 🔀 67 · 📋 240 - 19% open · ⏱️ 01.03.2022):

	```
	git clone https://github.com/mkdocstrings/mkdocstrings
	```
- [PyPi](https://pypi.org/project/mkdocstrings) (📥 170K / month · 📦 190 · ⏱️ 01.03.2022):
	```
	pip install mkdocstrings
	```
- [Conda](https://anaconda.org/conda-forge/mkdocstrings) (📥 14K · ⏱️ 17.03.2022):
	```
	conda install -c conda-forge mkdocstrings
	```
</details>
<details><summary><b><a href="https://github.com/pdoc3/pdoc">pdoc3</a></b> (🥉25 ·  ⭐ 800) - Auto-generate API documentation for Python projects. <code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code></summary>

- [GitHub](https://github.com/pdoc3/pdoc) (👨‍💻 57 · 🔀 120 · 📦 1.5K · 📋 280 - 31% open · ⏱️ 03.02.2022):

	```
	git clone https://github.com/pdoc3/pdoc
	```
- [PyPi](https://pypi.org/project/pdoc3) (📥 250K / month · 📦 120 · ⏱️ 03.08.2021):
	```
	pip install pdoc3
	```
- [Conda](https://anaconda.org/anaconda/pdoc3) (📥 590 · ⏱️ 30.11.2020):
	```
	conda install -c anaconda pdoc3
	```
</details>
<details><summary><b><a href="https://github.com/executablebooks/sphinx-autobuild">sphinx-autobuild</a></b> (🥉25 ·  ⭐ 380 · 💤) - Watch a Sphinx directory and rebuild the.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://www.sphinx-doc.org/en/master/_static/favicon.svg" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/executablebooks/sphinx-autobuild) (👨‍💻 17 · 🔀 52 · 📋 59 - 25% open · ⏱️ 14.03.2021):

	```
	git clone https://github.com/executablebooks/sphinx-autobuild
	```
- [PyPi](https://pypi.org/project/sphinx-autobuild) (📥 280K / month · 📦 2.6K · ⏱️ 14.03.2021):
	```
	pip install sphinx-autobuild
	```
- [Conda](https://anaconda.org/conda-forge/sphinx-autobuild) (📥 86K · ⏱️ 14.03.2021):
	```
	conda install -c conda-forge sphinx-autobuild
	```
</details>
<details><summary><b><a href="https://github.com/econchick/interrogate">interrogate</a></b> (🥉25 ·  ⭐ 340) - Explain yourself! Interrogate a codebase for docstring coverage. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/econchick/interrogate) (👨‍💻 12 · 🔀 27 · 📦 1.5K · 📋 36 - 33% open · ⏱️ 27.12.2021):

	```
	git clone https://github.com/econchick/interrogate
	```
- [PyPi](https://pypi.org/project/interrogate) (📥 100K / month · 📦 35 · ⏱️ 10.09.2021):
	```
	pip install interrogate
	```
</details>
<details><summary><b><a href="https://github.com/asottile/blacken-docs">blacken-docs</a></b> (🥉23 ·  ⭐ 350) - Run `black` on python code blocks in documentation files. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/asottile/blacken-docs) (👨‍💻 14 · 🔀 23 · 📋 44 - 6% open · ⏱️ 25.03.2022):

	```
	git clone https://github.com/asottile/blacken-docs
	```
- [PyPi](https://pypi.org/project/blacken-docs) (📥 31K / month · 📦 17 · ⏱️ 30.01.2022):
	```
	pip install blacken-docs
	```
- [Conda](https://anaconda.org/conda-forge/blacken-docs) (📥 20K · ⏱️ 30.01.2022):
	```
	conda install -c conda-forge blacken-docs
	```
</details>
<details><summary><b><a href="https://github.com/zhaoterryy/mkdocs-pdf-export-plugin">mkdocs-pdf-export-plugin</a></b> (🥉23 ·  ⭐ 230) - An MkDocs plugin to export content pages as PDF files. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://squidfunk.github.io/mkdocs-material/assets/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/zhaoterryy/mkdocs-pdf-export-plugin) (👨‍💻 11 · 🔀 35 · 📦 220 · 📋 86 - 47% open · ⏱️ 05.10.2021):

	```
	git clone https://github.com/zhaoterryy/mkdocs-pdf-export-plugin
	```
- [PyPi](https://pypi.org/project/mkdocs-pdf-export-plugin) (📥 23K / month · 📦 4 · ⏱️ 05.10.2021):
	```
	pip install mkdocs-pdf-export-plugin
	```
</details>
<details><summary><b><a href="https://github.com/lukasgeiter/mkdocs-awesome-pages-plugin">mkdocs-awesome-pages-plugin</a></b> (🥉23 ·  ⭐ 230) - An MkDocs plugin that simplifies configuring page.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://squidfunk.github.io/mkdocs-material/assets/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/lukasgeiter/mkdocs-awesome-pages-plugin) (👨‍💻 4 · 🔀 23 · 📋 49 - 16% open · ⏱️ 12.02.2022):

	```
	git clone https://github.com/lukasgeiter/mkdocs-awesome-pages-plugin
	```
- [PyPi](https://pypi.org/project/mkdocs-awesome-pages-plugin) (📥 68K / month · 📦 64 · ⏱️ 12.02.2022):
	```
	pip install mkdocs-awesome-pages-plugin
	```
</details>
<details><summary><b><a href="https://github.com/bitprophet/releases">releases</a></b> (🥉21 ·  ⭐ 160) - A powerful Sphinx changelog-generating extension. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code> <code><img src="https://www.sphinx-doc.org/en/master/_static/favicon.svg" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/bitprophet/releases) (👨‍💻 10 · 🔀 36 · 📦 430 · 📋 76 - 43% open · ⏱️ 24.09.2021):

	```
	git clone https://github.com/bitprophet/releases
	```
- [PyPi](https://pypi.org/project/releases) (📥 6.2K / month · 📦 370 · ⏱️ 11.01.2020):
	```
	pip install releases
	```
- [Conda](https://anaconda.org/conda-forge/sphinx-releases) (📥 44K · ⏱️ 19.10.2021):
	```
	conda install -c conda-forge sphinx-releases
	```
</details>
<details><summary><b><a href="https://github.com/orzih/mkdocs-with-pdf">mkdocs-with-pdf</a></b> (🥉21 ·  ⭐ 130) - Generate a single PDF file from MkDocs repository. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://squidfunk.github.io/mkdocs-material/assets/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/orzih/mkdocs-with-pdf) (👨‍💻 6 · 🔀 32 · 📦 120 · 📋 73 - 46% open · ⏱️ 14.10.2021):

	```
	git clone https://github.com/orzih/mkdocs-with-pdf
	```
- [PyPi](https://pypi.org/project/mkdocs-with-pdf) (📥 14K / month · ⏱️ 03.07.2021):
	```
	pip install mkdocs-with-pdf
	```
</details>
<details><summary><b><a href="https://github.com/timothycrosley/portray">portray</a></b> (🥉20 ·  ⭐ 780 · 💤) - Your Project with Great Documentation. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/timothycrosley/portray) (👨‍💻 16 · 🔀 61 · 📋 56 - 44% open · ⏱️ 13.06.2021):

	```
	git clone https://github.com/timothycrosley/portray
	```
- [PyPi](https://pypi.org/project/portray) (📥 5.2K / month · 📦 17 · ⏱️ 13.06.2021):
	```
	pip install portray
	```
</details>
<details><summary><b><a href="https://github.com/clayrisser/sphinx-markdown-builder">sphinx-markdown-builder</a></b> (🥉19 ·  ⭐ 120) - sphinx builder that outputs markdown files. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://www.sphinx-doc.org/en/master/_static/favicon.svg" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/clayrisser/sphinx-markdown-builder) (👨‍💻 17 · 🔀 32 · 📦 230 · 📋 37 - 56% open · ⏱️ 08.01.2022):

	```
	git clone https://github.com/clayrisser/sphinx-markdown-builder
	```
- [PyPi](https://pypi.org/project/sphinx-markdown-builder) (📥 47K / month · 📦 52 · ⏱️ 08.01.2022):
	```
	pip install sphinx-markdown-builder
	```
</details>
<details><summary><b><a href="https://github.com/ml-tooling/lazydocs">lazydocs</a></b> (🥉17 ·  ⭐ 77 · 💤) - Generate markdown API documentation from Google-style Python.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ml-tooling/lazydocs) (👨‍💻 7 · 🔀 21 · 📦 65 · 📋 13 - 30% open · ⏱️ 20.08.2021):

	```
	git clone https://github.com/ml-tooling/lazydocs
	```
- [PyPi](https://pypi.org/project/lazydocs) (📥 2.3K / month · 📦 12 · ⏱️ 27.07.2021):
	```
	pip install lazydocs
	```
</details>
<details><summary>Show 5 hidden projects...</summary>

- <b><a href="https://github.com/pycco-docs/pycco">pycco</a></b> (🥉23 ·  ⭐ 770 · 💀) - Literate-style documentation generator. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/mkdocstrings/pytkdocs">pytkdocs</a></b> (🥉23 ·  ⭐ 44) - Load Python objects documentation. <code><a href="http://bit.ly/3hkKRql">ISC</a></code>
- <b><a href="https://github.com/zhaoterryy/mkdocs-git-revision-date-plugin">mkdocs-git-revision-date-plugin</a></b> (🥉19 ·  ⭐ 41) - MkDocs plugin for setting revision date from git per.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://squidfunk.github.io/mkdocs-material/assets/favicon.png" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/timvink/mkdocs-print-site-plugin">mkdocs-print-site-plugin</a></b> (🥉19 ·  ⭐ 38) - MkDocs Plugin that adds an additional page that.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://squidfunk.github.io/mkdocs-material/assets/favicon.png" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/zayd62/mkdocs-versioning">mkdocs-versioning</a></b> (🥉16 ·  ⭐ 38 · 💤) - A tool that allows for versioning sites built with.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://squidfunk.github.io/mkdocs-material/assets/favicon.png" style="display:inline;" width="13" height="13"></code>
</details>
<br>

## Debugging Tools

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/inducer/pudb">pudb</a></b> (🥇33 ·  ⭐ 2.4K) - Full-screen console debugger for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/inducer/pudb) (👨‍💻 83 · 🔀 200 · 📦 3K · 📋 290 - 48% open · ⏱️ 12.03.2022):

	```
	git clone https://github.com/inducer/pudb
	```
- [PyPi](https://pypi.org/project/pudb) (📥 190K / month · 📦 740 · ⏱️ 12.03.2022):
	```
	pip install pudb
	```
- [Conda](https://anaconda.org/conda-forge/pudb) (📥 120K · ⏱️ 11.01.2022):
	```
	conda install -c conda-forge pudb
	```
</details>
<details><summary><b><a href="https://github.com/gotcha/ipdb">ipdb</a></b> (🥇31 ·  ⭐ 1.5K) - Integration of IPython pdb. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/gotcha/ipdb) (👨‍💻 49 · 🔀 130 · 📦 32K · 📋 170 - 33% open · ⏱️ 30.12.2021):

	```
	git clone https://github.com/gotcha/ipdb
	```
- [PyPi](https://pypi.org/project/ipdb) (📥 2.8M / month · 📦 8.7K · ⏱️ 02.06.2021):
	```
	pip install ipdb
	```
- [Conda](https://anaconda.org/conda-forge/ipdb) (📥 240K · ⏱️ 24.06.2021):
	```
	conda install -c conda-forge ipdb
	```
</details>
<details><summary><b><a href="https://github.com/cool-RR/PySnooper">PySnooper</a></b> (🥈30 ·  ⭐ 15K) - Never use print for debugging again. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/cool-RR/PySnooper) (👨‍💻 26 · 🔀 920 · 📦 620 · 📋 120 - 16% open · ⏱️ 14.01.2022):

	```
	git clone https://github.com/cool-RR/PySnooper
	```
- [PyPi](https://pypi.org/project/pysnooper) (📥 140K / month · 📦 48 · ⏱️ 14.01.2022):
	```
	pip install pysnooper
	```
- [Conda](https://anaconda.org/conda-forge/pysnooper) (📥 44K · ⏱️ 20.01.2022):
	```
	conda install -c conda-forge pysnooper
	```
</details>
<details><summary><b><a href="https://github.com/eliben/pyelftools">pyelftools</a></b> (🥈29 ·  ⭐ 1.4K) - Parsing ELF and DWARF in Python. <code><a href="http://bit.ly/3rvuUlR">Unlicense</a></code></summary>

- [GitHub](https://github.com/eliben/pyelftools) (👨‍💻 82 · 🔀 440 · 📦 3.2K · 📋 180 - 33% open · ⏱️ 14.02.2022):

	```
	git clone https://github.com/eliben/pyelftools
	```
- [PyPi](https://pypi.org/project/pyelftools) (📥 980K / month · 📦 520 · ⏱️ 03.02.2022):
	```
	pip install pyelftools
	```
- [Conda](https://anaconda.org/conda-forge/pyelftools) (📥 84K · ⏱️ 11.02.2022):
	```
	conda install -c conda-forge pyelftools
	```
</details>
<details><summary><b><a href="https://github.com/agronholm/typeguard">typeguard</a></b> (🥈28 ·  ⭐ 810) - Run-time type checker for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/agronholm/typeguard) (👨‍💻 19 · 🔀 69 · 📋 190 - 18% open · ⏱️ 10.12.2021):

	```
	git clone https://github.com/agronholm/typeguard
	```
- [PyPi](https://pypi.org/project/typeguard) (📥 3.9M / month · 📦 300 · ⏱️ 10.12.2021):
	```
	pip install typeguard
	```
- [Conda](https://anaconda.org/conda-forge/typeguard) (📥 81K · ⏱️ 11.10.2021):
	```
	conda install -c conda-forge typeguard
	```
</details>
<details><summary><b><a href="https://github.com/cs01/gdbgui">gdbgui</a></b> (🥉27 ·  ⭐ 8.5K) - Browser-based frontend to gdb (gnu debugger). Add breakpoints, view.. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/cs01/gdbgui) (👨‍💻 39 · 🔀 480 · 📥 7.6K · 📦 160 · 📋 290 - 42% open · ⏱️ 16.01.2022):

	```
	git clone https://github.com/cs01/gdbgui
	```
- [PyPi](https://pypi.org/project/gdbgui) (📥 170K / month · 📦 2 · ⏱️ 06.09.2021):
	```
	pip install gdbgui
	```
</details>
<details><summary><b><a href="https://github.com/gruns/icecream">icecream</a></b> (🥉27 ·  ⭐ 5.8K) - Never use print() to debug again. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/gruns/icecream) (👨‍💻 18 · 🔀 120 · 📋 90 - 31% open · ⏱️ 16.03.2022):

	```
	git clone https://github.com/gruns/icecream
	```
- [PyPi](https://pypi.org/project/icecream) (📥 210K / month · 📦 51 · ⏱️ 15.02.2022):
	```
	pip install icecream
	```
- [Conda](https://anaconda.org/conda-forge/icecream) (📥 2.3K · ⏱️ 16.02.2022):
	```
	conda install -c conda-forge icecream
	```
</details>
<details><summary><b><a href="https://github.com/pdbpp/pdbpp">pdbpp</a></b> (🥉25 ·  ⭐ 880) - pdb++, a drop-in replacement for pdb (the Python debugger). <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/pdbpp/pdbpp) (👨‍💻 41 · 🔀 46 · 📦 2.7K · 📋 180 - 35% open · ⏱️ 22.02.2022):

	```
	git clone https://github.com/pdbpp/pdbpp
	```
- [PyPi](https://pypi.org/project/pdbpp) (📥 230K / month · 📦 590 · ⏱️ 09.07.2021):
	```
	pip install pdbpp
	```
- [Conda](https://anaconda.org/conda-forge/pdbpp) (📥 71K · ⏱️ 11.07.2021):
	```
	conda install -c conda-forge pdbpp
	```
</details>
<details><summary><b><a href="https://github.com/alexmojaki/snoop">snoop</a></b> (🥉22 ·  ⭐ 730) - A powerful set of Python debugging tools, based on PySnooper. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/alexmojaki/snoop) (👨‍💻 21 · 🔀 25 · 📋 40 - 45% open · ⏱️ 26.03.2022):

	```
	git clone https://github.com/alexmojaki/snoop
	```
- [PyPi](https://pypi.org/project/snoop) (📥 25K / month · 📦 12 · ⏱️ 11.11.2021):
	```
	pip install snoop
	```
- [Conda](https://anaconda.org/conda-forge/snoop) (📥 260 · ⏱️ 11.11.2021):
	```
	conda install -c conda-forge snoop
	```
</details>
<details><summary><b><a href="https://github.com/ionelmc/python-hunter">python-hunter</a></b> (🥉22 ·  ⭐ 660 · 📉) - Hunter is a flexible code tracing toolkit. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/ionelmc/python-hunter) (👨‍💻 9 · 🔀 37 · 📦 84 · 📋 87 - 42% open · ⏱️ 15.12.2021):

	```
	git clone https://github.com/ionelmc/python-hunter
	```
- [PyPi](https://pypi.org/project/hunter) (📥 14K / month · 📦 21 · ⏱️ 15.12.2021):
	```
	pip install hunter
	```
- [Conda](https://anaconda.org/conda-forge/hunter) (📥 4.1K · ⏱️ 16.12.2021):
	```
	conda install -c conda-forge hunter
	```
</details>
<details><summary><b><a href="https://github.com/alexmojaki/birdseye">Birdseye</a></b> (🥉21 ·  ⭐ 1.5K) - Graphical Python debugger which lets you easily view the values of all.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/alexmojaki/birdseye) (👨‍💻 10 · 🔀 70 · 📋 50 - 36% open · ⏱️ 26.02.2022):

	```
	git clone https://github.com/alexmojaki/birdseye
	```
- [PyPi](https://pypi.org/project/birdseye) (📥 3.6K / month · 📦 3 · ⏱️ 11.11.2021):
	```
	pip install birdseye
	```
</details>
<details><summary><b><a href="https://github.com/ionelmc/python-manhole">python-manhole</a></b> (🥉20 ·  ⭐ 320) - Debugging manhole for python applications. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/ionelmc/python-manhole) (👨‍💻 11 · 🔀 18 · 📦 90 · 📋 21 - 28% open · ⏱️ 02.02.2022):

	```
	git clone https://github.com/ionelmc/python-manhole
	```
- [PyPi](https://pypi.org/project/manhole) (📥 16K / month · 📦 38 · ⏱️ 08.04.2021):
	```
	pip install manhole
	```
- [Conda](https://anaconda.org/conda-forge/manhole) (📥 2.1K · ⏱️ 07.11.2021):
	```
	conda install -c conda-forge manhole
	```
</details>
<details><summary>Show 1 hidden projects...</summary>

- <b><a href="https://github.com/lmacken/pyrasite">pyrasite</a></b> (🥉21 ·  ⭐ 2.6K · 💀) - Inject code into running Python processes. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
</details>
<br>

## Testing Tools

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

🔗&nbsp;<b><a href="https://github.com/ml-tooling/best-of-web-python">best-of-web-python - Testing</a></b> ( ⭐ 1.5K)  - Testing libraries & tools for python web frameworks.

🔗&nbsp;<b><a href="https://docs.python.org/3/library/unittest.html">unittest</a></b>  - Unittest is a test framework included in the Python standard library.

<details><summary><b><a href="https://github.com/pytest-dev/pytest">pytest</a></b> (🥇48 ·  ⭐ 8.6K) - The pytest framework makes it easy to write small tests, yet scales.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytest-dev/pytest) (👨‍💻 780 · 🔀 2K · 📦 480K · 📋 4.9K - 15% open · ⏱️ 27.03.2022):

	```
	git clone https://github.com/pytest-dev/pytest
	```
- [PyPi](https://pypi.org/project/pytest) (📥 40M / month · 📦 81K · ⏱️ 17.03.2022):
	```
	pip install pytest
	```
- [Conda](https://anaconda.org/conda-forge/pytest) (📥 12M · ⏱️ 18.03.2022):
	```
	conda install -c conda-forge pytest
	```
</details>
<details><summary><b><a href="https://github.com/robotframework/robotframework">robotframework</a></b> (🥇41 ·  ⭐ 6.8K · 📉) - Generic automation framework for acceptance testing and.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/robotframework/robotframework) (👨‍💻 160 · 🔀 1.9K · 📥 520 · 📦 5.2K · 📋 3.8K - 5% open · ⏱️ 23.03.2022):

	```
	git clone https://github.com/robotframework/robotframework
	```
- [PyPi](https://pypi.org/project/robotframework) (📥 970K / month · 📦 1K · ⏱️ 23.03.2022):
	```
	pip install robotframework
	```
- [Conda](https://anaconda.org/conda-forge/robotframework) (📥 73K · ⏱️ 23.03.2022):
	```
	conda install -c conda-forge robotframework
	```
</details>
<details><summary><b><a href="https://github.com/HypothesisWorks/hypothesis">hypothesis</a></b> (🥇38 ·  ⭐ 5.8K) - Hypothesis is a powerful, flexible, and easy to use library for.. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code></summary>

- [GitHub](https://github.com/HypothesisWorks/hypothesis) (👨‍💻 260 · 🔀 490 · 📦 12K · 📋 1.2K - 4% open · ⏱️ 29.03.2022):

	```
	git clone https://github.com/HypothesisWorks/hypothesis
	```
- [PyPi](https://pypi.org/project/hypothesis) (📥 2.6M / month · 📦 1.9K · ⏱️ 29.03.2022):
	```
	pip install hypothesis
	```
- [Conda](https://anaconda.org/conda-forge/hypothesis) (📥 5.3M · ⏱️ 29.03.2022):
	```
	conda install -c conda-forge hypothesis
	```
</details>
<details><summary><b><a href="https://github.com/tox-dev/tox">tox</a></b> (🥇38 ·  ⭐ 2.7K) - Command line driven CI frontend and development task automation tool. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tox-dev/tox) (👨‍💻 260 · 🔀 400 · 📦 56K · 📋 1.3K - 3% open · ⏱️ 22.03.2022):

	```
	git clone https://github.com/tox-dev/tox
	```
- [PyPi](https://pypi.org/project/tox) (📥 4.4M / month · 📦 20K · ⏱️ 06.02.2022):
	```
	pip install tox
	```
- [Conda](https://anaconda.org/conda-forge/tox) (📥 420K · ⏱️ 29.12.2021):
	```
	conda install -c conda-forge tox
	```
</details>
<details><summary><b><a href="https://github.com/pytest-dev/pytest-cov">pytest-cov</a></b> (🥇35 ·  ⭐ 1.2K) - Coverage plugin for pytest. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytest-dev/pytest-cov) (👨‍💻 74 · 🔀 170 · 📦 120K · 📋 320 - 34% open · ⏱️ 02.02.2022):

	```
	git clone https://github.com/pytest-dev/pytest-cov
	```
- [PyPi](https://pypi.org/project/pytest-cov) (📥 14M / month · 📦 28K · ⏱️ 04.10.2021):
	```
	pip install pytest-cov
	```
- [Conda](https://anaconda.org/conda-forge/pytest-cov) (📥 4.9M · ⏱️ 04.10.2021):
	```
	conda install -c conda-forge pytest-cov
	```
</details>
<details><summary><b><a href="https://github.com/spulec/freezegun">freezegun</a></b> (🥈34 ·  ⭐ 3.2K) - Let your Python tests travel through time. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/spulec/freezegun) (👨‍💻 100 · 🔀 220 · 📋 270 - 37% open · ⏱️ 18.03.2022):

	```
	git clone https://github.com/spulec/freezegun
	```
- [PyPi](https://pypi.org/project/freezegun) (📥 5M / month · 📦 4.4K · ⏱️ 18.03.2022):
	```
	pip install freezegun
	```
- [Conda](https://anaconda.org/conda-forge/freezegun) (📥 330K · ⏱️ 18.03.2022):
	```
	conda install -c conda-forge freezegun
	```
</details>
<details><summary><b><a href="https://github.com/pytest-dev/pytest-mock">pytest-mock</a></b> (🥈34 ·  ⭐ 1.3K) - Thin-wrapper around the mock package for easier use with pytest. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytest-dev/pytest-mock) (👨‍💻 55 · 🔀 100 · 📦 25K · 📋 110 - 11% open · ⏱️ 28.03.2022):

	```
	git clone https://github.com/pytest-dev/pytest-mock
	```
- [PyPi](https://pypi.org/project/pytest-mock) (📥 5.7M / month · 📦 4.2K · ⏱️ 28.01.2022):
	```
	pip install pytest-mock
	```
- [Conda](https://anaconda.org/conda-forge/pytest-mock) (📥 1.4M · ⏱️ 31.01.2022):
	```
	conda install -c conda-forge pytest-mock
	```
</details>
<details><summary><b><a href="https://github.com/pytest-dev/pytest-xdist">pytest-xdist</a></b> (🥈34 ·  ⭐ 870) - pytest plugin for distributed testing and loop-on-failures.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytest-dev/pytest-xdist) (👨‍💻 80 · 🔀 160 · 📋 460 - 44% open · ⏱️ 28.03.2022):

	```
	git clone https://github.com/pytest-dev/pytest-xdist
	```
- [PyPi](https://pypi.org/project/pytest-xdist) (📥 6.7M / month · 📦 4.5K · ⏱️ 10.12.2021):
	```
	pip install pytest-xdist
	```
- [Conda](https://anaconda.org/conda-forge/pytest-xdist) (📥 2.5M · ⏱️ 10.12.2021):
	```
	conda install -c conda-forge pytest-xdist
	```
</details>
<details><summary><b><a href="https://github.com/asweigart/pyautogui">pyautogui</a></b> (🥈33 ·  ⭐ 6.4K) - A cross-platform GUI automation Python module for human beings. Used.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/asweigart/pyautogui) (👨‍💻 51 · 🔀 860 · 📦 14K · 📋 580 - 64% open · ⏱️ 14.09.2021):

	```
	git clone https://github.com/asweigart/pyautogui
	```
- [PyPi](https://pypi.org/project/pyautogui) (📥 480K / month · 📦 570 · ⏱️ 07.07.2021):
	```
	pip install pyautogui
	```
- [Conda](https://anaconda.org/conda-forge/pyautogui) (📥 140K · ⏱️ 11.11.2021):
	```
	conda install -c conda-forge pyautogui
	```
</details>
<details><summary><b><a href="https://github.com/pytest-dev/pytest-asyncio">pytest-asyncio</a></b> (🥈33 ·  ⭐ 920) - Pytest support for asyncio. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytest-dev/pytest-asyncio) (👨‍💻 37 · 🔀 100 · 📥 18 · 📋 200 - 15% open · ⏱️ 25.03.2022):

	```
	git clone https://github.com/pytest-dev/pytest-asyncio
	```
- [PyPi](https://pypi.org/project/pytest-asyncio) (📥 3.5M / month · 📦 1.9K · ⏱️ 25.03.2022):
	```
	pip install pytest-asyncio
	```
- [Conda](https://anaconda.org/conda-forge/pytest-asyncio) (📥 880K · ⏱️ 25.03.2022):
	```
	conda install -c conda-forge pytest-asyncio
	```
</details>
<details><summary><b><a href="https://github.com/microsoft/playwright-python">playwright-python</a></b> (🥈32 ·  ⭐ 6K) - Python version of the Playwright testing and automation.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/microsoft/playwright-python) (👨‍💻 24 · 🔀 550 · 📦 970 · 📋 620 - 5% open · ⏱️ 15.03.2022):

	```
	git clone https://github.com/microsoft/playwright-python
	```
- [PyPi](https://pypi.org/project/playwright) (📥 250K / month · 📦 54 · ⏱️ 23.03.2022):
	```
	pip install playwright
	```
</details>
<details><summary><b><a href="https://github.com/lk-geimfari/mimesis">mimesis</a></b> (🥈32 ·  ⭐ 3.5K) - Mimesis is a high-performance fake data generator for Python, which.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/lk-geimfari/mimesis) (👨‍💻 110 · 🔀 280 · 📥 250 · 📋 300 - 1% open · ⏱️ 28.03.2022):

	```
	git clone https://github.com/lk-geimfari/mimesis
	```
- [PyPi](https://pypi.org/project/mimesis) (📥 110K / month · 📦 58 · ⏱️ 25.01.2022):
	```
	pip install mimesis
	```
- [Conda](https://anaconda.org/conda-forge/mimesis) (📥 6.6K · ⏱️ 15.07.2020):
	```
	conda install -c conda-forge mimesis
	```
</details>
<details><summary><b><a href="https://github.com/nose-devs/nose2">nose2</a></b> (🥈31 ·  ⭐ 700) - The successor to nose, based on unittest2. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/nose-devs/nose2) (👨‍💻 73 · 🔀 140 · 📦 4.7K · 📋 250 - 19% open · ⏱️ 29.03.2022):

	```
	git clone https://github.com/nose-devs/nose2
	```
- [PyPi](https://pypi.org/project/nose2) (📥 410K / month · 📦 1.1K · ⏱️ 13.02.2022):
	```
	pip install nose2
	```
- [Conda](https://anaconda.org/conda-forge/nose2) (📥 46K · ⏱️ 02.02.2020):
	```
	conda install -c conda-forge nose2
	```
</details>
<details><summary><b><a href="https://github.com/pytest-dev/pytest-html">pytest-html</a></b> (🥈31 ·  ⭐ 480) - Plugin for generating HTML reports for pytest results. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytest-dev/pytest-html) (👨‍💻 43 · 🔀 180 · 📦 19K · 📋 290 - 35% open · ⏱️ 31.03.2022):

	```
	git clone https://github.com/pytest-dev/pytest-html
	```
- [PyPi](https://pypi.org/project/pytest-html) (📥 1.9M / month · 📦 670 · ⏱️ 13.12.2020):
	```
	pip install pytest-html
	```
- [Conda](https://anaconda.org/conda-forge/pytest-html) (📥 220K · ⏱️ 13.12.2020):
	```
	conda install -c conda-forge pytest-html
	```
</details>
<details><summary><b><a href="https://github.com/TheKevJames/coveralls-python">coveralls-python</a></b> (🥈31 ·  ⭐ 470) - Show coverage stats online via coveralls.io. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/TheKevJames/coveralls-python) (👨‍💻 63 · 🔀 180 · 📦 21K · 📋 150 - 3% open · ⏱️ 15.03.2022):

	```
	git clone https://github.com/TheKevJames/coveralls-python
	```
- [PyPi](https://pypi.org/project/coveralls) (📥 570K / month · 📦 9.2K · ⏱️ 11.11.2021):
	```
	pip install coveralls
	```
- [Conda](https://anaconda.org/conda-forge/coveralls) (📥 640K · ⏱️ 12.11.2021):
	```
	conda install -c conda-forge coveralls
	```
</details>
<details><summary><b><a href="https://github.com/FactoryBoy/factory_boy">factory_boy</a></b> (🥈30 ·  ⭐ 2.8K) - A test fixtures replacement for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/FactoryBoy/factory_boy) (👨‍💻 120 · 🔀 330 · 📋 510 - 30% open · ⏱️ 16.02.2022):

	```
	git clone https://github.com/FactoryBoy/factory_boy
	```
- [PyPi](https://pypi.org/project/factory_boy) (📥 2.1M / month · 📦 2.1K · ⏱️ 05.05.2018):
	```
	pip install factory_boy
	```
- [Conda](https://anaconda.org/conda-forge/factory_boy) (📥 94K · ⏱️ 26.10.2021):
	```
	conda install -c conda-forge factory_boy
	```
</details>
<details><summary><b><a href="https://github.com/pytest-dev/pytest-bdd">pytest-bdd</a></b> (🥈30 ·  ⭐ 980) - BDD library for the py.test runner. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytest-dev/pytest-bdd) (👨‍💻 46 · 🔀 170 · 📋 290 - 46% open · ⏱️ 09.03.2022):

	```
	git clone https://github.com/pytest-dev/pytest-bdd
	```
- [PyPi](https://pypi.org/project/pytest-bdd) (📥 350K / month · 📦 170 · ⏱️ 25.10.2021):
	```
	pip install pytest-bdd
	```
- [Conda](https://anaconda.org/conda-forge/pytest-bdd) (📥 45K · ⏱️ 03.02.2020):
	```
	conda install -c conda-forge pytest-bdd
	```
</details>
<details><summary><b><a href="https://github.com/hamcrest/PyHamcrest">PyHamcrest</a></b> (🥈30 ·  ⭐ 620) - Hamcrest matchers for Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/hamcrest/PyHamcrest) (👨‍💻 38 · 🔀 91 · 📋 70 - 27% open · ⏱️ 28.03.2022):

	```
	git clone https://github.com/hamcrest/PyHamcrest
	```
- [PyPi](https://pypi.org/project/pyhamcrest) (📥 1.6M / month · 📦 1.8K · ⏱️ 12.12.2021):
	```
	pip install pyhamcrest
	```
- [Conda](https://anaconda.org/conda-forge/pyhamcrest) (📥 390K · ⏱️ 13.12.2021):
	```
	conda install -c conda-forge pyhamcrest
	```
</details>
<details><summary><b><a href="https://github.com/CleanCut/green">green</a></b> (🥉29 ·  ⭐ 730) - Green is a clean, colorful, fast python test runner. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/CleanCut/green) (👨‍💻 37 · 🔀 74 · 📦 660 · 📋 170 - 1% open · ⏱️ 20.01.2022):

	```
	git clone https://github.com/CleanCut/green
	```
- [PyPi](https://pypi.org/project/green) (📥 15K / month · 📦 210 · ⏱️ 20.01.2022):
	```
	pip install green
	```
- [Conda](https://anaconda.org/conda-forge/green) (📥 93K · ⏱️ 21.03.2022):
	```
	conda install -c conda-forge green
	```
</details>
<details><summary><b><a href="https://github.com/pytest-dev/pytest-testinfra">pytest-testinfra</a></b> (🥉28 ·  ⭐ 2K) - Testinfra test your infrastructures. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytest-dev/pytest-testinfra) (👨‍💻 110 · 🔀 290 · 📋 320 - 36% open · ⏱️ 31.03.2022):

	```
	git clone https://github.com/pytest-dev/pytest-testinfra
	```
- [PyPi](https://pypi.org/project/pytest-testinfra) (📥 130K / month · 📦 5 · ⏱️ 10.02.2022):
	```
	pip install pytest-testinfra
	```
- [Conda](https://anaconda.org/conda-forge/pytest-testinfra) (📥 2.6K · ⏱️ 11.02.2022):
	```
	conda install -c conda-forge pytest-testinfra
	```
</details>
<details><summary><b><a href="https://github.com/wntrblm/nox">nox</a></b> (🥉28 ·  ⭐ 740) - Flexible test automation for Python. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/wntrblm/nox) (👨‍💻 70 · 🔀 110 · 📋 270 - 10% open · ⏱️ 22.03.2022):

	```
	git clone https://github.com/theacodes/nox
	```
- [PyPi](https://pypi.org/project/nox) (📥 1M / month · 📦 150 · ⏱️ 07.01.2022):
	```
	pip install nox
	```
- [Conda](https://anaconda.org/conda-forge/nox) (📥 69K · ⏱️ 13.01.2022):
	```
	conda install -c conda-forge nox
	```
</details>
<details><summary><b><a href="https://github.com/airspeed-velocity/asv">asv</a></b> (🥉28 ·  ⭐ 660) - Airspeed Velocity: A simple Python benchmarking tool with web-based reporting. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/airspeed-velocity/asv) (👨‍💻 67 · 🔀 140 · 📋 490 - 27% open · ⏱️ 29.03.2022):

	```
	git clone https://github.com/airspeed-velocity/asv
	```
- [PyPi](https://pypi.org/project/asv) (📥 22K / month · 📦 63 · ⏱️ 06.02.2022):
	```
	pip install asv
	```
- [Conda](https://anaconda.org/conda-forge/asv) (📥 580K · ⏱️ 06.02.2022):
	```
	conda install -c conda-forge asv
	```
</details>
<details><summary><b><a href="https://github.com/datadriventests/ddt">ddt</a></b> (🥉28 ·  ⭐ 400) - Data-Driven Tests for Python Unittest. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/datadriventests/ddt) (👨‍💻 36 · 🔀 100 · 📦 4.1K · 📋 53 - 28% open · ⏱️ 04.10.2021):

	```
	git clone https://github.com/datadriventests/ddt
	```
- [PyPi](https://pypi.org/project/ddt) (📥 250K / month · 📦 1.3K · ⏱️ 04.10.2021):
	```
	pip install ddt
	```
- [Conda](https://anaconda.org/conda-forge/ddt) (📥 68K · ⏱️ 15.05.2020):
	```
	conda install -c conda-forge ddt
	```
</details>
<details><summary><b><a href="https://github.com/dbader/pytest-mypy">pytest-mypy</a></b> (🥉28 ·  ⭐ 200) - Mypy static type checker plugin for Pytest. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/dbader/pytest-mypy) (👨‍💻 16 · 🔀 33 · 📦 1.6K · 📋 49 - 16% open · ⏱️ 07.02.2022):

	```
	git clone https://github.com/dbader/pytest-mypy
	```
- [PyPi](https://pypi.org/project/pytest-mypy) (📥 1M / month · 📦 390 · ⏱️ 07.02.2022):
	```
	pip install pytest-mypy
	```
- [Conda](https://anaconda.org/conda-forge/pytest-mypy) (📥 23K · ⏱️ 24.11.2020):
	```
	conda install -c conda-forge pytest-mypy
	```
</details>
<details><summary><b><a href="https://github.com/pytest-dev/pytest-randomly">pytest-randomly</a></b> (🥉26 ·  ⭐ 410) - Pytest plugin to randomly order tests and control random.seed. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pytest-dev/pytest-randomly) (👨‍💻 16 · 🔀 22 · 📋 48 - 12% open · ⏱️ 28.03.2022):

	```
	git clone https://github.com/pytest-dev/pytest-randomly
	```
- [PyPi](https://pypi.org/project/pytest-randomly) (📥 450K / month · 📦 180 · ⏱️ 10.01.2022):
	```
	pip install pytest-randomly
	```
- [Conda](https://anaconda.org/conda-forge/pytest-randomly) (📥 23K · ⏱️ 10.01.2022):
	```
	conda install -c conda-forge pytest-randomly
	```
</details>
<details><summary><b><a href="https://github.com/ionelmc/pytest-benchmark">pytest-benchmark</a></b> (🥉25 ·  ⭐ 870) - py.test fixture for benchmarking code. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/ionelmc/pytest-benchmark) (👨‍💻 35 · 🔀 92 · 📦 2.7K · 📋 160 - 50% open · ⏱️ 23.02.2022):

	```
	git clone https://github.com/ionelmc/pytest-benchmark
	```
- [PyPi](https://pypi.org/project/pytest-benchmark) (📥 410K / month · 📦 560 · ⏱️ 17.04.2021):
	```
	pip install pytest-benchmark
	```
- [Conda](https://anaconda.org/conda-forge/pytest-benchmark) (📥 1.2M · ⏱️ 18.04.2021):
	```
	conda install -c conda-forge pytest-benchmark
	```
</details>
<details><summary><b><a href="https://github.com/tarpas/pytest-testmon">pytest-testmon</a></b> (🥉24 ·  ⭐ 530) - Selects tests affected by changed files. Continous.. <code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tarpas/pytest-testmon) (👨‍💻 16 · 🔀 30 · 📋 120 - 20% open · ⏱️ 29.03.2022):

	```
	git clone https://github.com/tarpas/pytest-testmon
	```
- [PyPi](https://pypi.org/project/pytest-testmon) (📥 140K / month · 📦 54 · ⏱️ 11.03.2022):
	```
	pip install pytest-testmon
	```
- [Conda](https://anaconda.org/conda-forge/pytest-testmon) (📥 34K · ⏱️ 03.08.2019):
	```
	conda install -c conda-forge pytest-testmon
	```
</details>
<details><summary><b><a href="https://github.com/Erotemic/xdoctest">xdoctest</a></b> (🥉24 ·  ⭐ 140) - A rewrite of Pythons builtin doctest module (with pytest plugin.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/Erotemic/xdoctest) (👨‍💻 8 · 🔀 8 · 📦 2.3K · 📋 39 - 48% open · ⏱️ 25.03.2022):

	```
	git clone https://github.com/Erotemic/xdoctest
	```
- [PyPi](https://pypi.org/project/xdoctest) (📥 120K / month · 📦 77 · ⏱️ 25.03.2022):
	```
	pip install xdoctest
	```
- [Conda](https://anaconda.org/conda-forge/xdoctest) (📥 22K · ⏱️ 26.03.2022):
	```
	conda install -c conda-forge xdoctest
	```
</details>
<details><summary><b><a href="https://github.com/man-group/pytest-plugins">pytest-plugins</a></b> (🥉23 ·  ⭐ 430) - A grab-bag of nifty pytest plugins. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/man-group/pytest-plugins) (👨‍💻 58 · 🔀 63 · 📋 100 - 43% open · ⏱️ 25.01.2022):

	```
	git clone https://github.com/man-group/pytest-plugins
	```
- [PyPi](https://pypi.org/project/pytest-virtualenv) (📥 50K / month · 📦 63 · ⏱️ 28.05.2019):
	```
	pip install pytest-virtualenv
	```
- [Conda](https://anaconda.org/conda-forge/pytest-shutil) (📥 19K · ⏱️ 18.10.2021):
	```
	conda install -c conda-forge pytest-shutil
	```
</details>
<details><summary><b><a href="https://github.com/avast/pytest-docker">pytest-docker</a></b> (🥉22 ·  ⭐ 280) - Docker-based integration tests. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/avast/pytest-docker) (👨‍💻 13 · 🔀 51 · 📥 86 · 📋 56 - 55% open · ⏱️ 28.03.2022):

	```
	git clone https://github.com/avast/pytest-docker
	```
- [PyPi](https://pypi.org/project/pytest-docker) (📥 62K / month · 📦 29 · ⏱️ 28.03.2022):
	```
	pip install pytest-docker
	```
</details>
<details><summary><b><a href="https://github.com/TvoroG/pytest-lazy-fixture">pytest-lazy-fixture</a></b> (🥉21 ·  ⭐ 240) - It helps to use fixtures in pytest.mark.parametrize. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/TvoroG/pytest-lazy-fixture) (👨‍💻 9 · 🔀 18 · 📦 640 · 📋 35 - 42% open · ⏱️ 27.01.2022):

	```
	git clone https://github.com/tvorog/pytest-lazy-fixture
	```
- [PyPi](https://pypi.org/project/pytest-lazy-fixture) (📥 380K / month · 📦 54 · ⏱️ 01.02.2020):
	```
	pip install pytest-lazy-fixture
	```
- [Conda](https://anaconda.org/conda-forge/pytest-lazy-fixture) (📥 330K · ⏱️ 01.02.2020):
	```
	conda install -c conda-forge pytest-lazy-fixture
	```
</details>
<details><summary><b><a href="https://github.com/gabrielcnr/pytest-datadir">pytest-datadir</a></b> (🥉20 ·  ⭐ 160) - pytest plugin for manipulating test data directories and.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/gabrielcnr/pytest-datadir) (👨‍💻 7 · 🔀 17 · 📦 570 · 📋 16 - 31% open · ⏱️ 18.01.2022):

	```
	git clone https://github.com/gabrielcnr/pytest-datadir
	```
- [PyPi](https://pypi.org/project/pytest-datadir) (📥 120K / month · 📦 71 · ⏱️ 22.10.2019):
	```
	pip install pytest-datadir
	```
- [Conda](https://anaconda.org/conda-forge/pytest-datadir) (📥 110K · ⏱️ 23.10.2019):
	```
	conda install -c conda-forge pytest-datadir
	```
</details>
<details><summary>Show 9 hidden projects...</summary>

- <b><a href="https://github.com/nose-devs/nose">nose</a></b> (🥈33 ·  ⭐ 1.3K · 💀) - nose is nicer testing for python. <code><a href="https://tldrlegal.com/search?q=LGPL-2.1%2B">❗️LGPL-2.1+</a></code>
- <b><a href="https://github.com/Teemu/pytest-sugar">pytest-sugar</a></b> (🥉28 ·  ⭐ 840 · 💀) - a plugin for py.test that changes the default look and.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/xiaocong/uiautomator">uiautomator</a></b> (🥉26 ·  ⭐ 1.8K · 💀) - Python wrapper of Android uiautomator test tool. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/joeyespo/pytest-watch">pytest-watch</a></b> (🥉26 ·  ⭐ 630 · 💀) - Local continuous test runner with pytest and watchdog. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/nestorsalceda/mamba">Mamba Test Runner</a></b> (🥉24 ·  ⭐ 480 · 💀) - The definitive testing tool for Python. Born under the.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/sixpack/sixpack">sixpack</a></b> (🥉22 ·  ⭐ 1.7K · 💀) - Sixpack is a language-agnostic a/b-testing framework. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code>
- <b><a href="https://github.com/ActivisionGameScience/assertpy">assertpy</a></b> (🥉19 ·  ⭐ 250 · 💀) - Simple assertion library for unit testing in python with a fluent.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/emirozer/fake2db">fake2db</a></b> (🥉18 ·  ⭐ 2.1K · 💀) - create custom test databases that are populated with fake data. <code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code>
- <b><a href="https://github.com/pytest-dev/pytest-play">pytest-play</a></b> (🥉16 ·  ⭐ 65 · 💀) - pytest plugin that let you automate actions and.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code>
</details>
<br>

## Code Packaging

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

🔗&nbsp;<b><a href="https://packaging.python.org/overview/">Python.org Packaging</a></b>  - An Overview of Packaging for Python.

<details><summary><b><a href="https://github.com/pyinstaller/pyinstaller">pyinstaller</a></b> (🥇37 ·  ⭐ 9K) - Freeze (package) Python programs into stand-alone executables. <code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code></summary>

- [GitHub](https://github.com/pyinstaller/pyinstaller) (👨‍💻 420 · 🔀 1.8K · 📥 730K · 📋 4.5K - 7% open · ⏱️ 29.03.2022):

	```
	git clone https://github.com/pyinstaller/pyinstaller
	```
- [PyPi](https://pypi.org/project/pyinstaller) (📥 800K / month · 📦 140 · ⏱️ 05.03.2022):
	```
	pip install pyinstaller
	```
- [Conda](https://anaconda.org/conda-forge/pyinstaller) (📥 300K · ⏱️ 06.03.2022):
	```
	conda install -c conda-forge pyinstaller
	```
</details>
<details><summary><b><a href="https://github.com/pypa/packaging">packaging</a></b> (🥇37 ·  ⭐ 380 · 📈) - Core utilities for Python packages. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/pypa/packaging) (👨‍💻 78 · 🔀 180 · 📥 300 · 📦 340K · 📋 240 - 26% open · ⏱️ 19.03.2022):

	```
	git clone https://github.com/pypa/packaging
	```
- [PyPi](https://pypi.org/project/packaging) (📥 100M / month · 📦 17K · ⏱️ 18.11.2021):
	```
	pip install packaging
	```
- [Conda](https://anaconda.org/conda-forge/packaging) (📥 13M · ⏱️ 18.11.2021):
	```
	conda install -c conda-forge packaging
	```
</details>
<details><summary><b><a href="https://github.com/Nuitka/Nuitka">Nuitka</a></b> (🥈32 ·  ⭐ 6.6K) - Nuitka is a Python compiler written in Python. Its fully compatible.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/Nuitka/Nuitka) (👨‍💻 110 · 🔀 370 · 📋 1.3K - 15% open · ⏱️ 29.03.2022):

	```
	git clone https://github.com/Nuitka/Nuitka
	```
- [PyPi](https://pypi.org/project/nuitka) (📥 32K / month · 📦 36 · ⏱️ 19.03.2022):
	```
	pip install nuitka
	```
- [Conda](https://anaconda.org/conda-forge/nuitka) (📥 330K · ⏱️ 20.03.2022):
	```
	conda install -c conda-forge nuitka
	```
</details>
<details><summary><b><a href="https://github.com/pantsbuild/pex">pex</a></b> (🥈32 ·  ⭐ 2.1K) - A library and tool for generating .pex (Python EXecutable) files. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/pantsbuild/pex) (👨‍💻 100 · 🔀 220 · 📥 730K · 📋 830 - 17% open · ⏱️ 30.03.2022):

	```
	git clone https://github.com/pantsbuild/pex
	```
- [PyPi](https://pypi.org/project/pex) (📥 290K / month · 📦 130 · ⏱️ 25.03.2022):
	```
	pip install pex
	```
</details>
<details><summary><b><a href="https://github.com/marcelotduarte/cx_Freeze">cx_Freeze</a></b> (🥈30 ·  ⭐ 880) - Create standalone executables from Python scripts, with the same.. <code><a href="http://bit.ly/35wkF7y">Python-2.0</a></code></summary>

- [GitHub](https://github.com/marcelotduarte/cx_Freeze) (👨‍💻 94 · 🔀 170 · 📋 740 - 8% open · ⏱️ 31.03.2022):

	```
	git clone https://github.com/marcelotduarte/cx_Freeze
	```
- [PyPi](https://pypi.org/project/cx_freeze) (📥 60K / month · 📦 150 · ⏱️ 16.12.2017):
	```
	pip install cx_freeze
	```
- [Conda](https://anaconda.org/conda-forge/cx_freeze) (📥 120K · ⏱️ 26.03.2022):
	```
	conda install -c conda-forge cx_freeze
	```
</details>
<details><summary><b><a href="https://github.com/beeware/briefcase">briefcase</a></b> (🥈29 ·  ⭐ 1.4K) - Tools to support converting a Python project into a standalone.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/beeware/briefcase) (👨‍💻 90 · 🔀 220 · 📋 410 - 28% open · ⏱️ 22.03.2022):

	```
	git clone https://github.com/beeware/briefcase
	```
- [PyPi](https://pypi.org/project/briefcase) (📥 4.8K / month · 📦 17 · ⏱️ 28.02.2022):
	```
	pip install briefcase
	```
</details>
<details><summary><b><a href="https://github.com/indygreg/PyOxidizer">PyOxidizer</a></b> (🥉27 ·  ⭐ 3.6K) - A modern Python application packaging and distribution tool. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code></summary>

- [GitHub](https://github.com/indygreg/PyOxidizer) (👨‍💻 41 · 🔀 140 · 📥 2.2K · 📋 450 - 58% open · ⏱️ 30.03.2022):

	```
	git clone https://github.com/indygreg/PyOxidizer
	```
- [PyPi](https://pypi.org/project/pyoxidizer) (📥 3.3K / month · ⏱️ 08.03.2022):
	```
	pip install pyoxidizer
	```
</details>
<details><summary><b><a href="https://github.com/ronaldoussoren/py2app">py2app</a></b> (🥉27 ·  ⭐ 170) - py2app is a Python setuptools command which will allow you to make.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ronaldoussoren/py2app) (👨‍💻 29 · 🔀 20 · 📦 4K · 📋 400 - 29% open · ⏱️ 08.03.2022):

	```
	git clone https://github.com/ronaldoussoren/py2app
	```
- [PyPi](https://pypi.org/project/py2app) (📥 13K / month · 📦 830 · ⏱️ 27.09.2021):
	```
	pip install py2app
	```
</details>
<details><summary><b><a href="https://github.com/linkedin/shiv">shiv</a></b> (🥉25 ·  ⭐ 1.4K) - shiv is a command line utility for building fully self contained Python.. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/linkedin/shiv) (👨‍💻 35 · 🔀 79 · 📥 180 · 📋 100 - 29% open · ⏱️ 24.01.2022):

	```
	git clone https://github.com/linkedin/shiv
	```
- [PyPi](https://pypi.org/project/shiv) (📥 13K / month · 📦 12 · ⏱️ 24.01.2022):
	```
	pip install shiv
	```
</details>
<details><summary><b><a href="https://github.com/py2exe/py2exe">py2exe</a></b> (🥉24 ·  ⭐ 380) - A distutils extension to create standalone Windows programs from Python code. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/py2exe/py2exe) (👨‍💻 14 · 🔀 48 · 📥 8.4K · 📦 1.4K · 📋 100 - 5% open · ⏱️ 13.02.2022):

	```
	git clone https://github.com/py2exe/py2exe
	```
- [PyPi](https://pypi.org/project/py2exe) (📥 20K / month · 📦 180 · ⏱️ 13.02.2022):
	```
	pip install py2exe
	```
</details>
<details><summary><b><a href="https://github.com/takluyver/pynsist">pynsist</a></b> (🥉23 ·  ⭐ 760) - Build Windows installers for Python applications. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/takluyver/pynsist) (👨‍💻 29 · 🔀 110 · 📋 160 - 16% open · ⏱️ 21.03.2022):

	```
	git clone https://github.com/takluyver/pynsist
	```
- [PyPi](https://pypi.org/project/pynsist) (📥 2.2K / month · 📦 47 · ⏱️ 21.03.2022):
	```
	pip install pynsist
	```
</details>
<details><summary><b><a href="https://github.com/conda/constructor">constructor</a></b> (🥉23 ·  ⭐ 350) - tool for creating installers from conda packages. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/conda/constructor) (👨‍💻 51 · 🔀 140 · 📥 230 · 📦 12 · 📋 270 - 24% open · ⏱️ 31.03.2022):

	```
	git clone https://github.com/conda/constructor
	```
- [Conda](https://anaconda.org/anaconda/constructor) (📥 5.4K · ⏱️ 23.03.2022):
	```
	conda install -c anaconda constructor
	```
</details>
<details><summary><b><a href="https://github.com/facebookincubator/xar">xar</a></b> (🥉21 ·  ⭐ 1.5K) - executable archive format. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/facebookincubator/xar) (👨‍💻 32 · 🔀 48 · 📦 18 · 📋 29 - 27% open · ⏱️ 05.03.2022):

	```
	git clone https://github.com/facebookincubator/xar
	```
- [PyPi](https://pypi.org/project/xar) (📥 180 / month · ⏱️ 02.12.2020):
	```
	pip install xar
	```
</details>
<details><summary>Show 2 hidden projects...</summary>

- <b><a href="https://github.com/google/subpar">subpar</a></b> (🥉13 ·  ⭐ 520 · 💀) - Subpar is a utility for creating self-contained python.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/jamesabel/pyship">pyship</a></b> (🥉10 ·  ⭐ 16 · 💤) - pyship - ship Python desktop apps to end users. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>
<br>

## Build Tools

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/pypa/setuptools">setuptools</a></b> (🥇44 ·  ⭐ 1.6K · 📉) - Official project repository for the Setuptools build system. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pypa/setuptools) (👨‍💻 490 · 🔀 840 · 📥 120 · 📦 160K · 📋 2K - 23% open · ⏱️ 27.03.2022):

	```
	git clone https://github.com/pypa/setuptools
	```
- [PyPi](https://pypi.org/project/setuptools) (📥 170M / month · 📦 36K · ⏱️ 27.03.2022):
	```
	pip install setuptools
	```
- [Conda](https://anaconda.org/conda-forge/setuptools) (📥 36M · ⏱️ 31.03.2022):
	```
	conda install -c conda-forge setuptools
	```
</details>
<details><summary><b><a href="https://github.com/buildbot/buildbot">buildbot</a></b> (🥇37 ·  ⭐ 4.8K) - Python-based continuous integration testing framework; your pull.. <code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code></summary>

- [GitHub](https://github.com/buildbot/buildbot) (👨‍💻 810 · 🔀 1.6K · 📥 23K · 📦 270 · 📋 1.4K - 45% open · ⏱️ 18.03.2022):

	```
	git clone https://github.com/buildbot/buildbot
	```
- [PyPi](https://pypi.org/project/buildbot) (📥 60K / month · 📦 460 · ⏱️ 06.03.2022):
	```
	pip install buildbot
	```
- [Conda](https://anaconda.org/conda-forge/buildbot) (📥 51K · ⏱️ 07.03.2022):
	```
	conda install -c conda-forge buildbot
	```
</details>
<details><summary><b><a href="https://github.com/pypa/twine">twine</a></b> (🥈36 ·  ⭐ 1.2K) - Utilities for interacting with PyPI. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/pypa/twine) (👨‍💻 110 · 🔀 260 · 📦 60K · 📋 400 - 9% open · ⏱️ 31.03.2022):

	```
	git clone https://github.com/pypa/twine
	```
- [PyPi](https://pypi.org/project/twine) (📥 3.4M / month · 📦 12K · ⏱️ 31.03.2022):
	```
	pip install twine
	```
- [Conda](https://anaconda.org/conda-forge/twine) (📥 420K · ⏱️ 03.02.2022):
	```
	conda install -c conda-forge twine
	```
</details>
<details><summary><b><a href="https://github.com/pyinvoke/invoke">invoke</a></b> (🥈35 ·  ⭐ 3.5K · 📈) - Pythonic task management & command execution. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/pyinvoke/invoke) (👨‍💻 57 · 🔀 310 · 📦 11K · 📋 710 - 47% open · ⏱️ 25.03.2022):

	```
	git clone https://github.com/pyinvoke/invoke
	```
- [PyPi](https://pypi.org/project/invoke) (📥 2.6M / month · 📦 2.6K · ⏱️ 19.03.2022):
	```
	pip install invoke
	```
- [Conda](https://anaconda.org/conda-forge/invoke) (📥 540K · ⏱️ 19.03.2022):
	```
	conda install -c conda-forge invoke
	```
</details>
<details><summary><b><a href="https://github.com/pypa/setuptools_scm">setuptools_scm</a></b> (🥈34 ·  ⭐ 560) - the blessed package to manage your versions by scm tags. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pypa/setuptools_scm) (👨‍💻 100 · 🔀 160 · 📋 390 - 20% open · ⏱️ 30.03.2022):

	```
	git clone https://github.com/pypa/setuptools_scm
	```
- [PyPi](https://pypi.org/project/setuptools_scm) (📥 16M / month · 📦 380 · ⏱️ 09.08.2018):
	```
	pip install setuptools_scm
	```
- [Conda](https://anaconda.org/conda-forge/setuptools_scm) (📥 920K · ⏱️ 19.01.2022):
	```
	conda install -c conda-forge setuptools_scm
	```
</details>
<details><summary><b><a href="https://github.com/pypa/wheel">wheel</a></b> (🥈34 ·  ⭐ 310) - The official binary distribution format for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pypa/wheel) (👨‍💻 64 · 🔀 100 · 📋 340 - 9% open · ⏱️ 14.03.2022):

	```
	git clone https://github.com/pypa/wheel
	```
- [PyPi](https://pypi.org/project/wheel) (📥 120M / month · 📦 35K · ⏱️ 22.12.2021):
	```
	pip install wheel
	```
- [Conda](https://anaconda.org/conda-forge/wheel) (📥 28M · ⏱️ 22.12.2021):
	```
	conda install -c conda-forge wheel
	```
</details>
<details><summary><b><a href="https://github.com/SCons/scons">scons</a></b> (🥉32 ·  ⭐ 1.4K) - SCons - a software construction tool. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/SCons/scons) (👨‍💻 140 · 🔀 250 · 📥 420 · 📋 3.3K - 19% open · ⏱️ 29.03.2022):

	```
	git clone https://github.com/SCons/scons
	```
- [PyPi](https://pypi.org/project/scons) (📥 210K / month · 📦 37 · ⏱️ 17.12.2019):
	```
	pip install scons
	```
- [Conda](https://anaconda.org/conda-forge/scons) (📥 270K · ⏱️ 17.11.2021):
	```
	conda install -c conda-forge scons
	```
</details>
<details><summary><b><a href="https://github.com/pydoit/doit">doit</a></b> (🥉32 ·  ⭐ 1.3K) - task management & automation tool. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pydoit/doit) (👨‍💻 62 · 🔀 150 · 📦 900 · 📋 270 - 23% open · ⏱️ 27.03.2022):

	```
	git clone https://github.com/pydoit/doit
	```
- [PyPi](https://pypi.org/project/doit) (📥 290K / month · 📦 280 · ⏱️ 18.02.2022):
	```
	pip install doit
	```
- [Conda](https://anaconda.org/conda-forge/doit) (📥 80K · ⏱️ 24.02.2022):
	```
	conda install -c conda-forge doit
	```
</details>
<details><summary><b><a href="https://github.com/pypa/flit">flit</a></b> (🥉30 ·  ⭐ 1.7K) - Simplified packaging of Python modules. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/pypa/flit) (👨‍💻 52 · 🔀 93 · 📋 320 - 34% open · ⏱️ 23.02.2022):

	```
	git clone https://github.com/pypa/flit
	```
- [PyPi](https://pypi.org/project/flit) (📥 140K / month · 📦 230 · ⏱️ 23.02.2022):
	```
	pip install flit
	```
- [Conda](https://anaconda.org/conda-forge/flit) (📥 110K · ⏱️ 23.02.2022):
	```
	conda install -c conda-forge flit
	```
</details>
<details><summary><b><a href="https://github.com/pybuilder/pybuilder">pybuilder</a></b> (🥉30 ·  ⭐ 1.4K) - Software build automation tool for Python. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/pybuilder/pybuilder) (👨‍💻 36 · 🔀 240 · 📋 500 - 18% open · ⏱️ 24.02.2022):

	```
	git clone https://github.com/pybuilder/pybuilder
	```
- [PyPi](https://pypi.org/project/pybuilder) (📥 17K / month · 📦 60 · ⏱️ 24.02.2022):
	```
	pip install pybuilder
	```
- [Conda](https://anaconda.org/conda-forge/pybuilder) (📥 9.6K · ⏱️ 23.02.2022):
	```
	conda install -c conda-forge pybuilder
	```
</details>
<details><summary><b><a href="https://github.com/paver/paver">paver</a></b> (🥉24 ·  ⭐ 450 · 💤) - Python-based project scripting. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/paver/paver) (👨‍💻 45 · 🔀 79 · 📋 130 - 28% open · ⏱️ 21.06.2021):

	```
	git clone https://github.com/paver/paver
	```
- [PyPi](https://pypi.org/project/paver) (📥 34K / month · 📦 960 · ⏱️ 31.12.2017):
	```
	pip install paver
	```
- [Conda](https://anaconda.org/conda-forge/paver) (📥 24K · ⏱️ 24.07.2018):
	```
	conda install -c conda-forge paver
	```
</details>
<details><summary><b><a href="https://github.com/ml-tooling/universal-build">universal-build</a></b> (🥉15 ·  ⭐ 16) - Universal build utilities for containerized build pipelines. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ml-tooling/universal-build) (👨‍💻 4 · 🔀 6 · 📥 16 · 📦 9 · ⏱️ 17.11.2021):

	```
	git clone https://github.com/ml-tooling/universal-build
	```
- [PyPi](https://pypi.org/project/universal-build) (📥 830 / month · 📦 5 · ⏱️ 12.12.2020):
	```
	pip install universal-build
	```
</details>
<details><summary>Show 2 hidden projects...</summary>

- <b><a href="https://github.com/buildout/buildout">buildout</a></b> (🥉31 ·  ⭐ 530) - Buildout is a deployment automation tool written in and extended.. <code><a href="https://tldrlegal.com/search?q=ZPL-2.1">❗️ZPL-2.1</a></code>
- <b><a href="https://github.com/rags/pynt">pynt</a></b> (🥉17 ·  ⭐ 150 · 💀) - A pynt of Python build. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>
<br>

## System Monitoring & Profiling

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/giampaolo/psutil">psutil</a></b> (🥇44 ·  ⭐ 8.2K) - Cross-platform lib for process and system monitoring in Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/giampaolo/psutil) (👨‍💻 180 · 🔀 1.2K · 📦 150K · 📋 1.5K - 13% open · ⏱️ 18.03.2022):

	```
	git clone https://github.com/giampaolo/psutil
	```
- [PyPi](https://pypi.org/project/psutil) (📥 42M / month · 📦 15K · ⏱️ 29.12.2021):
	```
	pip install psutil
	```
- [Conda](https://anaconda.org/conda-forge/psutil) (📥 11M · ⏱️ 30.12.2021):
	```
	conda install -c conda-forge psutil
	```
</details>
<details><summary><b><a href="https://github.com/nicolargo/glances">Glances</a></b> (🥇35 ·  ⭐ 20K) - Glances an Eye on your system. A top/htop alternative for.. <code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code></summary>

- [GitHub](https://github.com/nicolargo/glances) (👨‍💻 150 · 🔀 1.3K · 📥 730 · 📦 420 · 📋 1.5K - 15% open · ⏱️ 20.03.2022):

	```
	git clone https://github.com/nicolargo/glances
	```
- [PyPi](https://pypi.org/project/glances) (📥 150K / month · 📦 50 · ⏱️ 22.11.2021):
	```
	pip install glances
	```
- [Conda](https://anaconda.org/conda-forge/glances) (📥 150K · ⏱️ 20.11.2021):
	```
	conda install -c conda-forge glances
	```
</details>
<details><summary><b><a href="https://github.com/plasma-umass/scalene">Scalene</a></b> (🥈32 ·  ⭐ 5.5K) - Scalene: a high-performance, high-precision CPU, GPU, and memory.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/plasma-umass/scalene) (👨‍💻 28 · 🔀 190 · 📦 96 · 📋 200 - 24% open · ⏱️ 24.03.2022):

	```
	git clone https://github.com/plasma-umass/scalene
	```
- [PyPi](https://pypi.org/project/scalene) (📥 8.3K / month · 📦 3 · ⏱️ 12.03.2022):
	```
	pip install scalene
	```
</details>
<details><summary><b><a href="https://github.com/benfred/py-spy">py-spy</a></b> (🥈30 ·  ⭐ 8.3K) - Sampling profiler for Python programs. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/benfred/py-spy) (👨‍💻 29 · 🔀 280 · 📥 8.2K · 📋 240 - 30% open · ⏱️ 17.01.2022):

	```
	git clone https://github.com/benfred/py-spy
	```
- [PyPi](https://pypi.org/project/py-spy) (📥 850K / month · 📦 35 · ⏱️ 13.11.2021):
	```
	pip install py-spy
	```
- [Conda](https://anaconda.org/conda-forge/py-spy) (📥 300K · ⏱️ 18.12.2021):
	```
	conda install -c conda-forge py-spy
	```
- [Cargo](https://crates.io/crates/py-spy) (📥 460 / month · ⏱️ 13.11.2021):
	```
	cargo install py-spy
	```
</details>
<details><summary><b><a href="https://github.com/pythonprofilers/memory_profiler">memory-profiler</a></b> (🥈30 ·  ⭐ 3.4K) - Monitor Memory usage of Python code. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/pythonprofilers/memory_profiler) (👨‍💻 95 · 🔀 330 · 📋 220 - 50% open · ⏱️ 20.03.2022):

	```
	git clone https://github.com/pythonprofilers/memory_profiler
	```
- [PyPi](https://pypi.org/project/memory_profiler) (📥 490K / month · 📦 270 · ⏱️ 16.08.2018):
	```
	pip install memory_profiler
	```
- [Conda](https://anaconda.org/conda-forge/memory_profiler) (📥 160K · ⏱️ 19.12.2021):
	```
	conda install -c conda-forge memory_profiler
	```
</details>
<details><summary><b><a href="https://github.com/joerick/pyinstrument">pyinstrument</a></b> (🥈29 ·  ⭐ 4.2K) - Call stack profiler for Python. Shows you why your code is slow!. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/joerick/pyinstrument) (👨‍💻 38 · 🔀 170 · 📦 590 · 📋 98 - 16% open · ⏱️ 17.12.2021):

	```
	git clone https://github.com/joerick/pyinstrument
	```
- [PyPi](https://pypi.org/project/pyinstrument) (📥 320K / month · 📦 97 · ⏱️ 14.11.2021):
	```
	pip install pyinstrument
	```
- [Conda](https://anaconda.org/conda-forge/pyinstrument) (📥 98K · ⏱️ 26.01.2022):
	```
	conda install -c conda-forge pyinstrument
	```
</details>
<details><summary><b><a href="https://github.com/pyutils/line_profiler">line_profiler</a></b> (🥈29 ·  ⭐ 3.5K) - Line-by-line profiling for Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/pyutils/line_profiler) (👨‍💻 29 · 🔀 250 · 📋 57 - 45% open · ⏱️ 21.03.2022):

	```
	git clone https://github.com/pyutils/line_profiler
	```
- [PyPi](https://pypi.org/project/line_profiler) (📥 150K / month · 📦 350 · ⏱️ 20.12.2017):
	```
	pip install line_profiler
	```
- [Conda](https://anaconda.org/conda-forge/line_profiler) (📥 230K · ⏱️ 22.03.2022):
	```
	conda install -c conda-forge line_profiler
	```
</details>
<details><summary><b><a href="https://github.com/python-diamond/Diamond">Diamond</a></b> (🥈29 ·  ⭐ 1.7K) - Diamond is a python daemon that collects system metrics and publishes.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/python-diamond/Diamond) (👨‍💻 370 · 🔀 590 · 📦 82 · 📋 380 - 61% open · ⏱️ 11.03.2022):

	```
	git clone https://github.com/python-diamond/Diamond
	```
- [PyPi](https://pypi.org/project/diamond) (📥 36K / month · 📦 32 · ⏱️ 25.11.2016):
	```
	pip install diamond
	```
</details>
<details><summary><b><a href="https://github.com/sumerc/yappi">Yappi</a></b> (🥉28 ·  ⭐ 870) - Yet Another Python Profiler, but this time thread&coroutine&greenlet aware. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/sumerc/yappi) (👨‍💻 26 · 🔀 52 · 📦 560 · 📋 55 - 30% open · ⏱️ 08.12.2021):

	```
	git clone https://github.com/sumerc/yappi
	```
- [PyPi](https://pypi.org/project/yappi) (📥 740K / month · 📦 340 · ⏱️ 15.12.2021):
	```
	pip install yappi
	```
- [Conda](https://anaconda.org/conda-forge/yappi) (📥 98K · ⏱️ 30.03.2022):
	```
	conda install -c conda-forge yappi
	```
</details>
<details><summary><b><a href="https://github.com/aristocratos/bpytop">Bpytop</a></b> (🥉27 ·  ⭐ 8.4K) - Linux/OSX/FreeBSD resource monitor. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/aristocratos/bpytop) (👨‍💻 35 · 🔀 330 · 📋 280 - 21% open · ⏱️ 06.03.2022):

	```
	git clone https://github.com/aristocratos/bpytop
	```
- [PyPi](https://pypi.org/project/bpytop) (📥 9.8K / month · 📦 1 · ⏱️ 22.12.2021):
	```
	pip install bpytop
	```
- [Conda](https://anaconda.org/conda-forge/bpytop) (📥 4.2K · ⏱️ 22.12.2021):
	```
	conda install -c conda-forge bpytop
	```
</details>
<details><summary><b><a href="https://github.com/pympler/pympler">pympler</a></b> (🥉27 ·  ⭐ 900) - Development tool to measure, monitor and analyze the memory behavior.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/pympler/pympler) (👨‍💻 29 · 🔀 75 · 📋 90 - 44% open · ⏱️ 29.12.2021):

	```
	git clone https://github.com/pympler/pympler
	```
- [PyPi](https://pypi.org/project/pympler) (📥 1.6M / month · 📦 290 · ⏱️ 22.12.2021):
	```
	pip install pympler
	```
- [Conda](https://anaconda.org/conda-forge/pympler) (📥 180K · ⏱️ 14.10.2020):
	```
	conda install -c conda-forge pympler
	```
</details>
<details><summary><b><a href="https://github.com/alexmojaki/heartrate">heartrate</a></b> (🥉19 ·  ⭐ 1.4K) - Simple real time visualisation of the execution of a Python program. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/alexmojaki/heartrate) (👨‍💻 3 · 🔀 120 · 📦 39 · 📋 7 - 57% open · ⏱️ 13.11.2021):

	```
	git clone https://github.com/alexmojaki/heartrate
	```
- [PyPi](https://pypi.org/project/heartrate) (📥 1K / month · 📦 3 · ⏱️ 13.11.2021):
	```
	pip install heartrate
	```
- [Conda](https://anaconda.org/conda-forge/heartrate) (📥 500 · ⏱️ 13.11.2021):
	```
	conda install -c conda-forge heartrate
	```
</details>
<details><summary><b><a href="https://github.com/csurfer/pyheat">pyheat</a></b> (🥉18 ·  ⭐ 720) - pprofile + matplotlib = Python program profiled as an awesome heatmap!. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/csurfer/pyheat) (👨‍💻 5 · 🔀 40 · 📦 37 · 📋 14 - 35% open · ⏱️ 18.09.2021):

	```
	git clone https://github.com/csurfer/pyheat
	```
- [PyPi](https://pypi.org/project/py-heat) (📥 1.6K / month · 📦 6 · ⏱️ 06.12.2018):
	```
	pip install py-heat
	```
</details>
<details><summary>Show 4 hidden projects...</summary>

- <b><a href="https://github.com/nvdv/vprof">vprof</a></b> (🥉23 ·  ⭐ 3.8K · 💀) - Visual profiler for Python. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code>
- <b><a href="https://github.com/fabianp/memory_profiler">memory_profiler</a></b> (🥉22 ·  ⭐ 71 · 💀) - Monitor Memory usage of Python code. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/what-studio/profiling">Profiling</a></b> (🥉21 ·  ⭐ 3K · 💀) - Was an interactive continuous Python profiler. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/agermanidis/livepython">livepython</a></b> (🥉12 ·  ⭐ 2.5K · 💀) - Visually trace Python code in real-time. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>
<br>

## AST Tools

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/python/typed_ast">typed_ast</a></b> (🥇30 ·  ⭐ 200) - Modified fork of CPythons ast module that parses `# type:` comments. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/python/typed_ast) (👨‍💻 25 · 🔀 51 · 📋 89 - 5% open · ⏱️ 25.01.2022):

	```
	git clone https://github.com/python/typed_ast
	```
- [PyPi](https://pypi.org/project/typed_ast) (📥 13M / month · 📦 5.5K · ⏱️ 24.01.2022):
	```
	pip install typed_ast
	```
- [Conda](https://anaconda.org/conda-forge/typed-ast) (📥 4.1M · ⏱️ 24.01.2022):
	```
	conda install -c conda-forge typed-ast
	```
</details>
<details><summary><b><a href="https://github.com/berkerpeksag/astor">astor</a></b> (🥈29 ·  ⭐ 650) - Python AST read/write. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/berkerpeksag/astor) (👨‍💻 31 · 🔀 85 · 📋 110 - 31% open · ⏱️ 27.10.2021):

	```
	git clone https://github.com/berkerpeksag/astor
	```
- [PyPi](https://pypi.org/project/astor) (📥 5.1M / month · 📦 2.1K · ⏱️ 10.12.2019):
	```
	pip install astor
	```
- [Conda](https://anaconda.org/conda-forge/astor) (📥 1.5M · ⏱️ 01.07.2020):
	```
	conda install -c conda-forge astor
	```
</details>
<details><summary><b><a href="https://github.com/serge-sans-paille/gast">gast</a></b> (🥉28 ·  ⭐ 120) - Python AST that abstracts the underlying Python version. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/serge-sans-paille/gast) (👨‍💻 10 · 🔀 25 · 📦 81K · 📋 28 - 3% open · ⏱️ 24.02.2022):

	```
	git clone https://github.com/serge-sans-paille/gast
	```
- [PyPi](https://pypi.org/project/gast) (📥 12M / month · 📦 1.9K · ⏱️ 13.11.2021):
	```
	pip install gast
	```
- [Conda](https://anaconda.org/conda-forge/gast) (📥 1.4M · ⏱️ 15.11.2021):
	```
	conda install -c conda-forge gast
	```
</details>
<details><summary><b><a href="https://github.com/newville/asteval">asteval</a></b> (🥉24 ·  ⭐ 130) - minimalistic evaluator of python expression using ast module. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/newville/asteval) (👨‍💻 19 · 🔀 32 · 📋 59 - 16% open · ⏱️ 07.02.2022):

	```
	git clone https://github.com/newville/asteval
	```
- [PyPi](https://pypi.org/project/asteval) (📥 150K / month · 📦 160 · ⏱️ 16.01.2022):
	```
	pip install asteval
	```
- [Conda](https://anaconda.org/conda-forge/asteval) (📥 160K · ⏱️ 27.02.2021):
	```
	conda install -c conda-forge asteval
	```
</details>
<details><summary>Show 1 hidden projects...</summary>

- <b><a href="https://github.com/simonpercivall/astunparse">astunparse</a></b> (🥉27 ·  ⭐ 180 · 💀) - An AST unparser for Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
</details>
<br>

## Others

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/pre-commit/pre-commit">pre-commit</a></b> (🥇39 ·  ⭐ 7.8K) - A framework for managing and maintaining multi-language pre-commit.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pre-commit/pre-commit) (👨‍💻 130 · 🔀 540 · 📥 44K · 📦 45K · 📋 1.4K - 1% open · ⏱️ 30.03.2022):

	```
	git clone https://github.com/pre-commit/pre-commit
	```
- [PyPi](https://pypi.org/project/pre-commit) (📥 4.9M / month · 📦 2.8K · ⏱️ 18.01.2022):
	```
	pip install pre-commit
	```
- [Conda](https://anaconda.org/conda-forge/pre-commit) (📥 1.1M · ⏱️ 19.01.2022):
	```
	conda install -c conda-forge pre-commit
	```
</details>

---

## Related Resources

- [**Best-of lists**](https://best-of.org): Discover other best-of lists with awesome open-source projects on all kinds of topics.

## Contribution

Contributions are encouraged and always welcome! If you like to add or update projects, choose one of the following ways:

- Open an issue by selecting one of the provided categories from the [issue page](https://github.com/ml-tooling/best-of-python-dev/issues/new/choose) and fill in the requested information.
- Modify the [projects.yaml](https://github.com/ml-tooling/best-of-python-dev/blob/main/projects.yaml) with your additions or changes, and submit a pull request. This can also be done directly via the [Github UI](https://github.com/ml-tooling/best-of-python-dev/edit/main/projects.yaml).

If you like to contribute to or share suggestions regarding the project metadata collection or markdown generation, please refer to the [best-of-generator](https://github.com/best-of-lists/best-of-generator) repository. If you like to create your own best-of list, we recommend to follow [this guide](https://github.com/best-of-lists/best-of/blob/main/create-best-of-list.md).

For more information on how to add or update projects, please read the [contribution guidelines](https://github.com/ml-tooling/best-of-python-dev/blob/main/CONTRIBUTING.md). By participating in this project, you agree to abide by its [Code of Conduct](https://github.com/ml-tooling/best-of-python-dev/blob/main/.github/CODE_OF_CONDUCT.md).

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](https://creativecommons.org/licenses/by-sa/4.0/)
