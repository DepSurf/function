# Function: <code>uv_blade_to_pnode</code>

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
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/platform/uv/tlb_uv.c (ffffffff828c9a43)
Location: arch/x86/include/asm/uv/uv_hub.h:747
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:enable_timeouts
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff810984f5)
Location: arch/x86/include/asm/uv/uv_hub.h:747
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
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
In arch/x86/platform/uv/tlb_uv.c (ffffffff82cebf5e)
Location: arch/x86/include/asm/uv/uv_hub.h:692
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:activation_descriptor_init
  - arch/x86/platform/uv/tlb_uv.c:enable_timeouts
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff8109dce5)
Location: arch/x86/include/asm/uv/uv_hub.h:692
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/platform/uv/uv_irq.c (ffffffff810998b5)
Location: arch/x86/include/asm/uv/uv_hub.h:673
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/platform/uv/uv_irq.c (ffffffff8109a0c5)
Location: arch/x86/include/asm/uv/uv_hub.h:673
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/platform/uv/uv_irq.c (ffffffff810aa0e5)
Location: arch/x86/include/asm/uv/uv_hub.h:673
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/platform/uv/uv_irq.c (ffffffff810bfb19)
Location: arch/x86/include/asm/uv/uv_hub.h:673
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/platform/uv/uv_irq.c (ffffffff810db9f9)
Location: arch/x86/include/asm/uv/uv_hub.h:673
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
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
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff836b75d2)
Location: arch/x86/include/asm/uv/uv_hub.h:681
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff810e6f98)
Location: arch/x86/include/asm/uv/uv_hub.h:681
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
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
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff838e7eec)
Location: arch/x86/include/asm/uv/uv_hub.h:681
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff810ef349)
Location: arch/x86/include/asm/uv/uv_hub.h:681
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
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
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/platform/uv/tlb_uv.c (ffffffff828caa80)
Location: arch/x86/include/asm/uv/uv_hub.h:747
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:enable_timeouts
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff810999c5)
Location: arch/x86/include/asm/uv/uv_hub.h:747
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
```
</details>
</li>
</ul>

## Differences
