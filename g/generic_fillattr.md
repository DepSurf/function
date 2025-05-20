# Function: <code>generic_fillattr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void generic_fillattr(struct inode *inode, struct kstat *stat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff81211230)
Location: fs/stat.c:21
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getattr
  - fs/stat.c:vfs_getattr_nosec
  - fs/libfs.c:simple_getattr
  - fs/libfs.c:empty_dir_getattr
  - fs/proc/root.c:proc_root_getattr
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_task_getattr
  - fs/proc/generic.c:proc_getattr
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_net.c:proc_tgid_net_getattr
  - fs/kernfs/inode.c:kernfs_iop_getattr
  - fs/ext4/inode.c:ext4_getattr
  - fs/fat/file.c:fat_getattr
  - fs/ecryptfs/inode.c:ecryptfs_getattr
  - fs/fuse/dir.c:fuse_update_attributes
```
**Symbols:**

```
ffffffff81211230-ffffffff812112c4: generic_fillattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void generic_fillattr(struct inode *inode, struct kstat *stat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff81237ce0)
Location: fs/stat.c:21
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getattr
  - fs/stat.c:vfs_getattr_nosec
  - fs/libfs.c:empty_dir_getattr
  - fs/libfs.c:simple_getattr
  - fs/proc/root.c:proc_root_getattr
  - fs/proc/base.c:proc_task_getattr
  - fs/proc/base.c:pid_getattr
  - fs/proc/generic.c:proc_getattr
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_net.c:proc_tgid_net_getattr
  - fs/kernfs/inode.c:kernfs_iop_getattr
  - fs/ext4/inode.c:ext4_getattr
  - fs/fat/file.c:fat_getattr
  - fs/ecryptfs/inode.c:ecryptfs_getattr
  - fs/fuse/dir.c:fuse_update_attributes
```
**Symbols:**

```
ffffffff81237ce0-ffffffff81237d74: generic_fillattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void generic_fillattr(struct inode *inode, struct kstat *stat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff8124a9a0)
Location: fs/stat.c:21
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getattr
  - fs/stat.c:vfs_getattr_nosec
  - fs/libfs.c:empty_dir_getattr
  - fs/libfs.c:simple_getattr
  - fs/proc/root.c:proc_root_getattr
  - fs/proc/base.c:proc_task_getattr
  - fs/proc/base.c:pid_getattr
  - fs/proc/generic.c:proc_getattr
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_net.c:proc_tgid_net_getattr
  - fs/kernfs/inode.c:kernfs_iop_getattr
  - fs/ext4/inode.c:ext4_getattr
  - fs/fat/file.c:fat_getattr
  - fs/ecryptfs/inode.c:ecryptfs_getattr
  - fs/fuse/dir.c:fuse_update_attributes
```
**Symbols:**

```
ffffffff8124a9a0-ffffffff8124aa34: generic_fillattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void generic_fillattr(struct inode *inode, struct kstat *stat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812563a0)
Location: fs/stat.c:32
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getattr
  - fs/stat.c:vfs_getattr_nosec
  - fs/libfs.c:empty_dir_getattr
  - fs/libfs.c:simple_getattr
  - fs/proc/root.c:proc_root_getattr
  - fs/proc/base.c:proc_task_getattr
  - fs/proc/base.c:pid_getattr
  - fs/proc/generic.c:proc_getattr
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_net.c:proc_tgid_net_getattr
  - fs/kernfs/inode.c:kernfs_iop_getattr
  - fs/ext4/inode.c:ext4_getattr
  - fs/fat/file.c:fat_getattr
  - fs/ecryptfs/inode.c:ecryptfs_getattr
  - fs/ecryptfs/inode.c:ecryptfs_getattr_link
  - fs/fuse/dir.c:fuse_update_attributes
```
**Symbols:**

```
ffffffff812563a0-ffffffff81256458: generic_fillattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void generic_fillattr(struct inode *inode, struct kstat *stat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812785e0)
Location: fs/stat.c:33
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getattr
  - fs/stat.c:vfs_getattr_nosec
  - fs/libfs.c:empty_dir_getattr
  - fs/libfs.c:simple_getattr
  - fs/proc/root.c:proc_root_getattr
  - fs/proc/base.c:proc_task_getattr
  - fs/proc/base.c:pid_getattr
  - fs/proc/generic.c:proc_getattr
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_net.c:proc_tgid_net_getattr
  - fs/kernfs/inode.c:kernfs_iop_getattr
  - fs/ext4/inode.c:ext4_getattr
  - fs/fat/file.c:fat_getattr
  - fs/ecryptfs/inode.c:ecryptfs_getattr
  - fs/ecryptfs/inode.c:ecryptfs_getattr_link
  - fs/fuse/dir.c:fuse_getattr
```
**Symbols:**

```
ffffffff812785e0-ffffffff81278698: generic_fillattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void generic_fillattr(struct inode *inode, struct kstat *stat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff8129f000)
Location: fs/stat.c:33
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getattr
  - fs/stat.c:vfs_getattr_nosec
  - fs/libfs.c:empty_dir_getattr
  - fs/libfs.c:simple_getattr
  - fs/proc/root.c:proc_root_getattr
  - fs/proc/base.c:proc_task_getattr
  - fs/proc/base.c:pid_getattr
  - fs/proc/generic.c:proc_getattr
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_net.c:proc_tgid_net_getattr
  - fs/kernfs/inode.c:kernfs_iop_getattr
  - fs/ext4/inode.c:ext4_getattr
  - fs/fat/file.c:fat_getattr
  - fs/ecryptfs/inode.c:ecryptfs_getattr
  - fs/ecryptfs/inode.c:ecryptfs_getattr_link
  - fs/fuse/dir.c:fuse_getattr
```
**Symbols:**

```
ffffffff8129f000-ffffffff8129f0b4: generic_fillattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void generic_fillattr(struct inode *inode, struct kstat *stat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812b3fe0)
Location: fs/stat.c:33
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getattr
  - fs/stat.c:vfs_getattr_nosec
  - fs/libfs.c:empty_dir_getattr
  - fs/libfs.c:simple_getattr
  - fs/proc/root.c:proc_root_getattr
  - fs/proc/base.c:proc_task_getattr
  - fs/proc/base.c:pid_getattr
  - fs/proc/generic.c:proc_getattr
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_net.c:proc_tgid_net_getattr
  - fs/kernfs/inode.c:kernfs_iop_getattr
  - fs/ext4/inode.c:ext4_getattr
  - fs/fat/file.c:fat_getattr
  - fs/ecryptfs/inode.c:ecryptfs_getattr
  - fs/ecryptfs/inode.c:ecryptfs_getattr_link
  - fs/fuse/dir.c:fuse_getattr
```
**Symbols:**

```
ffffffff812b3fe0-ffffffff812b4095: generic_fillattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void generic_fillattr(struct inode *inode, struct kstat *stat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812d0d40)
Location: fs/stat.c:33
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getattr
  - fs/stat.c:vfs_getattr_nosec
  - fs/libfs.c:empty_dir_getattr
  - fs/libfs.c:simple_getattr
  - fs/proc/root.c:proc_root_getattr
  - fs/proc/base.c:proc_task_getattr
  - fs/proc/base.c:pid_getattr
  - fs/proc/generic.c:proc_getattr
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_net.c:proc_tgid_net_getattr
  - fs/kernfs/inode.c:kernfs_iop_getattr
  - fs/ext4/inode.c:ext4_getattr
  - fs/fat/file.c:fat_getattr
  - fs/ecryptfs/inode.c:ecryptfs_getattr
  - fs/ecryptfs/inode.c:ecryptfs_getattr_link
  - fs/fuse/dir.c:fuse_getattr
```
**Symbols:**

```
ffffffff812d0d40-ffffffff812d0dd6: generic_fillattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void generic_fillattr(struct inode *inode, struct kstat *stat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812e28d0)
Location: fs/stat.c:33
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getattr
  - fs/stat.c:vfs_getattr_nosec
  - fs/libfs.c:empty_dir_getattr
  - fs/libfs.c:simple_getattr
  - fs/proc/root.c:proc_root_getattr
  - fs/proc/base.c:proc_task_getattr
  - fs/proc/base.c:pid_getattr
  - fs/proc/generic.c:proc_getattr
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_net.c:proc_tgid_net_getattr
  - fs/kernfs/inode.c:kernfs_iop_getattr
  - fs/ext4/inode.c:ext4_getattr
  - fs/fat/file.c:fat_getattr
  - fs/ecryptfs/inode.c:ecryptfs_getattr
  - fs/ecryptfs/inode.c:ecryptfs_getattr_link
  - fs/fuse/dir.c:fuse_getattr
```
**Symbols:**

```
ffffffff812e28d0-ffffffff812e2966: generic_fillattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void generic_fillattr(struct inode *inode, struct kstat *stat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff81319c50)
Location: fs/stat.c:36
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getattr
  - fs/stat.c:vfs_getattr_nosec
  - fs/libfs.c:empty_dir_getattr
  - fs/libfs.c:simple_getattr
  - fs/proc/root.c:proc_root_getattr
  - fs/proc/base.c:proc_task_getattr
  - fs/proc/base.c:pid_getattr
  - fs/proc/generic.c:proc_getattr
  - fs/proc/generic.c:proc_getattr
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_net.c:proc_tgid_net_getattr
  - fs/kernfs/inode.c:kernfs_iop_getattr
  - fs/ext4/inode.c:ext4_getattr
  - fs/fat/file.c:fat_getattr
  - fs/ecryptfs/inode.c:ecryptfs_getattr
  - fs/ecryptfs/inode.c:ecryptfs_getattr_link
  - fs/fuse/dir.c:fuse_getattr
```
**Symbols:**

```
ffffffff81319c50-ffffffff81319ce6: generic_fillattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void generic_fillattr(struct inode *inode, struct kstat *stat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff813252e0)
Location: fs/stat.c:36
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getattr
  - fs/stat.c:vfs_getattr_nosec
  - fs/libfs.c:empty_dir_getattr
  - fs/libfs.c:simple_getattr
  - fs/proc/root.c:proc_root_getattr
  - fs/proc/base.c:proc_task_getattr
  - fs/proc/base.c:pid_getattr
  - fs/proc/generic.c:proc_getattr
  - fs/proc/generic.c:proc_getattr
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_net.c:proc_tgid_net_getattr
  - fs/kernfs/inode.c:kernfs_iop_getattr
  - fs/ext4/inode.c:ext4_getattr
  - fs/fat/file.c:fat_getattr
  - fs/ecryptfs/inode.c:ecryptfs_getattr
  - fs/ecryptfs/inode.c:ecryptfs_getattr_link
  - fs/fuse/dir.c:fuse_getattr
```
**Symbols:**

```
ffffffff813252e0-ffffffff81325376: generic_fillattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void generic_fillattr(struct user_namespace *mnt_userns, struct inode *inode, struct kstat *stat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff8132b4c0)
Location: fs/stat.c:43
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getattr
  - fs/stat.c:vfs_getattr_nosec
  - fs/libfs.c:empty_dir_getattr
  - fs/libfs.c:simple_getattr
  - fs/proc/root.c:proc_root_getattr
  - fs/proc/base.c:proc_task_getattr
  - fs/proc/base.c:pid_getattr
  - fs/proc/generic.c:proc_getattr
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_net.c:proc_tgid_net_getattr
  - fs/kernfs/inode.c:kernfs_iop_getattr
  - fs/ext4/inode.c:ext4_getattr
  - fs/fat/file.c:fat_getattr
  - fs/ecryptfs/inode.c:ecryptfs_getattr
  - fs/ecryptfs/inode.c:ecryptfs_getattr_link
  - fs/fuse/dir.c:fuse_getattr
```
**Symbols:**

```
ffffffff8132b4c0-ffffffff8132b584: generic_fillattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void generic_fillattr(struct user_namespace *mnt_userns, struct inode *inode, struct kstat *stat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/stat.c (0)
Location: fs/stat.c:43
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getattr
  - fs/stat.c:vfs_getattr_nosec
  - fs/libfs.c:empty_dir_getattr
  - fs/libfs.c:simple_getattr
  - fs/proc/root.c:proc_root_getattr
  - fs/proc/base.c:proc_task_getattr
  - fs/proc/base.c:pid_getattr
  - fs/proc/generic.c:proc_getattr
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_net.c:proc_tgid_net_getattr
  - fs/kernfs/inode.c:kernfs_iop_getattr
  - fs/ext4/inode.c:ext4_getattr
  - fs/fat/file.c:fat_getattr
  - fs/ecryptfs/inode.c:ecryptfs_getattr
  - fs/ecryptfs/inode.c:ecryptfs_getattr_link
  - fs/fuse/dir.c:fuse_getattr
```
**Symbols:**

```
ffffffff81cc397e-ffffffff81cc399e: generic_fillattr.cold (STB_LOCAL)
ffffffff81378c30-ffffffff81378cff: generic_fillattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void generic_fillattr(struct user_namespace *mnt_userns, struct inode *inode, struct kstat *stat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/stat.c (0)
Location: fs/stat.c:43
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getattr
  - fs/stat.c:vfs_getattr_nosec
  - fs/libfs.c:empty_dir_getattr
  - fs/libfs.c:simple_getattr
  - fs/proc/root.c:proc_root_getattr
  - fs/proc/base.c:proc_task_getattr
  - fs/proc/base.c:pid_getattr
  - fs/proc/generic.c:proc_getattr
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_net.c:proc_tgid_net_getattr
  - fs/kernfs/inode.c:kernfs_iop_getattr
  - fs/ext4/inode.c:ext4_getattr
  - fs/fat/file.c:fat_getattr
  - fs/ecryptfs/inode.c:ecryptfs_getattr
  - fs/ecryptfs/inode.c:ecryptfs_getattr_link
  - fs/fuse/dir.c:fuse_getattr
```
**Symbols:**

```
ffffffff81e760f5-ffffffff81e76115: generic_fillattr.cold (STB_LOCAL)
ffffffff813f7ff0-ffffffff813f8137: generic_fillattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void generic_fillattr(struct user_namespace *mnt_userns, struct inode *inode, struct kstat *stat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/stat.c (0)
Location: fs/stat.c:44
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getattr
  - fs/stat.c:vfs_getattr_nosec
  - fs/libfs.c:empty_dir_getattr
  - fs/libfs.c:simple_getattr
  - fs/proc/root.c:proc_root_getattr
  - fs/proc/base.c:proc_task_getattr
  - fs/proc/base.c:pid_getattr
  - fs/proc/generic.c:proc_getattr
  - fs/proc/fd.c:proc_fd_getattr
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_net.c:proc_tgid_net_getattr
  - fs/kernfs/inode.c:kernfs_iop_getattr
  - fs/ext4/inode.c:ext4_getattr
  - fs/fat/file.c:fat_getattr
  - fs/ecryptfs/inode.c:ecryptfs_getattr
  - fs/ecryptfs/inode.c:ecryptfs_getattr_link
  - fs/fuse/dir.c:fuse_getattr
```
**Symbols:**

```
ffffffff82068778-ffffffff82068798: generic_fillattr.cold (STB_LOCAL)
ffffffff81481470-ffffffff814815d6: generic_fillattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void generic_fillattr(struct mnt_idmap *idmap, struct inode *inode, struct kstat *stat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/stat.c (0)
Location: fs/stat.c:45
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getattr
  - fs/stat.c:vfs_getattr_nosec
  - fs/libfs.c:empty_dir_getattr
  - fs/libfs.c:simple_getattr
  - fs/proc/root.c:proc_root_getattr
  - fs/proc/base.c:proc_task_getattr
  - fs/proc/base.c:pid_getattr
  - fs/proc/generic.c:proc_getattr
  - fs/proc/fd.c:proc_fd_getattr
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_net.c:proc_tgid_net_getattr
  - fs/kernfs/inode.c:kernfs_iop_getattr
  - fs/ext4/inode.c:ext4_getattr
  - fs/fat/file.c:fat_getattr
  - fs/ecryptfs/inode.c:ecryptfs_getattr
  - fs/ecryptfs/inode.c:ecryptfs_getattr_link
  - fs/fuse/dir.c:fuse_getattr
```
**Symbols:**

```
ffffffff820e807b-ffffffff820e809b: generic_fillattr.cold (STB_LOCAL)
ffffffff814b60a0-ffffffff814b61a1: generic_fillattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void generic_fillattr(struct mnt_idmap *idmap, u32 request_mask, struct inode *inode, struct kstat *stat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/stat.c (0)
Location: fs/stat.c:46
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getattr
  - fs/stat.c:vfs_getattr_nosec
  - fs/libfs.c:empty_dir_getattr
  - fs/libfs.c:simple_getattr
  - fs/proc/root.c:proc_root_getattr
  - fs/proc/base.c:proc_task_getattr
  - fs/proc/base.c:pid_getattr
  - fs/proc/generic.c:proc_getattr
  - fs/proc/fd.c:proc_fd_getattr
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_net.c:proc_tgid_net_getattr
  - fs/kernfs/inode.c:kernfs_iop_getattr
  - fs/ext4/inode.c:ext4_getattr
  - fs/fat/file.c:fat_getattr
  - fs/ecryptfs/inode.c:ecryptfs_getattr
  - fs/ecryptfs/inode.c:ecryptfs_getattr_link
  - fs/fuse/dir.c:fuse_update_get_attr
  - fs/tracefs/inode.c:tracefs_getattr
  - fs/tracefs/event_inode.c:eventfs_get_attr
```
**Symbols:**

```
ffffffff821c4db7-ffffffff821c4dd7: generic_fillattr.cold (STB_LOCAL)
ffffffff814e83b0-ffffffff814e84fc: generic_fillattr (STB_GLOBAL)
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
void generic_fillattr(struct inode *inode, struct kstat *stat);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffff80001038a4c8)
Location: fs/stat.c:33
Inline: True
Inline callers:
  - fs/stat.c:vfs_getattr_nosec
Direct callers:
  - mm/shmem.c:shmem_getattr
  - mm/shmem.c:shmem_getattr
  - fs/libfs.c:empty_dir_getattr
  - fs/libfs.c:simple_getattr
  - fs/proc/root.c:proc_root_getattr
  - fs/proc/base.c:proc_task_getattr
  - fs/proc/base.c:pid_getattr
  - fs/proc/generic.c:proc_getattr
  - fs/proc/generic.c:proc_getattr
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_net.c:proc_tgid_net_getattr
  - fs/kernfs/inode.c:kernfs_iop_getattr
  - fs/ext4/inode.c:ext4_getattr
  - fs/fat/file.c:fat_getattr
  - fs/ecryptfs/inode.c:ecryptfs_getattr
  - fs/ecryptfs/inode.c:ecryptfs_getattr_link
  - fs/fuse/dir.c:fuse_getattr
```
**Symbols:**

```
ffff80001038a270-ffff80001038a30c: generic_fillattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void generic_fillattr(struct inode *inode, struct kstat *stat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (c0572594)
Location: fs/stat.c:33
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getattr
  - fs/stat.c:vfs_getattr_nosec
  - fs/libfs.c:empty_dir_getattr
  - fs/libfs.c:simple_getattr
  - fs/proc/root.c:proc_root_getattr
  - fs/proc/base.c:proc_task_getattr
  - fs/proc/base.c:pid_getattr
  - fs/proc/generic.c:proc_getattr
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_net.c:proc_tgid_net_getattr
  - fs/kernfs/inode.c:kernfs_iop_getattr
  - fs/ext4/inode.c:ext4_getattr
  - fs/fat/file.c:fat_getattr
  - fs/ecryptfs/inode.c:ecryptfs_getattr
  - fs/ecryptfs/inode.c:ecryptfs_getattr_link
```
**Symbols:**

```
c0572594-c0572698: generic_fillattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void generic_fillattr(struct inode *inode, struct kstat *stat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (c0000000004814f0)
Location: fs/stat.c:33
Inline: False
Direct callers:
  - fs/stat.c:vfs_getattr_nosec
  - fs/libfs.c:empty_dir_getattr
  - fs/libfs.c:simple_getattr
  - fs/proc/root.c:proc_root_getattr
  - fs/proc/base.c:proc_task_getattr
  - fs/proc/base.c:pid_getattr
  - fs/proc/generic.c:proc_getattr
  - fs/proc/generic.c:proc_getattr
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_net.c:proc_tgid_net_getattr
  - fs/kernfs/inode.c:kernfs_iop_getattr
  - fs/ext4/inode.c:ext4_getattr
  - fs/fat/file.c:fat_getattr
  - fs/ecryptfs/inode.c:ecryptfs_getattr
  - fs/ecryptfs/inode.c:ecryptfs_getattr_link
  - fs/fuse/dir.c:fuse_getattr
```
**Symbols:**

```
c0000000004814f0-c000000000481588: generic_fillattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void generic_fillattr(struct inode *inode, struct kstat *stat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffe00025c274)
Location: fs/stat.c:33
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getattr
  - fs/stat.c:vfs_getattr_nosec
  - fs/libfs.c:empty_dir_getattr
  - fs/libfs.c:simple_getattr
  - fs/proc/root.c:proc_root_getattr
  - fs/proc/base.c:proc_task_getattr
  - fs/proc/base.c:pid_getattr
  - fs/proc/generic.c:proc_getattr
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_net.c:proc_tgid_net_getattr
  - fs/kernfs/inode.c:kernfs_iop_getattr
  - fs/ext4/inode.c:ext4_getattr
  - fs/fat/file.c:fat_getattr
  - fs/ecryptfs/inode.c:ecryptfs_getattr
  - fs/ecryptfs/inode.c:ecryptfs_getattr_link
  - fs/fuse/dir.c:fuse_getattr
```
**Symbols:**

```
ffffffe00025c274-ffffffe00025c304: generic_fillattr (STB_GLOBAL)
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
void generic_fillattr(struct inode *inode, struct kstat *stat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812daeb0)
Location: fs/stat.c:33
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getattr
  - fs/stat.c:vfs_getattr_nosec
  - fs/libfs.c:empty_dir_getattr
  - fs/libfs.c:simple_getattr
  - fs/proc/root.c:proc_root_getattr
  - fs/proc/base.c:proc_task_getattr
  - fs/proc/base.c:pid_getattr
  - fs/proc/generic.c:proc_getattr
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_net.c:proc_tgid_net_getattr
  - fs/kernfs/inode.c:kernfs_iop_getattr
  - fs/ext4/inode.c:ext4_getattr
  - fs/fat/file.c:fat_getattr
  - fs/ecryptfs/inode.c:ecryptfs_getattr
  - fs/ecryptfs/inode.c:ecryptfs_getattr_link
  - fs/fuse/dir.c:fuse_getattr
```
**Symbols:**

```
ffffffff812daeb0-ffffffff812daf46: generic_fillattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void generic_fillattr(struct inode *inode, struct kstat *stat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812cbb30)
Location: fs/stat.c:33
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getattr
  - fs/stat.c:vfs_getattr_nosec
  - fs/libfs.c:empty_dir_getattr
  - fs/libfs.c:simple_getattr
  - fs/proc/root.c:proc_root_getattr
  - fs/proc/base.c:proc_task_getattr
  - fs/proc/base.c:pid_getattr
  - fs/proc/generic.c:proc_getattr
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_net.c:proc_tgid_net_getattr
  - fs/kernfs/inode.c:kernfs_iop_getattr
  - fs/ext4/inode.c:ext4_getattr
  - fs/fat/file.c:fat_getattr
  - fs/ecryptfs/inode.c:ecryptfs_getattr
  - fs/ecryptfs/inode.c:ecryptfs_getattr_link
  - fs/fuse/dir.c:fuse_getattr
```
**Symbols:**

```
ffffffff812cbb30-ffffffff812cbbc6: generic_fillattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void generic_fillattr(struct inode *inode, struct kstat *stat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812d8cc0)
Location: fs/stat.c:33
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getattr
  - fs/stat.c:vfs_getattr_nosec
  - fs/libfs.c:empty_dir_getattr
  - fs/libfs.c:simple_getattr
  - fs/proc/root.c:proc_root_getattr
  - fs/proc/base.c:proc_task_getattr
  - fs/proc/base.c:pid_getattr
  - fs/proc/generic.c:proc_getattr
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_net.c:proc_tgid_net_getattr
  - fs/kernfs/inode.c:kernfs_iop_getattr
  - fs/ext4/inode.c:ext4_getattr
  - fs/fat/file.c:fat_getattr
  - fs/ecryptfs/inode.c:ecryptfs_getattr
  - fs/ecryptfs/inode.c:ecryptfs_getattr_link
  - fs/fuse/dir.c:fuse_getattr
```
**Symbols:**

```
ffffffff812d8cc0-ffffffff812d8d56: generic_fillattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void generic_fillattr(struct inode *inode, struct kstat *stat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812e9af0)
Location: fs/stat.c:33
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getattr
  - fs/stat.c:vfs_getattr_nosec
  - fs/libfs.c:empty_dir_getattr
  - fs/libfs.c:simple_getattr
  - fs/proc/root.c:proc_root_getattr
  - fs/proc/base.c:proc_task_getattr
  - fs/proc/base.c:pid_getattr
  - fs/proc/generic.c:proc_getattr
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_net.c:proc_tgid_net_getattr
  - fs/kernfs/inode.c:kernfs_iop_getattr
  - fs/ext4/inode.c:ext4_getattr
  - fs/fat/file.c:fat_getattr
  - fs/ecryptfs/inode.c:ecryptfs_getattr
  - fs/ecryptfs/inode.c:ecryptfs_getattr_link
  - fs/fuse/dir.c:fuse_getattr
```
**Symbols:**

```
ffffffff812e9af0-ffffffff812e9b86: generic_fillattr (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct user_namespace *mnt_userns</code>
</li>
<li>
<b>Param reordered. </b>
<code>inode, stat</code> ➡️ <code>mnt_userns, inode, stat</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mnt_idmap *idmap</code>
</li>
<li>
<b>Param removed. </b>
<code>struct user_namespace *mnt_userns</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 request_mask</code>
</li>
<li>
<b>Param reordered. </b>
<code>idmap, inode, stat</code> ➡️ <code>idmap, request_mask, inode, stat</code>
</li>
</ul>
</details>
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
