# Function: <code>scatterwalk_map_and_copy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void scatterwalk_map_and_copy(void *buf, struct scatterlist *sg, unsigned int start, unsigned int nbytes, int out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffffffff8139eba0)
Location: crypto/scatterwalk.c:107
Inline: False
```
**Symbols:**

```
ffffffff8139eba0-ffffffff8139ec87: scatterwalk_map_and_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void scatterwalk_map_and_copy(void *buf, struct scatterlist *sg, unsigned int start, unsigned int nbytes, int out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffffffff813db960)
Location: crypto/scatterwalk.c:60
Inline: False
Direct callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/cts.c:cts_cbc_encrypt
```
**Symbols:**

```
ffffffff813db960-ffffffff813dba38: scatterwalk_map_and_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void scatterwalk_map_and_copy(void *buf, struct scatterlist *sg, unsigned int start, unsigned int nbytes, int out);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffffffff813f32a0)
Location: crypto/scatterwalk.c:60
Inline: True
Direct callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/scompress.c:scomp_acomp_comp_decomp
  - crypto/scompress.c:scomp_acomp_comp_decomp
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/cts.c:cts_cbc_encrypt
```
**Symbols:**

```
ffffffff813f32a0-ffffffff813f3313: scatterwalk_map_and_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void scatterwalk_map_and_copy(void *buf, struct scatterlist *sg, unsigned int start, unsigned int nbytes, int out);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffffffff813ff5c0)
Location: crypto/scatterwalk.c:60
Inline: True
Direct callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/scompress.c:scomp_acomp_comp_decomp
  - crypto/scompress.c:scomp_acomp_comp_decomp
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/cts.c:cts_cbc_encrypt
```
**Symbols:**

```
ffffffff813ff5c0-ffffffff813ff633: scatterwalk_map_and_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void scatterwalk_map_and_copy(void *buf, struct scatterlist *sg, unsigned int start, unsigned int nbytes, int out);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffffffff81427b80)
Location: crypto/scatterwalk.c:60
Inline: True
Direct callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/scompress.c:scomp_acomp_comp_decomp
  - crypto/scompress.c:scomp_acomp_comp_decomp
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:gcm_enc_copy_hash
```
**Symbols:**

```
ffffffff81427b80-ffffffff81427bf3: scatterwalk_map_and_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void scatterwalk_map_and_copy(void *buf, struct scatterlist *sg, unsigned int start, unsigned int nbytes, int out);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffffffff8145a9e0)
Location: crypto/scatterwalk.c:60
Inline: True
Direct callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/scompress.c:scomp_acomp_comp_decomp
  - crypto/scompress.c:scomp_acomp_comp_decomp
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:gcm_enc_copy_hash
```
**Symbols:**

```
ffffffff8145a9e0-ffffffff8145aa50: scatterwalk_map_and_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void scatterwalk_map_and_copy(void *buf, struct scatterlist *sg, unsigned int start, unsigned int nbytes, int out);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffffffff81478550)
Location: crypto/scatterwalk.c:60
Inline: True
Direct callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/scompress.c:scomp_acomp_comp_decomp
  - crypto/scompress.c:scomp_acomp_comp_decomp
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:gcm_enc_copy_hash
```
**Symbols:**

```
ffffffff81478550-ffffffff814785c0: scatterwalk_map_and_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void scatterwalk_map_and_copy(void *buf, struct scatterlist *sg, unsigned int start, unsigned int nbytes, int out);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffffffff814a6370)
Location: crypto/scatterwalk.c:55
Inline: True
Direct callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/scompress.c:scomp_acomp_comp_decomp
  - crypto/scompress.c:scomp_acomp_comp_decomp
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:gcm_enc_copy_hash
```
**Symbols:**

```
ffffffff814a6370-ffffffff814a63e0: scatterwalk_map_and_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void scatterwalk_map_and_copy(void *buf, struct scatterlist *sg, unsigned int start, unsigned int nbytes, int out);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffffffff814c1000)
Location: crypto/scatterwalk.c:55
Inline: True
Direct callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/scompress.c:scomp_acomp_comp_decomp
  - crypto/scompress.c:scomp_acomp_comp_decomp
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/xts.c:cts_final
  - crypto/xts.c:cts_final
  - crypto/xts.c:cts_final
  - crypto/xts.c:cts_final
  - crypto/xts.c:cts_final
  - crypto/xts.c:cts_done
  - crypto/xts.c:cts_done
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:gcm_enc_copy_hash
```
**Symbols:**

```
ffffffff814c1000-ffffffff814c1070: scatterwalk_map_and_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void scatterwalk_map_and_copy(void *buf, struct scatterlist *sg, unsigned int start, unsigned int nbytes, int out);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffffffff815218b0)
Location: crypto/scatterwalk.c:55
Inline: True
Direct callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/scompress.c:scomp_acomp_comp_decomp
  - crypto/scompress.c:scomp_acomp_comp_decomp
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/xts.c:cts_final
  - crypto/xts.c:cts_final
  - crypto/xts.c:cts_final
  - crypto/xts.c:cts_final
  - crypto/xts.c:cts_final
  - crypto/xts.c:cts_done
  - crypto/xts.c:cts_done
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:gcm_enc_copy_hash
```
**Symbols:**

```
ffffffff815218b0-ffffffff81521920: scatterwalk_map_and_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void scatterwalk_map_and_copy(void *buf, struct scatterlist *sg, unsigned int start, unsigned int nbytes, int out);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffffffff8153e720)
Location: crypto/scatterwalk.c:55
Inline: True
Direct callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/scompress.c:scomp_acomp_comp_decomp
  - crypto/scompress.c:scomp_acomp_comp_decomp
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/xts.c:xts_cts_final
  - crypto/xts.c:xts_cts_final
  - crypto/xts.c:xts_cts_final
  - crypto/xts.c:xts_cts_final
  - crypto/xts.c:xts_cts_final
  - crypto/xts.c:xts_cts_done
  - crypto/xts.c:xts_cts_done
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:gcm_enc_copy_hash
```
**Symbols:**

```
ffffffff8153e720-ffffffff8153e790: scatterwalk_map_and_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void scatterwalk_map_and_copy(void *buf, struct scatterlist *sg, unsigned int start, unsigned int nbytes, int out);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffffffff81546dd0)
Location: crypto/scatterwalk.c:55
Inline: True
Direct callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/scompress.c:scomp_acomp_comp_decomp
  - crypto/scompress.c:scomp_acomp_comp_decomp
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/xts.c:xts_cts_final
  - crypto/xts.c:xts_cts_final
  - crypto/xts.c:xts_cts_final
  - crypto/xts.c:xts_cts_final
  - crypto/xts.c:xts_cts_final
  - crypto/xts.c:xts_cts_done
  - crypto/xts.c:xts_cts_done
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:gcm_enc_copy_hash
```
**Symbols:**

```
ffffffff81546dd0-ffffffff81546e40: scatterwalk_map_and_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void scatterwalk_map_and_copy(void *buf, struct scatterlist *sg, unsigned int start, unsigned int nbytes, int out);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffffffff815a75b0)
Location: crypto/scatterwalk.c:55
Inline: True
Direct callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/scompress.c:scomp_acomp_comp_decomp
  - crypto/scompress.c:scomp_acomp_comp_decomp
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/xts.c:xts_cts_final
  - crypto/xts.c:xts_cts_final
  - crypto/xts.c:xts_cts_final
  - crypto/xts.c:xts_cts_final
  - crypto/xts.c:xts_cts_final
  - crypto/xts.c:xts_cts_done
  - crypto/xts.c:xts_cts_done
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:gcm_enc_copy_hash
```
**Symbols:**

```
ffffffff815a75b0-ffffffff815a7620: scatterwalk_map_and_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void scatterwalk_map_and_copy(void *buf, struct scatterlist *sg, unsigned int start, unsigned int nbytes, int out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffffffff8164e870)
Location: crypto/scatterwalk.c:55
Inline: False
Direct callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/scompress.c:scomp_acomp_comp_decomp
  - crypto/scompress.c:scomp_acomp_comp_decomp
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/xts.c:xts_cts_final
  - crypto/xts.c:xts_cts_final
  - crypto/xts.c:xts_cts_final
  - crypto/xts.c:xts_cts_final
  - crypto/xts.c:xts_cts_final
  - crypto/xts.c:xts_cts_done
  - crypto/xts.c:xts_cts_done
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:gcm_enc_copy_hash
```
**Symbols:**

```
ffffffff8164e870-ffffffff8164e90f: scatterwalk_map_and_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void scatterwalk_map_and_copy(void *buf, struct scatterlist *sg, unsigned int start, unsigned int nbytes, int out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffffffff81707ce0)
Location: crypto/scatterwalk.c:55
Inline: False
Direct callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/scompress.c:scomp_acomp_comp_decomp
  - crypto/scompress.c:scomp_acomp_comp_decomp
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/xts.c:xts_cts_final
  - crypto/xts.c:xts_cts_final
  - crypto/xts.c:xts_cts_final
  - crypto/xts.c:xts_cts_final
  - crypto/xts.c:xts_cts_final
  - crypto/xts.c:xts_cts_done
  - crypto/xts.c:xts_cts_done
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:gcm_enc_copy_hash
```
**Symbols:**

```
ffffffff81707ce0-ffffffff81707d7f: scatterwalk_map_and_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void scatterwalk_map_and_copy(void *buf, struct scatterlist *sg, unsigned int start, unsigned int nbytes, int out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffffffff81741400)
Location: crypto/scatterwalk.c:55
Inline: False
Direct callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/scompress.c:scomp_acomp_comp_decomp
  - crypto/scompress.c:scomp_acomp_comp_decomp
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/xts.c:xts_cts_final
  - crypto/xts.c:xts_cts_final
  - crypto/xts.c:xts_cts_final
  - crypto/xts.c:xts_cts_final
  - crypto/xts.c:xts_cts_final
  - crypto/xts.c:xts_cts_done
  - crypto/xts.c:xts_cts_done
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:gcm_enc_copy_hash
```
**Symbols:**

```
ffffffff81741400-ffffffff8174149f: scatterwalk_map_and_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void scatterwalk_map_and_copy(void *buf, struct scatterlist *sg, unsigned int start, unsigned int nbytes, int out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffffffff817822a0)
Location: crypto/scatterwalk.c:55
Inline: False
Direct callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/scompress.c:scomp_acomp_comp_decomp
  - crypto/scompress.c:scomp_acomp_comp_decomp
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/xts.c:xts_cts_final
  - crypto/xts.c:xts_cts_final
  - crypto/xts.c:xts_cts_final
  - crypto/xts.c:xts_cts_final
  - crypto/xts.c:xts_cts_final
  - crypto/xts.c:xts_cts_done
  - crypto/xts.c:xts_cts_done
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:gcm_enc_copy_hash
```
**Symbols:**

```
ffffffff817822a0-ffffffff8178233f: scatterwalk_map_and_copy (STB_GLOBAL)
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
void scatterwalk_map_and_copy(void *buf, struct scatterlist *sg, unsigned int start, unsigned int nbytes, int out);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffff8000105bb1b0)
Location: crypto/scatterwalk.c:55
Inline: True
Direct callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/scompress.c:scomp_acomp_comp_decomp
  - crypto/scompress.c:scomp_acomp_comp_decomp
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/xts.c:cts_final
  - crypto/xts.c:cts_final
  - crypto/xts.c:cts_final
  - crypto/xts.c:cts_final
  - crypto/xts.c:cts_final
  - crypto/xts.c:cts_done
  - crypto/xts.c:cts_done
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:gcm_enc_copy_hash
```
**Symbols:**

```
ffff8000105bb1b0-ffff8000105bb298: scatterwalk_map_and_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void scatterwalk_map_and_copy(void *buf, struct scatterlist *sg, unsigned int start, unsigned int nbytes, int out);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (c07694b4)
Location: crypto/scatterwalk.c:55
Inline: True
Direct callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/scompress.c:scomp_acomp_comp_decomp
  - crypto/scompress.c:scomp_acomp_comp_decomp
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/xts.c:cts_final
  - crypto/xts.c:cts_final
  - crypto/xts.c:cts_final
  - crypto/xts.c:cts_final
  - crypto/xts.c:cts_final
  - crypto/xts.c:cts_done
  - crypto/xts.c:cts_done
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:gcm_enc_copy_hash
```
**Symbols:**

```
c07694b4-c076958c: scatterwalk_map_and_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void scatterwalk_map_and_copy(void *buf, struct scatterlist *sg, unsigned int start, unsigned int nbytes, int out);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (c000000000741910)
Location: crypto/scatterwalk.c:55
Inline: True
Direct callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/scompress.c:scomp_acomp_comp_decomp
  - crypto/scompress.c:scomp_acomp_comp_decomp
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/xts.c:cts_final
  - crypto/xts.c:cts_final
  - crypto/xts.c:cts_final
  - crypto/xts.c:cts_final
  - crypto/xts.c:cts_final
  - crypto/xts.c:cts_done
  - crypto/xts.c:cts_done
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:gcm_enc_copy_hash
```
**Symbols:**

```
c000000000741910-c000000000741a40: scatterwalk_map_and_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void scatterwalk_map_and_copy(void *buf, struct scatterlist *sg, unsigned int start, unsigned int nbytes, int out);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffffffe000400d34)
Location: crypto/scatterwalk.c:55
Inline: True
Direct callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/scompress.c:scomp_acomp_comp_decomp
  - crypto/scompress.c:scomp_acomp_comp_decomp
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/xts.c:cts_final
  - crypto/xts.c:cts_final
  - crypto/xts.c:cts_final
  - crypto/xts.c:cts_final
  - crypto/xts.c:cts_final
  - crypto/xts.c:cts_done
  - crypto/xts.c:cts_done
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:gcm_enc_copy_hash
```
**Symbols:**

```
ffffffe000400d34-ffffffe000400da0: scatterwalk_map_and_copy (STB_GLOBAL)
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
void scatterwalk_map_and_copy(void *buf, struct scatterlist *sg, unsigned int start, unsigned int nbytes, int out);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffffffff814b95e0)
Location: crypto/scatterwalk.c:55
Inline: True
Direct callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/scompress.c:scomp_acomp_comp_decomp
  - crypto/scompress.c:scomp_acomp_comp_decomp
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/xts.c:cts_final
  - crypto/xts.c:cts_final
  - crypto/xts.c:cts_final
  - crypto/xts.c:cts_final
  - crypto/xts.c:cts_final
  - crypto/xts.c:cts_done
  - crypto/xts.c:cts_done
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:gcm_enc_copy_hash
```
**Symbols:**

```
ffffffff814b95e0-ffffffff814b9650: scatterwalk_map_and_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void scatterwalk_map_and_copy(void *buf, struct scatterlist *sg, unsigned int start, unsigned int nbytes, int out);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffffffff814aa000)
Location: crypto/scatterwalk.c:55
Inline: True
Direct callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/scompress.c:scomp_acomp_comp_decomp
  - crypto/scompress.c:scomp_acomp_comp_decomp
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/xts.c:cts_final
  - crypto/xts.c:cts_final
  - crypto/xts.c:cts_final
  - crypto/xts.c:cts_final
  - crypto/xts.c:cts_final
  - crypto/xts.c:cts_done
  - crypto/xts.c:cts_done
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:gcm_enc_copy_hash
```
**Symbols:**

```
ffffffff814aa000-ffffffff814aa070: scatterwalk_map_and_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void scatterwalk_map_and_copy(void *buf, struct scatterlist *sg, unsigned int start, unsigned int nbytes, int out);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffffffff814b5670)
Location: crypto/scatterwalk.c:55
Inline: True
Direct callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/scompress.c:scomp_acomp_comp_decomp
  - crypto/scompress.c:scomp_acomp_comp_decomp
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/xts.c:cts_final
  - crypto/xts.c:cts_final
  - crypto/xts.c:cts_final
  - crypto/xts.c:cts_final
  - crypto/xts.c:cts_final
  - crypto/xts.c:cts_done
  - crypto/xts.c:cts_done
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:gcm_enc_copy_hash
```
**Symbols:**

```
ffffffff814b5670-ffffffff814b56e0: scatterwalk_map_and_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void scatterwalk_map_and_copy(void *buf, struct scatterlist *sg, unsigned int start, unsigned int nbytes, int out);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffffffff814ce110)
Location: crypto/scatterwalk.c:55
Inline: True
Direct callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/scompress.c:scomp_acomp_comp_decomp
  - crypto/scompress.c:scomp_acomp_comp_decomp
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/xts.c:cts_final
  - crypto/xts.c:cts_final
  - crypto/xts.c:cts_final
  - crypto/xts.c:cts_final
  - crypto/xts.c:cts_final
  - crypto/xts.c:cts_done
  - crypto/xts.c:cts_done
  - crypto/gcm.c:crypto_rfc4106_crypt
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:gcm_enc_copy_hash
```
**Symbols:**

```
ffffffff814ce110-ffffffff814ce180: scatterwalk_map_and_copy (STB_GLOBAL)
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
