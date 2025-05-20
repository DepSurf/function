# Function: <code>is_canonical_address</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-svm.c (ffffffff8163a36d)
Location: drivers/iommu/intel-svm.c:555
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:prq_event_thread
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
In drivers/iommu/intel-svm.c (ffffffff816759b6)
Location: drivers/iommu/intel-svm.c:572
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:prq_event_thread
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-svm.c (ffffffff81694c88)
Location: drivers/iommu/intel-svm.c:507
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:prq_event_thread
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-svm.c (ffffffff816cd639)
Location: drivers/iommu/intel-svm.c:527
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:prq_event_thread
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-svm.c (ffffffff816f1479)
Location: drivers/iommu/intel-svm.c:523
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:prq_event_thread
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool is_canonical_address(u64 addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/svm.c (ffffffff817a91f0)
Location: drivers/iommu/intel/svm.c:704
Inline: False
Direct callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
```
**Symbols:**

```
ffffffff817a91f0-ffffffff817a9222: is_canonical_address (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool is_canonical_address(u64 addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/svm.c (ffffffff817b5110)
Location: drivers/iommu/intel/svm.c:780
Inline: False
Direct callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/iommu/intel/svm.c:prq_event_thread
```
**Symbols:**

```
ffffffff817b5110-ffffffff817b5142: is_canonical_address (STB_LOCAL)
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
In drivers/iommu/intel/svm.c (ffffffff81798c5b)
Location: drivers/iommu/intel/svm.c:733
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
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
In drivers/iommu/intel/svm.c (ffffffff81821315)
Location: drivers/iommu/intel/svm.c:723
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
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
In drivers/iommu/intel/svm.c (ffffffff81961472)
Location: drivers/iommu/intel/svm.c:502
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
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
In drivers/iommu/intel/svm.c (ffffffff81aca05d)
Location: drivers/iommu/intel/svm.c:468
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
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
In drivers/iommu/intel/svm.c (ffffffff81b16bdd)
Location: drivers/iommu/intel/svm.c:454
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
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
In drivers/iommu/intel/svm.c (ffffffff81b6c2bd)
Location: drivers/iommu/intel/svm.c:452
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-svm.c (ffffffff816b6c69)
Location: drivers/iommu/intel-svm.c:523
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:prq_event_thread
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-svm.c (ffffffff816948a9)
Location: drivers/iommu/intel-svm.c:523
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:prq_event_thread
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-svm.c (ffffffff816e5139)
Location: drivers/iommu/intel-svm.c:523
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:prq_event_thread
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-svm.c (ffffffff816ff807)
Location: drivers/iommu/intel-svm.c:523
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:prq_event_thread
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
