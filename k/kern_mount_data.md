# Function: <code>kern_mount_data</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct vfsmount *kern_mount_data(struct file_system_type *type, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8122c750)
Location: fs/namespace.c:3158
Inline: False
Direct callers:
  - mm/shmem.c:shmem_init
  - fs/pipe.c:init_pipe_fs
  - fs/nsfs.c:nsfs_init
  - fs/block_dev.c:bdev_cache_init
  - fs/anon_inodes.c:anon_inode_init
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/devpts/inode.c:init_devpts_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - ipc/mqueue.c:init_mqueue_fs
```
**Symbols:**

```
ffffffff8122c750-ffffffff8122c77e: kern_mount_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct vfsmount *kern_mount_data(struct file_system_type *type, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81254ee0)
Location: fs/namespace.c:3145
Inline: False
Direct callers:
  - mm/shmem.c:shmem_init
  - fs/pipe.c:init_pipe_fs
  - fs/nsfs.c:nsfs_init
  - fs/block_dev.c:bdev_cache_init
  - fs/anon_inodes.c:anon_inode_init
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - ipc/mqueue.c:init_mqueue_fs
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
```
**Symbols:**

```
ffffffff81254ee0-ffffffff81254f0e: kern_mount_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct vfsmount *kern_mount_data(struct file_system_type *type, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81268440)
Location: fs/namespace.c:3289
Inline: False
Direct callers:
  - mm/shmem.c:shmem_init
  - fs/pipe.c:init_pipe_fs
  - fs/nsfs.c:nsfs_init
  - fs/block_dev.c:bdev_cache_init
  - fs/anon_inodes.c:anon_inode_init
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - ipc/mqueue.c:init_mqueue_fs
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
```
**Symbols:**

```
ffffffff81268440-ffffffff8126846e: kern_mount_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct vfsmount *kern_mount_data(struct file_system_type *type, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81275dc0)
Location: fs/namespace.c:3225
Inline: False
Direct callers:
  - mm/shmem.c:shmem_init
  - mm/zsmalloc.c:zs_init
  - fs/nsfs.c:nsfs_init
  - fs/block_dev.c:bdev_cache_init
  - fs/anon_inodes.c:anon_inode_init
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - ipc/mqueue.c:init_mqueue_fs
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
```
**Symbols:**

```
ffffffff81275dc0-ffffffff81275dfc: kern_mount_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct vfsmount *kern_mount_data(struct file_system_type *type, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81298590)
Location: fs/namespace.c:3298
Inline: False
Direct callers:
  - mm/shmem.c:shmem_init
  - mm/zsmalloc.c:zs_init
  - fs/nsfs.c:nsfs_init
  - fs/block_dev.c:bdev_cache_init
  - fs/anon_inodes.c:anon_inode_init
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - ipc/mqueue.c:init_mqueue_fs
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
```
**Symbols:**

```
ffffffff81298590-ffffffff812985cc: kern_mount_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct vfsmount *kern_mount_data(struct file_system_type *type, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812be650)
Location: fs/namespace.c:3335
Inline: False
Direct callers:
  - mm/shmem.c:shmem_init
  - mm/zsmalloc.c:zs_init
  - fs/pipe.c:init_pipe_fs
  - fs/nsfs.c:nsfs_init
  - fs/block_dev.c:bdev_cache_init
  - fs/anon_inodes.c:anon_inode_init
  - fs/aio.c:aio_setup
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - ipc/mqueue.c:init_mqueue_fs
  - security/selinux/selinuxfs.c:init_sel_fs
  - security/smack/smackfs.c:init_smk_fs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/dax/super.c:dax_fs_init
  - net/socket.c:sock_init
```
**Symbols:**

```
ffffffff812be650-ffffffff812be68b: kern_mount_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct vfsmount *kern_mount_data(struct file_system_type *type, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812d3a50)
Location: fs/namespace.c:3307
Inline: False
Direct callers:
  - mm/shmem.c:shmem_init
  - mm/zsmalloc.c:zs_init
  - fs/pipe.c:init_pipe_fs
  - fs/nsfs.c:nsfs_init
  - fs/block_dev.c:bdev_cache_init
  - fs/anon_inodes.c:anon_inode_init
  - fs/aio.c:aio_setup
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - ipc/mqueue.c:init_mqueue_fs
  - security/selinux/selinuxfs.c:init_sel_fs
  - security/smack/smackfs.c:init_smk_fs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/dax/super.c:dax_fs_init
  - net/socket.c:sock_init
```
**Symbols:**

```
ffffffff812d3a50-ffffffff812d3a8b: kern_mount_data (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
</ul>
