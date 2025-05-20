# Function: <code>read_ti_thread_flags</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81041309)
Location: include/linux/thread_info.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/process.c (ffffffff81051815)
Location: include/linux/thread_info.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:arch_setup_new_exec
```
```
In arch/x86/mm/tlb.c (ffffffff810ae3a0)
Location: include/linux/thread_info.h:125
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In kernel/sched/core.c (ffffffff8110bb20)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In kernel/entry/common.c (ffffffff8118a3ef)
Location: include/linux/thread_info.h:125
Inline: True
Inline callers:
  - kernel/entry/common.c:exit_to_user_mode_prepare
  - kernel/entry/common.c:exit_to_user_mode_loop
```
```
In kernel/entry/kvm.c (ffffffff8118a716)
Location: include/linux/thread_info.h:125
Inline: True
Inline callers:
  - kernel/entry/kvm.c:xfer_to_guest_mode_handle_work
  - kernel/entry/kvm.c:xfer_to_guest_mode_handle_work
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
In arch/x86/kernel/process_64.c (ffffffff8104aa59)
Location: include/linux/thread_info.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/process.c (ffffffff8105ee95)
Location: include/linux/thread_info.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:arch_setup_new_exec
```
```
In arch/x86/mm/tlb.c (ffffffff810c8690)
Location: include/linux/thread_info.h:125
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In kernel/sched/core.c (ffffffff81131ee9)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In kernel/entry/common.c (ffffffff811c696f)
Location: include/linux/thread_info.h:125
Inline: True
Inline callers:
  - kernel/entry/common.c:exit_to_user_mode_prepare
  - kernel/entry/common.c:exit_to_user_mode_loop
```
```
In kernel/entry/kvm.c (ffffffff811c6cd6)
Location: include/linux/thread_info.h:125
Inline: True
Inline callers:
  - kernel/entry/kvm.c:xfer_to_guest_mode_handle_work
  - kernel/entry/kvm.c:xfer_to_guest_mode_handle_work
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
In arch/x86/kernel/process_64.c (ffffffff8104b299)
Location: include/linux/thread_info.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/process.c (ffffffff81060595)
Location: include/linux/thread_info.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:arch_setup_new_exec
```
```
In arch/x86/mm/tlb.c (ffffffff810cbc63)
Location: include/linux/thread_info.h:125
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In kernel/sched/core.c (ffffffff81140161)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In kernel/entry/common.c (ffffffff811d958f)
Location: include/linux/thread_info.h:125
Inline: True
Inline callers:
  - kernel/entry/common.c:exit_to_user_mode_prepare
  - kernel/entry/common.c:exit_to_user_mode_loop
```
```
In kernel/entry/kvm.c (ffffffff811d9ae6)
Location: include/linux/thread_info.h:125
Inline: True
Inline callers:
  - kernel/entry/kvm.c:xfer_to_guest_mode_handle_work
  - kernel/entry/kvm.c:xfer_to_guest_mode_handle_work
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
In arch/x86/kernel/process_64.c (ffffffff81052509)
Location: include/linux/thread_info.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/process.c (ffffffff81067615)
Location: include/linux/thread_info.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
  - arch/x86/kernel/process.c:arch_setup_new_exec
```
```
In arch/x86/mm/tlb.c (ffffffff810d42f3)
Location: include/linux/thread_info.h:125
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In kernel/sched/core.c (ffffffff8114b0c3)
Location: include/linux/thread_info.h:125
Inline: True
```
```
In kernel/entry/common.c (ffffffff82223e1a)
Location: include/linux/thread_info.h:125
Inline: True
Inline callers:
  - kernel/entry/common.c:irqentry_exit_to_user_mode
  - kernel/entry/common.c:irqentry_exit_to_user_mode
  - kernel/entry/common.c:syscall_exit_to_user_mode
  - kernel/entry/common.c:syscall_exit_to_user_mode
  - kernel/entry/common.c:syscall_exit_to_user_mode_work
  - kernel/entry/common.c:syscall_exit_to_user_mode_work
```
```
In kernel/entry/kvm.c (ffffffff811ef796)
Location: include/linux/thread_info.h:125
Inline: True
Inline callers:
  - kernel/entry/kvm.c:xfer_to_guest_mode_handle_work
  - kernel/entry/kvm.c:xfer_to_guest_mode_handle_work
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
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
