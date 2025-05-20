# Function: <code>uv_hub_info_list</code>

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
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff828bd255)
Location: arch/x86/include/asm/uv/uv_hub.h:205
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff828c929b)
Location: arch/x86/include/asm/uv/uv_hub.h:205
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:enable_timeouts
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff8109864a)
Location: arch/x86/include/asm/uv/uv_hub.h:205
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff828c9dce)
Location: arch/x86/include/asm/uv/uv_hub.h:205
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
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
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff82ce17bb)
Location: arch/x86/include/asm/uv/uv_hub.h:206
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff82cebd8f)
Location: arch/x86/include/asm/uv/uv_hub.h:206
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:activation_descriptor_init
  - arch/x86/platform/uv/tlb_uv.c:enable_timeouts
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff8109de3a)
Location: arch/x86/include/asm/uv/uv_hub.h:206
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff82cec71d)
Location: arch/x86/include/asm/uv/uv_hub.h:206
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
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
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff82fce562)
Location: arch/x86/include/asm/uv/uv_hub.h:195
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff81099a0a)
Location: arch/x86/include/asm/uv/uv_hub.h:195
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff82fd8d73)
Location: arch/x86/include/asm/uv/uv_hub.h:195
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
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
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff831d8ffc)
Location: arch/x86/include/asm/uv/uv_hub.h:195
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff8109a217)
Location: arch/x86/include/asm/uv/uv_hub.h:195
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff831e35f0)
Location: arch/x86/include/asm/uv/uv_hub.h:195
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
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
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff832bc4c5)
Location: arch/x86/include/asm/uv/uv_hub.h:195
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff810aa241)
Location: arch/x86/include/asm/uv/uv_hub.h:195
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff832c7027)
Location: arch/x86/include/asm/uv/uv_hub.h:195
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
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
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8346dde8)
Location: arch/x86/include/asm/uv/uv_hub.h:195
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff810bfc8d)
Location: arch/x86/include/asm/uv/uv_hub.h:195
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff83479d65)
Location: arch/x86/include/asm/uv/uv_hub.h:195
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
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
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff83e93b18)
Location: arch/x86/include/asm/uv/uv_hub.h:195
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff810dbb7d)
Location: arch/x86/include/asm/uv/uv_hub.h:195
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff83ea431e)
Location: arch/x86/include/asm/uv/uv_hub.h:195
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
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
In arch/x86/platform/uv/uv_irq.c (ffffffff810e714c)
Location: arch/x86/include/asm/uv/uv_hub.h:196
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff836c8664)
Location: arch/x86/include/asm/uv/uv_hub.h:196
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
In arch/x86/platform/uv/uv_irq.c (ffffffff810ef4fc)
Location: arch/x86/include/asm/uv/uv_hub.h:196
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff838f9264)
Location: arch/x86/include/asm/uv/uv_hub.h:196
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
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff828be282)
Location: arch/x86/include/asm/uv/uv_hub.h:205
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff828ca2d8)
Location: arch/x86/include/asm/uv/uv_hub.h:205
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:enable_timeouts
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff81099b1a)
Location: arch/x86/include/asm/uv/uv_hub.h:205
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff828cae0b)
Location: arch/x86/include/asm/uv/uv_hub.h:205
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
```
</details>
</li>
</ul>

## Differences
