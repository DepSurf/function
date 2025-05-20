# Function: <code>request_default_domain_for_dev</code>

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
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int request_default_domain_for_dev(struct device *dev, long unsigned int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (0)
Location: drivers/iommu/iommu.c:2133
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_request_dma_domain_for_dev
  - drivers/iommu/iommu.c:iommu_request_dm_for_dev
```
**Symbols:**

```
ffffffff816b7930-ffffffff816b7a94: request_default_domain_for_dev (STB_LOCAL)
ffffffff816b89c1-ffffffff816b89f3: request_default_domain_for_dev.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int request_default_domain_for_dev(struct device *dev, long unsigned int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816da660)
Location: drivers/iommu/iommu.c:2191
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_request_dma_domain_for_dev
  - drivers/iommu/iommu.c:iommu_request_dm_for_dev
```
**Symbols:**

```
ffffffff816da660-ffffffff816da7e9: request_default_domain_for_dev (STB_LOCAL)
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
int request_default_domain_for_dev(struct device *dev, long unsigned int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffff8000108c6730)
Location: drivers/iommu/iommu.c:2191
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_request_dma_domain_for_dev
  - drivers/iommu/iommu.c:iommu_request_dm_for_dev
```
**Symbols:**

```
ffff8000108c6730-ffff8000108c68a0: request_default_domain_for_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int request_default_domain_for_dev(struct device *dev, long unsigned int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c09bd498)
Location: drivers/iommu/iommu.c:2191
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_request_dma_domain_for_dev
  - drivers/iommu/iommu.c:iommu_request_dm_for_dev
```
**Symbols:**

```
c09bd498-c09bd610: request_default_domain_for_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int request_default_domain_for_dev(struct device *dev, long unsigned int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c00000000096c270)
Location: drivers/iommu/iommu.c:2191
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_request_dma_domain_for_dev
  - drivers/iommu/iommu.c:iommu_request_dm_for_dev
```
**Symbols:**

```
c00000000096c270-c00000000096c484: request_default_domain_for_dev (STB_LOCAL)
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
int request_default_domain_for_dev(struct device *dev, long unsigned int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816a00b0)
Location: drivers/iommu/iommu.c:2191
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_request_dma_domain_for_dev
  - drivers/iommu/iommu.c:iommu_request_dm_for_dev
```
**Symbols:**

```
ffffffff816a00b0-ffffffff816a0239: request_default_domain_for_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int request_default_domain_for_dev(struct device *dev, long unsigned int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8167daa0)
Location: drivers/iommu/iommu.c:2191
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_request_dma_domain_for_dev
  - drivers/iommu/iommu.c:iommu_request_dm_for_dev
```
**Symbols:**

```
ffffffff8167daa0-ffffffff8167dc29: request_default_domain_for_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int request_default_domain_for_dev(struct device *dev, long unsigned int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816ce320)
Location: drivers/iommu/iommu.c:2191
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_request_dma_domain_for_dev
  - drivers/iommu/iommu.c:iommu_request_dm_for_dev
```
**Symbols:**

```
ffffffff816ce320-ffffffff816ce4a9: request_default_domain_for_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int request_default_domain_for_dev(struct device *dev, long unsigned int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816e8870)
Location: drivers/iommu/iommu.c:2191
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_request_dma_domain_for_dev
  - drivers/iommu/iommu.c:iommu_request_dm_for_dev
```
**Symbols:**

```
ffffffff816e8870-ffffffff816e89f9: request_default_domain_for_dev (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
