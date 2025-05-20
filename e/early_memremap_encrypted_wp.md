# Function: <code>early_memremap_encrypted_wp</code>

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
void *early_memremap_encrypted_wp(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff826c352e)
Location: arch/x86/mm/ioremap.c:712
Inline: False
```
**Symbols:**

```
ffffffff826c352e-ffffffff826c3565: early_memremap_encrypted_wp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *early_memremap_encrypted_wp(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff826ed795)
Location: arch/x86/mm/ioremap.c:712
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec
```
**Symbols:**

```
ffffffff826ed795-ffffffff826ed7cc: early_memremap_encrypted_wp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *early_memremap_encrypted_wp(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff828a4327)
Location: arch/x86/mm/ioremap.c:720
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec
```
**Symbols:**

```
ffffffff828a4327-ffffffff828a435e: early_memremap_encrypted_wp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *early_memremap_encrypted_wp(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff828bc7e2)
Location: arch/x86/mm/ioremap.c:745
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec
```
**Symbols:**

```
ffffffff828bc7e2-ffffffff828bc819: early_memremap_encrypted_wp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *early_memremap_encrypted_wp(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff828c2c89)
Location: arch/x86/mm/ioremap.c:767
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec
```
**Symbols:**

```
ffffffff828c2c89-ffffffff828c2cc0: early_memremap_encrypted_wp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *early_memremap_encrypted_wp(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff82ce604a)
Location: arch/x86/mm/ioremap.c:778
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec
```
**Symbols:**

```
ffffffff82ce604a-ffffffff82ce609e: early_memremap_encrypted_wp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *early_memremap_encrypted_wp(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff82fd39d0)
Location: arch/x86/mm/ioremap.c:778
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec
```
**Symbols:**

```
ffffffff82fd39d0-ffffffff82fd3a24: early_memremap_encrypted_wp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *early_memremap_encrypted_wp(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff831de5cb)
Location: arch/x86/mm/ioremap.c:761
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec
```
**Symbols:**

```
ffffffff831de5cb-ffffffff831de61f: early_memremap_encrypted_wp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *early_memremap_encrypted_wp(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff832c18a7)
Location: arch/x86/mm/ioremap.c:806
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec
```
**Symbols:**

```
ffffffff832c18a7-ffffffff832c18fb: early_memremap_encrypted_wp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *early_memremap_encrypted_wp(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff83473f76)
Location: arch/x86/mm/ioremap.c:811
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_amd.c:__sme_early_enc_dec
```
**Symbols:**

```
ffffffff83473f76-ffffffff83473fd0: early_memremap_encrypted_wp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *early_memremap_encrypted_wp(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff83e9bc20)
Location: arch/x86/mm/ioremap.c:820
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_amd.c:__sme_early_enc_dec
```
**Symbols:**

```
ffffffff83e9bc20-ffffffff83e9bc7a: early_memremap_encrypted_wp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *early_memremap_encrypted_wp(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff836bf6c0)
Location: arch/x86/mm/ioremap.c:825
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_amd.c:__sme_early_enc_dec
```
**Symbols:**

```
ffffffff836bf6c0-ffffffff836bf71a: early_memremap_encrypted_wp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *early_memremap_encrypted_wp(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff838f0160)
Location: arch/x86/mm/ioremap.c:825
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_amd.c:__sme_early_enc_dec
```
**Symbols:**

```
ffffffff838f0160-ffffffff838f01ba: early_memremap_encrypted_wp (STB_GLOBAL)
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
void *early_memremap_encrypted_wp(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff828adc5f)
Location: arch/x86/mm/ioremap.c:767
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec
```
**Symbols:**

```
ffffffff828adc5f-ffffffff828adc96: early_memremap_encrypted_wp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *early_memremap_encrypted_wp(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff828a5ed2)
Location: arch/x86/mm/ioremap.c:767
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec
```
**Symbols:**

```
ffffffff828a5ed2-ffffffff828a5f09: early_memremap_encrypted_wp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *early_memremap_encrypted_wp(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff828c0b5e)
Location: arch/x86/mm/ioremap.c:767
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec
```
**Symbols:**

```
ffffffff828c0b5e-ffffffff828c0b95: early_memremap_encrypted_wp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *early_memremap_encrypted_wp(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff828c3ca9)
Location: arch/x86/mm/ioremap.c:767
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec
```
**Symbols:**

```
ffffffff828c3ca9-ffffffff828c3ce0: early_memremap_encrypted_wp (STB_GLOBAL)
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
