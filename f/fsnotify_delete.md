# Function: <code>fsnotify_delete</code>

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
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81386043)
Location: include/linux/fsnotify.h:223
Inline: True
Inline callers:
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
```
```
In fs/libfs.c (ffffffff813a76fa)
Location: include/linux/fsnotify.h:223
Inline: True
Inline callers:
  - fs/libfs.c:simple_recursive_removal
```
```
In fs/configfs/dir.c (ffffffff8143fa69)
Location: include/linux/fsnotify.h:223
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/devpts/inode.c (ffffffff81442c83)
Location: include/linux/fsnotify.h:223
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_kill
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
In fs/namei.c (ffffffff81403aa8)
Location: include/linux/fsnotify.h:235
Inline: True
Inline callers:
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
```
```
In fs/libfs.c (ffffffff8142c2e9)
Location: include/linux/fsnotify.h:235
Inline: True
Inline callers:
  - fs/libfs.c:simple_recursive_removal
```
```
In fs/configfs/dir.c (ffffffff814bbfcb)
Location: include/linux/fsnotify.h:235
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/devpts/inode.c (ffffffff814bea40)
Location: include/linux/fsnotify.h:235
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_kill
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
In fs/namei.c (ffffffff8148def8)
Location: include/linux/fsnotify.h:235
Inline: True
Inline callers:
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
```
```
In fs/libfs.c (ffffffff814b99f9)
Location: include/linux/fsnotify.h:235
Inline: True
Inline callers:
  - fs/libfs.c:simple_recursive_removal
```
```
In fs/configfs/dir.c (ffffffff81553af6)
Location: include/linux/fsnotify.h:235
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/devpts/inode.c (ffffffff81556900)
Location: include/linux/fsnotify.h:235
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_kill
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
In fs/namei.c (ffffffff814c2558)
Location: include/linux/fsnotify.h:237
Inline: True
Inline callers:
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
```
```
In fs/libfs.c (ffffffff814ee9a2)
Location: include/linux/fsnotify.h:237
Inline: True
Inline callers:
  - fs/libfs.c:simple_recursive_removal
```
```
In fs/configfs/dir.c (ffffffff8158b886)
Location: include/linux/fsnotify.h:237
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/devpts/inode.c (ffffffff8158e6c0)
Location: include/linux/fsnotify.h:237
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_kill
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
In fs/namei.c (ffffffff814f4a18)
Location: include/linux/fsnotify.h:275
Inline: True
Inline callers:
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
```
```
In fs/libfs.c (ffffffff81522990)
Location: include/linux/fsnotify.h:275
Inline: True
Inline callers:
  - fs/libfs.c:simple_recursive_removal
```
```
In fs/configfs/dir.c (ffffffff815c45bc)
Location: include/linux/fsnotify.h:275
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/devpts/inode.c (ffffffff815c73d3)
Location: include/linux/fsnotify.h:275
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_kill
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
