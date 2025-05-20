# Function: <code>__anon_vma_interval_tree_subtree_search</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct anon_vma_chain *__anon_vma_interval_tree_subtree_search(struct anon_vma_chain *node, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff811b86a0)
Location: mm/interval_tree.c:72
Inline: False
Direct callers:
  - mm/interval_tree.c:anon_vma_interval_tree_iter_first
  - mm/interval_tree.c:anon_vma_interval_tree_iter_next
```
**Symbols:**

```
ffffffff811b86a0-ffffffff811b8705: __anon_vma_interval_tree_subtree_search (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct anon_vma_chain *__anon_vma_interval_tree_subtree_search(struct anon_vma_chain *node, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff811d2940)
Location: mm/interval_tree.c:72
Inline: False
Direct callers:
  - mm/interval_tree.c:anon_vma_interval_tree_iter_next
  - mm/interval_tree.c:anon_vma_interval_tree_iter_first
```
**Symbols:**

```
ffffffff811d2940-ffffffff811d29a5: __anon_vma_interval_tree_subtree_search (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct anon_vma_chain *__anon_vma_interval_tree_subtree_search(struct anon_vma_chain *node, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff811e2800)
Location: mm/interval_tree.c:72
Inline: False
Direct callers:
  - mm/interval_tree.c:anon_vma_interval_tree_iter_next
  - mm/interval_tree.c:anon_vma_interval_tree_iter_first
```
**Symbols:**

```
ffffffff811e2800-ffffffff811e2865: __anon_vma_interval_tree_subtree_search (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct anon_vma_chain *__anon_vma_interval_tree_subtree_search(struct anon_vma_chain *node, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff811ecc50)
Location: mm/interval_tree.c:72
Inline: False
Direct callers:
  - mm/interval_tree.c:anon_vma_interval_tree_iter_next
  - mm/interval_tree.c:anon_vma_interval_tree_iter_first
```
**Symbols:**

```
ffffffff811ecc50-ffffffff811eccae: __anon_vma_interval_tree_subtree_search (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct anon_vma_chain *__anon_vma_interval_tree_subtree_search(struct anon_vma_chain *node, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff81202fc0)
Location: mm/interval_tree.c:72
Inline: False
Direct callers:
  - mm/interval_tree.c:anon_vma_interval_tree_iter_next
  - mm/interval_tree.c:anon_vma_interval_tree_iter_first
```
**Symbols:**

```
ffffffff81202fc0-ffffffff8120301e: __anon_vma_interval_tree_subtree_search (STB_LOCAL)
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
In mm/interval_tree.c (ffffffff8122457d)
Location: mm/interval_tree.c:72
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_iter_next
  - mm/interval_tree.c:anon_vma_interval_tree_iter_first
Direct callers:
  - mm/interval_tree.c:anon_vma_interval_tree_iter_next
  - mm/interval_tree.c:anon_vma_interval_tree_iter_first
```
**Symbols:**

```
ffffffff81223c10-ffffffff81223c7d: __anon_vma_interval_tree_subtree_search.part.8 (STB_LOCAL)
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
In mm/interval_tree.c (ffffffff812375cd)
Location: mm/interval_tree.c:72
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_iter_next
  - mm/interval_tree.c:anon_vma_interval_tree_iter_first
Direct callers:
  - mm/interval_tree.c:anon_vma_interval_tree_iter_next
  - mm/interval_tree.c:anon_vma_interval_tree_iter_first
```
**Symbols:**

```
ffffffff81236cc0-ffffffff81236d23: __anon_vma_interval_tree_subtree_search.part.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct anon_vma_chain *__anon_vma_interval_tree_subtree_search(struct anon_vma_chain *node, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff81248210)
Location: mm/interval_tree.c:71
Inline: False
Direct callers:
  - mm/interval_tree.c:anon_vma_interval_tree_iter_next
  - mm/interval_tree.c:anon_vma_interval_tree_iter_first
```
**Symbols:**

```
ffffffff81248210-ffffffff81248273: __anon_vma_interval_tree_subtree_search (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct anon_vma_chain *__anon_vma_interval_tree_subtree_search(struct anon_vma_chain *node, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff81256610)
Location: mm/interval_tree.c:71
Inline: False
Direct callers:
  - mm/interval_tree.c:anon_vma_interval_tree_iter_next
  - mm/interval_tree.c:anon_vma_interval_tree_iter_first
```
**Symbols:**

```
ffffffff81256610-ffffffff81256673: __anon_vma_interval_tree_subtree_search (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct anon_vma_chain *__anon_vma_interval_tree_subtree_search(struct anon_vma_chain *node, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff81284d20)
Location: mm/interval_tree.c:71
Inline: False
Direct callers:
  - mm/interval_tree.c:anon_vma_interval_tree_iter_next
  - mm/interval_tree.c:anon_vma_interval_tree_iter_first
```
**Symbols:**

```
ffffffff81284d20-ffffffff81284d86: __anon_vma_interval_tree_subtree_search (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct anon_vma_chain *__anon_vma_interval_tree_subtree_search(struct anon_vma_chain *node, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff8128f000)
Location: mm/interval_tree.c:71
Inline: False
Direct callers:
  - mm/interval_tree.c:anon_vma_interval_tree_iter_next
  - mm/interval_tree.c:anon_vma_interval_tree_iter_first
```
**Symbols:**

```
ffffffff8128f000-ffffffff8128f066: __anon_vma_interval_tree_subtree_search (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct anon_vma_chain *__anon_vma_interval_tree_subtree_search(struct anon_vma_chain *node, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff81294670)
Location: mm/interval_tree.c:71
Inline: False
Direct callers:
  - mm/interval_tree.c:anon_vma_interval_tree_iter_next
  - mm/interval_tree.c:anon_vma_interval_tree_iter_first
```
**Symbols:**

```
ffffffff81294670-ffffffff812946d3: __anon_vma_interval_tree_subtree_search (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct anon_vma_chain *__anon_vma_interval_tree_subtree_search(struct anon_vma_chain *node, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff812d4cd0)
Location: mm/interval_tree.c:71
Inline: False
Direct callers:
  - mm/interval_tree.c:anon_vma_interval_tree_iter_next
  - mm/interval_tree.c:anon_vma_interval_tree_iter_first
```
**Symbols:**

```
ffffffff812d4cd0-ffffffff812d4d33: __anon_vma_interval_tree_subtree_search (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct anon_vma_chain *__anon_vma_interval_tree_subtree_search(struct anon_vma_chain *node, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff81333da0)
Location: mm/interval_tree.c:71
Inline: False
Direct callers:
  - mm/interval_tree.c:anon_vma_interval_tree_iter_next
  - mm/interval_tree.c:anon_vma_interval_tree_iter_first
```
**Symbols:**

```
ffffffff81333da0-ffffffff81333e21: __anon_vma_interval_tree_subtree_search (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct anon_vma_chain *__anon_vma_interval_tree_subtree_search(struct anon_vma_chain *node, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff813aaa20)
Location: mm/interval_tree.c:71
Inline: False
Direct callers:
  - mm/interval_tree.c:anon_vma_interval_tree_iter_next
  - mm/interval_tree.c:anon_vma_interval_tree_iter_first
```
**Symbols:**

```
ffffffff813aaa20-ffffffff813aaa9e: __anon_vma_interval_tree_subtree_search (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct anon_vma_chain *__anon_vma_interval_tree_subtree_search(struct anon_vma_chain *node, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff813dede0)
Location: mm/interval_tree.c:71
Inline: False
Direct callers:
  - mm/interval_tree.c:anon_vma_interval_tree_iter_next
  - mm/interval_tree.c:anon_vma_interval_tree_iter_first
```
**Symbols:**

```
ffffffff813dede0-ffffffff813dee61: __anon_vma_interval_tree_subtree_search (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct anon_vma_chain *__anon_vma_interval_tree_subtree_search(struct anon_vma_chain *node, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff814094f0)
Location: mm/interval_tree.c:71
Inline: False
Direct callers:
  - mm/interval_tree.c:anon_vma_interval_tree_iter_next
  - mm/interval_tree.c:anon_vma_interval_tree_iter_first
```
**Symbols:**

```
ffffffff814094f0-ffffffff81409571: __anon_vma_interval_tree_subtree_search (STB_LOCAL)
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
struct anon_vma_chain *__anon_vma_interval_tree_subtree_search(struct anon_vma_chain *node, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffff8000102eddd8)
Location: mm/interval_tree.c:71
Inline: False
Direct callers:
  - mm/interval_tree.c:anon_vma_interval_tree_iter_next
  - mm/interval_tree.c:anon_vma_interval_tree_iter_first
```
**Symbols:**

```
ffff8000102eddd8-ffff8000102ede7c: __anon_vma_interval_tree_subtree_search (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct anon_vma_chain *__anon_vma_interval_tree_subtree_search(struct anon_vma_chain *node, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (c0511cb4)
Location: mm/interval_tree.c:71
Inline: False
Direct callers:
  - mm/interval_tree.c:anon_vma_interval_tree_iter_next
  - mm/interval_tree.c:anon_vma_interval_tree_iter_first
```
**Symbols:**

```
c0511cb4-c0511d40: __anon_vma_interval_tree_subtree_search (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct anon_vma_chain *__anon_vma_interval_tree_subtree_search(struct anon_vma_chain *node, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (c0000000003b1d30)
Location: mm/interval_tree.c:71
Inline: False
Direct callers:
  - mm/interval_tree.c:anon_vma_interval_tree_iter_next
  - mm/interval_tree.c:anon_vma_interval_tree_iter_first
```
**Symbols:**

```
c0000000003b1d30-c0000000003b1dc8: __anon_vma_interval_tree_subtree_search (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct anon_vma_chain *__anon_vma_interval_tree_subtree_search(struct anon_vma_chain *node, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffe000202198)
Location: mm/interval_tree.c:71
Inline: False
Direct callers:
  - mm/interval_tree.c:anon_vma_interval_tree_iter_next
  - mm/interval_tree.c:anon_vma_interval_tree_iter_first
```
**Symbols:**

```
ffffffe000202198-ffffffe000202202: __anon_vma_interval_tree_subtree_search (STB_LOCAL)
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
struct anon_vma_chain *__anon_vma_interval_tree_subtree_search(struct anon_vma_chain *node, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff8124ec60)
Location: mm/interval_tree.c:71
Inline: False
Direct callers:
  - mm/interval_tree.c:anon_vma_interval_tree_iter_next
  - mm/interval_tree.c:anon_vma_interval_tree_iter_first
```
**Symbols:**

```
ffffffff8124ec60-ffffffff8124ecc3: __anon_vma_interval_tree_subtree_search (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct anon_vma_chain *__anon_vma_interval_tree_subtree_search(struct anon_vma_chain *node, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff81241c00)
Location: mm/interval_tree.c:71
Inline: False
Direct callers:
  - mm/interval_tree.c:anon_vma_interval_tree_iter_next
  - mm/interval_tree.c:anon_vma_interval_tree_iter_first
```
**Symbols:**

```
ffffffff81241c00-ffffffff81241c63: __anon_vma_interval_tree_subtree_search (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct anon_vma_chain *__anon_vma_interval_tree_subtree_search(struct anon_vma_chain *node, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff8124ca00)
Location: mm/interval_tree.c:71
Inline: False
Direct callers:
  - mm/interval_tree.c:anon_vma_interval_tree_iter_next
  - mm/interval_tree.c:anon_vma_interval_tree_iter_first
```
**Symbols:**

```
ffffffff8124ca00-ffffffff8124ca63: __anon_vma_interval_tree_subtree_search (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct anon_vma_chain *__anon_vma_interval_tree_subtree_search(struct anon_vma_chain *node, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff8125c3c0)
Location: mm/interval_tree.c:71
Inline: False
Direct callers:
  - mm/interval_tree.c:anon_vma_interval_tree_iter_next
  - mm/interval_tree.c:anon_vma_interval_tree_iter_first
```
**Symbols:**

```
ffffffff8125c3c0-ffffffff8125c423: __anon_vma_interval_tree_subtree_search (STB_LOCAL)
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
