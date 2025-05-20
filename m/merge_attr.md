# Function: <code>merge_attr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct attribute **merge_attr(struct attribute **a, struct attribute **b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81f5cec9)
Location: arch/x86/events/core.c:1554
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
```
**Symbols:**

```
ffffffff81f5cec9-ffffffff81f5cf55: merge_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct attribute **merge_attr(struct attribute **a, struct attribute **b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81f84e1a)
Location: arch/x86/events/core.c:1590
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
```
**Symbols:**

```
ffffffff81f84e1a-ffffffff81f84ea6: merge_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct attribute **merge_attr(struct attribute **a, struct attribute **b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81fc022e)
Location: arch/x86/events/core.c:1619
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
```
**Symbols:**

```
ffffffff81fc022e-ffffffff81fc02ba: merge_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct attribute **merge_attr(struct attribute **a, struct attribute **b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff820a0416)
Location: arch/x86/events/core.c:1620
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
```
**Symbols:**

```
ffffffff820a0416-ffffffff820a04a5: merge_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct attribute **merge_attr(struct attribute **a, struct attribute **b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff826a6534)
Location: arch/x86/events/core.c:1626
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
```
**Symbols:**

```
ffffffff826a6534-ffffffff826a65c3: merge_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct attribute **merge_attr(struct attribute **a, struct attribute **b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff826cf6b1)
Location: arch/x86/events/core.c:1629
Inline: False
Direct callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:get_hsw_events_attrs
```
**Symbols:**

```
ffffffff826cf6b1-ffffffff826cf74f: merge_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct attribute **merge_attr(struct attribute **a, struct attribute **b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff828856de)
Location: arch/x86/events/core.c:1630
Inline: False
Direct callers:
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/core.c:init_hw_perf_events
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
```
**Symbols:**

```
ffffffff828856de-ffffffff82885790: merge_attr (STB_GLOBAL)
```
</details>
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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
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
</ul>
