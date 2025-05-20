# Function: <code>uv_blade_nr_possible_cpus</code>

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
In arch/x86/platform/uv/tlb_uv.c (ffffffff828c929b)
Location: arch/x86/include/asm/uv/uv_hub.h:759
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:enable_timeouts
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff828c9dce)
Location: arch/x86/include/asm/uv/uv_hub.h:759
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
In arch/x86/platform/uv/tlb_uv.c (ffffffff82cebd8f)
Location: arch/x86/include/asm/uv/uv_hub.h:704
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:enable_timeouts
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff82cec71d)
Location: arch/x86/include/asm/uv/uv_hub.h:704
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
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
In arch/x86/platform/uv/uv_time.c (ffffffff82fd8d73)
Location: arch/x86/include/asm/uv/uv_hub.h:685
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
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
In arch/x86/platform/uv/uv_time.c (ffffffff831e35f0)
Location: arch/x86/include/asm/uv/uv_hub.h:685
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
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
In arch/x86/platform/uv/uv_time.c (ffffffff832c7027)
Location: arch/x86/include/asm/uv/uv_hub.h:685
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
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
In arch/x86/platform/uv/uv_time.c (ffffffff83479d65)
Location: arch/x86/include/asm/uv/uv_hub.h:685
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
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
In arch/x86/platform/uv/uv_time.c (ffffffff83ea431e)
Location: arch/x86/include/asm/uv/uv_hub.h:685
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
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
In arch/x86/platform/uv/uv_time.c (ffffffff836c861e)
Location: arch/x86/include/asm/uv/uv_hub.h:695
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
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
In arch/x86/platform/uv/uv_time.c (ffffffff838f921e)
Location: arch/x86/include/asm/uv/uv_hub.h:695
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
In arch/x86/platform/uv/tlb_uv.c (ffffffff828ca2d8)
Location: arch/x86/include/asm/uv/uv_hub.h:759
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:enable_timeouts
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff828cae0b)
Location: arch/x86/include/asm/uv/uv_hub.h:759
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
```
</details>
</li>
</ul>

## Differences
