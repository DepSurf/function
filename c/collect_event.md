# Function: <code>collect_event</code>

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
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int collect_event(struct cpu_hw_events *cpuc, struct perf_event *event, int max_count, int n);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006300)
Location: arch/x86/events/core.c:1082
Inline: True
Direct callers:
  - arch/x86/events/core.c:collect_events
  - arch/x86/events/core.c:collect_events
```
**Symbols:**

```
ffffffff81006300-ffffffff81006388: collect_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int collect_event(struct cpu_hw_events *cpuc, struct perf_event *event, int max_count, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81005ff0)
Location: arch/x86/events/core.c:1132
Inline: False
Direct callers:
  - arch/x86/events/core.c:collect_events
  - arch/x86/events/core.c:collect_events
```
**Symbols:**

```
ffffffff81005ff0-ffffffff810060af: collect_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int collect_event(struct cpu_hw_events *cpuc, struct perf_event *event, int max_count, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff810066a0)
Location: arch/x86/events/core.c:1130
Inline: False
Direct callers:
  - arch/x86/events/core.c:collect_events
  - arch/x86/events/core.c:collect_events
```
**Symbols:**

```
ffffffff810066a0-ffffffff81006797: collect_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int collect_event(struct cpu_hw_events *cpuc, struct perf_event *event, int max_count, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81005aa0)
Location: arch/x86/events/core.c:1132
Inline: False
Direct callers:
  - arch/x86/events/core.c:collect_events
  - arch/x86/events/core.c:collect_events
```
**Symbols:**

```
ffffffff81005aa0-ffffffff81005baf: collect_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int collect_event(struct cpu_hw_events *cpuc, struct perf_event *event, int max_count, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81007030)
Location: arch/x86/events/core.c:1136
Inline: False
Direct callers:
  - arch/x86/events/core.c:collect_events
  - arch/x86/events/core.c:collect_events
```
**Symbols:**

```
ffffffff81007030-ffffffff81007133: collect_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int collect_event(struct cpu_hw_events *cpuc, struct perf_event *event, int max_count, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff810067d0)
Location: arch/x86/events/core.c:1136
Inline: False
Direct callers:
  - arch/x86/events/core.c:collect_events
  - arch/x86/events/core.c:collect_events
```
**Symbols:**

```
ffffffff810067d0-ffffffff810068de: collect_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int collect_event(struct cpu_hw_events *cpuc, struct perf_event *event, int max_count, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff8100bed0)
Location: arch/x86/events/core.c:1134
Inline: False
Direct callers:
  - arch/x86/events/core.c:collect_events
  - arch/x86/events/core.c:collect_events
```
**Symbols:**

```
ffffffff8100bed0-ffffffff8100bfde: collect_event (STB_LOCAL)
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
