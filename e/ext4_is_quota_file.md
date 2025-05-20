# Function: <code>ext4_is_quota_file</code>

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
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812fff20)
Location: fs/ext4/ext4.h:2106
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/ioctl.c (ffffffff81309a73)
Location: fs/ext4/ext4.h:2106
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/mballoc.c (ffffffff81310b39)
Location: fs/ext4/ext4.h:2106
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/move_extent.c (ffffffff81315caf)
Location: fs/ext4/ext4.h:2106
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
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
In fs/ext4/inode.c (ffffffff81324740)
Location: fs/ext4/ext4.h:2066
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/ioctl.c (ffffffff8132e505)
Location: fs/ext4/ext4.h:2066
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/mballoc.c (ffffffff813359d8)
Location: fs/ext4/ext4.h:2066
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/move_extent.c (ffffffff8133a515)
Location: fs/ext4/ext4.h:2066
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
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
In fs/ext4/inode.c (ffffffff81352ab8)
Location: fs/ext4/ext4.h:2067
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/ioctl.c (ffffffff8135cb76)
Location: fs/ext4/ext4.h:2067
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/mballoc.c (ffffffff81363bd8)
Location: fs/ext4/ext4.h:2067
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/move_extent.c (ffffffff81368aba)
Location: fs/ext4/ext4.h:2067
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
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
In fs/ext4/inode.c (ffffffff8136abd8)
Location: fs/ext4/ext4.h:2080
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/ioctl.c (ffffffff81374fd1)
Location: fs/ext4/ext4.h:2080
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/mballoc.c (ffffffff8137be78)
Location: fs/ext4/ext4.h:2080
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/move_extent.c (ffffffff81380f4c)
Location: fs/ext4/ext4.h:2080
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
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
In fs/ext4/inode.c (ffffffff81394137)
Location: fs/ext4/ext4.h:2104
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/ioctl.c (ffffffff8139e6bf)
Location: fs/ext4/ext4.h:2104
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/mballoc.c (ffffffff813a5fc8)
Location: fs/ext4/ext4.h:2104
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/move_extent.c (ffffffff813aa26e)
Location: fs/ext4/ext4.h:2104
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
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
In fs/ext4/inode.c (ffffffff813acac9)
Location: fs/ext4/ext4.h:2162
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/ioctl.c (ffffffff813b7457)
Location: fs/ext4/ext4.h:2162
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/mballoc.c (ffffffff813bee38)
Location: fs/ext4/ext4.h:2162
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/move_extent.c (ffffffff813c319e)
Location: fs/ext4/ext4.h:2162
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
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
In fs/ext4/inode.c (ffffffff813f8d9b)
Location: fs/ext4/ext4.h:2260
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/ioctl.c (ffffffff81400fea)
Location: fs/ext4/ext4.h:2260
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/mballoc.c (ffffffff8140af08)
Location: fs/ext4/ext4.h:2260
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/move_extent.c (ffffffff8140e71b)
Location: fs/ext4/ext4.h:2260
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_check_arguments
  - fs/ext4/move_extent.c:mext_check_arguments
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
In fs/ext4/inode.c (ffffffff8140b418)
Location: fs/ext4/ext4.h:2385
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/ioctl.c (ffffffff814138aa)
Location: fs/ext4/ext4.h:2385
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/mballoc.c (ffffffff8141e378)
Location: fs/ext4/ext4.h:2385
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/move_extent.c (ffffffff81421bcb)
Location: fs/ext4/ext4.h:2385
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_check_arguments
  - fs/ext4/move_extent.c:mext_check_arguments
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
In fs/ext4/inode.c (ffffffff814114d8)
Location: fs/ext4/ext4.h:2437
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/ioctl.c (ffffffff814195b2)
Location: fs/ext4/ext4.h:2437
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/mballoc.c (ffffffff81424ce8)
Location: fs/ext4/ext4.h:2437
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/move_extent.c (ffffffff814283d1)
Location: fs/ext4/ext4.h:2437
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_check_arguments
  - fs/ext4/move_extent.c:mext_check_arguments
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
In fs/ext4/inode.c (ffffffff81464523)
Location: fs/ext4/ext4.h:2507
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/ioctl.c (ffffffff8146c7a2)
Location: fs/ext4/ext4.h:2507
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/mballoc.c (ffffffff814789ea)
Location: fs/ext4/ext4.h:2507
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/move_extent.c (ffffffff8147c091)
Location: fs/ext4/ext4.h:2507
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_check_arguments
  - fs/ext4/move_extent.c:mext_check_arguments
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
In fs/ext4/inode.c (ffffffff814e3b16)
Location: fs/ext4/ext4.h:2512
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/ioctl.c (ffffffff814ece0d)
Location: fs/ext4/ext4.h:2512
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/mballoc.c (ffffffff814fb1d2)
Location: fs/ext4/ext4.h:2512
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/move_extent.c (ffffffff814fe5d0)
Location: fs/ext4/ext4.h:2512
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_check_arguments
  - fs/ext4/move_extent.c:mext_check_arguments
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
In fs/ext4/inode.c (ffffffff8157d016)
Location: fs/ext4/ext4.h:2522
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/ioctl.c (ffffffff81586c1d)
Location: fs/ext4/ext4.h:2522
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/mballoc.c (ffffffff81595972)
Location: fs/ext4/ext4.h:2522
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/move_extent.c (ffffffff81598e10)
Location: fs/ext4/ext4.h:2522
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_check_arguments
  - fs/ext4/move_extent.c:mext_check_arguments
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
In fs/ext4/inode.c (ffffffff815b43e7)
Location: fs/ext4/ext4.h:2516
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/ioctl.c (ffffffff815bd17d)
Location: fs/ext4/ext4.h:2516
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/mballoc.c (ffffffff815cc373)
Location: fs/ext4/ext4.h:2516
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/move_extent.c (ffffffff815cf8f0)
Location: fs/ext4/ext4.h:2516
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_check_arguments
  - fs/ext4/move_extent.c:mext_check_arguments
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
In fs/ext4/inode.c (ffffffff815ed1f5)
Location: fs/ext4/ext4.h:2534
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/ioctl.c (ffffffff815f5f46)
Location: fs/ext4/ext4.h:2534
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/mballoc.c (ffffffff81604e03)
Location: fs/ext4/ext4.h:2534
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/move_extent.c (ffffffff81608180)
Location: fs/ext4/ext4.h:2534
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:mext_check_arguments
  - fs/ext4/move_extent.c:mext_check_arguments
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
In fs/ext4/inode.c (ffff8000104812e0)
Location: fs/ext4/ext4.h:2162
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/ioctl.c (ffff80001048cef0)
Location: fs/ext4/ext4.h:2162
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/mballoc.c (ffff800010495b30)
Location: fs/ext4/ext4.h:2162
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/move_extent.c (ffff80001049aa38)
Location: fs/ext4/ext4.h:2162
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
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
In fs/ext4/inode.c (c0642370)
Location: fs/ext4/ext4.h:2162
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/ioctl.c (c064e800)
Location: fs/ext4/ext4.h:2162
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/mballoc.c (c06576bc)
Location: fs/ext4/ext4.h:2162
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/move_extent.c (c065c454)
Location: fs/ext4/ext4.h:2162
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
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
In fs/ext4/inode.c (c0000000005a57fc)
Location: fs/ext4/ext4.h:2162
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/ioctl.c (c0000000005b3ab0)
Location: fs/ext4/ext4.h:2162
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/mballoc.c (c0000000005bf7dc)
Location: fs/ext4/ext4.h:2162
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/move_extent.c (c0000000005c5314)
Location: fs/ext4/ext4.h:2162
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
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
In fs/ext4/inode.c (ffffffe000309f4c)
Location: fs/ext4/ext4.h:2162
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/ioctl.c (ffffffe000312e00)
Location: fs/ext4/ext4.h:2162
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/mballoc.c (ffffffe00031a722)
Location: fs/ext4/ext4.h:2162
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/move_extent.c (ffffffe00031e18e)
Location: fs/ext4/ext4.h:2162
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
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
In fs/ext4/inode.c (ffffffff813a50a9)
Location: fs/ext4/ext4.h:2162
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/ioctl.c (ffffffff813afa37)
Location: fs/ext4/ext4.h:2162
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/mballoc.c (ffffffff813b7418)
Location: fs/ext4/ext4.h:2162
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/move_extent.c (ffffffff813bb77e)
Location: fs/ext4/ext4.h:2162
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
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
In fs/ext4/inode.c (ffffffff81395b39)
Location: fs/ext4/ext4.h:2162
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/ioctl.c (ffffffff813a04c7)
Location: fs/ext4/ext4.h:2162
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/mballoc.c (ffffffff813a7ea8)
Location: fs/ext4/ext4.h:2162
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/move_extent.c (ffffffff813ac20e)
Location: fs/ext4/ext4.h:2162
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
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
In fs/ext4/inode.c (ffffffff813a2909)
Location: fs/ext4/ext4.h:2162
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/ioctl.c (ffffffff813ad297)
Location: fs/ext4/ext4.h:2162
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/mballoc.c (ffffffff813b4c78)
Location: fs/ext4/ext4.h:2162
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/move_extent.c (ffffffff813b8fde)
Location: fs/ext4/ext4.h:2162
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
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
In fs/ext4/inode.c (ffffffff813b6fe9)
Location: fs/ext4/ext4.h:2162
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/ioctl.c (ffffffff813c1c50)
Location: fs/ext4/ext4.h:2162
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
```
In fs/ext4/mballoc.c (ffffffff813c98a3)
Location: fs/ext4/ext4.h:2162
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
```
In fs/ext4/move_extent.c (ffffffff813cdcfe)
Location: fs/ext4/ext4.h:2162
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
```
</details>
</li>
</ul>

## Differences
