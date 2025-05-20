# Function: <code>trace_event_get_offsets_prq_report</code>

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
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/trace.c (ffffffff81820019)
Location: include/trace/events/intel_iommu.h:57
Inline: True
Inline callers:
  - drivers/iommu/intel/trace.c:perf_trace_prq_report
  - drivers/iommu/intel/trace.c:trace_event_raw_event_prq_report
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/trace.c (0)
Location: include/trace/events/intel_iommu.h:57
Inline: True
Direct callers:
  - drivers/iommu/intel/trace.c:perf_trace_prq_report
  - drivers/iommu/intel/trace.c:trace_event_raw_event_prq_report
```
**Symbols:**

```
ffffffff8195f870-ffffffff8195f91f: trace_event_get_offsets_prq_report.constprop.0 (STB_LOCAL)
ffffffff81ec89ab-ffffffff81ec89c3: trace_event_get_offsets_prq_report.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/trace.c (ffffffff81ac7500)
Location: drivers/iommu/intel/trace.h:58
Inline: True
Direct callers:
  - drivers/iommu/intel/trace.c:perf_trace_prq_report
  - drivers/iommu/intel/trace.c:trace_event_raw_event_prq_report
```
**Symbols:**

```
ffffffff81ac7500-ffffffff81ac75c4: trace_event_get_offsets_prq_report.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/trace.c (ffffffff81b14270)
Location: drivers/iommu/intel/trace.h:58
Inline: True
Direct callers:
  - drivers/iommu/intel/trace.c:perf_trace_prq_report
  - drivers/iommu/intel/trace.c:trace_event_raw_event_prq_report
```
**Symbols:**

```
ffffffff81b14270-ffffffff81b1433e: trace_event_get_offsets_prq_report.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/trace.c (ffffffff81b69bb0)
Location: drivers/iommu/intel/trace.h:58
Inline: True
Direct callers:
  - drivers/iommu/intel/trace.c:perf_trace_prq_report
  - drivers/iommu/intel/trace.c:trace_event_raw_event_prq_report
```
**Symbols:**

```
ffffffff81b69bb0-ffffffff81b69c7e: trace_event_get_offsets_prq_report.isra.0 (STB_LOCAL)
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
