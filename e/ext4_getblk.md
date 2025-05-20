# Function: <code>ext4_getblk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct buffer_head *ext4_getblk(handle_t *handle, struct inode *inode, ext4_lblk_t block, int map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81299610)
Location: fs/ext4/inode.c:755
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/namei.c:ext4_find_entry
```
**Symbols:**

```
ffffffff81299610-ffffffff81299793: ext4_getblk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct buffer_head *ext4_getblk(handle_t *handle, struct inode *inode, ext4_lblk_t block, int map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812c6c80)
Location: fs/ext4/inode.c:923
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/namei.c:ext4_find_entry
```
**Symbols:**

```
ffffffff812c6c80-ffffffff812c6e0a: ext4_getblk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct buffer_head *ext4_getblk(handle_t *handle, struct inode *inode, ext4_lblk_t block, int map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812dc770)
Location: fs/ext4/inode.c:937
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/namei.c:ext4_find_entry
```
**Symbols:**

```
ffffffff812dc770-ffffffff812dc8fa: ext4_getblk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct buffer_head *ext4_getblk(handle_t *handle, struct inode *inode, ext4_lblk_t block, int map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81300ec0)
Location: fs/ext4/inode.c:943
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/xattr.c:ext4_xattr_set_entry
```
**Symbols:**

```
ffffffff81300ec0-ffffffff81301048: ext4_getblk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct buffer_head *ext4_getblk(handle_t *handle, struct inode *inode, ext4_lblk_t block, int map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81325870)
Location: fs/ext4/inode.c:953
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/xattr.c:ext4_xattr_set_entry
```
**Symbols:**

```
ffffffff81325870-ffffffff813259f8: ext4_getblk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct buffer_head *ext4_getblk(handle_t *handle, struct inode *inode, ext4_lblk_t block, int map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81353b00)
Location: fs/ext4/inode.c:954
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
**Symbols:**

```
ffffffff81353b00-ffffffff81353c8e: ext4_getblk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct buffer_head *ext4_getblk(handle_t *handle, struct inode *inode, ext4_lblk_t block, int map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8136bc40)
Location: fs/ext4/inode.c:954
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
**Symbols:**

```
ffffffff8136bc40-ffffffff8136bdce: ext4_getblk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct buffer_head *ext4_getblk(handle_t *handle, struct inode *inode, ext4_lblk_t block, int map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813951d0)
Location: fs/ext4/inode.c:962
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
**Symbols:**

```
ffffffff813951d0-ffffffff81395373: ext4_getblk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct buffer_head *ext4_getblk(handle_t *handle, struct inode *inode, ext4_lblk_t block, int map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813adb60)
Location: fs/ext4/inode.c:971
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
**Symbols:**

```
ffffffff813adb60-ffffffff813add03: ext4_getblk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct buffer_head *ext4_getblk(handle_t *handle, struct inode *inode, ext4_lblk_t block, int map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813f9b30)
Location: fs/ext4/inode.c:820
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/xattr.c:ext4_xattr_inode_write
```
**Symbols:**

```
ffffffff813f9b30-ffffffff813f9cd3: ext4_getblk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct buffer_head *ext4_getblk(handle_t *handle, struct inode *inode, ext4_lblk_t block, int map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:834
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/xattr.c:ext4_xattr_inode_write
```
**Symbols:**

```
ffffffff81bec3cf-ffffffff81bec447: ext4_getblk.cold (STB_LOCAL)
ffffffff8140c150-ffffffff8140c322: ext4_getblk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct buffer_head *ext4_getblk(handle_t *handle, struct inode *inode, ext4_lblk_t block, int map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:835
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/xattr.c:ext4_xattr_inode_write
```
**Symbols:**

```
ffffffff81bde47a-ffffffff81bde4f2: ext4_getblk.cold (STB_LOCAL)
ffffffff814122d0-ffffffff814124a1: ext4_getblk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct buffer_head *ext4_getblk(handle_t *handle, struct inode *inode, ext4_lblk_t block, int map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:835
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/xattr.c:ext4_xattr_inode_write
```
**Symbols:**

```
ffffffff81ccacee-ffffffff81ccad66: ext4_getblk.cold (STB_LOCAL)
ffffffff814650b0-ffffffff8146528b: ext4_getblk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct buffer_head *ext4_getblk(handle_t *handle, struct inode *inode, ext4_lblk_t block, int map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:843
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/symlink.c:ext4_get_link
  - fs/ext4/xattr.c:ext4_xattr_inode_write
```
**Symbols:**

```
ffffffff81e7db6a-ffffffff81e7dc0a: ext4_getblk.cold (STB_LOCAL)
ffffffff814e49b0-ffffffff814e4be5: ext4_getblk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct buffer_head *ext4_getblk(handle_t *handle, struct inode *inode, ext4_lblk_t block, int map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8157df30)
Location: fs/ext4/inode.c:849
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/symlink.c:ext4_get_link
  - fs/ext4/xattr.c:ext4_xattr_inode_write
```
**Symbols:**

```
ffffffff8157df30-ffffffff8157e20c: ext4_getblk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct buffer_head *ext4_getblk(handle_t *handle, struct inode *inode, ext4_lblk_t block, int map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff815b5230)
Location: fs/ext4/inode.c:804
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/symlink.c:ext4_get_link
  - fs/ext4/xattr.c:ext4_xattr_inode_write
```
**Symbols:**

```
ffffffff815b5230-ffffffff815b550c: ext4_getblk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct buffer_head *ext4_getblk(handle_t *handle, struct inode *inode, ext4_lblk_t block, int map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff815edfd0)
Location: fs/ext4/inode.c:818
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/symlink.c:ext4_get_link
  - fs/ext4/xattr.c:ext4_xattr_inode_write
```
**Symbols:**

```
ffffffff815edfd0-ffffffff815ee2bb: ext4_getblk (STB_GLOBAL)
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
struct buffer_head *ext4_getblk(handle_t *handle, struct inode *inode, ext4_lblk_t block, int map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffff8000104823f0)
Location: fs/ext4/inode.c:971
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
**Symbols:**

```
ffff8000104823f0-ffff8000104825c0: ext4_getblk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct buffer_head *ext4_getblk(handle_t *handle, struct inode *inode, ext4_lblk_t block, int map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c06438d8)
Location: fs/ext4/inode.c:971
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/xattr.c:ext4_xattr_inode_write
```
**Symbols:**

```
c06438d8-c0643aac: ext4_getblk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct buffer_head *ext4_getblk(handle_t *handle, struct inode *inode, ext4_lblk_t block, int map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c0000000005a6e00)
Location: fs/ext4/inode.c:971
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
**Symbols:**

```
c0000000005a6e00-c0000000005a7078: ext4_getblk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct buffer_head *ext4_getblk(handle_t *handle, struct inode *inode, ext4_lblk_t block, int map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffe00030ae1c)
Location: fs/ext4/inode.c:971
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
**Symbols:**

```
ffffffe00030ae1c-ffffffe00030af86: ext4_getblk (STB_GLOBAL)
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
struct buffer_head *ext4_getblk(handle_t *handle, struct inode *inode, ext4_lblk_t block, int map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a6140)
Location: fs/ext4/inode.c:971
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
**Symbols:**

```
ffffffff813a6140-ffffffff813a62e3: ext4_getblk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct buffer_head *ext4_getblk(handle_t *handle, struct inode *inode, ext4_lblk_t block, int map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81396bd0)
Location: fs/ext4/inode.c:971
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
**Symbols:**

```
ffffffff81396bd0-ffffffff81396d73: ext4_getblk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct buffer_head *ext4_getblk(handle_t *handle, struct inode *inode, ext4_lblk_t block, int map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a39a0)
Location: fs/ext4/inode.c:971
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
**Symbols:**

```
ffffffff813a39a0-ffffffff813a3b43: ext4_getblk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct buffer_head *ext4_getblk(handle_t *handle, struct inode *inode, ext4_lblk_t block, int map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813b8090)
Location: fs/ext4/inode.c:971
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_bread_batch
  - fs/ext4/inode.c:ext4_bread
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
**Symbols:**

```
ffffffff813b8090-ffffffff813b822d: ext4_getblk (STB_GLOBAL)
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
