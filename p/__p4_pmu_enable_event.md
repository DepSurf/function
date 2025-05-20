# Function: <code>__p4_pmu_enable_event</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __p4_pmu_enable_event(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/p4.c (ffffffff81016940)
Location: arch/x86/events/intel/p4.c:950
Inline: False
Direct callers:
  - arch/x86/events/intel/p4.c:p4_pmu_enable_all
  - arch/x86/events/intel/p4.c:p4_pmu_enable_event
```
**Symbols:**

```
ffffffff81016940-ffffffff81016a44: __p4_pmu_enable_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __p4_pmu_enable_event(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/p4.c (ffffffff81018450)
Location: arch/x86/events/intel/p4.c:950
Inline: False
Direct callers:
  - arch/x86/events/intel/p4.c:p4_pmu_enable_all
  - arch/x86/events/intel/p4.c:p4_pmu_enable_event
```
**Symbols:**

```
ffffffff81018450-ffffffff81018590: __p4_pmu_enable_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __p4_pmu_enable_event(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/p4.c (ffffffff8101a5e0)
Location: arch/x86/events/intel/p4.c:950
Inline: False
Direct callers:
  - arch/x86/events/intel/p4.c:p4_pmu_enable_all
  - arch/x86/events/intel/p4.c:p4_pmu_enable_event
```
**Symbols:**

```
ffffffff8101a5e0-ffffffff8101a739: __p4_pmu_enable_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __p4_pmu_enable_event(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/p4.c (ffffffff8101e720)
Location: arch/x86/events/intel/p4.c:950
Inline: False
Direct callers:
  - arch/x86/events/intel/p4.c:p4_pmu_enable_all
  - arch/x86/events/intel/p4.c:p4_pmu_enable_event
```
**Symbols:**

```
ffffffff8101e720-ffffffff8101e879: __p4_pmu_enable_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __p4_pmu_enable_event(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/p4.c (ffffffff8101e410)
Location: arch/x86/events/intel/p4.c:950
Inline: False
Direct callers:
  - arch/x86/events/intel/p4.c:p4_pmu_enable_all
  - arch/x86/events/intel/p4.c:p4_pmu_enable_event
```
**Symbols:**

```
ffffffff8101e410-ffffffff8101e570: __p4_pmu_enable_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __p4_pmu_enable_event(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/p4.c (ffffffff81024860)
Location: arch/x86/events/intel/p4.c:950
Inline: False
Direct callers:
  - arch/x86/events/intel/p4.c:p4_pmu_enable_all
  - arch/x86/events/intel/p4.c:p4_pmu_enable_event
```
**Symbols:**

```
ffffffff81024860-ffffffff810249c0: __p4_pmu_enable_event (STB_LOCAL)
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
