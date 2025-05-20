# Function: <code>find_get_page_flags</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81242d26)
Location: include/linux/pagemap.h:279
Inline: True
Inline callers:
  - fs/buffer.c:__find_get_block_slow
```
```
In fs/ext4/mballoc.c (ffffffff812cf85c)
Location: include/linux/pagemap.h:279
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_load_buddy
  - fs/ext4/mballoc.c:ext4_mb_load_buddy
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8126c3ab)
Location: include/linux/pagemap.h:251
Inline: True
Inline callers:
  - fs/buffer.c:__find_get_block_slow
```
```
In fs/ext4/mballoc.c (ffffffff812ff28e)
Location: include/linux/pagemap.h:251
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8127fb1b)
Location: include/linux/pagemap.h:261
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff8131530e)
Location: include/linux/pagemap.h:261
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8128ceca)
Location: include/linux/pagemap.h:278
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff8130c768)
Location: include/linux/pagemap.h:278
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812afb6d)
Location: include/linux/pagemap.h:275
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff81331340)
Location: include/linux/pagemap.h:275
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812d7e22)
Location: include/linux/pagemap.h:275
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff8135f90e)
Location: include/linux/pagemap.h:275
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812ece62)
Location: include/linux/pagemap.h:275
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff81377db4)
Location: include/linux/pagemap.h:275
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
```
```
In fs/fuse/readdir.c (ffffffff813ea296)
Location: include/linux/pagemap.h:275
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8130e60c)
Location: include/linux/pagemap.h:263
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff813a123d)
Location: include/linux/pagemap.h:263
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
```
```
In fs/fuse/readdir.c (ffffffff814169d2)
Location: include/linux/pagemap.h:263
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8132162c)
Location: include/linux/pagemap.h:263
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff813ba0c5)
Location: include/linux/pagemap.h:263
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
```
```
In fs/fuse/readdir.c (ffffffff814308f2)
Location: include/linux/pagemap.h:263
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8135b72e)
Location: include/linux/pagemap.h:301
Inline: True
Inline callers:
  - fs/buffer.c:__find_get_block_slow
```
```
In fs/verity/enable.c (ffffffff81395bf5)
Location: include/linux/pagemap.h:301
Inline: True
Inline callers:
  - fs/verity/enable.c:read_file_data_page
```
```
In fs/ext4/mballoc.c (ffffffff81405cc6)
Location: include/linux/pagemap.h:301
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
```
```
In fs/ext4/verity.c (ffffffff8143bc89)
Location: include/linux/pagemap.h:301
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
```
```
In fs/fuse/readdir.c (ffffffff814804b7)
Location: include/linux/pagemap.h:301
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81369cfe)
Location: include/linux/pagemap.h:338
Inline: True
Inline callers:
  - fs/buffer.c:__find_get_block_slow
```
```
In fs/verity/enable.c (ffffffff813a790d)
Location: include/linux/pagemap.h:338
Inline: True
Inline callers:
  - fs/verity/enable.c:read_file_data_page
```
```
In fs/ext4/mballoc.c (ffffffff81418f61)
Location: include/linux/pagemap.h:338
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
```
```
In fs/ext4/verity.c (ffffffff81457fe4)
Location: include/linux/pagemap.h:338
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
```
```
In fs/fuse/readdir.c (ffffffff8149bb9a)
Location: include/linux/pagemap.h:338
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81370a2e)
Location: include/linux/pagemap.h:354
Inline: True
Inline callers:
  - fs/buffer.c:__find_get_block_slow
```
```
In fs/verity/enable.c (ffffffff813ae95f)
Location: include/linux/pagemap.h:354
Inline: True
Inline callers:
  - fs/verity/enable.c:read_file_data_page
```
```
In fs/ext4/mballoc.c (ffffffff8141f811)
Location: include/linux/pagemap.h:354
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
```
```
In fs/ext4/verity.c (ffffffff8145d99c)
Location: include/linux/pagemap.h:354
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
```
```
In fs/fuse/readdir.c (ffffffff814a0cba)
Location: include/linux/pagemap.h:354
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff813bf70c)
Location: include/linux/pagemap.h:354
Inline: True
Inline callers:
  - fs/buffer.c:__find_get_block_slow
```
```
In fs/verity/enable.c (ffffffff813fe4ff)
Location: include/linux/pagemap.h:354
Inline: True
Inline callers:
  - fs/verity/enable.c:read_file_data_page
```
```
In fs/ext4/mballoc.c (ffffffff81472f13)
Location: include/linux/pagemap.h:354
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
```
```
In fs/ext4/verity.c (ffffffff814b2e5c)
Location: include/linux/pagemap.h:354
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
```
```
In fs/fuse/readdir.c (ffffffff814f8bab)
Location: include/linux/pagemap.h:354
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
```
```
In drivers/dma-buf/udmabuf.c (ffffffff818ab650)
Location: include/linux/pagemap.h:354
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81444aad)
Location: include/linux/pagemap.h:568
Inline: True
Inline callers:
  - fs/buffer.c:__find_get_block_slow
```
```
In fs/ext4/mballoc.c (ffffffff814f413c)
Location: include/linux/pagemap.h:568
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
```
```
In fs/ext4/verity.c (ffffffff8153c5bc)
Location: include/linux/pagemap.h:568
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
```
```
In fs/fuse/readdir.c (ffffffff815891b0)
Location: include/linux/pagemap.h:568
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
```
```
In drivers/dma-buf/udmabuf.c (ffffffff819f5da3)
Location: include/linux/pagemap.h:568
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff814d3ebd)
Location: include/linux/pagemap.h:565
Inline: True
Inline callers:
  - fs/buffer.c:__find_get_block_slow
```
```
In fs/ext4/mballoc.c (ffffffff8158e660)
Location: include/linux/pagemap.h:565
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
```
```
In fs/ext4/verity.c (ffffffff815dac7c)
Location: include/linux/pagemap.h:565
Inline: True
Inline callers:
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
```
```
In fs/fuse/readdir.c (ffffffff8162f6af)
Location: include/linux/pagemap.h:565
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
```
```
In drivers/dma-buf/udmabuf.c (ffffffff81b7336a)
Location: include/linux/pagemap.h:565
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff815c504d)
Location: include/linux/pagemap.h:592
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
```
```
In fs/fuse/readdir.c (ffffffff81667922)
Location: include/linux/pagemap.h:592
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff815fd2cd)
Location: include/linux/pagemap.h:710
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
```
```
In fs/fuse/readdir.c (ffffffff816a1c67)
Location: include/linux/pagemap.h:710
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffff8000103d9f20)
Location: include/linux/pagemap.h:263
Inline: True
```
```
In fs/ext4/mballoc.c (ffff8000104908e0)
Location: include/linux/pagemap.h:263
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
```
```
In fs/fuse/readdir.c (ffff8000105153bc)
Location: include/linux/pagemap.h:263
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c05b343c)
Location: include/linux/pagemap.h:263
Inline: True
```
```
In fs/ext4/mballoc.c (c0651a4c)
Location: include/linux/pagemap.h:263
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
```
```
In fs/fuse/readdir.c (c06d0140)
Location: include/linux/pagemap.h:263
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c0000000004ded50)
Location: include/linux/pagemap.h:263
Inline: True
```
```
In fs/ext4/mballoc.c (c0000000005b8074)
Location: include/linux/pagemap.h:263
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
```
```
In fs/fuse/readdir.c (c00000000065dc10)
Location: include/linux/pagemap.h:263
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffe000292c46)
Location: include/linux/pagemap.h:263
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffe00031582e)
Location: include/linux/pagemap.h:263
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
```
```
In fs/fuse/readdir.c (ffffffe00037ed58)
Location: include/linux/pagemap.h:263
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81319c0c)
Location: include/linux/pagemap.h:263
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff813b26a5)
Location: include/linux/pagemap.h:263
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
```
```
In fs/fuse/readdir.c (ffffffff81428ed2)
Location: include/linux/pagemap.h:263
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8130a7bb)
Location: include/linux/pagemap.h:263
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff813a3135)
Location: include/linux/pagemap.h:263
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
```
```
In fs/fuse/readdir.c (ffffffff81419952)
Location: include/linux/pagemap.h:263
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff813176dc)
Location: include/linux/pagemap.h:263
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff813aff05)
Location: include/linux/pagemap.h:263
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
```
```
In fs/fuse/readdir.c (ffffffff81425072)
Location: include/linux/pagemap.h:263
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff813292eb)
Location: include/linux/pagemap.h:263
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff813c495f)
Location: include/linux/pagemap.h:263
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
```
```
In fs/fuse/readdir.c (ffffffff8143beef)
Location: include/linux/pagemap.h:263
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
```
</details>
</li>
</ul>

## Differences
