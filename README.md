# dotnet-resort-api
```
<Project Sdk="Microsoft.NET.Sdk.Web">

  <PropertyGroup>
    <TargetFramework>net6.0</TargetFramework>
  </PropertyGroup>

  <ItemGroup>
    <PackageReference Include="Microsoft.AspNetCore.Authentication.JwtBearer" Version="6.0.1" />
    <PackageReference Include="Microsoft.AspNetCore.Identity.EntityFrameworkCore" Version="6.0.1" />
    <PackageReference Include="Microsoft.AspNetCore.Mvc.Abstractions" Version="2.2.0" />
    <PackageReference Include="Microsoft.AspNetCore.Mvc.NewtonsoftJson" Version="6.0.1" />
    <PackageReference Include="Microsoft.EntityFrameworkCore" Version="6.0.1" />
    <PackageReference Include="Microsoft.EntityFrameworkCore.Design" Version="6.0.1">
      <IncludeAssets>runtime; build; native; contentfiles; analyzers; buildtransitive</IncludeAssets>
      <PrivateAssets>all</PrivateAssets>
    </PackageReference>
    <PackageReference Include="Microsoft.EntityFrameworkCore.SqlServer" Version="6.0.1" />
    <PackageReference Include="Microsoft.EntityFrameworkCore.Tools" Version="6.0.1">
      <PrivateAssets>all</PrivateAssets>
      <IncludeAssets>runtime; build; native; contentfiles; analyzers; buildtransitive</IncludeAssets>
    </PackageReference>
    <PackageReference Include="Microsoft.VisualStudio.Web.CodeGeneration.Utils" Version="6.0.1" />
    <PackageReference Include="Swashbuckle.AspNetCore" Version="6.0.1" />
  </ItemGroup>

</Project>
```