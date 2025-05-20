# Function: <code>domain_get_iommu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct intel_iommu *domain_get_iommu(struct dmar_domain *domain);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815371f0)
Location: drivers/iommu/intel-iommu.c:739
Inline: True
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_map_sg
  - drivers/iommu/intel-iommu.c:__intel_map_single
```
**Symbols:**

```
ffffffff815371f0-ffffffff81537253: domain_get_iommu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct intel_iommu *domain_get_iommu(struct dmar_domain *domain);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8158b630)
Location: drivers/iommu/intel-iommu.c:746
Inline: True
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_map_sg
  - drivers/iommu/intel-iommu.c:__intel_map_single
```
**Symbols:**

```
ffffffff8158b630-ffffffff8158b68a: domain_get_iommu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct intel_iommu *domain_get_iommu(struct dmar_domain *domain);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815b8d80)
Location: drivers/iommu/intel-iommu.c:747
Inline: True
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_map_sg
  - drivers/iommu/intel-iommu.c:__intel_map_single
```
**Symbols:**

```
ffffffff815b8d80-ffffffff815b8dda: domain_get_iommu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct intel_iommu *domain_get_iommu(struct dmar_domain *domain);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815ce590)
Location: drivers/iommu/intel-iommu.c:752
Inline: True
Direct callers:
  - drivers/iommu/intel-iommu.c:__intel_map_single
```
**Symbols:**

```
ffffffff815ce590-ffffffff815ce5f1: domain_get_iommu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct intel_iommu *domain_get_iommu(struct dmar_domain *domain);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81635480)
Location: drivers/iommu/intel-iommu.c:725
Inline: True
Direct callers:
  - drivers/iommu/intel-iommu.c:__intel_map_single
```
**Symbols:**

```
ffffffff81635480-ffffffff816354df: domain_get_iommu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct intel_iommu *domain_get_iommu(struct dmar_domain *domain);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81670a30)
Location: drivers/iommu/intel-iommu.c:727
Inline: True
Direct callers:
  - drivers/iommu/intel-iommu.c:__intel_map_single
```
**Symbols:**

```
ffffffff81670a30-ffffffff81670a8f: domain_get_iommu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct intel_iommu *domain_get_iommu(struct dmar_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816910a0)
Location: drivers/iommu/intel-iommu.c:603
Inline: True
Direct callers:
  - drivers/iommu/intel-iommu.c:__intel_map_page
```
**Symbols:**

```
ffffffff816910a0-ffffffff816910ff: domain_get_iommu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct intel_iommu *domain_get_iommu(struct dmar_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:586
Inline: True
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_unmap
  - drivers/iommu/intel-iommu.c:__intel_map_single
```
**Symbols:**

```
ffffffff816cc406-ffffffff816cc41b: domain_get_iommu.cold (STB_LOCAL)
ffffffff816c9060-ffffffff816c90af: domain_get_iommu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct intel_iommu *domain_get_iommu(struct dmar_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816ec020)
Location: drivers/iommu/intel-iommu.c:597
Inline: True
Direct callers:
  - drivers/iommu/intel-iommu.c:bounce_map_single
  - drivers/iommu/intel-iommu.c:intel_unmap
  - drivers/iommu/intel-iommu.c:__intel_map_single
```
**Symbols:**

```
ffffffff816ec020-ffffffff816ec071: domain_get_iommu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct intel_iommu *domain_get_iommu(struct dmar_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817a3ce0)
Location: drivers/iommu/intel/iommu.c:599
Inline: True
Direct callers:
  - drivers/iommu/intel/iommu.c:bounce_map_single
  - drivers/iommu/intel/iommu.c:intel_map_sg
  - drivers/iommu/intel/iommu.c:intel_unmap
  - drivers/iommu/intel/iommu.c:__intel_map_single
```
**Symbols:**

```
ffffffff817a3ce0-ffffffff817a3d2c: domain_get_iommu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct intel_iommu *domain_get_iommu(struct dmar_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817b0c20)
Location: drivers/iommu/intel/iommu.c:589
Inline: False
```
**Symbols:**

```
ffffffff817b0c20-ffffffff817b0c6c: domain_get_iommu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct intel_iommu *domain_get_iommu(struct dmar_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817936b0)
Location: drivers/iommu/intel/iommu.c:598
Inline: False
```
**Symbols:**

```
ffffffff817936b0-ffffffff817936fc: domain_get_iommu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct intel_iommu *domain_get_iommu(struct dmar_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff8181b4d0)
Location: drivers/iommu/intel/iommu.c:587
Inline: False
```
**Symbols:**

```
ffffffff8181b4d0-ffffffff8181b55a: domain_get_iommu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct intel_iommu *domain_get_iommu(struct dmar_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff8195c240)
Location: drivers/iommu/intel/iommu.c:467
Inline: False
```
**Symbols:**

```
ffffffff8195c240-ffffffff8195c2dc: domain_get_iommu (STB_GLOBAL)
```
</details>
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct intel_iommu *domain_get_iommu(struct dmar_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816b1950)
Location: drivers/iommu/intel-iommu.c:597
Inline: True
Direct callers:
  - drivers/iommu/intel-iommu.c:bounce_map_single
  - drivers/iommu/intel-iommu.c:intel_unmap
  - drivers/iommu/intel-iommu.c:__intel_map_single
```
**Symbols:**

```
ffffffff816b1950-ffffffff816b19a1: domain_get_iommu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct intel_iommu *domain_get_iommu(struct dmar_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8168f450)
Location: drivers/iommu/intel-iommu.c:597
Inline: True
Direct callers:
  - drivers/iommu/intel-iommu.c:bounce_map_single
  - drivers/iommu/intel-iommu.c:intel_unmap
  - drivers/iommu/intel-iommu.c:__intel_map_single
```
**Symbols:**

```
ffffffff8168f450-ffffffff8168f4a1: domain_get_iommu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct intel_iommu *domain_get_iommu(struct dmar_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816dfce0)
Location: drivers/iommu/intel-iommu.c:597
Inline: True
Direct callers:
  - drivers/iommu/intel-iommu.c:bounce_map_single
  - drivers/iommu/intel-iommu.c:intel_unmap
  - drivers/iommu/intel-iommu.c:__intel_map_single
```
**Symbols:**

```
ffffffff816dfce0-ffffffff816dfd31: domain_get_iommu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct intel_iommu *domain_get_iommu(struct dmar_domain *domain);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816fa2f0)
Location: drivers/iommu/intel-iommu.c:597
Inline: True
Direct callers:
  - drivers/iommu/intel-iommu.c:bounce_map_single
  - drivers/iommu/intel-iommu.c:intel_unmap
  - drivers/iommu/intel-iommu.c:__intel_map_single
```
**Symbols:**

```
ffffffff816fa2f0-ffffffff816fa341: domain_get_iommu (STB_GLOBAL)
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
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
</ul>
<b>Arch</b>
<ul>
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
