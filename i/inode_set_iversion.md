# Function: <code>inode_set_iversion</code>

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
In fs/ext4/ioctl.c (ffffffff8135c43d)
Location: include/linux/iversion.h:128
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff8137dfc2)
Location: include/linux/iversion.h:128
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/fat/inode.c (ffffffff813aed32)
Location: include/linux/iversion.h:128
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
In fs/ext4/ioctl.c (ffffffff813748aa)
Location: include/linux/iversion.h:128
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff81396867)
Location: include/linux/iversion.h:128
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/fat/inode.c (ffffffff813c7f11)
Location: include/linux/iversion.h:128
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
In fs/ext4/ioctl.c (ffffffff8139d386)
Location: include/linux/iversion.h:152
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/super.c (ffffffff813c08b8)
Location: include/linux/iversion.h:152
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/fat/inode.c (ffffffff813f2afa)
Location: include/linux/iversion.h:152
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
In fs/ext4/ioctl.c (ffffffff813b5df6)
Location: include/linux/iversion.h:152
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/super.c (ffffffff813d9c08)
Location: include/linux/iversion.h:152
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/fat/inode.c (ffffffff8140cabb)
Location: include/linux/iversion.h:152
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
In fs/ext4/ioctl.c (ffffffff814017f8)
Location: include/linux/iversion.h:152
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/super.c (ffffffff81425f38)
Location: include/linux/iversion.h:152
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/fat/inode.c (ffffffff8145aa20)
Location: include/linux/iversion.h:152
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
In fs/ext4/ioctl.c (ffffffff814141f3)
Location: include/linux/iversion.h:152
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/super.c (ffffffff8143d6c4)
Location: include/linux/iversion.h:152
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/fat/inode.c (ffffffff81476d70)
Location: include/linux/iversion.h:152
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
In fs/ext4/ioctl.c (ffffffff8141a465)
Location: include/linux/iversion.h:152
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/super.c (ffffffff81443504)
Location: include/linux/iversion.h:152
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/fat/inode.c (ffffffff8147c7e4)
Location: include/linux/iversion.h:152
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
In fs/ext4/ioctl.c (ffffffff8146d658)
Location: include/linux/iversion.h:152
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/super.c (ffffffff814971b4)
Location: include/linux/iversion.h:152
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/fat/inode.c (ffffffff814d3ed9)
Location: include/linux/iversion.h:152
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
In fs/ext4/ioctl.c (ffffffff814edf26)
Location: include/linux/iversion.h:152
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/super.c (ffffffff81521fdb)
Location: include/linux/iversion.h:152
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/fat/inode.c (ffffffff81561111)
Location: include/linux/iversion.h:152
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
In fs/ext4/ioctl.c (ffffffff81587e03)
Location: include/linux/iversion.h:147
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/super.c (ffffffff815be9f0)
Location: include/linux/iversion.h:147
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/fat/inode.c (ffffffff81603599)
Location: include/linux/iversion.h:147
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
In fs/ext4/ioctl.c (ffffffff815be683)
Location: include/linux/iversion.h:165
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/super.c (ffffffff815f57ab)
Location: include/linux/iversion.h:165
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/fat/inode.c (ffffffff8163b4b9)
Location: include/linux/iversion.h:165
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
In fs/ext4/ioctl.c (ffffffff815f743c)
Location: include/linux/iversion.h:165
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/super.c (ffffffff8162e0bb)
Location: include/linux/iversion.h:165
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/fat/inode.c (ffffffff81674a18)
Location: include/linux/iversion.h:165
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
In fs/ext4/ioctl.c (ffff80001048a7d4)
Location: include/linux/iversion.h:152
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/super.c (ffff8000104ad17c)
Location: include/linux/iversion.h:152
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/fat/inode.c (ffff8000104ed71c)
Location: include/linux/iversion.h:152
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
In fs/ext4/ioctl.c (c064ca54)
Location: include/linux/iversion.h:152
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/super.c (c0675f44)
Location: include/linux/iversion.h:152
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/fat/inode.c (c06ab474)
Location: include/linux/iversion.h:152
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
In fs/ext4/ioctl.c (c0000000005b1bd0)
Location: include/linux/iversion.h:152
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/super.c (c0000000005e5dac)
Location: include/linux/iversion.h:152
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/fat/inode.c (c00000000062c548)
Location: include/linux/iversion.h:152
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
In fs/ext4/ioctl.c (ffffffe000311cb2)
Location: include/linux/iversion.h:152
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/super.c (ffffffe0003306e6)
Location: include/linux/iversion.h:152
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/fat/inode.c (ffffffe00035dcca)
Location: include/linux/iversion.h:152
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
In fs/ext4/ioctl.c (ffffffff813ae3d6)
Location: include/linux/iversion.h:152
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/super.c (ffffffff813d21e8)
Location: include/linux/iversion.h:152
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/fat/inode.c (ffffffff8140509b)
Location: include/linux/iversion.h:152
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
In fs/ext4/ioctl.c (ffffffff8139ee66)
Location: include/linux/iversion.h:152
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/super.c (ffffffff813c2c68)
Location: include/linux/iversion.h:152
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/fat/inode.c (ffffffff813f5b1b)
Location: include/linux/iversion.h:152
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
In fs/ext4/ioctl.c (ffffffff813abc36)
Location: include/linux/iversion.h:152
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/super.c (ffffffff813cf678)
Location: include/linux/iversion.h:152
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/fat/inode.c (ffffffff8140241b)
Location: include/linux/iversion.h:152
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
In fs/ext4/ioctl.c (ffffffff813c05d6)
Location: include/linux/iversion.h:152
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
```
In fs/ext4/super.c (ffffffff813e4c78)
Location: include/linux/iversion.h:152
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/fat/inode.c (ffffffff814183eb)
Location: include/linux/iversion.h:152
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
```
</details>
</li>
</ul>

## Differences
