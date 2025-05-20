# Function: <code>fsnotify_inode</code>

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
In kernel/trace/trace.c (ffffffff811b9083)
Location: include/linux/fsnotify.h:42
Inline: True
Inline callers:
  - kernel/trace/trace.c:latency_fsnotify_workfn
```
```
In fs/namei.c (ffffffff81331c4a)
Location: include/linux/fsnotify.h:42
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
```
```
In fs/dcache.c (ffffffff8133d006)
Location: include/linux/fsnotify.h:42
Inline: True
Inline callers:
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/notify/fsnotify.c (ffffffff813737da)
Location: include/linux/fsnotify.h:42
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_unmount_inodes
```
```
In fs/kernfs/file.c (ffffffff813e2902)
Location: include/linux/fsnotify.h:42
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_notify_workfn
```
```
In fs/debugfs/inode.c (ffffffff8149e99f)
Location: include/linux/fsnotify.h:42
Inline: True
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
In kernel/trace/trace.c (ffffffff811b9933)
Location: include/linux/fsnotify.h:42
Inline: True
Inline callers:
  - kernel/trace/trace.c:latency_fsnotify_workfn
```
```
In fs/namei.c (ffffffff81335d23)
Location: include/linux/fsnotify.h:42
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
```
```
In fs/dcache.c (ffffffff81343486)
Location: include/linux/fsnotify.h:42
Inline: True
Inline callers:
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/notify/fsnotify.c (ffffffff8137a13a)
Location: include/linux/fsnotify.h:42
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_unmount_inodes
```
```
In fs/kernfs/file.c (ffffffff813e9512)
Location: include/linux/fsnotify.h:42
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_notify_workfn
```
```
In fs/debugfs/inode.c (ffffffff814a497c)
Location: include/linux/fsnotify.h:42
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
In kernel/trace/trace.c (ffffffff811e4118)
Location: include/linux/fsnotify.h:45
Inline: True
Inline callers:
  - kernel/trace/trace.c:latency_fsnotify_workfn
```
```
In fs/namei.c (ffffffff8138381a)
Location: include/linux/fsnotify.h:45
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
```
```
In fs/dcache.c (ffffffff81390dc6)
Location: include/linux/fsnotify.h:45
Inline: True
Inline callers:
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/notify/fsnotify.c (ffffffff813c6dea)
Location: include/linux/fsnotify.h:45
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
```
```
In fs/kernfs/file.c (ffffffff8143b272)
Location: include/linux/fsnotify.h:45
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_notify_workfn
```
```
In fs/debugfs/inode.c (ffffffff814fcb10)
Location: include/linux/fsnotify.h:45
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
In kernel/trace/trace.c (ffffffff8121b388)
Location: include/linux/fsnotify.h:45
Inline: True
Inline callers:
  - kernel/trace/trace.c:latency_fsnotify_workfn
```
```
In fs/namei.c (ffffffff814047c3)
Location: include/linux/fsnotify.h:45
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
```
```
In fs/dcache.c (ffffffff81412061)
Location: include/linux/fsnotify.h:45
Inline: True
Inline callers:
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/notify/fsnotify.c (ffffffff8144e121)
Location: include/linux/fsnotify.h:45
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
```
```
In fs/kernfs/file.c (ffffffff814b5c9c)
Location: include/linux/fsnotify.h:45
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_notify_workfn
```
```
In fs/debugfs/inode.c (ffffffff8158d326)
Location: include/linux/fsnotify.h:45
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_rename
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
In kernel/trace/trace.c (ffffffff81264eb8)
Location: include/linux/fsnotify.h:45
Inline: True
Inline callers:
  - kernel/trace/trace.c:latency_fsnotify_workfn
```
```
In fs/namei.c (ffffffff8148ec43)
Location: include/linux/fsnotify.h:45
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
```
```
In fs/dcache.c (ffffffff8149ce41)
Location: include/linux/fsnotify.h:45
Inline: True
Inline callers:
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/notify/fsnotify.c (ffffffff814dc811)
Location: include/linux/fsnotify.h:45
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
```
```
In fs/kernfs/file.c (ffffffff8154ce2c)
Location: include/linux/fsnotify.h:45
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_notify_workfn
```
```
In fs/debugfs/inode.c (ffffffff81633e26)
Location: include/linux/fsnotify.h:45
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_rename
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
In kernel/trace/trace.c (ffffffff8127bf78)
Location: include/linux/fsnotify.h:45
Inline: True
Inline callers:
  - kernel/trace/trace.c:latency_fsnotify_workfn
```
```
In fs/namei.c (ffffffff814c4480)
Location: include/linux/fsnotify.h:45
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
```
```
In fs/dcache.c (ffffffff814d2261)
Location: include/linux/fsnotify.h:45
Inline: True
Inline callers:
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/notify/fsnotify.c (ffffffff81513061)
Location: include/linux/fsnotify.h:45
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
```
```
In fs/kernfs/file.c (ffffffff81584aff)
Location: include/linux/fsnotify.h:45
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_notify_workfn
```
```
In fs/debugfs/inode.c (ffffffff8166c152)
Location: include/linux/fsnotify.h:45
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_rename
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
In kernel/trace/trace.c (ffffffff81296c68)
Location: include/linux/fsnotify.h:45
Inline: True
Inline callers:
  - kernel/trace/trace.c:latency_fsnotify_workfn
```
```
In fs/namei.c (ffffffff814f6409)
Location: include/linux/fsnotify.h:45
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
```
```
In fs/dcache.c (ffffffff81504ca1)
Location: include/linux/fsnotify.h:45
Inline: True
Inline callers:
  - fs/dcache.c:dentry_unlink_inode
```
```
In fs/notify/fsnotify.c (ffffffff81547511)
Location: include/linux/fsnotify.h:45
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
```
```
In fs/kernfs/file.c (ffffffff815bd54f)
Location: include/linux/fsnotify.h:45
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_notify_workfn
```
```
In fs/debugfs/inode.c (ffffffff816a65f2)
Location: include/linux/fsnotify.h:45
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_rename
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
