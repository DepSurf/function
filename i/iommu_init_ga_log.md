# Function: <code>iommu_init_ga_log</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff82012b4d)
Location: drivers/iommu/amd_iommu_init.c:725
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
In drivers/iommu/amd_iommu_init.c (ffffffff820f60cb)
Location: drivers/iommu/amd_iommu_init.c:734
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
In drivers/iommu/amd_iommu_init.c (ffffffff826ff69f)
Location: drivers/iommu/amd_iommu_init.c:779
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
In drivers/iommu/amd_iommu_init.c (ffffffff8166c741)
Location: drivers/iommu/amd_iommu_init.c:779
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
In drivers/iommu/amd_iommu_init.c (ffffffff828e1d37)
Location: drivers/iommu/amd_iommu_init.c:782
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
In drivers/iommu/amd_iommu_init.c (ffffffff828fb2f3)
Location: drivers/iommu/amd_iommu_init.c:770
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
In drivers/iommu/amd_iommu_init.c (ffffffff8290417c)
Location: drivers/iommu/amd_iommu_init.c:771
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int iommu_init_ga_log(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff8179bd39)
Location: drivers/iommu/amd/init.c:771
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:iommu_init_pci
```
**Symbols:**

```
ffffffff8179bd39-ffffffff8179be96: iommu_init_ga_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int iommu_init_ga_log(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff81c0bb4a)
Location: drivers/iommu/amd/init.c:821
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:iommu_init_pci
```
**Symbols:**

```
ffffffff81c0bb4a-ffffffff81c0bc9d: iommu_init_ga_log (STB_LOCAL)
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
In drivers/iommu/amd/init.c (ffffffff8321342b)
Location: drivers/iommu/amd/init.c:817
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
In drivers/iommu/amd/init.c (ffffffff832fc6ed)
Location: drivers/iommu/amd/init.c:855
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
In drivers/iommu/amd/init.c (ffffffff834b52ae)
Location: drivers/iommu/amd/init.c:859
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
In drivers/iommu/amd/init.c (ffffffff81ab9415)
Location: drivers/iommu/amd/init.c:936
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:enable_iommus_vapic
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
In drivers/iommu/amd/init.c (ffffffff81b05882)
Location: drivers/iommu/amd/init.c:971
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:enable_iommus_vapic
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
In drivers/iommu/amd/init.c (ffffffff81b592c2)
Location: drivers/iommu/amd/init.c:986
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:enable_iommus_vapic
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
In drivers/iommu/amd_iommu_init.c (ffffffff828eb963)
Location: drivers/iommu/amd_iommu_init.c:771
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
In drivers/iommu/amd_iommu_init.c (ffffffff828e2df0)
Location: drivers/iommu/amd_iommu_init.c:771
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
In drivers/iommu/amd_iommu_init.c (ffffffff828ff49f)
Location: drivers/iommu/amd_iommu_init.c:771
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
In drivers/iommu/amd_iommu_init.c (ffffffff829051de)
Location: drivers/iommu/amd_iommu_init.c:771
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
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
