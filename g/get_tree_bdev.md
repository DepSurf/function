# Function: <code>get_tree_bdev</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int get_tree_bdev(struct fs_context *fc, int (*fill_super)(struct super_block *, struct fs_context *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812e0ea0)
Location: fs/super.c:1277
Inline: False
Direct callers:
  - fs/squashfs/super.c:squashfs_get_tree
```
**Symbols:**

```
ffffffff812e0ea0-ffffffff812e10d5: get_tree_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int get_tree_bdev(struct fs_context *fc, int (*fill_super)(struct super_block *, struct fs_context *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81318140)
Location: fs/super.c:1277
Inline: False
Direct callers:
  - fs/squashfs/super.c:squashfs_get_tree
  - fs/fuse/inode.c:fuse_get_tree
```
**Symbols:**

```
ffffffff81318140-ffffffff81318393: get_tree_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int get_tree_bdev(struct fs_context *fc, int (*fill_super)(struct super_block *, struct fs_context *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81323500)
Location: fs/super.c:1226
Inline: False
Direct callers:
  - fs/squashfs/super.c:squashfs_get_tree
  - fs/fuse/inode.c:fuse_get_tree
```
**Symbols:**

```
ffffffff81323500-ffffffff81323761: get_tree_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int get_tree_bdev(struct fs_context *fc, int (*fill_super)(struct super_block *, struct fs_context *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff813295c0)
Location: fs/super.c:1228
Inline: False
Direct callers:
  - fs/squashfs/super.c:squashfs_get_tree
  - fs/fuse/inode.c:fuse_get_tree
```
**Symbols:**

```
ffffffff813295c0-ffffffff81329821: get_tree_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int get_tree_bdev(struct fs_context *fc, int (*fill_super)(struct super_block *, struct fs_context *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/super.c (0)
Location: fs/super.c:1228
Inline: False
Direct callers:
  - fs/squashfs/super.c:squashfs_get_tree
  - fs/fuse/inode.c:fuse_get_tree
```
**Symbols:**

```
ffffffff81cc3912-ffffffff81cc3932: get_tree_bdev.cold (STB_LOCAL)
ffffffff81376bf0-ffffffff81376e5a: get_tree_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int get_tree_bdev(struct fs_context *fc, int (*fill_super)(struct super_block *, struct fs_context *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/super.c (0)
Location: fs/super.c:1227
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_get_tree
  - fs/squashfs/super.c:squashfs_get_tree
  - fs/fuse/inode.c:fuse_get_tree
```
**Symbols:**

```
ffffffff81e76038-ffffffff81e76058: get_tree_bdev.cold (STB_LOCAL)
ffffffff813f5900-ffffffff813f5b71: get_tree_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int get_tree_bdev(struct fs_context *fc, int (*fill_super)(struct super_block *, struct fs_context *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/super.c (0)
Location: fs/super.c:1228
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_get_tree
  - fs/squashfs/super.c:squashfs_get_tree
  - fs/fuse/inode.c:fuse_get_tree
```
**Symbols:**

```
ffffffff82068700-ffffffff82068720: get_tree_bdev.cold (STB_LOCAL)
ffffffff8147eb90-ffffffff8147ee01: get_tree_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int get_tree_bdev(struct fs_context *fc, int (*fill_super)(struct super_block *, struct fs_context *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/super.c (0)
Location: fs/super.c:1255
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_get_tree
  - fs/squashfs/super.c:squashfs_get_tree
  - fs/fuse/inode.c:fuse_get_tree
```
**Symbols:**

```
ffffffff820e8003-ffffffff820e8023: get_tree_bdev.cold (STB_LOCAL)
ffffffff814b3860-ffffffff814b3ac5: get_tree_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int get_tree_bdev(struct fs_context *fc, int (*fill_super)(struct super_block *, struct fs_context *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff814e5ec0)
Location: fs/super.c:1582
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_get_tree
  - fs/squashfs/super.c:squashfs_get_tree
  - fs/fuse/inode.c:fuse_get_tree
```
**Symbols:**

```
ffffffff814e5ec0-ffffffff814e608d: get_tree_bdev (STB_GLOBAL)
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
int get_tree_bdev(struct fs_context *fc, int (*fill_super)(struct super_block *, struct fs_context *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffff800010387248)
Location: fs/super.c:1277
Inline: False
Direct callers:
  - fs/squashfs/super.c:squashfs_get_tree
```
**Symbols:**

```
ffff800010387248-ffff80001038746c: get_tree_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int get_tree_bdev(struct fs_context *fc, int (*fill_super)(struct super_block *, struct fs_context *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (c05703d8)
Location: fs/super.c:1277
Inline: False
Direct callers:
  - fs/squashfs/super.c:squashfs_get_tree
```
**Symbols:**

```
c05703d8-c05705f4: get_tree_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int get_tree_bdev(struct fs_context *fc, int (*fill_super)(struct super_block *, struct fs_context *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (c00000000047e440)
Location: fs/super.c:1277
Inline: False
Direct callers:
  - fs/squashfs/super.c:squashfs_get_tree
```
**Symbols:**

```
c00000000047e440-c00000000047e764: get_tree_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int get_tree_bdev(struct fs_context *fc, int (*fill_super)(struct super_block *, struct fs_context *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffe00025a2c4)
Location: fs/super.c:1277
Inline: False
Direct callers:
  - fs/squashfs/super.c:squashfs_get_tree
```
**Symbols:**

```
ffffffe00025a2c4-ffffffe00025a4ca: get_tree_bdev (STB_GLOBAL)
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
int get_tree_bdev(struct fs_context *fc, int (*fill_super)(struct super_block *, struct fs_context *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812d9480)
Location: fs/super.c:1277
Inline: False
Direct callers:
  - fs/squashfs/super.c:squashfs_get_tree
```
**Symbols:**

```
ffffffff812d9480-ffffffff812d96b5: get_tree_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int get_tree_bdev(struct fs_context *fc, int (*fill_super)(struct super_block *, struct fs_context *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812ca100)
Location: fs/super.c:1277
Inline: False
Direct callers:
  - fs/squashfs/super.c:squashfs_get_tree
```
**Symbols:**

```
ffffffff812ca100-ffffffff812ca335: get_tree_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int get_tree_bdev(struct fs_context *fc, int (*fill_super)(struct super_block *, struct fs_context *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812d7290)
Location: fs/super.c:1277
Inline: False
Direct callers:
  - fs/squashfs/super.c:squashfs_get_tree
```
**Symbols:**

```
ffffffff812d7290-ffffffff812d74c5: get_tree_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int get_tree_bdev(struct fs_context *fc, int (*fill_super)(struct super_block *, struct fs_context *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812e7c50)
Location: fs/super.c:1277
Inline: False
Direct callers:
  - fs/squashfs/super.c:squashfs_get_tree
```
**Symbols:**

```
ffffffff812e7c50-ffffffff812e7e85: get_tree_bdev (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
