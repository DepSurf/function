# Function: <code>load_cr3</code>

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
In arch/x86/xen/mmu.c (ffffffff8101e468)
Location: arch/x86/include/asm/processor.h:210
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_exit_mmap
```
```
In arch/x86/xen/smp.c (ffffffff8102b3e6)
Location: arch/x86/include/asm/processor.h:210
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:stop_self
  - arch/x86/xen/smp.c:xen_cpu_disable
```
```
In arch/x86/mm/init.c (ffffffff81f777ed)
Location: arch/x86/include/asm/processor.h:210
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/tlb.c (ffffffff81072517)
Location: arch/x86/include/asm/processor.h:210
Inline: True
```
```
In kernel/sched/core.c (ffffffff8181fc49)
Location: arch/x86/include/asm/processor.h:210
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:idle_task_exit
```
```
In mm/mmu_context.c (ffffffff811afc76)
Location: arch/x86/include/asm/processor.h:210
Inline: True
Inline callers:
  - mm/mmu_context.c:use_mm
  - mm/mmu_context.c:use_mm
```
```
In fs/exec.c (ffffffff812137a2)
Location: arch/x86/include/asm/processor.h:210
Inline: True
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
In arch/x86/xen/mmu.c (ffffffff81020889)
Location: arch/x86/include/asm/processor.h:208
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_exit_mmap
```
```
In arch/x86/xen/smp.c (ffffffff8102a05f)
Location: arch/x86/include/asm/processor.h:208
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:stop_self
  - arch/x86/xen/smp.c:xen_cpu_disable
```
```
In arch/x86/mm/init.c (ffffffff81f9ff3f)
Location: arch/x86/include/asm/processor.h:208
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/tlb.c (ffffffff81072467)
Location: arch/x86/include/asm/processor.h:208
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
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
In arch/x86/xen/mmu.c (ffffffff81020fed)
Location: arch/x86/include/asm/processor.h:241
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_exit_mmap
```
```
In arch/x86/xen/smp.c (ffffffff8102a7af)
Location: arch/x86/include/asm/processor.h:241
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:stop_self
  - arch/x86/xen/smp.c:xen_cpu_disable
```
```
In arch/x86/mm/init.c (ffffffff81fdb4a1)
Location: arch/x86/include/asm/processor.h:241
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/tlb.c (ffffffff81075ff8)
Location: arch/x86/include/asm/processor.h:241
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
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
In arch/x86/xen/smp_pv.c (ffffffff810292cf)
Location: arch/x86/include/asm/processor.h:242
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_disable
```
```
In arch/x86/mm/init.c (ffffffff820bc323)
Location: arch/x86/include/asm/processor.h:242
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/tlb.c (ffffffff810746f4)
Location: arch/x86/include/asm/processor.h:242
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/smp_pv.c (ffffffff81029537)
Location: arch/x86/include/asm/processor.h:251
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_disable
Direct callers:
  - arch/x86/xen/smp_pv.c:stop_self
```
```
In arch/x86/mm/init.c (ffffffff826c2d53)
Location: arch/x86/include/asm/processor.h:251
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
**Symbols:**

```
ffffffff81029480-ffffffff810294bc: load_cr3.constprop.3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/smp_pv.c (ffffffff81029f99)
Location: arch/x86/include/asm/processor.h:249
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_disable
Direct callers:
  - arch/x86/xen/smp_pv.c:stop_self
```
```
In arch/x86/mm/init.c (ffffffff826ecf65)
Location: arch/x86/include/asm/processor.h:249
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
**Symbols:**

```
ffffffff81029ef0-ffffffff81029f2c: load_cr3.constprop.2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/smp_pv.c (ffffffff8102a579)
Location: arch/x86/include/asm/processor.h:238
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_disable
Direct callers:
  - arch/x86/xen/smp_pv.c:stop_self
```
```
In arch/x86/mm/init.c (ffffffff828a3af7)
Location: arch/x86/include/asm/processor.h:238
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
**Symbols:**

```
ffffffff8102a4d0-ffffffff8102a50c: load_cr3.constprop.3 (STB_LOCAL)
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
In arch/x86/xen/smp_pv.c (ffffffff8102c356)
Location: arch/x86/include/asm/processor.h:241
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_disable
```
```
In arch/x86/mm/init.c (ffffffff828bbf96)
Location: arch/x86/include/asm/processor.h:241
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
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
In arch/x86/xen/smp_pv.c (ffffffff8102ccf6)
Location: arch/x86/include/asm/processor.h:241
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_disable
```
```
In arch/x86/mm/init.c (ffffffff828c243d)
Location: arch/x86/include/asm/processor.h:241
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/smp_pv.c (ffffffff8102ecd9)
Location: arch/x86/include/asm/processor.h:255
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_disable
Direct callers:
  - arch/x86/xen/smp_pv.c:stop_self
```
```
In arch/x86/mm/init.c (ffffffff82ce5778)
Location: arch/x86/include/asm/processor.h:255
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
**Symbols:**

```
ffffffff8102ec30-ffffffff8102ec6c: load_cr3.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/smp_pv.c (ffffffff8102fae9)
Location: arch/x86/include/asm/processor.h:255
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_disable
Direct callers:
  - arch/x86/xen/smp_pv.c:stop_self
```
```
In arch/x86/mm/init.c (ffffffff82fd2fce)
Location: arch/x86/include/asm/processor.h:255
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
**Symbols:**

```
ffffffff8102fa40-ffffffff8102fa7c: load_cr3.constprop.0 (STB_LOCAL)
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
In arch/x86/xen/smp_pv.c (ffffffff810305d6)
Location: arch/x86/include/asm/processor.h:255
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_disable
```
```
In arch/x86/mm/init.c (ffffffff831ddc12)
Location: arch/x86/include/asm/processor.h:255
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
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
In arch/x86/xen/smp_pv.c (ffffffff81035458)
Location: arch/x86/include/asm/processor.h:257
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_disable
```
```
In arch/x86/mm/init.c (ffffffff832c0e7a)
Location: arch/x86/include/asm/processor.h:257
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
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
In arch/x86/xen/smp_pv.c (ffffffff8103b3c8)
Location: arch/x86/include/asm/processor.h:260
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_disable
```
```
In arch/x86/mm/init.c (ffffffff83473469)
Location: arch/x86/include/asm/processor.h:260
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
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
In arch/x86/xen/smp_pv.c (ffffffff81043b88)
Location: arch/x86/include/asm/processor.h:211
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_disable
```
```
In arch/x86/mm/init.c (ffffffff83e9ac09)
Location: arch/x86/include/asm/processor.h:211
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
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
In arch/x86/xen/smp_pv.c (ffffffff81043ca8)
Location: arch/x86/include/asm/processor.h:211
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_disable
```
```
In arch/x86/mm/init.c (ffffffff836be601)
Location: arch/x86/include/asm/processor.h:211
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
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
In arch/x86/xen/smp_pv.c (ffffffff8104a1a8)
Location: arch/x86/include/asm/processor.h:226
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_disable
```
```
In arch/x86/mm/init.c (ffffffff838ef0c1)
Location: arch/x86/include/asm/processor.h:226
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
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
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp_pv.c (ffffffff8102ce56)
Location: arch/x86/include/asm/processor.h:241
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_disable
```
```
In arch/x86/mm/init.c (ffffffff828ad413)
Location: arch/x86/include/asm/processor.h:241
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff828a56da)
Location: arch/x86/include/asm/processor.h:241
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
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
In arch/x86/xen/smp_pv.c (ffffffff8102ccb6)
Location: arch/x86/include/asm/processor.h:241
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_disable
```
```
In arch/x86/mm/init.c (ffffffff828c0312)
Location: arch/x86/include/asm/processor.h:241
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
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
In arch/x86/xen/smp_pv.c (ffffffff8102daa6)
Location: arch/x86/include/asm/processor.h:241
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_disable
```
```
In arch/x86/mm/init.c (ffffffff828c345d)
Location: arch/x86/include/asm/processor.h:241
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
</details>
</li>
</ul>

## Differences
