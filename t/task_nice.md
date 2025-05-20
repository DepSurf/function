# Function: <code>task_nice</code>

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
In kernel/sys.c (0)
Location: include/linux/sched.h:2375
Inline: True
```
```
In kernel/sched/core.c (ffffffff810b02e2)
Location: include/linux/sched.h:2375
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
```
```
In kernel/sched/cputime.c (0)
Location: include/linux/sched.h:2375
Inline: True
```
```
In kernel/tsacct.c (0)
Location: include/linux/sched.h:2375
Inline: True
```
```
In fs/select.c (0)
Location: include/linux/sched.h:2375
Inline: True
```
```
In fs/binfmt_elf.c (0)
Location: include/linux/sched.h:2375
Inline: True
```
```
In fs/compat_binfmt_elf.c (0)
Location: include/linux/sched.h:2375
Inline: True
```
```
In fs/proc/array.c (ffffffff8128002a)
Location: include/linux/sched.h:2375
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In block/cfq-iosched.c (ffffffff813e18ca)
Location: include/linux/sched.h:2375
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_get_queue
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
In kernel/sys.c (ffffffff81096eaa)
Location: include/linux/sched.h:2546
Inline: True
Inline callers:
  - kernel/sys.c:SyS_getpriority
  - kernel/sys.c:SyS_getpriority
  - kernel/sys.c:SyS_getpriority
  - kernel/sys.c:set_one_prio
```
```
In kernel/sched/core.c (ffffffff810b06f2)
Location: include/linux/sched.h:2546
Inline: True
Inline callers:
  - kernel/sched/core.c:SyS_sched_getattr
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:SyS_nice
  - kernel/sched/core.c:SyS_nice
```
```
In kernel/sched/cputime.c (ffffffff810b42dc)
Location: include/linux/sched.h:2546
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_system_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/tsacct.c (ffffffff81147725)
Location: include/linux/sched.h:2546
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/select.c (ffffffff81248b69)
Location: include/linux/sched.h:2546
Inline: True
```
```
In fs/binfmt_elf.c (ffffffff81294c5c)
Location: include/linux/sched.h:2546
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff81297897)
Location: include/linux/sched.h:2546
Inline: True
```
```
In fs/proc/array.c (ffffffff812ad076)
Location: include/linux/sched.h:2546
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In block/cfq-iosched.c (ffffffff81427af7)
Location: include/linux/sched.h:2546
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_get_queue
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
In kernel/sys.c (ffffffff8109be5a)
Location: include/linux/sched.h:2644
Inline: True
Inline callers:
  - kernel/sys.c:SyS_getpriority
  - kernel/sys.c:SyS_getpriority
  - kernel/sys.c:SyS_getpriority
  - kernel/sys.c:set_one_prio
```
```
In kernel/sched/core.c (ffffffff810b6882)
Location: include/linux/sched.h:2644
Inline: True
Inline callers:
  - kernel/sched/core.c:SyS_sched_getattr
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:SyS_nice
  - kernel/sched/core.c:SyS_nice
```
```
In kernel/sched/cputime.c (ffffffff810ba8fa)
Location: include/linux/sched.h:2644
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_system_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/tsacct.c (ffffffff811515c5)
Location: include/linux/sched.h:2644
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/select.c (ffffffff8125bb99)
Location: include/linux/sched.h:2644
Inline: True
```
```
In fs/binfmt_elf.c (ffffffff812a991c)
Location: include/linux/sched.h:2644
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff812ac386)
Location: include/linux/sched.h:2644
Inline: True
```
```
In fs/proc/array.c (ffffffff812c294a)
Location: include/linux/sched.h:2644
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In block/cfq-iosched.c (ffffffff814416f7)
Location: include/linux/sched.h:2644
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_get_queue
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
In kernel/sys.c (ffffffff81098c6a)
Location: include/linux/sched.h:1389
Inline: True
Inline callers:
  - kernel/sys.c:SyS_getpriority
  - kernel/sys.c:SyS_getpriority
  - kernel/sys.c:SyS_getpriority
  - kernel/sys.c:set_one_prio
```
```
In kernel/sched/core.c (ffffffff810b405d)
Location: include/linux/sched.h:1389
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:SyS_sched_getattr
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:SyS_nice
  - kernel/sched/core.c:SyS_nice
```
```
In kernel/sched/cputime.c (ffffffff810b50ff)
Location: include/linux/sched.h:1389
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_guest_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/tsacct.c (ffffffff81153c45)
Location: include/linux/sched.h:1389
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/select.c (ffffffff81268b4a)
Location: include/linux/sched.h:1389
Inline: True
Inline callers:
  - fs/select.c:select_estimate_accuracy
```
```
In fs/binfmt_elf.c (ffffffff812b621d)
Location: include/linux/sched.h:1389
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff812b92d3)
Location: include/linux/sched.h:1389
Inline: True
```
```
In fs/proc/array.c (ffffffff812cfc3a)
Location: include/linux/sched.h:1389
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In block/cfq-iosched.c (ffffffff814509e6)
Location: include/linux/sched.h:1389
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_get_queue
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
In kernel/sys.c (ffffffff8109f94a)
Location: include/linux/sched.h:1419
Inline: True
Inline callers:
  - kernel/sys.c:SyS_getpriority
  - kernel/sys.c:SyS_getpriority
  - kernel/sys.c:SyS_getpriority
  - kernel/sys.c:set_one_prio
```
```
In kernel/sched/core.c (ffffffff810bb30d)
Location: include/linux/sched.h:1419
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:SyS_sched_getattr
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:SyS_nice
  - kernel/sched/core.c:SyS_nice
```
```
In kernel/sched/cputime.c (ffffffff810bc27f)
Location: include/linux/sched.h:1419
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_guest_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/tsacct.c (ffffffff81160445)
Location: include/linux/sched.h:1419
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/select.c (ffffffff8128b40a)
Location: include/linux/sched.h:1419
Inline: True
Inline callers:
  - fs/select.c:select_estimate_accuracy
```
```
In fs/binfmt_elf.c (ffffffff812d9adc)
Location: include/linux/sched.h:1419
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff812dcbe1)
Location: include/linux/sched.h:1419
Inline: True
```
```
In fs/proc/array.c (ffffffff812f43b9)
Location: include/linux/sched.h:1419
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In block/cfq-iosched.c (ffffffff8147c026)
Location: include/linux/sched.h:1419
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_get_queue
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
In kernel/sys.c (ffffffff810a63e3)
Location: include/linux/sched.h:1519
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:set_one_prio
```
```
In kernel/sched/core.c (ffffffff810c281c)
Location: include/linux/sched.h:1519
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
```
```
In kernel/sched/cputime.c (ffffffff810c3959)
Location: include/linux/sched.h:1519
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_guest_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/tsacct.c (ffffffff8116f376)
Location: include/linux/sched.h:1519
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/select.c (ffffffff812b1c37)
Location: include/linux/sched.h:1519
Inline: True
Inline callers:
  - fs/select.c:select_estimate_accuracy
```
```
In fs/binfmt_elf.c (ffffffff81305847)
Location: include/linux/sched.h:1519
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff813091a6)
Location: include/linux/sched.h:1519
Inline: True
```
```
In fs/proc/array.c (ffffffff813217c7)
Location: include/linux/sched.h:1519
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In block/cfq-iosched.c (ffffffff814b10e0)
Location: include/linux/sched.h:1519
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_get_queue
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
In kernel/sys.c (ffffffff810af0f3)
Location: include/linux/sched.h:1532
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:set_one_prio
```
```
In kernel/sched/core.c (ffffffff810cbb1c)
Location: include/linux/sched.h:1532
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
```
```
In kernel/sched/cputime.c (ffffffff810ccc19)
Location: include/linux/sched.h:1532
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_guest_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/tsacct.c (ffffffff8117ce76)
Location: include/linux/sched.h:1532
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/select.c (ffffffff812c6d57)
Location: include/linux/sched.h:1532
Inline: True
Inline callers:
  - fs/select.c:select_estimate_accuracy
```
```
In fs/binfmt_elf.c (ffffffff8131afd5)
Location: include/linux/sched.h:1532
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff8131e9b4)
Location: include/linux/sched.h:1532
Inline: True
```
```
In fs/proc/array.c (ffffffff813388d7)
Location: include/linux/sched.h:1532
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
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
In kernel/sys.c (ffffffff810b1134)
Location: include/linux/sched.h:1605
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:set_one_prio
```
```
In kernel/sched/core.c (ffffffff810d3b8c)
Location: include/linux/sched.h:1605
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
```
```
In kernel/sched/cputime.c (ffffffff810d4ff9)
Location: include/linux/sched.h:1605
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_guest_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/tsacct.c (ffffffff81189d37)
Location: include/linux/sched.h:1605
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/select.c (ffffffff812e38d7)
Location: include/linux/sched.h:1605
Inline: True
Inline callers:
  - fs/select.c:select_estimate_accuracy
```
```
In fs/binfmt_elf.c (ffffffff813427fc)
Location: include/linux/sched.h:1605
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff81346162)
Location: include/linux/sched.h:1605
Inline: True
```
```
In fs/proc/array.c (ffffffff81360f71)
Location: include/linux/sched.h:1605
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
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
In kernel/sys.c (ffffffff810baf74)
Location: include/linux/sched.h:1598
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:set_one_prio
```
```
In kernel/sched/core.c (ffffffff810de06c)
Location: include/linux/sched.h:1598
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
```
```
In kernel/sched/cputime.c (ffffffff810df5b8)
Location: include/linux/sched.h:1598
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_guest_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/tsacct.c (ffffffff81195c47)
Location: include/linux/sched.h:1598
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/select.c (ffffffff812f5317)
Location: include/linux/sched.h:1598
Inline: True
Inline callers:
  - fs/select.c:select_estimate_accuracy
```
```
In fs/binfmt_elf.c (ffffffff8135ac39)
Location: include/linux/sched.h:1598
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff8135e469)
Location: include/linux/sched.h:1598
Inline: True
```
```
In fs/proc/array.c (ffffffff813791d1)
Location: include/linux/sched.h:1598
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
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
In kernel/sys.c (ffffffff810c194e)
Location: include/linux/sched.h:1640
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:set_one_prio
```
```
In kernel/sched/core.c (ffffffff810e65c9)
Location: include/linux/sched.h:1640
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
```
```
In kernel/sched/cputime.c (ffffffff810e7908)
Location: include/linux/sched.h:1640
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_guest_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/tsacct.c (ffffffff811aae22)
Location: include/linux/sched.h:1640
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/select.c (ffffffff8132d8d7)
Location: include/linux/sched.h:1640
Inline: True
Inline callers:
  - fs/select.c:select_estimate_accuracy
```
```
In fs/binfmt_elf.c (ffffffff8139faf4)
Location: include/linux/sched.h:1640
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff813a298e)
Location: include/linux/sched.h:1640
Inline: True
```
```
In fs/proc/array.c (ffffffff813c227c)
Location: include/linux/sched.h:1640
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
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
In kernel/sys.c (ffffffff810bc950)
Location: include/linux/sched.h:1698
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:set_one_prio
```
```
In kernel/sched/core.c (ffffffff810e44c9)
Location: include/linux/sched.h:1698
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
```
```
In kernel/sched/cputime.c (ffffffff810e55f8)
Location: include/linux/sched.h:1698
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_guest_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/tsacct.c (ffffffff811a83d2)
Location: include/linux/sched.h:1698
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/select.c (ffffffff81339137)
Location: include/linux/sched.h:1698
Inline: True
Inline callers:
  - fs/select.c:select_estimate_accuracy
```
```
In fs/binfmt_elf.c (ffffffff813b0edd)
Location: include/linux/sched.h:1698
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff813b3a03)
Location: include/linux/sched.h:1698
Inline: True
```
```
In fs/proc/array.c (ffffffff813d43f2)
Location: include/linux/sched.h:1698
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
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
In kernel/sys.c (ffffffff810be1e2)
Location: include/linux/sched.h:1720
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:set_one_prio
```
```
In kernel/sched/core.c (ffffffff810e6479)
Location: include/linux/sched.h:1720
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
```
```
In kernel/sched/cputime.c (ffffffff810e75b8)
Location: include/linux/sched.h:1720
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_guest_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/tsacct.c (ffffffff811a8f52)
Location: include/linux/sched.h:1720
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/select.c (ffffffff8133f6f7)
Location: include/linux/sched.h:1720
Inline: True
Inline callers:
  - fs/select.c:select_estimate_accuracy
```
```
In fs/binfmt_elf.c (ffffffff813b7fcc)
Location: include/linux/sched.h:1720
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff813ba9c2)
Location: include/linux/sched.h:1720
Inline: True
```
```
In fs/proc/array.c (ffffffff813db21f)
Location: include/linux/sched.h:1720
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
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
In kernel/sys.c (ffffffff810d1062)
Location: include/linux/sched.h:1837
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:set_one_prio
```
```
In kernel/sched/core.c (ffffffff810fd9b9)
Location: include/linux/sched.h:1837
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
  - kernel/sched/core.c:__do_sys_sched_setattr
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
```
```
In kernel/sched/cputime.c (ffffffff810febcf)
Location: include/linux/sched.h:1837
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_guest_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/tsacct.c (ffffffff811d2aa7)
Location: include/linux/sched.h:1837
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/select.c (ffffffff8138d087)
Location: include/linux/sched.h:1837
Inline: True
Inline callers:
  - fs/select.c:select_estimate_accuracy
```
```
In fs/binfmt_elf.c (ffffffff81407b26)
Location: include/linux/sched.h:1837
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff8140a50c)
Location: include/linux/sched.h:1837
Inline: True
```
```
In fs/proc/array.c (ffffffff8142c891)
Location: include/linux/sched.h:1837
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
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
In kernel/sys.c (ffffffff810e739d)
Location: include/linux/sched.h:1862
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:set_one_prio
```
```
In kernel/sched/core.c (ffffffff8111a424)
Location: include/linux/sched.h:1862
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
  - kernel/sched/core.c:__do_sys_sched_setattr
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
  - kernel/sched/core.c:set_user_nice
```
```
In kernel/sched/build_policy.c (ffffffff81139443)
Location: include/linux/sched.h:1862
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:account_guest_time
  - kernel/sched/build_policy.c:account_user_time
```
```
In kernel/tsacct.c (ffffffff8120742b)
Location: include/linux/sched.h:1862
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/select.c (ffffffff8140e3e7)
Location: include/linux/sched.h:1862
Inline: True
Inline callers:
  - fs/select.c:select_estimate_accuracy
```
```
In fs/binfmt_elf.c (ffffffff8147c852)
Location: include/linux/sched.h:1862
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff8147f238)
Location: include/linux/sched.h:1862
Inline: True
```
```
In fs/proc/array.c (ffffffff814a6169)
Location: include/linux/sched.h:1862
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
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
In kernel/sys.c (ffffffff81107fad)
Location: include/linux/sched.h:1889
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:set_one_prio
```
```
In kernel/sched/core.c (ffffffff81141c94)
Location: include/linux/sched.h:1889
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
  - kernel/sched/core.c:__do_sys_sched_setattr
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
  - kernel/sched/core.c:set_user_nice
```
```
In kernel/sched/build_policy.c (ffffffff81163b33)
Location: include/linux/sched.h:1889
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:account_guest_time
  - kernel/sched/build_policy.c:account_user_time
```
```
In kernel/tsacct.c (ffffffff8124f7bb)
Location: include/linux/sched.h:1889
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/select.c (ffffffff81498f67)
Location: include/linux/sched.h:1889
Inline: True
Inline callers:
  - fs/select.c:select_estimate_accuracy
```
```
In fs/binfmt_elf.c (ffffffff8150f542)
Location: include/linux/sched.h:1889
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff815121f8)
Location: include/linux/sched.h:1889
Inline: True
```
```
In fs/proc/array.c (ffffffff8153b7a9)
Location: include/linux/sched.h:1889
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In block/ioprio.c (0)
Location: include/linux/sched.h:1889
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
In kernel/sys.c (ffffffff811142bd)
Location: include/linux/sched.h:1900
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:set_one_prio
```
```
In kernel/sched/core.c (ffffffff8114d964)
Location: include/linux/sched.h:1900
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
  - kernel/sched/core.c:__do_sys_sched_setattr
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
  - kernel/sched/core.c:set_user_nice
```
```
In kernel/sched/build_policy.c (ffffffff81174313)
Location: include/linux/sched.h:1900
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:account_guest_time
  - kernel/sched/build_policy.c:account_user_time
```
```
In kernel/tsacct.c (ffffffff81266b6b)
Location: include/linux/sched.h:1900
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/select.c (ffffffff814cdff7)
Location: include/linux/sched.h:1900
Inline: True
Inline callers:
  - fs/select.c:select_estimate_accuracy
```
```
In fs/binfmt_elf.c (ffffffff81546e30)
Location: include/linux/sched.h:1900
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff81549bf6)
Location: include/linux/sched.h:1900
Inline: True
```
```
In fs/proc/array.c (ffffffff81573ad4)
Location: include/linux/sched.h:1900
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In block/ioprio.c (ffffffff8178ec7e)
Location: include/linux/sched.h:1900
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
In kernel/sys.c (ffffffff8111dcad)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:set_one_prio
```
```
In kernel/sched/core.c (ffffffff81159774)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
  - kernel/sched/core.c:set_user_nice
```
```
In kernel/sched/build_policy.c (ffffffff8117555d)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:kcpustat_cpu_fetch
  - kernel/sched/build_policy.c:kcpustat_field_vtime
  - kernel/sched/build_policy.c:kcpustat_field_vtime
  - kernel/sched/build_policy.c:kcpustat_field_vtime
  - kernel/sched/build_policy.c:kcpustat_field_vtime
  - kernel/sched/build_policy.c:account_guest_time
  - kernel/sched/build_policy.c:account_user_time
```
```
In kernel/tsacct.c (ffffffff81280a8e)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In mm/filemap.c (ffffffff813bc389)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - mm/filemap.c:filemap_splice_read
```
```
In mm/page_io.c (ffffffff8146459f)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - mm/page_io.c:swap_read_folio_fs
  - mm/page_io.c:swap_writepage_fs
```
```
In fs/read_write.c (ffffffff814dd32b)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
  - fs/read_write.c:vfs_write
  - fs/read_write.c:__kernel_write_iter
  - fs/read_write.c:vfs_read
  - fs/read_write.c:__kernel_read
```
```
In fs/select.c (ffffffff81500937)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/select.c:select_estimate_accuracy
```
```
In fs/seq_file.c (ffffffff8151ce78)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/seq_file.c:seq_read
```
```
In fs/splice.c (ffffffff81530942)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:copy_splice_read
```
```
In fs/aio.c (ffffffff8155c9cb)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In fs/binfmt_elf.c (ffffffff8157c250)
Location: include/linux/sched.h:1804
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff8157ee76)
Location: include/linux/sched.h:1804
Inline: True
```
```
In fs/proc/array.c (ffffffff815ac4a0)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In block/blk-core.c (ffffffff817b46db)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
```
```
In block/ioprio.c (ffffffff817d1578)
Location: include/linux/sched.h:1804
Inline: True
```
```
In io_uring/rw.c (ffffffff81829475)
Location: include/linux/sched.h:1804
Inline: True
Inline callers:
  - io_uring/rw.c:io_prep_rw
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
In virt/kvm/kvm_main.c (ffff8000100b6340)
Location: include/linux/sched.h:1598
Inline: True
Inline callers:
  - virt/kvm/kvm_main.c:kvm_vm_worker_thread
```
```
In kernel/sys.c (ffff800010114a1c)
Location: include/linux/sched.h:1598
Inline: True
Inline callers:
  - kernel/sys.c:__arm64_sys_getpriority
  - kernel/sys.c:__arm64_sys_getpriority
  - kernel/sys.c:__arm64_sys_getpriority
  - kernel/sys.c:set_one_prio
```
```
In kernel/sched/core.c (ffff80001013dabc)
Location: include/linux/sched.h:1598
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:__arm64_sys_sched_getattr
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__arm64_sys_nice
  - kernel/sched/core.c:__arm64_sys_nice
```
```
In kernel/sched/cputime.c (ffff80001013ee78)
Location: include/linux/sched.h:1598
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_guest_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/tsacct.c (ffff80001020df18)
Location: include/linux/sched.h:1598
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/select.c (ffff8000103a2650)
Location: include/linux/sched.h:1598
Inline: True
Inline callers:
  - fs/select.c:select_estimate_accuracy
```
```
In fs/binfmt_elf.c (ffff8000104202b4)
Location: include/linux/sched.h:1598
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffff800010421b6c)
Location: include/linux/sched.h:1598
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:fill_psinfo
```
```
In fs/proc/array.c (ffff800010445698)
Location: include/linux/sched.h:1598
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
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
In kernel/sys.c (c036bcc8)
Location: include/linux/sched.h:1598
Inline: True
Inline callers:
  - kernel/sys.c:__se_sys_getpriority
  - kernel/sys.c:__se_sys_getpriority
  - kernel/sys.c:__se_sys_getpriority
  - kernel/sys.c:set_one_prio
```
```
In kernel/sched/core.c (c038da98)
Location: include/linux/sched.h:1598
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:__se_sys_sched_getattr
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__se_sys_nice
  - kernel/sched/core.c:__se_sys_nice
```
```
In kernel/sched/cputime.c (c038ee10)
Location: include/linux/sched.h:1598
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_guest_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/tsacct.c (c044c9ec)
Location: include/linux/sched.h:1598
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/select.c (c058508c)
Location: include/linux/sched.h:1598
Inline: True
Inline callers:
  - fs/select.c:select_estimate_accuracy
```
```
In fs/binfmt_elf.c (c05e6434)
Location: include/linux/sched.h:1598
Inline: True
Inline callers:
  - fs/binfmt_elf.c:fill_psinfo
```
```
In fs/binfmt_elf_fdpic.c (c05e96b8)
Location: include/linux/sched.h:1598
Inline: True
Inline callers:
  - fs/binfmt_elf_fdpic.c:fill_psinfo
```
```
In fs/proc/array.c (c060a6d0)
Location: include/linux/sched.h:1598
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
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
In kernel/sys.c (c00000000015ba74)
Location: include/linux/sched.h:1598
Inline: True
Inline callers:
  - kernel/sys.c:__se_sys_getpriority
  - kernel/sys.c:__se_sys_getpriority
  - kernel/sys.c:__se_sys_getpriority
  - kernel/sys.c:set_one_prio
```
```
In kernel/sched/core.c (c00000000018ca58)
Location: include/linux/sched.h:1598
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:__se_sys_sched_getattr
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__se_sys_nice
```
```
In kernel/sched/cputime.c (c00000000018e038)
Location: include/linux/sched.h:1598
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_guest_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/tsacct.c (c00000000028c0f8)
Location: include/linux/sched.h:1598
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/select.c (c00000000049bfc8)
Location: include/linux/sched.h:1598
Inline: True
Inline callers:
  - fs/select.c:select_estimate_accuracy
```
```
In fs/binfmt_elf.c (c00000000052f1bc)
Location: include/linux/sched.h:1598
Inline: True
```
```
In fs/compat_binfmt_elf.c (c000000000532dec)
Location: include/linux/sched.h:1598
Inline: True
```
```
In fs/proc/array.c (c00000000055b068)
Location: include/linux/sched.h:1598
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
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
In kernel/sys.c (ffffffe0000d2d50)
Location: include/linux/sched.h:1598
Inline: True
Inline callers:
  - kernel/sys.c:__se_sys_getpriority
  - kernel/sys.c:__se_sys_getpriority
  - kernel/sys.c:__se_sys_getpriority
  - kernel/sys.c:set_one_prio
```
```
In kernel/sched/core.c (ffffffe0000ec9ac)
Location: include/linux/sched.h:1598
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:__se_sys_sched_getattr
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
```
```
In kernel/sched/cputime.c (ffffffe0000ed642)
Location: include/linux/sched.h:1598
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_guest_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/tsacct.c (ffffffe00016edbe)
Location: include/linux/sched.h:1598
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/select.c (ffffffe00026aa62)
Location: include/linux/sched.h:1598
Inline: True
Inline callers:
  - fs/select.c:select_estimate_accuracy
```
```
In fs/binfmt_elf.c (ffffffe0002c11a2)
Location: include/linux/sched.h:1598
Inline: True
```
```
In fs/proc/array.c (ffffffe0002db5d6)
Location: include/linux/sched.h:1598
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
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
In kernel/sys.c (ffffffff810b52e4)
Location: include/linux/sched.h:1598
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:set_one_prio
```
```
In kernel/sched/core.c (ffffffff810d825c)
Location: include/linux/sched.h:1598
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
```
```
In kernel/sched/cputime.c (ffffffff810d97a8)
Location: include/linux/sched.h:1598
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_guest_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/tsacct.c (ffffffff8118e267)
Location: include/linux/sched.h:1598
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/select.c (ffffffff812ed8f7)
Location: include/linux/sched.h:1598
Inline: True
Inline callers:
  - fs/select.c:select_estimate_accuracy
```
```
In fs/binfmt_elf.c (ffffffff81353219)
Location: include/linux/sched.h:1598
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff81356a49)
Location: include/linux/sched.h:1598
Inline: True
```
```
In fs/proc/array.c (ffffffff813717b1)
Location: include/linux/sched.h:1598
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
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
In kernel/sys.c (ffffffff810a3c24)
Location: include/linux/sched.h:1598
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:set_one_prio
```
```
In kernel/sched/core.c (ffffffff810c6c6c)
Location: include/linux/sched.h:1598
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
```
```
In kernel/sched/cputime.c (ffffffff810c8188)
Location: include/linux/sched.h:1598
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_guest_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/tsacct.c (ffffffff8118138a)
Location: include/linux/sched.h:1598
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/select.c (ffffffff812de527)
Location: include/linux/sched.h:1598
Inline: True
Inline callers:
  - fs/select.c:select_estimate_accuracy
```
```
In fs/binfmt_elf.c (ffffffff81343ef9)
Location: include/linux/sched.h:1598
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff81347709)
Location: include/linux/sched.h:1598
Inline: True
```
```
In fs/proc/array.c (ffffffff8136228d)
Location: include/linux/sched.h:1598
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
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
In kernel/sys.c (ffffffff810b4844)
Location: include/linux/sched.h:1598
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:set_one_prio
```
```
In kernel/sched/core.c (ffffffff810d4a4c)
Location: include/linux/sched.h:1598
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
```
```
In kernel/sched/cputime.c (ffffffff810d5ae8)
Location: include/linux/sched.h:1598
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_guest_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/tsacct.c (ffffffff8118c037)
Location: include/linux/sched.h:1598
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/select.c (ffffffff812eb707)
Location: include/linux/sched.h:1598
Inline: True
Inline callers:
  - fs/select.c:select_estimate_accuracy
```
```
In fs/binfmt_elf.c (ffffffff81350ce9)
Location: include/linux/sched.h:1598
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff81354519)
Location: include/linux/sched.h:1598
Inline: True
```
```
In fs/proc/array.c (ffffffff8136f281)
Location: include/linux/sched.h:1598
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
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
In kernel/sys.c (ffffffff810b9769)
Location: include/linux/sched.h:1598
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:set_one_prio
```
```
In kernel/sched/core.c (ffffffff810dfe3c)
Location: include/linux/sched.h:1598
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:__ia32_sys_sched_getattr
  - kernel/sched/core.c:__x64_sys_sched_getattr
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
```
```
In kernel/sched/cputime.c (ffffffff810e13e8)
Location: include/linux/sched.h:1598
Inline: True
Inline callers:
  - kernel/sched/cputime.c:account_guest_time
  - kernel/sched/cputime.c:account_user_time
```
```
In kernel/tsacct.c (ffffffff811999b7)
Location: include/linux/sched.h:1598
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In fs/select.c (ffffffff812fc6f7)
Location: include/linux/sched.h:1598
Inline: True
Inline callers:
  - fs/select.c:select_estimate_accuracy
```
```
In fs/binfmt_elf.c (ffffffff81364282)
Location: include/linux/sched.h:1598
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff81365311)
Location: include/linux/sched.h:1598
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:fill_psinfo
```
```
In fs/proc/array.c (ffffffff81382c11)
Location: include/linux/sched.h:1598
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
</details>
</li>
</ul>

## Differences
