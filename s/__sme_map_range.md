# Function: <code>__sme_map_range</code>

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
void __sme_map_range(struct sme_populate_pgd_data *ppd, pmdval_t pmd_flags, pteval_t pte_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff826c5c89)
Location: arch/x86/mm/mem_encrypt.c:647
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:sme_map_range_decrypted_wp
  - arch/x86/mm/mem_encrypt.c:sme_map_range_decrypted
  - arch/x86/mm/mem_encrypt.c:sme_map_range_encrypted
```
**Symbols:**

```
ffffffff826c5c89-ffffffff826c5d63: __sme_map_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __sme_map_range(struct sme_populate_pgd_data *ppd, pmdval_t pmd_flags, pteval_t pte_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff826f02d0)
Location: arch/x86/mm/mem_encrypt_identity.c:193
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
```
**Symbols:**

```
ffffffff826f02d0-ffffffff826f03b6: __sme_map_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __sme_map_range(struct sme_populate_pgd_data *ppd, pmdval_t pmd_flags, pteval_t pte_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828a6fd8)
Location: arch/x86/mm/mem_encrypt_identity.c:194
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
```
**Symbols:**

```
ffffffff828a6fd8-ffffffff828a70be: __sme_map_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __sme_map_range(struct sme_populate_pgd_data *ppd, pmdval_t pmd_flags, pteval_t pte_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828bf68e)
Location: arch/x86/mm/mem_encrypt_identity.c:204
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
```
**Symbols:**

```
ffffffff828bf68e-ffffffff828bf77d: __sme_map_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __sme_map_range(struct sme_populate_pgd_data *ppd, pmdval_t pmd_flags, pteval_t pte_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c5b0d)
Location: arch/x86/mm/mem_encrypt_identity.c:204
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
```
**Symbols:**

```
ffffffff828c5b0d-ffffffff828c5c01: __sme_map_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __sme_map_range(struct sme_populate_pgd_data *ppd, pmdval_t pmd_flags, pteval_t pte_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff82ce8dc5)
Location: arch/x86/mm/mem_encrypt_identity.c:204
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_map_range_decrypted
  - arch/x86/mm/mem_encrypt_identity.c:sme_map_range_encrypted
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
```
**Symbols:**

```
ffffffff82ce8dc5-ffffffff82ce8e6e: __sme_map_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __sme_map_range(struct sme_populate_pgd_data *ppd, pmdval_t pmd_flags, pteval_t pte_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff82fd684b)
Location: arch/x86/mm/mem_encrypt_identity.c:204
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_map_range_decrypted
  - arch/x86/mm/mem_encrypt_identity.c:sme_map_range_encrypted
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
```
**Symbols:**

```
ffffffff82fd684b-ffffffff82fd68f4: __sme_map_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __sme_map_range(struct sme_populate_pgd_data *ppd, pmdval_t pmd_flags, pteval_t pte_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff831e1299)
Location: arch/x86/mm/mem_encrypt_identity.c:204
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_map_range_decrypted
  - arch/x86/mm/mem_encrypt_identity.c:sme_map_range_encrypted
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
```
**Symbols:**

```
ffffffff831e1299-ffffffff831e133e: __sme_map_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __sme_map_range(struct sme_populate_pgd_data *ppd, pmdval_t pmd_flags, pteval_t pte_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff832c4b23)
Location: arch/x86/mm/mem_encrypt_identity.c:213
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_map_range_decrypted
  - arch/x86/mm/mem_encrypt_identity.c:sme_map_range_encrypted
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
```
**Symbols:**

```
ffffffff832c4b23-ffffffff832c4bc8: __sme_map_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __sme_map_range(struct sme_populate_pgd_data *ppd, pmdval_t pmd_flags, pteval_t pte_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff83477561)
Location: arch/x86/mm/mem_encrypt_identity.c:216
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_map_range_decrypted
  - arch/x86/mm/mem_encrypt_identity.c:sme_map_range_encrypted
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
```
**Symbols:**

```
ffffffff83477561-ffffffff8347760d: __sme_map_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __sme_map_range(struct sme_populate_pgd_data *ppd, pmdval_t pmd_flags, pteval_t pte_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff83ea0bc0)
Location: arch/x86/mm/mem_encrypt_identity.c:216
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
```
**Symbols:**

```
ffffffff83ea0bc0-ffffffff83ea0cfc: __sme_map_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __sme_map_range(struct sme_populate_pgd_data *ppd, pmdval_t pmd_flags, pteval_t pte_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff836c4cd0)
Location: arch/x86/mm/mem_encrypt_identity.c:216
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
```
**Symbols:**

```
ffffffff836c4cd0-ffffffff836c4e0c: __sme_map_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __sme_map_range(struct sme_populate_pgd_data *ppd, pmdval_t pmd_flags, pteval_t pte_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff838f58d0)
Location: arch/x86/mm/mem_encrypt_identity.c:216
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
```
**Symbols:**

```
ffffffff838f58d0-ffffffff838f5a0c: __sme_map_range (STB_LOCAL)
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
void __sme_map_range(struct sme_populate_pgd_data *ppd, pmdval_t pmd_flags, pteval_t pte_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828b0aa5)
Location: arch/x86/mm/mem_encrypt_identity.c:204
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
```
**Symbols:**

```
ffffffff828b0aa5-ffffffff828b0b99: __sme_map_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __sme_map_range(struct sme_populate_pgd_data *ppd, pmdval_t pmd_flags, pteval_t pte_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828a8c2a)
Location: arch/x86/mm/mem_encrypt_identity.c:204
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
```
**Symbols:**

```
ffffffff828a8c2a-ffffffff828a8d1e: __sme_map_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __sme_map_range(struct sme_populate_pgd_data *ppd, pmdval_t pmd_flags, pteval_t pte_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c39a4)
Location: arch/x86/mm/mem_encrypt_identity.c:204
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
```
**Symbols:**

```
ffffffff828c39a4-ffffffff828c3a98: __sme_map_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __sme_map_range(struct sme_populate_pgd_data *ppd, pmdval_t pmd_flags, pteval_t pte_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c6b4a)
Location: arch/x86/mm/mem_encrypt_identity.c:204
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
  - arch/x86/mm/mem_encrypt_identity.c:sme_encrypt_kernel
```
**Symbols:**

```
ffffffff828c6b4a-ffffffff828c6c3e: __sme_map_range (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
