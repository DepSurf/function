# Function: <code>ext4_dirblock_csum_verify</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int ext4_dirblock_csum_verify(struct inode *inode, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813aaa70)
Location: fs/ext4/namei.c:361
Inline: True
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
```
**Symbols:**

```
ffffffff813aaa70-ffffffff813aab4d: ext4_dirblock_csum_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int ext4_dirblock_csum_verify(struct inode *inode, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813c39a0)
Location: fs/ext4/namei.c:361
Inline: True
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
```
**Symbols:**

```
ffffffff813c39a0-ffffffff813c3a7d: ext4_dirblock_csum_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int ext4_dirblock_csum_verify(struct inode *inode, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81410210)
Location: fs/ext4/namei.c:368
Inline: True
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
```
**Symbols:**

```
ffffffff81410210-ffffffff814102df: ext4_dirblock_csum_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int ext4_dirblock_csum_verify(struct inode *inode, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff814236e0)
Location: fs/ext4/namei.c:364
Inline: True
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
```
**Symbols:**

```
ffffffff814236e0-ffffffff814237af: ext4_dirblock_csum_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_dirblock_csum_verify(struct inode *inode, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81429e00)
Location: fs/ext4/namei.c:366
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
```
**Symbols:**

```
ffffffff81429e00-ffffffff81429ecf: ext4_dirblock_csum_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_dirblock_csum_verify(struct inode *inode, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8147ddd0)
Location: fs/ext4/namei.c:367
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
```
**Symbols:**

```
ffffffff8147ddd0-ffffffff8147de9f: ext4_dirblock_csum_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_dirblock_csum_verify(struct inode *inode, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff815009a0)
Location: fs/ext4/namei.c:390
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
```
**Symbols:**

```
ffffffff815009a0-ffffffff81500a99: ext4_dirblock_csum_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_dirblock_csum_verify(struct inode *inode, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8159b4c0)
Location: fs/ext4/namei.c:395
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
```
**Symbols:**

```
ffffffff8159b4c0-ffffffff8159b5b9: ext4_dirblock_csum_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_dirblock_csum_verify(struct inode *inode, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff815d1d40)
Location: fs/ext4/namei.c:395
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
```
**Symbols:**

```
ffffffff815d1d40-ffffffff815d1e39: ext4_dirblock_csum_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_dirblock_csum_verify(struct inode *inode, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8160a4d0)
Location: fs/ext4/namei.c:396
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
```
**Symbols:**

```
ffffffff8160a4d0-ffffffff8160a5cf: ext4_dirblock_csum_verify (STB_GLOBAL)
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
int ext4_dirblock_csum_verify(struct inode *inode, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffff80001049b390)
Location: fs/ext4/namei.c:361
Inline: True
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
```
**Symbols:**

```
ffff80001049b390-ffff80001049b480: ext4_dirblock_csum_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int ext4_dirblock_csum_verify(struct inode *inode, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (c065ce70)
Location: fs/ext4/namei.c:361
Inline: True
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
```
**Symbols:**

```
c065ce70-c065cf94: ext4_dirblock_csum_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int ext4_dirblock_csum_verify(struct inode *inode, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (c0000000005c5ed0)
Location: fs/ext4/namei.c:361
Inline: True
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
```
**Symbols:**

```
c0000000005c5ed0-c0000000005c6034: ext4_dirblock_csum_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int ext4_dirblock_csum_verify(struct inode *inode, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffe00031e904)
Location: fs/ext4/namei.c:361
Inline: True
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
```
**Symbols:**

```
ffffffe00031e904-ffffffe00031e9e0: ext4_dirblock_csum_verify (STB_GLOBAL)
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
int ext4_dirblock_csum_verify(struct inode *inode, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813bbf80)
Location: fs/ext4/namei.c:361
Inline: True
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
```
**Symbols:**

```
ffffffff813bbf80-ffffffff813bc05d: ext4_dirblock_csum_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int ext4_dirblock_csum_verify(struct inode *inode, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813aca10)
Location: fs/ext4/namei.c:361
Inline: True
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
```
**Symbols:**

```
ffffffff813aca10-ffffffff813acaed: ext4_dirblock_csum_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int ext4_dirblock_csum_verify(struct inode *inode, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813b9960)
Location: fs/ext4/namei.c:361
Inline: True
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
```
**Symbols:**

```
ffffffff813b9960-ffffffff813b9a3d: ext4_dirblock_csum_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int ext4_dirblock_csum_verify(struct inode *inode, struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813ce500)
Location: fs/ext4/namei.c:361
Inline: True
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
```
**Symbols:**

```
ffffffff813ce500-ffffffff813ce5dd: ext4_dirblock_csum_verify (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
