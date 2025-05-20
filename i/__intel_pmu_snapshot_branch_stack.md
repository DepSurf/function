# Function: <code>__intel_pmu_snapshot_branch_stack</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __intel_pmu_snapshot_branch_stack(struct perf_branch_entry *entries, unsigned int cnt, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100fd80)
Location: arch/x86/events/intel/core.c:2213
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_snapshot_arch_branch_stack
  - arch/x86/events/intel/core.c:intel_pmu_snapshot_branch_stack
```
**Symbols:**

```
ffffffff8100fd80-ffffffff8100fe01: __intel_pmu_snapshot_branch_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __intel_pmu_snapshot_branch_stack(struct perf_branch_entry *entries, unsigned int cnt, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff81013df0)
Location: arch/x86/events/intel/core.c:2229
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_snapshot_arch_branch_stack
  - arch/x86/events/intel/core.c:intel_pmu_snapshot_branch_stack
```
**Symbols:**

```
ffffffff81013df0-ffffffff81013e77: __intel_pmu_snapshot_branch_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __intel_pmu_snapshot_branch_stack(struct perf_branch_entry *entries, unsigned int cnt, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff81013650)
Location: arch/x86/events/intel/core.c:2249
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_snapshot_arch_branch_stack
  - arch/x86/events/intel/core.c:intel_pmu_snapshot_branch_stack
```
**Symbols:**

```
ffffffff81013650-ffffffff810136d7: __intel_pmu_snapshot_branch_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __intel_pmu_snapshot_branch_stack(struct perf_branch_entry *entries, unsigned int cnt, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff81018ce0)
Location: arch/x86/events/intel/core.c:2269
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_snapshot_arch_branch_stack
  - arch/x86/events/intel/core.c:intel_pmu_snapshot_branch_stack
```
**Symbols:**

```
ffffffff81018ce0-ffffffff81018d67: __intel_pmu_snapshot_branch_stack (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
