# Function: <code>set_user_nice</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_user_nice(struct task_struct *p, long int nice);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff810aa390)
Location: kernel/sched/core.c:3452
Inline: True
Inline callers:
  - kernel/sched/core.c:SyS_nice
  - kernel/sched/core.c:normalize_rt_tasks
Direct callers:
  - kernel/sys.c:set_one_prio
  - kernel/kmod.c:call_usermodehelper_exec_async
  - kernel/workqueue.c:create_worker
  - kernel/workqueue.c:rescuer_thread
  - kernel/sched/core.c:SyS_nice
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/hung_task.c:watchdog
  - mm/ksm.c:ksm_scan_thread
  - mm/huge_memory.c:khugepaged
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffffffff810aa390-ffffffff810aa5aa: set_user_nice.part.80 (STB_LOCAL)
ffffffff810aa5b0-ffffffff810aa5d8: set_user_nice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_user_nice(struct task_struct *p, long int nice);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff810b2f2c)
Location: kernel/sched/core.c:3705
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:SyS_nice
Direct callers:
  - kernel/sys.c:set_one_prio
  - kernel/kmod.c:call_usermodehelper_exec_async
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:create_worker
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:SyS_nice
  - kernel/hung_task.c:watchdog
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffffffff810acff0-ffffffff810ad1d9: set_user_nice.part.83 (STB_LOCAL)
ffffffff810ad1e0-ffffffff810ad209: set_user_nice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_user_nice(struct task_struct *p, long int nice);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff810b9511)
Location: kernel/sched/core.c:3736
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:SyS_nice
Direct callers:
  - kernel/sys.c:set_one_prio
  - kernel/kmod.c:call_usermodehelper_exec_async
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:create_worker
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:SyS_nice
  - kernel/hung_task.c:watchdog
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffffffff810b3070-ffffffff810b32b5: set_user_nice.part.81 (STB_LOCAL)
ffffffff810b32c0-ffffffff810b32e9: set_user_nice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_user_nice(struct task_struct *p, long int nice);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff810b4063)
Location: kernel/sched/core.c:3740
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:SyS_nice
Direct callers:
  - kernel/sys.c:set_one_prio
  - kernel/kmod.c:call_usermodehelper_exec_async
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:create_worker
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:SyS_nice
  - kernel/hung_task.c:watchdog
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffffffff810aefa0-ffffffff810af1c1: set_user_nice.part.71 (STB_LOCAL)
ffffffff810af1d0-ffffffff810af1fc: set_user_nice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_user_nice(struct task_struct *p, long int nice);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff810bb313)
Location: kernel/sched/core.c:3784
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:SyS_nice
Direct callers:
  - kernel/sys.c:set_one_prio
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:create_worker
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:SyS_nice
  - kernel/hung_task.c:watchdog
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffffffff810b61f0-ffffffff810b63f1: set_user_nice.part.69 (STB_LOCAL)
ffffffff810b6400-ffffffff810b642c: set_user_nice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_user_nice(struct task_struct *p, long int nice);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff810c281f)
Location: kernel/sched/core.c:3894
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
Direct callers:
  - kernel/sys.c:set_one_prio
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:create_worker
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
  - kernel/hung_task.c:watchdog
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffffffff810be050-ffffffff810be245: set_user_nice.part.66 (STB_LOCAL)
ffffffff810be250-ffffffff810be278: set_user_nice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_user_nice(struct task_struct *p, long int nice);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff810cbb1f)
Location: kernel/sched/core.c:3878
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
Direct callers:
  - kernel/sys.c:set_one_prio
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:create_worker
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
  - kernel/hung_task.c:watchdog
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffffffff810c7300-ffffffff810c74dd: set_user_nice.part.67 (STB_LOCAL)
ffffffff810c74e0-ffffffff810c7508: set_user_nice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_user_nice(struct task_struct *p, long int nice);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff810d3b8f)
Location: kernel/sched/core.c:4297
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
Direct callers:
  - kernel/sys.c:set_one_prio
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:create_worker
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
  - kernel/hung_task.c:watchdog
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - drivers/block/loop.c:loop_set_fd
```
**Symbols:**

```
ffffffff810cd860-ffffffff810cddcb: set_user_nice.part.0 (STB_LOCAL)
ffffffff810cddd0-ffffffff810cddf8: set_user_nice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_user_nice(struct task_struct *p, long int nice);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff810de06f)
Location: kernel/sched/core.c:4499
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
Direct callers:
  - kernel/sys.c:set_one_prio
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:create_worker
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
  - kernel/hung_task.c:watchdog
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - drivers/block/loop.c:loop_set_fd
```
**Symbols:**

```
ffffffff810d7390-ffffffff810d79c5: set_user_nice.part.0 (STB_LOCAL)
ffffffff810d79d0-ffffffff810d79f8: set_user_nice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_user_nice(struct task_struct *p, long int nice);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff810e65cc)
Location: kernel/sched/core.c:4733
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
Direct callers:
  - kernel/sys.c:set_one_prio
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:create_worker
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
  - kernel/hung_task.c:watchdog
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - drivers/block/loop.c:loop_configure
```
**Symbols:**

```
ffffffff810e02e0-ffffffff810e05b1: set_user_nice.part.0 (STB_LOCAL)
ffffffff810e05c0-ffffffff810e05e8: set_user_nice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_user_nice(struct task_struct *p, long int nice);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff810e44cc)
Location: kernel/sched/core.c:5506
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
Direct callers:
  - kernel/sys.c:set_one_prio
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:create_worker
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
  - kernel/hung_task.c:watchdog
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - drivers/block/loop.c:loop_configure
```
**Symbols:**

```
ffffffff810dd780-ffffffff810dda6d: set_user_nice.part.0 (STB_LOCAL)
ffffffff810dda70-ffffffff810dda98: set_user_nice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_user_nice(struct task_struct *p, long int nice);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff810e647c)
Location: kernel/sched/core.c:5717
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
Direct callers:
  - kernel/sys.c:set_one_prio
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:create_worker
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
  - kernel/hung_task.c:watchdog
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - drivers/block/loop.c:loop_configure
```
**Symbols:**

```
ffffffff810df1e0-ffffffff810df4dd: set_user_nice.part.0 (STB_LOCAL)
ffffffff810df4e0-ffffffff810df508: set_user_nice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_user_nice(struct task_struct *p, long int nice);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff810fd9bc)
Location: kernel/sched/core.c:6880
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
Direct callers:
  - kernel/sys.c:set_one_prio
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:create_worker
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
  - kernel/hung_task.c:watchdog
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
```
**Symbols:**

```
ffffffff810f41c0-ffffffff810f45e7: set_user_nice.part.0 (STB_LOCAL)
ffffffff810f45f0-ffffffff810f4618: set_user_nice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void set_user_nice(struct task_struct *p, long int nice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81110670)
Location: kernel/sched/core.c:6960
Inline: False
Direct callers:
  - kernel/sys.c:set_one_prio
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:create_worker
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
  - kernel/hung_task.c:watchdog
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
```
**Symbols:**

```
ffffffff81110670-ffffffff81110abb: set_user_nice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void set_user_nice(struct task_struct *p, long int nice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff811375c0)
Location: kernel/sched/core.c:7101
Inline: False
Direct callers:
  - kernel/sys.c:set_one_prio
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:create_worker
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
  - kernel/hung_task.c:watchdog
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
```
**Symbols:**

```
ffffffff811375c0-ffffffff81137a08: set_user_nice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void set_user_nice(struct task_struct *p, long int nice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81146630)
Location: kernel/sched/core.c:7202
Inline: False
Direct callers:
  - kernel/sys.c:set_one_prio
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:create_worker
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
  - kernel/hung_task.c:watchdog
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
```
**Symbols:**

```
ffffffff81146630-ffffffff81146a92: set_user_nice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void set_user_nice(struct task_struct *p, long int nice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81151e40)
Location: kernel/sched/core.c:7253
Inline: False
Direct callers:
  - kernel/sys.c:set_one_prio
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:create_worker
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
  - kernel/hung_task.c:watchdog
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
```
**Symbols:**

```
ffffffff81151e40-ffffffff811522ce: set_user_nice (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_user_nice(struct task_struct *p, long int nice);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffff80001013dac0)
Location: kernel/sched/core.c:4499
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:__arm64_sys_nice
Direct callers:
  - virt/kvm/kvm_main.c:kvm_vm_worker_thread
  - kernel/sys.c:set_one_prio
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:create_worker
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:__arm64_sys_nice
  - kernel/hung_task.c:watchdog
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - drivers/block/loop.c:loop_set_fd
```
**Symbols:**

```
ffff800010137ec8-ffff800010138098: set_user_nice.part.0 (STB_LOCAL)
ffff800010138098-ffff8000101380f4: set_user_nice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_user_nice(struct task_struct *p, long int nice);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (c038da9c)
Location: kernel/sched/core.c:4499
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:__se_sys_nice
Direct callers:
  - kernel/sys.c:set_one_prio
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:create_worker
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:__se_sys_nice
  - kernel/hung_task.c:watchdog
  - mm/ksm.c:ksm_scan_thread
  - drivers/block/loop.c:loop_set_fd
```
**Symbols:**

```
c03868d8-c0386ef4: set_user_nice.part.0 (STB_LOCAL)
c0386ef4-c0386f2c: set_user_nice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_user_nice(struct task_struct *p, long int nice);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (c00000000018cae0)
Location: kernel/sched/core.c:4499
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
Direct callers:
  - kernel/sys.c:set_one_prio
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:create_worker
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:__se_sys_nice
  - kernel/hung_task.c:watchdog
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - drivers/block/loop.c:loop_set_fd
```
**Symbols:**

```
c000000000183490-c000000000183bac: set_user_nice.part.0 (STB_LOCAL)
c000000000183bb0-c000000000183be4: set_user_nice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_user_nice(struct task_struct *p, long int nice);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffe0000ec95e)
Location: kernel/sched/core.c:4499
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
Direct callers:
  - kernel/sys.c:set_one_prio
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:create_worker
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/hung_task.c:watchdog
  - mm/ksm.c:ksm_scan_thread
  - drivers/block/loop.c:loop_set_fd
```
**Symbols:**

```
ffffffe0000e807a-ffffffe0000e8238: set_user_nice.part.0 (STB_LOCAL)
ffffffe0000e8238-ffffffe0000e828e: set_user_nice (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_user_nice(struct task_struct *p, long int nice);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff810d825f)
Location: kernel/sched/core.c:4499
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
Direct callers:
  - kernel/sys.c:set_one_prio
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:create_worker
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
  - kernel/hung_task.c:watchdog
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - drivers/block/loop.c:loop_set_fd
```
**Symbols:**

```
ffffffff810d1860-ffffffff810d1e97: set_user_nice.part.0 (STB_LOCAL)
ffffffff810d1ea0-ffffffff810d1ec8: set_user_nice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_user_nice(struct task_struct *p, long int nice);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff810c6c6f)
Location: kernel/sched/core.c:4499
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
Direct callers:
  - kernel/sys.c:set_one_prio
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:create_worker
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
  - kernel/hung_task.c:watchdog
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - drivers/block/loop.c:loop_set_fd
```
**Symbols:**

```
ffffffff810bfe20-ffffffff810c0455: set_user_nice.part.0 (STB_LOCAL)
ffffffff810c0460-ffffffff810c0488: set_user_nice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_user_nice(struct task_struct *p, long int nice);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff810d4a4f)
Location: kernel/sched/core.c:4499
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
Direct callers:
  - kernel/sys.c:set_one_prio
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:create_worker
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
  - kernel/hung_task.c:watchdog
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - drivers/block/loop.c:loop_set_fd
```
**Symbols:**

```
ffffffff810cfa20-ffffffff810cfc44: set_user_nice.part.0 (STB_LOCAL)
ffffffff810cfc50-ffffffff810cfc78: set_user_nice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_user_nice(struct task_struct *p, long int nice);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff810dfe3f)
Location: kernel/sched/core.c:4499
Inline: True
Inline callers:
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
Direct callers:
  - kernel/sys.c:set_one_prio
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:create_worker
  - kernel/sched/core.c:normalize_rt_tasks
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
  - kernel/hung_task.c:watchdog
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - drivers/block/loop.c:loop_set_fd
```
**Symbols:**

```
ffffffff810d8f60-ffffffff810d9595: set_user_nice.part.0 (STB_LOCAL)
ffffffff810d95a0-ffffffff810d95c8: set_user_nice (STB_GLOBAL)
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
