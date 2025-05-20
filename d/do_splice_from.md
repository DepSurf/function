# Function: <code>do_splice_from</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
long int do_splice_from(struct pipe_inode_info *pipe, struct file *out, loff_t *ppos, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff8123d650)
Location: fs/splice.c:1113
Inline: True
Inline callers:
  - fs/splice.c:direct_splice_actor
  - fs/splice.c:SyS_splice
```
**Symbols:**

```
ffffffff8123d650-ffffffff8123d676: do_splice_from (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
long int do_splice_from(struct pipe_inode_info *pipe, struct file *out, loff_t *ppos, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81267f2e)
Location: fs/splice.c:1114
Inline: True
Inline callers:
  - fs/splice.c:SyS_splice
  - fs/splice.c:direct_splice_actor
```
**Symbols:**

```
ffffffff81265750-ffffffff81265776: do_splice_from (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
long int do_splice_from(struct pipe_inode_info *pipe, struct file *out, loff_t *ppos, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff8127ae9e)
Location: fs/splice.c:860
Inline: True
Inline callers:
  - fs/splice.c:SyS_splice
  - fs/splice.c:direct_splice_actor
```
**Symbols:**

```
ffffffff81278c60-ffffffff81278c86: do_splice_from (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
long int do_splice_from(struct pipe_inode_info *pipe, struct file *out, loff_t *ppos, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff812882da)
Location: fs/splice.c:856
Inline: True
Inline callers:
  - fs/splice.c:SyS_splice
  - fs/splice.c:direct_splice_actor
```
**Symbols:**

```
ffffffff812861d0-ffffffff812861f6: do_splice_from (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
long int do_splice_from(struct pipe_inode_info *pipe, struct file *out, loff_t *ppos, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff812aae0a)
Location: fs/splice.c:840
Inline: True
Inline callers:
  - fs/splice.c:SyS_splice
  - fs/splice.c:direct_splice_actor
```
**Symbols:**

```
ffffffff812a8c50-ffffffff812a8c79: do_splice_from (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
long int do_splice_from(struct pipe_inode_info *pipe, struct file *out, loff_t *ppos, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff812d0a5c)
Location: fs/splice.c:841
Inline: True
Inline callers:
  - fs/splice.c:do_splice
  - fs/splice.c:direct_splice_actor
```
**Symbols:**

```
ffffffff812cf870-ffffffff812cf899: do_splice_from (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
long int do_splice_from(struct pipe_inode_info *pipe, struct file *out, loff_t *ppos, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff812e5c81)
Location: fs/splice.c:840
Inline: True
Inline callers:
  - fs/splice.c:do_splice
  - fs/splice.c:direct_splice_actor
```
**Symbols:**

```
ffffffff812e4be0-ffffffff812e4c09: do_splice_from (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
long int do_splice_from(struct pipe_inode_info *pipe, struct file *out, loff_t *ppos, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81304821)
Location: fs/splice.c:837
Inline: True
Inline callers:
  - fs/splice.c:do_splice
  - fs/splice.c:direct_splice_actor
```
**Symbols:**

```
ffffffff81303340-ffffffff81303369: do_splice_from (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
long int do_splice_from(struct pipe_inode_info *pipe, struct file *out, loff_t *ppos, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff813178a1)
Location: fs/splice.c:837
Inline: True
Inline callers:
  - fs/splice.c:do_splice
  - fs/splice.c:direct_splice_actor
```
**Symbols:**

```
ffffffff813163c0-ffffffff813163e9: do_splice_from (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
long int do_splice_from(struct pipe_inode_info *pipe, struct file *out, loff_t *ppos, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81350d12)
Location: fs/splice.c:842
Inline: True
Inline callers:
  - fs/splice.c:direct_splice_actor
Direct callers:
  - fs/splice.c:do_splice
```
**Symbols:**

```
ffffffff81350c30-ffffffff81350cdf: do_splice_from (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
long int do_splice_from(struct pipe_inode_info *pipe, struct file *out, loff_t *ppos, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff8135ec30)
Location: fs/splice.c:759
Inline: True
Inline callers:
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:direct_splice_actor
  - fs/splice.c:direct_splice_actor
```
**Symbols:**

```
ffffffff8135d2b0-ffffffff8135d2e6: do_splice_from (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff813655e4)
Location: fs/splice.c:762
Inline: True
Inline callers:
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:direct_splice_actor
  - fs/splice.c:direct_splice_actor
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
long int do_splice_from(struct pipe_inode_info *pipe, struct file *out, loff_t *ppos, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff813b3ed4)
Location: fs/splice.c:762
Inline: True
Inline callers:
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:direct_splice_actor
  - fs/splice.c:direct_splice_actor
```
**Symbols:**

```
ffffffff813b2540-ffffffff813b2576: do_splice_from (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff814391f3)
Location: fs/splice.c:762
Inline: True
Inline callers:
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:direct_splice_actor
  - fs/splice.c:direct_splice_actor
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff814c74e3)
Location: fs/splice.c:759
Inline: True
Inline callers:
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:direct_splice_actor
  - fs/splice.c:direct_splice_actor
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff814fd2d2)
Location: fs/splice.c:931
Inline: True
Inline callers:
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:direct_splice_actor
  - fs/splice.c:direct_splice_actor
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81531f19)
Location: fs/splice.c:936
Inline: True
Inline callers:
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/splice.c:splice_file_range_actor
  - fs/splice.c:splice_file_range_actor
  - fs/splice.c:direct_splice_actor
  - fs/splice.c:direct_splice_actor
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
long int do_splice_from(struct pipe_inode_info *pipe, struct file *out, loff_t *ppos, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffff8000103cef3c)
Location: fs/splice.c:837
Inline: True
Inline callers:
  - fs/splice.c:do_splice
  - fs/splice.c:direct_splice_actor
```
**Symbols:**

```
ffff8000103ccd58-ffff8000103ccdcc: do_splice_from (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
long int do_splice_from(struct pipe_inode_info *pipe, struct file *out, loff_t *ppos, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/splice.c (c05aa1f8)
Location: fs/splice.c:837
Inline: True
Inline callers:
  - fs/splice.c:do_splice
  - fs/splice.c:direct_splice_actor
```
**Symbols:**

```
c05a8914-c05a8958: do_splice_from (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
long int do_splice_from(struct pipe_inode_info *pipe, struct file *out, loff_t *ppos, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/splice.c (c0000000004d08c0)
Location: fs/splice.c:837
Inline: True
Inline callers:
  - fs/splice.c:do_splice
  - fs/splice.c:direct_splice_actor
```
**Symbols:**

```
c0000000004ce6a0-c0000000004ce714: do_splice_from (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
long int do_splice_from(struct pipe_inode_info *pipe, struct file *out, loff_t *ppos, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffe00028b0c0)
Location: fs/splice.c:837
Inline: True
Inline callers:
  - fs/splice.c:do_splice
  - fs/splice.c:direct_splice_actor
```
**Symbols:**

```
ffffffe00028a11c-ffffffe00028a170: do_splice_from (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
long int do_splice_from(struct pipe_inode_info *pipe, struct file *out, loff_t *ppos, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff8130fe81)
Location: fs/splice.c:837
Inline: True
Inline callers:
  - fs/splice.c:do_splice
  - fs/splice.c:direct_splice_actor
```
**Symbols:**

```
ffffffff8130e9a0-ffffffff8130e9c9: do_splice_from (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
long int do_splice_from(struct pipe_inode_info *pipe, struct file *out, loff_t *ppos, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81300a91)
Location: fs/splice.c:837
Inline: True
Inline callers:
  - fs/splice.c:do_splice
  - fs/splice.c:direct_splice_actor
```
**Symbols:**

```
ffffffff812ff5b0-ffffffff812ff5d9: do_splice_from (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
long int do_splice_from(struct pipe_inode_info *pipe, struct file *out, loff_t *ppos, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff8130dc71)
Location: fs/splice.c:837
Inline: True
Inline callers:
  - fs/splice.c:do_splice
  - fs/splice.c:direct_splice_actor
```
**Symbols:**

```
ffffffff8130c790-ffffffff8130c7b9: do_splice_from (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
long int do_splice_from(struct pipe_inode_info *pipe, struct file *out, loff_t *ppos, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff8131f471)
Location: fs/splice.c:837
Inline: True
Inline callers:
  - fs/splice.c:do_splice
  - fs/splice.c:direct_splice_actor
```
**Symbols:**

```
ffffffff8131dfc0-ffffffff8131dfe9: do_splice_from (STB_GLOBAL)
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
