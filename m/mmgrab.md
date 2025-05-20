# Function: <code>mmgrab</code>

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
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8103eb58)
Location: include/linux/sched/mm.h:32
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In kernel/exit.c (ffffffff81088cf4)
Location: include/linux/sched/mm.h:32
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/sched/core.c (ffffffff820c37a6)
Location: include/linux/sched/mm.h:32
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:__schedule
```
```
In kernel/futex.c (ffffffff8110fe89)
Location: include/linux/sched/mm.h:32
Inline: True
```
```
In mm/oom_kill.c (ffffffff811bd468)
Location: include/linux/sched/mm.h:32
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/mmu_context.c (ffffffff811e1f57)
Location: include/linux/sched/mm.h:32
Inline: True
Inline callers:
  - mm/mmu_context.c:use_mm
```
```
In mm/mmu_notifier.c (ffffffff8121f90b)
Location: include/linux/sched/mm.h:32
Inline: True
Inline callers:
  - mm/mmu_notifier.c:do_mmu_notifier_register
```
```
In mm/ksm.c (ffffffff812236a2)
Location: include/linux/sched/mm.h:32
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_enter
```
```
In mm/khugepaged.c (ffffffff8123a891)
Location: include/linux/sched/mm.h:32
Inline: True
Inline callers:
  - mm/khugepaged.c:__khugepaged_enter
```
```
In fs/userfaultfd.c (ffffffff812a57be)
Location: include/linux/sched/mm.h:32
Inline: True
Inline callers:
  - fs/userfaultfd.c:SyS_userfaultfd
```
```
In fs/proc/base.c (ffffffff812cc1a9)
Location: include/linux/sched/mm.h:32
Inline: True
Inline callers:
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:proc_mem_open
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
In arch/x86/kernel/cpu/common.c (ffffffff810417de)
Location: include/linux/sched/mm.h:33
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In kernel/exit.c (ffffffff8108fa3a)
Location: include/linux/sched/mm.h:33
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/sched/core.c (ffffffff826cb7f2)
Location: include/linux/sched/mm.h:33
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:__schedule
```
```
In kernel/futex.c (ffffffff8111b17d)
Location: include/linux/sched/mm.h:33
Inline: True
```
```
In mm/oom_kill.c (ffffffff811d208d)
Location: include/linux/sched/mm.h:33
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/mmu_context.c (ffffffff811f7ef7)
Location: include/linux/sched/mm.h:33
Inline: True
Inline callers:
  - mm/mmu_context.c:use_mm
```
```
In mm/mmu_notifier.c (ffffffff8123ab1b)
Location: include/linux/sched/mm.h:33
Inline: True
Inline callers:
  - mm/mmu_notifier.c:do_mmu_notifier_register
```
```
In mm/ksm.c (ffffffff8123ece2)
Location: include/linux/sched/mm.h:33
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_enter
```
```
In mm/khugepaged.c (ffffffff8125a121)
Location: include/linux/sched/mm.h:33
Inline: True
Inline callers:
  - mm/khugepaged.c:__khugepaged_enter
```
```
In fs/userfaultfd.c (ffffffff812c8cce)
Location: include/linux/sched/mm.h:33
Inline: True
Inline callers:
  - fs/userfaultfd.c:SyS_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
```
```
In fs/proc/base.c (ffffffff812f094a)
Location: include/linux/sched/mm.h:33
Inline: True
Inline callers:
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:proc_mem_open
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
In arch/x86/kernel/cpu/common.c (ffffffff810430b1)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In kernel/exit.c (ffffffff810935a0)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/sched/core.c (ffffffff826f5941)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:__schedule
```
```
In kernel/futex.c (ffffffff81127f15)
Location: include/linux/sched/mm.h:34
Inline: True
```
```
In mm/oom_kill.c (ffffffff811f3c92)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/mmu_context.c (ffffffff812191a9)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - mm/mmu_context.c:use_mm
```
```
In mm/mmu_notifier.c (ffffffff8125e1af)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - mm/mmu_notifier.c:do_mmu_notifier_register
```
```
In mm/ksm.c (ffffffff81262482)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_enter
```
```
In mm/khugepaged.c (ffffffff8127de42)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - mm/khugepaged.c:__khugepaged_enter
```
```
In fs/userfaultfd.c (ffffffff812ef8d7)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - fs/userfaultfd.c:__ia32_sys_userfaultfd
  - fs/userfaultfd.c:__x64_sys_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
```
```
In fs/proc/base.c (ffffffff8131dfd9)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:proc_mem_open
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
In arch/x86/kernel/cpu/common.c (ffffffff81044719)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In kernel/exit.c (ffffffff8109b85f)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/sched/core.c (ffffffff828ac786)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:__schedule
```
```
In kernel/futex.c (ffffffff81133755)
Location: include/linux/sched/mm.h:34
Inline: True
```
```
In mm/oom_kill.c (ffffffff81204927)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/mmu_context.c (ffffffff8122c109)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - mm/mmu_context.c:use_mm
```
```
In mm/mmu_notifier.c (ffffffff81272a31)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - mm/mmu_notifier.c:do_mmu_notifier_register
```
```
In mm/ksm.c (ffffffff81276d02)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_enter
```
```
In mm/khugepaged.c (ffffffff81292522)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - mm/khugepaged.c:__khugepaged_enter
```
```
In fs/userfaultfd.c (ffffffff81304257)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - fs/userfaultfd.c:__ia32_sys_userfaultfd
  - fs/userfaultfd.c:__x64_sys_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
```
```
In fs/proc/base.c (ffffffff81335409)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:proc_mem_open
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
In arch/x86/kernel/cpu/common.c (ffffffff81046cee)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In kernel/exit.c (ffffffff8109fece)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/sched/core.c (ffffffff828c5033)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:__schedule
```
```
In kernel/futex.c (ffffffff8113e701)
Location: include/linux/sched/mm.h:34
Inline: True
```
```
In mm/oom_kill.c (ffffffff8121c098)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/mmu_context.c (ffffffff8123be19)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - mm/mmu_context.c:use_mm
```
```
In mm/mmu_notifier.c (ffffffff8128e01c)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - mm/mmu_notifier.c:do_mmu_notifier_register
```
```
In mm/ksm.c (ffffffff8129256f)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_enter
```
```
In mm/khugepaged.c (ffffffff812acf0f)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - mm/khugepaged.c:__khugepaged_enter
```
```
In mm/hmm.c (ffffffff812c4231)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - mm/hmm.c:hmm_mirror_register
```
```
In fs/userfaultfd.c (ffffffff81325536)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - fs/userfaultfd.c:__ia32_sys_userfaultfd
  - fs/userfaultfd.c:__x64_sys_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
```
```
In fs/io_uring.c (ffffffff813311f3)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
```
```
In fs/proc/base.c (ffffffff8135cf63)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:proc_mem_open
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
In arch/x86/kernel/cpu/common.c (ffffffff8104746e)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In kernel/exit.c (ffffffff810a654c)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/sched/core.c (ffffffff828cd66d)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:__schedule
```
```
In kernel/futex.c (ffffffff8114a225)
Location: include/linux/sched/mm.h:34
Inline: True
```
```
In mm/oom_kill.c (ffffffff81229a2a)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/mmu_context.c (ffffffff8124a269)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - mm/mmu_context.c:use_mm
```
```
In mm/mmu_notifier.c (ffffffff8129db6c)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_notifier_register
```
```
In mm/ksm.c (ffffffff812a22ef)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_enter
```
```
In mm/khugepaged.c (ffffffff812bdb0f)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - mm/khugepaged.c:__khugepaged_enter
```
```
In fs/userfaultfd.c (ffffffff813382c6)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - fs/userfaultfd.c:__ia32_sys_userfaultfd
  - fs/userfaultfd.c:__x64_sys_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
```
```
In fs/io_uring.c (ffffffff81344dac)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
```
```
In fs/proc/base.c (ffffffff813756d3)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:proc_mem_open
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
In arch/x86/kernel/cpu/common.c (ffffffff8104b1c0)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In kernel/exit.c (ffffffff810adfb4)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - kernel/exit.c:exit_mm
```
```
In kernel/kthread.c (ffffffff810d1376)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_use_mm
```
```
In kernel/sched/core.c (ffffffff82ceea76)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:__schedule
```
```
In mm/oom_kill.c (ffffffff8125687d)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/mmu_notifier.c (ffffffff812d1cd8)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_interval_notifier_insert
  - mm/mmu_notifier.c:__mmu_notifier_register
```
```
In mm/ksm.c (ffffffff812d69ff)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_enter
```
```
In mm/khugepaged.c (ffffffff812f330f)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - mm/khugepaged.c:__khugepaged_enter
```
```
In fs/userfaultfd.c (ffffffff813720bf)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - fs/userfaultfd.c:__do_sys_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
```
```
In fs/io_uring.c (ffffffff8137eed2)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_offload_start
  - fs/io_uring.c:io_queue_async_work
```
```
In fs/proc/base.c (ffffffff813be462)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - fs/proc/base.c:proc_mem_open
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
In arch/x86/kernel/cpu/common.c (ffffffff8104a892)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In kernel/exit.c (ffffffff810a9645)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - kernel/exit.c:exit_mm
```
```
In kernel/kthread.c (ffffffff810cbb4b)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_use_mm
```
```
In kernel/sched/core.c (ffffffff82fdb18d)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:__schedule
```
```
In mm/oom_kill.c (ffffffff81261415)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/mmu_notifier.c (ffffffff812dd6d8)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_interval_notifier_insert
  - mm/mmu_notifier.c:__mmu_notifier_register
```
```
In mm/ksm.c (ffffffff812e253f)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_enter
```
```
In mm/khugepaged.c (ffffffff812fea6f)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - mm/khugepaged.c:__khugepaged_enter
```
```
In fs/userfaultfd.c (ffffffff8137ff02)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - fs/userfaultfd.c:__do_sys_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
```
```
In fs/io_uring.c (ffffffff81396965)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_grab_identity
```
```
In fs/proc/base.c (ffffffff813d01b2)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - fs/proc/base.c:proc_mem_open
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
In arch/x86/kernel/cpu/common.c (ffffffff8104c15a)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In kernel/exit.c (ffffffff810aa685)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - kernel/exit.c:exit_mm
```
```
In kernel/kthread.c (ffffffff810cd47b)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_use_mm
```
```
In kernel/sched/core.c (ffffffff831e5c8b)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:__schedule
```
```
In mm/oom_kill.c (ffffffff81265c51)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/mmu_notifier.c (ffffffff812e4e58)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_interval_notifier_insert
  - mm/mmu_notifier.c:__mmu_notifier_register
```
```
In mm/ksm.c (ffffffff812e9ccf)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_enter
```
```
In mm/khugepaged.c (ffffffff813056df)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - mm/khugepaged.c:__khugepaged_enter
```
```
In fs/userfaultfd.c (ffffffff81386bb2)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - fs/userfaultfd.c:__do_sys_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
```
```
In fs/io_uring.c (ffffffff81399cae)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
```
```
In fs/proc/base.c (ffffffff813d7092)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - fs/proc/base.c:proc_mem_open
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
In arch/x86/kernel/cpu/common.c (ffffffff810534af)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In kernel/exit.c (ffffffff810bc1b0)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - kernel/exit.c:exit_mm
```
```
In kernel/kthread.c (ffffffff810e066b)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_use_mm
```
```
In kernel/sched/core.c (ffffffff832c9d18)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:__schedule
```
```
In mm/oom_kill.c (ffffffff812a2481)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/mmu_notifier.c (ffffffff8132cc68)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_interval_notifier_insert
  - mm/mmu_notifier.c:__mmu_notifier_register
```
```
In mm/ksm.c (ffffffff81331c01)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_enter
```
```
In mm/khugepaged.c (ffffffff8134f541)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - mm/khugepaged.c:__khugepaged_enter
```
```
In fs/userfaultfd.c (ffffffff813d3eb4)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - fs/userfaultfd.c:__do_sys_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
```
```
In fs/io_uring.c (ffffffff813e8d8b)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
```
```
In fs/proc/base.c (ffffffff814287d2)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - fs/proc/base.c:proc_mem_open
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
In arch/x86/kernel/cpu/common.c (ffffffff8105ef32)
Location: include/linux/sched/mm.h:35
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In kernel/exit.c (ffffffff810d2c3f)
Location: include/linux/sched/mm.h:35
Inline: True
Inline callers:
  - kernel/exit.c:exit_mm
```
```
In kernel/kthread.c (ffffffff810f992a)
Location: include/linux/sched/mm.h:35
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_use_mm
```
```
In kernel/sched/core.c (ffffffff8347cf70)
Location: include/linux/sched/mm.h:35
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:__schedule
```
```
In mm/oom_kill.c (ffffffff812fb0b0)
Location: include/linux/sched/mm.h:35
Inline: True
Inline callers:
  - mm/oom_kill.c:__do_sys_process_mrelease
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/mmu_notifier.c (ffffffff8139cb58)
Location: include/linux/sched/mm.h:35
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_interval_notifier_insert
  - mm/mmu_notifier.c:__mmu_notifier_register
```
```
In mm/ksm.c (ffffffff813a2d8b)
Location: include/linux/sched/mm.h:35
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_enter
```
```
In mm/khugepaged.c (ffffffff813c7798)
Location: include/linux/sched/mm.h:35
Inline: True
Inline callers:
  - mm/khugepaged.c:__khugepaged_enter
```
```
In fs/userfaultfd.c (ffffffff8145d8b4)
Location: include/linux/sched/mm.h:35
Inline: True
Inline callers:
  - fs/userfaultfd.c:__do_sys_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
```
```
In fs/proc/base.c (ffffffff814a1a91)
Location: include/linux/sched/mm.h:35
Inline: True
Inline callers:
  - fs/proc/base.c:proc_mem_open
```
```
In io_uring/io_uring.c (ffffffff81e92631)
Location: include/linux/sched/mm.h:35
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_create
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
In arch/x86/kernel/cpu/common.c (ffffffff8106d692)
Location: include/linux/sched/mm.h:35
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In kernel/exit.c (ffffffff810f1747)
Location: include/linux/sched/mm.h:35
Inline: True
Inline callers:
  - kernel/exit.c:exit_mm
```
```
In kernel/kthread.c (ffffffff8111c67a)
Location: include/linux/sched/mm.h:35
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_use_mm
```
```
In kernel/sched/core.c (ffffffff83ea8440)
Location: include/linux/sched/mm.h:35
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:__schedule
```
```
In mm/oom_kill.c (ffffffff81364400)
Location: include/linux/sched/mm.h:35
Inline: True
Inline callers:
  - mm/oom_kill.c:__do_sys_process_mrelease
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/mmu_notifier.c (ffffffff8141bf58)
Location: include/linux/sched/mm.h:35
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_interval_notifier_insert
  - mm/mmu_notifier.c:__mmu_notifier_register
```
```
In mm/ksm.c (ffffffff814229eb)
Location: include/linux/sched/mm.h:35
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_enter
```
```
In mm/khugepaged.c (ffffffff8144ca62)
Location: include/linux/sched/mm.h:35
Inline: True
Inline callers:
  - mm/khugepaged.c:madvise_collapse
  - mm/khugepaged.c:__khugepaged_enter
```
```
In fs/userfaultfd.c (ffffffff814ecdad)
Location: include/linux/sched/mm.h:35
Inline: True
Inline callers:
  - fs/userfaultfd.c:new_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
```
```
In fs/proc/base.c (ffffffff81536af1)
Location: include/linux/sched/mm.h:35
Inline: True
Inline callers:
  - fs/proc/base.c:proc_mem_open
```
```
In io_uring/io_uring.c (ffffffff8178cbc9)
Location: include/linux/sched/mm.h:35
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_create
```
```
In drivers/iommu/iommu.c (ffffffff81ad28e5)
Location: include/linux/sched/mm.h:35
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_sva_domain_alloc
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
In arch/x86/kernel/cpu/common.c (ffffffff8106eff6)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In kernel/exit.c (ffffffff810fd69a)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - kernel/exit.c:exit_mm
```
```
In kernel/kthread.c (ffffffff8112a8d6)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_unuse_mm
  - kernel/kthread.c:kthread_use_mm
```
```
In kernel/sched/core.c (ffffffff836ccd10)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:__schedule
```
```
In kernel/trace/trace_events_user.c (ffffffff812c52a8)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_event_mm_alloc
```
```
In mm/oom_kill.c (ffffffff813968d0)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - mm/oom_kill.c:__do_sys_process_mrelease
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/mmu_notifier.c (ffffffff8144f50b)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_interval_notifier_insert
  - mm/mmu_notifier.c:__mmu_notifier_register
```
```
In mm/ksm.c (ffffffff814578cf)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_enter
```
```
In mm/khugepaged.c (ffffffff81482312)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - mm/khugepaged.c:madvise_collapse
  - mm/khugepaged.c:__khugepaged_enter
```
```
In fs/userfaultfd.c (ffffffff81523add)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - fs/userfaultfd.c:new_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
```
```
In fs/proc/base.c (ffffffff8156ecd1)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - fs/proc/base.c:proc_mem_open
```
```
In io_uring/io_uring.c (ffffffff817cdcb5)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_create
```
```
In drivers/iommu/iommu.c (ffffffff81b21055)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_sva_domain_alloc
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
In arch/x86/kernel/cpu/common.c (ffffffff81076365)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In kernel/exit.c (ffffffff8110650a)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - kernel/exit.c:exit_mm
```
```
In kernel/kthread.c (ffffffff81134f66)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_unuse_mm
  - kernel/kthread.c:kthread_use_mm
```
```
In kernel/sched/core.c (ffffffff838fe0f1)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:__schedule
```
```
In kernel/trace/trace_events_user.c (ffffffff812e1c78)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_event_mm_alloc
```
```
In mm/oom_kill.c (ffffffff813c01e0)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - mm/oom_kill.c:__do_sys_process_mrelease
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/mmu_notifier.c (ffffffff814891eb)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_interval_notifier_insert
  - mm/mmu_notifier.c:__mmu_notifier_register
```
```
In mm/ksm.c (ffffffff8149239f)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_enter
```
```
In mm/khugepaged.c (ffffffff814b16b8)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - mm/khugepaged.c:madvise_collapse
  - mm/khugepaged.c:__khugepaged_enter
```
```
In fs/userfaultfd.c (ffffffff8155805d)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - fs/userfaultfd.c:new_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
```
```
In fs/proc/base.c (ffffffff815a7691)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - fs/proc/base.c:proc_mem_open
```
```
In io_uring/io_uring.c (ffffffff81816898)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_create
```
```
In drivers/iommu/iommu.c (ffffffff81b77bf8)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_sva_domain_alloc
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
In arch/arm64/kernel/smp.c (ffff80001009c238)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - arch/arm64/kernel/smp.c:secondary_start_kernel
```
```
In virt/kvm/kvm_main.c (ffff8000100bc978)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - virt/kvm/kvm_main.c:kvm_create_vm
```
```
In kernel/exit.c (ffff8000100fd4b4)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/sched/core.c (ffff800011444e68)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:__schedule
```
```
In kernel/futex.c (ffff8000101b6a58)
Location: include/linux/sched/mm.h:34
Inline: True
```
```
In mm/oom_kill.c (ffff8000102b77e0)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/mmu_context.c (ffff8000102dff74)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - mm/mmu_context.c:use_mm
```
```
In mm/mmu_notifier.c (ffff80001033d01c)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_notifier_register
```
```
In mm/ksm.c (ffff800010341b58)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_enter
```
```
In mm/khugepaged.c (ffff80001035f040)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - mm/khugepaged.c:__khugepaged_enter
```
```
In fs/userfaultfd.c (ffff8000103f6d9c)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - fs/userfaultfd.c:__arm64_sys_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
```
```
In fs/io_uring.c (ffff8000104030f4)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
```
```
In fs/proc/base.c (ffff80001043f8dc)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:proc_mem_open
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
In arch/arm/kernel/smp.c (c0312ac4)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - arch/arm/kernel/smp.c:secondary_start_kernel
```
```
In kernel/exit.c (c035a630)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/sched/core.c (c151ef50)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:__schedule
```
```
In kernel/futex.c (c0400c1c)
Location: include/linux/sched/mm.h:34
Inline: True
```
```
In mm/oom_kill.c (c04e4418)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/mmu_context.c (c05048a4)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - mm/mmu_context.c:use_mm
```
```
In mm/mmu_notifier.c (c0543430)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_notifier_register
```
```
In mm/ksm.c (c0547a30)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_enter
```
```
In fs/userfaultfd.c (c05cdcd0)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - fs/userfaultfd.c:__se_sys_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
```
```
In fs/io_uring.c (c05d6638)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
```
```
In fs/proc/base.c (c0606280)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:proc_mem_open
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
In arch/powerpc/kernel/smp.c (c000000000055e9c)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - arch/powerpc/kernel/smp.c:start_secondary
```
```
In arch/powerpc/mm/book3s64/radix_tlb.c (c0000000000964f4)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/radix_tlb.c:do_exit_flush_lazy_tlb
```
```
In kernel/exit.c (c000000000144394)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/sched/core.c (c000000001369744)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:__schedule
```
```
In kernel/futex.c (c0000000002217f0)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
```
```
In mm/oom_kill.c (c00000000036f5d8)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/mmu_context.c (c00000000039f79c)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - mm/mmu_context.c:use_mm
```
```
In mm/mmu_notifier.c (c000000000417fbc)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_notifier_register
```
```
In mm/ksm.c (c00000000041f294)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_enter
```
```
In mm/khugepaged.c (c000000000449b24)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - mm/khugepaged.c:__khugepaged_enter
```
```
In fs/userfaultfd.c (c0000000004fe9dc)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - fs/userfaultfd.c:__se_sys_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
```
```
In fs/io_uring.c (c00000000050fa8c)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
```
```
In fs/proc/base.c (c000000000554e74)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:proc_mem_open
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
In arch/riscv/kernel/smpboot.c (ffffffe0000035ae)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - arch/riscv/kernel/smpboot.c:smp_callin
```
```
In kernel/exit.c (ffffffe0000c5d2a)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/sched/core.c (ffffffe000006d76)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:__schedule
```
```
In kernel/futex.c (ffffffe00013f382)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
```
```
In mm/oom_kill.c (ffffffe0001dbad8)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/mmu_context.c (ffffffe0001f7782)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - mm/mmu_context.c:use_mm
```
```
In mm/mmu_notifier.c (ffffffe000232602)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_notifier_register
```
```
In mm/ksm.c (ffffffe000235fb6)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_enter
```
```
In fs/userfaultfd.c (ffffffe0002a8f6a)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - fs/userfaultfd.c:__se_sys_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
```
```
In fs/io_uring.c (ffffffe0002b092a)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
```
```
In fs/proc/base.c (ffffffe0002d74d8)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:proc_mem_open
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
In arch/x86/kernel/cpu/common.c (ffffffff810475ee)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In kernel/exit.c (ffffffff8109fe6c)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/sched/core.c (ffffffff828b63fd)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:__schedule
```
```
In kernel/futex.c (ffffffff81142845)
Location: include/linux/sched/mm.h:34
Inline: True
```
```
In mm/oom_kill.c (ffffffff8122207a)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/mmu_context.c (ffffffff812428b9)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - mm/mmu_context.c:use_mm
```
```
In mm/mmu_notifier.c (ffffffff8129614c)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_notifier_register
```
```
In mm/ksm.c (ffffffff8129a8cf)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_enter
```
```
In mm/khugepaged.c (ffffffff812b60ef)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - mm/khugepaged.c:__khugepaged_enter
```
```
In fs/userfaultfd.c (ffffffff813308a6)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - fs/userfaultfd.c:__ia32_sys_userfaultfd
  - fs/userfaultfd.c:__x64_sys_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
```
```
In fs/io_uring.c (ffffffff8133d38c)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
```
```
In fs/proc/base.c (ffffffff8136dcb3)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:proc_mem_open
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
In arch/x86/kernel/cpu/common.c (ffffffff81036765)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In kernel/exit.c (ffffffff8108e89c)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/sched/core.c (ffffffff828ae5eb)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:__schedule
```
```
In kernel/futex.c (ffffffff81135ba5)
Location: include/linux/sched/mm.h:34
Inline: True
```
```
In mm/oom_kill.c (ffffffff8121522a)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/mmu_context.c (ffffffff81235889)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - mm/mmu_context.c:use_mm
```
```
In mm/mmu_notifier.c (ffffffff81287d5c)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_notifier_register
```
```
In mm/ksm.c (ffffffff8128c48f)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_enter
```
```
In mm/khugepaged.c (ffffffff812a72df)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - mm/khugepaged.c:__khugepaged_enter
```
```
In fs/userfaultfd.c (ffffffff81321496)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - fs/userfaultfd.c:__ia32_sys_userfaultfd
  - fs/userfaultfd.c:__x64_sys_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
```
```
In fs/io_uring.c (ffffffff8132e04c)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
```
```
In fs/proc/base.c (ffffffff8135e743)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:proc_mem_open
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
In arch/x86/kernel/cpu/common.c (ffffffff8104742e)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In kernel/exit.c (ffffffff8109fe1c)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/sched/core.c (ffffffff828c935f)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:__schedule
```
```
In kernel/futex.c (ffffffff811406f5)
Location: include/linux/sched/mm.h:34
Inline: True
```
```
In mm/oom_kill.c (ffffffff8121fe1a)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/mmu_context.c (ffffffff81240659)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - mm/mmu_context.c:use_mm
```
```
In mm/mmu_notifier.c (ffffffff81293f5c)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_notifier_register
```
```
In mm/ksm.c (ffffffff812986df)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_enter
```
```
In mm/khugepaged.c (ffffffff812b3eff)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - mm/khugepaged.c:__khugepaged_enter
```
```
In fs/userfaultfd.c (ffffffff8132e376)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - fs/userfaultfd.c:__ia32_sys_userfaultfd
  - fs/userfaultfd.c:__x64_sys_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
```
```
In fs/io_uring.c (ffffffff8133ae5c)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
```
```
In fs/proc/base.c (ffffffff8136b783)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:proc_mem_open
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
In arch/x86/kernel/cpu/common.c (ffffffff8104882e)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In kernel/exit.c (ffffffff810a7d87)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/sched/core.c (ffffffff828ce653)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:__schedule
```
```
In kernel/futex.c (ffffffff8114d4a5)
Location: include/linux/sched/mm.h:34
Inline: True
```
```
In mm/oom_kill.c (ffffffff8122eefa)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:mark_oom_victim
```
```
In mm/mmu_context.c (ffffffff8124fdb8)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - mm/mmu_context.c:use_mm
```
```
In mm/mmu_notifier.c (ffffffff812a3d7c)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_notifier_register
```
```
In mm/ksm.c (ffffffff812a845d)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_enter
```
```
In mm/khugepaged.c (ffffffff812c438f)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - mm/khugepaged.c:__khugepaged_enter
```
```
In fs/userfaultfd.c (ffffffff81340c76)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - fs/userfaultfd.c:__ia32_sys_userfaultfd
  - fs/userfaultfd.c:__x64_sys_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
```
```
In fs/io_uring.c (ffffffff8134e00c)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
```
```
In fs/proc/base.c (ffffffff8137eefd)
Location: include/linux/sched/mm.h:34
Inline: True
Inline callers:
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:proc_mem_open
```
</details>
</li>
</ul>

## Differences
