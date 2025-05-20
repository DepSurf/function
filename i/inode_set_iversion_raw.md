# Function: <code>inode_set_iversion_raw</code>

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
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81354ad0)
Location: include/linux/iversion.h:93
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffff8135c43d)
Location: include/linux/iversion.h:93
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff8137dfc2)
Location: include/linux/iversion.h:93
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/ext4/xattr.c (ffffffff8138dfcd)
Location: include/linux/iversion.h:93
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/fat/inode.c (ffffffff813aed32)
Location: include/linux/iversion.h:93
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
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
In fs/ext4/inode.c (ffffffff8136ce22)
Location: include/linux/iversion.h:93
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffff813748aa)
Location: include/linux/iversion.h:93
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff81396867)
Location: include/linux/iversion.h:93
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/ext4/xattr.c (ffffffff813a6568)
Location: include/linux/iversion.h:93
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/fat/inode.c (ffffffff813c7f11)
Location: include/linux/iversion.h:93
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
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
In fs/ext4/inode.c (ffffffff813963cf)
Location: include/linux/iversion.h:93
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffff8139d386)
Location: include/linux/iversion.h:93
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/super.c (ffffffff813c08b8)
Location: include/linux/iversion.h:93
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/ext4/xattr.c (ffffffff813d0dc5)
Location: include/linux/iversion.h:93
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/fat/inode.c (ffffffff813f2afa)
Location: include/linux/iversion.h:93
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
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
In fs/ext4/inode.c (ffffffff813aedd1)
Location: include/linux/iversion.h:93
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffff813b5df6)
Location: include/linux/iversion.h:93
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/super.c (ffffffff813d9c08)
Location: include/linux/iversion.h:93
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/ext4/xattr.c (ffffffff813ea495)
Location: include/linux/iversion.h:93
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/fat/inode.c (ffffffff8140cabb)
Location: include/linux/iversion.h:93
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
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
In fs/ext4/inode.c (ffffffff813fae4f)
Location: include/linux/iversion.h:93
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffff814017f8)
Location: include/linux/iversion.h:93
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/super.c (ffffffff81425f38)
Location: include/linux/iversion.h:93
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/ext4/xattr.c (ffffffff814361a1)
Location: include/linux/iversion.h:93
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_create
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/fat/inode.c (ffffffff8145aa20)
Location: include/linux/iversion.h:93
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
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
In fs/ext4/inode.c (ffffffff8140d4d9)
Location: include/linux/iversion.h:93
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffff814141f3)
Location: include/linux/iversion.h:93
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/super.c (ffffffff8143d6c4)
Location: include/linux/iversion.h:93
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/ext4/xattr.c (ffffffff8144ebe1)
Location: include/linux/iversion.h:93
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_create
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/fat/inode.c (ffffffff81476d70)
Location: include/linux/iversion.h:93
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
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
In fs/ext4/inode.c (ffffffff81413749)
Location: include/linux/iversion.h:93
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffff8141a465)
Location: include/linux/iversion.h:93
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/super.c (ffffffff81443504)
Location: include/linux/iversion.h:93
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/ext4/xattr.c (ffffffff81455a3e)
Location: include/linux/iversion.h:93
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/fat/inode.c (ffffffff8147c7e4)
Location: include/linux/iversion.h:93
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
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
In fs/ext4/inode.c (ffffffff81466a8b)
Location: include/linux/iversion.h:93
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffff8146d658)
Location: include/linux/iversion.h:93
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/super.c (ffffffff814971b4)
Location: include/linux/iversion.h:93
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/ext4/xattr.c (ffffffff814a9a5e)
Location: include/linux/iversion.h:93
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/fat/inode.c (ffffffff814d3ed9)
Location: include/linux/iversion.h:93
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
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
In fs/ext4/inode.c (ffffffff814e662b)
Location: include/linux/iversion.h:93
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffff814edf26)
Location: include/linux/iversion.h:93
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/super.c (ffffffff81521fdb)
Location: include/linux/iversion.h:93
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/ext4/xattr.c (ffffffff81531dc0)
Location: include/linux/iversion.h:93
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/fat/inode.c (ffffffff81561111)
Location: include/linux/iversion.h:93
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
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
In fs/ext4/inode.c (ffffffff8157fdc8)
Location: include/linux/iversion.h:93
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffff81587e03)
Location: include/linux/iversion.h:93
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/super.c (ffffffff815be9f0)
Location: include/linux/iversion.h:93
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/ext4/xattr.c (ffffffff815ce861)
Location: include/linux/iversion.h:93
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_create
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/fat/inode.c (ffffffff81603599)
Location: include/linux/iversion.h:93
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
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
In fs/ext4/inode.c (ffffffff815b726a)
Location: include/linux/iversion.h:111
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffff815be683)
Location: include/linux/iversion.h:111
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/super.c (ffffffff815f57ab)
Location: include/linux/iversion.h:111
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/ext4/xattr.c (ffffffff81606131)
Location: include/linux/iversion.h:111
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_create
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/fat/inode.c (ffffffff8163b4b9)
Location: include/linux/iversion.h:111
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
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
In fs/ext4/inode.c (ffffffff815efffc)
Location: include/linux/iversion.h:111
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffff815f743c)
Location: include/linux/iversion.h:111
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/super.c (ffffffff8162e0bb)
Location: include/linux/iversion.h:111
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/ext4/xattr.c (ffffffff8163ee5c)
Location: include/linux/iversion.h:111
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_create
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/fat/inode.c (ffffffff81674a18)
Location: include/linux/iversion.h:111
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
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
In fs/ext4/inode.c (ffff8000104837c8)
Location: include/linux/iversion.h:93
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (ffff80001048a7d4)
Location: include/linux/iversion.h:93
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/super.c (ffff8000104ad17c)
Location: include/linux/iversion.h:93
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/ext4/xattr.c (ffff8000104c2a2c)
Location: include/linux/iversion.h:93
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/fat/inode.c (ffff8000104ed71c)
Location: include/linux/iversion.h:93
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
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
In fs/ext4/inode.c (c0644c8c)
Location: include/linux/iversion.h:93
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (c064ca54)
Location: include/linux/iversion.h:93
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/super.c (c0675f44)
Location: include/linux/iversion.h:93
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/ext4/xattr.c (c0687660)
Location: include/linux/iversion.h:93
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/fat/inode.c (c06ab474)
Location: include/linux/iversion.h:93
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
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
In fs/ext4/inode.c (c0000000005a883c)
Location: include/linux/iversion.h:93
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (c0000000005b1bd0)
Location: include/linux/iversion.h:93
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/super.c (c0000000005e5dac)
Location: include/linux/iversion.h:93
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/ext4/xattr.c (c0000000005fa9c0)
Location: include/linux/iversion.h:93
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/fat/inode.c (c00000000062c548)
Location: include/linux/iversion.h:93
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
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
In fs/ext4/inode.c (ffffffe00030beb0)
Location: include/linux/iversion.h:93
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffe000311cb2)
Location: include/linux/iversion.h:93
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/super.c (ffffffe0003306e6)
Location: include/linux/iversion.h:93
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/ext4/xattr.c (ffffffe00033e234)
Location: include/linux/iversion.h:93
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/fat/inode.c (ffffffe00035dcca)
Location: include/linux/iversion.h:93
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
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
In fs/ext4/inode.c (ffffffff813a73b1)
Location: include/linux/iversion.h:93
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffff813ae3d6)
Location: include/linux/iversion.h:93
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/super.c (ffffffff813d21e8)
Location: include/linux/iversion.h:93
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/ext4/xattr.c (ffffffff813e2a75)
Location: include/linux/iversion.h:93
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/fat/inode.c (ffffffff8140509b)
Location: include/linux/iversion.h:93
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
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
In fs/ext4/inode.c (ffffffff81397e41)
Location: include/linux/iversion.h:93
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffff8139ee66)
Location: include/linux/iversion.h:93
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/super.c (ffffffff813c2c68)
Location: include/linux/iversion.h:93
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/ext4/xattr.c (ffffffff813d34f5)
Location: include/linux/iversion.h:93
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/fat/inode.c (ffffffff813f5b1b)
Location: include/linux/iversion.h:93
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
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
In fs/ext4/inode.c (ffffffff813a4c11)
Location: include/linux/iversion.h:93
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffff813abc36)
Location: include/linux/iversion.h:93
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/super.c (ffffffff813cf678)
Location: include/linux/iversion.h:93
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/ext4/xattr.c (ffffffff813dfdf5)
Location: include/linux/iversion.h:93
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/fat/inode.c (ffffffff8140241b)
Location: include/linux/iversion.h:93
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
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
In fs/ext4/inode.c (ffffffff813b9326)
Location: include/linux/iversion.h:93
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffff813c05d6)
Location: include/linux/iversion.h:93
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/super.c (ffffffff813e4c78)
Location: include/linux/iversion.h:93
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/ext4/xattr.c (ffffffff813f5215)
Location: include/linux/iversion.h:93
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/fat/inode.c (ffffffff814183eb)
Location: include/linux/iversion.h:93
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
```
</details>
</li>
</ul>

## Differences
