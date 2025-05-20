# Function: <code>vma_interval_tree_remove</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void vma_interval_tree_remove(struct vm_area_struct *node, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff811b8790)
Location: mm/interval_tree.c:24
Inline: False
Direct callers:
  - mm/mmap.c:__remove_shared_vm_struct
  - mm/mmap.c:vma_adjust
  - mm/mmap.c:vma_adjust
  - mm/mmap.c:vma_adjust
```
**Symbols:**

```
ffffffff811b8790-ffffffff811b89c9: vma_interval_tree_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void vma_interval_tree_remove(struct vm_area_struct *node, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff811d2a30)
Location: mm/interval_tree.c:24
Inline: False
Direct callers:
  - mm/mmap.c:vma_adjust
  - mm/mmap.c:vma_adjust
  - mm/mmap.c:vma_adjust
  - mm/mmap.c:__remove_shared_vm_struct
```
**Symbols:**

```
ffffffff811d2a30-ffffffff811d2c6b: vma_interval_tree_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void vma_interval_tree_remove(struct vm_area_struct *node, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff811e28f0)
Location: mm/interval_tree.c:24
Inline: False
Direct callers:
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__remove_shared_vm_struct
```
**Symbols:**

```
ffffffff811e28f0-ffffffff811e2b2b: vma_interval_tree_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void vma_interval_tree_remove(struct vm_area_struct *node, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff811ecd30)
Location: mm/interval_tree.c:24
Inline: False
Direct callers:
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__remove_shared_vm_struct
```
**Symbols:**

```
ffffffff811ecd30-ffffffff811ecf9a: vma_interval_tree_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void vma_interval_tree_remove(struct vm_area_struct *node, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff812030b0)
Location: mm/interval_tree.c:24
Inline: False
Direct callers:
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__remove_shared_vm_struct
```
**Symbols:**

```
ffffffff812030b0-ffffffff8120336a: vma_interval_tree_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void vma_interval_tree_remove(struct vm_area_struct *node, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff81223d70)
Location: mm/interval_tree.c:24
Inline: False
Direct callers:
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__remove_shared_vm_struct
```
**Symbols:**

```
ffffffff81223d70-ffffffff81224028: vma_interval_tree_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void vma_interval_tree_remove(struct vm_area_struct *node, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff81236dc0)
Location: mm/interval_tree.c:24
Inline: False
Direct callers:
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__remove_shared_vm_struct
```
**Symbols:**

```
ffffffff81236dc0-ffffffff8123707e: vma_interval_tree_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void vma_interval_tree_remove(struct vm_area_struct *node, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff81248330)
Location: mm/interval_tree.c:23
Inline: False
Direct callers:
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__remove_shared_vm_struct
```
**Symbols:**

```
ffffffff81248330-ffffffff812485e8: vma_interval_tree_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void vma_interval_tree_remove(struct vm_area_struct *node, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff81256790)
Location: mm/interval_tree.c:23
Inline: False
Direct callers:
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__remove_shared_vm_struct
```
**Symbols:**

```
ffffffff81256790-ffffffff81256a34: vma_interval_tree_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void vma_interval_tree_remove(struct vm_area_struct *node, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff81285110)
Location: mm/interval_tree.c:23
Inline: False
Direct callers:
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__remove_shared_vm_struct
```
**Symbols:**

```
ffffffff81285110-ffffffff812853c9: vma_interval_tree_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void vma_interval_tree_remove(struct vm_area_struct *node, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff8128f3f0)
Location: mm/interval_tree.c:23
Inline: False
Direct callers:
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__remove_shared_vm_struct
```
**Symbols:**

```
ffffffff8128f3f0-ffffffff8128f6a9: vma_interval_tree_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void vma_interval_tree_remove(struct vm_area_struct *node, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff81294a50)
Location: mm/interval_tree.c:23
Inline: False
Direct callers:
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__remove_shared_vm_struct
```
**Symbols:**

```
ffffffff81294a50-ffffffff81294d06: vma_interval_tree_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void vma_interval_tree_remove(struct vm_area_struct *node, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff812d50b0)
Location: mm/interval_tree.c:23
Inline: False
Direct callers:
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:unlink_file_vma
```
**Symbols:**

```
ffffffff812d50b0-ffffffff812d5366: vma_interval_tree_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void vma_interval_tree_remove(struct vm_area_struct *node, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff81334200)
Location: mm/interval_tree.c:23
Inline: False
Direct callers:
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:unlink_file_vma
```
**Symbols:**

```
ffffffff81334200-ffffffff813344eb: vma_interval_tree_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void vma_interval_tree_remove(struct vm_area_struct *node, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff813aae90)
Location: mm/interval_tree.c:23
Inline: False
Direct callers:
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_expand
  - mm/mmap.c:vma_expand
  - mm/mmap.c:vma_expand
  - mm/mmap.c:vma_expand
  - mm/mmap.c:unlink_file_vma
```
**Symbols:**

```
ffffffff813aae90-ffffffff813ab17b: vma_interval_tree_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void vma_interval_tree_remove(struct vm_area_struct *node, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff813df250)
Location: mm/interval_tree.c:23
Inline: False
Direct callers:
  - mm/mmap.c:vma_complete
  - mm/mmap.c:vma_complete
  - mm/mmap.c:unlink_file_vma
```
**Symbols:**

```
ffffffff813df250-ffffffff813df520: vma_interval_tree_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void vma_interval_tree_remove(struct vm_area_struct *node, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff81409960)
Location: mm/interval_tree.c:23
Inline: False
Direct callers:
  - mm/mmap.c:vma_complete
  - mm/mmap.c:vma_complete
  - mm/mmap.c:unlink_file_vma
```
**Symbols:**

```
ffffffff81409960-ffffffff81409c30: vma_interval_tree_remove (STB_GLOBAL)
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
void vma_interval_tree_remove(struct vm_area_struct *node, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffff8000102edf68)
Location: mm/interval_tree.c:23
Inline: False
Direct callers:
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__remove_shared_vm_struct
  - mm/mmap.c:__remove_shared_vm_struct
  - mm/mmap.c:__remove_shared_vm_struct
```
**Symbols:**

```
ffff8000102edf68-ffff8000102ee238: vma_interval_tree_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void vma_interval_tree_remove(struct vm_area_struct *node, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (c0511dfc)
Location: mm/interval_tree.c:23
Inline: False
Direct callers:
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__remove_shared_vm_struct
```
**Symbols:**

```
c0511dfc-c05120e8: vma_interval_tree_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void vma_interval_tree_remove(struct vm_area_struct *node, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (c0000000003b1ef0)
Location: mm/interval_tree.c:23
Inline: False
Direct callers:
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__remove_shared_vm_struct
```
**Symbols:**

```
c0000000003b1ef0-c0000000003b22b0: vma_interval_tree_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void vma_interval_tree_remove(struct vm_area_struct *node, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffe0002022a6)
Location: mm/interval_tree.c:23
Inline: False
Direct callers:
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__remove_shared_vm_struct
```
**Symbols:**

```
ffffffe0002022a6-ffffffe00020246c: vma_interval_tree_remove (STB_GLOBAL)
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
void vma_interval_tree_remove(struct vm_area_struct *node, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff8124ede0)
Location: mm/interval_tree.c:23
Inline: False
Direct callers:
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__remove_shared_vm_struct
```
**Symbols:**

```
ffffffff8124ede0-ffffffff8124f084: vma_interval_tree_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void vma_interval_tree_remove(struct vm_area_struct *node, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff81241d80)
Location: mm/interval_tree.c:23
Inline: False
Direct callers:
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__remove_shared_vm_struct
```
**Symbols:**

```
ffffffff81241d80-ffffffff81242024: vma_interval_tree_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void vma_interval_tree_remove(struct vm_area_struct *node, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff8124cb80)
Location: mm/interval_tree.c:23
Inline: False
Direct callers:
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__remove_shared_vm_struct
```
**Symbols:**

```
ffffffff8124cb80-ffffffff8124ce24: vma_interval_tree_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void vma_interval_tree_remove(struct vm_area_struct *node, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff8125c540)
Location: mm/interval_tree.c:23
Inline: False
Direct callers:
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__remove_shared_vm_struct
```
**Symbols:**

```
ffffffff8125c540-ffffffff8125c7e4: vma_interval_tree_remove (STB_GLOBAL)
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
