# Function: <code>clear_user</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int clear_user(void *to, long unsigned int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff813f7a30)
Location: arch/x86/lib/usercopy_64.c:49
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:sys_modify_ldt
  - arch/x86/kernel/ldt.c:sys_modify_ldt
  - mm/mempolicy.c:copy_nodes_to_user
  - mm/mempolicy.c:compat_SyS_get_mempolicy
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - ipc/compat_mq.c:compat_SyS_mq_getsetattr
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
**Symbols:**

```
ffffffff813f7a30-ffffffff813f7a61: clear_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int clear_user(void *to, long unsigned int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff8143e8e0)
Location: arch/x86/lib/usercopy_64.c:49
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:sys_modify_ldt
  - arch/x86/kernel/ldt.c:sys_modify_ldt
  - mm/mempolicy.c:compat_SyS_get_mempolicy
  - mm/mempolicy.c:copy_nodes_to_user
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - ipc/compat_mq.c:compat_SyS_mq_getsetattr
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
**Symbols:**

```
ffffffff8143e8e0-ffffffff8143e911: clear_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int clear_user(void *to, long unsigned int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff8145b930)
Location: arch/x86/lib/usercopy_64.c:49
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:sys_modify_ldt
  - arch/x86/kernel/ldt.c:sys_modify_ldt
  - mm/mempolicy.c:C_SYSC_get_mempolicy
  - mm/mempolicy.c:SYSC_get_mempolicy
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - ipc/compat_mq.c:compat_SyS_mq_getsetattr
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
**Symbols:**

```
ffffffff8145b930-ffffffff8145b961: clear_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int clear_user(void *to, long unsigned int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff818fd550)
Location: arch/x86/lib/usercopy_64.c:50
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:sys_modify_ldt
  - arch/x86/kernel/ldt.c:sys_modify_ldt
  - mm/mempolicy.c:C_SYSC_get_mempolicy
  - mm/mempolicy.c:SYSC_get_mempolicy
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
  - drivers/char/mem.c:read_mem
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
**Symbols:**

```
ffffffff818fd550-ffffffff818fd581: clear_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int clear_user(void *to, long unsigned int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff81985030)
Location: arch/x86/lib/usercopy_64.c:50
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:SyS_modify_ldt
  - arch/x86/kernel/ldt.c:SyS_modify_ldt
  - mm/mempolicy.c:C_SYSC_get_mempolicy
  - mm/mempolicy.c:SYSC_get_mempolicy
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/proc/kcore.c:read_kcore
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
  - drivers/char/mem.c:read_mem
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
**Symbols:**

```
ffffffff81985030-ffffffff81985062: clear_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int clear_user(void *to, long unsigned int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff819e1520)
Location: arch/x86/lib/usercopy_64.c:49
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:__ia32_sys_modify_ldt
  - arch/x86/kernel/ldt.c:__x64_sys_modify_ldt
  - arch/x86/kernel/ldt.c:read_ldt
  - kernel/rseq.c:__rseq_handle_notify_resume
  - kernel/rseq.c:__rseq_handle_notify_resume
  - mm/mempolicy.c:__do_compat_sys_get_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/proc/kcore.c:read_kcore
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
  - drivers/char/mem.c:read_mem
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
**Symbols:**

```
ffffffff819e1520-ffffffff819e1552: clear_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int clear_user(void *to, long unsigned int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff81a1c4d0)
Location: arch/x86/lib/usercopy_64.c:49
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:__ia32_sys_modify_ldt
  - arch/x86/kernel/ldt.c:__x64_sys_modify_ldt
  - arch/x86/kernel/ldt.c:read_ldt
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/rseq.c:__rseq_handle_notify_resume
  - kernel/rseq.c:__rseq_handle_notify_resume
  - mm/mempolicy.c:__do_compat_sys_get_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
  - drivers/char/mem.c:read_mem
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
**Symbols:**

```
ffffffff81a1c4d0-ffffffff81a1c502: clear_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int clear_user(void *to, long unsigned int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff81a8c180)
Location: arch/x86/lib/usercopy_64.c:50
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:__ia32_sys_modify_ldt
  - arch/x86/kernel/ldt.c:__x64_sys_modify_ldt
  - arch/x86/kernel/ldt.c:read_ldt
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/rseq.c:__rseq_handle_notify_resume
  - kernel/rseq.c:__rseq_handle_notify_resume
  - mm/mempolicy.c:__do_compat_sys_get_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:copy_fid_to_user
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
  - drivers/char/mem.c:read_mem
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
**Symbols:**

```
ffffffff81a8c180-ffffffff81a8c1b1: clear_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int clear_user(void *to, long unsigned int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff81ac3440)
Location: arch/x86/lib/usercopy_64.c:50
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:__ia32_sys_modify_ldt
  - arch/x86/kernel/ldt.c:__x64_sys_modify_ldt
  - arch/x86/kernel/ldt.c:read_ldt
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/rseq.c:__rseq_handle_notify_resume
  - kernel/rseq.c:__rseq_handle_notify_resume
  - mm/mempolicy.c:__do_compat_sys_get_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:copy_fid_to_user
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
  - drivers/char/mem.c:read_mem
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
**Symbols:**

```
ffffffff81ac3440-ffffffff81ac3471: clear_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int clear_user(void *to, long unsigned int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff815ffa00)
Location: arch/x86/lib/usercopy_64.c:51
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:__ia32_sys_modify_ldt
  - arch/x86/kernel/ldt.c:__x64_sys_modify_ldt
  - arch/x86/kernel/ldt.c:read_ldt
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__x64_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait
  - kernel/signal.c:__x64_sys_rt_sigtimedwait
  - kernel/rseq.c:rseq_ip_fixup
  - kernel/rseq.c:rseq_ip_fixup
  - mm/mempolicy.c:__do_compat_sys_get_mempolicy
  - mm/mempolicy.c:copy_nodes_to_user
  - fs/notify/inotify/inotify_user.c:copy_event_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_info_to_user
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
  - drivers/char/mem.c:read_mem
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/md/dm-ioctl.c:copy_params
  - drivers/md/dm-ioctl.c:copy_params
```
**Symbols:**

```
ffffffff815ffa00-ffffffff815ffa31: clear_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int clear_user(void *to, long unsigned int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff81624930)
Location: arch/x86/lib/usercopy_64.c:51
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:__ia32_sys_modify_ldt
  - arch/x86/kernel/ldt.c:__x64_sys_modify_ldt
  - arch/x86/kernel/ldt.c:read_ldt
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__x64_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait
  - kernel/signal.c:__x64_sys_rt_sigtimedwait
  - kernel/rseq.c:rseq_ip_fixup
  - kernel/rseq.c:rseq_ip_fixup
  - mm/mempolicy.c:__do_compat_sys_get_mempolicy
  - mm/mempolicy.c:copy_nodes_to_user
  - fs/notify/inotify/inotify_user.c:copy_event_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_info_to_user
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
  - drivers/char/mem.c:read_zero
  - drivers/char/mem.c:read_mem
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/md/dm-ioctl.c:copy_params
  - drivers/md/dm-ioctl.c:copy_params
```
**Symbols:**

```
ffffffff81624930-ffffffff81624978: clear_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int clear_user(void *to, long unsigned int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff81608300)
Location: arch/x86/lib/usercopy_64.c:51
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:__ia32_sys_modify_ldt
  - arch/x86/kernel/ldt.c:__x64_sys_modify_ldt
  - arch/x86/kernel/ldt.c:read_ldt
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__x64_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait
  - kernel/signal.c:__x64_sys_rt_sigtimedwait
  - mm/mempolicy.c:__do_compat_sys_get_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - fs/notify/inotify/inotify_user.c:copy_event_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_info_to_user
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
  - drivers/char/mem.c:read_zero
  - drivers/char/mem.c:read_mem
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/md/dm-ioctl.c:copy_params
  - drivers/md/dm-ioctl.c:copy_params
```
**Symbols:**

```
ffffffff81608300-ffffffff8160832b: clear_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int clear_user(void *to, long unsigned int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff81676f40)
Location: arch/x86/lib/usercopy_64.c:51
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:__ia32_sys_modify_ldt
  - arch/x86/kernel/ldt.c:__x64_sys_modify_ldt
  - arch/x86/kernel/ldt.c:read_ldt
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__x64_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait
  - kernel/signal.c:__x64_sys_rt_sigtimedwait
  - mm/mempolicy.c:kernel_get_mempolicy
  - fs/notify/inotify/inotify_user.c:copy_event_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_fid_info_to_user
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
  - lib/iov_iter.c:iov_iter_zero
  - drivers/char/mem.c:read_zero
  - drivers/char/mem.c:read_mem
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/md/dm-ioctl.c:copy_params
  - drivers/md/dm-ioctl.c:copy_params
```
**Symbols:**

```
ffffffff81676f40-ffffffff81676f6b: clear_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int clear_user(void *to, long unsigned int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff81791f20)
Location: arch/x86/lib/usercopy_64.c:49
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:__ia32_sys_modify_ldt
  - arch/x86/kernel/ldt.c:__x64_sys_modify_ldt
  - arch/x86/kernel/ldt.c:read_ldt
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__x64_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait
  - kernel/signal.c:__x64_sys_rt_sigtimedwait
  - mm/mempolicy.c:kernel_get_mempolicy
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:copy_fid_info_to_user
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - security/keys/keyctl.c:keyctl_capabilities
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
  - lib/iov_iter.c:iov_iter_zero
  - drivers/char/mem.c:read_zero
  - drivers/char/mem.c:read_mem
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/md/dm-ioctl.c:copy_params
  - drivers/md/dm-ioctl.c:copy_params
```
**Symbols:**

```
ffffffff81791f20-ffffffff81791f5f: clear_user (STB_GLOBAL)
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
In arch/x86/kernel/ldt.c (ffffffff81052901)
Location: arch/x86/include/asm/uaccess_64.h:121
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:read_default_ldt
  - arch/x86/kernel/ldt.c:read_ldt
```
```
In kernel/signal.c (ffffffff81105d5c)
Location: arch/x86/include/asm/uaccess_64.h:121
Inline: True
Inline callers:
  - kernel/signal.c:copy_siginfo_to_user
```
```
In mm/mempolicy.c (ffffffff81414b9a)
Location: arch/x86/include/asm/uaccess_64.h:121
Inline: True
Inline callers:
  - mm/mempolicy.c:copy_nodes_to_user
```
```
In fs/notify/inotify/inotify_user.c (ffffffff814e0393)
Location: arch/x86/include/asm/uaccess_64.h:121
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:copy_event_to_user
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff814e399f)
Location: arch/x86/include/asm/uaccess_64.h:121
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:copy_fid_info_to_user
```
```
In fs/binfmt_elf.c (ffffffff81510f1e)
Location: arch/x86/include/asm/uaccess_64.h:121
Inline: True
Inline callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:padzero
```
```
In fs/compat_binfmt_elf.c (ffffffff81513fc3)
Location: arch/x86/include/asm/uaccess_64.h:121
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:padzero
```
```
In fs/proc/kcore.c (ffffffff81545c8e)
Location: arch/x86/include/asm/uaccess_64.h:121
Inline: True
Inline callers:
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
```
```
In security/keys/keyctl.c (ffffffff81654d80)
Location: arch/x86/include/asm/uaccess_64.h:121
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_capabilities
```
```
In security/keys/keyctl_pkey.c (ffffffff8165a615)
Location: arch/x86/include/asm/uaccess_64.h:121
Inline: True
Inline callers:
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
```
```
In lib/iov_iter.c (ffffffff817d4f11)
Location: arch/x86/include/asm/uaccess_64.h:121
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
```
```
In drivers/char/mem.c (ffffffff81a921ab)
Location: arch/x86/include/asm/uaccess_64.h:121
Inline: True
Inline callers:
  - drivers/char/mem.c:read_zero
  - drivers/char/mem.c:read_mem
```
```
In drivers/input/evdev.c (ffffffff81caf906)
Location: arch/x86/include/asm/uaccess_64.h:121
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_get_mask
```
```
In drivers/md/dm-ioctl.c (ffffffff81d17de9)
Location: arch/x86/include/asm/uaccess_64.h:121
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:copy_params
  - drivers/md/dm-ioctl.c:copy_params
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
In arch/x86/kernel/ldt.c (ffffffff810539e1)
Location: arch/x86/include/asm/uaccess_64.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:read_default_ldt
  - arch/x86/kernel/ldt.c:read_ldt
```
```
In kernel/signal.c (ffffffff8111203d)
Location: arch/x86/include/asm/uaccess_64.h:188
Inline: True
Inline callers:
  - kernel/signal.c:copy_siginfo_to_user
```
```
In mm/mempolicy.c (ffffffff8144815b)
Location: arch/x86/include/asm/uaccess_64.h:188
Inline: True
Inline callers:
  - mm/mempolicy.c:copy_nodes_to_user
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81516c61)
Location: arch/x86/include/asm/uaccess_64.h:188
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:copy_event_to_user
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8151a2c2)
Location: arch/x86/include/asm/uaccess_64.h:188
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:copy_fid_info_to_user
```
```
In fs/binfmt_elf.c (ffffffff81548851)
Location: arch/x86/include/asm/uaccess_64.h:188
Inline: True
Inline callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:padzero
```
```
In fs/compat_binfmt_elf.c (ffffffff8154ba1f)
Location: arch/x86/include/asm/uaccess_64.h:188
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:padzero
```
```
In security/keys/keyctl.c (ffffffff8168d5c1)
Location: arch/x86/include/asm/uaccess_64.h:188
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_capabilities
```
```
In security/keys/keyctl_pkey.c (ffffffff81692ef5)
Location: arch/x86/include/asm/uaccess_64.h:188
Inline: True
Inline callers:
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
```
```
In lib/iov_iter.c (ffffffff818149a2)
Location: arch/x86/include/asm/uaccess_64.h:188
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
```
```
In drivers/char/mem.c (ffffffff81adda3c)
Location: arch/x86/include/asm/uaccess_64.h:188
Inline: True
Inline callers:
  - drivers/char/mem.c:read_zero
  - drivers/char/mem.c:read_mem
```
```
In drivers/input/evdev.c (ffffffff81d16e90)
Location: arch/x86/include/asm/uaccess_64.h:188
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_get_mask
```
```
In drivers/md/dm-ioctl.c (ffffffff81d81070)
Location: arch/x86/include/asm/uaccess_64.h:188
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:copy_params
  - drivers/md/dm-ioctl.c:copy_params
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
In arch/x86/kernel/ldt.c (ffffffff8105ac01)
Location: arch/x86/include/asm/uaccess_64.h:188
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:read_default_ldt
  - arch/x86/kernel/ldt.c:read_ldt
```
```
In kernel/signal.c (ffffffff8111ba2d)
Location: arch/x86/include/asm/uaccess_64.h:188
Inline: True
Inline callers:
  - kernel/signal.c:copy_siginfo_to_user
```
```
In mm/mempolicy.c (ffffffff81481b5b)
Location: arch/x86/include/asm/uaccess_64.h:188
Inline: True
Inline callers:
  - mm/mempolicy.c:copy_nodes_to_user
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8154b051)
Location: arch/x86/include/asm/uaccess_64.h:188
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:copy_event_to_user
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8154e692)
Location: arch/x86/include/asm/uaccess_64.h:188
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:copy_fid_info_to_user
```
```
In fs/binfmt_elf.c (ffffffff8157cead)
Location: arch/x86/include/asm/uaccess_64.h:188
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_load
```
```
In fs/compat_binfmt_elf.c (ffffffff8157fee8)
Location: arch/x86/include/asm/uaccess_64.h:188
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_load
```
```
In security/keys/keyctl.c (ffffffff816c9b11)
Location: arch/x86/include/asm/uaccess_64.h:188
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_capabilities
```
```
In security/keys/keyctl_pkey.c (ffffffff816cf4c5)
Location: arch/x86/include/asm/uaccess_64.h:188
Inline: True
Inline callers:
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
```
```
In lib/iov_iter.c (ffffffff8185a3b3)
Location: arch/x86/include/asm/uaccess_64.h:188
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
```
```
In drivers/char/mem.c (ffffffff81b30e2c)
Location: arch/x86/include/asm/uaccess_64.h:188
Inline: True
Inline callers:
  - drivers/char/mem.c:read_zero
  - drivers/char/mem.c:read_mem
```
```
In drivers/gpu/drm/drm_ioc32.c (ffffffff81cb9445)
Location: arch/x86/include/asm/uaccess_64.h:188
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_ioc32.c:compat_drm_getstats
```
```
In drivers/input/evdev.c (ffffffff81dccb40)
Location: arch/x86/include/asm/uaccess_64.h:188
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_get_mask
```
```
In drivers/md/dm-ioctl.c (ffffffff81e38714)
Location: arch/x86/include/asm/uaccess_64.h:188
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:copy_params
  - drivers/md/dm-ioctl.c:copy_params
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
<details>
<summary>In <code>armhf</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int clear_user(void *to, long unsigned int n);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c0369204)
Location: arch/arm/include/asm/uaccess.h:577
Inline: True
Inline callers:
  - kernel/signal.c:copy_siginfo_to_user
```
```
In kernel/rseq.c (c04d97c0)
Location: arch/arm/include/asm/uaccess.h:577
Inline: True
Inline callers:
  - kernel/rseq.c:rseq_ip_fixup
  - kernel/rseq.c:rseq_ip_fixup
```
```
In fs/notify/inotify/inotify_user.c (c05c3408)
Location: arch/arm/include/asm/uaccess.h:577
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_read
```
```
In fs/notify/fanotify/fanotify_user.c (c05c5544)
Location: arch/arm/include/asm/uaccess.h:577
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
```
In fs/binfmt_elf.c (c05e8068)
Location: arch/arm/include/asm/uaccess.h:577
Inline: True
Inline callers:
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_binary
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/binfmt_elf_fdpic.c (c05eb6f4)
Location: arch/arm/include/asm/uaccess.h:577
Inline: True
Inline callers:
  - fs/binfmt_elf_fdpic.c:elf_fdpic_map_file
  - fs/binfmt_elf_fdpic.c:elf_fdpic_map_file
```
```
In fs/binfmt_flat.c (c05ed024)
Location: arch/arm/include/asm/uaccess.h:577
Inline: True
Inline callers:
  - fs/binfmt_flat.c:load_flat_file
```
```
In security/keys/keyctl.c (c06e9758)
Location: arch/arm/include/asm/uaccess.h:577
Inline: True
```
```
In security/keys/keyctl_pkey.c (c06efad0)
Location: arch/arm/include/asm/uaccess.h:577
Inline: True
Inline callers:
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
```
```
In lib/iov_iter.c (c07d6e7c)
Location: arch/arm/include/asm/uaccess.h:577
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
```
```
In drivers/char/mem.c (c09a7528)
Location: arch/arm/include/asm/uaccess.h:577
Inline: True
Inline callers:
  - drivers/char/mem.c:read_mem
```
```
In drivers/input/evdev.c (c0b80318)
Location: arch/arm/include/asm/uaccess.h:577
Inline: True
```
```
In drivers/md/dm-ioctl.c (c0be7dc0)
Location: arch/arm/include/asm/uaccess.h:577
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
**Symbols:**

```
c05e6730-c05e679c: clear_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int clear_user(void *addr, long unsigned int size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/ptrace.c (c000000000017df0)
Location: arch/powerpc/include/asm/uaccess.h:406
Inline: True
Inline callers:
  - arch/powerpc/kernel/ptrace.c:tm_cgpr_get
  - arch/powerpc/kernel/ptrace.c:gpr_get
```
```
In kernel/signal.c (c0000000001598b8)
Location: arch/powerpc/include/asm/uaccess.h:406
Inline: True
Inline callers:
  - kernel/signal.c:copy_siginfo_to_user
```
```
In kernel/rseq.c (c000000000360a40)
Location: arch/powerpc/include/asm/uaccess.h:406
Inline: True
Inline callers:
  - kernel/rseq.c:__rseq_handle_notify_resume
  - kernel/rseq.c:__rseq_handle_notify_resume
```
```
In mm/mempolicy.c (c0000000004145cc)
Location: arch/powerpc/include/asm/uaccess.h:406
Inline: True
Inline callers:
  - mm/mempolicy.c:__se_compat_sys_get_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
```
```
In fs/notify/inotify/inotify_user.c (c0000000004f4470)
Location: arch/powerpc/include/asm/uaccess.h:406
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_read
```
```
In fs/notify/fanotify/fanotify_user.c (c0000000004f6110)
Location: arch/powerpc/include/asm/uaccess.h:406
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:copy_fid_to_user
```
```
In fs/binfmt_elf.c (c00000000052cdf8)
Location: arch/powerpc/include/asm/uaccess.h:406
Inline: True
Inline callers:
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_binary
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (c000000000530ad8)
Location: arch/powerpc/include/asm/uaccess.h:406
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_binary
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
```
In fs/proc/kcore.c (c000000000566038)
Location: arch/powerpc/include/asm/uaccess.h:406
Inline: True
Inline callers:
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
```
```
In security/keys/keyctl.c (c00000000067f800)
Location: arch/powerpc/include/asm/uaccess.h:406
Inline: True
```
```
In security/keys/keyctl_pkey.c (c000000000687f74)
Location: arch/powerpc/include/asm/uaccess.h:406
Inline: True
Inline callers:
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
```
```
In lib/iov_iter.c (c0000000007d44b4)
Location: arch/powerpc/include/asm/uaccess.h:406
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
```
```
In drivers/char/mem.c (c000000000942fcc)
Location: arch/powerpc/include/asm/uaccess.h:406
Inline: True
Inline callers:
  - drivers/char/mem.c:read_mem
```
```
In drivers/input/evdev.c (c000000000b80a30)
Location: arch/powerpc/include/asm/uaccess.h:406
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_do_ioctl
```
```
In drivers/md/dm-ioctl.c (c000000000bfb064)
Location: arch/powerpc/include/asm/uaccess.h:406
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
**Symbols:**

```
c00000000052cad0-c00000000052cb88: clear_user (STB_LOCAL)
c0000000005307a0-c000000000530858: clear_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int clear_user(void *to, long unsigned int n);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffe0000d12ae)
Location: arch/riscv/include/asm/uaccess.h:396
Inline: True
Inline callers:
  - kernel/signal.c:copy_siginfo_to_user
```
```
In fs/notify/inotify/inotify_user.c (ffffffe0002a0264)
Location: arch/riscv/include/asm/uaccess.h:396
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_read
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffe0002a180e)
Location: arch/riscv/include/asm/uaccess.h:396
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:copy_fid_to_user
```
```
In fs/binfmt_elf.c (ffffffe0002c27f4)
Location: arch/riscv/include/asm/uaccess.h:396
Inline: True
Inline callers:
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_binary
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/binfmt_flat.c (ffffffe0002c354c)
Location: arch/riscv/include/asm/uaccess.h:396
Inline: True
Inline callers:
  - fs/binfmt_flat.c:load_flat_file
```
```
In fs/proc/kcore.c (ffffffe0002e2c5c)
Location: arch/riscv/include/asm/uaccess.h:396
Inline: True
Inline callers:
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
```
```
In security/keys/keyctl.c (ffffffe000392910)
Location: arch/riscv/include/asm/uaccess.h:396
Inline: True
```
```
In security/keys/keyctl_pkey.c (ffffffe000397b1c)
Location: arch/riscv/include/asm/uaccess.h:396
Inline: True
Inline callers:
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
```
```
In lib/iov_iter.c (ffffffe00045f60e)
Location: arch/riscv/include/asm/uaccess.h:396
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
```
```
In drivers/char/mem.c (0)
Location: arch/riscv/include/asm/uaccess.h:396
Inline: False
```
```
In drivers/input/evdev.c (ffffffe0006ae838)
Location: arch/riscv/include/asm/uaccess.h:396
Inline: True
```
```
In drivers/md/dm-ioctl.c (ffffffe0006f7a92)
Location: arch/riscv/include/asm/uaccess.h:396
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
**Symbols:**

```
ffffffe0002c0654-ffffffe0002c0680: clear_user (STB_LOCAL)
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
long unsigned int clear_user(void *to, long unsigned int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff81a62290)
Location: arch/x86/lib/usercopy_64.c:50
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:__ia32_sys_modify_ldt
  - arch/x86/kernel/ldt.c:__x64_sys_modify_ldt
  - arch/x86/kernel/ldt.c:read_ldt
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/rseq.c:__rseq_handle_notify_resume
  - kernel/rseq.c:__rseq_handle_notify_resume
  - mm/mempolicy.c:__do_compat_sys_get_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:copy_fid_to_user
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
  - drivers/char/mem.c:read_mem
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
**Symbols:**

```
ffffffff81a62290-ffffffff81a622c1: clear_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int clear_user(void *to, long unsigned int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff81a1f300)
Location: arch/x86/lib/usercopy_64.c:50
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:__ia32_sys_modify_ldt
  - arch/x86/kernel/ldt.c:__x64_sys_modify_ldt
  - arch/x86/kernel/ldt.c:read_ldt
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/rseq.c:__rseq_handle_notify_resume
  - kernel/rseq.c:__rseq_handle_notify_resume
  - mm/mempolicy.c:__do_compat_sys_get_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:copy_fid_to_user
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
  - drivers/char/mem.c:read_mem
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
**Symbols:**

```
ffffffff81a1f300-ffffffff81a1f331: clear_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int clear_user(void *to, long unsigned int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff81ace680)
Location: arch/x86/lib/usercopy_64.c:50
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:__ia32_sys_modify_ldt
  - arch/x86/kernel/ldt.c:__x64_sys_modify_ldt
  - arch/x86/kernel/ldt.c:read_ldt
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/rseq.c:__rseq_handle_notify_resume
  - kernel/rseq.c:__rseq_handle_notify_resume
  - mm/mempolicy.c:__do_compat_sys_get_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:copy_fid_to_user
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
  - drivers/char/mem.c:read_mem
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
**Symbols:**

```
ffffffff81ace680-ffffffff81ace6b1: clear_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int clear_user(void *to, long unsigned int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff81adab90)
Location: arch/x86/lib/usercopy_64.c:50
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:__ia32_sys_modify_ldt
  - arch/x86/kernel/ldt.c:__x64_sys_modify_ldt
  - arch/x86/kernel/ldt.c:read_ldt
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/rseq.c:rseq_ip_fixup
  - kernel/rseq.c:rseq_ip_fixup
  - mm/mempolicy.c:__do_compat_sys_get_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:copy_fid_to_user
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
  - drivers/char/mem.c:read_mem
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
**Symbols:**

```
ffffffff81adab90-ffffffff81adabc1: clear_user (STB_GLOBAL)
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>ppc64el</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>void *addr</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int size</code>
</li>
<li>
<b>Param removed. </b>
<code>void *to</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int n</code>
</li>
</ul>
</details>
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
