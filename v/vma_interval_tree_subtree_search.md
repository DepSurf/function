# Function: <code>vma_interval_tree_subtree_search</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct vm_area_struct *vma_interval_tree_subtree_search(struct vm_area_struct *node, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff811b85d0)
Location: mm/interval_tree.c:24
Inline: False
Direct callers:
  - mm/interval_tree.c:vma_interval_tree_iter_first
  - mm/interval_tree.c:vma_interval_tree_iter_next
```
**Symbols:**

```
ffffffff811b85d0-ffffffff811b8632: vma_interval_tree_subtree_search (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct vm_area_struct *vma_interval_tree_subtree_search(struct vm_area_struct *node, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff811d2870)
Location: mm/interval_tree.c:24
Inline: False
Direct callers:
  - mm/interval_tree.c:vma_interval_tree_iter_next
  - mm/interval_tree.c:vma_interval_tree_iter_first
```
**Symbols:**

```
ffffffff811d2870-ffffffff811d28d2: vma_interval_tree_subtree_search (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct vm_area_struct *vma_interval_tree_subtree_search(struct vm_area_struct *node, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff811e2730)
Location: mm/interval_tree.c:24
Inline: False
Direct callers:
  - mm/interval_tree.c:vma_interval_tree_iter_next
  - mm/interval_tree.c:vma_interval_tree_iter_first
```
**Symbols:**

```
ffffffff811e2730-ffffffff811e2792: vma_interval_tree_subtree_search (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct vm_area_struct *vma_interval_tree_subtree_search(struct vm_area_struct *node, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff811ecb90)
Location: mm/interval_tree.c:24
Inline: False
Direct callers:
  - mm/interval_tree.c:vma_interval_tree_iter_next
  - mm/interval_tree.c:vma_interval_tree_iter_first
```
**Symbols:**

```
ffffffff811ecb90-ffffffff811ecbeb: vma_interval_tree_subtree_search (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct vm_area_struct *vma_interval_tree_subtree_search(struct vm_area_struct *node, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff81202f00)
Location: mm/interval_tree.c:24
Inline: False
Direct callers:
  - mm/interval_tree.c:vma_interval_tree_iter_next
  - mm/interval_tree.c:vma_interval_tree_iter_first
```
**Symbols:**

```
ffffffff81202f00-ffffffff81202f5b: vma_interval_tree_subtree_search (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/interval_tree.c (ffffffff812240ca)
Location: mm/interval_tree.c:24
Inline: True
Inline callers:
  - mm/interval_tree.c:vma_interval_tree_iter_next
  - mm/interval_tree.c:vma_interval_tree_iter_first
Direct callers:
  - mm/interval_tree.c:vma_interval_tree_iter_next
  - mm/interval_tree.c:vma_interval_tree_iter_first
```
**Symbols:**

```
ffffffff81223ba0-ffffffff81223c0a: vma_interval_tree_subtree_search.part.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/interval_tree.c (ffffffff8123710a)
Location: mm/interval_tree.c:24
Inline: True
Inline callers:
  - mm/interval_tree.c:vma_interval_tree_iter_next
  - mm/interval_tree.c:vma_interval_tree_iter_first
Direct callers:
  - mm/interval_tree.c:vma_interval_tree_iter_next
  - mm/interval_tree.c:vma_interval_tree_iter_first
```
**Symbols:**

```
ffffffff81236c60-ffffffff81236cc0: vma_interval_tree_subtree_search.part.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct vm_area_struct *vma_interval_tree_subtree_search(struct vm_area_struct *node, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff81248150)
Location: mm/interval_tree.c:23
Inline: False
Direct callers:
  - mm/interval_tree.c:vma_interval_tree_iter_next
  - mm/interval_tree.c:vma_interval_tree_iter_first
```
**Symbols:**

```
ffffffff81248150-ffffffff812481b0: vma_interval_tree_subtree_search (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct vm_area_struct *vma_interval_tree_subtree_search(struct vm_area_struct *node, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff81256550)
Location: mm/interval_tree.c:23
Inline: False
Direct callers:
  - mm/interval_tree.c:vma_interval_tree_iter_next
  - mm/interval_tree.c:vma_interval_tree_iter_first
```
**Symbols:**

```
ffffffff81256550-ffffffff812565b0: vma_interval_tree_subtree_search (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct vm_area_struct *vma_interval_tree_subtree_search(struct vm_area_struct *node, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff81284c50)
Location: mm/interval_tree.c:23
Inline: False
Direct callers:
  - mm/interval_tree.c:vma_interval_tree_iter_next
  - mm/interval_tree.c:vma_interval_tree_iter_first
```
**Symbols:**

```
ffffffff81284c50-ffffffff81284cb3: vma_interval_tree_subtree_search (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct vm_area_struct *vma_interval_tree_subtree_search(struct vm_area_struct *node, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff8128ef30)
Location: mm/interval_tree.c:23
Inline: False
Direct callers:
  - mm/interval_tree.c:vma_interval_tree_iter_next
  - mm/interval_tree.c:vma_interval_tree_iter_first
```
**Symbols:**

```
ffffffff8128ef30-ffffffff8128ef93: vma_interval_tree_subtree_search (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct vm_area_struct *vma_interval_tree_subtree_search(struct vm_area_struct *node, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff812945b0)
Location: mm/interval_tree.c:23
Inline: False
Direct callers:
  - mm/interval_tree.c:vma_interval_tree_iter_next
  - mm/interval_tree.c:vma_interval_tree_iter_first
```
**Symbols:**

```
ffffffff812945b0-ffffffff81294610: vma_interval_tree_subtree_search (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct vm_area_struct *vma_interval_tree_subtree_search(struct vm_area_struct *node, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff812d4c10)
Location: mm/interval_tree.c:23
Inline: False
Direct callers:
  - mm/interval_tree.c:vma_interval_tree_iter_next
  - mm/interval_tree.c:vma_interval_tree_iter_first
```
**Symbols:**

```
ffffffff812d4c10-ffffffff812d4c70: vma_interval_tree_subtree_search (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct vm_area_struct *vma_interval_tree_subtree_search(struct vm_area_struct *node, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff81333cb0)
Location: mm/interval_tree.c:23
Inline: False
Direct callers:
  - mm/interval_tree.c:vma_interval_tree_iter_next
  - mm/interval_tree.c:vma_interval_tree_iter_first
```
**Symbols:**

```
ffffffff81333cb0-ffffffff81333d28: vma_interval_tree_subtree_search (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct vm_area_struct *vma_interval_tree_subtree_search(struct vm_area_struct *node, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff813aa910)
Location: mm/interval_tree.c:23
Inline: False
Direct callers:
  - mm/interval_tree.c:vma_interval_tree_iter_next
  - mm/interval_tree.c:vma_interval_tree_iter_first
```
**Symbols:**

```
ffffffff813aa910-ffffffff813aa985: vma_interval_tree_subtree_search (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct vm_area_struct *vma_interval_tree_subtree_search(struct vm_area_struct *node, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff813decd0)
Location: mm/interval_tree.c:23
Inline: False
Direct callers:
  - mm/interval_tree.c:vma_interval_tree_iter_next
  - mm/interval_tree.c:vma_interval_tree_iter_first
```
**Symbols:**

```
ffffffff813decd0-ffffffff813ded48: vma_interval_tree_subtree_search (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct vm_area_struct *vma_interval_tree_subtree_search(struct vm_area_struct *node, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff814093e0)
Location: mm/interval_tree.c:23
Inline: False
Direct callers:
  - mm/interval_tree.c:vma_interval_tree_iter_next
  - mm/interval_tree.c:vma_interval_tree_iter_first
```
**Symbols:**

```
ffffffff814093e0-ffffffff81409458: vma_interval_tree_subtree_search (STB_LOCAL)
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
struct vm_area_struct *vma_interval_tree_subtree_search(struct vm_area_struct *node, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffff8000102edcc0)
Location: mm/interval_tree.c:23
Inline: False
Direct callers:
  - mm/interval_tree.c:vma_interval_tree_iter_next
  - mm/interval_tree.c:vma_interval_tree_iter_first
```
**Symbols:**

```
ffff8000102edcc0-ffff8000102edd60: vma_interval_tree_subtree_search (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct vm_area_struct *vma_interval_tree_subtree_search(struct vm_area_struct *node, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (c0511bb8)
Location: mm/interval_tree.c:23
Inline: False
Direct callers:
  - mm/interval_tree.c:vma_interval_tree_iter_next
  - mm/interval_tree.c:vma_interval_tree_iter_first
```
**Symbols:**

```
c0511bb8-c0511c44: vma_interval_tree_subtree_search (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct vm_area_struct *vma_interval_tree_subtree_search(struct vm_area_struct *node, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (c0000000003b1c00)
Location: mm/interval_tree.c:23
Inline: False
Direct callers:
  - mm/interval_tree.c:vma_interval_tree_iter_next
  - mm/interval_tree.c:vma_interval_tree_iter_first
```
**Symbols:**

```
c0000000003b1c00-c0000000003b1c98: vma_interval_tree_subtree_search (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct vm_area_struct *vma_interval_tree_subtree_search(struct vm_area_struct *node, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffe0002020c8)
Location: mm/interval_tree.c:23
Inline: False
Direct callers:
  - mm/interval_tree.c:vma_interval_tree_iter_next
  - mm/interval_tree.c:vma_interval_tree_iter_first
```
**Symbols:**

```
ffffffe0002020c8-ffffffe000202130: vma_interval_tree_subtree_search (STB_LOCAL)
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
struct vm_area_struct *vma_interval_tree_subtree_search(struct vm_area_struct *node, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff8124eba0)
Location: mm/interval_tree.c:23
Inline: False
Direct callers:
  - mm/interval_tree.c:vma_interval_tree_iter_next
  - mm/interval_tree.c:vma_interval_tree_iter_first
```
**Symbols:**

```
ffffffff8124eba0-ffffffff8124ec00: vma_interval_tree_subtree_search (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct vm_area_struct *vma_interval_tree_subtree_search(struct vm_area_struct *node, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff81241b40)
Location: mm/interval_tree.c:23
Inline: False
Direct callers:
  - mm/interval_tree.c:vma_interval_tree_iter_next
  - mm/interval_tree.c:vma_interval_tree_iter_first
```
**Symbols:**

```
ffffffff81241b40-ffffffff81241ba0: vma_interval_tree_subtree_search (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct vm_area_struct *vma_interval_tree_subtree_search(struct vm_area_struct *node, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff8124c940)
Location: mm/interval_tree.c:23
Inline: False
Direct callers:
  - mm/interval_tree.c:vma_interval_tree_iter_next
  - mm/interval_tree.c:vma_interval_tree_iter_first
```
**Symbols:**

```
ffffffff8124c940-ffffffff8124c9a0: vma_interval_tree_subtree_search (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct vm_area_struct *vma_interval_tree_subtree_search(struct vm_area_struct *node, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff8125c300)
Location: mm/interval_tree.c:23
Inline: False
Direct callers:
  - mm/interval_tree.c:vma_interval_tree_iter_next
  - mm/interval_tree.c:vma_interval_tree_iter_first
```
**Symbols:**

```
ffffffff8125c300-ffffffff8125c360: vma_interval_tree_subtree_search (STB_LOCAL)
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
