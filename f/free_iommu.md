# Function: <code>free_iommu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff81066728)
Location: arch/x86/kernel/amd_gart_64.c:129
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_page
```
```
In drivers/iommu/dmar.c (ffffffff8153438b)
Location: drivers/iommu/dmar.c:1085
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_free_drhd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff810664b8)
Location: arch/x86/kernel/amd_gart_64.c:128
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_page
```
```
In drivers/iommu/dmar.c (ffffffff81588c2b)
Location: drivers/iommu/dmar.c:1103
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_free_drhd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff8106a148)
Location: arch/x86/kernel/amd_gart_64.c:128
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_page
```
```
In drivers/iommu/dmar.c (ffffffff815b62eb)
Location: drivers/iommu/dmar.c:1104
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_free_drhd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff8106949f)
Location: arch/x86/kernel/amd_gart_64.c:129
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_page
```
```
In drivers/iommu/dmar.c (ffffffff815cc141)
Location: drivers/iommu/dmar.c:1110
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_free_drhd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff8106dd4f)
Location: arch/x86/kernel/amd_gart_64.c:129
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_page
```
```
In drivers/iommu/dmar.c (ffffffff81632f11)
Location: drivers/iommu/dmar.c:1113
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_free_drhd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff81070c4f)
Location: arch/x86/kernel/amd_gart_64.c:130
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_page
```
```
In drivers/iommu/dmar.c (ffffffff8166e131)
Location: drivers/iommu/dmar.c:1113
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_free_drhd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff81076c42)
Location: arch/x86/kernel/amd_gart_64.c:126
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_page
```
```
In drivers/iommu/dmar.c (ffffffff8168c561)
Location: drivers/iommu/dmar.c:1113
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_free_drhd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff8107a7e2)
Location: arch/x86/kernel/amd_gart_64.c:126
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_page
```
```
In drivers/iommu/dmar.c (ffffffff816c3fb1)
Location: drivers/iommu/dmar.c:1102
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_free_drhd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff8107b8d2)
Location: arch/x86/kernel/amd_gart_64.c:126
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_page
```
```
In drivers/iommu/dmar.c (ffffffff816e6f01)
Location: drivers/iommu/dmar.c:1112
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_free_drhd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Selective Inline ⚠️</summary>

```c
void free_iommu(long unsigned int offset, int size);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff81082bd2)
Location: arch/x86/kernel/amd_gart_64.c:125
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_page
```
```
In drivers/iommu/intel/dmar.c (ffffffff8179ceb0)
Location: drivers/iommu/intel/dmar.c:1118
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_hp_release_drhd
```
**Symbols:**

```
ffffffff8179ceb0-ffffffff8179cfb4: free_iommu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Selective Inline ⚠️</summary>

```c
void free_iommu(long unsigned int offset, int size);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff81084642)
Location: arch/x86/kernel/amd_gart_64.c:125
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_page
```
```
In drivers/iommu/intel/dmar.c (ffffffff817aab80)
Location: drivers/iommu/intel/dmar.c:1157
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_hp_release_drhd
```
**Symbols:**

```
ffffffff817aab80-ffffffff817aac91: free_iommu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff810853a7)
Location: arch/x86/kernel/amd_gart_64.c:125
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_page
```
```
In drivers/iommu/intel/dmar.c (ffffffff8178e241)
Location: drivers/iommu/intel/dmar.c:1164
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_free_drhd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff81094317)
Location: arch/x86/kernel/amd_gart_64.c:125
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_page
```
```
In drivers/iommu/intel/dmar.c (ffffffff81815ad1)
Location: drivers/iommu/intel/dmar.c:1163
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_free_drhd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff810a6507)
Location: arch/x86/kernel/amd_gart_64.c:123
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_page
```
```
In drivers/iommu/intel/dmar.c (ffffffff81956951)
Location: drivers/iommu/intel/dmar.c:1159
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_free_drhd
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Selective Inline ⚠️</summary>

```c
void free_iommu(long unsigned int offset, int size);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff810bf410)
Location: arch/x86/kernel/amd_gart_64.c:123
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_page
```
```
In drivers/iommu/intel/dmar.c (ffffffff81abd7a1)
Location: drivers/iommu/intel/dmar.c:1148
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_free_drhd
```
**Symbols:**

```
ffffffff810bf410-ffffffff810bf479: free_iommu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Selective Inline ⚠️</summary>

```c
void free_iommu(long unsigned int offset, int size);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff810c2ad0)
Location: arch/x86/kernel/amd_gart_64.c:123
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_page
```
```
In drivers/iommu/intel/dmar.c (ffffffff81b0a101)
Location: drivers/iommu/intel/dmar.c:1166
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_free_drhd
```
**Symbols:**

```
ffffffff810c2ad0-ffffffff810c2b39: free_iommu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Selective Inline ⚠️</summary>

```c
void free_iommu(long unsigned int offset, int size);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff810caf10)
Location: arch/x86/kernel/amd_gart_64.c:123
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_page
```
```
In drivers/iommu/intel/dmar.c (ffffffff81b5e151)
Location: drivers/iommu/intel/dmar.c:1166
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_free_drhd
```
**Symbols:**

```
ffffffff810caf10-ffffffff810caf79: free_iommu (STB_LOCAL)
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
<summary>In <code>aws</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff8107a8d2)
Location: arch/x86/kernel/amd_gart_64.c:126
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_page
```
```
In drivers/iommu/dmar.c (ffffffff816ac9e1)
Location: drivers/iommu/dmar.c:1112
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_free_drhd
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff8106a002)
Location: arch/x86/kernel/amd_gart_64.c:126
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_page
```
```
In drivers/iommu/dmar.c (ffffffff8168a341)
Location: drivers/iommu/dmar.c:1112
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_free_drhd
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff8107a882)
Location: arch/x86/kernel/amd_gart_64.c:126
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_page
```
```
In drivers/iommu/dmar.c (ffffffff816dabc1)
Location: drivers/iommu/dmar.c:1112
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_free_drhd
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff8107c982)
Location: arch/x86/kernel/amd_gart_64.c:126
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_unmap_page
```
```
In drivers/iommu/dmar.c (ffffffff816f5171)
Location: drivers/iommu/dmar.c:1112
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_free_drhd
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
