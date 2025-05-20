# Function: <code>anon_vma_interval_tree_iter_next</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct anon_vma_chain *anon_vma_interval_tree_iter_next(struct anon_vma_chain *node, long unsigned int first, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff811b8e10)
Location: mm/interval_tree.c:100
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk
  - mm/ksm.c:rmap_walk_ksm
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/memory-failure.c:memory_failure
```
**Symbols:**

```
ffffffff811b8e10-ffffffff811b8e7c: anon_vma_interval_tree_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct anon_vma_chain *anon_vma_interval_tree_iter_next(struct anon_vma_chain *node, long unsigned int first, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff811d30b0)
Location: mm/interval_tree.c:100
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/ksm.c:rmap_walk_ksm
  - mm/memory-failure.c:memory_failure
```
**Symbols:**

```
ffffffff811d30b0-ffffffff811d311c: anon_vma_interval_tree_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct anon_vma_chain *anon_vma_interval_tree_iter_next(struct anon_vma_chain *node, long unsigned int first, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff811e2f70)
Location: mm/interval_tree.c:100
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/ksm.c:rmap_walk_ksm
  - mm/memory-failure.c:memory_failure
```
**Symbols:**

```
ffffffff811e2f70-ffffffff811e2fdc: anon_vma_interval_tree_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct anon_vma_chain *anon_vma_interval_tree_iter_next(struct anon_vma_chain *node, long unsigned int first, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff811ed410)
Location: mm/interval_tree.c:100
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/ksm.c:rmap_walk_ksm
```
**Symbols:**

```
ffffffff811ed410-ffffffff811ed47c: anon_vma_interval_tree_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct anon_vma_chain *anon_vma_interval_tree_iter_next(struct anon_vma_chain *node, long unsigned int first, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff81203860)
Location: mm/interval_tree.c:100
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/ksm.c:rmap_walk_ksm
```
**Symbols:**

```
ffffffff81203860-ffffffff812038cc: anon_vma_interval_tree_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct anon_vma_chain *anon_vma_interval_tree_iter_next(struct anon_vma_chain *node, long unsigned int first, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff81224520)
Location: mm/interval_tree.c:100
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/ksm.c:rmap_walk_ksm
  - mm/memory-failure.c:collect_procs
```
**Symbols:**

```
ffffffff81224520-ffffffff8122458c: anon_vma_interval_tree_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct anon_vma_chain *anon_vma_interval_tree_iter_next(struct anon_vma_chain *node, long unsigned int first, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff81237570)
Location: mm/interval_tree.c:100
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/ksm.c:rmap_walk_ksm
  - mm/memory-failure.c:collect_procs
```
**Symbols:**

```
ffffffff81237570-ffffffff812375dc: anon_vma_interval_tree_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct anon_vma_chain *anon_vma_interval_tree_iter_next(struct anon_vma_chain *node, long unsigned int first, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff81248b20)
Location: mm/interval_tree.c:99
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/ksm.c:rmap_walk_ksm
  - mm/memory-failure.c:collect_procs
```
**Symbols:**

```
ffffffff81248b20-ffffffff81248b8c: anon_vma_interval_tree_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct anon_vma_chain *anon_vma_interval_tree_iter_next(struct anon_vma_chain *node, long unsigned int first, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff81256f70)
Location: mm/interval_tree.c:99
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/ksm.c:rmap_walk_ksm
  - mm/memory-failure.c:collect_procs
```
**Symbols:**

```
ffffffff81256f70-ffffffff81256fdc: anon_vma_interval_tree_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct anon_vma_chain *anon_vma_interval_tree_iter_next(struct anon_vma_chain *node, long unsigned int first, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff81285640)
Location: mm/interval_tree.c:99
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/ksm.c:rmap_walk_ksm
  - mm/memory-failure.c:collect_procs_anon
```
**Symbols:**

```
ffffffff81285640-ffffffff812856b2: anon_vma_interval_tree_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct anon_vma_chain *anon_vma_interval_tree_iter_next(struct anon_vma_chain *node, long unsigned int first, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff8128f920)
Location: mm/interval_tree.c:99
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/ksm.c:rmap_walk_ksm
  - mm/memory-failure.c:collect_procs_anon
```
**Symbols:**

```
ffffffff8128f920-ffffffff8128f992: anon_vma_interval_tree_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct anon_vma_chain *anon_vma_interval_tree_iter_next(struct anon_vma_chain *node, long unsigned int first, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff81294f80)
Location: mm/interval_tree.c:99
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/ksm.c:rmap_walk_ksm
  - mm/memory-failure.c:collect_procs
```
**Symbols:**

```
ffffffff81294f80-ffffffff81294ff5: anon_vma_interval_tree_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct anon_vma_chain *anon_vma_interval_tree_iter_next(struct anon_vma_chain *node, long unsigned int first, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff812d55e0)
Location: mm/interval_tree.c:99
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/ksm.c:rmap_walk_ksm
  - mm/memory-failure.c:collect_procs
```
**Symbols:**

```
ffffffff812d55e0-ffffffff812d5655: anon_vma_interval_tree_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct anon_vma_chain *anon_vma_interval_tree_iter_next(struct anon_vma_chain *node, long unsigned int first, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff81334830)
Location: mm/interval_tree.c:99
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/ksm.c:rmap_walk_ksm
```
**Symbols:**

```
ffffffff81334830-ffffffff813348df: anon_vma_interval_tree_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct anon_vma_chain *anon_vma_interval_tree_iter_next(struct anon_vma_chain *node, long unsigned int first, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff813ab520)
Location: mm/interval_tree.c:99
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/ksm.c:rmap_walk_ksm
```
**Symbols:**

```
ffffffff813ab520-ffffffff813ab5cc: anon_vma_interval_tree_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct anon_vma_chain *anon_vma_interval_tree_iter_next(struct anon_vma_chain *node, long unsigned int first, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff813df8c0)
Location: mm/interval_tree.c:99
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/ksm.c:collect_procs_ksm
  - mm/ksm.c:rmap_walk_ksm
  - mm/memory-failure.c:collect_procs_anon
```
**Symbols:**

```
ffffffff813df8c0-ffffffff813df96f: anon_vma_interval_tree_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct anon_vma_chain *anon_vma_interval_tree_iter_next(struct anon_vma_chain *node, long unsigned int first, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff81409fd0)
Location: mm/interval_tree.c:99
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/ksm.c:collect_procs_ksm
  - mm/ksm.c:rmap_walk_ksm
  - mm/memory-failure.c:collect_procs_anon
```
**Symbols:**

```
ffffffff81409fd0-ffffffff8140a07f: anon_vma_interval_tree_iter_next (STB_GLOBAL)
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
struct anon_vma_chain *anon_vma_interval_tree_iter_next(struct anon_vma_chain *node, long unsigned int first, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffff8000102ee890)
Location: mm/interval_tree.c:99
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/ksm.c:rmap_walk_ksm
```
**Symbols:**

```
ffff8000102ee890-ffff8000102ee944: anon_vma_interval_tree_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct anon_vma_chain *anon_vma_interval_tree_iter_next(struct anon_vma_chain *node, long unsigned int first, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (c05126a4)
Location: mm/interval_tree.c:99
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/ksm.c:rmap_walk_ksm
```
**Symbols:**

```
c05126a4-c051273c: anon_vma_interval_tree_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct anon_vma_chain *anon_vma_interval_tree_iter_next(struct anon_vma_chain *node, long unsigned int first, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (c0000000003b2ab0)
Location: mm/interval_tree.c:99
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/ksm.c:rmap_walk_ksm
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
```
**Symbols:**

```
c0000000003b2ab0-c0000000003b2b58: anon_vma_interval_tree_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct anon_vma_chain *anon_vma_interval_tree_iter_next(struct anon_vma_chain *node, long unsigned int first, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffe0002028d0)
Location: mm/interval_tree.c:99
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/ksm.c:rmap_walk_ksm
```
**Symbols:**

```
ffffffe0002028d0-ffffffe00020294c: anon_vma_interval_tree_iter_next (STB_GLOBAL)
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
struct anon_vma_chain *anon_vma_interval_tree_iter_next(struct anon_vma_chain *node, long unsigned int first, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff8124f5c0)
Location: mm/interval_tree.c:99
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/ksm.c:rmap_walk_ksm
  - mm/memory-failure.c:collect_procs
```
**Symbols:**

```
ffffffff8124f5c0-ffffffff8124f62c: anon_vma_interval_tree_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct anon_vma_chain *anon_vma_interval_tree_iter_next(struct anon_vma_chain *node, long unsigned int first, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff81242560)
Location: mm/interval_tree.c:99
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/ksm.c:rmap_walk_ksm
  - mm/memory-failure.c:collect_procs
```
**Symbols:**

```
ffffffff81242560-ffffffff812425cc: anon_vma_interval_tree_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct anon_vma_chain *anon_vma_interval_tree_iter_next(struct anon_vma_chain *node, long unsigned int first, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff8124d360)
Location: mm/interval_tree.c:99
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/ksm.c:rmap_walk_ksm
  - mm/memory-failure.c:collect_procs
```
**Symbols:**

```
ffffffff8124d360-ffffffff8124d3cc: anon_vma_interval_tree_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct anon_vma_chain *anon_vma_interval_tree_iter_next(struct anon_vma_chain *node, long unsigned int first, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff8125cd20)
Location: mm/interval_tree.c:99
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/ksm.c:rmap_walk_ksm
  - mm/memory-failure.c:collect_procs
```
**Symbols:**

```
ffffffff8125cd20-ffffffff8125cd8c: anon_vma_interval_tree_iter_next (STB_GLOBAL)
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
