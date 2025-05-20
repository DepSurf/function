# Function: <code>ext4_test_mount_flag</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff813fafdc)
Location: fs/ext4/ext4.h:1738
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
```
```
In fs/ext4/fsync.c (ffffffff813fd765)
Location: fs/ext4/ext4.h:1738
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inode.c (ffffffff8140e646)
Location: fs/ext4/ext4.h:1738
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_map_and_submit_extent
```
```
In fs/ext4/super.c (ffffffff8144a41d)
Location: fs/ext4/ext4.h:1738
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
```
```
In fs/ext4/fast_commit.c (ffffffff81457287)
Location: fs/ext4/ext4.h:1738
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_commit
  - fs/ext4/fast_commit.c:ext4_fc_commit
  - fs/ext4/fast_commit.c:__ext4_fc_track_create
  - fs/ext4/fast_commit.c:__ext4_fc_track_link
  - fs/ext4/fast_commit.c:__ext4_fc_track_unlink
  - fs/ext4/fast_commit.c:__track_dentry_update
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
In fs/ext4/file.c (ffffffff814014ac)
Location: fs/ext4/ext4.h:1747
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
```
```
In fs/ext4/fsync.c (ffffffff81403b75)
Location: fs/ext4/ext4.h:1747
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inode.c (ffffffff814149c5)
Location: fs/ext4/ext4.h:1747
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_map_and_submit_extent
```
```
In fs/ext4/super.c (ffffffff8144fd95)
Location: fs/ext4/ext4.h:1747
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
```
```
In fs/ext4/fast_commit.c (ffffffff8145cc2d)
Location: fs/ext4/ext4.h:1747
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_commit
  - fs/ext4/fast_commit.c:ext4_fc_commit
  - fs/ext4/fast_commit.c:__ext4_fc_track_create
  - fs/ext4/fast_commit.c:__ext4_fc_track_link
  - fs/ext4/fast_commit.c:__ext4_fc_track_unlink
  - fs/ext4/fast_commit.c:__track_dentry_update
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
In fs/ext4/file.c (ffffffff81453a2c)
Location: fs/ext4/ext4.h:1808
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
```
```
In fs/ext4/fsync.c (ffffffff81456345)
Location: fs/ext4/ext4.h:1808
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inode.c (ffffffff81467f48)
Location: fs/ext4/ext4.h:1808
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_map_and_submit_extent
```
```
In fs/ext4/super.c (ffffffff814a6a12)
Location: fs/ext4/ext4.h:1808
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_remount
```
```
In fs/ext4/fast_commit.c (ffffffff814b03ae)
Location: fs/ext4/ext4.h:1808
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_commit
  - fs/ext4/fast_commit.c:__ext4_fc_track_create
  - fs/ext4/fast_commit.c:__ext4_fc_track_link
  - fs/ext4/fast_commit.c:__ext4_fc_track_unlink
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
In fs/ext4/file.c (ffffffff814d0eee)
Location: fs/ext4/ext4.h:1810
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
```
```
In fs/ext4/fsync.c (ffffffff814d3c7a)
Location: fs/ext4/ext4.h:1810
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inode.c (ffffffff814e7ab7)
Location: fs/ext4/ext4.h:1810
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:mpage_map_and_submit_extent
```
```
In fs/ext4/namei.c (ffffffff8150730b)
Location: fs/ext4/ext4.h:1810
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
```
```
In fs/ext4/super.c (ffffffff8152b3aa)
Location: fs/ext4/ext4.h:1810
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:__ext4_remount
```
```
In fs/ext4/fast_commit.c (ffffffff81538c6b)
Location: fs/ext4/ext4.h:1810
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_commit
  - fs/ext4/fast_commit.c:ext4_fc_track_range
  - fs/ext4/fast_commit.c:ext4_fc_track_inode
  - fs/ext4/fast_commit.c:ext4_fc_track_create
  - fs/ext4/fast_commit.c:ext4_fc_track_link
  - fs/ext4/fast_commit.c:ext4_fc_track_unlink
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
In fs/ext4/file.c (ffffffff8156992e)
Location: fs/ext4/ext4.h:1820
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
```
```
In fs/ext4/fsync.c (ffffffff8156c8ca)
Location: fs/ext4/ext4.h:1820
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inode.c (ffffffff81581ed0)
Location: fs/ext4/ext4.h:1820
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_writepages
  - fs/ext4/inode.c:mpage_map_and_submit_extent
```
```
In fs/ext4/namei.c (ffffffff815a1dce)
Location: fs/ext4/ext4.h:1820
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
```
```
In fs/ext4/super.c (ffffffff815ca3da)
Location: fs/ext4/ext4.h:1820
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:__ext4_remount
```
```
In fs/ext4/fast_commit.c (ffffffff815d6f3b)
Location: fs/ext4/ext4.h:1820
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_commit
  - fs/ext4/fast_commit.c:ext4_fc_track_range
  - fs/ext4/fast_commit.c:ext4_fc_track_inode
  - fs/ext4/fast_commit.c:ext4_fc_track_create
  - fs/ext4/fast_commit.c:ext4_fc_track_link
  - fs/ext4/fast_commit.c:ext4_fc_track_unlink
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
In fs/ext4/file.c (ffffffff815a171e)
Location: fs/ext4/ext4.h:1815
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
```
```
In fs/ext4/fsync.c (ffffffff815a4817)
Location: fs/ext4/ext4.h:1815
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
```
In fs/ext4/inode.c (ffffffff815b8ac0)
Location: fs/ext4/ext4.h:1815
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_writepages
  - fs/ext4/inode.c:mpage_map_and_submit_extent
```
```
In fs/ext4/namei.c (ffffffff815d8753)
Location: fs/ext4/ext4.h:1815
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
```
```
In fs/ext4/super.c (ffffffff81602270)
Location: fs/ext4/ext4.h:1815
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:__ext4_remount
```
```
In fs/ext4/fast_commit.c (ffffffff8160eb0b)
Location: fs/ext4/ext4.h:1815
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_commit
  - fs/ext4/fast_commit.c:ext4_fc_track_range
  - fs/ext4/fast_commit.c:ext4_fc_track_inode
  - fs/ext4/fast_commit.c:ext4_fc_track_create
  - fs/ext4/fast_commit.c:ext4_fc_track_link
  - fs/ext4/fast_commit.c:ext4_fc_track_unlink
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
In fs/ext4/file.c (ffffffff815da4ce)
Location: fs/ext4/ext4.h:1833
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
```
```
In fs/ext4/namei.c (ffffffff81610dbe)
Location: fs/ext4/ext4.h:1833
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
```
```
In fs/ext4/fast_commit.c (ffffffff816478cb)
Location: fs/ext4/ext4.h:1833
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_commit
  - fs/ext4/fast_commit.c:ext4_fc_track_range
  - fs/ext4/fast_commit.c:ext4_fc_track_inode
  - fs/ext4/fast_commit.c:ext4_fc_track_create
  - fs/ext4/fast_commit.c:ext4_fc_track_link
  - fs/ext4/fast_commit.c:ext4_fc_track_unlink
```
</details>
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
