# Function: <code>__flush_pasid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __flush_pasid(struct protection_domain *domain, int pasid, u64 address, bool size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff8152dd10)
Location: drivers/iommu/amd_iommu.c:3202
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_flush_page
  - drivers/iommu/amd_iommu.c:amd_iommu_flush_tlb
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_set_gcr3
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_clear_gcr3
```
**Symbols:**

```
ffffffff8152dd10-ffffffff8152dedc: __flush_pasid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __flush_pasid(struct protection_domain *domain, int pasid, u64 address, bool size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81581860)
Location: drivers/iommu/amd_iommu.c:3222
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_clear_gcr3
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_set_gcr3
  - drivers/iommu/amd_iommu.c:amd_iommu_flush_tlb
  - drivers/iommu/amd_iommu.c:amd_iommu_flush_page
```
**Symbols:**

```
ffffffff81581860-ffffffff81581a2d: __flush_pasid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __flush_pasid(struct protection_domain *domain, int pasid, u64 address, bool size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815af210)
Location: drivers/iommu/amd_iommu.c:3346
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_clear_gcr3
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_set_gcr3
  - drivers/iommu/amd_iommu.c:amd_iommu_flush_tlb
  - drivers/iommu/amd_iommu.c:amd_iommu_flush_page
```
**Symbols:**

```
ffffffff815af210-ffffffff815af3d6: __flush_pasid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __flush_pasid(struct protection_domain *domain, int pasid, u64 address, bool size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815c4fd0)
Location: drivers/iommu/amd_iommu.c:3486
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_clear_gcr3
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_set_gcr3
  - drivers/iommu/amd_iommu.c:amd_iommu_flush_tlb
  - drivers/iommu/amd_iommu.c:amd_iommu_flush_page
```
**Symbols:**

```
ffffffff815c4fd0-ffffffff815c5165: __flush_pasid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __flush_pasid(struct protection_domain *domain, int pasid, u64 address, bool size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff8162bd20)
Location: drivers/iommu/amd_iommu.c:3277
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_clear_gcr3
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_set_gcr3
  - drivers/iommu/amd_iommu.c:amd_iommu_flush_tlb
  - drivers/iommu/amd_iommu.c:amd_iommu_flush_page
```
**Symbols:**

```
ffffffff8162bd20-ffffffff8162beb5: __flush_pasid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __flush_pasid(struct protection_domain *domain, int pasid, u64 address, bool size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81667220)
Location: drivers/iommu/amd_iommu.c:3301
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_clear_gcr3
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_set_gcr3
  - drivers/iommu/amd_iommu.c:amd_iommu_flush_tlb
  - drivers/iommu/amd_iommu.c:amd_iommu_flush_page
```
**Symbols:**

```
ffffffff81667220-ffffffff816673b6: __flush_pasid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __flush_pasid(struct protection_domain *domain, int pasid, u64 address, bool size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816858d0)
Location: drivers/iommu/amd_iommu.c:3366
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_clear_gcr3
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_set_gcr3
  - drivers/iommu/amd_iommu.c:amd_iommu_flush_tlb
  - drivers/iommu/amd_iommu.c:amd_iommu_flush_page
```
**Symbols:**

```
ffffffff816858d0-ffffffff81685a66: __flush_pasid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __flush_pasid(struct protection_domain *domain, int pasid, u64 address, bool size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816bce10)
Location: drivers/iommu/amd_iommu.c:3347
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_clear_gcr3
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_set_gcr3
  - drivers/iommu/amd_iommu.c:amd_iommu_flush_tlb
  - drivers/iommu/amd_iommu.c:amd_iommu_flush_page
```
**Symbols:**

```
ffffffff816bce10-ffffffff816bcfab: __flush_pasid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __flush_pasid(struct protection_domain *domain, int pasid, u64 address, bool size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816dfde0)
Location: drivers/iommu/amd_iommu.c:3383
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_clear_gcr3
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_set_gcr3
  - drivers/iommu/amd_iommu.c:amd_iommu_flush_tlb
  - drivers/iommu/amd_iommu.c:amd_iommu_flush_page
```
**Symbols:**

```
ffffffff816dfde0-ffffffff816dff83: __flush_pasid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __flush_pasid(struct protection_domain *domain, int pasid, u64 address, bool size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff817961a0)
Location: drivers/iommu/amd/iommu.c:2780
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_clear_gcr3
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_set_gcr3
  - drivers/iommu/amd/iommu.c:amd_iommu_flush_tlb
  - drivers/iommu/amd/iommu.c:amd_iommu_flush_page
```
**Symbols:**

```
ffffffff817961a0-ffffffff81796379: __flush_pasid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __flush_pasid(struct protection_domain *domain, u32 pasid, u64 address, bool size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff817a4980)
Location: drivers/iommu/amd/iommu.c:2871
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_clear_gcr3
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_set_gcr3
  - drivers/iommu/amd/iommu.c:amd_iommu_flush_tlb
  - drivers/iommu/amd/iommu.c:amd_iommu_flush_page
```
**Symbols:**

```
ffffffff817a4980-ffffffff817a4b59: __flush_pasid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __flush_pasid(struct protection_domain *domain, u32 pasid, u64 address, bool size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff8178a300)
Location: drivers/iommu/amd/iommu.c:2287
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_clear_gcr3
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_set_gcr3
  - drivers/iommu/amd/iommu.c:amd_iommu_flush_tlb
  - drivers/iommu/amd/iommu.c:amd_iommu_flush_page
```
**Symbols:**

```
ffffffff8178a300-ffffffff8178a502: __flush_pasid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __flush_pasid(struct protection_domain *domain, u32 pasid, u64 address, bool size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:2355
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_clear_gcr3
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_set_gcr3
  - drivers/iommu/amd/iommu.c:amd_iommu_flush_tlb
  - drivers/iommu/amd/iommu.c:amd_iommu_flush_page
```
**Symbols:**

```
ffffffff81811620-ffffffff8181184c: __flush_pasid (STB_LOCAL)
ffffffff81cfe432-ffffffff81cfe446: __flush_pasid.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __flush_pasid(struct protection_domain *domain, u32 pasid, u64 address, bool size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:2381
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_clear_gcr3
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_set_gcr3
  - drivers/iommu/amd/iommu.c:amd_iommu_flush_tlb
  - drivers/iommu/amd/iommu.c:amd_iommu_flush_page
```
**Symbols:**

```
ffffffff81951bc0-ffffffff81951ea3: __flush_pasid (STB_LOCAL)
ffffffff81ec6bc8-ffffffff81ec6bdd: __flush_pasid.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __flush_pasid(struct protection_domain *domain, u32 pasid, u64 address, bool size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:2541
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_clear_gcr3
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_set_gcr3
  - drivers/iommu/amd/iommu.c:amd_iommu_flush_tlb
  - drivers/iommu/amd/iommu.c:amd_iommu_flush_page
```
**Symbols:**

```
ffffffff81ab6c80-ffffffff81ab6f68: __flush_pasid (STB_LOCAL)
ffffffff82096fe0-ffffffff82096ff5: __flush_pasid.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __flush_pasid(struct protection_domain *domain, u32 pasid, u64 address, bool size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:2561
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_clear_gcr3
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_set_gcr3
  - drivers/iommu/amd/iommu.c:amd_iommu_flush_tlb
  - drivers/iommu/amd/iommu.c:amd_iommu_flush_page
```
**Symbols:**

```
ffffffff81b02f10-ffffffff81b0328a: __flush_pasid (STB_LOCAL)
ffffffff82117ec6-ffffffff82117edb: __flush_pasid.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __flush_pasid(struct protection_domain *domain, u32 pasid, u64 address, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81b55200)
Location: drivers/iommu/amd/iommu.c:2648
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_clear_gcr3
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_set_gcr3
  - drivers/iommu/amd/iommu.c:amd_iommu_flush_tlb
  - drivers/iommu/amd/iommu.c:amd_iommu_flush_page
```
**Symbols:**

```
ffffffff81b55200-ffffffff81b55509: __flush_pasid (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
int __flush_pasid(struct protection_domain *domain, int pasid, u64 address, bool size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816a5830)
Location: drivers/iommu/amd_iommu.c:3383
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_clear_gcr3
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_set_gcr3
  - drivers/iommu/amd_iommu.c:amd_iommu_flush_tlb
  - drivers/iommu/amd_iommu.c:amd_iommu_flush_page
```
**Symbols:**

```
ffffffff816a5830-ffffffff816a59d3: __flush_pasid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __flush_pasid(struct protection_domain *domain, int pasid, u64 address, bool size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81683220)
Location: drivers/iommu/amd_iommu.c:3383
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_clear_gcr3
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_set_gcr3
  - drivers/iommu/amd_iommu.c:amd_iommu_flush_tlb
  - drivers/iommu/amd_iommu.c:amd_iommu_flush_page
```
**Symbols:**

```
ffffffff81683220-ffffffff816833c3: __flush_pasid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __flush_pasid(struct protection_domain *domain, int pasid, u64 address, bool size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816d3aa0)
Location: drivers/iommu/amd_iommu.c:3383
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_clear_gcr3
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_set_gcr3
  - drivers/iommu/amd_iommu.c:amd_iommu_flush_tlb
  - drivers/iommu/amd_iommu.c:amd_iommu_flush_page
```
**Symbols:**

```
ffffffff816d3aa0-ffffffff816d3c43: __flush_pasid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __flush_pasid(struct protection_domain *domain, int pasid, u64 address, bool size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816ee1a0)
Location: drivers/iommu/amd_iommu.c:3383
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_clear_gcr3
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_set_gcr3
  - drivers/iommu/amd_iommu.c:amd_iommu_flush_tlb
  - drivers/iommu/amd_iommu.c:amd_iommu_flush_page
```
**Symbols:**

```
ffffffff816ee1a0-ffffffff816ee343: __flush_pasid (STB_LOCAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>bool size</code> ➡️ <code>size_t size</code>
</li>
</ul>
</details>
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
