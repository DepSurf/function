# Function: <code>copy_struct_from_user</code>

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
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109d12c)
Location: include/linux/uaccess.h:284
Inline: True
Inline callers:
  - kernel/fork.c:copy_clone_args_from_user
```
```
In kernel/sched/core.c (ffffffff810d28be)
Location: include/linux/uaccess.h:284
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_copy_attr
```
```
In kernel/events/core.c (ffffffff812086fa)
Location: include/linux/uaccess.h:284
Inline: True
Inline callers:
  - kernel/events/core.c:perf_copy_attr
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
In kernel/fork.c (ffffffff810a3eef)
Location: include/linux/uaccess.h:284
Inline: True
Inline callers:
  - kernel/fork.c:copy_clone_args_from_user
```
```
In kernel/sched/core.c (ffffffff810de1d0)
Location: include/linux/uaccess.h:284
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_copy_attr
```
```
In kernel/events/core.c (ffffffff81233d05)
Location: include/linux/uaccess.h:284
Inline: True
Inline callers:
  - kernel/events/core.c:perf_copy_attr
```
```
In fs/open.c (ffffffff8130fb36)
Location: include/linux/uaccess.h:284
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_openat2
  - fs/open.c:__x64_sys_openat2
```
```
In fs/io_uring.c (ffffffff8137c1e9)
Location: include/linux/uaccess.h:284
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
In kernel/fork.c (ffffffff8109f57f)
Location: include/linux/uaccess.h:345
Inline: True
Inline callers:
  - kernel/fork.c:copy_clone_args_from_user
```
```
In kernel/sched/core.c (ffffffff810dac30)
Location: include/linux/uaccess.h:345
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_copy_attr
```
```
In kernel/seccomp.c (ffffffff811a2ad5)
Location: include/linux/uaccess.h:345
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_notify_addfd
```
```
In kernel/events/core.c (ffffffff8123da65)
Location: include/linux/uaccess.h:345
Inline: True
Inline callers:
  - kernel/events/core.c:perf_copy_attr
```
```
In fs/open.c (ffffffff8131bdf6)
Location: include/linux/uaccess.h:345
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_openat2
  - fs/open.c:__x64_sys_openat2
```
```
In fs/io_uring.c (ffffffff813949a4)
Location: include/linux/uaccess.h:345
Inline: True
Inline callers:
  - fs/io_uring.c:io_req_prep
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
In kernel/fork.c (ffffffff810a044c)
Location: include/linux/uaccess.h:345
Inline: True
Inline callers:
  - kernel/fork.c:copy_clone_args_from_user
```
```
In kernel/sched/core.c (ffffffff810dc780)
Location: include/linux/uaccess.h:345
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_copy_attr
```
```
In kernel/seccomp.c (ffffffff811a35a5)
Location: include/linux/uaccess.h:345
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_notify_addfd
```
```
In kernel/events/core.c (ffffffff812423f5)
Location: include/linux/uaccess.h:345
Inline: True
Inline callers:
  - kernel/events/core.c:perf_copy_attr
```
```
In fs/open.c (ffffffff81321f67)
Location: include/linux/uaccess.h:345
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_openat2
  - fs/open.c:__x64_sys_openat2
```
```
In fs/namespace.c (ffffffff8134f42c)
Location: include/linux/uaccess.h:345
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_mount_setattr
```
```
In fs/io_uring.c (ffffffff8139c5b9)
Location: include/linux/uaccess.h:345
Inline: True
Inline callers:
  - fs/io_uring.c:io_req_prep
```
```
In security/landlock/syscalls.c (ffffffff81537096)
Location: include/linux/uaccess.h:345
Inline: True
Inline callers:
  - security/landlock/syscalls.c:__ia32_sys_landlock_create_ruleset
  - security/landlock/syscalls.c:__x64_sys_landlock_create_ruleset
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
In kernel/fork.c (ffffffff810b185c)
Location: include/linux/uaccess.h:335
Inline: True
Inline callers:
  - kernel/fork.c:copy_clone_args_from_user
```
```
In kernel/sched/core.c (ffffffff810ee2b0)
Location: include/linux/uaccess.h:335
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_copy_attr
```
```
In kernel/seccomp.c (ffffffff811ccc85)
Location: include/linux/uaccess.h:335
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_notify_addfd
```
```
In kernel/events/core.c (ffffffff8127cd05)
Location: include/linux/uaccess.h:335
Inline: True
Inline callers:
  - kernel/events/core.c:perf_copy_attr
```
```
In fs/open.c (ffffffff8136f457)
Location: include/linux/uaccess.h:335
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_openat2
  - fs/open.c:__x64_sys_openat2
```
```
In fs/namespace.c (ffffffff8139d70c)
Location: include/linux/uaccess.h:335
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_mount_setattr
```
```
In fs/io_uring.c (ffffffff813e6702)
Location: include/linux/uaccess.h:335
Inline: True
Inline callers:
  - fs/io_uring.c:io_req_prep
```
```
In security/landlock/syscalls.c (ffffffff815958da)
Location: include/linux/uaccess.h:335
Inline: True
Inline callers:
  - security/landlock/syscalls.c:__ia32_sys_landlock_create_ruleset
  - security/landlock/syscalls.c:__x64_sys_landlock_create_ruleset
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
In kernel/fork.c (ffffffff810c7c8f)
Location: include/linux/uaccess.h:317
Inline: True
Inline callers:
  - kernel/fork.c:copy_clone_args_from_user
```
```
In kernel/sched/core.c (ffffffff8110bd8e)
Location: include/linux/uaccess.h:317
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_copy_attr
```
```
In kernel/seccomp.c (ffffffff81200a0c)
Location: include/linux/uaccess.h:317
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_notify_addfd
```
```
In kernel/events/core.c (ffffffff812d076b)
Location: include/linux/uaccess.h:317
Inline: True
Inline callers:
  - kernel/events/core.c:perf_copy_attr
```
```
In fs/open.c (ffffffff813ede96)
Location: include/linux/uaccess.h:317
Inline: True
Inline callers:
  - fs/open.c:__do_sys_openat2
```
```
In fs/namespace.c (ffffffff814206bb)
Location: include/linux/uaccess.h:317
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_mount_setattr
```
```
In security/landlock/syscalls.c (ffffffff81637b92)
Location: include/linux/uaccess.h:317
Inline: True
Inline callers:
  - security/landlock/syscalls.c:__ia32_sys_landlock_create_ruleset
  - security/landlock/syscalls.c:__x64_sys_landlock_create_ruleset
```
```
In io_uring/io_uring.c (ffffffff816c7eb6)
Location: include/linux/uaccess.h:317
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_openat2_prep
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
In kernel/fork.c (ffffffff810e462f)
Location: include/linux/uaccess.h:326
Inline: True
Inline callers:
  - kernel/fork.c:copy_clone_args_from_user
```
```
In kernel/sched/core.c (ffffffff8113220e)
Location: include/linux/uaccess.h:326
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_copy_attr
```
```
In kernel/seccomp.c (ffffffff8124873c)
Location: include/linux/uaccess.h:326
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_notify_addfd
```
```
In kernel/events/core.c (ffffffff81339b6b)
Location: include/linux/uaccess.h:326
Inline: True
Inline callers:
  - kernel/events/core.c:perf_copy_attr
```
```
In fs/open.c (ffffffff81476626)
Location: include/linux/uaccess.h:326
Inline: True
Inline callers:
  - fs/open.c:__do_sys_openat2
```
```
In fs/namespace.c (ffffffff814acc56)
Location: include/linux/uaccess.h:326
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_mount_setattr
```
```
In security/landlock/syscalls.c (ffffffff816eef72)
Location: include/linux/uaccess.h:326
Inline: True
Inline callers:
  - security/landlock/syscalls.c:__ia32_sys_landlock_create_ruleset
  - security/landlock/syscalls.c:__x64_sys_landlock_create_ruleset
```
```
In io_uring/openclose.c (ffffffff81794686)
Location: include/linux/uaccess.h:326
Inline: True
Inline callers:
  - io_uring/openclose.c:io_openat2_prep
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
In kernel/fork.c (ffffffff810efcbf)
Location: include/linux/uaccess.h:348
Inline: True
Inline callers:
  - kernel/fork.c:copy_clone_args_from_user
```
```
In kernel/sched/core.c (ffffffff8114047e)
Location: include/linux/uaccess.h:348
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_copy_attr
```
```
In kernel/seccomp.c (ffffffff8125fb2c)
Location: include/linux/uaccess.h:348
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_notify_addfd
```
```
In kernel/trace/trace_events_user.c (ffffffff812c5d05)
Location: include/linux/uaccess.h:348
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_events_ioctl_unreg
  - kernel/trace/trace_events_user.c:user_events_ioctl_reg
```
```
In kernel/events/core.c (ffffffff8136ac2b)
Location: include/linux/uaccess.h:348
Inline: True
Inline callers:
  - kernel/events/core.c:perf_copy_attr
```
```
In fs/open.c (ffffffff814aaed1)
Location: include/linux/uaccess.h:348
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_openat2
  - fs/open.c:__x64_sys_openat2
```
```
In fs/namespace.c (ffffffff814e1958)
Location: include/linux/uaccess.h:348
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_mount_setattr
  - fs/namespace.c:__x64_sys_mount_setattr
```
```
In security/landlock/syscalls.c (ffffffff81729412)
Location: include/linux/uaccess.h:348
Inline: True
Inline callers:
  - security/landlock/syscalls.c:__ia32_sys_landlock_create_ruleset
  - security/landlock/syscalls.c:__x64_sys_landlock_create_ruleset
```
```
In io_uring/openclose.c (ffffffff817d5366)
Location: include/linux/uaccess.h:348
Inline: True
Inline callers:
  - io_uring/openclose.c:io_openat2_prep
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
In kernel/fork.c (ffffffff810f90cf)
Location: include/linux/uaccess.h:348
Inline: True
Inline callers:
  - kernel/fork.c:copy_clone_args_from_user
```
```
In kernel/sched/core.c (ffffffff8114b52e)
Location: include/linux/uaccess.h:348
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_copy_attr
```
```
In kernel/seccomp.c (ffffffff81279c7c)
Location: include/linux/uaccess.h:348
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_notify_addfd
```
```
In kernel/trace/trace_events_user.c (ffffffff812e2545)
Location: include/linux/uaccess.h:348
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_events_ioctl_unreg
  - kernel/trace/trace_events_user.c:user_events_ioctl_reg
```
```
In kernel/events/core.c (ffffffff8139386b)
Location: include/linux/uaccess.h:348
Inline: True
Inline callers:
  - kernel/events/core.c:perf_copy_attr
```
```
In fs/open.c (ffffffff814dc371)
Location: include/linux/uaccess.h:348
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_openat2
  - fs/open.c:__x64_sys_openat2
```
```
In fs/namespace.c (ffffffff815114d3)
Location: include/linux/uaccess.h:348
Inline: True
Inline callers:
  - fs/namespace.c:copy_mnt_id_req
  - fs/namespace.c:__ia32_sys_mount_setattr
  - fs/namespace.c:__x64_sys_mount_setattr
```
```
In security/landlock/syscalls.c (ffffffff8176a8f8)
Location: include/linux/uaccess.h:348
Inline: True
Inline callers:
  - security/landlock/syscalls.c:__do_sys_landlock_create_ruleset
```
```
In io_uring/openclose.c (ffffffff818191b6)
Location: include/linux/uaccess.h:348
Inline: True
Inline callers:
  - io_uring/openclose.c:io_openat2_prep
```
```
In drivers/iommu/intel/nested.c (ffffffff81b695ec)
Location: include/linux/uaccess.h:348
Inline: True
Inline callers:
  - drivers/iommu/intel/nested.c:intel_nested_domain_alloc
  - drivers/iommu/intel/nested.c:intel_nested_cache_invalidate_user
```
```
In net/ipv4/tcp_ao.c (ffffffff82053d43)
Location: include/linux/uaccess.h:348
Inline: True
Inline callers:
  - net/ipv4/tcp_ao.c:copy_struct_from_sockptr
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
In kernel/fork.c (ffff8000100f204c)
Location: include/linux/uaccess.h:284
Inline: True
Inline callers:
  - kernel/fork.c:copy_clone_args_from_user
```
```
In kernel/sched/core.c (ffff8000101379a4)
Location: include/linux/uaccess.h:284
Inline: True
Inline callers:
  - kernel/sched/core.c:__arm64_sys_sched_setattr
```
```
In kernel/events/core.c (ffff80001029888c)
Location: include/linux/uaccess.h:284
Inline: True
Inline callers:
  - kernel/events/core.c:perf_copy_attr
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
In kernel/fork.c (c0350898)
Location: include/linux/uaccess.h:284
Inline: True
Inline callers:
  - kernel/fork.c:copy_clone_args_from_user
```
```
In kernel/sched/core.c (c038c350)
Location: include/linux/uaccess.h:284
Inline: True
Inline callers:
  - kernel/sched/core.c:__se_sys_sched_setattr
```
```
In kernel/events/core.c (c04c5418)
Location: include/linux/uaccess.h:284
Inline: True
Inline callers:
  - kernel/events/core.c:perf_copy_attr
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
In kernel/fork.c (c000000000137068)
Location: include/linux/uaccess.h:284
Inline: True
Inline callers:
  - kernel/fork.c:copy_clone_args_from_user
```
```
In kernel/sched/core.c (c000000000183044)
Location: include/linux/uaccess.h:284
Inline: True
Inline callers:
  - kernel/sched/core.c:__se_sys_sched_setattr
```
```
In kernel/events/core.c (c00000000034403c)
Location: include/linux/uaccess.h:284
Inline: True
Inline callers:
  - kernel/events/core.c:perf_copy_attr
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
In kernel/fork.c (ffffffe0000beaac)
Location: include/linux/uaccess.h:284
Inline: True
Inline callers:
  - kernel/fork.c:copy_clone_args_from_user
```
```
In kernel/sched/core.c (ffffffe0000eba12)
Location: include/linux/uaccess.h:284
Inline: True
Inline callers:
  - kernel/sched/core.c:__se_sys_sched_setattr
```
```
In kernel/events/core.c (ffffffe0001c7f9e)
Location: include/linux/uaccess.h:284
Inline: True
Inline callers:
  - kernel/events/core.c:perf_copy_attr
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
In kernel/fork.c (ffffffff81096a4c)
Location: include/linux/uaccess.h:284
Inline: True
Inline callers:
  - kernel/fork.c:copy_clone_args_from_user
```
```
In kernel/sched/core.c (ffffffff810ccc3e)
Location: include/linux/uaccess.h:284
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_copy_attr
```
```
In kernel/events/core.c (ffffffff81200d1a)
Location: include/linux/uaccess.h:284
Inline: True
Inline callers:
  - kernel/events/core.c:perf_copy_attr
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
In kernel/fork.c (ffffffff810854cc)
Location: include/linux/uaccess.h:284
Inline: True
Inline callers:
  - kernel/fork.c:copy_clone_args_from_user
```
```
In kernel/sched/core.c (ffffffff810bb43e)
Location: include/linux/uaccess.h:284
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_copy_attr
```
```
In kernel/events/core.c (ffffffff811f3a6a)
Location: include/linux/uaccess.h:284
Inline: True
Inline callers:
  - kernel/events/core.c:perf_copy_attr
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
In kernel/fork.c (ffffffff810969fc)
Location: include/linux/uaccess.h:284
Inline: True
Inline callers:
  - kernel/fork.c:copy_clone_args_from_user
```
```
In kernel/sched/core.c (ffffffff810cc15e)
Location: include/linux/uaccess.h:284
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_copy_attr
```
```
In kernel/events/core.c (ffffffff811feaea)
Location: include/linux/uaccess.h:284
Inline: True
Inline callers:
  - kernel/events/core.c:perf_copy_attr
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
In kernel/fork.c (ffffffff8109e89c)
Location: include/linux/uaccess.h:284
Inline: True
Inline callers:
  - kernel/fork.c:copy_clone_args_from_user
```
```
In kernel/sched/core.c (ffffffff810d49be)
Location: include/linux/uaccess.h:284
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_copy_attr
```
```
In kernel/events/core.c (ffffffff8120db7a)
Location: include/linux/uaccess.h:284
Inline: True
Inline callers:
  - kernel/events/core.c:perf_copy_attr
```
</details>
</li>
</ul>

## Differences
