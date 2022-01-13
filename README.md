# Python Project Template

The purpose of this project is to maintain my personal **`Python` project templates** that I commonly use, it's recommended that you use [vscode](https://code.visualstudio.com/) to develop your projects.

The main functions are as follows:

- Automatically creates and manages a virtualenv for your projects by [pipenv](https://github.com/pypa/pipenv)
- Python code formatter [black](https://github.com/psf/black)
- Sort your python project imports by [isort](https://github.com/PyCQA/isort)
- Static code analysis by [pylint](https://github.com/PyCQA/pylint)

Execute the following command in the terminal to get started quickly:

```shell
# Assuming you are already using conda to manage your python environment
conda create -n python38 python=3.8
# Clone repository
git clone https://github.com/howie6879/py_project_template

# Install python env for this project
cd py_project_template
pipenv install --python ~/anaconda3/envs/python38/bin/python3.8 --skip-lock --dev
# Remove .git
rm -Rf .git
# Start write your code
```

BTW, For my insights on python project development management you can read this article: [浅谈Python项目开发&管理](https://www.howie6879.cn/post/2021/14_about_python_env/).