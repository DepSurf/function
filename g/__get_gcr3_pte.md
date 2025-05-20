# Function: <code>__get_gcr3_pte</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
u64 *__get_gcr3_pte(u64 *root, int level, int pasid, bool alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff8152e210)
Location: drivers/iommu/amd_iommu.c:3308
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_set_gcr3
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_clear_gcr3
```
**Symbols:**

```
ffffffff8152e210-ffffffff8152e2de: __get_gcr3_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
u64 *__get_gcr3_pte(u64 *root, int level, int pasid, bool alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81581ca0)
Location: drivers/iommu/amd_iommu.c:3324
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_clear_gcr3
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_set_gcr3
```
**Symbols:**

```
ffffffff81581ca0-ffffffff81581d60: __get_gcr3_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u64 *__get_gcr3_pte(u64 *root, int level, int pasid, bool alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815ae610)
Location: drivers/iommu/amd_iommu.c:3448
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_clear_gcr3
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_set_gcr3
```
**Symbols:**

```
ffffffff815ae610-ffffffff815ae6d0: __get_gcr3_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u64 *__get_gcr3_pte(u64 *root, int level, int pasid, bool alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815c4210)
Location: drivers/iommu/amd_iommu.c:3588
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_clear_gcr3
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_set_gcr3
```
**Symbols:**

```
ffffffff815c4210-ffffffff815c42d0: __get_gcr3_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u64 *__get_gcr3_pte(u64 *root, int level, int pasid, bool alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff8162af60)
Location: drivers/iommu/amd_iommu.c:3379
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_clear_gcr3
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_set_gcr3
```
**Symbols:**

```
ffffffff8162af60-ffffffff8162b045: __get_gcr3_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u64 *__get_gcr3_pte(u64 *root, int level, int pasid, bool alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81665b70)
Location: drivers/iommu/amd_iommu.c:3403
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_clear_gcr3
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_set_gcr3
```
**Symbols:**

```
ffffffff81665b70-ffffffff81665c4b: __get_gcr3_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u64 *__get_gcr3_pte(u64 *root, int level, int pasid, bool alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816845e0)
Location: drivers/iommu/amd_iommu.c:3468
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_clear_gcr3
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_set_gcr3
```
**Symbols:**

```
ffffffff816845e0-ffffffff816846bb: __get_gcr3_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u64 *__get_gcr3_pte(u64 *root, int level, int pasid, bool alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816bbb40)
Location: drivers/iommu/amd_iommu.c:3449
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_clear_gcr3
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_set_gcr3
```
**Symbols:**

```
ffffffff816bbb40-ffffffff816bbc10: __get_gcr3_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 *__get_gcr3_pte(u64 *root, int level, int pasid, bool alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816de9d0)
Location: drivers/iommu/amd_iommu.c:3485
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_clear_gcr3
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_set_gcr3
```
**Symbols:**

```
ffffffff816de9d0-ffffffff816deaa0: __get_gcr3_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 *__get_gcr3_pte(u64 *root, int level, int pasid, bool alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81795150)
Location: drivers/iommu/amd/iommu.c:2882
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_clear_gcr3
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_set_gcr3
```
**Symbols:**

```
ffffffff81795150-ffffffff81795220: __get_gcr3_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 *__get_gcr3_pte(u64 *root, int level, u32 pasid, bool alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff817a3510)
Location: drivers/iommu/amd/iommu.c:2973
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_clear_gcr3
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_set_gcr3
```
**Symbols:**

```
ffffffff817a3510-ffffffff817a35e0: __get_gcr3_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 *__get_gcr3_pte(u64 *root, int level, u32 pasid, bool alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff817862c0)
Location: drivers/iommu/amd/iommu.c:2389
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_clear_gcr3
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_set_gcr3
```
**Symbols:**

```
ffffffff817862c0-ffffffff81786390: __get_gcr3_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
u64 *__get_gcr3_pte(u64 *root, int level, u32 pasid, bool alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:2457
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_clear_gcr3
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_set_gcr3
```
**Symbols:**

```
ffffffff8180d130-ffffffff8180d1fb: __get_gcr3_pte (STB_LOCAL)
ffffffff81cfdbbe-ffffffff81cfdbe7: __get_gcr3_pte.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
u64 *__get_gcr3_pte(u64 *root, int level, u32 pasid, bool alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:2483
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_clear_gcr3
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_set_gcr3
```
**Symbols:**

```
ffffffff8194d870-ffffffff8194d966: __get_gcr3_pte (STB_LOCAL)
ffffffff81ec64c4-ffffffff81ec64ed: __get_gcr3_pte.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
u64 *__get_gcr3_pte(u64 *root, int level, u32 pasid, bool alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:2644
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_clear_gcr3
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_set_gcr3
```
**Symbols:**

```
ffffffff81ab1d90-ffffffff81ab1e86: __get_gcr3_pte (STB_LOCAL)
ffffffff82096c38-ffffffff82096c61: __get_gcr3_pte.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
u64 *__get_gcr3_pte(u64 *root, int level, u32 pasid, bool alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:2664
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_clear_gcr3
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_set_gcr3
```
**Symbols:**

```
ffffffff81afde40-ffffffff81afdf37: __get_gcr3_pte (STB_LOCAL)
ffffffff82117b0a-ffffffff82117b24: __get_gcr3_pte.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
u64 *__get_gcr3_pte(u64 *root, int level, u32 pasid, bool alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:2748
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_clear_gcr3
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_set_gcr3
```
**Symbols:**

```
ffffffff81b515b0-ffffffff81b516a7: __get_gcr3_pte (STB_LOCAL)
ffffffff821f5894-ffffffff821f58ae: __get_gcr3_pte.cold (STB_LOCAL)
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
u64 *__get_gcr3_pte(u64 *root, int level, int pasid, bool alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816a4420)
Location: drivers/iommu/amd_iommu.c:3485
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_clear_gcr3
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_set_gcr3
```
**Symbols:**

```
ffffffff816a4420-ffffffff816a44f0: __get_gcr3_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 *__get_gcr3_pte(u64 *root, int level, int pasid, bool alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81681e10)
Location: drivers/iommu/amd_iommu.c:3485
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_clear_gcr3
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_set_gcr3
```
**Symbols:**

```
ffffffff81681e10-ffffffff81681ee0: __get_gcr3_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 *__get_gcr3_pte(u64 *root, int level, int pasid, bool alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816d2690)
Location: drivers/iommu/amd_iommu.c:3485
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_clear_gcr3
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_set_gcr3
```
**Symbols:**

```
ffffffff816d2690-ffffffff816d2760: __get_gcr3_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 *__get_gcr3_pte(u64 *root, int level, int pasid, bool alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816eccd0)
Location: drivers/iommu/amd_iommu.c:3485
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_clear_gcr3
  - drivers/iommu/amd_iommu.c:amd_iommu_domain_set_gcr3
```
**Symbols:**

```
ffffffff816eccd0-ffffffff816ecda0: __get_gcr3_pte (STB_LOCAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
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
