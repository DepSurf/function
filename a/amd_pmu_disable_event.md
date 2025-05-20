# Function: <code>amd_pmu_disable_event</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void amd_pmu_disable_event(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff81008c50)
Location: arch/x86/events/amd/core.c:616
Inline: False
```
**Symbols:**

```
ffffffff81008c50-ffffffff81008c93: amd_pmu_disable_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void amd_pmu_disable_event(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff81008f70)
Location: arch/x86/events/amd/core.c:637
Inline: False
```
**Symbols:**

```
ffffffff81008f70-ffffffff81008ff7: amd_pmu_disable_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void amd_pmu_disable_event(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff8100a660)
Location: arch/x86/events/amd/core.c:637
Inline: False
```
**Symbols:**

```
ffffffff8100a660-ffffffff8100a6e9: amd_pmu_disable_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void amd_pmu_disable_event(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff810094e0)
Location: arch/x86/events/amd/core.c:637
Inline: False
```
**Symbols:**

```
ffffffff810094e0-ffffffff81009569: amd_pmu_disable_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void amd_pmu_disable_event(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff81009ea0)
Location: arch/x86/events/amd/core.c:637
Inline: False
```
**Symbols:**

```
ffffffff81009ea0-ffffffff81009f36: amd_pmu_disable_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void amd_pmu_disable_event(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff8100afb0)
Location: arch/x86/events/amd/core.c:637
Inline: False
```
**Symbols:**

```
ffffffff8100afb0-ffffffff8100b046: amd_pmu_disable_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void amd_pmu_disable_event(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff8100ad80)
Location: arch/x86/events/amd/core.c:807
Inline: True
```
**Symbols:**

```
ffffffff8100ad80-ffffffff8100ae6e: amd_pmu_disable_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void amd_pmu_disable_event(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff8100cbf0)
Location: arch/x86/events/amd/core.c:763
Inline: True
```
**Symbols:**

```
ffffffff8100cbf0-ffffffff8100ccde: amd_pmu_disable_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void amd_pmu_disable_event(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff8100c3b0)
Location: arch/x86/events/amd/core.c:763
Inline: True
```
**Symbols:**

```
ffffffff8100c3b0-ffffffff8100c49e: amd_pmu_disable_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void amd_pmu_disable_event(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff81011b90)
Location: arch/x86/events/amd/core.c:765
Inline: True
```
**Symbols:**

```
ffffffff81011b90-ffffffff81011c7e: amd_pmu_disable_event (STB_LOCAL)
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
void amd_pmu_disable_event(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff81008f70)
Location: arch/x86/events/amd/core.c:637
Inline: False
```
**Symbols:**

```
ffffffff81008f70-ffffffff81008ff7: amd_pmu_disable_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void amd_pmu_disable_event(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff81007ce0)
Location: arch/x86/events/amd/core.c:637
Inline: False
```
**Symbols:**

```
ffffffff81007ce0-ffffffff81007d84: amd_pmu_disable_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void amd_pmu_disable_event(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff81008f30)
Location: arch/x86/events/amd/core.c:637
Inline: False
```
**Symbols:**

```
ffffffff81008f30-ffffffff81008fb7: amd_pmu_disable_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void amd_pmu_disable_event(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff81009090)
Location: arch/x86/events/amd/core.c:637
Inline: False
```
**Symbols:**

```
ffffffff81009090-ffffffff81009117: amd_pmu_disable_event (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
