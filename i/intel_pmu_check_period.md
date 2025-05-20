# Function: <code>intel_pmu_check_period</code>

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
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int intel_pmu_check_period(struct perf_event *event, u64 value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100c250)
Location: arch/x86/events/intel/core.c:3662
Inline: True
```
**Symbols:**

```
ffffffff8100c250-ffffffff8100c29d: intel_pmu_check_period (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int intel_pmu_check_period(struct perf_event *event, u64 value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100c9c0)
Location: arch/x86/events/intel/core.c:3814
Inline: True
```
**Symbols:**

```
ffffffff8100c9c0-ffffffff8100ca0d: intel_pmu_check_period (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int intel_pmu_check_period(struct perf_event *event, u64 value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100cdf0)
Location: arch/x86/events/intel/core.c:3822
Inline: True
```
**Symbols:**

```
ffffffff8100cdf0-ffffffff8100ce3d: intel_pmu_check_period (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int intel_pmu_check_period(struct perf_event *event, u64 value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100dca0)
Location: arch/x86/events/intel/core.c:3859
Inline: False
```
**Symbols:**

```
ffffffff8100dca0-ffffffff8100dced: intel_pmu_check_period (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int intel_pmu_check_period(struct perf_event *event, u64 value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100ce70)
Location: arch/x86/events/intel/core.c:4213
Inline: False
```
**Symbols:**

```
ffffffff8100ce70-ffffffff8100cebd: intel_pmu_check_period (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int intel_pmu_check_period(struct perf_event *event, u64 value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100d990)
Location: arch/x86/events/intel/core.c:4492
Inline: False
```
**Symbols:**

```
ffffffff8100d990-ffffffff8100d9dd: intel_pmu_check_period (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int intel_pmu_check_period(struct perf_event *event, u64 value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100dfc0)
Location: arch/x86/events/intel/core.c:4499
Inline: False
```
**Symbols:**

```
ffffffff8100dfc0-ffffffff8100e00d: intel_pmu_check_period (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int intel_pmu_check_period(struct perf_event *event, u64 value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100f530)
Location: arch/x86/events/intel/core.c:4561
Inline: False
```
**Symbols:**

```
ffffffff8100f530-ffffffff8100f58d: intel_pmu_check_period (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int intel_pmu_check_period(struct perf_event *event, u64 value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff81012f10)
Location: arch/x86/events/intel/core.c:4685
Inline: False
```
**Symbols:**

```
ffffffff81012f10-ffffffff81012f6d: intel_pmu_check_period (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int intel_pmu_check_period(struct perf_event *event, u64 value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff810124e0)
Location: arch/x86/events/intel/core.c:4816
Inline: False
```
**Symbols:**

```
ffffffff810124e0-ffffffff8101253d: intel_pmu_check_period (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int intel_pmu_check_period(struct perf_event *event, u64 value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff81017e00)
Location: arch/x86/events/intel/core.c:4971
Inline: False
```
**Symbols:**

```
ffffffff81017e00-ffffffff81017e5d: intel_pmu_check_period (STB_LOCAL)
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
int intel_pmu_check_period(struct perf_event *event, u64 value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100cdf0)
Location: arch/x86/events/intel/core.c:3822
Inline: True
```
**Symbols:**

```
ffffffff8100cdf0-ffffffff8100ce3d: intel_pmu_check_period (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int intel_pmu_check_period(struct perf_event *event, u64 value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100b5f0)
Location: arch/x86/events/intel/core.c:3822
Inline: True
```
**Symbols:**

```
ffffffff8100b5f0-ffffffff8100b63d: intel_pmu_check_period (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int intel_pmu_check_period(struct perf_event *event, u64 value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100cdb0)
Location: arch/x86/events/intel/core.c:3822
Inline: True
```
**Symbols:**

```
ffffffff8100cdb0-ffffffff8100cdfd: intel_pmu_check_period (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int intel_pmu_check_period(struct perf_event *event, u64 value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100cfe0)
Location: arch/x86/events/intel/core.c:3822
Inline: True
```
**Symbols:**

```
ffffffff8100cfe0-ffffffff8100d02d: intel_pmu_check_period (STB_LOCAL)
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
