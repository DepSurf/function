# Function: <code>perf_guest_state</code>

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
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81009845)
Location: include/linux/perf_event.h:1270
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_misc_flags
  - arch/x86/events/core.c:perf_instruction_pointer
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_kernel
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
In arch/x86/events/core.c (ffffffff8100ad05)
Location: include/linux/perf_event.h:1369
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_misc_flags
  - arch/x86/events/core.c:perf_instruction_pointer
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_kernel
```
```
In arch/x86/events/intel/core.c (ffffffff8101552b)
Location: include/linux/perf_event.h:1369
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
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
In arch/x86/events/core.c (ffffffff8100a4f5)
Location: include/linux/perf_event.h:1483
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_misc_flags
  - arch/x86/events/core.c:perf_instruction_pointer
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_kernel
```
```
In arch/x86/events/intel/core.c (ffffffff81014de1)
Location: include/linux/perf_event.h:1483
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
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
In arch/x86/events/core.c (ffffffff8100fc15)
Location: include/linux/perf_event.h:1525
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_misc_flags
  - arch/x86/events/core.c:perf_instruction_pointer
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_kernel
```
```
In arch/x86/events/intel/core.c (ffffffff81019d9c)
Location: include/linux/perf_event.h:1525
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:handle_pmi_common
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
