# Function: <code>sync_global_pgds</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void sync_global_pgds(long unsigned int start, long unsigned int end, int removed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81069470)
Location: arch/x86/mm/init_64.c:166
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/fault.c:vmalloc_sync_all
```
**Symbols:**

```
ffffffff81069470-ffffffff81069638: sync_global_pgds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void sync_global_pgds(long unsigned int start, long unsigned int end, int removed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81069200)
Location: arch/x86/mm/init_64.c:95
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
  - arch/x86/mm/fault.c:vmalloc_sync_all
```
**Symbols:**

```
ffffffff81069200-ffffffff810693cf: sync_global_pgds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void sync_global_pgds(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8106ce50)
Location: arch/x86/mm/init_64.c:95
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
  - arch/x86/mm/fault.c:vmalloc_sync_all
```
**Symbols:**

```
ffffffff8106ce50-ffffffff8106cfac: sync_global_pgds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void sync_global_pgds(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8106c490)
Location: arch/x86/mm/init_64.c:133
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
  - arch/x86/mm/fault.c:vmalloc_sync_all
```
**Symbols:**

```
ffffffff8106c490-ffffffff8106c607: sync_global_pgds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void sync_global_pgds(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81070f50)
Location: arch/x86/mm/init_64.c:133
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
  - arch/x86/mm/fault.c:vmalloc_sync_all
```
**Symbols:**

```
ffffffff81070f50-ffffffff810710de: sync_global_pgds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void sync_global_pgds(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff819e9286)
Location: arch/x86/mm/init_64.c:181
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
Direct callers:
  - arch/x86/mm/fault.c:vmalloc_sync_all
```
**Symbols:**

```
ffffffff81073e50-ffffffff81073e60: sync_global_pgds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void sync_global_pgds(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81a24bcc)
Location: arch/x86/mm/init_64.c:180
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
Direct callers:
  - arch/x86/mm/fault.c:vmalloc_sync_all
```
**Symbols:**

```
ffffffff81079d40-ffffffff81079d50: sync_global_pgds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void sync_global_pgds(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81a94f8e)
Location: arch/x86/mm/init_64.c:212
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
Direct callers:
  - arch/x86/mm/fault.c:vmalloc_sync_all
```
**Symbols:**

```
ffffffff8107da70-ffffffff8107da80: sync_global_pgds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void sync_global_pgds(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81acc86e)
Location: arch/x86/mm/init_64.c:212
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
Direct callers:
  - arch/x86/mm/fault.c:vmalloc_sync_mappings
```
**Symbols:**

```
ffffffff8107eb00-ffffffff8107eb10: sync_global_pgds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void sync_global_pgds(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff810853f0)
Location: arch/x86/mm/init_64.c:212
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:arch_sync_kernel_mappings
```
**Symbols:**

```
ffffffff810853f0-ffffffff8108540c: sync_global_pgds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void sync_global_pgds(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81bd8ff8)
Location: arch/x86/mm/init_64.c:212
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
```
**Symbols:**

```
ffffffff81bd8ff8-ffffffff81bd9016: sync_global_pgds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void sync_global_pgds(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81bcafaf)
Location: arch/x86/mm/init_64.c:212
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
```
**Symbols:**

```
ffffffff81bcafaf-ffffffff81bcafcd: sync_global_pgds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void sync_global_pgds(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81ca054b)
Location: arch/x86/mm/init_64.c:213
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
```
**Symbols:**

```
ffffffff81ca054b-ffffffff81ca0569: sync_global_pgds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void sync_global_pgds(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81e4fbdd)
Location: arch/x86/mm/init_64.c:212
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
```
**Symbols:**

```
ffffffff81e4fbdd-ffffffff81e4fc03: sync_global_pgds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void sync_global_pgds(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff810c16e0)
Location: arch/x86/mm/init_64.c:218
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
```
**Symbols:**

```
ffffffff810c16e0-ffffffff810c170c: sync_global_pgds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void sync_global_pgds(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff810c4dc0)
Location: arch/x86/mm/init_64.c:218
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
```
**Symbols:**

```
ffffffff810c4dc0-ffffffff810c4dec: sync_global_pgds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void sync_global_pgds(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff810cd210)
Location: arch/x86/mm/init_64.c:218
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
```
**Symbols:**

```
ffffffff810cd210-ffffffff810cd23c: sync_global_pgds (STB_LOCAL)
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
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void sync_global_pgds(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81a6b6de)
Location: arch/x86/mm/init_64.c:212
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
Direct callers:
  - arch/x86/mm/fault.c:vmalloc_sync_mappings
```
**Symbols:**

```
ffffffff8107db00-ffffffff8107db10: sync_global_pgds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void sync_global_pgds(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81a27c2d)
Location: arch/x86/mm/init_64.c:212
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
Direct callers:
  - arch/x86/mm/fault.c:vmalloc_sync_mappings
```
**Symbols:**

```
ffffffff8106ce00-ffffffff8106ce10: sync_global_pgds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void sync_global_pgds(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81ad7aee)
Location: arch/x86/mm/init_64.c:212
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
Direct callers:
  - arch/x86/mm/fault.c:vmalloc_sync_mappings
```
**Symbols:**

```
ffffffff8107dab0-ffffffff8107dac0: sync_global_pgds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void sync_global_pgds(long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81ae3fae)
Location: arch/x86/mm/init_64.c:212
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
Direct callers:
  - arch/x86/mm/fault.c:vmalloc_sync_mappings
```
**Symbols:**

```
ffffffff8107fba0-ffffffff8107fbb0: sync_global_pgds (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int removed</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
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
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
