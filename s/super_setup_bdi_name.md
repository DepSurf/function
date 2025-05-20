# Function: <code>super_setup_bdi_name</code>

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
int super_setup_bdi_name(struct super_block *sb, char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81253b20)
Location: fs/super.c:1289
Inline: False
Direct callers:
  - fs/super.c:super_setup_bdi
  - fs/fuse/inode.c:fuse_fill_super
```
**Symbols:**

```
ffffffff81253b20-ffffffff81253bff: super_setup_bdi_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int super_setup_bdi_name(struct super_block *sb, char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81275ba0)
Location: fs/super.c:1289
Inline: False
Direct callers:
  - fs/super.c:super_setup_bdi
  - fs/fuse/inode.c:fuse_fill_super
```
**Symbols:**

```
ffffffff81275ba0-ffffffff81275c7f: super_setup_bdi_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int super_setup_bdi_name(struct super_block *sb, char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff8129c0f0)
Location: fs/super.c:1352
Inline: False
Direct callers:
  - fs/super.c:super_setup_bdi
  - fs/fuse/inode.c:fuse_fill_super
```
**Symbols:**

```
ffffffff8129c0f0-ffffffff8129c1d5: super_setup_bdi_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int super_setup_bdi_name(struct super_block *sb, char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812b1230)
Location: fs/super.c:1338
Inline: False
Direct callers:
  - fs/super.c:super_setup_bdi
  - fs/fuse/inode.c:fuse_fill_super
```
**Symbols:**

```
ffffffff812b1230-ffffffff812b1315: super_setup_bdi_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int super_setup_bdi_name(struct super_block *sb, char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/super.c (0)
Location: fs/super.c:1494
Inline: False
Direct callers:
  - fs/super.c:super_setup_bdi
  - fs/fuse/inode.c:fuse_fill_super
```
**Symbols:**

```
ffffffff812cff64-ffffffff812cff77: super_setup_bdi_name.cold (STB_LOCAL)
ffffffff812cdcd0-ffffffff812cddab: super_setup_bdi_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int super_setup_bdi_name(struct super_block *sb, char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812df6f0)
Location: fs/super.c:1595
Inline: False
Direct callers:
  - fs/super.c:super_setup_bdi
  - fs/fuse/inode.c:fuse_fill_super_common
```
**Symbols:**

```
ffffffff812df6f0-ffffffff812df7d3: super_setup_bdi_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int super_setup_bdi_name(struct super_block *sb, char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff813164c0)
Location: fs/super.c:1595
Inline: False
Direct callers:
  - fs/super.c:super_setup_bdi
  - fs/fuse/inode.c:fuse_fill_super_common
```
**Symbols:**

```
ffffffff813164c0-ffffffff8131658e: super_setup_bdi_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int super_setup_bdi_name(struct super_block *sb, char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff813219e0)
Location: fs/super.c:1544
Inline: False
Direct callers:
  - fs/super.c:super_setup_bdi
  - fs/fuse/inode.c:fuse_fill_super_common
```
**Symbols:**

```
ffffffff813219e0-ffffffff81321aae: super_setup_bdi_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int super_setup_bdi_name(struct super_block *sb, char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81327a70)
Location: fs/super.c:1546
Inline: False
Direct callers:
  - fs/super.c:super_setup_bdi
  - fs/fuse/inode.c:fuse_fill_super_common
```
**Symbols:**

```
ffffffff81327a70-ffffffff81327b3e: super_setup_bdi_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int super_setup_bdi_name(struct super_block *sb, char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81375040)
Location: fs/super.c:1546
Inline: False
Direct callers:
  - fs/super.c:super_setup_bdi
  - fs/fuse/inode.c:fuse_fill_super_common
```
**Symbols:**

```
ffffffff81375040-ffffffff8137510e: super_setup_bdi_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int super_setup_bdi_name(struct super_block *sb, char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff813f42f0)
Location: fs/super.c:1545
Inline: False
Direct callers:
  - fs/super.c:super_setup_bdi
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/fuse/inode.c:fuse_fill_super_common
```
**Symbols:**

```
ffffffff813f42f0-ffffffff813f43f7: super_setup_bdi_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int super_setup_bdi_name(struct super_block *sb, char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff8147d3b0)
Location: fs/super.c:1550
Inline: False
Direct callers:
  - fs/super.c:super_setup_bdi
  - fs/fuse/inode.c:fuse_fill_super_common
```
**Symbols:**

```
ffffffff8147d3b0-ffffffff8147d4b7: super_setup_bdi_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int super_setup_bdi_name(struct super_block *sb, char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff814b2170)
Location: fs/super.c:1567
Inline: False
Direct callers:
  - fs/super.c:super_setup_bdi
  - fs/fuse/inode.c:fuse_fill_super_common
```
**Symbols:**

```
ffffffff814b2170-ffffffff814b2277: super_setup_bdi_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int super_setup_bdi_name(struct super_block *sb, char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff814e37d0)
Location: fs/super.c:1827
Inline: False
Direct callers:
  - fs/super.c:super_setup_bdi
  - fs/fuse/inode.c:fuse_fill_super_common
```
**Symbols:**

```
ffffffff814e37d0-ffffffff814e38d7: super_setup_bdi_name (STB_GLOBAL)
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
int super_setup_bdi_name(struct super_block *sb, char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffff800010386128)
Location: fs/super.c:1595
Inline: False
Direct callers:
  - fs/super.c:super_setup_bdi
  - fs/super.c:super_setup_bdi
  - fs/fuse/inode.c:fuse_fill_super_common
```
**Symbols:**

```
ffff800010386128-ffff800010386220: super_setup_bdi_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int super_setup_bdi_name(struct super_block *sb, char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (c056f078)
Location: fs/super.c:1595
Inline: False
Direct callers:
  - fs/super.c:super_setup_bdi
  - fs/fuse/inode.c:fuse_fill_super_common
```
**Symbols:**

```
c056f078-c056f158: super_setup_bdi_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int super_setup_bdi_name(struct super_block *sb, char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (c00000000047c670)
Location: fs/super.c:1595
Inline: False
Direct callers:
  - fs/super.c:super_setup_bdi
  - fs/fuse/inode.c:fuse_fill_super_common
```
**Symbols:**

```
c00000000047c670-c00000000047c774: super_setup_bdi_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int super_setup_bdi_name(struct super_block *sb, char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffe000258c2c)
Location: fs/super.c:1595
Inline: False
Direct callers:
  - fs/super.c:super_setup_bdi
  - fs/fuse/inode.c:fuse_fill_super_common
```
**Symbols:**

```
ffffffe000258c2c-ffffffe000258cce: super_setup_bdi_name (STB_GLOBAL)
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
int super_setup_bdi_name(struct super_block *sb, char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812d7cd0)
Location: fs/super.c:1595
Inline: False
Direct callers:
  - fs/super.c:super_setup_bdi
  - fs/fuse/inode.c:fuse_fill_super_common
```
**Symbols:**

```
ffffffff812d7cd0-ffffffff812d7db3: super_setup_bdi_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int super_setup_bdi_name(struct super_block *sb, char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812c8950)
Location: fs/super.c:1595
Inline: False
Direct callers:
  - fs/super.c:super_setup_bdi
  - fs/fuse/inode.c:fuse_fill_super_common
```
**Symbols:**

```
ffffffff812c8950-ffffffff812c8a33: super_setup_bdi_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int super_setup_bdi_name(struct super_block *sb, char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812d5ae0)
Location: fs/super.c:1595
Inline: False
Direct callers:
  - fs/super.c:super_setup_bdi
  - fs/fuse/inode.c:fuse_fill_super_common
```
**Symbols:**

```
ffffffff812d5ae0-ffffffff812d5bc3: super_setup_bdi_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int super_setup_bdi_name(struct super_block *sb, char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812e6af0)
Location: fs/super.c:1595
Inline: False
Direct callers:
  - fs/super.c:super_setup_bdi
  - fs/fuse/inode.c:fuse_fill_super_common
```
**Symbols:**

```
ffffffff812e6af0-ffffffff812e6bd3: super_setup_bdi_name (STB_GLOBAL)
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
