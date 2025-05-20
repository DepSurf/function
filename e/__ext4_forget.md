# Function: <code>__ext4_forget</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __ext4_forget(const char *where, unsigned int line, handle_t *handle, int is_metadata, struct inode *inode, struct buffer_head *bh, ext4_fsblk_t blocknr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ext4_jbd2.c (ffffffff812cbb30)
Location: fs/ext4/ext4_jbd2.c:184
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
**Symbols:**

```
ffffffff812cbb30-ffffffff812cbcf2: __ext4_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __ext4_forget(const char *where, unsigned int line, handle_t *handle, int is_metadata, struct inode *inode, struct buffer_head *bh, ext4_fsblk_t blocknr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ext4_jbd2.c (ffffffff812fb460)
Location: fs/ext4/ext4_jbd2.c:184
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
**Symbols:**

```
ffffffff812fb460-ffffffff812fb623: __ext4_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __ext4_forget(const char *where, unsigned int line, handle_t *handle, int is_metadata, struct inode *inode, struct buffer_head *bh, ext4_fsblk_t blocknr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ext4_jbd2.c (ffffffff81311400)
Location: fs/ext4/ext4_jbd2.c:184
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
**Symbols:**

```
ffffffff81311400-ffffffff813115d3: __ext4_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __ext4_forget(const char *where, unsigned int line, handle_t *handle, int is_metadata, struct inode *inode, struct buffer_head *bh, ext4_fsblk_t blocknr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ext4_jbd2.c (ffffffff812e6330)
Location: fs/ext4/ext4_jbd2.c:195
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
```
**Symbols:**

```
ffffffff812e6330-ffffffff812e64e1: __ext4_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __ext4_forget(const char *where, unsigned int line, handle_t *handle, int is_metadata, struct inode *inode, struct buffer_head *bh, ext4_fsblk_t blocknr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ext4_jbd2.c (ffffffff8130ad40)
Location: fs/ext4/ext4_jbd2.c:196
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
```
**Symbols:**

```
ffffffff8130ad40-ffffffff8130aef3: __ext4_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __ext4_forget(const char *where, unsigned int line, handle_t *handle, int is_metadata, struct inode *inode, struct buffer_head *bh, ext4_fsblk_t blocknr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ext4_jbd2.c (ffffffff81338cb0)
Location: fs/ext4/ext4_jbd2.c:189
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
```
**Symbols:**

```
ffffffff81338cb0-ffffffff81338e6a: __ext4_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __ext4_forget(const char *where, unsigned int line, handle_t *handle, int is_metadata, struct inode *inode, struct buffer_head *bh, ext4_fsblk_t blocknr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ext4_jbd2.c (ffffffff8134ff60)
Location: fs/ext4/ext4_jbd2.c:189
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
```
**Symbols:**

```
ffffffff8134ff60-ffffffff8135011a: __ext4_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __ext4_forget(const char *where, unsigned int line, handle_t *handle, int is_metadata, struct inode *inode, struct buffer_head *bh, ext4_fsblk_t blocknr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ext4_jbd2.c (ffffffff81378c00)
Location: fs/ext4/ext4_jbd2.c:189
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
```
**Symbols:**

```
ffffffff81378c00-ffffffff81378db4: __ext4_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __ext4_forget(const char *where, unsigned int line, handle_t *handle, int is_metadata, struct inode *inode, struct buffer_head *bh, ext4_fsblk_t blocknr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ext4_jbd2.c (ffffffff81390fc0)
Location: fs/ext4/ext4_jbd2.c:189
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
```
**Symbols:**

```
ffffffff81390fc0-ffffffff81391174: __ext4_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __ext4_forget(const char *where, unsigned int line, handle_t *handle, int is_metadata, struct inode *inode, struct buffer_head *bh, ext4_fsblk_t blocknr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ext4_jbd2.c (ffffffff813dc890)
Location: fs/ext4/ext4_jbd2.c:251
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
```
**Symbols:**

```
ffffffff813dc890-ffffffff813dca06: __ext4_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __ext4_forget(const char *where, unsigned int line, handle_t *handle, int is_metadata, struct inode *inode, struct buffer_head *bh, ext4_fsblk_t blocknr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ext4_jbd2.c (ffffffff813ee2e0)
Location: fs/ext4/ext4_jbd2.c:251
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
```
**Symbols:**

```
ffffffff813ee2e0-ffffffff813ee444: __ext4_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __ext4_forget(const char *where, unsigned int line, handle_t *handle, int is_metadata, struct inode *inode, struct buffer_head *bh, ext4_fsblk_t blocknr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ext4_jbd2.c (ffffffff813f48a0)
Location: fs/ext4/ext4_jbd2.c:251
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
```
**Symbols:**

```
ffffffff813f48a0-ffffffff813f4a04: __ext4_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __ext4_forget(const char *where, unsigned int line, handle_t *handle, int is_metadata, struct inode *inode, struct buffer_head *bh, ext4_fsblk_t blocknr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ext4_jbd2.c (ffffffff81446a80)
Location: fs/ext4/ext4_jbd2.c:259
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
```
**Symbols:**

```
ffffffff81446a80-ffffffff81446be4: __ext4_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __ext4_forget(const char *where, unsigned int line, handle_t *handle, int is_metadata, struct inode *inode, struct buffer_head *bh, ext4_fsblk_t blocknr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ext4_jbd2.c (ffffffff814c2d20)
Location: fs/ext4/ext4_jbd2.c:259
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
```
**Symbols:**

```
ffffffff814c2d20-ffffffff814c2ece: __ext4_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __ext4_forget(const char *where, unsigned int line, handle_t *handle, int is_metadata, struct inode *inode, struct buffer_head *bh, ext4_fsblk_t blocknr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ext4_jbd2.c (ffffffff8155b090)
Location: fs/ext4/ext4_jbd2.c:265
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
```
**Symbols:**

```
ffffffff8155b090-ffffffff8155b23e: __ext4_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __ext4_forget(const char *where, unsigned int line, handle_t *handle, int is_metadata, struct inode *inode, struct buffer_head *bh, ext4_fsblk_t blocknr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ext4_jbd2.c (ffffffff81592eb0)
Location: fs/ext4/ext4_jbd2.c:265
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
```
**Symbols:**

```
ffffffff81592eb0-ffffffff81593051: __ext4_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __ext4_forget(const char *where, unsigned int line, handle_t *handle, int is_metadata, struct inode *inode, struct buffer_head *bh, ext4_fsblk_t blocknr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ext4_jbd2.c (ffffffff815cbba0)
Location: fs/ext4/ext4_jbd2.c:264
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
```
**Symbols:**

```
ffffffff815cbba0-ffffffff815cbd41: __ext4_forget (STB_GLOBAL)
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
int __ext4_forget(const char *where, unsigned int line, handle_t *handle, int is_metadata, struct inode *inode, struct buffer_head *bh, ext4_fsblk_t blocknr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ext4_jbd2.c (ffff800010463ac0)
Location: fs/ext4/ext4_jbd2.c:189
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
```
**Symbols:**

```
ffff800010463ac0-ffff800010463cc8: __ext4_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __ext4_forget(const char *where, unsigned int line, handle_t *handle, int is_metadata, struct inode *inode, struct buffer_head *bh, ext4_fsblk_t blocknr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ext4_jbd2.c (c06240dc)
Location: fs/ext4/ext4_jbd2.c:189
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
```
**Symbols:**

```
c06240dc-c06242cc: __ext4_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __ext4_forget(const char *where, unsigned int line, handle_t *handle, int is_metadata, struct inode *inode, struct buffer_head *bh, ext4_fsblk_t blocknr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ext4_jbd2.c (c000000000580cd0)
Location: fs/ext4/ext4_jbd2.c:189
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
```
**Symbols:**

```
c000000000580cd0-c000000000580f80: __ext4_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __ext4_forget(const char *where, unsigned int line, handle_t *handle, int is_metadata, struct inode *inode, struct buffer_head *bh, ext4_fsblk_t blocknr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ext4_jbd2.c (ffffffe0002f22cc)
Location: fs/ext4/ext4_jbd2.c:189
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
```
**Symbols:**

```
ffffffe0002f22cc-ffffffe0002f2464: __ext4_forget (STB_GLOBAL)
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
int __ext4_forget(const char *where, unsigned int line, handle_t *handle, int is_metadata, struct inode *inode, struct buffer_head *bh, ext4_fsblk_t blocknr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ext4_jbd2.c (ffffffff813895a0)
Location: fs/ext4/ext4_jbd2.c:189
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
```
**Symbols:**

```
ffffffff813895a0-ffffffff81389754: __ext4_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __ext4_forget(const char *where, unsigned int line, handle_t *handle, int is_metadata, struct inode *inode, struct buffer_head *bh, ext4_fsblk_t blocknr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ext4_jbd2.c (ffffffff8137a030)
Location: fs/ext4/ext4_jbd2.c:189
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
```
**Symbols:**

```
ffffffff8137a030-ffffffff8137a1e4: __ext4_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __ext4_forget(const char *where, unsigned int line, handle_t *handle, int is_metadata, struct inode *inode, struct buffer_head *bh, ext4_fsblk_t blocknr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ext4_jbd2.c (ffffffff81386f00)
Location: fs/ext4/ext4_jbd2.c:189
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_alloc_branch
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
```
**Symbols:**

```
ffffffff81386f00-ffffffff813870b4: __ext4_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __ext4_forget(const char *where, unsigned int line, handle_t *handle, int is_metadata, struct inode *inode, struct buffer_head *bh, ext4_fsblk_t blocknr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ext4_jbd2.c (ffffffff8139abe0)
Location: fs/ext4/ext4_jbd2.c:189
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_blocks
```
**Symbols:**

```
ffffffff8139abe0-ffffffff8139ada0: __ext4_forget (STB_GLOBAL)
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
