# Function: <code>handle_bad_prq_event</code>

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
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/svm.c (ffffffff81d010e6)
Location: drivers/iommu/intel/svm.c:892
Inline: True
Direct callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/iommu/intel/svm.c:prq_event_thread
```
**Symbols:**

```
ffffffff81d010e6-ffffffff81d011de: handle_bad_prq_event.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/svm.c (ffffffff81ec95e6)
Location: drivers/iommu/intel/svm.c:671
Inline: True
Direct callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/iommu/intel/svm.c:prq_event_thread
```
**Symbols:**

```
ffffffff81ec95e6-ffffffff81ec96f8: handle_bad_prq_event.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/svm.c (ffffffff81ac9d60)
Location: drivers/iommu/intel/svm.c:637
Inline: True
Direct callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/iommu/intel/svm.c:prq_event_thread
```
**Symbols:**

```
ffffffff81ac9d60-ffffffff81ac9e88: handle_bad_prq_event.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/svm.c (ffffffff81b168e0)
Location: drivers/iommu/intel/svm.c:623
Inline: True
Direct callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/iommu/intel/svm.c:prq_event_thread
```
**Symbols:**

```
ffffffff81b168e0-ffffffff81b16a0e: handle_bad_prq_event.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/svm.c (ffffffff81b6bfc0)
Location: drivers/iommu/intel/svm.c:609
Inline: True
Direct callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/iommu/intel/svm.c:prq_event_thread
```
**Symbols:**

```
ffffffff81b6bfc0-ffffffff81b6c0ee: handle_bad_prq_event.constprop.0 (STB_LOCAL)
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
