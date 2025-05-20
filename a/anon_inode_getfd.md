# Function: <code>anon_inode_getfd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int anon_inode_getfd(const char *name, const struct file_operations *fops, void *priv, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/anon_inodes.c (ffffffff81256f50)
Location: fs/anon_inodes.c:139
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:SyS_bpf
  - fs/notify/inotify/inotify_user.c:sys_inotify_init
  - fs/notify/fanotify/fanotify_user.c:SyS_fanotify_init
  - fs/signalfd.c:SyS_signalfd
  - fs/signalfd.c:compat_SyS_signalfd
  - fs/timerfd.c:SyS_timerfd_create
```
**Symbols:**

```
ffffffff81256f50-ffffffff81256fc6: anon_inode_getfd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int anon_inode_getfd(const char *name, const struct file_operations *fops, void *priv, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/anon_inodes.c (ffffffff8127f8a0)
Location: fs/anon_inodes.c:139
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:bpf_prog_load
  - fs/notify/inotify/inotify_user.c:sys_inotify_init
  - fs/notify/fanotify/fanotify_user.c:SyS_fanotify_init
  - fs/signalfd.c:compat_SyS_signalfd
  - fs/signalfd.c:SyS_signalfd
  - fs/timerfd.c:SyS_timerfd_create
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:linehandle_create
```
**Symbols:**

```
ffffffff8127f8a0-ffffffff8127f916: anon_inode_getfd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int anon_inode_getfd(const char *name, const struct file_operations *fops, void *priv, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/anon_inodes.c (ffffffff81293410)
Location: fs/anon_inodes.c:139
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:bpf_prog_load
  - fs/notify/inotify/inotify_user.c:sys_inotify_init
  - fs/notify/fanotify/fanotify_user.c:SyS_fanotify_init
  - fs/signalfd.c:compat_SyS_signalfd
  - fs/signalfd.c:SyS_signalfd
  - fs/timerfd.c:SyS_timerfd_create
```
**Symbols:**

```
ffffffff81293410-ffffffff81293486: anon_inode_getfd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int anon_inode_getfd(const char *name, const struct file_operations *fops, void *priv, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/anon_inodes.c (ffffffff812a06b0)
Location: fs/anon_inodes.c:139
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:bpf_prog_load
  - fs/notify/inotify/inotify_user.c:sys_inotify_init
  - fs/notify/fanotify/fanotify_user.c:SyS_fanotify_init
  - fs/signalfd.c:compat_SyS_signalfd
  - fs/signalfd.c:SyS_signalfd
  - fs/timerfd.c:SyS_timerfd_create
```
**Symbols:**

```
ffffffff812a06b0-ffffffff812a0714: anon_inode_getfd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int anon_inode_getfd(const char *name, const struct file_operations *fops, void *priv, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/anon_inodes.c (ffffffff812c3a80)
Location: fs/anon_inodes.c:139
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:sys_inotify_init
  - fs/notify/fanotify/fanotify_user.c:SyS_fanotify_init
  - fs/signalfd.c:compat_SyS_signalfd
  - fs/signalfd.c:SyS_signalfd
  - fs/timerfd.c:SyS_timerfd_create
```
**Symbols:**

```
ffffffff812c3a80-ffffffff812c3ae4: anon_inode_getfd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int anon_inode_getfd(const char *name, const struct file_operations *fops, void *priv, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/anon_inodes.c (ffffffff812ecd00)
Location: fs/anon_inodes.c:139
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_get_fd_by_id
  - kernel/bpf/btf.c:btf_new_fd
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init
  - fs/timerfd.c:__ia32_sys_timerfd_create
  - fs/timerfd.c:__x64_sys_timerfd_create
  - fs/eventfd.c:do_eventfd
  - fs/userfaultfd.c:__ia32_sys_userfaultfd
  - fs/userfaultfd.c:__x64_sys_userfaultfd
  - fs/userfaultfd.c:userfaultfd_read
```
**Symbols:**

```
ffffffff812ecd00-ffffffff812ecd6f: anon_inode_getfd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int anon_inode_getfd(const char *name, const struct file_operations *fops, void *priv, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/anon_inodes.c (ffffffff81301690)
Location: fs/anon_inodes.c:121
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_get_fd_by_id
  - kernel/bpf/btf.c:btf_new_fd
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init
  - fs/timerfd.c:__ia32_sys_timerfd_create
  - fs/timerfd.c:__x64_sys_timerfd_create
  - fs/eventfd.c:do_eventfd
  - fs/userfaultfd.c:__ia32_sys_userfaultfd
  - fs/userfaultfd.c:__x64_sys_userfaultfd
  - fs/userfaultfd.c:userfaultfd_read
```
**Symbols:**

```
ffffffff81301690-ffffffff813016ff: anon_inode_getfd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int anon_inode_getfd(const char *name, const struct file_operations *fops, void *priv, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/anon_inodes.c (ffffffff81322c00)
Location: fs/anon_inodes.c:125
Inline: False
Direct callers:
  - kernel/pid.c:pidfd_create
  - kernel/bpf/btf.c:btf_get_fd_by_id
  - kernel/bpf/btf.c:btf_new_fd
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init
  - fs/timerfd.c:__ia32_sys_timerfd_create
  - fs/timerfd.c:__x64_sys_timerfd_create
  - fs/eventfd.c:do_eventfd
  - fs/userfaultfd.c:__ia32_sys_userfaultfd
  - fs/userfaultfd.c:__x64_sys_userfaultfd
  - fs/userfaultfd.c:userfaultfd_read
```
**Symbols:**

```
ffffffff81322c00-ffffffff81322c68: anon_inode_getfd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int anon_inode_getfd(const char *name, const struct file_operations *fops, void *priv, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/anon_inodes.c (ffffffff81335960)
Location: fs/anon_inodes.c:125
Inline: False
Direct callers:
  - kernel/pid.c:pidfd_create
  - kernel/bpf/btf.c:btf_get_fd_by_id
  - kernel/bpf/btf.c:btf_new_fd
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init
  - fs/timerfd.c:__ia32_sys_timerfd_create
  - fs/timerfd.c:__x64_sys_timerfd_create
  - fs/eventfd.c:do_eventfd
  - fs/userfaultfd.c:__ia32_sys_userfaultfd
  - fs/userfaultfd.c:__x64_sys_userfaultfd
  - fs/userfaultfd.c:userfaultfd_read
```
**Symbols:**

```
ffffffff81335960-ffffffff813359c8: anon_inode_getfd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int anon_inode_getfd(const char *name, const struct file_operations *fops, void *priv, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/anon_inodes.c (ffffffff8136f530)
Location: fs/anon_inodes.c:125
Inline: False
Direct callers:
  - kernel/pid.c:__ia32_sys_pidfd_open
  - kernel/pid.c:__x64_sys_pidfd_open
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_enable_stats
  - kernel/bpf/syscall.c:bpf_link_get_fd_by_id
  - kernel/bpf/syscall.c:bpf_map_get_fd_by_id
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/btf.c:btf_get_fd_by_id
  - kernel/bpf/btf.c:btf_new_fd
  - fs/fsopen.c:__do_sys_fspick
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - fs/notify/inotify/inotify_user.c:__do_sys_inotify_init
  - fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init
  - fs/signalfd.c:do_signalfd4
  - fs/timerfd.c:__do_sys_timerfd_create
  - fs/userfaultfd.c:__do_sys_userfaultfd
  - fs/userfaultfd.c:userfaultfd_ctx_read
```
**Symbols:**

```
ffffffff8136f530-ffffffff8136f598: anon_inode_getfd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int anon_inode_getfd(const char *name, const struct file_operations *fops, void *priv, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/anon_inodes.c (ffffffff8137d290)
Location: fs/anon_inodes.c:125
Inline: False
Direct callers:
  - kernel/pid.c:pidfd_create
  - kernel/pid.c:pidfd_create
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_enable_stats
  - kernel/bpf/syscall.c:bpf_map_get_fd_by_id
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/btf.c:btf_get_fd_by_id
  - kernel/bpf/btf.c:btf_new_fd
  - fs/fsopen.c:__do_sys_fspick
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - fs/notify/inotify/inotify_user.c:__do_sys_inotify_init
  - fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init
  - fs/signalfd.c:do_signalfd4
  - fs/timerfd.c:__do_sys_timerfd_create
  - fs/userfaultfd.c:__do_sys_userfaultfd
  - fs/userfaultfd.c:userfaultfd_ctx_read
```
**Symbols:**

```
ffffffff8137d290-ffffffff8137d2f8: anon_inode_getfd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int anon_inode_getfd(const char *name, const struct file_operations *fops, void *priv, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/anon_inodes.c (ffffffff81383e20)
Location: fs/anon_inodes.c:197
Inline: False
Direct callers:
  - kernel/pid.c:pidfd_create
  - kernel/pid.c:pidfd_create
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/btf.c:btf_get_fd_by_id
  - kernel/bpf/btf.c:btf_new_fd
  - fs/fsopen.c:__do_sys_fspick
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init
  - fs/signalfd.c:do_signalfd4
  - fs/timerfd.c:__do_sys_timerfd_create
  - security/landlock/syscalls.c:__ia32_sys_landlock_create_ruleset
  - security/landlock/syscalls.c:__x64_sys_landlock_create_ruleset
```
**Symbols:**

```
ffffffff81383e20-ffffffff81383e8e: anon_inode_getfd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int anon_inode_getfd(const char *name, const struct file_operations *fops, void *priv, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/anon_inodes.c (ffffffff813d10c0)
Location: fs/anon_inodes.c:197
Inline: False
Direct callers:
  - kernel/pid.c:pidfd_create
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/btf.c:bpf_btf_find_by_name_kind
  - kernel/bpf/btf.c:btf_get_fd_by_id
  - kernel/bpf/btf.c:btf_new_fd
  - fs/fsopen.c:__do_sys_fspick
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init
  - fs/signalfd.c:do_signalfd4
  - fs/timerfd.c:__do_sys_timerfd_create
  - security/landlock/syscalls.c:__ia32_sys_landlock_create_ruleset
  - security/landlock/syscalls.c:__x64_sys_landlock_create_ruleset
```
**Symbols:**

```
ffffffff813d10c0-ffffffff813d112e: anon_inode_getfd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int anon_inode_getfd(const char *name, const struct file_operations *fops, void *priv, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/anon_inodes.c (ffffffff8145a2d0)
Location: fs/anon_inodes.c:226
Inline: False
Direct callers:
  - kernel/pid.c:pidfd_create
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/btf.c:bpf_btf_find_by_name_kind
  - kernel/bpf/btf.c:btf_get_fd_by_id
  - kernel/bpf/btf.c:btf_new_fd
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init
  - fs/signalfd.c:do_signalfd4
  - fs/timerfd.c:__do_sys_timerfd_create
  - security/landlock/syscalls.c:__ia32_sys_landlock_create_ruleset
  - security/landlock/syscalls.c:__x64_sys_landlock_create_ruleset
```
**Symbols:**

```
ffffffff8145a2d0-ffffffff8145a34c: anon_inode_getfd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int anon_inode_getfd(const char *name, const struct file_operations *fops, void *priv, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/anon_inodes.c (ffffffff814e9790)
Location: fs/anon_inodes.c:226
Inline: False
Direct callers:
  - kernel/pid.c:pidfd_create
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/btf.c:bpf_btf_find_by_name_kind
  - kernel/bpf/btf.c:btf_get_fd_by_id
  - kernel/bpf/btf.c:btf_new_fd
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init
  - fs/signalfd.c:do_signalfd4
  - fs/timerfd.c:__do_sys_timerfd_create
  - security/landlock/syscalls.c:__ia32_sys_landlock_create_ruleset
  - security/landlock/syscalls.c:__x64_sys_landlock_create_ruleset
```
**Symbols:**

```
ffffffff814e9790-ffffffff814e980c: anon_inode_getfd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int anon_inode_getfd(const char *name, const struct file_operations *fops, void *priv, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/anon_inodes.c (ffffffff81520530)
Location: fs/anon_inodes.c:226
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:bpf_map_get_fd_by_id
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/btf.c:bpf_btf_find_by_name_kind
  - kernel/bpf/btf.c:btf_get_fd_by_id
  - kernel/bpf/btf.c:btf_new_fd
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init
  - fs/signalfd.c:do_signalfd4
  - fs/timerfd.c:__do_sys_timerfd_create
  - security/landlock/syscalls.c:__ia32_sys_landlock_create_ruleset
  - security/landlock/syscalls.c:__x64_sys_landlock_create_ruleset
```
**Symbols:**

```
ffffffff81520530-ffffffff815205ac: anon_inode_getfd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int anon_inode_getfd(const char *name, const struct file_operations *fops, void *priv, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/anon_inodes.c (ffffffff81554b80)
Location: fs/anon_inodes.c:234
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:bpf_map_get_fd_by_id
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/btf.c:bpf_btf_find_by_name_kind
  - kernel/bpf/btf.c:btf_get_fd_by_id
  - kernel/bpf/btf.c:btf_new_fd
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init
  - fs/signalfd.c:do_signalfd4
  - fs/timerfd.c:__do_sys_timerfd_create
  - security/landlock/syscalls.c:__do_sys_landlock_create_ruleset
```
**Symbols:**

```
ffffffff81554b80-ffffffff81554bfc: anon_inode_getfd (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int anon_inode_getfd(const char *name, const struct file_operations *fops, void *priv, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/anon_inodes.c (ffff8000103f3330)
Location: fs/anon_inodes.c:125
Inline: False
Direct callers:
  - virt/kvm/kvm_main.c:kvm_vm_ioctl
  - virt/kvm/kvm_main.c:kvm_vm_ioctl
  - kernel/pid.c:__arm64_sys_pidfd_open
  - kernel/bpf/btf.c:btf_get_fd_by_id
  - kernel/bpf/btf.c:btf_new_fd
  - fs/fsopen.c:__arm64_sys_fspick
  - fs/fsopen.c:__arm64_sys_fsopen
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/fanotify/fanotify_user.c:__arm64_sys_fanotify_init
  - fs/timerfd.c:__arm64_sys_timerfd_create
  - fs/eventfd.c:do_eventfd
  - fs/userfaultfd.c:__arm64_sys_userfaultfd
  - fs/userfaultfd.c:userfaultfd_read
```
**Symbols:**

```
ffff8000103f3330-ffff8000103f33b8: anon_inode_getfd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int anon_inode_getfd(const char *name, const struct file_operations *fops, void *priv, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/anon_inodes.c (c05c876c)
Location: fs/anon_inodes.c:125
Inline: False
Direct callers:
  - kernel/pid.c:__se_sys_pidfd_open
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_open
  - kernel/bpf/btf.c:btf_get_fd_by_id
  - kernel/bpf/btf.c:btf_new_fd
  - fs/fsopen.c:__se_sys_fspick
  - fs/fsopen.c:__se_sys_fsopen
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_init
  - fs/signalfd.c:do_signalfd4
  - fs/timerfd.c:__se_sys_timerfd_create
  - fs/eventfd.c:do_eventfd
  - fs/userfaultfd.c:__se_sys_userfaultfd
  - fs/userfaultfd.c:userfaultfd_ctx_read
```
**Symbols:**

```
c05c876c-c05c87dc: anon_inode_getfd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int anon_inode_getfd(const char *name, const struct file_operations *fops, void *priv, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/anon_inodes.c (c0000000004fb0e0)
Location: fs/anon_inodes.c:125
Inline: False
Direct callers:
  - kernel/pid.c:__se_sys_pidfd_open
  - kernel/bpf/btf.c:btf_get_fd_by_id
  - kernel/bpf/btf.c:btf_new_fd
  - fs/fsopen.c:__se_sys_fspick
  - fs/fsopen.c:__se_sys_fsopen
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_init
  - fs/timerfd.c:__se_sys_timerfd_create
  - fs/eventfd.c:do_eventfd
  - fs/userfaultfd.c:__se_sys_userfaultfd
  - fs/userfaultfd.c:userfaultfd_ctx_read
```
**Symbols:**

```
c0000000004fb0e0-c0000000004fb1b0: anon_inode_getfd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int anon_inode_getfd(const char *name, const struct file_operations *fops, void *priv, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/anon_inodes.c (ffffffe0002a4d36)
Location: fs/anon_inodes.c:125
Inline: False
Direct callers:
  - kernel/pid.c:__se_sys_pidfd_open
  - kernel/bpf/btf.c:btf_get_fd_by_id
  - kernel/bpf/btf.c:btf_new_fd
  - fs/fsopen.c:__se_sys_fspick
  - fs/fsopen.c:__se_sys_fsopen
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_init
  - fs/timerfd.c:__se_sys_timerfd_create
  - fs/eventfd.c:do_eventfd
  - fs/userfaultfd.c:__se_sys_userfaultfd
  - fs/userfaultfd.c:userfaultfd_read
```
**Symbols:**

```
ffffffe0002a4d36-ffffffe0002a4db0: anon_inode_getfd (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int anon_inode_getfd(const char *name, const struct file_operations *fops, void *priv, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/anon_inodes.c (ffffffff8132df40)
Location: fs/anon_inodes.c:125
Inline: False
Direct callers:
  - kernel/pid.c:pidfd_create
  - kernel/bpf/btf.c:btf_get_fd_by_id
  - kernel/bpf/btf.c:btf_new_fd
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init
  - fs/timerfd.c:__ia32_sys_timerfd_create
  - fs/timerfd.c:__x64_sys_timerfd_create
  - fs/eventfd.c:do_eventfd
  - fs/userfaultfd.c:__ia32_sys_userfaultfd
  - fs/userfaultfd.c:__x64_sys_userfaultfd
  - fs/userfaultfd.c:userfaultfd_read
```
**Symbols:**

```
ffffffff8132df40-ffffffff8132dfa8: anon_inode_getfd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int anon_inode_getfd(const char *name, const struct file_operations *fops, void *priv, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/anon_inodes.c (ffffffff8131eba0)
Location: fs/anon_inodes.c:125
Inline: False
Direct callers:
  - kernel/pid.c:pidfd_create
  - kernel/bpf/btf.c:btf_get_fd_by_id
  - kernel/bpf/btf.c:btf_new_fd
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init
  - fs/timerfd.c:__ia32_sys_timerfd_create
  - fs/timerfd.c:__x64_sys_timerfd_create
  - fs/eventfd.c:do_eventfd
  - fs/userfaultfd.c:__ia32_sys_userfaultfd
  - fs/userfaultfd.c:__x64_sys_userfaultfd
  - fs/userfaultfd.c:userfaultfd_read
```
**Symbols:**

```
ffffffff8131eba0-ffffffff8131ec08: anon_inode_getfd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int anon_inode_getfd(const char *name, const struct file_operations *fops, void *priv, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/anon_inodes.c (ffffffff8132ba10)
Location: fs/anon_inodes.c:125
Inline: False
Direct callers:
  - kernel/pid.c:pidfd_create
  - kernel/bpf/btf.c:btf_get_fd_by_id
  - kernel/bpf/btf.c:btf_new_fd
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init
  - fs/timerfd.c:__ia32_sys_timerfd_create
  - fs/timerfd.c:__x64_sys_timerfd_create
  - fs/eventfd.c:do_eventfd
  - fs/userfaultfd.c:__ia32_sys_userfaultfd
  - fs/userfaultfd.c:__x64_sys_userfaultfd
  - fs/userfaultfd.c:userfaultfd_read
```
**Symbols:**

```
ffffffff8132ba10-ffffffff8132ba78: anon_inode_getfd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int anon_inode_getfd(const char *name, const struct file_operations *fops, void *priv, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/anon_inodes.c (ffffffff8133e3c0)
Location: fs/anon_inodes.c:125
Inline: False
Direct callers:
  - kernel/pid.c:pidfd_create
  - kernel/bpf/btf.c:btf_get_fd_by_id
  - kernel/bpf/btf.c:btf_new_fd
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init
  - fs/timerfd.c:__ia32_sys_timerfd_create
  - fs/timerfd.c:__x64_sys_timerfd_create
  - fs/eventfd.c:do_eventfd
  - fs/userfaultfd.c:__ia32_sys_userfaultfd
  - fs/userfaultfd.c:__x64_sys_userfaultfd
  - fs/userfaultfd.c:userfaultfd_read
```
**Symbols:**

```
ffffffff8133e3c0-ffffffff8133e428: anon_inode_getfd (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
