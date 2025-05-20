# Function: <code>update_saved_topdown_regs</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void update_saved_topdown_regs(struct perf_event *event, u64 slots, u64 metrics);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100c320)
Location: arch/x86/events/intel/core.c:2340
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:icl_update_topdown_event
  - arch/x86/events/intel/core.c:icl_update_topdown_event
```
**Symbols:**

```
ffffffff8100c320-ffffffff8100c3b4: update_saved_topdown_regs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void update_saved_topdown_regs(struct perf_event *event, u64 slots, u64 metrics, int metric_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100dd30)
Location: arch/x86/events/intel/core.c:2504
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_update_topdown_event
  - arch/x86/events/intel/core.c:intel_update_topdown_event
```
**Symbols:**

```
ffffffff8100dd30-ffffffff8100dddc: update_saved_topdown_regs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void update_saved_topdown_regs(struct perf_event *event, u64 slots, u64 metrics, int metric_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100e3c0)
Location: arch/x86/events/intel/core.c:2506
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_update_topdown_event
  - arch/x86/events/intel/core.c:intel_update_topdown_event
```
**Symbols:**

```
ffffffff8100e3c0-ffffffff8100e491: update_saved_topdown_regs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void update_saved_topdown_regs(struct perf_event *event, u64 slots, u64 metrics, int metric_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100fa70)
Location: arch/x86/events/intel/core.c:2574
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_update_topdown_event
  - arch/x86/events/intel/core.c:intel_update_topdown_event
```
**Symbols:**

```
ffffffff8100fa70-ffffffff8100fb61: update_saved_topdown_regs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void update_saved_topdown_regs(struct perf_event *event, u64 slots, u64 metrics, int metric_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff810134b0)
Location: arch/x86/events/intel/core.c:2591
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_update_topdown_event
  - arch/x86/events/intel/core.c:intel_update_topdown_event
```
**Symbols:**

```
ffffffff810134b0-ffffffff8101357b: update_saved_topdown_regs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void update_saved_topdown_regs(struct perf_event *event, u64 slots, u64 metrics, int metric_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff81012800)
Location: arch/x86/events/intel/core.c:2611
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_update_topdown_event
  - arch/x86/events/intel/core.c:intel_update_topdown_event
```
**Symbols:**

```
ffffffff81012800-ffffffff810128cb: update_saved_topdown_regs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void update_saved_topdown_regs(struct perf_event *event, u64 slots, u64 metrics, int metric_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff81018120)
Location: arch/x86/events/intel/core.c:2626
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_update_topdown_event
  - arch/x86/events/intel/core.c:intel_update_topdown_event
```
**Symbols:**

```
ffffffff81018120-ffffffff810181eb: update_saved_topdown_regs (STB_LOCAL)
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
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int metric_end</code>
</li>
</ul>
</details>
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
