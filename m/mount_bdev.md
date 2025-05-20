# Function: <code>mount_bdev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct dentry *mount_bdev(struct file_system_type *fs_type, int flags, const char *dev_name, void *data, int (*fill_super)(struct super_block *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff8120fb40)
Location: fs/super.c:998
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_mount
  - fs/fat/namei_vfat.c:vfat_mount
  - fs/fuse/inode.c:fuse_mount_blk
```
**Symbols:**

```
ffffffff8120fb40-ffffffff8120fe09: mount_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct dentry *mount_bdev(struct file_system_type *fs_type, int flags, const char *dev_name, void *data, int (*fill_super)(struct super_block *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81236570)
Location: fs/super.c:1020
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_mount
  - fs/squashfs/super.c:squashfs_mount
  - fs/fat/namei_vfat.c:vfat_mount
  - fs/fuse/inode.c:fuse_mount_blk
```
**Symbols:**

```
ffffffff81236570-ffffffff812367f0: mount_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct dentry *mount_bdev(struct file_system_type *fs_type, int flags, const char *dev_name, void *data, int (*fill_super)(struct super_block *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81249220)
Location: fs/super.c:1066
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_mount
  - fs/squashfs/super.c:squashfs_mount
  - fs/fat/namei_vfat.c:vfat_mount
  - fs/fuse/inode.c:fuse_mount_blk
```
**Symbols:**

```
ffffffff81249220-ffffffff812494a0: mount_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct dentry *mount_bdev(struct file_system_type *fs_type, int flags, const char *dev_name, void *data, int (*fill_super)(struct super_block *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81254b10)
Location: fs/super.c:1065
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_mount
  - fs/squashfs/super.c:squashfs_mount
  - fs/fat/namei_vfat.c:vfat_mount
  - fs/fuse/inode.c:fuse_mount_blk
```
**Symbols:**

```
ffffffff81254b10-ffffffff81254d98: mount_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct dentry *mount_bdev(struct file_system_type *fs_type, int flags, const char *dev_name, void *data, int (*fill_super)(struct super_block *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81276ca0)
Location: fs/super.c:1065
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_mount
  - fs/squashfs/super.c:squashfs_mount
  - fs/fat/namei_vfat.c:vfat_mount
  - fs/fuse/inode.c:fuse_mount_blk
```
**Symbols:**

```
ffffffff81276ca0-ffffffff81276f2b: mount_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct dentry *mount_bdev(struct file_system_type *fs_type, int flags, const char *dev_name, void *data, int (*fill_super)(struct super_block *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff8129d6b0)
Location: fs/super.c:1120
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_mount
  - fs/squashfs/super.c:squashfs_mount
  - fs/fat/namei_vfat.c:vfat_mount
  - fs/fuse/inode.c:fuse_mount_blk
```
**Symbols:**

```
ffffffff8129d6b0-ffffffff8129d92e: mount_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct dentry *mount_bdev(struct file_system_type *fs_type, int flags, const char *dev_name, void *data, int (*fill_super)(struct super_block *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812b2640)
Location: fs/super.c:1105
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_mount
  - fs/squashfs/super.c:squashfs_mount
  - fs/fat/namei_vfat.c:vfat_mount
  - fs/fuse/inode.c:fuse_mount_blk
```
**Symbols:**

```
ffffffff812b2640-ffffffff812b28e7: mount_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct dentry *mount_bdev(struct file_system_type *fs_type, int flags, const char *dev_name, void *data, int (*fill_super)(struct super_block *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812cf0a0)
Location: fs/super.c:1229
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_mount
  - fs/squashfs/super.c:squashfs_mount
  - fs/fat/namei_vfat.c:vfat_mount
  - fs/fuse/inode.c:fuse_mount_blk
```
**Symbols:**

```
ffffffff812cf0a0-ffffffff812cf315: mount_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct dentry *mount_bdev(struct file_system_type *fs_type, int flags, const char *dev_name, void *data, int (*fill_super)(struct super_block *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812e0ad0)
Location: fs/super.c:1363
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_mount
  - fs/fat/namei_vfat.c:vfat_mount
```
**Symbols:**

```
ffffffff812e0ad0-ffffffff812e0c77: mount_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct dentry *mount_bdev(struct file_system_type *fs_type, int flags, const char *dev_name, void *data, int (*fill_super)(struct super_block *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81317d60)
Location: fs/super.c:1363
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_mount
  - fs/fat/namei_vfat.c:vfat_mount
```
**Symbols:**

```
ffffffff81317d60-ffffffff81317f07: mount_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct dentry *mount_bdev(struct file_system_type *fs_type, int flags, const char *dev_name, void *data, int (*fill_super)(struct super_block *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81322fd0)
Location: fs/super.c:1312
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_mount
  - fs/fat/namei_vfat.c:vfat_mount
```
**Symbols:**

```
ffffffff81322fd0-ffffffff81323185: mount_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct dentry *mount_bdev(struct file_system_type *fs_type, int flags, const char *dev_name, void *data, int (*fill_super)(struct super_block *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81329090)
Location: fs/super.c:1314
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_mount
  - fs/fat/namei_vfat.c:vfat_mount
```
**Symbols:**

```
ffffffff81329090-ffffffff81329245: mount_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct dentry *mount_bdev(struct file_system_type *fs_type, int flags, const char *dev_name, void *data, int (*fill_super)(struct super_block *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/super.c (0)
Location: fs/super.c:1314
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_mount
  - fs/fat/namei_vfat.c:vfat_mount
```
**Symbols:**

```
ffffffff81cc38f2-ffffffff81cc3912: mount_bdev.cold (STB_LOCAL)
ffffffff813766c0-ffffffff8137687e: mount_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct dentry *mount_bdev(struct file_system_type *fs_type, int flags, const char *dev_name, void *data, int (*fill_super)(struct super_block *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/super.c (0)
Location: fs/super.c:1313
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_mount
```
**Symbols:**

```
ffffffff81e76058-ffffffff81e76078: mount_bdev.cold (STB_LOCAL)
ffffffff813f5e80-ffffffff813f6045: mount_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct dentry *mount_bdev(struct file_system_type *fs_type, int flags, const char *dev_name, void *data, int (*fill_super)(struct super_block *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/super.c (0)
Location: fs/super.c:1316
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_mount
```
**Symbols:**

```
ffffffff82068720-ffffffff82068740: mount_bdev.cold (STB_LOCAL)
ffffffff8147f130-ffffffff8147f2f5: mount_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct dentry *mount_bdev(struct file_system_type *fs_type, int flags, const char *dev_name, void *data, int (*fill_super)(struct super_block *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/super.c (0)
Location: fs/super.c:1339
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_mount
```
**Symbols:**

```
ffffffff820e8023-ffffffff820e8043: mount_bdev.cold (STB_LOCAL)
ffffffff814b3d90-ffffffff814b3f43: mount_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct dentry *mount_bdev(struct file_system_type *fs_type, int flags, const char *dev_name, void *data, int (*fill_super)(struct super_block *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff814e6560)
Location: fs/super.c:1633
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_mount
```
**Symbols:**

```
ffffffff814e6560-ffffffff814e669d: mount_bdev (STB_GLOBAL)
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
struct dentry *mount_bdev(struct file_system_type *fs_type, int flags, const char *dev_name, void *data, int (*fill_super)(struct super_block *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffff800010387798)
Location: fs/super.c:1363
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_mount
  - fs/fat/namei_vfat.c:vfat_mount
```
**Symbols:**

```
ffff800010387798-ffff800010387990: mount_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct dentry *mount_bdev(struct file_system_type *fs_type, int flags, const char *dev_name, void *data, int (*fill_super)(struct super_block *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (c05708e4)
Location: fs/super.c:1363
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_mount
  - fs/fat/namei_vfat.c:vfat_mount
```
**Symbols:**

```
c05708e4-c0570a84: mount_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct dentry *mount_bdev(struct file_system_type *fs_type, int flags, const char *dev_name, void *data, int (*fill_super)(struct super_block *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (c00000000047ebc0)
Location: fs/super.c:1363
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_mount
  - fs/fat/namei_vfat.c:vfat_mount
```
**Symbols:**

```
c00000000047ebc0-c00000000047eeb4: mount_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct dentry *mount_bdev(struct file_system_type *fs_type, int flags, const char *dev_name, void *data, int (*fill_super)(struct super_block *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffe00025a7d6)
Location: fs/super.c:1363
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_mount
  - fs/fat/namei_vfat.c:vfat_mount
```
**Symbols:**

```
ffffffe00025a7d6-ffffffe00025a95e: mount_bdev (STB_GLOBAL)
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
struct dentry *mount_bdev(struct file_system_type *fs_type, int flags, const char *dev_name, void *data, int (*fill_super)(struct super_block *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812d90b0)
Location: fs/super.c:1363
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_mount
  - fs/fat/namei_vfat.c:vfat_mount
```
**Symbols:**

```
ffffffff812d90b0-ffffffff812d9257: mount_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct dentry *mount_bdev(struct file_system_type *fs_type, int flags, const char *dev_name, void *data, int (*fill_super)(struct super_block *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812c9d30)
Location: fs/super.c:1363
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_mount
  - fs/fat/namei_vfat.c:vfat_mount
```
**Symbols:**

```
ffffffff812c9d30-ffffffff812c9ed7: mount_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct dentry *mount_bdev(struct file_system_type *fs_type, int flags, const char *dev_name, void *data, int (*fill_super)(struct super_block *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812d6ec0)
Location: fs/super.c:1363
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_mount
  - fs/fat/namei_vfat.c:vfat_mount
```
**Symbols:**

```
ffffffff812d6ec0-ffffffff812d7067: mount_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct dentry *mount_bdev(struct file_system_type *fs_type, int flags, const char *dev_name, void *data, int (*fill_super)(struct super_block *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812e8130)
Location: fs/super.c:1363
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_mount
  - fs/fat/namei_vfat.c:vfat_mount
```
**Symbols:**

```
ffffffff812e8130-ffffffff812e82d7: mount_bdev (STB_GLOBAL)
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
