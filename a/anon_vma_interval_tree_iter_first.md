# Function: <code>anon_vma_interval_tree_iter_first</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct anon_vma_chain *anon_vma_interval_tree_iter_first(struct rb_root *root, long unsigned int first, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff811b8de0)
Location: mm/interval_tree.c:93
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
ffffffff811b8de0-ffffffff811b8e08: anon_vma_interval_tree_iter_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct anon_vma_chain *anon_vma_interval_tree_iter_first(struct rb_root *root, long unsigned int first, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff811d3080)
Location: mm/interval_tree.c:93
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/ksm.c:rmap_walk_ksm
  - mm/memory-failure.c:memory_failure
```
**Symbols:**

```
ffffffff811d3080-ffffffff811d30a8: anon_vma_interval_tree_iter_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct anon_vma_chain *anon_vma_interval_tree_iter_first(struct rb_root *root, long unsigned int first, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff811e2f40)
Location: mm/interval_tree.c:93
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/ksm.c:rmap_walk_ksm
  - mm/memory-failure.c:memory_failure
```
**Symbols:**

```
ffffffff811e2f40-ffffffff811e2f68: anon_vma_interval_tree_iter_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct anon_vma_chain *anon_vma_interval_tree_iter_first(struct rb_root *root, long unsigned int first, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff811ed3e0)
Location: mm/interval_tree.c:93
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/ksm.c:rmap_walk_ksm
```
**Symbols:**

```
ffffffff811ed3e0-ffffffff811ed405: anon_vma_interval_tree_iter_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct anon_vma_chain *anon_vma_interval_tree_iter_first(struct rb_root_cached *root, long unsigned int first, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff81203820)
Location: mm/interval_tree.c:93
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/ksm.c:rmap_walk_ksm
```
**Symbols:**

```
ffffffff81203820-ffffffff81203859: anon_vma_interval_tree_iter_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct anon_vma_chain *anon_vma_interval_tree_iter_first(struct rb_root_cached *root, long unsigned int first, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff812244e0)
Location: mm/interval_tree.c:93
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/ksm.c:rmap_walk_ksm
  - mm/memory-failure.c:collect_procs
```
**Symbols:**

```
ffffffff812244e0-ffffffff81224519: anon_vma_interval_tree_iter_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct anon_vma_chain *anon_vma_interval_tree_iter_first(struct rb_root_cached *root, long unsigned int first, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff81237530)
Location: mm/interval_tree.c:93
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/ksm.c:rmap_walk_ksm
  - mm/memory-failure.c:collect_procs
```
**Symbols:**

```
ffffffff81237530-ffffffff81237567: anon_vma_interval_tree_iter_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct anon_vma_chain *anon_vma_interval_tree_iter_first(struct rb_root_cached *root, long unsigned int first, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff81248ae0)
Location: mm/interval_tree.c:92
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/ksm.c:rmap_walk_ksm
  - mm/memory-failure.c:collect_procs
```
**Symbols:**

```
ffffffff81248ae0-ffffffff81248b17: anon_vma_interval_tree_iter_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct anon_vma_chain *anon_vma_interval_tree_iter_first(struct rb_root_cached *root, long unsigned int first, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff81256f30)
Location: mm/interval_tree.c:92
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/ksm.c:rmap_walk_ksm
  - mm/memory-failure.c:collect_procs
```
**Symbols:**

```
ffffffff81256f30-ffffffff81256f67: anon_vma_interval_tree_iter_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct anon_vma_chain *anon_vma_interval_tree_iter_first(struct rb_root_cached *root, long unsigned int first, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff81285600)
Location: mm/interval_tree.c:92
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/ksm.c:rmap_walk_ksm
  - mm/memory-failure.c:collect_procs_anon
```
**Symbols:**

```
ffffffff81285600-ffffffff81285637: anon_vma_interval_tree_iter_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct anon_vma_chain *anon_vma_interval_tree_iter_first(struct rb_root_cached *root, long unsigned int first, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff8128f8e0)
Location: mm/interval_tree.c:92
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/ksm.c:rmap_walk_ksm
  - mm/memory-failure.c:collect_procs_anon
```
**Symbols:**

```
ffffffff8128f8e0-ffffffff8128f917: anon_vma_interval_tree_iter_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct anon_vma_chain *anon_vma_interval_tree_iter_first(struct rb_root_cached *root, long unsigned int first, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff81294f40)
Location: mm/interval_tree.c:92
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/ksm.c:rmap_walk_ksm
  - mm/memory-failure.c:collect_procs
```
**Symbols:**

```
ffffffff81294f40-ffffffff81294f77: anon_vma_interval_tree_iter_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct anon_vma_chain *anon_vma_interval_tree_iter_first(struct rb_root_cached *root, long unsigned int first, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff812d55a0)
Location: mm/interval_tree.c:92
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/ksm.c:rmap_walk_ksm
  - mm/memory-failure.c:collect_procs
```
**Symbols:**

```
ffffffff812d55a0-ffffffff812d55d7: anon_vma_interval_tree_iter_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct anon_vma_chain *anon_vma_interval_tree_iter_first(struct rb_root_cached *root, long unsigned int first, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff813347d0)
Location: mm/interval_tree.c:92
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/ksm.c:rmap_walk_ksm
```
**Symbols:**

```
ffffffff813347d0-ffffffff8133482b: anon_vma_interval_tree_iter_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct anon_vma_chain *anon_vma_interval_tree_iter_first(struct rb_root_cached *root, long unsigned int first, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff813ab4b0)
Location: mm/interval_tree.c:92
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/ksm.c:rmap_walk_ksm
```
**Symbols:**

```
ffffffff813ab4b0-ffffffff813ab508: anon_vma_interval_tree_iter_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct anon_vma_chain *anon_vma_interval_tree_iter_first(struct rb_root_cached *root, long unsigned int first, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff813df850)
Location: mm/interval_tree.c:92
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/ksm.c:collect_procs_ksm
  - mm/ksm.c:rmap_walk_ksm
  - mm/memory-failure.c:collect_procs_anon
```
**Symbols:**

```
ffffffff813df850-ffffffff813df8ab: anon_vma_interval_tree_iter_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct anon_vma_chain *anon_vma_interval_tree_iter_first(struct rb_root_cached *root, long unsigned int first, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff81409f60)
Location: mm/interval_tree.c:92
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/ksm.c:collect_procs_ksm
  - mm/ksm.c:rmap_walk_ksm
  - mm/memory-failure.c:collect_procs_anon
```
**Symbols:**

```
ffffffff81409f60-ffffffff81409fbb: anon_vma_interval_tree_iter_first (STB_GLOBAL)
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
struct anon_vma_chain *anon_vma_interval_tree_iter_first(struct rb_root_cached *root, long unsigned int first, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffff8000102ee808)
Location: mm/interval_tree.c:92
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/ksm.c:rmap_walk_ksm
```
**Symbols:**

```
ffff8000102ee808-ffff8000102ee890: anon_vma_interval_tree_iter_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct anon_vma_chain *anon_vma_interval_tree_iter_first(struct rb_root_cached *root, long unsigned int first, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (c0512648)
Location: mm/interval_tree.c:92
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/ksm.c:rmap_walk_ksm
```
**Symbols:**

```
c0512648-c05126a4: anon_vma_interval_tree_iter_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct anon_vma_chain *anon_vma_interval_tree_iter_first(struct rb_root_cached *root, long unsigned int first, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (c0000000003b2a50)
Location: mm/interval_tree.c:92
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/ksm.c:rmap_walk_ksm
  - mm/memory-failure.c:collect_procs
```
**Symbols:**

```
c0000000003b2a50-c0000000003b2aa8: anon_vma_interval_tree_iter_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct anon_vma_chain *anon_vma_interval_tree_iter_first(struct rb_root_cached *root, long unsigned int first, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffe000202870)
Location: mm/interval_tree.c:92
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/ksm.c:rmap_walk_ksm
```
**Symbols:**

```
ffffffe000202870-ffffffe0002028d0: anon_vma_interval_tree_iter_first (STB_GLOBAL)
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
struct anon_vma_chain *anon_vma_interval_tree_iter_first(struct rb_root_cached *root, long unsigned int first, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff8124f580)
Location: mm/interval_tree.c:92
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/ksm.c:rmap_walk_ksm
  - mm/memory-failure.c:collect_procs
```
**Symbols:**

```
ffffffff8124f580-ffffffff8124f5b7: anon_vma_interval_tree_iter_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct anon_vma_chain *anon_vma_interval_tree_iter_first(struct rb_root_cached *root, long unsigned int first, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff81242520)
Location: mm/interval_tree.c:92
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/ksm.c:rmap_walk_ksm
  - mm/memory-failure.c:collect_procs
```
**Symbols:**

```
ffffffff81242520-ffffffff81242557: anon_vma_interval_tree_iter_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct anon_vma_chain *anon_vma_interval_tree_iter_first(struct rb_root_cached *root, long unsigned int first, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff8124d320)
Location: mm/interval_tree.c:92
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/ksm.c:rmap_walk_ksm
  - mm/memory-failure.c:collect_procs
```
**Symbols:**

```
ffffffff8124d320-ffffffff8124d357: anon_vma_interval_tree_iter_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct anon_vma_chain *anon_vma_interval_tree_iter_first(struct rb_root_cached *root, long unsigned int first, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff8125cce0)
Location: mm/interval_tree.c:92
Inline: False
Direct callers:
  - mm/rmap.c:rmap_walk_anon
  - mm/ksm.c:rmap_walk_ksm
  - mm/memory-failure.c:collect_procs
```
**Symbols:**

```
ffffffff8125cce0-ffffffff8125cd17: anon_vma_interval_tree_iter_first (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct rb_root *root</code> ➡️ <code>struct rb_root_cached *root</code>
</li>
</ul>
</details>
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
