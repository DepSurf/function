# Function: <code>inode_set_ctime</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81509e55)
Location: include/linux/fs.h:1615
Inline: True
Inline callers:
  - fs/inode.c:inode_update_timestamps
```
```
In fs/ext4/xattr.c (ffffffff8163ee30)
Location: include/linux/fs.h:1615
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_create
  - fs/ext4/xattr.c:ext4_xattr_inode_update_ref
  - fs/ext4/xattr.c:ext4_xattr_inode_iget
```
```
In fs/squashfs/inode.c (ffffffff81660ca4)
Location: include/linux/fs.h:1615
Inline: True
Inline callers:
  - fs/squashfs/inode.c:squashfs_read_inode
```
```
In fs/fat/inode.c (ffffffff81674b02)
Location: include/linux/fs.h:1615
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
```
```
In fs/fuse/inode.c (ffffffff8169b9ff)
Location: include/linux/fs.h:1615
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_init_inode
  - fs/fuse/inode.c:fuse_change_attributes_common
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
