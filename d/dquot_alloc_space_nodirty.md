# Function: <code>dquot_alloc_space_nodirty</code>

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
In fs/ext4/mballoc.c (ffffffff812d414e)
Location: include/linux/quotaops.h:279
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/xattr.c (ffffffff812dda94)
Location: include/linux/quotaops.h:279
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
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
In fs/ext4/mballoc.c (ffffffff813038a1)
Location: include/linux/quotaops.h:282
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/xattr.c (ffffffff8130d446)
Location: include/linux/quotaops.h:282
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
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
In fs/ext4/mballoc.c (ffffffff81319861)
Location: include/linux/quotaops.h:282
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/xattr.c (ffffffff8132333b)
Location: include/linux/quotaops.h:282
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
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
In fs/ext4/mballoc.c (ffffffff81310bde)
Location: include/linux/quotaops.h:287
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/xattr.c (ffffffff8133c7a7)
Location: include/linux/quotaops.h:287
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
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
In fs/ext4/mballoc.c (ffffffff81335a7f)
Location: include/linux/quotaops.h:283
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/xattr.c (ffffffff81360d27)
Location: include/linux/quotaops.h:283
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
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
In fs/ext4/mballoc.c (ffffffff81363c77)
Location: include/linux/quotaops.h:286
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/xattr.c (ffffffff8138f67c)
Location: include/linux/quotaops.h:286
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
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
In fs/ext4/ioctl.c (ffffffff813751bf)
Location: include/linux/quotaops.h:286
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/mballoc.c (ffffffff8137bf19)
Location: include/linux/quotaops.h:286
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/xattr.c (ffffffff813a8003)
Location: include/linux/quotaops.h:286
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
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
In fs/ext4/ioctl.c (ffffffff8139d562)
Location: include/linux/quotaops.h:286
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mballoc.c (ffffffff813a6069)
Location: include/linux/quotaops.h:286
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/xattr.c (ffffffff813d24ee)
Location: include/linux/quotaops.h:286
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
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
In fs/ext4/ioctl.c (ffffffff813b5fd2)
Location: include/linux/quotaops.h:296
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mballoc.c (ffffffff813beed9)
Location: include/linux/quotaops.h:296
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/xattr.c (ffffffff813ebbce)
Location: include/linux/quotaops.h:296
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
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
In fs/ext4/ioctl.c (ffffffff81401a10)
Location: include/linux/quotaops.h:298
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mballoc.c (ffffffff8140afa9)
Location: include/linux/quotaops.h:298
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/xattr.c (ffffffff81438dbd)
Location: include/linux/quotaops.h:298
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
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
In fs/ext4/ioctl.c (ffffffff81414415)
Location: include/linux/quotaops.h:295
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mballoc.c (ffffffff8141e3f9)
Location: include/linux/quotaops.h:295
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/xattr.c (ffffffff814518e6)
Location: include/linux/quotaops.h:295
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
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
In fs/ext4/ioctl.c (ffffffff8141a688)
Location: include/linux/quotaops.h:295
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mballoc.c (ffffffff81424d78)
Location: include/linux/quotaops.h:295
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/xattr.c (ffffffff81457016)
Location: include/linux/quotaops.h:295
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
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
In fs/ext4/ioctl.c (ffffffff8146d874)
Location: include/linux/quotaops.h:295
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mballoc.c (ffffffff81478a9a)
Location: include/linux/quotaops.h:295
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/xattr.c (ffffffff814ab0b0)
Location: include/linux/quotaops.h:295
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
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
In fs/ext4/ioctl.c (ffffffff814ee110)
Location: include/linux/quotaops.h:295
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mballoc.c (ffffffff814fb282)
Location: include/linux/quotaops.h:295
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/xattr.c (ffffffff81532d89)
Location: include/linux/quotaops.h:295
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
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
In fs/ext4/ioctl.c (ffffffff81587ff2)
Location: include/linux/quotaops.h:298
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mballoc.c (ffffffff81595a22)
Location: include/linux/quotaops.h:298
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/xattr.c (ffffffff815d1259)
Location: include/linux/quotaops.h:298
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
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
In fs/ext4/ioctl.c (ffffffff815be876)
Location: include/linux/quotaops.h:298
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mballoc.c (ffffffff815cc418)
Location: include/linux/quotaops.h:298
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/xattr.c (ffffffff81608df9)
Location: include/linux/quotaops.h:298
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
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
In mm/shmem.c (ffffffff813e834e)
Location: include/linux/quotaops.h:297
Inline: True
Inline callers:
  - mm/shmem.c:shmem_inode_acct_blocks
  - mm/shmem.c:shmem_inode_acct_blocks
```
```
In fs/ext4/ioctl.c (ffffffff815f761f)
Location: include/linux/quotaops.h:297
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mballoc.c (ffffffff81604ea8)
Location: include/linux/quotaops.h:297
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/xattr.c (ffffffff81641b39)
Location: include/linux/quotaops.h:297
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
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
In fs/ext4/ioctl.c (ffff80001048a938)
Location: include/linux/quotaops.h:296
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mballoc.c (ffff800010495bc8)
Location: include/linux/quotaops.h:296
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/xattr.c (ffff8000104c4a90)
Location: include/linux/quotaops.h:296
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
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
In fs/ext4/ioctl.c (c064ccd4)
Location: include/linux/quotaops.h:296
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mballoc.c (c0657788)
Location: include/linux/quotaops.h:296
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/xattr.c (c0688a78)
Location: include/linux/quotaops.h:296
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
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
In fs/ext4/ioctl.c (c0000000005b1dc4)
Location: include/linux/quotaops.h:296
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mballoc.c (c0000000005bf89c)
Location: include/linux/quotaops.h:296
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/xattr.c (c0000000005fc38c)
Location: include/linux/quotaops.h:296
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
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
In fs/ext4/ioctl.c (ffffffe000311cf4)
Location: include/linux/quotaops.h:296
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mballoc.c (ffffffe00031a7b0)
Location: include/linux/quotaops.h:296
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/xattr.c (ffffffe00033f390)
Location: include/linux/quotaops.h:296
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
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
In fs/ext4/ioctl.c (ffffffff813ae5b2)
Location: include/linux/quotaops.h:296
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mballoc.c (ffffffff813b74b9)
Location: include/linux/quotaops.h:296
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/xattr.c (ffffffff813e41ae)
Location: include/linux/quotaops.h:296
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
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
In fs/ext4/ioctl.c (ffffffff8139f042)
Location: include/linux/quotaops.h:296
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mballoc.c (ffffffff813a7f49)
Location: include/linux/quotaops.h:296
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/xattr.c (ffffffff813d4c2e)
Location: include/linux/quotaops.h:296
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
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
In fs/ext4/ioctl.c (ffffffff813abe12)
Location: include/linux/quotaops.h:296
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mballoc.c (ffffffff813b4d19)
Location: include/linux/quotaops.h:296
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/xattr.c (ffffffff813e152e)
Location: include/linux/quotaops.h:296
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
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
In fs/ext4/ioctl.c (ffffffff813c07b2)
Location: include/linux/quotaops.h:296
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/mballoc.c (ffffffff813c993b)
Location: include/linux/quotaops.h:296
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/xattr.c (ffffffff813f6944)
Location: include/linux/quotaops.h:296
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_set_entry
```
</details>
</li>
</ul>

## Differences
