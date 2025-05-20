# Function: <code>u64_to_fsid</code>

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
In fs/ext4/super.c (0)
Location: include/linux/statfs.h:48
Inline: True
```
```
In fs/squashfs/super.c (ffffffff8146913b)
Location: include/linux/statfs.h:48
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_statfs
```
```
In fs/fat/inode.c (ffffffff814755d4)
Location: include/linux/statfs.h:48
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_statfs
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
In mm/shmem.c (0)
Location: include/linux/statfs.h:49
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/statfs.h:49
Inline: True
```
```
In fs/squashfs/super.c (ffffffff8146e83b)
Location: include/linux/statfs.h:49
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_statfs
```
```
In fs/fat/inode.c (ffffffff8147b042)
Location: include/linux/statfs.h:49
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_statfs
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
In mm/shmem.c (0)
Location: include/linux/statfs.h:49
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/statfs.h:49
Inline: True
```
```
In fs/squashfs/super.c (ffffffff814c50d8)
Location: include/linux/statfs.h:49
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_statfs
```
```
In fs/fat/inode.c (ffffffff814d2662)
Location: include/linux/statfs.h:49
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_statfs
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
In mm/shmem.c (0)
Location: include/linux/statfs.h:49
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/statfs.h:49
Inline: True
```
```
In fs/squashfs/super.c (ffffffff8154ff07)
Location: include/linux/statfs.h:49
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_statfs
```
```
In fs/fat/inode.c (ffffffff8155f642)
Location: include/linux/statfs.h:49
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_statfs
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
In mm/shmem.c (0)
Location: include/linux/statfs.h:49
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/statfs.h:49
Inline: True
```
```
In fs/squashfs/super.c (ffffffff815f0a47)
Location: include/linux/statfs.h:49
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_statfs
```
```
In fs/fat/inode.c (ffffffff81601912)
Location: include/linux/statfs.h:49
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_statfs
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
In mm/shmem.c (0)
Location: include/linux/statfs.h:49
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/statfs.h:49
Inline: True
```
```
In fs/squashfs/super.c (ffffffff81628a87)
Location: include/linux/statfs.h:49
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_statfs
```
```
In fs/fat/inode.c (ffffffff81639802)
Location: include/linux/statfs.h:49
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_statfs
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
In mm/shmem.c (0)
Location: include/linux/statfs.h:49
Inline: True
```
```
In fs/libfs.c (ffffffff815204bd)
Location: include/linux/statfs.h:49
Inline: True
Inline callers:
  - fs/libfs.c:simple_statfs
```
```
In fs/kernfs/mount.c (0)
Location: include/linux/statfs.h:49
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/statfs.h:49
Inline: True
```
```
In fs/squashfs/super.c (ffffffff81661c77)
Location: include/linux/statfs.h:49
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_statfs
```
```
In fs/hugetlbfs/inode.c (ffffffff81667a62)
Location: include/linux/statfs.h:49
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_statfs
```
```
In fs/fat/inode.c (ffffffff81672cf2)
Location: include/linux/statfs.h:49
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_statfs
```
```
In fs/efivarfs/super.c (ffffffff816aec6a)
Location: include/linux/statfs.h:49
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_statfs
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
