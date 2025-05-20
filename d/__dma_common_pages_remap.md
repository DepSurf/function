# Function: <code>__dma_common_pages_remap</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/dma-mapping.c (ffffffff815f6240)
Location: drivers/base/dma-mapping.c:254
Inline: True
Inline callers:
  - drivers/base/dma-mapping.c:dma_common_contiguous_remap
  - drivers/base/dma-mapping.c:dma_common_pages_remap
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/dma-mapping.c (ffffffff8165e160)
Location: drivers/base/dma-mapping.c:251
Inline: True
Inline callers:
  - drivers/base/dma-mapping.c:dma_common_contiguous_remap
  - drivers/base/dma-mapping.c:dma_common_pages_remap
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff8110cc0d)
Location: kernel/dma/mapping.c:248
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_common_contiguous_remap
  - kernel/dma/mapping.c:dma_common_pages_remap
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct vm_struct *__dma_common_pages_remap(struct page **pages, size_t size, pgprot_t prot, const void *caller);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/remap.c (ffff800010197118)
Location: kernel/dma/remap.c:23
Inline: False
Direct callers:
  - kernel/dma/remap.c:dma_common_contiguous_remap
  - kernel/dma/remap.c:dma_common_pages_remap
```
**Symbols:**

```
ffff800010197118-ffff80001019718c: __dma_common_pages_remap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct vm_struct *__dma_common_pages_remap(struct page **pages, size_t size, pgprot_t prot, const void *caller);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/remap.c (c03e28d4)
Location: kernel/dma/remap.c:23
Inline: False
Direct callers:
  - kernel/dma/remap.c:dma_common_contiguous_remap
  - kernel/dma/remap.c:dma_common_pages_remap
```
**Symbols:**

```
c03e28d4-c03e2934: __dma_common_pages_remap (STB_LOCAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
