# Function: <code>vma_interval_tree_insert_after</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void vma_interval_tree_insert_after(struct vm_area_struct *node, struct vm_area_struct *prev, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff811b8a70)
Location: mm/interval_tree.c:29
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff811b8a70-ffffffff811b8af2: vma_interval_tree_insert_after (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void vma_interval_tree_insert_after(struct vm_area_struct *node, struct vm_area_struct *prev, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff811d2d10)
Location: mm/interval_tree.c:29
Inline: False
```
**Symbols:**

```
ffffffff811d2d10-ffffffff811d2d92: vma_interval_tree_insert_after (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void vma_interval_tree_insert_after(struct vm_area_struct *node, struct vm_area_struct *prev, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff811e2bd0)
Location: mm/interval_tree.c:29
Inline: False
```
**Symbols:**

```
ffffffff811e2bd0-ffffffff811e2c52: vma_interval_tree_insert_after (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void vma_interval_tree_insert_after(struct vm_area_struct *node, struct vm_area_struct *prev, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff811ed040)
Location: mm/interval_tree.c:29
Inline: False
```
**Symbols:**

```
ffffffff811ed040-ffffffff811ed0c2: vma_interval_tree_insert_after (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void vma_interval_tree_insert_after(struct vm_area_struct *node, struct vm_area_struct *prev, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff81203420)
Location: mm/interval_tree.c:29
Inline: False
```
**Symbols:**

```
ffffffff81203420-ffffffff812034a6: vma_interval_tree_insert_after (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void vma_interval_tree_insert_after(struct vm_area_struct *node, struct vm_area_struct *prev, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff812240e0)
Location: mm/interval_tree.c:29
Inline: False
Direct callers:
  - kernel/fork.c:copy_mm
```
**Symbols:**

```
ffffffff812240e0-ffffffff81224166: vma_interval_tree_insert_after (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void vma_interval_tree_insert_after(struct vm_area_struct *node, struct vm_area_struct *prev, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff81237120)
Location: mm/interval_tree.c:29
Inline: False
```
**Symbols:**

```
ffffffff81237120-ffffffff812371a6: vma_interval_tree_insert_after (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void vma_interval_tree_insert_after(struct vm_area_struct *node, struct vm_area_struct *prev, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff81248690)
Location: mm/interval_tree.c:28
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
```
**Symbols:**

```
ffffffff81248690-ffffffff81248734: vma_interval_tree_insert_after (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void vma_interval_tree_insert_after(struct vm_area_struct *node, struct vm_area_struct *prev, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff81256ae0)
Location: mm/interval_tree.c:28
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
```
**Symbols:**

```
ffffffff81256ae0-ffffffff81256b84: vma_interval_tree_insert_after (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void vma_interval_tree_insert_after(struct vm_area_struct *node, struct vm_area_struct *prev, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff81285470)
Location: mm/interval_tree.c:28
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
```
**Symbols:**

```
ffffffff81285470-ffffffff81285514: vma_interval_tree_insert_after (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void vma_interval_tree_insert_after(struct vm_area_struct *node, struct vm_area_struct *prev, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff8128f750)
Location: mm/interval_tree.c:28
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
```
**Symbols:**

```
ffffffff8128f750-ffffffff8128f7f4: vma_interval_tree_insert_after (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void vma_interval_tree_insert_after(struct vm_area_struct *node, struct vm_area_struct *prev, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff81294db0)
Location: mm/interval_tree.c:28
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
```
**Symbols:**

```
ffffffff81294db0-ffffffff81294e54: vma_interval_tree_insert_after (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void vma_interval_tree_insert_after(struct vm_area_struct *node, struct vm_area_struct *prev, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff812d5410)
Location: mm/interval_tree.c:28
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
```
**Symbols:**

```
ffffffff812d5410-ffffffff812d54b4: vma_interval_tree_insert_after (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void vma_interval_tree_insert_after(struct vm_area_struct *node, struct vm_area_struct *prev, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff81334600)
Location: mm/interval_tree.c:28
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
```
**Symbols:**

```
ffffffff81334600-ffffffff813346b6: vma_interval_tree_insert_after (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void vma_interval_tree_insert_after(struct vm_area_struct *node, struct vm_area_struct *prev, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff813ab2c0)
Location: mm/interval_tree.c:28
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
```
**Symbols:**

```
ffffffff813ab2c0-ffffffff813ab373: vma_interval_tree_insert_after (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void vma_interval_tree_insert_after(struct vm_area_struct *node, struct vm_area_struct *prev, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff813df660)
Location: mm/interval_tree.c:28
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
```
**Symbols:**

```
ffffffff813df660-ffffffff813df716: vma_interval_tree_insert_after (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void vma_interval_tree_insert_after(struct vm_area_struct *node, struct vm_area_struct *prev, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff81409d70)
Location: mm/interval_tree.c:28
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
```
**Symbols:**

```
ffffffff81409d70-ffffffff81409e26: vma_interval_tree_insert_after (STB_GLOBAL)
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
void vma_interval_tree_insert_after(struct vm_area_struct *node, struct vm_area_struct *prev, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffff8000102ee378)
Location: mm/interval_tree.c:28
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
```
**Symbols:**

```
ffff8000102ee378-ffff8000102ee440: vma_interval_tree_insert_after (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void vma_interval_tree_insert_after(struct vm_area_struct *node, struct vm_area_struct *prev, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (c05121d4)
Location: mm/interval_tree.c:28
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
```
**Symbols:**

```
c05121d4-c0512294: vma_interval_tree_insert_after (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void vma_interval_tree_insert_after(struct vm_area_struct *node, struct vm_area_struct *prev, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (c0000000003b23a0)
Location: mm/interval_tree.c:28
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
```
**Symbols:**

```
c0000000003b23a0-c0000000003b24e8: vma_interval_tree_insert_after (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void vma_interval_tree_insert_after(struct vm_area_struct *node, struct vm_area_struct *prev, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffe00020254a)
Location: mm/interval_tree.c:28
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
```
**Symbols:**

```
ffffffe00020254a-ffffffe0002025ec: vma_interval_tree_insert_after (STB_GLOBAL)
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
void vma_interval_tree_insert_after(struct vm_area_struct *node, struct vm_area_struct *prev, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff8124f130)
Location: mm/interval_tree.c:28
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
```
**Symbols:**

```
ffffffff8124f130-ffffffff8124f1d4: vma_interval_tree_insert_after (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void vma_interval_tree_insert_after(struct vm_area_struct *node, struct vm_area_struct *prev, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff812420d0)
Location: mm/interval_tree.c:28
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
```
**Symbols:**

```
ffffffff812420d0-ffffffff81242174: vma_interval_tree_insert_after (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void vma_interval_tree_insert_after(struct vm_area_struct *node, struct vm_area_struct *prev, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff8124ced0)
Location: mm/interval_tree.c:28
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
```
**Symbols:**

```
ffffffff8124ced0-ffffffff8124cf74: vma_interval_tree_insert_after (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void vma_interval_tree_insert_after(struct vm_area_struct *node, struct vm_area_struct *prev, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff8125c890)
Location: mm/interval_tree.c:28
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
```
**Symbols:**

```
ffffffff8125c890-ffffffff8125c934: vma_interval_tree_insert_after (STB_GLOBAL)
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
