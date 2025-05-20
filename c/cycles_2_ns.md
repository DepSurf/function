# Function: <code>cycles_2_ns</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff81037b34)
Location: arch/x86/kernel/tsc.c:205
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:set_cyc2ns_scale
  - arch/x86/kernel/tsc.c:native_sched_clock
  - arch/x86/kernel/tsc.c:native_sched_clock_from_tsc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff81037008)
Location: arch/x86/kernel/tsc.c:206
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:native_sched_clock_from_tsc
  - arch/x86/kernel/tsc.c:native_sched_clock
  - arch/x86/kernel/tsc.c:set_cyc2ns_scale
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff81036d48)
Location: arch/x86/kernel/tsc.c:207
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:native_sched_clock_from_tsc
  - arch/x86/kernel/tsc.c:native_sched_clock
  - arch/x86/kernel/tsc.c:set_cyc2ns_scale
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff81034e23)
Location: arch/x86/kernel/tsc.c:125
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:native_sched_clock_from_tsc
  - arch/x86/kernel/tsc.c:set_cyc2ns_scale
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff81037183)
Location: arch/x86/kernel/tsc.c:125
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:native_sched_clock_from_tsc
  - arch/x86/kernel/tsc.c:set_cyc2ns_scale
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
In arch/x86/kernel/tsc.c (ffffffff8103817f)
Location: arch/x86/kernel/tsc.c:126
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:native_sched_clock_from_tsc
  - arch/x86/kernel/tsc.c:set_cyc2ns_scale
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff82892dad)
Location: arch/x86/kernel/tsc.c:107
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_enable_sched_clock
  - arch/x86/kernel/tsc.c:native_sched_clock_from_tsc
  - arch/x86/kernel/tsc.c:set_cyc2ns_scale
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8103be50)
Location: arch/x86/kernel/tsc.c:108
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:native_sched_clock_from_tsc
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8103c610)
Location: arch/x86/kernel/tsc.c:108
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:native_sched_clock_from_tsc
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff81095adb)
Location: arch/x86/platform/uv/tlb_uv.c:453
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:ptc_seq_show
  - arch/x86/platform/uv/tlb_uv.c:ptc_seq_show
  - arch/x86/platform/uv/tlb_uv.c:uv2_3_wait_completion
  - arch/x86/platform/uv/tlb_uv.c:uv1_wait_completion
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8103f400)
Location: arch/x86/kernel/tsc.c:115
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:native_sched_clock_from_tsc
  - arch/x86/kernel/tsc.c:native_sched_clock
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff8109ae23)
Location: arch/x86/platform/uv/tlb_uv.c:453
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:ptc_seq_show
  - arch/x86/platform/uv/tlb_uv.c:ptc_seq_show
  - arch/x86/platform/uv/tlb_uv.c:uv2_3_wait_completion
  - arch/x86/platform/uv/tlb_uv.c:uv1_wait_completion
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
In arch/x86/kernel/tsc.c (ffffffff8103f4c0)
Location: arch/x86/kernel/tsc.c:115
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:native_sched_clock_from_tsc
  - arch/x86/kernel/tsc.c:native_sched_clock
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
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
In arch/x86/kernel/tsc.c (ffffffff81040e30)
Location: arch/x86/kernel/tsc.c:116
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:native_sched_clock_from_tsc
  - arch/x86/kernel/tsc.c:native_sched_clock
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
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
In arch/x86/kernel/tsc.c (ffffffff81046f51)
Location: arch/x86/kernel/tsc.c:116
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:native_sched_clock_from_tsc
  - arch/x86/kernel/tsc.c:native_sched_clock
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
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
In arch/x86/kernel/tsc.c (ffffffff8104fcf1)
Location: arch/x86/kernel/tsc.c:116
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:native_sched_clock_from_tsc
  - arch/x86/kernel/tsc.c:native_sched_clock
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
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
In arch/x86/kernel/tsc.c (ffffffff8105d071)
Location: arch/x86/kernel/tsc.c:116
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:native_sched_clock_from_tsc
  - arch/x86/kernel/tsc.c:native_sched_clock
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
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
In arch/x86/kernel/tsc.c (ffffffff8105e5e1)
Location: arch/x86/kernel/tsc.c:135
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:native_sched_clock_from_tsc
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
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
In arch/x86/kernel/tsc.c (ffffffff810656a1)
Location: arch/x86/kernel/tsc.c:135
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:native_sched_clock_from_tsc
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8103c770)
Location: arch/x86/kernel/tsc.c:108
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:native_sched_clock_from_tsc
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
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
In arch/x86/kernel/tsc.c (ffffffff8102be60)
Location: arch/x86/kernel/tsc.c:108
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:native_sched_clock_from_tsc
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8103c5d0)
Location: arch/x86/kernel/tsc.c:108
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:native_sched_clock_from_tsc
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8103d640)
Location: arch/x86/kernel/tsc.c:108
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:native_sched_clock_from_tsc
  - arch/x86/kernel/tsc.c:native_sched_clock
  - arch/x86/kernel/tsc.c:__set_cyc2ns_scale
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff8109706b)
Location: arch/x86/platform/uv/tlb_uv.c:453
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:ptc_seq_show
  - arch/x86/platform/uv/tlb_uv.c:ptc_seq_show
  - arch/x86/platform/uv/tlb_uv.c:uv2_3_wait_completion
  - arch/x86/platform/uv/tlb_uv.c:uv1_wait_completion
```
</details>
</li>
</ul>

## Differences
