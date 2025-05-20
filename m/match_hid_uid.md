# Function: <code>match_hid_uid</code>

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
In drivers/iommu/amd_iommu.c (ffffffff8158432b)
Location: drivers/iommu/amd_iommu.c:175
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:get_irq_domain
  - drivers/iommu/amd_iommu.c:amd_iommu_get_dm_regions
  - drivers/iommu/amd_iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_device_group
  - drivers/iommu/amd_iommu.c:check_device
  - drivers/iommu/amd_iommu.c:get_alias
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
In drivers/iommu/amd_iommu.c (ffffffff815b165b)
Location: drivers/iommu/amd_iommu.c:176
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:get_irq_domain
  - drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd_iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_device_group
  - drivers/iommu/amd_iommu.c:check_device
  - drivers/iommu/amd_iommu.c:get_alias
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
In drivers/iommu/amd_iommu.c (ffffffff815c8087)
Location: drivers/iommu/amd_iommu.c:205
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:get_irq_domain
  - drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd_iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_device_group
  - drivers/iommu/amd_iommu.c:get_alias
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
In drivers/iommu/amd_iommu.c (ffffffff8162ea43)
Location: drivers/iommu/amd_iommu.c:138
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:get_irq_domain
  - drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd_iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_device_group
  - drivers/iommu/amd_iommu.c:get_alias
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Selective Inline ⚠️</summary>

```c
int match_hid_uid(struct device *dev, void *data);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff8157ff70)
Location: drivers/acpi/acpi_lpss.c:481
Inline: False
```
```
In drivers/iommu/amd_iommu.c (ffffffff8166a34d)
Location: drivers/iommu/amd_iommu.c:139
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd_iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_device_group
  - drivers/iommu/amd_iommu.c:get_alias
```
**Symbols:**

```
ffffffff8157ff70-ffffffff8157ffce: match_hid_uid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Selective Inline ⚠️</summary>

```c
int match_hid_uid(struct device *dev, void *data);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff81597cd0)
Location: drivers/acpi/acpi_lpss.c:514
Inline: False
```
```
In drivers/iommu/amd_iommu.c (ffffffff81687f72)
Location: drivers/iommu/amd_iommu.c:139
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd_iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_device_group
  - drivers/iommu/amd_iommu.c:get_alias
```
**Symbols:**

```
ffffffff81597cd0-ffffffff81597d15: match_hid_uid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Selective Inline ⚠️</summary>

```c
int match_hid_uid(struct device *dev, const void *data);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff815c8e70)
Location: drivers/acpi/acpi_lpss.c:511
Inline: False
```
```
In drivers/iommu/amd_iommu.c (ffffffff816bf4ef)
Location: drivers/iommu/amd_iommu.c:128
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd_iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_device_group
  - drivers/iommu/amd_iommu.c:get_alias
```
**Symbols:**

```
ffffffff815c8e70-ffffffff815c8eb7: match_hid_uid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Selective Inline ⚠️</summary>

```c
int match_hid_uid(struct device *dev, const void *data);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff815ea090)
Location: drivers/acpi/acpi_lpss.c:534
Inline: False
```
```
In drivers/iommu/amd_iommu.c (ffffffff816e287f)
Location: drivers/iommu/amd_iommu.c:127
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd_iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_device_group
```
**Symbols:**

```
ffffffff815ea090-ffffffff815ea0d7: match_hid_uid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int match_hid_uid(struct device *dev, const void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff81695a30)
Location: drivers/acpi/acpi_lpss.c:512
Inline: False
```
**Symbols:**

```
ffffffff81695a30-ffffffff81695a77: match_hid_uid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int match_hid_uid(struct device *dev, const void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff816b2b60)
Location: drivers/acpi/acpi_lpss.c:519
Inline: False
```
**Symbols:**

```
ffffffff816b2b60-ffffffff816b2ba7: match_hid_uid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int match_hid_uid(struct device *dev, const void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff81694df0)
Location: drivers/acpi/acpi_lpss.c:520
Inline: False
```
**Symbols:**

```
ffffffff81694df0-ffffffff81694e37: match_hid_uid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int match_hid_uid(struct device *dev, const void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff8170aae0)
Location: drivers/acpi/acpi_lpss.c:521
Inline: False
```
**Symbols:**

```
ffffffff8170aae0-ffffffff8170ab27: match_hid_uid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int match_hid_uid(struct device *dev, const void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff81839000)
Location: drivers/acpi/acpi_lpss.c:543
Inline: False
```
**Symbols:**

```
ffffffff81839000-ffffffff8183904f: match_hid_uid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int match_hid_uid(struct device *dev, const void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff8196e4b0)
Location: drivers/acpi/acpi_lpss.c:535
Inline: False
```
**Symbols:**

```
ffffffff8196e4b0-ffffffff8196e4ff: match_hid_uid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int match_hid_uid(struct device *dev, const void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff819b49f0)
Location: drivers/acpi/acpi_lpss.c:550
Inline: False
```
**Symbols:**

```
ffffffff819b49f0-ffffffff819b4a3f: match_hid_uid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int match_hid_uid(struct device *dev, const void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff819fff00)
Location: drivers/acpi/acpi_lpss.c:539
Inline: False
```
**Symbols:**

```
ffffffff819fff00-ffffffff819fff89: match_hid_uid (STB_LOCAL)
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
In drivers/iommu/amd_iommu.c (ffffffff816a82cf)
Location: drivers/iommu/amd_iommu.c:127
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd_iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_device_group
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Selective Inline ⚠️</summary>

```c
int match_hid_uid(struct device *dev, const void *data);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff815c4b00)
Location: drivers/acpi/acpi_lpss.c:534
Inline: False
```
```
In drivers/iommu/amd_iommu.c (ffffffff81685cbf)
Location: drivers/iommu/amd_iommu.c:127
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd_iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_device_group
```
**Symbols:**

```
ffffffff815c4b00-ffffffff815c4b47: match_hid_uid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Selective Inline ⚠️</summary>

```c
int match_hid_uid(struct device *dev, const void *data);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff815de370)
Location: drivers/acpi/acpi_lpss.c:534
Inline: False
```
```
In drivers/iommu/amd_iommu.c (ffffffff816d653f)
Location: drivers/iommu/amd_iommu.c:127
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd_iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_device_group
```
**Symbols:**

```
ffffffff815de370-ffffffff815de3b7: match_hid_uid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Selective Inline ⚠️</summary>

```c
int match_hid_uid(struct device *dev, const void *data);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff815f8230)
Location: drivers/acpi/acpi_lpss.c:534
Inline: False
```
```
In drivers/iommu/amd_iommu.c (ffffffff816f0aef)
Location: drivers/iommu/amd_iommu.c:127
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd_iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_device_group
```
**Symbols:**

```
ffffffff815f8230-ffffffff815f8277: match_hid_uid (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>void *data</code> ➡️ <code>const void *data</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
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
