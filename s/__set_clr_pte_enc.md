# Function: <code>__set_clr_pte_enc</code>

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
void __set_clr_pte_enc(pte_t *kpte, int level, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff826c5ddd)
Location: arch/x86/mm/mem_encrypt.c:264
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
```
**Symbols:**

```
ffffffff826c5ddd-ffffffff826c5fcf: __set_clr_pte_enc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __set_clr_pte_enc(pte_t *kpte, int level, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff826efb87)
Location: arch/x86/mm/mem_encrypt.c:198
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
```
**Symbols:**

```
ffffffff826efb87-ffffffff826efda3: __set_clr_pte_enc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __set_clr_pte_enc(pte_t *kpte, int level, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff828a6844)
Location: arch/x86/mm/mem_encrypt.c:198
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
```
**Symbols:**

```
ffffffff828a6844-ffffffff828a6a60: __set_clr_pte_enc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __set_clr_pte_enc(pte_t *kpte, int level, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff828beef0)
Location: arch/x86/mm/mem_encrypt.c:199
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
```
**Symbols:**

```
ffffffff828beef0-ffffffff828bf10a: __set_clr_pte_enc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __set_clr_pte_enc(pte_t *kpte, int level, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff828c5369)
Location: arch/x86/mm/mem_encrypt.c:199
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
```
**Symbols:**

```
ffffffff828c5369-ffffffff828c5585: __set_clr_pte_enc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __set_clr_pte_enc(pte_t *kpte, int level, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff82ce857d)
Location: arch/x86/mm/mem_encrypt.c:199
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
```
**Symbols:**

```
ffffffff82ce857d-ffffffff82ce8795: __set_clr_pte_enc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __set_clr_pte_enc(pte_t *kpte, int level, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff82fd5f9c)
Location: arch/x86/mm/mem_encrypt.c:232
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
```
**Symbols:**

```
ffffffff82fd5f9c-ffffffff82fd61a7: __set_clr_pte_enc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __set_clr_pte_enc(pte_t *kpte, int level, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff831e0a08)
Location: arch/x86/mm/mem_encrypt.c:231
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
```
**Symbols:**

```
ffffffff831e0a08-ffffffff831e0c02: __set_clr_pte_enc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __set_clr_pte_enc(pte_t *kpte, int level, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff832c40e6)
Location: arch/x86/mm/mem_encrypt.c:232
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
```
**Symbols:**

```
ffffffff832c40e6-ffffffff832c42da: __set_clr_pte_enc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __set_clr_pte_enc(pte_t *kpte, int level, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff83476b29)
Location: arch/x86/mm/mem_encrypt_amd.c:347
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_amd.c:early_set_memory_enc_dec
  - arch/x86/mm/mem_encrypt_amd.c:early_set_memory_enc_dec
```
**Symbols:**

```
ffffffff83476b29-ffffffff83476c8a: __set_clr_pte_enc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __set_clr_pte_enc(pte_t *kpte, int level, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff83e9fd40)
Location: arch/x86/mm/mem_encrypt_amd.c:348
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_amd.c:early_set_memory_enc_dec
  - arch/x86/mm/mem_encrypt_amd.c:early_set_memory_enc_dec
```
**Symbols:**

```
ffffffff83e9fd40-ffffffff83e9fefd: __set_clr_pte_enc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __set_clr_pte_enc(pte_t *kpte, int level, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff836c3ed0)
Location: arch/x86/mm/mem_encrypt_amd.c:349
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_amd.c:early_set_memory_enc_dec
  - arch/x86/mm/mem_encrypt_amd.c:early_set_memory_enc_dec
```
**Symbols:**

```
ffffffff836c3ed0-ffffffff836c407f: __set_clr_pte_enc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __set_clr_pte_enc(pte_t *kpte, int level, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff838f4b50)
Location: arch/x86/mm/mem_encrypt_amd.c:314
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_amd.c:early_set_memory_enc_dec
  - arch/x86/mm/mem_encrypt_amd.c:early_set_memory_enc_dec
```
**Symbols:**

```
ffffffff838f4b50-ffffffff838f4cff: __set_clr_pte_enc (STB_LOCAL)
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
void __set_clr_pte_enc(pte_t *kpte, int level, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff828b0301)
Location: arch/x86/mm/mem_encrypt.c:199
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
```
**Symbols:**

```
ffffffff828b0301-ffffffff828b051d: __set_clr_pte_enc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __set_clr_pte_enc(pte_t *kpte, int level, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff828a84e9)
Location: arch/x86/mm/mem_encrypt.c:199
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
```
**Symbols:**

```
ffffffff828a84e9-ffffffff828a86a2: __set_clr_pte_enc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __set_clr_pte_enc(pte_t *kpte, int level, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff828c3200)
Location: arch/x86/mm/mem_encrypt.c:199
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
```
**Symbols:**

```
ffffffff828c3200-ffffffff828c341c: __set_clr_pte_enc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __set_clr_pte_enc(pte_t *kpte, int level, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff828c63a6)
Location: arch/x86/mm/mem_encrypt.c:199
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
```
**Symbols:**

```
ffffffff828c63a6-ffffffff828c65c2: __set_clr_pte_enc (STB_LOCAL)
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
