# Function: <code>probe_acpi_namespace_devices</code>

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
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff828fe6b7)
Location: drivers/iommu/intel-iommu.c:4609
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
In drivers/iommu/intel-iommu.c (ffffffff8290771f)
Location: drivers/iommu/intel-iommu.c:4880
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
int probe_acpi_namespace_devices();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff82d1d5b3)
Location: drivers/iommu/intel/iommu.c:4779
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff82d1d5b3-ffffffff82d1d6b0: probe_acpi_namespace_devices (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int probe_acpi_namespace_devices();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff8300b2cf)
Location: drivers/iommu/intel/iommu.c:4176
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff8300b2cf-ffffffff8300b3cc: probe_acpi_namespace_devices (STB_LOCAL)
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
In drivers/iommu/intel/iommu.c (ffffffff83216a30)
Location: drivers/iommu/intel/iommu.c:4262
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
In drivers/iommu/intel/iommu.c (ffffffff833002b0)
Location: drivers/iommu/intel/iommu.c:4251
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_init
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
In drivers/iommu/intel/iommu.c (ffffffff834b8f70)
Location: drivers/iommu/intel/iommu.c:3996
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_init
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
In drivers/iommu/intel/iommu.c (ffffffff83ef601c)
Location: drivers/iommu/intel/iommu.c:3874
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_init
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
In drivers/iommu/intel/iommu.c (ffffffff8371bad4)
Location: drivers/iommu/intel/iommu.c:3762
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_init
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
In drivers/iommu/intel/iommu.c (ffffffff8394f5e1)
Location: drivers/iommu/intel/iommu.c:3611
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_init
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
In drivers/iommu/intel-iommu.c (ffffffff828eeef0)
Location: drivers/iommu/intel-iommu.c:4880
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
In drivers/iommu/intel-iommu.c (ffffffff828e6393)
Location: drivers/iommu/intel-iommu.c:4880
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
In drivers/iommu/intel-iommu.c (ffffffff82902a42)
Location: drivers/iommu/intel-iommu.c:4880
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
In drivers/iommu/intel-iommu.c (ffffffff82908781)
Location: drivers/iommu/intel-iommu.c:4880
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
