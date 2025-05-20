# Function: <code>icl_set_topdown_event_period</code>

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
int icl_set_topdown_event_period(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100e730)
Location: arch/x86/events/intel/core.c:2259
Inline: False
```
**Symbols:**

```
ffffffff8100e730-ffffffff8100e7fd: icl_set_topdown_event_period (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int icl_set_topdown_event_period(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100ec30)
Location: arch/x86/events/intel/core.c:2413
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:adl_set_topdown_event_period
```
**Symbols:**

```
ffffffff8100ec30-ffffffff8100ecfd: icl_set_topdown_event_period (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int icl_set_topdown_event_period(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100f770)
Location: arch/x86/events/intel/core.c:2415
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:adl_set_topdown_event_period
```
**Symbols:**

```
ffffffff8100f770-ffffffff8100f83d: icl_set_topdown_event_period (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int icl_set_topdown_event_period(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff81010cc0)
Location: arch/x86/events/intel/core.c:2483
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:adl_set_topdown_event_period
```
**Symbols:**

```
ffffffff81010cc0-ffffffff81010dd3: icl_set_topdown_event_period (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int icl_set_topdown_event_period(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff81014670)
Location: arch/x86/events/intel/core.c:2498
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:adl_set_topdown_event_period
```
**Symbols:**

```
ffffffff81014670-ffffffff81014783: icl_set_topdown_event_period (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int icl_set_topdown_event_period(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff81013ed0)
Location: arch/x86/events/intel/core.c:2518
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:adl_set_topdown_event_period
```
**Symbols:**

```
ffffffff81013ed0-ffffffff81013fe3: icl_set_topdown_event_period (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int icl_set_topdown_event_period(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff81019510)
Location: arch/x86/events/intel/core.c:2543
Inline: False
```
**Symbols:**

```
ffffffff81019510-ffffffff81019623: icl_set_topdown_event_period (STB_LOCAL)
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
