# Function: <code>switch_to_super_page</code>

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
void switch_to_super_page(struct dmar_domain *domain, long unsigned int start_pfn, long unsigned int end_pfn, int level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81792ba0)
Location: drivers/iommu/intel/iommu.c:2308
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:__domain_mapping
```
**Symbols:**

```
ffffffff81792ba0-ffffffff81792d85: switch_to_super_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void switch_to_super_page(struct dmar_domain *domain, long unsigned int start_pfn, long unsigned int end_pfn, int level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:2300
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:__domain_mapping
```
**Symbols:**

```
ffffffff8181aa20-ffffffff8181ac3d: switch_to_super_page (STB_LOCAL)
ffffffff81cff981-ffffffff81cffa52: switch_to_super_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void switch_to_super_page(struct dmar_domain *domain, long unsigned int start_pfn, long unsigned int end_pfn, int level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:2192
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:__domain_mapping
```
**Symbols:**

```
ffffffff8195b170-ffffffff8195b311: switch_to_super_page (STB_LOCAL)
ffffffff81ec80bf-ffffffff81ec80fd: switch_to_super_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void switch_to_super_page(struct dmar_domain *domain, long unsigned int start_pfn, long unsigned int end_pfn, int level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:2151
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:__domain_mapping
```
**Symbols:**

```
ffffffff81ac2d60-ffffffff81ac2f10: switch_to_super_page (STB_LOCAL)
ffffffff82097955-ffffffff82097993: switch_to_super_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void switch_to_super_page(struct dmar_domain *domain, long unsigned int start_pfn, long unsigned int end_pfn, int level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:2113
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:__domain_mapping
```
**Symbols:**

```
ffffffff81b0fc00-ffffffff81b0fe18: switch_to_super_page (STB_LOCAL)
ffffffff821188b0-ffffffff82118905: switch_to_super_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void switch_to_super_page(struct dmar_domain *domain, long unsigned int start_pfn, long unsigned int end_pfn, int level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:2024
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:__domain_mapping
```
**Symbols:**

```
ffffffff81b64650-ffffffff81b64882: switch_to_super_page (STB_LOCAL)
ffffffff821f65e4-ffffffff821f6639: switch_to_super_page.cold (STB_LOCAL)
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
