# Function: <code>audit_inode_child</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812181b6)
Location: include/linux/audit.h:205
Inline: True
Inline callers:
  - fs/namei.c:may_delete
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
```
```
In fs/devpts/inode.c (ffffffff8128e537)
Location: include/linux/audit.h:205
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff8131dc29)
Location: include/linux/audit.h:205
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff8131f37d)
Location: include/linux/audit.h:205
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812416ab)
Location: include/linux/audit.h:308
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:may_delete
```
```
In fs/devpts/inode.c (ffffffff812bbac9)
Location: include/linux/audit.h:308
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff813526c9)
Location: include/linux/audit.h:308
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff8135483d)
Location: include/linux/audit.h:308
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81254552)
Location: include/linux/audit.h:308
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:may_delete
```
```
In fs/devpts/inode.c (ffffffff812d1111)
Location: include/linux/audit.h:308
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff8136897c)
Location: include/linux/audit.h:308
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff8136aafd)
Location: include/linux/audit.h:308
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812601ea)
Location: include/linux/audit.h:307
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:may_delete
```
```
In fs/devpts/inode.c (ffffffff812e2780)
Location: include/linux/audit.h:307
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff8137cf0b)
Location: include/linux/audit.h:307
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff8137f14d)
Location: include/linux/audit.h:307
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812828ca)
Location: include/linux/audit.h:299
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:may_delete
```
```
In fs/devpts/inode.c (ffffffff813071b0)
Location: include/linux/audit.h:299
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff813a1e1b)
Location: include/linux/audit.h:299
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff813a418d)
Location: include/linux/audit.h:299
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
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
In fs/namei.c (ffffffff812ab73f)
Location: include/linux/audit.h:309
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:may_delete
```
```
In fs/devpts/inode.c (ffffffff81335145)
Location: include/linux/audit.h:309
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff813d114b)
Location: include/linux/audit.h:309
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff813d356f)
Location: include/linux/audit.h:309
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
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
In fs/namei.c (ffffffff812be34f)
Location: include/linux/audit.h:308
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:may_delete
```
```
In fs/devpts/inode.c (ffffffff8134c3d5)
Location: include/linux/audit.h:308
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff813ebc10)
Location: include/linux/audit.h:308
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff813edc5f)
Location: include/linux/audit.h:308
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
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
In fs/namei.c (ffffffff812db04a)
Location: include/linux/audit.h:354
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:may_delete
```
```
In fs/devpts/inode.c (ffffffff81374d9f)
Location: include/linux/audit.h:354
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff81417cfe)
Location: include/linux/audit.h:354
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff81419eef)
Location: include/linux/audit.h:354
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
In fs/namei.c (ffffffff812ecb5a)
Location: include/linux/audit.h:347
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:may_delete
```
```
In fs/devpts/inode.c (ffffffff8138d01f)
Location: include/linux/audit.h:347
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff81431bbe)
Location: include/linux/audit.h:347
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff81433d3f)
Location: include/linux/audit.h:347
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
In fs/namei.c (ffffffff8132683f)
Location: include/linux/audit.h:364
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mknod
  - fs/namei.c:vfs_mknod
  - fs/namei.c:open_last_lookups
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:may_delete
```
```
In fs/devpts/inode.c (ffffffff813d846f)
Location: include/linux/audit.h:364
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff814814aa)
Location: include/linux/audit.h:364
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff81483a6b)
Location: include/linux/audit.h:364
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
In fs/namei.c (ffffffff81331cb0)
Location: include/linux/audit.h:381
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mknod
  - fs/namei.c:vfs_mknod
  - fs/namei.c:open_last_lookups
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:may_delete
```
```
In fs/devpts/inode.c (ffffffff813ea10e)
Location: include/linux/audit.h:381
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff8149ef73)
Location: include/linux/audit.h:381
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff814a10df)
Location: include/linux/audit.h:381
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
In fs/namei.c (ffffffff81335d7b)
Location: include/linux/audit.h:381
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mknod
  - fs/namei.c:vfs_mknod
  - fs/namei.c:open_last_lookups
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:may_delete
```
```
In fs/devpts/inode.c (ffffffff813f0c4e)
Location: include/linux/audit.h:381
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff814a4f53)
Location: include/linux/audit.h:381
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff814a720f)
Location: include/linux/audit.h:381
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
In fs/namei.c (ffffffff8138385b)
Location: include/linux/audit.h:381
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mknod
  - fs/namei.c:vfs_mknod
  - fs/namei.c:open_last_lookups
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:may_delete
```
```
In fs/devpts/inode.c (ffffffff81442b3e)
Location: include/linux/audit.h:381
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff814fd07c)
Location: include/linux/audit.h:381
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff814ff2bf)
Location: include/linux/audit.h:381
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
In fs/namei.c (ffffffff81404804)
Location: include/linux/audit.h:407
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mknod
  - fs/namei.c:open_last_lookups
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:may_delete
```
```
In fs/devpts/inode.c (ffffffff814be8da)
Location: include/linux/audit.h:407
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff8158d367)
Location: include/linux/audit.h:407
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff81590589)
Location: include/linux/audit.h:407
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
In fs/namei.c (ffffffff8148ec84)
Location: include/linux/audit.h:404
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mknod
  - fs/namei.c:open_last_lookups
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:may_delete
```
```
In fs/devpts/inode.c (ffffffff8155677a)
Location: include/linux/audit.h:404
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff81633e67)
Location: include/linux/audit.h:404
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff81637a09)
Location: include/linux/audit.h:404
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
In fs/namei.c (ffffffff814c3e16)
Location: include/linux/audit.h:403
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mknod
  - fs/namei.c:vfs_mknod
  - fs/namei.c:open_last_lookups
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:may_delete
```
```
In fs/devpts/inode.c (ffffffff8158e53a)
Location: include/linux/audit.h:403
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff8166c193)
Location: include/linux/audit.h:403
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff8166fe09)
Location: include/linux/audit.h:403
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
In fs/namei.c (ffffffff814f644a)
Location: include/linux/audit.h:402
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mknod
  - fs/namei.c:vfs_mknod
  - fs/namei.c:open_last_lookups
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:may_delete
```
```
In fs/devpts/inode.c (ffffffff815c7250)
Location: include/linux/audit.h:402
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff816a6633)
Location: include/linux/audit.h:402
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff816aaa1f)
Location: include/linux/audit.h:402
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
```
```
In fs/tracefs/event_inode.c (ffffffff816abf1f)
Location: include/linux/audit.h:402
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
In fs/namei.c (ffff80001039623c)
Location: include/linux/audit.h:347
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:may_delete
```
```
In fs/devpts/inode.c (ffff80001045ed08)
Location: include/linux/audit.h:347
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffff80001051691c)
Location: include/linux/audit.h:347
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffff800010519800)
Location: include/linux/audit.h:347
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
In fs/namei.c (c057b698)
Location: include/linux/audit.h:347
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:may_delete
```
```
In fs/devpts/inode.c (c061f754)
Location: include/linux/audit.h:347
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (c06d16d4)
Location: include/linux/audit.h:347
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (c06d3f0c)
Location: include/linux/audit.h:347
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
In fs/namei.c (c00000000048e490)
Location: include/linux/audit.h:347
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:may_delete
```
```
In fs/devpts/inode.c (c00000000057ae94)
Location: include/linux/audit.h:347
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (c00000000065f8e8)
Location: include/linux/audit.h:347
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (c000000000662e70)
Location: include/linux/audit.h:347
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
In fs/namei.c (ffffffe000264726)
Location: include/linux/audit.h:347
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:may_delete
```
```
In fs/devpts/inode.c (ffffffe0002ee87a)
Location: include/linux/audit.h:347
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffe000380022)
Location: include/linux/audit.h:347
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffe000382b1c)
Location: include/linux/audit.h:347
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
In fs/namei.c (ffffffff812e513a)
Location: include/linux/audit.h:347
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:may_delete
```
```
In fs/devpts/inode.c (ffffffff813855ff)
Location: include/linux/audit.h:347
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff8142a19e)
Location: include/linux/audit.h:347
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff8142c31f)
Location: include/linux/audit.h:347
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
In fs/namei.c (ffffffff812d5d7a)
Location: include/linux/audit.h:347
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:may_delete
```
```
In fs/devpts/inode.c (ffffffff8137608f)
Location: include/linux/audit.h:347
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff8141ac1e)
Location: include/linux/audit.h:347
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff8141cd9f)
Location: include/linux/audit.h:347
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
In fs/namei.c (ffffffff812e2f4a)
Location: include/linux/audit.h:347
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:may_delete
```
```
In fs/devpts/inode.c (ffffffff813830cf)
Location: include/linux/audit.h:347
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff8142633e)
Location: include/linux/audit.h:347
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff814284bf)
Location: include/linux/audit.h:347
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
In fs/namei.c (ffffffff812f2e88)
Location: include/linux/audit.h:347
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:vfs_mkobj
  - fs/namei.c:may_delete
```
```
In fs/devpts/inode.c (ffffffff81396bef)
Location: include/linux/audit.h:347
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff8143d1fe)
Location: include/linux/audit.h:347
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff8143f37f)
Location: include/linux/audit.h:347
Inline: True
Inline callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
```
</details>
</li>
</ul>

## Differences
