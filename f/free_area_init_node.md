# Function: <code>free_area_init_node</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void free_area_init_node(int nid, long unsigned int *zones_size, long unsigned int node_start_pfn, long unsigned int *zholes_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8181d33b)
Location: mm/page_alloc.c:5314
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:free_area_init
  - mm/memory_hotplug.c:hotadd_new_pgdat
```
**Symbols:**

```
ffffffff8181d33b-ffffffff8181d7dd: free_area_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void free_area_init_node(int nid, long unsigned int *zones_size, long unsigned int node_start_pfn, long unsigned int *zholes_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff818975bd)
Location: mm/page_alloc.c:5900
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:free_area_init_nodes
  - mm/memory_hotplug.c:hotadd_new_pgdat
```
**Symbols:**

```
ffffffff818975bd-ffffffff81897b4d: free_area_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void free_area_init_node(int nid, long unsigned int *zones_size, long unsigned int node_start_pfn, long unsigned int *zholes_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff818cbcb9)
Location: mm/page_alloc.c:5939
Inline: False
Direct callers:
  - arch/x86/mm/numa.c:init_cpu_to_node
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:free_area_init_nodes
  - mm/memory_hotplug.c:hotadd_new_pgdat
```
**Symbols:**

```
ffffffff818cbcb9-ffffffff818cc1e9: free_area_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void free_area_init_node(int nid, long unsigned int *zones_size, long unsigned int node_start_pfn, long unsigned int *zholes_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8190323d)
Location: mm/page_alloc.c:6236
Inline: False
Direct callers:
  - arch/x86/mm/numa.c:init_cpu_to_node
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:free_area_init_nodes
  - mm/memory_hotplug.c:hotadd_new_pgdat
```
**Symbols:**

```
ffffffff8190323d-ffffffff81903761: free_area_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void free_area_init_node(int nid, long unsigned int *zones_size, long unsigned int node_start_pfn, long unsigned int *zholes_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8198d14d)
Location: mm/page_alloc.c:6213
Inline: False
Direct callers:
  - arch/x86/mm/numa.c:init_cpu_to_node
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:free_area_init_nodes
  - mm/memory_hotplug.c:hotadd_new_pgdat
```
**Symbols:**

```
ffffffff8198d14d-ffffffff8198d671: free_area_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void free_area_init_node(int nid, long unsigned int *zones_size, long unsigned int node_start_pfn, long unsigned int *zholes_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff819e9a15)
Location: mm/page_alloc.c:6348
Inline: False
Direct callers:
  - arch/x86/mm/numa.c:init_cpu_to_node
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:free_area_init_nodes
  - mm/memory_hotplug.c:hotadd_new_pgdat
```
**Symbols:**

```
ffffffff819e9a15-ffffffff819e9f31: free_area_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void free_area_init_node(int nid, long unsigned int *zones_size, long unsigned int node_start_pfn, long unsigned int *zholes_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff828b909e)
Location: mm/page_alloc.c:6643
Inline: False
Direct callers:
  - arch/x86/mm/numa.c:init_cpu_to_node
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:free_area_init_nodes
```
**Symbols:**

```
ffffffff828b909e-ffffffff828b94e1: free_area_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void free_area_init_node(int nid, long unsigned int *zones_size, long unsigned int node_start_pfn, long unsigned int *zholes_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff828d616c)
Location: mm/page_alloc.c:6839
Inline: False
Direct callers:
  - arch/x86/mm/numa.c:init_cpu_to_node
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:free_area_init_nodes
```
**Symbols:**

```
ffffffff828d616c-ffffffff828d65d8: free_area_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void free_area_init_node(int nid, long unsigned int *zones_size, long unsigned int node_start_pfn, long unsigned int *zholes_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff828de5e0)
Location: mm/page_alloc.c:6859
Inline: False
Direct callers:
  - arch/x86/mm/numa.c:init_cpu_to_node
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:free_area_init_nodes
```
**Symbols:**

```
ffffffff828de5e0-ffffffff828dea5b: free_area_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void free_area_init_node(int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff82cfbe49)
Location: mm/page_alloc.c:6884
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:free_area_init_memoryless_node
```
**Symbols:**

```
ffffffff82cfbe49-ffffffff82cfbf28: free_area_init_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void free_area_init_node(int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff82fe8869)
Location: mm/page_alloc.c:7114
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:free_area_init_memoryless_node
```
**Symbols:**

```
ffffffff82fe8869-ffffffff82fe8948: free_area_init_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void free_area_init_node(int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff831f2daf)
Location: mm/page_alloc.c:7330
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:free_area_init_memoryless_node
```
**Symbols:**

```
ffffffff831f2daf-ffffffff831f31f2: free_area_init_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void free_area_init_node(int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff832d8ed0)
Location: mm/page_alloc.c:7572
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:free_area_init_memoryless_node
```
**Symbols:**

```
ffffffff832d8ed0-ffffffff832d92e3: free_area_init_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void free_area_init_node(int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8348dd39)
Location: mm/page_alloc.c:7718
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:free_area_init
```
**Symbols:**

```
ffffffff8348dd39-ffffffff8348e1ef: free_area_init_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void free_area_init_node(int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff83ebff70)
Location: mm/page_alloc.c:7903
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:free_area_init
```
**Symbols:**

```
ffffffff83ebff70-ffffffff83ec0286: free_area_init_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void free_area_init_node(int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mm_init.c (ffffffff836e2010)
Location: mm/mm_init.c:1705
Inline: False
Direct callers:
  - mm/mm_init.c:free_area_init
  - mm/mm_init.c:free_area_init
```
**Symbols:**

```
ffffffff836e2010-ffffffff836e21b5: free_area_init_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void free_area_init_node(int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mm_init.c (ffffffff83914920)
Location: mm/mm_init.c:1703
Inline: False
Direct callers:
  - mm/mm_init.c:free_area_init
  - mm/mm_init.c:free_area_init
```
**Symbols:**

```
ffffffff83914920-ffffffff83914ac5: free_area_init_node (STB_LOCAL)
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
void free_area_init_node(int nid, long unsigned int *zones_size, long unsigned int node_start_pfn, long unsigned int *zholes_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffff800011457324)
Location: mm/page_alloc.c:6859
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:free_area_init_nodes
```
**Symbols:**

```
ffff800011457324-ffff800011457764: free_area_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void free_area_init_node(int nid, long unsigned int *zones_size, long unsigned int node_start_pfn, long unsigned int *zholes_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c153194c)
Location: mm/page_alloc.c:6859
Inline: False
Direct callers:
  - arch/arm/mm/init.c:bootmem_init
  - mm/page_alloc.c:free_area_init
```
**Symbols:**

```
c153194c-c1531c78: free_area_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void free_area_init_node(int nid, long unsigned int *zones_size, long unsigned int node_start_pfn, long unsigned int *zholes_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c000000001380858)
Location: mm/page_alloc.c:6859
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:free_area_init_nodes
```
**Symbols:**

```
c000000001380858-c000000001380db8: free_area_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void free_area_init_node(int nid, long unsigned int *zones_size, long unsigned int node_start_pfn, long unsigned int *zholes_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffe000015dca)
Location: mm/page_alloc.c:6859
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:free_area_init_nodes
```
**Symbols:**

```
ffffffe000015dca-ffffffe00001624a: free_area_init_node (STB_GLOBAL)
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
void free_area_init_node(int nid, long unsigned int *zones_size, long unsigned int node_start_pfn, long unsigned int *zholes_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff828c7494)
Location: mm/page_alloc.c:6859
Inline: False
Direct callers:
  - arch/x86/mm/numa.c:init_cpu_to_node
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:free_area_init_nodes
```
**Symbols:**

```
ffffffff828c7494-ffffffff828c790f: free_area_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void free_area_init_node(int nid, long unsigned int *zones_size, long unsigned int node_start_pfn, long unsigned int *zholes_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff828bfbb9)
Location: mm/page_alloc.c:6859
Inline: False
Direct callers:
  - arch/x86/mm/numa.c:init_cpu_to_node
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:free_area_init_nodes
```
**Symbols:**

```
ffffffff828bfbb9-ffffffff828c0034: free_area_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void free_area_init_node(int nid, long unsigned int *zones_size, long unsigned int node_start_pfn, long unsigned int *zholes_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff828da214)
Location: mm/page_alloc.c:6859
Inline: False
Direct callers:
  - arch/x86/mm/numa.c:init_cpu_to_node
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:free_area_init_nodes
```
**Symbols:**

```
ffffffff828da214-ffffffff828da68f: free_area_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void free_area_init_node(int nid, long unsigned int *zones_size, long unsigned int node_start_pfn, long unsigned int *zholes_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff828df635)
Location: mm/page_alloc.c:6859
Inline: False
Direct callers:
  - arch/x86/mm/numa.c:init_cpu_to_node
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:free_area_init_nodes
```
**Symbols:**

```
ffffffff828df635-ffffffff828dfab0: free_area_init_node (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>long unsigned int *zones_size</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int node_start_pfn</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int *zholes_size</code>
</li>
</ul>
</details>
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
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
