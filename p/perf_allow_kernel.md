# Function: <code>perf_allow_kernel</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/bts.c (ffffffff810101fb)
Location: include/linux/perf_event.h:1309
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_event_init
```
```
In kernel/events/core.c (ffffffff8123f2a8)
Location: include/linux/perf_event.h:1309
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
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/bts.c (ffffffff8100f75b)
Location: include/linux/perf_event.h:1325
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_event_init
```
```
In kernel/events/core.c (ffffffff812496a5)
Location: include/linux/perf_event.h:1325
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
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/bts.c (ffffffff810107ab)
Location: include/linux/perf_event.h:1326
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_event_init
```
```
In kernel/events/core.c (ffffffff8124daf2)
Location: include/linux/perf_event.h:1326
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
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/bts.c (ffffffff810111db)
Location: include/linux/perf_event.h:1331
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_event_init
```
```
In kernel/events/core.c (ffffffff81288841)
Location: include/linux/perf_event.h:1331
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
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/bts.c (ffffffff81012935)
Location: include/linux/perf_event.h:1373
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_event_init
```
```
In kernel/events/core.c (ffffffff812dd9e3)
Location: include/linux/perf_event.h:1373
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
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/bts.c (ffffffff81016925)
Location: include/linux/perf_event.h:1472
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_event_init
```
```
In kernel/events/core.c (ffffffff81345eab)
Location: include/linux/perf_event.h:1472
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
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/bts.c (ffffffff810162c5)
Location: include/linux/perf_event.h:1585
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_event_init
```
```
In kernel/events/core.c (ffffffff81376f6e)
Location: include/linux/perf_event.h:1585
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
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/bts.c (ffffffff8101be05)
Location: include/linux/perf_event.h:1627
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_event_init
```
```
In kernel/events/core.c (ffffffff813a01f0)
Location: include/linux/perf_event.h:1627
Inline: True
Inline callers:
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_copy_attr
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
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
