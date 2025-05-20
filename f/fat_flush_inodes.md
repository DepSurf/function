# Function: <code>fat_flush_inodes</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int fat_flush_inodes(struct super_block *sb, struct inode *i1, struct inode *i2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff812fcc80)
Location: fs/fat/inode.c:1806
Inline: True
Direct callers:
  - fs/fat/file.c:fat_truncate_blocks
```
**Symbols:**

```
ffffffff812fcc80-ffffffff812fccec: fat_flush_inodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int fat_flush_inodes(struct super_block *sb, struct inode *i1, struct inode *i2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff81330940)
Location: fs/fat/inode.c:1896
Inline: True
Direct callers:
  - fs/fat/file.c:fat_truncate_blocks
```
**Symbols:**

```
ffffffff81330940-ffffffff813309a9: fat_flush_inodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int fat_flush_inodes(struct super_block *sb, struct inode *i1, struct inode *i2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff81346690)
Location: fs/fat/inode.c:1907
Inline: True
Direct callers:
  - fs/fat/file.c:fat_truncate_blocks
```
**Symbols:**

```
ffffffff81346690-ffffffff813466f9: fat_flush_inodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int fat_flush_inodes(struct super_block *sb, struct inode *i1, struct inode *i2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff8135b0a0)
Location: fs/fat/inode.c:1907
Inline: True
Direct callers:
  - fs/fat/file.c:fat_truncate_blocks
```
**Symbols:**

```
ffffffff8135b0a0-ffffffff8135b108: fat_flush_inodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int fat_flush_inodes(struct super_block *sb, struct inode *i1, struct inode *i2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff8137fda0)
Location: fs/fat/inode.c:1907
Inline: True
Direct callers:
  - fs/fat/file.c:fat_truncate_blocks
```
**Symbols:**

```
ffffffff8137fda0-ffffffff8137fe08: fat_flush_inodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int fat_flush_inodes(struct super_block *sb, struct inode *i1, struct inode *i2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff813ae200)
Location: fs/fat/inode.c:1928
Inline: True
Direct callers:
  - fs/fat/file.c:fat_truncate_blocks
```
**Symbols:**

```
ffffffff813ae200-ffffffff813ae270: fat_flush_inodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int fat_flush_inodes(struct super_block *sb, struct inode *i1, struct inode *i2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff813c7710)
Location: fs/fat/inode.c:1929
Inline: True
Direct callers:
  - fs/fat/file.c:fat_truncate_blocks
```
**Symbols:**

```
ffffffff813c7710-ffffffff813c7780: fat_flush_inodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int fat_flush_inodes(struct super_block *sb, struct inode *i1, struct inode *i2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff813f2200)
Location: fs/fat/inode.c:1924
Inline: True
Direct callers:
  - fs/fat/file.c:fat_truncate_blocks
```
**Symbols:**

```
ffffffff813f2200-ffffffff813f226f: fat_flush_inodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int fat_flush_inodes(struct super_block *sb, struct inode *i1, struct inode *i2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff8140c100)
Location: fs/fat/inode.c:1931
Inline: True
Direct callers:
  - fs/fat/file.c:fat_truncate_blocks
```
**Symbols:**

```
ffffffff8140c100-ffffffff8140c16f: fat_flush_inodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int fat_flush_inodes(struct super_block *sb, struct inode *i1, struct inode *i2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff81459e70)
Location: fs/fat/inode.c:1937
Inline: True
Direct callers:
  - fs/fat/file.c:fat_setattr
```
**Symbols:**

```
ffffffff81459e70-ffffffff81459f03: fat_flush_inodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int fat_flush_inodes(struct super_block *sb, struct inode *i1, struct inode *i2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff814761c0)
Location: fs/fat/inode.c:1936
Inline: True
Direct callers:
  - fs/fat/file.c:fat_setattr
```
**Symbols:**

```
ffffffff814761c0-ffffffff81476253: fat_flush_inodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int fat_flush_inodes(struct super_block *sb, struct inode *i1, struct inode *i2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff8147bc30)
Location: fs/fat/inode.c:1936
Inline: True
Direct callers:
  - fs/fat/file.c:fat_setattr
```
**Symbols:**

```
ffffffff8147bc30-ffffffff8147bcc3: fat_flush_inodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int fat_flush_inodes(struct super_block *sb, struct inode *i1, struct inode *i2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff814d3390)
Location: fs/fat/inode.c:1937
Inline: True
Direct callers:
  - fs/fat/file.c:fat_truncate_blocks
```
**Symbols:**

```
ffffffff814d3390-ffffffff814d3423: fat_flush_inodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int fat_flush_inodes(struct super_block *sb, struct inode *i1, struct inode *i2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff81560770)
Location: fs/fat/inode.c:1932
Inline: True
Direct callers:
  - fs/fat/file.c:fat_truncate_blocks
```
**Symbols:**

```
ffffffff81560770-ffffffff8156080f: fat_flush_inodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int fat_flush_inodes(struct super_block *sb, struct inode *i1, struct inode *i2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff81602cb0)
Location: fs/fat/inode.c:1927
Inline: True
Direct callers:
  - fs/fat/file.c:fat_truncate_blocks
```
**Symbols:**

```
ffffffff81602cb0-ffffffff81602d4f: fat_flush_inodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int fat_flush_inodes(struct super_block *sb, struct inode *i1, struct inode *i2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff8163abd0)
Location: fs/fat/inode.c:1927
Inline: True
Direct callers:
  - fs/fat/file.c:fat_truncate_blocks
```
**Symbols:**

```
ffffffff8163abd0-ffffffff8163ac6f: fat_flush_inodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int fat_flush_inodes(struct super_block *sb, struct inode *i1, struct inode *i2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff81674100)
Location: fs/fat/inode.c:1935
Inline: True
Direct callers:
  - fs/fat/file.c:fat_truncate_blocks
```
**Symbols:**

```
ffffffff81674100-ffffffff8167419f: fat_flush_inodes (STB_GLOBAL)
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
int fat_flush_inodes(struct super_block *sb, struct inode *i1, struct inode *i2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffff8000104ecb38)
Location: fs/fat/inode.c:1931
Inline: True
Direct callers:
  - fs/fat/file.c:fat_truncate_blocks
```
**Symbols:**

```
ffff8000104ecb38-ffff8000104ecbdc: fat_flush_inodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int fat_flush_inodes(struct super_block *sb, struct inode *i1, struct inode *i2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (c06aace8)
Location: fs/fat/inode.c:1931
Inline: True
Direct callers:
  - fs/fat/file.c:fat_truncate_blocks
```
**Symbols:**

```
c06aace8-c06aad80: fat_flush_inodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int fat_flush_inodes(struct super_block *sb, struct inode *i1, struct inode *i2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (c00000000062baa0)
Location: fs/fat/inode.c:1931
Inline: True
Direct callers:
  - fs/fat/file.c:fat_truncate_blocks
```
**Symbols:**

```
c00000000062baa0-c00000000062bb6c: fat_flush_inodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int fat_flush_inodes(struct super_block *sb, struct inode *i1, struct inode *i2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffe00035d13a)
Location: fs/fat/inode.c:1931
Inline: True
Direct callers:
  - fs/fat/file.c:fat_truncate_blocks
```
**Symbols:**

```
ffffffe00035d13a-ffffffe00035d1b2: fat_flush_inodes (STB_GLOBAL)
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
int fat_flush_inodes(struct super_block *sb, struct inode *i1, struct inode *i2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff814046e0)
Location: fs/fat/inode.c:1931
Inline: True
Direct callers:
  - fs/fat/file.c:fat_truncate_blocks
```
**Symbols:**

```
ffffffff814046e0-ffffffff8140474f: fat_flush_inodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int fat_flush_inodes(struct super_block *sb, struct inode *i1, struct inode *i2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff813f5160)
Location: fs/fat/inode.c:1931
Inline: True
Direct callers:
  - fs/fat/file.c:fat_truncate_blocks
```
**Symbols:**

```
ffffffff813f5160-ffffffff813f51cf: fat_flush_inodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int fat_flush_inodes(struct super_block *sb, struct inode *i1, struct inode *i2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff81401a60)
Location: fs/fat/inode.c:1931
Inline: True
Direct callers:
  - fs/fat/file.c:fat_truncate_blocks
```
**Symbols:**

```
ffffffff81401a60-ffffffff81401acf: fat_flush_inodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int fat_flush_inodes(struct super_block *sb, struct inode *i1, struct inode *i2);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff81417c00)
Location: fs/fat/inode.c:1931
Inline: True
Direct callers:
  - fs/fat/file.c:fat_truncate_blocks
```
**Symbols:**

```
ffffffff81417c00-ffffffff81417c6f: fat_flush_inodes (STB_GLOBAL)
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
