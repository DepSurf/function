# Function: <code>icl_get_event_constraints</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct event_constraint *icl_get_event_constraints(struct cpu_hw_events *cpuc, int idx, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100d110)
Location: arch/x86/events/intel/core.c:3477
Inline: False
```
**Symbols:**

```
ffffffff8100d110-ffffffff8100d15b: icl_get_event_constraints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct event_constraint *icl_get_event_constraints(struct cpu_hw_events *cpuc, int idx, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100d580)
Location: arch/x86/events/intel/core.c:3485
Inline: False
```
**Symbols:**

```
ffffffff8100d580-ffffffff8100d5cb: icl_get_event_constraints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct event_constraint *icl_get_event_constraints(struct cpu_hw_events *cpuc, int idx, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100e950)
Location: arch/x86/events/intel/core.c:3516
Inline: False
```
**Symbols:**

```
ffffffff8100e950-ffffffff8100e9c2: icl_get_event_constraints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct event_constraint *icl_get_event_constraints(struct cpu_hw_events *cpuc, int idx, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100dd70)
Location: arch/x86/events/intel/core.c:3859
Inline: False
```
**Symbols:**

```
ffffffff8100dd70-ffffffff8100dde2: icl_get_event_constraints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct event_constraint *icl_get_event_constraints(struct cpu_hw_events *cpuc, int idx, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff810100e5)
Location: arch/x86/events/intel/core.c:4015
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:spr_get_event_constraints
```
**Symbols:**

```
ffffffff8100fff0-ffffffff81010062: icl_get_event_constraints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct event_constraint *icl_get_event_constraints(struct cpu_hw_events *cpuc, int idx, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff81010c55)
Location: arch/x86/events/intel/core.c:4022
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:spr_get_event_constraints
```
**Symbols:**

```
ffffffff81010b00-ffffffff81010b72: icl_get_event_constraints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct event_constraint *icl_get_event_constraints(struct cpu_hw_events *cpuc, int idx, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff81012345)
Location: arch/x86/events/intel/core.c:4084
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:spr_get_event_constraints
```
**Symbols:**

```
ffffffff810121d0-ffffffff8101224e: icl_get_event_constraints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct event_constraint *icl_get_event_constraints(struct cpu_hw_events *cpuc, int idx, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff810162a5)
Location: arch/x86/events/intel/core.c:4213
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:spr_get_event_constraints
```
**Symbols:**

```
ffffffff81016110-ffffffff8101618e: icl_get_event_constraints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct event_constraint *icl_get_event_constraints(struct cpu_hw_events *cpuc, int idx, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff81015b25)
Location: arch/x86/events/intel/core.c:4250
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:spr_get_event_constraints
```
**Symbols:**

```
ffffffff81015990-ffffffff81015a0b: icl_get_event_constraints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct event_constraint *icl_get_event_constraints(struct cpu_hw_events *cpuc, int idx, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8101b605)
Location: arch/x86/events/intel/core.c:4325
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:glc_get_event_constraints
```
**Symbols:**

```
ffffffff8101b470-ffffffff8101b4eb: icl_get_event_constraints (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
struct event_constraint *icl_get_event_constraints(struct cpu_hw_events *cpuc, int idx, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100d580)
Location: arch/x86/events/intel/core.c:3485
Inline: False
```
**Symbols:**

```
ffffffff8100d580-ffffffff8100d5cb: icl_get_event_constraints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct event_constraint *icl_get_event_constraints(struct cpu_hw_events *cpuc, int idx, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100bd80)
Location: arch/x86/events/intel/core.c:3485
Inline: False
```
**Symbols:**

```
ffffffff8100bd80-ffffffff8100bdcb: icl_get_event_constraints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct event_constraint *icl_get_event_constraints(struct cpu_hw_events *cpuc, int idx, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100d540)
Location: arch/x86/events/intel/core.c:3485
Inline: False
```
**Symbols:**

```
ffffffff8100d540-ffffffff8100d58b: icl_get_event_constraints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct event_constraint *icl_get_event_constraints(struct cpu_hw_events *cpuc, int idx, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100d770)
Location: arch/x86/events/intel/core.c:3485
Inline: False
```
**Symbols:**

```
ffffffff8100d770-ffffffff8100d7bb: icl_get_event_constraints (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
