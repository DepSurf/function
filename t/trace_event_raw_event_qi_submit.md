# Function: <code>trace_event_raw_event_qi_submit</code>

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
void trace_event_raw_event_qi_submit(void *__data, struct intel_iommu *iommu, u64 qw0, u64 qw1, u64 qw2, u64 qw3);
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
ffffffff81797660-ffffffff8179784d: trace_event_raw_event_qi_submit (STB_LOCAL)
ffffffff81bfe627-ffffffff81bfe63f: trace_event_raw_event_qi_submit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void trace_event_raw_event_qi_submit(void *__data, struct intel_iommu *iommu, u64 qw0, u64 qw1, u64 qw2, u64 qw3);
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
ffffffff8181fdf0-ffffffff8181ffdd: trace_event_raw_event_qi_submit (STB_LOCAL)
ffffffff81d004f3-ffffffff81d0050b: trace_event_raw_event_qi_submit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void trace_event_raw_event_qi_submit(void *__data, struct intel_iommu *iommu, u64 qw0, u64 qw1, u64 qw2, u64 qw3);
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
ffffffff819601b0-ffffffff81960399: trace_event_raw_event_qi_submit (STB_LOCAL)
ffffffff81ec8a0b-ffffffff81ec8a23: trace_event_raw_event_qi_submit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void trace_event_raw_event_qi_submit(void *__data, struct intel_iommu *iommu, u64 qw0, u64 qw1, u64 qw2, u64 qw3);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/trace.c (ffffffff81ac7ef0)
Location: drivers/iommu/intel/trace.h:21
Inline: False
```
**Symbols:**

```
ffffffff81ac7ef0-ffffffff81ac80f0: trace_event_raw_event_qi_submit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void trace_event_raw_event_qi_submit(void *__data, struct intel_iommu *iommu, u64 qw0, u64 qw1, u64 qw2, u64 qw3);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/trace.c (ffffffff81b14ae0)
Location: drivers/iommu/intel/trace.h:21
Inline: False
```
**Symbols:**

```
ffffffff81b14ae0-ffffffff81b14d1d: trace_event_raw_event_qi_submit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void trace_event_raw_event_qi_submit(void *__data, struct intel_iommu *iommu, u64 qw0, u64 qw1, u64 qw2, u64 qw3);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/trace.c (ffffffff81b6a420)
Location: drivers/iommu/intel/trace.h:21
Inline: False
```
**Symbols:**

```
ffffffff81b6a420-ffffffff81b6a65d: trace_event_raw_event_qi_submit (STB_LOCAL)
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
