# DepView

Analyze calling dependencies in Java projects, and visualize them in a dependency graph.

You can use it to:

+ Get to know the structure of new projects, especially those with little documentation
+ Adjust package structure according to connections between classes

Related article: [Depview: Java 程序调用依赖关系的分析与显示](http://nettee.github.io/posts/2018/Depview-View-invocation-relationships-in-Java-projects/)

![Dependency graph](img/depgraph.png)

## Quickstart

Write a configuration file for the project that you want to analyze. Follow the examples in `conf-example/` directory.

Build and run DepView:

```Shell
bin/depview.py <CONF_FILE>
```

Now the dependencies is in directory `output/<PROJECT_NAME>/`. You can view the dependency graph by running:

```Shell
bin/serve output/<PROJECT_NAME>
```

Open [localhost:8000](localhost:8000) to view the dependency graph.
