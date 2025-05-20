# Function: <code>anon_vma_interval_tree_remove</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void anon_vma_interval_tree_remove(struct anon_vma_chain *node, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff811b8b90)
Location: mm/interval_tree.c:86
Inline: False
Direct callers:
  - mm/mmap.c:vma_adjust
  - mm/mmap.c:vma_adjust
  - mm/mmap.c:expand_downwards
  - mm/rmap.c:unlink_anon_vmas
```
**Symbols:**

```
ffffffff811b8b90-ffffffff811b8dd5: anon_vma_interval_tree_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void anon_vma_interval_tree_remove(struct anon_vma_chain *node, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff811d2e30)
Location: mm/interval_tree.c:86
Inline: False
Direct callers:
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:vma_adjust
  - mm/mmap.c:vma_adjust
  - mm/rmap.c:unlink_anon_vmas
```
**Symbols:**

```
ffffffff811d2e30-ffffffff811d3077: anon_vma_interval_tree_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void anon_vma_interval_tree_remove(struct anon_vma_chain *node, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff811e2cf0)
Location: mm/interval_tree.c:86
Inline: False
Direct callers:
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/rmap.c:unlink_anon_vmas
```
**Symbols:**

```
ffffffff811e2cf0-ffffffff811e2f37: anon_vma_interval_tree_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void anon_vma_interval_tree_remove(struct anon_vma_chain *node, struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff811ed160)
Location: mm/interval_tree.c:86
Inline: False
Direct callers:
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/rmap.c:unlink_anon_vmas
```
**Symbols:**

```
ffffffff811ed160-ffffffff811ed3d6: anon_vma_interval_tree_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void anon_vma_interval_tree_remove(struct anon_vma_chain *node, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff81203550)
Location: mm/interval_tree.c:86
Inline: False
Direct callers:
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/rmap.c:unlink_anon_vmas
```
**Symbols:**

```
ffffffff81203550-ffffffff81203820: anon_vma_interval_tree_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void anon_vma_interval_tree_remove(struct anon_vma_chain *node, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff81224210)
Location: mm/interval_tree.c:86
Inline: False
Direct callers:
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/rmap.c:unlink_anon_vmas
```
**Symbols:**

```
ffffffff81224210-ffffffff812244db: anon_vma_interval_tree_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void anon_vma_interval_tree_remove(struct anon_vma_chain *node, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff81237250)
Location: mm/interval_tree.c:86
Inline: False
Direct callers:
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/rmap.c:unlink_anon_vmas
```
**Symbols:**

```
ffffffff81237250-ffffffff81237521: anon_vma_interval_tree_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void anon_vma_interval_tree_remove(struct anon_vma_chain *node, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff81248810)
Location: mm/interval_tree.c:85
Inline: False
Direct callers:
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/rmap.c:unlink_anon_vmas
```
**Symbols:**

```
ffffffff81248810-ffffffff81248add: anon_vma_interval_tree_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void anon_vma_interval_tree_remove(struct anon_vma_chain *node, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff81256c60)
Location: mm/interval_tree.c:85
Inline: False
Direct callers:
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/rmap.c:unlink_anon_vmas
```
**Symbols:**

```
ffffffff81256c60-ffffffff81256f2d: anon_vma_interval_tree_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void anon_vma_interval_tree_remove(struct anon_vma_chain *node, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff812855f0)
Location: mm/interval_tree.c:85
Inline: False
Direct callers:
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/rmap.c:unlink_anon_vmas
```
**Symbols:**

```
ffffffff812855f0-ffffffff81285600: anon_vma_interval_tree_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void anon_vma_interval_tree_remove(struct anon_vma_chain *node, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff8128f8d0)
Location: mm/interval_tree.c:85
Inline: False
Direct callers:
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/rmap.c:unlink_anon_vmas
```
**Symbols:**

```
ffffffff8128f8d0-ffffffff8128f8e0: anon_vma_interval_tree_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void anon_vma_interval_tree_remove(struct anon_vma_chain *node, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff81294f30)
Location: mm/interval_tree.c:85
Inline: False
Direct callers:
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/rmap.c:unlink_anon_vmas
```
**Symbols:**

```
ffffffff81294f30-ffffffff81294f40: anon_vma_interval_tree_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void anon_vma_interval_tree_remove(struct anon_vma_chain *node, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff812d5590)
Location: mm/interval_tree.c:85
Inline: False
Direct callers:
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/rmap.c:unlink_anon_vmas
```
**Symbols:**

```
ffffffff812d5590-ffffffff812d55a0: anon_vma_interval_tree_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void anon_vma_interval_tree_remove(struct anon_vma_chain *node, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff813347b0)
Location: mm/interval_tree.c:85
Inline: False
Direct callers:
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/rmap.c:unlink_anon_vmas
```
**Symbols:**

```
ffffffff813347b0-ffffffff813347c8: anon_vma_interval_tree_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void anon_vma_interval_tree_remove(struct anon_vma_chain *node, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff813ab480)
Location: mm/interval_tree.c:85
Inline: False
Direct callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_expand
  - mm/rmap.c:unlink_anon_vmas
```
**Symbols:**

```
ffffffff813ab480-ffffffff813ab498: anon_vma_interval_tree_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void anon_vma_interval_tree_remove(struct anon_vma_chain *node, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff813df820)
Location: mm/interval_tree.c:85
Inline: False
Direct callers:
  - mm/mmap.c:expand_downwards
  - mm/rmap.c:unlink_anon_vmas
```
**Symbols:**

```
ffffffff813df820-ffffffff813df838: anon_vma_interval_tree_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void anon_vma_interval_tree_remove(struct anon_vma_chain *node, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff81409f30)
Location: mm/interval_tree.c:85
Inline: False
Direct callers:
  - mm/mmap.c:expand_downwards
  - mm/rmap.c:unlink_anon_vmas
```
**Symbols:**

```
ffffffff81409f30-ffffffff81409f48: anon_vma_interval_tree_remove (STB_GLOBAL)
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
void anon_vma_interval_tree_remove(struct anon_vma_chain *node, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffff8000102ee528)
Location: mm/interval_tree.c:85
Inline: False
Direct callers:
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/rmap.c:unlink_anon_vmas
```
**Symbols:**

```
ffff8000102ee528-ffff8000102ee808: anon_vma_interval_tree_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void anon_vma_interval_tree_remove(struct anon_vma_chain *node, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (c0512358)
Location: mm/interval_tree.c:85
Inline: False
Direct callers:
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/rmap.c:unlink_anon_vmas
```
**Symbols:**

```
c0512358-c0512648: anon_vma_interval_tree_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void anon_vma_interval_tree_remove(struct anon_vma_chain *node, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (c0000000003b2620)
Location: mm/interval_tree.c:85
Inline: False
Direct callers:
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/rmap.c:unlink_anon_vmas
```
**Symbols:**

```
c0000000003b2620-c0000000003b2a50: anon_vma_interval_tree_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void anon_vma_interval_tree_remove(struct anon_vma_chain *node, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffe000202694)
Location: mm/interval_tree.c:85
Inline: False
Direct callers:
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/rmap.c:unlink_anon_vmas
```
**Symbols:**

```
ffffffe000202694-ffffffe000202870: anon_vma_interval_tree_remove (STB_GLOBAL)
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
void anon_vma_interval_tree_remove(struct anon_vma_chain *node, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff8124f2b0)
Location: mm/interval_tree.c:85
Inline: False
Direct callers:
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/rmap.c:unlink_anon_vmas
```
**Symbols:**

```
ffffffff8124f2b0-ffffffff8124f57d: anon_vma_interval_tree_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void anon_vma_interval_tree_remove(struct anon_vma_chain *node, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff81242250)
Location: mm/interval_tree.c:85
Inline: False
Direct callers:
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/rmap.c:unlink_anon_vmas
```
**Symbols:**

```
ffffffff81242250-ffffffff8124251d: anon_vma_interval_tree_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void anon_vma_interval_tree_remove(struct anon_vma_chain *node, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff8124d050)
Location: mm/interval_tree.c:85
Inline: False
Direct callers:
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/rmap.c:unlink_anon_vmas
```
**Symbols:**

```
ffffffff8124d050-ffffffff8124d31d: anon_vma_interval_tree_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void anon_vma_interval_tree_remove(struct anon_vma_chain *node, struct rb_root_cached *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff8125ca10)
Location: mm/interval_tree.c:85
Inline: False
Direct callers:
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:__vma_adjust
  - mm/rmap.c:unlink_anon_vmas
```
**Symbols:**

```
ffffffff8125ca10-ffffffff8125ccdd: anon_vma_interval_tree_remove (STB_GLOBAL)
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
