# Function: <code>alloc_anon_inode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct inode *alloc_anon_inode(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81234730)
Location: fs/libfs.c:1048
Inline: False
Direct callers:
  - fs/anon_inodes.c:anon_inode_init
  - fs/aio.c:SyS_io_setup
```
**Symbols:**

```
ffffffff81234730-ffffffff812347d7: alloc_anon_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct inode *alloc_anon_inode(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff8125cbc0)
Location: fs/libfs.c:1071
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_create_pool
  - fs/anon_inodes.c:anon_inode_init
  - fs/aio.c:aio_setup_ring
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
```
**Symbols:**

```
ffffffff8125cbc0-ffffffff8125cc67: alloc_anon_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct inode *alloc_anon_inode(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81270110)
Location: fs/libfs.c:1079
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_create_pool
  - fs/anon_inodes.c:anon_inode_init
  - fs/aio.c:aio_setup_ring
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
```
**Symbols:**

```
ffffffff81270110-ffffffff812701ab: alloc_anon_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct inode *alloc_anon_inode(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff8127d830)
Location: fs/libfs.c:1084
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_create_pool
  - fs/anon_inodes.c:anon_inode_init
  - fs/aio.c:aio_setup_ring
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
```
**Symbols:**

```
ffffffff8127d830-ffffffff8127d8cf: alloc_anon_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct inode *alloc_anon_inode(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff812a02d0)
Location: fs/libfs.c:1084
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_create_pool
  - fs/anon_inodes.c:anon_inode_init
  - fs/aio.c:aio_setup_ring
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
```
**Symbols:**

```
ffffffff812a02d0-ffffffff812a036f: alloc_anon_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct inode *alloc_anon_inode(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff812c6a70)
Location: fs/libfs.c:1123
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_create_pool
  - fs/anon_inodes.c:anon_inode_init
  - fs/aio.c:aio_setup_ring
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
```
**Symbols:**

```
ffffffff812c6a70-ffffffff812c6b0b: alloc_anon_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct inode *alloc_anon_inode(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff812dbc70)
Location: fs/libfs.c:1123
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_create_pool
  - fs/anon_inodes.c:anon_inode_init
  - fs/aio.c:aio_setup_ring
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
```
**Symbols:**

```
ffffffff812dbc70-ffffffff812dbd0b: alloc_anon_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct inode *alloc_anon_inode(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff812fa2f0)
Location: fs/libfs.c:1142
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_create_pool
  - fs/anon_inodes.c:anon_inode_init
  - fs/aio.c:aio_setup_ring
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/dma-buf/dma-buf.c:dma_buf_export
```
**Symbols:**

```
ffffffff812fa2f0-ffffffff812fa3a2: alloc_anon_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct inode *alloc_anon_inode(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff8130c0f0)
Location: fs/libfs.c:1182
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_create_pool
  - fs/anon_inodes.c:anon_inode_init
  - fs/aio.c:aio_setup_ring
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/dma-buf/dma-buf.c:dma_buf_export
```
**Symbols:**

```
ffffffff8130c0f0-ffffffff8130c1a2: alloc_anon_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct inode *alloc_anon_inode(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff813455d0)
Location: fs/libfs.c:1218
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_create_pool
  - fs/anon_inodes.c:anon_inode_init
  - fs/aio.c:aio_setup_ring
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/char/mem.c:chr_dev_init
  - drivers/dma-buf/dma-buf.c:dma_buf_export
```
**Symbols:**

```
ffffffff813455d0-ffffffff81345684: alloc_anon_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct inode *alloc_anon_inode(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81351920)
Location: fs/libfs.c:1222
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_create_pool
  - fs/anon_inodes.c:anon_inode_init
  - fs/aio.c:aio_setup_ring
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/char/mem.c:chr_dev_init
  - drivers/dma-buf/dma-buf.c:dma_buf_export
```
**Symbols:**

```
ffffffff81351920-ffffffff813519d4: alloc_anon_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct inode *alloc_anon_inode(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81358640)
Location: fs/libfs.c:1220
Inline: False
Direct callers:
  - kernel/resource.c:iomem_init_inode
  - mm/zsmalloc.c:zs_create_pool
  - fs/anon_inodes.c:anon_inode_init
  - fs/anon_inodes.c:__anon_inode_getfile
  - fs/aio.c:aio_setup_ring
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/dma-buf/dma-buf.c:dma_buf_export
```
**Symbols:**

```
ffffffff81358640-ffffffff813586f4: alloc_anon_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct inode *alloc_anon_inode(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff813a6c80)
Location: fs/libfs.c:1204
Inline: False
Direct callers:
  - kernel/resource.c:iomem_init_inode
  - mm/zsmalloc.c:zs_create_pool
  - fs/anon_inodes.c:anon_inode_init
  - fs/anon_inodes.c:__anon_inode_getfile
  - fs/aio.c:aio_setup_ring
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/dma-buf/dma-buf.c:dma_buf_export
```
**Symbols:**

```
ffffffff813a6c80-ffffffff813a6d37: alloc_anon_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct inode *alloc_anon_inode(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff8142b940)
Location: fs/libfs.c:1220
Inline: False
Direct callers:
  - kernel/resource.c:iomem_init_inode
  - mm/zsmalloc.c:zs_create_pool
  - fs/anon_inodes.c:anon_inode_init
  - fs/anon_inodes.c:__anon_inode_getfile
  - fs/aio.c:aio_setup_ring
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/dma-buf/dma-buf.c:dma_buf_export
```
**Symbols:**

```
ffffffff8142b940-ffffffff8142b9e9: alloc_anon_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct inode *alloc_anon_inode(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff814b8a30)
Location: fs/libfs.c:1237
Inline: False
Direct callers:
  - kernel/resource.c:iomem_init_inode
  - fs/anon_inodes.c:anon_inode_init
  - fs/anon_inodes.c:__anon_inode_getfile
  - fs/aio.c:aio_setup_ring
  - drivers/dma-buf/dma-buf.c:dma_buf_export
```
**Symbols:**

```
ffffffff814b8a30-ffffffff814b8ad9: alloc_anon_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct inode *alloc_anon_inode(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff814edc40)
Location: fs/libfs.c:1232
Inline: False
Direct callers:
  - kernel/resource.c:iomem_init_inode
  - fs/anon_inodes.c:anon_inode_init
  - fs/anon_inodes.c:__anon_inode_getfile
  - fs/aio.c:aio_setup_ring
  - drivers/dma-buf/dma-buf.c:dma_buf_export
```
**Symbols:**

```
ffffffff814edc40-ffffffff814edce6: alloc_anon_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct inode *alloc_anon_inode(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff815233c0)
Location: fs/libfs.c:1543
Inline: False
Direct callers:
  - kernel/resource.c:iomem_init_inode
  - fs/anon_inodes.c:anon_inode_init
  - fs/anon_inodes.c:__anon_inode_getfile
  - fs/aio.c:aio_setup_ring
  - drivers/dma-buf/dma-buf.c:dma_buf_export
  - drivers/gpu/drm/drm_drv.c:drm_dev_init
```
**Symbols:**

```
ffffffff815233c0-ffffffff8152345b: alloc_anon_inode (STB_GLOBAL)
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
struct inode *alloc_anon_inode(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffff8000103c0750)
Location: fs/libfs.c:1182
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_create_pool
  - fs/anon_inodes.c:anon_inode_init
  - fs/aio.c:aio_setup_ring
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/dma-buf/dma-buf.c:dma_buf_export
```
**Symbols:**

```
ffff8000103c0750-ffff8000103c0804: alloc_anon_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct inode *alloc_anon_inode(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (c059dad4)
Location: fs/libfs.c:1182
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_create_pool
  - fs/anon_inodes.c:anon_inode_init
  - fs/aio.c:aio_setup_ring
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/dma-buf/dma-buf.c:dma_buf_export
```
**Symbols:**

```
c059dad4-c059dbc4: alloc_anon_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct inode *alloc_anon_inode(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (c0000000004bfd80)
Location: fs/libfs.c:1182
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_create_pool
  - fs/anon_inodes.c:anon_inode_init
  - fs/aio.c:aio_setup_ring
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/dma-buf/dma-buf.c:dma_buf_export
```
**Symbols:**

```
c0000000004bfd80-c0000000004bfe5c: alloc_anon_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct inode *alloc_anon_inode(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffe000280e72)
Location: fs/libfs.c:1182
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_create_pool
  - fs/anon_inodes.c:anon_inode_init
  - fs/aio.c:aio_setup_ring
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/dma-buf/dma-buf.c:dma_buf_export
```
**Symbols:**

```
ffffffe000280e72-ffffffe000280f04: alloc_anon_inode (STB_GLOBAL)
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
struct inode *alloc_anon_inode(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff813046d0)
Location: fs/libfs.c:1182
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_create_pool
  - fs/anon_inodes.c:anon_inode_init
  - fs/aio.c:aio_setup_ring
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/dma-buf/dma-buf.c:dma_buf_export
```
**Symbols:**

```
ffffffff813046d0-ffffffff81304782: alloc_anon_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct inode *alloc_anon_inode(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff812f52f0)
Location: fs/libfs.c:1182
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_create_pool
  - fs/anon_inodes.c:anon_inode_init
  - fs/aio.c:aio_setup_ring
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/dma-buf/dma-buf.c:dma_buf_export
```
**Symbols:**

```
ffffffff812f52f0-ffffffff812f53a2: alloc_anon_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct inode *alloc_anon_inode(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff813024c0)
Location: fs/libfs.c:1182
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_create_pool
  - fs/anon_inodes.c:anon_inode_init
  - fs/aio.c:aio_setup_ring
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/dma-buf/dma-buf.c:dma_buf_export
```
**Symbols:**

```
ffffffff813024c0-ffffffff81302572: alloc_anon_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct inode *alloc_anon_inode(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81313ae0)
Location: fs/libfs.c:1182
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_create_pool
  - fs/anon_inodes.c:anon_inode_init
  - fs/aio.c:aio_setup_ring
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/dma-buf/dma-buf.c:dma_buf_export
```
**Symbols:**

```
ffffffff81313ae0-ffffffff81313b92: alloc_anon_inode (STB_GLOBAL)
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
