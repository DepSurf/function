# Function: <code>fuse_iget</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct inode *fuse_iget(struct super_block *sb, u64 nodeid, int generation, struct fuse_attr *attr, u64 attr_valid, u64 attr_version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8131be70)
Location: fs/fuse/inode.c:298
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/inode.c:fuse_get_root_inode
```
**Symbols:**

```
ffffffff8131be70-ffffffff8131c04e: fuse_iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct inode *fuse_iget(struct super_block *sb, u64 nodeid, int generation, struct fuse_attr *attr, u64 attr_valid, u64 attr_version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff81350950)
Location: fs/fuse/inode.c:296
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/inode.c:fuse_get_root_inode
```
**Symbols:**

```
ffffffff81350950-ffffffff81350b27: fuse_iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct inode *fuse_iget(struct super_block *sb, u64 nodeid, int generation, struct fuse_attr *attr, u64 attr_valid, u64 attr_version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff813662b0)
Location: fs/fuse/inode.c:298
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/inode.c:fuse_get_root_inode
```
**Symbols:**

```
ffffffff813662b0-ffffffff81366487: fuse_iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct inode *fuse_iget(struct super_block *sb, u64 nodeid, int generation, struct fuse_attr *attr, u64 attr_valid, u64 attr_version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8137a970)
Location: fs/fuse/inode.c:298
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/inode.c:fuse_get_root_inode
```
**Symbols:**

```
ffffffff8137a970-ffffffff8137ab47: fuse_iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct inode *fuse_iget(struct super_block *sb, u64 nodeid, int generation, struct fuse_attr *attr, u64 attr_valid, u64 attr_version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8139f810)
Location: fs/fuse/inode.c:298
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/inode.c:fuse_get_root_inode
```
**Symbols:**

```
ffffffff8139f810-ffffffff8139f9e7: fuse_iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct inode *fuse_iget(struct super_block *sb, u64 nodeid, int generation, struct fuse_attr *attr, u64 attr_valid, u64 attr_version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff813cebb0)
Location: fs/fuse/inode.c:298
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/inode.c:fuse_get_root_inode
```
**Symbols:**

```
ffffffff813cebb0-ffffffff813ced87: fuse_iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct inode *fuse_iget(struct super_block *sb, u64 nodeid, int generation, struct fuse_attr *attr, u64 attr_valid, u64 attr_version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff813e8020)
Location: fs/fuse/inode.c:297
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/inode.c:fuse_get_root_inode
  - fs/fuse/readdir.c:fuse_readdir
```
**Symbols:**

```
ffffffff813e8020-ffffffff813e81f7: fuse_iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct inode *fuse_iget(struct super_block *sb, u64 nodeid, int generation, struct fuse_attr *attr, u64 attr_valid, u64 attr_version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff814140e0)
Location: fs/fuse/inode.c:295
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/inode.c:fuse_get_root_inode
```
**Symbols:**

```
ffffffff814140e0-ffffffff814142ca: fuse_iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct inode *fuse_iget(struct super_block *sb, u64 nodeid, int generation, struct fuse_attr *attr, u64 attr_valid, u64 attr_version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8142e180)
Location: fs/fuse/inode.c:285
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/inode.c:fuse_fill_super_common
```
**Symbols:**

```
ffffffff8142e180-ffffffff8142e36a: fuse_iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct inode *fuse_iget(struct super_block *sb, u64 nodeid, int generation, struct fuse_attr *attr, u64 attr_valid, u64 attr_version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8147dde0)
Location: fs/fuse/inode.c:287
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/inode.c:fuse_fill_super_common
```
**Symbols:**

```
ffffffff8147dde0-ffffffff8147dfda: fuse_iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct inode *fuse_iget(struct super_block *sb, u64 nodeid, int generation, struct fuse_attr *attr, u64 attr_valid, u64 attr_version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff81499170)
Location: fs/fuse/inode.c:314
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/inode.c:fuse_fill_super_common
  - fs/fuse/inode.c:fuse_fill_super_submount
```
**Symbols:**

```
ffffffff81499170-ffffffff81499309: fuse_iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct inode *fuse_iget(struct super_block *sb, u64 nodeid, int generation, struct fuse_attr *attr, u64 attr_valid, u64 attr_version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8149e3a0)
Location: fs/fuse/inode.c:314
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/inode.c:fuse_fill_super_common
  - fs/fuse/inode.c:fuse_fill_super_submount
```
**Symbols:**

```
ffffffff8149e3a0-ffffffff8149e548: fuse_iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct inode *fuse_iget(struct super_block *sb, u64 nodeid, int generation, struct fuse_attr *attr, u64 attr_valid, u64 attr_version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff814f6250)
Location: fs/fuse/inode.c:316
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/inode.c:fuse_fill_super_common
  - fs/fuse/inode.c:fuse_fill_super_submount
```
**Symbols:**

```
ffffffff814f6250-ffffffff814f63f8: fuse_iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct inode *fuse_iget(struct super_block *sb, u64 nodeid, int generation, struct fuse_attr *attr, u64 attr_valid, u64 attr_version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff81586050)
Location: fs/fuse/inode.c:354
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/inode.c:fuse_fill_super_common
  - fs/fuse/inode.c:fuse_fill_super_submount
```
**Symbols:**

```
ffffffff81586050-ffffffff81586209: fuse_iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct inode *fuse_iget(struct super_block *sb, u64 nodeid, int generation, struct fuse_attr *attr, u64 attr_valid, u64 attr_version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8162c2c0)
Location: fs/fuse/inode.c:361
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/inode.c:fuse_fill_super_common
  - fs/fuse/inode.c:fuse_fill_super_submount
```
**Symbols:**

```
ffffffff8162c2c0-ffffffff8162c47f: fuse_iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct inode *fuse_iget(struct super_block *sb, u64 nodeid, int generation, struct fuse_attr *attr, u64 attr_valid, u64 attr_version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff81664500)
Location: fs/fuse/inode.c:361
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/inode.c:fuse_fill_super_common
  - fs/fuse/inode.c:fuse_fill_super_submount
```
**Symbols:**

```
ffffffff81664500-ffffffff816646bf: fuse_iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct inode *fuse_iget(struct super_block *sb, u64 nodeid, int generation, struct fuse_attr *attr, u64 attr_valid, u64 attr_version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8169e710)
Location: fs/fuse/inode.c:420
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/inode.c:fuse_fill_super_common
  - fs/fuse/inode.c:fuse_fill_super_submount
```
**Symbols:**

```
ffffffff8169e710-ffffffff8169e949: fuse_iget (STB_GLOBAL)
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
struct inode *fuse_iget(struct super_block *sb, u64 nodeid, int generation, struct fuse_attr *attr, u64 attr_valid, u64 attr_version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffff800010512838)
Location: fs/fuse/inode.c:285
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/inode.c:fuse_fill_super_common
  - fs/fuse/readdir.c:parse_dirplusfile
```
**Symbols:**

```
ffff800010512838-ffff800010512a94: fuse_iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct inode *fuse_iget(struct super_block *sb, u64 nodeid, int generation, struct fuse_attr *attr, u64 attr_valid, u64 attr_version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (c06cd964)
Location: fs/fuse/inode.c:285
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/inode.c:fuse_fill_super_common
  - fs/fuse/readdir.c:parse_dirplusfile
```
**Symbols:**

```
c06cd964-c06cdb70: fuse_iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct inode *fuse_iget(struct super_block *sb, u64 nodeid, int generation, struct fuse_attr *attr, u64 attr_valid, u64 attr_version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (c00000000065a550)
Location: fs/fuse/inode.c:285
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/inode.c:fuse_fill_super_common
  - fs/fuse/readdir.c:parse_dirplusfile
```
**Symbols:**

```
c00000000065a550-c00000000065a82c: fuse_iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct inode *fuse_iget(struct super_block *sb, u64 nodeid, int generation, struct fuse_attr *attr, u64 attr_valid, u64 attr_version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffe00037c896)
Location: fs/fuse/inode.c:285
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/inode.c:fuse_fill_super_common
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
ffffffe00037c896-ffffffe00037caa4: fuse_iget (STB_GLOBAL)
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
struct inode *fuse_iget(struct super_block *sb, u64 nodeid, int generation, struct fuse_attr *attr, u64 attr_valid, u64 attr_version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff81426760)
Location: fs/fuse/inode.c:285
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/inode.c:fuse_fill_super_common
```
**Symbols:**

```
ffffffff81426760-ffffffff8142694a: fuse_iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct inode *fuse_iget(struct super_block *sb, u64 nodeid, int generation, struct fuse_attr *attr, u64 attr_valid, u64 attr_version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff814171e0)
Location: fs/fuse/inode.c:285
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/inode.c:fuse_fill_super_common
```
**Symbols:**

```
ffffffff814171e0-ffffffff814173ca: fuse_iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct inode *fuse_iget(struct super_block *sb, u64 nodeid, int generation, struct fuse_attr *attr, u64 attr_valid, u64 attr_version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff81422900)
Location: fs/fuse/inode.c:285
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/inode.c:fuse_fill_super_common
```
**Symbols:**

```
ffffffff81422900-ffffffff81422aea: fuse_iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct inode *fuse_iget(struct super_block *sb, u64 nodeid, int generation, struct fuse_attr *attr, u64 attr_valid, u64 attr_version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff81439730)
Location: fs/fuse/inode.c:285
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/inode.c:fuse_fill_super_common
```
**Symbols:**

```
ffffffff81439730-ffffffff81439918: fuse_iget (STB_GLOBAL)
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
