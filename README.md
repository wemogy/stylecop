# ![wemogy logo](https://wemogyimages.blob.core.windows.net/logos/wemogy-github-tiny.png) StyleCop

To use this set of StyleCop coding style rules automatically in all projects of a solution, create a `Directory.Build.props` file next to your `.sln` solution file with the following content:

```xml
<?xml version="1.0" encoding="utf-8"?>
<Project>
    <ItemGroup>
        <PackageReference Include="Wemogy.StyleCop" Version="0.1.5" />
    </ItemGroup>
</Project>
```
