# Function: <code>uv_blade_to_node</code>

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
In arch/x86/platform/uv/tlb_uv.c (0)
Location: arch/x86/include/asm/uv/uv_hub.h:719
Inline: True
```
```
In arch/x86/platform/uv/uv_irq.c (0)
Location: arch/x86/include/asm/uv/uv_hub.h:719
Inline: True
```
```
In arch/x86/platform/uv/uv_time.c (0)
Location: arch/x86/include/asm/uv/uv_hub.h:719
Inline: True
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
In arch/x86/platform/uv/tlb_uv.c (0)
Location: arch/x86/include/asm/uv/uv_hub.h:664
Inline: True
```
```
In arch/x86/platform/uv/uv_irq.c (0)
Location: arch/x86/include/asm/uv/uv_hub.h:664
Inline: True
```
```
In arch/x86/platform/uv/uv_time.c (0)
Location: arch/x86/include/asm/uv/uv_hub.h:664
Inline: True
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
In arch/x86/platform/uv/uv_irq.c (0)
Location: arch/x86/include/asm/uv/uv_hub.h:645
Inline: True
```
```
In arch/x86/platform/uv/uv_time.c (0)
Location: arch/x86/include/asm/uv/uv_hub.h:645
Inline: True
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
In arch/x86/platform/uv/uv_irq.c (0)
Location: arch/x86/include/asm/uv/uv_hub.h:645
Inline: True
```
```
In arch/x86/platform/uv/uv_time.c (0)
Location: arch/x86/include/asm/uv/uv_hub.h:645
Inline: True
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
In arch/x86/platform/uv/uv_irq.c (0)
Location: arch/x86/include/asm/uv/uv_hub.h:645
Inline: True
```
```
In arch/x86/platform/uv/uv_time.c (0)
Location: arch/x86/include/asm/uv/uv_hub.h:645
Inline: True
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
In arch/x86/platform/uv/uv_irq.c (0)
Location: arch/x86/include/asm/uv/uv_hub.h:645
Inline: True
```
```
In arch/x86/platform/uv/uv_time.c (0)
Location: arch/x86/include/asm/uv/uv_hub.h:645
Inline: True
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
In arch/x86/platform/uv/uv_irq.c (0)
Location: arch/x86/include/asm/uv/uv_hub.h:645
Inline: True
```
```
In arch/x86/platform/uv/uv_time.c (0)
Location: arch/x86/include/asm/uv/uv_hub.h:645
Inline: True
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
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff836b7633)
Location: arch/x86/include/asm/uv/uv_hub.h:651
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff810e7133)
Location: arch/x86/include/asm/uv/uv_hub.h:651
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff836c861e)
Location: arch/x86/include/asm/uv/uv_hub.h:651
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
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
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff838e7f4d)
Location: arch/x86/include/asm/uv/uv_hub.h:651
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff810ef4e3)
Location: arch/x86/include/asm/uv/uv_hub.h:651
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff838f921e)
Location: arch/x86/include/asm/uv/uv_hub.h:651
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
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
In arch/x86/platform/uv/tlb_uv.c (0)
Location: arch/x86/include/asm/uv/uv_hub.h:719
Inline: True
```
```
In arch/x86/platform/uv/uv_irq.c (0)
Location: arch/x86/include/asm/uv/uv_hub.h:719
Inline: True
```
```
In arch/x86/platform/uv/uv_time.c (0)
Location: arch/x86/include/asm/uv/uv_hub.h:719
Inline: True
```
</details>
</li>
</ul>

## Differences
