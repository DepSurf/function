# Function: <code>fsnotify_name</code>

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
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8132677b)
Location: include/linux/fsnotify.h:28
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mknod
  - fs/namei.c:open_last_lookups
  - fs/namei.c:vfs_mkobj
```
```
In fs/libfs.c (ffffffff81345f88)
Location: include/linux/fsnotify.h:28
Inline: True
Inline callers:
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
```
```
In fs/configfs/dir.c (ffffffff813d5b85)
Location: include/linux/fsnotify.h:28
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/devpts/inode.c (ffffffff813d85ba)
Location: include/linux/fsnotify.h:28
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff814814cf)
Location: include/linux/fsnotify.h:28
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff81483a90)
Location: include/linux/fsnotify.h:28
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
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
In fs/namei.c (ffffffff81331bec)
Location: include/linux/fsnotify.h:29
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mknod
  - fs/namei.c:open_last_lookups
  - fs/namei.c:vfs_mkobj
```
```
In fs/libfs.c (ffffffff81352455)
Location: include/linux/fsnotify.h:29
Inline: True
Inline callers:
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
```
```
In fs/configfs/dir.c (ffffffff813e7867)
Location: include/linux/fsnotify.h:29
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/devpts/inode.c (ffffffff813ea232)
Location: include/linux/fsnotify.h:29
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff8149efa6)
Location: include/linux/fsnotify.h:29
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff814a10fa)
Location: include/linux/fsnotify.h:29
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
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
In fs/namei.c (ffffffff81335cb3)
Location: include/linux/fsnotify.h:29
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mknod
  - fs/namei.c:open_last_lookups
  - fs/namei.c:vfs_mkobj
```
```
In fs/libfs.c (ffffffff81358e8e)
Location: include/linux/fsnotify.h:29
Inline: True
Inline callers:
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
```
```
In fs/configfs/dir.c (ffffffff813ee237)
Location: include/linux/fsnotify.h:29
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/devpts/inode.c (ffffffff813f0d72)
Location: include/linux/fsnotify.h:29
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff814a4f86)
Location: include/linux/fsnotify.h:29
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff814a722a)
Location: include/linux/fsnotify.h:29
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
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
In fs/namei.c (ffffffff813837af)
Location: include/linux/fsnotify.h:29
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mknod
  - fs/namei.c:vfs_mknod
  - fs/namei.c:open_last_lookups
  - fs/namei.c:open_last_lookups
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:vfs_mkobj
```
```
In fs/libfs.c (ffffffff813a7712)
Location: include/linux/fsnotify.h:29
Inline: True
Inline callers:
  - fs/libfs.c:simple_recursive_removal
```
```
In fs/configfs/dir.c (ffffffff8143fa81)
Location: include/linux/fsnotify.h:29
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/devpts/inode.c (ffffffff81442c9b)
Location: include/linux/fsnotify.h:29
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/devpts/inode.c:devpts_pty_new
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff814fd0af)
Location: include/linux/fsnotify.h:29
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff814ff2da)
Location: include/linux/fsnotify.h:29
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
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
In fs/namei.c (ffffffff81404725)
Location: include/linux/fsnotify.h:29
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mknod
  - fs/namei.c:vfs_mknod
  - fs/namei.c:open_last_lookups
  - fs/namei.c:open_last_lookups
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:vfs_mkobj
```
```
In fs/libfs.c (ffffffff8142c301)
Location: include/linux/fsnotify.h:29
Inline: True
Inline callers:
  - fs/libfs.c:simple_recursive_removal
```
```
In fs/configfs/dir.c (ffffffff814bbfe3)
Location: include/linux/fsnotify.h:29
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/devpts/inode.c (ffffffff814bea58)
Location: include/linux/fsnotify.h:29
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/devpts/inode.c:devpts_pty_new
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff8158d262)
Location: include/linux/fsnotify.h:29
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff815905a4)
Location: include/linux/fsnotify.h:29
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
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
In fs/namei.c (ffffffff8148eba5)
Location: include/linux/fsnotify.h:29
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mknod
  - fs/namei.c:vfs_mknod
  - fs/namei.c:open_last_lookups
  - fs/namei.c:open_last_lookups
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:vfs_mkobj
```
```
In fs/libfs.c (ffffffff814b9a11)
Location: include/linux/fsnotify.h:29
Inline: True
Inline callers:
  - fs/libfs.c:simple_recursive_removal
```
```
In fs/configfs/dir.c (ffffffff81553b0e)
Location: include/linux/fsnotify.h:29
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/devpts/inode.c (ffffffff81556918)
Location: include/linux/fsnotify.h:29
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/devpts/inode.c:devpts_pty_new
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff81633d62)
Location: include/linux/fsnotify.h:29
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff81637a24)
Location: include/linux/fsnotify.h:29
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
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
In fs/namei.c (ffffffff814c43d7)
Location: include/linux/fsnotify.h:29
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mknod
  - fs/namei.c:vfs_mknod
  - fs/namei.c:open_last_lookups
  - fs/namei.c:open_last_lookups
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:vfs_mkobj
```
```
In fs/libfs.c (ffffffff814ee9ba)
Location: include/linux/fsnotify.h:29
Inline: True
Inline callers:
  - fs/libfs.c:simple_recursive_removal
```
```
In fs/configfs/dir.c (ffffffff8158b89e)
Location: include/linux/fsnotify.h:29
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/devpts/inode.c (ffffffff8158e6d8)
Location: include/linux/fsnotify.h:29
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/devpts/inode.c:devpts_pty_new
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff8166c08b)
Location: include/linux/fsnotify.h:29
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff8166fe24)
Location: include/linux/fsnotify.h:29
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
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
In fs/namei.c (ffffffff814f635f)
Location: include/linux/fsnotify.h:29
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mknod
  - fs/namei.c:vfs_mknod
  - fs/namei.c:open_last_lookups
  - fs/namei.c:open_last_lookups
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:vfs_mkobj
```
```
In fs/libfs.c (ffffffff815229a8)
Location: include/linux/fsnotify.h:29
Inline: True
Inline callers:
  - fs/libfs.c:simple_recursive_removal
```
```
In fs/configfs/dir.c (ffffffff815c45d4)
Location: include/linux/fsnotify.h:29
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/devpts/inode.c (ffffffff815c73eb)
Location: include/linux/fsnotify.h:29
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/devpts/inode.c:devpts_pty_new
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff816a652b)
Location: include/linux/fsnotify.h:29
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff816aaa3e)
Location: include/linux/fsnotify.h:29
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
```
```
In fs/tracefs/event_inode.c (ffffffff816abf3a)
Location: include/linux/fsnotify.h:29
Inline: True
Inline callers:
  - fs/tracefs/event_inode.c:eventfs_create_events_dir
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
