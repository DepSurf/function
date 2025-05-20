# Function: <code>hsw_get_event_constraints</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct event_constraint *hsw_get_event_constraints(struct cpu_hw_events *cpuc, int idx, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100bde0)
Location: arch/x86/events/intel/core.c:2704
Inline: False
```
**Symbols:**

```
ffffffff8100bde0-ffffffff8100be13: hsw_get_event_constraints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct event_constraint *hsw_get_event_constraints(struct cpu_hw_events *cpuc, int idx, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100bf80)
Location: arch/x86/events/intel/core.c:2987
Inline: False
```
**Symbols:**

```
ffffffff8100bf80-ffffffff8100bfb3: hsw_get_event_constraints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct event_constraint *hsw_get_event_constraints(struct cpu_hw_events *cpuc, int idx, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100c060)
Location: arch/x86/events/intel/core.c:3002
Inline: False
```
**Symbols:**

```
ffffffff8100c060-ffffffff8100c093: hsw_get_event_constraints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct event_constraint *hsw_get_event_constraints(struct cpu_hw_events *cpuc, int idx, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100bdc0)
Location: arch/x86/events/intel/core.c:3140
Inline: False
```
**Symbols:**

```
ffffffff8100bdc0-ffffffff8100bdf3: hsw_get_event_constraints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct event_constraint *hsw_get_event_constraints(struct cpu_hw_events *cpuc, int idx, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100c240)
Location: arch/x86/events/intel/core.c:3144
Inline: False
```
**Symbols:**

```
ffffffff8100c240-ffffffff8100c273: hsw_get_event_constraints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct event_constraint *hsw_get_event_constraints(struct cpu_hw_events *cpuc, int idx, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100c930)
Location: arch/x86/events/intel/core.c:3163
Inline: False
```
**Symbols:**

```
ffffffff8100c930-ffffffff8100c963: hsw_get_event_constraints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct event_constraint *hsw_get_event_constraints(struct cpu_hw_events *cpuc, int idx, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100c940)
Location: arch/x86/events/intel/core.c:3358
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:tfa_get_event_constraints
```
**Symbols:**

```
ffffffff8100c940-ffffffff8100c973: hsw_get_event_constraints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct event_constraint *hsw_get_event_constraints(struct cpu_hw_events *cpuc, int idx, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100d0d0)
Location: arch/x86/events/intel/core.c:3459
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:tfa_get_event_constraints
  - arch/x86/events/intel/core.c:icl_get_event_constraints
```
**Symbols:**

```
ffffffff8100d0d0-ffffffff8100d103: hsw_get_event_constraints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct event_constraint *hsw_get_event_constraints(struct cpu_hw_events *cpuc, int idx, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100d540)
Location: arch/x86/events/intel/core.c:3467
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:tfa_get_event_constraints
  - arch/x86/events/intel/core.c:icl_get_event_constraints
```
**Symbols:**

```
ffffffff8100d540-ffffffff8100d573: hsw_get_event_constraints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct event_constraint *hsw_get_event_constraints(struct cpu_hw_events *cpuc, int idx, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100e9d5)
Location: arch/x86/events/intel/core.c:3498
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:tfa_get_event_constraints
  - arch/x86/events/intel/core.c:icl_get_event_constraints
```
**Symbols:**

```
ffffffff8100e880-ffffffff8100e8b6: hsw_get_event_constraints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct event_constraint *hsw_get_event_constraints(struct cpu_hw_events *cpuc, int idx, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100de07)
Location: arch/x86/events/intel/core.c:3841
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:tfa_get_event_constraints
  - arch/x86/events/intel/core.c:icl_get_event_constraints
```
**Symbols:**

```
ffffffff8100dca0-ffffffff8100dcd6: hsw_get_event_constraints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct event_constraint *hsw_get_event_constraints(struct cpu_hw_events *cpuc, int idx, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff81010087)
Location: arch/x86/events/intel/core.c:3997
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:tfa_get_event_constraints
  - arch/x86/events/intel/core.c:spr_get_event_constraints
```
**Symbols:**

```
ffffffff8100ff20-ffffffff8100ff56: hsw_get_event_constraints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct event_constraint *hsw_get_event_constraints(struct cpu_hw_events *cpuc, int idx, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff81010b97)
Location: arch/x86/events/intel/core.c:4004
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:tfa_get_event_constraints
  - arch/x86/events/intel/core.c:spr_get_event_constraints
```
**Symbols:**

```
ffffffff81010a30-ffffffff81010a66: hsw_get_event_constraints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct event_constraint *hsw_get_event_constraints(struct cpu_hw_events *cpuc, int idx, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8101226a)
Location: arch/x86/events/intel/core.c:4066
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:tfa_get_event_constraints
  - arch/x86/events/intel/core.c:spr_get_event_constraints
```
**Symbols:**

```
ffffffff810120d0-ffffffff81012110: hsw_get_event_constraints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct event_constraint *hsw_get_event_constraints(struct cpu_hw_events *cpuc, int idx, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff810161ba)
Location: arch/x86/events/intel/core.c:4195
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:tfa_get_event_constraints
  - arch/x86/events/intel/core.c:spr_get_event_constraints
```
**Symbols:**

```
ffffffff81015fe0-ffffffff81016020: hsw_get_event_constraints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct event_constraint *hsw_get_event_constraints(struct cpu_hw_events *cpuc, int idx, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff81015a3a)
Location: arch/x86/events/intel/core.c:4232
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:tfa_get_event_constraints
  - arch/x86/events/intel/core.c:spr_get_event_constraints
```
**Symbols:**

```
ffffffff81015870-ffffffff810158b0: hsw_get_event_constraints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct event_constraint *hsw_get_event_constraints(struct cpu_hw_events *cpuc, int idx, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8101b51a)
Location: arch/x86/events/intel/core.c:4307
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:tfa_get_event_constraints
  - arch/x86/events/intel/core.c:glc_get_event_constraints
```
**Symbols:**

```
ffffffff8101b2a0-ffffffff8101b2e0: hsw_get_event_constraints (STB_LOCAL)
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
struct event_constraint *hsw_get_event_constraints(struct cpu_hw_events *cpuc, int idx, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100d540)
Location: arch/x86/events/intel/core.c:3467
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:tfa_get_event_constraints
  - arch/x86/events/intel/core.c:icl_get_event_constraints
```
**Symbols:**

```
ffffffff8100d540-ffffffff8100d573: hsw_get_event_constraints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct event_constraint *hsw_get_event_constraints(struct cpu_hw_events *cpuc, int idx, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100bd40)
Location: arch/x86/events/intel/core.c:3467
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:tfa_get_event_constraints
  - arch/x86/events/intel/core.c:icl_get_event_constraints
```
**Symbols:**

```
ffffffff8100bd40-ffffffff8100bd73: hsw_get_event_constraints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct event_constraint *hsw_get_event_constraints(struct cpu_hw_events *cpuc, int idx, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100d500)
Location: arch/x86/events/intel/core.c:3467
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:tfa_get_event_constraints
  - arch/x86/events/intel/core.c:icl_get_event_constraints
```
**Symbols:**

```
ffffffff8100d500-ffffffff8100d533: hsw_get_event_constraints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct event_constraint *hsw_get_event_constraints(struct cpu_hw_events *cpuc, int idx, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100d730)
Location: arch/x86/events/intel/core.c:3467
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:tfa_get_event_constraints
  - arch/x86/events/intel/core.c:icl_get_event_constraints
```
**Symbols:**

```
ffffffff8100d730-ffffffff8100d763: hsw_get_event_constraints (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
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
