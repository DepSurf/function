# Function: <code>qi_flush_pasid_cache</code>

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
void qi_flush_pasid_cache(struct intel_iommu *iommu, u16 did, u64 granu, int pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff8179e5a0)
Location: drivers/iommu/intel/dmar.c:1486
Inline: False
```
**Symbols:**

```
ffffffff8179e5a0-ffffffff8179e617: qi_flush_pasid_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void qi_flush_pasid_cache(struct intel_iommu *iommu, u16 did, u64 granu, u32 pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff817ac2f0)
Location: drivers/iommu/intel/dmar.c:1523
Inline: False
```
**Symbols:**

```
ffffffff817ac2f0-ffffffff817ac367: qi_flush_pasid_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void qi_flush_pasid_cache(struct intel_iommu *iommu, u16 did, u64 granu, u32 pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff8178f1c0)
Location: drivers/iommu/intel/dmar.c:1592
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:domain_context_clear_one
  - drivers/iommu/intel/iommu.c:iommu_set_root_entry
```
**Symbols:**

```
ffffffff8178f1c0-ffffffff8178f237: qi_flush_pasid_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void qi_flush_pasid_cache(struct intel_iommu *iommu, u16 did, u64 granu, u32 pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff81816ae0)
Location: drivers/iommu/intel/dmar.c:1621
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:domain_context_clear_one
  - drivers/iommu/intel/iommu.c:iommu_set_root_entry
```
**Symbols:**

```
ffffffff81816ae0-ffffffff81816b57: qi_flush_pasid_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void qi_flush_pasid_cache(struct intel_iommu *iommu, u16 did, u64 granu, u32 pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff81957ab0)
Location: drivers/iommu/intel/dmar.c:1617
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:domain_context_clear_one
  - drivers/iommu/intel/iommu.c:iommu_set_root_entry
```
**Symbols:**

```
ffffffff81957ab0-ffffffff81957b35: qi_flush_pasid_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void qi_flush_pasid_cache(struct intel_iommu *iommu, u16 did, u64 granu, u32 pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff81abea50)
Location: drivers/iommu/intel/dmar.c:1606
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:domain_context_clear_one
  - drivers/iommu/intel/iommu.c:iommu_set_root_entry
```
**Symbols:**

```
ffffffff81abea50-ffffffff81abead5: qi_flush_pasid_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void qi_flush_pasid_cache(struct intel_iommu *iommu, u16 did, u64 granu, u32 pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff81b0b3e0)
Location: drivers/iommu/intel/dmar.c:1627
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:domain_context_clear_one
  - drivers/iommu/intel/iommu.c:iommu_set_root_entry
```
**Symbols:**

```
ffffffff81b0b3e0-ffffffff81b0b465: qi_flush_pasid_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void qi_flush_pasid_cache(struct intel_iommu *iommu, u16 did, u64 granu, u32 pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff81b5f450)
Location: drivers/iommu/intel/dmar.c:1645
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:domain_context_clear_one
  - drivers/iommu/intel/iommu.c:iommu_set_root_entry
```
**Symbols:**

```
ffffffff81b5f450-ffffffff81b5f4d5: qi_flush_pasid_cache (STB_GLOBAL)
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
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int pasid</code> ➡️ <code>u32 pasid</code>
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
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
