# Function: <code>cpumask_last</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (ffffffff826cbc14)
Location: include/linux/cpumask.h:193
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (ffffffff826f5d7d)
Location: include/linux/cpumask.h:195
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
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
In arch/x86/hyperv/mmu.c (ffffffff8102bd96)
Location: include/linux/cpumask.h:207
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102cc86)
Location: include/linux/cpumask.h:207
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
```
In kernel/sched/isolation.c (ffffffff828acbc7)
Location: include/linux/cpumask.h:207
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
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
In arch/x86/hyperv/mmu.c (ffffffff8102de6d)
Location: include/linux/cpumask.h:207
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102ebd0)
Location: include/linux/cpumask.h:207
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
```
In kernel/sched/isolation.c (ffffffff828c54fe)
Location: include/linux/cpumask.h:207
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
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
In arch/x86/hyperv/mmu.c (ffffffff8102e77d)
Location: include/linux/cpumask.h:223
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102f4e0)
Location: include/linux/cpumask.h:223
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
```
In kernel/sched/isolation.c (ffffffff828cdb67)
Location: include/linux/cpumask.h:223
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
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
In arch/x86/hyperv/mmu.c (ffffffff810312a7)
Location: include/linux/cpumask.h:228
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81031a20)
Location: include/linux/cpumask.h:228
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
```
In kernel/sched/isolation.c (ffffffff82ceef2b)
Location: include/linux/cpumask.h:228
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
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
In arch/x86/hyperv/mmu.c (ffffffff81031fcd)
Location: include/linux/cpumask.h:233
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81032720)
Location: include/linux/cpumask.h:233
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
```
In kernel/sched/isolation.c (ffffffff82fdb642)
Location: include/linux/cpumask.h:233
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
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
In arch/x86/hyperv/mmu.c (ffffffff81032ae4)
Location: include/linux/cpumask.h:204
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81033b70)
Location: include/linux/cpumask.h:204
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
```
In kernel/sched/isolation.c (ffffffff831e639c)
Location: include/linux/cpumask.h:204
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
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
In arch/x86/hyperv/mmu.c (ffffffff81037b4e)
Location: include/linux/cpumask.h:204
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81038f31)
Location: include/linux/cpumask.h:204
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
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
In arch/x86/hyperv/mmu.c (ffffffff8103de6a)
Location: include/linux/cpumask.h:239
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8103fd12)
Location: include/linux/cpumask.h:239
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
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
In arch/x86/hyperv/mmu.c (ffffffff81046cdf)
Location: include/linux/cpumask.h:162
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81048c62)
Location: include/linux/cpumask.h:162
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
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
In arch/x86/hyperv/mmu.c (ffffffff81046ef4)
Location: include/linux/cpumask.h:195
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81048ec2)
Location: include/linux/cpumask.h:195
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
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
In arch/x86/hyperv/mmu.c (ffffffff8104d613)
Location: include/linux/cpumask.h:195
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff81050132)
Location: include/linux/cpumask.h:195
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (ffff80001144543c)
Location: include/linux/cpumask.h:223
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (c151f56c)
Location: include/linux/cpumask.h:223
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
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
In arch/powerpc/perf/imc-pmu.c (c00000000012a208)
Location: include/linux/cpumask.h:223
Inline: True
Inline callers:
  - arch/powerpc/perf/imc-pmu.c:ppc_core_imc_cpu_offline
  - arch/powerpc/perf/imc-pmu.c:ppc_nest_imc_cpu_offline
```
```
In kernel/sched/isolation.c (c000000001369eb4)
Location: include/linux/cpumask.h:223
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (ffffffe000007218)
Location: include/linux/cpumask.h:223
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
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
In arch/x86/hyperv/mmu.c (ffffffff8102e8dd)
Location: include/linux/cpumask.h:223
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102f640)
Location: include/linux/cpumask.h:223
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
```
In kernel/sched/isolation.c (ffffffff828b68f7)
Location: include/linux/cpumask.h:223
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
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
In arch/x86/hyperv/mmu.c (ffffffff8101e43a)
Location: include/linux/cpumask.h:223
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8101ecc9)
Location: include/linux/cpumask.h:223
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
```
In kernel/sched/isolation.c (ffffffff828aeaed)
Location: include/linux/cpumask.h:223
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
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
In arch/x86/hyperv/mmu.c (ffffffff8102e73d)
Location: include/linux/cpumask.h:223
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff8102f4a0)
Location: include/linux/cpumask.h:223
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
```
In kernel/sched/isolation.c (ffffffff828c979b)
Location: include/linux/cpumask.h:223
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
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
In arch/x86/hyperv/mmu.c (ffffffff8102f52d)
Location: include/linux/cpumask.h:223
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
```
In arch/x86/hyperv/hv_apic.c (ffffffff810302e0)
Location: include/linux/cpumask.h:223
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
```
```
In kernel/sched/isolation.c (ffffffff828ceb4d)
Location: include/linux/cpumask.h:223
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
```
</details>
</li>
</ul>

## Differences
