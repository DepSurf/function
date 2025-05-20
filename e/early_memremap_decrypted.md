# Function: <code>early_memremap_decrypted</code>

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
void *early_memremap_decrypted(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff826c3565)
Location: arch/x86/mm/ioremap.c:723
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
```
**Symbols:**

```
ffffffff826c3565-ffffffff826c357f: early_memremap_decrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *early_memremap_decrypted(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff826ed7cc)
Location: arch/x86/mm/ioremap.c:723
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
  - arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec
```
**Symbols:**

```
ffffffff826ed7cc-ffffffff826ed7e6: early_memremap_decrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *early_memremap_decrypted(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff828a435e)
Location: arch/x86/mm/ioremap.c:731
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
  - arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec
```
**Symbols:**

```
ffffffff828a435e-ffffffff828a4378: early_memremap_decrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *early_memremap_decrypted(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff828bc819)
Location: arch/x86/mm/ioremap.c:756
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
  - arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec
```
**Symbols:**

```
ffffffff828bc819-ffffffff828bc833: early_memremap_decrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *early_memremap_decrypted(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff828c2cc0)
Location: arch/x86/mm/ioremap.c:778
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
  - arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec
```
**Symbols:**

```
ffffffff828c2cc0-ffffffff828c2cda: early_memremap_decrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *early_memremap_decrypted(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff82ce609e)
Location: arch/x86/mm/ioremap.c:787
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
  - arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec
```
**Symbols:**

```
ffffffff82ce609e-ffffffff82ce60b8: early_memremap_decrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *early_memremap_decrypted(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff82fd3a24)
Location: arch/x86/mm/ioremap.c:787
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
  - arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec
```
**Symbols:**

```
ffffffff82fd3a24-ffffffff82fd3a3e: early_memremap_decrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *early_memremap_decrypted(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff831de61f)
Location: arch/x86/mm/ioremap.c:770
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
  - arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec
```
**Symbols:**

```
ffffffff831de61f-ffffffff831de639: early_memremap_decrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *early_memremap_decrypted(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff832c18fb)
Location: arch/x86/mm/ioremap.c:815
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
  - arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec
```
**Symbols:**

```
ffffffff832c18fb-ffffffff832c1915: early_memremap_decrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *early_memremap_decrypted(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff83473fd0)
Location: arch/x86/mm/ioremap.c:820
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
  - arch/x86/mm/mem_encrypt_amd.c:__sme_early_enc_dec
```
**Symbols:**

```
ffffffff83473fd0-ffffffff83473ff4: early_memremap_decrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void *early_memremap_decrypted(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff83e9bdd2)
Location: arch/x86/mm/ioremap.c:829
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
Direct callers:
  - arch/x86/mm/mem_encrypt_amd.c:__sme_early_enc_dec
```
**Symbols:**

```
ffffffff83e9bc90-ffffffff83e9bcb4: early_memremap_decrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void *early_memremap_decrypted(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff836bf872)
Location: arch/x86/mm/ioremap.c:834
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
Direct callers:
  - arch/x86/mm/mem_encrypt_amd.c:__sme_early_enc_dec
```
**Symbols:**

```
ffffffff836bf730-ffffffff836bf754: early_memremap_decrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void *early_memremap_decrypted(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff838f0312)
Location: arch/x86/mm/ioremap.c:834
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
Direct callers:
  - arch/x86/mm/mem_encrypt_amd.c:__sme_early_enc_dec
```
**Symbols:**

```
ffffffff838f01d0-ffffffff838f01f4: early_memremap_decrypted (STB_GLOBAL)
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
void *early_memremap_decrypted(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff828adc96)
Location: arch/x86/mm/ioremap.c:778
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
  - arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec
```
**Symbols:**

```
ffffffff828adc96-ffffffff828adcb0: early_memremap_decrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *early_memremap_decrypted(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff828a5f09)
Location: arch/x86/mm/ioremap.c:778
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
  - arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec
```
**Symbols:**

```
ffffffff828a5f09-ffffffff828a5f23: early_memremap_decrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *early_memremap_decrypted(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff828c0b95)
Location: arch/x86/mm/ioremap.c:778
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
  - arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec
```
**Symbols:**

```
ffffffff828c0b95-ffffffff828c0baf: early_memremap_decrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *early_memremap_decrypted(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff828c3ce0)
Location: arch/x86/mm/ioremap.c:778
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
  - arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec
```
**Symbols:**

```
ffffffff828c3ce0-ffffffff828c3cfa: early_memremap_decrypted (STB_GLOBAL)
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
