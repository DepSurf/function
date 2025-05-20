# Function: <code>free_all_cpu_cached_iovas</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8158ba27)
Location: drivers/iommu/intel-iommu.c:4599
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_cpu_notifier
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
In drivers/iommu/intel-iommu.c (ffffffff815b9165)
Location: drivers/iommu/intel-iommu.c:4704
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_cpu_dead
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
In drivers/iommu/intel-iommu.c (ffffffff815ce9c5)
Location: drivers/iommu/intel-iommu.c:4699
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_cpu_dead
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
In drivers/iommu/intel-iommu.c (ffffffff81635355)
Location: drivers/iommu/intel-iommu.c:4605
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_cpu_dead
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
In drivers/iommu/intel-iommu.c (ffffffff81670935)
Location: drivers/iommu/intel-iommu.c:4647
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_cpu_dead
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
In drivers/iommu/intel-iommu.c (ffffffff8168ecd5)
Location: drivers/iommu/intel-iommu.c:4656
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_cpu_dead
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
In drivers/iommu/intel-iommu.c (ffffffff816c6205)
Location: drivers/iommu/intel-iommu.c:4451
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_cpu_dead
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
In drivers/iommu/intel-iommu.c (ffffffff816e9235)
Location: drivers/iommu/intel-iommu.c:4727
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_cpu_dead
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void free_all_cpu_cached_iovas(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817a13f0)
Location: drivers/iommu/intel/iommu.c:4605
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_cpu_dead
```
**Symbols:**

```
ffffffff817a13f0-ffffffff817a148d: free_all_cpu_cached_iovas (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void free_all_cpu_cached_iovas(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817ae880)
Location: drivers/iommu/intel/iommu.c:4002
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_cpu_dead
```
**Symbols:**

```
ffffffff817ae880-ffffffff817ae91d: free_all_cpu_cached_iovas (STB_LOCAL)
```
</details>
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
In drivers/iommu/intel-iommu.c (ffffffff816aed15)
Location: drivers/iommu/intel-iommu.c:4727
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_cpu_dead
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
In drivers/iommu/intel-iommu.c (ffffffff8168c675)
Location: drivers/iommu/intel-iommu.c:4727
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_cpu_dead
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
In drivers/iommu/intel-iommu.c (ffffffff816dcef5)
Location: drivers/iommu/intel-iommu.c:4727
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_cpu_dead
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
In drivers/iommu/intel-iommu.c (ffffffff816f7535)
Location: drivers/iommu/intel-iommu.c:4727
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_cpu_dead
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
