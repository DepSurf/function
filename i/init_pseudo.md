# Function: <code>init_pseudo</code>

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
struct pseudo_fs_context *init_pseudo(struct fs_context *fc, long unsigned int magic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff812f9c80)
Location: fs/libfs.c:291
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_init_fs_context
  - fs/pipe.c:pipefs_init_fs_context
  - fs/nsfs.c:nsfs_init_fs_context
  - fs/block_dev.c:bd_init_fs_context
  - fs/anon_inodes.c:anon_inodefs_init_fs_context
  - fs/aio.c:aio_init_fs_context
  - drivers/virtio/virtio_balloon.c:balloon_init_fs_context
  - drivers/dax/super.c:dax_init_fs_context
  - drivers/dma-buf/dma-buf.c:dma_buf_fs_init_context
  - net/socket.c:sockfs_init_fs_context
```
**Symbols:**

```
ffffffff812f9c80-ffffffff812f9cd2: init_pseudo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct pseudo_fs_context *init_pseudo(struct fs_context *fc, long unsigned int magic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff8130b8b0)
Location: fs/libfs.c:297
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_init_fs_context
  - fs/pipe.c:pipefs_init_fs_context
  - fs/nsfs.c:nsfs_init_fs_context
  - fs/block_dev.c:bd_init_fs_context
  - fs/anon_inodes.c:anon_inodefs_init_fs_context
  - fs/aio.c:aio_init_fs_context
  - drivers/virtio/virtio_balloon.c:balloon_init_fs_context
  - drivers/dax/super.c:dax_init_fs_context
  - drivers/dma-buf/dma-buf.c:dma_buf_fs_init_context
  - net/socket.c:sockfs_init_fs_context
```
**Symbols:**

```
ffffffff8130b8b0-ffffffff8130b902: init_pseudo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct pseudo_fs_context *init_pseudo(struct fs_context *fc, long unsigned int magic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81345920)
Location: fs/libfs.c:366
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_init_fs_context
  - fs/pipe.c:pipefs_init_fs_context
  - fs/nsfs.c:nsfs_init_fs_context
  - fs/block_dev.c:bd_init_fs_context
  - fs/anon_inodes.c:anon_inodefs_init_fs_context
  - fs/aio.c:aio_init_fs_context
  - drivers/virtio/virtio_balloon.c:balloon_init_fs_context
  - drivers/char/mem.c:devmem_fs_init_fs_context
  - drivers/dax/super.c:dax_init_fs_context
  - drivers/dma-buf/dma-buf.c:dma_buf_fs_init_context
  - net/socket.c:sockfs_init_fs_context
```
**Symbols:**

```
ffffffff81345920-ffffffff81345972: init_pseudo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct pseudo_fs_context *init_pseudo(struct fs_context *fc, long unsigned int magic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81351cf0)
Location: fs/libfs.c:368
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_init_fs_context
  - fs/pipe.c:pipefs_init_fs_context
  - fs/nsfs.c:nsfs_init_fs_context
  - fs/block_dev.c:bd_init_fs_context
  - fs/anon_inodes.c:anon_inodefs_init_fs_context
  - fs/aio.c:aio_init_fs_context
  - drivers/virtio/virtio_balloon.c:balloon_init_fs_context
  - drivers/char/mem.c:devmem_fs_init_fs_context
  - drivers/dax/super.c:dax_init_fs_context
  - drivers/dma-buf/dma-buf.c:dma_buf_fs_init_context
  - net/socket.c:sockfs_init_fs_context
```
**Symbols:**

```
ffffffff81351cf0-ffffffff81351d42: init_pseudo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct pseudo_fs_context *init_pseudo(struct fs_context *fc, long unsigned int magic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81358a10)
Location: fs/libfs.c:369
Inline: False
Direct callers:
  - kernel/resource.c:iomem_fs_init_fs_context
  - mm/zsmalloc.c:zs_init_fs_context
  - fs/pipe.c:pipefs_init_fs_context
  - fs/nsfs.c:nsfs_init_fs_context
  - fs/block_dev.c:bd_init_fs_context
  - fs/anon_inodes.c:anon_inodefs_init_fs_context
  - fs/aio.c:aio_init_fs_context
  - drivers/virtio/virtio_balloon.c:balloon_init_fs_context
  - drivers/dax/super.c:dax_init_fs_context
  - drivers/dma-buf/dma-buf.c:dma_buf_fs_init_context
  - net/socket.c:sockfs_init_fs_context
```
**Symbols:**

```
ffffffff81358a10-ffffffff81358a62: init_pseudo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct pseudo_fs_context *init_pseudo(struct fs_context *fc, long unsigned int magic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff813a7040)
Location: fs/libfs.c:369
Inline: False
Direct callers:
  - kernel/resource.c:iomem_fs_init_fs_context
  - mm/zsmalloc.c:zs_init_fs_context
  - mm/secretmem.c:secretmem_init_fs_context
  - fs/pipe.c:pipefs_init_fs_context
  - fs/nsfs.c:nsfs_init_fs_context
  - fs/anon_inodes.c:anon_inodefs_init_fs_context
  - fs/aio.c:aio_init_fs_context
  - block/bdev.c:bd_init_fs_context
  - drivers/virtio/virtio_balloon.c:balloon_init_fs_context
  - drivers/dax/super.c:dax_init_fs_context
  - drivers/dma-buf/dma-buf.c:dma_buf_fs_init_context
  - net/socket.c:sockfs_init_fs_context
```
**Symbols:**

```
ffffffff813a7040-ffffffff813a7092: init_pseudo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct pseudo_fs_context *init_pseudo(struct fs_context *fc, long unsigned int magic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff8142c0e0)
Location: fs/libfs.c:369
Inline: False
Direct callers:
  - kernel/resource.c:iomem_fs_init_fs_context
  - mm/zsmalloc.c:zs_init_fs_context
  - mm/secretmem.c:secretmem_init_fs_context
  - fs/pipe.c:pipefs_init_fs_context
  - fs/nsfs.c:nsfs_init_fs_context
  - fs/anon_inodes.c:anon_inodefs_init_fs_context
  - fs/aio.c:aio_init_fs_context
  - block/bdev.c:bd_init_fs_context
  - drivers/virtio/virtio_balloon.c:balloon_init_fs_context
  - drivers/dax/super.c:dax_init_fs_context
  - drivers/dma-buf/dma-buf.c:dma_buf_fs_init_context
  - net/socket.c:sockfs_init_fs_context
```
**Symbols:**

```
ffffffff8142c0e0-ffffffff8142c13c: init_pseudo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct pseudo_fs_context *init_pseudo(struct fs_context *fc, long unsigned int magic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff814b97e0)
Location: fs/libfs.c:370
Inline: False
Direct callers:
  - kernel/resource.c:iomem_fs_init_fs_context
  - mm/secretmem.c:secretmem_init_fs_context
  - fs/pipe.c:pipefs_init_fs_context
  - fs/nsfs.c:nsfs_init_fs_context
  - fs/anon_inodes.c:anon_inodefs_init_fs_context
  - fs/aio.c:aio_init_fs_context
  - block/bdev.c:bd_init_fs_context
  - drivers/dax/super.c:dax_init_fs_context
  - drivers/dma-buf/dma-buf.c:dma_buf_fs_init_context
  - net/socket.c:sockfs_init_fs_context
```
**Symbols:**

```
ffffffff814b97e0-ffffffff814b983c: init_pseudo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct pseudo_fs_context *init_pseudo(struct fs_context *fc, long unsigned int magic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff814ee790)
Location: fs/libfs.c:365
Inline: False
Direct callers:
  - kernel/resource.c:iomem_fs_init_fs_context
  - mm/secretmem.c:secretmem_init_fs_context
  - fs/pipe.c:pipefs_init_fs_context
  - fs/nsfs.c:nsfs_init_fs_context
  - fs/anon_inodes.c:anon_inodefs_init_fs_context
  - fs/aio.c:aio_init_fs_context
  - block/bdev.c:bd_init_fs_context
  - drivers/dax/super.c:dax_init_fs_context
  - drivers/dma-buf/dma-buf.c:dma_buf_fs_init_context
  - net/socket.c:sockfs_init_fs_context
```
**Symbols:**

```
ffffffff814ee790-ffffffff814ee7ec: init_pseudo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct pseudo_fs_context *init_pseudo(struct fs_context *fc, long unsigned int magic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81522760)
Location: fs/libfs.c:621
Inline: False
Direct callers:
  - kernel/resource.c:iomem_fs_init_fs_context
  - mm/secretmem.c:secretmem_init_fs_context
  - fs/pipe.c:pipefs_init_fs_context
  - fs/nsfs.c:nsfs_init_fs_context
  - fs/anon_inodes.c:anon_inodefs_init_fs_context
  - fs/aio.c:aio_init_fs_context
  - block/bdev.c:bd_init_fs_context
  - drivers/dax/super.c:dax_init_fs_context
  - drivers/dma-buf/dma-buf.c:dma_buf_fs_init_context
  - drivers/gpu/drm/drm_drv.c:drm_fs_init_fs_context
  - net/socket.c:sockfs_init_fs_context
```
**Symbols:**

```
ffffffff81522760-ffffffff815227f1: init_pseudo (STB_GLOBAL)
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
struct pseudo_fs_context *init_pseudo(struct fs_context *fc, long unsigned int magic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffff8000103bff20)
Location: fs/libfs.c:297
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_init_fs_context
  - fs/pipe.c:pipefs_init_fs_context
  - fs/nsfs.c:nsfs_init_fs_context
  - fs/block_dev.c:bd_init_fs_context
  - fs/anon_inodes.c:anon_inodefs_init_fs_context
  - fs/aio.c:aio_init_fs_context
  - drivers/virtio/virtio_balloon.c:balloon_init_fs_context
  - drivers/dax/super.c:dax_init_fs_context
  - drivers/dma-buf/dma-buf.c:dma_buf_fs_init_context
  - net/socket.c:sockfs_init_fs_context
```
**Symbols:**

```
ffff8000103bff20-ffff8000103bff90: init_pseudo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct pseudo_fs_context *init_pseudo(struct fs_context *fc, long unsigned int magic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (c059cfcc)
Location: fs/libfs.c:297
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_init_fs_context
  - fs/pipe.c:pipefs_init_fs_context
  - fs/nsfs.c:nsfs_init_fs_context
  - fs/block_dev.c:bd_init_fs_context
  - fs/anon_inodes.c:anon_inodefs_init_fs_context
  - fs/aio.c:aio_init_fs_context
  - drivers/virtio/virtio_balloon.c:balloon_init_fs_context
  - drivers/dax/super.c:dax_init_fs_context
  - drivers/dma-buf/dma-buf.c:dma_buf_fs_init_context
  - net/socket.c:sockfs_init_fs_context
```
**Symbols:**

```
c059cfcc-c059d038: init_pseudo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct pseudo_fs_context *init_pseudo(struct fs_context *fc, long unsigned int magic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (c0000000004c0450)
Location: fs/libfs.c:297
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_init_fs_context
  - fs/pipe.c:pipefs_init_fs_context
  - fs/nsfs.c:nsfs_init_fs_context
  - fs/block_dev.c:bd_init_fs_context
  - fs/anon_inodes.c:anon_inodefs_init_fs_context
  - fs/aio.c:aio_init_fs_context
  - drivers/virtio/virtio_balloon.c:balloon_init_fs_context
  - drivers/dax/super.c:dax_init_fs_context
  - drivers/dma-buf/dma-buf.c:dma_buf_fs_init_context
  - net/socket.c:sockfs_init_fs_context
```
**Symbols:**

```
c0000000004c0450-c0000000004c04e4: init_pseudo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct pseudo_fs_context *init_pseudo(struct fs_context *fc, long unsigned int magic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffe000280708)
Location: fs/libfs.c:297
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_init_fs_context
  - fs/pipe.c:pipefs_init_fs_context
  - fs/nsfs.c:nsfs_init_fs_context
  - fs/block_dev.c:bd_init_fs_context
  - fs/anon_inodes.c:anon_inodefs_init_fs_context
  - fs/aio.c:aio_init_fs_context
  - drivers/virtio/virtio_balloon.c:balloon_init_fs_context
  - drivers/dax/super.c:dax_init_fs_context
  - drivers/dma-buf/dma-buf.c:dma_buf_fs_init_context
  - net/socket.c:sockfs_init_fs_context
```
**Symbols:**

```
ffffffe000280708-ffffffe000280776: init_pseudo (STB_GLOBAL)
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
struct pseudo_fs_context *init_pseudo(struct fs_context *fc, long unsigned int magic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81303e90)
Location: fs/libfs.c:297
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_init_fs_context
  - fs/pipe.c:pipefs_init_fs_context
  - fs/nsfs.c:nsfs_init_fs_context
  - fs/block_dev.c:bd_init_fs_context
  - fs/anon_inodes.c:anon_inodefs_init_fs_context
  - fs/aio.c:aio_init_fs_context
  - drivers/virtio/virtio_balloon.c:balloon_init_fs_context
  - drivers/dax/super.c:dax_init_fs_context
  - drivers/dma-buf/dma-buf.c:dma_buf_fs_init_context
  - net/socket.c:sockfs_init_fs_context
```
**Symbols:**

```
ffffffff81303e90-ffffffff81303ee2: init_pseudo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct pseudo_fs_context *init_pseudo(struct fs_context *fc, long unsigned int magic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff812f4ab0)
Location: fs/libfs.c:297
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_init_fs_context
  - fs/pipe.c:pipefs_init_fs_context
  - fs/nsfs.c:nsfs_init_fs_context
  - fs/block_dev.c:bd_init_fs_context
  - fs/anon_inodes.c:anon_inodefs_init_fs_context
  - fs/aio.c:aio_init_fs_context
  - drivers/virtio/virtio_balloon.c:balloon_init_fs_context
  - drivers/dax/super.c:dax_init_fs_context
  - drivers/dma-buf/dma-buf.c:dma_buf_fs_init_context
  - net/socket.c:sockfs_init_fs_context
```
**Symbols:**

```
ffffffff812f4ab0-ffffffff812f4b02: init_pseudo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct pseudo_fs_context *init_pseudo(struct fs_context *fc, long unsigned int magic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81301c80)
Location: fs/libfs.c:297
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_init_fs_context
  - fs/pipe.c:pipefs_init_fs_context
  - fs/nsfs.c:nsfs_init_fs_context
  - fs/block_dev.c:bd_init_fs_context
  - fs/anon_inodes.c:anon_inodefs_init_fs_context
  - fs/aio.c:aio_init_fs_context
  - drivers/virtio/virtio_balloon.c:balloon_init_fs_context
  - drivers/dax/super.c:dax_init_fs_context
  - drivers/dma-buf/dma-buf.c:dma_buf_fs_init_context
  - net/socket.c:sockfs_init_fs_context
```
**Symbols:**

```
ffffffff81301c80-ffffffff81301cd2: init_pseudo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct pseudo_fs_context *init_pseudo(struct fs_context *fc, long unsigned int magic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81313050)
Location: fs/libfs.c:297
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_init_fs_context
  - fs/pipe.c:pipefs_init_fs_context
  - fs/nsfs.c:nsfs_init_fs_context
  - fs/block_dev.c:bd_init_fs_context
  - fs/anon_inodes.c:anon_inodefs_init_fs_context
  - fs/aio.c:aio_init_fs_context
  - drivers/virtio/virtio_balloon.c:balloon_init_fs_context
  - drivers/dax/super.c:dax_init_fs_context
  - drivers/dma-buf/dma-buf.c:dma_buf_fs_init_context
  - net/socket.c:sockfs_init_fs_context
```
**Symbols:**

```
ffffffff81313050-ffffffff813130a2: init_pseudo (STB_GLOBAL)
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
