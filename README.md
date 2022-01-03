<?xml version="1.0" encoding="utf-8"?>
<!-- Licensed to the .NET Foundation under one or more agreements. The .NET Foundation licenses this file to you under the MIT license. See the LICENSE file in the project root for more information. -->
<configuration>
  <packageSources>
    <clear />
    <!--TODO: Merged PIAs - evaluate the need of this once packages are in public feeds-->
    <add key="dotnet-eng" value="https://pkgs.dev.azure.com/dnceng/public/_packaging/dotnet-eng/nuget/v3/index.json" />
    <add key="dotnet-tools" value="https://pkgs.dev.azure.com/dnceng/public/_packaging/dotnet-tools/nuget/v3/index.json" />
    <add key="dotnet5" value="https://pkgs.dev.azure.com/dnceng/public/_packaging/dotnet5/nuget/v3/index.json" />
    <add key="dotnet-public" value="https://pkgs.dev.azure.com/dnceng/public/_packaging/dotnet-public/nuget/v3/index.json" />
    <add key="vssdk" value="https://pkgs.dev.azure.com/azure-public/vside/_packaging/vssdk/nuget/v3/index.json" />
    <add key="vs-impl" value="https://pkgs.dev.azure.com/azure-public/vside/_packaging/vs-impl/nuget/v3/index.json" />
    <add key="myget-legacy" value="https://pkgs.dev.azure.com/dnceng/public/_packaging/myget-legacy/nuget/v3/index.json" />
  </packageSources>
  <disabledPackageSources>
    <clear />
  </disabledPackageSources>
</configuration>
