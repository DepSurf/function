# Function: <code>intel_cap_smts_sanity</code>

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
bool intel_cap_smts_sanity();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/cap_audit.c (ffffffff817984e0)
Location: drivers/iommu/intel/cap_audit.c:187
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_enable_nesting
  - drivers/iommu/intel/iommu.c:intel_iommu_dev_feat_enabled
  - drivers/iommu/intel/iommu.c:alloc_domain
```
**Symbols:**

```
ffffffff817984e0-ffffffff817984f9: intel_cap_smts_sanity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool intel_cap_smts_sanity();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/cap_audit.c (ffffffff81820d20)
Location: drivers/iommu/intel/cap_audit.c:187
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_dev_feat_enabled
  - drivers/iommu/intel/iommu.c:alloc_domain
```
**Symbols:**

```
ffffffff81820d20-ffffffff81820d39: intel_cap_smts_sanity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool intel_cap_smts_sanity();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/cap_audit.c (ffffffff81960deb)
Location: drivers/iommu/intel/cap_audit.c:196
Inline: True
Inline callers:
  - drivers/iommu/intel/cap_audit.c:intel_cap_audit
Direct callers:
  - drivers/iommu/intel/iommu.c:alloc_domain
```
**Symbols:**

```
ffffffff81960e50-ffffffff81960e6d: intel_cap_smts_sanity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool intel_cap_smts_sanity();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/cap_audit.c (ffffffff81ac98c6)
Location: drivers/iommu/intel/cap_audit.c:196
Inline: True
Inline callers:
  - drivers/iommu/intel/cap_audit.c:intel_cap_audit
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff81ac9960-ffffffff81ac997d: intel_cap_smts_sanity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool intel_cap_smts_sanity();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/cap_audit.c (ffffffff81b1645a)
Location: drivers/iommu/intel/cap_audit.c:194
Inline: True
Inline callers:
  - drivers/iommu/intel/cap_audit.c:intel_cap_audit
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff81b164f0-ffffffff81b1650d: intel_cap_smts_sanity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool intel_cap_smts_sanity();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/cap_audit.c (ffffffff81b6bd9a)
Location: drivers/iommu/intel/cap_audit.c:194
Inline: True
Inline callers:
  - drivers/iommu/intel/cap_audit.c:intel_cap_audit
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff81b6be30-ffffffff81b6be4d: intel_cap_smts_sanity (STB_GLOBAL)
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
