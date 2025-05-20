# Function: <code>free_area_init_memoryless_node</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void free_area_init_memoryless_node(int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff82cfbf28)
Location: mm/page_alloc.c:6910
Inline: False
Direct callers:
  - arch/x86/mm/numa.c:init_cpu_to_node
```
**Symbols:**

```
ffffffff82cfbf28-ffffffff82cfbf38: free_area_init_memoryless_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void free_area_init_memoryless_node(int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff82fe8948)
Location: mm/page_alloc.c:7140
Inline: False
Direct callers:
  - arch/x86/mm/numa.c:init_gi_nodes
  - arch/x86/mm/numa.c:init_cpu_to_node
```
**Symbols:**

```
ffffffff82fe8948-ffffffff82fe8958: free_area_init_memoryless_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void free_area_init_memoryless_node(int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff831f31f2)
Location: mm/page_alloc.c:7356
Inline: False
Direct callers:
  - arch/x86/mm/numa.c:init_gi_nodes
  - arch/x86/mm/numa.c:init_cpu_to_node
```
**Symbols:**

```
ffffffff831f31f2-ffffffff831f3202: free_area_init_memoryless_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void free_area_init_memoryless_node(int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff832d92e3)
Location: mm/page_alloc.c:7598
Inline: False
Direct callers:
  - arch/x86/mm/numa.c:init_gi_nodes
  - arch/x86/mm/numa.c:init_cpu_to_node
```
**Symbols:**

```
ffffffff832d92e3-ffffffff832d92f3: free_area_init_memoryless_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8348e6d1)
Location: mm/page_alloc.c:7749
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init
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
In mm/page_alloc.c (ffffffff83ec07ba)
Location: mm/page_alloc.c:7934
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
