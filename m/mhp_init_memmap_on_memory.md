# Function: <code>mhp_init_memmap_on_memory</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int mhp_init_memmap_on_memory(long unsigned int pfn, long unsigned int nr_pages, struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812c7120)
Location: mm/memory_hotplug.c:876
Inline: False
Direct callers:
  - drivers/base/memory.c:memory_block_online
```
**Symbols:**

```
ffffffff812c7120-ffffffff812c716f: mhp_init_memmap_on_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int mhp_init_memmap_on_memory(long unsigned int pfn, long unsigned int nr_pages, struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff8130be60)
Location: mm/memory_hotplug.c:1031
Inline: False
Direct callers:
  - drivers/base/memory.c:memory_block_online
```
**Symbols:**

```
ffffffff8130be60-ffffffff8130beaf: mhp_init_memmap_on_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int mhp_init_memmap_on_memory(long unsigned int pfn, long unsigned int nr_pages, struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81374e10)
Location: mm/memory_hotplug.c:1030
Inline: False
Direct callers:
  - drivers/base/memory.c:memory_block_online
```
**Symbols:**

```
ffffffff81374e10-ffffffff81374e7d: mhp_init_memmap_on_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mhp_init_memmap_on_memory(long unsigned int pfn, long unsigned int nr_pages, struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff813f2770)
Location: mm/memory_hotplug.c:1026
Inline: False
Direct callers:
  - drivers/base/memory.c:memory_block_online
```
**Symbols:**

```
ffffffff813f2770-ffffffff813f27ee: mhp_init_memmap_on_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mhp_init_memmap_on_memory(long unsigned int pfn, long unsigned int nr_pages, struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff814261b0)
Location: mm/memory_hotplug.c:1020
Inline: False
Direct callers:
  - drivers/base/memory.c:memory_block_online
```
**Symbols:**

```
ffffffff814261b0-ffffffff8142622e: mhp_init_memmap_on_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mhp_init_memmap_on_memory(long unsigned int pfn, long unsigned int nr_pages, struct zone *zone, bool mhp_off_inaccessible);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff814533f0)
Location: mm/memory_hotplug.c:1089
Inline: False
Direct callers:
  - drivers/base/memory.c:memory_block_online
```
**Symbols:**

```
ffffffff814533f0-ffffffff8145346e: mhp_init_memmap_on_memory (STB_GLOBAL)
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
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool mhp_off_inaccessible</code>
</li>
</ul>
</details>
</li>
</ul>
