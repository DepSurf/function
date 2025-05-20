# Function: <code>ext4_inode_block_unlocked_dio</code>

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
In fs/ext4/inode.c (ffffffff8129c86f)
Location: fs/ext4/ext4.h:3197
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
```
```
In fs/ext4/ioctl.c (ffffffff812a0a5c)
Location: fs/ext4/ext4.h:3197
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/extents.c (ffffffff812c3396)
Location: fs/ext4/ext4.h:3197
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_fallocate
```
```
In fs/ext4/move_extent.c (ffffffff812d743c)
Location: fs/ext4/ext4.h:3197
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
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
In fs/ext4/inode.c (ffffffff812cd6e5)
Location: fs/ext4/ext4.h:3234
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_punch_hole
```
```
In fs/ext4/ioctl.c (ffffffff812cf78c)
Location: fs/ext4/ext4.h:3234
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/extents.c (ffffffff812f9d5b)
Location: fs/ext4/ext4.h:3234
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
```
```
In fs/ext4/move_extent.c (ffffffff81307184)
Location: fs/ext4/ext4.h:3234
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
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
In fs/ext4/inode.c (ffffffff812e34a5)
Location: fs/ext4/ext4.h:3212
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_punch_hole
```
```
In fs/ext4/ioctl.c (ffffffff812e55b8)
Location: fs/ext4/ext4.h:3212
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/extents.c (ffffffff8130fd2b)
Location: fs/ext4/ext4.h:3212
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
```
```
In fs/ext4/move_extent.c (ffffffff8131d15e)
Location: fs/ext4/ext4.h:3212
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
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
In fs/ext4/extents.c (ffffffff812ee31d)
Location: fs/ext4/ext4.h:3229
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
```
```
In fs/ext4/inode.c (ffffffff81307692)
Location: fs/ext4/ext4.h:3229
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_punch_hole
```
```
In fs/ext4/ioctl.c (ffffffff81308d55)
Location: fs/ext4/ext4.h:3229
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/move_extent.c (ffffffff81315c16)
Location: fs/ext4/ext4.h:3229
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
In fs/ext4/extents.c (ffffffff81312de0)
Location: fs/ext4/ext4.h:3190
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
```
```
In fs/ext4/inode.c (ffffffff8132c2e2)
Location: fs/ext4/ext4.h:3190
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_punch_hole
```
```
In fs/ext4/ioctl.c (ffffffff8132dbd6)
Location: fs/ext4/ext4.h:3190
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/move_extent.c (ffffffff8133a476)
Location: fs/ext4/ext4.h:3190
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
```
</details>
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
