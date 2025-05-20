# Function: <code>iommu_request_dm_for_dev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int iommu_request_dm_for_dev(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8152ba80)
Location: drivers/iommu/iommu.c:1577
Inline: False
```
**Symbols:**

```
ffffffff8152ba80-ffffffff8152bbb5: iommu_request_dm_for_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int iommu_request_dm_for_dev(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8157eed0)
Location: drivers/iommu/iommu.c:1565
Inline: False
```
**Symbols:**

```
ffffffff8157eed0-ffffffff8157f01a: iommu_request_dm_for_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int iommu_request_dm_for_dev(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff815ab960)
Location: drivers/iommu/iommu.c:1734
Inline: False
```
**Symbols:**

```
ffffffff815ab960-ffffffff815abaaa: iommu_request_dm_for_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int iommu_request_dm_for_dev(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff815c1630)
Location: drivers/iommu/iommu.c:1826
Inline: False
```
**Symbols:**

```
ffffffff815c1630-ffffffff815c1777: iommu_request_dm_for_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int iommu_request_dm_for_dev(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81627df0)
Location: drivers/iommu/iommu.c:1849
Inline: False
```
**Symbols:**

```
ffffffff81627df0-ffffffff81627f49: iommu_request_dm_for_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int iommu_request_dm_for_dev(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (0)
Location: drivers/iommu/iommu.c:1855
Inline: False
```
**Symbols:**

```
ffffffff81662d36-ffffffff81662d5f: iommu_request_dm_for_dev.cold.23 (STB_LOCAL)
ffffffff816629b0-ffffffff81662b08: iommu_request_dm_for_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int iommu_request_dm_for_dev(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (0)
Location: drivers/iommu/iommu.c:1912
Inline: False
```
**Symbols:**

```
ffffffff81681318-ffffffff81681341: iommu_request_dm_for_dev.cold.25 (STB_LOCAL)
ffffffff81680f90-ffffffff816810e8: iommu_request_dm_for_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int iommu_request_dm_for_dev(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816b8790)
Location: drivers/iommu/iommu.c:2188
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_add_device
```
**Symbols:**

```
ffffffff816b8790-ffffffff816b87a5: iommu_request_dm_for_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int iommu_request_dm_for_dev(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816db5b0)
Location: drivers/iommu/iommu.c:2244
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_add_device
```
**Symbols:**

```
ffffffff816db5b0-ffffffff816db5c5: iommu_request_dm_for_dev (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
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
<summary>In <code>arm64</code>: ✅</summary>

```c
int iommu_request_dm_for_dev(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffff8000108c75a8)
Location: drivers/iommu/iommu.c:2244
Inline: False
```
**Symbols:**

```
ffff8000108c75a8-ffff8000108c75d8: iommu_request_dm_for_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int iommu_request_dm_for_dev(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c09be54c)
Location: drivers/iommu/iommu.c:2244
Inline: False
```
**Symbols:**

```
c09be54c-c09be56c: iommu_request_dm_for_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int iommu_request_dm_for_dev(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c00000000096e560)
Location: drivers/iommu/iommu.c:2244
Inline: False
```
**Symbols:**

```
c00000000096e560-c00000000096e578: iommu_request_dm_for_dev (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
int iommu_request_dm_for_dev(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816a1000)
Location: drivers/iommu/iommu.c:2244
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_add_device
```
**Symbols:**

```
ffffffff816a1000-ffffffff816a1015: iommu_request_dm_for_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int iommu_request_dm_for_dev(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8167e9f0)
Location: drivers/iommu/iommu.c:2244
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_add_device
```
**Symbols:**

```
ffffffff8167e9f0-ffffffff8167ea05: iommu_request_dm_for_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int iommu_request_dm_for_dev(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816cf270)
Location: drivers/iommu/iommu.c:2244
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_add_device
```
**Symbols:**

```
ffffffff816cf270-ffffffff816cf285: iommu_request_dm_for_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int iommu_request_dm_for_dev(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816e97e0)
Location: drivers/iommu/iommu.c:2244
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_add_device
```
**Symbols:**

```
ffffffff816e97e0-ffffffff816e97f5: iommu_request_dm_for_dev (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
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
