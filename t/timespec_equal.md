# Function: <code>timespec_equal</code>

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
In fs/inode.c (ffffffff812276df)
Location: include/linux/time.h:13
Inline: True
Inline callers:
  - fs/inode.c:file_update_time
  - fs/inode.c:file_update_time
  - fs/inode.c:atime_needs_update
```
```
In fs/fuse/inode.c (0)
Location: include/linux/time.h:13
Inline: True
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
In fs/inode.c (ffffffff8124fdef)
Location: include/linux/time.h:13
Inline: True
Inline callers:
  - fs/inode.c:file_update_time
  - fs/inode.c:file_update_time
  - fs/inode.c:atime_needs_update
```
```
In fs/fuse/inode.c (0)
Location: include/linux/time.h:13
Inline: True
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
In fs/inode.c (ffffffff81262f0e)
Location: include/linux/time.h:13
Inline: True
Inline callers:
  - fs/inode.c:file_update_time
  - fs/inode.c:file_update_time
  - fs/inode.c:__atime_needs_update
  - fs/inode.c:__atime_needs_update
  - fs/inode.c:__atime_needs_update
```
```
In fs/fuse/inode.c (0)
Location: include/linux/time.h:13
Inline: True
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
In fs/inode.c (ffffffff812707b0)
Location: include/linux/time.h:22
Inline: True
Inline callers:
  - fs/inode.c:file_update_time
  - fs/inode.c:file_update_time
  - fs/inode.c:__atime_needs_update
  - fs/inode.c:__atime_needs_update
  - fs/inode.c:__atime_needs_update
```
```
In fs/fuse/inode.c (ffffffff8137a933)
Location: include/linux/time.h:22
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes
```
</details>
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff813ceb76)
Location: include/linux/time32.h:49
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes
```
</details>
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
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In sound/core/pcm_lib.c (c0c99440)
Location: include/linux/time32.h:109
Inline: True
Inline callers:
  - sound/core/pcm_lib.c:update_audio_tstamp
```
</details>
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
