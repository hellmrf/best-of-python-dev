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
    <a href="#Contents" title="Project Count"><img src="https://img.shields.io/badge/projects-250-blue.svg?color=5ac4bf"></a>
    <a href="#Contribution" title="Contributions are welcome"><img src="https://img.shields.io/badge/contributions-welcome-green.svg"></a>
    <a href="https://github.com/ml-tooling/best-of-python-dev/releases" title="Best-of Updates"><img src="https://img.shields.io/github/release-date/ml-tooling/best-of-python-dev?color=green&label=updated"></a>
    <a href="https://mltooling.substack.com/subscribe" title="Subscribe to newsletter"><img src="http://bit.ly/2Md9rxM"></a>
    <a href="https://twitter.com/mltooling" title="Follow on Twitter"><img src="https://img.shields.io/twitter/follow/mltooling.svg?style=social&label=Follow"></a>
</p>

This curated list contains 250 awesome open-source projects with a total of 630K stars grouped into 15 categories. All projects are ranked by a project-quality score, which is calculated based on various metrics automatically collected from GitHub and different package managers. If you like to add or update projects, feel free to open an [issue](https://github.com/ml-tooling/best-of-python-dev/issues/new/choose), submit a [pull request](https://github.com/ml-tooling/best-of-python-dev/pulls), or directly edit the [projects.yaml](https://github.com/ml-tooling/best-of-python-dev/edit/main/projects.yaml). Contributions are very welcome!

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
- [Documentation](#documentation) _26 projects_
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

<details><summary><b><a href="https://github.com/python/mypy">mypy</a></b> (🥇33 ·  ⭐ 12K) - Optional static typing for Python 3 and 2 (PEP 484). <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/python/mypy) (👨‍💻 500 · 🔀 1.9K · 📦 49K · 📋 6.9K - 28% open · ⏱️ 04.11.2021):

	```
	git clone https://github.com/python/mypy
	```
- [PyPi](https://pypi.org/project/mypy) (📦 6.1K · ⏱️ 22.06.2021):
	```
	pip install mypy
	```
- [Conda](https://anaconda.org/conda-forge/mypy) (📥 1.4M · ⏱️ 03.11.2021):
	```
	conda install -c conda-forge mypy
	```
</details>
<details><summary><b><a href="https://github.com/PyCQA/pyflakes">pyflakes</a></b> (🥇33 ·  ⭐ 1.1K) - A simple program which checks Python source files for errors. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/PyCQA/pyflakes) (👨‍💻 78 · 🔀 160 · 📦 100K · 📋 440 - 18% open · ⏱️ 06.10.2021):

	```
	git clone https://github.com/PyCQA/pyflakes
	```
- [PyPi](https://pypi.org/project/pyflakes) (📥 14M / month · 📦 26K · ⏱️ 06.10.2021):
	```
	pip install pyflakes
	```
- [Conda](https://anaconda.org/conda-forge/pyflakes) (📥 3.2M · ⏱️ 07.10.2021):
	```
	conda install -c conda-forge pyflakes
	```
</details>
<details><summary><b><a href="https://github.com/PyCQA/pycodestyle">pycodestyle</a></b> (🥇31 ·  ⭐ 4.4K) - Simple Python style checker in one Python file. <code><a href="https://tldrlegal.com/search?q=Saxpath">❗️Saxpath</a></code></summary>

- [GitHub](https://github.com/PyCQA/pycodestyle) (👨‍💻 130 · 🔀 610 · 📦 170K · 📋 660 - 17% open · ⏱️ 13.10.2021):

	```
	git clone https://github.com/PyCQA/pycodestyle
	```
- [PyPi](https://pypi.org/project/pycodestyle) (📥 20M / month · 📦 21K · ⏱️ 11.10.2021):
	```
	pip install pycodestyle
	```
- [Conda](https://anaconda.org/conda-forge/pycodestyle) (📥 3.4M · ⏱️ 11.10.2021):
	```
	conda install -c conda-forge pycodestyle
	```
</details>
<details><summary><b><a href="https://github.com/PyCQA/pylint">pylint</a></b> (🥇31 ·  ⭐ 3.6K) - It's not just a linter that annoys you!. <code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code></summary>

- [GitHub](https://github.com/PyCQA/pylint) (👨‍💻 420 · 🔀 760 · 📋 3.7K - 19% open · ⏱️ 04.11.2021):

	```
	git clone https://github.com/PyCQA/pylint
	```
- [PyPi](https://pypi.org/project/pylint) (📥 9.3M / month · 📦 38K · ⏱️ 16.09.2021):
	```
	pip install pylint
	```
- [Conda](https://anaconda.org/conda-forge/pylint) (📥 2.4M · ⏱️ 17.09.2021):
	```
	conda install -c conda-forge pylint
	```
</details>
<details><summary><b><a href="https://github.com/davidhalter/parso">parso</a></b> (🥇31 ·  ⭐ 460) - A Python Parser. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/davidhalter/parso) (👨‍💻 43 · 🔀 75 · 📦 160K · 📋 100 - 7% open · ⏱️ 15.09.2021):

	```
	git clone https://github.com/davidhalter/parso
	```
- [PyPi](https://pypi.org/project/parso) (📥 23M / month · 📦 11K · ⏱️ 30.03.2021):
	```
	pip install parso
	```
- [Conda](https://anaconda.org/conda-forge/parso) (📥 5.4M · ⏱️ 31.03.2021):
	```
	conda install -c conda-forge parso
	```
</details>
<details><summary><b><a href="https://github.com/wemake-services/wemake-python-styleguide">wemake-python-styleguide</a></b> (🥈30 ·  ⭐ 1.7K) - The strictest and most opinionated python linter ever!. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/wemake-services/wemake-python-styleguide) (👨‍💻 160 · 🔀 310 · 📦 770 · 📋 990 - 9% open · ⏱️ 03.11.2021):

	```
	git clone https://github.com/wemake-services/wemake-python-styleguide
	```
- [PyPi](https://pypi.org/project/wemake-python-styleguide) (📥 120K / month · 📦 14 · ⏱️ 21.06.2021):
	```
	pip install wemake-python-styleguide
	```
</details>
<details><summary><b><a href="https://github.com/PyCQA/flake8">flake8</a></b> (🥈30 ·  ⭐ 1.6K · 📉) - Flake8 is a wrapper around these tools: PyFlakes; pycodestyle; Ned.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/PyCQA/flake8) (👨‍💻 160 · 🔀 170 · 📦 200K · 📋 1.3K - 2% open · ⏱️ 02.11.2021):

	```
	git clone https://github.com/PyCQA/flake8
	```
- [PyPi](https://pypi.org/project/flake8) (📦 71K · ⏱️ 11.10.2021):
	```
	pip install flake8
	```
- [Conda](https://anaconda.org/conda-forge/flake8) (📥 3.2M · ⏱️ 02.11.2021):
	```
	conda install -c conda-forge flake8
	```
</details>
<details><summary><b><a href="https://github.com/PyCQA/pydocstyle">pydocstyle</a></b> (🥈30 ·  ⭐ 820) - docstring style checker. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/PyCQA/pydocstyle) (👨‍💻 74 · 🔀 150 · 📥 56 · 📦 20K · 📋 270 - 28% open · ⏱️ 10.10.2021):

	```
	git clone https://github.com/PyCQA/pydocstyle
	```
- [PyPi](https://pypi.org/project/pydocstyle) (📥 2.1M / month · 📦 3.9K · ⏱️ 17.05.2021):
	```
	pip install pydocstyle
	```
- [Conda](https://anaconda.org/conda-forge/pydocstyle) (📥 460K · ⏱️ 18.05.2021):
	```
	conda install -c conda-forge pydocstyle
	```
</details>
<details><summary><b><a href="https://github.com/PyCQA/flake8-bugbear">flake8-bugbear</a></b> (🥈29 ·  ⭐ 620) - A plugin for Flake8 finding likely bugs and design problems.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://cdn.iconscout.com/icon/free/png-256/8-eight-digital-number-numerical-numbers-36025.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PyCQA/flake8-bugbear) (👨‍💻 43 · 🔀 52 · 📦 5.5K · 📋 100 - 41% open · ⏱️ 29.10.2021):

	```
	git clone https://github.com/PyCQA/flake8-bugbear
	```
- [PyPi](https://pypi.org/project/flake8-bugbear) (📥 1.2M / month · 📦 1K · ⏱️ 29.09.2021):
	```
	pip install flake8-bugbear
	```
- [Conda](https://anaconda.org/conda-forge/flake8-bugbear) (📥 500K · ⏱️ 29.09.2021):
	```
	conda install -c conda-forge flake8-bugbear
	```
</details>
<details><summary><b><a href="https://github.com/openstack/hacking">hacking</a></b> (🥈29 ·  ⭐ 220) - OpenStack Hacking Style Checks. Mirror of code maintained at.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://cdn.iconscout.com/icon/free/png-256/8-eight-digital-number-numerical-numbers-36025.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/openstack/hacking) (👨‍💻 180 · 🔀 66 · ⏱️ 07.10.2021):

	```
	git clone https://github.com/openstack/hacking
	```
- [PyPi](https://pypi.org/project/hacking) (📥 550K / month · 📦 8.7K · ⏱️ 21.04.2021):
	```
	pip install hacking
	```
</details>
<details><summary><b><a href="https://github.com/google/pytype">pytype</a></b> (🥈28 ·  ⭐ 3.5K) - A static type analyzer for Python code. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/google/pytype) (👨‍💻 69 · 🔀 220 · 📋 450 - 21% open · ⏱️ 02.11.2021):

	```
	git clone https://github.com/google/pytype
	```
- [PyPi](https://pypi.org/project/pytype) (📥 140K / month · 📦 88 · ⏱️ 02.11.2021):
	```
	pip install pytype
	```
- [Conda](https://anaconda.org/conda-forge/pytype) (📥 62K · ⏱️ 13.10.2020):
	```
	conda install -c conda-forge pytype
	```
</details>
<details><summary><b><a href="https://github.com/PyCQA/pylint-django">pylint-django</a></b> (🥈28 ·  ⭐ 490 · 💤) - Pylint plugin for improving code analysis for when.. <code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code> <code><img src="https://www.pylint.org/ico/favicon.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PyCQA/pylint-django) (👨‍💻 58 · 🔀 100 · 📥 200 · 📦 15K · 📋 180 - 18% open · ⏱️ 26.04.2021):

	```
	git clone https://github.com/PyCQA/pylint-django
	```
- [PyPi](https://pypi.org/project/pylint-django) (📥 700K / month · 📦 2.2K · ⏱️ 09.04.2021):
	```
	pip install pylint-django
	```
- [Conda](https://anaconda.org/conda-forge/pylint-django) (📥 87K · ⏱️ 27.09.2021):
	```
	conda install -c conda-forge pylint-django
	```
</details>
<details><summary><b><a href="https://github.com/coala/coala">coala</a></b> (🥈27 ·  ⭐ 3.3K) - coala provides a unified command-line interface for linting and.. <code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code></summary>

- [GitHub](https://github.com/coala/coala) (👨‍💻 480 · 🔀 1.4K · 📥 150 · 📦 10 · 📋 3.2K - 26% open · ⏱️ 11.06.2021):

	```
	git clone https://github.com/coala/coala
	```
- [PyPi](https://pypi.org/project/coala-bears) (📥 2.2K / month · 📦 210 · ⏱️ 10.11.2017):
	```
	pip install coala-bears
	```
</details>
<details><summary><b><a href="https://github.com/zheller/flake8-quotes">flake8-quotes</a></b> (🥈27 ·  ⭐ 130) - Flake8 extension for checking quotes in python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://cdn.iconscout.com/icon/free/png-256/8-eight-digital-number-numerical-numbers-36025.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/zheller/flake8-quotes) (👨‍💻 30 · 🔀 34 · 📦 3.8K · 📋 43 - 6% open · ⏱️ 19.10.2021):

	```
	git clone https://github.com/zheller/flake8-quotes
	```
- [PyPi](https://pypi.org/project/flake8-quotes) (📥 640K / month · 📦 1.4K · ⏱️ 19.10.2021):
	```
	pip install flake8-quotes
	```
- [Conda](https://anaconda.org/conda-forge/flake8-quotes) (📥 580K · ⏱️ 19.10.2021):
	```
	conda install -c conda-forge flake8-quotes
	```
</details>
<details><summary><b><a href="https://github.com/gforcada/flake8-isort">flake8-isort</a></b> (🥈27 ·  ⭐ 110) - flake8 plugin that integrates isort. <code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code> <code><img src="https://cdn.iconscout.com/icon/free/png-256/8-eight-digital-number-numerical-numbers-36025.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/gforcada/flake8-isort) (👨‍💻 29 · 🔀 40 · 📦 4K · 📋 53 - 24% open · ⏱️ 15.10.2021):

	```
	git clone https://github.com/gforcada/flake8-isort
	```
- [PyPi](https://pypi.org/project/flake8-isort) (📥 530K / month · 📦 930 · ⏱️ 14.10.2021):
	```
	pip install flake8-isort
	```
- [Conda](https://anaconda.org/conda-forge/flake8-isort) (📥 14K · ⏱️ 14.10.2021):
	```
	conda install -c conda-forge flake8-isort
	```
</details>
<details><summary><b><a href="https://github.com/microsoft/pyright">pyright</a></b> (🥈25 ·  ⭐ 7.3K) - Static type checker for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/microsoft/pyright) (👨‍💻 64 · 🔀 390 · 📦 140 · 📋 2K - 0% open · ⏱️ 04.11.2021):

	```
	git clone https://github.com/Microsoft/pyright
	```
- [NPM](https://www.npmjs.com/package/pyright) (📥 140K / month · 📦 4 · ⏱️ 01.11.2021):
	```
	npm install pyright
	```
</details>
<details><summary><b><a href="https://github.com/facebook/pyre-check">pyre-check</a></b> (🥈25 ·  ⭐ 5.6K) - Performant type-checking for python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/facebook/pyre-check) (👨‍💻 180 · 🔀 370 · 📋 280 - 27% open · ⏱️ 04.11.2021):

	```
	git clone https://github.com/facebook/pyre-check
	```
- [PyPi](https://pypi.org/project/pyre-check) (📥 25K / month · 📦 46 · ⏱️ 29.10.2021):
	```
	pip install pyre-check
	```
</details>
<details><summary><b><a href="https://github.com/mgedmin/check-manifest">check-manifest</a></b> (🥈25 ·  ⭐ 240) - Tool to check the completeness of MANIFEST.in for Python packages. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/mgedmin/check-manifest) (👨‍💻 20 · 🔀 31 · 📦 6.8K · 📋 88 - 18% open · ⏱️ 16.10.2021):

	```
	git clone https://github.com/mgedmin/check-manifest
	```
- [PyPi](https://pypi.org/project/check-manifest) (📥 200K / month · 📦 1.8K · ⏱️ 22.09.2021):
	```
	pip install check-manifest
	```
- [Conda](https://anaconda.org/conda-forge/check-manifest) (📥 34K · ⏱️ 22.09.2021):
	```
	conda install -c conda-forge check-manifest
	```
</details>
<details><summary><b><a href="https://github.com/terrencepreilly/darglint">darglint</a></b> (🥉24 ·  ⭐ 360) - A python documentation linter which checks that the docstring description.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/terrencepreilly/darglint) (👨‍💻 22 · 🔀 29 · 📦 1.1K · 📋 140 - 32% open · ⏱️ 18.10.2021):

	```
	git clone https://github.com/terrencepreilly/darglint
	```
- [PyPi](https://pypi.org/project/darglint) (📦 20 · ⏱️ 18.10.2021):
	```
	pip install darglint
	```
- [Conda](https://anaconda.org/conda-forge/darglint) (📥 25K · ⏱️ 05.04.2021):
	```
	conda install -c conda-forge darglint
	```
</details>
<details><summary><b><a href="https://github.com/dropbox/mypy-protobuf">mypy-protobuf</a></b> (🥉23 ·  ⭐ 400) - open source tools to generate mypy stubs from protobufs. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/dropbox/mypy-protobuf) (👨‍💻 29 · 🔀 62 · 📋 95 - 5% open · ⏱️ 02.11.2021):

	```
	git clone https://github.com/dropbox/mypy-protobuf
	```
- [PyPi](https://pypi.org/project/mypy-protobuf) (📥 1.2M / month · 📦 24 · ⏱️ 12.10.2021):
	```
	pip install mypy-protobuf
	```
</details>
<details><summary><b><a href="https://github.com/adamchainz/flake8-comprehensions">flake8-comprehensions</a></b> (🥉23 ·  ⭐ 310) - A flake8 plugin to help you write better.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://cdn.iconscout.com/icon/free/png-256/8-eight-digital-number-numerical-numbers-36025.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/adamchainz/flake8-comprehensions) (👨‍💻 12 · 🔀 15 · 📋 40 - 17% open · ⏱️ 01.11.2021):

	```
	git clone https://github.com/adamchainz/flake8-comprehensions
	```
- [PyPi](https://pypi.org/project/flake8-comprehensions) (📥 620K / month · 📦 710 · ⏱️ 11.10.2021):
	```
	pip install flake8-comprehensions
	```
- [Conda](https://anaconda.org/conda-forge/flake8-comprehensions) (📥 450K · ⏱️ 12.10.2021):
	```
	conda install -c conda-forge flake8-comprehensions
	```
</details>
<details><summary><b><a href="https://github.com/wemake-services/flake8-eradicate">flake8-eradicate</a></b> (🥉23 ·  ⭐ 200) - Flake8 plugin to find commented out or dead code. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://cdn.iconscout.com/icon/free/png-256/8-eight-digital-number-numerical-numbers-36025.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/wemake-services/flake8-eradicate) (👨‍💻 13 · 🔀 7 · 📋 28 - 3% open · ⏱️ 29.10.2021):

	```
	git clone https://github.com/wemake-services/flake8-eradicate
	```
- [PyPi](https://pypi.org/project/flake8-eradicate) (📥 250K / month · 📦 72 · ⏱️ 19.10.2021):
	```
	pip install flake8-eradicate
	```
</details>
<details><summary><b><a href="https://github.com/peterjc/flake8-black">flake8-black</a></b> (🥉23 ·  ⭐ 97) - flake8 plugin to run black for checking Python coding style. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://cdn.iconscout.com/icon/free/png-256/8-eight-digital-number-numerical-numbers-36025.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/peterjc/flake8-black) (👨‍💻 5 · 🔀 8 · 📦 1.4K · 📋 21 - 33% open · ⏱️ 11.10.2021):

	```
	git clone https://github.com/peterjc/flake8-black
	```
- [PyPi](https://pypi.org/project/flake8-black) (📥 220K / month · 📦 36 · ⏱️ 16.07.2021):
	```
	pip install flake8-black
	```
- [Conda](https://anaconda.org/conda-forge/flake8-black) (📥 160K · ⏱️ 17.07.2021):
	```
	conda install -c conda-forge flake8-black
	```
</details>
<details><summary><b><a href="https://github.com/predictive-analytics-lab/data-science-types">data-science-types</a></b> (🥉22 ·  ⭐ 190 · 💤) - Mypy stubs, i.e., type information, for numpy, pandas.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/predictive-analytics-lab/data-science-types) (👨‍💻 44 · 🔀 57 · 📦 140 · 📋 62 - 62% open · ⏱️ 16.02.2021):

	```
	git clone https://github.com/predictive-analytics-lab/data-science-types
	```
- [PyPi](https://pypi.org/project/data-science-types) (📥 51K / month · ⏱️ 16.02.2021):
	```
	pip install data-science-types
	```
</details>
<details><summary><b><a href="https://github.com/gforcada/flake8-builtins">flake8-builtins</a></b> (🥉22 ·  ⭐ 73) - Check for python builtins being used as variables or.. <code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code> <code><img src="https://cdn.iconscout.com/icon/free/png-256/8-eight-digital-number-numerical-numbers-36025.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/gforcada/flake8-builtins) (👨‍💻 15 · 🔀 17 · 📦 2.8K · 📋 34 - 5% open · ⏱️ 20.09.2021):

	```
	git clone https://github.com/gforcada/flake8-builtins
	```
- [PyPi](https://pypi.org/project/flake8-builtins) (📥 430K / month · 📦 510 · ⏱️ 14.05.2020):
	```
	pip install flake8-builtins
	```
- [Conda](https://anaconda.org/conda-forge/flake8-builtins) (📥 130K · ⏱️ 18.05.2020):
	```
	conda install -c conda-forge flake8-builtins
	```
</details>
<details><summary><b><a href="https://github.com/Instagram/Fixit">Fixit</a></b> (🥉20 ·  ⭐ 280) - Fixit is a Python Lint Framework based on LibCST. It comes with useful.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/Instagram/Fixit) (👨‍💻 27 · 🔀 39 · 📦 11 · 📋 57 - 56% open · ⏱️ 05.08.2021):

	```
	git clone https://github.com/Instagram/Fixit
	```
- [PyPi](https://pypi.org/project/fixit) (📥 6.1K / month · ⏱️ 30.07.2021):
	```
	pip install fixit
	```
</details>
<details><summary><b><a href="https://github.com/jschaf/pylint-flask">pylint-flask</a></b> (🥉20 ·  ⭐ 59 · 💤) - A Pylint plugin to analyze Flask applications. <code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code> <code><img src="https://www.pylint.org/ico/favicon.ico" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/jschaf/pylint-flask) (👨‍💻 7 · 🔀 9 · 📦 5.4K · 📋 10 - 50% open · ⏱️ 10.03.2021):

	```
	git clone https://github.com/jschaf/pylint-flask
	```
- [PyPi](https://pypi.org/project/pylint-flask) (📥 200K / month · 📦 710 · ⏱️ 30.01.2019):
	```
	pip install pylint-flask
	```
- [Conda](https://anaconda.org/conda-forge/pylint-flask) (📥 53K · ⏱️ 02.02.2019):
	```
	conda install -c conda-forge pylint-flask
	```
</details>
<details><summary><b><a href="https://github.com/PyCQA/flake8-commas">flake8-commas</a></b> (🥉19 ·  ⭐ 130) - Flake8 extension for enforcing trailing commas in python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://cdn.iconscout.com/icon/free/png-256/8-eight-digital-number-numerical-numbers-36025.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PyCQA/flake8-commas) (👨‍💻 12 · 🔀 23 · 📋 31 - 16% open · ⏱️ 13.10.2021):

	```
	git clone https://github.com/PyCQA/flake8-commas
	```
- [PyPi](https://pypi.org/project/flake8-commas) (📦 550 · ⏱️ 13.10.2021):
	```
	pip install flake8-commas
	```
</details>
<details><summary><b><a href="https://github.com/life4/flakehell">flakehell</a></b> (🥉18 ·  ⭐ 220 · 💤) - Flake8 wrapper to make it nice, legacy-friendly, configurable. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://cdn.iconscout.com/icon/free/png-256/8-eight-digital-number-numerical-numbers-36025.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/life4/flakehell) (👨‍💻 16 · 🔀 32 · 📥 57 · ⏱️ 11.01.2021):

	```
	git clone https://github.com/life4/flakehell
	```
- [PyPi](https://pypi.org/project/flakehell) (📥 43K / month · ⏱️ 11.01.2021):
	```
	pip install flakehell
	```
</details>
<details><summary><b><a href="https://github.com/justinabrahms/imhotep">imhotep</a></b> (🥉18 ·  ⭐ 220) - A static-analysis bot for Github. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/justinabrahms/imhotep) (👨‍💻 16 · 🔀 37 · 📦 7 · 📋 46 - 50% open · ⏱️ 01.10.2021):

	```
	git clone https://github.com/justinabrahms/imhotep
	```
- [PyPi](https://pypi.org/project/imhotep) (📥 37 / month · 📦 4 · ⏱️ 18.09.2016):
	```
	pip install imhotep
	```
</details>
<details><summary><b><a href="https://github.com/deppen8/pandas-vet">pandas-vet</a></b> (🥉18 ·  ⭐ 110 · 💤) - A plugin for Flake8 that checks pandas code. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://cdn.iconscout.com/icon/free/png-256/8-eight-digital-number-numerical-numbers-36025.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/deppen8/pandas-vet) (👨‍💻 10 · 🔀 14 · 📥 39 · 📦 52 · 📋 50 - 42% open · ⏱️ 03.03.2021):

	```
	git clone https://github.com/deppen8/pandas-vet
	```
- [PyPi](https://pypi.org/project/pandas-vet) (📥 5.7K / month · ⏱️ 01.02.2020):
	```
	pip install pandas-vet
	```
- [Conda](https://anaconda.org/conda-forge/pandas-vet) (📥 7.6K · ⏱️ 01.02.2020):
	```
	conda install -c conda-forge pandas-vet
	```
</details>
<details><summary><b><a href="https://github.com/beartype/beartype">beartype</a></b> (🥉17 ·  ⭐ 500) - Unbearably fast O(1) runtime type-checking in pure Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/beartype/beartype) (👨‍💻 8 · 🔀 13 · 📋 49 - 20% open · ⏱️ 04.11.2021):

	```
	git clone https://github.com/beartype/beartype
	```
- [PyPi](https://pypi.org/project/beartype) (📥 36K / month · ⏱️ 22.10.2021):
	```
	pip install beartype
	```
- [Conda](https://anaconda.org/conda-forge/beartype) (📥 8.1K · ⏱️ 22.10.2021):
	```
	conda install -c conda-forge beartype
	```
</details>
<details><summary><b><a href="https://github.com/hchasestevens/bellybutton">bellybutton</a></b> (🥉17 ·  ⭐ 220) - Custom Python linting through AST expressions. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/hchasestevens/bellybutton) (👨‍💻 5 · 🔀 11 · 📦 12 · 📋 14 - 57% open · ⏱️ 15.07.2021):

	```
	git clone https://github.com/hchasestevens/bellybutton
	```
- [PyPi](https://pypi.org/project/bellybutton) (📥 6.3K / month · ⏱️ 27.11.2020):
	```
	pip install bellybutton
	```
</details>
<details><summary><b><a href="https://github.com/andreoliwa/nitpick">nitpick</a></b> (🥉15 ·  ⭐ 180) - Enforce the same settings on multiple projects. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://cdn.iconscout.com/icon/free/png-256/8-eight-digital-number-numerical-numbers-36025.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/andreoliwa/nitpick) (👨‍💻 12 · 🔀 12 · 📥 4 · 📋 89 - 37% open · ⏱️ 29.10.2021):

	```
	git clone https://github.com/andreoliwa/nitpick
	```
- [PyPi](https://pypi.org/project/nitpick) (⏱️ 27.10.2021):
	```
	pip install nitpick
	```
</details>
<details><summary><b><a href="https://github.com/lyft/linty_fresh">linty_fresh</a></b> (🥉14 ·  ⭐ 180 · 💤) - Surface lint errors during code review. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://cdn.iconscout.com/icon/free/png-256/8-eight-digital-number-numerical-numbers-36025.png" style="display:inline;" width="13" height="13"></code> <code>mypy</code></summary>

- [GitHub](https://github.com/lyft/linty_fresh) (👨‍💻 17 · 🔀 21 · 📋 9 - 88% open · ⏱️ 30.11.2020):

	```
	git clone https://github.com/lyft/linty_fresh
	```
- [PyPi](https://pypi.org/project/linty-fresh) (📥 19 / month · ⏱️ 12.12.2018):
	```
	pip install linty-fresh
	```
</details>
<details><summary>Show 7 hidden projects...</summary>

- <b><a href="https://github.com/PyCQA/pep8-naming">pep8-naming</a></b> (🥈26 ·  ⭐ 340) - Naming Convention checker for Python. <code><a href="https://tldrlegal.com/search?q=Saxpath">❗️Saxpath</a></code>
- <b><a href="https://github.com/klen/pylama">pylama</a></b> (🥉24 ·  ⭐ 820 · 💀) - Code audit tool for python. <code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code>
- <b><a href="https://github.com/PyCQA/flake8-import-order">flake8-import-order</a></b> (🥉24 ·  ⭐ 250 · 💀) - Flake8 plugin that checks import order against.. <code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code> <code><img src="https://cdn.iconscout.com/icon/free/png-256/8-eight-digital-number-numerical-numbers-36025.png" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/ambv/flake8-mypy">flake8-mypy</a></b> (🥉20 ·  ⭐ 100 · 💀) - A plugin for flake8 integrating Mypy. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://cdn.iconscout.com/icon/free/png-256/8-eight-digital-number-numerical-numbers-36025.png" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/bndr/pycycle">pycycle</a></b> (🥉17 ·  ⭐ 290 · 💀) - Tool for pinpointing circular imports in Python. Find cyclic imports.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/cemsbr/yala">yala</a></b> (🥉17 ·  ⭐ 11 · 💤) - Yet Another Linter Aggregator. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://cdn.iconscout.com/icon/free/png-256/8-eight-digital-number-numerical-numbers-36025.png" style="display:inline;" width="13" height="13"></code> <code><img src="https://www.pylint.org/ico/favicon.ico" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/tylerwince/flake8-bandit">flake8-bandit</a></b> (🥉15 ·  ⭐ 65 · 💀) - Automated security testing using bandit and flake8. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://cdn.iconscout.com/icon/free/png-256/8-eight-digital-number-numerical-numbers-36025.png" style="display:inline;" width="13" height="13"></code>
</details>
<br>

## Code Formatters

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/hhatto/autopep8">autopep8</a></b> (🥇32 ·  ⭐ 3.9K) - A tool that automatically formats Python code to conform to the PEP 8.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/hhatto/autopep8) (👨‍💻 51 · 🔀 250 · 📦 95K · 📋 430 - 21% open · ⏱️ 30.10.2021):

	```
	git clone https://github.com/hhatto/autopep8
	```
- [PyPi](https://pypi.org/project/autopep8) (📦 10K · ⏱️ 24.10.2021):
	```
	pip install autopep8
	```
- [Conda](https://anaconda.org/conda-forge/autopep8) (📥 560K · ⏱️ 26.10.2021):
	```
	conda install -c conda-forge autopep8
	```
</details>
<details><summary><b><a href="https://github.com/psf/black">black</a></b> (🥈31 ·  ⭐ 23K) - The uncompromising Python code formatter. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/psf/black) (👨‍💻 280 · 🔀 1.5K · 📥 18K · 📦 92K · 📋 1.7K - 20% open · ⏱️ 01.11.2021):

	```
	git clone https://github.com/psf/black
	```
- [PyPi](https://pypi.org/project/black) (📦 6.2K · ⏱️ 01.11.2021):
	```
	pip install black
	```
- [Conda](https://anaconda.org/conda-forge/black) (📥 2.4M · ⏱️ 02.11.2021):
	```
	conda install -c conda-forge black
	```
</details>
<details><summary><b><a href="https://github.com/PyCQA/isort">isort</a></b> (🥈30 ·  ⭐ 4.3K) - A Python utility / library to sort imports. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/PyCQA/isort) (👨‍💻 250 · 🔀 430 · 📦 200K · 📋 1K - 3% open · ⏱️ 03.11.2021):

	```
	git clone https://github.com/PyCQA/isort
	```
- [PyPi](https://pypi.org/project/isort) (📦 24K · ⏱️ 03.11.2021):
	```
	pip install isort
	```
- [Conda](https://anaconda.org/conda-forge/isort) (📥 2.5M · ⏱️ 03.11.2021):
	```
	conda install -c conda-forge isort
	```
</details>
<details><summary><b><a href="https://github.com/google/yapf">yapf</a></b> (🥉28 ·  ⭐ 12K) - A formatter for Python files. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/google/yapf) (👨‍💻 130 · 🔀 820 · 📦 25K · 📋 720 - 46% open · ⏱️ 04.11.2021):

	```
	git clone https://github.com/google/yapf
	```
- [PyPi](https://pypi.org/project/yapf) (📦 3.4K · ⏱️ 23.04.2020):
	```
	pip install yapf
	```
- [Conda](https://anaconda.org/conda-forge/yapf) (📥 860K · ⏱️ 19.04.2021):
	```
	conda install -c conda-forge yapf
	```
</details>
<details><summary><b><a href="https://github.com/myint/docformatter">docformatter</a></b> (🥉23 ·  ⭐ 240 · 💤) - Formats docstrings to follow PEP 257. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/myint/docformatter) (👨‍💻 15 · 🔀 32 · 📦 740 · 📋 49 - 55% open · ⏱️ 27.12.2020):

	```
	git clone https://github.com/myint/docformatter
	```
- [PyPi](https://pypi.org/project/docformatter) (📥 93K / month · 📦 110 · ⏱️ 27.12.2020):
	```
	pip install docformatter
	```
</details>
<details><summary>Show 1 hidden projects...</summary>

- <b><a href="https://github.com/myint/pyformat">pyformat</a></b> (🥉15 ·  ⭐ 84 · 💀) - Formats Python code to follow a consistent style. <code><a href="https://tldrlegal.com/search?q=Saxpath">❗️Saxpath</a></code>
</details>
<br>

## Code Refactoring

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/davidhalter/jedi">jedi</a></b> (🥇35 ·  ⭐ 5K) - Awesome autocompletion, static analysis and refactoring library for python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/davidhalter/jedi) (👨‍💻 150 · 🔀 440 · 📦 160K · 📋 1.3K - 2% open · ⏱️ 09.10.2021):

	```
	git clone https://github.com/davidhalter/jedi
	```
- [PyPi](https://pypi.org/project/jedi) (📥 23M / month · 📦 16K · ⏱️ 25.12.2020):
	```
	pip install jedi
	```
- [Conda](https://anaconda.org/conda-forge/jedi) (📥 6.7M · ⏱️ 02.11.2021):
	```
	conda install -c conda-forge jedi
	```
</details>
<details><summary><b><a href="https://github.com/python-rope/rope">rope</a></b> (🥇31 ·  ⭐ 1.2K · 📈) - a python refactoring library. <code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code></summary>

- [GitHub](https://github.com/python-rope/rope) (👨‍💻 66 · 🔀 140 · 📦 32K · 📋 230 - 30% open · ⏱️ 31.10.2021):

	```
	git clone https://github.com/python-rope/rope
	```
- [PyPi](https://pypi.org/project/rope) (📥 540K / month · 📦 2.9K · ⏱️ 18.10.2021):
	```
	pip install rope
	```
- [Conda](https://anaconda.org/conda-forge/rope) (📥 590K · ⏱️ 18.10.2021):
	```
	conda install -c conda-forge rope
	```
</details>
<details><summary><b><a href="https://github.com/asottile/pyupgrade">pyupgrade</a></b> (🥈25 ·  ⭐ 1.2K) - A tool (and pre-commit hook) to automatically upgrade syntax for newer.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/asottile/pyupgrade) (👨‍💻 21 · 🔀 81 · 📋 240 - 3% open · ⏱️ 01.11.2021):

	```
	git clone https://github.com/asottile/pyupgrade
	```
- [PyPi](https://pypi.org/project/pyupgrade) (📥 110K / month · 📦 10 · ⏱️ 28.09.2021):
	```
	pip install pyupgrade
	```
- [Conda](https://anaconda.org/conda-forge/pyupgrade) (📥 270K · ⏱️ 30.09.2021):
	```
	conda install -c conda-forge pyupgrade
	```
</details>
<details><summary><b><a href="https://github.com/jendrikseipp/vulture">vulture</a></b> (🥈23 ·  ⭐ 1.9K) - Find dead Python code. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jendrikseipp/vulture) (👨‍💻 29 · 🔀 89 · 📦 1.2K · 📋 150 - 9% open · ⏱️ 27.10.2021):

	```
	git clone https://github.com/jendrikseipp/vulture
	```
- [PyPi](https://pypi.org/project/vulture) (📦 360 · ⏱️ 16.01.2021):
	```
	pip install vulture
	```
- [Conda](https://anaconda.org/conda-forge/vulture) (📥 50K · ⏱️ 11.08.2020):
	```
	conda install -c conda-forge vulture
	```
</details>
<details><summary><b><a href="https://github.com/myint/autoflake">autoflake</a></b> (🥈23 ·  ⭐ 440 · 💤) - Removes unused imports and unused variables as reported by pyflakes. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/myint/autoflake) (👨‍💻 17 · 🔀 49 · 📦 3.1K · 📋 66 - 50% open · ⏱️ 27.12.2020):

	```
	git clone https://github.com/myint/autoflake
	```
- [PyPi](https://pypi.org/project/autoflake) (📦 580 · ⏱️ 04.08.2019):
	```
	pip install autoflake
	```
- [Conda](https://anaconda.org/conda-forge/autoflake) (📥 200K · ⏱️ 26.05.2021):
	```
	conda install -c conda-forge autoflake
	```
</details>
<details><summary><b><a href="https://github.com/Instagram/MonkeyType">MonkeyType</a></b> (🥉22 ·  ⭐ 3.6K) - A system for Python that generates static type annotations by.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/Instagram/MonkeyType) (👨‍💻 37 · 🔀 130 · 📦 150 · 📋 150 - 24% open · ⏱️ 15.09.2021):

	```
	git clone https://github.com/Instagram/MonkeyType
	```
- [PyPi](https://pypi.org/project/monkeytype) (📥 35K / month · 📦 34 · ⏱️ 21.05.2021):
	```
	pip install monkeytype
	```
- [Conda](https://anaconda.org/conda-forge/monkeytype) (📥 37K · ⏱️ 22.05.2021):
	```
	conda install -c conda-forge monkeytype
	```
</details>
<details><summary><b><a href="https://github.com/facebookincubator/Bowler">Bowler</a></b> (🥉21 ·  ⭐ 1.3K) - Safe code refactoring for modern Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/facebookincubator/Bowler) (👨‍💻 26 · 🔀 88 · 📋 80 - 57% open · ⏱️ 01.09.2021):

	```
	git clone https://github.com/facebookincubator/Bowler
	```
- [PyPi](https://pypi.org/project/bowler) (📥 40K / month · 📦 10 · ⏱️ 17.09.2020):
	```
	pip install bowler
	```
- [Conda](https://anaconda.org/conda-forge/bowler) (📥 11K · ⏱️ 12.06.2019):
	```
	conda install -c conda-forge bowler
	```
</details>
<details><summary><b><a href="https://github.com/dropbox/pyannotate">pyannotate</a></b> (🥉21 ·  ⭐ 1.2K) - Auto-generate PEP-484 annotations. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/dropbox/pyannotate) (👨‍💻 17 · 🔀 53 · 📦 65 · 📋 59 - 44% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/dropbox/pyannotate
	```
- [PyPi](https://pypi.org/project/pyannotate) (📥 3.5K / month · 📦 26 · ⏱️ 16.09.2019):
	```
	pip install pyannotate
	```
</details>
<details><summary><b><a href="https://github.com/asottile/add-trailing-comma">add-trailing-comma</a></b> (🥉21 ·  ⭐ 200) - A tool (and pre-commit hook) to automatically add trailing.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/asottile/add-trailing-comma) (👨‍💻 9 · 🔀 14 · 📋 35 - 2% open · ⏱️ 01.11.2021):

	```
	git clone https://github.com/asottile/add-trailing-comma
	```
- [PyPi](https://pypi.org/project/add-trailing-comma) (📥 12K / month · 📦 14 · ⏱️ 19.10.2021):
	```
	pip install add-trailing-comma
	```
</details>
<details><summary><b><a href="https://github.com/hakancelik96/unimport">unimport</a></b> (🥉19 ·  ⭐ 120) - A linter, formatter for finding and removing unused import statements. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/hakancelik96/unimport) (👨‍💻 13 · 🔀 13 · 📦 14 · 📋 76 - 13% open · ⏱️ 14.09.2021):

	```
	git clone https://github.com/hakancelik96/unimport
	```
- [PyPi](https://pypi.org/project/unimport) (📥 5.1K / month · ⏱️ 14.09.2021):
	```
	pip install unimport
	```
</details>
<details><summary><b><a href="https://github.com/ambv/retype">retype</a></b> (🥉17 ·  ⭐ 110) - Re-apply type annotations from .pyi stubs to your codebase. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ambv/retype) (👨‍💻 8 · 🔀 17 · 📋 14 - 42% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/ambv/retype
	```
- [PyPi](https://pypi.org/project/retype) (📥 1K / month · 📦 34 · ⏱️ 04.10.2021):
	```
	pip install retype
	```
- [Conda](https://anaconda.org/conda-forge/retype) (📥 15K · ⏱️ 04.10.2021):
	```
	conda install -c conda-forge retype
	```
</details>
<details><summary><b><a href="https://github.com/elmotec/massedit">massedit</a></b> (🥉17 ·  ⭐ 93 · 💤) - Programmatically edit text files with Python. Useful for source to.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/elmotec/massedit) (👨‍💻 6 · 🔀 14 · 📥 17 · 📋 8 - 37% open · ⏱️ 23.12.2020):

	```
	git clone https://github.com/elmotec/massedit
	```
- [PyPi](https://pypi.org/project/massedit) (📥 1.8K / month · 📦 10 · ⏱️ 23.12.2020):
	```
	pip install massedit
	```
</details>
<details><summary><b><a href="https://github.com/ilevkivskyi/com2ann">com2ann</a></b> (🥉13 ·  ⭐ 100) - Tool for translation type comments to type annotations in Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ilevkivskyi/com2ann) (👨‍💻 4 · 🔀 7 · 📦 7 · 📋 20 - 25% open · ⏱️ 21.08.2021):

	```
	git clone https://github.com/ilevkivskyi/com2ann
	```
- [PyPi](https://pypi.org/project/com2ann) (⏱️ 21.08.2021):
	```
	pip install com2ann
	```
</details>
<details><summary>Show 5 hidden projects...</summary>

- <b><a href="https://github.com/PyCQA/redbaron">redbaron</a></b> (🥈23 ·  ⭐ 620 · 💀) - Bottom-up approach to refactoring in python. <code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code>
- <b><a href="https://github.com/PyCQA/baron">baron</a></b> (🥈23 ·  ⭐ 270 · 💀) - IDE allow you to refactor code, Baron allows you to write.. <code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code>
- <b><a href="https://github.com/myint/unify">unify</a></b> (🥉20 ·  ⭐ 60 · 💀) - Modifies strings to all use the same quote where possible. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/myint/eradicate">eradicate</a></b> (🥉19 ·  ⭐ 120 · 💀) - Removes commented-out code from Python files. <code><a href="https://tldrlegal.com/search?q=Saxpath">❗️Saxpath</a></code>
- <b><a href="https://github.com/spulec/pep8ify">pep8ify</a></b> (🥉16 ·  ⭐ 120 · 💀) - A library that modifies python source code to conform to pep8. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
</details>
<br>

## Code Security

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/PyCQA/bandit">bandit</a></b> (🥇28 ·  ⭐ 3.6K) - Bandit is a tool designed to find common security issues in Python.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/PyCQA/bandit) (👨‍💻 130 · 🔀 370 · 📥 120 · 📦 8.8K · 📋 550 - 32% open · ⏱️ 24.10.2021):

	```
	git clone https://github.com/PyCQA/bandit
	```
- [PyPi](https://pypi.org/project/bandit) (📦 2.4K · ⏱️ 13.12.2020):
	```
	pip install bandit
	```
- [Conda](https://anaconda.org/conda-forge/bandit) (📥 94K · ⏱️ 16.09.2021):
	```
	conda install -c conda-forge bandit
	```
</details>
<details><summary><b><a href="https://github.com/sqlmapproject/sqlmap">sqlmap</a></b> (🥈26 ·  ⭐ 22K) - Automatic SQL injection and database takeover tool. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/sqlmapproject/sqlmap) (👨‍💻 110 · 🔀 4.5K · 📋 4.5K - 1% open · ⏱️ 01.11.2021):

	```
	git clone https://github.com/sqlmapproject/sqlmap
	```
- [PyPi](https://pypi.org/project/sqlmap) (📥 7.7K / month · 📦 8 · ⏱️ 01.11.2021):
	```
	pip install sqlmap
	```
</details>
<details><summary><b><a href="https://github.com/pyupio/safety">safety</a></b> (🥉25 ·  ⭐ 1.1K · 💤) - Safety checks your installed dependencies for known security.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pyupio/safety) (👨‍💻 35 · 🔀 96 · 📥 94K · 📦 2.9K · 📋 120 - 38% open · ⏱️ 28.04.2021):

	```
	git clone https://github.com/pyupio/safety
	```
- [PyPi](https://pypi.org/project/safety) (📦 540 · ⏱️ 15.01.2021):
	```
	pip install safety
	```
- [Conda](https://anaconda.org/conda-forge/safety) (📥 24K · ⏱️ 15.01.2021):
	```
	conda install -c conda-forge safety
	```
</details>
<details><summary><b><a href="https://github.com/dlint-py/dlint">dlint</a></b> (🥉21 ·  ⭐ 77) - Dlint is a tool for encouraging best coding practices and helping ensure.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/dlint-py/dlint) (👨‍💻 8 · 🔀 6 · 📋 33 - 57% open · ⏱️ 27.10.2021):

	```
	git clone https://github.com/dlint-py/dlint
	```
- [PyPi](https://pypi.org/project/dlint) (📥 110K / month · 📦 18 · ⏱️ 27.10.2021):
	```
	pip install dlint
	```
</details>
<details><summary><b><a href="https://github.com/Yelp/detect-secrets">detect-secrets</a></b> (🥉20 ·  ⭐ 2K · 📉) - An enterprise friendly way of detecting and preventing.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/Yelp/detect-secrets) (👨‍💻 51 · 🔀 240 · 📋 230 - 35% open · ⏱️ 01.08.2021):

	```
	git clone https://github.com/Yelp/detect-secrets
	```
- [PyPi](https://pypi.org/project/detect-secrets) (📦 34 · ⏱️ 14.04.2021):
	```
	pip install detect-secrets
	```
</details>
<details><summary><b><a href="https://github.com/landscapeio/dodgy">dodgy</a></b> (🥉18 ·  ⭐ 94 · 💤) - Looks at Python code to search for things which look dodgy such as.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/landscapeio/dodgy) (👨‍💻 14 · 🔀 18 · 📦 1.4K · 📋 12 - 75% open · ⏱️ 21.03.2021):

	```
	git clone https://github.com/landscapeio/dodgy
	```
- [PyPi](https://pypi.org/project/dodgy) (📦 520 · ⏱️ 31.12.2019):
	```
	pip install dodgy
	```
- [Conda](https://anaconda.org/conda-forge/dodgy) (📥 26K · ⏱️ 10.06.2020):
	```
	conda install -c conda-forge dodgy
	```
</details>
<details><summary>Show 2 hidden projects...</summary>

- <b><a href="https://github.com/dashingsoft/pyarmor">pyarmor</a></b> (🥈27 ·  ⭐ 1.2K) - A tool used to obfuscate python scripts, bind obfuscated scripts.. <code><a href="https://tldrlegal.com/search?q=SGI-B-2.0">❗️SGI-B-2.0</a></code>
- <b><a href="https://github.com/python-security/pyt">pyt</a></b> (🥉18 ·  ⭐ 2.1K · 💀) - A Static Analysis Tool for Detecting Security Vulnerabilities in.. <code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code>
</details>
<br>

## Virtual Environments

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/pypa/pipenv">pipenv</a></b> (🥇29 ·  ⭐ 22K · 📉) - Python Development Workflow for Humans. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pypa/pipenv) (👨‍💻 390 · 🔀 1.6K · 📦 23K · 📋 3.5K - 16% open · ⏱️ 04.11.2021):

	```
	git clone https://github.com/pypa/pipenv
	```
- [PyPi](https://pypi.org/project/pipenv) (📦 2.3K · ⏱️ 29.05.2021):
	```
	pip install pipenv
	```
- [Conda](https://anaconda.org/conda-forge/pipenv) (📥 44K · ⏱️ 15.11.2020):
	```
	conda install -c conda-forge pipenv
	```
</details>
<details><summary><b><a href="https://github.com/pypa/virtualenv">virtualenv</a></b> (🥇29 ·  ⭐ 4K) - Virtual Python Environment builder. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pypa/virtualenv) (👨‍💻 220 · 🔀 910 · 📋 1.2K - 5% open · ⏱️ 01.11.2021):

	```
	git clone https://github.com/pypa/virtualenv
	```
- [PyPi](https://pypi.org/project/virtualenv) (📦 34K · ⏱️ 01.11.2021):
	```
	pip install virtualenv
	```
- [Conda](https://anaconda.org/conda-forge/virtualenv) (📥 1.3M · ⏱️ 02.11.2021):
	```
	conda install -c conda-forge virtualenv
	```
</details>
<details><summary><b><a href="https://github.com/pyenv/pyenv">pyenv</a></b> (🥈26 ·  ⭐ 25K) - Simple Python version management. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pyenv/pyenv) (👨‍💻 340 · 🔀 2.2K · 📋 1.4K - 2% open · ⏱️ 31.10.2021):

	```
	git clone https://github.com/pyenv/pyenv
	```
- [PyPi](https://pypi.org/project/pyenv) (📥 7.1K / month · 📦 1 · ⏱️ 12.01.2019):
	```
	pip install pyenv
	```
</details>
<details><summary><b><a href="https://github.com/pyenv/pyenv-virtualenv">pyenv-virtualenv</a></b> (🥉18 ·  ⭐ 4.6K) - a pyenv plugin to manage virtualenv (a.k.a. python-virtualenv). <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pyenv/pyenv-virtualenv) (👨‍💻 44 · 🔀 310 · 📋 330 - 41% open · ⏱️ 08.10.2021):

	```
	git clone https://github.com/pyenv/pyenv-virtualenv
	```
</details>
<details><summary><b><a href="https://github.com/spotify/dh-virtualenv">dh-virtualenv</a></b> (🥉15 ·  ⭐ 1.5K) - Python virtualenvs in Debian packages. <code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code></summary>

- [GitHub](https://github.com/spotify/dh-virtualenv) (👨‍💻 57 · 🔀 160 · 📋 190 - 12% open · ⏱️ 26.07.2021):

	```
	git clone https://github.com/spotify/dh-virtualenv
	```
</details>
<details><summary><b><a href="https://github.com/pyenv/pyenv-installer">pyenv-installer</a></b> (🥉14 ·  ⭐ 2.9K) - This tool is used to install `pyenv` and friends. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pyenv/pyenv-installer) (👨‍💻 33 · 🔀 320 · 📋 69 - 7% open · ⏱️ 27.08.2021):

	```
	git clone https://github.com/pyenv/pyenv-installer
	```
</details>
<details><summary>Show 2 hidden projects...</summary>

- <b><a href="https://github.com/sashahart/vex">vex</a></b> (🥉17 ·  ⭐ 370 · 💀) - Run a command in the named virtualenv. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/gtalarico/pipenv-pipes">pipenv-pipes</a></b> (🥉12 ·  ⭐ 130 · 💀) - A PipEnv Environment Switcher. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>
<br>

## Dependency & Package Mangers

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/jazzband/pip-tools">pip-tools</a></b> (🥇33 ·  ⭐ 5.3K) - A set of tools to keep your pinned Python dependencies fresh. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jazzband/pip-tools) (👨‍💻 160 · 🔀 470 · 📋 780 - 15% open · ⏱️ 04.11.2021):

	```
	git clone https://github.com/jazzband/pip-tools
	```
- [PyPi](https://pypi.org/project/pip-tools) (📥 5.2M / month · 📦 3.3K · ⏱️ 12.10.2021):
	```
	pip install pip-tools
	```
- [Conda](https://anaconda.org/conda-forge/pip-tools) (📥 18K · ⏱️ 12.10.2021):
	```
	conda install -c conda-forge pip-tools
	```
</details>
<details><summary><b><a href="https://github.com/pypa/pip">pip</a></b> (🥈32 ·  ⭐ 7.5K) - The Python package installer. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pypa/pip) (👨‍💻 640 · 🔀 2.4K · 📦 63K · 📋 6K - 15% open · ⏱️ 29.10.2021):

	```
	git clone https://github.com/pypa/pip
	```
- [PyPi](https://pypi.org/project/pip) (📦 19K · ⏱️ 22.10.2021):
	```
	pip install pip
	```
- [Conda](https://anaconda.org/conda-forge/pip) (📥 27M · ⏱️ 22.10.2021):
	```
	conda install -c conda-forge pip
	```
</details>
<details><summary><b><a href="https://github.com/conda/conda">conda</a></b> (🥈32 ·  ⭐ 4.4K) - OS-agnostic, system-level binary package manager and ecosystem. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/conda/conda) (👨‍💻 370 · 🔀 1.1K · 📋 8.2K - 25% open · ⏱️ 04.11.2021):

	```
	git clone https://github.com/conda/conda
	```
- [PyPi](https://pypi.org/project/conda) (📥 74K / month · 📦 2.1K · ⏱️ 22.04.2017):
	```
	pip install conda
	```
- [Conda](https://anaconda.org/conda-forge/conda) (📥 23M · ⏱️ 03.11.2021):
	```
	conda install -c conda-forge conda
	```
</details>
<details><summary><b><a href="https://github.com/python-poetry/poetry">poetry</a></b> (🥈31 ·  ⭐ 17K) - Python dependency management and packaging made easy. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/python-poetry/poetry) (👨‍💻 300 · 🔀 1.4K · 📥 9M · 📋 3.4K - 37% open · ⏱️ 30.10.2021):

	```
	git clone https://github.com/python-poetry/poetry
	```
- [PyPi](https://pypi.org/project/poetry) (📦 64 · ⏱️ 04.10.2021):
	```
	pip install poetry
	```
- [Conda](https://anaconda.org/conda-forge/poetry) (📥 290K · ⏱️ 05.10.2021):
	```
	conda install -c conda-forge poetry
	```
</details>
<details><summary><b><a href="https://github.com/bndr/pipreqs">pipreqs</a></b> (🥉27 ·  ⭐ 3.8K) - pipreqs - Generate pip requirements.txt file based on imports of any.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/bndr/pipreqs) (👨‍💻 51 · 🔀 250 · 📦 7.3K · 📋 180 - 50% open · ⏱️ 23.10.2021):

	```
	git clone https://github.com/bndr/pipreqs
	```
- [PyPi](https://pypi.org/project/pipreqs) (📦 530 · ⏱️ 23.10.2021):
	```
	pip install pipreqs
	```
- [Conda](https://anaconda.org/conda-forge/pipreqs) (📥 23K · ⏱️ 14.11.2019):
	```
	conda install -c conda-forge pipreqs
	```
</details>
<details><summary><b><a href="https://github.com/dephell/dephell">dephell</a></b> (🥉24 ·  ⭐ 1.7K · 💤) - Python project management. Manage packages: convert between formats,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/dephell/dephell) (👨‍💻 37 · 🔀 100 · 📥 160 · 📦 320 · 📋 270 - 40% open · ⏱️ 11.01.2021):

	```
	git clone https://github.com/dephell/dephell
	```
- [PyPi](https://pypi.org/project/dephell) (📥 15K / month · 📦 8 · ⏱️ 28.04.2020):
	```
	pip install dephell
	```
</details>
<details><summary><b><a href="https://github.com/pypa/pipx">pipx</a></b> (🥉23 ·  ⭐ 4.2K) - Install and Run Python Applications in Isolated Environments. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pypa/pipx) (👨‍💻 63 · 🔀 180 · 📋 420 - 20% open · ⏱️ 01.10.2021):

	```
	git clone https://github.com/pypa/pipx
	```
- [PyPi](https://pypi.org/project/pipx) (📥 120K / month · 📦 4 · ⏱️ 05.08.2021):
	```
	pip install pipx
	```
</details>
<details><summary><b><a href="https://github.com/mamba-org/mamba">mamba</a></b> (🥉21 ·  ⭐ 2.3K) - The Fast Cross-Platform Package Manager. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/mamba-org/mamba) (👨‍💻 62 · 🔀 120 · 📋 640 - 31% open · ⏱️ 04.11.2021):

	```
	git clone https://github.com/mamba-org/mamba
	```
- [Conda](https://anaconda.org/conda-forge/mamba) (📥 1.5M · ⏱️ 14.10.2021):
	```
	conda install -c conda-forge mamba
	```
</details>
<details><summary><b><a href="https://github.com/David-OConnor/pyflow">pyflow</a></b> (🥉18 ·  ⭐ 910) - An installation and dependency system for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/David-OConnor/pyflow) (👨‍💻 25 · 🔀 35 · 📥 3.6K · 📋 110 - 39% open · ⏱️ 25.10.2021):

	```
	git clone https://github.com/David-OConnor/pyflow
	```
- [PyPi](https://pypi.org/project/pyflow) (⏱️ 02.07.2021):
	```
	pip install pyflow
	```
</details>
<details><summary><b><a href="https://github.com/jaraco/pip-run">pip-run</a></b> (🥉16 ·  ⭐ 61) - pip-run - dynamic dependency loader for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jaraco/pip-run) (👨‍💻 11 · 🔀 10 · 📋 41 - 7% open · ⏱️ 02.10.2021):

	```
	git clone https://github.com/jaraco/pip-run
	```
- [PyPi](https://pypi.org/project/pip-run) (📥 9.5K / month · ⏱️ 02.10.2021):
	```
	pip install pip-run
	```
</details>
<br>

## Code Metrics & Complexity

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/PyCQA/prospector">prospector</a></b> (🥇29 ·  ⭐ 1.5K · 📈) - Inspects Python source files and provides information about.. <code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code></summary>

- [GitHub](https://github.com/PyCQA/prospector) (👨‍💻 77 · 🔀 140 · 📋 280 - 17% open · ⏱️ 01.11.2021):

	```
	git clone https://github.com/PyCQA/prospector
	```
- [PyPi](https://pypi.org/project/prospector) (📥 480K / month · 📦 1.1K · ⏱️ 17.09.2021):
	```
	pip install prospector
	```
- [Conda](https://anaconda.org/conda-forge/prospector) (📥 27K · ⏱️ 18.11.2020):
	```
	conda install -c conda-forge prospector
	```
</details>
<details><summary><b><a href="https://github.com/rubik/radon">radon</a></b> (🥈28 ·  ⭐ 1.3K) - Various code metrics for Python code. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/rubik/radon) (👨‍💻 49 · 🔀 97 · 📦 2.1K · 📋 160 - 12% open · ⏱️ 08.08.2021):

	```
	git clone https://github.com/rubik/radon
	```
- [PyPi](https://pypi.org/project/radon) (📥 400K / month · 📦 1.1K · ⏱️ 08.08.2021):
	```
	pip install radon
	```
- [Conda](https://anaconda.org/conda-forge/radon) (📥 35K · ⏱️ 07.09.2021):
	```
	conda install -c conda-forge radon
	```
</details>
<details><summary><b><a href="https://github.com/PyCQA/mccabe">mccabe</a></b> (🥈28 ·  ⭐ 440 · 💤) - McCabe complexity checker for Python. <code><a href="https://tldrlegal.com/search?q=Saxpath">❗️Saxpath</a></code></summary>

- [GitHub](https://github.com/PyCQA/mccabe) (👨‍💻 21 · 🔀 41 · 📦 220K · 📋 40 - 15% open · ⏱️ 02.04.2021):

	```
	git clone https://github.com/PyCQA/mccabe
	```
- [PyPi](https://pypi.org/project/mccabe) (📥 18M / month · 📦 31K · ⏱️ 26.01.2017):
	```
	pip install mccabe
	```
- [Conda](https://anaconda.org/conda-forge/mccabe) (📥 3.5M · ⏱️ 08.07.2018):
	```
	conda install -c conda-forge mccabe
	```
</details>
<details><summary><b><a href="https://github.com/rubik/xenon">xenon</a></b> (🥉22 ·  ⭐ 200) - Monitoring tool based on radon. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/rubik/xenon) (👨‍💻 8 · 🔀 15 · 📦 260 · 📋 31 - 19% open · ⏱️ 03.09.2021):

	```
	git clone https://github.com/rubik/xenon
	```
- [PyPi](https://pypi.org/project/xenon) (📥 67K / month · 📦 120 · ⏱️ 03.09.2021):
	```
	pip install xenon
	```
- [Conda](https://anaconda.org/conda-forge/xenon) (📥 14K · ⏱️ 12.10.2019):
	```
	conda install -c conda-forge xenon
	```
</details>
<details><summary><b><a href="https://github.com/tonybaloney/wily">wily</a></b> (🥉21 ·  ⭐ 820) - A Python application for tracking, reporting on timing and complexity in.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/tonybaloney/wily) (👨‍💻 16 · 🔀 45 · 📋 80 - 35% open · ⏱️ 01.07.2021):

	```
	git clone https://github.com/tonybaloney/wily
	```
- [PyPi](https://pypi.org/project/wily) (📥 10K / month · 📦 16 · ⏱️ 01.07.2021):
	```
	pip install wily
	```
</details>
<details><summary>Show 1 hidden projects...</summary>

- <b><a href="https://github.com/mschwager/cohesion">cohesion</a></b> (🥉12 ·  ⭐ 140 · 💀) - A tool for measuring Python class cohesion. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
</details>
<br>

## Logging

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/tqdm/tqdm">tqdm</a></b> (🥇37 ·  ⭐ 20K) - A Fast, Extensible Progress Bar for Python and CLI. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code></summary>

- [GitHub](https://github.com/tqdm/tqdm) (👨‍💻 110 · 🔀 1K · 📥 8K · 📦 220K · 📋 840 - 37% open · ⏱️ 20.09.2021):

	```
	git clone https://github.com/tqdm/tqdm
	```
- [PyPi](https://pypi.org/project/tqdm) (📥 27M / month · 📦 26K · ⏱️ 20.09.2021):
	```
	pip install tqdm
	```
- [Conda](https://anaconda.org/conda-forge/tqdm) (📥 8.4M · ⏱️ 20.09.2021):
	```
	conda install -c conda-forge tqdm
	```
- [Docker Hub](https://hub.docker.com/r/tqdm/tqdm) (📥 3.9K · ⭐ 2 · ⏱️ 30.10.2021):
	```
	docker pull tqdm/tqdm
	```
</details>
<details><summary><b><a href="https://github.com/willmcgugan/rich">rich</a></b> (🥇33 ·  ⭐ 31K) - Rich is a Python library for rich text and beautiful formatting in the terminal. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/willmcgugan/rich) (👨‍💻 130 · 🔀 960 · 📦 8.1K · 📋 560 - 4% open · ⏱️ 16.10.2021):

	```
	git clone https://github.com/willmcgugan/rich
	```
- [PyPi](https://pypi.org/project/rich) (📥 2.5M / month · ⏱️ 06.10.2021):
	```
	pip install rich
	```
- [Conda](https://anaconda.org/conda-forge/rich) (📥 440K · ⏱️ 06.10.2021):
	```
	conda install -c conda-forge rich
	```
</details>
<details><summary><b><a href="https://github.com/madzak/python-json-logger">python-json-logger</a></b> (🥇32 ·  ⭐ 1.1K) - Json Formatter for the standard python logger. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/madzak/python-json-logger) (👨‍💻 46 · 🔀 160 · 📦 18K · 📋 67 - 31% open · ⏱️ 27.07.2021):

	```
	git clone https://github.com/madzak/python-json-logger
	```
- [PyPi](https://pypi.org/project/python-json-logger) (📥 4.2M / month · 📦 920 · ⏱️ 27.07.2021):
	```
	pip install python-json-logger
	```
- [Conda](https://anaconda.org/conda-forge/python-json-logger) (📥 970K · ⏱️ 12.10.2020):
	```
	conda install -c conda-forge python-json-logger
	```
</details>
<details><summary><b><a href="https://github.com/getsentry/sentry-python">sentry-sdk</a></b> (🥇32 ·  ⭐ 1.1K) - The new Python SDK for Sentry.io. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/getsentry/sentry-python) (👨‍💻 100 · 🔀 240 · 📥 4.5K · 📦 15K · 📋 580 - 32% open · ⏱️ 04.11.2021):

	```
	git clone https://github.com/getsentry/sentry-python
	```
- [PyPi](https://pypi.org/project/sentry-sdk) (📥 11M / month · 📦 990 · ⏱️ 29.09.2021):
	```
	pip install sentry-sdk
	```
- [Conda](https://anaconda.org/conda-forge/sentry-sdk) (📥 110K · ⏱️ 29.09.2021):
	```
	conda install -c conda-forge sentry-sdk
	```
</details>
<details><summary><b><a href="https://github.com/Delgan/loguru">loguru</a></b> (🥈31 ·  ⭐ 10K) - Python logging made (stupidly) simple. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/Delgan/loguru) (👨‍💻 30 · 🔀 450 · 📦 11K · 📋 480 - 15% open · ⏱️ 09.09.2021):

	```
	git clone https://github.com/Delgan/loguru
	```
- [PyPi](https://pypi.org/project/loguru) (📥 2M / month · 📦 340 · ⏱️ 20.09.2020):
	```
	pip install loguru
	```
- [Conda](https://anaconda.org/conda-forge/loguru) (📥 290K · ⏱️ 02.11.2021):
	```
	conda install -c conda-forge loguru
	```
</details>
<details><summary><b><a href="https://github.com/astanin/python-tabulate">tabulate</a></b> (🥈31 ·  ⭐ 1K · 💤) - Pretty-print tabular data in Python, a library and a command-line.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/astanin/python-tabulate) (👨‍💻 67 · 🔀 80 · 📦 55K · 📋 110 - 44% open · ⏱️ 04.03.2021):

	```
	git clone https://github.com/astanin/python-tabulate
	```
- [PyPi](https://pypi.org/project/tabulate) (📥 36M / month · 📦 8.1K · ⏱️ 22.02.2021):
	```
	pip install tabulate
	```
- [Conda](https://anaconda.org/conda-forge/tabulate) (📥 1.6M · ⏱️ 22.02.2021):
	```
	conda install -c conda-forge tabulate
	```
</details>
<details><summary><b><a href="https://github.com/WoLpH/python-progressbar">progressbar2</a></b> (🥈29 ·  ⭐ 730) - Progressbar 2 - A progress bar for Python 2 and Python 3 - pip.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/WoLpH/python-progressbar) (👨‍💻 41 · 🔀 100 · 📥 1.6K · 📦 13K · 📋 190 - 3% open · ⏱️ 15.10.2021):

	```
	git clone https://github.com/WoLpH/python-progressbar
	```
- [PyPi](https://pypi.org/project/progressbar2) (📥 1.9M / month · 📦 2.2K · ⏱️ 15.10.2021):
	```
	pip install progressbar2
	```
- [Conda](https://anaconda.org/conda-forge/progressbar2) (📥 360K · ⏱️ 09.09.2020):
	```
	conda install -c conda-forge progressbar2
	```
</details>
<details><summary><b><a href="https://github.com/hynek/structlog">structlog</a></b> (🥈28 ·  ⭐ 1.8K) - Structured Logging for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/hynek/structlog) (👨‍💻 78 · 🔀 150 · 📦 3.8K · 📋 200 - 15% open · ⏱️ 02.11.2021):

	```
	git clone https://github.com/hynek/structlog
	```
- [PyPi](https://pypi.org/project/structlog) (📥 2.4M / month · 📦 1.2K · ⏱️ 12.10.2021):
	```
	pip install structlog
	```
- [Conda](https://anaconda.org/conda-forge/structlog) (📥 140K · ⏱️ 13.10.2021):
	```
	conda install -c conda-forge structlog
	```
</details>
<details><summary><b><a href="https://github.com/borntyping/python-colorlog">colorlog</a></b> (🥈28 ·  ⭐ 720) - A colored formatter for the python logging module. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/borntyping/python-colorlog) (👨‍💻 30 · 🔀 74 · 📦 12K · ⏱️ 07.10.2021):

	```
	git clone https://github.com/borntyping/python-colorlog
	```
- [PyPi](https://pypi.org/project/colorlog) (📥 5.2M / month · 📦 3.7K · ⏱️ 23.08.2021):
	```
	pip install colorlog
	```
- [Conda](https://anaconda.org/conda-forge/colorlog) (📥 440K · ⏱️ 04.11.2021):
	```
	conda install -c conda-forge colorlog
	```
</details>
<details><summary><b><a href="https://github.com/xolox/python-coloredlogs">python-coloredlogs</a></b> (🥉27 ·  ⭐ 430) - Colored terminal output for Python's logging module. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/xolox/python-coloredlogs) (👨‍💻 16 · 🔀 36 · 📦 9.3K · 📋 74 - 33% open · ⏱️ 11.06.2021):

	```
	git clone https://github.com/xolox/python-coloredlogs
	```
- [PyPi](https://pypi.org/project/coloredlogs) (📥 2.2M / month · 📦 2.1K · ⏱️ 11.06.2021):
	```
	pip install coloredlogs
	```
</details>
<details><summary><b><a href="https://github.com/liiight/notifiers">notifiers</a></b> (🥉26 ·  ⭐ 2K) - The easy way to send notifications. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/liiight/notifiers) (👨‍💻 16 · 🔀 77 · 📦 180 · 📋 92 - 41% open · ⏱️ 22.09.2021):

	```
	git clone https://github.com/liiight/notifiers
	```
- [PyPi](https://pypi.org/project/notifiers) (📥 290K / month · 📦 6 · ⏱️ 05.10.2019):
	```
	pip install notifiers
	```
</details>
<details><summary><b><a href="https://github.com/ines/wasabi">wasabi</a></b> (🥉26 ·  ⭐ 310 · 💤) - A lightweight console printing and formatting toolkit. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ines/wasabi) (👨‍💻 4 · 🔀 18 · 📦 14K · 📋 6 - 50% open · ⏱️ 31.01.2021):

	```
	git clone https://github.com/ines/wasabi
	```
- [PyPi](https://pypi.org/project/wasabi) (📥 3.6M / month · 📦 410 · ⏱️ 31.01.2021):
	```
	pip install wasabi
	```
- [Conda](https://anaconda.org/conda-forge/wasabi) (📥 460K · ⏱️ 01.02.2021):
	```
	conda install -c conda-forge wasabi
	```
</details>
<details><summary><b><a href="https://github.com/shobrook/rebound">rebound</a></b> (🥉23 ·  ⭐ 3.7K · 💤) - Command-line tool that instantly fetches Stack Overflow results when.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/shobrook/rebound) (👨‍💻 16 · 🔀 340 · 📥 180 · 📦 22 · 📋 58 - 34% open · ⏱️ 04.01.2021):

	```
	git clone https://github.com/shobrook/rebound
	```
- [PyPi](https://pypi.org/project/rebound) (📥 1.6K / month · 📦 14 · ⏱️ 29.09.2021):
	```
	pip install rebound
	```
- [Conda](https://anaconda.org/conda-forge/rebound) (📥 160K · ⏱️ 29.09.2021):
	```
	conda install -c conda-forge rebound
	```
</details>
<details><summary><b><a href="https://github.com/rsalmei/alive-progress">alive-progress</a></b> (🥉22 ·  ⭐ 2.8K) - A new kind of Progress Bar, with real time throughput, ETA and.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/rsalmei/alive-progress) (👨‍💻 1 · 🔀 110 · 📦 470 · 📋 91 - 27% open · ⏱️ 30.10.2021):

	```
	git clone https://github.com/rsalmei/alive-progress
	```
- [PyPi](https://pypi.org/project/alive-progress) (📥 19K / month · ⏱️ 19.10.2021):
	```
	pip install alive-progress
	```
- [Conda](https://anaconda.org/conda-forge/alive-progress) (📥 11K · ⏱️ 08.01.2021):
	```
	conda install -c conda-forge alive-progress
	```
</details>
<details><summary><b><a href="https://github.com/Qix-/better-exceptions">better-exceptions</a></b> (🥉19 ·  ⭐ 4.1K) - Pretty and useful exceptions in Python, automatically. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/Qix-/better-exceptions) (👨‍💻 15 · 🔀 200 · 📋 70 - 41% open · ⏱️ 19.10.2021):

	```
	git clone https://github.com/Qix-/better-exceptions
	```
- [PyPi](https://pypi.org/project/better-exceptions) (📦 74 · ⏱️ 29.01.2021):
	```
	pip install better-exceptions
	```
</details>
<details><summary><b><a href="https://github.com/onelivesleft/PrettyErrors">PrettyErrors</a></b> (🥉19 ·  ⭐ 2.2K) - Prettify Python exception output to make it legible. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/onelivesleft/PrettyErrors) (👨‍💻 5 · 🔀 65 · ⏱️ 19.08.2021):

	```
	git clone https://github.com/onelivesleft/PrettyErrors
	```
- [PyPi](https://pypi.org/project/pretty_errors) (📥 19K / month · ⏱️ 19.08.2021):
	```
	pip install pretty_errors
	```
</details>
<details><summary><b><a href="https://github.com/cknd/stackprinter">stackprinter</a></b> (🥉18 ·  ⭐ 1.1K · 💤) - Debugging-friendly exceptions for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/cknd/stackprinter) (👨‍💻 6 · 🔀 33 · 📦 78 · 📋 26 - 42% open · ⏱️ 01.01.2021):

	```
	git clone https://github.com/cknd/stackprinter
	```
- [PyPi](https://pypi.org/project/stackprinter) (📦 4 · ⏱️ 31.10.2020):
	```
	pip install stackprinter
	```
</details>
<details><summary><b><a href="https://github.com/samuelcolvin/python-devtools">python-devtools</a></b> (🥉18 ·  ⭐ 420) - Dev tools for python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/samuelcolvin/python-devtools) (👨‍💻 7 · 🔀 15 · 📦 470 · 📋 36 - 5% open · ⏱️ 08.09.2021):

	```
	git clone https://github.com/samuelcolvin/python-devtools
	```
- [PyPi](https://pypi.org/project/python-devtools) (📦 1 · ⏱️ 21.08.2017):
	```
	pip install python-devtools
	```
</details>
<details><summary>Show 3 hidden projects...</summary>

- <b><a href="https://github.com/getlogbook/logbook">logbook</a></b> (🥈30 ·  ⭐ 1.4K · 💀) - A cool logging replacement for Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/jazzband/prettytable">prettytable</a></b> (🥉23 ·  ⭐ 580) - Display tabular data in a visually appealing ASCII table.. <code><a href="https://tldrlegal.com/search?q=BSD-1-Clause">❗️BSD-1-Clause</a></code>
- <b><a href="https://github.com/skorokithakis/tbvaccine">tbvaccine</a></b> (🥉16 ·  ⭐ 360 · 💀) - A small utility to pretty-print Python tracebacks. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>
<br>

## Documentation

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/mkdocs/mkdocs">mkdocs</a></b> (🥇36 ·  ⭐ 13K) - Project documentation with Markdown. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code> <code><img src="https://squidfunk.github.io/mkdocs-material/assets/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/mkdocs/mkdocs) (👨‍💻 200 · 🔀 1.8K · 📦 16K · 📋 1.6K - 6% open · ⏱️ 01.11.2021):

	```
	git clone https://github.com/mkdocs/mkdocs
	```
- [PyPi](https://pypi.org/project/mkdocs) (📥 800K / month · 📦 5.9K · ⏱️ 12.10.2021):
	```
	pip install mkdocs
	```
- [Conda](https://anaconda.org/conda-forge/mkdocs) (📥 160K · ⏱️ 13.10.2021):
	```
	conda install -c conda-forge mkdocs
	```
</details>
<details><summary><b><a href="https://github.com/sphinx-doc/sphinx">sphinx</a></b> (🥇36 ·  ⭐ 4.2K) - Main repository for the Sphinx documentation builder. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://www.sphinx-doc.org/en/master/_static/favicon.svg" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/sphinx-doc/sphinx) (👨‍💻 690 · 🔀 1.6K · 📦 160K · 📋 5.7K - 15% open · ⏱️ 31.10.2021):

	```
	git clone https://github.com/sphinx-doc/sphinx
	```
- [PyPi](https://pypi.org/project/sphinx) (📦 100K · ⏱️ 12.09.2021):
	```
	pip install sphinx
	```
- [Conda](https://anaconda.org/conda-forge/sphinx) (📥 4.2M · ⏱️ 12.09.2021):
	```
	conda install -c conda-forge sphinx
	```
</details>
<details><summary><b><a href="https://github.com/squidfunk/mkdocs-material">mkdocs-material</a></b> (🥇33 ·  ⭐ 7.9K) - Technical documentation that just works. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://squidfunk.github.io/mkdocs-material/assets/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/squidfunk/mkdocs-material) (👨‍💻 130 · 🔀 1.8K · 📦 9.4K · 📋 1.2K - 1% open · ⏱️ 04.11.2021):

	```
	git clone https://github.com/squidfunk/mkdocs-material
	```
- [PyPi](https://pypi.org/project/mkdocs-material) (📥 730K / month · 📦 1.5K · ⏱️ 30.10.2021):
	```
	pip install mkdocs-material
	```
- [Conda](https://anaconda.org/conda-forge/mkdocs-material) (📥 70K · ⏱️ 30.10.2021):
	```
	conda install -c conda-forge mkdocs-material
	```
</details>
<details><summary><b><a href="https://github.com/readthedocs/sphinx_rtd_theme">sphinx_rtd_theme</a></b> (🥇33 ·  ⭐ 3.9K) - Sphinx theme for readthedocs.org. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://www.sphinx-doc.org/en/master/_static/favicon.svg" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/readthedocs/sphinx_rtd_theme) (👨‍💻 110 · 🔀 1.6K · 📦 16 · 📋 720 - 25% open · ⏱️ 19.10.2021):

	```
	git clone https://github.com/readthedocs/sphinx_rtd_theme
	```
- [PyPi](https://pypi.org/project/sphinx_rtd_theme) (📥 1.8M / month · 📦 23K · ⏱️ 05.10.2018):
	```
	pip install sphinx_rtd_theme
	```
- [Conda](https://anaconda.org/conda-forge/sphinx_rtd_theme) (📥 1.9M · ⏱️ 17.09.2021):
	```
	conda install -c conda-forge sphinx_rtd_theme
	```
</details>
<details><summary><b><a href="https://github.com/numpy/numpydoc">numpydoc</a></b> (🥈30 ·  ⭐ 19K) - Numpy's Sphinx extensions. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://www.sphinx-doc.org/en/master/_static/favicon.svg" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/numpy/numpydoc) (👨‍💻 67 · 🔀 6K · 📦 29K · 📋 160 - 37% open · ⏱️ 25.10.2021):

	```
	git clone https://github.com/numpy/numpydoc
	```
- [PyPi](https://pypi.org/project/numpydoc) (📥 250K / month · 📦 7.3K · ⏱️ 01.07.2020):
	```
	pip install numpydoc
	```
- [Conda](https://anaconda.org/conda-forge/numpydoc) (📥 860K · ⏱️ 01.10.2020):
	```
	conda install -c conda-forge numpydoc
	```
</details>
<details><summary><b><a href="https://github.com/michaeljones/breathe">breathe</a></b> (🥈29 ·  ⭐ 560) - ReStructuredText and Sphinx bridge to Doxygen. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/michaeljones/breathe) (👨‍💻 96 · 🔀 140 · 📥 140 · 📦 5.3K · 📋 470 - 25% open · ⏱️ 29.09.2021):

	```
	git clone https://github.com/michaeljones/breathe
	```
- [PyPi](https://pypi.org/project/breathe) (📥 170K / month · 📦 2K · ⏱️ 14.09.2021):
	```
	pip install breathe
	```
- [Conda](https://anaconda.org/conda-forge/breathe) (📥 230K · ⏱️ 15.09.2021):
	```
	conda install -c conda-forge breathe
	```
</details>
<details><summary><b><a href="https://github.com/bitprophet/alabaster">alabaster</a></b> (🥈28 ·  ⭐ 620) - Lightweight, configurable Sphinx theme. Now the Sphinx default!. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://www.sphinx-doc.org/en/master/_static/favicon.svg" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/bitprophet/alabaster) (👨‍💻 28 · 🔀 180 · 📦 53K · 📋 140 - 60% open · ⏱️ 24.09.2021):

	```
	git clone https://github.com/bitprophet/alabaster
	```
- [PyPi](https://pypi.org/project/alabaster) (📦 15K · ⏱️ 03.10.2018):
	```
	pip install alabaster
	```
- [Conda](https://anaconda.org/conda-forge/alabaster) (📥 3.1M · ⏱️ 03.10.2018):
	```
	conda install -c conda-forge alabaster
	```
</details>
<details><summary><b><a href="https://github.com/ryan-roemer/sphinx-bootstrap-theme">sphinx-bootstrap-theme</a></b> (🥈28 ·  ⭐ 580) - Sphinx Bootstrap Theme. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://www.sphinx-doc.org/en/master/_static/favicon.svg" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/ryan-roemer/sphinx-bootstrap-theme) (👨‍💻 38 · 🔀 210 · 📋 140 - 40% open · ⏱️ 02.10.2021):

	```
	git clone https://github.com/ryan-roemer/sphinx-bootstrap-theme
	```
- [PyPi](https://pypi.org/project/sphinx-bootstrap-theme) (📥 180K / month · 📦 980 · ⏱️ 12.09.2021):
	```
	pip install sphinx-bootstrap-theme
	```
</details>
<details><summary><b><a href="https://github.com/agronholm/sphinx-autodoc-typehints">sphinx-autodoc-typehints</a></b> (🥈26 ·  ⭐ 370) - Type hints support for the Sphinx autodoc extension. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://www.sphinx-doc.org/en/master/_static/favicon.svg" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/agronholm/sphinx-autodoc-typehints) (👨‍💻 30 · 🔀 70 · 📋 130 - 44% open · ⏱️ 08.10.2021):

	```
	git clone https://github.com/agronholm/sphinx-autodoc-typehints
	```
- [PyPi](https://pypi.org/project/sphinx-autodoc-typehints) (📥 300K / month · 📦 1.4K · ⏱️ 12.10.2020):
	```
	pip install sphinx-autodoc-typehints
	```
- [Conda](https://anaconda.org/conda-forge/sphinx-autodoc-typehints) (📥 240K · ⏱️ 15.04.2021):
	```
	conda install -c conda-forge sphinx-autodoc-typehints
	```
</details>
<details><summary><b><a href="https://github.com/econchick/interrogate">interrogate</a></b> (🥈26 ·  ⭐ 320) - Explain yourself! Interrogate a codebase for docstring coverage. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/econchick/interrogate) (👨‍💻 11 · 🔀 22 · 📦 1K · 📋 31 - 25% open · ⏱️ 10.09.2021):

	```
	git clone https://github.com/econchick/interrogate
	```
- [PyPi](https://pypi.org/project/interrogate) (📥 110K / month · ⏱️ 10.09.2021):
	```
	pip install interrogate
	```
</details>
<details><summary><b><a href="https://github.com/mitmproxy/pdoc">pdoc</a></b> (🥈24 ·  ⭐ 1.1K) - API Documentation for Python Projects. <code><a href="http://bit.ly/3rvuUlR">Unlicense</a></code></summary>

- [GitHub](https://github.com/mitmproxy/pdoc) (👨‍💻 31 · 🔀 120 · 📦 440 · 📋 190 - 4% open · ⏱️ 29.10.2021):

	```
	git clone https://github.com/mitmproxy/pdoc
	```
- [PyPi](https://pypi.org/project/pdoc) (📥 92K / month · 📦 290 · ⏱️ 29.10.2021):
	```
	pip install pdoc
	```
</details>
<details><summary><b><a href="https://github.com/bitprophet/releases">releases</a></b> (🥈24 ·  ⭐ 160) - A powerful Sphinx changelog-generating extension. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code> <code><img src="https://www.sphinx-doc.org/en/master/_static/favicon.svg" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/bitprophet/releases) (👨‍💻 10 · 🔀 36 · 📦 390 · 📋 76 - 43% open · ⏱️ 24.09.2021):

	```
	git clone https://github.com/bitprophet/releases
	```
- [PyPi](https://pypi.org/project/releases) (📥 11K / month · 📦 710 · ⏱️ 11.01.2020):
	```
	pip install releases
	```
</details>
<details><summary><b><a href="https://github.com/executablebooks/sphinx-autobuild">sphinx-autobuild</a></b> (🥉23 ·  ⭐ 360 · 💤) - Watch a Sphinx directory and rebuild the.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://www.sphinx-doc.org/en/master/_static/favicon.svg" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/executablebooks/sphinx-autobuild) (👨‍💻 17 · 🔀 50 · 📋 57 - 22% open · ⏱️ 14.03.2021):

	```
	git clone https://github.com/executablebooks/sphinx-autobuild
	```
- [PyPi](https://pypi.org/project/sphinx-autobuild) (📥 190K / month · 📦 4.7K · ⏱️ 14.03.2021):
	```
	pip install sphinx-autobuild
	```
- [Conda](https://anaconda.org/conda-forge/sphinx-autobuild) (📥 77K · ⏱️ 14.03.2021):
	```
	conda install -c conda-forge sphinx-autobuild
	```
</details>
<details><summary><b><a href="https://github.com/mkdocstrings/mkdocstrings">mkdocstrings</a></b> (🥉22 ·  ⭐ 520) - Automatic documentation from sources, for MkDocs. <code><a href="http://bit.ly/3hkKRql">ISC</a></code> <code><img src="https://squidfunk.github.io/mkdocs-material/assets/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/mkdocstrings/mkdocstrings) (👨‍💻 25 · 🔀 53 · 📋 200 - 24% open · ⏱️ 31.10.2021):

	```
	git clone https://github.com/mkdocstrings/mkdocstrings
	```
- [PyPi](https://pypi.org/project/mkdocstrings) (📥 83K / month · ⏱️ 04.10.2021):
	```
	pip install mkdocstrings
	```
- [Conda](https://anaconda.org/conda-forge/mkdocstrings) (📥 9.5K · ⏱️ 04.10.2021):
	```
	conda install -c conda-forge mkdocstrings
	```
</details>
<details><summary><b><a href="https://github.com/zhaoterryy/mkdocs-pdf-export-plugin">mkdocs-pdf-export-plugin</a></b> (🥉22 ·  ⭐ 220) - An MkDocs plugin to export content pages as PDF files. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://squidfunk.github.io/mkdocs-material/assets/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/zhaoterryy/mkdocs-pdf-export-plugin) (👨‍💻 11 · 🔀 34 · 📦 170 · 📋 85 - 48% open · ⏱️ 05.10.2021):

	```
	git clone https://github.com/zhaoterryy/mkdocs-pdf-export-plugin
	```
- [PyPi](https://pypi.org/project/mkdocs-pdf-export-plugin) (📥 14K / month · 📦 4 · ⏱️ 05.10.2021):
	```
	pip install mkdocs-pdf-export-plugin
	```
</details>
<details><summary><b><a href="https://github.com/lukasgeiter/mkdocs-awesome-pages-plugin">mkdocs-awesome-pages-plugin</a></b> (🥉22 ·  ⭐ 190 · 📈) - An MkDocs plugin that simplifies configuring page.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://squidfunk.github.io/mkdocs-material/assets/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/lukasgeiter/mkdocs-awesome-pages-plugin) (👨‍💻 3 · 🔀 20 · 📦 540 · 📋 47 - 23% open · ⏱️ 19.10.2021):

	```
	git clone https://github.com/lukasgeiter/mkdocs-awesome-pages-plugin
	```
- [PyPi](https://pypi.org/project/mkdocs-awesome-pages-plugin) (📥 46K / month · 📦 90 · ⏱️ 19.10.2021):
	```
	pip install mkdocs-awesome-pages-plugin
	```
</details>
<details><summary><b><a href="https://github.com/pdoc3/pdoc">pdoc3</a></b> (🥉21 ·  ⭐ 740 · 📉) - Auto-generate API documentation for Python projects. <code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code></summary>

- [GitHub](https://github.com/pdoc3/pdoc) (👨‍💻 56 · 🔀 120 · 📦 1.1K · 📋 270 - 32% open · ⏱️ 24.09.2021):

	```
	git clone https://github.com/pdoc3/pdoc
	```
- [PyPi](https://pypi.org/project/pdoc3) (📦 90 · ⏱️ 03.08.2021):
	```
	pip install pdoc3
	```
</details>
<details><summary><b><a href="https://github.com/orzih/mkdocs-with-pdf">mkdocs-with-pdf</a></b> (🥉21 ·  ⭐ 97) - Generate a single PDF file from MkDocs repository. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://squidfunk.github.io/mkdocs-material/assets/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/orzih/mkdocs-with-pdf) (👨‍💻 6 · 🔀 18 · 📦 68 · 📋 62 - 40% open · ⏱️ 14.10.2021):

	```
	git clone https://github.com/orzih/mkdocs-with-pdf
	```
- [PyPi](https://pypi.org/project/mkdocs-with-pdf) (📥 10K / month · ⏱️ 03.07.2021):
	```
	pip install mkdocs-with-pdf
	```
</details>
<details><summary><b><a href="https://github.com/asottile/blacken-docs">blacken-docs</a></b> (🥉20 ·  ⭐ 280) - Run `black` on python code blocks in documentation files. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/asottile/blacken-docs) (👨‍💻 12 · 🔀 18 · 📋 35 - 5% open · ⏱️ 25.10.2021):

	```
	git clone https://github.com/asottile/blacken-docs
	```
- [PyPi](https://pypi.org/project/blacken-docs) (📦 22 · ⏱️ 27.08.2021):
	```
	pip install blacken-docs
	```
- [Conda](https://anaconda.org/conda-forge/blacken-docs) (📥 18K · ⏱️ 27.08.2021):
	```
	conda install -c conda-forge blacken-docs
	```
</details>
<details><summary><b><a href="https://github.com/timothycrosley/portray">portray</a></b> (🥉17 ·  ⭐ 770) - Your Project with Great Documentation. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/timothycrosley/portray) (👨‍💻 16 · 🔀 58 · 📋 50 - 42% open · ⏱️ 13.06.2021):

	```
	git clone https://github.com/timothycrosley/portray
	```
- [PyPi](https://pypi.org/project/portray) (📥 7.7K / month · 📦 8 · ⏱️ 13.06.2021):
	```
	pip install portray
	```
</details>
<details><summary><b><a href="https://github.com/ml-tooling/lazydocs">lazydocs</a></b> (🥉16 ·  ⭐ 47) - Generate markdown API documentation from Google-style Python docstring... <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ml-tooling/lazydocs) (👨‍💻 7 · 🔀 11 · 📦 50 · 📋 5 - 40% open · ⏱️ 20.08.2021):

	```
	git clone https://github.com/ml-tooling/lazydocs
	```
- [PyPi](https://pypi.org/project/lazydocs) (📥 1.1K / month · ⏱️ 27.07.2021):
	```
	pip install lazydocs
	```
</details>
<details><summary>Show 5 hidden projects...</summary>

- <b><a href="https://github.com/pycco-docs/pycco">pycco</a></b> (🥉22 ·  ⭐ 760 · 💀) - Literate-style documentation generator. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/clayrisser/sphinx-markdown-builder">sphinx-markdown-builder</a></b> (🥉21 ·  ⭐ 110 · 💀) - sphinx builder that outputs markdown files. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://www.sphinx-doc.org/en/master/_static/favicon.svg" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/zhaoterryy/mkdocs-git-revision-date-plugin">mkdocs-git-revision-date-plugin</a></b> (🥉19 ·  ⭐ 38 · 💀) - MkDocs plugin for setting revision date from git per.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://squidfunk.github.io/mkdocs-material/assets/favicon.png" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/timvink/mkdocs-print-site-plugin">mkdocs-print-site-plugin</a></b> (🥉19 ·  ⭐ 24 · 📈) - MkDocs Plugin that adds an additional page that.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://squidfunk.github.io/mkdocs-material/assets/favicon.png" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/zayd62/mkdocs-versioning">mkdocs-versioning</a></b> (🥉14 ·  ⭐ 40) - A tool that allows for versioning sites built with mkdocs. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://squidfunk.github.io/mkdocs-material/assets/favicon.png" style="display:inline;" width="13" height="13"></code>
</details>
<br>

## Debugging Tools

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/gotcha/ipdb">ipdb</a></b> (🥇31 ·  ⭐ 1.5K) - Integration of IPython pdb. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/gotcha/ipdb) (👨‍💻 49 · 🔀 130 · 📦 29K · 📋 170 - 33% open · ⏱️ 09.09.2021):

	```
	git clone https://github.com/gotcha/ipdb
	```
- [PyPi](https://pypi.org/project/ipdb) (📥 1.7M / month · 📦 17K · ⏱️ 02.06.2021):
	```
	pip install ipdb
	```
- [Conda](https://anaconda.org/conda-forge/ipdb) (📥 210K · ⏱️ 24.06.2021):
	```
	conda install -c conda-forge ipdb
	```
</details>
<details><summary><b><a href="https://github.com/inducer/pudb">pudb</a></b> (🥇28 ·  ⭐ 2.2K) - Full-screen console debugger for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/inducer/pudb) (👨‍💻 80 · 🔀 190 · 📦 2.6K · 📋 280 - 48% open · ⏱️ 01.11.2021):

	```
	git clone https://github.com/inducer/pudb
	```
- [PyPi](https://pypi.org/project/pudb) (📥 160K / month · 📦 1.4K · ⏱️ 01.11.2021):
	```
	pip install pudb
	```
- [Conda](https://anaconda.org/conda-forge/pudb) (📥 110K · ⏱️ 21.08.2021):
	```
	conda install -c conda-forge pudb
	```
</details>
<details><summary><b><a href="https://github.com/cool-RR/PySnooper">PySnooper</a></b> (🥈27 ·  ⭐ 15K) - Never use print for debugging again. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/cool-RR/PySnooper) (👨‍💻 26 · 🔀 910 · 📦 510 · 📋 110 - 16% open · ⏱️ 11.09.2021):

	```
	git clone https://github.com/cool-RR/PySnooper
	```
- [PyPi](https://pypi.org/project/pysnooper) (📦 46 · ⏱️ 11.09.2021):
	```
	pip install pysnooper
	```
- [Conda](https://anaconda.org/conda-forge/pysnooper) (📥 42K · ⏱️ 19.05.2021):
	```
	conda install -c conda-forge pysnooper
	```
</details>
<details><summary><b><a href="https://github.com/agronholm/typeguard">typeguard</a></b> (🥈26 ·  ⭐ 750) - Run-time type checker for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/agronholm/typeguard) (👨‍💻 18 · 🔀 64 · 📋 170 - 19% open · ⏱️ 11.10.2021):

	```
	git clone https://github.com/agronholm/typeguard
	```
- [PyPi](https://pypi.org/project/typeguard) (📥 15M / month · 📦 160 · ⏱️ 10.10.2021):
	```
	pip install typeguard
	```
- [Conda](https://anaconda.org/conda-forge/typeguard) (📥 60K · ⏱️ 11.10.2021):
	```
	conda install -c conda-forge typeguard
	```
</details>
<details><summary><b><a href="https://github.com/eliben/pyelftools">pyelftools</a></b> (🥈25 ·  ⭐ 1.3K) - Parsing ELF and DWARF in Python. <code><a href="http://bit.ly/3rvuUlR">Unlicense</a></code></summary>

- [GitHub](https://github.com/eliben/pyelftools) (👨‍💻 80 · 🔀 400 · 📦 2.6K · 📋 170 - 31% open · ⏱️ 29.10.2021):

	```
	git clone https://github.com/eliben/pyelftools
	```
- [PyPi](https://pypi.org/project/pyelftools) (📦 880 · ⏱️ 27.10.2020):
	```
	pip install pyelftools
	```
- [Conda](https://anaconda.org/conda-forge/pyelftools) (📥 77K · ⏱️ 27.10.2020):
	```
	conda install -c conda-forge pyelftools
	```
</details>
<details><summary><b><a href="https://github.com/pdbpp/pdbpp">pdbpp</a></b> (🥈25 ·  ⭐ 820) - pdb++, a drop-in replacement for pdb (the Python debugger). <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/pdbpp/pdbpp) (👨‍💻 40 · 🔀 46 · 📦 2.4K · 📋 180 - 35% open · ⏱️ 28.09.2021):

	```
	git clone https://github.com/pdbpp/pdbpp
	```
- [PyPi](https://pypi.org/project/pdbpp) (📦 1K · ⏱️ 09.07.2021):
	```
	pip install pdbpp
	```
- [Conda](https://anaconda.org/conda-forge/pdbpp) (📥 65K · ⏱️ 11.07.2021):
	```
	conda install -c conda-forge pdbpp
	```
</details>
<details><summary><b><a href="https://github.com/alexmojaki/snoop">snoop</a></b> (🥉24 ·  ⭐ 650) - A powerful set of Python debugging tools, based on PySnooper. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/alexmojaki/snoop) (👨‍💻 21 · 🔀 23 · 📦 66 · 📋 35 - 51% open · ⏱️ 09.10.2021):

	```
	git clone https://github.com/alexmojaki/snoop
	```
- [PyPi](https://pypi.org/project/snoop) (📥 29K / month · 📦 8 · ⏱️ 05.07.2021):
	```
	pip install snoop
	```
</details>
<details><summary><b><a href="https://github.com/cs01/gdbgui">gdbgui</a></b> (🥉23 ·  ⭐ 8.3K) - Browser-based frontend to gdb (gnu debugger). Add breakpoints, view.. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/cs01/gdbgui) (👨‍💻 38 · 🔀 480 · 📥 5.7K · 📦 120 · 📋 280 - 40% open · ⏱️ 06.09.2021):

	```
	git clone https://github.com/cs01/gdbgui
	```
- [PyPi](https://pypi.org/project/gdbgui) (📦 2 · ⏱️ 06.09.2021):
	```
	pip install gdbgui
	```
</details>
<details><summary><b><a href="https://github.com/gruns/icecream">icecream</a></b> (🥉22 ·  ⭐ 5.5K) - Never use print() to debug again. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/gruns/icecream) (👨‍💻 16 · 🔀 110 · 📋 82 - 31% open · ⏱️ 31.08.2021):

	```
	git clone https://github.com/gruns/icecream
	```
- [PyPi](https://pypi.org/project/icecream) (📥 120K / month · 📦 6 · ⏱️ 22.06.2021):
	```
	pip install icecream
	```
</details>
<details><summary><b><a href="https://github.com/ionelmc/python-hunter">python-hunter</a></b> (🥉19 ·  ⭐ 650) - Hunter is a flexible code tracing toolkit. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/ionelmc/python-hunter) (👨‍💻 9 · 🔀 35 · 📦 68 · 📋 87 - 42% open · ⏱️ 13.10.2021):

	```
	git clone https://github.com/ionelmc/python-hunter
	```
- [PyPi](https://pypi.org/project/hunter) (📦 34 · ⏱️ 23.06.2021):
	```
	pip install hunter
	```
</details>
<details><summary><b><a href="https://github.com/alexmojaki/birdseye">Birdseye</a></b> (🥉18 ·  ⭐ 1.4K) - Graphical Python debugger which lets you easily view the values of all.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/alexmojaki/birdseye) (👨‍💻 10 · 🔀 68 · 📋 50 - 36% open · ⏱️ 01.08.2021):

	```
	git clone https://github.com/alexmojaki/birdseye
	```
- [PyPi](https://pypi.org/project/birdseye) (📥 1K / month · ⏱️ 01.08.2021):
	```
	pip install birdseye
	```
</details>
<details><summary><b><a href="https://github.com/ionelmc/python-manhole">python-manhole</a></b> (🥉17 ·  ⭐ 310) - Debugging manhole for python applications. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/ionelmc/python-manhole) (👨‍💻 11 · 🔀 16 · 📦 77 · 📋 20 - 25% open · ⏱️ 15.09.2021):

	```
	git clone https://github.com/ionelmc/python-manhole
	```
- [PyPi](https://pypi.org/project/manhole) (📦 66 · ⏱️ 08.04.2021):
	```
	pip install manhole
	```
</details>
<details><summary>Show 1 hidden projects...</summary>

- <b><a href="https://github.com/lmacken/pyrasite">pyrasite</a></b> (🥉20 ·  ⭐ 2.6K · 💀) - Inject code into running Python processes. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
</details>
<br>

## Testing Tools

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

🔗&nbsp;<b><a href="https://github.com/ml-tooling/best-of-web-python">best-of-web-python - Testing</a></b> ( ⭐ 1.4K)  - Testing libraries & tools for python web frameworks.

🔗&nbsp;<b><a href="https://docs.python.org/3/library/unittest.html">unittest</a></b>  - Unittest is a test framework included in the Python standard library.

<details><summary><b><a href="https://github.com/tox-dev/tox">tox</a></b> (🥇35 ·  ⭐ 2.5K) - Command line driven CI frontend and development task automation tool. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tox-dev/tox) (👨‍💻 250 · 🔀 380 · 📦 50K · 📋 1.3K - 10% open · ⏱️ 11.10.2021):

	```
	git clone https://github.com/tox-dev/tox
	```
- [PyPi](https://pypi.org/project/tox) (📥 3.9M / month · 📦 36K · ⏱️ 16.09.2021):
	```
	pip install tox
	```
- [Conda](https://anaconda.org/conda-forge/tox) (📥 370K · ⏱️ 04.11.2021):
	```
	conda install -c conda-forge tox
	```
</details>
<details><summary><b><a href="https://github.com/pytest-dev/pytest-cov">pytest-cov</a></b> (🥇34 ·  ⭐ 1.1K · 📈) - Coverage plugin for pytest. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytest-dev/pytest-cov) (👨‍💻 72 · 🔀 160 · 📦 100K · 📋 300 - 34% open · ⏱️ 10.10.2021):

	```
	git clone https://github.com/pytest-dev/pytest-cov
	```
- [PyPi](https://pypi.org/project/pytest-cov) (📥 11M / month · 📦 43K · ⏱️ 04.10.2021):
	```
	pip install pytest-cov
	```
- [Conda](https://anaconda.org/conda-forge/pytest-cov) (📥 3.9M · ⏱️ 04.10.2021):
	```
	conda install -c conda-forge pytest-cov
	```
</details>
<details><summary><b><a href="https://github.com/pytest-dev/pytest">pytest</a></b> (🥇33 ·  ⭐ 7.9K) - The pytest framework makes it easy to write small tests, yet scales.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytest-dev/pytest) (👨‍💻 750 · 🔀 1.8K · 📦 390K · 📋 4.7K - 15% open · ⏱️ 03.11.2021):

	```
	git clone https://github.com/pytest-dev/pytest
	```
- [PyPi](https://pypi.org/project/pytest) (📦 130K · ⏱️ 30.08.2021):
	```
	pip install pytest
	```
- [Conda](https://anaconda.org/conda-forge/pytest) (📥 10M · ⏱️ 02.11.2021):
	```
	conda install -c conda-forge pytest
	```
</details>
<details><summary><b><a href="https://github.com/HypothesisWorks/hypothesis">hypothesis</a></b> (🥇32 ·  ⭐ 5.5K) - Hypothesis is a powerful, flexible, and easy to use library for.. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code></summary>

- [GitHub](https://github.com/HypothesisWorks/hypothesis) (👨‍💻 250 · 🔀 480 · 📦 10K · 📋 1.2K - 5% open · ⏱️ 01.11.2021):

	```
	git clone https://github.com/HypothesisWorks/hypothesis
	```
- [PyPi](https://pypi.org/project/hypothesis) (📦 2.6K · ⏱️ 01.11.2021):
	```
	pip install hypothesis
	```
- [Conda](https://anaconda.org/conda-forge/hypothesis) (📥 4.9M · ⏱️ 01.11.2021):
	```
	conda install -c conda-forge hypothesis
	```
</details>
<details><summary><b><a href="https://github.com/robotframework/robotframework">robotframework</a></b> (🥈31 ·  ⭐ 6.4K) - Generic automation framework for acceptance testing and RPA. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/robotframework/robotframework) (👨‍💻 150 · 🔀 1.8K · 📥 510 · 📦 4.4K · 📋 3.7K - 6% open · ⏱️ 04.11.2021):

	```
	git clone https://github.com/robotframework/robotframework
	```
- [PyPi](https://pypi.org/project/robotframework) (📦 1.4K · ⏱️ 15.10.2021):
	```
	pip install robotframework
	```
- [Conda](https://anaconda.org/conda-forge/robotframework) (📥 66K · ⏱️ 15.10.2021):
	```
	conda install -c conda-forge robotframework
	```
</details>
<details><summary><b><a href="https://github.com/spulec/freezegun">freezegun</a></b> (🥈31 ·  ⭐ 3K) - Let your Python tests travel through time. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/spulec/freezegun) (👨‍💻 97 · 🔀 200 · 📋 240 - 28% open · ⏱️ 25.08.2021):

	```
	git clone https://github.com/spulec/freezegun
	```
- [PyPi](https://pypi.org/project/freezegun) (📥 3.7M / month · 📦 8.4K · ⏱️ 20.01.2021):
	```
	pip install freezegun
	```
- [Conda](https://anaconda.org/conda-forge/freezegun) (📥 280K · ⏱️ 20.01.2021):
	```
	conda install -c conda-forge freezegun
	```
</details>
<details><summary><b><a href="https://github.com/pytest-dev/pytest-asyncio">pytest-asyncio</a></b> (🥈31 ·  ⭐ 800) - Pytest support for asyncio. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytest-dev/pytest-asyncio) (👨‍💻 26 · 🔀 89 · 📦 17K · 📋 180 - 43% open · ⏱️ 15.10.2021):

	```
	git clone https://github.com/pytest-dev/pytest-asyncio
	```
- [PyPi](https://pypi.org/project/pytest-asyncio) (📥 3.9M / month · 📦 2K · ⏱️ 15.10.2021):
	```
	pip install pytest-asyncio
	```
- [Conda](https://anaconda.org/conda-forge/pytest-asyncio) (📥 660K · ⏱️ 18.10.2021):
	```
	conda install -c conda-forge pytest-asyncio
	```
</details>
<details><summary><b><a href="https://github.com/pytest-dev/pytest-xdist">pytest-xdist</a></b> (🥈31 ·  ⭐ 780) - pytest plugin for distributed testing and loop-on-failures.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytest-dev/pytest-xdist) (👨‍💻 76 · 🔀 160 · 📋 450 - 45% open · ⏱️ 02.11.2021):

	```
	git clone https://github.com/pytest-dev/pytest-xdist
	```
- [PyPi](https://pypi.org/project/pytest-xdist) (📥 5.1M / month · 📦 7.3K · ⏱️ 21.09.2021):
	```
	pip install pytest-xdist
	```
- [Conda](https://anaconda.org/conda-forge/pytest-xdist) (📥 2M · ⏱️ 21.09.2021):
	```
	conda install -c conda-forge pytest-xdist
	```
</details>
<details><summary><b><a href="https://github.com/TheKevJames/coveralls-python">coveralls-python</a></b> (🥈31 ·  ⭐ 460) - Show coverage stats online via coveralls.io. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/TheKevJames/coveralls-python) (👨‍💻 61 · 🔀 180 · 📦 19K · 📋 150 - 3% open · ⏱️ 04.11.2021):

	```
	git clone https://github.com/TheKevJames/coveralls-python
	```
- [PyPi](https://pypi.org/project/coveralls) (📥 500K / month · 📦 17K · ⏱️ 04.11.2021):
	```
	pip install coveralls
	```
</details>
<details><summary><b><a href="https://github.com/FactoryBoy/factory_boy">factory_boy</a></b> (🥈30 ·  ⭐ 2.7K) - A test fixtures replacement for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/FactoryBoy/factory_boy) (👨‍💻 120 · 🔀 330 · 📋 510 - 30% open · ⏱️ 19.10.2021):

	```
	git clone https://github.com/FactoryBoy/factory_boy
	```
- [PyPi](https://pypi.org/project/factory_boy) (📥 1.9M / month · 📦 4.3K · ⏱️ 05.05.2018):
	```
	pip install factory_boy
	```
- [Conda](https://anaconda.org/conda-forge/factory_boy) (📥 85K · ⏱️ 26.10.2021):
	```
	conda install -c conda-forge factory_boy
	```
</details>
<details><summary><b><a href="https://github.com/pytest-dev/pytest-mock">pytest-mock</a></b> (🥈29 ·  ⭐ 1.2K) - Thin-wrapper around the mock package for easier use with pytest. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytest-dev/pytest-mock) (👨‍💻 54 · 🔀 98 · 📦 20K · 📋 100 - 11% open · ⏱️ 01.11.2021):

	```
	git clone https://github.com/pytest-dev/pytest-mock
	```
- [PyPi](https://pypi.org/project/pytest-mock) (📥 5.1M / month · 📦 6.2K · ⏱️ 06.05.2021):
	```
	pip install pytest-mock
	```
- [Conda](https://anaconda.org/conda-forge/pytest-mock) (📥 1.3M · ⏱️ 07.05.2021):
	```
	conda install -c conda-forge pytest-mock
	```
</details>
<details><summary><b><a href="https://github.com/pytest-dev/pytest-html">pytest-html</a></b> (🥈29 ·  ⭐ 450 · 💤) - Plugin for generating HTML reports for pytest results. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytest-dev/pytest-html) (👨‍💻 43 · 🔀 180 · 📦 13K · 📋 270 - 33% open · ⏱️ 23.01.2021):

	```
	git clone https://github.com/pytest-dev/pytest-html
	```
- [PyPi](https://pypi.org/project/pytest-html) (📥 1.5M / month · 📦 980 · ⏱️ 13.12.2020):
	```
	pip install pytest-html
	```
- [Conda](https://anaconda.org/conda-forge/pytest-html) (📥 180K · ⏱️ 13.12.2020):
	```
	conda install -c conda-forge pytest-html
	```
</details>
<details><summary><b><a href="https://github.com/asweigart/pyautogui">pyautogui</a></b> (🥈28 ·  ⭐ 5.7K) - A cross-platform GUI automation Python module for human beings. Used.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/asweigart/pyautogui) (👨‍💻 51 · 🔀 770 · 📦 11K · 📋 530 - 63% open · ⏱️ 14.09.2021):

	```
	git clone https://github.com/asweigart/pyautogui
	```
- [PyPi](https://pypi.org/project/pyautogui) (📦 610 · ⏱️ 07.07.2021):
	```
	pip install pyautogui
	```
- [Conda](https://anaconda.org/conda-forge/pyautogui) (📥 140K · ⏱️ 13.10.2021):
	```
	conda install -c conda-forge pyautogui
	```
</details>
<details><summary><b><a href="https://github.com/microsoft/playwright-python">playwright-python</a></b> (🥈28 ·  ⭐ 5.4K) - Python version of the Playwright testing and automation.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/microsoft/playwright-python) (👨‍💻 21 · 🔀 460 · 📦 500 · 📋 490 - 4% open · ⏱️ 04.11.2021):

	```
	git clone https://github.com/microsoft/playwright-python
	```
- [PyPi](https://pypi.org/project/playwright) (📥 130K / month · ⏱️ 29.10.2021):
	```
	pip install playwright
	```
</details>
<details><summary><b><a href="https://github.com/lk-geimfari/mimesis">mimesis</a></b> (🥈28 ·  ⭐ 3.4K) - Mimesis is a high-performance fake data generator for Python, which.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/lk-geimfari/mimesis) (👨‍💻 110 · 🔀 280 · 📥 180 · 📋 300 - 1% open · ⏱️ 02.11.2021):

	```
	git clone https://github.com/lk-geimfari/mimesis
	```
- [PyPi](https://pypi.org/project/mimesis) (📥 83K / month · 📦 84 · ⏱️ 29.10.2021):
	```
	pip install mimesis
	```
</details>
<details><summary><b><a href="https://github.com/datadriventests/ddt">ddt</a></b> (🥈28 ·  ⭐ 400) - Data-Driven Tests for Python Unittest. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/datadriventests/ddt) (👨‍💻 36 · 🔀 100 · 📦 3.8K · 📋 53 - 28% open · ⏱️ 04.10.2021):

	```
	git clone https://github.com/datadriventests/ddt
	```
- [PyPi](https://pypi.org/project/ddt) (📥 280K / month · 📦 2.5K · ⏱️ 04.10.2021):
	```
	pip install ddt
	```
- [Conda](https://anaconda.org/conda-forge/ddt) (📥 65K · ⏱️ 15.05.2020):
	```
	conda install -c conda-forge ddt
	```
</details>
<details><summary><b><a href="https://github.com/pytest-dev/pytest-bdd">pytest-bdd</a></b> (🥉27 ·  ⭐ 900) - BDD library for the py.test runner. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytest-dev/pytest-bdd) (👨‍💻 44 · 🔀 150 · 📋 260 - 48% open · ⏱️ 25.10.2021):

	```
	git clone https://github.com/pytest-dev/pytest-bdd
	```
- [PyPi](https://pypi.org/project/pytest-bdd) (📥 240K / month · 📦 270 · ⏱️ 25.10.2021):
	```
	pip install pytest-bdd
	```
- [Conda](https://anaconda.org/conda-forge/pytest-bdd) (📥 40K · ⏱️ 03.02.2020):
	```
	conda install -c conda-forge pytest-bdd
	```
</details>
<details><summary><b><a href="https://github.com/nose-devs/nose2">nose2</a></b> (🥉27 ·  ⭐ 690) - The successor to nose, based on unittest2. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/nose-devs/nose2) (👨‍💻 71 · 🔀 130 · 📦 4.2K · 📋 260 - 21% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/nose-devs/nose2
	```
- [PyPi](https://pypi.org/project/nose2) (📥 410K / month · 📦 1.9K · ⏱️ 27.01.2021):
	```
	pip install nose2
	```
- [Conda](https://anaconda.org/conda-forge/nose2) (📥 39K · ⏱️ 02.02.2020):
	```
	conda install -c conda-forge nose2
	```
</details>
<details><summary><b><a href="https://github.com/ionelmc/pytest-benchmark">pytest-benchmark</a></b> (🥉26 ·  ⭐ 810) - py.test fixture for benchmarking code. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/ionelmc/pytest-benchmark) (👨‍💻 34 · 🔀 86 · 📦 2.3K · 📋 150 - 49% open · ⏱️ 14.06.2021):

	```
	git clone https://github.com/ionelmc/pytest-benchmark
	```
- [PyPi](https://pypi.org/project/pytest-benchmark) (📥 480K / month · 📦 730 · ⏱️ 17.04.2021):
	```
	pip install pytest-benchmark
	```
- [Conda](https://anaconda.org/conda-forge/pytest-benchmark) (📥 990K · ⏱️ 18.04.2021):
	```
	conda install -c conda-forge pytest-benchmark
	```
</details>
<details><summary><b><a href="https://github.com/hamcrest/PyHamcrest">PyHamcrest</a></b> (🥉25 ·  ⭐ 580) - Hamcrest matchers for Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/hamcrest/PyHamcrest) (👨‍💻 35 · 🔀 87 · 📋 65 - 24% open · ⏱️ 10.10.2021):

	```
	git clone https://github.com/hamcrest/PyHamcrest
	```
- [PyPi](https://pypi.org/project/pyhamcrest) (📥 960K / month · 📦 3.4K · ⏱️ 02.03.2020):
	```
	pip install pyhamcrest
	```
- [Conda](https://anaconda.org/conda-forge/pyhamcrest) (📥 380K · ⏱️ 02.03.2020):
	```
	conda install -c conda-forge pyhamcrest
	```
</details>
<details><summary><b><a href="https://github.com/pytest-dev/pytest-testinfra">pytest-testinfra</a></b> (🥉24 ·  ⭐ 2K) - Testinfra test your infrastructures. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytest-dev/pytest-testinfra) (👨‍💻 110 · 🔀 280 · 📋 310 - 36% open · ⏱️ 04.11.2021):

	```
	git clone https://github.com/pytest-dev/pytest-testinfra
	```
- [PyPi](https://pypi.org/project/pytest-testinfra) (📥 120K / month · ⏱️ 20.06.2021):
	```
	pip install pytest-testinfra
	```
</details>
<details><summary><b><a href="https://github.com/xiaocong/uiautomator">uiautomator</a></b> (🥉24 ·  ⭐ 1.7K · 💤) - Python wrapper of Android uiautomator test tool. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/xiaocong/uiautomator) (👨‍💻 13 · 🔀 590 · 📦 200 · 📋 290 - 59% open · ⏱️ 16.11.2020):

	```
	git clone https://github.com/xiaocong/uiautomator
	```
- [PyPi](https://pypi.org/project/uiautomator) (📥 34K / month · 📦 120 · ⏱️ 16.11.2020):
	```
	pip install uiautomator
	```
</details>
<details><summary><b><a href="https://github.com/CleanCut/green">green</a></b> (🥉24 ·  ⭐ 710) - Green is a clean, colorful, fast python test runner. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/CleanCut/green) (👨‍💻 37 · 🔀 75 · 📦 610 · 📋 170 - 3% open · ⏱️ 16.07.2021):

	```
	git clone https://github.com/CleanCut/green
	```
- [PyPi](https://pypi.org/project/green) (📦 360 · ⏱️ 16.07.2021):
	```
	pip install green
	```
- [Conda](https://anaconda.org/conda-forge/green) (📥 89K · ⏱️ 12.11.2020):
	```
	conda install -c conda-forge green
	```
</details>
<details><summary><b><a href="https://github.com/theacodes/nox">nox</a></b> (🥉24 ·  ⭐ 650) - Flexible test automation for Python. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/theacodes/nox) (👨‍💻 63 · 🔀 99 · 📋 240 - 15% open · ⏱️ 25.10.2021):

	```
	git clone https://github.com/theacodes/nox
	```
- [PyPi](https://pypi.org/project/nox) (📥 630K / month · 📦 56 · ⏱️ 01.10.2021):
	```
	pip install nox
	```
- [Conda](https://anaconda.org/conda-forge/nox) (📥 41K · ⏱️ 02.10.2021):
	```
	conda install -c conda-forge nox
	```
</details>
<details><summary><b><a href="https://github.com/airspeed-velocity/asv">asv</a></b> (🥉24 ·  ⭐ 620) - Airspeed Velocity: A simple Python benchmarking tool with web-based reporting. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/airspeed-velocity/asv) (👨‍💻 55 · 🔀 130 · 📦 200 · 📋 410 - 26% open · ⏱️ 15.08.2021):

	```
	git clone https://github.com/airspeed-velocity/asv
	```
- [PyPi](https://pypi.org/project/asv) (📥 29K / month · 📦 88 · ⏱️ 16.05.2020):
	```
	pip install asv
	```
- [Conda](https://anaconda.org/conda-forge/asv) (📥 540K · ⏱️ 07.08.2021):
	```
	conda install -c conda-forge asv
	```
</details>
<details><summary><b><a href="https://github.com/nestorsalceda/mamba">Mamba Test Runner</a></b> (🥉24 ·  ⭐ 480 · 💤) - The definitive testing tool for Python. Born under the.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/nestorsalceda/mamba) (👨‍💻 22 · 🔀 64 · 📦 370 · 📋 97 - 46% open · ⏱️ 16.11.2020):

	```
	git clone https://github.com/nestorsalceda/mamba
	```
- [PyPi](https://pypi.org/project/mamba) (📥 18K / month · 📦 220 · ⏱️ 16.11.2020):
	```
	pip install mamba
	```
</details>
<details><summary><b><a href="https://github.com/dbader/pytest-mypy">pytest-mypy</a></b> (🥉24 ·  ⭐ 190) - Mypy static type checker plugin for Pytest. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/dbader/pytest-mypy) (👨‍💻 15 · 🔀 32 · 📦 1.3K · 📋 46 - 19% open · ⏱️ 16.06.2021):

	```
	git clone https://github.com/dbader/pytest-mypy
	```
- [PyPi](https://pypi.org/project/pytest-mypy) (📥 430K / month · 📦 270 · ⏱️ 21.03.2021):
	```
	pip install pytest-mypy
	```
- [Conda](https://anaconda.org/conda-forge/pytest-mypy) (📥 16K · ⏱️ 24.11.2020):
	```
	conda install -c conda-forge pytest-mypy
	```
</details>
<details><summary><b><a href="https://github.com/tarpas/pytest-testmon">pytest-testmon</a></b> (🥉23 ·  ⭐ 500) - Selects tests affected by changed files. Continous.. <code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tarpas/pytest-testmon) (👨‍💻 16 · 🔀 29 · 📋 120 - 24% open · ⏱️ 22.10.2021):

	```
	git clone https://github.com/tarpas/pytest-testmon
	```
- [PyPi](https://pypi.org/project/pytest-testmon) (📥 100K / month · 📦 98 · ⏱️ 22.10.2021):
	```
	pip install pytest-testmon
	```
- [Conda](https://anaconda.org/conda-forge/pytest-testmon) (📥 33K · ⏱️ 03.08.2019):
	```
	conda install -c conda-forge pytest-testmon
	```
</details>
<details><summary><b><a href="https://github.com/pytest-dev/pytest-randomly">pytest-randomly</a></b> (🥉23 ·  ⭐ 370) - Pytest plugin to randomly order tests and control random.seed. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pytest-dev/pytest-randomly) (👨‍💻 16 · 🔀 21 · 📋 45 - 11% open · ⏱️ 01.11.2021):

	```
	git clone https://github.com/pytest-dev/pytest-randomly
	```
- [PyPi](https://pypi.org/project/pytest-randomly) (📥 360K / month · 📦 210 · ⏱️ 13.08.2021):
	```
	pip install pytest-randomly
	```
</details>
<details><summary><b><a href="https://github.com/Erotemic/xdoctest">xdoctest</a></b> (🥉22 ·  ⭐ 120) - A rewrite of Python's builtin doctest module (with pytest plugin.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/Erotemic/xdoctest) (👨‍💻 6 · 🔀 6 · 📦 1.6K · 📋 37 - 45% open · ⏱️ 06.10.2021):

	```
	git clone https://github.com/Erotemic/xdoctest
	```
- [PyPi](https://pypi.org/project/xdoctest) (📥 96K / month · 📦 52 · ⏱️ 06.10.2021):
	```
	pip install xdoctest
	```
</details>
<details><summary><b><a href="https://github.com/avast/pytest-docker">pytest-docker</a></b> (🥉21 ·  ⭐ 240) - Docker-based integration tests. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/avast/pytest-docker) (👨‍💻 11 · 🔀 42 · 📥 82 · 📋 33 - 51% open · ⏱️ 14.06.2021):

	```
	git clone https://github.com/avast/pytest-docker
	```
- [PyPi](https://pypi.org/project/pytest-docker) (📥 51K / month · 📦 28 · ⏱️ 14.06.2021):
	```
	pip install pytest-docker
	```
</details>
<details><summary><b><a href="https://github.com/TvoroG/pytest-lazy-fixture">pytest-lazy-fixture</a></b> (🥉21 ·  ⭐ 220) - It helps to use fixtures in pytest.mark.parametrize. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/TvoroG/pytest-lazy-fixture) (👨‍💻 8 · 🔀 15 · 📦 460 · 📋 35 - 42% open · ⏱️ 09.07.2021):

	```
	git clone https://github.com/tvorog/pytest-lazy-fixture
	```
- [PyPi](https://pypi.org/project/pytest-lazy-fixture) (📥 260K / month · 📦 62 · ⏱️ 01.02.2020):
	```
	pip install pytest-lazy-fixture
	```
- [Conda](https://anaconda.org/conda-forge/pytest-lazy-fixture) (📥 290K · ⏱️ 01.02.2020):
	```
	conda install -c conda-forge pytest-lazy-fixture
	```
</details>
<details><summary><b><a href="https://github.com/man-group/pytest-plugins">pytest-plugins</a></b> (🥉14 ·  ⭐ 390) - A grab-bag of nifty pytest plugins. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/man-group/pytest-plugins) (👨‍💻 48 · 🔀 59 · 📋 98 - 45% open · ⏱️ 06.10.2021):

	```
	git clone https://github.com/man-group/pytest-plugins
	```
</details>
<details><summary>Show 8 hidden projects...</summary>

- <b><a href="https://github.com/nose-devs/nose">nose</a></b> (🥇32 ·  ⭐ 1.3K · 💀) - nose is nicer testing for python. <code><a href="https://tldrlegal.com/search?q=LGPL-2.1%2B">❗️LGPL-2.1+</a></code>
- <b><a href="https://github.com/Teemu/pytest-sugar">pytest-sugar</a></b> (🥉27 ·  ⭐ 740 · 💀) - a plugin for py.test that changes the default look and.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/joeyespo/pytest-watch">pytest-watch</a></b> (🥉25 ·  ⭐ 600 · 💀) - Local continuous test runner with pytest and watchdog. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/sixpack/sixpack">sixpack</a></b> (🥉21 ·  ⭐ 1.7K · 💀) - Sixpack is a language-agnostic a/b-testing framework. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code>
- <b><a href="https://github.com/ActivisionGameScience/assertpy">assertpy</a></b> (🥉21 ·  ⭐ 250 · 💀) - Simple assertion library for unit testing in python with a fluent.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/gabrielcnr/pytest-datadir">pytest-datadir</a></b> (🥉20 ·  ⭐ 150 · 💀) - pytest plugin for manipulating test data directories and.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/emirozer/fake2db">fake2db</a></b> (🥉18 ·  ⭐ 2.1K · 💀) - create custom test databases that are populated with fake data. <code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code>
- <b><a href="https://github.com/pytest-dev/pytest-play">pytest-play</a></b> (🥉16 ·  ⭐ 64 · 💀) - pytest plugin that let you automate actions and.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://docs.pytest.org/en/stable/_static/favicon.png" style="display:inline;" width="13" height="13"></code>
</details>
<br>

## Code Packaging

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

🔗&nbsp;<b><a href="https://packaging.python.org/overview/">Python.org Packaging</a></b>  - An Overview of Packaging for Python.

<details><summary><b><a href="https://github.com/pypa/packaging">packaging</a></b> (🥇31 ·  ⭐ 340) - Core utilities for Python packages. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/pypa/packaging) (👨‍💻 72 · 🔀 170 · 📥 170 · 📦 270K · 📋 230 - 28% open · ⏱️ 02.11.2021):

	```
	git clone https://github.com/pypa/packaging
	```
- [PyPi](https://pypi.org/project/packaging) (📥 80M / month · 📦 29K · ⏱️ 29.10.2021):
	```
	pip install packaging
	```
- [Conda](https://anaconda.org/conda-forge/packaging) (📥 10M · ⏱️ 29.10.2021):
	```
	conda install -c conda-forge packaging
	```
</details>
<details><summary><b><a href="https://github.com/Nuitka/Nuitka">Nuitka</a></b> (🥇28 ·  ⭐ 6K) - Nuitka is a Python compiler written in Python. It's fully compatible.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/Nuitka/Nuitka) (👨‍💻 100 · 🔀 340 · 📋 1.1K - 21% open · ⏱️ 01.11.2021):

	```
	git clone https://github.com/Nuitka/Nuitka
	```
- [PyPi](https://pypi.org/project/nuitka) (📥 26K / month · 📦 54 · ⏱️ 29.10.2021):
	```
	pip install nuitka
	```
- [Conda](https://anaconda.org/conda-forge/nuitka) (📥 320K · ⏱️ 25.10.2021):
	```
	conda install -c conda-forge nuitka
	```
</details>
<details><summary><b><a href="https://github.com/pyinstaller/pyinstaller">pyinstaller</a></b> (🥈27 ·  ⭐ 8.6K) - Freeze (package) Python programs into stand-alone executables. <code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code></summary>

- [GitHub](https://github.com/pyinstaller/pyinstaller) (👨‍💻 420 · 🔀 1.7K · 📥 720K · 📋 4.3K - 7% open · ⏱️ 04.11.2021):

	```
	git clone https://github.com/pyinstaller/pyinstaller
	```
- [PyPi](https://pypi.org/project/pyinstaller) (📥 600K / month · ⏱️ 29.10.2021):
	```
	pip install pyinstaller
	```
- [Conda](https://anaconda.org/conda-forge/pyinstaller) (📥 270K · ⏱️ 30.10.2021):
	```
	conda install -c conda-forge pyinstaller
	```
</details>
<details><summary><b><a href="https://github.com/pantsbuild/pex">pex</a></b> (🥈26 ·  ⭐ 2K) - A library and tool for generating .pex (Python EXecutable) files. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/pantsbuild/pex) (👨‍💻 100 · 🔀 210 · 📥 460K · 📋 750 - 19% open · ⏱️ 03.11.2021):

	```
	git clone https://github.com/pantsbuild/pex
	```
- [PyPi](https://pypi.org/project/pex) (📥 170K / month · 📦 230 · ⏱️ 01.11.2021):
	```
	pip install pex
	```
</details>
<details><summary><b><a href="https://github.com/beeware/briefcase">briefcase</a></b> (🥈24 ·  ⭐ 1.2K) - Tools to support converting a Python project into a standalone.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/beeware/briefcase) (👨‍💻 86 · 🔀 200 · 📋 360 - 27% open · ⏱️ 26.09.2021):

	```
	git clone https://github.com/beeware/briefcase
	```
- [PyPi](https://pypi.org/project/briefcase) (📥 2.9K / month · 📦 24 · ⏱️ 06.03.2021):
	```
	pip install briefcase
	```
</details>
<details><summary><b><a href="https://github.com/marcelotduarte/cx_Freeze">cx_Freeze</a></b> (🥈22 ·  ⭐ 810) - Create standalone executables from Python scripts, with the same.. <code><a href="http://bit.ly/35wkF7y">Python-2.0</a></code></summary>

- [GitHub](https://github.com/marcelotduarte/cx_Freeze) (👨‍💻 91 · 🔀 160 · 📋 700 - 8% open · ⏱️ 20.10.2021):

	```
	git clone https://github.com/marcelotduarte/cx_Freeze
	```
- [PyPi](https://pypi.org/project/cx_freeze) (📦 150 · ⏱️ 16.12.2017):
	```
	pip install cx_freeze
	```
- [Conda](https://anaconda.org/conda-forge/cx_freeze) (📥 98K · ⏱️ 01.10.2021):
	```
	conda install -c conda-forge cx_freeze
	```
</details>
<details><summary><b><a href="https://github.com/takluyver/pynsist">pynsist</a></b> (🥈22 ·  ⭐ 730) - Build Windows installers for Python applications. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/takluyver/pynsist) (👨‍💻 28 · 🔀 100 · 📋 160 - 15% open · ⏱️ 10.10.2021):

	```
	git clone https://github.com/takluyver/pynsist
	```
- [PyPi](https://pypi.org/project/pynsist) (📥 1.8K / month · 📦 88 · ⏱️ 28.03.2021):
	```
	pip install pynsist
	```
</details>
<details><summary><b><a href="https://github.com/py2exe/py2exe">py2exe</a></b> (🥈22 ·  ⭐ 310) - A distutils extension to create standalone Windows programs from Python code. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/py2exe/py2exe) (👨‍💻 14 · 🔀 42 · 📥 11K · 📦 1.3K · 📋 87 - 4% open · ⏱️ 07.09.2021):

	```
	git clone https://github.com/py2exe/py2exe
	```
- [PyPi](https://pypi.org/project/py2exe) (📦 350 · ⏱️ 07.09.2021):
	```
	pip install py2exe
	```
</details>
<details><summary><b><a href="https://github.com/ronaldoussoren/py2app">py2app</a></b> (🥈22 ·  ⭐ 160) - py2app is a Python setuptools command which will allow you to make.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ronaldoussoren/py2app) (👨‍💻 26 · 🔀 16 · 📦 3.8K · 📋 370 - 27% open · ⏱️ 05.10.2021):

	```
	git clone https://github.com/ronaldoussoren/py2app
	```
- [PyPi](https://pypi.org/project/py2app) (📦 1.6K · ⏱️ 27.09.2021):
	```
	pip install py2app
	```
</details>
<details><summary><b><a href="https://github.com/conda/constructor">constructor</a></b> (🥉19 ·  ⭐ 330) - tool for creating installers from conda packages. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/conda/constructor) (👨‍💻 47 · 🔀 130 · 📥 220 · 📦 10 · 📋 250 - 22% open · ⏱️ 26.08.2021):

	```
	git clone https://github.com/conda/constructor
	```
- [Conda](https://anaconda.org/anaconda/constructor) (📥 4.7K · ⏱️ 01.04.2021):
	```
	conda install -c anaconda constructor
	```
</details>
<details><summary><b><a href="https://github.com/facebookincubator/xar">xar</a></b> (🥉17 ·  ⭐ 1.5K) - executable archive format. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/facebookincubator/xar) (👨‍💻 28 · 🔀 45 · 📦 15 · 📋 29 - 27% open · ⏱️ 22.10.2021):

	```
	git clone https://github.com/facebookincubator/xar
	```
- [PyPi](https://pypi.org/project/xar) (⏱️ 02.12.2020):
	```
	pip install xar
	```
</details>
<details><summary><b><a href="https://github.com/linkedin/shiv">shiv</a></b> (🥉17 ·  ⭐ 1.3K) - shiv is a command line utility for building fully self contained Python.. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/linkedin/shiv) (👨‍💻 34 · 🔀 70 · 📥 150 · 📋 90 - 30% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/linkedin/shiv
	```
- [PyPi](https://pypi.org/project/shiv) (📦 10 · ⏱️ 30.04.2021):
	```
	pip install shiv
	```
</details>
<details><summary><b><a href="https://github.com/indygreg/PyOxidizer">PyOxidizer</a></b> (🥉16 ·  ⭐ 3.2K) - A modern Python application packaging and distribution tool. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code></summary>

- [GitHub](https://github.com/indygreg/PyOxidizer) (👨‍💻 37 · 🔀 130 · 📥 1.1K · 📋 400 - 60% open · ⏱️ 29.10.2021):

	```
	git clone https://github.com/indygreg/PyOxidizer
	```
</details>
<details><summary>Show 2 hidden projects...</summary>

- <b><a href="https://github.com/google/subpar">subpar</a></b> (🥉14 ·  ⭐ 500 · 💀) - Subpar is a utility for creating self-contained python.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/jamesabel/pyship">pyship</a></b> (🥉10 ·  ⭐ 15) - pyship - ship Python desktop apps to end users. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>
<br>

## Build Tools

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/pypa/setuptools">setuptools</a></b> (🥇34 ·  ⭐ 1.5K) - Official project repository for the Setuptools build system. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pypa/setuptools) (👨‍💻 470 · 🔀 780 · 📥 110 · 📦 120K · 📋 1.8K - 28% open · ⏱️ 03.11.2021):

	```
	git clone https://github.com/pypa/setuptools
	```
- [PyPi](https://pypi.org/project/setuptools) (📥 140M / month · 📦 58K · ⏱️ 04.11.2021):
	```
	pip install setuptools
	```
- [Conda](https://anaconda.org/conda-forge/setuptools) (📥 28M · ⏱️ 04.11.2021):
	```
	conda install -c conda-forge setuptools
	```
</details>
<details><summary><b><a href="https://github.com/pyinvoke/invoke">invoke</a></b> (🥇32 ·  ⭐ 3.4K) - Pythonic task management & command execution. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/pyinvoke/invoke) (👨‍💻 56 · 🔀 300 · 📦 9.2K · 📋 690 - 48% open · ⏱️ 16.10.2021):

	```
	git clone https://github.com/pyinvoke/invoke
	```
- [PyPi](https://pypi.org/project/invoke) (📥 2M / month · 📦 4.6K · ⏱️ 09.07.2021):
	```
	pip install invoke
	```
- [Conda](https://anaconda.org/conda-forge/invoke) (📥 460K · ⏱️ 10.07.2021):
	```
	conda install -c conda-forge invoke
	```
</details>
<details><summary><b><a href="https://github.com/buildbot/buildbot">buildbot</a></b> (🥈31 ·  ⭐ 4.7K) - Python-based continuous integration testing framework; your pull.. <code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code></summary>

- [GitHub](https://github.com/buildbot/buildbot) (👨‍💻 800 · 🔀 1.6K · 📥 18K · 📦 260 · 📋 1.4K - 45% open · ⏱️ 02.11.2021):

	```
	git clone https://github.com/buildbot/buildbot
	```
- [PyPi](https://pypi.org/project/buildbot) (📥 56K / month · 📦 890 · ⏱️ 16.10.2021):
	```
	pip install buildbot
	```
- [Conda](https://anaconda.org/conda-forge/buildbot) (📥 45K · ⏱️ 16.10.2021):
	```
	conda install -c conda-forge buildbot
	```
</details>
<details><summary><b><a href="https://github.com/pypa/twine">twine</a></b> (🥈30 ·  ⭐ 1.2K) - Utilities for interacting with PyPI. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/pypa/twine) (👨‍💻 100 · 🔀 250 · 📦 48K · 📋 380 - 10% open · ⏱️ 03.11.2021):

	```
	git clone https://github.com/pypa/twine
	```
- [PyPi](https://pypi.org/project/twine) (📥 2.3M / month · 📦 18K · ⏱️ 03.11.2021):
	```
	pip install twine
	```
- [Conda](https://anaconda.org/conda-forge/twine) (📥 360K · ⏱️ 03.11.2021):
	```
	conda install -c conda-forge twine
	```
</details>
<details><summary><b><a href="https://github.com/pypa/wheel">wheel</a></b> (🥈30 ·  ⭐ 270) - The official binary distribution format for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pypa/wheel) (👨‍💻 62 · 🔀 99 · 📋 330 - 9% open · ⏱️ 07.10.2021):

	```
	git clone https://github.com/pypa/wheel
	```
- [PyPi](https://pypi.org/project/wheel) (📥 100M / month · 📦 63K · ⏱️ 09.08.2021):
	```
	pip install wheel
	```
- [Conda](https://anaconda.org/conda-forge/wheel) (📥 23M · ⏱️ 13.08.2021):
	```
	conda install -c conda-forge wheel
	```
</details>
<details><summary><b><a href="https://github.com/SCons/scons">scons</a></b> (🥈28 ·  ⭐ 1.3K) - SCons - a software construction tool. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/SCons/scons) (👨‍💻 140 · 🔀 240 · 📥 380 · 📋 3.3K - 19% open · ⏱️ 01.11.2021):

	```
	git clone https://github.com/SCons/scons
	```
- [PyPi](https://pypi.org/project/scons) (📥 200K / month · 📦 50 · ⏱️ 17.12.2019):
	```
	pip install scons
	```
- [Conda](https://anaconda.org/conda-forge/scons) (📥 240K · ⏱️ 01.08.2021):
	```
	conda install -c conda-forge scons
	```
</details>
<details><summary><b><a href="https://github.com/pydoit/doit">doit</a></b> (🥈28 ·  ⭐ 1.1K) - task management & automation tool. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pydoit/doit) (👨‍💻 56 · 🔀 140 · 📦 810 · 📋 260 - 25% open · ⏱️ 06.07.2021):

	```
	git clone https://github.com/pydoit/doit
	```
- [PyPi](https://pypi.org/project/doit) (📥 230K / month · 📦 470 · ⏱️ 04.09.2020):
	```
	pip install doit
	```
- [Conda](https://anaconda.org/conda-forge/doit) (📥 68K · ⏱️ 11.10.2020):
	```
	conda install -c conda-forge doit
	```
</details>
<details><summary><b><a href="https://github.com/takluyver/flit">flit</a></b> (🥉27 ·  ⭐ 1.5K) - Simplified packaging of Python modules. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/takluyver/flit) (👨‍💻 47 · 🔀 82 · 📋 280 - 34% open · ⏱️ 02.11.2021):

	```
	git clone https://github.com/takluyver/flit
	```
- [PyPi](https://pypi.org/project/flit) (📥 290K / month · 📦 230 · ⏱️ 10.10.2021):
	```
	pip install flit
	```
- [Conda](https://anaconda.org/conda-forge/flit) (📥 97K · ⏱️ 12.10.2021):
	```
	conda install -c conda-forge flit
	```
</details>
<details><summary><b><a href="https://github.com/paver/paver">paver</a></b> (🥉24 ·  ⭐ 440) - Python-based project scripting. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/paver/paver) (👨‍💻 45 · 🔀 78 · 📋 130 - 28% open · ⏱️ 21.06.2021):

	```
	git clone https://github.com/paver/paver
	```
- [PyPi](https://pypi.org/project/paver) (📥 35K / month · 📦 1.9K · ⏱️ 31.12.2017):
	```
	pip install paver
	```
- [Conda](https://anaconda.org/conda-forge/paver) (📥 23K · ⏱️ 24.07.2018):
	```
	conda install -c conda-forge paver
	```
</details>
<details><summary><b><a href="https://github.com/pybuilder/pybuilder">pybuilder</a></b> (🥉23 ·  ⭐ 1.3K) - Software build automation tool for Python. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/pybuilder/pybuilder) (👨‍💻 36 · 🔀 240 · 📋 500 - 17% open · ⏱️ 24.10.2021):

	```
	git clone https://github.com/pybuilder/pybuilder
	```
- [PyPi](https://pypi.org/project/pybuilder) (📦 110 · ⏱️ 24.10.2021):
	```
	pip install pybuilder
	```
</details>
<details><summary><b><a href="https://github.com/pypa/setuptools_scm">setuptools_scm</a></b> (🥉23 ·  ⭐ 510) - the blessed package to manage your versions by scm tags. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pypa/setuptools_scm) (👨‍💻 92 · 🔀 150 · 📋 370 - 22% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/pypa/setuptools_scm
	```
- [PyPi](https://pypi.org/project/setuptools_scm) (📦 690 · ⏱️ 09.08.2018):
	```
	pip install setuptools_scm
	```
- [Conda](https://anaconda.org/conda-forge/setuptools_scm) (📥 790K · ⏱️ 11.09.2021):
	```
	conda install -c conda-forge setuptools_scm
	```
</details>
<details><summary><b><a href="https://github.com/ml-tooling/universal-build">universal-build</a></b> (🥉13 ·  ⭐ 13) - Universal build utilities for containerized build pipelines. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ml-tooling/universal-build) (👨‍💻 4 · 🔀 5 · 📥 16 · 📦 6 · ⏱️ 25.08.2021):

	```
	git clone https://github.com/ml-tooling/universal-build
	```
- [PyPi](https://pypi.org/project/universal-build) (📥 290 / month · ⏱️ 12.12.2020):
	```
	pip install universal-build
	```
</details>
<details><summary>Show 2 hidden projects...</summary>

- <b><a href="https://github.com/buildout/buildout">buildout</a></b> (🥉27 ·  ⭐ 520) - Buildout is a deployment automation tool written in and extended.. <code><a href="https://tldrlegal.com/search?q=ZPL-2.1">❗️ZPL-2.1</a></code>
- <b><a href="https://github.com/rags/pynt">pynt</a></b> (🥉18 ·  ⭐ 150 · 💀) - A pynt of Python build. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>
<br>

## System Monitoring & Profiling

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/giampaolo/psutil">psutil</a></b> (🥇37 ·  ⭐ 7.8K) - Cross-platform lib for process and system monitoring in Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/giampaolo/psutil) (👨‍💻 170 · 🔀 1.1K · 📦 120K · 📋 1.5K - 13% open · ⏱️ 04.11.2021):

	```
	git clone https://github.com/giampaolo/psutil
	```
- [PyPi](https://pypi.org/project/psutil) (📥 40M / month · 📦 25K · ⏱️ 19.12.2020):
	```
	pip install psutil
	```
- [Conda](https://anaconda.org/conda-forge/psutil) (📥 8.7M · ⏱️ 02.11.2021):
	```
	conda install -c conda-forge psutil
	```
</details>
<details><summary><b><a href="https://github.com/nicolargo/glances">Glances</a></b> (🥇30 ·  ⭐ 19K) - Glances an Eye on your system. A top/htop alternative for.. <code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code></summary>

- [GitHub](https://github.com/nicolargo/glances) (👨‍💻 150 · 🔀 1.2K · 📥 660 · 📦 340 · 📋 1.4K - 14% open · ⏱️ 04.11.2021):

	```
	git clone https://github.com/nicolargo/glances
	```
- [PyPi](https://pypi.org/project/glances) (📥 120K / month · 📦 50 · ⏱️ 21.08.2021):
	```
	pip install glances
	```
- [Conda](https://anaconda.org/conda-forge/glances) (📥 150K · ⏱️ 13.09.2021):
	```
	conda install -c conda-forge glances
	```
</details>
<details><summary><b><a href="https://github.com/pyutils/line_profiler">line_profiler</a></b> (🥈26 ·  ⭐ 3.5K) - Line-by-line profiling for Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/pyutils/line_profiler) (👨‍💻 27 · 🔀 250 · 📋 48 - 58% open · ⏱️ 27.09.2021):

	```
	git clone https://github.com/pyutils/line_profiler
	```
- [PyPi](https://pypi.org/project/line_profiler) (📥 130K / month · 📦 690 · ⏱️ 20.12.2017):
	```
	pip install line_profiler
	```
- [Conda](https://anaconda.org/conda-forge/line_profiler) (📥 210K · ⏱️ 29.09.2021):
	```
	conda install -c conda-forge line_profiler
	```
</details>
<details><summary><b><a href="https://github.com/sumerc/yappi">Yappi</a></b> (🥈25 ·  ⭐ 740) - Yet Another Python Profiler, but this time thread&coroutine&greenlet aware. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/sumerc/yappi) (👨‍💻 26 · 🔀 50 · 📦 490 · 📋 51 - 31% open · ⏱️ 05.10.2021):

	```
	git clone https://github.com/sumerc/yappi
	```
- [PyPi](https://pypi.org/project/yappi) (📦 640 · ⏱️ 05.10.2021):
	```
	pip install yappi
	```
- [Conda](https://anaconda.org/conda-forge/yappi) (📥 92K · ⏱️ 05.10.2021):
	```
	conda install -c conda-forge yappi
	```
</details>
<details><summary><b><a href="https://github.com/benfred/py-spy">py-spy</a></b> (🥈24 ·  ⭐ 7.5K) - Sampling profiler for Python programs. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/benfred/py-spy) (👨‍💻 29 · 🔀 270 · 📥 6.9K · 📋 230 - 30% open · ⏱️ 21.10.2021):

	```
	git clone https://github.com/benfred/py-spy
	```
- [PyPi](https://pypi.org/project/py-spy) (📦 50 · ⏱️ 27.09.2021):
	```
	pip install py-spy
	```
</details>
<details><summary><b><a href="https://github.com/aristocratos/bpytop">Bpytop</a></b> (🥈23 ·  ⭐ 7.7K) - Linux/OSX/FreeBSD resource monitor. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/aristocratos/bpytop) (👨‍💻 30 · 🔀 300 · 📋 260 - 18% open · ⏱️ 18.09.2021):

	```
	git clone https://github.com/aristocratos/bpytop
	```
- [PyPi](https://pypi.org/project/bpytop) (📥 10K / month · ⏱️ 07.06.2021):
	```
	pip install bpytop
	```
</details>
<details><summary><b><a href="https://github.com/plasma-umass/scalene">Scalene</a></b> (🥈23 ·  ⭐ 4.7K) - Scalene: a high-performance, high-precision CPU, GPU, and memory.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/plasma-umass/scalene) (👨‍💻 23 · 🔀 160 · 📦 72 · 📋 150 - 24% open · ⏱️ 28.10.2021):

	```
	git clone https://github.com/plasma-umass/scalene
	```
- [PyPi](https://pypi.org/project/scalene) (⏱️ 21.10.2021):
	```
	pip install scalene
	```
</details>
<details><summary><b><a href="https://github.com/joerick/pyinstrument">pyinstrument</a></b> (🥈23 ·  ⭐ 3.5K) - Call stack profiler for Python. Shows you why your code is slow!. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/joerick/pyinstrument) (👨‍💻 34 · 🔀 150 · 📦 400 · 📋 88 - 17% open · ⏱️ 04.11.2021):

	```
	git clone https://github.com/joerick/pyinstrument
	```
- [PyPi](https://pypi.org/project/pyinstrument) (📦 140 · ⏱️ 03.10.2021):
	```
	pip install pyinstrument
	```
- [Conda](https://anaconda.org/conda-forge/pyinstrument) (📥 87K · ⏱️ 05.10.2021):
	```
	conda install -c conda-forge pyinstrument
	```
</details>
<details><summary><b><a href="https://github.com/pympler/pympler">pympler</a></b> (🥈23 ·  ⭐ 820) - Development tool to measure, monitor and analyze the memory behavior.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/pympler/pympler) (👨‍💻 29 · 🔀 68 · 📋 83 - 42% open · ⏱️ 23.10.2021):

	```
	git clone https://github.com/pympler/pympler
	```
- [PyPi](https://pypi.org/project/pympler) (📦 480 · ⏱️ 14.10.2020):
	```
	pip install pympler
	```
- [Conda](https://anaconda.org/conda-forge/pympler) (📥 170K · ⏱️ 14.10.2020):
	```
	conda install -c conda-forge pympler
	```
</details>
<details><summary><b><a href="https://github.com/pythonprofilers/memory_profiler">memory-profiler</a></b> (🥉22 ·  ⭐ 3.1K · 📉) - Monitor Memory usage of Python code. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/pythonprofilers/memory_profiler) (👨‍💻 89 · 🔀 320 · 📋 200 - 51% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/pythonprofilers/memory_profiler
	```
- [PyPi](https://pypi.org/project/memory_profiler) (📦 530 · ⏱️ 16.08.2018):
	```
	pip install memory_profiler
	```
</details>
<details><summary><b><a href="https://github.com/nvdv/vprof">vprof</a></b> (🥉19 ·  ⭐ 3.8K · 💤) - Visual profiler for Python. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/nvdv/vprof) (👨‍💻 17 · 🔀 170 · 📦 84 · 📋 81 - 30% open · ⏱️ 20.02.2021):

	```
	git clone https://github.com/nvdv/vprof
	```
- [PyPi](https://pypi.org/project/vprof) (📦 18 · ⏱️ 29.02.2020):
	```
	pip install vprof
	```
</details>
<details><summary><b><a href="https://github.com/csurfer/pyheat">pyheat</a></b> (🥉19 ·  ⭐ 580) - pprofile + matplotlib = Python program profiled as an awesome heatmap!. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/csurfer/pyheat) (👨‍💻 5 · 🔀 32 · 📦 32 · 📋 12 - 25% open · ⏱️ 18.09.2021):

	```
	git clone https://github.com/csurfer/pyheat
	```
- [PyPi](https://pypi.org/project/py-heat) (📥 2.8K / month · 📦 10 · ⏱️ 06.12.2018):
	```
	pip install py-heat
	```
</details>
<details><summary><b><a href="https://github.com/alexmojaki/heartrate">heartrate</a></b> (🥉15 ·  ⭐ 1.3K) - Simple real time visualisation of the execution of a Python program. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/alexmojaki/heartrate) (👨‍💻 2 · 🔀 110 · 📦 26 · 📋 6 - 66% open · ⏱️ 06.07.2021):

	```
	git clone https://github.com/alexmojaki/heartrate
	```
- [PyPi](https://pypi.org/project/heartrate) (⏱️ 14.08.2019):
	```
	pip install heartrate
	```
</details>
<details><summary>Show 4 hidden projects...</summary>

- <b><a href="https://github.com/python-diamond/Diamond">Diamond</a></b> (🥈26 ·  ⭐ 1.6K · 💀) - Diamond is a python daemon that collects system metrics and publishes.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/what-studio/profiling">Profiling</a></b> (🥉21 ·  ⭐ 3K · 💀) - Was an interactive continuous Python profiler. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/fabianp/memory_profiler">memory_profiler</a></b> (🥉20 ·  ⭐ 66 · 💀) - Monitor Memory usage of Python code. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/agermanidis/livepython">livepython</a></b> (🥉12 ·  ⭐ 2.5K · 💀) - Visually trace Python code in real-time. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>
<br>

## AST Tools

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/python/typed_ast">typed_ast</a></b> (🥇29 ·  ⭐ 190) - Modified fork of CPython's ast module that parses `# type:`.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/python/typed_ast) (👨‍💻 22 · 🔀 48 · 📋 82 - 6% open · ⏱️ 26.10.2021):

	```
	git clone https://github.com/python/typed_ast
	```
- [PyPi](https://pypi.org/project/typed_ast) (📥 12M / month · 📦 10K · ⏱️ 11.04.2021):
	```
	pip install typed_ast
	```
</details>
<details><summary><b><a href="https://github.com/berkerpeksag/astor">astor</a></b> (🥈28 ·  ⭐ 610) - Python AST read/write. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/berkerpeksag/astor) (👨‍💻 31 · 🔀 84 · 📋 110 - 31% open · ⏱️ 27.10.2021):

	```
	git clone https://github.com/berkerpeksag/astor
	```
- [PyPi](https://pypi.org/project/astor) (📥 4.4M / month · 📦 3.8K · ⏱️ 10.12.2019):
	```
	pip install astor
	```
- [Conda](https://anaconda.org/conda-forge/astor) (📥 1.4M · ⏱️ 01.07.2020):
	```
	conda install -c conda-forge astor
	```
</details>
<details><summary><b><a href="https://github.com/serge-sans-paille/gast">gast</a></b> (🥈28 ·  ⭐ 120) - Python AST that abstracts the underlying Python version. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/serge-sans-paille/gast) (👨‍💻 10 · 🔀 24 · 📦 69K · ⏱️ 19.10.2021):

	```
	git clone https://github.com/serge-sans-paille/gast
	```
- [PyPi](https://pypi.org/project/gast) (📥 9.7M / month · 📦 3.4K · ⏱️ 02.08.2021):
	```
	pip install gast
	```
- [Conda](https://anaconda.org/conda-forge/gast) (📥 1.3M · ⏱️ 29.06.2021):
	```
	conda install -c conda-forge gast
	```
</details>
<details><summary><b><a href="https://github.com/newville/asteval">asteval</a></b> (🥉25 ·  ⭐ 120) - minimalistic evaluator of python expression using ast module. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/newville/asteval) (👨‍💻 19 · 🔀 32 · 📦 660 · 📋 52 - 11% open · ⏱️ 25.09.2021):

	```
	git clone https://github.com/newville/asteval
	```
- [PyPi](https://pypi.org/project/asteval) (📥 170K / month · 📦 240 · ⏱️ 22.06.2021):
	```
	pip install asteval
	```
- [Conda](https://anaconda.org/conda-forge/asteval) (📥 150K · ⏱️ 27.02.2021):
	```
	conda install -c conda-forge asteval
	```
</details>
<details><summary>Show 1 hidden projects...</summary>

- <b><a href="https://github.com/simonpercivall/astunparse">astunparse</a></b> (🥉27 ·  ⭐ 170 · 💀) - An AST unparser for Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
</details>
<br>

## Others

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/pre-commit/pre-commit">pre-commit</a></b> (🥇32 ·  ⭐ 6.8K) - A framework for managing and maintaining multi-language pre-commit.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pre-commit/pre-commit) (👨‍💻 130 · 🔀 500 · 📥 17K · 📋 1.3K - 1% open · ⏱️ 01.11.2021):

	```
	git clone https://github.com/pre-commit/pre-commit
	```
- [PyPi](https://pypi.org/project/pre-commit) (📥 3.9M / month · 📦 2.1K · ⏱️ 03.09.2021):
	```
	pip install pre-commit
	```
- [Conda](https://anaconda.org/conda-forge/pre-commit) (📥 800K · ⏱️ 03.09.2021):
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
