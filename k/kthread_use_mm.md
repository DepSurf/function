# Function: <code>kthread_use_mm</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void kthread_use_mm(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810d1320)
Location: kernel/kthread.c:1245
Inline: False
Direct callers:
  - fs/io-wq.c:io_worker_handle_work
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dma_rw_chunk
```
**Symbols:**

```
ffffffff810d1320-ffffffff810d1440: kthread_use_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void kthread_use_mm(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810cbaf0)
Location: kernel/kthread.c:1299
Inline: False
Direct callers:
  - fs/io-wq.c:io_impersonate_work
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dma_rw_chunk
```
**Symbols:**

```
ffffffff810cbaf0-ffffffff810cbbde: kthread_use_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void kthread_use_mm(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810cd420)
Location: kernel/kthread.c:1357
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dma_rw_chunk
```
**Symbols:**

```
ffffffff810cd420-ffffffff810cd50e: kthread_use_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void kthread_use_mm(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810e0610)
Location: kernel/kthread.c:1357
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dma_rw_chunk
```
**Symbols:**

```
ffffffff810e0610-ffffffff810e06fe: kthread_use_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void kthread_use_mm(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810f98d0)
Location: kernel/kthread.c:1417
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dma_rw_chunk
```
**Symbols:**

```
ffffffff810f98d0-ffffffff810f99c0: kthread_use_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void kthread_use_mm(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff8111c620)
Location: kernel/kthread.c:1417
Inline: False
```
**Symbols:**

```
ffffffff8111c620-ffffffff8111c714: kthread_use_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void kthread_use_mm(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff81129870)
Location: kernel/kthread.c:1423
Inline: False
```
**Symbols:**

```
ffffffff81129870-ffffffff8112994d: kthread_use_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void kthread_use_mm(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff81133eb0)
Location: kernel/kthread.c:1440
Inline: False
```
**Symbols:**

```
ffffffff81133eb0-ffffffff81133f8d: kthread_use_mm (STB_GLOBAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
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
