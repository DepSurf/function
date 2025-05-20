# Function: <code>vcmd_free_pasid</code>

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
void vcmd_free_pasid(struct intel_iommu *iommu, unsigned int pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/pasid.c (0)
Location: drivers/iommu/intel/pasid.c:61
Inline: False
```
**Symbols:**

```
ffffffff817a85d9-ffffffff817a85fb: vcmd_free_pasid.cold (STB_LOCAL)
ffffffff817a76f0-ffffffff817a77ac: vcmd_free_pasid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void vcmd_free_pasid(struct intel_iommu *iommu, u32 pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/pasid.c (0)
Location: drivers/iommu/intel/pasid.c:61
Inline: False
```
**Symbols:**

```
ffffffff81c0ccb2-ffffffff81c0ccd4: vcmd_free_pasid.cold (STB_LOCAL)
ffffffff817b3590-ffffffff817b364c: vcmd_free_pasid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void vcmd_free_pasid(struct intel_iommu *iommu, u32 pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/pasid.c (0)
Location: drivers/iommu/intel/pasid.c:60
Inline: False
```
**Symbols:**

```
ffffffff81bfe3fd-ffffffff81bfe41f: vcmd_free_pasid.cold (STB_LOCAL)
ffffffff817966c0-ffffffff8179677c: vcmd_free_pasid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void vcmd_free_pasid(struct intel_iommu *iommu, u32 pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/pasid.c (0)
Location: drivers/iommu/intel/pasid.c:60
Inline: False
```
**Symbols:**

```
ffffffff81d00276-ffffffff81d00298: vcmd_free_pasid.cold (STB_LOCAL)
ffffffff8181e650-ffffffff8181e70b: vcmd_free_pasid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void vcmd_free_pasid(struct intel_iommu *iommu, u32 pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/pasid.c (0)
Location: drivers/iommu/intel/pasid.c:60
Inline: False
```
**Symbols:**

```
ffffffff81ec8899-ffffffff81ec88bb: vcmd_free_pasid.cold (STB_LOCAL)
ffffffff8195ea20-ffffffff8195eaea: vcmd_free_pasid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void vcmd_free_pasid(struct intel_iommu *iommu, u32 pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/pasid.c (ffffffff81ac6490)
Location: drivers/iommu/intel/pasid.c:60
Inline: False
```
**Symbols:**

```
ffffffff81ac6490-ffffffff81ac656f: vcmd_free_pasid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void vcmd_free_pasid(struct intel_iommu *iommu, u32 pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/pasid.c (ffffffff81b13070)
Location: drivers/iommu/intel/pasid.c:60
Inline: False
```
**Symbols:**

```
ffffffff81b13070-ffffffff81b1315d: vcmd_free_pasid (STB_GLOBAL)
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
<code>unsigned int pasid</code> ➡️ <code>u32 pasid</code>
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
