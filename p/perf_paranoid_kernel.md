# Function: <code>perf_paranoid_kernel</code>

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
In arch/x86/events/intel/bts.c (0)
Location: include/linux/perf_event.h:1003
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/perf_event.h:1003
Inline: True
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
In arch/x86/events/intel/bts.c (0)
Location: include/linux/perf_event.h:1163
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/perf_event.h:1163
Inline: True
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
In arch/x86/events/intel/bts.c (0)
Location: include/linux/perf_event.h:1186
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/perf_event.h:1186
Inline: True
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
In arch/x86/events/intel/bts.c (0)
Location: include/linux/perf_event.h:1182
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/perf_event.h:1182
Inline: True
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
In arch/x86/events/intel/bts.c (0)
Location: include/linux/perf_event.h:1169
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/perf_event.h:1169
Inline: True
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
In arch/x86/events/intel/bts.c (ffffffff8100db88)
Location: include/linux/perf_event.h:1197
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_event_init
```
```
In kernel/events/core.c (ffffffff811ddf63)
Location: include/linux/perf_event.h:1197
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_copy_attr
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
In arch/x86/events/intel/bts.c (ffffffff8100e058)
Location: include/linux/perf_event.h:1202
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_event_init
```
```
In kernel/events/core.c (ffffffff811ee373)
Location: include/linux/perf_event.h:1202
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_copy_attr
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
In arch/x86/events/intel/bts.c (ffffffff8100e918)
Location: include/linux/perf_event.h:1245
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_event_init
```
```
In kernel/events/core.c (ffffffff81205db3)
Location: include/linux/perf_event.h:1245
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_copy_attr
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
In arch/x86/events/intel/bts.c (ffffffff8100ede8)
Location: include/linux/perf_event.h:1259
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_event_init
```
```
In kernel/events/core.c (ffffffff81213143)
Location: include/linux/perf_event.h:1259
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_copy_attr
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
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff80001029d4fc)
Location: include/linux/perf_event.h:1259
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_copy_attr
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
In kernel/events/core.c (c04ccc7c)
Location: include/linux/perf_event.h:1259
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_copy_attr
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
In arch/powerpc/perf/core-book3s.c (c000000000128e78)
Location: include/linux/perf_event.h:1259
Inline: True
Inline callers:
  - arch/powerpc/perf/core-book3s.c:record_and_restart
  - arch/powerpc/perf/core-book3s.c:record_and_restart
```
```
In kernel/events/core.c (c00000000034dfcc)
Location: include/linux/perf_event.h:1259
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_copy_attr
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
In kernel/events/core.c (ffffffe0001cb698)
Location: include/linux/perf_event.h:1259
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_copy_attr
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
In arch/x86/events/intel/bts.c (ffffffff8100ede8)
Location: include/linux/perf_event.h:1259
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_event_init
```
```
In kernel/events/core.c (ffffffff8120b793)
Location: include/linux/perf_event.h:1259
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_copy_attr
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
In arch/x86/events/intel/bts.c (ffffffff8100db48)
Location: include/linux/perf_event.h:1259
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_event_init
```
```
In kernel/events/core.c (ffffffff811fe563)
Location: include/linux/perf_event.h:1259
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_copy_attr
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
In arch/x86/events/intel/bts.c (ffffffff8100eda8)
Location: include/linux/perf_event.h:1259
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_event_init
```
```
In kernel/events/core.c (ffffffff81209533)
Location: include/linux/perf_event.h:1259
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_copy_attr
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
In arch/x86/events/intel/bts.c (ffffffff8100ef78)
Location: include/linux/perf_event.h:1259
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_event_init
```
```
In kernel/events/core.c (ffffffff812182d3)
Location: include/linux/perf_event.h:1259
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_copy_attr
```
</details>
</li>
</ul>

## Differences
