# Function: <code>HYPERVISOR_xenpmu_op</code>

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
In arch/x86/xen/pmu.c (ffffffff81026382)
Location: arch/x86/include/asm/xen/hypercall.h:469
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:pmu_apic_update
  - arch/x86/xen/pmu.c:xen_pmu_irq_handler
  - arch/x86/xen/pmu.c:xen_pmu_init
  - arch/x86/xen/pmu.c:xen_pmu_finish
```
```
In drivers/xen/sys-hypervisor.c (ffffffff814d374c)
Location: arch/x86/include/asm/xen/hypercall.h:469
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:pmu_features_store
  - drivers/xen/sys-hypervisor.c:pmu_features_show
  - drivers/xen/sys-hypervisor.c:pmu_mode_show
  - drivers/xen/sys-hypervisor.c:pmu_mode_store
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
In arch/x86/xen/pmu.c (ffffffff81025c9c)
Location: arch/x86/include/asm/xen/hypercall.h:470
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_finish
  - arch/x86/xen/pmu.c:xen_pmu_init
  - arch/x86/xen/pmu.c:xen_pmu_irq_handler
  - arch/x86/xen/pmu.c:pmu_apic_update
```
```
In drivers/xen/sys-hypervisor.c (ffffffff815245b9)
Location: arch/x86/include/asm/xen/hypercall.h:470
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:pmu_features_show
  - drivers/xen/sys-hypervisor.c:pmu_features_store
  - drivers/xen/sys-hypervisor.c:pmu_mode_show
  - drivers/xen/sys-hypervisor.c:pmu_mode_store
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
In arch/x86/xen/pmu.c (ffffffff810263ec)
Location: arch/x86/include/asm/xen/hypercall.h:470
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_finish
  - arch/x86/xen/pmu.c:xen_pmu_init
  - arch/x86/xen/pmu.c:xen_pmu_irq_handler
  - arch/x86/xen/pmu.c:pmu_apic_update
```
```
In drivers/xen/sys-hypervisor.c (ffffffff81550a79)
Location: arch/x86/include/asm/xen/hypercall.h:470
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:pmu_features_show
  - drivers/xen/sys-hypervisor.c:pmu_features_store
  - drivers/xen/sys-hypervisor.c:pmu_mode_show
  - drivers/xen/sys-hypervisor.c:pmu_mode_store
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
In arch/x86/xen/pmu.c (ffffffff8101cd45)
Location: arch/x86/include/asm/xen/hypercall.h:475
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_finish
  - arch/x86/xen/pmu.c:xen_pmu_init
  - arch/x86/xen/pmu.c:xen_pmu_irq_handler
  - arch/x86/xen/pmu.c:pmu_apic_update
```
```
In drivers/xen/sys-hypervisor.c (ffffffff81565199)
Location: arch/x86/include/asm/xen/hypercall.h:475
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:pmu_features_show
  - drivers/xen/sys-hypervisor.c:pmu_features_store
  - drivers/xen/sys-hypervisor.c:pmu_mode_show
  - drivers/xen/sys-hypervisor.c:pmu_mode_store
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
In arch/x86/xen/pmu.c (ffffffff8101d9f5)
Location: arch/x86/include/asm/xen/hypercall.h:475
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_finish
  - arch/x86/xen/pmu.c:xen_pmu_init
  - arch/x86/xen/pmu.c:xen_pmu_irq_handler
  - arch/x86/xen/pmu.c:pmu_apic_update
```
```
In drivers/xen/sys-hypervisor.c (ffffffff815c9339)
Location: arch/x86/include/asm/xen/hypercall.h:475
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:pmu_features_show
  - drivers/xen/sys-hypervisor.c:pmu_features_store
  - drivers/xen/sys-hypervisor.c:pmu_mode_show
  - drivers/xen/sys-hypervisor.c:pmu_mode_store
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
In arch/x86/xen/pmu.c (ffffffff8101e355)
Location: arch/x86/include/asm/xen/hypercall.h:475
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_finish
  - arch/x86/xen/pmu.c:xen_pmu_init
  - arch/x86/xen/pmu.c:xen_pmu_irq_handler
  - arch/x86/xen/pmu.c:pmu_apic_update
```
```
In drivers/xen/sys-hypervisor.c (ffffffff81601c06)
Location: arch/x86/include/asm/xen/hypercall.h:475
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:pmu_features_show
  - drivers/xen/sys-hypervisor.c:pmu_features_store
  - drivers/xen/sys-hypervisor.c:pmu_mode_show
  - drivers/xen/sys-hypervisor.c:pmu_mode_store
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
In arch/x86/xen/pmu.c (ffffffff8101dbe5)
Location: arch/x86/include/asm/xen/hypercall.h:423
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_finish
  - arch/x86/xen/pmu.c:xen_pmu_init
  - arch/x86/xen/pmu.c:xen_pmu_irq_handler
  - arch/x86/xen/pmu.c:pmu_apic_update
```
```
In drivers/xen/sys-hypervisor.c (ffffffff8161ccf6)
Location: arch/x86/include/asm/xen/hypercall.h:423
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:pmu_features_show
  - drivers/xen/sys-hypervisor.c:pmu_features_store
  - drivers/xen/sys-hypervisor.c:pmu_mode_show
  - drivers/xen/sys-hypervisor.c:pmu_mode_store
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
In arch/x86/xen/pmu.c (ffffffff8101f77f)
Location: arch/x86/include/asm/xen/hypercall.h:433
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_finish
  - arch/x86/xen/pmu.c:xen_pmu_init
  - arch/x86/xen/pmu.c:xen_pmu_irq_handler
  - arch/x86/xen/pmu.c:pmu_apic_update
```
```
In drivers/xen/sys-hypervisor.c (ffffffff8164ff36)
Location: arch/x86/include/asm/xen/hypercall.h:433
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:pmu_features_show
  - drivers/xen/sys-hypervisor.c:pmu_features_store
  - drivers/xen/sys-hypervisor.c:pmu_mode_show
  - drivers/xen/sys-hypervisor.c:pmu_mode_store
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
In arch/x86/xen/pmu.c (ffffffff810200df)
Location: arch/x86/include/asm/xen/hypercall.h:433
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_finish
  - arch/x86/xen/pmu.c:xen_pmu_init
  - arch/x86/xen/pmu.c:xen_pmu_irq_handler
  - arch/x86/xen/pmu.c:pmu_apic_update
```
```
In drivers/xen/sys-hypervisor.c (ffffffff816724d6)
Location: arch/x86/include/asm/xen/hypercall.h:433
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:pmu_features_show
  - drivers/xen/sys-hypervisor.c:pmu_features_store
  - drivers/xen/sys-hypervisor.c:pmu_mode_show
  - drivers/xen/sys-hypervisor.c:pmu_mode_store
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
In arch/x86/xen/pmu.c (ffffffff8102272f)
Location: arch/x86/include/asm/xen/hypercall.h:433
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_finish
  - arch/x86/xen/pmu.c:xen_pmu_init
  - arch/x86/xen/pmu.c:xen_pmu_irq_handler
  - arch/x86/xen/pmu.c:pmu_apic_update
```
```
In drivers/xen/sys-hypervisor.c (ffffffff81722ba4)
Location: arch/x86/include/asm/xen/hypercall.h:433
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:pmu_features_show
  - drivers/xen/sys-hypervisor.c:pmu_features_store
  - drivers/xen/sys-hypervisor.c:pmu_mode_show
  - drivers/xen/sys-hypervisor.c:pmu_mode_store
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
In arch/x86/xen/pmu.c (ffffffff81022e0f)
Location: arch/x86/include/asm/xen/hypercall.h:433
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_finish
  - arch/x86/xen/pmu.c:xen_pmu_init
  - arch/x86/xen/pmu.c:xen_pmu_irq_handler
  - arch/x86/xen/pmu.c:pmu_apic_update
```
```
In drivers/xen/sys-hypervisor.c (ffffffff8173f804)
Location: arch/x86/include/asm/xen/hypercall.h:433
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:pmu_features_show
  - drivers/xen/sys-hypervisor.c:pmu_features_store
  - drivers/xen/sys-hypervisor.c:pmu_mode_show
  - drivers/xen/sys-hypervisor.c:pmu_mode_store
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
In arch/x86/xen/pmu.c (ffffffff8102512f)
Location: arch/x86/include/asm/xen/hypercall.h:433
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_finish
  - arch/x86/xen/pmu.c:xen_pmu_init
  - arch/x86/xen/pmu.c:xen_pmu_irq_handler
  - arch/x86/xen/pmu.c:pmu_apic_update
```
```
In drivers/xen/sys-hypervisor.c (ffffffff81723254)
Location: arch/x86/include/asm/xen/hypercall.h:433
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:pmu_features_show
  - drivers/xen/sys-hypervisor.c:pmu_features_store
  - drivers/xen/sys-hypervisor.c:pmu_mode_show
  - drivers/xen/sys-hypervisor.c:pmu_mode_store
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
In arch/x86/xen/pmu.c (ffffffff81029617)
Location: arch/x86/include/asm/xen/hypercall.h:433
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_finish
  - arch/x86/xen/pmu.c:xen_pmu_init
  - arch/x86/xen/pmu.c:xen_pmu_irq_handler
  - arch/x86/xen/pmu.c:pmu_apic_update
```
```
In drivers/xen/sys-hypervisor.c (ffffffff817a2044)
Location: arch/x86/include/asm/xen/hypercall.h:433
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:pmu_features_show
  - drivers/xen/sys-hypervisor.c:pmu_features_store
  - drivers/xen/sys-hypervisor.c:pmu_mode_show
  - drivers/xen/sys-hypervisor.c:pmu_mode_store
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
In arch/x86/xen/pmu.c (ffffffff8102df9f)
Location: arch/x86/include/asm/xen/hypercall.h:488
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_finish
  - arch/x86/xen/pmu.c:xen_pmu_init
  - arch/x86/xen/pmu.c:xen_pmu_irq_handler
  - arch/x86/xen/pmu.c:pmu_apic_update
```
```
In drivers/xen/sys-hypervisor.c (ffffffff818dc1a6)
Location: arch/x86/include/asm/xen/hypercall.h:488
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:pmu_features_show
  - drivers/xen/sys-hypervisor.c:pmu_features_store
  - drivers/xen/sys-hypervisor.c:pmu_mode_show
  - drivers/xen/sys-hypervisor.c:pmu_mode_store
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
In arch/x86/xen/pmu.c (ffffffff8103538f)
Location: arch/x86/include/asm/xen/hypercall.h:488
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_finish
  - arch/x86/xen/pmu.c:xen_pmu_init
  - arch/x86/xen/pmu.c:xen_pmu_irq_handler
  - arch/x86/xen/pmu.c:pmu_apic_update
```
```
In drivers/xen/sys-hypervisor.c (ffffffff81a2f406)
Location: arch/x86/include/asm/xen/hypercall.h:488
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:pmu_features_show
  - drivers/xen/sys-hypervisor.c:pmu_features_store
  - drivers/xen/sys-hypervisor.c:pmu_mode_show
  - drivers/xen/sys-hypervisor.c:pmu_mode_store
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
In arch/x86/xen/pmu.c (ffffffff8103530f)
Location: arch/x86/include/asm/xen/hypercall.h:488
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_finish
  - arch/x86/xen/pmu.c:xen_pmu_init
  - arch/x86/xen/pmu.c:xen_pmu_irq_handler
  - arch/x86/xen/pmu.c:pmu_apic_update
```
```
In drivers/xen/sys-hypervisor.c (ffffffff81a78c16)
Location: arch/x86/include/asm/xen/hypercall.h:488
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:pmu_features_show
  - drivers/xen/sys-hypervisor.c:pmu_features_store
  - drivers/xen/sys-hypervisor.c:pmu_mode_show
  - drivers/xen/sys-hypervisor.c:pmu_mode_store
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
In arch/x86/xen/pmu.c (ffffffff8103b50f)
Location: arch/x86/include/asm/xen/hypercall.h:488
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_finish
  - arch/x86/xen/pmu.c:xen_pmu_init
  - arch/x86/xen/pmu.c:xen_pmu_irq_handler
  - arch/x86/xen/pmu.c:pmu_apic_update
```
```
In drivers/xen/sys-hypervisor.c (ffffffff81acaf36)
Location: arch/x86/include/asm/xen/hypercall.h:488
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:pmu_features_show
  - drivers/xen/sys-hypervisor.c:pmu_features_store
  - drivers/xen/sys-hypervisor.c:pmu_mode_show
  - drivers/xen/sys-hypervisor.c:pmu_mode_store
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
In arch/x86/xen/pmu.c (ffffffff8102023f)
Location: arch/x86/include/asm/xen/hypercall.h:433
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_finish
  - arch/x86/xen/pmu.c:xen_pmu_init
  - arch/x86/xen/pmu.c:xen_pmu_irq_handler
  - arch/x86/xen/pmu.c:pmu_apic_update
```
```
In drivers/xen/sys-hypervisor.c (ffffffff816381c6)
Location: arch/x86/include/asm/xen/hypercall.h:433
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:pmu_features_show
  - drivers/xen/sys-hypervisor.c:pmu_features_store
  - drivers/xen/sys-hypervisor.c:pmu_mode_show
  - drivers/xen/sys-hypervisor.c:pmu_mode_store
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff8102009f)
Location: arch/x86/include/asm/xen/hypercall.h:433
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_finish
  - arch/x86/xen/pmu.c:xen_pmu_init
  - arch/x86/xen/pmu.c:xen_pmu_irq_handler
  - arch/x86/xen/pmu.c:pmu_apic_update
```
```
In drivers/xen/sys-hypervisor.c (ffffffff81666316)
Location: arch/x86/include/asm/xen/hypercall.h:433
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:pmu_features_show
  - drivers/xen/sys-hypervisor.c:pmu_features_store
  - drivers/xen/sys-hypervisor.c:pmu_mode_show
  - drivers/xen/sys-hypervisor.c:pmu_mode_store
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
In arch/x86/xen/pmu.c (ffffffff810202ef)
Location: arch/x86/include/asm/xen/hypercall.h:433
Inline: True
Inline callers:
  - arch/x86/xen/pmu.c:xen_pmu_finish
  - arch/x86/xen/pmu.c:xen_pmu_init
  - arch/x86/xen/pmu.c:xen_pmu_irq_handler
  - arch/x86/xen/pmu.c:pmu_apic_update
```
```
In drivers/xen/sys-hypervisor.c (ffffffff816808c6)
Location: arch/x86/include/asm/xen/hypercall.h:433
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:pmu_features_show
  - drivers/xen/sys-hypervisor.c:pmu_features_store
  - drivers/xen/sys-hypervisor.c:pmu_mode_show
  - drivers/xen/sys-hypervisor.c:pmu_mode_store
```
</details>
</li>
</ul>

## Differences
