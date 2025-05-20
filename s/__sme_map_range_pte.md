# Function: <code>__sme_map_range_pte</code>

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
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff826c5cb3)
Location: arch/x86/mm/mem_encrypt.c:637
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__sme_map_range
  - arch/x86/mm/mem_encrypt.c:__sme_map_range
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __sme_map_range_pte(struct sme_populate_pgd_data *ppd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff826f01d6)
Location: arch/x86/mm/mem_encrypt_identity.c:183
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
```
**Symbols:**

```
ffffffff826f01d6-ffffffff826f02d0: __sme_map_range_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __sme_map_range_pte(struct sme_populate_pgd_data *ppd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828a6ede)
Location: arch/x86/mm/mem_encrypt_identity.c:184
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
```
**Symbols:**

```
ffffffff828a6ede-ffffffff828a6fd8: __sme_map_range_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __sme_map_range_pte(struct sme_populate_pgd_data *ppd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828bf594)
Location: arch/x86/mm/mem_encrypt_identity.c:194
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
```
**Symbols:**

```
ffffffff828bf594-ffffffff828bf68e: __sme_map_range_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __sme_map_range_pte(struct sme_populate_pgd_data *ppd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c5a0f)
Location: arch/x86/mm/mem_encrypt_identity.c:194
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
```
**Symbols:**

```
ffffffff828c5a0f-ffffffff828c5b0d: __sme_map_range_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __sme_map_range_pte(struct sme_populate_pgd_data *ppd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff82ce8d96)
Location: arch/x86/mm/mem_encrypt_identity.c:194
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
```
**Symbols:**

```
ffffffff82ce8d96-ffffffff82ce8dc5: __sme_map_range_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __sme_map_range_pte(struct sme_populate_pgd_data *ppd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff82fd681c)
Location: arch/x86/mm/mem_encrypt_identity.c:194
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
```
**Symbols:**

```
ffffffff82fd681c-ffffffff82fd684b: __sme_map_range_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __sme_map_range_pte(struct sme_populate_pgd_data *ppd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff831e11c7)
Location: arch/x86/mm/mem_encrypt_identity.c:194
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
```
**Symbols:**

```
ffffffff831e11c7-ffffffff831e1299: __sme_map_range_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __sme_map_range_pte(struct sme_populate_pgd_data *ppd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff832c4a51)
Location: arch/x86/mm/mem_encrypt_identity.c:203
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
```
**Symbols:**

```
ffffffff832c4a51-ffffffff832c4b23: __sme_map_range_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __sme_map_range_pte(struct sme_populate_pgd_data *ppd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff83477489)
Location: arch/x86/mm/mem_encrypt_identity.c:206
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
```
**Symbols:**

```
ffffffff83477489-ffffffff83477561: __sme_map_range_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff83ea0bec)
Location: arch/x86/mm/mem_encrypt_identity.c:206
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff836c4cfc)
Location: arch/x86/mm/mem_encrypt_identity.c:206
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff838f58fc)
Location: arch/x86/mm/mem_encrypt_identity.c:206
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
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
void __sme_map_range_pte(struct sme_populate_pgd_data *ppd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828b09a7)
Location: arch/x86/mm/mem_encrypt_identity.c:194
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
```
**Symbols:**

```
ffffffff828b09a7-ffffffff828b0aa5: __sme_map_range_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __sme_map_range_pte(struct sme_populate_pgd_data *ppd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828a8b2c)
Location: arch/x86/mm/mem_encrypt_identity.c:194
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
```
**Symbols:**

```
ffffffff828a8b2c-ffffffff828a8c2a: __sme_map_range_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __sme_map_range_pte(struct sme_populate_pgd_data *ppd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c38a6)
Location: arch/x86/mm/mem_encrypt_identity.c:194
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
```
**Symbols:**

```
ffffffff828c38a6-ffffffff828c39a4: __sme_map_range_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __sme_map_range_pte(struct sme_populate_pgd_data *ppd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c6a4c)
Location: arch/x86/mm/mem_encrypt_identity.c:194
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
```
**Symbols:**

```
ffffffff828c6a4c-ffffffff828c6b4a: __sme_map_range_pte (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
