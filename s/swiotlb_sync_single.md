# Function: <code>swiotlb_sync_single</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void swiotlb_sync_single(struct device *hwdev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir, enum dma_sync_target target);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/swiotlb.c (ffffffff81412930)
Location: lib/swiotlb.c:827
Inline: True
Direct callers:
  - lib/swiotlb.c:swiotlb_sync_single_for_cpu
  - lib/swiotlb.c:swiotlb_sync_single_for_device
  - lib/swiotlb.c:swiotlb_sync_sg_for_device
  - lib/swiotlb.c:swiotlb_sync_sg_for_cpu
```
**Symbols:**

```
ffffffff81412930-ffffffff81412955: swiotlb_sync_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void swiotlb_sync_single(struct device *hwdev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir, enum dma_sync_target target);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/swiotlb.c (ffffffff8145a660)
Location: lib/swiotlb.c:827
Inline: True
Direct callers:
  - lib/swiotlb.c:swiotlb_sync_sg_for_device
  - lib/swiotlb.c:swiotlb_sync_sg_for_cpu
  - lib/swiotlb.c:swiotlb_sync_single_for_device
  - lib/swiotlb.c:swiotlb_sync_single_for_cpu
```
**Symbols:**

```
ffffffff8145a660-ffffffff8145a685: swiotlb_sync_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void swiotlb_sync_single(struct device *hwdev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir, enum dma_sync_target target);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/swiotlb.c (ffffffff81479220)
Location: lib/swiotlb.c:883
Inline: True
Direct callers:
  - lib/swiotlb.c:swiotlb_sync_sg_for_device
  - lib/swiotlb.c:swiotlb_sync_sg_for_cpu
  - lib/swiotlb.c:swiotlb_sync_single_for_device
  - lib/swiotlb.c:swiotlb_sync_single_for_cpu
```
**Symbols:**

```
ffffffff81479220-ffffffff81479245: swiotlb_sync_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void swiotlb_sync_single(struct device *hwdev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir, enum dma_sync_target target);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/swiotlb.c (ffffffff81482400)
Location: lib/swiotlb.c:883
Inline: True
Direct callers:
  - lib/swiotlb.c:swiotlb_sync_sg_for_device
  - lib/swiotlb.c:swiotlb_sync_sg_for_cpu
  - lib/swiotlb.c:swiotlb_sync_single_for_device
  - lib/swiotlb.c:swiotlb_sync_single_for_cpu
```
**Symbols:**

```
ffffffff81482400-ffffffff81482426: swiotlb_sync_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void swiotlb_sync_single(struct device *hwdev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir, enum dma_sync_target target);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/swiotlb.c (ffffffff814be580)
Location: lib/swiotlb.c:928
Inline: True
Direct callers:
  - lib/swiotlb.c:swiotlb_sync_sg_for_device
  - lib/swiotlb.c:swiotlb_sync_sg_for_cpu
  - lib/swiotlb.c:swiotlb_sync_single_for_device
  - lib/swiotlb.c:swiotlb_sync_single_for_cpu
```
**Symbols:**

```
ffffffff814be580-ffffffff814be5b3: swiotlb_sync_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void swiotlb_sync_single(struct device *hwdev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir, enum dma_sync_target target);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff8110e640)
Location: kernel/dma/swiotlb.c:890
Inline: True
Direct callers:
  - kernel/dma/swiotlb.c:swiotlb_sync_sg_for_device
  - kernel/dma/swiotlb.c:swiotlb_sync_sg_for_cpu
  - kernel/dma/swiotlb.c:swiotlb_sync_single_for_device
  - kernel/dma/swiotlb.c:swiotlb_sync_single_for_cpu
```
**Symbols:**

```
ffffffff8110e640-ffffffff8110e684: swiotlb_sync_single (STB_LOCAL)
```
</details>
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
</ul>
