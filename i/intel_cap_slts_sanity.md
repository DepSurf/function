# Function: <code>intel_cap_slts_sanity</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool intel_cap_slts_sanity();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/cap_audit.c (ffffffff81960e00)
Location: drivers/iommu/intel/cap_audit.c:216
Inline: True
Inline callers:
  - drivers/iommu/intel/cap_audit.c:intel_cap_audit
Direct callers:
  - drivers/iommu/intel/iommu.c:alloc_domain
```
**Symbols:**

```
ffffffff81960ed0-ffffffff81960eed: intel_cap_slts_sanity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool intel_cap_slts_sanity();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/cap_audit.c (ffffffff81ac98db)
Location: drivers/iommu/intel/cap_audit.c:216
Inline: True
Inline callers:
  - drivers/iommu/intel/cap_audit.c:intel_cap_audit
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff81ac9a20-ffffffff81ac9a3d: intel_cap_slts_sanity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool intel_cap_slts_sanity();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/cap_audit.c (ffffffff81b165b0)
Location: drivers/iommu/intel/cap_audit.c:214
Inline: True
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff81b165b0-ffffffff81b165cd: intel_cap_slts_sanity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool intel_cap_slts_sanity();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/cap_audit.c (ffffffff81b6bef0)
Location: drivers/iommu/intel/cap_audit.c:214
Inline: True
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff81b6bef0-ffffffff81b6bf0d: intel_cap_slts_sanity (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
