# Function: <code>zhaoxin_pmu_disable_event</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void zhaoxin_pmu_disable_event(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/zhaoxin/core.c (ffffffff8101fb00)
Location: arch/x86/events/zhaoxin/core.c:301
Inline: False
```
**Symbols:**

```
ffffffff8101fb00-ffffffff8101fbbb: zhaoxin_pmu_disable_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void zhaoxin_pmu_disable_event(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/zhaoxin/core.c (ffffffff810205a0)
Location: arch/x86/events/zhaoxin/core.c:301
Inline: False
```
**Symbols:**

```
ffffffff810205a0-ffffffff8102065b: zhaoxin_pmu_disable_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void zhaoxin_pmu_disable_event(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/zhaoxin/core.c (ffffffff81022930)
Location: arch/x86/events/zhaoxin/core.c:301
Inline: False
```
**Symbols:**

```
ffffffff81022930-ffffffff810229f8: zhaoxin_pmu_disable_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void zhaoxin_pmu_disable_event(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/zhaoxin/core.c (0)
Location: arch/x86/events/zhaoxin/core.c:301
Inline: False
```
**Symbols:**

```
ffffffff810267c0-ffffffff81026894: zhaoxin_pmu_disable_event (STB_LOCAL)
ffffffff81c96e9e-ffffffff81c96ebe: zhaoxin_pmu_disable_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void zhaoxin_pmu_disable_event(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/zhaoxin/core.c (0)
Location: arch/x86/events/zhaoxin/core.c:301
Inline: False
```
**Symbols:**

```
ffffffff8102a8f0-ffffffff8102aa12: zhaoxin_pmu_disable_event (STB_LOCAL)
ffffffff81e462f7-ffffffff81e46317: zhaoxin_pmu_disable_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void zhaoxin_pmu_disable_event(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/zhaoxin/core.c (0)
Location: arch/x86/events/zhaoxin/core.c:301
Inline: False
```
**Symbols:**

```
ffffffff810314d0-ffffffff810315f2: zhaoxin_pmu_disable_event (STB_LOCAL)
ffffffff820517aa-ffffffff820517ca: zhaoxin_pmu_disable_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void zhaoxin_pmu_disable_event(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/zhaoxin/core.c (0)
Location: arch/x86/events/zhaoxin/core.c:301
Inline: False
```
**Symbols:**

```
ffffffff810314d0-ffffffff810315f2: zhaoxin_pmu_disable_event (STB_LOCAL)
ffffffff820cfc96-ffffffff820cfcb6: zhaoxin_pmu_disable_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void zhaoxin_pmu_disable_event(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/zhaoxin/core.c (0)
Location: arch/x86/events/zhaoxin/core.c:301
Inline: False
```
**Symbols:**

```
ffffffff810377c0-ffffffff810378e2: zhaoxin_pmu_disable_event (STB_LOCAL)
ffffffff821aa604-ffffffff821aa624: zhaoxin_pmu_disable_event.cold (STB_LOCAL)
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
