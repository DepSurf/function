# Function: <code>do_attach</code>

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
In drivers/iommu/amd_iommu.c (ffffffff815303fd)
Location: drivers/iommu/amd_iommu.c:1886
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
In drivers/iommu/amd_iommu.c (ffffffff81584f9b)
Location: drivers/iommu/amd_iommu.c:1766
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
In drivers/iommu/amd_iommu.c (ffffffff815b209a)
Location: drivers/iommu/amd_iommu.c:1859
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
In drivers/iommu/amd_iommu.c (ffffffff815c7d95)
Location: drivers/iommu/amd_iommu.c:2106
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
In drivers/iommu/amd_iommu.c (ffffffff8162d2ba)
Location: drivers/iommu/amd_iommu.c:1877
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
In drivers/iommu/amd_iommu.c (ffffffff81667d7a)
Location: drivers/iommu/amd_iommu.c:1888
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
In drivers/iommu/amd_iommu.c (ffffffff81686a8a)
Location: drivers/iommu/amd_iommu.c:1969
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
In drivers/iommu/amd_iommu.c (ffffffff816be2e4)
Location: drivers/iommu/amd_iommu.c:1968
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
In drivers/iommu/amd_iommu.c (ffffffff816e1713)
Location: drivers/iommu/amd_iommu.c:2032
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
void do_attach(struct iommu_dev_data *dev_data, struct protection_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81799250)
Location: drivers/iommu/amd/iommu.c:1890
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:attach_device
```
**Symbols:**

```
ffffffff81799250-ffffffff81799352: do_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void do_attach(struct iommu_dev_data *dev_data, struct protection_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff817a7ad0)
Location: drivers/iommu/amd/iommu.c:1981
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:attach_device
```
**Symbols:**

```
ffffffff817a7ad0-ffffffff817a7bd2: do_attach (STB_LOCAL)
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
In drivers/iommu/amd/iommu.c (ffffffff8178a001)
Location: drivers/iommu/amd/iommu.c:1473
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
In drivers/iommu/amd/iommu.c (ffffffff818112e1)
Location: drivers/iommu/amd/iommu.c:1522
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
In drivers/iommu/amd/iommu.c (ffffffff81951891)
Location: drivers/iommu/amd/iommu.c:1544
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:attach_device
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
In drivers/iommu/amd/iommu.c (ffffffff81ab6921)
Location: drivers/iommu/amd/iommu.c:1640
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:attach_device
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
In drivers/iommu/amd/iommu.c (ffffffff81b02b41)
Location: drivers/iommu/amd/iommu.c:1665
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:attach_device
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
In drivers/iommu/amd/iommu.c (ffffffff81b56ce9)
Location: drivers/iommu/amd/iommu.c:1807
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_attach_device
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
In drivers/iommu/amd_iommu.c (ffffffff816a7163)
Location: drivers/iommu/amd_iommu.c:2032
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
In drivers/iommu/amd_iommu.c (ffffffff81684b53)
Location: drivers/iommu/amd_iommu.c:2032
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
In drivers/iommu/amd_iommu.c (ffffffff816d53d3)
Location: drivers/iommu/amd_iommu.c:2032
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
In drivers/iommu/amd_iommu.c (ffffffff816efd12)
Location: drivers/iommu/amd_iommu.c:2032
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
