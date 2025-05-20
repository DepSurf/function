# Function: <code>vcmd_alloc_pasid</code>

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
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int vcmd_alloc_pasid(struct intel_iommu *iommu, unsigned int *pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/pasid.c (0)
Location: drivers/iommu/intel/pasid.c:30
Inline: False
```
**Symbols:**

```
ffffffff817a85b3-ffffffff817a85d9: vcmd_alloc_pasid.cold (STB_LOCAL)
ffffffff817a7610-ffffffff817a76e6: vcmd_alloc_pasid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int vcmd_alloc_pasid(struct intel_iommu *iommu, u32 *pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/pasid.c (0)
Location: drivers/iommu/intel/pasid.c:30
Inline: False
```
**Symbols:**

```
ffffffff81c0cc8c-ffffffff81c0ccb2: vcmd_alloc_pasid.cold (STB_LOCAL)
ffffffff817b34b0-ffffffff817b3586: vcmd_alloc_pasid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int vcmd_alloc_pasid(struct intel_iommu *iommu, u32 *pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/pasid.c (0)
Location: drivers/iommu/intel/pasid.c:29
Inline: False
```
**Symbols:**

```
ffffffff81bfe3d7-ffffffff81bfe3fd: vcmd_alloc_pasid.cold (STB_LOCAL)
ffffffff817965f0-ffffffff817966b7: vcmd_alloc_pasid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int vcmd_alloc_pasid(struct intel_iommu *iommu, u32 *pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/pasid.c (0)
Location: drivers/iommu/intel/pasid.c:29
Inline: False
```
**Symbols:**

```
ffffffff81d00250-ffffffff81d00276: vcmd_alloc_pasid.cold (STB_LOCAL)
ffffffff8181e580-ffffffff8181e646: vcmd_alloc_pasid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int vcmd_alloc_pasid(struct intel_iommu *iommu, u32 *pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/pasid.c (0)
Location: drivers/iommu/intel/pasid.c:29
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_vcmd_ioasid_alloc
```
**Symbols:**

```
ffffffff81ec8873-ffffffff81ec8899: vcmd_alloc_pasid.cold (STB_LOCAL)
ffffffff8195e940-ffffffff8195ea14: vcmd_alloc_pasid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int vcmd_alloc_pasid(struct intel_iommu *iommu, u32 *pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/pasid.c (ffffffff81ac6360)
Location: drivers/iommu/intel/pasid.c:29
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_vcmd_ioasid_alloc
```
**Symbols:**

```
ffffffff81ac6360-ffffffff81ac6476: vcmd_alloc_pasid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int vcmd_alloc_pasid(struct intel_iommu *iommu, u32 *pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/pasid.c (ffffffff81b12f30)
Location: drivers/iommu/intel/pasid.c:29
Inline: False
```
**Symbols:**

```
ffffffff81b12f30-ffffffff81b13055: vcmd_alloc_pasid (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>unsigned int *pasid</code> ➡️ <code>u32 *pasid</code>
</li>
</ul>
</details>
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
