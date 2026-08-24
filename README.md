## 🧭 Summary

Software Engineer building software systems and utilities, interested in the fundamentals and deeper concepts of Computer Science and Software Engineering.     
Enjoys solving problems where performance, design, architecture, and engineering quality matter, and improving real-world systems through Open Source contributions.

---

### 🛠️ Open Source Contributions
<sub><i>Selected contributions.</i></sub>

- Microsoft .NET / Runtime — Optimized `ImmutableHashSet<T>.SetEquals` with comparer-aware fast paths and direct lookups, eliminating unnecessary intermediate allocations and achieving up to ~**4,071,000**× speedup in specific benchmark scenarios, with zero allocations on compatible paths. ([PR #126309](https://github.com/dotnet/runtime/pull/126309))

- Microsoft .NET / Runtime — Optimized `ImmutableSortedSet<T>.SetEquals` with comparer-aware fast paths and a sequential `O(n)` comparison instead of per-element `O(log n)` lookups, achieving up to **~4,681,000**× speedup in specific benchmark scenarios, with zero allocations on compatible paths. ([PR #126549](https://github.com/dotnet/runtime/pull/126549))

- Microsoft .NET / F# — Optimized `Set.intersect` for asymmetric set sizes by dynamically selecting traversal direction using tree height, eliminating argument-order performance cliffs and achieving up to **8,000**× speedup in specific benchmark scenarios. ([PR #19292](https://github.com/dotnet/fsharp/pull/19292))

- Microsoft .NET / EF Core — Fixed a memory leak issue in `LazyLoaderFactory` by replacing strong references with `WeakReference`, preventing unbounded memory growth and `OutOfMemoryException` during large-scale data streaming. ([PR #37977](https://github.com/dotnet/efcore/pull/37977))

- Microsoft .NET / F# — Fixed assembly signing failures by robustly handling multiple RSA key blob layouts through explicit format validation. ([PR #19242](https://github.com/dotnet/fsharp/pull/19242))

- Microsoft .NET / VMR (Arcade SDK) — Fixed source-build failures on non-Windows platforms by disabling full assembly signing for non-official builds, resolving RSA+SHA-1 compatibility issues. ([PR #5226](https://github.com/dotnet/dotnet/pull/5226))

---

<p align="center">
  🌱 Still learning. Constantly evolving.
</p>
