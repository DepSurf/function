# Function: <code>init_iommu_perf_ctr</code>

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
In drivers/iommu/amd_iommu_init.c (ffffffff81fa9fbd)
Location: drivers/iommu/amd_iommu_init.c:1167
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:state_next
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
In drivers/iommu/amd_iommu_init.c (ffffffff81fd6a86)
Location: drivers/iommu/amd_iommu_init.c:1372
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:state_next
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
In drivers/iommu/amd_iommu_init.c (ffffffff82012dac)
Location: drivers/iommu/amd_iommu_init.c:1479
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
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
In drivers/iommu/amd_iommu_init.c (ffffffff820f61d7)
Location: drivers/iommu/amd_iommu_init.c:1490
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
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
In drivers/iommu/amd_iommu_init.c (ffffffff826ff927)
Location: drivers/iommu/amd_iommu_init.c:1635
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
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
In drivers/iommu/amd_iommu_init.c (ffffffff8166c83b)
Location: drivers/iommu/amd_iommu_init.c:1635
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
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
In drivers/iommu/amd_iommu_init.c (ffffffff828e1e3b)
Location: drivers/iommu/amd_iommu_init.c:1666
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
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
In drivers/iommu/amd_iommu_init.c (ffffffff828fb401)
Location: drivers/iommu/amd_iommu_init.c:1652
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
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
In drivers/iommu/amd_iommu_init.c (ffffffff8290428a)
Location: drivers/iommu/amd_iommu_init.c:1660
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff82d1a97e)
Location: drivers/iommu/amd/init.c:1655
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:iommu_init_pci
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void init_iommu_perf_ctr(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff8300842d)
Location: drivers/iommu/amd/init.c:1718
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:iommu_init_pci
```
**Symbols:**

```
ffffffff8300842d-ffffffff830085f9: init_iommu_perf_ctr (STB_LOCAL)
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
In drivers/iommu/amd/init.c (ffffffff83213536)
Location: drivers/iommu/amd/init.c:1714
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:iommu_init_pci
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
In drivers/iommu/amd/init.c (ffffffff832fc780)
Location: drivers/iommu/amd/init.c:1725
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:iommu_init_pci
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
In drivers/iommu/amd/init.c (ffffffff834b533c)
Location: drivers/iommu/amd/init.c:1732
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:iommu_init_pci
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
In drivers/iommu/amd/init.c (ffffffff83ef0ee1)
Location: drivers/iommu/amd/init.c:1920
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:iommu_init_pci
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
In drivers/iommu/amd/init.c (ffffffff83716b99)
Location: drivers/iommu/amd/init.c:1955
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:iommu_init_pci
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
In drivers/iommu/amd/init.c (ffffffff8394a5f3)
Location: drivers/iommu/amd/init.c:1970
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:iommu_init_pci
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
In drivers/iommu/amd_iommu_init.c (ffffffff828eba71)
Location: drivers/iommu/amd_iommu_init.c:1660
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
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
In drivers/iommu/amd_iommu_init.c (ffffffff828e2efe)
Location: drivers/iommu/amd_iommu_init.c:1660
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
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
In drivers/iommu/amd_iommu_init.c (ffffffff828ff5ad)
Location: drivers/iommu/amd_iommu_init.c:1660
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
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
In drivers/iommu/amd_iommu_init.c (ffffffff829052ec)
Location: drivers/iommu/amd_iommu_init.c:1660
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
