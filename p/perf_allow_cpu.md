# Function: <code>perf_allow_cpu</code>

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
In arch/x86/events/intel/core.c (ffffffff8100db43)
Location: include/linux/perf_event.h:1317
Inline: True
```
```
In arch/x86/events/intel/p4.c (ffffffff81015437)
Location: include/linux/perf_event.h:1317
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_hw_config
```
```
In kernel/events/core.c (ffffffff8123bdd0)
Location: include/linux/perf_event.h:1317
Inline: True
Inline callers:
  - kernel/events/core.c:find_get_context
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
In arch/x86/events/intel/core.c (ffffffff8100cc8d)
Location: include/linux/perf_event.h:1333
Inline: True
```
```
In arch/x86/events/intel/p4.c (ffffffff810158d7)
Location: include/linux/perf_event.h:1333
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_hw_config
```
```
In kernel/events/core.c (ffffffff81244f4b)
Location: include/linux/perf_event.h:1333
Inline: True
Inline callers:
  - kernel/events/core.c:find_get_context
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
In arch/x86/events/intel/core.c (ffffffff8100d744)
Location: include/linux/perf_event.h:1334
Inline: True
```
```
In arch/x86/events/intel/p4.c (ffffffff81016bf6)
Location: include/linux/perf_event.h:1334
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_hw_config
```
```
In kernel/events/core.c (ffffffff8124a187)
Location: include/linux/perf_event.h:1334
Inline: True
Inline callers:
  - kernel/events/core.c:find_get_context
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
In arch/x86/events/intel/core.c (ffffffff8100dd04)
Location: include/linux/perf_event.h:1339
Inline: True
```
```
In arch/x86/events/intel/p4.c (ffffffff81018788)
Location: include/linux/perf_event.h:1339
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_hw_config
```
```
In kernel/events/core.c (ffffffff812830db)
Location: include/linux/perf_event.h:1339
Inline: True
Inline callers:
  - kernel/events/core.c:find_get_context
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
In arch/x86/events/intel/core.c (ffffffff8100f124)
Location: include/linux/perf_event.h:1381
Inline: True
```
```
In arch/x86/events/intel/p4.c (ffffffff8101a946)
Location: include/linux/perf_event.h:1381
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_hw_config
```
```
In kernel/events/core.c (ffffffff812d77d8)
Location: include/linux/perf_event.h:1381
Inline: True
Inline callers:
  - kernel/events/core.c:find_get_context
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
In arch/x86/events/intel/core.c (ffffffff81012ad3)
Location: include/linux/perf_event.h:1480
Inline: True
```
```
In arch/x86/events/intel/p4.c (ffffffff8101eab6)
Location: include/linux/perf_event.h:1480
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_hw_config
```
```
In kernel/events/core.c (ffffffff81340170)
Location: include/linux/perf_event.h:1480
Inline: True
Inline callers:
  - kernel/events/core.c:find_get_context
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
In arch/x86/events/intel/core.c (ffffffff8101204b)
Location: include/linux/perf_event.h:1593
Inline: True
```
```
In arch/x86/events/intel/p4.c (ffffffff8101e7a6)
Location: include/linux/perf_event.h:1593
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_hw_config
```
```
In kernel/events/core.c (ffffffff81371112)
Location: include/linux/perf_event.h:1593
Inline: True
Inline callers:
  - kernel/events/core.c:find_get_context
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
In arch/x86/events/intel/core.c (ffffffff810178e8)
Location: include/linux/perf_event.h:1635
Inline: True
```
```
In arch/x86/events/intel/p4.c (ffffffff810245e6)
Location: include/linux/perf_event.h:1635
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_hw_config
```
```
In kernel/events/core.c (ffffffff8139a412)
Location: include/linux/perf_event.h:1635
Inline: True
Inline callers:
  - kernel/events/core.c:find_get_context
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
