# Function: <code>tfa_get_event_constraints</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct event_constraint *tfa_get_event_constraints(struct cpu_hw_events *cpuc, int idx, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100c980)
Location: arch/x86/events/intel/core.c:3393
Inline: False
```
**Symbols:**

```
ffffffff8100c980-ffffffff8100c9cf: tfa_get_event_constraints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct event_constraint *tfa_get_event_constraints(struct cpu_hw_events *cpuc, int idx, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100d160)
Location: arch/x86/events/intel/core.c:3532
Inline: False
```
**Symbols:**

```
ffffffff8100d160-ffffffff8100d1ac: tfa_get_event_constraints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct event_constraint *tfa_get_event_constraints(struct cpu_hw_events *cpuc, int idx, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100d5d0)
Location: arch/x86/events/intel/core.c:3540
Inline: False
```
**Symbols:**

```
ffffffff8100d5d0-ffffffff8100d61c: tfa_get_event_constraints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct event_constraint *tfa_get_event_constraints(struct cpu_hw_events *cpuc, int idx, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100e9d0)
Location: arch/x86/events/intel/core.c:3571
Inline: False
```
**Symbols:**

```
ffffffff8100e9d0-ffffffff8100ea3f: tfa_get_event_constraints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct event_constraint *tfa_get_event_constraints(struct cpu_hw_events *cpuc, int idx, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100ddf0)
Location: arch/x86/events/intel/core.c:3914
Inline: False
```
**Symbols:**

```
ffffffff8100ddf0-ffffffff8100de5f: tfa_get_event_constraints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct event_constraint *tfa_get_event_constraints(struct cpu_hw_events *cpuc, int idx, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff81010070)
Location: arch/x86/events/intel/core.c:4095
Inline: False
```
**Symbols:**

```
ffffffff81010070-ffffffff810100df: tfa_get_event_constraints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct event_constraint *tfa_get_event_constraints(struct cpu_hw_events *cpuc, int idx, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/core.c (0)
Location: arch/x86/events/intel/core.c:4102
Inline: False
```
**Symbols:**

```
ffffffff81010b80-ffffffff81010c4c: tfa_get_event_constraints (STB_LOCAL)
ffffffff81c95c1a-ffffffff81c95c36: tfa_get_event_constraints.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct event_constraint *tfa_get_event_constraints(struct cpu_hw_events *cpuc, int idx, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/core.c (0)
Location: arch/x86/events/intel/core.c:4164
Inline: False
```
**Symbols:**

```
ffffffff81012250-ffffffff81012333: tfa_get_event_constraints (STB_LOCAL)
ffffffff81e44f4d-ffffffff81e44f69: tfa_get_event_constraints.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct event_constraint *tfa_get_event_constraints(struct cpu_hw_events *cpuc, int idx, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/core.c (0)
Location: arch/x86/events/intel/core.c:4293
Inline: False
```
**Symbols:**

```
ffffffff810161a0-ffffffff81016283: tfa_get_event_constraints (STB_LOCAL)
ffffffff820507c0-ffffffff820507dc: tfa_get_event_constraints.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct event_constraint *tfa_get_event_constraints(struct cpu_hw_events *cpuc, int idx, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/core.c (0)
Location: arch/x86/events/intel/core.c:4330
Inline: False
```
**Symbols:**

```
ffffffff81015a20-ffffffff81015b03: tfa_get_event_constraints (STB_LOCAL)
ffffffff820cebfd-ffffffff820cec19: tfa_get_event_constraints.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct event_constraint *tfa_get_event_constraints(struct cpu_hw_events *cpuc, int idx, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/core.c (0)
Location: arch/x86/events/intel/core.c:4405
Inline: False
```
**Symbols:**

```
ffffffff8101b500-ffffffff8101b5e3: tfa_get_event_constraints (STB_LOCAL)
ffffffff821a949c-ffffffff821a94b8: tfa_get_event_constraints.cold (STB_LOCAL)
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
struct event_constraint *tfa_get_event_constraints(struct cpu_hw_events *cpuc, int idx, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100d5d0)
Location: arch/x86/events/intel/core.c:3540
Inline: False
```
**Symbols:**

```
ffffffff8100d5d0-ffffffff8100d61c: tfa_get_event_constraints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct event_constraint *tfa_get_event_constraints(struct cpu_hw_events *cpuc, int idx, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100bdd0)
Location: arch/x86/events/intel/core.c:3540
Inline: False
```
**Symbols:**

```
ffffffff8100bdd0-ffffffff8100be1c: tfa_get_event_constraints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct event_constraint *tfa_get_event_constraints(struct cpu_hw_events *cpuc, int idx, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100d590)
Location: arch/x86/events/intel/core.c:3540
Inline: False
```
**Symbols:**

```
ffffffff8100d590-ffffffff8100d5dc: tfa_get_event_constraints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct event_constraint *tfa_get_event_constraints(struct cpu_hw_events *cpuc, int idx, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100d7c0)
Location: arch/x86/events/intel/core.c:3540
Inline: False
```
**Symbols:**

```
ffffffff8100d7c0-ffffffff8100d80c: tfa_get_event_constraints (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
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
