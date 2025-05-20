# Function: <code>early_memremap_decrypted_wp</code>

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
void *early_memremap_decrypted_wp(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff826c357f)
Location: arch/x86/mm/ioremap.c:733
Inline: False
```
**Symbols:**

```
ffffffff826c357f-ffffffff826c35af: early_memremap_decrypted_wp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *early_memremap_decrypted_wp(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff826ed7e6)
Location: arch/x86/mm/ioremap.c:733
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec
```
**Symbols:**

```
ffffffff826ed7e6-ffffffff826ed816: early_memremap_decrypted_wp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *early_memremap_decrypted_wp(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff828a4378)
Location: arch/x86/mm/ioremap.c:741
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec
```
**Symbols:**

```
ffffffff828a4378-ffffffff828a43a8: early_memremap_decrypted_wp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *early_memremap_decrypted_wp(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff828bc833)
Location: arch/x86/mm/ioremap.c:766
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec
```
**Symbols:**

```
ffffffff828bc833-ffffffff828bc863: early_memremap_decrypted_wp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *early_memremap_decrypted_wp(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff828c2cda)
Location: arch/x86/mm/ioremap.c:788
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec
```
**Symbols:**

```
ffffffff828c2cda-ffffffff828c2d0a: early_memremap_decrypted_wp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *early_memremap_decrypted_wp(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff82ce60b8)
Location: arch/x86/mm/ioremap.c:797
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec
```
**Symbols:**

```
ffffffff82ce60b8-ffffffff82ce6102: early_memremap_decrypted_wp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *early_memremap_decrypted_wp(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff82fd3a3e)
Location: arch/x86/mm/ioremap.c:797
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec
```
**Symbols:**

```
ffffffff82fd3a3e-ffffffff82fd3a88: early_memremap_decrypted_wp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *early_memremap_decrypted_wp(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff831de639)
Location: arch/x86/mm/ioremap.c:780
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec
```
**Symbols:**

```
ffffffff831de639-ffffffff831de683: early_memremap_decrypted_wp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *early_memremap_decrypted_wp(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff832c1915)
Location: arch/x86/mm/ioremap.c:825
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec
```
**Symbols:**

```
ffffffff832c1915-ffffffff832c195f: early_memremap_decrypted_wp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *early_memremap_decrypted_wp(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff83473ff4)
Location: arch/x86/mm/ioremap.c:830
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_amd.c:__sme_early_enc_dec
```
**Symbols:**

```
ffffffff83473ff4-ffffffff83474044: early_memremap_decrypted_wp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *early_memremap_decrypted_wp(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff83e9bcd0)
Location: arch/x86/mm/ioremap.c:839
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_amd.c:__sme_early_enc_dec
```
**Symbols:**

```
ffffffff83e9bcd0-ffffffff83e9bd20: early_memremap_decrypted_wp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *early_memremap_decrypted_wp(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff836bf770)
Location: arch/x86/mm/ioremap.c:844
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_amd.c:__sme_early_enc_dec
```
**Symbols:**

```
ffffffff836bf770-ffffffff836bf7c0: early_memremap_decrypted_wp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *early_memremap_decrypted_wp(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff838f0210)
Location: arch/x86/mm/ioremap.c:844
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_amd.c:__sme_early_enc_dec
```
**Symbols:**

```
ffffffff838f0210-ffffffff838f0260: early_memremap_decrypted_wp (STB_GLOBAL)
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
void *early_memremap_decrypted_wp(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff828adcb0)
Location: arch/x86/mm/ioremap.c:788
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec
```
**Symbols:**

```
ffffffff828adcb0-ffffffff828adce0: early_memremap_decrypted_wp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *early_memremap_decrypted_wp(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff828a5f23)
Location: arch/x86/mm/ioremap.c:788
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec
```
**Symbols:**

```
ffffffff828a5f23-ffffffff828a5f53: early_memremap_decrypted_wp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *early_memremap_decrypted_wp(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff828c0baf)
Location: arch/x86/mm/ioremap.c:788
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec
```
**Symbols:**

```
ffffffff828c0baf-ffffffff828c0bdf: early_memremap_decrypted_wp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *early_memremap_decrypted_wp(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff828c3cfa)
Location: arch/x86/mm/ioremap.c:788
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec
```
**Symbols:**

```
ffffffff828c3cfa-ffffffff828c3d2a: early_memremap_decrypted_wp (STB_GLOBAL)
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
