Sphinx Typlog Theme
===================

forked from `typlog/sphinx-typlog-theme`_, A sphinx theme sponsored by Typlog_, created by `Hsiaoming Yang`_.

modifications:

   github icon & block distance & add docstatus in sidebar & add sidebar of rst syntax support & add last_updated time option in footer

| In the original theme, there are no empty lines between blocks, and if subtitle ends with list or admonitions, there is 2 empty lines between next subtitle, if not, there is 1 empty line.
| This theme uniform all to 1 empty line.

| If want comments, in your project templates folder(should be source/_templates(or .templates)) add codes like: `ocg-rule/footer.html <https://github.com/lucays/ocg-rule/blob/master/source/.templates/footer.html>`__.(powered by livere)
| Sure you need change the data-uid to yours.

.. _typlog/sphinx-typlog-theme: https://github.com/typlog/sphinx-typlog-theme
.. _Typlog: https://typlog.com/
.. _`Hsiaoming Yang`: https://lepture.com/

Examples
--------

This theme options example: `ocg-rule/conf.py <https://github.com/lucays/ocg-rule/blob/master/source/conf.py>`__.

- original theme document: https://sphinx-typlog-theme.readthedocs.io
- use this theme: https://ocg-rule.readthedocs.io
