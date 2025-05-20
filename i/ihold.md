# Function: <code>ihold</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void ihold(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81227830)
Location: fs/inode.c:388
Inline: True
Direct callers:
  - mm/shmem.c:shmem_link
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:do_unlinkat
  - fs/attr.c:notify_change
  - fs/libfs.c:simple_link
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/block_dev.c:blkdev_get
  - fs/devpts/inode.c:devpts_add_ref
  - fs/ext4/namei.c:ext4_link
  - ipc/mqueue.c:SyS_mq_unlink
  - net/socket.c:sock_alloc_file
```
**Symbols:**

```
ffffffff81227830-ffffffff81227862: ihold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void ihold(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff8124ffc0)
Location: fs/inode.c:396
Inline: True
Direct callers:
  - mm/shmem.c:shmem_link
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/attr.c:notify_change
  - fs/libfs.c:simple_link
  - fs/block_dev.c:blkdev_get
  - fs/ext4/namei.c:ext4_link
  - ipc/mqueue.c:SyS_mq_unlink
  - net/socket.c:sock_alloc_file
```
**Symbols:**

```
ffffffff8124ffc0-ffffffff8124fff2: ihold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void ihold(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81263060)
Location: fs/inode.c:398
Inline: True
Direct callers:
  - mm/shmem.c:shmem_link
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/attr.c:notify_change
  - fs/libfs.c:simple_link
  - fs/block_dev.c:blkdev_get
  - fs/ext4/namei.c:ext4_link
  - ipc/mqueue.c:SyS_mq_unlink
  - net/socket.c:sock_alloc_file
```
**Symbols:**

```
ffffffff81263060-ffffffff81263092: ihold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void ihold(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812708e0)
Location: fs/inode.c:396
Inline: True
Direct callers:
  - mm/shmem.c:shmem_link
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/attr.c:notify_change
  - fs/libfs.c:simple_link
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:bd_acquire
  - fs/block_dev.c:bd_acquire
  - fs/ext4/namei.c:ext4_link
  - ipc/mqueue.c:SyS_mq_unlink
  - net/socket.c:sock_alloc_file
```
**Symbols:**

```
ffffffff812708e0-ffffffff81270904: ihold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void ihold(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81293220)
Location: fs/inode.c:396
Inline: True
Direct callers:
  - mm/shmem.c:shmem_link
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/attr.c:notify_change
  - fs/libfs.c:simple_link
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:bd_acquire
  - fs/block_dev.c:bd_acquire
  - fs/ext4/namei.c:ext4_link
  - ipc/mqueue.c:SyS_mq_unlink
  - net/socket.c:sock_alloc_file
```
**Symbols:**

```
ffffffff81293220-ffffffff81293244: ihold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void ihold(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812b8e90)
Location: fs/inode.c:402
Inline: True
Direct callers:
  - mm/shmem.c:shmem_link
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/attr.c:notify_change
  - fs/libfs.c:simple_link
  - fs/block_dev.c:blkdev_get
  - fs/ext4/namei.c:ext4_link
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
  - net/socket.c:sock_alloc_file
```
**Symbols:**

```
ffffffff812b8e90-ffffffff812b8eb4: ihold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void ihold(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812cdfd0)
Location: fs/inode.c:402
Inline: True
Direct callers:
  - mm/shmem.c:shmem_link
  - fs/file_table.c:alloc_file_pseudo
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/attr.c:notify_change
  - fs/libfs.c:simple_link
  - fs/block_dev.c:blkdev_get
  - fs/ext4/namei.c:ext4_link
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
```
**Symbols:**

```
ffffffff812cdfd0-ffffffff812cdff4: ihold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ihold(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/inode.c (ffffffff812ecf59)
Location: fs/inode.c:415
Inline: True
Direct callers:
  - mm/shmem.c:shmem_link
  - fs/file_table.c:alloc_file_pseudo
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/attr.c:notify_change
  - fs/libfs.c:simple_link
  - fs/block_dev.c:bd_start_claiming
  - fs/ext4/namei.c:ext4_link
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
```
**Symbols:**

```
ffffffff812ecf59-ffffffff812ecf6c: ihold.cold (STB_LOCAL)
ffffffff812eae00-ffffffff812eae24: ihold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void ihold(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812fc940)
Location: fs/inode.c:419
Inline: True
Direct callers:
  - mm/shmem.c:shmem_link
  - fs/file_table.c:alloc_file_pseudo
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/attr.c:notify_change
  - fs/libfs.c:simple_link
  - fs/block_dev.c:bd_start_claiming
  - fs/ext4/namei.c:ext4_link
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
```
**Symbols:**

```
ffffffff812fc940-ffffffff812fc964: ihold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void ihold(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff813351a0)
Location: fs/inode.c:420
Inline: True
Direct callers:
  - mm/shmem.c:shmem_link
  - fs/file_table.c:alloc_file_pseudo
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/attr.c:notify_change
  - fs/xattr.c:__vfs_removexattr_locked
  - fs/xattr.c:__vfs_setxattr_locked
  - fs/libfs.c:simple_link
  - fs/block_dev.c:bd_start_claiming
  - fs/block_dev.c:bd_acquire
  - fs/block_dev.c:bd_acquire
  - fs/ext4/namei.c:ext4_link
  - ipc/mqueue.c:__do_sys_mq_unlink
```
**Symbols:**

```
ffffffff813351a0-ffffffff813351c4: ihold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void ihold(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81340b10)
Location: fs/inode.c:421
Inline: True
Direct callers:
  - mm/shmem.c:shmem_link
  - fs/file_table.c:alloc_file_pseudo
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/attr.c:notify_change
  - fs/xattr.c:__vfs_removexattr_locked
  - fs/xattr.c:__vfs_setxattr_locked
  - fs/libfs.c:simple_link
  - fs/ext4/namei.c:__ext4_link
  - ipc/mqueue.c:__do_sys_mq_unlink
```
**Symbols:**

```
ffffffff81340b10-ffffffff81340b34: ihold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void ihold(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81346f90)
Location: fs/inode.c:421
Inline: True
Direct callers:
  - mm/shmem.c:shmem_link
  - fs/file_table.c:alloc_file_pseudo
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/attr.c:notify_change
  - fs/xattr.c:__vfs_removexattr_locked
  - fs/xattr.c:__vfs_setxattr_locked
  - fs/libfs.c:simple_link
  - fs/anon_inodes.c:__anon_inode_getfile
  - fs/ext4/namei.c:__ext4_link
  - ipc/mqueue.c:__do_sys_mq_unlink
  - security/landlock/fs.c:landlock_append_fs_rule
```
**Symbols:**

```
ffffffff81346f90-ffffffff81346fb4: ihold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ihold(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81394350)
Location: fs/inode.c:425
Inline: False
Direct callers:
  - mm/shmem.c:shmem_link
  - fs/file_table.c:alloc_file_pseudo
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
  - fs/attr.c:notify_change
  - fs/xattr.c:__vfs_removexattr_locked
  - fs/xattr.c:__vfs_setxattr_locked
  - fs/libfs.c:simple_link
  - fs/notify/mark.c:fsnotify_add_mark_list
  - fs/anon_inodes.c:__anon_inode_getfile
  - fs/ext4/namei.c:__ext4_link
  - ipc/mqueue.c:__do_sys_mq_unlink
  - security/landlock/fs.c:landlock_append_fs_rule
```
**Symbols:**

```
ffffffff81394350-ffffffff81394374: ihold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ihold(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff814160a0)
Location: fs/inode.c:449
Inline: False
Direct callers:
  - mm/shmem.c:shmem_link
  - fs/file_table.c:alloc_file_pseudo
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
  - fs/attr.c:notify_change
  - fs/xattr.c:__vfs_removexattr_locked
  - fs/xattr.c:__vfs_setxattr_locked
  - fs/libfs.c:simple_link
  - fs/notify/mark.c:__fsnotify_recalc_mask
  - fs/anon_inodes.c:__anon_inode_getfile
  - fs/ext4/namei.c:__ext4_link
  - ipc/mqueue.c:__do_sys_mq_unlink
  - security/landlock/fs.c:landlock_append_fs_rule
```
**Symbols:**

```
ffffffff814160a0-ffffffff814160d4: ihold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ihold(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff814a1110)
Location: fs/inode.c:448
Inline: False
Direct callers:
  - mm/shmem.c:shmem_link
  - fs/file_table.c:alloc_file_pseudo
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
  - fs/attr.c:notify_change
  - fs/xattr.c:__vfs_removexattr_locked
  - fs/xattr.c:__vfs_setxattr_locked
  - fs/libfs.c:simple_link
  - fs/notify/mark.c:__fsnotify_recalc_mask
  - fs/anon_inodes.c:__anon_inode_getfile
  - fs/posix_acl.c:vfs_remove_acl
  - fs/posix_acl.c:vfs_set_acl
  - fs/ext4/namei.c:__ext4_link
  - ipc/mqueue.c:__do_sys_mq_unlink
  - security/landlock/fs.c:landlock_append_fs_rule
```
**Symbols:**

```
ffffffff814a1110-ffffffff814a1144: ihold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ihold(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff814d6420)
Location: fs/inode.c:448
Inline: False
Direct callers:
  - mm/shmem.c:shmem_link
  - fs/file_table.c:alloc_file_pseudo
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
  - fs/attr.c:notify_change
  - fs/xattr.c:__vfs_removexattr_locked
  - fs/xattr.c:__vfs_setxattr_locked
  - fs/libfs.c:simple_link
  - fs/notify/mark.c:__fsnotify_recalc_mask
  - fs/anon_inodes.c:__anon_inode_getfile
  - fs/posix_acl.c:vfs_remove_acl
  - fs/posix_acl.c:vfs_set_acl
  - fs/ext4/namei.c:__ext4_link
  - ipc/mqueue.c:__do_sys_mq_unlink
  - security/landlock/fs.c:landlock_append_fs_rule
```
**Symbols:**

```
ffffffff814d6420-ffffffff814d6454: ihold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ihold(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff815087f0)
Location: fs/inode.c:449
Inline: False
Direct callers:
  - mm/shmem.c:shmem_link
  - fs/file_table.c:alloc_file_pseudo
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
  - fs/attr.c:notify_change
  - fs/xattr.c:__vfs_removexattr_locked
  - fs/xattr.c:__vfs_setxattr_locked
  - fs/libfs.c:simple_link
  - fs/notify/mark.c:__fsnotify_recalc_mask
  - fs/anon_inodes.c:__anon_inode_getfile
  - fs/posix_acl.c:vfs_remove_acl
  - fs/posix_acl.c:vfs_set_acl
  - fs/ext4/namei.c:__ext4_link
  - ipc/mqueue.c:__do_sys_mq_unlink
  - security/landlock/fs.c:landlock_append_fs_rule
```
**Symbols:**

```
ffffffff815087f0-ffffffff81508824: ihold (STB_GLOBAL)
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
void ihold(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffff8000103ac650)
Location: fs/inode.c:419
Inline: True
Direct callers:
  - mm/shmem.c:shmem_link
  - fs/file_table.c:alloc_file_pseudo
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/attr.c:notify_change
  - fs/libfs.c:simple_link
  - fs/block_dev.c:bd_start_claiming
  - fs/block_dev.c:bd_acquire
  - fs/block_dev.c:bd_acquire
  - fs/ext4/namei.c:ext4_link
  - ipc/mqueue.c:__arm64_sys_mq_unlink
```
**Symbols:**

```
ffff8000103ac650-ffff8000103ac6b4: ihold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void ihold(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (c058d774)
Location: fs/inode.c:419
Inline: True
Direct callers:
  - mm/shmem.c:shmem_link
  - fs/file_table.c:alloc_file_pseudo
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/attr.c:notify_change
  - fs/libfs.c:simple_link
  - fs/block_dev.c:bd_start_claiming
  - fs/block_dev.c:bd_acquire
  - fs/block_dev.c:bd_acquire
  - fs/ext4/namei.c:ext4_link
  - ipc/mqueue.c:__se_sys_mq_unlink
```
**Symbols:**

```
c058d774-c058d7d0: ihold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ihold(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (c0000000004a6500)
Location: fs/inode.c:419
Inline: False
Direct callers:
  - mm/shmem.c:shmem_link
  - fs/file_table.c:alloc_file_pseudo
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/attr.c:notify_change
  - fs/libfs.c:simple_link
  - fs/block_dev.c:bd_start_claiming
  - fs/block_dev.c:bd_acquire
  - fs/block_dev.c:bd_acquire
  - fs/ext4/namei.c:ext4_link
  - ipc/mqueue.c:__se_sys_mq_unlink
```
**Symbols:**

```
c0000000004a6500-c0000000004a653c: ihold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void ihold(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffe0002718cc)
Location: fs/inode.c:419
Inline: True
Direct callers:
  - mm/shmem.c:shmem_link
  - fs/file_table.c:alloc_file_pseudo
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/attr.c:notify_change
  - fs/libfs.c:simple_link
  - fs/block_dev.c:bd_start_claiming
  - fs/ext4/namei.c:ext4_link
  - ipc/mqueue.c:__se_sys_mq_unlink
```
**Symbols:**

```
ffffffe0002718cc-ffffffe00027190a: ihold (STB_GLOBAL)
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
void ihold(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812f4f20)
Location: fs/inode.c:419
Inline: True
Direct callers:
  - mm/shmem.c:shmem_link
  - fs/file_table.c:alloc_file_pseudo
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/attr.c:notify_change
  - fs/libfs.c:simple_link
  - fs/block_dev.c:bd_start_claiming
  - fs/ext4/namei.c:ext4_link
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
```
**Symbols:**

```
ffffffff812f4f20-ffffffff812f4f44: ihold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void ihold(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812e5b40)
Location: fs/inode.c:419
Inline: True
Direct callers:
  - mm/shmem.c:shmem_link
  - fs/file_table.c:alloc_file_pseudo
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/attr.c:notify_change
  - fs/libfs.c:simple_link
  - fs/block_dev.c:bd_start_claiming
  - fs/ext4/namei.c:ext4_link
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
```
**Symbols:**

```
ffffffff812e5b40-ffffffff812e5b64: ihold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void ihold(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812f2d30)
Location: fs/inode.c:419
Inline: True
Direct callers:
  - mm/shmem.c:shmem_link
  - fs/file_table.c:alloc_file_pseudo
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/attr.c:notify_change
  - fs/libfs.c:simple_link
  - fs/block_dev.c:bd_start_claiming
  - fs/ext4/namei.c:ext4_link
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
```
**Symbols:**

```
ffffffff812f2d30-ffffffff812f2d54: ihold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void ihold(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81304440)
Location: fs/inode.c:419
Inline: True
Direct callers:
  - mm/shmem.c:shmem_link
  - fs/file_table.c:alloc_file_pseudo
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:do_unlinkat
  - fs/namei.c:vfs_unlink
  - fs/attr.c:notify_change
  - fs/libfs.c:simple_link
  - fs/block_dev.c:bd_start_claiming
  - fs/ext4/namei.c:ext4_link
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
```
**Symbols:**

```
ffffffff81304440-ffffffff81304464: ihold (STB_GLOBAL)
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
