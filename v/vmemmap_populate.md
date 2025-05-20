# Function: <code>vmemmap_populate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int vmemmap_populate(long unsigned int start, long unsigned int end, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8181ca09)
Location: arch/x86/mm/init_64.c:1295
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:sparse_mem_map_populate
```
**Symbols:**

```
ffffffff8181ca09-ffffffff8181cc53: vmemmap_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int vmemmap_populate(long unsigned int start, long unsigned int end, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81896b0b)
Location: arch/x86/mm/init_64.c:1228
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:sparse_mem_map_populate
```
**Symbols:**

```
ffffffff81896b0b-ffffffff81896dac: vmemmap_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int vmemmap_populate(long unsigned int start, long unsigned int end, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff818cb1f6)
Location: arch/x86/mm/init_64.c:1218
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:sparse_mem_map_populate
```
**Symbols:**

```
ffffffff818cb1f6-ffffffff818cb495: vmemmap_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int vmemmap_populate(long unsigned int start, long unsigned int end, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff819027d1)
Location: arch/x86/mm/init_64.c:1401
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:sparse_mem_map_populate
```
**Symbols:**

```
ffffffff819027d1-ffffffff81902a81: vmemmap_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int vmemmap_populate(long unsigned int start, long unsigned int end, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8198c736)
Location: arch/x86/mm/init_64.c:1414
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:sparse_mem_map_populate
```
**Symbols:**

```
ffffffff8198c736-ffffffff8198c9b5: vmemmap_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int vmemmap_populate(long unsigned int start, long unsigned int end, int node, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff819e9020)
Location: arch/x86/mm/init_64.c:1471
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:sparse_mem_map_populate
```
**Symbols:**

```
ffffffff819e9020-ffffffff819e92ce: vmemmap_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int vmemmap_populate(long unsigned int start, long unsigned int end, int node, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81a24966)
Location: arch/x86/mm/init_64.c:1459
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:sparse_mem_map_populate
```
**Symbols:**

```
ffffffff81a24966-ffffffff81a24c14: vmemmap_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int vmemmap_populate(long unsigned int start, long unsigned int end, int node, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81a94d0d)
Location: arch/x86/mm/init_64.c:1516
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:__populate_section_memmap
```
**Symbols:**

```
ffffffff81a94d0d-ffffffff81a94fe1: vmemmap_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int vmemmap_populate(long unsigned int start, long unsigned int end, int node, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81acc5ed)
Location: arch/x86/mm/init_64.c:1514
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:__populate_section_memmap
```
**Symbols:**

```
ffffffff81acc5ed-ffffffff81acc8c1: vmemmap_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int vmemmap_populate(long unsigned int start, long unsigned int end, int node, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81bc5083)
Location: arch/x86/mm/init_64.c:1502
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:__populate_section_memmap
```
**Symbols:**

```
ffffffff81bc5083-ffffffff81bc5110: vmemmap_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int vmemmap_populate(long unsigned int start, long unsigned int end, int node, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81c3df54)
Location: arch/x86/mm/init_64.c:1554
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:__populate_section_memmap
```
**Symbols:**

```
ffffffff81c3df54-ffffffff81c3dfe3: vmemmap_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int vmemmap_populate(long unsigned int start, long unsigned int end, int node, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81c3029d)
Location: arch/x86/mm/init_64.c:1603
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:__populate_section_memmap
```
**Symbols:**

```
ffffffff81c3029d-ffffffff81c3032c: vmemmap_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int vmemmap_populate(long unsigned int start, long unsigned int end, int node, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81d4ea28)
Location: arch/x86/mm/init_64.c:1603
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:__populate_section_memmap
```
**Symbols:**

```
ffffffff81d4ea28-ffffffff81d4eacd: vmemmap_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int vmemmap_populate(long unsigned int start, long unsigned int end, int node, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81f1e855)
Location: arch/x86/mm/init_64.c:1603
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:__populate_section_memmap
```
**Symbols:**

```
ffffffff81f1e855-ffffffff81f1e904: vmemmap_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int vmemmap_populate(long unsigned int start, long unsigned int end, int node, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff820c7640)
Location: arch/x86/mm/init_64.c:1535
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:__populate_section_memmap
```
**Symbols:**

```
ffffffff820c7640-ffffffff820c770a: vmemmap_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int vmemmap_populate(long unsigned int start, long unsigned int end, int node, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8214b6d0)
Location: arch/x86/mm/init_64.c:1535
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:__populate_section_memmap
```
**Symbols:**

```
ffffffff8214b6d0-ffffffff8214b79a: vmemmap_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int vmemmap_populate(long unsigned int start, long unsigned int end, int node, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8222e180)
Location: arch/x86/mm/init_64.c:1535
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:__populate_section_memmap
```
**Symbols:**

```
ffffffff8222e180-ffffffff8222e24a: vmemmap_populate (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int vmemmap_populate(long unsigned int start, long unsigned int end, int node, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/mm/mmu.c (ffff800010d9f7c4)
Location: arch/arm64/mm/mmu.c:736
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:__populate_section_memmap
```
**Symbols:**

```
ffff800010d9f7c4-ffff800010d9f920: vmemmap_populate (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int vmemmap_populate(long unsigned int start, long unsigned int end, int node, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/mm/init_64.c (c000000000eeb1a4)
Location: arch/powerpc/mm/init_64.c:190
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:__populate_section_memmap
```
**Symbols:**

```
c000000000eeb1a4-c000000000eeb4a8: vmemmap_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int vmemmap_populate(long unsigned int start, long unsigned int end, int node, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/riscv/mm/init.c (ffffffe000046f0c)
Location: arch/riscv/mm/init.c:463
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:__populate_section_memmap
```
**Symbols:**

```
ffffffe000046f0c-ffffffe000046f24: vmemmap_populate (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int vmemmap_populate(long unsigned int start, long unsigned int end, int node, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81a6b45d)
Location: arch/x86/mm/init_64.c:1514
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:__populate_section_memmap
```
**Symbols:**

```
ffffffff81a6b45d-ffffffff81a6b731: vmemmap_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int vmemmap_populate(long unsigned int start, long unsigned int end, int node, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81a279aa)
Location: arch/x86/mm/init_64.c:1514
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:__populate_section_memmap
```
**Symbols:**

```
ffffffff81a279aa-ffffffff81a27c80: vmemmap_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int vmemmap_populate(long unsigned int start, long unsigned int end, int node, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81ad786d)
Location: arch/x86/mm/init_64.c:1514
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:__populate_section_memmap
```
**Symbols:**

```
ffffffff81ad786d-ffffffff81ad7b41: vmemmap_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int vmemmap_populate(long unsigned int start, long unsigned int end, int node, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81ae3d2d)
Location: arch/x86/mm/init_64.c:1514
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:__populate_section_memmap
```
**Symbols:**

```
ffffffff81ae3d2d-ffffffff81ae4001: vmemmap_populate (STB_GLOBAL)
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
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct vmem_altmap *altmap</code>
</li>
</ul>
</details>
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
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
