# Function: <code>acpi_dev_hid_uid_match</code>

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
<summary>In <code>5.8</code>: ✅</summary>

```c
bool acpi_dev_hid_uid_match(struct acpi_device *adev, const char *hid2, const char *uid2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff81681ae0)
Location: drivers/acpi/utils.c:738
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:match_hid_uid
  - drivers/iommu/amd/iommu.c:get_devid
  - drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd/iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd/iommu.c:amd_iommu_device_group
  - drivers/iommu/amd/iommu.c:amd_iommu_release_device
  - drivers/iommu/amd/iommu.c:iommu_init_device
```
**Symbols:**

```
ffffffff81681ae0-ffffffff81681b42: acpi_dev_hid_uid_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool acpi_dev_hid_uid_match(struct acpi_device *adev, const char *hid2, const char *uid2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff816a0630)
Location: drivers/acpi/utils.c:734
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:match_hid_uid
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
  - drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd/iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd/iommu.c:amd_iommu_device_group
  - drivers/iommu/amd/iommu.c:amd_iommu_release_device
  - drivers/iommu/amd/iommu.c:iommu_init_device
```
**Symbols:**

```
ffffffff816a0630-ffffffff816a0692: acpi_dev_hid_uid_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool acpi_dev_hid_uid_match(struct acpi_device *adev, const char *hid2, const char *uid2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff81683090)
Location: drivers/acpi/utils.c:728
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/acpi/acpi_lpss.c:match_hid_uid
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
  - drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd/iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd/iommu.c:amd_iommu_device_group
  - drivers/iommu/amd/iommu.c:amd_iommu_release_device
  - drivers/iommu/amd/iommu.c:iommu_init_device
```
**Symbols:**

```
ffffffff81683090-ffffffff816830f2: acpi_dev_hid_uid_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool acpi_dev_hid_uid_match(struct acpi_device *adev, const char *hid2, const char *uid2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff816f81e0)
Location: drivers/acpi/utils.c:742
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/acpi/acpi_lpss.c:match_hid_uid
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
  - drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd/iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd/iommu.c:amd_iommu_device_group
  - drivers/iommu/amd/iommu.c:amd_iommu_release_device
  - drivers/iommu/amd/iommu.c:iommu_init_device
```
**Symbols:**

```
ffffffff816f81e0-ffffffff816f8242: acpi_dev_hid_uid_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool acpi_dev_hid_uid_match(struct acpi_device *adev, const char *hid2, const char *uid2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff81825340)
Location: drivers/acpi/utils.c:742
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/acpi/acpi_lpss.c:match_hid_uid
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
  - drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd/iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd/iommu.c:amd_iommu_device_group
  - drivers/iommu/amd/iommu.c:amd_iommu_release_device
  - drivers/iommu/amd/iommu.c:iommu_init_device
  - drivers/iommu/amd/iommu.c:check_device
```
**Symbols:**

```
ffffffff81825340-ffffffff818253b4: acpi_dev_hid_uid_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool acpi_dev_hid_uid_match(struct acpi_device *adev, const char *hid2, const char *uid2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff81956670)
Location: drivers/acpi/utils.c:780
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/acpi/acpi_lpss.c:match_hid_uid
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
  - drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd/iommu.c:amd_iommu_device_group
  - drivers/iommu/amd/iommu.c:amd_iommu_probe_device
  - drivers/iommu/amd/iommu.c:iommu_init_device
  - drivers/iommu/amd/iommu.c:check_device
  - drivers/iommu/amd/iommu.c:rlookup_amd_iommu
  - drivers/iommu/amd/iommu.c:rlookup_amd_iommu
```
**Symbols:**

```
ffffffff81956670-ffffffff819566e4: acpi_dev_hid_uid_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool acpi_dev_hid_uid_match(struct acpi_device *adev, const char *hid2, const char *uid2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff8199ca70)
Location: drivers/acpi/utils.c:780
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/acpi/acpi_lpss.c:match_hid_uid
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
  - drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd/iommu.c:amd_iommu_device_group
  - drivers/iommu/amd/iommu.c:amd_iommu_probe_device
  - drivers/iommu/amd/iommu.c:amd_iommu_probe_device
  - drivers/iommu/amd/iommu.c:iommu_init_device
  - drivers/iommu/amd/iommu.c:rlookup_amd_iommu
  - drivers/iommu/amd/iommu.c:rlookup_amd_iommu
```
**Symbols:**

```
ffffffff8199ca70-ffffffff8199cae4: acpi_dev_hid_uid_match (STB_GLOBAL)
```
</details>
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
</ul>
