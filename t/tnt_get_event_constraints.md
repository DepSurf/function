# Function: <code>tnt_get_event_constraints</code>

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
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct event_constraint *tnt_get_event_constraints(struct cpu_hw_events *cpuc, int idx, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100d1b0)
Location: arch/x86/events/intel/core.c:3507
Inline: True
```
**Symbols:**

```
ffffffff8100d1b0-ffffffff8100d203: tnt_get_event_constraints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct event_constraint *tnt_get_event_constraints(struct cpu_hw_events *cpuc, int idx, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100d620)
Location: arch/x86/events/intel/core.c:3515
Inline: True
```
**Symbols:**

```
ffffffff8100d620-ffffffff8100d673: tnt_get_event_constraints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct event_constraint *tnt_get_event_constraints(struct cpu_hw_events *cpuc, int idx, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100e8c0)
Location: arch/x86/events/intel/core.c:3546
Inline: True
```
**Symbols:**

```
ffffffff8100e8c0-ffffffff8100e913: tnt_get_event_constraints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct event_constraint *tnt_get_event_constraints(struct cpu_hw_events *cpuc, int idx, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100dce0)
Location: arch/x86/events/intel/core.c:3889
Inline: True
```
**Symbols:**

```
ffffffff8100dce0-ffffffff8100dd33: tnt_get_event_constraints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct event_constraint *tnt_get_event_constraints(struct cpu_hw_events *cpuc, int idx, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff810101e1)
Location: arch/x86/events/intel/core.c:4070
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:adl_get_event_constraints
  - arch/x86/events/intel/core.c:adl_get_event_constraints
```
**Symbols:**

```
ffffffff8100ff60-ffffffff8100ffb3: tnt_get_event_constraints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct event_constraint *tnt_get_event_constraints(struct cpu_hw_events *cpuc, int idx, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff81010d51)
Location: arch/x86/events/intel/core.c:4077
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:adl_get_event_constraints
  - arch/x86/events/intel/core.c:adl_get_event_constraints
```
**Symbols:**

```
ffffffff81010a70-ffffffff81010ac3: tnt_get_event_constraints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct event_constraint *tnt_get_event_constraints(struct cpu_hw_events *cpuc, int idx, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8101246d)
Location: arch/x86/events/intel/core.c:4139
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:adl_get_event_constraints
  - arch/x86/events/intel/core.c:adl_get_event_constraints
```
**Symbols:**

```
ffffffff81012110-ffffffff81012176: tnt_get_event_constraints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct event_constraint *tnt_get_event_constraints(struct cpu_hw_events *cpuc, int idx, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff810163dd)
Location: arch/x86/events/intel/core.c:4268
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:adl_get_event_constraints
  - arch/x86/events/intel/core.c:adl_get_event_constraints
```
**Symbols:**

```
ffffffff81016030-ffffffff81016096: tnt_get_event_constraints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct event_constraint *tnt_get_event_constraints(struct cpu_hw_events *cpuc, int idx, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff81015d6d)
Location: arch/x86/events/intel/core.c:4305
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:adl_get_event_constraints
  - arch/x86/events/intel/core.c:adl_get_event_constraints
```
**Symbols:**

```
ffffffff810158c0-ffffffff81015922: tnt_get_event_constraints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct event_constraint *tnt_get_event_constraints(struct cpu_hw_events *cpuc, int idx, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8101b80e)
Location: arch/x86/events/intel/core.c:4380
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:adl_get_event_constraints
  - arch/x86/events/intel/core.c:adl_get_event_constraints
```
**Symbols:**

```
ffffffff8101b3a0-ffffffff8101b402: tnt_get_event_constraints (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct event_constraint *tnt_get_event_constraints(struct cpu_hw_events *cpuc, int idx, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100d620)
Location: arch/x86/events/intel/core.c:3515
Inline: True
```
**Symbols:**

```
ffffffff8100d620-ffffffff8100d673: tnt_get_event_constraints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct event_constraint *tnt_get_event_constraints(struct cpu_hw_events *cpuc, int idx, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100be20)
Location: arch/x86/events/intel/core.c:3515
Inline: True
```
**Symbols:**

```
ffffffff8100be20-ffffffff8100be73: tnt_get_event_constraints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct event_constraint *tnt_get_event_constraints(struct cpu_hw_events *cpuc, int idx, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100d5e0)
Location: arch/x86/events/intel/core.c:3515
Inline: True
```
**Symbols:**

```
ffffffff8100d5e0-ffffffff8100d633: tnt_get_event_constraints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct event_constraint *tnt_get_event_constraints(struct cpu_hw_events *cpuc, int idx, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100d810)
Location: arch/x86/events/intel/core.c:3515
Inline: True
```
**Symbols:**

```
ffffffff8100d810-ffffffff8100d863: tnt_get_event_constraints (STB_LOCAL)
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
