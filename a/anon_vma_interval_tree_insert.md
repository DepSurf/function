# Function: <code>anon_vma_interval_tree_insert</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void anon_vma_interval_tree_insert(struct anon_vma_chain *node, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff811b8b00)
Location: mm/interval_tree.c:76
Inline: False
Direct callers:
  - mm/mmap.c:vma_adjust
  - mm/mmap.c:vma_adjust
  - mm/mmap.c:expand_downwards
  - mm/rmap.c:anon_vma_clone
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_prepare
```
**Symbols:**

```
ffffffff811b8b00-ffffffff811b8b86: anon_vma_interval_tree_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void anon_vma_interval_tree_insert(struct anon_vma_chain *node, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff811d2da0)
Location: mm/interval_tree.c:76
Inline: False
Direct callers:
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:vma_adjust
  - mm/mmap.c:vma_adjust
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_clone
  - mm/rmap.c:anon_vma_prepare
```
**Symbols:**

```
ffffffff811d2da0-ffffffff811d2e26: anon_vma_interval_tree_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void anon_vma_interval_tree_insert(struct anon_vma_chain *node, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff811e2c60)
Location: mm/interval_tree.c:76
Inline: False
Direct callers:
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_clone
  - mm/rmap.c:__anon_vma_prepare
```
**Symbols:**

```
ffffffff811e2c60-ffffffff811e2ce6: anon_vma_interval_tree_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void anon_vma_interval_tree_insert(struct anon_vma_chain *node, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff811ed0d0)
Location: mm/interval_tree.c:76
Inline: False
Direct callers:
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_clone
  - mm/rmap.c:__anon_vma_prepare
```
**Symbols:**

```
ffffffff811ed0d0-ffffffff811ed154: anon_vma_interval_tree_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void anon_vma_interval_tree_insert(struct anon_vma_chain *node, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff812034b0)
Location: mm/interval_tree.c:76
Inline: False
Direct callers:
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_clone
  - mm/rmap.c:__anon_vma_prepare
```
**Symbols:**

```
ffffffff812034b0-ffffffff81203542: anon_vma_interval_tree_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void anon_vma_interval_tree_insert(struct anon_vma_chain *node, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff81224170)
Location: mm/interval_tree.c:76
Inline: False
Direct callers:
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_clone
  - mm/rmap.c:__anon_vma_prepare
```
**Symbols:**

```
ffffffff81224170-ffffffff81224202: anon_vma_interval_tree_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void anon_vma_interval_tree_insert(struct anon_vma_chain *node, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff812371b0)
Location: mm/interval_tree.c:76
Inline: False
Direct callers:
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_clone
  - mm/rmap.c:__anon_vma_prepare
```
**Symbols:**

```
ffffffff812371b0-ffffffff81237242: anon_vma_interval_tree_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void anon_vma_interval_tree_insert(struct anon_vma_chain *node, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff81248740)
Location: mm/interval_tree.c:75
Inline: False
Direct callers:
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_clone
  - mm/rmap.c:__anon_vma_prepare
```
**Symbols:**

```
ffffffff81248740-ffffffff81248804: anon_vma_interval_tree_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void anon_vma_interval_tree_insert(struct anon_vma_chain *node, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff81256b90)
Location: mm/interval_tree.c:75
Inline: False
Direct callers:
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_clone
  - mm/rmap.c:__anon_vma_prepare
```
**Symbols:**

```
ffffffff81256b90-ffffffff81256c54: anon_vma_interval_tree_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void anon_vma_interval_tree_insert(struct anon_vma_chain *node, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff81285520)
Location: mm/interval_tree.c:75
Inline: False
Direct callers:
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_clone
  - mm/rmap.c:__anon_vma_prepare
```
**Symbols:**

```
ffffffff81285520-ffffffff812855e3: anon_vma_interval_tree_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void anon_vma_interval_tree_insert(struct anon_vma_chain *node, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff8128f800)
Location: mm/interval_tree.c:75
Inline: False
Direct callers:
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_clone
  - mm/rmap.c:__anon_vma_prepare
```
**Symbols:**

```
ffffffff8128f800-ffffffff8128f8c3: anon_vma_interval_tree_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void anon_vma_interval_tree_insert(struct anon_vma_chain *node, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff81294e60)
Location: mm/interval_tree.c:75
Inline: False
Direct callers:
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_clone
  - mm/rmap.c:__anon_vma_prepare
```
**Symbols:**

```
ffffffff81294e60-ffffffff81294f23: anon_vma_interval_tree_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void anon_vma_interval_tree_insert(struct anon_vma_chain *node, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff812d54c0)
Location: mm/interval_tree.c:75
Inline: False
Direct callers:
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_clone
  - mm/rmap.c:__anon_vma_prepare
```
**Symbols:**

```
ffffffff812d54c0-ffffffff812d5583: anon_vma_interval_tree_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void anon_vma_interval_tree_insert(struct anon_vma_chain *node, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff813346c0)
Location: mm/interval_tree.c:75
Inline: False
Direct callers:
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_clone
  - mm/rmap.c:__anon_vma_prepare
```
**Symbols:**

```
ffffffff813346c0-ffffffff813347a1: anon_vma_interval_tree_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void anon_vma_interval_tree_insert(struct anon_vma_chain *node, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff813ab390)
Location: mm/interval_tree.c:75
Inline: False
Direct callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_expand
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_clone
  - mm/rmap.c:__anon_vma_prepare
```
**Symbols:**

```
ffffffff813ab390-ffffffff813ab46b: anon_vma_interval_tree_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void anon_vma_interval_tree_insert(struct anon_vma_chain *node, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff813df730)
Location: mm/interval_tree.c:75
Inline: False
Direct callers:
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:vma_complete
  - mm/mmap.c:vma_complete
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_clone
  - mm/rmap.c:__anon_vma_prepare
```
**Symbols:**

```
ffffffff813df730-ffffffff813df80f: anon_vma_interval_tree_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void anon_vma_interval_tree_insert(struct anon_vma_chain *node, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff81409e40)
Location: mm/interval_tree.c:75
Inline: False
Direct callers:
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:vma_complete
  - mm/mmap.c:vma_complete
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_clone
  - mm/rmap.c:__anon_vma_prepare
```
**Symbols:**

```
ffffffff81409e40-ffffffff81409f1f: anon_vma_interval_tree_insert (STB_GLOBAL)
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
void anon_vma_interval_tree_insert(struct anon_vma_chain *node, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffff8000102ee440)
Location: mm/interval_tree.c:75
Inline: False
Direct callers:
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_clone
  - mm/rmap.c:__anon_vma_prepare
```
**Symbols:**

```
ffff8000102ee440-ffff8000102ee528: anon_vma_interval_tree_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void anon_vma_interval_tree_insert(struct anon_vma_chain *node, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (c0512294)
Location: mm/interval_tree.c:75
Inline: False
Direct callers:
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_clone
  - mm/rmap.c:__anon_vma_prepare
```
**Symbols:**

```
c0512294-c0512358: anon_vma_interval_tree_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void anon_vma_interval_tree_insert(struct anon_vma_chain *node, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (c0000000003b24f0)
Location: mm/interval_tree.c:75
Inline: False
Direct callers:
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_clone
  - mm/rmap.c:__anon_vma_prepare
```
**Symbols:**

```
c0000000003b24f0-c0000000003b2618: anon_vma_interval_tree_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void anon_vma_interval_tree_insert(struct anon_vma_chain *node, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffe0002025ec)
Location: mm/interval_tree.c:75
Inline: False
Direct callers:
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_clone
  - mm/rmap.c:__anon_vma_prepare
```
**Symbols:**

```
ffffffe0002025ec-ffffffe000202694: anon_vma_interval_tree_insert (STB_GLOBAL)
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
void anon_vma_interval_tree_insert(struct anon_vma_chain *node, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff8124f1e0)
Location: mm/interval_tree.c:75
Inline: False
Direct callers:
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_clone
  - mm/rmap.c:__anon_vma_prepare
```
**Symbols:**

```
ffffffff8124f1e0-ffffffff8124f2a4: anon_vma_interval_tree_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void anon_vma_interval_tree_insert(struct anon_vma_chain *node, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff81242180)
Location: mm/interval_tree.c:75
Inline: False
Direct callers:
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_clone
  - mm/rmap.c:__anon_vma_prepare
```
**Symbols:**

```
ffffffff81242180-ffffffff81242244: anon_vma_interval_tree_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void anon_vma_interval_tree_insert(struct anon_vma_chain *node, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff8124cf80)
Location: mm/interval_tree.c:75
Inline: False
Direct callers:
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_clone
  - mm/rmap.c:__anon_vma_prepare
```
**Symbols:**

```
ffffffff8124cf80-ffffffff8124d044: anon_vma_interval_tree_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void anon_vma_interval_tree_insert(struct anon_vma_chain *node, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff8125c940)
Location: mm/interval_tree.c:75
Inline: False
Direct callers:
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_clone
  - mm/rmap.c:__anon_vma_prepare
```
**Symbols:**

```
ffffffff8125c940-ffffffff8125ca04: anon_vma_interval_tree_insert (STB_GLOBAL)
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
