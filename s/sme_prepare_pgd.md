# Function: <code>sme_prepare_pgd</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
pmd_t *sme_prepare_pgd(struct sme_populate_pgd_data *ppd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff826c5a62)
Location: arch/x86/mm/mem_encrypt.c:515
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:__sme_map_range
  - arch/x86/mm/mem_encrypt.c:sme_populate_pgd
```
**Symbols:**

```
ffffffff826c5a62-ffffffff826c5b3d: sme_prepare_pgd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
pud_t *sme_prepare_pgd(struct sme_populate_pgd_data *ppd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff826f0117)
Location: arch/x86/mm/mem_encrypt_identity.c:94
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
**Symbols:**

```
ffffffff826f0117-ffffffff826f01d6: sme_prepare_pgd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
pud_t *sme_prepare_pgd(struct sme_populate_pgd_data *ppd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828a6e1f)
Location: arch/x86/mm/mem_encrypt_identity.c:95
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
**Symbols:**

```
ffffffff828a6e1f-ffffffff828a6ede: sme_prepare_pgd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
pud_t *sme_prepare_pgd(struct sme_populate_pgd_data *ppd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828bf4d5)
Location: arch/x86/mm/mem_encrypt_identity.c:105
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
**Symbols:**

```
ffffffff828bf4d5-ffffffff828bf594: sme_prepare_pgd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
pud_t *sme_prepare_pgd(struct sme_populate_pgd_data *ppd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c5950)
Location: arch/x86/mm/mem_encrypt_identity.c:105
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
**Symbols:**

```
ffffffff828c5950-ffffffff828c5a0f: sme_prepare_pgd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
pud_t *sme_prepare_pgd(struct sme_populate_pgd_data *ppd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff82ce8bba)
Location: arch/x86/mm/mem_encrypt_identity.c:105
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:sme_populate_pgd
```
**Symbols:**

```
ffffffff82ce8bba-ffffffff82ce8cef: sme_prepare_pgd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
pud_t *sme_prepare_pgd(struct sme_populate_pgd_data *ppd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff82fd6640)
Location: arch/x86/mm/mem_encrypt_identity.c:105
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:sme_populate_pgd
```
**Symbols:**

```
ffffffff82fd6640-ffffffff82fd6775: sme_prepare_pgd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
pud_t *sme_prepare_pgd(struct sme_populate_pgd_data *ppd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff831e1094)
Location: arch/x86/mm/mem_encrypt_identity.c:105
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
**Symbols:**

```
ffffffff831e1094-ffffffff831e11c7: sme_prepare_pgd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
pud_t *sme_prepare_pgd(struct sme_populate_pgd_data *ppd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff832c48f3)
Location: arch/x86/mm/mem_encrypt_identity.c:114
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
**Symbols:**

```
ffffffff832c48f3-ffffffff832c4a51: sme_prepare_pgd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
pud_t *sme_prepare_pgd(struct sme_populate_pgd_data *ppd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff8347731d)
Location: arch/x86/mm/mem_encrypt_identity.c:117
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
**Symbols:**

```
ffffffff8347731d-ffffffff83477489: sme_prepare_pgd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
pud_t *sme_prepare_pgd(struct sme_populate_pgd_data *ppd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff83ea0850)
Location: arch/x86/mm/mem_encrypt_identity.c:117
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:sme_populate_pgd
```
**Symbols:**

```
ffffffff83ea0850-ffffffff83ea0a84: sme_prepare_pgd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
pud_t *sme_prepare_pgd(struct sme_populate_pgd_data *ppd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff836c49c0)
Location: arch/x86/mm/mem_encrypt_identity.c:117
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:sme_populate_pgd
```
**Symbols:**

```
ffffffff836c49c0-ffffffff836c4b92: sme_prepare_pgd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
pud_t *sme_prepare_pgd(struct sme_populate_pgd_data *ppd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff838f55c0)
Location: arch/x86/mm/mem_encrypt_identity.c:117
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:sme_populate_pgd
```
**Symbols:**

```
ffffffff838f55c0-ffffffff838f5792: sme_prepare_pgd (STB_LOCAL)
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
pud_t *sme_prepare_pgd(struct sme_populate_pgd_data *ppd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828b08e8)
Location: arch/x86/mm/mem_encrypt_identity.c:105
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
**Symbols:**

```
ffffffff828b08e8-ffffffff828b09a7: sme_prepare_pgd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
pud_t *sme_prepare_pgd(struct sme_populate_pgd_data *ppd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828a8a6d)
Location: arch/x86/mm/mem_encrypt_identity.c:105
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
**Symbols:**

```
ffffffff828a8a6d-ffffffff828a8b2c: sme_prepare_pgd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
pud_t *sme_prepare_pgd(struct sme_populate_pgd_data *ppd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c37e7)
Location: arch/x86/mm/mem_encrypt_identity.c:105
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
**Symbols:**

```
ffffffff828c37e7-ffffffff828c38a6: sme_prepare_pgd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
pud_t *sme_prepare_pgd(struct sme_populate_pgd_data *ppd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c698d)
Location: arch/x86/mm/mem_encrypt_identity.c:105
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
**Symbols:**

```
ffffffff828c698d-ffffffff828c6a4c: sme_prepare_pgd (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>pmd_t *</code> ➡️ <code>pud_t *</code>
</li>
</ul>
</details>
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
