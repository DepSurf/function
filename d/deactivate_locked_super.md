# Function: <code>deactivate_locked_super</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void deactivate_locked_super(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff8120edf0)
Location: fs/super.c:300
Inline: False
Direct callers:
  - fs/super.c:freeze_super
  - fs/super.c:freeze_super
  - fs/super.c:thaw_super
  - fs/super.c:mount_ns
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/super.c:mount_bdev
  - fs/super.c:mount_single
  - fs/super.c:mount_fs
  - fs/libfs.c:mount_pseudo
  - fs/proc/root.c:proc_mount
  - fs/proc/root.c:proc_mount
  - fs/kernfs/mount.c:kernfs_mount_ns
  - fs/devpts/inode.c:devpts_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
```
**Symbols:**

```
ffffffff8120edf0-ffffffff8120ee60: deactivate_locked_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void deactivate_locked_super(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81235820)
Location: fs/super.c:304
Inline: False
Direct callers:
  - fs/super.c:thaw_super
  - fs/super.c:freeze_super
  - fs/super.c:freeze_super
  - fs/super.c:mount_fs
  - fs/super.c:mount_single
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/super.c:mount_bdev
  - fs/super.c:mount_ns
  - fs/libfs.c:mount_pseudo
  - fs/kernfs/mount.c:kernfs_mount_ns
  - fs/devpts/inode.c:devpts_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
```
**Symbols:**

```
ffffffff81235820-ffffffff81235890: deactivate_locked_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void deactivate_locked_super(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812483d0)
Location: fs/super.c:303
Inline: False
Direct callers:
  - fs/super.c:thaw_super
  - fs/super.c:freeze_super
  - fs/super.c:freeze_super
  - fs/super.c:mount_fs
  - fs/super.c:mount_single
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/super.c:mount_bdev
  - fs/super.c:mount_ns
  - fs/libfs.c:mount_pseudo_xattr
  - fs/kernfs/mount.c:kernfs_mount_ns
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
```
**Symbols:**

```
ffffffff812483d0-ffffffff81248440: deactivate_locked_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void deactivate_locked_super(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81253cd0)
Location: fs/super.c:302
Inline: False
Direct callers:
  - fs/super.c:thaw_super
  - fs/super.c:freeze_super
  - fs/super.c:freeze_super
  - fs/super.c:mount_fs
  - fs/super.c:mount_single
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/super.c:mount_bdev
  - fs/super.c:mount_ns
  - fs/libfs.c:mount_pseudo_xattr
  - fs/kernfs/mount.c:kernfs_mount_ns
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
```
**Symbols:**

```
ffffffff81253cd0-ffffffff81253d40: deactivate_locked_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void deactivate_locked_super(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81275dd0)
Location: fs/super.c:306
Inline: False
Direct callers:
  - fs/super.c:thaw_super
  - fs/super.c:freeze_super
  - fs/super.c:freeze_super
  - fs/super.c:mount_fs
  - fs/super.c:mount_single
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/super.c:mount_bdev
  - fs/super.c:mount_ns
  - fs/super.c:sget_userns
  - fs/libfs.c:mount_pseudo_xattr
  - fs/kernfs/mount.c:kernfs_mount_ns
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
```
**Symbols:**

```
ffffffff81275dd0-ffffffff81275e45: deactivate_locked_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void deactivate_locked_super(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff8129c420)
Location: fs/super.c:320
Inline: False
Direct callers:
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
  - fs/super.c:freeze_super
  - fs/super.c:mount_fs
  - fs/super.c:mount_single
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/super.c:mount_bdev
  - fs/super.c:mount_ns
  - fs/libfs.c:mount_pseudo_xattr
  - fs/kernfs/mount.c:kernfs_mount_ns
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
```
**Symbols:**

```
ffffffff8129c420-ffffffff8129c495: deactivate_locked_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void deactivate_locked_super(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812b1560)
Location: fs/super.c:324
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_do_mount
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
  - fs/super.c:freeze_super
  - fs/super.c:mount_fs
  - fs/super.c:mount_single
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/super.c:mount_bdev
  - fs/super.c:mount_ns
  - fs/libfs.c:mount_pseudo_xattr
  - fs/kernfs/mount.c:kernfs_mount_ns
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
```
**Symbols:**

```
ffffffff812b1560-ffffffff812b15d5: deactivate_locked_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void deactivate_locked_super(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812ce2b0)
Location: fs/super.c:325
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
  - fs/super.c:freeze_super
  - fs/super.c:mount_single
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/super.c:mount_bdev
  - fs/super.c:vfs_get_super
  - fs/fs_context.c:fc_drop_locked
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
```
**Symbols:**

```
ffffffff812ce2b0-ffffffff812ce32a: deactivate_locked_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void deactivate_locked_super(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812dfd60)
Location: fs/super.c:329
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
  - fs/super.c:freeze_super
  - fs/super.c:mount_single
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/super.c:mount_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:vfs_get_super
  - fs/fs_context.c:fc_drop_locked
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
```
**Symbols:**

```
ffffffff812dfd60-ffffffff812dfdda: deactivate_locked_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void deactivate_locked_super(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81317670)
Location: fs/super.c:329
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
  - fs/super.c:freeze_super
  - fs/super.c:mount_single
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/super.c:mount_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_keyed
  - fs/super.c:get_tree_single
  - fs/super.c:get_tree_nodev
  - fs/super.c:deactivate_super
  - fs/fs_context.c:fc_drop_locked
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
```
**Symbols:**

```
ffffffff81317670-ffffffff81317711: deactivate_locked_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void deactivate_locked_super(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff813228d0)
Location: fs/super.c:329
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
  - fs/super.c:freeze_super
  - fs/super.c:mount_single
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/super.c:mount_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_keyed
  - fs/super.c:get_tree_single
  - fs/super.c:get_tree_nodev
  - fs/super.c:deactivate_super
  - fs/fs_context.c:fc_drop_locked
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/fuse/dir.c:fuse_dentry_automount
```
**Symbols:**

```
ffffffff813228d0-ffffffff81322971: deactivate_locked_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void deactivate_locked_super(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81328990)
Location: fs/super.c:329
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
  - fs/super.c:freeze_super
  - fs/super.c:mount_single
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/super.c:mount_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_keyed
  - fs/super.c:get_tree_single
  - fs/super.c:get_tree_nodev
  - fs/super.c:deactivate_super
  - fs/fs_context.c:fc_drop_locked
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/fuse/dir.c:fuse_dentry_automount
```
**Symbols:**

```
ffffffff81328990-ffffffff81328a31: deactivate_locked_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void deactivate_locked_super(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81375f60)
Location: fs/super.c:329
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
  - fs/super.c:freeze_super
  - fs/super.c:freeze_super
  - fs/super.c:mount_single
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/super.c:mount_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_keyed
  - fs/super.c:get_tree_single
  - fs/super.c:get_tree_nodev
  - fs/super.c:deactivate_super
  - fs/fs_context.c:fc_drop_locked
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/fuse/inode.c:fuse_get_tree_submount
  - drivers/base/devtmpfs.c:public_dev_mount
```
**Symbols:**

```
ffffffff81375f60-ffffffff81376001: deactivate_locked_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void deactivate_locked_super(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff813f4f10)
Location: fs/super.c:327
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
  - fs/super.c:freeze_super
  - fs/super.c:freeze_super
  - fs/super.c:mount_single
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/super.c:mount_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_keyed
  - fs/super.c:get_tree_single
  - fs/super.c:get_tree_nodev
  - fs/fs_context.c:fc_drop_locked
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/fuse/inode.c:fuse_get_tree_submount
  - drivers/base/devtmpfs.c:public_dev_mount
```
**Symbols:**

```
ffffffff813f4f10-ffffffff813f4fb3: deactivate_locked_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void deactivate_locked_super(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff8147e0a0)
Location: fs/super.c:327
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
  - fs/super.c:freeze_super
  - fs/super.c:freeze_super
  - fs/super.c:mount_single
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/super.c:mount_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:vfs_get_super
  - fs/fs_context.c:fc_drop_locked
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/fuse/inode.c:fuse_get_tree_submount
  - drivers/base/devtmpfs.c:public_dev_mount
```
**Symbols:**

```
ffffffff8147e0a0-ffffffff8147e143: deactivate_locked_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void deactivate_locked_super(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff814b3050)
Location: fs/super.c:325
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
  - fs/super.c:freeze_super
  - fs/super.c:freeze_super
  - fs/super.c:mount_single
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/super.c:mount_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:vfs_get_super
  - fs/fs_context.c:fc_drop_locked
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/fuse/inode.c:fuse_get_tree_submount
  - drivers/base/devtmpfs.c:public_dev_mount
```
**Symbols:**

```
ffffffff814b3050-ffffffff814b30f3: deactivate_locked_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void deactivate_locked_super(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff814e4ab0)
Location: fs/super.c:467
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - fs/super.c:thaw_super_locked
  - fs/super.c:mount_single
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/super.c:mount_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_keyed
  - fs/super.c:get_tree_single
  - fs/super.c:get_tree_nodev
  - fs/fs_context.c:fc_drop_locked
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/fuse/inode.c:fuse_get_tree_submount
  - drivers/base/devtmpfs.c:public_dev_mount
```
**Symbols:**

```
ffffffff814e4ab0-ffffffff814e4b63: deactivate_locked_super (STB_GLOBAL)
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
void deactivate_locked_super(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffff800010386a40)
Location: fs/super.c:329
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
  - fs/super.c:freeze_super
  - fs/super.c:mount_single
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/super.c:mount_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:vfs_get_super
  - fs/fs_context.c:fc_drop_locked
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
```
**Symbols:**

```
ffff800010386a40-ffff800010386ae8: deactivate_locked_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void deactivate_locked_super(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (c056f36c)
Location: fs/super.c:329
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
  - fs/super.c:freeze_super
  - fs/super.c:mount_single
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/super.c:mount_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:vfs_get_super
  - fs/fs_context.c:fc_drop_locked
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - drivers/mtd/mtdsuper.c:mtd_get_sb
```
**Symbols:**

```
c056f36c-c056f3fc: deactivate_locked_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void deactivate_locked_super(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (c00000000047ca80)
Location: fs/super.c:329
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
  - fs/super.c:freeze_super
  - fs/super.c:mount_single
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/super.c:mount_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:vfs_get_super
  - fs/fs_context.c:fc_drop_locked
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
```
**Symbols:**

```
c00000000047ca80-c00000000047cb64: deactivate_locked_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void deactivate_locked_super(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffe0002592c4)
Location: fs/super.c:329
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
  - fs/super.c:freeze_super
  - fs/super.c:mount_single
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/super.c:mount_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:vfs_get_super
  - fs/fs_context.c:fc_drop_locked
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
```
**Symbols:**

```
ffffffe0002592c4-ffffffe000259360: deactivate_locked_super (STB_GLOBAL)
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
void deactivate_locked_super(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812d8340)
Location: fs/super.c:329
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
  - fs/super.c:freeze_super
  - fs/super.c:mount_single
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/super.c:mount_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:vfs_get_super
  - fs/fs_context.c:fc_drop_locked
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
```
**Symbols:**

```
ffffffff812d8340-ffffffff812d83ba: deactivate_locked_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void deactivate_locked_super(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812c8fc0)
Location: fs/super.c:329
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
  - fs/super.c:freeze_super
  - fs/super.c:mount_single
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/super.c:mount_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:vfs_get_super
  - fs/fs_context.c:fc_drop_locked
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
```
**Symbols:**

```
ffffffff812c8fc0-ffffffff812c903a: deactivate_locked_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void deactivate_locked_super(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812d6150)
Location: fs/super.c:329
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
  - fs/super.c:freeze_super
  - fs/super.c:mount_single
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/super.c:mount_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:vfs_get_super
  - fs/fs_context.c:fc_drop_locked
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
```
**Symbols:**

```
ffffffff812d6150-ffffffff812d61ca: deactivate_locked_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void deactivate_locked_super(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812e6d60)
Location: fs/super.c:329
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
  - fs/super.c:freeze_super
  - fs/super.c:mount_single
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/super.c:mount_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:get_tree_bdev
  - fs/super.c:vfs_get_super
  - fs/fs_context.c:fc_drop_locked
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
```
**Symbols:**

```
ffffffff812e6d60-ffffffff812e6dda: deactivate_locked_super (STB_GLOBAL)
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
