# GenerateNugetDependencyGraph

* To generate dependency graph execute `dotnet msbuild /t:GenerateRestoreGraphFile /p:RestoreGraphOutputPath=graph.dg`

## Prerequisite
Have graphviz installed on your machine (needed to pass in the -v flag) download from https://graphviz.org/download/

## How-to generate graph image
execute 
* `DGVisulizer.exe -g <path to dg file> -v <Graphviz bin path> -o <output file path>`

example

`DGVisulizer.exe -g C:\git\SomeRepo\graph.dg -v C:\Graphviz\bin -o c:\temp\nugetgrapth.jpg`

**Note: temp folder must exists**



## Related blog post
https://www.jerriepelser.com/blog/analyze-dotnet-project-dependencies-part-1/
