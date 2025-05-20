# Function: <code>mhp_deinit_memmap_on_memory</code>

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
void mhp_deinit_memmap_on_memory(long unsigned int pfn, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812c7170)
Location: mm/memory_hotplug.c:899
Inline: False
Direct callers:
  - drivers/base/memory.c:memory_subsys_offline
  - drivers/base/memory.c:memory_block_online
```
**Symbols:**

```
ffffffff812c7170-ffffffff812c71dd: mhp_deinit_memmap_on_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void mhp_deinit_memmap_on_memory(long unsigned int pfn, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff8130beb0)
Location: mm/memory_hotplug.c:1054
Inline: False
Direct callers:
  - drivers/base/memory.c:memory_subsys_offline
  - drivers/base/memory.c:memory_block_online
```
**Symbols:**

```
ffffffff8130beb0-ffffffff8130bf3e: mhp_deinit_memmap_on_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void mhp_deinit_memmap_on_memory(long unsigned int pfn, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81374e80)
Location: mm/memory_hotplug.c:1053
Inline: False
Direct callers:
  - drivers/base/memory.c:memory_subsys_offline
  - drivers/base/memory.c:memory_block_online
```
**Symbols:**

```
ffffffff81374e80-ffffffff81374f1b: mhp_deinit_memmap_on_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mhp_deinit_memmap_on_memory(long unsigned int pfn, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff813f2800)
Location: mm/memory_hotplug.c:1052
Inline: False
Direct callers:
  - drivers/base/memory.c:memory_subsys_offline
  - drivers/base/memory.c:memory_block_online
```
**Symbols:**

```
ffffffff813f2800-ffffffff813f289b: mhp_deinit_memmap_on_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mhp_deinit_memmap_on_memory(long unsigned int pfn, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81426240)
Location: mm/memory_hotplug.c:1046
Inline: False
Direct callers:
  - drivers/base/memory.c:memory_subsys_offline
  - drivers/base/memory.c:memory_block_online
```
**Symbols:**

```
ffffffff81426240-ffffffff814262db: mhp_deinit_memmap_on_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mhp_deinit_memmap_on_memory(long unsigned int pfn, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81453480)
Location: mm/memory_hotplug.c:1124
Inline: False
Direct callers:
  - drivers/base/memory.c:memory_subsys_offline
  - drivers/base/memory.c:memory_block_online
```
**Symbols:**

```
ffffffff81453480-ffffffff8145351b: mhp_deinit_memmap_on_memory (STB_GLOBAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
