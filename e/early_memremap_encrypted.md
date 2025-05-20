# Function: <code>early_memremap_encrypted</code>

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
void *early_memremap_encrypted(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff826c350d)
Location: arch/x86/mm/ioremap.c:702
Inline: False
```
**Symbols:**

```
ffffffff826c350d-ffffffff826c352e: early_memremap_encrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *early_memremap_encrypted(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff826ed774)
Location: arch/x86/mm/ioremap.c:702
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec
```
**Symbols:**

```
ffffffff826ed774-ffffffff826ed795: early_memremap_encrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *early_memremap_encrypted(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff828a4306)
Location: arch/x86/mm/ioremap.c:710
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec
```
**Symbols:**

```
ffffffff828a4306-ffffffff828a4327: early_memremap_encrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *early_memremap_encrypted(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff828bc7c1)
Location: arch/x86/mm/ioremap.c:735
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec
```
**Symbols:**

```
ffffffff828bc7c1-ffffffff828bc7e2: early_memremap_encrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *early_memremap_encrypted(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff828c2c68)
Location: arch/x86/mm/ioremap.c:757
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec
```
**Symbols:**

```
ffffffff828c2c68-ffffffff828c2c89: early_memremap_encrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *early_memremap_encrypted(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff82ce6029)
Location: arch/x86/mm/ioremap.c:768
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec
```
**Symbols:**

```
ffffffff82ce6029-ffffffff82ce604a: early_memremap_encrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *early_memremap_encrypted(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff82fd39af)
Location: arch/x86/mm/ioremap.c:768
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec
```
**Symbols:**

```
ffffffff82fd39af-ffffffff82fd39d0: early_memremap_encrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *early_memremap_encrypted(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff831de5aa)
Location: arch/x86/mm/ioremap.c:751
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec
```
**Symbols:**

```
ffffffff831de5aa-ffffffff831de5cb: early_memremap_encrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *early_memremap_encrypted(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff832c1886)
Location: arch/x86/mm/ioremap.c:796
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec
```
**Symbols:**

```
ffffffff832c1886-ffffffff832c18a7: early_memremap_encrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *early_memremap_encrypted(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff83473f4b)
Location: arch/x86/mm/ioremap.c:801
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_amd.c:__sme_early_enc_dec
```
**Symbols:**

```
ffffffff83473f4b-ffffffff83473f76: early_memremap_encrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *early_memremap_encrypted(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff83e9bbe0)
Location: arch/x86/mm/ioremap.c:810
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_amd.c:__sme_early_enc_dec
```
**Symbols:**

```
ffffffff83e9bbe0-ffffffff83e9bc0b: early_memremap_encrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *early_memremap_encrypted(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff836bf680)
Location: arch/x86/mm/ioremap.c:815
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_amd.c:__sme_early_enc_dec
```
**Symbols:**

```
ffffffff836bf680-ffffffff836bf6ab: early_memremap_encrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *early_memremap_encrypted(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff838f0120)
Location: arch/x86/mm/ioremap.c:815
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_amd.c:__sme_early_enc_dec
```
**Symbols:**

```
ffffffff838f0120-ffffffff838f014b: early_memremap_encrypted (STB_GLOBAL)
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
void *early_memremap_encrypted(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff828adc3e)
Location: arch/x86/mm/ioremap.c:757
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec
```
**Symbols:**

```
ffffffff828adc3e-ffffffff828adc5f: early_memremap_encrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *early_memremap_encrypted(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff828a5eb1)
Location: arch/x86/mm/ioremap.c:757
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec
```
**Symbols:**

```
ffffffff828a5eb1-ffffffff828a5ed2: early_memremap_encrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *early_memremap_encrypted(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff828c0b3d)
Location: arch/x86/mm/ioremap.c:757
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec
```
**Symbols:**

```
ffffffff828c0b3d-ffffffff828c0b5e: early_memremap_encrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *early_memremap_encrypted(resource_size_t phys_addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff828c3c88)
Location: arch/x86/mm/ioremap.c:757
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec
```
**Symbols:**

```
ffffffff828c3c88-ffffffff828c3ca9: early_memremap_encrypted (STB_GLOBAL)
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
