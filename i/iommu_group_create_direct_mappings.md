# Function: <code>iommu_group_create_direct_mappings</code>

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
In drivers/iommu/iommu.c (ffffffff8152b56c)
Location: drivers/iommu/iommu.c:328
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_add_device
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
In drivers/iommu/iommu.c (ffffffff8157e575)
Location: drivers/iommu/iommu.c:316
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_add_device
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
In drivers/iommu/iommu.c (ffffffff815aab15)
Location: drivers/iommu/iommu.c:451
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_add_device
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
In drivers/iommu/iommu.c (ffffffff815c067c)
Location: drivers/iommu/iommu.c:484
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_add_device
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
In drivers/iommu/iommu.c (ffffffff81626d4c)
Location: drivers/iommu/iommu.c:484
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_add_device
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
In drivers/iommu/iommu.c (ffffffff81661a4c)
Location: drivers/iommu/iommu.c:485
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_add_device
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
In drivers/iommu/iommu.c (ffffffff8168010c)
Location: drivers/iommu/iommu.c:551
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_group_add_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816b74d0)
Location: drivers/iommu/iommu.c:568
Inline: True
Direct callers:
  - drivers/iommu/iommu.c:request_default_domain_for_dev
  - drivers/iommu/iommu.c:iommu_group_add_device
```
**Symbols:**

```
ffffffff816b74d0-ffffffff816b76a1: iommu_group_create_direct_mappings.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816da080)
Location: drivers/iommu/iommu.c:623
Inline: True
Direct callers:
  - drivers/iommu/iommu.c:request_default_domain_for_dev
  - drivers/iommu/iommu.c:iommu_group_add_device
```
**Symbols:**

```
ffffffff816da080-ffffffff816da251: iommu_group_create_direct_mappings.isra.0 (STB_LOCAL)
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
In drivers/iommu/iommu.c (ffffffff8178fffd)
Location: drivers/iommu/iommu.c:1722
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:bus_iommu_probe
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
In drivers/iommu/iommu.c (ffffffff817bc3fd)
Location: drivers/iommu/iommu.c:1752
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:bus_iommu_probe
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
In drivers/iommu/iommu.c (ffffffff8179f5dd)
Location: drivers/iommu/iommu.c:1773
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:bus_iommu_probe
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
In drivers/iommu/iommu.c (ffffffff818285cd)
Location: drivers/iommu/iommu.c:1788
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:bus_iommu_probe
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
In drivers/iommu/iommu.c (ffffffff81968569)
Location: drivers/iommu/iommu.c:1725
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:bus_iommu_probe
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
In drivers/iommu/iommu.c (ffffffff81ad22a1)
Location: drivers/iommu/iommu.c:1828
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:bus_iommu_probe
```
</details>
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
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (ffff8000108c6298)
Location: drivers/iommu/iommu.c:623
Inline: True
Direct callers:
  - drivers/iommu/iommu.c:request_default_domain_for_dev
  - drivers/iommu/iommu.c:iommu_group_add_device
```
**Symbols:**

```
ffff8000108c6298-ffff8000108c6490: iommu_group_create_direct_mappings.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int iommu_group_create_direct_mappings(struct iommu_group *group, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c09bcae8)
Location: drivers/iommu/iommu.c:623
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:request_default_domain_for_dev
  - drivers/iommu/iommu.c:iommu_group_add_device
```
**Symbols:**

```
c09bcae8-c09bccf0: iommu_group_create_direct_mappings (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int iommu_group_create_direct_mappings(struct iommu_group *group, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c00000000096ba10)
Location: drivers/iommu/iommu.c:623
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:request_default_domain_for_dev
  - drivers/iommu/iommu.c:iommu_group_add_device
```
**Symbols:**

```
c00000000096ba10-c00000000096bcec: iommu_group_create_direct_mappings (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8169fad0)
Location: drivers/iommu/iommu.c:623
Inline: True
Direct callers:
  - drivers/iommu/iommu.c:request_default_domain_for_dev
  - drivers/iommu/iommu.c:iommu_group_add_device
```
**Symbols:**

```
ffffffff8169fad0-ffffffff8169fca1: iommu_group_create_direct_mappings.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8167d4c0)
Location: drivers/iommu/iommu.c:623
Inline: True
Direct callers:
  - drivers/iommu/iommu.c:request_default_domain_for_dev
  - drivers/iommu/iommu.c:iommu_group_add_device
```
**Symbols:**

```
ffffffff8167d4c0-ffffffff8167d691: iommu_group_create_direct_mappings.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816cdd40)
Location: drivers/iommu/iommu.c:623
Inline: True
Direct callers:
  - drivers/iommu/iommu.c:request_default_domain_for_dev
  - drivers/iommu/iommu.c:iommu_group_add_device
```
**Symbols:**

```
ffffffff816cdd40-ffffffff816cdf11: iommu_group_create_direct_mappings.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816e8280)
Location: drivers/iommu/iommu.c:623
Inline: True
Direct callers:
  - drivers/iommu/iommu.c:request_default_domain_for_dev
  - drivers/iommu/iommu.c:iommu_group_add_device
```
**Symbols:**

```
ffffffff816e8280-ffffffff816e8451: iommu_group_create_direct_mappings.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
