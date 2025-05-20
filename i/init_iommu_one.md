# Function: <code>init_iommu_one</code>

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
In drivers/iommu/amd_iommu_init.c (ffffffff81fa9113)
Location: drivers/iommu/amd_iommu_init.c:1055
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:init_iommu_all
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
In drivers/iommu/amd_iommu_init.c (ffffffff81fd628c)
Location: drivers/iommu/amd_iommu_init.c:1226
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
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
In drivers/iommu/amd_iommu_init.c (ffffffff82014421)
Location: drivers/iommu/amd_iommu_init.c:1329
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
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
In drivers/iommu/amd_iommu_init.c (ffffffff820f5937)
Location: drivers/iommu/amd_iommu_init.c:1338
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
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
In drivers/iommu/amd_iommu_init.c (ffffffff826feff7)
Location: drivers/iommu/amd_iommu_init.c:1473
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
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
In drivers/iommu/amd_iommu_init.c (ffffffff827293fe)
Location: drivers/iommu/amd_iommu_init.c:1473
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
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
In drivers/iommu/amd_iommu_init.c (ffffffff828e164b)
Location: drivers/iommu/amd_iommu_init.c:1500
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
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
In drivers/iommu/amd_iommu_init.c (ffffffff828fc145)
Location: drivers/iommu/amd_iommu_init.c:1486
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:init_iommu_all
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
In drivers/iommu/amd_iommu_init.c (ffffffff82905103)
Location: drivers/iommu/amd_iommu_init.c:1489
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:init_iommu_all
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int init_iommu_one(struct amd_iommu *iommu, struct ivhd_header *h);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff82d1bea8)
Location: drivers/iommu/amd/init.c:1467
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:init_iommu_all
```
**Symbols:**

```
ffffffff82d1bea8-ffffffff82d1c14a: init_iommu_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int init_iommu_one(struct amd_iommu *iommu, struct ivhd_header *h);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff83009c78)
Location: drivers/iommu/amd/init.c:1531
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:init_iommu_all
```
**Symbols:**

```
ffffffff83009c78-ffffffff83009f48: init_iommu_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int init_iommu_one(struct amd_iommu *iommu, struct ivhd_header *h);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff832147a5)
Location: drivers/iommu/amd/init.c:1527
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:init_iommu_all
```
**Symbols:**

```
ffffffff832147a5-ffffffff83214a78: init_iommu_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int init_iommu_one(struct amd_iommu *iommu, struct ivhd_header *h);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff832fdd6f)
Location: drivers/iommu/amd/init.c:1538
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:init_iommu_all
```
**Symbols:**

```
ffffffff832fdd6f-ffffffff832fe09f: init_iommu_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int init_iommu_one(struct amd_iommu *iommu, struct ivhd_header *h);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff834b697c)
Location: drivers/iommu/amd/init.c:1545
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:init_iommu_all
```
**Symbols:**

```
ffffffff834b697c-ffffffff834b6cba: init_iommu_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int init_iommu_one(struct amd_iommu *iommu, struct ivhd_header *h, struct acpi_table_header *ivrs_base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff83ef3080)
Location: drivers/iommu/amd/init.c:1714
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:init_iommu_all
```
**Symbols:**

```
ffffffff83ef3080-ffffffff83ef3334: init_iommu_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int init_iommu_one(struct amd_iommu *iommu, struct ivhd_header *h, struct acpi_table_header *ivrs_base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff83718c30)
Location: drivers/iommu/amd/init.c:1749
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:init_iommu_all
```
**Symbols:**

```
ffffffff83718c30-ffffffff83718ee8: init_iommu_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int init_iommu_one(struct amd_iommu *iommu, struct ivhd_header *h, struct acpi_table_header *ivrs_base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff8394c6f0)
Location: drivers/iommu/amd/init.c:1764
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:init_iommu_all
```
**Symbols:**

```
ffffffff8394c6f0-ffffffff8394c9a8: init_iommu_one (STB_LOCAL)
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
In drivers/iommu/amd_iommu_init.c (ffffffff828ec8ea)
Location: drivers/iommu/amd_iommu_init.c:1489
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:init_iommu_all
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
In drivers/iommu/amd_iommu_init.c (ffffffff828e3d77)
Location: drivers/iommu/amd_iommu_init.c:1489
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:init_iommu_all
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
In drivers/iommu/amd_iommu_init.c (ffffffff82900426)
Location: drivers/iommu/amd_iommu_init.c:1489
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:init_iommu_all
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
In drivers/iommu/amd_iommu_init.c (ffffffff82906165)
Location: drivers/iommu/amd_iommu_init.c:1489
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:init_iommu_all
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct acpi_table_header *ivrs_base</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
