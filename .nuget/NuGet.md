Commands
------------
nuget setApiKey xxx-xxx-xxxx-xxxx -Source https://www.nuget.org/api/v2/package

nuget push .\packages\Redola.Rpc.1.0.0.0.nupkg -Source https://www.nuget.org/api/v2/package
nuget pack ..\Redola\Redola.Rpc\Redola.Rpc.csproj -IncludeReferencedProjects -Symbols -Build -Prop Configuration=Release -OutputDirectory ".\packages"
