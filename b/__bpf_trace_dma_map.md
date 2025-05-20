# Function: <code>__bpf_trace_dma_map</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __bpf_trace_dma_map(void *__data, struct device *dev, dma_addr_t dev_addr, phys_addr_t phys_addr, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-trace.c (ffffffff816f0e10)
Location: include/trace/events/intel_iommu.h:19
Inline: False
```
**Symbols:**

```
ffffffff816f0e10-ffffffff816f0e1b: __bpf_trace_dma_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __bpf_trace_dma_map(void *__data, struct device *dev, dma_addr_t dev_addr, phys_addr_t phys_addr, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/trace.c (ffffffff817a8920)
Location: include/trace/events/intel_iommu.h:19
Inline: False
```
**Symbols:**

```
ffffffff817a8920-ffffffff817a892b: __bpf_trace_dma_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __bpf_trace_dma_map(void *__data, struct device *dev, dma_addr_t dev_addr, phys_addr_t phys_addr, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/trace.c (ffffffff817b4840)
Location: include/trace/events/intel_iommu.h:19
Inline: False
```
**Symbols:**

```
ffffffff817b4840-ffffffff817b484b: __bpf_trace_dma_map (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
<summary>In <code>aws</code>: ✅</summary>

```c
void __bpf_trace_dma_map(void *__data, struct device *dev, dma_addr_t dev_addr, phys_addr_t phys_addr, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-trace.c (ffffffff816b6600)
Location: include/trace/events/intel_iommu.h:19
Inline: False
```
**Symbols:**

```
ffffffff816b6600-ffffffff816b660b: __bpf_trace_dma_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __bpf_trace_dma_map(void *__data, struct device *dev, dma_addr_t dev_addr, phys_addr_t phys_addr, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-trace.c (ffffffff81694240)
Location: include/trace/events/intel_iommu.h:19
Inline: False
```
**Symbols:**

```
ffffffff81694240-ffffffff8169424b: __bpf_trace_dma_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __bpf_trace_dma_map(void *__data, struct device *dev, dma_addr_t dev_addr, phys_addr_t phys_addr, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-trace.c (ffffffff816e4ad0)
Location: include/trace/events/intel_iommu.h:19
Inline: False
```
**Symbols:**

```
ffffffff816e4ad0-ffffffff816e4adb: __bpf_trace_dma_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __bpf_trace_dma_map(void *__data, struct device *dev, dma_addr_t dev_addr, phys_addr_t phys_addr, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-trace.c (ffffffff816ff190)
Location: include/trace/events/intel_iommu.h:19
Inline: False
```
**Symbols:**

```
ffffffff816ff190-ffffffff816ff19b: __bpf_trace_dma_map (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
