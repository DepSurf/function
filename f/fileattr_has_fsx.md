# Function: <code>fileattr_has_fsx</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/efivarfs/inode.c (ffffffff814a8b95)
Location: include/linux/fileattr.h:48
Inline: True
Inline callers:
  - fs/efivarfs/inode.c:efivarfs_fileattr_set
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/efivarfs/inode.c (ffffffff81500ec5)
Location: include/linux/fileattr.h:48
Inline: True
Inline callers:
  - fs/efivarfs/inode.c:efivarfs_fileattr_set
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/efivarfs/inode.c (ffffffff815921e5)
Location: include/linux/fileattr.h:48
Inline: True
Inline callers:
  - fs/efivarfs/inode.c:efivarfs_fileattr_set
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
In mm/shmem.c (ffffffff8138acee)
Location: include/linux/fileattr.h:48
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fileattr_set
```
```
In fs/efivarfs/inode.c (ffffffff81639af5)
Location: include/linux/fileattr.h:48
Inline: True
Inline callers:
  - fs/efivarfs/inode.c:efivarfs_fileattr_set
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
In mm/shmem.c (ffffffff813bd31e)
Location: include/linux/fileattr.h:48
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fileattr_set
```
```
In fs/efivarfs/inode.c (ffffffff81671f55)
Location: include/linux/fileattr.h:48
Inline: True
Inline callers:
  - fs/efivarfs/inode.c:efivarfs_fileattr_set
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
In mm/shmem.c (ffffffff813e821e)
Location: include/linux/fileattr.h:48
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fileattr_set
```
```
In fs/efivarfs/inode.c (ffffffff816adf35)
Location: include/linux/fileattr.h:48
Inline: True
Inline callers:
  - fs/efivarfs/inode.c:efivarfs_fileattr_set
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
