# Function: <code>init_iommu_from_acpi</code>

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
In drivers/iommu/amd_iommu_init.c (ffffffff81fa9252)
Location: drivers/iommu/amd_iommu_init.c:779
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:init_iommu_all
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int init_iommu_from_acpi(struct amd_iommu *iommu, struct ivhd_header *h);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff81fd582c)
Location: drivers/iommu/amd_iommu_init.c:878
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
```
**Symbols:**

```
ffffffff81fd582c-ffffffff81fd5f2e: init_iommu_from_acpi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int init_iommu_from_acpi(struct amd_iommu *iommu, struct ivhd_header *h);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff820139b0)
Location: drivers/iommu/amd_iommu_init.c:980
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
```
**Symbols:**

```
ffffffff820139b0-ffffffff820140b2: init_iommu_from_acpi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int init_iommu_from_acpi(struct amd_iommu *iommu, struct ivhd_header *h);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff820f4f0e)
Location: drivers/iommu/amd_iommu_init.c:989
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
```
**Symbols:**

```
ffffffff820f4f0e-ffffffff820f562d: init_iommu_from_acpi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int init_iommu_from_acpi(struct amd_iommu *iommu, struct ivhd_header *h);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff826fe5ce)
Location: drivers/iommu/amd_iommu_init.c:1124
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
```
**Symbols:**

```
ffffffff826fe5ce-ffffffff826feced: init_iommu_from_acpi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int init_iommu_from_acpi(struct amd_iommu *iommu, struct ivhd_header *h);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff8272888e)
Location: drivers/iommu/amd_iommu_init.c:1124
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
```
**Symbols:**

```
ffffffff8272888e-ffffffff82728fcc: init_iommu_from_acpi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int init_iommu_from_acpi(struct amd_iommu *iommu, struct ivhd_header *h);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff828e0add)
Location: drivers/iommu/amd_iommu_init.c:1151
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
```
**Symbols:**

```
ffffffff828e0add-ffffffff828e121b: init_iommu_from_acpi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int init_iommu_from_acpi(struct amd_iommu *iommu, struct ivhd_header *h);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff828fb936)
Location: drivers/iommu/amd_iommu_init.c:1139
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:init_iommu_all
```
**Symbols:**

```
ffffffff828fb936-ffffffff828fc08a: init_iommu_from_acpi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int init_iommu_from_acpi(struct amd_iommu *iommu, struct ivhd_header *h);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff829048de)
Location: drivers/iommu/amd_iommu_init.c:1140
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:init_iommu_all
```
**Symbols:**

```
ffffffff829048de-ffffffff8290503d: init_iommu_from_acpi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int init_iommu_from_acpi(struct amd_iommu *iommu, struct ivhd_header *h);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff82d1b7fd)
Location: drivers/iommu/amd/init.c:1117
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:init_iommu_one
```
**Symbols:**

```
ffffffff82d1b7fd-ffffffff82d1bea8: init_iommu_from_acpi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int init_iommu_from_acpi(struct amd_iommu *iommu, struct ivhd_header *h);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff830095cd)
Location: drivers/iommu/amd/init.c:1180
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:init_iommu_one
```
**Symbols:**

```
ffffffff830095cd-ffffffff83009c78: init_iommu_from_acpi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int init_iommu_from_acpi(struct amd_iommu *iommu, struct ivhd_header *h);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff83214042)
Location: drivers/iommu/amd/init.c:1176
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:init_iommu_one
```
**Symbols:**

```
ffffffff83214042-ffffffff832147a5: init_iommu_from_acpi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int init_iommu_from_acpi(struct amd_iommu *iommu, struct ivhd_header *h);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff832fd384)
Location: drivers/iommu/amd/init.c:1187
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:init_iommu_one
```
**Symbols:**

```
ffffffff832fd384-ffffffff832fdd6f: init_iommu_from_acpi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int init_iommu_from_acpi(struct amd_iommu *iommu, struct ivhd_header *h);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff834b5f81)
Location: drivers/iommu/amd/init.c:1193
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:init_iommu_one
```
**Symbols:**

```
ffffffff834b5f81-ffffffff834b697c: init_iommu_from_acpi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int init_iommu_from_acpi(struct amd_iommu *iommu, struct ivhd_header *h);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff83ef2200)
Location: drivers/iommu/amd/init.c:1291
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:init_iommu_one
```
**Symbols:**

```
ffffffff83ef2200-ffffffff83ef3067: init_iommu_from_acpi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int init_iommu_from_acpi(struct amd_iommu *iommu, struct ivhd_header *h);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff83717e30)
Location: drivers/iommu/amd/init.c:1326
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:init_iommu_one
```
**Symbols:**

```
ffffffff83717e30-ffffffff83718c15: init_iommu_from_acpi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int init_iommu_from_acpi(struct amd_iommu *iommu, struct ivhd_header *h);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff8394b8f0)
Location: drivers/iommu/amd/init.c:1341
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:init_iommu_one
```
**Symbols:**

```
ffffffff8394b8f0-ffffffff8394c6d5: init_iommu_from_acpi (STB_LOCAL)
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
int init_iommu_from_acpi(struct amd_iommu *iommu, struct ivhd_header *h);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff828ec0c5)
Location: drivers/iommu/amd_iommu_init.c:1140
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:init_iommu_all
```
**Symbols:**

```
ffffffff828ec0c5-ffffffff828ec824: init_iommu_from_acpi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int init_iommu_from_acpi(struct amd_iommu *iommu, struct ivhd_header *h);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff828e3552)
Location: drivers/iommu/amd_iommu_init.c:1140
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:init_iommu_all
```
**Symbols:**

```
ffffffff828e3552-ffffffff828e3cb1: init_iommu_from_acpi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int init_iommu_from_acpi(struct amd_iommu *iommu, struct ivhd_header *h);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff828ffc01)
Location: drivers/iommu/amd_iommu_init.c:1140
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:init_iommu_all
```
**Symbols:**

```
ffffffff828ffc01-ffffffff82900360: init_iommu_from_acpi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int init_iommu_from_acpi(struct amd_iommu *iommu, struct ivhd_header *h);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff82905940)
Location: drivers/iommu/amd_iommu_init.c:1140
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:init_iommu_all
```
**Symbols:**

```
ffffffff82905940-ffffffff8290609f: init_iommu_from_acpi (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
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
