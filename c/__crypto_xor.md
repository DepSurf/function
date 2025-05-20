# Function: <code>__crypto_xor</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __crypto_xor(u8 *dst, const u8 *src, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff813fdc40)
Location: crypto/algapi.c:978
Inline: False
Direct callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
**Symbols:**

```
ffffffff813fdc40-ffffffff813fdcb1: __crypto_xor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __crypto_xor(u8 *dst, const u8 *src1, const u8 *src2, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff814261e0)
Location: crypto/algapi.c:992
Inline: False
Direct callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
**Symbols:**

```
ffffffff814261e0-ffffffff81426265: __crypto_xor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __crypto_xor(u8 *dst, const u8 *src1, const u8 *src2, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff814591e0)
Location: crypto/algapi.c:989
Inline: False
Direct callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
**Symbols:**

```
ffffffff814591e0-ffffffff81459265: __crypto_xor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __crypto_xor(u8 *dst, const u8 *src1, const u8 *src2, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff81476660)
Location: crypto/algapi.c:998
Inline: False
Direct callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
**Symbols:**

```
ffffffff81476660-ffffffff814766e5: __crypto_xor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __crypto_xor(u8 *dst, const u8 *src1, const u8 *src2, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff814a4330)
Location: crypto/algapi.c:967
Inline: False
Direct callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
**Symbols:**

```
ffffffff814a4330-ffffffff814a43b5: __crypto_xor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __crypto_xor(u8 *dst, const u8 *src1, const u8 *src2, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff814bef60)
Location: crypto/algapi.c:977
Inline: False
Direct callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
**Symbols:**

```
ffffffff814bef60-ffffffff814befe5: __crypto_xor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __crypto_xor(u8 *dst, const u8 *src1, const u8 *src2, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff8151f6e0)
Location: crypto/algapi.c:975
Inline: False
Direct callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
**Symbols:**

```
ffffffff8151f6e0-ffffffff8151f776: __crypto_xor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __crypto_xor(u8 *dst, const u8 *src1, const u8 *src2, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff8153c540)
Location: crypto/algapi.c:994
Inline: False
Direct callers:
  - crypto/cbc.c:crypto_cbc_decrypt_inplace
  - crypto/cbc.c:crypto_cbc_decrypt_inplace
  - crypto/cbc.c:crypto_cbc_decrypt_segment
  - crypto/cbc.c:crypto_cbc_encrypt
  - crypto/cbc.c:crypto_cbc_encrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
**Symbols:**

```
ffffffff8153c540-ffffffff8153c5d6: __crypto_xor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __crypto_xor(u8 *dst, const u8 *src1, const u8 *src2, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff81544c20)
Location: crypto/algapi.c:994
Inline: False
Direct callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_encrypt
  - crypto/cbc.c:crypto_cbc_encrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
**Symbols:**

```
ffffffff81544c20-ffffffff81544cb6: __crypto_xor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __crypto_xor(u8 *dst, const u8 *src1, const u8 *src2, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff815a5380)
Location: crypto/algapi.c:976
Inline: False
Direct callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_encrypt
  - crypto/cbc.c:crypto_cbc_encrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
**Symbols:**

```
ffffffff815a5380-ffffffff815a5416: __crypto_xor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __crypto_xor(u8 *dst, const u8 *src1, const u8 *src2, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff8164c060)
Location: crypto/algapi.c:1000
Inline: False
Direct callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt_inplace
  - crypto/cbc.c:crypto_cbc_decrypt_inplace
  - crypto/cbc.c:crypto_cbc_encrypt
  - crypto/cbc.c:crypto_cbc_encrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
**Symbols:**

```
ffffffff8164c060-ffffffff8164c10a: __crypto_xor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __crypto_xor(u8 *dst, const u8 *src1, const u8 *src2, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crypto/utils.c (ffffffff817dfa10)
Location: lib/crypto/utils.c:17
Inline: False
Direct callers:
  - crypto/cbc.c:crypto_cbc_decrypt_inplace
  - crypto/cbc.c:crypto_cbc_decrypt_inplace
  - crypto/cbc.c:crypto_cbc_decrypt_segment
  - crypto/cbc.c:crypto_cbc_encrypt_inplace
  - crypto/cbc.c:crypto_cbc_encrypt_segment
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
**Symbols:**

```
ffffffff817dfa10-ffffffff817dfaba: __crypto_xor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __crypto_xor(u8 *dst, const u8 *src1, const u8 *src2, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crypto/utils.c (ffffffff8181f190)
Location: lib/crypto/utils.c:17
Inline: False
Direct callers:
  - crypto/cbc.c:crypto_cbc_decrypt_inplace
  - crypto/cbc.c:crypto_cbc_decrypt_inplace
  - crypto/cbc.c:crypto_cbc_decrypt_segment
  - crypto/cbc.c:crypto_cbc_encrypt_inplace
  - crypto/cbc.c:crypto_cbc_encrypt_segment
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
**Symbols:**

```
ffffffff8181f190-ffffffff8181f23a: __crypto_xor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __crypto_xor(u8 *dst, const u8 *src1, const u8 *src2, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crypto/utils.c (ffffffff81865110)
Location: lib/crypto/utils.c:17
Inline: False
Direct callers:
  - crypto/cbc.c:crypto_cbc_decrypt_inplace
  - crypto/cbc.c:crypto_cbc_decrypt_inplace
  - crypto/cbc.c:crypto_cbc_decrypt_segment
  - crypto/cbc.c:crypto_cbc_encrypt_inplace
  - crypto/cbc.c:crypto_cbc_encrypt_segment
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
**Symbols:**

```
ffffffff81865110-ffffffff818651ba: __crypto_xor (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void __crypto_xor(u8 *dst, const u8 *src1, const u8 *src2, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffff8000105b8248)
Location: crypto/algapi.c:977
Inline: False
Direct callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
**Symbols:**

```
ffff8000105b8248-ffff8000105b8314: __crypto_xor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __crypto_xor(u8 *dst, const u8 *src1, const u8 *src2, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (c0766e9c)
Location: crypto/algapi.c:977
Inline: False
Direct callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_encrypt
  - crypto/cbc.c:crypto_cbc_encrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
**Symbols:**

```
c0766e9c-c0766f34: __crypto_xor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __crypto_xor(u8 *dst, const u8 *src1, const u8 *src2, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (c00000000073d2d0)
Location: crypto/algapi.c:977
Inline: False
Direct callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
**Symbols:**

```
c00000000073d2d0-c00000000073d3a4: __crypto_xor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __crypto_xor(u8 *dst, const u8 *src1, const u8 *src2, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffe0003fe970)
Location: crypto/algapi.c:977
Inline: False
Direct callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:gcm_enc_copy_hash
  - crypto/ghash-generic.c:ghash_update
```
**Symbols:**

```
ffffffe0003fe970-ffffffe0003feb0a: __crypto_xor (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void __crypto_xor(u8 *dst, const u8 *src1, const u8 *src2, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff814b7540)
Location: crypto/algapi.c:977
Inline: False
Direct callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
**Symbols:**

```
ffffffff814b7540-ffffffff814b75c5: __crypto_xor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __crypto_xor(u8 *dst, const u8 *src1, const u8 *src2, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff814a7f60)
Location: crypto/algapi.c:977
Inline: False
Direct callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
**Symbols:**

```
ffffffff814a7f60-ffffffff814a7fe5: __crypto_xor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __crypto_xor(u8 *dst, const u8 *src1, const u8 *src2, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff814b35d0)
Location: crypto/algapi.c:977
Inline: False
Direct callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
**Symbols:**

```
ffffffff814b35d0-ffffffff814b3655: __crypto_xor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __crypto_xor(u8 *dst, const u8 *src1, const u8 *src2, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff814cc050)
Location: crypto/algapi.c:977
Inline: False
Direct callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
**Symbols:**

```
ffffffff814cc050-ffffffff814cc0d5: __crypto_xor (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const u8 *src1</code>
</li>
<li>
<b>Param added. </b>
<code>const u8 *src2</code>
</li>
<li>
<b>Param removed. </b>
<code>const u8 *src</code>
</li>
<li>
<b>Param reordered. </b>
<code>dst, src, len</code> ➡️ <code>dst, src1, src2, len</code>
</li>
</ul>
</details>
</li>
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
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
