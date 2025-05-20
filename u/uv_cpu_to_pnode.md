# Function: <code>uv_cpu_to_pnode</code>

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
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8106d48f)
Location: arch/x86/include/asm/uv/uv_hub.h:771
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_heartbeat_disable
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_heartbeat_enable
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff828c9774)
Location: arch/x86/include/asm/uv/uv_hub.h:771
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:ptc_seq_show
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff81099136)
Location: arch/x86/include/asm/uv/uv_hub.h:771
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_next_event
  - arch/x86/platform/uv/uv_time.c:uv_rtc_unset_timer
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
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
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff810744df)
Location: arch/x86/include/asm/uv/uv_hub.h:716
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_heartbeat_disable
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_heartbeat_enable
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff8109d3cd)
Location: arch/x86/include/asm/uv/uv_hub.h:716
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:pq_init
  - arch/x86/platform/uv/tlb_uv.c:ptc_seq_show
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff8109e615)
Location: arch/x86/include/asm/uv/uv_hub.h:716
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_unset_timer
  - arch/x86/platform/uv/uv_time.c:uv_rtc_set_timer
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
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
In arch/x86/platform/uv/uv_time.c (ffffffff8109a195)
Location: arch/x86/include/asm/uv/uv_hub.h:697
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_unset_timer
  - arch/x86/platform/uv/uv_time.c:uv_rtc_set_timer
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
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
In arch/x86/platform/uv/uv_time.c (ffffffff8109aae9)
Location: arch/x86/include/asm/uv/uv_hub.h:697
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_next_event
  - arch/x86/platform/uv/uv_time.c:uv_rtc_unset_timer
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
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
In arch/x86/platform/uv/uv_time.c (ffffffff810aacfb)
Location: arch/x86/include/asm/uv/uv_hub.h:697
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_next_event
  - arch/x86/platform/uv/uv_time.c:uv_rtc_unset_timer
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
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
In arch/x86/platform/uv/uv_time.c (ffffffff810c0778)
Location: arch/x86/include/asm/uv/uv_hub.h:697
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_next_event
  - arch/x86/platform/uv/uv_time.c:uv_rtc_unset_timer
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
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
In arch/x86/platform/uv/uv_time.c (ffffffff810dc728)
Location: arch/x86/include/asm/uv/uv_hub.h:697
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_next_event
  - arch/x86/platform/uv/uv_time.c:uv_rtc_unset_timer
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/platform/uv/uv_time.c (ffffffff810e7cfb)
Location: arch/x86/include/asm/uv/uv_hub.h:707
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_next_event
  - arch/x86/platform/uv/uv_time.c:uv_rtc_unset_timer
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/platform/uv/uv_time.c (ffffffff810f008b)
Location: arch/x86/include/asm/uv/uv_hub.h:707
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_next_event
  - arch/x86/platform/uv/uv_time.c:uv_rtc_unset_timer
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
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
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8106eb5f)
Location: arch/x86/include/asm/uv/uv_hub.h:771
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_heartbeat_disable
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_heartbeat_enable
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff828ca7b1)
Location: arch/x86/include/asm/uv/uv_hub.h:771
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:ptc_seq_show
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff8109a606)
Location: arch/x86/include/asm/uv/uv_hub.h:771
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_next_event
  - arch/x86/platform/uv/uv_time.c:uv_rtc_unset_timer
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
```
</details>
</li>
</ul>

## Differences
