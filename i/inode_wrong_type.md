# Function: <code>inode_wrong_type</code>

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
In fs/fuse/dir.c (ffffffff814957d2)
Location: include/linux/fs.h:3026
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/inode.c (ffffffff8149e453)
Location: include/linux/fs.h:3026
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_iget
```
```
In fs/fuse/readdir.c (ffffffff814a0a63)
Location: include/linux/fs.h:3026
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
In fs/fuse/dir.c (ffffffff814ed26c)
Location: include/linux/fs.h:3009
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/inode.c (ffffffff814f6303)
Location: include/linux/fs.h:3009
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_iget
```
```
In fs/fuse/readdir.c (ffffffff814f8933)
Location: include/linux/fs.h:3009
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
In fs/fuse/dir.c (ffffffff8157c0e6)
Location: include/linux/fs.h:2775
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/inode.c (ffffffff81586106)
Location: include/linux/fs.h:2775
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_iget
```
```
In fs/fuse/readdir.c (ffffffff81588726)
Location: include/linux/fs.h:2775
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
In fs/fuse/dir.c (ffffffff81621af6)
Location: include/linux/fs.h:2929
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/inode.c (ffffffff8162c376)
Location: include/linux/fs.h:2929
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_iget
```
```
In fs/fuse/readdir.c (ffffffff8162ebe6)
Location: include/linux/fs.h:2929
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
In fs/fuse/dir.c (ffffffff81659f4c)
Location: include/linux/fs.h:2543
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/inode.c (ffffffff816645b6)
Location: include/linux/fs.h:2543
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_iget
```
```
In fs/fuse/readdir.c (ffffffff81666e46)
Location: include/linux/fs.h:2543
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
In fs/fuse/dir.c (ffffffff81693bcc)
Location: include/linux/fs.h:2778
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_do_statx
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In fs/fuse/inode.c (ffffffff8169e7c6)
Location: include/linux/fs.h:2778
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_iget
```
```
In fs/fuse/readdir.c (ffffffff816a115b)
Location: include/linux/fs.h:2778
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
