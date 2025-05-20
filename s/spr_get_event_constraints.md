# Function: <code>spr_get_event_constraints</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct event_constraint *spr_get_event_constraints(struct cpu_hw_events *cpuc, int idx, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff810100e0)
Location: arch/x86/events/intel/core.c:4030
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:adl_get_event_constraints
```
**Symbols:**

```
ffffffff810100e0-ffffffff810101a1: spr_get_event_constraints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct event_constraint *spr_get_event_constraints(struct cpu_hw_events *cpuc, int idx, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff81010c50)
Location: arch/x86/events/intel/core.c:4037
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:adl_get_event_constraints
```
**Symbols:**

```
ffffffff81010c50-ffffffff81010d11: spr_get_event_constraints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct event_constraint *spr_get_event_constraints(struct cpu_hw_events *cpuc, int idx, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff81012340)
Location: arch/x86/events/intel/core.c:4099
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:adl_get_event_constraints
```
**Symbols:**

```
ffffffff81012340-ffffffff81012419: spr_get_event_constraints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct event_constraint *spr_get_event_constraints(struct cpu_hw_events *cpuc, int idx, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff810162a0)
Location: arch/x86/events/intel/core.c:4228
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:adl_get_event_constraints
```
**Symbols:**

```
ffffffff810162a0-ffffffff81016379: spr_get_event_constraints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct event_constraint *spr_get_event_constraints(struct cpu_hw_events *cpuc, int idx, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff81015b20)
Location: arch/x86/events/intel/core.c:4265
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:mtl_get_event_constraints
  - arch/x86/events/intel/core.c:adl_get_event_constraints
```
**Symbols:**

```
ffffffff81015b20-ffffffff81015c00: spr_get_event_constraints (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
<b>Regular</b>
<ul>
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
</ul>
