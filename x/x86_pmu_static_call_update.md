# Function: <code>x86_pmu_static_call_update</code>

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
void x86_pmu_static_call_update();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81bd1d58)
Location: arch/x86/events/core.c:1901
Inline: False
Direct callers:
  - arch/x86/events/core.c:init_hw_perf_events
```
**Symbols:**

```
ffffffff81bd1d58-ffffffff81bd1f37: x86_pmu_static_call_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void x86_pmu_static_call_update();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81bc3c6a)
Location: arch/x86/events/core.c:2002
Inline: False
Direct callers:
  - arch/x86/events/core.c:init_hw_perf_events
```
**Symbols:**

```
ffffffff81bc3c6a-ffffffff81bc3e63: x86_pmu_static_call_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void x86_pmu_static_call_update();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81c94cdc)
Location: arch/x86/events/core.c:2000
Inline: False
Direct callers:
  - arch/x86/events/core.c:init_hw_perf_events
```
**Symbols:**

```
ffffffff81c94cdc-ffffffff81c94ed5: x86_pmu_static_call_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void x86_pmu_static_call_update();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81e43fb2)
Location: arch/x86/events/core.c:2012
Inline: False
Direct callers:
  - arch/x86/events/core.c:init_hw_perf_events
```
**Symbols:**

```
ffffffff81e43fb2-ffffffff81e441cf: x86_pmu_static_call_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void x86_pmu_static_call_update();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006860)
Location: arch/x86/events/core.c:2003
Inline: False
Direct callers:
  - arch/x86/events/core.c:init_hw_perf_events
```
**Symbols:**

```
ffffffff81006860-ffffffff81006ae5: x86_pmu_static_call_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void x86_pmu_static_call_update();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006000)
Location: arch/x86/events/core.c:2001
Inline: False
Direct callers:
  - arch/x86/events/core.c:init_hw_perf_events
```
**Symbols:**

```
ffffffff81006000-ffffffff81006285: x86_pmu_static_call_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void x86_pmu_static_call_update();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff8100b700)
Location: arch/x86/events/core.c:1999
Inline: False
Direct callers:
  - arch/x86/events/core.c:init_hw_perf_events
```
**Symbols:**

```
ffffffff8100b700-ffffffff8100b985: x86_pmu_static_call_update (STB_LOCAL)
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
