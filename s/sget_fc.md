# Function: <code>sget_fc</code>

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
<summary>In <code>5.3</code>: ✅</summary>

```c
struct super_block *sget_fc(struct fs_context *fc, int (*test)(struct super_block *, struct fs_context *), int (*set)(struct super_block *, struct fs_context *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812cf320)
Location: fs/super.c:505
Inline: False
Direct callers:
  - fs/super.c:vfs_get_super
  - fs/kernfs/mount.c:kernfs_get_tree
```
**Symbols:**

```
ffffffff812cf320-ffffffff812cf53f: sget_fc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct super_block *sget_fc(struct fs_context *fc, int (*test)(struct super_block *, struct fs_context *), int (*set)(struct super_block *, struct fs_context *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812e0c80)
Location: fs/super.c:511
Inline: False
Direct callers:
  - fs/super.c:get_tree_bdev
  - fs/super.c:vfs_get_super
  - fs/kernfs/mount.c:kernfs_get_tree
```
**Symbols:**

```
ffffffff812e0c80-ffffffff812e0e9f: sget_fc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct super_block *sget_fc(struct fs_context *fc, int (*test)(struct super_block *, struct fs_context *), int (*set)(struct super_block *, struct fs_context *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81317f10)
Location: fs/super.c:511
Inline: False
Direct callers:
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_keyed
  - fs/super.c:get_tree_single
  - fs/super.c:get_tree_nodev
  - fs/kernfs/mount.c:kernfs_get_tree
```
**Symbols:**

```
ffffffff81317f10-ffffffff81318135: sget_fc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct super_block *sget_fc(struct fs_context *fc, int (*test)(struct super_block *, struct fs_context *), int (*set)(struct super_block *, struct fs_context *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81323220)
Location: fs/super.c:511
Inline: False
Direct callers:
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_keyed
  - fs/super.c:get_tree_single
  - fs/super.c:get_tree_nodev
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/fuse/dir.c:fuse_dentry_automount
```
**Symbols:**

```
ffffffff81323220-ffffffff813234f6: sget_fc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct super_block *sget_fc(struct fs_context *fc, int (*test)(struct super_block *, struct fs_context *), int (*set)(struct super_block *, struct fs_context *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff813292e0)
Location: fs/super.c:512
Inline: False
Direct callers:
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_keyed
  - fs/super.c:get_tree_single
  - fs/super.c:get_tree_nodev
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/fuse/dir.c:fuse_dentry_automount
```
**Symbols:**

```
ffffffff813292e0-ffffffff813295b5: sget_fc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct super_block *sget_fc(struct fs_context *fc, int (*test)(struct super_block *, struct fs_context *), int (*set)(struct super_block *, struct fs_context *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81376910)
Location: fs/super.c:512
Inline: False
Direct callers:
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_keyed
  - fs/super.c:get_tree_single
  - fs/super.c:get_tree_nodev
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/fuse/inode.c:fuse_get_tree
  - fs/fuse/inode.c:fuse_get_tree_submount
```
**Symbols:**

```
ffffffff81376910-ffffffff81376be5: sget_fc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct super_block *sget_fc(struct fs_context *fc, int (*test)(struct super_block *, struct fs_context *), int (*set)(struct super_block *, struct fs_context *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff813f55e0)
Location: fs/super.c:511
Inline: False
Direct callers:
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_keyed
  - fs/super.c:get_tree_single
  - fs/super.c:get_tree_nodev
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/fuse/inode.c:fuse_get_tree
  - fs/fuse/inode.c:fuse_get_tree_submount
```
**Symbols:**

```
ffffffff813f55e0-ffffffff813f58fc: sget_fc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct super_block *sget_fc(struct fs_context *fc, int (*test)(struct super_block *, struct fs_context *), int (*set)(struct super_block *, struct fs_context *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff8147e860)
Location: fs/super.c:554
Inline: False
Direct callers:
  - fs/super.c:get_tree_bdev
  - fs/super.c:vfs_get_super
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/fuse/inode.c:fuse_get_tree
  - fs/fuse/inode.c:fuse_get_tree_submount
```
**Symbols:**

```
ffffffff8147e860-ffffffff8147eb7c: sget_fc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct super_block *sget_fc(struct fs_context *fc, int (*test)(struct super_block *, struct fs_context *), int (*set)(struct super_block *, struct fs_context *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff814b3590)
Location: fs/super.c:561
Inline: False
Direct callers:
  - fs/super.c:get_tree_bdev
  - fs/super.c:vfs_get_super
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/fuse/inode.c:fuse_get_tree
  - fs/fuse/inode.c:fuse_get_tree_submount
```
**Symbols:**

```
ffffffff814b3590-ffffffff814b3849: sget_fc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct super_block *sget_fc(struct fs_context *fc, int (*test)(struct super_block *, struct fs_context *), int (*set)(struct super_block *, struct fs_context *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff814e5a10)
Location: fs/super.c:729
Inline: False
Direct callers:
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_keyed
  - fs/super.c:get_tree_single
  - fs/super.c:get_tree_nodev
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/fuse/inode.c:fuse_get_tree
  - fs/fuse/inode.c:fuse_get_tree_submount
```
**Symbols:**

```
ffffffff814e5a10-ffffffff814e5d9d: sget_fc (STB_GLOBAL)
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
struct super_block *sget_fc(struct fs_context *fc, int (*test)(struct super_block *, struct fs_context *), int (*set)(struct super_block *, struct fs_context *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffff800010386fd0)
Location: fs/super.c:511
Inline: False
Direct callers:
  - fs/super.c:get_tree_bdev
  - fs/super.c:vfs_get_super
  - fs/kernfs/mount.c:kernfs_get_tree
```
**Symbols:**

```
ffff800010386fd0-ffff800010387244: sget_fc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct super_block *sget_fc(struct fs_context *fc, int (*test)(struct super_block *, struct fs_context *), int (*set)(struct super_block *, struct fs_context *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (c05701a0)
Location: fs/super.c:511
Inline: False
Direct callers:
  - fs/super.c:get_tree_bdev
  - fs/super.c:vfs_get_super
  - fs/kernfs/mount.c:kernfs_get_tree
  - drivers/mtd/mtdsuper.c:mtd_get_sb
```
**Symbols:**

```
c05701a0-c05703d8: sget_fc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct super_block *sget_fc(struct fs_context *fc, int (*test)(struct super_block *, struct fs_context *), int (*set)(struct super_block *, struct fs_context *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (c00000000047e050)
Location: fs/super.c:511
Inline: False
Direct callers:
  - fs/super.c:get_tree_bdev
  - fs/super.c:vfs_get_super
  - fs/kernfs/mount.c:kernfs_get_tree
```
**Symbols:**

```
c00000000047e050-c00000000047e438: sget_fc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct super_block *sget_fc(struct fs_context *fc, int (*test)(struct super_block *, struct fs_context *), int (*set)(struct super_block *, struct fs_context *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffe00025a026)
Location: fs/super.c:511
Inline: False
Direct callers:
  - fs/super.c:get_tree_bdev
  - fs/super.c:vfs_get_super
  - fs/kernfs/mount.c:kernfs_get_tree
```
**Symbols:**

```
ffffffe00025a026-ffffffe00025a2c4: sget_fc (STB_GLOBAL)
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
struct super_block *sget_fc(struct fs_context *fc, int (*test)(struct super_block *, struct fs_context *), int (*set)(struct super_block *, struct fs_context *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812d9260)
Location: fs/super.c:511
Inline: False
Direct callers:
  - fs/super.c:get_tree_bdev
  - fs/super.c:vfs_get_super
  - fs/kernfs/mount.c:kernfs_get_tree
```
**Symbols:**

```
ffffffff812d9260-ffffffff812d947f: sget_fc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct super_block *sget_fc(struct fs_context *fc, int (*test)(struct super_block *, struct fs_context *), int (*set)(struct super_block *, struct fs_context *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812c9ee0)
Location: fs/super.c:511
Inline: False
Direct callers:
  - fs/super.c:get_tree_bdev
  - fs/super.c:vfs_get_super
  - fs/kernfs/mount.c:kernfs_get_tree
```
**Symbols:**

```
ffffffff812c9ee0-ffffffff812ca0ff: sget_fc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct super_block *sget_fc(struct fs_context *fc, int (*test)(struct super_block *, struct fs_context *), int (*set)(struct super_block *, struct fs_context *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812d7070)
Location: fs/super.c:511
Inline: False
Direct callers:
  - fs/super.c:get_tree_bdev
  - fs/super.c:vfs_get_super
  - fs/kernfs/mount.c:kernfs_get_tree
```
**Symbols:**

```
ffffffff812d7070-ffffffff812d728f: sget_fc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct super_block *sget_fc(struct fs_context *fc, int (*test)(struct super_block *, struct fs_context *), int (*set)(struct super_block *, struct fs_context *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812e7a30)
Location: fs/super.c:511
Inline: False
Direct callers:
  - fs/super.c:get_tree_bdev
  - fs/super.c:vfs_get_super
  - fs/kernfs/mount.c:kernfs_get_tree
```
**Symbols:**

```
ffffffff812e7a30-ffffffff812e7c4c: sget_fc (STB_GLOBAL)
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
