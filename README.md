# Taha Zahit Hakyemez

Backend-focused full-stack .NET developer at Kivi ERP. Most of my day is C#, ASP.NET Core, EF Core and SQL Server;
on the side I maintain a few small, tested .NET libraries on NuGet.

**Focus:** backend services and data access in .NET, EF Core and SQL Server, thread-safe collections, developer tooling.

**Stack:** C#, .NET, ASP.NET Core, EF Core, SQL Server / T-SQL, TypeScript, React, Electron, Python.

## Projects

| Project | What it does | Downloads |
| --- | --- | --- |
| [EFCore.NoLock](https://github.com/TahaZahit/EFCore.NoLock) | Adds `WITH (NOLOCK)` to selected EF Core and LinqToDB queries through a fluent `.WithNoLock()` call. Rewrites the SQL with Microsoft's T-SQL ScriptDom parser instead of regex and caches the result. .NET 6 to 10. | [![NuGet](https://img.shields.io/nuget/dt/EFCore.NoLock?label=nuget)](https://www.nuget.org/packages/EFCore.NoLock) |
| [BiMap](https://github.com/TahaZahit/BiMap) | Thread-safe generic bidirectional (1:1) map with O(1) lookups in both directions. netstandard2.0. | [![NuGet](https://img.shields.io/nuget/dt/BiMap?label=nuget)](https://www.nuget.org/packages/BiMap) |
| [MultiMap.NET](https://github.com/TahaZahit/MultiMap.NET) | Thread-safe mutable multi-map (many values per key) that implements `ILookup<TKey, TValue>`, so it drops into existing LINQ code. | [![NuGet](https://img.shields.io/nuget/dt/MultiMap.NET?label=nuget)](https://www.nuget.org/packages/MultiMap.NET) |
| [cron-manager](https://github.com/TahaZahit/cron-manager) | Raycast extension to create, run, pause and inspect local cron jobs. Published in the [Raycast Store](https://www.raycast.com/tahazahit/cron-manager). | |
| [absolutely-not](https://github.com/TahaZahit/absolutely-not) | A skill and a Stop hook for coding agents: rules against reflexive agreement, and a guard that blocks "done" when nothing was run. | |
| [dassh](https://github.com/TahaZahit/dassh) | Electron + React SSH client with a multi-terminal grid, an SFTP file manager and command broadcast. | |

## Open source contributions

- [raycast/extensions#24426](https://github.com/raycast/extensions/pull/24426): adds the cron-manager extension to the Raycast Store (merged)
- [raycast/extensions#25845](https://github.com/raycast/extensions/pull/25845): cron-manager fix for tasks disappearing from the UI and permission handling (merged)
- [yash-srivastava/Overdrive-release#341](https://github.com/yash-srivastava/Overdrive-release/pull/341): fix for the vehicle capacity field on comma-decimal locales (merged)

## Contact

[tahazahit@gmail.com](mailto:tahazahit@gmail.com) · [NuGet](https://www.nuget.org/profiles/TahaZahit) · [Raycast](https://www.raycast.com/tahazahit)
