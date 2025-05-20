# Function: <code>inode_fsuid_set</code>

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
In fs/inode.c (ffffffff81346d81)
Location: include/linux/fs.h:1706
Inline: True
Inline callers:
  - fs/inode.c:inode_init_owner
```
```
In fs/ext4/ialloc.c (ffffffff8140678e)
Location: include/linux/fs.h:1706
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
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
In fs/inode.c (ffffffff813947e1)
Location: include/linux/fs.h:1756
Inline: True
Inline callers:
  - fs/inode.c:inode_init_owner
```
```
In fs/ext4/ialloc.c (ffffffff81459003)
Location: include/linux/fs.h:1756
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
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
In fs/inode.c (ffffffff81416925)
Location: include/linux/fs.h:1634
Inline: True
Inline callers:
  - fs/inode.c:inode_init_owner
```
```
In fs/ext4/ialloc.c (ffffffff814d719a)
Location: include/linux/fs.h:1634
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
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
In fs/inode.c (ffffffff814a1e25)
Location: include/linux/fs.h:1749
Inline: True
Inline callers:
  - fs/inode.c:inode_init_owner
```
```
In fs/ext4/ialloc.c (ffffffff8156ff22)
Location: include/linux/fs.h:1749
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
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
In fs/inode.c (ffffffff814d6f78)
Location: include/linux/fs.h:1429
Inline: True
Inline callers:
  - fs/inode.c:inode_init_owner
```
```
In fs/ext4/ialloc.c (ffffffff815a7dba)
Location: include/linux/fs.h:1429
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
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
In fs/inode.c (ffffffff815092f8)
Location: include/linux/fs.h:1474
Inline: True
Inline callers:
  - fs/inode.c:inode_init_owner
```
```
In fs/ext4/ialloc.c (ffffffff815e0bb1)
Location: include/linux/fs.h:1474
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
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
