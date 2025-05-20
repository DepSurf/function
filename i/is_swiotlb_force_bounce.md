# Function: <code>is_swiotlb_force_bounce</code>

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
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff8115bd07)
Location: include/linux/swiotlb.h:117
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_direct_map_page
```
```
In kernel/dma/direct.c (ffffffff8115d903)
Location: include/linux/swiotlb.h:117
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_max_mapping_size
  - kernel/dma/direct.c:dma_direct_map_page
```
```
In drivers/xen/swiotlb-xen.c (ffffffff817a3a8b)
Location: include/linux/swiotlb.h:117
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811858f8)
Location: include/linux/swiotlb.h:120
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_direct_map_page
```
```
In kernel/dma/direct.c (ffffffff8118789b)
Location: include/linux/swiotlb.h:120
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_max_mapping_size
  - kernel/dma/direct.c:dma_direct_map_page
```
```
In kernel/dma/swiotlb.c (ffffffff811883c0)
Location: include/linux/swiotlb.h:120
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:perf_trace_swiotlb_bounced
  - kernel/dma/swiotlb.c:trace_event_raw_event_swiotlb_bounced
```
```
In drivers/xen/swiotlb-xen.c (ffffffff818ddde7)
Location: include/linux/swiotlb.h:120
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811c126d)
Location: include/linux/swiotlb.h:115
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_direct_map_page
```
```
In kernel/dma/direct.c (ffffffff811c349b)
Location: include/linux/swiotlb.h:115
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_max_mapping_size
  - kernel/dma/direct.c:dma_direct_map_page
```
```
In kernel/dma/swiotlb.c (ffffffff811c42bd)
Location: include/linux/swiotlb.h:115
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:perf_trace_swiotlb_bounced
  - kernel/dma/swiotlb.c:trace_event_raw_event_swiotlb_bounced
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81a312d4)
Location: include/linux/swiotlb.h:115
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811d3ced)
Location: include/linux/swiotlb.h:122
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_direct_map_page
```
```
In kernel/dma/direct.c (ffffffff811d5feb)
Location: include/linux/swiotlb.h:122
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_max_mapping_size
  - kernel/dma/direct.c:dma_direct_map_page
```
```
In kernel/dma/swiotlb.c (ffffffff811d745d)
Location: include/linux/swiotlb.h:122
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:perf_trace_swiotlb_bounced
  - kernel/dma/swiotlb.c:trace_event_raw_event_swiotlb_bounced
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81a7aae4)
Location: include/linux/swiotlb.h:122
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811e898d)
Location: include/linux/swiotlb.h:194
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_direct_map_page
```
```
In kernel/dma/direct.c (ffffffff811eafaf)
Location: include/linux/swiotlb.h:194
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_max_mapping_size
  - kernel/dma/direct.c:dma_direct_map_page
```
```
In kernel/dma/swiotlb.c (ffffffff811ec40d)
Location: include/linux/swiotlb.h:194
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:perf_trace_swiotlb_bounced
  - kernel/dma/swiotlb.c:trace_event_raw_event_swiotlb_bounced
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81accc4d)
Location: include/linux/swiotlb.h:194
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_page
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
