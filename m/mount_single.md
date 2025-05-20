# Function: <code>mount_single</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct dentry *mount_single(struct file_system_type *fs_type, int flags, void *data, int (*fill_super)(struct super_block *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812105c0)
Location: fs/super.c:1143
Inline: False
Direct callers:
  - fs/fuse/control.c:fuse_ctl_mount
  - fs/debugfs/inode.c:debug_mount
  - fs/tracefs/inode.c:trace_mount
  - fs/pstore/inode.c:pstore_mount
  - fs/efivarfs/super.c:efivarfs_mount
  - security/inode.c:get_sb
  - security/selinux/selinuxfs.c:sel_mount
  - security/smack/smackfs.c:smk_mount
  - drivers/base/devtmpfs.c:dev_mount
```
**Symbols:**

```
ffffffff812105c0-ffffffff81210681: mount_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct dentry *mount_single(struct file_system_type *fs_type, int flags, void *data, int (*fill_super)(struct super_block *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81237070)
Location: fs/super.c:1163
Inline: False
Direct callers:
  - fs/fuse/control.c:fuse_ctl_mount
  - fs/debugfs/inode.c:debug_mount
  - fs/tracefs/inode.c:trace_mount
  - fs/pstore/inode.c:pstore_mount
  - fs/efivarfs/super.c:efivarfs_mount
  - security/inode.c:get_sb
  - security/selinux/selinuxfs.c:sel_mount
  - security/smack/smackfs.c:smk_mount
  - drivers/base/devtmpfs.c:dev_mount
```
**Symbols:**

```
ffffffff81237070-ffffffff8123711a: mount_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct dentry *mount_single(struct file_system_type *fs_type, int flags, void *data, int (*fill_super)(struct super_block *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81249d20)
Location: fs/super.c:1209
Inline: False
Direct callers:
  - fs/fuse/control.c:fuse_ctl_mount
  - fs/debugfs/inode.c:debug_mount
  - fs/tracefs/inode.c:trace_mount
  - fs/pstore/inode.c:pstore_mount
  - fs/efivarfs/super.c:efivarfs_mount
  - security/inode.c:get_sb
  - security/selinux/selinuxfs.c:sel_mount
  - security/smack/smackfs.c:smk_mount
  - drivers/base/devtmpfs.c:dev_mount
```
**Symbols:**

```
ffffffff81249d20-ffffffff81249dca: mount_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct dentry *mount_single(struct file_system_type *fs_type, int flags, void *data, int (*fill_super)(struct super_block *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81255610)
Location: fs/super.c:1208
Inline: False
Direct callers:
  - fs/configfs/mount.c:configfs_do_mount
  - fs/fuse/control.c:fuse_ctl_mount
  - fs/debugfs/inode.c:debug_mount
  - fs/tracefs/inode.c:trace_mount
  - fs/pstore/inode.c:pstore_mount
  - fs/efivarfs/super.c:efivarfs_mount
  - security/inode.c:get_sb
  - security/selinux/selinuxfs.c:sel_mount
  - security/smack/smackfs.c:smk_mount
  - security/apparmor/apparmorfs.c:aafs_mount
  - drivers/base/devtmpfs.c:dev_mount
```
**Symbols:**

```
ffffffff81255610-ffffffff812556c8: mount_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct dentry *mount_single(struct file_system_type *fs_type, int flags, void *data, int (*fill_super)(struct super_block *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812777a0)
Location: fs/super.c:1208
Inline: False
Direct callers:
  - fs/configfs/mount.c:configfs_do_mount
  - fs/fuse/control.c:fuse_ctl_mount
  - fs/debugfs/inode.c:debug_mount
  - fs/tracefs/inode.c:trace_mount
  - fs/pstore/inode.c:pstore_mount
  - fs/efivarfs/super.c:efivarfs_mount
  - security/inode.c:get_sb
  - security/selinux/selinuxfs.c:sel_mount
  - security/smack/smackfs.c:smk_mount
  - security/apparmor/apparmorfs.c:aafs_mount
  - drivers/base/devtmpfs.c:dev_mount
```
**Symbols:**

```
ffffffff812777a0-ffffffff8127785a: mount_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct dentry *mount_single(struct file_system_type *fs_type, int flags, void *data, int (*fill_super)(struct super_block *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff8129e0b0)
Location: fs/super.c:1263
Inline: False
Direct callers:
  - fs/configfs/mount.c:configfs_do_mount
  - fs/fuse/control.c:fuse_ctl_mount
  - fs/debugfs/inode.c:debug_mount
  - fs/tracefs/inode.c:trace_mount
  - fs/pstore/inode.c:pstore_mount
  - fs/efivarfs/super.c:efivarfs_mount
  - security/inode.c:get_sb
  - security/selinux/selinuxfs.c:sel_mount
  - security/smack/smackfs.c:smk_mount
  - security/apparmor/apparmorfs.c:aafs_mount
  - drivers/base/devtmpfs.c:dev_mount
```
**Symbols:**

```
ffffffff8129e0b0-ffffffff8129e15c: mount_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct dentry *mount_single(struct file_system_type *fs_type, int flags, void *data, int (*fill_super)(struct super_block *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812b3070)
Location: fs/super.c:1248
Inline: False
Direct callers:
  - fs/configfs/mount.c:configfs_do_mount
  - fs/fuse/control.c:fuse_ctl_mount
  - fs/debugfs/inode.c:debug_mount
  - fs/tracefs/inode.c:trace_mount
  - fs/pstore/inode.c:pstore_mount
  - fs/efivarfs/super.c:efivarfs_mount
  - security/inode.c:get_sb
  - security/selinux/selinuxfs.c:sel_mount
  - security/smack/smackfs.c:smk_mount
  - security/apparmor/apparmorfs.c:aafs_mount
  - drivers/base/devtmpfs.c:dev_mount
```
**Symbols:**

```
ffffffff812b3070-ffffffff812b311c: mount_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct dentry *mount_single(struct file_system_type *fs_type, int flags, void *data, int (*fill_super)(struct super_block *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812cfd90)
Location: fs/super.c:1397
Inline: False
Direct callers:
  - fs/debugfs/inode.c:debug_mount
  - fs/tracefs/inode.c:trace_mount
  - fs/pstore/inode.c:pstore_mount
  - drivers/base/devtmpfs.c:dev_mount
```
**Symbols:**

```
ffffffff812cfd90-ffffffff812cfe71: mount_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct dentry *mount_single(struct file_system_type *fs_type, int flags, void *data, int (*fill_super)(struct super_block *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812e19a0)
Location: fs/super.c:1503
Inline: False
Direct callers:
  - fs/debugfs/inode.c:debug_mount
  - fs/tracefs/inode.c:trace_mount
  - fs/pstore/inode.c:pstore_mount
```
**Symbols:**

```
ffffffff812e19a0-ffffffff812e1a81: mount_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct dentry *mount_single(struct file_system_type *fs_type, int flags, void *data, int (*fill_super)(struct super_block *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81318cb0)
Location: fs/super.c:1503
Inline: False
Direct callers:
  - fs/debugfs/inode.c:debug_mount
  - fs/tracefs/inode.c:trace_mount
  - fs/pstore/inode.c:pstore_mount
```
**Symbols:**

```
ffffffff81318cb0-ffffffff81318d91: mount_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct dentry *mount_single(struct file_system_type *fs_type, int flags, void *data, int (*fill_super)(struct super_block *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff813241f0)
Location: fs/super.c:1452
Inline: False
Direct callers:
  - fs/tracefs/inode.c:trace_mount
  - fs/pstore/inode.c:pstore_mount
```
**Symbols:**

```
ffffffff813241f0-ffffffff813242d1: mount_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct dentry *mount_single(struct file_system_type *fs_type, int flags, void *data, int (*fill_super)(struct super_block *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff8132a2c0)
Location: fs/super.c:1454
Inline: False
Direct callers:
  - fs/tracefs/inode.c:trace_mount
  - fs/pstore/inode.c:pstore_mount
```
**Symbols:**

```
ffffffff8132a2c0-ffffffff8132a3a1: mount_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct dentry *mount_single(struct file_system_type *fs_type, int flags, void *data, int (*fill_super)(struct super_block *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff813778f0)
Location: fs/super.c:1454
Inline: False
Direct callers:
  - fs/tracefs/inode.c:trace_mount
  - fs/pstore/inode.c:pstore_mount
```
**Symbols:**

```
ffffffff813778f0-ffffffff813779d1: mount_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct dentry *mount_single(struct file_system_type *fs_type, int flags, void *data, int (*fill_super)(struct super_block *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff813f6b90)
Location: fs/super.c:1453
Inline: False
Direct callers:
  - fs/tracefs/inode.c:trace_mount
  - fs/pstore/inode.c:pstore_mount
```
**Symbols:**

```
ffffffff813f6b90-ffffffff813f6c81: mount_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct dentry *mount_single(struct file_system_type *fs_type, int flags, void *data, int (*fill_super)(struct super_block *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff8147fdb0)
Location: fs/super.c:1458
Inline: False
Direct callers:
  - fs/tracefs/inode.c:trace_mount
  - fs/pstore/inode.c:pstore_mount
```
**Symbols:**

```
ffffffff8147fdb0-ffffffff8147fea1: mount_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct dentry *mount_single(struct file_system_type *fs_type, int flags, void *data, int (*fill_super)(struct super_block *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff814b4aa0)
Location: fs/super.c:1475
Inline: False
Direct callers:
  - fs/tracefs/inode.c:trace_mount
  - fs/pstore/inode.c:pstore_mount
```
**Symbols:**

```
ffffffff814b4aa0-ffffffff814b4b91: mount_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct dentry *mount_single(struct file_system_type *fs_type, int flags, void *data, int (*fill_super)(struct super_block *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff814e6d70)
Location: fs/super.c:1735
Inline: False
Direct callers:
  - fs/tracefs/inode.c:trace_mount
  - fs/pstore/inode.c:pstore_mount
```
**Symbols:**

```
ffffffff814e6d70-ffffffff814e6e61: mount_single (STB_GLOBAL)
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
struct dentry *mount_single(struct file_system_type *fs_type, int flags, void *data, int (*fill_super)(struct super_block *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffff800010388dd8)
Location: fs/super.c:1503
Inline: False
Direct callers:
  - fs/debugfs/inode.c:debug_mount
  - fs/tracefs/inode.c:trace_mount
  - fs/pstore/inode.c:pstore_mount
```
**Symbols:**

```
ffff800010388dd8-ffff800010388ed8: mount_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct dentry *mount_single(struct file_system_type *fs_type, int flags, void *data, int (*fill_super)(struct super_block *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (c05713b0)
Location: fs/super.c:1503
Inline: False
Direct callers:
  - fs/debugfs/inode.c:debug_mount
  - fs/tracefs/inode.c:trace_mount
  - fs/pstore/inode.c:pstore_mount
```
**Symbols:**

```
c05713b0-c05714b0: mount_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct dentry *mount_single(struct file_system_type *fs_type, int flags, void *data, int (*fill_super)(struct super_block *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (c00000000047fd00)
Location: fs/super.c:1503
Inline: False
Direct callers:
  - fs/debugfs/inode.c:debug_mount
  - fs/tracefs/inode.c:trace_mount
  - fs/pstore/inode.c:pstore_mount
```
**Symbols:**

```
c00000000047fd00-c00000000047fe60: mount_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct dentry *mount_single(struct file_system_type *fs_type, int flags, void *data, int (*fill_super)(struct super_block *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffe00025b2f8)
Location: fs/super.c:1503
Inline: False
Direct callers:
  - fs/debugfs/inode.c:debug_mount
  - fs/tracefs/inode.c:trace_mount
  - fs/pstore/inode.c:pstore_mount
```
**Symbols:**

```
ffffffe00025b2f8-ffffffe00025b3dc: mount_single (STB_GLOBAL)
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
struct dentry *mount_single(struct file_system_type *fs_type, int flags, void *data, int (*fill_super)(struct super_block *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812d9f80)
Location: fs/super.c:1503
Inline: False
Direct callers:
  - fs/debugfs/inode.c:debug_mount
  - fs/tracefs/inode.c:trace_mount
  - fs/pstore/inode.c:pstore_mount
```
**Symbols:**

```
ffffffff812d9f80-ffffffff812da061: mount_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct dentry *mount_single(struct file_system_type *fs_type, int flags, void *data, int (*fill_super)(struct super_block *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812cac00)
Location: fs/super.c:1503
Inline: False
Direct callers:
  - fs/debugfs/inode.c:debug_mount
  - fs/tracefs/inode.c:trace_mount
  - fs/pstore/inode.c:pstore_mount
```
**Symbols:**

```
ffffffff812cac00-ffffffff812cace1: mount_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct dentry *mount_single(struct file_system_type *fs_type, int flags, void *data, int (*fill_super)(struct super_block *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812d7d90)
Location: fs/super.c:1503
Inline: False
Direct callers:
  - fs/debugfs/inode.c:debug_mount
  - fs/tracefs/inode.c:trace_mount
  - fs/pstore/inode.c:pstore_mount
```
**Symbols:**

```
ffffffff812d7d90-ffffffff812d7e71: mount_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct dentry *mount_single(struct file_system_type *fs_type, int flags, void *data, int (*fill_super)(struct super_block *, void *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812e8bd0)
Location: fs/super.c:1503
Inline: False
Direct callers:
  - fs/debugfs/inode.c:debug_mount
  - fs/tracefs/inode.c:trace_mount
  - fs/pstore/inode.c:pstore_mount
```
**Symbols:**

```
ffffffff812e8bd0-ffffffff812e8cb1: mount_single (STB_GLOBAL)
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
