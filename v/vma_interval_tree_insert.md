# Function: <code>vma_interval_tree_insert</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void vma_interval_tree_insert(struct vm_area_struct *node, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff811b8710)
Location: mm/interval_tree.c:24
Inline: False
Direct callers:
  - mm/mmap.c:__vma_link_file
  - mm/mmap.c:vma_adjust
  - mm/mmap.c:vma_adjust
```
**Symbols:**

```
ffffffff811b8710-ffffffff811b878c: vma_interval_tree_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void vma_interval_tree_insert(struct vm_area_struct *node, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff811d29b0)
Location: mm/interval_tree.c:24
Inline: False
Direct callers:
  - mm/mmap.c:vma_adjust
  - mm/mmap.c:vma_adjust
  - mm/mmap.c:__vma_link_file
```
**Symbols:**

```
ffffffff811d29b0-ffffffff811d2a2c: vma_interval_tree_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void vma_interval_tree_insert(struct vm_area_struct *node, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff811e2870)
Location: mm/interval_tree.c:24
Inline: False
Direct callers:
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_link_file
```
**Symbols:**

```
ffffffff811e2870-ffffffff811e28ec: vma_interval_tree_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void vma_interval_tree_insert(struct vm_area_struct *node, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff811eccb0)
Location: mm/interval_tree.c:24
Inline: False
Direct callers:
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_link_file
```
**Symbols:**

```
ffffffff811eccb0-ffffffff811ecd2b: vma_interval_tree_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void vma_interval_tree_insert(struct vm_area_struct *node, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff81203020)
Location: mm/interval_tree.c:24
Inline: False
Direct callers:
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_link_file
```
**Symbols:**

```
ffffffff81203020-ffffffff812030a6: vma_interval_tree_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void vma_interval_tree_insert(struct vm_area_struct *node, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff81223ce0)
Location: mm/interval_tree.c:24
Inline: False
Direct callers:
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_link_file
```
**Symbols:**

```
ffffffff81223ce0-ffffffff81223d66: vma_interval_tree_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void vma_interval_tree_insert(struct vm_area_struct *node, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff81236d30)
Location: mm/interval_tree.c:24
Inline: False
Direct callers:
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_link_file
```
**Symbols:**

```
ffffffff81236d30-ffffffff81236db6: vma_interval_tree_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void vma_interval_tree_insert(struct vm_area_struct *node, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff81248280)
Location: mm/interval_tree.c:23
Inline: False
Direct callers:
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_link_file
```
**Symbols:**

```
ffffffff81248280-ffffffff81248330: vma_interval_tree_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void vma_interval_tree_insert(struct vm_area_struct *node, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff812566e0)
Location: mm/interval_tree.c:23
Inline: False
Direct callers:
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_link_file
```
**Symbols:**

```
ffffffff812566e0-ffffffff81256790: vma_interval_tree_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void vma_interval_tree_insert(struct vm_area_struct *node, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff81285050)
Location: mm/interval_tree.c:23
Inline: False
Direct callers:
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_link_file
```
**Symbols:**

```
ffffffff81285050-ffffffff81285106: vma_interval_tree_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void vma_interval_tree_insert(struct vm_area_struct *node, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff8128f330)
Location: mm/interval_tree.c:23
Inline: False
Direct callers:
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_link_file
```
**Symbols:**

```
ffffffff8128f330-ffffffff8128f3e6: vma_interval_tree_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void vma_interval_tree_insert(struct vm_area_struct *node, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff812949a0)
Location: mm/interval_tree.c:23
Inline: False
Direct callers:
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_link_file
```
**Symbols:**

```
ffffffff812949a0-ffffffff81294a50: vma_interval_tree_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void vma_interval_tree_insert(struct vm_area_struct *node, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff812d5000)
Location: mm/interval_tree.c:23
Inline: False
Direct callers:
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_link_file
```
**Symbols:**

```
ffffffff812d5000-ffffffff812d50b0: vma_interval_tree_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void vma_interval_tree_insert(struct vm_area_struct *node, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff81334130)
Location: mm/interval_tree.c:23
Inline: False
Direct callers:
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_link_file
```
**Symbols:**

```
ffffffff81334130-ffffffff813341fa: vma_interval_tree_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void vma_interval_tree_insert(struct vm_area_struct *node, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff813aadb0)
Location: mm/interval_tree.c:23
Inline: False
Direct callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_expand
  - mm/mmap.c:vma_expand
  - mm/mmap.c:vma_link
```
**Symbols:**

```
ffffffff813aadb0-ffffffff813aae77: vma_interval_tree_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void vma_interval_tree_insert(struct vm_area_struct *node, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff813df170)
Location: mm/interval_tree.c:23
Inline: False
Direct callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:vma_complete
  - mm/mmap.c:vma_complete
  - mm/mmap.c:vma_link
```
**Symbols:**

```
ffffffff813df170-ffffffff813df23b: vma_interval_tree_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void vma_interval_tree_insert(struct vm_area_struct *node, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff81409880)
Location: mm/interval_tree.c:23
Inline: False
Direct callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:vma_complete
  - mm/mmap.c:vma_complete
  - mm/mmap.c:vma_link
```
**Symbols:**

```
ffffffff81409880-ffffffff8140994b: vma_interval_tree_insert (STB_GLOBAL)
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
void vma_interval_tree_insert(struct vm_area_struct *node, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffff8000102ede80)
Location: mm/interval_tree.c:23
Inline: False
Direct callers:
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_link_file
```
**Symbols:**

```
ffff8000102ede80-ffff8000102edf64: vma_interval_tree_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void vma_interval_tree_insert(struct vm_area_struct *node, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (c0511d40)
Location: mm/interval_tree.c:23
Inline: False
Direct callers:
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_link_file
```
**Symbols:**

```
c0511d40-c0511dfc: vma_interval_tree_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void vma_interval_tree_insert(struct vm_area_struct *node, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (c0000000003b1dd0)
Location: mm/interval_tree.c:23
Inline: False
Direct callers:
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_link_file
```
**Symbols:**

```
c0000000003b1dd0-c0000000003b1ee8: vma_interval_tree_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void vma_interval_tree_insert(struct vm_area_struct *node, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffe000202202)
Location: mm/interval_tree.c:23
Inline: False
Direct callers:
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_link_file
```
**Symbols:**

```
ffffffe000202202-ffffffe0002022a6: vma_interval_tree_insert (STB_GLOBAL)
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
void vma_interval_tree_insert(struct vm_area_struct *node, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff8124ed30)
Location: mm/interval_tree.c:23
Inline: False
Direct callers:
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_link_file
```
**Symbols:**

```
ffffffff8124ed30-ffffffff8124ede0: vma_interval_tree_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void vma_interval_tree_insert(struct vm_area_struct *node, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff81241cd0)
Location: mm/interval_tree.c:23
Inline: False
Direct callers:
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_link_file
```
**Symbols:**

```
ffffffff81241cd0-ffffffff81241d80: vma_interval_tree_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void vma_interval_tree_insert(struct vm_area_struct *node, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff8124cad0)
Location: mm/interval_tree.c:23
Inline: False
Direct callers:
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_link_file
```
**Symbols:**

```
ffffffff8124cad0-ffffffff8124cb80: vma_interval_tree_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void vma_interval_tree_insert(struct vm_area_struct *node, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff8125c490)
Location: mm/interval_tree.c:23
Inline: False
Direct callers:
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_link_file
```
**Symbols:**

```
ffffffff8125c490-ffffffff8125c540: vma_interval_tree_insert (STB_GLOBAL)
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
