# Function: <code>kernfs_dentry_node</code>

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
In fs/kernfs/mount.c (ffffffff812fce66)
Location: fs/kernfs/kernfs-internal.h:73
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_get_parent_dentry
  - fs/kernfs/mount.c:kernfs_sop_show_path
  - fs/kernfs/mount.c:kernfs_sop_show_options
```
```
In fs/kernfs/inode.c (ffffffff812fd7ee)
Location: fs/kernfs/kernfs-internal.h:73
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_iop_listxattr
```
```
In fs/kernfs/dir.c (ffffffff812fe6a0)
Location: fs/kernfs/kernfs-internal.h:73
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_node_from_dentry
  - fs/kernfs/dir.c:kernfs_dop_revalidate
  - fs/kernfs/dir.c:kernfs_dop_revalidate
```
```
In fs/kernfs/file.c (ffffffff81300235)
Location: fs/kernfs/kernfs-internal.h:73
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff8132aa75)
Location: fs/kernfs/kernfs-internal.h:73
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_get_parent_dentry
  - fs/kernfs/mount.c:kernfs_sop_show_path
  - fs/kernfs/mount.c:kernfs_sop_show_options
```
```
In fs/kernfs/inode.c (ffffffff8132b305)
Location: fs/kernfs/kernfs-internal.h:73
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_iop_listxattr
```
```
In fs/kernfs/dir.c (ffffffff8132c8b0)
Location: fs/kernfs/kernfs-internal.h:73
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_node_from_dentry
  - fs/kernfs/dir.c:kernfs_dop_revalidate
  - fs/kernfs/dir.c:kernfs_dop_revalidate
```
```
In fs/kernfs/file.c (ffffffff8132df13)
Location: fs/kernfs/kernfs-internal.h:73
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_poll
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
In fs/kernfs/mount.c (ffffffff81341dd5)
Location: fs/kernfs/kernfs-internal.h:73
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_get_parent_dentry
  - fs/kernfs/mount.c:kernfs_sop_show_path
  - fs/kernfs/mount.c:kernfs_sop_show_options
```
```
In fs/kernfs/inode.c (ffffffff813424d5)
Location: fs/kernfs/kernfs-internal.h:73
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_iop_listxattr
```
```
In fs/kernfs/dir.c (ffffffff81343840)
Location: fs/kernfs/kernfs-internal.h:73
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_node_from_dentry
  - fs/kernfs/dir.c:kernfs_dop_revalidate
  - fs/kernfs/dir.c:kernfs_dop_revalidate
```
```
In fs/kernfs/file.c (ffffffff81345313)
Location: fs/kernfs/kernfs-internal.h:73
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_poll
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
In fs/kernfs/mount.c (ffffffff8136a1f5)
Location: fs/kernfs/kernfs-internal.h:75
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_get_parent_dentry
  - fs/kernfs/mount.c:kernfs_sop_show_path
  - fs/kernfs/mount.c:kernfs_sop_show_options
```
```
In fs/kernfs/inode.c (ffffffff8136a815)
Location: fs/kernfs/kernfs-internal.h:75
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_iop_listxattr
```
```
In fs/kernfs/dir.c (ffffffff8136bab0)
Location: fs/kernfs/kernfs-internal.h:75
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_node_from_dentry
  - fs/kernfs/dir.c:kernfs_dop_revalidate
  - fs/kernfs/dir.c:kernfs_dop_revalidate
```
```
In fs/kernfs/file.c (ffffffff8136e13d)
Location: fs/kernfs/kernfs-internal.h:75
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_poll
  - fs/kernfs/file.c:kernfs_generic_poll
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
In fs/kernfs/mount.c (ffffffff813823e5)
Location: fs/kernfs/kernfs-internal.h:75
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_get_parent_dentry
  - fs/kernfs/mount.c:kernfs_sop_show_path
  - fs/kernfs/mount.c:kernfs_sop_show_options
```
```
In fs/kernfs/inode.c (ffffffff813829f5)
Location: fs/kernfs/kernfs-internal.h:75
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_iop_listxattr
```
```
In fs/kernfs/dir.c (ffffffff81383c80)
Location: fs/kernfs/kernfs-internal.h:75
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_node_from_dentry
  - fs/kernfs/dir.c:kernfs_dop_revalidate
  - fs/kernfs/dir.c:kernfs_dop_revalidate
```
```
In fs/kernfs/file.c (ffffffff813862fd)
Location: fs/kernfs/kernfs-internal.h:75
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_poll
  - fs/kernfs/file.c:kernfs_generic_poll
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
In fs/kernfs/mount.c (ffffffff813ccae5)
Location: fs/kernfs/kernfs-internal.h:77
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_get_parent_dentry
  - fs/kernfs/mount.c:kernfs_sop_show_path
  - fs/kernfs/mount.c:kernfs_sop_show_options
```
```
In fs/kernfs/inode.c (ffffffff813cd125)
Location: fs/kernfs/kernfs-internal.h:77
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_iop_listxattr
```
```
In fs/kernfs/dir.c (ffffffff813ceaf0)
Location: fs/kernfs/kernfs-internal.h:77
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_node_from_dentry
  - fs/kernfs/dir.c:kernfs_dop_revalidate
  - fs/kernfs/dir.c:kernfs_dop_revalidate
```
```
In fs/kernfs/file.c (ffffffff813d0efd)
Location: fs/kernfs/kernfs-internal.h:77
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_poll
  - fs/kernfs/file.c:kernfs_generic_poll
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
In fs/kernfs/mount.c (ffffffff813de735)
Location: fs/kernfs/kernfs-internal.h:77
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_get_parent_dentry
  - fs/kernfs/mount.c:kernfs_sop_show_path
  - fs/kernfs/mount.c:kernfs_sop_show_options
```
```
In fs/kernfs/inode.c (ffffffff813ded55)
Location: fs/kernfs/kernfs-internal.h:77
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_iop_listxattr
```
```
In fs/kernfs/dir.c (ffffffff813e0720)
Location: fs/kernfs/kernfs-internal.h:77
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_node_from_dentry
  - fs/kernfs/dir.c:kernfs_dop_revalidate
  - fs/kernfs/dir.c:kernfs_dop_revalidate
```
```
In fs/kernfs/file.c (ffffffff813e2b0d)
Location: fs/kernfs/kernfs-internal.h:77
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_poll
  - fs/kernfs/file.c:kernfs_generic_poll
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
In fs/kernfs/mount.c (ffffffff813e5485)
Location: fs/kernfs/kernfs-internal.h:77
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_get_parent_dentry
  - fs/kernfs/mount.c:kernfs_sop_show_path
  - fs/kernfs/mount.c:kernfs_sop_show_options
```
```
In fs/kernfs/inode.c (ffffffff813e5a75)
Location: fs/kernfs/kernfs-internal.h:77
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_iop_listxattr
```
```
In fs/kernfs/dir.c (ffffffff813e7250)
Location: fs/kernfs/kernfs-internal.h:77
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_node_from_dentry
  - fs/kernfs/dir.c:kernfs_dop_revalidate
  - fs/kernfs/dir.c:kernfs_dop_revalidate
```
```
In fs/kernfs/file.c (ffffffff813e971d)
Location: fs/kernfs/kernfs-internal.h:77
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_poll
  - fs/kernfs/file.c:kernfs_generic_poll
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
In fs/kernfs/mount.c (ffffffff81437055)
Location: fs/kernfs/kernfs-internal.h:78
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_get_parent_dentry
  - fs/kernfs/mount.c:kernfs_sop_show_path
  - fs/kernfs/mount.c:kernfs_sop_show_options
```
```
In fs/kernfs/inode.c (ffffffff81437645)
Location: fs/kernfs/kernfs-internal.h:78
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_iop_listxattr
```
```
In fs/kernfs/dir.c (ffffffff81438dfd)
Location: fs/kernfs/kernfs-internal.h:78
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_dop_revalidate
  - fs/kernfs/dir.c:kernfs_dop_revalidate
  - fs/kernfs/dir.c:kernfs_dop_revalidate
  - fs/kernfs/dir.c:kernfs_node_from_dentry
```
```
In fs/kernfs/file.c (ffffffff8143b48d)
Location: fs/kernfs/kernfs-internal.h:78
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_poll
  - fs/kernfs/file.c:kernfs_generic_poll
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
In fs/kernfs/mount.c (ffffffff814b1c05)
Location: fs/kernfs/kernfs-internal.h:96
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_get_parent_dentry
  - fs/kernfs/mount.c:kernfs_sop_show_path
  - fs/kernfs/mount.c:kernfs_sop_show_options
```
```
In fs/kernfs/inode.c (ffffffff814b22c5)
Location: fs/kernfs/kernfs-internal.h:96
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_iop_listxattr
```
```
In fs/kernfs/dir.c (ffffffff814b3efd)
Location: fs/kernfs/kernfs-internal.h:96
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_dop_revalidate
  - fs/kernfs/dir.c:kernfs_dop_revalidate
  - fs/kernfs/dir.c:kernfs_dop_revalidate
  - fs/kernfs/dir.c:kernfs_node_from_dentry
```
```
In fs/kernfs/file.c (ffffffff814b671c)
Location: fs/kernfs/kernfs-internal.h:96
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_poll
  - fs/kernfs/file.c:kernfs_generic_poll
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
In fs/kernfs/mount.c (ffffffff815486c5)
Location: fs/kernfs/kernfs-internal.h:96
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_get_parent_dentry
  - fs/kernfs/mount.c:kernfs_sop_show_path
  - fs/kernfs/mount.c:kernfs_sop_show_options
```
```
In fs/kernfs/inode.c (ffffffff81548e45)
Location: fs/kernfs/kernfs-internal.h:96
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_iop_listxattr
```
```
In fs/kernfs/dir.c (ffffffff8154aced)
Location: fs/kernfs/kernfs-internal.h:96
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_dop_revalidate
  - fs/kernfs/dir.c:kernfs_dop_revalidate
  - fs/kernfs/dir.c:kernfs_dop_revalidate
  - fs/kernfs/dir.c:kernfs_node_from_dentry
```
```
In fs/kernfs/file.c (ffffffff8154d6fe)
Location: fs/kernfs/kernfs-internal.h:96
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_poll
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
In fs/kernfs/mount.c (ffffffff81580285)
Location: fs/kernfs/kernfs-internal.h:98
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_get_parent_dentry
  - fs/kernfs/mount.c:kernfs_sop_show_path
  - fs/kernfs/mount.c:kernfs_sop_show_options
```
```
In fs/kernfs/inode.c (ffffffff81580a15)
Location: fs/kernfs/kernfs-internal.h:98
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_iop_listxattr
```
```
In fs/kernfs/dir.c (ffffffff81582940)
Location: fs/kernfs/kernfs-internal.h:98
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_dop_revalidate
  - fs/kernfs/dir.c:kernfs_dop_revalidate
  - fs/kernfs/dir.c:kernfs_dop_revalidate
  - fs/kernfs/dir.c:kernfs_node_from_dentry
```
```
In fs/kernfs/file.c (ffffffff8158539e)
Location: fs/kernfs/kernfs-internal.h:98
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_poll
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
In fs/kernfs/mount.c (ffffffff815b8cc5)
Location: fs/kernfs/kernfs-internal.h:98
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_get_parent_dentry
  - fs/kernfs/mount.c:kernfs_sop_show_path
  - fs/kernfs/mount.c:kernfs_sop_show_options
```
```
In fs/kernfs/inode.c (ffffffff815b94a5)
Location: fs/kernfs/kernfs-internal.h:98
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_iop_listxattr
```
```
In fs/kernfs/dir.c (ffffffff815bb570)
Location: fs/kernfs/kernfs-internal.h:98
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_dop_revalidate
  - fs/kernfs/dir.c:kernfs_dop_revalidate
  - fs/kernfs/dir.c:kernfs_dop_revalidate
  - fs/kernfs/dir.c:kernfs_node_from_dentry
```
```
In fs/kernfs/file.c (ffffffff815bde4e)
Location: fs/kernfs/kernfs-internal.h:98
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_poll
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
In fs/kernfs/mount.c (ffff800010450770)
Location: fs/kernfs/kernfs-internal.h:75
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_get_parent_dentry
  - fs/kernfs/mount.c:kernfs_sop_show_path
  - fs/kernfs/mount.c:kernfs_sop_show_options
```
```
In fs/kernfs/inode.c (ffff800010450ec4)
Location: fs/kernfs/kernfs-internal.h:75
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_iop_listxattr
```
```
In fs/kernfs/dir.c (ffff800010452974)
Location: fs/kernfs/kernfs-internal.h:75
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_node_from_dentry
  - fs/kernfs/dir.c:kernfs_dop_revalidate
  - fs/kernfs/dir.c:kernfs_dop_revalidate
```
```
In fs/kernfs/file.c (ffff800010455c30)
Location: fs/kernfs/kernfs-internal.h:75
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_poll
  - fs/kernfs/file.c:kernfs_generic_poll
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
In fs/kernfs/mount.c (c06137b0)
Location: fs/kernfs/kernfs-internal.h:75
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_get_parent_dentry
  - fs/kernfs/mount.c:kernfs_sop_show_path
  - fs/kernfs/mount.c:kernfs_sop_show_options
```
```
In fs/kernfs/inode.c (c0613e70)
Location: fs/kernfs/kernfs-internal.h:75
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_iop_listxattr
```
```
In fs/kernfs/dir.c (c0615170)
Location: fs/kernfs/kernfs-internal.h:75
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_node_from_dentry
  - fs/kernfs/dir.c:kernfs_dop_revalidate
  - fs/kernfs/dir.c:kernfs_dop_revalidate
```
```
In fs/kernfs/file.c (c0617eb0)
Location: fs/kernfs/kernfs-internal.h:75
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_poll
  - fs/kernfs/file.c:kernfs_generic_poll
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
In fs/kernfs/mount.c (c00000000056890c)
Location: fs/kernfs/kernfs-internal.h:75
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_get_parent_dentry
  - fs/kernfs/mount.c:kernfs_sop_show_path
  - fs/kernfs/mount.c:kernfs_sop_show_options
```
```
In fs/kernfs/inode.c (c000000000569348)
Location: fs/kernfs/kernfs-internal.h:75
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_iop_listxattr
```
```
In fs/kernfs/dir.c (c00000000056afa4)
Location: fs/kernfs/kernfs-internal.h:75
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_node_from_dentry
  - fs/kernfs/dir.c:kernfs_dop_revalidate
  - fs/kernfs/dir.c:kernfs_dop_revalidate
```
```
In fs/kernfs/file.c (c00000000056f87c)
Location: fs/kernfs/kernfs-internal.h:75
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_poll
  - fs/kernfs/file.c:kernfs_generic_poll
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
In fs/kernfs/mount.c (ffffffe0002e3744)
Location: fs/kernfs/kernfs-internal.h:75
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_get_parent_dentry
  - fs/kernfs/mount.c:kernfs_sop_show_path
  - fs/kernfs/mount.c:kernfs_sop_show_options
```
```
In fs/kernfs/inode.c (ffffffe0002e3da6)
Location: fs/kernfs/kernfs-internal.h:75
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_iop_listxattr
```
```
In fs/kernfs/dir.c (ffffffe0002e5386)
Location: fs/kernfs/kernfs-internal.h:75
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_node_from_dentry
  - fs/kernfs/dir.c:kernfs_dop_revalidate
  - fs/kernfs/dir.c:kernfs_dop_revalidate
```
```
In fs/kernfs/file.c (ffffffe0002e76fe)
Location: fs/kernfs/kernfs-internal.h:75
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_poll
  - fs/kernfs/file.c:kernfs_generic_poll
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
In fs/kernfs/mount.c (ffffffff8137a9c5)
Location: fs/kernfs/kernfs-internal.h:75
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_get_parent_dentry
  - fs/kernfs/mount.c:kernfs_sop_show_path
  - fs/kernfs/mount.c:kernfs_sop_show_options
```
```
In fs/kernfs/inode.c (ffffffff8137afd5)
Location: fs/kernfs/kernfs-internal.h:75
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_iop_listxattr
```
```
In fs/kernfs/dir.c (ffffffff8137c260)
Location: fs/kernfs/kernfs-internal.h:75
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_node_from_dentry
  - fs/kernfs/dir.c:kernfs_dop_revalidate
  - fs/kernfs/dir.c:kernfs_dop_revalidate
```
```
In fs/kernfs/file.c (ffffffff8137e8dd)
Location: fs/kernfs/kernfs-internal.h:75
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_poll
  - fs/kernfs/file.c:kernfs_generic_poll
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
In fs/kernfs/mount.c (ffffffff8136b495)
Location: fs/kernfs/kernfs-internal.h:75
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_get_parent_dentry
  - fs/kernfs/mount.c:kernfs_sop_show_path
  - fs/kernfs/mount.c:kernfs_sop_show_options
```
```
In fs/kernfs/inode.c (ffffffff8136baa5)
Location: fs/kernfs/kernfs-internal.h:75
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_iop_listxattr
```
```
In fs/kernfs/dir.c (ffffffff8136cd30)
Location: fs/kernfs/kernfs-internal.h:75
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_node_from_dentry
  - fs/kernfs/dir.c:kernfs_dop_revalidate
  - fs/kernfs/dir.c:kernfs_dop_revalidate
```
```
In fs/kernfs/file.c (ffffffff8136f36d)
Location: fs/kernfs/kernfs-internal.h:75
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_poll
  - fs/kernfs/file.c:kernfs_generic_poll
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
In fs/kernfs/mount.c (ffffffff81378495)
Location: fs/kernfs/kernfs-internal.h:75
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_get_parent_dentry
  - fs/kernfs/mount.c:kernfs_sop_show_path
  - fs/kernfs/mount.c:kernfs_sop_show_options
```
```
In fs/kernfs/inode.c (ffffffff81378aa5)
Location: fs/kernfs/kernfs-internal.h:75
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_iop_listxattr
```
```
In fs/kernfs/dir.c (ffffffff81379d30)
Location: fs/kernfs/kernfs-internal.h:75
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_node_from_dentry
  - fs/kernfs/dir.c:kernfs_dop_revalidate
  - fs/kernfs/dir.c:kernfs_dop_revalidate
```
```
In fs/kernfs/file.c (ffffffff8137c3ad)
Location: fs/kernfs/kernfs-internal.h:75
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_poll
  - fs/kernfs/file.c:kernfs_generic_poll
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
In fs/kernfs/mount.c (ffffffff8138bf45)
Location: fs/kernfs/kernfs-internal.h:75
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_get_parent_dentry
  - fs/kernfs/mount.c:kernfs_sop_show_path
  - fs/kernfs/mount.c:kernfs_sop_show_options
```
```
In fs/kernfs/inode.c (ffffffff8138c555)
Location: fs/kernfs/kernfs-internal.h:75
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_iop_listxattr
```
```
In fs/kernfs/dir.c (ffffffff8138d670)
Location: fs/kernfs/kernfs-internal.h:75
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_fop_readdir
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_node_from_dentry
  - fs/kernfs/dir.c:kernfs_dop_revalidate
  - fs/kernfs/dir.c:kernfs_dop_revalidate
```
```
In fs/kernfs/file.c (ffffffff8138fe8d)
Location: fs/kernfs/kernfs-internal.h:75
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_poll
  - fs/kernfs/file.c:kernfs_generic_poll
```
</details>
</li>
</ul>

## Differences
