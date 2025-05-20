# Function: <code>switch_mm</code>

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
In kernel/sched/core.c (ffffffff8181fc18)
Location: arch/x86/include/asm/mmu_context.h:107
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:idle_task_exit
```
```
In mm/mmu_context.c (ffffffff811afc41)
Location: arch/x86/include/asm/mmu_context.h:107
Inline: True
Inline callers:
  - mm/mmu_context.c:use_mm
```
```
In fs/exec.c (ffffffff8121376e)
Location: arch/x86/include/asm/mmu_context.h:107
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void switch_mm(struct mm_struct *prev, struct mm_struct *next, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810726a0)
Location: arch/x86/mm/tlb.c:64
Inline: False
Direct callers:
  - mm/mmu_context.c:use_mm
```
**Symbols:**

```
ffffffff810726a0-ffffffff810726cd: switch_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void switch_mm(struct mm_struct *prev, struct mm_struct *next, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff81076250)
Location: arch/x86/mm/tlb.c:64
Inline: False
Direct callers:
  - mm/mmu_context.c:use_mm
```
**Symbols:**

```
ffffffff81076250-ffffffff8107627d: switch_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void switch_mm(struct mm_struct *prev, struct mm_struct *next, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff81074860)
Location: arch/x86/mm/tlb.c:53
Inline: False
Direct callers:
  - kernel/sched/core.c:idle_task_exit
  - mm/mmu_context.c:use_mm
```
**Symbols:**

```
ffffffff81074860-ffffffff8107488d: switch_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void switch_mm(struct mm_struct *prev, struct mm_struct *next, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8107a7c0)
Location: arch/x86/mm/tlb.c:145
Inline: False
Direct callers:
  - arch/x86/mm/tlb.c:enter_lazy_tlb
  - arch/x86/mm/tlb.c:leave_mm
  - kernel/sched/core.c:idle_task_exit
  - mm/mmu_context.c:use_mm
```
**Symbols:**

```
ffffffff8107a7c0-ffffffff8107a7ed: switch_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void switch_mm(struct mm_struct *prev, struct mm_struct *next, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8107d570)
Location: arch/x86/mm/tlb.c:145
Inline: False
Direct callers:
  - arch/x86/mm/tlb.c:enter_lazy_tlb
  - arch/x86/mm/tlb.c:leave_mm
  - arch/x86/platform/efi/efi_64.c:efi_switch_mm
  - kernel/sched/core.c:idle_task_exit
  - mm/mmu_context.c:use_mm
```
**Symbols:**

```
ffffffff8107d570-ffffffff8107d59d: switch_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void switch_mm(struct mm_struct *prev, struct mm_struct *next, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810840a0)
Location: arch/x86/mm/tlb.c:153
Inline: False
Direct callers:
  - arch/x86/mm/tlb.c:leave_mm
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog
  - kernel/sched/core.c:idle_task_exit
  - mm/mmu_context.c:use_mm
```
**Symbols:**

```
ffffffff810840a0-ffffffff810840cd: switch_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void switch_mm(struct mm_struct *prev, struct mm_struct *next, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff81087d30)
Location: arch/x86/mm/tlb.c:154
Inline: False
Direct callers:
  - arch/x86/mm/tlb.c:leave_mm
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog
  - kernel/sched/core.c:idle_task_exit
  - mm/mmu_context.c:use_mm
```
**Symbols:**

```
ffffffff81087d30-ffffffff81087d5d: switch_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void switch_mm(struct mm_struct *prev, struct mm_struct *next, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810889f0)
Location: arch/x86/mm/tlb.c:154
Inline: False
Direct callers:
  - arch/x86/mm/tlb.c:leave_mm
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog
  - kernel/sched/core.c:idle_task_exit
  - mm/mmu_context.c:use_mm
```
**Symbols:**

```
ffffffff810889f0-ffffffff81088a1d: switch_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void switch_mm(struct mm_struct *prev, struct mm_struct *next, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8108b2e5)
Location: arch/x86/mm/tlb.c:310
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:leave_mm
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - kernel/sched/core.c:idle_task_exit
  - fs/exec.c:exec_mmap
```
**Symbols:**

```
ffffffff8108b020-ffffffff8108b050: switch_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void switch_mm(struct mm_struct *prev, struct mm_struct *next, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8108b3a5)
Location: arch/x86/mm/tlb.c:309
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:leave_mm
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - kernel/sched/core.c:idle_task_exit
  - fs/exec.c:exec_mmap
```
**Symbols:**

```
ffffffff8108b120-ffffffff8108b150: switch_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void switch_mm(struct mm_struct *prev, struct mm_struct *next, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8108bf25)
Location: arch/x86/mm/tlb.c:310
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:leave_mm
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - kernel/sched/core.c:idle_task_exit
  - fs/exec.c:exec_mmap
```
**Symbols:**

```
ffffffff8108bce0-ffffffff8108bd18: switch_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void switch_mm(struct mm_struct *prev, struct mm_struct *next, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8109b6e5)
Location: arch/x86/mm/tlb.c:317
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:leave_mm
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - kernel/sched/core.c:idle_task_exit
  - fs/exec.c:exec_mmap
```
**Symbols:**

```
ffffffff8109b430-ffffffff8109b468: switch_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void switch_mm(struct mm_struct *prev, struct mm_struct *next, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810ae8e0)
Location: arch/x86/mm/tlb.c:318
Inline: False
Direct callers:
  - arch/x86/mm/tlb.c:leave_mm
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - kernel/sched/core.c:idle_task_exit
  - fs/exec.c:exec_mmap
```
**Symbols:**

```
ffffffff810ae8e0-ffffffff810ae91b: switch_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void switch_mm(struct mm_struct *prev, struct mm_struct *next, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810c8be0)
Location: arch/x86/mm/tlb.c:318
Inline: False
Direct callers:
  - arch/x86/mm/tlb.c:leave_mm
  - arch/x86/platform/efi/efi_64.c:efi_set_virtual_address_map
  - arch/x86/platform/efi/efi_64.c:efi_set_virtual_address_map
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map
  - kernel/sched/core.c:idle_task_exit
  - fs/exec.c:exec_mmap
```
**Symbols:**

```
ffffffff810c8be0-ffffffff810c8c38: switch_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void switch_mm(struct mm_struct *prev, struct mm_struct *next, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810cc220)
Location: arch/x86/mm/tlb.c:323
Inline: False
Direct callers:
  - arch/x86/mm/tlb.c:leave_mm
  - arch/x86/platform/efi/efi_64.c:efi_set_virtual_address_map
  - arch/x86/platform/efi/efi_64.c:efi_set_virtual_address_map
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map
  - kernel/sched/core.c:idle_task_exit
  - fs/exec.c:exec_mmap
```
**Symbols:**

```
ffffffff810cc220-ffffffff810cc278: switch_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void switch_mm(struct mm_struct *prev, struct mm_struct *next, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810d48b0)
Location: arch/x86/mm/tlb.c:324
Inline: False
Direct callers:
  - arch/x86/mm/tlb.c:leave_mm
  - arch/x86/platform/efi/efi_64.c:efi_set_virtual_address_map
  - arch/x86/platform/efi/efi_64.c:efi_set_virtual_address_map
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map
  - arch/x86/platform/efi/efi_64.c:arch_efi_call_virt_teardown
  - arch/x86/platform/efi/efi_64.c:arch_efi_call_virt_setup
  - kernel/sched/core.c:idle_task_exit
  - fs/exec.c:exec_mmap
```
**Symbols:**

```
ffffffff810d48b0-ffffffff810d4908: switch_mm (STB_GLOBAL)
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
In kernel/sched/core.c (ffff80001013d0c0)
Location: arch/arm64/include/asm/mmu_context.h:230
Inline: True
Inline callers:
  - kernel/sched/core.c:idle_task_exit
  - kernel/sched/core.c:__schedule
```
```
In mm/mmu_context.c (ffff8000102dff94)
Location: arch/arm64/include/asm/mmu_context.h:230
Inline: True
Inline callers:
  - mm/mmu_context.c:use_mm
```
```
In fs/exec.c (ffff80001038ecf4)
Location: arch/arm64/include/asm/mmu_context.h:230
Inline: True
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
In kernel/sched/core.c (c038d29c)
Location: arch/arm/include/asm/mmu_context.h:128
Inline: True
Inline callers:
  - kernel/sched/core.c:idle_task_exit
  - kernel/sched/core.c:__schedule
```
```
In mm/mmu_context.c (c05048d0)
Location: arch/arm/include/asm/mmu_context.h:128
Inline: True
Inline callers:
  - mm/mmu_context.c:use_mm
```
```
In fs/exec.c (c0575240)
Location: arch/arm/include/asm/mmu_context.h:128
Inline: True
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
In arch/powerpc/mm/book3s64/radix_tlb.c (c000000000096510)
Location: arch/powerpc/include/asm/mmu_context.h:199
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/radix_tlb.c:do_exit_flush_lazy_tlb
```
```
In kernel/sched/core.c (c00000000018be54)
Location: arch/powerpc/include/asm/mmu_context.h:199
Inline: True
Inline callers:
  - kernel/sched/core.c:idle_task_exit
```
```
In mm/mmu_context.c (c00000000039f7bc)
Location: arch/powerpc/include/asm/mmu_context.h:199
Inline: True
Inline callers:
  - mm/mmu_context.c:use_mm
```
```
In fs/exec.c (c000000000485ccc)
Location: arch/powerpc/include/asm/mmu_context.h:199
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void switch_mm(struct mm_struct *prev, struct mm_struct *next, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/riscv/mm/context.c (ffffffe0000ba140)
Location: arch/riscv/mm/context.c:43
Inline: False
Direct callers:
  - kernel/sched/core.c:__schedule
  - mm/mmu_context.c:use_mm
```
**Symbols:**

```
ffffffe0000ba140-ffffffe0000ba1fe: switch_mm (STB_GLOBAL)
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
void switch_mm(struct mm_struct *prev, struct mm_struct *next, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810879f0)
Location: arch/x86/mm/tlb.c:154
Inline: False
Direct callers:
  - arch/x86/mm/tlb.c:leave_mm
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog
  - kernel/sched/core.c:idle_task_exit
  - mm/mmu_context.c:use_mm
```
**Symbols:**

```
ffffffff810879f0-ffffffff81087a1d: switch_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void switch_mm(struct mm_struct *prev, struct mm_struct *next, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810766a5)
Location: arch/x86/mm/tlb.c:154
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:leave_mm
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog
  - kernel/sched/core.c:idle_task_exit
  - mm/mmu_context.c:use_mm
```
**Symbols:**

```
ffffffff81076660-ffffffff81076677: switch_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void switch_mm(struct mm_struct *prev, struct mm_struct *next, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810879a0)
Location: arch/x86/mm/tlb.c:154
Inline: False
Direct callers:
  - arch/x86/mm/tlb.c:leave_mm
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog
  - kernel/sched/core.c:idle_task_exit
  - mm/mmu_context.c:use_mm
```
**Symbols:**

```
ffffffff810879a0-ffffffff810879cd: switch_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void switch_mm(struct mm_struct *prev, struct mm_struct *next, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff81089b50)
Location: arch/x86/mm/tlb.c:154
Inline: False
Direct callers:
  - arch/x86/mm/tlb.c:leave_mm
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog
  - kernel/sched/core.c:idle_task_exit
  - mm/mmu_context.c:use_mm
  - mm/mmu_context.c:use_mm
```
**Symbols:**

```
ffffffff81089b50-ffffffff81089b7d: switch_mm (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>amd64</code> and <code>riscv64</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct task_struct *task</code>
</li>
<li>
<b>Param removed. </b>
<code>struct task_struct *tsk</code>
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
