# Function: <code>perf_trace_qi_submit</code>

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
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void perf_trace_qi_submit(void *__data, struct intel_iommu *iommu, u64 qw0, u64 qw1, u64 qw2, u64 qw3);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/trace.c (0)
Location: include/trace/events/intel_iommu.h:18
Inline: False
```
**Symbols:**

```
ffffffff81797850-ffffffff81797a76: perf_trace_qi_submit (STB_LOCAL)
ffffffff81bfe63f-ffffffff81bfe657: perf_trace_qi_submit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void perf_trace_qi_submit(void *__data, struct intel_iommu *iommu, u64 qw0, u64 qw1, u64 qw2, u64 qw3);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/trace.c (0)
Location: include/trace/events/intel_iommu.h:20
Inline: False
```
**Symbols:**

```
ffffffff8181fbc0-ffffffff8181fde6: perf_trace_qi_submit (STB_LOCAL)
ffffffff81d004db-ffffffff81d004f3: perf_trace_qi_submit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void perf_trace_qi_submit(void *__data, struct intel_iommu *iommu, u64 qw0, u64 qw1, u64 qw2, u64 qw3);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/trace.c (0)
Location: include/trace/events/intel_iommu.h:20
Inline: False
```
**Symbols:**

```
ffffffff8195fdb0-ffffffff8195ffff: perf_trace_qi_submit (STB_LOCAL)
ffffffff81ec89f3-ffffffff81ec8a0b: perf_trace_qi_submit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void perf_trace_qi_submit(void *__data, struct intel_iommu *iommu, u64 qw0, u64 qw1, u64 qw2, u64 qw3);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/trace.c (ffffffff81ac7ab0)
Location: drivers/iommu/intel/trace.h:21
Inline: False
```
**Symbols:**

```
ffffffff81ac7ab0-ffffffff81ac7d18: perf_trace_qi_submit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void perf_trace_qi_submit(void *__data, struct intel_iommu *iommu, u64 qw0, u64 qw1, u64 qw2, u64 qw3);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/trace.c (ffffffff81b14840)
Location: drivers/iommu/intel/trace.h:21
Inline: False
```
**Symbols:**

```
ffffffff81b14840-ffffffff81b14acd: perf_trace_qi_submit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void perf_trace_qi_submit(void *__data, struct intel_iommu *iommu, u64 qw0, u64 qw1, u64 qw2, u64 qw3);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/trace.c (ffffffff81b6a180)
Location: drivers/iommu/intel/trace.h:21
Inline: False
```
**Symbols:**

```
ffffffff81b6a180-ffffffff81b6a40d: perf_trace_qi_submit (STB_LOCAL)
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
