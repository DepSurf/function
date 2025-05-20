# Function: <code>intel_pmu_store_lbr</code>

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
void intel_pmu_store_lbr(struct cpu_hw_events *cpuc, struct lbr_entry *entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff81013c90)
Location: arch/x86/events/intel/lbr.c:931
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_store_pebs_lbrs
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_read_xsave
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_read_xsave
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_read
```
**Symbols:**

```
ffffffff81013c90-ffffffff81013ec9: intel_pmu_store_lbr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void intel_pmu_store_lbr(struct cpu_hw_events *cpuc, struct lbr_entry *entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff81014e50)
Location: arch/x86/events/intel/lbr.c:947
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_store_pebs_lbrs
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_read_xsave
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_read_xsave
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_read
```
**Symbols:**

```
ffffffff81014e50-ffffffff8101508c: intel_pmu_store_lbr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void intel_pmu_store_lbr(struct cpu_hw_events *cpuc, struct lbr_entry *entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff81016460)
Location: arch/x86/events/intel/lbr.c:947
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_store_pebs_lbrs
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_read_xsave
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_read_xsave
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_read
```
**Symbols:**

```
ffffffff81016460-ffffffff810166be: intel_pmu_store_lbr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void intel_pmu_store_lbr(struct cpu_hw_events *cpuc, struct lbr_entry *entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff810186a0)
Location: arch/x86/events/intel/lbr.c:929
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_store_pebs_lbrs
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_read
```
**Symbols:**

```
ffffffff810186a0-ffffffff810188e0: intel_pmu_store_lbr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void intel_pmu_store_lbr(struct cpu_hw_events *cpuc, struct lbr_entry *entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff8101c4e0)
Location: arch/x86/events/intel/lbr.c:869
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_store_pebs_lbrs
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_read
```
**Symbols:**

```
ffffffff8101c4e0-ffffffff8101c726: intel_pmu_store_lbr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void intel_pmu_store_lbr(struct cpu_hw_events *cpuc, struct lbr_entry *entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff8101c1a0)
Location: arch/x86/events/intel/lbr.c:869
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_store_pebs_lbrs
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_read
```
**Symbols:**

```
ffffffff8101c1a0-ffffffff8101c3e5: intel_pmu_store_lbr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void intel_pmu_store_lbr(struct cpu_hw_events *cpuc, struct lbr_entry *entries);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff81022120)
Location: arch/x86/events/intel/lbr.c:890
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_store_pebs_lbrs
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_read
```
**Symbols:**

```
ffffffff81022120-ffffffff8102237e: intel_pmu_store_lbr (STB_LOCAL)
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
