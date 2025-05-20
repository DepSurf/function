# Function: <code>kern_mount</code>

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
struct vfsmount *kern_mount(struct file_system_type *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812f0ab0)
Location: fs/namespace.c:3764
Inline: False
Direct callers:
  - mm/shmem.c:shmem_init
  - mm/zsmalloc.c:zs_init
  - fs/pipe.c:init_pipe_fs
  - fs/nsfs.c:nsfs_init
  - fs/block_dev.c:bdev_cache_init
  - fs/anon_inodes.c:anon_inode_init
  - fs/aio.c:aio_setup
  - security/selinux/selinuxfs.c:init_sel_fs
  - security/smack/smackfs.c:init_smk_fs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/dax/super.c:dax_core_init
  - drivers/dma-buf/dma-buf.c:dma_buf_init
  - net/socket.c:sock_init
```
**Symbols:**

```
ffffffff812f0ab0-ffffffff812f0aea: kern_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct vfsmount *kern_mount(struct file_system_type *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81302650)
Location: fs/namespace.c:3797
Inline: False
Direct callers:
  - mm/shmem.c:shmem_init
  - mm/zsmalloc.c:zs_init
  - fs/pipe.c:init_pipe_fs
  - fs/nsfs.c:nsfs_init
  - fs/block_dev.c:bdev_cache_init
  - fs/anon_inodes.c:anon_inode_init
  - fs/aio.c:aio_setup
  - security/selinux/selinuxfs.c:init_sel_fs
  - security/smack/smackfs.c:init_smk_fs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/dax/super.c:dax_core_init
  - drivers/dma-buf/dma-buf.c:dma_buf_init
  - net/socket.c:sock_init
```
**Symbols:**

```
ffffffff81302650-ffffffff8130268a: kern_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct vfsmount *kern_mount(struct file_system_type *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8133bc70)
Location: fs/namespace.c:3850
Inline: False
Direct callers:
  - mm/shmem.c:shmem_init
  - mm/zsmalloc.c:zs_init
  - fs/pipe.c:init_pipe_fs
  - fs/nsfs.c:nsfs_init
  - fs/block_dev.c:bdev_cache_init
  - fs/anon_inodes.c:anon_inode_init
  - fs/aio.c:aio_setup
  - fs/proc/proc_sysctl.c:process_sysctl_arg
  - security/selinux/selinuxfs.c:init_sel_fs
  - security/smack/smackfs.c:init_smk_fs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/dax/super.c:dax_core_init
  - drivers/dma-buf/dma-buf.c:dma_buf_init
  - net/socket.c:sock_init
```
**Symbols:**

```
ffffffff8133bc70-ffffffff8133bcaa: kern_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct vfsmount *kern_mount(struct file_system_type *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81347b10)
Location: fs/namespace.c:3872
Inline: False
Direct callers:
  - kernel/usermode_driver.c:blob_to_mnt
  - mm/shmem.c:shmem_init
  - mm/zsmalloc.c:zs_init
  - fs/pipe.c:init_pipe_fs
  - fs/nsfs.c:nsfs_init
  - fs/block_dev.c:bdev_cache_init
  - fs/anon_inodes.c:anon_inode_init
  - fs/aio.c:aio_setup
  - fs/proc/proc_sysctl.c:process_sysctl_arg
  - security/selinux/selinuxfs.c:init_sel_fs
  - security/smack/smackfs.c:init_smk_fs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/dax/super.c:dax_core_init
  - drivers/dma-buf/dma-buf.c:dma_buf_init
  - net/socket.c:sock_init
```
**Symbols:**

```
ffffffff81347b10-ffffffff81347b4a: kern_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct vfsmount *kern_mount(struct file_system_type *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8134dfc0)
Location: fs/namespace.c:4278
Inline: False
Direct callers:
  - kernel/usermode_driver.c:umd_load_blob
  - mm/shmem.c:shmem_init
  - mm/zsmalloc.c:zs_init
  - fs/pipe.c:init_pipe_fs
  - fs/nsfs.c:nsfs_init
  - fs/block_dev.c:bdev_cache_init
  - fs/anon_inodes.c:anon_inode_init
  - fs/aio.c:aio_setup
  - fs/proc/proc_sysctl.c:process_sysctl_arg
  - security/selinux/selinuxfs.c:init_sel_fs
  - security/smack/smackfs.c:init_smk_fs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/dax/super.c:dax_core_init
  - drivers/dma-buf/dma-buf.c:dma_buf_init
  - net/socket.c:sock_init
```
**Symbols:**

```
ffffffff8134dfc0-ffffffff8134dffa: kern_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct vfsmount *kern_mount(struct file_system_type *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8139bfc0)
Location: fs/namespace.c:4356
Inline: False
Direct callers:
  - kernel/usermode_driver.c:umd_load_blob
  - mm/shmem.c:shmem_init
  - mm/zsmalloc.c:zs_init
  - fs/pipe.c:init_pipe_fs
  - fs/nsfs.c:nsfs_init
  - fs/anon_inodes.c:anon_inode_init
  - fs/aio.c:aio_setup
  - fs/proc/proc_sysctl.c:process_sysctl_arg
  - security/selinux/selinuxfs.c:init_sel_fs
  - security/smack/smackfs.c:init_smk_fs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - block/bdev.c:bdev_cache_init
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/dax/super.c:dax_core_init
  - drivers/dma-buf/dma-buf.c:dma_buf_init
  - net/socket.c:sock_init
```
**Symbols:**

```
ffffffff8139bfc0-ffffffff8139bffa: kern_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct vfsmount *kern_mount(struct file_system_type *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8141ef20)
Location: fs/namespace.c:4449
Inline: False
Direct callers:
  - kernel/usermode_driver.c:umd_load_blob
  - mm/shmem.c:shmem_init
  - mm/zsmalloc.c:zs_init
  - fs/pipe.c:init_pipe_fs
  - fs/nsfs.c:nsfs_init
  - fs/anon_inodes.c:anon_inode_init
  - fs/aio.c:aio_setup
  - fs/proc/proc_sysctl.c:process_sysctl_arg
  - security/selinux/selinuxfs.c:init_sel_fs
  - security/smack/smackfs.c:init_smk_fs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - block/bdev.c:bdev_cache_init
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/dax/super.c:dax_core_init
  - drivers/dma-buf/dma-buf.c:dma_buf_init
  - net/socket.c:sock_init
```
**Symbols:**

```
ffffffff8141ef20-ffffffff8141ef72: kern_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct vfsmount *kern_mount(struct file_system_type *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814ab440)
Location: fs/namespace.c:4558
Inline: False
Direct callers:
  - kernel/usermode_driver.c:umd_load_blob
  - mm/shmem.c:shmem_init
  - mm/secretmem.c:secretmem_init
  - fs/pipe.c:init_pipe_fs
  - fs/nsfs.c:nsfs_init
  - fs/anon_inodes.c:anon_inode_init
  - fs/aio.c:aio_setup
  - fs/proc/proc_sysctl.c:process_sysctl_arg
  - security/selinux/selinuxfs.c:init_sel_fs
  - security/smack/smackfs.c:init_smk_fs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - block/bdev.c:bdev_cache_init
  - drivers/dax/super.c:dax_core_init
  - drivers/dma-buf/dma-buf.c:dma_buf_init
  - net/socket.c:sock_init
```
**Symbols:**

```
ffffffff814ab440-ffffffff814ab492: kern_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct vfsmount *kern_mount(struct file_system_type *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814e0240)
Location: fs/namespace.c:4750
Inline: False
Direct callers:
  - kernel/usermode_driver.c:umd_load_blob
  - mm/shmem.c:shmem_init
  - mm/secretmem.c:secretmem_init
  - fs/pipe.c:init_pipe_fs
  - fs/nsfs.c:nsfs_init
  - fs/anon_inodes.c:anon_inode_init
  - fs/aio.c:aio_setup
  - fs/proc/proc_sysctl.c:process_sysctl_arg
  - security/selinux/selinuxfs.c:init_sel_fs
  - security/smack/smackfs.c:init_smk_fs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - block/bdev.c:bdev_cache_init
  - drivers/dax/super.c:dax_core_init
  - drivers/dma-buf/dma-buf.c:dma_buf_init
  - net/socket.c:sock_init
```
**Symbols:**

```
ffffffff814e0240-ffffffff814e0292: kern_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct vfsmount *kern_mount(struct file_system_type *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81513510)
Location: fs/namespace.c:5205
Inline: False
Direct callers:
  - mm/shmem.c:shmem_init
  - mm/secretmem.c:secretmem_init
  - fs/pipe.c:init_pipe_fs
  - fs/nsfs.c:nsfs_init
  - fs/anon_inodes.c:anon_inode_init
  - fs/aio.c:aio_setup
  - fs/proc/proc_sysctl.c:process_sysctl_arg
  - security/selinux/selinuxfs.c:init_sel_fs
  - security/smack/smackfs.c:init_smk_fs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - block/bdev.c:bdev_cache_init
  - drivers/dax/super.c:dax_core_init
  - drivers/dma-buf/dma-buf.c:dma_buf_init
  - net/socket.c:sock_init
```
**Symbols:**

```
ffffffff81513510-ffffffff81513562: kern_mount (STB_GLOBAL)
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
struct vfsmount *kern_mount(struct file_system_type *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffff8000103b5370)
Location: fs/namespace.c:3797
Inline: False
Direct callers:
  - mm/shmem.c:shmem_init
  - mm/zsmalloc.c:zs_init
  - fs/pipe.c:init_pipe_fs
  - fs/nsfs.c:nsfs_init
  - fs/block_dev.c:bdev_cache_init
  - fs/anon_inodes.c:anon_inode_init
  - fs/aio.c:aio_setup
  - security/selinux/selinuxfs.c:init_sel_fs
  - security/smack/smackfs.c:init_smk_fs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/dax/super.c:dax_core_init
  - drivers/dma-buf/dma-buf.c:dma_buf_init
  - net/socket.c:sock_init
```
**Symbols:**

```
ffff8000103b5370-ffff8000103b53c0: kern_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct vfsmount *kern_mount(struct file_system_type *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0593eac)
Location: fs/namespace.c:3797
Inline: False
Direct callers:
  - mm/shmem.c:shmem_init
  - mm/zsmalloc.c:zs_init
  - fs/pipe.c:init_pipe_fs
  - fs/nsfs.c:nsfs_init
  - fs/block_dev.c:bdev_cache_init
  - fs/anon_inodes.c:anon_inode_init
  - fs/aio.c:aio_setup
  - security/selinux/selinuxfs.c:init_sel_fs
  - security/smack/smackfs.c:init_smk_fs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/dax/super.c:dax_core_init
  - drivers/dma-buf/dma-buf.c:dma_buf_init
  - net/socket.c:sock_init
```
**Symbols:**

```
c0593eac-c0593ef0: kern_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct vfsmount *kern_mount(struct file_system_type *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0000000004b19b0)
Location: fs/namespace.c:3797
Inline: False
Direct callers:
  - mm/shmem.c:shmem_init
  - mm/zsmalloc.c:zs_init
  - fs/pipe.c:init_pipe_fs
  - fs/nsfs.c:nsfs_init
  - fs/block_dev.c:bdev_cache_init
  - fs/anon_inodes.c:anon_inode_init
  - fs/aio.c:aio_setup
  - security/selinux/selinuxfs.c:init_sel_fs
  - security/smack/smackfs.c:init_smk_fs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/dax/super.c:dax_core_init
  - drivers/dma-buf/dma-buf.c:dma_buf_init
  - net/socket.c:sock_init
```
**Symbols:**

```
c0000000004b19b0-c0000000004b1a18: kern_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct vfsmount *kern_mount(struct file_system_type *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffe0002783c8)
Location: fs/namespace.c:3797
Inline: False
Direct callers:
  - mm/shmem.c:shmem_init
  - mm/zsmalloc.c:zs_init
  - fs/pipe.c:init_pipe_fs
  - fs/nsfs.c:nsfs_init
  - fs/block_dev.c:bdev_cache_init
  - fs/anon_inodes.c:anon_inode_init
  - fs/aio.c:aio_setup
  - security/selinux/selinuxfs.c:init_sel_fs
  - security/smack/smackfs.c:init_smk_fs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/dax/super.c:dax_core_init
  - drivers/dma-buf/dma-buf.c:dma_buf_init
  - net/socket.c:sock_init
```
**Symbols:**

```
ffffffe0002783c8-ffffffe000278408: kern_mount (STB_GLOBAL)
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
struct vfsmount *kern_mount(struct file_system_type *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812fac30)
Location: fs/namespace.c:3797
Inline: False
Direct callers:
  - mm/shmem.c:shmem_init
  - mm/zsmalloc.c:zs_init
  - fs/pipe.c:init_pipe_fs
  - fs/nsfs.c:nsfs_init
  - fs/block_dev.c:bdev_cache_init
  - fs/anon_inodes.c:anon_inode_init
  - fs/aio.c:aio_setup
  - security/selinux/selinuxfs.c:init_sel_fs
  - security/smack/smackfs.c:init_smk_fs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/dax/super.c:dax_core_init
  - drivers/dma-buf/dma-buf.c:dma_buf_init
  - net/socket.c:sock_init
```
**Symbols:**

```
ffffffff812fac30-ffffffff812fac6a: kern_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct vfsmount *kern_mount(struct file_system_type *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812eb850)
Location: fs/namespace.c:3797
Inline: False
Direct callers:
  - mm/shmem.c:shmem_init
  - mm/zsmalloc.c:zs_init
  - fs/pipe.c:init_pipe_fs
  - fs/nsfs.c:nsfs_init
  - fs/block_dev.c:bdev_cache_init
  - fs/anon_inodes.c:anon_inode_init
  - fs/aio.c:aio_setup
  - security/selinux/selinuxfs.c:init_sel_fs
  - security/smack/smackfs.c:init_smk_fs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/dax/super.c:dax_core_init
  - drivers/dma-buf/dma-buf.c:dma_buf_init
  - net/socket.c:sock_init
```
**Symbols:**

```
ffffffff812eb850-ffffffff812eb88a: kern_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct vfsmount *kern_mount(struct file_system_type *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812f8a20)
Location: fs/namespace.c:3797
Inline: False
Direct callers:
  - mm/shmem.c:shmem_init
  - mm/zsmalloc.c:zs_init
  - fs/pipe.c:init_pipe_fs
  - fs/nsfs.c:nsfs_init
  - fs/block_dev.c:bdev_cache_init
  - fs/anon_inodes.c:anon_inode_init
  - fs/aio.c:aio_setup
  - security/selinux/selinuxfs.c:init_sel_fs
  - security/smack/smackfs.c:init_smk_fs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/dax/super.c:dax_core_init
  - drivers/dma-buf/dma-buf.c:dma_buf_init
  - net/socket.c:sock_init
```
**Symbols:**

```
ffffffff812f8a20-ffffffff812f8a5a: kern_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct vfsmount *kern_mount(struct file_system_type *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81309e20)
Location: fs/namespace.c:3797
Inline: False
Direct callers:
  - mm/shmem.c:shmem_init
  - mm/zsmalloc.c:zs_init
  - fs/pipe.c:init_pipe_fs
  - fs/nsfs.c:nsfs_init
  - fs/block_dev.c:bdev_cache_init
  - fs/anon_inodes.c:anon_inode_init
  - fs/aio.c:aio_setup
  - security/selinux/selinuxfs.c:init_sel_fs
  - security/smack/smackfs.c:init_smk_fs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/dax/super.c:dax_core_init
  - drivers/dma-buf/dma-buf.c:dma_buf_init
  - net/socket.c:sock_init
```
**Symbols:**

```
ffffffff81309e20-ffffffff81309e5a: kern_mount (STB_GLOBAL)
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
