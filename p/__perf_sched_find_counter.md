# Function: <code>__perf_sched_find_counter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81004f73)
Location: arch/x86/events/core.c:715
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_assign_events
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff810051ac)
Location: arch/x86/events/core.c:742
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_assign_events
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff810051cc)
Location: arch/x86/events/core.c:751
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_assign_events
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff8100504a)
Location: arch/x86/events/core.c:752
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_assign_events
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff810052fa)
Location: arch/x86/events/core.c:758
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_assign_events
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81005ab9)
Location: arch/x86/events/core.c:764
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_assign_events
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff810059b9)
Location: arch/x86/events/core.c:744
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_assign_events
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81005ff8)
Location: arch/x86/events/core.c:763
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_assign_events
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81005fb5)
Location: arch/x86/events/core.c:775
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_assign_events
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006ede)
Location: arch/x86/events/core.c:776
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_assign_events
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81005d1e)
Location: arch/x86/events/core.c:808
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_assign_events
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool __perf_sched_find_counter(struct perf_sched *sched);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff810060b0)
Location: arch/x86/events/core.c:857
Inline: False
Direct callers:
  - arch/x86/events/core.c:perf_assign_events
  - arch/x86/events/core.c:perf_assign_events
```
**Symbols:**

```
ffffffff810060b0-ffffffff8100625e: __perf_sched_find_counter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool __perf_sched_find_counter(struct perf_sched *sched);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (0)
Location: arch/x86/events/core.c:857
Inline: False
Direct callers:
  - arch/x86/events/core.c:perf_assign_events
  - arch/x86/events/core.c:perf_assign_events
```
**Symbols:**

```
ffffffff810068c0-ffffffff81006a5f: __perf_sched_find_counter (STB_LOCAL)
ffffffff81c94eea-ffffffff81c94f28: __perf_sched_find_counter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool __perf_sched_find_counter(struct perf_sched *sched);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (0)
Location: arch/x86/events/core.c:859
Inline: False
Direct callers:
  - arch/x86/events/core.c:perf_assign_events
  - arch/x86/events/core.c:perf_assign_events
```
**Symbols:**

```
ffffffff81005cf0-ffffffff81005eeb: __perf_sched_find_counter (STB_LOCAL)
ffffffff81e441e4-ffffffff81e44222: __perf_sched_find_counter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff8100720c)
Location: arch/x86/events/core.c:863
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_assign_events
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool __perf_sched_find_counter(struct perf_sched *sched);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (0)
Location: arch/x86/events/core.c:863
Inline: False
Direct callers:
  - arch/x86/events/core.c:perf_assign_events
  - arch/x86/events/core.c:perf_assign_events
```
**Symbols:**

```
ffffffff810068f0-ffffffff81006aee: __perf_sched_find_counter (STB_LOCAL)
ffffffff820ce646-ffffffff820ce684: __perf_sched_find_counter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool __perf_sched_find_counter(struct perf_sched *sched);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (0)
Location: arch/x86/events/core.c:861
Inline: False
Direct callers:
  - arch/x86/events/core.c:perf_assign_events
  - arch/x86/events/core.c:perf_assign_events
```
**Symbols:**

```
ffffffff8100bff0-ffffffff8100c1ee: __perf_sched_find_counter (STB_LOCAL)
ffffffff821a8e82-ffffffff821a8ec0: __perf_sched_find_counter.cold (STB_LOCAL)
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81005fb5)
Location: arch/x86/events/core.c:775
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_assign_events
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81004735)
Location: arch/x86/events/core.c:775
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_assign_events
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81005f75)
Location: arch/x86/events/core.c:775
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_assign_events
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff810060d5)
Location: arch/x86/events/core.c:775
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_assign_events
```
</details>
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
