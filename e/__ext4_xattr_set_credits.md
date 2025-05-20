# Function: <code>__ext4_xattr_set_credits</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __ext4_xattr_set_credits(struct super_block *sb, struct inode *inode, struct buffer_head *block_bh, size_t value_len, bool is_create);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8133d770)
Location: fs/ext4/xattr.c:847
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
**Symbols:**

```
ffffffff8133d770-ffffffff8133d86d: __ext4_xattr_set_credits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __ext4_xattr_set_credits(struct super_block *sb, struct inode *inode, struct buffer_head *block_bh, size_t value_len, bool is_create);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81361d50)
Location: fs/ext4/xattr.c:862
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
**Symbols:**

```
ffffffff81361d50-ffffffff81361e4d: __ext4_xattr_set_credits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __ext4_xattr_set_credits(struct super_block *sb, struct inode *inode, struct buffer_head *block_bh, size_t value_len, bool is_create);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813905b0)
Location: fs/ext4/xattr.c:890
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
**Symbols:**

```
ffffffff813905b0-ffffffff813906b8: __ext4_xattr_set_credits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __ext4_xattr_set_credits(struct super_block *sb, struct inode *inode, struct buffer_head *block_bh, size_t value_len, bool is_create);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813a9190)
Location: fs/ext4/xattr.c:886
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
**Symbols:**

```
ffffffff813a9190-ffffffff813a9298: __ext4_xattr_set_credits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __ext4_xattr_set_credits(struct super_block *sb, struct inode *inode, struct buffer_head *block_bh, size_t value_len, bool is_create);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813d3400)
Location: fs/ext4/xattr.c:887
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
**Symbols:**

```
ffffffff813d3400-ffffffff813d3508: __ext4_xattr_set_credits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __ext4_xattr_set_credits(struct super_block *sb, struct inode *inode, struct buffer_head *block_bh, size_t value_len, bool is_create);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813ecae0)
Location: fs/ext4/xattr.c:887
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
**Symbols:**

```
ffffffff813ecae0-ffffffff813ecbe8: __ext4_xattr_set_credits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __ext4_xattr_set_credits(struct super_block *sb, struct inode *inode, struct buffer_head *block_bh, size_t value_len, bool is_create);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff814399b0)
Location: fs/ext4/xattr.c:889
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
**Symbols:**

```
ffffffff814399b0-ffffffff81439ab5: __ext4_xattr_set_credits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __ext4_xattr_set_credits(struct super_block *sb, struct inode *inode, struct buffer_head *block_bh, size_t value_len, bool is_create);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff814524b0)
Location: fs/ext4/xattr.c:892
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:ext4_xattr_credits_for_new_inode
  - fs/ext4/ialloc.c:ext4_xattr_credits_for_new_inode
  - fs/ext4/ialloc.c:ext4_xattr_credits_for_new_inode
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
**Symbols:**

```
ffffffff814524b0-ffffffff814525c8: __ext4_xattr_set_credits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __ext4_xattr_set_credits(struct super_block *sb, struct inode *inode, struct buffer_head *block_bh, size_t value_len, bool is_create);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81457e40)
Location: fs/ext4/xattr.c:892
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
**Symbols:**

```
ffffffff81457e40-ffffffff81457f54: __ext4_xattr_set_credits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __ext4_xattr_set_credits(struct super_block *sb, struct inode *inode, struct buffer_head *block_bh, size_t value_len, bool is_create);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/xattr.c (0)
Location: fs/ext4/xattr.c:893
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
**Symbols:**

```
ffffffff81cce254-ffffffff81cce29a: __ext4_xattr_set_credits.cold (STB_LOCAL)
ffffffff814abf20-ffffffff814ac054: __ext4_xattr_set_credits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __ext4_xattr_set_credits(struct super_block *sb, struct inode *inode, struct buffer_head *block_bh, size_t value_len, bool is_create);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/xattr.c (0)
Location: fs/ext4/xattr.c:908
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
**Symbols:**

```
ffffffff81e8127b-ffffffff81e812c1: __ext4_xattr_set_credits.cold (STB_LOCAL)
ffffffff81533e10-ffffffff81533f50: __ext4_xattr_set_credits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __ext4_xattr_set_credits(struct super_block *sb, struct inode *inode, struct buffer_head *block_bh, size_t value_len, bool is_create);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/xattr.c (0)
Location: fs/ext4/xattr.c:924
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
**Symbols:**

```
ffffffff82071147-ffffffff8207118d: __ext4_xattr_set_credits.cold (STB_LOCAL)
ffffffff815d22d0-ffffffff815d2410: __ext4_xattr_set_credits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __ext4_xattr_set_credits(struct super_block *sb, struct inode *inode, struct buffer_head *block_bh, size_t value_len, bool is_create);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/xattr.c (0)
Location: fs/ext4/xattr.c:952
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
**Symbols:**

```
ffffffff820f0e2d-ffffffff820f0e73: __ext4_xattr_set_credits.cold (STB_LOCAL)
ffffffff81609db0-ffffffff81609ef0: __ext4_xattr_set_credits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __ext4_xattr_set_credits(struct super_block *sb, struct inode *inode, struct buffer_head *block_bh, size_t value_len, bool is_create);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/xattr.c (0)
Location: fs/ext4/xattr.c:952
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
**Symbols:**

```
ffffffff821cdfe4-ffffffff821ce02a: __ext4_xattr_set_credits.cold (STB_LOCAL)
ffffffff81642b00-ffffffff81642c40: __ext4_xattr_set_credits (STB_GLOBAL)
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
int __ext4_xattr_set_credits(struct super_block *sb, struct inode *inode, struct buffer_head *block_bh, size_t value_len, bool is_create);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffff8000104c59b0)
Location: fs/ext4/xattr.c:887
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
**Symbols:**

```
ffff8000104c59b0-ffff8000104c5adc: __ext4_xattr_set_credits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __ext4_xattr_set_credits(struct super_block *sb, struct inode *inode, struct buffer_head *block_bh, size_t value_len, bool is_create);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (c0689a60)
Location: fs/ext4/xattr.c:887
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
**Symbols:**

```
c0689a60-c0689b74: __ext4_xattr_set_credits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __ext4_xattr_set_credits(struct super_block *sb, struct inode *inode, struct buffer_head *block_bh, size_t value_len, bool is_create);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (c0000000005fd8f0)
Location: fs/ext4/xattr.c:887
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
**Symbols:**

```
c0000000005fd8f0-c0000000005fda74: __ext4_xattr_set_credits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __ext4_xattr_set_credits(struct super_block *sb, struct inode *inode, struct buffer_head *block_bh, size_t value_len, bool is_create);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffe0003400ae)
Location: fs/ext4/xattr.c:887
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
**Symbols:**

```
ffffffe0003400ae-ffffffe00034019e: __ext4_xattr_set_credits (STB_GLOBAL)
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
int __ext4_xattr_set_credits(struct super_block *sb, struct inode *inode, struct buffer_head *block_bh, size_t value_len, bool is_create);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813e50c0)
Location: fs/ext4/xattr.c:887
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
**Symbols:**

```
ffffffff813e50c0-ffffffff813e51c8: __ext4_xattr_set_credits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __ext4_xattr_set_credits(struct super_block *sb, struct inode *inode, struct buffer_head *block_bh, size_t value_len, bool is_create);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813d5b40)
Location: fs/ext4/xattr.c:887
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
**Symbols:**

```
ffffffff813d5b40-ffffffff813d5c48: __ext4_xattr_set_credits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __ext4_xattr_set_credits(struct super_block *sb, struct inode *inode, struct buffer_head *block_bh, size_t value_len, bool is_create);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813e2440)
Location: fs/ext4/xattr.c:887
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
**Symbols:**

```
ffffffff813e2440-ffffffff813e2548: __ext4_xattr_set_credits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __ext4_xattr_set_credits(struct super_block *sb, struct inode *inode, struct buffer_head *block_bh, size_t value_len, bool is_create);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813f7850)
Location: fs/ext4/xattr.c:887
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
**Symbols:**

```
ffffffff813f7850-ffffffff813f7958: __ext4_xattr_set_credits (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
