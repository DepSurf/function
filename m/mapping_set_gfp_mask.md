# Function: <code>mapping_set_gfp_mask</code>

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
In fs/inode.c (ffffffff81226bb1)
Location: include/linux/pagemap.h:83
Inline: True
Inline callers:
  - fs/inode.c:inode_init_always
```
```
In fs/block_dev.c (ffffffff81247aad)
Location: include/linux/pagemap.h:83
Inline: True
Inline callers:
  - fs/block_dev.c:bdget
```
```
In fs/ramfs/inode.c (ffffffff812f3279)
Location: include/linux/pagemap.h:83
Inline: True
Inline callers:
  - fs/ramfs/inode.c:ramfs_get_inode
```
```
In drivers/block/loop.c (ffffffff8156f16e)
Location: include/linux/pagemap.h:83
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_clr_fd
  - drivers/block/loop.c:loop_switch
  - drivers/block/loop.c:loop_switch
  - drivers/block/loop.c:lo_ioctl
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
In fs/inode.c (ffffffff8124f10d)
Location: include/linux/pagemap.h:83
Inline: True
Inline callers:
  - fs/inode.c:inode_nohighmem
  - fs/inode.c:inode_init_always
```
```
In fs/block_dev.c (ffffffff8127027d)
Location: include/linux/pagemap.h:83
Inline: True
Inline callers:
  - fs/block_dev.c:bdget
```
```
In fs/ramfs/inode.c (ffffffff813269f9)
Location: include/linux/pagemap.h:83
Inline: True
Inline callers:
  - fs/ramfs/inode.c:ramfs_get_inode
```
```
In drivers/block/loop.c (ffffffff815c58bc)
Location: include/linux/pagemap.h:83
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_clr_fd
  - drivers/block/loop.c:loop_switch
  - drivers/block/loop.c:loop_switch
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
In fs/inode.c (ffffffff8126211d)
Location: include/linux/pagemap.h:94
Inline: True
Inline callers:
  - fs/inode.c:inode_nohighmem
  - fs/inode.c:inode_init_always
```
```
In fs/block_dev.c (ffffffff8128346c)
Location: include/linux/pagemap.h:94
Inline: True
Inline callers:
  - fs/block_dev.c:bdget
```
```
In fs/ramfs/inode.c (ffffffff8133c7a9)
Location: include/linux/pagemap.h:94
Inline: True
Inline callers:
  - fs/ramfs/inode.c:ramfs_get_inode
```
```
In drivers/block/loop.c (ffffffff815f3c51)
Location: include/linux/pagemap.h:94
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_clr_fd
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
In fs/inode.c (ffffffff8126f9cd)
Location: include/linux/pagemap.h:113
Inline: True
Inline callers:
  - fs/inode.c:inode_nohighmem
  - fs/inode.c:inode_init_always
```
```
In fs/block_dev.c (ffffffff81290b3c)
Location: include/linux/pagemap.h:113
Inline: True
Inline callers:
  - fs/block_dev.c:bdget
```
```
In fs/ramfs/inode.c (ffffffff813512db)
Location: include/linux/pagemap.h:113
Inline: True
Inline callers:
  - fs/ramfs/inode.c:ramfs_get_inode
```
```
In drivers/block/loop.c (ffffffff81607452)
Location: include/linux/pagemap.h:113
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_clr_fd
  - drivers/block/loop.c:loop_switch
```
```
In drivers/dax/super.c (ffffffff8163cd4e)
Location: include/linux/pagemap.h:113
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
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
In fs/inode.c (ffffffff812922ed)
Location: include/linux/pagemap.h:116
Inline: True
Inline callers:
  - fs/inode.c:inode_nohighmem
  - fs/inode.c:inode_init_always
```
```
In fs/block_dev.c (ffffffff812b381c)
Location: include/linux/pagemap.h:116
Inline: True
Inline callers:
  - fs/block_dev.c:bdget
```
```
In fs/ramfs/inode.c (ffffffff81375ddb)
Location: include/linux/pagemap.h:116
Inline: True
Inline callers:
  - fs/ramfs/inode.c:ramfs_get_inode
```
```
In drivers/block/loop.c (ffffffff81670d77)
Location: include/linux/pagemap.h:116
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_clr_fd
```
```
In drivers/dax/super.c (ffffffff816a5a1e)
Location: include/linux/pagemap.h:116
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
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
In fs/inode.c (ffffffff812b81ba)
Location: include/linux/pagemap.h:116
Inline: True
Inline callers:
  - fs/inode.c:inode_nohighmem
  - fs/inode.c:inode_init_always
```
```
In fs/block_dev.c (ffffffff812dcbf5)
Location: include/linux/pagemap.h:116
Inline: True
Inline callers:
  - fs/block_dev.c:bdget
```
```
In fs/ramfs/inode.c (ffffffff813a47f9)
Location: include/linux/pagemap.h:116
Inline: True
Inline callers:
  - fs/ramfs/inode.c:ramfs_get_inode
```
```
In drivers/block/loop.c (ffffffff816ac58b)
Location: include/linux/pagemap.h:116
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_clr_fd
```
```
In drivers/dax/super.c (ffffffff816e1e1e)
Location: include/linux/pagemap.h:116
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
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
In fs/inode.c (ffffffff812cd30a)
Location: include/linux/pagemap.h:116
Inline: True
Inline callers:
  - fs/inode.c:inode_nohighmem
  - fs/inode.c:inode_init_always
```
```
In fs/block_dev.c (ffffffff812f28b6)
Location: include/linux/pagemap.h:116
Inline: True
Inline callers:
  - fs/block_dev.c:bdget
```
```
In fs/ramfs/inode.c (ffffffff813bd5f9)
Location: include/linux/pagemap.h:116
Inline: True
Inline callers:
  - fs/ramfs/inode.c:ramfs_get_inode
```
```
In drivers/block/loop.c (ffffffff816ce19d)
Location: include/linux/pagemap.h:116
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:__loop_clr_fd
```
```
In drivers/dax/super.c (ffffffff8170523e)
Location: include/linux/pagemap.h:116
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
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
In fs/inode.c (ffffffff812e9f4a)
Location: include/linux/pagemap.h:116
Inline: True
Inline callers:
  - fs/inode.c:inode_nohighmem
  - fs/inode.c:inode_init_always
```
```
In fs/block_dev.c (ffffffff81314466)
Location: include/linux/pagemap.h:116
Inline: True
Inline callers:
  - fs/block_dev.c:bdget
```
```
In fs/ramfs/inode.c (ffffffff813e7ebb)
Location: include/linux/pagemap.h:116
Inline: True
Inline callers:
  - fs/ramfs/inode.c:ramfs_get_inode
```
```
In drivers/block/loop.c (ffffffff817090dc)
Location: include/linux/pagemap.h:116
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_set_fd
```
```
In drivers/dax/super.c (ffffffff8173f0a7)
Location: include/linux/pagemap.h:116
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
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
In fs/inode.c (ffffffff812fb9da)
Location: include/linux/pagemap.h:116
Inline: True
Inline callers:
  - fs/inode.c:inode_nohighmem
  - fs/inode.c:inode_init_always
```
```
In fs/block_dev.c (ffffffff81326dd6)
Location: include/linux/pagemap.h:116
Inline: True
Inline callers:
  - fs/block_dev.c:bdget
```
```
In fs/ramfs/inode.c (ffffffff8140202b)
Location: include/linux/pagemap.h:116
Inline: True
Inline callers:
  - fs/ramfs/inode.c:ramfs_get_inode
```
```
In drivers/block/loop.c (ffffffff8172d3ba)
Location: include/linux/pagemap.h:116
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_set_fd
```
```
In drivers/dax/super.c (ffffffff81763287)
Location: include/linux/pagemap.h:116
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
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
In fs/inode.c (ffffffff813347da)
Location: include/linux/pagemap.h:117
Inline: True
Inline callers:
  - fs/inode.c:inode_nohighmem
  - fs/inode.c:inode_init_always
```
```
In fs/block_dev.c (ffffffff81360f76)
Location: include/linux/pagemap.h:117
Inline: True
Inline callers:
  - fs/block_dev.c:bdget
```
```
In fs/ramfs/inode.c (ffffffff8144fc3b)
Location: include/linux/pagemap.h:117
Inline: True
Inline callers:
  - fs/ramfs/inode.c:ramfs_get_inode
```
```
In drivers/block/loop.c (ffffffff817e7275)
Location: include/linux/pagemap.h:117
Inline: True
Inline callers:
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_change_fd
  - drivers/block/loop.c:loop_change_fd
```
```
In drivers/dax/super.c (ffffffff818230db)
Location: include/linux/pagemap.h:117
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
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
In fs/inode.c (ffffffff8134012a)
Location: include/linux/pagemap.h:119
Inline: True
Inline callers:
  - fs/inode.c:inode_nohighmem
  - fs/inode.c:inode_init_always
```
```
In fs/block_dev.c (ffffffff8136e73b)
Location: include/linux/pagemap.h:119
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_alloc
```
```
In fs/ramfs/inode.c (ffffffff8146c14b)
Location: include/linux/pagemap.h:119
Inline: True
Inline callers:
  - fs/ramfs/inode.c:ramfs_get_inode
```
```
In drivers/block/loop.c (ffffffff817fbebb)
Location: include/linux/pagemap.h:119
Inline: True
Inline callers:
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_change_fd
  - drivers/block/loop.c:loop_change_fd
```
```
In drivers/dax/super.c (ffffffff81831e1b)
Location: include/linux/pagemap.h:119
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
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
In fs/inode.c (ffffffff8134664a)
Location: include/linux/pagemap.h:124
Inline: True
Inline callers:
  - fs/inode.c:inode_nohighmem
  - fs/inode.c:inode_init_always
```
```
In fs/block_dev.c (ffffffff8137504b)
Location: include/linux/pagemap.h:124
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_alloc
```
```
In fs/ramfs/inode.c (ffffffff814717d2)
Location: include/linux/pagemap.h:124
Inline: True
Inline callers:
  - fs/ramfs/inode.c:ramfs_get_inode
```
```
In drivers/block/loop.c (ffffffff817e0f7e)
Location: include/linux/pagemap.h:124
Inline: True
Inline callers:
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_change_fd
  - drivers/block/loop.c:loop_change_fd
```
```
In drivers/dax/super.c (ffffffff8181504b)
Location: include/linux/pagemap.h:124
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
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
In mm/secretmem.c (ffffffff813664e9)
Location: include/linux/pagemap.h:124
Inline: True
```
```
In fs/inode.c (ffffffff8139406a)
Location: include/linux/pagemap.h:124
Inline: True
Inline callers:
  - fs/inode.c:inode_nohighmem
  - fs/inode.c:inode_init_always
```
```
In fs/ramfs/inode.c (ffffffff814c8265)
Location: include/linux/pagemap.h:124
Inline: True
Inline callers:
  - fs/ramfs/inode.c:ramfs_get_inode
```
```
In block/bdev.c (ffffffff815c4a28)
Location: include/linux/pagemap.h:124
Inline: True
Inline callers:
  - block/bdev.c:bdev_alloc
```
```
In drivers/block/loop.c (ffffffff818705c7)
Location: include/linux/pagemap.h:124
Inline: True
Inline callers:
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_change_fd
  - drivers/block/loop.c:loop_change_fd
```
```
In drivers/dax/super.c (ffffffff8189f7bb)
Location: include/linux/pagemap.h:124
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
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
In mm/secretmem.c (ffffffff813e3597)
Location: include/linux/pagemap.h:288
Inline: True
```
```
In fs/inode.c (ffffffff81415c5a)
Location: include/linux/pagemap.h:288
Inline: True
Inline callers:
  - fs/inode.c:inode_nohighmem
  - fs/inode.c:inode_init_always
```
```
In fs/ramfs/inode.c (ffffffff81553793)
Location: include/linux/pagemap.h:288
Inline: True
Inline callers:
  - fs/ramfs/inode.c:ramfs_get_inode
```
```
In block/bdev.c (ffffffff8166f471)
Location: include/linux/pagemap.h:288
Inline: True
Inline callers:
  - block/bdev.c:bdev_alloc
```
```
In drivers/block/loop.c (ffffffff819b59a5)
Location: include/linux/pagemap.h:288
Inline: True
Inline callers:
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_change_fd
  - drivers/block/loop.c:loop_change_fd
```
```
In drivers/dax/super.c (ffffffff819e911b)
Location: include/linux/pagemap.h:288
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
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
In mm/secretmem.c (ffffffff8146af5e)
Location: include/linux/pagemap.h:288
Inline: True
```
```
In fs/inode.c (ffffffff814a108a)
Location: include/linux/pagemap.h:288
Inline: True
Inline callers:
  - fs/inode.c:inode_nohighmem
  - fs/inode.c:inode_init_always
```
```
In fs/ramfs/inode.c (ffffffff815f4f83)
Location: include/linux/pagemap.h:288
Inline: True
Inline callers:
  - fs/ramfs/inode.c:ramfs_get_inode
```
```
In block/bdev.c (ffffffff8172a801)
Location: include/linux/pagemap.h:288
Inline: True
Inline callers:
  - block/bdev.c:bdev_alloc
```
```
In drivers/block/loop.c (ffffffff81b2aa75)
Location: include/linux/pagemap.h:288
Inline: True
Inline callers:
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_change_fd
  - drivers/block/loop.c:loop_change_fd
```
```
In drivers/dax/super.c (ffffffff81b6574b)
Location: include/linux/pagemap.h:288
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
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
In mm/secretmem.c (ffffffff8149fe1e)
Location: include/linux/pagemap.h:292
Inline: True
```
```
In fs/inode.c (ffffffff814d639a)
Location: include/linux/pagemap.h:292
Inline: True
Inline callers:
  - fs/inode.c:inode_nohighmem
  - fs/inode.c:inode_init_always
```
```
In fs/squashfs/super.c (ffffffff816297e2)
Location: include/linux/pagemap.h:292
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_fill_super
```
```
In fs/ramfs/inode.c (ffffffff8162d000)
Location: include/linux/pagemap.h:292
Inline: True
Inline callers:
  - fs/ramfs/inode.c:ramfs_get_inode
```
```
In block/bdev.c (ffffffff81766998)
Location: include/linux/pagemap.h:292
Inline: True
Inline callers:
  - block/bdev.c:bdev_alloc
```
```
In drivers/block/loop.c (ffffffff81b7ad5b)
Location: include/linux/pagemap.h:292
Inline: True
Inline callers:
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_change_fd
  - drivers/block/loop.c:loop_change_fd
```
```
In drivers/dax/super.c (ffffffff81bb8d6b)
Location: include/linux/pagemap.h:292
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
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
In mm/secretmem.c (ffffffff814cf56e)
Location: include/linux/pagemap.h:342
Inline: True
```
```
In fs/inode.c (ffffffff8150876a)
Location: include/linux/pagemap.h:342
Inline: True
Inline callers:
  - fs/inode.c:inode_nohighmem
  - fs/inode.c:inode_init_always
```
```
In fs/squashfs/super.c (ffffffff81662a31)
Location: include/linux/pagemap.h:342
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_fill_super
```
```
In fs/ramfs/inode.c (ffffffff8166651c)
Location: include/linux/pagemap.h:342
Inline: True
Inline callers:
  - fs/ramfs/inode.c:ramfs_get_inode
```
```
In block/bdev.c (ffffffff817a85b8)
Location: include/linux/pagemap.h:342
Inline: True
Inline callers:
  - block/bdev.c:bdev_alloc
```
```
In drivers/block/loop.c (ffffffff81bceb28)
Location: include/linux/pagemap.h:342
Inline: True
Inline callers:
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_change_fd
  - drivers/block/loop.c:loop_change_fd
```
```
In drivers/dax/super.c (ffffffff81c0d3cb)
Location: include/linux/pagemap.h:342
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
```
```
In drivers/gpu/drm/drm_gem_shmem_helper.c (ffffffff81cbe117)
Location: include/linux/pagemap.h:342
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_gem_shmem_helper.c:__drm_gem_shmem_create
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
In fs/inode.c (ffff8000103ab828)
Location: include/linux/pagemap.h:116
Inline: True
Inline callers:
  - fs/inode.c:inode_nohighmem
  - fs/inode.c:inode_init_always
```
```
In fs/block_dev.c (ffff8000103e1cd4)
Location: include/linux/pagemap.h:116
Inline: True
Inline callers:
  - fs/block_dev.c:bdget
```
```
In fs/ramfs/inode.c (ffff8000104e039c)
Location: include/linux/pagemap.h:116
Inline: True
Inline callers:
  - fs/ramfs/inode.c:ramfs_get_inode
```
```
In drivers/block/loop.c (ffff800010924c8c)
Location: include/linux/pagemap.h:116
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_set_fd
```
```
In drivers/dax/super.c (ffff800010963ac4)
Location: include/linux/pagemap.h:116
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
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
In fs/inode.c (c058c2b0)
Location: include/linux/pagemap.h:116
Inline: True
Inline callers:
  - fs/inode.c:inode_nohighmem
  - fs/inode.c:inode_init_always
```
```
In fs/block_dev.c (c05b7e0c)
Location: include/linux/pagemap.h:116
Inline: True
Inline callers:
  - fs/block_dev.c:bdget
```
```
In fs/ramfs/inode.c (c06a1c30)
Location: include/linux/pagemap.h:116
Inline: True
Inline callers:
  - fs/ramfs/inode.c:ramfs_get_inode
```
```
In drivers/block/loop.c (c0a08360)
Location: include/linux/pagemap.h:116
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_set_fd
```
```
In drivers/dax/super.c (c0a39cd4)
Location: include/linux/pagemap.h:116
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
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
In fs/inode.c (c0000000004a61ac)
Location: include/linux/pagemap.h:116
Inline: True
Inline callers:
  - fs/inode.c:inode_nohighmem
  - fs/inode.c:inode_init_always
```
```
In fs/block_dev.c (c0000000004e4ba4)
Location: include/linux/pagemap.h:116
Inline: True
Inline callers:
  - fs/block_dev.c:bdget
```
```
In fs/ramfs/inode.c (c00000000061cb5c)
Location: include/linux/pagemap.h:116
Inline: True
Inline callers:
  - fs/ramfs/inode.c:ramfs_get_inode
```
```
In drivers/block/loop.c (c0000000009c8db0)
Location: include/linux/pagemap.h:116
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_set_fd
```
```
In drivers/dax/super.c (c000000000a18f38)
Location: include/linux/pagemap.h:116
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
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
In fs/inode.c (ffffffe000270a3a)
Location: include/linux/pagemap.h:116
Inline: True
Inline callers:
  - fs/inode.c:inode_nohighmem
  - fs/inode.c:inode_init_always
```
```
In fs/block_dev.c (ffffffe00029819c)
Location: include/linux/pagemap.h:116
Inline: True
Inline callers:
  - fs/block_dev.c:bdget
```
```
In fs/ramfs/inode.c (ffffffe00035462a)
Location: include/linux/pagemap.h:116
Inline: True
Inline callers:
  - fs/ramfs/inode.c:ramfs_get_inode
```
```
In drivers/block/loop.c (ffffffe0005a1d40)
Location: include/linux/pagemap.h:116
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_set_fd
```
```
In drivers/dax/super.c (ffffffe0005d05f8)
Location: include/linux/pagemap.h:116
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
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
In fs/inode.c (ffffffff812f3fba)
Location: include/linux/pagemap.h:116
Inline: True
Inline callers:
  - fs/inode.c:inode_nohighmem
  - fs/inode.c:inode_init_always
```
```
In fs/block_dev.c (ffffffff8131f3b6)
Location: include/linux/pagemap.h:116
Inline: True
Inline callers:
  - fs/block_dev.c:bdget
```
```
In fs/ramfs/inode.c (ffffffff813fa60b)
Location: include/linux/pagemap.h:116
Inline: True
Inline callers:
  - fs/ramfs/inode.c:ramfs_get_inode
```
```
In drivers/block/loop.c (ffffffff816f319a)
Location: include/linux/pagemap.h:116
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_set_fd
```
```
In drivers/dax/super.c (ffffffff81717977)
Location: include/linux/pagemap.h:116
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
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
In fs/inode.c (ffffffff812e4bea)
Location: include/linux/pagemap.h:116
Inline: True
Inline callers:
  - fs/inode.c:inode_nohighmem
  - fs/inode.c:inode_init_always
```
```
In fs/block_dev.c (ffffffff8130ff56)
Location: include/linux/pagemap.h:116
Inline: True
Inline callers:
  - fs/block_dev.c:bdget
```
```
In fs/ramfs/inode.c (ffffffff813eb08b)
Location: include/linux/pagemap.h:116
Inline: True
Inline callers:
  - fs/ramfs/inode.c:ramfs_get_inode
```
```
In drivers/block/loop.c (ffffffff816cd29a)
Location: include/linux/pagemap.h:116
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_set_fd
```
```
In drivers/dax/super.c (ffffffff816efea7)
Location: include/linux/pagemap.h:116
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
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
In fs/inode.c (ffffffff812f1dca)
Location: include/linux/pagemap.h:116
Inline: True
Inline callers:
  - fs/inode.c:inode_nohighmem
  - fs/inode.c:inode_init_always
```
```
In fs/block_dev.c (ffffffff8131ce86)
Location: include/linux/pagemap.h:116
Inline: True
Inline callers:
  - fs/block_dev.c:bdget
```
```
In fs/ramfs/inode.c (ffffffff813f798b)
Location: include/linux/pagemap.h:116
Inline: True
Inline callers:
  - fs/ramfs/inode.c:ramfs_get_inode
```
```
In drivers/block/loop.c (ffffffff8172087a)
Location: include/linux/pagemap.h:116
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_set_fd
```
```
In drivers/dax/super.c (ffffffff81756747)
Location: include/linux/pagemap.h:116
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
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
In fs/inode.c (ffffffff8130339a)
Location: include/linux/pagemap.h:116
Inline: True
Inline callers:
  - fs/inode.c:inode_nohighmem
  - fs/inode.c:inode_init_always
```
```
In fs/block_dev.c (ffffffff8132d266)
Location: include/linux/pagemap.h:116
Inline: True
Inline callers:
  - fs/block_dev.c:bdget
```
```
In fs/ramfs/inode.c (ffffffff8140d61b)
Location: include/linux/pagemap.h:116
Inline: True
Inline callers:
  - fs/ramfs/inode.c:ramfs_get_inode
```
```
In drivers/block/loop.c (ffffffff8173bc3a)
Location: include/linux/pagemap.h:116
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_set_fd
```
```
In drivers/dax/super.c (ffffffff8177199a)
Location: include/linux/pagemap.h:116
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
```
</details>
</li>
</ul>

## Differences
