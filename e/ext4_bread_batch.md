# Function: <code>ext4_bread_batch</code>

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
int ext4_bread_batch(struct inode *inode, ext4_lblk_t block, int bh_count, bool wait, struct buffer_head **bhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813010f0)
Location: fs/ext4/inode.c:1019
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_read
  - fs/ext4/xattr.c:ext4_xattr_inode_read
```
**Symbols:**

```
ffffffff813010f0-ffffffff8130123b: ext4_bread_batch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ext4_bread_batch(struct inode *inode, ext4_lblk_t block, int bh_count, bool wait, struct buffer_head **bhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81325aa0)
Location: fs/ext4/inode.c:1029
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_read
  - fs/ext4/xattr.c:ext4_xattr_inode_read
```
**Symbols:**

```
ffffffff81325aa0-ffffffff81325beb: ext4_bread_batch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ext4_bread_batch(struct inode *inode, ext4_lblk_t block, int bh_count, bool wait, struct buffer_head **bhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81353d30)
Location: fs/ext4/inode.c:1030
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_read
  - fs/ext4/xattr.c:ext4_xattr_inode_read
```
**Symbols:**

```
ffffffff81353d30-ffffffff81353e7e: ext4_bread_batch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ext4_bread_batch(struct inode *inode, ext4_lblk_t block, int bh_count, bool wait, struct buffer_head **bhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8136be70)
Location: fs/ext4/inode.c:1030
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_read
  - fs/ext4/xattr.c:ext4_xattr_inode_read
```
**Symbols:**

```
ffffffff8136be70-ffffffff8136bfbe: ext4_bread_batch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ext4_bread_batch(struct inode *inode, ext4_lblk_t block, int bh_count, bool wait, struct buffer_head **bhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81395430)
Location: fs/ext4/inode.c:1038
Inline: False
Direct callers:
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_read
  - fs/ext4/xattr.c:ext4_xattr_inode_read
```
**Symbols:**

```
ffffffff81395430-ffffffff8139557e: ext4_bread_batch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ext4_bread_batch(struct inode *inode, ext4_lblk_t block, int bh_count, bool wait, struct buffer_head **bhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813adde0)
Location: fs/ext4/inode.c:1047
Inline: False
Direct callers:
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_read
  - fs/ext4/xattr.c:ext4_xattr_inode_read
```
**Symbols:**

```
ffffffff813adde0-ffffffff813adf50: ext4_bread_batch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_bread_batch(struct inode *inode, ext4_lblk_t block, int bh_count, bool wait, struct buffer_head **bhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813f9da0)
Location: fs/ext4/inode.c:896
Inline: False
Direct callers:
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_read
  - fs/ext4/xattr.c:ext4_xattr_inode_read
```
**Symbols:**

```
ffffffff813f9da0-ffffffff813f9f13: ext4_bread_batch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_bread_batch(struct inode *inode, ext4_lblk_t block, int bh_count, bool wait, struct buffer_head **bhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8140c3b0)
Location: fs/ext4/inode.c:914
Inline: False
Direct callers:
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_read
  - fs/ext4/xattr.c:ext4_xattr_inode_read
```
**Symbols:**

```
ffffffff8140c3b0-ffffffff8140c51f: ext4_bread_batch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_bread_batch(struct inode *inode, ext4_lblk_t block, int bh_count, bool wait, struct buffer_head **bhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81412530)
Location: fs/ext4/inode.c:915
Inline: False
Direct callers:
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_read
  - fs/ext4/xattr.c:ext4_xattr_inode_read
```
**Symbols:**

```
ffffffff81412530-ffffffff8141269f: ext4_bread_batch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_bread_batch(struct inode *inode, ext4_lblk_t block, int bh_count, bool wait, struct buffer_head **bhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81465310)
Location: fs/ext4/inode.c:916
Inline: False
Direct callers:
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_read
  - fs/ext4/xattr.c:ext4_xattr_inode_read
```
**Symbols:**

```
ffffffff81465310-ffffffff8146547c: ext4_bread_batch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_bread_batch(struct inode *inode, ext4_lblk_t block, int bh_count, bool wait, struct buffer_head **bhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff814e4c70)
Location: fs/ext4/inode.c:929
Inline: False
Direct callers:
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_read
  - fs/ext4/xattr.c:ext4_xattr_inode_read
```
**Symbols:**

```
ffffffff814e4c70-ffffffff814e4dd7: ext4_bread_batch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_bread_batch(struct inode *inode, ext4_lblk_t block, int bh_count, bool wait, struct buffer_head **bhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8157e2b0)
Location: fs/ext4/inode.c:935
Inline: False
Direct callers:
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_read
  - fs/ext4/xattr.c:ext4_xattr_inode_read
```
**Symbols:**

```
ffffffff8157e2b0-ffffffff8157e41b: ext4_bread_batch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_bread_batch(struct inode *inode, ext4_lblk_t block, int bh_count, bool wait, struct buffer_head **bhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff815b55b0)
Location: fs/ext4/inode.c:890
Inline: False
Direct callers:
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_read
  - fs/ext4/xattr.c:ext4_xattr_inode_read
```
**Symbols:**

```
ffffffff815b55b0-ffffffff815b571b: ext4_bread_batch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_bread_batch(struct inode *inode, ext4_lblk_t block, int bh_count, bool wait, struct buffer_head **bhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff815ee360)
Location: fs/ext4/inode.c:904
Inline: False
Direct callers:
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_read
  - fs/ext4/xattr.c:ext4_xattr_inode_read
```
**Symbols:**

```
ffffffff815ee360-ffffffff815ee4cb: ext4_bread_batch (STB_GLOBAL)
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
int ext4_bread_batch(struct inode *inode, ext4_lblk_t block, int bh_count, bool wait, struct buffer_head **bhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffff800010482700)
Location: fs/ext4/inode.c:1047
Inline: False
Direct callers:
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_read
  - fs/ext4/xattr.c:ext4_xattr_inode_read
```
**Symbols:**

```
ffff800010482700-ffff8000104828e0: ext4_bread_batch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_bread_batch(struct inode *inode, ext4_lblk_t block, int bh_count, bool wait, struct buffer_head **bhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c0643bc0)
Location: fs/ext4/inode.c:1047
Inline: False
Direct callers:
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_read
  - fs/ext4/xattr.c:ext4_xattr_inode_read
```
**Symbols:**

```
c0643bc0-c0643d80: ext4_bread_batch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_bread_batch(struct inode *inode, ext4_lblk_t block, int bh_count, bool wait, struct buffer_head **bhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c0000000005a71e0)
Location: fs/ext4/inode.c:1047
Inline: False
Direct callers:
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_read
  - fs/ext4/xattr.c:ext4_xattr_inode_read
```
**Symbols:**

```
c0000000005a71e0-c0000000005a7488: ext4_bread_batch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ext4_bread_batch(struct inode *inode, ext4_lblk_t block, int bh_count, bool wait, struct buffer_head **bhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffe00030b056)
Location: fs/ext4/inode.c:1047
Inline: False
Direct callers:
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_read
  - fs/ext4/xattr.c:ext4_xattr_inode_read
```
**Symbols:**

```
ffffffe00030b056-ffffffe00030b1a4: ext4_bread_batch (STB_GLOBAL)
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
int ext4_bread_batch(struct inode *inode, ext4_lblk_t block, int bh_count, bool wait, struct buffer_head **bhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a63c0)
Location: fs/ext4/inode.c:1047
Inline: False
Direct callers:
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_read
  - fs/ext4/xattr.c:ext4_xattr_inode_read
```
**Symbols:**

```
ffffffff813a63c0-ffffffff813a6530: ext4_bread_batch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ext4_bread_batch(struct inode *inode, ext4_lblk_t block, int bh_count, bool wait, struct buffer_head **bhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81396e50)
Location: fs/ext4/inode.c:1047
Inline: False
Direct callers:
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_read
  - fs/ext4/xattr.c:ext4_xattr_inode_read
```
**Symbols:**

```
ffffffff81396e50-ffffffff81396fc0: ext4_bread_batch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ext4_bread_batch(struct inode *inode, ext4_lblk_t block, int bh_count, bool wait, struct buffer_head **bhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a3c20)
Location: fs/ext4/inode.c:1047
Inline: False
Direct callers:
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_read
  - fs/ext4/xattr.c:ext4_xattr_inode_read
```
**Symbols:**

```
ffffffff813a3c20-ffffffff813a3d90: ext4_bread_batch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ext4_bread_batch(struct inode *inode, ext4_lblk_t block, int bh_count, bool wait, struct buffer_head **bhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813b82f0)
Location: fs/ext4/inode.c:1047
Inline: False
Direct callers:
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_read
  - fs/ext4/xattr.c:ext4_xattr_inode_read
```
**Symbols:**

```
ffffffff813b82f0-ffffffff813b8458: ext4_bread_batch (STB_GLOBAL)
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
