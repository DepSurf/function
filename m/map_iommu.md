# Function: <code>map_iommu</code>

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
In drivers/iommu/dmar.c (ffffffff81533fd2)
Location: drivers/iommu/dmar.c:917
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
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
In drivers/iommu/dmar.c (ffffffff81588860)
Location: drivers/iommu/dmar.c:929
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
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
In drivers/iommu/dmar.c (ffffffff815b5f20)
Location: drivers/iommu/dmar.c:930
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
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
In drivers/iommu/dmar.c (ffffffff815cbd4e)
Location: drivers/iommu/dmar.c:933
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
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
In drivers/iommu/dmar.c (ffffffff81632b1e)
Location: drivers/iommu/dmar.c:936
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
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
In drivers/iommu/dmar.c (ffffffff8166dd86)
Location: drivers/iommu/dmar.c:936
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
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
In drivers/iommu/dmar.c (ffffffff8168c1b6)
Location: drivers/iommu/dmar.c:936
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
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
In drivers/iommu/dmar.c (ffffffff816c3826)
Location: drivers/iommu/dmar.c:925
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:alloc_iommu
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
In drivers/iommu/dmar.c (ffffffff816e6776)
Location: drivers/iommu/dmar.c:935
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:alloc_iommu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int map_iommu(struct intel_iommu *iommu, u64 phys_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (0)
Location: drivers/iommu/intel/dmar.c:939
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:alloc_iommu
```
**Symbols:**

```
ffffffff8179c350-ffffffff8179c4d4: map_iommu (STB_LOCAL)
ffffffff8179eb8b-ffffffff8179ebb7: map_iommu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int map_iommu(struct intel_iommu *iommu, u64 phys_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (0)
Location: drivers/iommu/intel/dmar.c:961
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:alloc_iommu
```
**Symbols:**

```
ffffffff817aa020-ffffffff817aa1af: map_iommu (STB_LOCAL)
ffffffff81c0bfb6-ffffffff81c0bfe2: map_iommu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int map_iommu(struct intel_iommu *iommu, u64 phys_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (0)
Location: drivers/iommu/intel/dmar.c:968
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:alloc_iommu
```
**Symbols:**

```
ffffffff8178cda0-ffffffff8178cf34: map_iommu (STB_LOCAL)
ffffffff81bfd7cf-ffffffff81bfd7fb: map_iommu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int map_iommu(struct intel_iommu *iommu, u64 phys_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (0)
Location: drivers/iommu/intel/dmar.c:967
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:alloc_iommu
```
**Symbols:**

```
ffffffff81814660-ffffffff818147f4: map_iommu (STB_LOCAL)
ffffffff81cfed05-ffffffff81cfed31: map_iommu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int map_iommu(struct intel_iommu *iommu, u64 phys_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (0)
Location: drivers/iommu/intel/dmar.c:963
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:alloc_iommu
```
**Symbols:**

```
ffffffff819554e0-ffffffff81955683: map_iommu (STB_LOCAL)
ffffffff81ec7512-ffffffff81ec753e: map_iommu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int map_iommu(struct intel_iommu *iommu, u64 phys_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff81abbb10)
Location: drivers/iommu/intel/dmar.c:964
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:alloc_iommu
```
**Symbols:**

```
ffffffff81abbb10-ffffffff81abbce8: map_iommu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int map_iommu(struct intel_iommu *iommu, struct dmar_drhd_unit *drhd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff81b083f0)
Location: drivers/iommu/intel/dmar.c:966
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:alloc_iommu
```
**Symbols:**

```
ffffffff81b083f0-ffffffff81b08606: map_iommu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int map_iommu(struct intel_iommu *iommu, struct dmar_drhd_unit *drhd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff81b5c410)
Location: drivers/iommu/intel/dmar.c:966
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:alloc_iommu
```
**Symbols:**

```
ffffffff81b5c410-ffffffff81b5c626: map_iommu (STB_LOCAL)
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
In drivers/iommu/dmar.c (ffffffff816ac256)
Location: drivers/iommu/dmar.c:935
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:alloc_iommu
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
In drivers/iommu/dmar.c (ffffffff81689bb6)
Location: drivers/iommu/dmar.c:935
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:alloc_iommu
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
In drivers/iommu/dmar.c (ffffffff816da436)
Location: drivers/iommu/dmar.c:935
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:alloc_iommu
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
In drivers/iommu/dmar.c (ffffffff816f49e6)
Location: drivers/iommu/dmar.c:935
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:alloc_iommu
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct dmar_drhd_unit *drhd</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 phys_addr</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
