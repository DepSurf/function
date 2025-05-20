# Function: <code>mhp_memmap_on_memory</code>

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
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool mhp_memmap_on_memory();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81f1a9b2)
Location: mm/memory_hotplug.c:66
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:mhp_supports_memmap_on_memory
Direct callers:
  - mm/hugetlb_vmemmap.c:hugetlb_vmemmap_sysctls_init
```
**Symbols:**

```
ffffffff81e706c7-ffffffff81e706f1: mhp_memmap_on_memory.cold (STB_LOCAL)
ffffffff81374740-ffffffff81374762: mhp_memmap_on_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff820c2852)
Location: mm/memory_hotplug.c:53
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:mhp_supports_memmap_on_memory
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff821465f2)
Location: mm/memory_hotplug.c:52
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:mhp_supports_memmap_on_memory
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff82228ddd)
Location: mm/memory_hotplug.c:120
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_remove_memory
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
</ul>
