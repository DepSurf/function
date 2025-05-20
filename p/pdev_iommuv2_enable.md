# Function: <code>pdev_iommuv2_enable</code>

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
In drivers/iommu/amd_iommu.c (ffffffff815304fb)
Location: drivers/iommu/amd_iommu.c:2005
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
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
In drivers/iommu/amd_iommu.c (ffffffff815850aa)
Location: drivers/iommu/amd_iommu.c:1885
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
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
In drivers/iommu/amd_iommu.c (ffffffff815b21be)
Location: drivers/iommu/amd_iommu.c:1978
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
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
In drivers/iommu/amd_iommu.c (ffffffff815c7ec0)
Location: drivers/iommu/amd_iommu.c:2225
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
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
In drivers/iommu/amd_iommu.c (ffffffff8162d3b7)
Location: drivers/iommu/amd_iommu.c:1996
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:attach_device
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
In drivers/iommu/amd_iommu.c (ffffffff81667e7d)
Location: drivers/iommu/amd_iommu.c:1998
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:attach_device
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
In drivers/iommu/amd_iommu.c (ffffffff81686b89)
Location: drivers/iommu/amd_iommu.c:2080
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:attach_device
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
In drivers/iommu/amd_iommu.c (ffffffff816be3f3)
Location: drivers/iommu/amd_iommu.c:2079
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:attach_device
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
In drivers/iommu/amd_iommu.c (ffffffff816e1815)
Location: drivers/iommu/amd_iommu.c:2107
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:attach_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pdev_iommuv2_enable(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81795270)
Location: drivers/iommu/amd/iommu.c:1968
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:attach_device
```
**Symbols:**

```
ffffffff81795270-ffffffff81795381: pdev_iommuv2_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pdev_iommuv2_enable(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff817a3630)
Location: drivers/iommu/amd/iommu.c:2059
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:attach_device
```
**Symbols:**

```
ffffffff817a3630-ffffffff817a374c: pdev_iommuv2_enable (STB_LOCAL)
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
In drivers/iommu/amd/iommu.c (ffffffff8178a172)
Location: drivers/iommu/amd/iommu.c:1532
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:attach_device
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
In drivers/iommu/amd/iommu.c (ffffffff8181147f)
Location: drivers/iommu/amd/iommu.c:1581
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:attach_device
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
In drivers/iommu/amd/iommu.c (ffffffff81951a63)
Location: drivers/iommu/amd/iommu.c:1603
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:attach_device
```
</details>
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
In drivers/iommu/amd_iommu.c (ffffffff816a7265)
Location: drivers/iommu/amd_iommu.c:2107
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:attach_device
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
In drivers/iommu/amd_iommu.c (ffffffff81684c55)
Location: drivers/iommu/amd_iommu.c:2107
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:attach_device
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
In drivers/iommu/amd_iommu.c (ffffffff816d54d5)
Location: drivers/iommu/amd_iommu.c:2107
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:attach_device
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
In drivers/iommu/amd_iommu.c (ffffffff816efe0c)
Location: drivers/iommu/amd_iommu.c:2107
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:attach_device
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
