# Function: <code>intel_pmu_arch_lbr_read_xsave</code>

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
void intel_pmu_arch_lbr_read_xsave(struct cpu_hw_events *cpuc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff81013ef0)
Location: arch/x86/events/intel/lbr.c:972
Inline: False
```
**Symbols:**

```
ffffffff81013ef0-ffffffff81013f39: intel_pmu_arch_lbr_read_xsave (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void intel_pmu_arch_lbr_read_xsave(struct cpu_hw_events *cpuc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff810150b0)
Location: arch/x86/events/intel/lbr.c:988
Inline: False
```
**Symbols:**

```
ffffffff810150b0-ffffffff810150f9: intel_pmu_arch_lbr_read_xsave (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void intel_pmu_arch_lbr_read_xsave(struct cpu_hw_events *cpuc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff810166e0)
Location: arch/x86/events/intel/lbr.c:988
Inline: False
```
**Symbols:**

```
ffffffff810166e0-ffffffff81016729: intel_pmu_arch_lbr_read_xsave (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void intel_pmu_arch_lbr_read_xsave(struct cpu_hw_events *cpuc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff81018900)
Location: arch/x86/events/intel/lbr.c:971
Inline: True
```
**Symbols:**

```
ffffffff81018900-ffffffff81018959: intel_pmu_arch_lbr_read_xsave (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void intel_pmu_arch_lbr_read_xsave(struct cpu_hw_events *cpuc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff8101c770)
Location: arch/x86/events/intel/lbr.c:911
Inline: True
```
**Symbols:**

```
ffffffff8101c770-ffffffff8101c7c9: intel_pmu_arch_lbr_read_xsave (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void intel_pmu_arch_lbr_read_xsave(struct cpu_hw_events *cpuc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff8101c430)
Location: arch/x86/events/intel/lbr.c:911
Inline: True
```
**Symbols:**

```
ffffffff8101c430-ffffffff8101c489: intel_pmu_arch_lbr_read_xsave (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void intel_pmu_arch_lbr_read_xsave(struct cpu_hw_events *cpuc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff810223c0)
Location: arch/x86/events/intel/lbr.c:988
Inline: True
```
**Symbols:**

```
ffffffff810223c0-ffffffff81022419: intel_pmu_arch_lbr_read_xsave (STB_LOCAL)
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
