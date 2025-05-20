# Function: <code>iommu_init_mempool</code>

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
In drivers/iommu/intel-iommu.c (ffffffff81fabbdf)
Location: drivers/iommu/intel-iommu.c:3825
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
In drivers/iommu/intel-iommu.c (ffffffff81fd8786)
Location: drivers/iommu/intel-iommu.c:3922
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
In drivers/iommu/intel-iommu.c (ffffffff82016436)
Location: drivers/iommu/intel-iommu.c:4013
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
In drivers/iommu/intel-iommu.c (ffffffff820f810b)
Location: drivers/iommu/intel-iommu.c:4008
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
In drivers/iommu/intel-iommu.c (ffffffff8270179d)
Location: drivers/iommu/intel-iommu.c:3914
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
In drivers/iommu/intel-iommu.c (ffffffff8272b4ba)
Location: drivers/iommu/intel-iommu.c:3956
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
In drivers/iommu/intel-iommu.c (ffffffff828e3db9)
Location: drivers/iommu/intel-iommu.c:3965
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
In drivers/iommu/intel-iommu.c (ffffffff828fe25d)
Location: drivers/iommu/intel-iommu.c:3807
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
In drivers/iommu/intel-iommu.c (ffffffff8290729b)
Location: drivers/iommu/intel-iommu.c:4082
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
int iommu_init_mempool();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff82d1d516)
Location: drivers/iommu/intel/iommu.c:3959
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff82d1d516-ffffffff82d1d5b3: iommu_init_mempool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int iommu_init_mempool();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff8300b232)
Location: drivers/iommu/intel/iommu.c:3388
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff8300b232-ffffffff8300b2cf: iommu_init_mempool (STB_LOCAL)
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
In drivers/iommu/intel/iommu.c (ffffffff832166a1)
Location: drivers/iommu/intel/iommu.c:3430
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_init
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
In drivers/iommu/intel/iommu.c (ffffffff832fff10)
Location: drivers/iommu/intel/iommu.c:3425
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_init
```
</details>
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
In drivers/iommu/intel-iommu.c (ffffffff828eea78)
Location: drivers/iommu/intel-iommu.c:4082
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
In drivers/iommu/intel-iommu.c (ffffffff828e5f0f)
Location: drivers/iommu/intel-iommu.c:4082
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
In drivers/iommu/intel-iommu.c (ffffffff829025be)
Location: drivers/iommu/intel-iommu.c:4082
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
In drivers/iommu/intel-iommu.c (ffffffff829082fd)
Location: drivers/iommu/intel-iommu.c:4082
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
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
