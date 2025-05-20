# Function: <code>entering_ack_irq</code>

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
In arch/x86/kernel/irq.c (ffffffff81030a66)
Location: arch/x86/include/asm/apic.h:638
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_trace_x86_platform_ipi
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81826f66)
Location: arch/x86/include/asm/apic.h:638
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:smp_trace_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81055976)
Location: arch/x86/include/asm/apic.h:638
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt
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
In arch/x86/kernel/irq.c (ffffffff8102fc3c)
Location: arch/x86/include/asm/apic.h:645
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:smp_trace_x86_platform_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
```
```
In arch/x86/kernel/apic/apic.c (ffffffff818a19cc)
Location: arch/x86/include/asm/apic.h:645
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_trace_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81055c13)
Location: arch/x86/include/asm/apic.h:645
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt
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
In arch/x86/kernel/irq.c (ffffffff8102fc1c)
Location: arch/x86/include/asm/apic.h:644
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:smp_trace_x86_platform_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
```
```
In arch/x86/kernel/apic/apic.c (ffffffff818d6f1c)
Location: arch/x86/include/asm/apic.h:644
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_trace_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff810589b3)
Location: arch/x86/include/asm/apic.h:644
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt
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
In arch/x86/kernel/irq.c (ffffffff8190e10c)
Location: arch/x86/include/asm/apic.h:624
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:smp_trace_x86_platform_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8190e8fc)
Location: arch/x86/include/asm/apic.h:624
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_trace_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff8190eb8f)
Location: arch/x86/include/asm/apic.h:624
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt
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
In arch/x86/kernel/irq.c (ffffffff8103015a)
Location: arch/x86/include/asm/apic.h:527
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81a02d2c)
Location: arch/x86/include/asm/apic.h:527
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81a0313d)
Location: arch/x86/include/asm/apic.h:527
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt
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
In arch/x86/hyperv/hv_init.c (ffffffff81a01bb5)
Location: arch/x86/include/asm/apic.h:521
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_reenlightenment_intr
```
```
In arch/x86/kernel/irq.c (ffffffff810313ba)
Location: arch/x86/include/asm/apic.h:521
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81a0245c)
Location: arch/x86/include/asm/apic.h:521
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81a0285d)
Location: arch/x86/include/asm/apic.h:521
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt
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
In arch/x86/hyperv/hv_init.c (ffffffff81c01bc5)
Location: arch/x86/include/asm/apic.h:521
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_reenlightenment_intr
```
```
In arch/x86/kernel/irq.c (ffffffff8103265a)
Location: arch/x86/include/asm/apic.h:521
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81c024fc)
Location: arch/x86/include/asm/apic.h:521
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81c0291d)
Location: arch/x86/include/asm/apic.h:521
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt
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
In arch/x86/hyperv/hv_init.c (ffffffff81c01da5)
Location: arch/x86/include/asm/apic.h:522
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_reenlightenment_intr
```
```
In arch/x86/kernel/irq.c (ffffffff8103436a)
Location: arch/x86/include/asm/apic.h:522
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff81c0245a)
Location: arch/x86/include/asm/apic.h:522
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:acrn_hv_vector_handler
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81c0274c)
Location: arch/x86/include/asm/apic.h:522
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81c02b9d)
Location: arch/x86/include/asm/apic.h:522
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt
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
In arch/x86/hyperv/hv_init.c (ffffffff81c01dc5)
Location: arch/x86/include/asm/apic.h:531
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_reenlightenment_intr
```
```
In arch/x86/kernel/irq.c (ffffffff81034c2a)
Location: arch/x86/include/asm/apic.h:531
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff81c0248a)
Location: arch/x86/include/asm/apic.h:531
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:acrn_hv_vector_handler
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81c0277c)
Location: arch/x86/include/asm/apic.h:531
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81c02bcd)
Location: arch/x86/include/asm/apic.h:531
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt
```
</details>
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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In arch/x86/hyperv/hv_init.c (ffffffff81c01da5)
Location: arch/x86/include/asm/apic.h:531
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_reenlightenment_intr
```
```
In arch/x86/kernel/irq.c (ffffffff81034d8a)
Location: arch/x86/include/asm/apic.h:531
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff81c0246a)
Location: arch/x86/include/asm/apic.h:531
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:acrn_hv_vector_handler
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81c0275c)
Location: arch/x86/include/asm/apic.h:531
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81c02bad)
Location: arch/x86/include/asm/apic.h:531
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt
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
In arch/x86/hyperv/hv_init.c (ffffffff81c01c55)
Location: arch/x86/include/asm/apic.h:531
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_reenlightenment_intr
```
```
In arch/x86/kernel/irq.c (ffffffff810246ca)
Location: arch/x86/include/asm/apic.h:531
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff81c0231a)
Location: arch/x86/include/asm/apic.h:531
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:acrn_hv_vector_handler
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81c0260c)
Location: arch/x86/include/asm/apic.h:531
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81c02a5d)
Location: arch/x86/include/asm/apic.h:531
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt
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
In arch/x86/hyperv/hv_init.c (ffffffff81c01d85)
Location: arch/x86/include/asm/apic.h:531
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_reenlightenment_intr
```
```
In arch/x86/kernel/irq.c (ffffffff81034bea)
Location: arch/x86/include/asm/apic.h:531
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81c026cc)
Location: arch/x86/include/asm/apic.h:531
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81c02b1d)
Location: arch/x86/include/asm/apic.h:531
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt
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
In arch/x86/hyperv/hv_init.c (ffffffff81c01de5)
Location: arch/x86/include/asm/apic.h:531
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_reenlightenment_intr
```
```
In arch/x86/kernel/irq.c (ffffffff81035b4a)
Location: arch/x86/include/asm/apic.h:531
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_wakeup_ipi
  - arch/x86/kernel/irq.c:smp_kvm_posted_intr_ipi
  - arch/x86/kernel/irq.c:smp_x86_platform_ipi
```
```
In arch/x86/kernel/cpu/acrn.c (ffffffff81c0259a)
Location: arch/x86/include/asm/apic.h:531
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/acrn.c:acrn_hv_vector_handler
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81c0291c)
Location: arch/x86/include/asm/apic.h:531
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
```
```
In arch/x86/kernel/apic/vector.c (ffffffff81c02e0d)
Location: arch/x86/include/asm/apic.h:531
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:smp_irq_move_cleanup_interrupt
```
</details>
</li>
</ul>

## Differences
