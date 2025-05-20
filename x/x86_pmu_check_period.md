# Function: <code>x86_pmu_check_period</code>

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
int x86_pmu_check_period(struct perf_event *event, u64 value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006040)
Location: arch/x86/events/core.c:2278
Inline: True
```
**Symbols:**

```
ffffffff81006040-ffffffff81006096: x86_pmu_check_period (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int x86_pmu_check_period(struct perf_event *event, u64 value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006250)
Location: arch/x86/events/core.c:2231
Inline: True
```
**Symbols:**

```
ffffffff81006250-ffffffff810062a6: x86_pmu_check_period (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int x86_pmu_check_period(struct perf_event *event, u64 value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff810062d0)
Location: arch/x86/events/core.c:2307
Inline: True
```
**Symbols:**

```
ffffffff810062d0-ffffffff81006326: x86_pmu_check_period (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int x86_pmu_check_period(struct perf_event *event, u64 value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81007200)
Location: arch/x86/events/core.c:2319
Inline: True
```
**Symbols:**

```
ffffffff81007200-ffffffff81007256: x86_pmu_check_period (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int x86_pmu_check_period(struct perf_event *event, u64 value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006080)
Location: arch/x86/events/core.c:2431
Inline: True
```
**Symbols:**

```
ffffffff81006080-ffffffff810060d6: x86_pmu_check_period (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int x86_pmu_check_period(struct perf_event *event, u64 value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81005df0)
Location: arch/x86/events/core.c:2651
Inline: True
```
**Symbols:**

```
ffffffff81005df0-ffffffff81005e46: x86_pmu_check_period (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int x86_pmu_check_period(struct perf_event *event, u64 value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff810064a0)
Location: arch/x86/events/core.c:2650
Inline: True
```
**Symbols:**

```
ffffffff810064a0-ffffffff810064f6: x86_pmu_check_period (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int x86_pmu_check_period(struct perf_event *event, u64 value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81005070)
Location: arch/x86/events/core.c:2664
Inline: False
```
**Symbols:**

```
ffffffff81005070-ffffffff810050ce: x86_pmu_check_period (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int x86_pmu_check_period(struct perf_event *event, u64 value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81005b80)
Location: arch/x86/events/core.c:2645
Inline: False
```
**Symbols:**

```
ffffffff81005b80-ffffffff81005c0f: x86_pmu_check_period (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int x86_pmu_check_period(struct perf_event *event, u64 value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81005330)
Location: arch/x86/events/core.c:2643
Inline: False
```
**Symbols:**

```
ffffffff81005330-ffffffff810053bf: x86_pmu_check_period (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int x86_pmu_check_period(struct perf_event *event, u64 value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff8100aa30)
Location: arch/x86/events/core.c:2640
Inline: False
```
**Symbols:**

```
ffffffff8100aa30-ffffffff8100aabf: x86_pmu_check_period (STB_LOCAL)
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
int x86_pmu_check_period(struct perf_event *event, u64 value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff810062d0)
Location: arch/x86/events/core.c:2307
Inline: True
```
**Symbols:**

```
ffffffff810062d0-ffffffff81006326: x86_pmu_check_period (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int x86_pmu_check_period(struct perf_event *event, u64 value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81004a50)
Location: arch/x86/events/core.c:2307
Inline: True
```
**Symbols:**

```
ffffffff81004a50-ffffffff81004aa6: x86_pmu_check_period (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int x86_pmu_check_period(struct perf_event *event, u64 value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006290)
Location: arch/x86/events/core.c:2307
Inline: True
```
**Symbols:**

```
ffffffff81006290-ffffffff810062e6: x86_pmu_check_period (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int x86_pmu_check_period(struct perf_event *event, u64 value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff810063f0)
Location: arch/x86/events/core.c:2307
Inline: True
```
**Symbols:**

```
ffffffff810063f0-ffffffff81006446: x86_pmu_check_period (STB_LOCAL)
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
