# Function: <code>d_invalidate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void d_invalidate(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812240f0)
Location: fs/dcache.c:1492
Inline: True
Direct callers:
  - fs/namei.c:lookup_fast
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_reverse_inval_entry
```
**Symbols:**

```
ffffffff812240f0-ffffffff812241fe: d_invalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void d_invalidate(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8124c790)
Location: fs/dcache.c:1503
Inline: True
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:lookup_slow
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_dcache
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
```
**Symbols:**

```
ffffffff8124c790-ffffffff8124c8a3: d_invalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void d_invalidate(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8125f780)
Location: fs/dcache.c:1512
Inline: True
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:lookup_slow
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_dcache
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
```
**Symbols:**

```
ffffffff8125f780-ffffffff8125f893: d_invalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void d_invalidate(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8126d0e0)
Location: fs/dcache.c:1545
Inline: True
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:lookup_slow
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_dcache
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
```
**Symbols:**

```
ffffffff8126d0e0-ffffffff8126d1ec: d_invalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void d_invalidate(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8128f480)
Location: fs/dcache.c:1557
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:lookup_slow
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_dcache
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
```
**Symbols:**

```
ffffffff8128f480-ffffffff8128f58c: d_invalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void d_invalidate(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812b6a30)
Location: fs/dcache.c:1567
Inline: True
Direct callers:
  - fs/namei.c:lookup_open
  - fs/namei.c:__lookup_slow
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_dcache
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/control.c:fuse_ctl_remove_conn
```
**Symbols:**

```
ffffffff812b6a30-ffffffff812b6b07: d_invalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void d_invalidate(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812cba80)
Location: fs/dcache.c:1576
Inline: True
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:__lookup_slow
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_dcache
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/control.c:fuse_ctl_remove_conn
  - fs/fuse/readdir.c:fuse_readdir
```
**Symbols:**

```
ffffffff812cba80-ffffffff812cbb57: d_invalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void d_invalidate(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812e8cb0)
Location: fs/dcache.c:1642
Inline: True
Direct callers:
  - fs/namei.c:lookup_open
  - fs/namei.c:__lookup_slow
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_dcache
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/control.c:fuse_ctl_remove_conn
```
**Symbols:**

```
ffffffff812e8cb0-ffffffff812e8d8b: d_invalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void d_invalidate(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812fa850)
Location: fs/dcache.c:1642
Inline: True
Direct callers:
  - fs/namei.c:lookup_open
  - fs/namei.c:__lookup_slow
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_dcache
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/control.c:fuse_ctl_remove_conn
```
**Symbols:**

```
ffffffff812fa850-ffffffff812fa92b: d_invalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void d_invalidate(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff813338a0)
Location: fs/dcache.c:1663
Inline: True
Direct callers:
  - fs/namei.c:__lookup_slow
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_dcache
  - fs/libfs.c:simple_recursive_removal
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rmdir
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/control.c:fuse_ctl_remove_conn
```
**Symbols:**

```
ffffffff813338a0-ffffffff81333989: d_invalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void d_invalidate(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8133f220)
Location: fs/dcache.c:1670
Inline: True
Direct callers:
  - fs/namei.c:__lookup_slow
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_dcache
  - fs/libfs.c:simple_recursive_removal
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
  - fs/ext4/namei.c:ext4_unlink
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rmdir
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/control.c:fuse_ctl_remove_conn
```
**Symbols:**

```
ffffffff8133f220-ffffffff8133f309: d_invalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void d_invalidate(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff813456a0)
Location: fs/dcache.c:1697
Inline: True
Direct callers:
  - fs/namei.c:__lookup_slow
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_dcache
  - fs/libfs.c:simple_recursive_removal
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
  - fs/ext4/namei.c:ext4_unlink
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rmdir
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/control.c:fuse_ctl_remove_conn
```
**Symbols:**

```
ffffffff813456a0-ffffffff81345789: d_invalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void d_invalidate(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff813932b0)
Location: fs/dcache.c:1698
Inline: True
Direct callers:
  - fs/namei.c:__lookup_slow
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_dcache
  - fs/libfs.c:simple_recursive_removal
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
  - fs/ext4/namei.c:ext4_unlink
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rmdir
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/control.c:fuse_ctl_remove_conn
```
**Symbols:**

```
ffffffff813932b0-ffffffff81393399: d_invalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void d_invalidate(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff814149e0)
Location: fs/dcache.c:1722
Inline: True
Direct callers:
  - fs/namei.c:__lookup_slow
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_dcache
  - fs/libfs.c:simple_recursive_removal
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
  - fs/ext4/namei.c:ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rmdir
  - fs/fuse/dir.c:fuse_unlink
```
**Symbols:**

```
ffffffff814149e0-ffffffff81414acb: d_invalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void d_invalidate(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8149fed0)
Location: fs/dcache.c:1722
Inline: True
Direct callers:
  - fs/namei.c:__lookup_slow
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_dcache
  - fs/libfs.c:simple_recursive_removal
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
  - fs/ext4/namei.c:ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rmdir
  - fs/fuse/dir.c:fuse_unlink
```
**Symbols:**

```
ffffffff8149fed0-ffffffff8149ffbb: d_invalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void d_invalidate(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff814d51f0)
Location: fs/dcache.c:1722
Inline: True
Direct callers:
  - fs/namei.c:__lookup_slow
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_dcache
  - fs/libfs.c:simple_recursive_removal
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
  - fs/ext4/namei.c:ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rmdir
  - fs/fuse/dir.c:fuse_unlink
```
**Symbols:**

```
ffffffff814d51f0-ffffffff814d52db: d_invalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void d_invalidate(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81507610)
Location: fs/dcache.c:1577
Inline: True
Direct callers:
  - fs/namei.c:__lookup_slow
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_dcache
  - fs/libfs.c:simple_recursive_removal
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
  - fs/ext4/namei.c:ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rmdir
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/dir.c:fuse_atomic_open
  - fs/tracefs/event_inode.c:eventfs_remove_events_dir
```
**Symbols:**

```
ffffffff81507610-ffffffff815076fb: d_invalidate (STB_GLOBAL)
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
void d_invalidate(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffff8000103a9998)
Location: fs/dcache.c:1642
Inline: True
Direct callers:
  - fs/namei.c:lookup_open
  - fs/namei.c:__lookup_slow
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_dcache
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/control.c:fuse_ctl_remove_conn
  - fs/fuse/readdir.c:parse_dirplusfile
```
**Symbols:**

```
ffff8000103a9998-ffff8000103a9acc: d_invalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void d_invalidate(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c058aae0)
Location: fs/dcache.c:1642
Inline: True
Direct callers:
  - fs/namei.c:lookup_open
  - fs/namei.c:__lookup_slow
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_dcache
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/control.c:fuse_ctl_remove_conn
  - fs/fuse/readdir.c:parse_dirplusfile
```
**Symbols:**

```
c058aae0-c058abfc: d_invalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void d_invalidate(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c0000000004a4570)
Location: fs/dcache.c:1642
Inline: True
Direct callers:
  - fs/namei.c:lookup_open
  - fs/namei.c:__lookup_slow
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_dcache
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/control.c:fuse_ctl_remove_conn
  - fs/fuse/readdir.c:parse_dirplusfile
```
**Symbols:**

```
c0000000004a4570-c0000000004a4720: d_invalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void d_invalidate(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffe00026f804)
Location: fs/dcache.c:1642
Inline: True
Direct callers:
  - fs/namei.c:lookup_open
  - fs/namei.c:__lookup_slow
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_dcache
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/control.c:fuse_ctl_remove_conn
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
ffffffe00026f804-ffffffe00026f952: d_invalidate (STB_GLOBAL)
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
void d_invalidate(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812f2e30)
Location: fs/dcache.c:1642
Inline: True
Direct callers:
  - fs/namei.c:lookup_open
  - fs/namei.c:__lookup_slow
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_dcache
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/control.c:fuse_ctl_remove_conn
```
**Symbols:**

```
ffffffff812f2e30-ffffffff812f2f0b: d_invalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void d_invalidate(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812e3a60)
Location: fs/dcache.c:1642
Inline: True
Direct callers:
  - fs/namei.c:lookup_open
  - fs/namei.c:__lookup_slow
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_dcache
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/control.c:fuse_ctl_remove_conn
```
**Symbols:**

```
ffffffff812e3a60-ffffffff812e3b3b: d_invalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void d_invalidate(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812f0c40)
Location: fs/dcache.c:1642
Inline: True
Direct callers:
  - fs/namei.c:lookup_open
  - fs/namei.c:__lookup_slow
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_dcache
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/control.c:fuse_ctl_remove_conn
```
**Symbols:**

```
ffffffff812f0c40-ffffffff812f0d1b: d_invalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void d_invalidate(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81301e00)
Location: fs/dcache.c:1642
Inline: True
Direct callers:
  - fs/namei.c:lookup_open
  - fs/namei.c:__lookup_slow
  - fs/namei.c:lookup_fast
  - fs/namei.c:lookup_dcache
  - fs/proc/base.c:proc_flush_task
  - fs/proc/base.c:proc_flush_task
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_rename_common
  - fs/fuse/dir.c:fuse_unlink
  - fs/fuse/control.c:fuse_ctl_remove_conn
```
**Symbols:**

```
ffffffff81301e00-ffffffff81301ed6: d_invalidate (STB_GLOBAL)
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
