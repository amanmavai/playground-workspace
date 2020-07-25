# Webpack

- static module bundler.
- it internally builds a dependency graph which maps every module your project needs and generates one or more bundles.

## Core Concepts:

### Entry 
 - indicates which module webpack should use to begin building out its internal dependency graph.
 -  webpack will figure out which other modules and libraries that entry point depends on (directly and indirectly).

### Output
 - The output property tells webpack where to emit the bundles it creates and how to name these files.

### Loaders
 - Out of the box, webpack only understands JavaScript and JSON files.
 -  Loaders allow webpack to process other types of files and convert them into valid modules that can be consumed by your application and added to the dependency graph.
 -  Note that the ability to import any type of module, e.g. .css files, is a feature specific to webpack

 - At a high level, loaders have two properties in your webpack configuration:

   1. The **test** property identifies which file or files should be transformed.
   2. The **use** property indicates which loader should be used to do the transforming.

### Plugins

### Mode

