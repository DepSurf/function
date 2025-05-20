# Function: <code>do_exit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void do_exit(long int code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810838c0)
Location: kernel/exit.c:653
Inline: False
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/kernel/dumpstack.c:oops_end
  - kernel/exit.c:complete_and_exit
  - kernel/exit.c:SyS_exit
  - kernel/exit.c:do_group_exit
  - kernel/kmod.c:call_usermodehelper_exec_async
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
  - kernel/reboot.c:SYSC_reboot
  - kernel/reboot.c:SYSC_reboot
  - kernel/module.c:__module_put_and_exit
  - kernel/pid_namespace.c:reboot_pid_ns
  - kernel/seccomp.c:seccomp_phase2
  - fs/buffer.c:SyS_bdflush
```
**Symbols:**

```
ffffffff810838c0-ffffffff8108439b: do_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void do_exit(long int code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810869e0)
Location: kernel/exit.c:728
Inline: False
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - kernel/exit.c:do_group_exit
  - kernel/exit.c:SyS_exit
  - kernel/exit.c:complete_and_exit
  - kernel/kmod.c:call_usermodehelper_exec_async
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
  - kernel/reboot.c:SYSC_reboot
  - kernel/reboot.c:SYSC_reboot
  - kernel/module.c:__module_put_and_exit
  - kernel/pid_namespace.c:reboot_pid_ns
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - fs/buffer.c:SyS_bdflush
```
**Symbols:**

```
ffffffff810869e0-ffffffff810874f6: do_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void do_exit(long int code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8108b950)
Location: kernel/exit.c:737
Inline: False
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - kernel/exit.c:do_group_exit
  - kernel/exit.c:SyS_exit
  - kernel/exit.c:complete_and_exit
  - kernel/kmod.c:call_usermodehelper_exec_async
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
  - kernel/reboot.c:SYSC_reboot
  - kernel/reboot.c:SYSC_reboot
  - kernel/module.c:__module_put_and_exit
  - kernel/pid_namespace.c:reboot_pid_ns
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - fs/buffer.c:SyS_bdflush
```
**Symbols:**

```
ffffffff8108b950-ffffffff8108c459: do_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void do_exit(long int code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff81088ae0)
Location: kernel/exit.c:763
Inline: False
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - kernel/exit.c:do_group_exit
  - kernel/exit.c:SyS_exit
  - kernel/exit.c:complete_and_exit
  - kernel/kmod.c:call_usermodehelper_exec_async
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
  - kernel/reboot.c:SYSC_reboot
  - kernel/reboot.c:SYSC_reboot
  - kernel/module.c:__module_put_and_exit
  - kernel/pid_namespace.c:reboot_pid_ns
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - fs/buffer.c:SyS_bdflush
```
**Symbols:**

```
ffffffff81088ae0-ffffffff810895c5: do_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void do_exit(long int code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8108f810)
Location: kernel/exit.c:763
Inline: False
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - kernel/exit.c:do_group_exit
  - kernel/exit.c:SyS_exit
  - kernel/exit.c:complete_and_exit
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
  - kernel/reboot.c:SYSC_reboot
  - kernel/reboot.c:SYSC_reboot
  - kernel/module.c:__module_put_and_exit
  - kernel/pid_namespace.c:reboot_pid_ns
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - fs/buffer.c:SyS_bdflush
```
**Symbols:**

```
ffffffff8108f810-ffffffff8109034e: do_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void do_exit(long int code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/exit.c (0)
Location: kernel/exit.c:763
Inline: False
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - kernel/exit.c:do_group_exit
  - kernel/exit.c:__ia32_sys_exit
  - kernel/exit.c:__x64_sys_exit
  - kernel/exit.c:complete_and_exit
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
  - kernel/reboot.c:__do_sys_reboot
  - kernel/reboot.c:__do_sys_reboot
  - kernel/module.c:__module_put_and_exit
  - kernel/pid_namespace.c:reboot_pid_ns
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - fs/buffer.c:__ia32_sys_bdflush
  - fs/buffer.c:__x64_sys_bdflush
```
**Symbols:**

```
ffffffff8109428b-ffffffff81094344: do_exit.cold.23 (STB_LOCAL)
ffffffff81093380-ffffffff81093dee: do_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void do_exit(long int code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/exit.c (0)
Location: kernel/exit.c:773
Inline: False
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - kernel/exit.c:do_group_exit
  - kernel/exit.c:__ia32_sys_exit
  - kernel/exit.c:__x64_sys_exit
  - kernel/exit.c:complete_and_exit
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
  - kernel/reboot.c:__do_sys_reboot
  - kernel/reboot.c:__do_sys_reboot
  - kernel/module.c:__module_put_and_exit
  - kernel/pid_namespace.c:reboot_pid_ns
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - fs/buffer.c:__ia32_sys_bdflush
  - fs/buffer.c:__x64_sys_bdflush
```
**Symbols:**

```
ffffffff8109c62b-ffffffff8109c6a0: do_exit.cold.24 (STB_LOCAL)
ffffffff8109b640-ffffffff8109c16b: do_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void do_exit(long int code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/exit.c (0)
Location: kernel/exit.c:777
Inline: False
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - kernel/exit.c:do_group_exit
  - kernel/exit.c:__ia32_sys_exit
  - kernel/exit.c:__x64_sys_exit
  - kernel/exit.c:complete_and_exit
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
  - kernel/reboot.c:__do_sys_reboot
  - kernel/reboot.c:__do_sys_reboot
  - kernel/module.c:__module_put_and_exit
  - kernel/pid_namespace.c:reboot_pid_ns
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - fs/buffer.c:__ia32_sys_bdflush
  - fs/buffer.c:__x64_sys_bdflush
```
**Symbols:**

```
ffffffff810a0c4b-ffffffff810a0d17: do_exit.cold (STB_LOCAL)
ffffffff8109fca0-ffffffff810a078e: do_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void do_exit(long int code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/exit.c (0)
Location: kernel/exit.c:711
Inline: False
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - kernel/exit.c:do_group_exit
  - kernel/exit.c:__ia32_sys_exit
  - kernel/exit.c:__x64_sys_exit
  - kernel/exit.c:complete_and_exit
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
  - kernel/reboot.c:__do_sys_reboot
  - kernel/reboot.c:__do_sys_reboot
  - kernel/module.c:__module_put_and_exit
  - kernel/pid_namespace.c:reboot_pid_ns
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - fs/buffer.c:__ia32_sys_bdflush
  - fs/buffer.c:__x64_sys_bdflush
```
**Symbols:**

```
ffffffff810a722b-ffffffff810a72db: do_exit.cold (STB_LOCAL)
ffffffff810a62b0-ffffffff810a6d66: do_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void do_exit(long int code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/exit.c (0)
Location: kernel/exit.c:708
Inline: False
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - kernel/exit.c:do_group_exit
  - kernel/exit.c:__ia32_sys_exit
  - kernel/exit.c:__x64_sys_exit
  - kernel/exit.c:complete_and_exit
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
  - kernel/reboot.c:__do_sys_reboot
  - kernel/reboot.c:__do_sys_reboot
  - kernel/module.c:__module_put_and_exit
  - kernel/pid_namespace.c:reboot_pid_ns
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - fs/buffer.c:__ia32_sys_bdflush
  - fs/buffer.c:__x64_sys_bdflush
```
**Symbols:**

```
ffffffff810ae97b-ffffffff810aea22: do_exit.cold (STB_LOCAL)
ffffffff810ae080-ffffffff810ae4b5: do_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void do_exit(long int code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/exit.c (0)
Location: kernel/exit.c:727
Inline: False
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - kernel/exit.c:do_group_exit
  - kernel/exit.c:__ia32_sys_exit
  - kernel/exit.c:__x64_sys_exit
  - kernel/exit.c:complete_and_exit
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
  - kernel/reboot.c:__do_sys_reboot
  - kernel/reboot.c:__do_sys_reboot
  - kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch
  - kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch
  - kernel/module.c:__module_put_and_exit
  - kernel/pid_namespace.c:reboot_pid_ns
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - fs/buffer.c:__ia32_sys_bdflush
  - fs/buffer.c:__x64_sys_bdflush
```
**Symbols:**

```
ffffffff81bdb73e-ffffffff81bdb7ee: do_exit.cold (STB_LOCAL)
ffffffff810a9730-ffffffff810a9b10: do_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void do_exit(long int code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/exit.c (0)
Location: kernel/exit.c:727
Inline: False
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - kernel/exit.c:do_group_exit
  - kernel/exit.c:__ia32_sys_exit
  - kernel/exit.c:__x64_sys_exit
  - kernel/exit.c:complete_and_exit
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
  - kernel/reboot.c:__do_sys_reboot
  - kernel/reboot.c:__do_sys_reboot
  - kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch
  - kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch
  - kernel/module.c:__module_put_and_exit
  - kernel/pid_namespace.c:reboot_pid_ns
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - fs/buffer.c:__ia32_sys_bdflush
  - fs/buffer.c:__x64_sys_bdflush
  - fs/io_uring.c:io_sq_thread
  - fs/io-wq.c:io_wqe_worker
```
**Symbols:**

```
ffffffff81bcd830-ffffffff81bcd8e0: do_exit.cold (STB_LOCAL)
ffffffff810aa770-ffffffff810aab3b: do_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void do_exit(long int code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/exit.c (0)
Location: kernel/exit.c:727
Inline: False
Direct callers:
  - kernel/exit.c:do_group_exit
  - kernel/exit.c:__ia32_sys_exit
  - kernel/exit.c:__x64_sys_exit
  - kernel/exit.c:complete_and_exit
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
  - kernel/reboot.c:__do_sys_reboot
  - kernel/reboot.c:__do_sys_reboot
  - kernel/module.c:__module_put_and_exit
  - kernel/pid_namespace.c:reboot_pid_ns
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - fs/io_uring.c:io_sq_thread
  - fs/io-wq.c:io_wqe_worker
```
**Symbols:**

```
ffffffff81ca4186-ffffffff81ca4226: do_exit.cold (STB_LOCAL)
ffffffff810bc2a0-ffffffff810bc65f: do_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void do_exit(long int code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/exit.c (0)
Location: kernel/exit.c:736
Inline: False
Direct callers:
  - kernel/exit.c:do_group_exit
  - kernel/exit.c:__ia32_sys_exit
  - kernel/exit.c:__x64_sys_exit
  - kernel/exit.c:make_task_dead
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/kthread.c:kthread_exit
  - kernel/reboot.c:__do_sys_reboot
  - kernel/reboot.c:__do_sys_reboot
  - kernel/pid_namespace.c:reboot_pid_ns
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - io_uring/io_uring.c:io_sq_thread
  - io_uring/io-wq.c:io_wqe_worker
```
**Symbols:**

```
ffffffff81e53a22-ffffffff81e53a37: do_exit.cold (STB_LOCAL)
ffffffff810d2d20-ffffffff810d33be: do_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void do_exit(long int code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810f1840)
Location: kernel/exit.c:805
Inline: False
Direct callers:
  - kernel/exit.c:do_group_exit
  - kernel/exit.c:__ia32_sys_exit
  - kernel/exit.c:__x64_sys_exit
  - kernel/exit.c:make_task_dead
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/kthread.c:kthread_exit
  - kernel/reboot.c:__do_sys_reboot
  - kernel/reboot.c:__do_sys_reboot
  - kernel/pid_namespace.c:reboot_pid_ns
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - io_uring/sqpoll.c:io_sq_thread
  - io_uring/io-wq.c:io_wqe_worker
```
**Symbols:**

```
ffffffff810f1840-ffffffff810f1ef8: do_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void do_exit(long int code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810fd790)
Location: kernel/exit.c:809
Inline: False
Direct callers:
  - kernel/exit.c:do_group_exit
  - kernel/exit.c:__ia32_sys_exit
  - kernel/exit.c:__x64_sys_exit
  - kernel/exit.c:make_task_dead
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/kthread.c:kthread_exit
  - kernel/reboot.c:__do_sys_reboot
  - kernel/reboot.c:__do_sys_reboot
  - kernel/vhost_task.c:vhost_task_fn
  - kernel/pid_namespace.c:reboot_pid_ns
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - io_uring/sqpoll.c:io_sq_thread
  - io_uring/io-wq.c:io_wq_worker
```
**Symbols:**

```
ffffffff810fd790-ffffffff810fde74: do_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void do_exit(long int code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff81106600)
Location: kernel/exit.c:811
Inline: False
Direct callers:
  - kernel/exit.c:do_group_exit
  - kernel/exit.c:__ia32_sys_exit
  - kernel/exit.c:__x64_sys_exit
  - kernel/exit.c:make_task_dead
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/kthread.c:kthread_exit
  - kernel/reboot.c:__do_sys_reboot
  - kernel/reboot.c:__do_sys_reboot
  - kernel/vhost_task.c:vhost_task_fn
  - kernel/pid_namespace.c:reboot_pid_ns
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - io_uring/sqpoll.c:io_sq_thread
  - io_uring/io-wq.c:io_wq_worker
```
**Symbols:**

```
ffffffff81106600-ffffffff81106b22: do_exit (STB_GLOBAL)
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
void do_exit(long int code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffff8000100fd260)
Location: kernel/exit.c:711
Inline: False
Direct callers:
  - arch/arm64/kernel/traps.c:die
  - arch/arm64/mm/fault.c:die_kernel_fault
  - kernel/exit.c:do_group_exit
  - kernel/exit.c:__arm64_sys_exit
  - kernel/exit.c:complete_and_exit
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
  - kernel/reboot.c:__do_sys_reboot
  - kernel/reboot.c:__do_sys_reboot
  - kernel/module.c:__module_put_and_exit
  - kernel/pid_namespace.c:reboot_pid_ns
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - fs/buffer.c:__arm64_sys_bdflush
```
**Symbols:**

```
ffff8000100fd260-ffff8000100fdc64: do_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void do_exit(long int code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (c035a30c)
Location: kernel/exit.c:711
Inline: False
Direct callers:
  - arch/arm/kernel/traps.c:die
  - kernel/exit.c:do_group_exit
  - kernel/exit.c:__se_sys_exit
  - kernel/exit.c:complete_and_exit
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
  - kernel/reboot.c:__do_sys_reboot
  - kernel/reboot.c:__do_sys_reboot
  - kernel/module.c:__module_put_and_exit
  - kernel/pid_namespace.c:reboot_pid_ns
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - fs/buffer.c:__se_sys_bdflush
```
**Symbols:**

```
c035a30c-c035aec0: do_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void do_exit(long int code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (c000000000144060)
Location: kernel/exit.c:711
Inline: False
Direct callers:
  - arch/powerpc/kernel/signal_32.c:__do_compat_sys_swapcontext
  - arch/powerpc/kernel/signal_64.c:__se_sys_swapcontext
  - kernel/exit.c:do_group_exit
  - kernel/exit.c:__se_sys_exit
  - kernel/exit.c:complete_and_exit
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
  - kernel/reboot.c:__do_sys_reboot
  - kernel/reboot.c:__do_sys_reboot
  - kernel/module.c:__module_put_and_exit
  - kernel/pid_namespace.c:reboot_pid_ns
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - fs/buffer.c:__se_sys_bdflush
```
**Symbols:**

```
c000000000144060-c000000000144d28: do_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void do_exit(long int code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffe0000c5b14)
Location: kernel/exit.c:711
Inline: False
Direct callers:
  - arch/riscv/kernel/traps.c:die
  - arch/riscv/mm/fault.c:do_page_fault
  - kernel/exit.c:do_group_exit
  - kernel/exit.c:__se_sys_exit
  - kernel/exit.c:complete_and_exit
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
  - kernel/reboot.c:__do_sys_reboot
  - kernel/reboot.c:__do_sys_reboot
  - kernel/module.c:__module_put_and_exit
  - kernel/pid_namespace.c:reboot_pid_ns
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - fs/buffer.c:__se_sys_bdflush
```
**Symbols:**

```
ffffffe0000c5b14-ffffffe0000c63ea: do_exit (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void do_exit(long int code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/exit.c (0)
Location: kernel/exit.c:711
Inline: False
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - kernel/exit.c:do_group_exit
  - kernel/exit.c:__ia32_sys_exit
  - kernel/exit.c:__x64_sys_exit
  - kernel/exit.c:complete_and_exit
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
  - kernel/reboot.c:__do_sys_reboot
  - kernel/reboot.c:__do_sys_reboot
  - kernel/module.c:__module_put_and_exit
  - kernel/pid_namespace.c:reboot_pid_ns
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - fs/buffer.c:__ia32_sys_bdflush
  - fs/buffer.c:__x64_sys_bdflush
```
**Symbols:**

```
ffffffff810a0b4b-ffffffff810a0bfb: do_exit.cold (STB_LOCAL)
ffffffff8109fbd0-ffffffff810a0686: do_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void do_exit(long int code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/exit.c (0)
Location: kernel/exit.c:711
Inline: False
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - kernel/exit.c:do_group_exit
  - kernel/exit.c:__ia32_sys_exit
  - kernel/exit.c:__x64_sys_exit
  - kernel/exit.c:complete_and_exit
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
  - kernel/reboot.c:__do_sys_reboot
  - kernel/reboot.c:__do_sys_reboot
  - kernel/module.c:__module_put_and_exit
  - kernel/pid_namespace.c:reboot_pid_ns
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - fs/buffer.c:__ia32_sys_bdflush
  - fs/buffer.c:__x64_sys_bdflush
```
**Symbols:**

```
ffffffff8108f56b-ffffffff8108f61b: do_exit.cold (STB_LOCAL)
ffffffff8108e600-ffffffff8108f0a6: do_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void do_exit(long int code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/exit.c (0)
Location: kernel/exit.c:711
Inline: False
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - kernel/exit.c:do_group_exit
  - kernel/exit.c:__ia32_sys_exit
  - kernel/exit.c:__x64_sys_exit
  - kernel/exit.c:complete_and_exit
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
  - kernel/reboot.c:__do_sys_reboot
  - kernel/reboot.c:__do_sys_reboot
  - kernel/module.c:__module_put_and_exit
  - kernel/pid_namespace.c:reboot_pid_ns
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - fs/buffer.c:__ia32_sys_bdflush
  - fs/buffer.c:__x64_sys_bdflush
```
**Symbols:**

```
ffffffff810a0afb-ffffffff810a0bab: do_exit.cold (STB_LOCAL)
ffffffff8109fb80-ffffffff810a0636: do_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void do_exit(long int code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/exit.c (0)
Location: kernel/exit.c:711
Inline: False
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - kernel/exit.c:do_group_exit
  - kernel/exit.c:__ia32_sys_exit
  - kernel/exit.c:__x64_sys_exit
  - kernel/exit.c:complete_and_exit
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
  - kernel/reboot.c:__do_sys_reboot
  - kernel/reboot.c:__do_sys_reboot
  - kernel/module.c:__module_put_and_exit
  - kernel/pid_namespace.c:reboot_pid_ns
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - fs/buffer.c:__ia32_sys_bdflush
  - fs/buffer.c:__x64_sys_bdflush
```
**Symbols:**

```
ffffffff810a8a7b-ffffffff810a8b2b: do_exit.cold (STB_LOCAL)
ffffffff810a7af0-ffffffff810a85c1: do_exit (STB_GLOBAL)
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
