# Function: <code>intel_pmu_arch_lbr_read</code>

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
void intel_pmu_arch_lbr_read(struct cpu_hw_events *cpuc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff81013ed0)
Location: arch/x86/events/intel/lbr.c:967
Inline: False
```
**Symbols:**

```
ffffffff81013ed0-ffffffff81013ee2: intel_pmu_arch_lbr_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void intel_pmu_arch_lbr_read(struct cpu_hw_events *cpuc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff81015090)
Location: arch/x86/events/intel/lbr.c:983
Inline: False
```
**Symbols:**

```
ffffffff81015090-ffffffff810150a2: intel_pmu_arch_lbr_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void intel_pmu_arch_lbr_read(struct cpu_hw_events *cpuc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff810166c0)
Location: arch/x86/events/intel/lbr.c:983
Inline: False
```
**Symbols:**

```
ffffffff810166c0-ffffffff810166d2: intel_pmu_arch_lbr_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void intel_pmu_arch_lbr_read(struct cpu_hw_events *cpuc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff810188e0)
Location: arch/x86/events/intel/lbr.c:966
Inline: False
```
**Symbols:**

```
ffffffff810188e0-ffffffff810188fa: intel_pmu_arch_lbr_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void intel_pmu_arch_lbr_read(struct cpu_hw_events *cpuc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff8101c740)
Location: arch/x86/events/intel/lbr.c:906
Inline: False
```
**Symbols:**

```
ffffffff8101c740-ffffffff8101c75a: intel_pmu_arch_lbr_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void intel_pmu_arch_lbr_read(struct cpu_hw_events *cpuc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff8101c400)
Location: arch/x86/events/intel/lbr.c:906
Inline: False
```
**Symbols:**

```
ffffffff8101c400-ffffffff8101c41a: intel_pmu_arch_lbr_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void intel_pmu_arch_lbr_read(struct cpu_hw_events *cpuc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff81022390)
Location: arch/x86/events/intel/lbr.c:983
Inline: False
```
**Symbols:**

```
ffffffff81022390-ffffffff810223aa: intel_pmu_arch_lbr_read (STB_LOCAL)
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
