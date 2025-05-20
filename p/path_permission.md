# Function: <code>path_permission</code>

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
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int path_permission(const struct path *path, int mask);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff81218db0)
Location: include/linux/fs.h:3013
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_obj_get_user
```
```
In fs/open.c (ffffffff8131fcc7)
Location: include/linux/fs.h:3013
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__x64_sys_chroot
  - fs/open.c:__ia32_sys_chdir
  - fs/open.c:__x64_sys_chdir
```
```
In fs/init.c (ffffffff81bdca11)
Location: include/linux/fs.h:3013
Inline: False
Direct callers:
  - fs/init.c:init_eaccess
  - fs/init.c:init_chroot
  - fs/init.c:init_chdir
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8137d02c)
Location: include/linux/fs.h:3013
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_find_inode
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8137f7c6)
Location: include/linux/fs.h:3013
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
```
```
In net/unix/af_unix.c (ffffffff81b22151)
Location: include/linux/fs.h:3013
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_find_other
```
**Symbols:**

```
ffffffff81bdca11-ffffffff81bdca2d: path_permission (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int path_permission(const struct path *path, int mask);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff8124f4c0)
Location: include/linux/fs.h:2996
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_obj_get_user
```
```
In fs/open.c (ffffffff8136d267)
Location: include/linux/fs.h:2996
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__x64_sys_chroot
  - fs/open.c:__ia32_sys_chdir
  - fs/open.c:__x64_sys_chdir
```
```
In fs/init.c (ffffffff81cc42f3)
Location: include/linux/fs.h:2996
Inline: False
Direct callers:
  - fs/init.c:init_eaccess
  - fs/init.c:init_chroot
  - fs/init.c:init_chdir
```
```
In fs/notify/inotify/inotify_user.c (ffffffff813c9edc)
Location: include/linux/fs.h:2996
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_find_inode
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff813cc783)
Location: include/linux/fs.h:2996
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
```
```
In net/unix/af_unix.c (ffffffff81be7480)
Location: include/linux/fs.h:2996
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_find_other
```
**Symbols:**

```
ffffffff81cc42f3-ffffffff81cc430f: path_permission (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int path_permission(const struct path *path, int mask);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff8129661c)
Location: include/linux/fs.h:2762
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_obj_get_user
```
```
In fs/open.c (ffffffff813eb62e)
Location: include/linux/fs.h:2762
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__x64_sys_chroot
  - fs/open.c:__ia32_sys_chdir
  - fs/open.c:__x64_sys_chdir
```
```
In fs/init.c (ffffffff81e76bf9)
Location: include/linux/fs.h:2762
Inline: False
Direct callers:
  - fs/init.c:init_eaccess
  - fs/init.c:init_chroot
  - fs/init.c:init_chdir
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81451f88)
Location: include/linux/fs.h:2762
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_find_inode
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff81454f57)
Location: include/linux/fs.h:2762
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
```
```
In net/unix/af_unix.c (ffffffff81d80c07)
Location: include/linux/fs.h:2762
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_find_other
```
**Symbols:**

```
ffffffff81e76bf9-ffffffff81e76c1f: path_permission (STB_LOCAL)
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
In kernel/bpf/inode.c (ffffffff812f152d)
Location: include/linux/fs.h:2916
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_obj_get_user
```
```
In fs/open.c (ffffffff8147399e)
Location: include/linux/fs.h:2916
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__x64_sys_chroot
  - fs/open.c:__ia32_sys_chdir
  - fs/open.c:__x64_sys_chdir
```
```
In fs/init.c (ffffffff83ec9a21)
Location: include/linux/fs.h:2916
Inline: True
Inline callers:
  - fs/init.c:init_eaccess
  - fs/init.c:init_chroot
  - fs/init.c:init_chdir
```
```
In fs/notify/inotify/inotify_user.c (ffffffff814e0d19)
Location: include/linux/fs.h:2916
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_find_inode
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff814e3ea3)
Location: include/linux/fs.h:2916
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
```
```
In net/unix/af_unix.c (ffffffff81f4e791)
Location: include/linux/fs.h:2916
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_find_other
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
In kernel/bpf/inode.c (ffffffff8131e12d)
Location: include/linux/fs.h:2530
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_obj_get_user
```
```
In fs/open.c (ffffffff814a819e)
Location: include/linux/fs.h:2530
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__x64_sys_chroot
  - fs/open.c:__ia32_sys_chdir
  - fs/open.c:__x64_sys_chdir
```
```
In fs/init.c (ffffffff836eea71)
Location: include/linux/fs.h:2530
Inline: True
Inline callers:
  - fs/init.c:init_eaccess
  - fs/init.c:init_chroot
  - fs/init.c:init_chdir
```
```
In fs/notify/inotify/inotify_user.c (ffffffff815175c8)
Location: include/linux/fs.h:2530
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_find_inode
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8151a897)
Location: include/linux/fs.h:2530
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
```
```
In net/unix/af_unix.c (ffffffff81fae046)
Location: include/linux/fs.h:2530
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_find_other
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
In kernel/bpf/inode.c (ffffffff8134054d)
Location: include/linux/fs.h:2765
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_obj_get_user
```
```
In fs/open.c (ffffffff814d922e)
Location: include/linux/fs.h:2765
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__x64_sys_chroot
  - fs/open.c:__ia32_sys_chdir
  - fs/open.c:__x64_sys_chdir
```
```
In fs/init.c (ffffffff83921ac1)
Location: include/linux/fs.h:2765
Inline: True
Inline callers:
  - fs/init.c:init_eaccess
  - fs/init.c:init_chroot
  - fs/init.c:init_chdir
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8154b9a8)
Location: include/linux/fs.h:2765
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_find_inode
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8154ee97)
Location: include/linux/fs.h:2765
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
```
```
In net/unix/af_unix.c (ffffffff8207a916)
Location: include/linux/fs.h:2765
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_find_other
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
<b>Regular</b>
<ul>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
