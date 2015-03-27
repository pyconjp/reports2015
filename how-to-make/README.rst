===========================
 How to Make PyCon JP 2015
===========================

はじめに
========
このフォルダはgihyo.jpでの連載記事「PyCon JP 2015の作り方」の原稿を置く場所です。

Sphinx の環境構築手順
=====================

::

  $ hg clone ssh://hg@bitbucket.org/pyconjp/reports2015
  $ cd reports2015/how-to-make/
  $ virtualenv .venv
  $ . .venv/bin/activate
  (.venv)$ pip install sphinx
  (.venv)$ make html
  
