# Function: <code>iommu_queue_iopf</code>

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
int iommu_queue_iopf(struct iommu_fault *fault, void *cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/io-pgfault.c (ffffffff818301e0)
Location: drivers/iommu/io-pgfault.c:186
Inline: False
```
**Symbols:**

```
ffffffff818301e0-ffffffff8183044c: iommu_queue_iopf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int iommu_queue_iopf(struct iommu_fault *fault, void *cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/io-pgfault.c (ffffffff81971470)
Location: drivers/iommu/io-pgfault.c:186
Inline: False
```
**Symbols:**

```
ffffffff81971470-ffffffff8197170b: iommu_queue_iopf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int iommu_queue_iopf(struct iommu_fault *fault, void *cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/io-pgfault.c (ffffffff81adc5b0)
Location: drivers/iommu/io-pgfault.c:143
Inline: False
```
**Symbols:**

```
ffffffff81adc5b0-ffffffff81adc84b: iommu_queue_iopf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int iommu_queue_iopf(struct iommu_fault *fault, void *cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/io-pgfault.c (ffffffff81b2a820)
Location: drivers/iommu/io-pgfault.c:143
Inline: False
```
**Symbols:**

```
ffffffff81b2a820-ffffffff81b2aaba: iommu_queue_iopf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int iommu_queue_iopf(struct iommu_fault *fault, void *cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/io-pgfault.c (ffffffff81b81a50)
Location: drivers/iommu/io-pgfault.c:143
Inline: False
```
**Symbols:**

```
ffffffff81b81a50-ffffffff81b81d3e: iommu_queue_iopf (STB_GLOBAL)
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
