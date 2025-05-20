# Function: <code>fuse_stale_inode</code>

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
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8149377e)
Location: fs/fuse/fuse_i.h:873
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/inode.c (ffffffff8149e44b)
Location: fs/fuse/fuse_i.h:873
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_iget
```
```
In fs/fuse/readdir.c (ffffffff814a0973)
Location: fs/fuse/fuse_i.h:873
Inline: True
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
In fs/fuse/dir.c (ffffffff814eabde)
Location: fs/fuse/fuse_i.h:878
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/inode.c (ffffffff814f62fb)
Location: fs/fuse/fuse_i.h:878
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_iget
```
```
In fs/fuse/readdir.c (ffffffff814f8843)
Location: fs/fuse/fuse_i.h:878
Inline: True
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
In fs/fuse/dir.c (ffffffff8157973c)
Location: fs/fuse/fuse_i.h:899
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/inode.c (ffffffff815860ca)
Location: fs/fuse/fuse_i.h:899
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_iget
```
```
In fs/fuse/readdir.c (ffffffff815885b6)
Location: fs/fuse/fuse_i.h:899
Inline: True
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
In fs/fuse/dir.c (ffffffff8161edcc)
Location: fs/fuse/fuse_i.h:902
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/inode.c (ffffffff8162c33a)
Location: fs/fuse/fuse_i.h:902
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_iget
```
```
In fs/fuse/readdir.c (ffffffff8162ea76)
Location: fs/fuse/fuse_i.h:902
Inline: True
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
In fs/fuse/dir.c (ffffffff816571e5)
Location: fs/fuse/fuse_i.h:907
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/inode.c (ffffffff8166457a)
Location: fs/fuse/fuse_i.h:907
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_iget
```
```
In fs/fuse/readdir.c (ffffffff81666cd6)
Location: fs/fuse/fuse_i.h:907
Inline: True
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
In fs/fuse/dir.c (ffffffff81690e3b)
Location: fs/fuse/fuse_i.h:934
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/inode.c (ffffffff8169e78a)
Location: fs/fuse/fuse_i.h:934
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_iget
```
```
In fs/fuse/readdir.c (ffffffff816a0fe6)
Location: fs/fuse/fuse_i.h:934
Inline: True
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
