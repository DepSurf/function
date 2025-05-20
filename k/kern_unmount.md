# Function: <code>kern_unmount</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void kern_unmount(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8122d160)
Location: fs/namespace.c:3173
Inline: True
Direct callers:
  - fs/proc/root.c:pid_ns_release_proc
  - fs/hugetlbfs/inode.c:exit_hugetlbfs_fs
  - ipc/mqueue.c:mq_put_mnt
  - security/selinux/selinuxfs.c:exit_sel_fs
```
**Symbols:**

```
ffffffff8122d160-ffffffff8122d1b0: kern_unmount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void kern_unmount(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81255900)
Location: fs/namespace.c:3160
Inline: True
Direct callers:
  - mm/zsmalloc.c:zs_exit
  - fs/proc/root.c:pid_ns_release_proc
  - ipc/mqueue.c:mq_put_mnt
  - security/selinux/selinuxfs.c:exit_sel_fs
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
```
**Symbols:**

```
ffffffff81255900-ffffffff81255950: kern_unmount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void kern_unmount(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81268cf0)
Location: fs/namespace.c:3304
Inline: True
Direct callers:
  - mm/zsmalloc.c:zs_exit
  - fs/proc/root.c:pid_ns_release_proc
  - ipc/mqueue.c:mq_put_mnt
  - security/selinux/selinuxfs.c:exit_sel_fs
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
```
**Symbols:**

```
ffffffff81268cf0-ffffffff81268d40: kern_unmount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void kern_unmount(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81276490)
Location: fs/namespace.c:3240
Inline: True
Direct callers:
  - mm/zsmalloc.c:zs_exit
  - mm/zsmalloc.c:zs_init
  - fs/proc/root.c:pid_ns_release_proc
  - ipc/mqueue.c:mq_put_mnt
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/dax/super.c:__dax_fs_exit
```
**Symbols:**

```
ffffffff81276490-ffffffff812764e1: kern_unmount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void kern_unmount(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81298de0)
Location: fs/namespace.c:3313
Inline: True
Direct callers:
  - mm/zsmalloc.c:zs_exit
  - mm/zsmalloc.c:zs_init
  - fs/proc/root.c:pid_ns_release_proc
  - ipc/mqueue.c:mq_put_mnt
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/dax/super.c:__dax_fs_exit
```
**Symbols:**

```
ffffffff81298de0-ffffffff81298e31: kern_unmount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void kern_unmount(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812befd0)
Location: fs/namespace.c:3350
Inline: True
Direct callers:
  - mm/zsmalloc.c:zs_exit
  - mm/zsmalloc.c:zs_init
  - fs/proc/root.c:pid_ns_release_proc
  - ipc/mqueue.c:mq_put_mnt
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/dax/super.c:__dax_fs_exit
```
**Symbols:**

```
ffffffff812befd0-ffffffff812bf01f: kern_unmount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void kern_unmount(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812d41c0)
Location: fs/namespace.c:3322
Inline: True
Direct callers:
  - mm/zsmalloc.c:zs_exit
  - mm/zsmalloc.c:zs_init
  - fs/proc/root.c:pid_ns_release_proc
  - ipc/mqueue.c:mq_put_mnt
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/dax/super.c:__dax_fs_exit
```
**Symbols:**

```
ffffffff812d41c0-ffffffff812d420f: kern_unmount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void kern_unmount(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812f17d0)
Location: fs/namespace.c:3779
Inline: True
Direct callers:
  - mm/zsmalloc.c:zs_exit
  - mm/zsmalloc.c:zs_init
  - fs/proc/root.c:pid_ns_release_proc
  - ipc/mqueue.c:mq_put_mnt
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/dax/super.c:dax_fs_exit
  - drivers/dma-buf/dma-buf.c:dma_buf_deinit
```
**Symbols:**

```
ffffffff812f17d0-ffffffff812f181e: kern_unmount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void kern_unmount(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81303380)
Location: fs/namespace.c:3812
Inline: True
Direct callers:
  - mm/zsmalloc.c:zs_exit
  - mm/zsmalloc.c:zs_init
  - fs/proc/root.c:pid_ns_release_proc
  - ipc/mqueue.c:mq_put_mnt
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/dax/super.c:dax_fs_exit
  - drivers/dma-buf/dma-buf.c:dma_buf_deinit
```
**Symbols:**

```
ffffffff81303380-ffffffff813033ce: kern_unmount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void kern_unmount(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8133ca20)
Location: fs/namespace.c:3865
Inline: True
Direct callers:
  - mm/zsmalloc.c:zs_exit
  - mm/zsmalloc.c:zs_init
  - fs/proc/proc_sysctl.c:do_sysctl_args
  - ipc/mqueue.c:mq_put_mnt
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/dax/super.c:dax_fs_exit
  - drivers/dma-buf/dma-buf.c:dma_buf_deinit
```
**Symbols:**

```
ffffffff8133ca20-ffffffff8133ca71: kern_unmount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void kern_unmount(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff813488e0)
Location: fs/namespace.c:3887
Inline: True
Direct callers:
  - kernel/usermode_driver.c:umd_unload_blob
  - mm/zsmalloc.c:zs_exit
  - mm/zsmalloc.c:zs_init
  - fs/proc/proc_sysctl.c:do_sysctl_args
  - ipc/mqueue.c:mq_put_mnt
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/dax/super.c:dax_fs_exit
  - drivers/dma-buf/dma-buf.c:dma_buf_deinit
```
**Symbols:**

```
ffffffff813488e0-ffffffff81348931: kern_unmount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void kern_unmount(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8134ecb0)
Location: fs/namespace.c:4293
Inline: True
Direct callers:
  - kernel/usermode_driver.c:umd_unload_blob
  - mm/zsmalloc.c:zs_exit
  - mm/zsmalloc.c:zs_init
  - fs/proc/proc_sysctl.c:do_sysctl_args
  - ipc/mqueue.c:mq_put_mnt
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/dax/super.c:dax_fs_exit
  - drivers/dma-buf/dma-buf.c:dma_buf_deinit
```
**Symbols:**

```
ffffffff8134ecb0-ffffffff8134ed01: kern_unmount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void kern_unmount(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8139cd50)
Location: fs/namespace.c:4371
Inline: True
Direct callers:
  - kernel/usermode_driver.c:umd_unload_blob
  - mm/zsmalloc.c:zs_exit
  - mm/zsmalloc.c:zs_init
  - fs/proc/proc_sysctl.c:do_sysctl_args
  - ipc/mqueue.c:mq_put_mnt
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/dax/super.c:dax_fs_exit
  - drivers/dma-buf/dma-buf.c:dma_buf_deinit
```
**Symbols:**

```
ffffffff8139cd50-ffffffff8139cda1: kern_unmount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void kern_unmount(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8141fc90)
Location: fs/namespace.c:4464
Inline: True
Direct callers:
  - kernel/usermode_driver.c:umd_unload_blob
  - kernel/usermode_driver.c:umd_load_blob
  - kernel/usermode_driver.c:umd_load_blob
  - kernel/usermode_driver.c:umd_load_blob
  - mm/zsmalloc.c:zs_exit
  - mm/zsmalloc.c:zs_init
  - fs/proc/proc_sysctl.c:do_sysctl_args
  - ipc/mqueue.c:mq_put_mnt
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/dax/super.c:dax_fs_exit
  - drivers/dma-buf/dma-buf.c:dma_buf_deinit
```
**Symbols:**

```
ffffffff8141fc90-ffffffff8141fcf1: kern_unmount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void kern_unmount(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814ac190)
Location: fs/namespace.c:4573
Inline: True
Direct callers:
  - kernel/usermode_driver.c:umd_unload_blob
  - kernel/usermode_driver.c:umd_load_blob
  - kernel/usermode_driver.c:umd_load_blob
  - kernel/usermode_driver.c:umd_load_blob
  - fs/proc/proc_sysctl.c:do_sysctl_args
  - ipc/mqueue.c:mq_put_mnt
  - drivers/dax/super.c:dax_core_exit
  - drivers/dax/super.c:dax_core_init
  - drivers/dma-buf/dma-buf.c:dma_buf_deinit
```
**Symbols:**

```
ffffffff814ac190-ffffffff814ac1f1: kern_unmount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void kern_unmount(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814e0f50)
Location: fs/namespace.c:4765
Inline: False
Direct callers:
  - kernel/usermode_driver.c:umd_unload_blob
  - kernel/usermode_driver.c:umd_load_blob
  - kernel/usermode_driver.c:umd_load_blob
  - kernel/usermode_driver.c:umd_load_blob
  - fs/proc/proc_sysctl.c:do_sysctl_args
  - drivers/dax/super.c:dax_core_exit
  - drivers/dax/super.c:dax_core_init
  - drivers/dma-buf/dma-buf.c:dma_buf_deinit
```
**Symbols:**

```
ffffffff814e0f50-ffffffff814e0fc4: kern_unmount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void kern_unmount(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81515020)
Location: fs/namespace.c:5220
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:do_sysctl_args
  - drivers/dax/super.c:dax_core_exit
  - drivers/dax/super.c:dax_core_init
  - drivers/dma-buf/dma-buf.c:dma_buf_deinit
```
**Symbols:**

```
ffffffff81515020-ffffffff81515094: kern_unmount (STB_GLOBAL)
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
void kern_unmount(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffff8000103b67d8)
Location: fs/namespace.c:3812
Inline: True
Direct callers:
  - mm/zsmalloc.c:zs_exit
  - mm/zsmalloc.c:zs_init
  - fs/proc/root.c:pid_ns_release_proc
  - ipc/mqueue.c:mq_put_mnt
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/dax/super.c:dax_fs_exit
  - drivers/dma-buf/dma-buf.c:dma_buf_deinit
```
**Symbols:**

```
ffff8000103b67d8-ffff8000103b682c: kern_unmount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void kern_unmount(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0594a90)
Location: fs/namespace.c:3812
Inline: True
Direct callers:
  - mm/zsmalloc.c:zs_exit
  - mm/zsmalloc.c:zs_init
  - fs/proc/root.c:pid_ns_release_proc
  - ipc/mqueue.c:mq_put_mnt
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/dax/super.c:dax_fs_exit
  - drivers/dma-buf/dma-buf.c:dma_buf_deinit
```
**Symbols:**

```
c0594a90-c0594ae0: kern_unmount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void kern_unmount(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0000000004b2f80)
Location: fs/namespace.c:3812
Inline: True
Direct callers:
  - mm/zsmalloc.c:zs_exit
  - mm/zsmalloc.c:zs_init
  - fs/proc/root.c:pid_ns_release_proc
  - ipc/mqueue.c:mq_put_mnt
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/dax/super.c:dax_fs_exit
  - drivers/dma-buf/dma-buf.c:dma_buf_deinit
```
**Symbols:**

```
c0000000004b2f80-c0000000004b3008: kern_unmount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void kern_unmount(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffe0002793e4)
Location: fs/namespace.c:3812
Inline: True
Direct callers:
  - mm/zsmalloc.c:zs_exit
  - mm/zsmalloc.c:zs_init
  - fs/proc/root.c:pid_ns_release_proc
  - ipc/mqueue.c:mq_put_mnt
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/dax/super.c:dax_fs_exit
  - drivers/dma-buf/dma-buf.c:dma_buf_deinit
```
**Symbols:**

```
ffffffe0002793e4-ffffffe000279430: kern_unmount (STB_GLOBAL)
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
void kern_unmount(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812fb960)
Location: fs/namespace.c:3812
Inline: True
Direct callers:
  - mm/zsmalloc.c:zs_exit
  - mm/zsmalloc.c:zs_init
  - fs/proc/root.c:pid_ns_release_proc
  - ipc/mqueue.c:mq_put_mnt
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/dax/super.c:dax_fs_exit
  - drivers/dma-buf/dma-buf.c:dma_buf_deinit
```
**Symbols:**

```
ffffffff812fb960-ffffffff812fb9ae: kern_unmount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void kern_unmount(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812ec580)
Location: fs/namespace.c:3812
Inline: True
Direct callers:
  - mm/zsmalloc.c:zs_exit
  - mm/zsmalloc.c:zs_init
  - fs/proc/root.c:pid_ns_release_proc
  - ipc/mqueue.c:mq_put_mnt
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/dax/super.c:dax_fs_exit
  - drivers/dma-buf/dma-buf.c:dma_buf_deinit
```
**Symbols:**

```
ffffffff812ec580-ffffffff812ec5ce: kern_unmount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void kern_unmount(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812f9750)
Location: fs/namespace.c:3812
Inline: True
Direct callers:
  - mm/zsmalloc.c:zs_exit
  - mm/zsmalloc.c:zs_init
  - fs/proc/root.c:pid_ns_release_proc
  - ipc/mqueue.c:mq_put_mnt
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/dax/super.c:dax_fs_exit
  - drivers/dma-buf/dma-buf.c:dma_buf_deinit
```
**Symbols:**

```
ffffffff812f9750-ffffffff812f979e: kern_unmount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void kern_unmount(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8130aa60)
Location: fs/namespace.c:3812
Inline: True
Direct callers:
  - mm/zsmalloc.c:zs_exit
  - mm/zsmalloc.c:zs_init
  - fs/proc/root.c:pid_ns_release_proc
  - ipc/mqueue.c:mq_put_mnt
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/dax/super.c:dax_fs_exit
  - drivers/dma-buf/dma-buf.c:dma_buf_deinit
```
**Symbols:**

```
ffffffff8130aa60-ffffffff8130aaae: kern_unmount (STB_GLOBAL)
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
