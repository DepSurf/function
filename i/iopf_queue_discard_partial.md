# Function: <code>iopf_queue_discard_partial</code>

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
int iopf_queue_discard_partial(struct iopf_queue *queue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/io-pgfault.c (ffffffff8182fc10)
Location: drivers/iommu/io-pgfault.c:304
Inline: False
Direct callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
```
**Symbols:**

```
ffffffff8182fc10-ffffffff8182fcdd: iopf_queue_discard_partial (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int iopf_queue_discard_partial(struct iopf_queue *queue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/io-pgfault.c (ffffffff81970e20)
Location: drivers/iommu/io-pgfault.c:304
Inline: False
Direct callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
```
**Symbols:**

```
ffffffff81970e20-ffffffff81970f05: iopf_queue_discard_partial (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int iopf_queue_discard_partial(struct iopf_queue *queue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/io-pgfault.c (ffffffff81adc000)
Location: drivers/iommu/io-pgfault.c:261
Inline: False
Direct callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
```
**Symbols:**

```
ffffffff81adc000-ffffffff81adc0e5: iopf_queue_discard_partial (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int iopf_queue_discard_partial(struct iopf_queue *queue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/io-pgfault.c (ffffffff81b2a270)
Location: drivers/iommu/io-pgfault.c:261
Inline: False
Direct callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
```
**Symbols:**

```
ffffffff81b2a270-ffffffff81b2a355: iopf_queue_discard_partial (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int iopf_queue_discard_partial(struct iopf_queue *queue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/io-pgfault.c (ffffffff81b81440)
Location: drivers/iommu/io-pgfault.c:261
Inline: False
Direct callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
```
**Symbols:**

```
ffffffff81b81440-ffffffff81b81525: iopf_queue_discard_partial (STB_GLOBAL)
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
