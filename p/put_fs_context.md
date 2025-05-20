# Function: <code>put_fs_context</code>

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
void put_fs_context(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff8130a4b0)
Location: fs/fs_context.c:491
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:do_emergency_remount_callback
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:ksys_umount
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - fs/fsopen.c:fscontext_release
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - ipc/mqueue.c:mq_create_mount
```
**Symbols:**

```
ffffffff8130a4b0-ffffffff8130a5e9: put_fs_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void put_fs_context(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff8131d480)
Location: fs/fs_context.c:489
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:do_emergency_remount_callback
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:ksys_umount
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - fs/fsopen.c:fscontext_release
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/hugetlbfs/inode.c:mount_one_hugetlbfs
  - ipc/mqueue.c:mq_create_mount
```
**Symbols:**

```
ffffffff8131d480-ffffffff8131d5a8: put_fs_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void put_fs_context(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff813574f0)
Location: fs/fs_context.c:434
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:do_emergency_remount_callback
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_umount
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fsopen.c:__do_sys_fspick
  - fs/fsopen.c:__do_sys_fspick
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - fs/fsopen.c:fscontext_release
  - fs/hugetlbfs/inode.c:mount_one_hugetlbfs
  - ipc/mqueue.c:mq_init_ns
```
**Symbols:**

```
ffffffff813574f0-ffffffff81357654: put_fs_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void put_fs_context(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff81363ea0)
Location: fs/fs_context.c:434
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:do_emergency_remount_callback
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_umount
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fsopen.c:__do_sys_fspick
  - fs/fsopen.c:__do_sys_fspick
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - fs/fsopen.c:fscontext_release
  - fs/hugetlbfs/inode.c:mount_one_hugetlbfs
  - fs/fuse/dir.c:fuse_dentry_automount
  - fs/fuse/dir.c:fuse_dentry_automount
  - ipc/mqueue.c:mq_init_ns
```
**Symbols:**

```
ffffffff81363ea0-ffffffff8136403f: put_fs_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void put_fs_context(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff8136a920)
Location: fs/fs_context.c:434
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:do_emergency_remount_callback
  - fs/namespace.c:path_mount
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_umount
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fsopen.c:__do_sys_fspick
  - fs/fsopen.c:__do_sys_fspick
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - fs/fsopen.c:fscontext_release
  - fs/hugetlbfs/inode.c:mount_one_hugetlbfs
  - fs/fuse/dir.c:fuse_dentry_automount
  - fs/fuse/dir.c:fuse_dentry_automount
  - ipc/mqueue.c:mq_init_ns
```
**Symbols:**

```
ffffffff8136a920-ffffffff8136aabf: put_fs_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void put_fs_context(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff813b95e0)
Location: fs/fs_context.c:457
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:do_emergency_remount_callback
  - fs/namespace.c:path_mount
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_umount
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fsopen.c:__do_sys_fspick
  - fs/fsopen.c:__do_sys_fspick
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - fs/fsopen.c:fscontext_release
  - fs/hugetlbfs/inode.c:mount_one_hugetlbfs
  - fs/fuse/dir.c:fuse_dentry_automount
  - ipc/mqueue.c:mq_init_ns
```
**Symbols:**

```
ffffffff813b95e0-ffffffff813b977f: put_fs_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void put_fs_context(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff8143f040)
Location: fs/fs_context.c:457
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:mount_single
  - fs/super.c:do_emergency_remount_callback
  - fs/namespace.c:path_mount
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_umount
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - fs/fsopen.c:fscontext_release
  - fs/hugetlbfs/inode.c:mount_one_hugetlbfs
  - fs/fuse/dir.c:fuse_dentry_automount
  - ipc/mqueue.c:mq_init_ns
```
**Symbols:**

```
ffffffff8143f040-ffffffff8143f1e1: put_fs_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void put_fs_context(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff814cdcc0)
Location: fs/fs_context.c:457
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:mount_single
  - fs/super.c:do_emergency_remount_callback
  - fs/namespace.c:path_mount
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_umount
  - fs/fs_context.c:alloc_fs_context
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - fs/fsopen.c:fscontext_release
  - fs/hugetlbfs/inode.c:mount_one_hugetlbfs
  - fs/fuse/dir.c:fuse_dentry_automount
  - ipc/mqueue.c:mq_init_ns
```
**Symbols:**

```
ffffffff814cdcc0-ffffffff814cde61: put_fs_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void put_fs_context(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff81503eb0)
Location: fs/fs_context.c:478
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:mount_single
  - fs/super.c:do_emergency_remount_callback
  - fs/namespace.c:path_mount
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_umount
  - fs/fs_context.c:fs_context_for_submount
  - fs/fs_context.c:alloc_fs_context
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - fs/fsopen.c:fscontext_release
  - fs/hugetlbfs/inode.c:mount_one_hugetlbfs
  - fs/fuse/dir.c:fuse_dentry_automount
  - ipc/mqueue.c:mq_init_ns
```
**Symbols:**

```
ffffffff81503eb0-ffffffff81504068: put_fs_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void put_fs_context(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff81538b70)
Location: fs/fs_context.c:508
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:mount_single
  - fs/namespace.c:path_mount
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_umount
  - fs/fs_context.c:fs_context_for_submount
  - fs/fs_context.c:alloc_fs_context
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - fs/fsopen.c:fscontext_release
  - fs/hugetlbfs/inode.c:mount_one_hugetlbfs
  - fs/fuse/dir.c:fuse_dentry_automount
  - ipc/mqueue.c:mq_init_ns
```
**Symbols:**

```
ffffffff81538b70-ffffffff81538d2a: put_fs_context (STB_GLOBAL)
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
void put_fs_context(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffff8000103d5860)
Location: fs/fs_context.c:489
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:do_emergency_remount_callback
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:ksys_umount
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fsopen.c:__arm64_sys_fspick
  - fs/fsopen.c:__arm64_sys_fspick
  - fs/fsopen.c:__arm64_sys_fsopen
  - fs/fsopen.c:__arm64_sys_fsopen
  - fs/fsopen.c:fscontext_release
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/hugetlbfs/inode.c:mount_one_hugetlbfs
  - ipc/mqueue.c:mq_create_mount
```
**Symbols:**

```
ffff8000103d5860-ffff8000103d59ec: put_fs_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void put_fs_context(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (c05aef78)
Location: fs/fs_context.c:489
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:do_emergency_remount_callback
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_umount
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fsopen.c:__se_sys_fspick
  - fs/fsopen.c:__se_sys_fspick
  - fs/fsopen.c:__se_sys_fsopen
  - fs/fsopen.c:fscontext_release
  - fs/proc/root.c:pid_ns_prepare_proc
  - ipc/mqueue.c:mq_create_mount
```
**Symbols:**

```
c05aef78-c05af108: put_fs_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void put_fs_context(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (c0000000004d8050)
Location: fs/fs_context.c:489
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:do_emergency_remount_callback
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:ksys_umount
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fsopen.c:__se_sys_fspick
  - fs/fsopen.c:__se_sys_fspick
  - fs/fsopen.c:__se_sys_fsopen
  - fs/fsopen.c:fscontext_release
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/hugetlbfs/inode.c:mount_one_hugetlbfs
  - ipc/mqueue.c:mq_create_mount
```
**Symbols:**

```
c0000000004d8050-c0000000004d827c: put_fs_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void put_fs_context(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffe00028f34e)
Location: fs/fs_context.c:489
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:do_emergency_remount_callback
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:ksys_umount
  - fs/fs_context.c:alloc_fs_context
  - fs/fsopen.c:__se_sys_fspick
  - fs/fsopen.c:__se_sys_fspick
  - fs/fsopen.c:__se_sys_fsopen
  - fs/fsopen.c:fscontext_release
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/hugetlbfs/inode.c:mount_one_hugetlbfs
  - ipc/mqueue.c:mq_create_mount
```
**Symbols:**

```
ffffffe00028f34e-ffffffe00028f48e: put_fs_context (STB_GLOBAL)
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
void put_fs_context(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff81315a60)
Location: fs/fs_context.c:489
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:do_emergency_remount_callback
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:ksys_umount
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - fs/fsopen.c:fscontext_release
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/hugetlbfs/inode.c:mount_one_hugetlbfs
  - ipc/mqueue.c:mq_create_mount
```
**Symbols:**

```
ffffffff81315a60-ffffffff81315b88: put_fs_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void put_fs_context(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff81306650)
Location: fs/fs_context.c:489
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:do_emergency_remount_callback
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:ksys_umount
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - fs/fsopen.c:fscontext_release
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/hugetlbfs/inode.c:mount_one_hugetlbfs
  - ipc/mqueue.c:mq_create_mount
```
**Symbols:**

```
ffffffff81306650-ffffffff81306778: put_fs_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void put_fs_context(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff81313850)
Location: fs/fs_context.c:489
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:do_emergency_remount_callback
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:ksys_umount
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - fs/fsopen.c:fscontext_release
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/hugetlbfs/inode.c:mount_one_hugetlbfs
  - ipc/mqueue.c:mq_create_mount
```
**Symbols:**

```
ffffffff81313850-ffffffff81313978: put_fs_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void put_fs_context(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff813250a0)
Location: fs/fs_context.c:489
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:do_emergency_remount_callback
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:ksys_umount
  - fs/fs_context.c:vfs_dup_fs_context
  - fs/fs_context.c:alloc_fs_context
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - fs/fsopen.c:fscontext_release
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/hugetlbfs/inode.c:mount_one_hugetlbfs
  - ipc/mqueue.c:mq_create_mount
```
**Symbols:**

```
ffffffff813250a0-ffffffff813251c8: put_fs_context (STB_GLOBAL)
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
