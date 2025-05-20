# Function: <code>timespec64_equal</code>

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
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812930f0)
Location: include/linux/time64.h:42
Inline: True
Inline callers:
  - fs/inode.c:file_update_time
  - fs/inode.c:file_update_time
  - fs/inode.c:__atime_needs_update
  - fs/inode.c:__atime_needs_update
  - fs/inode.c:__atime_needs_update
```
```
In fs/fuse/inode.c (ffffffff8139f7d3)
Location: include/linux/time64.h:42
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812b8d48)
Location: include/linux/time64.h:43
Inline: True
Inline callers:
  - fs/inode.c:file_update_time
  - fs/inode.c:file_update_time
  - fs/inode.c:__atime_needs_update
  - fs/inode.c:__atime_needs_update
  - fs/inode.c:__atime_needs_update
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
In fs/inode.c (ffffffff812cde88)
Location: include/linux/time64.h:44
Inline: True
Inline callers:
  - fs/inode.c:file_update_time
  - fs/inode.c:file_update_time
  - fs/inode.c:atime_needs_update
```
```
In fs/fuse/inode.c (ffffffff813e7fe6)
Location: include/linux/time64.h:44
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes
```
```
In fs/fuse/readdir.c (ffffffff813ea01a)
Location: include/linux/time64.h:44
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
In fs/inode.c (ffffffff812eacbc)
Location: include/linux/time64.h:47
Inline: True
Inline callers:
  - fs/inode.c:file_update_time
  - fs/inode.c:file_update_time
  - fs/inode.c:atime_needs_update
```
```
In fs/fuse/inode.c (ffffffff81414091)
Location: include/linux/time64.h:47
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes
```
```
In fs/fuse/readdir.c (ffffffff814168be)
Location: include/linux/time64.h:47
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
In fs/inode.c (ffffffff812fc7ec)
Location: include/linux/time64.h:49
Inline: True
Inline callers:
  - fs/inode.c:file_update_time
  - fs/inode.c:file_update_time
  - fs/inode.c:atime_needs_update
```
```
In fs/fuse/inode.c (ffffffff8142e131)
Location: include/linux/time64.h:49
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes
```
```
In fs/fuse/readdir.c (ffffffff814307de)
Location: include/linux/time64.h:49
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
In fs/inode.c (ffffffff81335955)
Location: include/linux/time64.h:41
Inline: True
Inline callers:
  - fs/inode.c:file_update_time
  - fs/inode.c:file_update_time
  - fs/inode.c:atime_needs_update
```
```
In fs/fuse/inode.c (ffffffff8147dda1)
Location: include/linux/time64.h:41
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes
```
```
In fs/fuse/readdir.c (ffffffff814803cf)
Location: include/linux/time64.h:41
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
In fs/inode.c (ffffffff813412d5)
Location: include/linux/time64.h:41
Inline: True
Inline callers:
  - fs/inode.c:file_update_time
  - fs/inode.c:file_update_time
  - fs/inode.c:atime_needs_update
```
```
In fs/fuse/inode.c (ffffffff81499124)
Location: include/linux/time64.h:41
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes
```
```
In fs/fuse/readdir.c (ffffffff8149bab2)
Location: include/linux/time64.h:41
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
In fs/inode.c (ffffffff81347615)
Location: include/linux/time64.h:41
Inline: True
Inline callers:
  - fs/inode.c:file_update_time
  - fs/inode.c:file_update_time
  - fs/inode.c:atime_needs_update
```
```
In fs/fuse/inode.c (ffffffff8149e354)
Location: include/linux/time64.h:41
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes
```
```
In fs/fuse/readdir.c (ffffffff814a0bd2)
Location: include/linux/time64.h:41
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
In fs/inode.c (ffffffff81395135)
Location: include/linux/time64.h:43
Inline: True
Inline callers:
  - fs/inode.c:file_update_time
  - fs/inode.c:file_update_time
  - fs/inode.c:atime_needs_update
```
```
In fs/fuse/inode.c (ffffffff814f6204)
Location: include/linux/time64.h:43
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes
```
```
In fs/fuse/readdir.c (ffffffff814f8ab1)
Location: include/linux/time64.h:43
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
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
In fs/inode.c (ffffffff81417f8f)
Location: include/linux/time64.h:43
Inline: True
Inline callers:
  - fs/inode.c:file_update_time
  - fs/inode.c:file_update_time
  - fs/inode.c:atime_needs_update
```
```
In fs/fuse/inode.c (ffffffff81586007)
Location: include/linux/time64.h:43
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes
```
```
In fs/fuse/readdir.c (ffffffff815890a4)
Location: include/linux/time64.h:43
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
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
In fs/inode.c (ffffffff814a4f64)
Location: include/linux/time64.h:46
Inline: True
Inline callers:
  - fs/inode.c:atime_needs_update
```
```
In fs/fuse/inode.c (ffffffff8162c1fd)
Location: include/linux/time64.h:46
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes
```
```
In fs/fuse/readdir.c (ffffffff8162f5bb)
Location: include/linux/time64.h:46
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
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
In fs/inode.c (ffffffff814da1dc)
Location: include/linux/time64.h:46
Inline: True
Inline callers:
  - fs/inode.c:atime_needs_update
```
```
In fs/fuse/inode.c (ffffffff8166443d)
Location: include/linux/time64.h:46
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes
```
```
In fs/fuse/readdir.c (ffffffff8166782e)
Location: include/linux/time64.h:46
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
In fs/inode.c (ffffffff81509c86)
Location: include/linux/time64.h:46
Inline: True
Inline callers:
  - fs/inode.c:inode_needs_update_time
  - fs/inode.c:inode_needs_update_time
  - fs/inode.c:atime_needs_update
  - fs/inode.c:inode_update_timestamps
  - fs/inode.c:inode_update_timestamps
  - fs/inode.c:inode_update_timestamps
```
```
In fs/fuse/inode.c (ffffffff8169e63d)
Location: include/linux/time64.h:46
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes
```
```
In fs/fuse/readdir.c (ffffffff816a1b81)
Location: include/linux/time64.h:46
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
In fs/inode.c (ffff8000103ac27c)
Location: include/linux/time64.h:49
Inline: True
Inline callers:
  - fs/inode.c:file_update_time
  - fs/inode.c:file_update_time
  - fs/inode.c:atime_needs_update
```
```
In fs/fuse/inode.c (ffff800010512804)
Location: include/linux/time64.h:49
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes
```
```
In fs/fuse/readdir.c (ffff800010515308)
Location: include/linux/time64.h:49
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
In fs/inode.c (c058d55c)
Location: include/linux/time64.h:49
Inline: True
Inline callers:
  - fs/inode.c:file_update_time
  - fs/inode.c:file_update_time
  - fs/inode.c:atime_needs_update
```
```
In fs/fuse/inode.c (c06cd910)
Location: include/linux/time64.h:49
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes
```
```
In fs/fuse/readdir.c (c06cffe8)
Location: include/linux/time64.h:49
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
In fs/inode.c (c0000000004a7810)
Location: include/linux/time64.h:49
Inline: True
Inline callers:
  - fs/inode.c:file_update_time
  - fs/inode.c:file_update_time
  - fs/inode.c:atime_needs_update
```
```
In fs/fuse/inode.c (c00000000065a4e0)
Location: include/linux/time64.h:49
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes
```
```
In fs/fuse/readdir.c (c00000000065dac0)
Location: include/linux/time64.h:49
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
In fs/inode.c (ffffffe0002717d0)
Location: include/linux/time64.h:49
Inline: True
Inline callers:
  - fs/inode.c:file_update_time
  - fs/inode.c:file_update_time
  - fs/inode.c:atime_needs_update
```
```
In fs/fuse/inode.c (ffffffe00037c84e)
Location: include/linux/time64.h:49
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes
```
```
In fs/fuse/readdir.c (ffffffe00037ec8a)
Location: include/linux/time64.h:49
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
In fs/inode.c (ffffffff812f4dcc)
Location: include/linux/time64.h:49
Inline: True
Inline callers:
  - fs/inode.c:file_update_time
  - fs/inode.c:file_update_time
  - fs/inode.c:atime_needs_update
```
```
In fs/fuse/inode.c (ffffffff81426711)
Location: include/linux/time64.h:49
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes
```
```
In fs/fuse/readdir.c (ffffffff81428dbe)
Location: include/linux/time64.h:49
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
In fs/inode.c (ffffffff812e59ec)
Location: include/linux/time64.h:49
Inline: True
Inline callers:
  - fs/inode.c:file_update_time
  - fs/inode.c:file_update_time
  - fs/inode.c:atime_needs_update
```
```
In fs/fuse/inode.c (ffffffff81417191)
Location: include/linux/time64.h:49
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes
```
```
In fs/fuse/readdir.c (ffffffff8141983e)
Location: include/linux/time64.h:49
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
In fs/inode.c (ffffffff812f2bdc)
Location: include/linux/time64.h:49
Inline: True
Inline callers:
  - fs/inode.c:file_update_time
  - fs/inode.c:file_update_time
  - fs/inode.c:atime_needs_update
```
```
In fs/fuse/inode.c (ffffffff814228b1)
Location: include/linux/time64.h:49
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes
```
```
In fs/fuse/readdir.c (ffffffff81424f5e)
Location: include/linux/time64.h:49
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
In fs/inode.c (ffffffff813042ec)
Location: include/linux/time64.h:49
Inline: True
Inline callers:
  - fs/inode.c:file_update_time
  - fs/inode.c:file_update_time
  - fs/inode.c:atime_needs_update
```
```
In fs/fuse/inode.c (ffffffff814396ee)
Location: include/linux/time64.h:49
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes
```
```
In fs/fuse/readdir.c (ffffffff8143bdf9)
Location: include/linux/time64.h:49
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
```
</details>
</li>
</ul>

## Differences
