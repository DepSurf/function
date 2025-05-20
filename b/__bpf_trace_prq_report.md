# Function: <code>__bpf_trace_prq_report</code>

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
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __bpf_trace_prq_report(void *__data, struct intel_iommu *iommu, struct device *dev, u64 dw0, u64 dw1, u64 dw2, u64 dw3, long unsigned int seq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/trace.c (ffffffff8181f740)
Location: include/trace/events/intel_iommu.h:57
Inline: False
```
**Symbols:**

```
ffffffff8181f740-ffffffff8181f753: __bpf_trace_prq_report (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __bpf_trace_prq_report(void *__data, struct intel_iommu *iommu, struct device *dev, u64 dw0, u64 dw1, u64 dw2, u64 dw3, long unsigned int seq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/trace.c (ffffffff8195f840)
Location: include/trace/events/intel_iommu.h:57
Inline: False
```
**Symbols:**

```
ffffffff8195f840-ffffffff8195f867: __bpf_trace_prq_report (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __bpf_trace_prq_report(void *__data, struct intel_iommu *iommu, struct device *dev, u64 dw0, u64 dw1, u64 dw2, u64 dw3, long unsigned int seq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/trace.c (ffffffff81ac74c0)
Location: drivers/iommu/intel/trace.h:58
Inline: False
```
**Symbols:**

```
ffffffff81ac74c0-ffffffff81ac74e7: __bpf_trace_prq_report (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __bpf_trace_prq_report(void *__data, struct intel_iommu *iommu, struct device *dev, u64 dw0, u64 dw1, u64 dw2, u64 dw3, long unsigned int seq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/trace.c (ffffffff81b14070)
Location: drivers/iommu/intel/trace.h:58
Inline: False
```
**Symbols:**

```
ffffffff81b14070-ffffffff81b14097: __bpf_trace_prq_report (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __bpf_trace_prq_report(void *__data, struct intel_iommu *iommu, struct device *dev, u64 dw0, u64 dw1, u64 dw2, u64 dw3, long unsigned int seq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/trace.c (ffffffff81b699b0)
Location: drivers/iommu/intel/trace.h:58
Inline: False
```
**Symbols:**

```
ffffffff81b699b0-ffffffff81b699d7: __bpf_trace_prq_report (STB_LOCAL)
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
