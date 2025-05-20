# Function: <code>copy_reserved_iova</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void copy_reserved_iova(struct iova_domain *from, struct iova_domain *to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff8152d2c0)
Location: drivers/iommu/iova.c:493
Inline: False
```
**Symbols:**

```
ffffffff8152d2c0-ffffffff8152d33d: copy_reserved_iova (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void copy_reserved_iova(struct iova_domain *from, struct iova_domain *to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff81580640)
Location: drivers/iommu/iova.c:574
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
```
**Symbols:**

```
ffffffff81580640-ffffffff815806c4: copy_reserved_iova (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void copy_reserved_iova(struct iova_domain *from, struct iova_domain *to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff815ad1e0)
Location: drivers/iommu/iova.c:574
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
```
**Symbols:**

```
ffffffff815ad1e0-ffffffff815ad264: copy_reserved_iova (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void copy_reserved_iova(struct iova_domain *from, struct iova_domain *to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff815c2d70)
Location: drivers/iommu/iova.c:548
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
```
**Symbols:**

```
ffffffff815c2d70-ffffffff815c2df4: copy_reserved_iova (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void copy_reserved_iova(struct iova_domain *from, struct iova_domain *to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff81629860)
Location: drivers/iommu/iova.c:696
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
```
**Symbols:**

```
ffffffff81629860-ffffffff816298ea: copy_reserved_iova (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void copy_reserved_iova(struct iova_domain *from, struct iova_domain *to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iova.c (0)
Location: drivers/iommu/iova.c:696
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
```
**Symbols:**

```
ffffffff81665349-ffffffff8166535d: copy_reserved_iova.cold.18 (STB_LOCAL)
ffffffff81664570-ffffffff816645ed: copy_reserved_iova (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void copy_reserved_iova(struct iova_domain *from, struct iova_domain *to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iova.c (0)
Location: drivers/iommu/iova.c:705
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
```
**Symbols:**

```
ffffffff81683949-ffffffff8168395d: copy_reserved_iova.cold.18 (STB_LOCAL)
ffffffff81682700-ffffffff8168277d: copy_reserved_iova (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void copy_reserved_iova(struct iova_domain *from, struct iova_domain *to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iova.c (0)
Location: drivers/iommu/iova.c:704
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
```
**Symbols:**

```
ffffffff816bb104-ffffffff816bb11d: copy_reserved_iova.cold (STB_LOCAL)
ffffffff816b9f10-ffffffff816b9f84: copy_reserved_iova (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void copy_reserved_iova(struct iova_domain *from, struct iova_domain *to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iova.c (0)
Location: drivers/iommu/iova.c:706
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
```
**Symbols:**

```
ffffffff816ddf1c-ffffffff816ddf35: copy_reserved_iova.cold (STB_LOCAL)
ffffffff816dcd20-ffffffff816dcd94: copy_reserved_iova (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void copy_reserved_iova(struct iova_domain *from, struct iova_domain *to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iova.c (0)
Location: drivers/iommu/iova.c:706
Inline: False
```
**Symbols:**

```
ffffffff81794bec-ffffffff81794c05: copy_reserved_iova.cold (STB_LOCAL)
ffffffff81793cd0-ffffffff81793d44: copy_reserved_iova (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void copy_reserved_iova(struct iova_domain *from, struct iova_domain *to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iova.c (0)
Location: drivers/iommu/iova.c:721
Inline: False
```
**Symbols:**

```
ffffffff81c0d839-ffffffff81c0d852: copy_reserved_iova.cold (STB_LOCAL)
ffffffff817c0260-ffffffff817c02d4: copy_reserved_iova (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void copy_reserved_iova(struct iova_domain *from, struct iova_domain *to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffff8000108cd470)
Location: drivers/iommu/iova.c:706
Inline: False
```
**Symbols:**

```
ffff8000108cd470-ffff8000108cd570: copy_reserved_iova (STB_GLOBAL)
```
</details>
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void copy_reserved_iova(struct iova_domain *from, struct iova_domain *to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iova.c (0)
Location: drivers/iommu/iova.c:706
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
```
**Symbols:**

```
ffffffff816a396c-ffffffff816a3985: copy_reserved_iova.cold (STB_LOCAL)
ffffffff816a2770-ffffffff816a27e4: copy_reserved_iova (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void copy_reserved_iova(struct iova_domain *from, struct iova_domain *to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iova.c (0)
Location: drivers/iommu/iova.c:706
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
```
**Symbols:**

```
ffffffff8168135c-ffffffff81681375: copy_reserved_iova.cold (STB_LOCAL)
ffffffff81680160-ffffffff816801d4: copy_reserved_iova (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void copy_reserved_iova(struct iova_domain *from, struct iova_domain *to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iova.c (0)
Location: drivers/iommu/iova.c:706
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
```
**Symbols:**

```
ffffffff816d1bdc-ffffffff816d1bf5: copy_reserved_iova.cold (STB_LOCAL)
ffffffff816d09e0-ffffffff816d0a54: copy_reserved_iova (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void copy_reserved_iova(struct iova_domain *from, struct iova_domain *to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iova.c (0)
Location: drivers/iommu/iova.c:706
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_alloc
```
**Symbols:**

```
ffffffff816ec19c-ffffffff816ec1b5: copy_reserved_iova.cold (STB_LOCAL)
ffffffff816eaf70-ffffffff816eafe4: copy_reserved_iova (STB_GLOBAL)
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
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
