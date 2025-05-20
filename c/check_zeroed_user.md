# Function: <code>check_zeroed_user</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int check_zeroed_user(const void *from, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/usercopy.c (ffffffff8152c1a0)
Location: lib/usercopy.c:50
Inline: False
Direct callers:
  - kernel/fork.c:copy_clone_args_from_user
  - kernel/sched/core.c:sched_copy_attr
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/events/core.c:perf_copy_attr
```
**Symbols:**

```
ffffffff8152c1a0-ffffffff8152c261: check_zeroed_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int check_zeroed_user(const void *from, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/usercopy.c (ffffffff8158fa70)
Location: lib/usercopy.c:51
Inline: False
Direct callers:
  - kernel/fork.c:copy_clone_args_from_user
  - kernel/sched/core.c:sched_copy_attr
  - kernel/seccomp.c:seccomp_notify_recv
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/events/core.c:perf_copy_attr
  - fs/open.c:__ia32_sys_openat2
  - fs/open.c:__x64_sys_openat2
```
**Symbols:**

```
ffffffff8158fa70-ffffffff8158fb31: check_zeroed_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int check_zeroed_user(const void *from, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/usercopy.c (ffffffff815ac5a0)
Location: lib/usercopy.c:54
Inline: False
Direct callers:
  - kernel/fork.c:copy_clone_args_from_user
  - kernel/sched/core.c:sched_copy_attr
  - kernel/seccomp.c:seccomp_notify_addfd
  - kernel/seccomp.c:seccomp_notify_recv
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/events/core.c:perf_copy_attr
  - fs/open.c:__ia32_sys_openat2
  - fs/open.c:__x64_sys_openat2
  - fs/io_uring.c:io_req_prep
```
**Symbols:**

```
ffffffff815ac5a0-ffffffff815ac67a: check_zeroed_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int check_zeroed_user(const void *from, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/usercopy.c (ffffffff815b7270)
Location: lib/usercopy.c:54
Inline: False
Direct callers:
  - kernel/fork.c:copy_clone_args_from_user
  - kernel/sched/core.c:sched_copy_attr
  - kernel/seccomp.c:seccomp_notify_addfd
  - kernel/seccomp.c:seccomp_notify_recv
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/events/core.c:perf_copy_attr
  - fs/open.c:__ia32_sys_openat2
  - fs/open.c:__x64_sys_openat2
  - fs/namespace.c:__do_sys_mount_setattr
  - fs/io_uring.c:io_req_prep
  - security/landlock/syscalls.c:__ia32_sys_landlock_create_ruleset
  - security/landlock/syscalls.c:__x64_sys_landlock_create_ruleset
```
**Symbols:**

```
ffffffff815b7270-ffffffff815b732e: check_zeroed_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int check_zeroed_user(const void *from, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/usercopy.c (ffffffff8161d8a0)
Location: lib/usercopy.c:54
Inline: False
Direct callers:
  - kernel/fork.c:copy_clone_args_from_user
  - kernel/sched/core.c:sched_copy_attr
  - kernel/seccomp.c:seccomp_notify_addfd
  - kernel/seccomp.c:seccomp_notify_recv
  - kernel/bpf/syscall.c:bpf_check_uarg_tail_zero
  - kernel/events/core.c:perf_copy_attr
  - fs/open.c:__ia32_sys_openat2
  - fs/open.c:__x64_sys_openat2
  - fs/namespace.c:__do_sys_mount_setattr
  - fs/io_uring.c:io_req_prep
  - security/landlock/syscalls.c:__ia32_sys_landlock_create_ruleset
  - security/landlock/syscalls.c:__x64_sys_landlock_create_ruleset
```
**Symbols:**

```
ffffffff8161d8a0-ffffffff8161d960: check_zeroed_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int check_zeroed_user(const void *from, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/usercopy.c (ffffffff816eb400)
Location: lib/usercopy.c:54
Inline: False
Direct callers:
  - kernel/fork.c:copy_clone_args_from_user
  - kernel/sched/core.c:sched_copy_attr
  - kernel/seccomp.c:seccomp_notify_addfd
  - kernel/seccomp.c:seccomp_notify_recv
  - kernel/bpf/syscall.c:bpf_check_uarg_tail_zero
  - kernel/events/core.c:perf_copy_attr
  - fs/open.c:__do_sys_openat2
  - fs/namespace.c:__do_sys_mount_setattr
  - security/landlock/syscalls.c:__ia32_sys_landlock_create_ruleset
  - security/landlock/syscalls.c:__x64_sys_landlock_create_ruleset
  - io_uring/io_uring.c:io_openat2_prep
```
**Symbols:**

```
ffffffff816eb400-ffffffff816eb4e6: check_zeroed_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int check_zeroed_user(const void *from, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/usercopy.c (ffffffff817dbad0)
Location: lib/usercopy.c:62
Inline: False
Direct callers:
  - kernel/fork.c:copy_clone_args_from_user
  - kernel/sched/core.c:sched_copy_attr
  - kernel/seccomp.c:seccomp_notify_addfd
  - kernel/seccomp.c:seccomp_notify_recv
  - kernel/bpf/syscall.c:bpf_check_uarg_tail_zero
  - kernel/events/core.c:perf_copy_attr
  - fs/open.c:__do_sys_openat2
  - fs/namespace.c:__do_sys_mount_setattr
  - security/landlock/syscalls.c:__ia32_sys_landlock_create_ruleset
  - security/landlock/syscalls.c:__x64_sys_landlock_create_ruleset
  - io_uring/openclose.c:io_openat2_prep
  - net/ipv4/tcp.c:do_tcp_getsockopt
```
**Symbols:**

```
ffffffff817dbad0-ffffffff817dbba9: check_zeroed_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int check_zeroed_user(const void *from, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/usercopy.c (ffffffff8181ae80)
Location: lib/usercopy.c:62
Inline: False
Direct callers:
  - kernel/fork.c:copy_clone_args_from_user
  - kernel/sched/core.c:sched_copy_attr
  - kernel/seccomp.c:seccomp_notify_addfd
  - kernel/seccomp.c:seccomp_notify_recv
  - kernel/trace/trace_events_user.c:user_events_ioctl_unreg
  - kernel/trace/trace_events_user.c:user_events_ioctl_reg
  - kernel/bpf/syscall.c:bpf_check_uarg_tail_zero
  - kernel/events/core.c:perf_copy_attr
  - fs/open.c:__ia32_sys_openat2
  - fs/open.c:__x64_sys_openat2
  - fs/namespace.c:__ia32_sys_mount_setattr
  - fs/namespace.c:__x64_sys_mount_setattr
  - security/landlock/syscalls.c:__ia32_sys_landlock_create_ruleset
  - security/landlock/syscalls.c:__x64_sys_landlock_create_ruleset
  - io_uring/openclose.c:io_openat2_prep
  - net/ipv4/tcp.c:do_tcp_getsockopt
```
**Symbols:**

```
ffffffff8181ae80-ffffffff8181af47: check_zeroed_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int check_zeroed_user(const void *from, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/usercopy.c (ffffffff818601d0)
Location: lib/usercopy.c:62
Inline: False
Direct callers:
  - kernel/fork.c:copy_clone_args_from_user
  - kernel/sched/core.c:sched_copy_attr
  - kernel/seccomp.c:seccomp_notify_addfd
  - kernel/seccomp.c:seccomp_notify_recv
  - kernel/trace/trace_events_user.c:user_events_ioctl_unreg
  - kernel/trace/trace_events_user.c:user_events_ioctl_reg
  - kernel/bpf/syscall.c:bpf_check_uarg_tail_zero
  - kernel/events/core.c:perf_copy_attr
  - fs/open.c:__ia32_sys_openat2
  - fs/open.c:__x64_sys_openat2
  - fs/namespace.c:copy_mnt_id_req
  - fs/namespace.c:__ia32_sys_mount_setattr
  - fs/namespace.c:__x64_sys_mount_setattr
  - security/landlock/syscalls.c:__do_sys_landlock_create_ruleset
  - io_uring/openclose.c:io_openat2_prep
  - net/ipv4/tcp.c:do_tcp_getsockopt
```
**Symbols:**

```
ffffffff818601d0-ffffffff818602ac: check_zeroed_user (STB_GLOBAL)
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
int check_zeroed_user(const void *from, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/usercopy.c (ffff800010637e10)
Location: lib/usercopy.c:50
Inline: False
Direct callers:
  - kernel/fork.c:copy_clone_args_from_user
  - kernel/sched/core.c:__arm64_sys_sched_setattr
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/events/core.c:perf_copy_attr
```
**Symbols:**

```
ffff800010637e10-ffff80001063812c: check_zeroed_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int check_zeroed_user(const void *from, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/usercopy.c (c07dd964)
Location: lib/usercopy.c:50
Inline: False
Direct callers:
  - kernel/fork.c:copy_clone_args_from_user
  - kernel/sched/core.c:__se_sys_sched_setattr
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/events/core.c:perf_copy_attr
```
**Symbols:**

```
c07dd964-c07dda84: check_zeroed_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int check_zeroed_user(const void *from, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/usercopy.c (c0000000007de000)
Location: lib/usercopy.c:50
Inline: False
Direct callers:
  - kernel/fork.c:copy_clone_args_from_user
  - kernel/sched/core.c:__se_sys_sched_setattr
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/events/core.c:perf_copy_attr
```
**Symbols:**

```
c0000000007de000-c0000000007de1a8: check_zeroed_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int check_zeroed_user(const void *from, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/usercopy.c (ffffffe000464e74)
Location: lib/usercopy.c:50
Inline: False
Direct callers:
  - kernel/fork.c:copy_clone_args_from_user
  - kernel/sched/core.c:__se_sys_sched_setattr
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/events/core.c:perf_copy_attr
```
**Symbols:**

```
ffffffe000464e74-ffffffe000464f08: check_zeroed_user (STB_GLOBAL)
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
int check_zeroed_user(const void *from, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/usercopy.c (ffffffff81524780)
Location: lib/usercopy.c:50
Inline: False
Direct callers:
  - kernel/fork.c:copy_clone_args_from_user
  - kernel/sched/core.c:sched_copy_attr
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/events/core.c:perf_copy_attr
```
**Symbols:**

```
ffffffff81524780-ffffffff81524841: check_zeroed_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int check_zeroed_user(const void *from, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/usercopy.c (ffffffff81514a60)
Location: lib/usercopy.c:50
Inline: False
Direct callers:
  - kernel/fork.c:copy_clone_args_from_user
  - kernel/sched/core.c:sched_copy_attr
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/events/core.c:perf_copy_attr
```
**Symbols:**

```
ffffffff81514a60-ffffffff81514b21: check_zeroed_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int check_zeroed_user(const void *from, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/usercopy.c (ffffffff81520810)
Location: lib/usercopy.c:50
Inline: False
Direct callers:
  - kernel/fork.c:copy_clone_args_from_user
  - kernel/sched/core.c:sched_copy_attr
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/events/core.c:perf_copy_attr
```
**Symbols:**

```
ffffffff81520810-ffffffff815208d1: check_zeroed_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int check_zeroed_user(const void *from, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/usercopy.c (ffffffff8153a190)
Location: lib/usercopy.c:50
Inline: False
Direct callers:
  - kernel/fork.c:copy_clone_args_from_user
  - kernel/sched/core.c:sched_copy_attr
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/events/core.c:perf_copy_attr
```
**Symbols:**

```
ffffffff8153a190-ffffffff8153a251: check_zeroed_user (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
