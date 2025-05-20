# Function: <code>build_inv_iotlb_pages</code>

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
In drivers/iommu/amd_iommu.c (ffffffff8152f5d3)
Location: drivers/iommu/amd_iommu.c:745
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
Location: drivers/iommu/amd_iommu.c:841
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
Location: drivers/iommu/amd_iommu.c:911
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:__domain_flush_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void build_inv_iotlb_pages(struct iommu_cmd *cmd, u16 devid, int qdep, u64 address, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815c3ec0)
Location: drivers/iommu/amd_iommu.c:969
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:__domain_flush_pages
```
**Symbols:**

```
ffffffff815c3ec0-ffffffff815c3f22: build_inv_iotlb_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void build_inv_iotlb_pages(struct iommu_cmd *cmd, u16 devid, int qdep, u64 address, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff8162ac10)
Location: drivers/iommu/amd_iommu.c:910
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:__domain_flush_pages
```
**Symbols:**

```
ffffffff8162ac10-ffffffff8162ac72: build_inv_iotlb_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void build_inv_iotlb_pages(struct iommu_cmd *cmd, u16 devid, int qdep, u64 address, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81665840)
Location: drivers/iommu/amd_iommu.c:916
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:__domain_flush_pages
```
**Symbols:**

```
ffffffff81665840-ffffffff81665894: build_inv_iotlb_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void build_inv_iotlb_pages(struct iommu_cmd *cmd, u16 devid, int qdep, u64 address, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816842b0)
Location: drivers/iommu/amd_iommu.c:931
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:__domain_flush_pages
```
**Symbols:**

```
ffffffff816842b0-ffffffff81684304: build_inv_iotlb_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void build_inv_iotlb_pages(struct iommu_cmd *cmd, u16 devid, int qdep, u64 address, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816bb820)
Location: drivers/iommu/amd_iommu.c:919
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:__domain_flush_pages
```
**Symbols:**

```
ffffffff816bb820-ffffffff816bb874: build_inv_iotlb_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void build_inv_iotlb_pages(struct iommu_cmd *cmd, u16 devid, int qdep, u64 address, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816de6b0)
Location: drivers/iommu/amd_iommu.c:926
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:__domain_flush_pages
  - drivers/iommu/amd_iommu.c:device_flush_dte
```
**Symbols:**

```
ffffffff816de6b0-ffffffff816de704: build_inv_iotlb_pages (STB_LOCAL)
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
In drivers/iommu/amd/iommu.c (ffffffff817968af)
Location: drivers/iommu/amd/iommu.c:870
Inline: True
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
In drivers/iommu/amd/iommu.c (ffffffff817a4fcf)
Location: drivers/iommu/amd/iommu.c:961
Inline: True
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
In drivers/iommu/amd/iommu.c (ffffffff8178727c)
Location: drivers/iommu/amd/iommu.c:910
Inline: True
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
In drivers/iommu/amd/iommu.c (ffffffff8180e54c)
Location: drivers/iommu/amd/iommu.c:922
Inline: True
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
In drivers/iommu/amd/iommu.c (ffffffff8194f738)
Location: drivers/iommu/amd/iommu.c:944
Inline: True
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
In drivers/iommu/amd/iommu.c (ffffffff81ab4924)
Location: drivers/iommu/amd/iommu.c:1013
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:device_flush_iotlb
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
In drivers/iommu/amd/iommu.c (ffffffff81b00f94)
Location: drivers/iommu/amd/iommu.c:1030
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:device_flush_iotlb
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void build_inv_iotlb_pages(struct iommu_cmd *cmd, u16 devid, int qdep, u64 address, size_t size, ioasid_t pasid, bool gn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81b512a0)
Location: drivers/iommu/amd/iommu.c:1149
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:__flush_pasid
  - drivers/iommu/amd/iommu.c:__domain_flush_pages
```
**Symbols:**

```
ffffffff81b512a0-ffffffff81b51397: build_inv_iotlb_pages (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
void build_inv_iotlb_pages(struct iommu_cmd *cmd, u16 devid, int qdep, u64 address, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816a4100)
Location: drivers/iommu/amd_iommu.c:926
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:__domain_flush_pages
  - drivers/iommu/amd_iommu.c:device_flush_dte
```
**Symbols:**

```
ffffffff816a4100-ffffffff816a4154: build_inv_iotlb_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void build_inv_iotlb_pages(struct iommu_cmd *cmd, u16 devid, int qdep, u64 address, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81681af0)
Location: drivers/iommu/amd_iommu.c:926
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:__domain_flush_pages
  - drivers/iommu/amd_iommu.c:device_flush_dte
```
**Symbols:**

```
ffffffff81681af0-ffffffff81681b44: build_inv_iotlb_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void build_inv_iotlb_pages(struct iommu_cmd *cmd, u16 devid, int qdep, u64 address, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816d2370)
Location: drivers/iommu/amd_iommu.c:926
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:__domain_flush_pages
  - drivers/iommu/amd_iommu.c:device_flush_dte
```
**Symbols:**

```
ffffffff816d2370-ffffffff816d23c4: build_inv_iotlb_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void build_inv_iotlb_pages(struct iommu_cmd *cmd, u16 devid, int qdep, u64 address, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816ec9b0)
Location: drivers/iommu/amd_iommu.c:926
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:__domain_flush_pages
  - drivers/iommu/amd_iommu.c:device_flush_dte
```
**Symbols:**

```
ffffffff816ec9b0-ffffffff816eca04: build_inv_iotlb_pages (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
