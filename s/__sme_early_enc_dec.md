# Function: <code>__sme_early_enc_dec</code>

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
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff826c5dc5)
Location: arch/x86/mm/mem_encrypt.c:63
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:sme_early_decrypt
  - arch/x86/mm/mem_encrypt.c:sme_early_encrypt
Direct callers:
  - arch/x86/mm/mem_encrypt.c:sme_early_decrypt
  - arch/x86/mm/mem_encrypt.c:sme_early_encrypt
```
**Symbols:**

```
ffffffff826c5bc9-ffffffff826c5c89: __sme_early_enc_dec.part.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __sme_early_enc_dec(resource_size_t paddr, long unsigned int size, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff826efa9d)
Location: arch/x86/mm/mem_encrypt.c:58
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:sme_early_decrypt
  - arch/x86/mm/mem_encrypt.c:sme_early_encrypt
```
**Symbols:**

```
ffffffff826efa9d-ffffffff826efb6a: __sme_early_enc_dec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __sme_early_enc_dec(resource_size_t paddr, long unsigned int size, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff828a675a)
Location: arch/x86/mm/mem_encrypt.c:58
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:sme_early_decrypt
  - arch/x86/mm/mem_encrypt.c:sme_early_encrypt
```
**Symbols:**

```
ffffffff828a675a-ffffffff828a6827: __sme_early_enc_dec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __sme_early_enc_dec(resource_size_t paddr, long unsigned int size, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff828bedff)
Location: arch/x86/mm/mem_encrypt.c:59
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:sme_early_decrypt
  - arch/x86/mm/mem_encrypt.c:sme_early_encrypt
```
**Symbols:**

```
ffffffff828bedff-ffffffff828beed3: __sme_early_enc_dec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __sme_early_enc_dec(resource_size_t paddr, long unsigned int size, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff828c5278)
Location: arch/x86/mm/mem_encrypt.c:59
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:sme_early_decrypt
  - arch/x86/mm/mem_encrypt.c:sme_early_encrypt
```
**Symbols:**

```
ffffffff828c5278-ffffffff828c534c: __sme_early_enc_dec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __sme_early_enc_dec(resource_size_t paddr, long unsigned int size, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff82ce844c)
Location: arch/x86/mm/mem_encrypt.c:59
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:sme_early_decrypt
  - arch/x86/mm/mem_encrypt.c:sme_early_encrypt
```
**Symbols:**

```
ffffffff82ce844c-ffffffff82ce8520: __sme_early_enc_dec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __sme_early_enc_dec(resource_size_t paddr, long unsigned int size, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff82fd5e6b)
Location: arch/x86/mm/mem_encrypt.c:61
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:sme_early_decrypt
  - arch/x86/mm/mem_encrypt.c:sme_early_encrypt
```
**Symbols:**

```
ffffffff82fd5e6b-ffffffff82fd5f3f: __sme_early_enc_dec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __sme_early_enc_dec(resource_size_t paddr, long unsigned int size, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff831e08dd)
Location: arch/x86/mm/mem_encrypt.c:60
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:sme_early_decrypt
  - arch/x86/mm/mem_encrypt.c:sme_early_encrypt
```
**Symbols:**

```
ffffffff831e08dd-ffffffff831e09ab: __sme_early_enc_dec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __sme_early_enc_dec(resource_size_t paddr, long unsigned int size, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff832c3fbb)
Location: arch/x86/mm/mem_encrypt.c:61
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:sme_early_decrypt
  - arch/x86/mm/mem_encrypt.c:sme_early_encrypt
```
**Symbols:**

```
ffffffff832c3fbb-ffffffff832c4089: __sme_early_enc_dec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __sme_early_enc_dec(resource_size_t paddr, long unsigned int size, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff83476978)
Location: arch/x86/mm/mem_encrypt_amd.c:91
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_amd.c:sme_early_decrypt
  - arch/x86/mm/mem_encrypt_amd.c:sme_early_encrypt
```
**Symbols:**

```
ffffffff83476978-ffffffff83476aac: __sme_early_enc_dec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __sme_early_enc_dec(resource_size_t paddr, long unsigned int size, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff83e9faf0)
Location: arch/x86/mm/mem_encrypt_amd.c:92
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_amd.c:__set_clr_pte_enc
  - arch/x86/mm/mem_encrypt_amd.c:__set_clr_pte_enc
```
**Symbols:**

```
ffffffff83e9faf0-ffffffff83e9fd23: __sme_early_enc_dec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __sme_early_enc_dec(resource_size_t paddr, long unsigned int size, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff836c3c80)
Location: arch/x86/mm/mem_encrypt_amd.c:92
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_amd.c:__set_clr_pte_enc
  - arch/x86/mm/mem_encrypt_amd.c:__set_clr_pte_enc
```
**Symbols:**

```
ffffffff836c3c80-ffffffff836c3ebb: __sme_early_enc_dec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __sme_early_enc_dec(resource_size_t paddr, long unsigned int size, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff838f4900)
Location: arch/x86/mm/mem_encrypt_amd.c:91
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_amd.c:__set_clr_pte_enc
  - arch/x86/mm/mem_encrypt_amd.c:__set_clr_pte_enc
```
**Symbols:**

```
ffffffff838f4900-ffffffff838f4b3b: __sme_early_enc_dec (STB_LOCAL)
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
void __sme_early_enc_dec(resource_size_t paddr, long unsigned int size, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff828b0210)
Location: arch/x86/mm/mem_encrypt.c:59
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:sme_early_decrypt
  - arch/x86/mm/mem_encrypt.c:sme_early_encrypt
```
**Symbols:**

```
ffffffff828b0210-ffffffff828b02e4: __sme_early_enc_dec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __sme_early_enc_dec(resource_size_t paddr, long unsigned int size, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff828a83fd)
Location: arch/x86/mm/mem_encrypt.c:59
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:sme_early_decrypt
  - arch/x86/mm/mem_encrypt.c:sme_early_encrypt
```
**Symbols:**

```
ffffffff828a83fd-ffffffff828a84cc: __sme_early_enc_dec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __sme_early_enc_dec(resource_size_t paddr, long unsigned int size, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff828c310f)
Location: arch/x86/mm/mem_encrypt.c:59
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:sme_early_decrypt
  - arch/x86/mm/mem_encrypt.c:sme_early_encrypt
```
**Symbols:**

```
ffffffff828c310f-ffffffff828c31e3: __sme_early_enc_dec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __sme_early_enc_dec(resource_size_t paddr, long unsigned int size, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff828c62b5)
Location: arch/x86/mm/mem_encrypt.c:59
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:sme_early_decrypt
  - arch/x86/mm/mem_encrypt.c:sme_early_encrypt
```
**Symbols:**

```
ffffffff828c62b5-ffffffff828c6389: __sme_early_enc_dec (STB_LOCAL)
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
