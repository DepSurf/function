# Function: <code>device_flush_iotlb</code>

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
In drivers/iommu/amd_iommu.c (ffffffff8152f5cc)
Location: drivers/iommu/amd_iommu.c:995
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:__domain_flush_pages
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
In drivers/iommu/amd_iommu.c (ffffffff81582ec2)
Location: drivers/iommu/amd_iommu.c:1091
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:__domain_flush_pages
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
In drivers/iommu/amd_iommu.c (ffffffff815b01ed)
Location: drivers/iommu/amd_iommu.c:1180
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:__domain_flush_pages
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
In drivers/iommu/amd_iommu.c (ffffffff815c54de)
Location: drivers/iommu/amd_iommu.c:1239
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:__domain_flush_pages
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
In drivers/iommu/amd_iommu.c (ffffffff8162c22e)
Location: drivers/iommu/amd_iommu.c:1180
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:__domain_flush_pages
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
In drivers/iommu/amd_iommu.c (ffffffff8166772e)
Location: drivers/iommu/amd_iommu.c:1186
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:__domain_flush_pages
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
In drivers/iommu/amd_iommu.c (ffffffff816861de)
Location: drivers/iommu/amd_iommu.c:1201
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:__domain_flush_pages
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
In drivers/iommu/amd_iommu.c (ffffffff816bda8b)
Location: drivers/iommu/amd_iommu.c:1200
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:__domain_flush_pages
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
In drivers/iommu/amd_iommu.c (ffffffff816e0c7f)
Location: drivers/iommu/amd_iommu.c:1207
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:__domain_flush_pages
  - drivers/iommu/amd_iommu.c:device_flush_dte
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81796870)
Location: drivers/iommu/amd/iommu.c:1151
Inline: True
Direct callers:
  - drivers/iommu/amd/iommu.c:__domain_flush_pages
```
**Symbols:**

```
ffffffff81796870-ffffffff8179693f: device_flush_iotlb.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff817a4f90)
Location: drivers/iommu/amd/iommu.c:1241
Inline: True
Direct callers:
  - drivers/iommu/amd/iommu.c:__domain_flush_pages
```
**Symbols:**

```
ffffffff817a4f90-ffffffff817a505f: device_flush_iotlb.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81787240)
Location: drivers/iommu/amd/iommu.c:1173
Inline: True
Direct callers:
  - drivers/iommu/amd/iommu.c:__domain_flush_pages
```
**Symbols:**

```
ffffffff81787240-ffffffff8178735d: device_flush_iotlb.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff8180e510)
Location: drivers/iommu/amd/iommu.c:1185
Inline: True
```
**Symbols:**

```
ffffffff8180e510-ffffffff8180e62d: device_flush_iotlb.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff8194f6f0)
Location: drivers/iommu/amd/iommu.c:1207
Inline: True
```
**Symbols:**

```
ffffffff8194f6f0-ffffffff8194f830: device_flush_iotlb.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int device_flush_iotlb(struct iommu_dev_data *dev_data, u64 address, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81ab48c0)
Location: drivers/iommu/amd/iommu.c:1279
Inline: False
```
**Symbols:**

```
ffffffff81ab48c0-ffffffff81ab4a22: device_flush_iotlb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int device_flush_iotlb(struct iommu_dev_data *dev_data, u64 address, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81b00f30)
Location: drivers/iommu/amd/iommu.c:1299
Inline: False
```
**Symbols:**

```
ffffffff81b00f30-ffffffff81b01092: device_flush_iotlb (STB_LOCAL)
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
In drivers/iommu/amd/iommu.c (ffffffff81b548be)
Location: drivers/iommu/amd/iommu.c:1388
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:__domain_flush_pages
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
In drivers/iommu/amd_iommu.c (ffffffff816a66cf)
Location: drivers/iommu/amd_iommu.c:1207
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:__domain_flush_pages
  - drivers/iommu/amd_iommu.c:device_flush_dte
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
In drivers/iommu/amd_iommu.c (ffffffff816840bf)
Location: drivers/iommu/amd_iommu.c:1207
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:__domain_flush_pages
  - drivers/iommu/amd_iommu.c:device_flush_dte
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
In drivers/iommu/amd_iommu.c (ffffffff816d493f)
Location: drivers/iommu/amd_iommu.c:1207
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:__domain_flush_pages
  - drivers/iommu/amd_iommu.c:device_flush_dte
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
In drivers/iommu/amd_iommu.c (ffffffff816ef03f)
Location: drivers/iommu/amd_iommu.c:1207
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:__domain_flush_pages
  - drivers/iommu/amd_iommu.c:device_flush_dte
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
</ul>
