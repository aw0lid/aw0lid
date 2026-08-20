# Hi, I'm Ahmed 👋
# Software Engineer 👽

🔍 **Curious about how things work under the hood.** I care about the **why** and **how**, not just using tools. 

🧩 **I enjoy solving problems where performance, architecture, and clean engineering matter.**

⚙️ **Currently:** building **Backend systems & Utilities**, mastering **Computer Science & Software Engineering**, and improving **real-world systems**       through **Open Source** contributions.

---

### 🛠️ Open Source Contributions
*Selected technical impacts on major frameworks and repositories.*

* **Microsoft .NET / Runtime:** Optimized `ImmutableHashSet<T>.SetEquals` by introducing **type and comparer-aware fast paths** with an **$O(1)$ pre-scan** and **reverse-lookup strategy**. For compatible collections, this eliminates temporary allocations entirely (**zero allocations**) and achieves up to **~4,071,000× speedup**. [PR #126309](https://github.com/dotnet/runtime/pull/126309)

* **Microsoft .NET / Runtime:** Optimized `ImmutableSortedSet<T>.SetEquals` using **comparer-aware fast paths** and replacing $O(\log n)$ per-element lookups with a **dual-enumerator sequential scan ($O(n)$)**. For compatible sorted collections, this achieves **zero allocations** and up to **~4,681,000× speedup**. [PR #126549](https://github.com/dotnet/runtime/pull/126549)

* **Microsoft .NET / F#:** Optimized `Set.intersect` for asymmetric set sizes by **selecting traversal direction dynamically using tree height ($O(1)$ heuristic)**, eliminating argument-order performance cliffs and achieving up to an **8,000× speedup**. [PR #19292](https://github.com/dotnet/fsharp/pull/19292)

* **Microsoft .NET / EF Core:** Fixed a memory leak rooting bug in `LazyLoaderFactory` by transitioning from strong references to **`List<WeakReference>`** (cleared on dispose/reset), preventing unbounded memory growth and `OutOfMemoryException` during large-scale data streaming. [PR #37977](https://github.com/dotnet/efcore/pull/37977)

* **Microsoft .NET / F#:** Fixed assembly signing failures by implementing robust RSA key blob parsing via **magic number verification (`RSA_PUB`/`RSA_PRIV`) at explicit offsets (8 and 20)** to correctly handle both raw and CLR key layouts. [PR #19242](https://github.com/dotnet/fsharp/pull/19242)

* **Microsoft .NET / Arcade:** Fixed source-build failures on non-Windows platforms by disabling full assembly signing for non-official builds, resolving RSA+SHA-1 compatibility issues. [PR #5226](https://github.com/dotnet/dotnet/pull/5226)
  
---

### 🧠 My Philosophy:
* ✨ **Clarity** over Complexity
* 🏗️ **Fundamentals** over Shortcuts
* 📈 **Continuous Progress** over Quick Wins

---

🌱 *Still learning. Constantly evolving.*
