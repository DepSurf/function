# Function: <code>cpu_cache_has_invalidate_memregion</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool cpu_cache_has_invalidate_memregion();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810c9c30)
Location: arch/x86/mm/pat/set_memory.c:352
Inline: False
Direct callers:
  - arch/x86/mm/pat/set_memory.c:cpu_cache_invalidate_memregion
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/region.c:nd_region_remove
```
**Symbols:**

```
ffffffff810c9c30-ffffffff810c9c51: cpu_cache_has_invalidate_memregion (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool cpu_cache_has_invalidate_memregion();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810cd2a0)
Location: arch/x86/mm/pat/set_memory.c:353
Inline: False
Direct callers:
  - arch/x86/mm/pat/set_memory.c:cpu_cache_invalidate_memregion
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/region.c:nd_region_remove
```
**Symbols:**

```
ffffffff810cd2a0-ffffffff810cd2c1: cpu_cache_has_invalidate_memregion (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool cpu_cache_has_invalidate_memregion();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810d5980)
Location: arch/x86/mm/pat/set_memory.c:353
Inline: False
Direct callers:
  - arch/x86/mm/pat/set_memory.c:cpu_cache_invalidate_memregion
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/region.c:nd_region_remove
```
**Symbols:**

```
ffffffff810d5980-ffffffff810d59a1: cpu_cache_has_invalidate_memregion (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
