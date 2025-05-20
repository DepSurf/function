# Function: <code>__clear_user</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int __clear_user(void *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff813f79a0)
Location: arch/x86/lib/usercopy_64.c:15
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - fs/signalfd.c:signalfd_copyinfo
  - fs/compat.c:put_compat_statfs
  - fs/compat.c:put_compat_statfs64
  - arch/x86/lib/usercopy_64.c:clear_user
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
```
**Symbols:**

```
ffffffff813f79a0-ffffffff813f79e7: __clear_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int __clear_user(void *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff8143e850)
Location: arch/x86/lib/usercopy_64.c:15
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - fs/signalfd.c:signalfd_copyinfo
  - fs/compat.c:put_compat_statfs64
  - fs/compat.c:put_compat_statfs
  - arch/x86/lib/usercopy_64.c:clear_user
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
```
**Symbols:**

```
ffffffff8143e850-ffffffff8143e897: __clear_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int __clear_user(void *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff8145b8a0)
Location: arch/x86/lib/usercopy_64.c:15
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - fs/signalfd.c:signalfd_copyinfo
  - fs/compat.c:put_compat_statfs64
  - fs/compat.c:put_compat_statfs
  - arch/x86/lib/usercopy_64.c:clear_user
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
```
**Symbols:**

```
ffffffff8145b8a0-ffffffff8145b8e7: __clear_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int __clear_user(void *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff818fd500)
Location: arch/x86/lib/usercopy_64.c:16
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - fs/signalfd.c:signalfd_copyinfo
  - arch/x86/lib/usercopy_64.c:clear_user
```
**Symbols:**

```
ffffffff818fd500-ffffffff818fd547: __clear_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int __clear_user(void *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff81984fe0)
Location: arch/x86/lib/usercopy_64.c:16
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - fs/signalfd.c:signalfd_copyinfo
  - arch/x86/lib/usercopy_64.c:clear_user
```
**Symbols:**

```
ffffffff81984fe0-ffffffff81985027: __clear_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int __clear_user(void *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff819e14d0)
Location: arch/x86/lib/usercopy_64.c:16
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/lib/usercopy_64.c:clear_user
```
**Symbols:**

```
ffffffff819e14d0-ffffffff819e1516: __clear_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int __clear_user(void *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff81a1c480)
Location: arch/x86/lib/usercopy_64.c:16
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/lib/usercopy_64.c:clear_user
```
**Symbols:**

```
ffffffff81a1c480-ffffffff81a1c4c6: __clear_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int __clear_user(void *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff81a8c130)
Location: arch/x86/lib/usercopy_64.c:17
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/lib/usercopy_64.c:clear_user
```
**Symbols:**

```
ffffffff81a8c130-ffffffff81a8c176: __clear_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int __clear_user(void *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff81ac33f0)
Location: arch/x86/lib/usercopy_64.c:17
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/lib/usercopy_64.c:clear_user
```
**Symbols:**

```
ffffffff81ac33f0-ffffffff81ac3436: __clear_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int __clear_user(void *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff815ff960)
Location: arch/x86/lib/usercopy_64.c:17
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/lib/usercopy_64.c:clear_user
```
**Symbols:**

```
ffffffff815ff960-ffffffff815ff9a8: __clear_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int __clear_user(void *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff81624890)
Location: arch/x86/lib/usercopy_64.c:17
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/lib/usercopy_64.c:clear_user
```
**Symbols:**

```
ffffffff81624890-ffffffff816248d8: __clear_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int __clear_user(void *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff81608260)
Location: arch/x86/lib/usercopy_64.c:17
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/lib/usercopy_64.c:clear_user
```
**Symbols:**

```
ffffffff81608260-ffffffff816082a8: __clear_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int __clear_user(void *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff81676ea0)
Location: arch/x86/lib/usercopy_64.c:17
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/lib/usercopy_64.c:clear_user
```
**Symbols:**

```
ffffffff81676ea0-ffffffff81676ee8: __clear_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int __clear_user(void *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff81791e50)
Location: arch/x86/lib/usercopy_64.c:17
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/lib/usercopy_64.c:clear_user
```
**Symbols:**

```
ffffffff81791e50-ffffffff81791ea2: __clear_user (STB_GLOBAL)
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
In arch/x86/kernel/ldt.c (ffffffff8105292d)
Location: arch/x86/include/asm/uaccess_64.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:read_default_ldt
  - arch/x86/kernel/ldt.c:read_ldt
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81062bcf)
Location: arch/x86/include/asm/uaccess_64.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In kernel/signal.c (ffffffff81105d79)
Location: arch/x86/include/asm/uaccess_64.h:94
Inline: True
Inline callers:
  - kernel/signal.c:copy_siginfo_to_user
```
```
In mm/mempolicy.c (ffffffff81414bc3)
Location: arch/x86/include/asm/uaccess_64.h:94
Inline: True
Inline callers:
  - mm/mempolicy.c:copy_nodes_to_user
```
```
In fs/notify/inotify/inotify_user.c (ffffffff814e046c)
Location: arch/x86/include/asm/uaccess_64.h:94
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:copy_event_to_user
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff814e39be)
Location: arch/x86/include/asm/uaccess_64.h:94
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:copy_fid_info_to_user
```
```
In fs/binfmt_elf.c (ffffffff81510f3d)
Location: arch/x86/include/asm/uaccess_64.h:94
Inline: True
Inline callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:padzero
```
```
In fs/compat_binfmt_elf.c (ffffffff81513fe2)
Location: arch/x86/include/asm/uaccess_64.h:94
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:padzero
```
```
In fs/proc/kcore.c (ffffffff81545cad)
Location: arch/x86/include/asm/uaccess_64.h:94
Inline: True
Inline callers:
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
```
```
In security/keys/keyctl.c (ffffffff81654d9f)
Location: arch/x86/include/asm/uaccess_64.h:94
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_capabilities
```
```
In security/keys/keyctl_pkey.c (ffffffff8165a632)
Location: arch/x86/include/asm/uaccess_64.h:94
Inline: True
Inline callers:
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
```
```
In lib/iov_iter.c (ffffffff817d4f77)
Location: arch/x86/include/asm/uaccess_64.h:94
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
```
```
In drivers/char/mem.c (ffffffff81a921d1)
Location: arch/x86/include/asm/uaccess_64.h:94
Inline: True
Inline callers:
  - drivers/char/mem.c:read_zero
  - drivers/char/mem.c:read_mem
```
```
In drivers/input/evdev.c (ffffffff81caf924)
Location: arch/x86/include/asm/uaccess_64.h:94
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_get_mask
```
```
In drivers/md/dm-ioctl.c (ffffffff81d17f4d)
Location: arch/x86/include/asm/uaccess_64.h:94
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
In arch/x86/kernel/ldt.c (ffffffff810539ff)
Location: arch/x86/include/asm/uaccess_64.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:read_default_ldt
  - arch/x86/kernel/ldt.c:read_ldt
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff810645c4)
Location: arch/x86/include/asm/uaccess_64.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In kernel/signal.c (ffffffff81112059)
Location: arch/x86/include/asm/uaccess_64.h:165
Inline: True
Inline callers:
  - kernel/signal.c:copy_siginfo_to_user
```
```
In mm/mempolicy.c (ffffffff81448178)
Location: arch/x86/include/asm/uaccess_64.h:165
Inline: True
Inline callers:
  - mm/mempolicy.c:copy_nodes_to_user
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81516c74)
Location: arch/x86/include/asm/uaccess_64.h:165
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:copy_event_to_user
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8151a305)
Location: arch/x86/include/asm/uaccess_64.h:165
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:copy_fid_info_to_user
```
```
In fs/binfmt_elf.c (ffffffff8154885a)
Location: arch/x86/include/asm/uaccess_64.h:165
Inline: True
Inline callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:padzero
```
```
In fs/compat_binfmt_elf.c (ffffffff8154ba28)
Location: arch/x86/include/asm/uaccess_64.h:165
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:padzero
```
```
In security/keys/keyctl.c (ffffffff8168d5d6)
Location: arch/x86/include/asm/uaccess_64.h:165
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_capabilities
```
```
In security/keys/keyctl_pkey.c (ffffffff81692f40)
Location: arch/x86/include/asm/uaccess_64.h:165
Inline: True
Inline callers:
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
```
```
In lib/iov_iter.c (ffffffff818149b6)
Location: arch/x86/include/asm/uaccess_64.h:165
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
```
```
In drivers/char/mem.c (ffffffff81adda7b)
Location: arch/x86/include/asm/uaccess_64.h:165
Inline: True
Inline callers:
  - drivers/char/mem.c:read_zero
  - drivers/char/mem.c:read_mem
```
```
In drivers/input/evdev.c (ffffffff81d16ead)
Location: arch/x86/include/asm/uaccess_64.h:165
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_get_mask
```
```
In drivers/md/dm-ioctl.c (ffffffff81d81093)
Location: arch/x86/include/asm/uaccess_64.h:165
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
In arch/x86/kernel/ldt.c (ffffffff8105ac1f)
Location: arch/x86/include/asm/uaccess_64.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:read_default_ldt
  - arch/x86/kernel/ldt.c:read_ldt
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8106ba84)
Location: arch/x86/include/asm/uaccess_64.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In kernel/signal.c (ffffffff8111ba49)
Location: arch/x86/include/asm/uaccess_64.h:165
Inline: True
Inline callers:
  - kernel/signal.c:copy_siginfo_to_user
```
```
In mm/mempolicy.c (ffffffff81481b78)
Location: arch/x86/include/asm/uaccess_64.h:165
Inline: True
Inline callers:
  - mm/mempolicy.c:copy_nodes_to_user
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8154b064)
Location: arch/x86/include/asm/uaccess_64.h:165
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:copy_event_to_user
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8154e6d5)
Location: arch/x86/include/asm/uaccess_64.h:165
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:copy_fid_info_to_user
```
```
In fs/binfmt_elf.c (ffffffff8157cef2)
Location: arch/x86/include/asm/uaccess_64.h:165
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_load
```
```
In fs/compat_binfmt_elf.c (ffffffff8157ff2d)
Location: arch/x86/include/asm/uaccess_64.h:165
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_load
```
```
In security/keys/keyctl.c (ffffffff816c9b26)
Location: arch/x86/include/asm/uaccess_64.h:165
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_capabilities
```
```
In security/keys/keyctl_pkey.c (ffffffff816cf510)
Location: arch/x86/include/asm/uaccess_64.h:165
Inline: True
Inline callers:
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
```
```
In lib/iov_iter.c (ffffffff8185a3c4)
Location: arch/x86/include/asm/uaccess_64.h:165
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
```
```
In drivers/char/mem.c (ffffffff81b30e6b)
Location: arch/x86/include/asm/uaccess_64.h:165
Inline: True
Inline callers:
  - drivers/char/mem.c:read_zero
  - drivers/char/mem.c:read_mem
```
```
In drivers/gpu/drm/drm_ioc32.c (ffffffff81cb945a)
Location: arch/x86/include/asm/uaccess_64.h:165
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_ioc32.c:compat_drm_getstats
```
```
In drivers/input/evdev.c (ffffffff81dccb5d)
Location: arch/x86/include/asm/uaccess_64.h:165
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_get_mask
```
```
In drivers/md/dm-ioctl.c (ffffffff81e38737)
Location: arch/x86/include/asm/uaccess_64.h:165
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
<details>
<summary>In <code>arm64</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int __clear_user(void *to, long unsigned int n);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/arm64/kernel/ptrace.c (ffff80001008dd04)
Location: arch/arm64/include/asm/uaccess.h:420
Inline: True
Inline callers:
  - arch/arm64/kernel/ptrace.c:sve_get
  - arch/arm64/kernel/ptrace.c:hw_break_get
  - arch/arm64/kernel/ptrace.c:hw_break_get
```
```
In arch/arm64/kvm/guest.c (ffff8000100d2dbc)
Location: arch/arm64/include/asm/uaccess.h:420
Inline: True
Inline callers:
  - arch/arm64/kvm/guest.c:kvm_arm_get_reg
```
```
In kernel/signal.c (ffff800010111d68)
Location: arch/arm64/include/asm/uaccess.h:420
Inline: True
Inline callers:
  - kernel/signal.c:copy_siginfo_to_user
```
```
In kernel/rseq.c (ffff8000102ac7f8)
Location: arch/arm64/include/asm/uaccess.h:420
Inline: True
Inline callers:
  - kernel/rseq.c:__rseq_handle_notify_resume
  - kernel/rseq.c:__rseq_handle_notify_resume
```
```
In mm/mempolicy.c (ffff800010339e58)
Location: arch/arm64/include/asm/uaccess.h:420
Inline: True
Inline callers:
  - mm/mempolicy.c:__arm64_compat_sys_get_mempolicy
  - mm/mempolicy.c:__arm64_compat_sys_get_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
```
```
In fs/notify/inotify/inotify_user.c (ffff8000103ec320)
Location: arch/arm64/include/asm/uaccess.h:420
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_read
```
```
In fs/notify/fanotify/fanotify_user.c (ffff8000103ee374)
Location: arch/arm64/include/asm/uaccess.h:420
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:copy_fid_to_user
```
```
In fs/binfmt_elf.c (ffff8000104208f8)
Location: arch/arm64/include/asm/uaccess.h:420
Inline: True
Inline callers:
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffff8000104241b0)
Location: arch/arm64/include/asm/uaccess.h:420
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
```
In fs/proc/kcore.c (ffff80001044e508)
Location: arch/arm64/include/asm/uaccess.h:420
Inline: True
Inline callers:
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
Direct callers:
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
```
```
In security/keys/keyctl.c (ffff80001053212c)
Location: arch/arm64/include/asm/uaccess.h:420
Inline: True
```
```
In security/keys/keyctl_pkey.c (ffff800010539198)
Location: arch/arm64/include/asm/uaccess.h:420
Inline: True
Inline callers:
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
```
```
In lib/iov_iter.c (ffff8000106304f8)
Location: arch/arm64/include/asm/uaccess.h:420
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
```
```
In drivers/char/mem.c (ffff8000108ab6c4)
Location: arch/arm64/include/asm/uaccess.h:420
Inline: True
Inline callers:
  - drivers/char/mem.c:read_mem
```
```
In drivers/input/evdev.c (ffff800010a9ff0c)
Location: arch/arm64/include/asm/uaccess.h:420
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_do_ioctl
```
```
In drivers/md/dm-ioctl.c (ffff800010b09564)
Location: arch/arm64/include/asm/uaccess.h:420
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
**Symbols:**

```
ffff80001041e1a8-ffff80001041e308: __clear_user (STB_LOCAL)
ffff800010421c88-ffff800010421de8: __clear_user (STB_LOCAL)
ffff80001044dc68-ffff80001044dd64: __clear_user.part.0 (STB_LOCAL)
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
In arch/arm/kernel/ptrace.c (0)
Location: arch/arm/include/asm/uaccess.h:551
Inline: True
```
```
In kernel/signal.c (c0369224)
Location: arch/arm/include/asm/uaccess.h:551
Inline: True
Inline callers:
  - kernel/signal.c:copy_siginfo_to_user
```
```
In kernel/rseq.c (c04d986c)
Location: arch/arm/include/asm/uaccess.h:551
Inline: True
Inline callers:
  - kernel/rseq.c:rseq_ip_fixup
  - kernel/rseq.c:rseq_ip_fixup
```
```
In fs/notify/inotify/inotify_user.c (c05c3470)
Location: arch/arm/include/asm/uaccess.h:551
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_read
```
```
In fs/notify/fanotify/fanotify_user.c (c05c5558)
Location: arch/arm/include/asm/uaccess.h:551
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
```
In fs/binfmt_elf.c (c05e8088)
Location: arch/arm/include/asm/uaccess.h:551
Inline: True
Inline callers:
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/binfmt_elf_fdpic.c (c05eb71c)
Location: arch/arm/include/asm/uaccess.h:551
Inline: True
Inline callers:
  - fs/binfmt_elf_fdpic.c:elf_fdpic_map_file
  - fs/binfmt_elf_fdpic.c:elf_fdpic_map_file
```
```
In fs/binfmt_flat.c (c05ed204)
Location: arch/arm/include/asm/uaccess.h:551
Inline: True
Inline callers:
  - fs/binfmt_flat.c:load_flat_file
```
```
In security/keys/keyctl.c (c06e9780)
Location: arch/arm/include/asm/uaccess.h:551
Inline: True
```
```
In security/keys/keyctl_pkey.c (c06efae8)
Location: arch/arm/include/asm/uaccess.h:551
Inline: True
Inline callers:
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
```
```
In lib/iov_iter.c (c07d6f1c)
Location: arch/arm/include/asm/uaccess.h:551
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
```
```
In drivers/char/mem.c (c09a7540)
Location: arch/arm/include/asm/uaccess.h:551
Inline: True
Inline callers:
  - drivers/char/mem.c:read_mem
```
```
In drivers/input/evdev.c (c0b807a0)
Location: arch/arm/include/asm/uaccess.h:551
Inline: True
```
```
In drivers/md/dm-ioctl.c (c0be7edc)
Location: arch/arm/include/asm/uaccess.h:551
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/ptrace.c (c000000000017df0)
Location: arch/powerpc/include/asm/uaccess.h:418
Inline: True
Inline callers:
  - arch/powerpc/kernel/ptrace.c:tm_cgpr_get
  - arch/powerpc/kernel/ptrace.c:gpr_get
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - kernel/signal.c:copy_siginfo_to_user
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:copy_fid_to_user
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_flat.c:load_flat_file
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
**Symbols:**

```
ffffffe0008c3f78-ffffffe0008c3fc6: __clear_user (STB_GLOBAL)
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
long unsigned int __clear_user(void *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff81a62240)
Location: arch/x86/lib/usercopy_64.c:17
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/lib/usercopy_64.c:clear_user
```
**Symbols:**

```
ffffffff81a62240-ffffffff81a62286: __clear_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int __clear_user(void *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff81a1f2b0)
Location: arch/x86/lib/usercopy_64.c:17
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/lib/usercopy_64.c:clear_user
```
**Symbols:**

```
ffffffff81a1f2b0-ffffffff81a1f2f6: __clear_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int __clear_user(void *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff81ace630)
Location: arch/x86/lib/usercopy_64.c:17
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/lib/usercopy_64.c:clear_user
```
**Symbols:**

```
ffffffff81ace630-ffffffff81ace676: __clear_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int __clear_user(void *addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff81adab40)
Location: arch/x86/lib/usercopy_64.c:17
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/lib/usercopy_64.c:clear_user
```
**Symbols:**

```
ffffffff81adab40-ffffffff81adab86: __clear_user (STB_GLOBAL)
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
<details>
<summary>Changed between <code>amd64</code> and <code>arm64</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>void *to</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int n</code>
</li>
<li>
<b>Param removed. </b>
<code>void *addr</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int size</code>
</li>
</ul>
</details>
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
