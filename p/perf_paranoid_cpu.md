# Function: <code>perf_paranoid_cpu</code>

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
In arch/x86/events/intel/core.c (0)
Location: include/linux/perf_event.h:998
Inline: True
```
```
In arch/x86/events/intel/p4.c (0)
Location: include/linux/perf_event.h:998
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/perf_event.h:998
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
In arch/x86/events/intel/core.c (0)
Location: include/linux/perf_event.h:1158
Inline: True
```
```
In arch/x86/events/intel/p4.c (0)
Location: include/linux/perf_event.h:1158
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/perf_event.h:1158
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
In arch/x86/events/intel/core.c (0)
Location: include/linux/perf_event.h:1181
Inline: True
```
```
In arch/x86/events/intel/p4.c (0)
Location: include/linux/perf_event.h:1181
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/perf_event.h:1181
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
In arch/x86/events/intel/core.c (0)
Location: include/linux/perf_event.h:1177
Inline: True
```
```
In arch/x86/events/intel/p4.c (0)
Location: include/linux/perf_event.h:1177
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/perf_event.h:1177
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
In arch/x86/events/intel/core.c (0)
Location: include/linux/perf_event.h:1164
Inline: True
```
```
In arch/x86/events/intel/p4.c (0)
Location: include/linux/perf_event.h:1164
Inline: True
```
```
In kernel/events/core.c (0)
Location: include/linux/perf_event.h:1164
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
In arch/x86/events/intel/core.c (ffffffff8100c320)
Location: include/linux/perf_event.h:1192
Inline: True
```
```
In arch/x86/events/intel/p4.c (ffffffff81011b1e)
Location: include/linux/perf_event.h:1192
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_hw_config
```
```
In kernel/events/core.c (ffffffff811db893)
Location: include/linux/perf_event.h:1192
Inline: True
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
In arch/x86/events/intel/core.c (ffffffff8100c48d)
Location: include/linux/perf_event.h:1197
Inline: True
```
```
In arch/x86/events/intel/p4.c (ffffffff8101219e)
Location: include/linux/perf_event.h:1197
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_hw_config
```
```
In kernel/events/core.c (ffffffff811ebbd7)
Location: include/linux/perf_event.h:1197
Inline: True
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
In arch/x86/events/intel/core.c (ffffffff8100cc0d)
Location: include/linux/perf_event.h:1240
Inline: True
```
```
In arch/x86/events/intel/p4.c (ffffffff81013519)
Location: include/linux/perf_event.h:1240
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_hw_config
```
```
In kernel/events/core.c (ffffffff81203584)
Location: include/linux/perf_event.h:1240
Inline: True
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
In arch/x86/events/intel/core.c (ffffffff8100d046)
Location: include/linux/perf_event.h:1254
Inline: True
```
```
In arch/x86/events/intel/p4.c (ffffffff81013cc9)
Location: include/linux/perf_event.h:1254
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_hw_config
```
```
In kernel/events/core.c (ffffffff812101a2)
Location: include/linux/perf_event.h:1254
Inline: True
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
In kernel/events/core.c (ffff8000102965fc)
Location: include/linux/perf_event.h:1254
Inline: True
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
In kernel/events/core.c (c04c8084)
Location: include/linux/perf_event.h:1254
Inline: True
Inline callers:
  - kernel/events/core.c:find_get_context
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c000000000347eb8)
Location: include/linux/perf_event.h:1254
Inline: True
Inline callers:
  - kernel/events/core.c:find_get_context
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
In kernel/events/core.c (ffffffe0001c93fc)
Location: include/linux/perf_event.h:1254
Inline: True
Inline callers:
  - kernel/events/core.c:find_get_context
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
In arch/x86/events/intel/core.c (ffffffff8100d046)
Location: include/linux/perf_event.h:1254
Inline: True
```
```
In arch/x86/events/intel/p4.c (ffffffff81013cc9)
Location: include/linux/perf_event.h:1254
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_hw_config
```
```
In kernel/events/core.c (ffffffff812087c4)
Location: include/linux/perf_event.h:1254
Inline: True
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
In arch/x86/events/intel/core.c (ffffffff8100b846)
Location: include/linux/perf_event.h:1254
Inline: True
```
```
In arch/x86/events/intel/p4.c (ffffffff81012e59)
Location: include/linux/perf_event.h:1254
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_hw_config
```
```
In kernel/events/core.c (ffffffff811fb554)
Location: include/linux/perf_event.h:1254
Inline: True
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
In arch/x86/events/intel/core.c (ffffffff8100d006)
Location: include/linux/perf_event.h:1254
Inline: True
```
```
In arch/x86/events/intel/p4.c (ffffffff81013c89)
Location: include/linux/perf_event.h:1254
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_hw_config
```
```
In kernel/events/core.c (ffffffff81206592)
Location: include/linux/perf_event.h:1254
Inline: True
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
In arch/x86/events/intel/core.c (ffffffff8100d236)
Location: include/linux/perf_event.h:1254
Inline: True
```
```
In arch/x86/events/intel/p4.c (ffffffff81013ebd)
Location: include/linux/perf_event.h:1254
Inline: True
Inline callers:
  - arch/x86/events/intel/p4.c:p4_hw_config
```
```
In kernel/events/core.c (ffffffff812152d4)
Location: include/linux/perf_event.h:1254
Inline: True
```
</details>
</li>
</ul>

## Differences
