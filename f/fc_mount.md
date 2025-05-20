# Function: <code>fc_mount</code>

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
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct vfsmount *fc_mount(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812f0970)
Location: fs/namespace.c:968
Inline: True
Direct callers:
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - ipc/mqueue.c:mq_create_mount
```
**Symbols:**

```
ffffffff812f0970-ffffffff812f09b5: fc_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct vfsmount *fc_mount(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81302510)
Location: fs/namespace.c:968
Inline: True
Direct callers:
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/hugetlbfs/inode.c:mount_one_hugetlbfs
  - ipc/mqueue.c:mq_create_mount
```
**Symbols:**

```
ffffffff81302510-ffffffff81302555: fc_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct vfsmount *fc_mount(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8133bb10)
Location: fs/namespace.c:984
Inline: True
Direct callers:
  - fs/hugetlbfs/inode.c:mount_one_hugetlbfs
  - ipc/mqueue.c:mq_init_ns
```
**Symbols:**

```
ffffffff8133bb10-ffffffff8133bb59: fc_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct vfsmount *fc_mount(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff813479b0)
Location: fs/namespace.c:984
Inline: True
Direct callers:
  - fs/hugetlbfs/inode.c:mount_one_hugetlbfs
  - ipc/mqueue.c:mq_init_ns
```
**Symbols:**

```
ffffffff813479b0-ffffffff813479f9: fc_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct vfsmount *fc_mount(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8134de60)
Location: fs/namespace.c:991
Inline: True
Direct callers:
  - fs/hugetlbfs/inode.c:mount_one_hugetlbfs
  - ipc/mqueue.c:mq_init_ns
```
**Symbols:**

```
ffffffff8134de60-ffffffff8134dea9: fc_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct vfsmount *fc_mount(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8139be60)
Location: fs/namespace.c:1000
Inline: True
Direct callers:
  - fs/hugetlbfs/inode.c:mount_one_hugetlbfs
  - fs/fuse/dir.c:fuse_dentry_automount
  - ipc/mqueue.c:mq_init_ns
```
**Symbols:**

```
ffffffff8139be60-ffffffff8139bea9: fc_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct vfsmount *fc_mount(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8141ed50)
Location: fs/namespace.c:1041
Inline: True
Direct callers:
  - fs/hugetlbfs/inode.c:mount_one_hugetlbfs
  - fs/fuse/dir.c:fuse_dentry_automount
  - ipc/mqueue.c:mq_init_ns
```
**Symbols:**

```
ffffffff8141ed50-ffffffff8141eda7: fc_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct vfsmount *fc_mount(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814ab230)
Location: fs/namespace.c:1147
Inline: True
Direct callers:
  - fs/hugetlbfs/inode.c:mount_one_hugetlbfs
  - fs/fuse/dir.c:fuse_dentry_automount
  - ipc/mqueue.c:mq_init_ns
```
**Symbols:**

```
ffffffff814ab230-ffffffff814ab287: fc_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct vfsmount *fc_mount(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814e0030)
Location: fs/namespace.c:1110
Inline: True
Direct callers:
  - fs/hugetlbfs/inode.c:mount_one_hugetlbfs
  - fs/fuse/dir.c:fuse_dentry_automount
  - ipc/mqueue.c:mq_init_ns
```
**Symbols:**

```
ffffffff814e0030-ffffffff814e0087: fc_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct vfsmount *fc_mount(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81513300)
Location: fs/namespace.c:1123
Inline: True
Direct callers:
  - fs/hugetlbfs/inode.c:mount_one_hugetlbfs
  - fs/fuse/dir.c:fuse_dentry_automount
  - ipc/mqueue.c:mq_init_ns
```
**Symbols:**

```
ffffffff81513300-ffffffff81513357: fc_mount (STB_GLOBAL)
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
struct vfsmount *fc_mount(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffff8000103b5180)
Location: fs/namespace.c:968
Inline: True
Direct callers:
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/hugetlbfs/inode.c:mount_one_hugetlbfs
  - ipc/mqueue.c:mq_create_mount
```
**Symbols:**

```
ffff8000103b5180-ffff8000103b51d8: fc_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct vfsmount *fc_mount(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0593d50)
Location: fs/namespace.c:968
Inline: True
Direct callers:
  - fs/proc/root.c:pid_ns_prepare_proc
  - ipc/mqueue.c:mq_create_mount
```
**Symbols:**

```
c0593d50-c0593d90: fc_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct vfsmount *fc_mount(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0000000004b1790)
Location: fs/namespace.c:968
Inline: True
Direct callers:
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/hugetlbfs/inode.c:mount_one_hugetlbfs
  - ipc/mqueue.c:mq_create_mount
```
**Symbols:**

```
c0000000004b1790-c0000000004b180c: fc_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct vfsmount *fc_mount(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffe00027822c)
Location: fs/namespace.c:968
Inline: True
Direct callers:
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/hugetlbfs/inode.c:mount_one_hugetlbfs
  - ipc/mqueue.c:mq_create_mount
```
**Symbols:**

```
ffffffe00027822c-ffffffe00027827c: fc_mount (STB_GLOBAL)
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
struct vfsmount *fc_mount(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812faaf0)
Location: fs/namespace.c:968
Inline: True
Direct callers:
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/hugetlbfs/inode.c:mount_one_hugetlbfs
  - ipc/mqueue.c:mq_create_mount
```
**Symbols:**

```
ffffffff812faaf0-ffffffff812fab35: fc_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct vfsmount *fc_mount(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812eb710)
Location: fs/namespace.c:968
Inline: True
Direct callers:
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/hugetlbfs/inode.c:mount_one_hugetlbfs
  - ipc/mqueue.c:mq_create_mount
```
**Symbols:**

```
ffffffff812eb710-ffffffff812eb755: fc_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct vfsmount *fc_mount(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812f88e0)
Location: fs/namespace.c:968
Inline: True
Direct callers:
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/hugetlbfs/inode.c:mount_one_hugetlbfs
  - ipc/mqueue.c:mq_create_mount
```
**Symbols:**

```
ffffffff812f88e0-ffffffff812f8925: fc_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct vfsmount *fc_mount(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81309d20)
Location: fs/namespace.c:968
Inline: True
Direct callers:
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/hugetlbfs/inode.c:mount_one_hugetlbfs
  - ipc/mqueue.c:mq_create_mount
```
**Symbols:**

```
ffffffff81309d20-ffffffff81309d65: fc_mount (STB_GLOBAL)
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
