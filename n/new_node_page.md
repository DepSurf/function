# Function: <code>new_node_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct page *new_node_page(struct page *page, long unsigned int node, int **x);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff811e0260)
Location: mm/mempolicy.c:939
Inline: True
```
**Symbols:**

```
ffffffff811e0260-ffffffff811e02d6: new_node_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Selective Inline ⚠️</summary>

```c
struct page *new_node_page(struct page *page, long unsigned int node, int **x);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff811fe540)
Location: mm/mempolicy.c:971
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff8120ecd0)
Location: mm/memory_hotplug.c:1553
Inline: False
```
**Symbols:**

```
ffffffff811fe540-ffffffff811fe5b6: new_node_page (STB_LOCAL)
ffffffff8120ecd0-ffffffff8120ee04: new_node_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Selective Inline ⚠️</summary>

```c
struct page *new_node_page(struct page *page, long unsigned int node, int **x);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8120f280)
Location: mm/mempolicy.c:973
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff81220d00)
Location: mm/memory_hotplug.c:1558
Inline: False
```
**Symbols:**

```
ffffffff8120f280-ffffffff8120f2f6: new_node_page (STB_LOCAL)
ffffffff81220d00-ffffffff81220f03: new_node_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Selective Inline ⚠️</summary>

```c
struct page *new_node_page(struct page *page, long unsigned int node, int **x);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8121abc0)
Location: mm/mempolicy.c:901
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff8122c610)
Location: mm/memory_hotplug.c:1371
Inline: False
```
**Symbols:**

```
ffffffff8121abc0-ffffffff8121ac27: new_node_page (STB_LOCAL)
ffffffff8122c610-ffffffff8122c7d3: new_node_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Selective Inline ⚠️</summary>

```c
struct page *new_node_page(struct page *page, long unsigned int node, int **x);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81235d90)
Location: mm/mempolicy.c:945
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff81247df0)
Location: mm/memory_hotplug.c:1359
Inline: False
```
**Symbols:**

```
ffffffff81235d90-ffffffff81235e4a: new_node_page (STB_LOCAL)
ffffffff81247df0-ffffffff81248001: new_node_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct page *new_node_page(struct page *page, long unsigned int private);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff8126b740)
Location: mm/memory_hotplug.c:1369
Inline: False
```
**Symbols:**

```
ffffffff8126b740-ffffffff8126b94d: new_node_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct page *new_node_page(struct page *page, long unsigned int private);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff8127ffd0)
Location: mm/memory_hotplug.c:1349
Inline: False
```
**Symbols:**

```
ffffffff8127ffd0-ffffffff812801e2: new_node_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct page *new_node_page(struct page *page, long unsigned int private);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff8129c000)
Location: mm/memory_hotplug.c:1331
Inline: False
```
**Symbols:**

```
ffffffff8129c000-ffffffff8129c222: new_node_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct page *new_node_page(struct page *page, long unsigned int private);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812ac0b0)
Location: mm/memory_hotplug.c:1306
Inline: False
```
**Symbols:**

```
ffffffff812ac0b0-ffffffff812ac2d2: new_node_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct page *new_node_page(struct page *page, long unsigned int private);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812e0f90)
Location: mm/memory_hotplug.c:1276
Inline: False
```
**Symbols:**

```
ffffffff812e0f90-ffffffff812e11ad: new_node_page (STB_LOCAL)
```
</details>
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
In <code>6.2</code>: Absent ⚠️
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
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct page *new_node_page(struct page *page, long unsigned int private);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (c00000000042d9f0)
Location: mm/memory_hotplug.c:1306
Inline: False
```
**Symbols:**

```
c00000000042d9f0-c00000000042dc00: new_node_page (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct page *new_node_page(struct page *page, long unsigned int private);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812a4690)
Location: mm/memory_hotplug.c:1306
Inline: False
```
**Symbols:**

```
ffffffff812a4690-ffffffff812a48b2: new_node_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct page *new_node_page(struct page *page, long unsigned int private);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81296160)
Location: mm/memory_hotplug.c:1306
Inline: False
```
**Symbols:**

```
ffffffff81296160-ffffffff81296382: new_node_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct page *new_node_page(struct page *page, long unsigned int private);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812a24a0)
Location: mm/memory_hotplug.c:1306
Inline: False
```
**Symbols:**

```
ffffffff812a24a0-ffffffff812a26c2: new_node_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct page *new_node_page(struct page *page, long unsigned int private);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812b2800)
Location: mm/memory_hotplug.c:1306
Inline: False
```
**Symbols:**

```
ffffffff812b2800-ffffffff812b2a22: new_node_page (STB_LOCAL)
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
<code>long unsigned int private</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int node</code>
</li>
<li>
<b>Param removed. </b>
<code>int **x</code>
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
