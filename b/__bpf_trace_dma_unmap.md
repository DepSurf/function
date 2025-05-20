# Function: <code>__bpf_trace_dma_unmap</code>

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
void __bpf_trace_dma_unmap(void *__data, struct device *dev, dma_addr_t dev_addr, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-trace.c (ffffffff816f0e20)
Location: include/trace/events/intel_iommu.h:64
Inline: False
```
**Symbols:**

```
ffffffff816f0e20-ffffffff816f0e2b: __bpf_trace_dma_unmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __bpf_trace_dma_unmap(void *__data, struct device *dev, dma_addr_t dev_addr, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/trace.c (ffffffff817a8940)
Location: include/trace/events/intel_iommu.h:58
Inline: False
```
**Symbols:**

```
ffffffff817a8940-ffffffff817a894b: __bpf_trace_dma_unmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __bpf_trace_dma_unmap(void *__data, struct device *dev, dma_addr_t dev_addr, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/trace.c (ffffffff817b4860)
Location: include/trace/events/intel_iommu.h:58
Inline: False
```
**Symbols:**

```
ffffffff817b4860-ffffffff817b486b: __bpf_trace_dma_unmap (STB_LOCAL)
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
void __bpf_trace_dma_unmap(void *__data, struct device *dev, dma_addr_t dev_addr, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-trace.c (ffffffff816b6610)
Location: include/trace/events/intel_iommu.h:64
Inline: False
```
**Symbols:**

```
ffffffff816b6610-ffffffff816b661b: __bpf_trace_dma_unmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __bpf_trace_dma_unmap(void *__data, struct device *dev, dma_addr_t dev_addr, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-trace.c (ffffffff81694250)
Location: include/trace/events/intel_iommu.h:64
Inline: False
```
**Symbols:**

```
ffffffff81694250-ffffffff8169425b: __bpf_trace_dma_unmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __bpf_trace_dma_unmap(void *__data, struct device *dev, dma_addr_t dev_addr, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-trace.c (ffffffff816e4ae0)
Location: include/trace/events/intel_iommu.h:64
Inline: False
```
**Symbols:**

```
ffffffff816e4ae0-ffffffff816e4aeb: __bpf_trace_dma_unmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __bpf_trace_dma_unmap(void *__data, struct device *dev, dma_addr_t dev_addr, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-trace.c (ffffffff816ff1a0)
Location: include/trace/events/intel_iommu.h:64
Inline: False
```
**Symbols:**

```
ffffffff816ff1a0-ffffffff816ff1ab: __bpf_trace_dma_unmap (STB_LOCAL)
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
