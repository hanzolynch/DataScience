They require at least Python 3.6.

(If you're looking for the code and examples from the first edition, that's in the `first-edition` folder.)

If you want to use the code, you should be able to clone the repo and just do things like

```
In [1]: from scratch.linear_algebra import dot

In [2]: dot([1, 2, 3], [4, 5, 6])
Out[2]: 32
```

and so on and so forth.

Two notes:

1. In order to use the library like this, you need to be in the root directory (that is, the directory that contains the `scratch` folder). If you are in the `scratch` directory itself, the imports won't work.

2. It's possible that it will just work. It's also possible that you may need to add the root directory to your `PYTHONPATH`, if you are on Linux or OSX this is as simple as 

```
export PYTHONPATH=/path/to/where/you/cloned/this/repo
```

(substituting in the real path, of course).

If you are on Windows, it's [potentially more complicated](https://stackoverflow.com/questions/3701646/how-to-add-to-the-pythonpath-in-windows-so-it-finds-my-modules-packages).

