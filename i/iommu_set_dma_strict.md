# Function: <code>iommu_set_dma_strict</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void iommu_set_dma_strict(bool strict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8179f490)
Location: drivers/iommu/iommu.c:347
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_init_api
  - drivers/iommu/intel/iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff8179f490-ffffffff8179f4b0: iommu_set_dma_strict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void iommu_set_dma_strict();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81828470)
Location: drivers/iommu/iommu.c:367
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:parse_amd_iommu_options
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/intel/iommu.c:quirk_calpella_no_shadow_gtt
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/intel/iommu.c:intel_iommu_setup
```
**Symbols:**

```
ffffffff81828470-ffffffff81828497: iommu_set_dma_strict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void iommu_set_dma_strict();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81968410)
Location: drivers/iommu/iommu.c:374
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:parse_amd_iommu_options
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/intel/iommu.c:quirk_calpella_no_shadow_gtt
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/intel/iommu.c:intel_iommu_setup
```
**Symbols:**

```
ffffffff81968410-ffffffff8196843f: iommu_set_dma_strict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void iommu_set_dma_strict();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81ad2120)
Location: drivers/iommu/iommu.c:501
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:parse_amd_iommu_options
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/intel/iommu.c:quirk_calpella_no_shadow_gtt
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/intel/iommu.c:intel_iommu_setup
```
**Symbols:**

```
ffffffff81ad2120-ffffffff81ad214f: iommu_set_dma_strict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void iommu_set_dma_strict();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81b209f0)
Location: drivers/iommu/iommu.c:571
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:parse_amd_iommu_options
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/intel/iommu.c:quirk_calpella_no_shadow_gtt
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/intel/iommu.c:intel_iommu_setup
```
**Symbols:**

```
ffffffff81b209f0-ffffffff81b20a1f: iommu_set_dma_strict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void iommu_set_dma_strict();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81b77640)
Location: drivers/iommu/iommu.c:701
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:parse_amd_iommu_options
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/intel/iommu.c:quirk_calpella_no_shadow_gtt
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/intel/iommu.c:intel_iommu_setup
```
**Symbols:**

```
ffffffff81b77640-ffffffff81b7766f: iommu_set_dma_strict (STB_GLOBAL)
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
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool strict</code>
</li>
</ul>
</details>
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
