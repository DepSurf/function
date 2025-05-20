# Function: <code>uv_cpu_to_blade_id</code>

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
In arch/x86/platform/uv/tlb_uv.c (ffffffff828c96f1)
Location: arch/x86/include/asm/uv/uv_hub.h:741
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff81099149)
Location: arch/x86/include/asm/uv/uv_hub.h:741
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_next_event
  - arch/x86/platform/uv/uv_time.c:uv_rtc_unset_timer
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
In arch/x86/platform/uv/tlb_uv.c (ffffffff82cebee6)
Location: arch/x86/include/asm/uv/uv_hub.h:686
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:activation_descriptor_init
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff8109e645)
Location: arch/x86/include/asm/uv/uv_hub.h:686
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_unset_timer
  - arch/x86/platform/uv/uv_time.c:uv_rtc_set_timer
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
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
In arch/x86/platform/uv/uv_time.c (ffffffff8109a1c5)
Location: arch/x86/include/asm/uv/uv_hub.h:667
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_unset_timer
  - arch/x86/platform/uv/uv_time.c:uv_rtc_set_timer
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
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
In arch/x86/platform/uv/uv_time.c (ffffffff8109aafc)
Location: arch/x86/include/asm/uv/uv_hub.h:667
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_next_event
  - arch/x86/platform/uv/uv_time.c:uv_rtc_unset_timer
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
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
In arch/x86/platform/uv/uv_time.c (ffffffff810aad24)
Location: arch/x86/include/asm/uv/uv_hub.h:667
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_next_event
  - arch/x86/platform/uv/uv_time.c:uv_rtc_unset_timer
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
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
In arch/x86/platform/uv/uv_time.c (ffffffff810c07a3)
Location: arch/x86/include/asm/uv/uv_hub.h:667
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_next_event
  - arch/x86/platform/uv/uv_time.c:uv_rtc_unset_timer
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
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
In arch/x86/platform/uv/uv_time.c (ffffffff810dc753)
Location: arch/x86/include/asm/uv/uv_hub.h:667
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_next_event
  - arch/x86/platform/uv/uv_time.c:uv_rtc_unset_timer
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
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
In arch/x86/platform/uv/uv_time.c (ffffffff810e7d20)
Location: arch/x86/include/asm/uv/uv_hub.h:675
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_next_event
  - arch/x86/platform/uv/uv_time.c:uv_rtc_unset_timer
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
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
In arch/x86/platform/uv/uv_time.c (ffffffff810f00b0)
Location: arch/x86/include/asm/uv/uv_hub.h:675
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_next_event
  - arch/x86/platform/uv/uv_time.c:uv_rtc_unset_timer
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
In arch/x86/platform/uv/tlb_uv.c (ffffffff828ca72e)
Location: arch/x86/include/asm/uv/uv_hub.h:741
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff8109a619)
Location: arch/x86/include/asm/uv/uv_hub.h:741
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_next_event
  - arch/x86/platform/uv/uv_time.c:uv_rtc_unset_timer
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
```
</details>
</li>
</ul>

## Differences
