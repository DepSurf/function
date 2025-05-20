# Function: <code>enter_lazy_tlb</code>

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
In arch/x86/kernel/cpu/common.c (ffffffff8104126c)
Location: arch/x86/include/asm/mmu_context.h:99
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In kernel/exit.c (ffffffff81083b13)
Location: arch/x86/include/asm/mmu_context.h:99
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/sched/core.c (ffffffff8181ff40)
Location: arch/x86/include/asm/mmu_context.h:99
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:sched_init
```
```
In mm/mmu_context.c (ffffffff811afbc2)
Location: arch/x86/include/asm/mmu_context.h:99
Inline: True
Inline callers:
  - mm/mmu_context.c:unuse_mm
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
In arch/x86/kernel/cpu/common.c (ffffffff8104118b)
Location: arch/x86/include/asm/mmu_context.h:99
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In kernel/exit.c (ffffffff81086c2e)
Location: arch/x86/include/asm/mmu_context.h:99
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/sched/core.c (ffffffff81fa729c)
Location: arch/x86/include/asm/mmu_context.h:99
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:__schedule
```
```
In mm/mmu_context.c (ffffffff811c90f2)
Location: arch/x86/include/asm/mmu_context.h:99
Inline: True
Inline callers:
  - mm/mmu_context.c:unuse_mm
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
In arch/x86/kernel/cpu/common.c (ffffffff81040bd8)
Location: arch/x86/include/asm/mmu_context.h:100
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In kernel/exit.c (ffffffff8108bb99)
Location: arch/x86/include/asm/mmu_context.h:100
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/sched/core.c (ffffffff81fe2f2a)
Location: arch/x86/include/asm/mmu_context.h:100
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:__schedule
```
```
In mm/mmu_context.c (ffffffff811d91d2)
Location: arch/x86/include/asm/mmu_context.h:100
Inline: True
Inline callers:
  - mm/mmu_context.c:unuse_mm
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
In arch/x86/kernel/cpu/common.c (ffffffff8103eb78)
Location: arch/x86/include/asm/mmu_context.h:126
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In kernel/exit.c (ffffffff81088d2f)
Location: arch/x86/include/asm/mmu_context.h:126
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/sched/core.c (ffffffff820c37ad)
Location: arch/x86/include/asm/mmu_context.h:126
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:__schedule
```
```
In mm/mmu_context.c (ffffffff811e1fe2)
Location: arch/x86/include/asm/mmu_context.h:126
Inline: True
Inline callers:
  - mm/mmu_context.c:unuse_mm
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void enter_lazy_tlb(struct mm_struct *mm, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8107aa90)
Location: arch/x86/mm/tlb.c:346
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - kernel/exit.c:do_exit
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:__schedule
  - mm/mmu_context.c:unuse_mm
```
**Symbols:**

```
ffffffff8107aa90-ffffffff8107aaca: enter_lazy_tlb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void enter_lazy_tlb(struct mm_struct *mm, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8107d840)
Location: arch/x86/mm/tlb.c:359
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - kernel/exit.c:do_exit
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:__schedule
  - mm/mmu_context.c:unuse_mm
```
**Symbols:**

```
ffffffff8107d840-ffffffff8107d87a: enter_lazy_tlb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void enter_lazy_tlb(struct mm_struct *mm, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff81084380)
Location: arch/x86/mm/tlb.c:460
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - kernel/exit.c:do_exit
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:__schedule
  - mm/mmu_context.c:unuse_mm
```
**Symbols:**

```
ffffffff81084380-ffffffff810843a3: enter_lazy_tlb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void enter_lazy_tlb(struct mm_struct *mm, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff81088000)
Location: arch/x86/mm/tlb.c:461
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - kernel/exit.c:do_exit
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:__schedule
  - mm/mmu_context.c:unuse_mm
```
**Symbols:**

```
ffffffff81088000-ffffffff81088023: enter_lazy_tlb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void enter_lazy_tlb(struct mm_struct *mm, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff81088cc0)
Location: arch/x86/mm/tlb.c:461
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - kernel/exit.c:do_exit
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:__schedule
  - mm/mmu_context.c:unuse_mm
```
**Symbols:**

```
ffffffff81088cc0-ffffffff81088ce3: enter_lazy_tlb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void enter_lazy_tlb(struct mm_struct *mm, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8108b320)
Location: arch/x86/mm/tlb.c:637
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - kernel/exit.c:exit_mm
  - kernel/kthread.c:kthread_unuse_mm
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:__schedule
```
**Symbols:**

```
ffffffff8108b320-ffffffff8108b343: enter_lazy_tlb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void enter_lazy_tlb(struct mm_struct *mm, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8108b3e0)
Location: arch/x86/mm/tlb.c:596
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - kernel/exit.c:exit_mm
  - kernel/kthread.c:kthread_unuse_mm
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:__schedule
```
**Symbols:**

```
ffffffff8108b3e0-ffffffff8108b403: enter_lazy_tlb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void enter_lazy_tlb(struct mm_struct *mm, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8108bf70)
Location: arch/x86/mm/tlb.c:603
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - kernel/exit.c:exit_mm
  - kernel/kthread.c:kthread_unuse_mm
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:__schedule
```
**Symbols:**

```
ffffffff8108bf70-ffffffff8108bf93: enter_lazy_tlb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void enter_lazy_tlb(struct mm_struct *mm, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8109b730)
Location: arch/x86/mm/tlb.c:662
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - kernel/exit.c:exit_mm
  - kernel/kthread.c:kthread_unuse_mm
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:__schedule
```
**Symbols:**

```
ffffffff8109b730-ffffffff8109b753: enter_lazy_tlb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void enter_lazy_tlb(struct mm_struct *mm, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810aec20)
Location: arch/x86/mm/tlb.c:663
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - kernel/exit.c:exit_mm
  - kernel/kthread.c:kthread_unuse_mm
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:__schedule
```
**Symbols:**

```
ffffffff810aec20-ffffffff810aec49: enter_lazy_tlb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void enter_lazy_tlb(struct mm_struct *mm, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810c8f80)
Location: arch/x86/mm/tlb.c:663
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - kernel/exit.c:exit_mm
  - kernel/kthread.c:kthread_unuse_mm
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:__schedule
```
**Symbols:**

```
ffffffff810c8f80-ffffffff810c8fa9: enter_lazy_tlb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void enter_lazy_tlb(struct mm_struct *mm, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810cc5c0)
Location: arch/x86/mm/tlb.c:677
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - kernel/exit.c:exit_mm
  - kernel/kthread.c:kthread_unuse_mm
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:__schedule
```
**Symbols:**

```
ffffffff810cc5c0-ffffffff810cc5e9: enter_lazy_tlb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void enter_lazy_tlb(struct mm_struct *mm, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810d4c50)
Location: arch/x86/mm/tlb.c:678
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - kernel/exit.c:exit_mm
  - kernel/kthread.c:kthread_unuse_mm
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:__schedule
```
**Symbols:**

```
ffffffff810d4c50-ffffffff810d4c79: enter_lazy_tlb (STB_GLOBAL)
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
In kernel/exit.c (ffff8000100fd4f0)
Location: arch/arm64/include/asm/mmu_context.h:204
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/sched/core.c (ffff800011444e78)
Location: arch/arm64/include/asm/mmu_context.h:204
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:__schedule
```
```
In mm/mmu_context.c (ffff8000102dfea0)
Location: arch/arm64/include/asm/mmu_context.h:204
Inline: True
Inline callers:
  - mm/mmu_context.c:unuse_mm
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
In arch/arm/kernel/smp.c (0)
Location: arch/arm/include/asm/mmu_context.h:117
Inline: True
```
```
In kernel/exit.c (0)
Location: arch/arm/include/asm/mmu_context.h:117
Inline: True
```
```
In kernel/sched/core.c (0)
Location: arch/arm/include/asm/mmu_context.h:117
Inline: True
```
```
In mm/mmu_context.c (0)
Location: arch/arm/include/asm/mmu_context.h:117
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
In kernel/exit.c (0)
Location: arch/powerpc/include/asm/mmu_context.h:223
Inline: True
```
```
In kernel/sched/core.c (0)
Location: arch/powerpc/include/asm/mmu_context.h:223
Inline: True
```
```
In mm/mmu_context.c (0)
Location: arch/powerpc/include/asm/mmu_context.h:223
Inline: True
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
In kernel/exit.c (0)
Location: arch/riscv/include/asm/mmu_context.h:16
Inline: True
```
```
In kernel/sched/core.c (0)
Location: arch/riscv/include/asm/mmu_context.h:16
Inline: True
```
```
In mm/mmu_context.c (0)
Location: arch/riscv/include/asm/mmu_context.h:16
Inline: True
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
void enter_lazy_tlb(struct mm_struct *mm, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff81087cc0)
Location: arch/x86/mm/tlb.c:461
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - kernel/exit.c:do_exit
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:__schedule
  - mm/mmu_context.c:unuse_mm
```
**Symbols:**

```
ffffffff81087cc0-ffffffff81087ce3: enter_lazy_tlb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void enter_lazy_tlb(struct mm_struct *mm, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff81076930)
Location: arch/x86/mm/tlb.c:461
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - kernel/exit.c:do_exit
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:__schedule
  - mm/mmu_context.c:unuse_mm
```
**Symbols:**

```
ffffffff81076930-ffffffff81076953: enter_lazy_tlb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void enter_lazy_tlb(struct mm_struct *mm, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff81087c70)
Location: arch/x86/mm/tlb.c:461
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - kernel/exit.c:do_exit
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:__schedule
  - mm/mmu_context.c:unuse_mm
```
**Symbols:**

```
ffffffff81087c70-ffffffff81087c93: enter_lazy_tlb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void enter_lazy_tlb(struct mm_struct *mm, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff81089e60)
Location: arch/x86/mm/tlb.c:461
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - kernel/exit.c:do_exit
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:__schedule
  - mm/mmu_context.c:unuse_mm
```
**Symbols:**

```
ffffffff81089e60-ffffffff81089e83: enter_lazy_tlb (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
