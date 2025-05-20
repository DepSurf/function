# Function: <code>switch_mm_irqs_off</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void switch_mm_irqs_off(struct mm_struct *prev, struct mm_struct *next, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff81072410)
Location: arch/x86/mm/tlb.c:74
Inline: False
Direct callers:
  - arch/x86/mm/tlb.c:switch_mm
  - kernel/sched/core.c:idle_task_exit
  - kernel/sched/core.c:__schedule
```
**Symbols:**

```
ffffffff81072410-ffffffff81072691: switch_mm_irqs_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void switch_mm_irqs_off(struct mm_struct *prev, struct mm_struct *next, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff81075f80)
Location: arch/x86/mm/tlb.c:74
Inline: False
Direct callers:
  - arch/x86/mm/tlb.c:switch_mm
  - kernel/sched/core.c:idle_task_exit
  - kernel/sched/core.c:__schedule
```
**Symbols:**

```
ffffffff81075f80-ffffffff8107624a: switch_mm_irqs_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void switch_mm_irqs_off(struct mm_struct *prev, struct mm_struct *next, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff81074690)
Location: arch/x86/mm/tlb.c:63
Inline: False
Direct callers:
  - arch/x86/mm/tlb.c:switch_mm
  - kernel/sched/core.c:__schedule
```
**Symbols:**

```
ffffffff81074690-ffffffff8107485f: switch_mm_irqs_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void switch_mm_irqs_off(struct mm_struct *prev, struct mm_struct *next, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8107a3c0)
Location: arch/x86/mm/tlb.c:183
Inline: False
Direct callers:
  - arch/x86/mm/tlb.c:switch_mm
  - kernel/sched/core.c:__schedule
```
**Symbols:**

```
ffffffff8107a3c0-ffffffff8107a7b9: switch_mm_irqs_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void switch_mm_irqs_off(struct mm_struct *prev, struct mm_struct *next, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8107d160)
Location: arch/x86/mm/tlb.c:183
Inline: False
Direct callers:
  - arch/x86/mm/tlb.c:switch_mm
  - kernel/sched/core.c:__schedule
```
**Symbols:**

```
ffffffff8107d160-ffffffff8107d562: switch_mm_irqs_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void switch_mm_irqs_off(struct mm_struct *prev, struct mm_struct *next, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff81083b50)
Location: arch/x86/mm/tlb.c:274
Inline: False
Direct callers:
  - arch/x86/mm/tlb.c:switch_mm
  - kernel/sched/core.c:__schedule
```
**Symbols:**

```
ffffffff81083b50-ffffffff8108409c: switch_mm_irqs_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void switch_mm_irqs_off(struct mm_struct *prev, struct mm_struct *next, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff81087800)
Location: arch/x86/mm/tlb.c:275
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/mm/tlb.c:switch_mm
  - kernel/sched/core.c:__schedule
```
**Symbols:**

```
ffffffff81087800-ffffffff81087d2a: switch_mm_irqs_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void switch_mm_irqs_off(struct mm_struct *prev, struct mm_struct *next, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810884f0)
Location: arch/x86/mm/tlb.c:275
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/mm/tlb.c:switch_mm
  - kernel/sched/core.c:__schedule
```
**Symbols:**

```
ffffffff810884f0-ffffffff810889ea: switch_mm_irqs_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void switch_mm_irqs_off(struct mm_struct *prev, struct mm_struct *next, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8108ac90)
Location: arch/x86/mm/tlb.c:451
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/mm/tlb.c:leave_mm
  - kernel/kthread.c:kthread_use_mm
  - kernel/sched/core.c:__schedule
```
**Symbols:**

```
ffffffff8108ac90-ffffffff8108b01a: switch_mm_irqs_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void switch_mm_irqs_off(struct mm_struct *prev, struct mm_struct *next, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8108ae20)
Location: arch/x86/mm/tlb.c:422
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/mm/tlb.c:leave_mm
  - kernel/kthread.c:kthread_use_mm
  - kernel/sched/core.c:__schedule
```
**Symbols:**

```
ffffffff8108ae20-ffffffff8108b117: switch_mm_irqs_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void switch_mm_irqs_off(struct mm_struct *prev, struct mm_struct *next, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8108b920)
Location: arch/x86/mm/tlb.c:428
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/mm/tlb.c:flush_tlb_func
  - arch/x86/mm/tlb.c:leave_mm
  - kernel/kthread.c:kthread_use_mm
  - kernel/sched/core.c:__schedule
```
**Symbols:**

```
ffffffff8108b920-ffffffff8108bcd4: switch_mm_irqs_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void switch_mm_irqs_off(struct mm_struct *prev, struct mm_struct *next, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8109aef0)
Location: arch/x86/mm/tlb.c:488
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/mm/tlb.c:flush_tlb_func
  - arch/x86/mm/tlb.c:leave_mm
  - kernel/kthread.c:kthread_use_mm
  - kernel/sched/core.c:__schedule
```
**Symbols:**

```
ffffffff8109aef0-ffffffff8109b42a: switch_mm_irqs_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void switch_mm_irqs_off(struct mm_struct *prev, struct mm_struct *next, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810ae340)
Location: arch/x86/mm/tlb.c:489
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/mm/tlb.c:flush_tlb_func
  - arch/x86/mm/tlb.c:switch_mm
  - kernel/kthread.c:kthread_use_mm
  - kernel/sched/core.c:__schedule
```
**Symbols:**

```
ffffffff810ae340-ffffffff810ae8dc: switch_mm_irqs_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void switch_mm_irqs_off(struct mm_struct *prev, struct mm_struct *next, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810c8630)
Location: arch/x86/mm/tlb.c:489
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/mm/tlb.c:flush_tlb_func
  - arch/x86/mm/tlb.c:switch_mm
  - kernel/kthread.c:kthread_use_mm
  - kernel/sched/core.c:__schedule
```
**Symbols:**

```
ffffffff810c8630-ffffffff810c8bc5: switch_mm_irqs_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void switch_mm_irqs_off(struct mm_struct *prev, struct mm_struct *next, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810cbbf0)
Location: arch/x86/mm/tlb.c:494
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/mm/tlb.c:flush_tlb_func
  - arch/x86/mm/tlb.c:switch_mm
  - kernel/kthread.c:kthread_use_mm
  - kernel/sched/core.c:__schedule
```
**Symbols:**

```
ffffffff810cbbf0-ffffffff810cc209: switch_mm_irqs_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void switch_mm_irqs_off(struct mm_struct *prev, struct mm_struct *next, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810d4280)
Location: arch/x86/mm/tlb.c:495
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/mm/tlb.c:flush_tlb_func
  - arch/x86/mm/tlb.c:switch_mm
  - kernel/kthread.c:kthread_use_mm
  - kernel/sched/core.c:__schedule
```
**Symbols:**

```
ffffffff810d4280-ffffffff810d4899: switch_mm_irqs_off (STB_GLOBAL)
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
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void switch_mm_irqs_off(struct mm_struct *prev, struct mm_struct *next, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/mm/mmu_context.c (c00000000008a0c0)
Location: arch/powerpc/mm/mmu_context.c:34
Inline: False
Direct callers:
  - arch/powerpc/mm/book3s64/radix_tlb.c:do_exit_flush_lazy_tlb
  - kernel/sched/core.c:idle_task_exit
  - kernel/sched/core.c:__schedule
  - mm/mmu_context.c:use_mm
```
**Symbols:**

```
c00000000008a0c0-c00000000008a204: switch_mm_irqs_off (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void switch_mm_irqs_off(struct mm_struct *prev, struct mm_struct *next, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810874f0)
Location: arch/x86/mm/tlb.c:275
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/mm/tlb.c:switch_mm
  - kernel/sched/core.c:__schedule
```
**Symbols:**

```
ffffffff810874f0-ffffffff810879ea: switch_mm_irqs_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void switch_mm_irqs_off(struct mm_struct *prev, struct mm_struct *next, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff81076160)
Location: arch/x86/mm/tlb.c:275
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/mm/tlb.c:leave_mm
  - kernel/sched/core.c:__schedule
```
**Symbols:**

```
ffffffff81076160-ffffffff8107665f: switch_mm_irqs_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void switch_mm_irqs_off(struct mm_struct *prev, struct mm_struct *next, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810874a0)
Location: arch/x86/mm/tlb.c:275
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/mm/tlb.c:switch_mm
  - kernel/sched/core.c:__schedule
```
**Symbols:**

```
ffffffff810874a0-ffffffff8108799a: switch_mm_irqs_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void switch_mm_irqs_off(struct mm_struct *prev, struct mm_struct *next, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810895d0)
Location: arch/x86/mm/tlb.c:275
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/mm/tlb.c:switch_mm
  - kernel/sched/core.c:__schedule
```
**Symbols:**

```
ffffffff810895d0-ffffffff81089b4b: switch_mm_irqs_off (STB_GLOBAL)
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
