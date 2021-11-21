# GenerateNugetDependencyGraph

* To generate dependency graph execute `dotnet msbuild /t:GenerateRestoreGraphFile /p:RestoreGraphOutputPath=graph.dg`

* To generate graph image (jpg) execute:
* `DGVisulizer.exe -g <path to dg file> -v <Graphviz bin path> -o <output file path>`




https://www.jerriepelser.com/blog/analyze-dotnet-project-dependencies-part-1/