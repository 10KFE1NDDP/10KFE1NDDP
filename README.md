<Project Sdk="Microsoft.NET.Sdk">

  <PropertyGroup>
    <OutputType>WinExe</OutputType>
    <TargetFramework>net7.0-windows</TargetFramework>
    <RootNamespace>10K_Swapper</RootNamespace>
    <Nullable>enable</Nullable>
    <UseWPF>true</UseWPF>
    <AllowUnsafeBlocks>True</AllowUnsafeBlocks>
    <PlatformTarget>x64</PlatformTarget>
    <ApplicationIcon>Workspace\Assets\Logo.ico</ApplicationIcon>
    <Authors>ddp_2k#8920</Authors>
    <Copyright>Copyright © 10K Swapper </Copyright>
    <PackageReadmeFile>README.md</PackageReadmeFile>
    <RepositoryUrl>https://github.com/10KSwapperOfficial/10K-Swapper-</RepositoryUrl>
    <PackageLicenseFile>LICENSE</PackageLicenseFile>
  </PropertyGroup>

  <PropertyGroup Condition="'$(Configuration)|$(Platform)'=='Debug|AnyCPU'">
    <Optimize>False</Optimize>
  </PropertyGroup>

  <PropertyGroup Condition="'$(Configuration)|$(Platform)'=='Release|AnyCPU'">
    <Optimize>False</Optimize>
  </PropertyGroup>

  <ItemGroup>
    <None Remove="Workspace\Assets\Arrow.png" />
    <None Remove="Workspace\Assets\Backpacks.png" />
    <None Remove="Workspace\Assets\Backpacks_Clicked.png" />
    <None Remove="Workspace\Assets\Banner.png" />
    <None Remove="Workspace\Assets\Character.png" />
    <None Remove="Workspace\Assets\Characters.png" />
    <None Remove="Workspace\Assets\Characters_Clicked.png" />
    <None Remove="Workspace\Assets\Close.png" />
    <None Remove="Workspace\Assets\Dances.png" />
    <None Remove="Workspace\Assets\Dances_Clicked.png" />
    <None Remove="Workspace\Assets\Dashboard.png" />
    <None Remove="Workspace\Assets\Dashboard_Clicked.png" />
    <None Remove="Workspace\Assets\discord.png" />
    <None Remove="Workspace\Assets\Embed.png" />
    <None Remove="Workspace\Assets\FallBackCosmeticImage.png" />
    <None Remove="Workspace\Assets\FallBackImage.png" />
    <None Remove="Workspace\Assets\FallBackPluginImage.png" />
    <None Remove="Workspace\Assets\Gliders.png" />
    <None Remove="Workspace\Assets\Gliders_Clicked.png" />
    <None Remove="Workspace\Assets\Hide.png" />
    <None Remove="Workspace\Assets\LoginPage.png" />
    <None Remove="Workspace\Assets\Logo.png" />
    <None Remove="Workspace\Assets\Minimize.png" />
    <None Remove="Workspace\Assets\Misc.png" />
    <None Remove="Workspace\Assets\Misc_Clicked.png" />
    <None Remove="Workspace\Assets\oo2core_9_win64.dll" />
    <None Remove="Workspace\Assets\Pickaxes.png" />
    <None Remove="Workspace\Assets\Pickaxes_Clicked.png" />
    <None Remove="Workspace\Assets\Plugins.png" />
    <None Remove="Workspace\Assets\Plugins_Clicked.png" />
    <None Remove="Workspace\Assets\ReImport.png" />
    <None Remove="Workspace\Assets\Remove.png" />
    <None Remove="Workspace\Assets\Searchbar.png" />
    <None Remove="Workspace\Assets\Searching.png" />
    <None Remove="Workspace\Assets\Settings.png" />
    <None Remove="Workspace\Assets\Settings_Clicked.png" />
    <None Remove="Workspace\Assets\Show.png" />
    <None Remove="Workspace\Assets\ThumbsUp.png" />
    <None Remove="Workspace\Assets\Wave.png" />
    <None Remove="Workspace\Assets\Weapons.png" />
    <None Remove="Workspace\Assets\Weapons_Clicked.png" />
    <None Remove="Workspace\CProvider\README.md" />
  </ItemGroup>

  <ItemGroup>
    <Content Include="Workspace\Assets\Logo.ico" />
  </ItemGroup>

  <ItemGroup>
    <PackageReference Include="DiscordRichPresence" Version="1.1.3.18" />
    <PackageReference Include="DotNetZip" Version="1.16.0" />
    <PackageReference Include="GenericReader" Version="1.0.3" />
    <PackageReference Include="K4os.Compression.LZ4" Version="1.3.5" />
    <PackageReference Include="Newtonsoft.Json" Version="13.0.3" />
    <PackageReference Include="RestSharp" Version="110.2.0" />
    <PackageReference Include="Serilog" Version="2.12.0" />
    <PackageReference Include="Serilog.Sinks.Debug" Version="2.0.0" />
    <PackageReference Include="Serilog.Sinks.File" Version="5.0.0" />
    <PackageReference Include="SharpZipLib" Version="1.4.2" />
    <PackageReference Include="WindowsAPICodePack.Shell.CommonFileDialogs" Version="1.1.5" />
  </ItemGroup>

  <ItemGroup>
    <Resource Include="Workspace\Assets\Arrow.png" />
    <Resource Include="Workspace\Assets\Backpacks.png" />
    <Resource Include="Workspace\Assets\Backpacks_Clicked.png" />
    <Resource Include="Workspace\Assets\Banner.png" />
    <Resource Include="Workspace\Assets\Character.png" />
    <Resource Include="Workspace\Assets\Characters.png" />
    <Resource Include="Workspace\Assets\Characters_Clicked.png" />
    <Resource Include="Workspace\Assets\Close.png" />
    <Resource Include="Workspace\Assets\Dances.png" />
    <Resource Include="Workspace\Assets\Dances_Clicked.png" />
    <Resource Include="Workspace\Assets\Dashboard.png" />
    <Resource Include="Workspace\Assets\Dashboard_Clicked.png" />
    <Resource Include="Workspace\Assets\Discord.png" />
    <Resource Include="Workspace\Assets\Embed.png" />
    <Resource Include="Workspace\Assets\FallBackCosmeticImage.png" />
    <Resource Include="Workspace\Assets\FallBackImage.png" />
    <Resource Include="Workspace\Assets\FallBackPluginImage.png" />
    <Resource Include="Workspace\Assets\Gliders.png" />
    <Resource Include="Workspace\Assets\Gliders_Clicked.png" />
    <Resource Include="Workspace\Assets\Hide.png" />
    <Resource Include="Workspace\Assets\LoginPage.png" />
    <Resource Include="Workspace\Assets\Logo.png" />
    <Resource Include="Workspace\Assets\Minimize.png" />
    <Resource Include="Workspace\Assets\Misc.png" />
    <Resource Include="Workspace\Assets\Misc_Clicked.png" />
    <EmbeddedResource Include="README.md" />
    <EmbeddedResource Include="Workspace\Assets\oo2core_9_win64.dll" />
    <Resource Include="Workspace\Assets\Pickaxes.png" />
    <Resource Include="Workspace\Assets\Pickaxes_Clicked.png" />
    <Resource Include="Workspace\Assets\Plugins.png" />
    <Resource Include="Workspace\Assets\Plugins_Clicked.png" />
    <Resource Include="Workspace\Assets\ReImport.png" />
    <Resource Include="Workspace\Assets\Remove.png" />
    <Resource Include="Workspace\Assets\Searchbar.png" />
    <Resource Include="Workspace\Assets\Searching.png" />
    <Resource Include="Workspace\Assets\Settings.png" />
    <Resource Include="Workspace\Assets\Settings_Clicked.png" />
    <Resource Include="Workspace\Assets\Show.png" />
    <Resource Include="Workspace\Assets\ThumbsUp.png" />
    <Resource Include="Workspace\Assets\Wave.png" />
    <Resource Include="Workspace\Assets\Weapons.png" />
    <Resource Include="Workspace\Assets\Weapons_Clicked.png" />
    <EmbeddedResource Include="Workspace\CProvider\README.md" />
  </ItemGroup>

  <ItemGroup>
    <None Update="LICENSE">
      <Pack>True</Pack>
      <PackagePath>\</PackagePath>
    </None>
    <None Update="README.md">
      <Pack>True</Pack>
      <PackagePath>\</PackagePath>
    </None>
  </ItemGroup>

</Project>
