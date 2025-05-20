# Function: <code>dmar_init_reserved_ranges</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81fabd04)
Location: drivers/iommu/intel-iommu.c:1802
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81fd88ac)
Location: drivers/iommu/intel-iommu.c:1842
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8201655c)
Location: drivers/iommu/intel-iommu.c:1866
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff820f828e)
Location: drivers/iommu/intel-iommu.c:1871
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_init
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
In drivers/iommu/intel-iommu.c (ffffffff82701941)
Location: drivers/iommu/intel-iommu.c:1873
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_init
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
In drivers/iommu/intel-iommu.c (ffffffff8272b662)
Location: drivers/iommu/intel-iommu.c:1901
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_init
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
In drivers/iommu/intel-iommu.c (ffffffff828e3f5b)
Location: drivers/iommu/intel-iommu.c:1787
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_init
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
In drivers/iommu/intel-iommu.c (ffffffff828fe405)
Location: drivers/iommu/intel-iommu.c:1778
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_init
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
In drivers/iommu/intel-iommu.c (ffffffff82907443)
Location: drivers/iommu/intel-iommu.c:1789
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int dmar_init_reserved_ranges();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817a6a7a)
Location: drivers/iommu/intel/iommu.c:1866
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff817a6a7a-ffffffff817a6b62: dmar_init_reserved_ranges (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff828eec20)
Location: drivers/iommu/intel-iommu.c:1789
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_init
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
In drivers/iommu/intel-iommu.c (ffffffff828e60b7)
Location: drivers/iommu/intel-iommu.c:1789
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_init
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
In drivers/iommu/intel-iommu.c (ffffffff82902766)
Location: drivers/iommu/intel-iommu.c:1789
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_init
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
In drivers/iommu/intel-iommu.c (ffffffff829084a5)
Location: drivers/iommu/intel-iommu.c:1789
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
