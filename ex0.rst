{% import "macros/ork.jinja" as ork with context %}
习题 0: 准备工作
=====================

本章节是学习前的预备工作，主要是如何设置计算机。如果要在其中包含代码，方法是这样的：

{{ ork.code('code/ex0.py|pyg') }}

代码运行后的输出是这样显示的::

    {{ d['code/ex0.py|py']|indent(4) }}

如果要包含基本文本，那就是这样子::

    {{ d['code/ex0.txt']|indent(4) }}

直接包含的代码是这样实现的：

::

    make ex0
    make ex0
    ./ex0


