# sphinx-document-repository

## 要件

* Python 3.9+
* Poetry 1.1+

## 利用方法

```bash
# sphinx-document-repository をテンプレートにリポジトリを作る。
gh repo create -p https://github.com/kumarstack55/sphinx-document-repository.git sphinx_your_awesome_doc
cd ./sphinx_your_awesome_doc
poetry install
```

## ドキュメントをビルドする方法

```bash
cd ./sphinx_your_awesome_doc
poetry run make.bat html
```