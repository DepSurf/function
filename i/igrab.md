# Function: <code>igrab</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct inode *igrab(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81227a50)
Location: fs/inode.c:1191
Inline: True
Direct callers:
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - fs/notify/inode_mark.c:fsnotify_set_inode_mark_mask_locked
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/fat/inode.c:fat_iget
  - fs/fat/nfs.c:fat_dget
  - fs/fuse/file.c:fuse_release_common
  - security/selinux/hooks.c:sb_finish_set_opts
```
**Symbols:**

```
ffffffff81227a50-ffffffff81227aa4: igrab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct inode *igrab(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81250070)
Location: fs/inode.c:1200
Inline: True
Direct callers:
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/events/core.c:perf_event_set_addr_filter
  - mm/shmem.c:shmem_unused_huge_shrink
  - fs/notify/inode_mark.c:fsnotify_set_inode_mark_mask_locked
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/fat/inode.c:fat_iget
  - fs/fat/nfs.c:fat_dget
  - fs/fuse/file.c:fuse_release_common
  - security/selinux/hooks.c:sb_finish_set_opts
```
**Symbols:**

```
ffffffff81250070-ffffffff812500c1: igrab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct inode *igrab(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81263110)
Location: fs/inode.c:1218
Inline: True
Direct callers:
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/events/core.c:perf_event_set_addr_filter
  - mm/shmem.c:shmem_unused_huge_shrink
  - fs/notify/inode_mark.c:fsnotify_set_inode_mark_mask_locked
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/fat/inode.c:fat_iget
  - fs/fat/nfs.c:fat_dget
  - fs/fuse/file.c:fuse_release_common
  - security/selinux/hooks.c:sb_finish_set_opts
```
**Symbols:**

```
ffffffff81263110-ffffffff81263161: igrab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct inode *igrab(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81270970)
Location: fs/inode.c:1219
Inline: True
Direct callers:
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/events/core.c:perf_event_parse_addr_filter
  - mm/shmem.c:shmem_unused_huge_shrink
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/notify/fdinfo.c:inotify_fdinfo
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/super.c:ext4_quota_off
  - fs/fat/inode.c:fat_iget
  - fs/fat/nfs.c:fat_dget
  - fs/fuse/file.c:fuse_release_common
  - security/selinux/hooks.c:sb_finish_set_opts
  - drivers/dax/super.c:dax_get_by_host
```
**Symbols:**

```
ffffffff81270970-ffffffff812709be: igrab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct inode *igrab(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812932a0)
Location: fs/inode.c:1219
Inline: True
Direct callers:
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/events/core.c:perf_event_parse_addr_filter
  - mm/shmem.c:shmem_unused_huge_shrink
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/notify/fdinfo.c:inotify_fdinfo
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/super.c:ext4_quota_off
  - fs/fat/inode.c:fat_iget
  - fs/fat/nfs.c:fat_dget
  - fs/fuse/file.c:fuse_release_common
  - security/selinux/hooks.c:sb_finish_set_opts
  - drivers/dax/super.c:dax_get_by_host
```
**Symbols:**

```
ffffffff812932a0-ffffffff812932ee: igrab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct inode *igrab(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812b95b0)
Location: fs/inode.c:1240
Inline: False
Direct callers:
  - mm/shmem.c:shmem_unused_huge_shrink
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/notify/fdinfo.c:inotify_fdinfo
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/super.c:ext4_quota_off
  - fs/fuse/file.c:fuse_release_common
  - security/selinux/hooks.c:sb_finish_set_opts
  - drivers/dax/super.c:dax_get_by_host
```
**Symbols:**

```
ffffffff812b95b0-ffffffff812b9601: igrab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct inode *igrab(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812ce800)
Location: fs/inode.c:1271
Inline: False
Direct callers:
  - mm/shmem.c:shmem_unused_huge_shrink
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/notify/fdinfo.c:inotify_fdinfo
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/super.c:ext4_quota_off
  - fs/fuse/file.c:fuse_release_common
  - security/selinux/hooks.c:sb_finish_set_opts
  - drivers/dax/super.c:dax_get_by_host
```
**Symbols:**

```
ffffffff812ce800-ffffffff812ce851: igrab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct inode *igrab(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812eb700)
Location: fs/inode.c:1284
Inline: False
Direct callers:
  - mm/shmem.c:shmem_unused_huge_shrink
  - fs/notify/mark.c:fsnotify_add_mark_list
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/notify/fdinfo.c:inotify_fdinfo
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/super.c:ext4_quota_off
  - fs/fuse/file.c:fuse_release_common
  - security/selinux/hooks.c:sb_finish_set_opts
  - drivers/dax/super.c:dax_get_by_host
```
**Symbols:**

```
ffffffff812eb700-ffffffff812eb751: igrab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct inode *igrab(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812fd230)
Location: fs/inode.c:1295
Inline: False
Direct callers:
  - mm/shmem.c:shmem_unused_huge_shrink
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/notify/fdinfo.c:inotify_fdinfo
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/super.c:ext4_quota_off
  - fs/fuse/file.c:fuse_release_common
  - security/selinux/hooks.c:sb_finish_set_opts
  - drivers/dax/super.c:dax_get_by_host
```
**Symbols:**

```
ffffffff812fd230-ffffffff812fd281: igrab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct inode *igrab(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81336040)
Location: fs/inode.c:1293
Inline: False
Direct callers:
  - mm/shmem.c:shmem_unused_huge_shrink
  - fs/notify/mark.c:fsnotify_add_mark_list
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/notify/fdinfo.c:inotify_fdinfo
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
  - fs/ext4/super.c:ext4_quota_off
  - fs/fat/inode.c:fat_iget
  - fs/fat/nfs.c:fat_dget
  - fs/fuse/file.c:fuse_release_common
  - security/selinux/hooks.c:sb_finish_set_opts
  - drivers/dax/super.c:dax_get_by_host
```
**Symbols:**

```
ffffffff81336040-ffffffff81336091: igrab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct inode *igrab(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff813419d0)
Location: fs/inode.c:1292
Inline: False
Direct callers:
  - mm/shmem.c:shmem_unused_huge_shrink
  - fs/block_dev.c:__blkdev_get
  - fs/notify/mark.c:fsnotify_add_mark_list
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/notify/fdinfo.c:inotify_fdinfo
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
  - fs/ext4/super.c:ext4_quota_off
  - fs/fat/inode.c:fat_iget
  - fs/fat/nfs.c:fat_dget
  - fs/fuse/file.c:fuse_release_common
  - security/selinux/hooks.c:sb_finish_set_opts
  - drivers/dax/super.c:dax_get_by_host
```
**Symbols:**

```
ffffffff813419d0-ffffffff81341a21: igrab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct inode *igrab(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81347dc0)
Location: fs/inode.c:1299
Inline: False
Direct callers:
  - mm/shmem.c:shmem_unused_huge_shrink
  - fs/block_dev.c:__blkdev_get
  - fs/notify/mark.c:fsnotify_add_mark_list
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/notify/fdinfo.c:inotify_fdinfo
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
  - fs/ext4/super.c:ext4_quota_off
  - fs/fat/inode.c:fat_iget
  - fs/fat/nfs.c:fat_dget
  - fs/fuse/file.c:fuse_file_release
  - security/selinux/hooks.c:sb_finish_set_opts
  - drivers/dax/super.c:dax_get_by_host
```
**Symbols:**

```
ffffffff81347dc0-ffffffff81347e11: igrab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct inode *igrab(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff813959d0)
Location: fs/inode.c:1303
Inline: False
Direct callers:
  - mm/shmem.c:shmem_unused_huge_shrink
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/notify/fdinfo.c:inotify_fdinfo
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/fat/inode.c:fat_iget
  - fs/fat/nfs.c:fat_dget
  - fs/fuse/file.c:fuse_file_release
  - security/selinux/hooks.c:sb_finish_set_opts
  - drivers/dax/super.c:dax_get_by_host
```
**Symbols:**

```
ffffffff813959d0-ffffffff81395a21: igrab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct inode *igrab(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81415b10)
Location: fs/inode.c:1384
Inline: False
Direct callers:
  - mm/shmem.c:shmem_unused_huge_shrink
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/notify/fdinfo.c:inotify_fdinfo
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/fat/inode.c:fat_iget
  - fs/fat/nfs.c:fat_dget
  - fs/fuse/file.c:fuse_file_release
  - security/selinux/hooks.c:sb_finish_set_opts
  - drivers/dax/super.c:fs_dax_get_by_bdev
```
**Symbols:**

```
ffffffff81415b10-ffffffff81415b69: igrab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct inode *igrab(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff814a0f00)
Location: fs/inode.c:1386
Inline: False
Direct callers:
  - mm/shmem.c:shmem_unused_huge_shrink
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/notify/fdinfo.c:inotify_fdinfo
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
  - fs/ext4/super.c:ext4_quota_off
  - fs/ext4/super.c:ext4_enable_quotas
  - fs/fat/inode.c:fat_iget
  - fs/fat/nfs.c:fat_dget
  - fs/fuse/file.c:fuse_file_release
  - security/selinux/hooks.c:sb_finish_set_opts
  - drivers/dax/super.c:fs_dax_get_by_bdev
```
**Symbols:**

```
ffffffff814a0f00-ffffffff814a0f59: igrab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct inode *igrab(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff814d6210)
Location: fs/inode.c:1430
Inline: False
Direct callers:
  - mm/shmem.c:shmem_unused_huge_shrink
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/notify/fdinfo.c:inotify_fdinfo
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
  - fs/ext4/super.c:ext4_quota_off
  - fs/fat/inode.c:fat_iget
  - fs/fat/nfs.c:fat_dget
  - fs/fuse/file.c:fuse_file_release
  - security/selinux/hooks.c:sb_finish_set_opts
  - drivers/dax/super.c:fs_dax_get_by_bdev
```
**Symbols:**

```
ffffffff814d6210-ffffffff814d6269: igrab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct inode *igrab(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff815085e0)
Location: fs/inode.c:1378
Inline: False
Direct callers:
  - mm/shmem.c:shmem_unused_huge_shrink
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/notify/fdinfo.c:inotify_fdinfo
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
  - fs/ext4/super.c:ext4_quota_off
  - fs/fat/inode.c:fat_iget
  - fs/fat/nfs.c:fat_dget
  - fs/fuse/file.c:fuse_file_release
  - security/selinux/hooks.c:sb_finish_set_opts
  - drivers/dax/super.c:fs_dax_get_by_bdev
```
**Symbols:**

```
ffffffff815085e0-ffffffff81508639: igrab (STB_GLOBAL)
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
struct inode *igrab(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffff8000103acfa0)
Location: fs/inode.c:1295
Inline: True
Direct callers:
  - mm/shmem.c:shmem_unused_huge_shrink
  - fs/notify/mark.c:fsnotify_add_mark_list
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/notify/fdinfo.c:inotify_fdinfo
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/super.c:ext4_quota_off
  - fs/fuse/file.c:fuse_release_common
  - security/selinux/hooks.c:sb_finish_set_opts
  - drivers/dax/super.c:dax_get_by_host
```
**Symbols:**

```
ffff8000103acfa0-ffff8000103ad070: igrab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct inode *igrab(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (c058d85c)
Location: fs/inode.c:1295
Inline: True
Direct callers:
  - fs/notify/mark.c:fsnotify_add_mark_list
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/notify/fdinfo.c:inotify_fdinfo
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/super.c:ext4_quota_off
  - fs/fat/inode.c:fat_iget
  - fs/fat/nfs.c:fat_dget
  - fs/fuse/file.c:fuse_release_common
  - security/selinux/hooks.c:sb_finish_set_opts
  - drivers/dax/super.c:dax_get_by_host
```
**Symbols:**

```
c058d85c-c058d8e4: igrab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct inode *igrab(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (c0000000004a8010)
Location: fs/inode.c:1295
Inline: True
Direct callers:
  - mm/shmem.c:shmem_unused_huge_shrink
  - fs/notify/mark.c:fsnotify_add_mark_list
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/notify/fdinfo.c:inotify_fdinfo
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/super.c:ext4_quota_off
  - fs/fat/inode.c:fat_iget
  - fs/fat/nfs.c:fat_dget
  - fs/fuse/file.c:fuse_release_common
  - security/selinux/hooks.c:sb_finish_set_opts
  - drivers/dax/super.c:dax_get_by_host
```
**Symbols:**

```
c0000000004a8010-c0000000004a8100: igrab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct inode *igrab(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffe000272410)
Location: fs/inode.c:1295
Inline: False
Direct callers:
  - fs/notify/mark.c:fsnotify_add_mark_list
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/notify/fdinfo.c:inotify_fdinfo
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/super.c:ext4_quota_off
  - fs/fuse/file.c:fuse_release_common
  - security/selinux/hooks.c:sb_finish_set_opts
  - drivers/dax/super.c:dax_get_by_host
```
**Symbols:**

```
ffffffe000272410-ffffffe0002724dc: igrab (STB_GLOBAL)
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
struct inode *igrab(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812f5810)
Location: fs/inode.c:1295
Inline: False
Direct callers:
  - mm/shmem.c:shmem_unused_huge_shrink
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/notify/fdinfo.c:inotify_fdinfo
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/super.c:ext4_quota_off
  - fs/fuse/file.c:fuse_release_common
  - security/selinux/hooks.c:sb_finish_set_opts
  - drivers/dax/super.c:dax_get_by_host
```
**Symbols:**

```
ffffffff812f5810-ffffffff812f5861: igrab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct inode *igrab(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812e6430)
Location: fs/inode.c:1295
Inline: False
Direct callers:
  - mm/shmem.c:shmem_unused_huge_shrink
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/notify/fdinfo.c:inotify_fdinfo
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/super.c:ext4_quota_off
  - fs/fuse/file.c:fuse_release_common
  - security/selinux/hooks.c:sb_finish_set_opts
  - drivers/dax/super.c:dax_get_by_host
```
**Symbols:**

```
ffffffff812e6430-ffffffff812e6481: igrab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct inode *igrab(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812f3620)
Location: fs/inode.c:1295
Inline: False
Direct callers:
  - mm/shmem.c:shmem_unused_huge_shrink
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/notify/fdinfo.c:inotify_fdinfo
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/super.c:ext4_quota_off
  - fs/fuse/file.c:fuse_release_common
  - security/selinux/hooks.c:sb_finish_set_opts
  - drivers/dax/super.c:dax_get_by_host
```
**Symbols:**

```
ffffffff812f3620-ffffffff812f3671: igrab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct inode *igrab(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff813031b0)
Location: fs/inode.c:1295
Inline: False
Direct callers:
  - mm/shmem.c:shmem_unused_huge_shrink
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/notify/fdinfo.c:inotify_fdinfo
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/super.c:ext4_quota_off
  - fs/fuse/file.c:fuse_release_common
  - security/selinux/hooks.c:sb_finish_set_opts
  - drivers/dax/super.c:dax_get_by_host
```
**Symbols:**

```
ffffffff813031b0-ffffffff813031fd: igrab (STB_GLOBAL)
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
