# Function: <code>sg_nents_for_len</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int sg_nents_for_len(struct scatterlist *sg, u64 len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff813fa270)
Location: lib/scatterlist.c:73
Inline: True
```
**Symbols:**

```
ffffffff813fa270-ffffffff813fa2c9: sg_nents_for_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int sg_nents_for_len(struct scatterlist *sg, u64 len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff814412d0)
Location: lib/scatterlist.c:73
Inline: True
Direct callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
```
**Symbols:**

```
ffffffff814412d0-ffffffff81441338: sg_nents_for_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int sg_nents_for_len(struct scatterlist *sg, u64 len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff8145e470)
Location: lib/scatterlist.c:73
Inline: True
Direct callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
```
**Symbols:**

```
ffffffff8145e470-ffffffff8145e4d8: sg_nents_for_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int sg_nents_for_len(struct scatterlist *sg, u64 len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff814635b0)
Location: lib/scatterlist.c:73
Inline: True
Direct callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
```
**Symbols:**

```
ffffffff814635b0-ffffffff81463618: sg_nents_for_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int sg_nents_for_len(struct scatterlist *sg, u64 len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff8148f4c0)
Location: lib/scatterlist.c:73
Inline: True
Direct callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
```
**Symbols:**

```
ffffffff8148f4c0-ffffffff8148f528: sg_nents_for_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int sg_nents_for_len(struct scatterlist *sg, u64 len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff814c4110)
Location: lib/scatterlist.c:70
Inline: True
Direct callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
```
**Symbols:**

```
ffffffff814c4110-ffffffff814c416d: sg_nents_for_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int sg_nents_for_len(struct scatterlist *sg, u64 len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff814d8810)
Location: lib/scatterlist.c:70
Inline: True
Direct callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
```
**Symbols:**

```
ffffffff814d8810-ffffffff814d886d: sg_nents_for_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int sg_nents_for_len(struct scatterlist *sg, u64 len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81504770)
Location: lib/scatterlist.c:68
Inline: True
Direct callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
```
**Symbols:**

```
ffffffff81504770-ffffffff815047c6: sg_nents_for_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int sg_nents_for_len(struct scatterlist *sg, u64 len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81522700)
Location: lib/scatterlist.c:68
Inline: True
Direct callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
```
**Symbols:**

```
ffffffff81522700-ffffffff81522756: sg_nents_for_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int sg_nents_for_len(struct scatterlist *sg, u64 len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff815859f0)
Location: lib/scatterlist.c:68
Inline: True
Direct callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
```
**Symbols:**

```
ffffffff815859f0-ffffffff81585a46: sg_nents_for_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int sg_nents_for_len(struct scatterlist *sg, u64 len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff815a2ad0)
Location: lib/scatterlist.c:68
Inline: True
Direct callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
```
**Symbols:**

```
ffffffff815a2ad0-ffffffff815a2b26: sg_nents_for_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int sg_nents_for_len(struct scatterlist *sg, u64 len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff815a9a00)
Location: lib/scatterlist.c:68
Inline: True
Direct callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
```
**Symbols:**

```
ffffffff815a9a00-ffffffff815a9a56: sg_nents_for_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int sg_nents_for_len(struct scatterlist *sg, u64 len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81612c40)
Location: lib/scatterlist.c:68
Inline: True
Direct callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
```
**Symbols:**

```
ffffffff81612c40-ffffffff81612c96: sg_nents_for_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int sg_nents_for_len(struct scatterlist *sg, u64 len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff816df390)
Location: lib/scatterlist.c:68
Inline: True
Direct callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
```
**Symbols:**

```
ffffffff816df390-ffffffff816df3f0: sg_nents_for_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int sg_nents_for_len(struct scatterlist *sg, u64 len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff817cf5b0)
Location: lib/scatterlist.c:68
Inline: True
Direct callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
```
**Symbols:**

```
ffffffff817cf5b0-ffffffff817cf610: sg_nents_for_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int sg_nents_for_len(struct scatterlist *sg, u64 len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff8180da60)
Location: lib/scatterlist.c:70
Inline: True
Direct callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
```
**Symbols:**

```
ffffffff8180da60-ffffffff8180dac0: sg_nents_for_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int sg_nents_for_len(struct scatterlist *sg, u64 len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81853710)
Location: lib/scatterlist.c:70
Inline: True
Direct callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
  - lib/crypto/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/crypto/mpi/mpicoder.c:mpi_write_to_sgl
```
**Symbols:**

```
ffffffff81853710-ffffffff81853770: sg_nents_for_len (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int sg_nents_for_len(struct scatterlist *sg, u64 len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffff80001062c3a0)
Location: lib/scatterlist.c:68
Inline: True
Direct callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
```
**Symbols:**

```
ffff80001062c3a0-ffff80001062c400: sg_nents_for_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int sg_nents_for_len(struct scatterlist *sg, u64 len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (c07d2e28)
Location: lib/scatterlist.c:68
Inline: True
Direct callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
```
**Symbols:**

```
c07d2e28-c07d2ec0: sg_nents_for_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int sg_nents_for_len(struct scatterlist *sg, u64 len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (c0000000007cedd0)
Location: lib/scatterlist.c:68
Inline: True
Direct callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
```
**Symbols:**

```
c0000000007cedd0-c0000000007cee68: sg_nents_for_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int sg_nents_for_len(struct scatterlist *sg, u64 len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffe00045c5d6)
Location: lib/scatterlist.c:68
Inline: True
Direct callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
```
**Symbols:**

```
ffffffe00045c5d6-ffffffe00045c622: sg_nents_for_len (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int sg_nents_for_len(struct scatterlist *sg, u64 len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff8151ace0)
Location: lib/scatterlist.c:68
Inline: True
Direct callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
```
**Symbols:**

```
ffffffff8151ace0-ffffffff8151ad36: sg_nents_for_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int sg_nents_for_len(struct scatterlist *sg, u64 len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff8150afd0)
Location: lib/scatterlist.c:68
Inline: True
Direct callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
```
**Symbols:**

```
ffffffff8150afd0-ffffffff8150b026: sg_nents_for_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int sg_nents_for_len(struct scatterlist *sg, u64 len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81516d70)
Location: lib/scatterlist.c:68
Inline: True
Direct callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
```
**Symbols:**

```
ffffffff81516d70-ffffffff81516dc6: sg_nents_for_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int sg_nents_for_len(struct scatterlist *sg, u64 len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81530500)
Location: lib/scatterlist.c:68
Inline: True
Direct callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
```
**Symbols:**

```
ffffffff81530500-ffffffff81530556: sg_nents_for_len (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
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
