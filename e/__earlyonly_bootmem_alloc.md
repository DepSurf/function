# Function: <code>__earlyonly_bootmem_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81819577)
Location: mm/sparse-vmemmap.c:38
Inline: True
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
  - mm/sparse-vmemmap.c:sparse_mem_maps_populate_node
```
**Symbols:**

```
ffffffff81819577-ffffffff81819597: __earlyonly_bootmem_alloc.constprop.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *__earlyonly_bootmem_alloc(int node, long unsigned int size, long unsigned int align, long unsigned int goal);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff818930c3)
Location: mm/sparse-vmemmap.c:39
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:sparse_mem_maps_populate_node
```
**Symbols:**

```
ffffffff818930c3-ffffffff818930e1: __earlyonly_bootmem_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *__earlyonly_bootmem_alloc(int node, long unsigned int size, long unsigned int align, long unsigned int goal);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff818c7913)
Location: mm/sparse-vmemmap.c:39
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:sparse_mem_maps_populate_node
```
**Symbols:**

```
ffffffff818c7913-ffffffff818c7931: __earlyonly_bootmem_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *__earlyonly_bootmem_alloc(int node, long unsigned int size, long unsigned int align, long unsigned int goal);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff818ff073)
Location: mm/sparse-vmemmap.c:39
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:sparse_mem_maps_populate_node
```
**Symbols:**

```
ffffffff818ff073-ffffffff818ff091: __earlyonly_bootmem_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *__earlyonly_bootmem_alloc(int node, long unsigned int size, long unsigned int align, long unsigned int goal);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff819891e2)
Location: mm/sparse-vmemmap.c:40
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:sparse_mem_maps_populate_node
```
**Symbols:**

```
ffffffff819891e2-ffffffff81989200: __earlyonly_bootmem_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *__earlyonly_bootmem_alloc(int node, long unsigned int size, long unsigned int align, long unsigned int goal);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff819e5b3f)
Location: mm/sparse-vmemmap.c:40
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:sparse_mem_maps_populate_node
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
**Symbols:**

```
ffffffff819e5b3f-ffffffff819e5b5d: __earlyonly_bootmem_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *__earlyonly_bootmem_alloc(int node, long unsigned int size, long unsigned int align, long unsigned int goal);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81a20f19)
Location: mm/sparse-vmemmap.c:40
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
**Symbols:**

```
ffffffff81a20f19-ffffffff81a20f37: __earlyonly_bootmem_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *__earlyonly_bootmem_alloc(int node, long unsigned int size, long unsigned int align, long unsigned int goal);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81a914fd)
Location: mm/sparse-vmemmap.c:40
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
**Symbols:**

```
ffffffff81a914fd-ffffffff81a9151b: __earlyonly_bootmem_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *__earlyonly_bootmem_alloc(int node, long unsigned int size, long unsigned int align, long unsigned int goal);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81ac882a)
Location: mm/sparse-vmemmap.c:40
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
**Symbols:**

```
ffffffff81ac882a-ffffffff81ac8848: __earlyonly_bootmem_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *__earlyonly_bootmem_alloc(int node, long unsigned int size, long unsigned int align, long unsigned int goal);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81bc122a)
Location: mm/sparse-vmemmap.c:39
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
**Symbols:**

```
ffffffff81bc122a-ffffffff81bc1248: __earlyonly_bootmem_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *__earlyonly_bootmem_alloc(int node, long unsigned int size, long unsigned int align, long unsigned int goal);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81c3a27c)
Location: mm/sparse-vmemmap.c:39
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
**Symbols:**

```
ffffffff81c3a27c-ffffffff81c3a29a: __earlyonly_bootmem_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *__earlyonly_bootmem_alloc(int node, long unsigned int size, long unsigned int align, long unsigned int goal);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81c2dafc)
Location: mm/sparse-vmemmap.c:39
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
**Symbols:**

```
ffffffff81c2dafc-ffffffff81c2db1a: __earlyonly_bootmem_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *__earlyonly_bootmem_alloc(int node, long unsigned int size, long unsigned int align, long unsigned int goal);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81d4c3f1)
Location: mm/sparse-vmemmap.c:393
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
**Symbols:**

```
ffffffff81d4c3f1-ffffffff81d4c40f: __earlyonly_bootmem_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *__earlyonly_bootmem_alloc(int node, long unsigned int size, long unsigned int align, long unsigned int goal);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81f1bf16)
Location: mm/sparse-vmemmap.c:439
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
**Symbols:**

```
ffffffff81f1bf16-ffffffff81f1bf43: __earlyonly_bootmem_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *__earlyonly_bootmem_alloc(int node, long unsigned int size, long unsigned int align, long unsigned int goal);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff820c3ec0)
Location: mm/sparse-vmemmap.c:40
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
**Symbols:**

```
ffffffff820c3ec0-ffffffff820c3eed: __earlyonly_bootmem_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *__earlyonly_bootmem_alloc(int node, long unsigned int size, long unsigned int align, long unsigned int goal);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff82147c70)
Location: mm/sparse-vmemmap.c:40
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
**Symbols:**

```
ffffffff82147c70-ffffffff82147c9d: __earlyonly_bootmem_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *__earlyonly_bootmem_alloc(int node, long unsigned int size, long unsigned int align, long unsigned int goal);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff8222a570)
Location: mm/sparse-vmemmap.c:40
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
**Symbols:**

```
ffffffff8222a570-ffffffff8222a59d: __earlyonly_bootmem_alloc (STB_LOCAL)
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
void *__earlyonly_bootmem_alloc(int node, long unsigned int size, long unsigned int align, long unsigned int goal);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffff800010d9c538)
Location: mm/sparse-vmemmap.c:40
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
**Symbols:**

```
ffff800010d9c538-ffff800010d9c588: __earlyonly_bootmem_alloc (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/sparse-vmemmap.c (c000000000417e64)
Location: mm/sparse-vmemmap.c:40
Inline: True
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
**Symbols:**

```
c000000000417e64-c000000000417eb4: __earlyonly_bootmem_alloc.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *__earlyonly_bootmem_alloc(int node, long unsigned int size, long unsigned int align, long unsigned int goal);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffe0008c469a)
Location: mm/sparse-vmemmap.c:40
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
**Symbols:**

```
ffffffe0008c469a-ffffffe0008c46de: __earlyonly_bootmem_alloc (STB_LOCAL)
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
void *__earlyonly_bootmem_alloc(int node, long unsigned int size, long unsigned int align, long unsigned int goal);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81a6769a)
Location: mm/sparse-vmemmap.c:40
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
**Symbols:**

```
ffffffff81a6769a-ffffffff81a676b8: __earlyonly_bootmem_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *__earlyonly_bootmem_alloc(int node, long unsigned int size, long unsigned int align, long unsigned int goal);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81a2415a)
Location: mm/sparse-vmemmap.c:40
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
**Symbols:**

```
ffffffff81a2415a-ffffffff81a24178: __earlyonly_bootmem_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *__earlyonly_bootmem_alloc(int node, long unsigned int size, long unsigned int align, long unsigned int goal);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81ad3aaa)
Location: mm/sparse-vmemmap.c:40
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
**Symbols:**

```
ffffffff81ad3aaa-ffffffff81ad3ac8: __earlyonly_bootmem_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *__earlyonly_bootmem_alloc(int node, long unsigned int size, long unsigned int align, long unsigned int goal);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81adff9d)
Location: mm/sparse-vmemmap.c:40
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
**Symbols:**

```
ffffffff81adff9d-ffffffff81adffbb: __earlyonly_bootmem_alloc (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
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
