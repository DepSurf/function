# Function: <code>uncore_assign_hw_event</code>

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
In arch/x86/events/intel/uncore.c (ffffffff81016e72)
Location: arch/x86/events/intel/uncore.c:210
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
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
In arch/x86/events/intel/uncore.c (ffffffff810160d6)
Location: arch/x86/events/intel/uncore.c:192
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
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
In arch/x86/events/intel/uncore.c (ffffffff81016292)
Location: arch/x86/events/intel/uncore.c:198
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
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
In arch/x86/events/intel/uncore.c (ffffffff81014720)
Location: arch/x86/events/intel/uncore.c:198
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
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
In arch/x86/events/intel/uncore.c (ffffffff81014f80)
Location: arch/x86/events/intel/uncore.c:198
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
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
In arch/x86/events/intel/uncore.c (ffffffff81015b17)
Location: arch/x86/events/intel/uncore.c:198
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
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
In arch/x86/events/intel/uncore.c (ffffffff81016237)
Location: arch/x86/events/intel/uncore.c:198
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
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
In arch/x86/events/intel/uncore.c (ffffffff81017827)
Location: arch/x86/events/intel/uncore.c:215
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
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
In arch/x86/events/intel/uncore.c (ffffffff810181b7)
Location: arch/x86/events/intel/uncore.c:215
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void uncore_assign_hw_event(struct intel_uncore_box *box, struct perf_event *event, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81018e90)
Location: arch/x86/events/intel/uncore.c:215
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
```
**Symbols:**

```
ffffffff81018e90-ffffffff810190d1: uncore_assign_hw_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void uncore_assign_hw_event(struct intel_uncore_box *box, struct perf_event *event, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81019610)
Location: arch/x86/events/intel/uncore.c:220
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
```
**Symbols:**

```
ffffffff81019610-ffffffff81019853: uncore_assign_hw_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void uncore_assign_hw_event(struct intel_uncore_box *box, struct perf_event *event, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff8101a930)
Location: arch/x86/events/intel/uncore.c:237
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
```
**Symbols:**

```
ffffffff8101a930-ffffffff8101ab77: uncore_assign_hw_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void uncore_assign_hw_event(struct intel_uncore_box *box, struct perf_event *event, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff8101d2f0)
Location: arch/x86/events/intel/uncore.c:237
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
```
**Symbols:**

```
ffffffff8101d2f0-ffffffff8101d56c: uncore_assign_hw_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void uncore_assign_hw_event(struct intel_uncore_box *box, struct perf_event *event, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff8101fc40)
Location: arch/x86/events/intel/uncore.c:237
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
```
**Symbols:**

```
ffffffff8101fc40-ffffffff8101fee0: uncore_assign_hw_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void uncore_assign_hw_event(struct intel_uncore_box *box, struct perf_event *event, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff810244a0)
Location: arch/x86/events/intel/uncore.c:237
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
```
**Symbols:**

```
ffffffff810244a0-ffffffff81024740: uncore_assign_hw_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void uncore_assign_hw_event(struct intel_uncore_box *box, struct perf_event *event, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81024200)
Location: arch/x86/events/intel/uncore.c:252
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
```
**Symbols:**

```
ffffffff81024200-ffffffff810244a0: uncore_assign_hw_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void uncore_assign_hw_event(struct intel_uncore_box *box, struct perf_event *event, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff8102a330)
Location: arch/x86/events/intel/uncore.c:252
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
```
**Symbols:**

```
ffffffff8102a330-ffffffff8102a5d0: uncore_assign_hw_event (STB_LOCAL)
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
In arch/x86/events/intel/uncore.c (ffffffff810181b7)
Location: arch/x86/events/intel/uncore.c:215
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
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
In arch/x86/events/intel/uncore.c (ffffffff810175e7)
Location: arch/x86/events/intel/uncore.c:215
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
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
In arch/x86/events/intel/uncore.c (ffffffff81018177)
Location: arch/x86/events/intel/uncore.c:215
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
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
In arch/x86/events/intel/uncore.c (ffffffff810183b7)
Location: arch/x86/events/intel/uncore.c:215
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
```
</details>
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
