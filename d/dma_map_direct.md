# Function: <code>dma_map_direct</code>

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
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81137c69)
Location: kernel/dma/mapping.c:134
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_need_sync
  - kernel/dma/mapping.c:dma_max_mapping_size
  - kernel/dma/mapping.c:dma_sync_sg_for_device
  - kernel/dma/mapping.c:dma_sync_sg_for_cpu
  - kernel/dma/mapping.c:dma_sync_single_for_device
  - kernel/dma/mapping.c:dma_sync_single_for_cpu
  - kernel/dma/mapping.c:dma_map_resource
  - kernel/dma/mapping.c:dma_unmap_sg_attrs
  - kernel/dma/mapping.c:dma_map_sg_attrs
  - kernel/dma/mapping.c:dma_unmap_page_attrs
  - kernel/dma/mapping.c:dma_map_page_attrs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81138ca5)
Location: kernel/dma/mapping.c:136
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_need_sync
  - kernel/dma/mapping.c:dma_max_mapping_size
  - kernel/dma/mapping.c:dma_sync_sg_for_device
  - kernel/dma/mapping.c:dma_sync_sg_for_cpu
  - kernel/dma/mapping.c:dma_sync_single_for_device
  - kernel/dma/mapping.c:dma_sync_single_for_cpu
  - kernel/dma/mapping.c:dma_map_resource
  - kernel/dma/mapping.c:dma_unmap_sg_attrs
  - kernel/dma/mapping.c:dma_map_sg_attrs
  - kernel/dma/mapping.c:dma_unmap_page_attrs
  - kernel/dma/mapping.c:dma_map_page_attrs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff8115bbb5)
Location: kernel/dma/mapping.c:136
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_need_sync
  - kernel/dma/mapping.c:dma_max_mapping_size
  - kernel/dma/mapping.c:dma_sync_sg_for_device
  - kernel/dma/mapping.c:dma_sync_sg_for_cpu
  - kernel/dma/mapping.c:dma_sync_single_for_device
  - kernel/dma/mapping.c:dma_sync_single_for_cpu
  - kernel/dma/mapping.c:dma_unmap_resource
  - kernel/dma/mapping.c:dma_map_resource
  - kernel/dma/mapping.c:dma_unmap_sg_attrs
  - kernel/dma/mapping.c:__dma_map_sg_attrs
  - kernel/dma/mapping.c:dma_unmap_page_attrs
  - kernel/dma/mapping.c:dma_map_page_attrs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff8118573f)
Location: kernel/dma/mapping.c:136
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_need_sync
  - kernel/dma/mapping.c:dma_max_mapping_size
  - kernel/dma/mapping.c:dma_sync_sg_for_device
  - kernel/dma/mapping.c:dma_sync_sg_for_cpu
  - kernel/dma/mapping.c:dma_sync_single_for_device
  - kernel/dma/mapping.c:dma_sync_single_for_cpu
  - kernel/dma/mapping.c:dma_unmap_resource
  - kernel/dma/mapping.c:dma_map_resource
  - kernel/dma/mapping.c:dma_unmap_sg_attrs
  - kernel/dma/mapping.c:__dma_map_sg_attrs
  - kernel/dma/mapping.c:dma_unmap_page_attrs
  - kernel/dma/mapping.c:dma_map_page_attrs
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811c108f)
Location: kernel/dma/mapping.c:137
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_need_sync
  - kernel/dma/mapping.c:dma_max_mapping_size
  - kernel/dma/mapping.c:dma_sync_sg_for_device
  - kernel/dma/mapping.c:dma_sync_sg_for_cpu
  - kernel/dma/mapping.c:dma_sync_single_for_device
  - kernel/dma/mapping.c:dma_sync_single_for_cpu
  - kernel/dma/mapping.c:dma_unmap_resource
  - kernel/dma/mapping.c:dma_map_resource
  - kernel/dma/mapping.c:dma_unmap_sg_attrs
  - kernel/dma/mapping.c:__dma_map_sg_attrs
  - kernel/dma/mapping.c:dma_unmap_page_attrs
  - kernel/dma/mapping.c:dma_map_page_attrs
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811d3aff)
Location: kernel/dma/mapping.c:141
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_need_sync
  - kernel/dma/mapping.c:dma_opt_mapping_size
  - kernel/dma/mapping.c:dma_sync_sg_for_device
  - kernel/dma/mapping.c:dma_sync_sg_for_cpu
  - kernel/dma/mapping.c:dma_sync_single_for_device
  - kernel/dma/mapping.c:dma_sync_single_for_cpu
  - kernel/dma/mapping.c:dma_unmap_resource
  - kernel/dma/mapping.c:dma_map_resource
  - kernel/dma/mapping.c:dma_unmap_sg_attrs
  - kernel/dma/mapping.c:__dma_map_sg_attrs
  - kernel/dma/mapping.c:dma_unmap_page_attrs
  - kernel/dma/mapping.c:dma_map_page_attrs
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811e879f)
Location: kernel/dma/mapping.c:141
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_need_sync
  - kernel/dma/mapping.c:dma_opt_mapping_size
  - kernel/dma/mapping.c:dma_sync_sg_for_device
  - kernel/dma/mapping.c:dma_sync_sg_for_cpu
  - kernel/dma/mapping.c:dma_sync_single_for_device
  - kernel/dma/mapping.c:dma_sync_single_for_cpu
  - kernel/dma/mapping.c:dma_unmap_resource
  - kernel/dma/mapping.c:dma_map_resource
  - kernel/dma/mapping.c:dma_unmap_sg_attrs
  - kernel/dma/mapping.c:__dma_map_sg_attrs
  - kernel/dma/mapping.c:dma_unmap_page_attrs
  - kernel/dma/mapping.c:dma_map_page_attrs
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
