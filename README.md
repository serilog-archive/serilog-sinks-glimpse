# Serilog.Sinks.Glimpse

[![Build status](https://ci.appveyor.com/api/projects/status/692ndogowuda2dn7/branch/master?svg=true)](https://ci.appveyor.com/project/serilog/serilog-sinks-glimpse/branch/master)


A sink for Serilog that writes events to [Glimpse](http://getglimpse.com).

**Package** - [Serilog.Sinks.Glimpse](http://nuget.org/packages/serilog.sinks.glimpse)
| **Platforms** - .NET 4.5

```csharp
var log = new LoggerConfiguration()
    .WriteTo.Glimpse()
    .CreateLogger();
```

Log events will appear in a Serilog tab under the Glimpse UI.
