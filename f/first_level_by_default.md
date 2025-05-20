# Function: <code>first_level_by_default</code>

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
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff8179f816)
Location: drivers/iommu/intel/iommu.c:1764
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:alloc_domain
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817ad38a)
Location: drivers/iommu/intel/iommu.c:1862
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:alloc_domain
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
In drivers/iommu/intel/iommu.c (ffffffff817916da)
Location: drivers/iommu/intel/iommu.c:1886
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:alloc_domain
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
In drivers/iommu/intel/iommu.c (ffffffff81818bda)
Location: drivers/iommu/intel/iommu.c:1887
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:alloc_domain
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
In drivers/iommu/intel/iommu.c (ffffffff8195a0b5)
Location: drivers/iommu/intel/iommu.c:1779
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:alloc_domain
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool first_level_by_default(unsigned int type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff83ef5f64)
Location: drivers/iommu/intel/iommu.c:1743
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/intel/iommu.c:intel_iommu_init
Direct callers:
  - drivers/iommu/intel/iommu.c:alloc_domain
```
**Symbols:**

```
ffffffff81ac0680-ffffffff81ac06f4: first_level_by_default (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool first_level_by_default(unsigned int type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff8371ba1c)
Location: drivers/iommu/intel/iommu.c:1711
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/intel/iommu.c:intel_iommu_init
Direct callers:
  - drivers/iommu/intel/iommu.c:alloc_domain
```
**Symbols:**

```
ffffffff81b0ceb0-ffffffff81b0cf24: first_level_by_default (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool first_level_by_default(unsigned int type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff8394f529)
Location: drivers/iommu/intel/iommu.c:1661
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/intel/iommu.c:intel_iommu_init
Direct callers:
  - drivers/iommu/intel/iommu.c:alloc_domain
```
**Symbols:**

```
ffffffff81b618c0-ffffffff81b61934: first_level_by_default (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
