# Function: <code>is_idmapped_mnt</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8141de57)
Location: include/linux/fs.h:2607
Inline: True
Inline callers:
  - fs/namespace.c:mount_setattr_prepare
```
```
In fs/proc_namespace.c (ffffffff8144cada)
Location: include/linux/fs.h:2607
Inline: True
```
```
In fs/ecryptfs/main.c (ffffffff81568367)
Location: include/linux/fs.h:2607
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
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
In fs/namespace.c (ffffffff814aa1dd)
Location: include/linux/fs.h:2746
Inline: True
Inline callers:
  - fs/namespace.c:mount_setattr_prepare
```
```
In fs/proc_namespace.c (ffffffff814db03a)
Location: include/linux/fs.h:2746
Inline: True
```
```
In fs/ecryptfs/main.c (ffffffff8160bc71)
Location: include/linux/fs.h:2746
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
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
In mm/shmem.c (ffffffff813bc825)
Location: include/linux/fs.h:2340
Inline: True
```
```
In fs/namespace.c (ffffffff814df293)
Location: include/linux/fs.h:2340
Inline: True
Inline callers:
  - fs/namespace.c:mount_setattr_prepare
```
```
In fs/proc_namespace.c (ffffffff8150f5ea)
Location: include/linux/fs.h:2340
Inline: True
```
```
In fs/ecryptfs/main.c (ffffffff81643b51)
Location: include/linux/fs.h:2340
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
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
In mm/shmem.c (ffffffff813e8b25)
Location: include/linux/fs.h:2570
Inline: True
```
```
In fs/namespace.c (ffffffff81511a18)
Location: include/linux/fs.h:2570
Inline: True
Inline callers:
  - fs/namespace.c:statmount_mnt_basic
  - fs/namespace.c:mount_setattr_prepare
```
```
In fs/proc_namespace.c (ffffffff81543aea)
Location: include/linux/fs.h:2570
Inline: True
```
```
In fs/ecryptfs/main.c (ffffffff8167d0e1)
Location: include/linux/fs.h:2570
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
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
