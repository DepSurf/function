# Function: <code>__get_dumpable</code>

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
In kernel/ptrace.c (0)
Location: include/linux/sched.h:469
Inline: True
```
```
In kernel/sys.c (0)
Location: include/linux/sched.h:469
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/sched.h:469
Inline: True
```
```
In fs/coredump.c (0)
Location: include/linux/sched.h:469
Inline: True
```
```
In fs/proc/base.c (ffffffff8127b56d)
Location: include/linux/sched.h:469
Inline: True
Inline callers:
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:pid_revalidate
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:proc_pid_make_inode
```
```
In fs/proc/fd.c (ffffffff81281a5e)
Location: include/linux/sched.h:469
Inline: True
Inline callers:
  - fs/proc/fd.c:tid_fd_revalidate
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
In kernel/ptrace.c (ffffffff8108d937)
Location: include/linux/sched.h:484
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_may_access
```
```
In kernel/sys.c (ffffffff8109914c)
Location: include/linux/sched.h:484
Inline: True
Inline callers:
  - kernel/sys.c:SyS_prctl
```
```
In fs/exec.c (ffffffff812392e2)
Location: include/linux/sched.h:484
Inline: True
Inline callers:
  - fs/exec.c:install_exec_creds
```
```
In fs/coredump.c (ffffffff8129a8e3)
Location: include/linux/sched.h:484
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
```
In fs/proc/base.c (ffffffff812a9903)
Location: include/linux/sched.h:484
Inline: True
Inline callers:
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:pid_revalidate
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_pid_make_inode
```
```
In fs/proc/fd.c (ffffffff812aeb10)
Location: include/linux/sched.h:484
Inline: True
Inline callers:
  - fs/proc/fd.c:tid_fd_revalidate
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
In kernel/ptrace.c (ffffffff81092aee)
Location: include/linux/sched.h:506
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_may_access
  - kernel/ptrace.c:ptrace_access_vm
```
```
In kernel/sys.c (ffffffff8109e0fc)
Location: include/linux/sched.h:506
Inline: True
Inline callers:
  - kernel/sys.c:SyS_prctl
```
```
In fs/exec.c (ffffffff8124c022)
Location: include/linux/sched.h:506
Inline: True
Inline callers:
  - fs/exec.c:install_exec_creds
```
```
In fs/coredump.c (ffffffff812af473)
Location: include/linux/sched.h:506
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
```
In fs/proc/base.c (ffffffff812bf223)
Location: include/linux/sched.h:506
Inline: True
Inline callers:
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:pid_revalidate
  - fs/proc/base.c:pid_getattr
  - fs/proc/base.c:proc_pid_make_inode
```
```
In fs/proc/fd.c (ffffffff812c44e0)
Location: include/linux/sched.h:506
Inline: True
Inline callers:
  - fs/proc/fd.c:tid_fd_revalidate
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
In kernel/ptrace.c (ffffffff8108fc27)
Location: include/linux/sched/coredump.h:23
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_may_access
  - kernel/ptrace.c:ptrace_access_vm
```
```
In kernel/sys.c (ffffffff8109b88c)
Location: include/linux/sched/coredump.h:23
Inline: True
Inline callers:
  - kernel/sys.c:SyS_prctl
```
```
In fs/exec.c (ffffffff81258132)
Location: include/linux/sched/coredump.h:23
Inline: True
Inline callers:
  - fs/exec.c:install_exec_creds
```
```
In fs/coredump.c (ffffffff812bc8ab)
Location: include/linux/sched/coredump.h:23
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
```
In fs/proc/base.c (ffffffff812ccfb6)
Location: include/linux/sched/coredump.h:23
Inline: True
Inline callers:
  - fs/proc/base.c:task_dump_owner
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
In arch/x86/mm/tlb.c (ffffffff8107a418)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In kernel/ptrace.c (ffffffff81096af7)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_may_access
  - kernel/ptrace.c:ptrace_access_vm
```
```
In kernel/sys.c (ffffffff810a2588)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - kernel/sys.c:SyS_prctl
```
```
In fs/exec.c (ffffffff8127a399)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - fs/exec.c:install_exec_creds
```
```
In fs/coredump.c (ffffffff812e0198)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
```
In fs/proc/base.c (ffffffff812f1855)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - fs/proc/base.c:task_dump_owner
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
In arch/x86/mm/tlb.c (ffffffff8107d1b8)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In kernel/ptrace.c (ffffffff81099db5)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_may_access
  - kernel/ptrace.c:ptrace_access_vm
```
```
In kernel/sys.c (ffffffff810a88c7)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
```
```
In fs/exec.c (ffffffff812a0f12)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - fs/exec.c:install_exec_creds
```
```
In fs/coredump.c (ffffffff8130c374)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
```
In fs/proc/base.c (ffffffff8131e739)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - fs/proc/base.c:task_dump_owner
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
In kernel/ptrace.c (ffffffff810a21f5)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_may_access
  - kernel/ptrace.c:ptrace_access_vm
```
```
In kernel/sys.c (ffffffff810b16c2)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
```
```
In fs/exec.c (ffffffff812b5f12)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - fs/exec.c:install_exec_creds
```
```
In fs/coredump.c (ffffffff81321bd4)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
```
In fs/proc/base.c (ffffffff81335829)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - fs/proc/base.c:task_dump_owner
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
In kernel/ptrace.c (ffffffff810a6e97)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_may_access
  - kernel/ptrace.c:ptrace_access_vm
```
```
In kernel/sys.c (ffffffff810b6f48)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
```
```
In fs/exec.c (ffffffff812d2c9f)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - fs/exec.c:install_exec_creds
```
```
In fs/coredump.c (ffffffff81349a09)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
```
In fs/proc/base.c (ffffffff8135d89f)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - fs/proc/base.c:task_dump_owner
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
In kernel/ptrace.c (ffffffff810ad202)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_may_access
  - kernel/ptrace.c:ptrace_access_vm
```
```
In kernel/sys.c (ffffffff810bd41b)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
```
```
In fs/exec.c (ffffffff812e47af)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - fs/exec.c:install_exec_creds
```
```
In fs/coredump.c (ffffffff81361ca9)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
```
In fs/proc/base.c (ffffffff81375aff)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - fs/proc/base.c:task_dump_owner
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
In kernel/ptrace.c (ffffffff810b507b)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_may_access
```
```
In kernel/sys.c (ffffffff810c4bf3)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prctl
```
```
In fs/exec.c (ffffffff8131e6ac)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - fs/exec.c:begin_new_exec
```
```
In fs/coredump.c (ffffffff813a7f3a)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:format_corename
```
```
In fs/proc/base.c (ffffffff813be5b4)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - fs/proc/base.c:task_dump_owner
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
In kernel/ptrace.c (ffffffff810b0294)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_may_access
```
```
In kernel/sys.c (ffffffff810bfff7)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prctl
```
```
In fs/exec.c (ffffffff81329c7a)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - fs/exec.c:begin_new_exec
```
```
In fs/coredump.c (ffffffff813b8fba)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:format_corename
```
```
In fs/proc/base.c (ffffffff813d0305)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - fs/proc/base.c:task_dump_owner
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
In kernel/ptrace.c (ffffffff810b1808)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_may_access
```
```
In kernel/sys.c (ffffffff810c1a76)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prctl
```
```
In fs/exec.c (ffffffff8132fb8f)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - fs/exec.c:begin_new_exec
```
```
In fs/coredump.c (ffffffff813bff19)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
```
In fs/proc/base.c (ffffffff813d7225)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - fs/proc/base.c:task_dump_owner
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
In kernel/ptrace.c (ffffffff810c38f8)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_may_access
```
```
In kernel/sys.c (ffffffff810d47d8)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prctl
```
```
In fs/exec.c (ffffffff8137d3b6)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - fs/exec.c:begin_new_exec
```
```
In fs/coredump.c (ffffffff8140fd49)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
```
In fs/proc/base.c (ffffffff81428965)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - fs/proc/base.c:task_dump_owner
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
In kernel/ptrace.c (ffffffff810db064)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_may_access
```
```
In kernel/sys.c (ffffffff810ed4c7)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prctl
```
```
In fs/exec.c (ffffffff813fcfaa)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - fs/exec.c:begin_new_exec
```
```
In fs/coredump.c (ffffffff81485709)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
```
In fs/proc/base.c (ffffffff814a1c78)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - fs/proc/base.c:task_dump_owner
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
In kernel/ptrace.c (ffffffff810fb1b4)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_may_access
```
```
In kernel/sys.c (ffffffff8110e8e7)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prctl
```
```
In fs/exec.c (ffffffff81486b08)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - fs/exec.c:begin_new_exec
```
```
In fs/coredump.c (ffffffff81518d72)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
```
In fs/proc/base.c (ffffffff81536d28)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - fs/proc/base.c:task_dump_owner
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
In kernel/ptrace.c (ffffffff81107474)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_may_access
```
```
In kernel/sys.c (ffffffff8111aac5)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prctl
```
```
In fs/exec.c (ffffffff814bb8da)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - fs/exec.c:begin_new_exec
```
```
In fs/coredump.c (ffffffff81550672)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
```
In fs/proc/base.c (ffffffff8156ef08)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - fs/proc/base.c:task_dump_owner
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
In kernel/ptrace.c (ffffffff81110dc4)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_may_access
```
```
In kernel/sys.c (ffffffff81124594)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_prctl
```
```
In fs/exec.c (ffffffff814ede4a)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - fs/exec.c:begin_new_exec
```
```
In fs/coredump.c (ffffffff81586502)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
```
In fs/proc/base.c (ffffffff815a78c8)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - fs/proc/base.c:task_dump_owner
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
In kernel/ptrace.c (ffff8000101069f0)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_may_access
  - kernel/ptrace.c:ptrace_access_vm
```
```
In kernel/sys.c (ffff80001011a3e0)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - kernel/sys.c:__arm64_sys_prctl
```
```
In fs/exec.c (ffff80001038c084)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - fs/exec.c:install_exec_creds
```
```
In fs/coredump.c (ffff800010428394)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
```
In fs/proc/base.c (ffff800010440e44)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - fs/proc/base.c:task_dump_owner
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
In kernel/ptrace.c (c036168c)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_may_access
  - kernel/ptrace.c:ptrace_access_vm
```
```
In kernel/sys.c (c036e888)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - kernel/sys.c:__se_sys_prctl
```
```
In fs/exec.c (c0574008)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - fs/exec.c:install_exec_creds
```
```
In fs/coredump.c (c05f101c)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
  - fs/coredump.c:format_corename
```
```
In fs/proc/base.c (c0606810)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - fs/proc/base.c:task_dump_owner
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
In kernel/ptrace.c (c00000000014df54)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_may_access
  - kernel/ptrace.c:ptrace_access_vm
```
```
In kernel/sys.c (c000000000161d70)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - kernel/sys.c:__se_sys_prctl
```
```
In fs/exec.c (c000000000483c44)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - fs/exec.c:install_exec_creds
```
```
In fs/coredump.c (c000000000538530)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
```
In fs/proc/base.c (c000000000555d40)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - fs/proc/base.c:task_dump_owner
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
In kernel/ptrace.c (ffffffe0000cb710)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_may_access
  - kernel/ptrace.c:ptrace_access_vm
```
```
In kernel/sys.c (ffffffe0000d4cd4)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - kernel/sys.c:__se_sys_prctl
```
```
In fs/exec.c (ffffffe00025d630)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - fs/exec.c:install_exec_creds
```
```
In fs/coredump.c (ffffffe0002c6616)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
```
In fs/proc/base.c (ffffffe0002d7e8c)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - fs/proc/base.c:task_dump_owner
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
In kernel/ptrace.c (ffffffff810a7572)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_may_access
  - kernel/ptrace.c:ptrace_access_vm
```
```
In kernel/sys.c (ffffffff810b778b)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
```
```
In fs/exec.c (ffffffff812dcd8f)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - fs/exec.c:install_exec_creds
```
```
In fs/coredump.c (ffffffff8135a289)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
```
In fs/proc/base.c (ffffffff8136e0df)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - fs/proc/base.c:task_dump_owner
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
In kernel/ptrace.c (ffffffff81095f52)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_may_access
  - kernel/ptrace.c:ptrace_access_vm
```
```
In kernel/sys.c (ffffffff810a60cb)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
```
```
In fs/exec.c (ffffffff812cda0f)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - fs/exec.c:install_exec_creds
```
```
In fs/coredump.c (ffffffff8134af39)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
```
In fs/proc/base.c (ffffffff8135eb6f)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - fs/proc/base.c:task_dump_owner
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
In kernel/ptrace.c (ffffffff810a6ad2)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_may_access
  - kernel/ptrace.c:ptrace_access_vm
```
```
In kernel/sys.c (ffffffff810b6ceb)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
```
```
In fs/exec.c (ffffffff812dab9f)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - fs/exec.c:install_exec_creds
```
```
In fs/coredump.c (ffffffff81357d59)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
```
In fs/proc/base.c (ffffffff8136bbaf)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - fs/proc/base.c:task_dump_owner
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
In kernel/ptrace.c (ffffffff810aec30)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_may_access
  - kernel/ptrace.c:ptrace_access_vm
```
```
In kernel/sys.c (ffffffff810bf06b)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
```
```
In fs/exec.c (ffffffff812eba9f)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - fs/exec.c:install_exec_creds
```
```
In fs/coredump.c (ffffffff8136b439)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:do_coredump
```
```
In fs/proc/base.c (ffffffff8137f45a)
Location: include/linux/sched/coredump.h:24
Inline: True
Inline callers:
  - fs/proc/base.c:task_dump_owner
```
</details>
</li>
</ul>

## Differences
