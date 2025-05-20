# Function: <code>perf_event_addr_filters</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/pt.c (ffffffff81012de6)
Location: include/linux/perf_event.h:1210
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_addr_filters_sync
```
```
In kernel/events/core.c (ffffffff8118ac21)
Location: include/linux/perf_event.h:1210
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/core.c:__perf_addr_filters_adjust
  - kernel/events/core.c:perf_event_addr_filters_exec
  - kernel/events/core.c:perf_event_addr_filters_sync
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
In arch/x86/events/intel/pt.c (ffffffff81012ed6)
Location: include/linux/perf_event.h:1233
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_addr_filters_sync
```
```
In kernel/events/core.c (ffffffff81199bd1)
Location: include/linux/perf_event.h:1233
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/core.c:__perf_addr_filters_adjust
  - kernel/events/core.c:perf_event_addr_filters_exec
  - kernel/events/core.c:perf_event_addr_filters_sync
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
In arch/x86/events/intel/pt.c (ffffffff81011486)
Location: include/linux/perf_event.h:1229
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_addr_filters_sync
```
```
In kernel/events/core.c (ffffffff811a2e11)
Location: include/linux/perf_event.h:1229
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/core.c:__perf_addr_filters_adjust
  - kernel/events/core.c:perf_event_addr_filters_exec
  - kernel/events/core.c:perf_event_addr_filters_sync
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
In arch/x86/events/intel/pt.c (ffffffff81011bc6)
Location: include/linux/perf_event.h:1219
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_addr_filters_sync
```
```
In kernel/events/core.c (ffffffff811b6ff1)
Location: include/linux/perf_event.h:1219
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/core.c:__perf_addr_filters_adjust
  - kernel/events/core.c:perf_event_addr_filters_exec
  - kernel/events/core.c:perf_event_addr_filters_sync
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
In arch/x86/events/intel/pt.c (ffffffff81012595)
Location: include/linux/perf_event.h:1247
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_addr_filters_sync
```
```
In kernel/events/core.c (ffffffff811d68c0)
Location: include/linux/perf_event.h:1247
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/core.c:__perf_addr_filters_adjust
  - kernel/events/core.c:perf_event_addr_filters_exec
  - kernel/events/core.c:perf_event_addr_filters_sync
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
In arch/x86/events/intel/pt.c (ffffffff81012c95)
Location: include/linux/perf_event.h:1252
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_addr_filters_sync
```
```
In kernel/events/core.c (ffffffff811e6b30)
Location: include/linux/perf_event.h:1252
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/core.c:__perf_addr_filters_adjust
  - kernel/events/core.c:perf_event_addr_filters_exec
  - kernel/events/core.c:perf_event_addr_filters_sync
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
In arch/x86/events/intel/pt.c (ffffffff81014035)
Location: include/linux/perf_event.h:1295
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_addr_filters_sync
```
```
In kernel/events/core.c (ffffffff811fbf70)
Location: include/linux/perf_event.h:1295
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/core.c:__perf_addr_filters_adjust
  - kernel/events/core.c:perf_event_addr_filters_exec
  - kernel/events/core.c:perf_event_addr_filters_sync
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
In arch/x86/events/intel/pt.c (ffffffff81014735)
Location: include/linux/perf_event.h:1309
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_addr_filters_sync
```
```
In kernel/events/core.c (ffffffff81209040)
Location: include/linux/perf_event.h:1309
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/core.c:__perf_addr_filters_adjust
  - kernel/events/core.c:perf_event_addr_filters_exec
  - kernel/events/core.c:perf_event_addr_filters_sync
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
In arch/x86/events/intel/pt.c (ffffffff81015cf5)
Location: include/linux/perf_event.h:1378
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_addr_filters_sync
```
```
In kernel/events/core.c (ffffffff81232610)
Location: include/linux/perf_event.h:1378
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/core.c:__perf_addr_filters_adjust
  - kernel/events/core.c:perf_event_addr_filters_exec
  - kernel/events/core.c:perf_event_addr_filters_sync
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
In arch/x86/events/intel/pt.c (ffffffff81016195)
Location: include/linux/perf_event.h:1394
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_addr_filters_sync
```
```
In kernel/events/core.c (ffffffff8123c200)
Location: include/linux/perf_event.h:1394
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/core.c:__perf_addr_filters_adjust
  - kernel/events/core.c:perf_event_addr_filters_exec
  - kernel/events/core.c:perf_event_addr_filters_sync
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
In arch/x86/events/intel/pt.c (ffffffff81017485)
Location: include/linux/perf_event.h:1395
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_addr_filters_sync
```
```
In kernel/events/core.c (ffffffff81240850)
Location: include/linux/perf_event.h:1395
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/core.c:__perf_addr_filters_adjust
  - kernel/events/core.c:perf_event_addr_filters_exec
  - kernel/events/core.c:perf_event_addr_filters_sync
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
In arch/x86/events/intel/pt.c (ffffffff810191f5)
Location: include/linux/perf_event.h:1400
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_addr_filters_sync
```
```
In kernel/events/core.c (ffffffff8127b2d0)
Location: include/linux/perf_event.h:1400
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/core.c:__perf_addr_filters_adjust
  - kernel/events/core.c:perf_event_addr_filters_exec
  - kernel/events/core.c:perf_event_addr_filters_sync
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
In arch/x86/events/intel/pt.c (ffffffff8101b4c5)
Location: include/linux/perf_event.h:1442
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_addr_filters_sync
```
```
In kernel/events/core.c (ffffffff812cf0b5)
Location: include/linux/perf_event.h:1442
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/core.c:__perf_addr_filters_adjust
  - kernel/events/core.c:perf_event_addr_filters_exec
  - kernel/events/core.c:perf_event_addr_filters_sync
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
In arch/x86/events/intel/pt.c (ffffffff8101f725)
Location: include/linux/perf_event.h:1541
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_addr_filters_sync
```
```
In kernel/events/core.c (ffffffff813379d5)
Location: include/linux/perf_event.h:1541
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/core.c:__perf_addr_filters_adjust
  - kernel/events/core.c:perf_event_addr_filters_exec
  - kernel/events/core.c:perf_event_addr_filters_sync
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
In arch/x86/events/intel/pt.c (ffffffff8101f435)
Location: include/linux/perf_event.h:1654
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_addr_filters_sync
```
```
In kernel/events/core.c (ffffffff813689f5)
Location: include/linux/perf_event.h:1654
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/core.c:__perf_addr_filters_adjust
  - kernel/events/core.c:perf_event_addr_filters_exec
  - kernel/events/core.c:perf_event_addr_filters_sync
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
In arch/x86/events/intel/pt.c (ffffffff810254f5)
Location: include/linux/perf_event.h:1696
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_addr_filters_sync
```
```
In kernel/events/core.c (ffffffff81391825)
Location: include/linux/perf_event.h:1696
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/core.c:__perf_addr_filters_adjust
  - kernel/events/core.c:perf_event_addr_filters_exec
  - kernel/events/core.c:perf_event_addr_filters_sync
```
</details>
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
In kernel/events/core.c (ffff800010298dc8)
Location: include/linux/perf_event.h:1309
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/core.c:perf_event_mmap
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_event_addr_filters_sync
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
In kernel/events/core.c (c04c2da8)
Location: include/linux/perf_event.h:1309
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/core.c:perf_event_mmap
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_event_addr_filters_sync
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
In kernel/events/core.c (c000000000340994)
Location: include/linux/perf_event.h:1309
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/core.c:perf_event_mmap
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_event_addr_filters_sync
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
In kernel/events/core.c (ffffffe0001c49c0)
Location: include/linux/perf_event.h:1309
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/core.c:perf_event_mmap
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_event_addr_filters_sync
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
In arch/x86/events/intel/pt.c (ffffffff81014735)
Location: include/linux/perf_event.h:1309
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_addr_filters_sync
```
```
In kernel/events/core.c (ffffffff81201660)
Location: include/linux/perf_event.h:1309
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/core.c:__perf_addr_filters_adjust
  - kernel/events/core.c:perf_event_addr_filters_exec
  - kernel/events/core.c:perf_event_addr_filters_sync
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
In arch/x86/events/intel/pt.c (ffffffff81013a15)
Location: include/linux/perf_event.h:1309
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_addr_filters_sync
```
```
In kernel/events/core.c (ffffffff811f43b0)
Location: include/linux/perf_event.h:1309
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/core.c:__perf_addr_filters_adjust
  - kernel/events/core.c:perf_event_addr_filters_exec
  - kernel/events/core.c:perf_event_addr_filters_sync
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
In arch/x86/events/intel/pt.c (ffffffff810146f5)
Location: include/linux/perf_event.h:1309
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_addr_filters_sync
```
```
In kernel/events/core.c (ffffffff811ff430)
Location: include/linux/perf_event.h:1309
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/core.c:__perf_addr_filters_adjust
  - kernel/events/core.c:perf_event_addr_filters_exec
  - kernel/events/core.c:perf_event_addr_filters_sync
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
In arch/x86/events/intel/pt.c (ffffffff81014935)
Location: include/linux/perf_event.h:1309
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_addr_filters_sync
```
```
In kernel/events/core.c (ffffffff8120e4c0)
Location: include/linux/perf_event.h:1309
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_addr_filters_apply
  - kernel/events/core.c:__perf_addr_filters_adjust
  - kernel/events/core.c:perf_event_addr_filters_exec
  - kernel/events/core.c:perf_event_addr_filters_sync
```
</details>
</li>
</ul>

## Differences
