# Function: <code>fsnotify_dirent</code>

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
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812da901)
Location: include/linux/fsnotify.h:26
Inline: True
Inline callers:
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
```
```
In fs/configfs/dir.c (ffffffff813721b4)
Location: include/linux/fsnotify.h:26
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/devpts/inode.c (ffffffff81374ec2)
Location: include/linux/fsnotify.h:26
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff81417d19)
Location: include/linux/fsnotify.h:26
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff81419f0a)
Location: include/linux/fsnotify.h:26
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
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
In fs/namei.c (ffffffff812ec411)
Location: include/linux/fsnotify.h:26
Inline: True
Inline callers:
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
```
```
In fs/configfs/dir.c (ffffffff8138a7c4)
Location: include/linux/fsnotify.h:26
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/devpts/inode.c (ffffffff8138d142)
Location: include/linux/fsnotify.h:26
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff81431bd9)
Location: include/linux/fsnotify.h:26
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff81433d5a)
Location: include/linux/fsnotify.h:26
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
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
In fs/namei.c (ffffffff81325a68)
Location: include/linux/fsnotify.h:41
Inline: True
Inline callers:
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mknod
  - fs/namei.c:open_last_lookups
  - fs/namei.c:vfs_mkobj
```
```
In fs/libfs.c (ffffffff81345f84)
Location: include/linux/fsnotify.h:41
Inline: True
Inline callers:
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
```
```
In fs/configfs/dir.c (ffffffff813d5b7b)
Location: include/linux/fsnotify.h:41
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/devpts/inode.c (ffffffff813d85b5)
Location: include/linux/fsnotify.h:41
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff814814c5)
Location: include/linux/fsnotify.h:41
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff81483a86)
Location: include/linux/fsnotify.h:41
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
In fs/namei.c (ffffffff8132faa2)
Location: include/linux/fsnotify.h:36
Inline: True
Inline callers:
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mknod
  - fs/namei.c:open_last_lookups
  - fs/namei.c:vfs_mkobj
```
```
In fs/libfs.c (ffffffff81352455)
Location: include/linux/fsnotify.h:36
Inline: True
Inline callers:
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
```
```
In fs/configfs/dir.c (ffffffff813e7867)
Location: include/linux/fsnotify.h:36
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/devpts/inode.c (ffffffff813ea232)
Location: include/linux/fsnotify.h:36
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff8149efa6)
Location: include/linux/fsnotify.h:36
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff814a10fa)
Location: include/linux/fsnotify.h:36
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
In fs/namei.c (ffffffff81335802)
Location: include/linux/fsnotify.h:36
Inline: True
Inline callers:
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mknod
  - fs/namei.c:open_last_lookups
  - fs/namei.c:vfs_mkobj
```
```
In fs/libfs.c (ffffffff81358e8e)
Location: include/linux/fsnotify.h:36
Inline: True
Inline callers:
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:simple_recursive_removal
```
```
In fs/configfs/dir.c (ffffffff813ee237)
Location: include/linux/fsnotify.h:36
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/devpts/inode.c (ffffffff813f0d72)
Location: include/linux/fsnotify.h:36
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff814a4f86)
Location: include/linux/fsnotify.h:36
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff814a722a)
Location: include/linux/fsnotify.h:36
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
In fs/namei.c (ffffffff81384b58)
Location: include/linux/fsnotify.h:39
Inline: True
Inline callers:
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mknod
  - fs/namei.c:open_last_lookups
  - fs/namei.c:vfs_mkobj
```
```
In fs/devpts/inode.c (ffffffff81442b71)
Location: include/linux/fsnotify.h:39
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff814fd0af)
Location: include/linux/fsnotify.h:39
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff814ff2da)
Location: include/linux/fsnotify.h:39
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
In fs/namei.c (ffffffff814023a2)
Location: include/linux/fsnotify.h:39
Inline: True
Inline callers:
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mknod
  - fs/namei.c:open_last_lookups
  - fs/namei.c:vfs_mkobj
```
```
In fs/devpts/inode.c (ffffffff814be905)
Location: include/linux/fsnotify.h:39
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff8158d8f8)
Location: include/linux/fsnotify.h:39
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff815905a4)
Location: include/linux/fsnotify.h:39
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
In fs/namei.c (ffffffff8148c62e)
Location: include/linux/fsnotify.h:39
Inline: True
Inline callers:
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mknod
  - fs/namei.c:open_last_lookups
  - fs/namei.c:vfs_mkobj
```
```
In fs/devpts/inode.c (ffffffff815567a5)
Location: include/linux/fsnotify.h:39
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff816347f8)
Location: include/linux/fsnotify.h:39
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff81637a24)
Location: include/linux/fsnotify.h:39
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
In fs/namei.c (ffffffff814c2fc8)
Location: include/linux/fsnotify.h:39
Inline: True
Inline callers:
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mknod
  - fs/namei.c:open_last_lookups
  - fs/namei.c:vfs_mkobj
```
```
In fs/devpts/inode.c (ffffffff8158e565)
Location: include/linux/fsnotify.h:39
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff8166cb08)
Location: include/linux/fsnotify.h:39
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff8166fe24)
Location: include/linux/fsnotify.h:39
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
In fs/namei.c (ffffffff814f548e)
Location: include/linux/fsnotify.h:39
Inline: True
Inline callers:
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mknod
  - fs/namei.c:open_last_lookups
  - fs/namei.c:vfs_mkobj
```
```
In fs/devpts/inode.c (ffffffff815c727b)
Location: include/linux/fsnotify.h:39
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff816a7098)
Location: include/linux/fsnotify.h:39
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff816aaa3e)
Location: include/linux/fsnotify.h:39
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
```
```
In fs/tracefs/event_inode.c (ffffffff816abf3a)
Location: include/linux/fsnotify.h:39
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
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffff800010395c00)
Location: include/linux/fsnotify.h:26
Inline: True
Inline callers:
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
```
```
In fs/configfs/dir.c (ffff80001045ade8)
Location: include/linux/fsnotify.h:26
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/devpts/inode.c (ffff80001045ee54)
Location: include/linux/fsnotify.h:26
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffff800010516928)
Location: include/linux/fsnotify.h:26
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffff80001051980c)
Location: include/linux/fsnotify.h:26
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
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
In fs/namei.c (c057aff4)
Location: include/linux/fsnotify.h:26
Inline: True
Inline callers:
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
```
```
In fs/configfs/dir.c (c061c9a0)
Location: include/linux/fsnotify.h:26
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/devpts/inode.c (c061f86c)
Location: include/linux/fsnotify.h:26
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (c06d16fc)
Location: include/linux/fsnotify.h:26
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (c06d3f34)
Location: include/linux/fsnotify.h:26
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
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
In fs/namei.c (c00000000048dff0)
Location: include/linux/fsnotify.h:26
Inline: True
Inline callers:
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
```
```
In fs/configfs/dir.c (c000000000576840)
Location: include/linux/fsnotify.h:26
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/devpts/inode.c (c00000000057b01c)
Location: include/linux/fsnotify.h:26
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (c00000000065f8fc)
Location: include/linux/fsnotify.h:26
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (c000000000662e84)
Location: include/linux/fsnotify.h:26
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
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
In fs/namei.c (ffffffe00026430c)
Location: include/linux/fsnotify.h:26
Inline: True
Inline callers:
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
```
```
In fs/configfs/dir.c (ffffffe0002eb6fa)
Location: include/linux/fsnotify.h:26
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/devpts/inode.c (ffffffe0002ee962)
Location: include/linux/fsnotify.h:26
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffe00038002e)
Location: include/linux/fsnotify.h:26
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffe000382b28)
Location: include/linux/fsnotify.h:26
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
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
In fs/namei.c (ffffffff812e49f1)
Location: include/linux/fsnotify.h:26
Inline: True
Inline callers:
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
```
```
In fs/configfs/dir.c (ffffffff81382da4)
Location: include/linux/fsnotify.h:26
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/devpts/inode.c (ffffffff81385722)
Location: include/linux/fsnotify.h:26
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff8142a1b9)
Location: include/linux/fsnotify.h:26
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff8142c33a)
Location: include/linux/fsnotify.h:26
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
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
In fs/namei.c (ffffffff812d5631)
Location: include/linux/fsnotify.h:26
Inline: True
Inline callers:
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
```
```
In fs/configfs/dir.c (ffffffff81373834)
Location: include/linux/fsnotify.h:26
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/devpts/inode.c (ffffffff813761b2)
Location: include/linux/fsnotify.h:26
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff8141ac39)
Location: include/linux/fsnotify.h:26
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff8141cdba)
Location: include/linux/fsnotify.h:26
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
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
In fs/namei.c (ffffffff812e2801)
Location: include/linux/fsnotify.h:26
Inline: True
Inline callers:
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
```
```
In fs/configfs/dir.c (ffffffff81380874)
Location: include/linux/fsnotify.h:26
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/devpts/inode.c (ffffffff813831f2)
Location: include/linux/fsnotify.h:26
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff81426359)
Location: include/linux/fsnotify.h:26
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff814284da)
Location: include/linux/fsnotify.h:26
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
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
In fs/namei.c (ffffffff812f238f)
Location: include/linux/fsnotify.h:26
Inline: True
Inline callers:
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
```
```
In fs/configfs/dir.c (ffffffff81394330)
Location: include/linux/fsnotify.h:26
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/devpts/inode.c (ffffffff81396d12)
Location: include/linux/fsnotify.h:26
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff8143d219)
Location: include/linux/fsnotify.h:26
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff8143f39a)
Location: include/linux/fsnotify.h:26
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
```
</details>
</li>
</ul>

## Differences
