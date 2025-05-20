# Function: <code>d_unlinked</code>

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
In fs/dcache.c (ffffffff81224512)
Location: include/linux/dcache.h:378
Inline: True
Inline callers:
  - fs/dcache.c:d_tmpfile
  - fs/dcache.c:d_path
  - fs/dcache.c:d_set_mounted
  - fs/dcache.c:dentry_path
  - fs/dcache.c:SyS_getcwd
```
```
In fs/namespace.c (ffffffff8122b5e7)
Location: include/linux/dcache.h:378
Inline: True
Inline callers:
  - fs/namespace.c:lookup_mountpoint
  - fs/namespace.c:SyS_pivot_root
```
```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff81251856)
Location: include/linux/dcache.h:378
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
```
```
In security/apparmor/path.c (ffffffff813798e1)
Location: include/linux/dcache.h:378
Inline: True
Inline callers:
  - security/apparmor/path.c:aa_path_name
```
```
In security/apparmor/file.c (ffffffff81387e44)
Location: include/linux/dcache.h:378
Inline: True
Inline callers:
  - security/apparmor/file.c:path_name
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
In fs/dcache.c (ffffffff8124b412)
Location: include/linux/dcache.h:336
Inline: True
Inline callers:
  - fs/dcache.c:d_tmpfile
  - fs/dcache.c:SyS_getcwd
  - fs/dcache.c:dentry_path
  - fs/dcache.c:d_path
  - fs/dcache.c:d_set_mounted
```
```
In fs/namespace.c (ffffffff81258697)
Location: include/linux/dcache.h:336
Inline: True
Inline callers:
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:lookup_mountpoint
```
```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff8127a06b)
Location: include/linux/dcache.h:336
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
```
```
In fs/debugfs/file.c (ffffffff81353a5a)
Location: include/linux/dcache.h:336
Inline: True
Inline callers:
  - fs/debugfs/file.c:read_file_blob
  - fs/debugfs/file.c:debugfs_write_file_bool
  - fs/debugfs/file.c:debugfs_read_file_bool
  - fs/debugfs/file.c:debugfs_attr_write
  - fs/debugfs/file.c:debugfs_attr_read
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:full_proxy_poll
  - fs/debugfs/file.c:full_proxy_unlocked_ioctl
  - fs/debugfs/file.c:full_proxy_write
  - fs/debugfs/file.c:full_proxy_read
  - fs/debugfs/file.c:full_proxy_llseek
  - fs/debugfs/file.c:open_proxy_open
```
```
In security/apparmor/path.c (ffffffff813b26aa)
Location: include/linux/dcache.h:336
Inline: True
Inline callers:
  - security/apparmor/path.c:aa_path_name
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
In fs/dcache.c (ffffffff8125e3f2)
Location: include/linux/dcache.h:336
Inline: True
Inline callers:
  - fs/dcache.c:d_tmpfile
  - fs/dcache.c:SyS_getcwd
  - fs/dcache.c:dentry_path
  - fs/dcache.c:d_path
  - fs/dcache.c:d_set_mounted
```
```
In fs/namespace.c (ffffffff8126bb28)
Location: include/linux/dcache.h:336
Inline: True
Inline callers:
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:lookup_mountpoint
```
```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff8128dc1b)
Location: include/linux/dcache.h:336
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
```
```
In fs/debugfs/file.c (ffffffff81369d0a)
Location: include/linux/dcache.h:336
Inline: True
Inline callers:
  - fs/debugfs/file.c:read_file_blob
  - fs/debugfs/file.c:debugfs_write_file_bool
  - fs/debugfs/file.c:debugfs_read_file_bool
  - fs/debugfs/file.c:debugfs_attr_write
  - fs/debugfs/file.c:debugfs_attr_read
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:full_proxy_poll
  - fs/debugfs/file.c:full_proxy_unlocked_ioctl
  - fs/debugfs/file.c:full_proxy_write
  - fs/debugfs/file.c:full_proxy_read
  - fs/debugfs/file.c:full_proxy_llseek
  - fs/debugfs/file.c:open_proxy_open
```
```
In security/apparmor/path.c (ffffffff813c986a)
Location: include/linux/dcache.h:336
Inline: True
Inline callers:
  - security/apparmor/path.c:aa_path_name
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
In fs/dcache.c (ffffffff8126bc52)
Location: include/linux/dcache.h:342
Inline: True
Inline callers:
  - fs/dcache.c:d_tmpfile
  - fs/dcache.c:SyS_getcwd
  - fs/dcache.c:dentry_path
  - fs/dcache.c:d_path
  - fs/dcache.c:d_set_mounted
```
```
In fs/namespace.c (ffffffff812792fa)
Location: include/linux/dcache.h:342
Inline: True
Inline callers:
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:lookup_mountpoint
```
```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff8129ab63)
Location: include/linux/dcache.h:342
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
```
```
In fs/debugfs/file.c (ffffffff8137e37a)
Location: include/linux/dcache.h:342
Inline: True
Inline callers:
  - fs/debugfs/file.c:read_file_blob
  - fs/debugfs/file.c:debugfs_write_file_bool
  - fs/debugfs/file.c:debugfs_read_file_bool
  - fs/debugfs/file.c:debugfs_attr_write
  - fs/debugfs/file.c:debugfs_attr_read
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:full_proxy_poll
  - fs/debugfs/file.c:full_proxy_unlocked_ioctl
  - fs/debugfs/file.c:full_proxy_write
  - fs/debugfs/file.c:full_proxy_read
  - fs/debugfs/file.c:full_proxy_llseek
  - fs/debugfs/file.c:open_proxy_open
```
```
In security/apparmor/path.c (ffffffff813def35)
Location: include/linux/dcache.h:342
Inline: True
Inline callers:
  - security/apparmor/path.c:aa_path_name
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
In fs/dcache.c (ffffffff8128e4e2)
Location: include/linux/dcache.h:343
Inline: True
Inline callers:
  - fs/dcache.c:d_tmpfile
  - fs/dcache.c:SyS_getcwd
  - fs/dcache.c:dentry_path
  - fs/dcache.c:d_path
  - fs/dcache.c:d_set_mounted
```
```
In fs/namespace.c (ffffffff8129bd3a)
Location: include/linux/dcache.h:343
Inline: True
Inline callers:
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:lookup_mountpoint
```
```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff812bdf73)
Location: include/linux/dcache.h:343
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
```
```
In fs/debugfs/file.c (ffffffff813a24ca)
Location: include/linux/dcache.h:343
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In security/apparmor/path.c (ffffffff814058d5)
Location: include/linux/dcache.h:343
Inline: True
Inline callers:
  - security/apparmor/path.c:aa_path_name
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
In fs/dcache.c (ffffffff812b4f8f)
Location: include/linux/dcache.h:344
Inline: True
Inline callers:
  - fs/dcache.c:d_tmpfile
  - fs/dcache.c:d_set_mounted
```
```
In fs/namespace.c (ffffffff812c1e6a)
Location: include/linux/dcache.h:344
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:lookup_mountpoint
```
```
In fs/d_path.c (ffffffff812d3d47)
Location: include/linux/dcache.h:344
Inline: True
Inline callers:
  - fs/d_path.c:__ia32_sys_getcwd
  - fs/d_path.c:__x64_sys_getcwd
  - fs/d_path.c:dentry_path
  - fs/d_path.c:d_path
```
```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff812e6c30)
Location: include/linux/dcache.h:344
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
```
```
In fs/debugfs/file.c (ffffffff813d18ca)
Location: include/linux/dcache.h:344
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In security/apparmor/path.c (ffffffff81436f5a)
Location: include/linux/dcache.h:344
Inline: True
Inline callers:
  - security/apparmor/path.c:aa_path_name
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
In fs/dcache.c (ffffffff812ca2af)
Location: include/linux/dcache.h:341
Inline: True
Inline callers:
  - fs/dcache.c:d_tmpfile
  - fs/dcache.c:d_set_mounted
```
```
In fs/namespace.c (ffffffff812d710a)
Location: include/linux/dcache.h:341
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:get_mountpoint
```
```
In fs/d_path.c (ffffffff812e8f97)
Location: include/linux/dcache.h:341
Inline: True
Inline callers:
  - fs/d_path.c:__ia32_sys_getcwd
  - fs/d_path.c:__x64_sys_getcwd
  - fs/d_path.c:dentry_path
  - fs/d_path.c:d_path
```
```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff812fb802)
Location: include/linux/dcache.h:341
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
```
```
In fs/debugfs/file.c (ffffffff813ebfca)
Location: include/linux/dcache.h:341
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In security/apparmor/path.c (ffffffff81453bba)
Location: include/linux/dcache.h:341
Inline: True
Inline callers:
  - security/apparmor/path.c:aa_path_name
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
In fs/dcache.c (ffffffff812e6d13)
Location: include/linux/dcache.h:339
Inline: True
Inline callers:
  - fs/dcache.c:d_tmpfile
  - fs/dcache.c:d_set_mounted
```
```
In fs/namespace.c (ffffffff812f556d)
Location: include/linux/dcache.h:339
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:get_mountpoint
```
```
In fs/d_path.c (ffffffff81307825)
Location: include/linux/dcache.h:339
Inline: True
Inline callers:
  - fs/d_path.c:__ia32_sys_getcwd
  - fs/d_path.c:__x64_sys_getcwd
  - fs/d_path.c:dentry_path
  - fs/d_path.c:d_path
```
```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff8131c152)
Location: include/linux/dcache.h:339
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
```
```
In fs/debugfs/file.c (ffffffff8141821b)
Location: include/linux/dcache.h:339
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In security/apparmor/path.c (ffffffff81481450)
Location: include/linux/dcache.h:339
Inline: True
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
In fs/dcache.c (ffffffff812f8913)
Location: include/linux/dcache.h:339
Inline: True
Inline callers:
  - fs/dcache.c:d_tmpfile
  - fs/dcache.c:d_set_mounted
```
```
In fs/namespace.c (ffffffff813070ed)
Location: include/linux/dcache.h:339
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:get_mountpoint
```
```
In fs/d_path.c (ffffffff8131a895)
Location: include/linux/dcache.h:339
Inline: True
Inline callers:
  - fs/d_path.c:__ia32_sys_getcwd
  - fs/d_path.c:__x64_sys_getcwd
  - fs/d_path.c:dentry_path
  - fs/d_path.c:d_path
```
```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff8132ef23)
Location: include/linux/dcache.h:339
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
```
```
In fs/debugfs/file.c (ffffffff814320db)
Location: include/linux/dcache.h:339
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In security/apparmor/path.c (ffffffff8149b180)
Location: include/linux/dcache.h:339
Inline: True
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
In fs/dcache.c (ffffffff81331783)
Location: include/linux/dcache.h:341
Inline: True
Inline callers:
  - fs/dcache.c:d_tmpfile
  - fs/dcache.c:d_set_mounted
```
```
In fs/namespace.c (ffffffff813408c7)
Location: include/linux/dcache.h:341
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:get_mountpoint
```
```
In fs/d_path.c (ffffffff813547c1)
Location: include/linux/dcache.h:341
Inline: True
Inline callers:
  - fs/d_path.c:__do_sys_getcwd
  - fs/d_path.c:dentry_path
  - fs/d_path.c:d_path
```
```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff81368cc2)
Location: include/linux/dcache.h:341
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
```
```
In fs/debugfs/file.c (ffffffff814824eb)
Location: include/linux/dcache.h:341
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In security/apparmor/path.c (ffffffff814f3bae)
Location: include/linux/dcache.h:341
Inline: True
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
In fs/dcache.c (ffffffff8133d123)
Location: include/linux/dcache.h:342
Inline: True
Inline callers:
  - fs/dcache.c:d_tmpfile
  - fs/dcache.c:d_set_mounted
```
```
In fs/namespace.c (ffffffff8134c957)
Location: include/linux/dcache.h:342
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:get_mountpoint
```
```
In fs/d_path.c (ffffffff813610cf)
Location: include/linux/dcache.h:342
Inline: True
Inline callers:
  - fs/d_path.c:__do_sys_getcwd
  - fs/d_path.c:dentry_path
  - fs/d_path.c:d_path
```
```
In fs/notify/fsnotify.c (ffffffff813731b5)
Location: include/linux/dcache.h:342
Inline: True
```
```
In fs/debugfs/file.c (ffffffff8149fb7b)
Location: include/linux/dcache.h:342
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In security/apparmor/path.c (ffffffff81510d0e)
Location: include/linux/dcache.h:342
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
In fs/dcache.c (ffffffff813435a3)
Location: include/linux/dcache.h:345
Inline: True
Inline callers:
  - fs/dcache.c:d_tmpfile
  - fs/dcache.c:d_set_mounted
```
```
In fs/namespace.c (ffffffff81353526)
Location: include/linux/dcache.h:345
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:get_mountpoint
```
```
In fs/d_path.c (ffffffff81367baf)
Location: include/linux/dcache.h:345
Inline: True
Inline callers:
  - fs/d_path.c:__do_sys_getcwd
  - fs/d_path.c:dentry_path
  - fs/d_path.c:d_path
```
```
In fs/notify/fsnotify.c (ffffffff81379a8c)
Location: include/linux/dcache.h:345
Inline: True
```
```
In fs/debugfs/file.c (ffffffff814a5b7b)
Location: include/linux/dcache.h:345
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In security/apparmor/path.c (ffffffff8151768e)
Location: include/linux/dcache.h:345
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
In mm/swapfile.c (ffffffff81316f29)
Location: include/linux/dcache.h:345
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In fs/dcache.c (ffffffff81391143)
Location: include/linux/dcache.h:345
Inline: True
Inline callers:
  - fs/dcache.c:d_tmpfile
  - fs/dcache.c:d_set_mounted
```
```
In fs/namespace.c (ffffffff813a1976)
Location: include/linux/dcache.h:345
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:get_mountpoint
```
```
In fs/d_path.c (ffffffff813b675e)
Location: include/linux/dcache.h:345
Inline: True
Inline callers:
  - fs/d_path.c:__do_sys_getcwd
  - fs/d_path.c:dentry_path
  - fs/d_path.c:d_path
```
```
In fs/notify/fsnotify.c (ffffffff813c65ec)
Location: include/linux/dcache.h:345
Inline: True
```
```
In fs/debugfs/file.c (ffffffff814fdd1b)
Location: include/linux/dcache.h:345
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In security/apparmor/path.c (ffffffff8157568e)
Location: include/linux/dcache.h:345
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
In mm/swapfile.c (ffffffff81382550)
Location: include/linux/dcache.h:335
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In fs/dcache.c (ffffffff814129bf)
Location: include/linux/dcache.h:335
Inline: True
Inline callers:
  - fs/dcache.c:d_tmpfile
  - fs/dcache.c:d_set_mounted
```
```
In fs/namespace.c (ffffffff81425382)
Location: include/linux/dcache.h:335
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:get_mountpoint
```
```
In fs/d_path.c (ffffffff8143bd54)
Location: include/linux/dcache.h:335
Inline: True
Inline callers:
  - fs/d_path.c:__do_sys_getcwd
  - fs/d_path.c:dentry_path
  - fs/d_path.c:d_path
```
```
In fs/notify/fsnotify.c (ffffffff8144d5aa)
Location: include/linux/dcache.h:335
Inline: True
```
```
In fs/debugfs/file.c (ffffffff8158e90b)
Location: include/linux/dcache.h:335
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In security/apparmor/path.c (ffffffff8161317e)
Location: include/linux/dcache.h:335
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
In mm/swapfile.c (ffffffff813fc4b1)
Location: include/linux/dcache.h:338
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In fs/dcache.c (ffffffff8149dd50)
Location: include/linux/dcache.h:338
Inline: True
Inline callers:
  - fs/dcache.c:d_tmpfile
  - fs/dcache.c:d_set_mounted
```
```
In fs/namespace.c (ffffffff814b1b02)
Location: include/linux/dcache.h:338
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:get_mountpoint
```
```
In fs/d_path.c (ffffffff814ca384)
Location: include/linux/dcache.h:338
Inline: True
Inline callers:
  - fs/d_path.c:__do_sys_getcwd
  - fs/d_path.c:dentry_path
  - fs/d_path.c:d_path
```
```
In fs/notify/fsnotify.c (ffffffff814dbbaa)
Location: include/linux/dcache.h:338
Inline: True
```
```
In fs/debugfs/file.c (ffffffff8163599b)
Location: include/linux/dcache.h:338
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In security/apparmor/path.c (ffffffff816c5dce)
Location: include/linux/dcache.h:338
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
In mm/swapfile.c (ffffffff8142f7c4)
Location: include/linux/dcache.h:338
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In fs/dcache.c (ffffffff814d3073)
Location: include/linux/dcache.h:338
Inline: True
Inline callers:
  - fs/dcache.c:d_tmpfile
  - fs/dcache.c:d_set_mounted
```
```
In fs/namespace.c (ffffffff814e6b51)
Location: include/linux/dcache.h:338
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:get_mountpoint
```
```
In fs/d_path.c (ffffffff815005c4)
Location: include/linux/dcache.h:338
Inline: True
Inline callers:
  - fs/d_path.c:__do_sys_getcwd
  - fs/d_path.c:dentry_path
  - fs/d_path.c:d_path
```
```
In fs/notify/fsnotify.c (ffffffff8151239a)
Location: include/linux/dcache.h:338
Inline: True
```
```
In fs/debugfs/file.c (ffffffff8166dcab)
Location: include/linux/dcache.h:338
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In security/apparmor/path.c (ffffffff816febae)
Location: include/linux/dcache.h:338
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
In mm/swapfile.c (ffffffff81469399)
Location: include/linux/dcache.h:345
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
```
In fs/dcache.c (ffffffff815042ab)
Location: include/linux/dcache.h:345
Inline: True
Inline callers:
  - fs/dcache.c:d_mark_tmpfile
  - fs/dcache.c:d_set_mounted
```
```
In fs/namespace.c (ffffffff8151a991)
Location: include/linux/dcache.h:345
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:get_mountpoint
```
```
In fs/d_path.c (ffffffff815351e4)
Location: include/linux/dcache.h:345
Inline: True
Inline callers:
  - fs/d_path.c:__do_sys_getcwd
  - fs/d_path.c:dentry_path
  - fs/d_path.c:d_path
```
```
In fs/notify/fsnotify.c (ffffffff8154684a)
Location: include/linux/dcache.h:345
Inline: True
```
```
In fs/debugfs/file.c (ffffffff816a7551)
Location: include/linux/dcache.h:345
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_enter_cancellation
  - fs/debugfs/file.c:debugfs_file_get
```
```
In security/apparmor/path.c (ffffffff8173c13e)
Location: include/linux/dcache.h:345
Inline: True
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
In fs/dcache.c (ffff8000103a7054)
Location: include/linux/dcache.h:339
Inline: True
Inline callers:
  - fs/dcache.c:d_tmpfile
  - fs/dcache.c:d_set_mounted
```
```
In fs/namespace.c (ffff8000103ba90c)
Location: include/linux/dcache.h:339
Inline: True
Inline callers:
  - fs/namespace.c:__arm64_sys_pivot_root
  - fs/namespace.c:get_mountpoint
```
```
In fs/d_path.c (ffff8000103d1e0c)
Location: include/linux/dcache.h:339
Inline: True
Inline callers:
  - fs/d_path.c:__arm64_sys_getcwd
  - fs/d_path.c:dentry_path
  - fs/d_path.c:d_path
```
```
In fs/notify/inotify/inotify_fsnotify.c (ffff8000103eba7c)
Location: include/linux/dcache.h:339
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
```
```
In fs/debugfs/file.c (ffff800010516fd8)
Location: include/linux/dcache.h:339
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In security/apparmor/path.c (ffff8000105914b0)
Location: include/linux/dcache.h:339
Inline: True
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
In fs/dcache.c (c05885f4)
Location: include/linux/dcache.h:339
Inline: True
Inline callers:
  - fs/dcache.c:d_tmpfile
  - fs/dcache.c:d_set_mounted
```
```
In fs/namespace.c (c05986b4)
Location: include/linux/dcache.h:339
Inline: True
Inline callers:
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:get_mountpoint
```
```
In fs/d_path.c (c05acf08)
Location: include/linux/dcache.h:339
Inline: True
Inline callers:
  - fs/d_path.c:__se_sys_getcwd
  - fs/d_path.c:dentry_path
  - fs/d_path.c:d_path
```
```
In fs/notify/inotify/inotify_fsnotify.c (c05c2948)
Location: include/linux/dcache.h:339
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
```
```
In fs/debugfs/file.c (c06d2d5c)
Location: include/linux/dcache.h:339
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In security/apparmor/path.c (c07420b8)
Location: include/linux/dcache.h:339
Inline: True
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
In fs/dcache.c (c0000000004a1604)
Location: include/linux/dcache.h:339
Inline: True
Inline callers:
  - fs/dcache.c:d_tmpfile
  - fs/dcache.c:d_set_mounted
```
```
In fs/namespace.c (c0000000004b818c)
Location: include/linux/dcache.h:339
Inline: True
Inline callers:
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:get_mountpoint
```
```
In fs/d_path.c (c0000000004d46d8)
Location: include/linux/dcache.h:339
Inline: True
Inline callers:
  - fs/d_path.c:__se_sys_getcwd
  - fs/d_path.c:dentry_path
  - fs/d_path.c:d_path
```
```
In fs/notify/inotify/inotify_fsnotify.c (c0000000004f2efc)
Location: include/linux/dcache.h:339
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
```
```
In fs/debugfs/file.c (c00000000065ff1c)
Location: include/linux/dcache.h:339
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In security/apparmor/path.c (c000000000704fe0)
Location: include/linux/dcache.h:339
Inline: True
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
In fs/dcache.c (ffffffe00026d128)
Location: include/linux/dcache.h:339
Inline: True
Inline callers:
  - fs/dcache.c:d_tmpfile
  - fs/dcache.c:d_set_mounted
```
```
In fs/namespace.c (ffffffe00027cd80)
Location: include/linux/dcache.h:339
Inline: True
Inline callers:
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:get_mountpoint
```
```
In fs/d_path.c (ffffffe00028d73a)
Location: include/linux/dcache.h:339
Inline: True
Inline callers:
  - fs/d_path.c:__se_sys_getcwd
  - fs/d_path.c:dentry_path
  - fs/d_path.c:d_path
```
```
In fs/notify/inotify/inotify_fsnotify.c (ffffffe00029fcba)
Location: include/linux/dcache.h:339
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
```
```
In fs/debugfs/file.c (ffffffe0003805d2)
Location: include/linux/dcache.h:339
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In security/apparmor/path.c (ffffffe0003dee3a)
Location: include/linux/dcache.h:339
Inline: True
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
In fs/dcache.c (ffffffff812f0ef3)
Location: include/linux/dcache.h:339
Inline: True
Inline callers:
  - fs/dcache.c:d_tmpfile
  - fs/dcache.c:d_set_mounted
```
```
In fs/namespace.c (ffffffff812ff6cd)
Location: include/linux/dcache.h:339
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:get_mountpoint
```
```
In fs/d_path.c (ffffffff81312e75)
Location: include/linux/dcache.h:339
Inline: True
Inline callers:
  - fs/d_path.c:__ia32_sys_getcwd
  - fs/d_path.c:__x64_sys_getcwd
  - fs/d_path.c:dentry_path
  - fs/d_path.c:d_path
```
```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff81327503)
Location: include/linux/dcache.h:339
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
```
```
In fs/debugfs/file.c (ffffffff8142a6bb)
Location: include/linux/dcache.h:339
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In security/apparmor/path.c (ffffffff81493760)
Location: include/linux/dcache.h:339
Inline: True
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
In fs/dcache.c (ffffffff812e1b23)
Location: include/linux/dcache.h:339
Inline: True
Inline callers:
  - fs/dcache.c:d_tmpfile
  - fs/dcache.c:d_set_mounted
```
```
In fs/namespace.c (ffffffff812f02ed)
Location: include/linux/dcache.h:339
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:get_mountpoint
```
```
In fs/d_path.c (ffffffff81303a85)
Location: include/linux/dcache.h:339
Inline: True
Inline callers:
  - fs/d_path.c:__ia32_sys_getcwd
  - fs/d_path.c:__x64_sys_getcwd
  - fs/d_path.c:dentry_path
  - fs/d_path.c:d_path
```
```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff813180a3)
Location: include/linux/dcache.h:339
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
```
```
In fs/debugfs/file.c (ffffffff8141b13b)
Location: include/linux/dcache.h:339
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In security/apparmor/path.c (ffffffff81484180)
Location: include/linux/dcache.h:339
Inline: True
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
In fs/dcache.c (ffffffff812eed03)
Location: include/linux/dcache.h:339
Inline: True
Inline callers:
  - fs/dcache.c:d_tmpfile
  - fs/dcache.c:d_set_mounted
```
```
In fs/namespace.c (ffffffff812fd4bd)
Location: include/linux/dcache.h:339
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:get_mountpoint
```
```
In fs/d_path.c (ffffffff81310c65)
Location: include/linux/dcache.h:339
Inline: True
Inline callers:
  - fs/d_path.c:__ia32_sys_getcwd
  - fs/d_path.c:__x64_sys_getcwd
  - fs/d_path.c:dentry_path
  - fs/d_path.c:d_path
```
```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff81324fd3)
Location: include/linux/dcache.h:339
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
```
```
In fs/debugfs/file.c (ffffffff8142685b)
Location: include/linux/dcache.h:339
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In security/apparmor/path.c (ffffffff8148f800)
Location: include/linux/dcache.h:339
Inline: True
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
In fs/dcache.c (ffffffff812ffe63)
Location: include/linux/dcache.h:339
Inline: True
Inline callers:
  - fs/dcache.c:d_tmpfile
  - fs/dcache.c:d_set_mounted
```
```
In fs/namespace.c (ffffffff8130e81b)
Location: include/linux/dcache.h:339
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:get_mountpoint
```
```
In fs/d_path.c (ffffffff8132249a)
Location: include/linux/dcache.h:339
Inline: True
Inline callers:
  - fs/d_path.c:__ia32_sys_getcwd
  - fs/d_path.c:__x64_sys_getcwd
  - fs/d_path.c:dentry_path
  - fs/d_path.c:d_path
```
```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff81336db3)
Location: include/linux/dcache.h:339
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
```
```
In fs/debugfs/file.c (ffffffff8143d71b)
Location: include/linux/dcache.h:339
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In security/apparmor/path.c (ffffffff814a7710)
Location: include/linux/dcache.h:339
Inline: True
```
</details>
</li>
</ul>

## Differences
