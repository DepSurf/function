# Function: <code>snp_memcpy</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void snp_memcpy(void *dst, void *src, size_t sz, long unsigned int paddr, bool decrypt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff83476905)
Location: arch/x86/mm/mem_encrypt_amd.c:57
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_amd.c:__sme_early_enc_dec
  - arch/x86/mm/mem_encrypt_amd.c:__sme_early_enc_dec
```
**Symbols:**

```
ffffffff83476905-ffffffff83476978: snp_memcpy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void snp_memcpy(void *dst, void *src, size_t sz, long unsigned int paddr, bool decrypt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff83e9f970)
Location: arch/x86/mm/mem_encrypt_amd.c:58
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_amd.c:__sme_early_enc_dec
  - arch/x86/mm/mem_encrypt_amd.c:__sme_early_enc_dec
```
**Symbols:**

```
ffffffff83e9f970-ffffffff83e9fadb: snp_memcpy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void snp_memcpy(void *dst, void *src, size_t sz, long unsigned int paddr, bool decrypt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff836c3b00)
Location: arch/x86/mm/mem_encrypt_amd.c:58
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_amd.c:__sme_early_enc_dec
  - arch/x86/mm/mem_encrypt_amd.c:__sme_early_enc_dec
```
**Symbols:**

```
ffffffff836c3b00-ffffffff836c3c6b: snp_memcpy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void snp_memcpy(void *dst, void *src, size_t sz, long unsigned int paddr, bool decrypt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff838f4780)
Location: arch/x86/mm/mem_encrypt_amd.c:57
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_amd.c:__sme_early_enc_dec
  - arch/x86/mm/mem_encrypt_amd.c:__sme_early_enc_dec
```
**Symbols:**

```
ffffffff838f4780-ffffffff838f48eb: snp_memcpy (STB_LOCAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
