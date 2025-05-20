# Function: <code>aead_request_ctx</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/seqiv.c (ffffffff813dea38)
Location: include/crypto/internal/aead.h:68
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/seqiv.c (ffffffff813f6fd8)
Location: include/crypto/internal/aead.h:68
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/seqiv.c (ffffffff814033d4)
Location: include/crypto/internal/aead.h:68
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/seqiv.c (ffffffff8142baca)
Location: include/crypto/internal/aead.h:68
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/gcm.c (ffffffff8143a299)
Location: include/crypto/internal/aead.h:68
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:gcm_hash_crypt_remain_continue
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/seqiv.c (ffffffff8145e519)
Location: include/crypto/internal/aead.h:68
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/gcm.c (ffffffff8146c37a)
Location: include/crypto/internal/aead.h:68
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:gcm_encrypt_continue
  - crypto/gcm.c:gcm_enc_copy_hash
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_init_continue
  - crypto/gcm.c:gcm_hash_assoc_continue
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
  - crypto/gcm.c:gcm_hash_len_done
  - crypto/gcm.c:crypto_gcm_init_common
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/seqiv.c (ffffffff8147bde6)
Location: include/crypto/internal/aead.h:68
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/gcm.c (ffffffff8148a6fa)
Location: include/crypto/internal/aead.h:68
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:gcm_encrypt_continue
  - crypto/gcm.c:gcm_enc_copy_hash
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
  - crypto/gcm.c:gcm_hash_len_done
  - crypto/gcm.c:gcm_hash_update
  - crypto/gcm.c:crypto_gcm_init_common
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/seqiv.c (ffffffff814aa1d9)
Location: include/crypto/internal/aead.h:63
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/gcm.c (ffffffff814b7e2a)
Location: include/crypto/internal/aead.h:63
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:gcm_encrypt_continue
  - crypto/gcm.c:gcm_enc_copy_hash
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
  - crypto/gcm.c:gcm_hash_len_done
  - crypto/gcm.c:gcm_hash_update
  - crypto/gcm.c:crypto_gcm_init_common
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/seqiv.c (ffffffff814c4e99)
Location: include/crypto/internal/aead.h:63
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/gcm.c (ffffffff814d104a)
Location: include/crypto/internal/aead.h:63
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:gcm_encrypt_continue
  - crypto/gcm.c:gcm_enc_copy_hash
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
  - crypto/gcm.c:gcm_hash_len_done
  - crypto/gcm.c:gcm_hash_update
  - crypto/gcm.c:crypto_gcm_init_common
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/seqiv.c (ffffffff81523da9)
Location: include/crypto/internal/aead.h:63
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/gcm.c (ffffffff8153009a)
Location: include/crypto/internal/aead.h:63
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:gcm_encrypt_continue
  - crypto/gcm.c:gcm_enc_copy_hash
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
  - crypto/gcm.c:gcm_hash_crypt_remain_continue
  - crypto/gcm.c:gcm_hash_len_done
  - crypto/gcm.c:gcm_hash_len
  - crypto/gcm.c:gcm_hash_update
  - crypto/gcm.c:crypto_gcm_init_common
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/seqiv.c (ffffffff81540c29)
Location: include/crypto/internal/aead.h:63
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/gcm.c (ffffffff8154cc7a)
Location: include/crypto/internal/aead.h:63
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:gcm_encrypt_continue
  - crypto/gcm.c:gcm_enc_copy_hash
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
  - crypto/gcm.c:gcm_hash_crypt_remain_continue
  - crypto/gcm.c:gcm_hash_len_done
  - crypto/gcm.c:gcm_hash_len
  - crypto/gcm.c:gcm_hash_update
  - crypto/gcm.c:crypto_gcm_init_common
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/seqiv.c (ffffffff81549292)
Location: include/crypto/internal/aead.h:63
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/gcm.c (ffffffff8155574a)
Location: include/crypto/internal/aead.h:63
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:gcm_encrypt_continue
  - crypto/gcm.c:gcm_enc_copy_hash
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
  - crypto/gcm.c:gcm_hash_crypt_remain_continue
  - crypto/gcm.c:gcm_hash_len_done
  - crypto/gcm.c:gcm_hash_update
  - crypto/gcm.c:crypto_gcm_init_common
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/seqiv.c (ffffffff815a9a72)
Location: include/crypto/internal/aead.h:63
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/gcm.c (ffffffff815b4cc4)
Location: include/crypto/internal/aead.h:63
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:gcm_encrypt_continue
  - crypto/gcm.c:gcm_enc_copy_hash
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
  - crypto/gcm.c:gcm_hash_crypt_remain_continue
  - crypto/gcm.c:gcm_hash_len_done
  - crypto/gcm.c:gcm_hash_update
  - crypto/gcm.c:crypto_gcm_init_common
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/seqiv.c (ffffffff81650f31)
Location: include/crypto/internal/aead.h:63
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/gcm.c (ffffffff8165dc74)
Location: include/crypto/internal/aead.h:63
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:gcm_encrypt_continue
  - crypto/gcm.c:gcm_enc_copy_hash
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
  - crypto/gcm.c:gcm_hash_crypt_remain_continue
  - crypto/gcm.c:gcm_hash_len_done
  - crypto/gcm.c:gcm_hash_update
  - crypto/gcm.c:crypto_gcm_init_common
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/seqiv.c (ffffffff8170a761)
Location: include/crypto/internal/aead.h:68
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/gcm.c (ffffffff81717cb4)
Location: include/crypto/internal/aead.h:68
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:gcm_encrypt_continue
  - crypto/gcm.c:gcm_enc_copy_hash
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
  - crypto/gcm.c:gcm_hash_crypt_remain_continue
  - crypto/gcm.c:gcm_hash_len_done
  - crypto/gcm.c:gcm_hash_update
  - crypto/gcm.c:crypto_gcm_init_common
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/seqiv.c (ffffffff81743fb1)
Location: include/crypto/internal/aead.h:68
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/gcm.c (ffffffff817535d4)
Location: include/crypto/internal/aead.h:68
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:gcm_encrypt_continue
  - crypto/gcm.c:gcm_enc_copy_hash
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
  - crypto/gcm.c:gcm_hash_crypt_remain_continue
  - crypto/gcm.c:gcm_hash_len_done
  - crypto/gcm.c:gcm_hash_len
  - crypto/gcm.c:gcm_hash_update
  - crypto/gcm.c:crypto_gcm_init_common
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/seqiv.c (ffffffff81786571)
Location: include/crypto/internal/aead.h:68
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/gcm.c (ffffffff817954a4)
Location: include/crypto/internal/aead.h:68
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:gcm_encrypt_continue
  - crypto/gcm.c:gcm_enc_copy_hash
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_init_continue
  - crypto/gcm.c:gcm_hash_assoc_continue
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
  - crypto/gcm.c:gcm_hash_crypt_remain_continue
  - crypto/gcm.c:gcm_hash_len_done
  - crypto/gcm.c:gcm_hash_len
  - crypto/gcm.c:crypto_gcm_init_common
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/seqiv.c (ffff8000105bfa50)
Location: include/crypto/internal/aead.h:63
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/gcm.c (ffff8000105cd2e4)
Location: include/crypto/internal/aead.h:63
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:gcm_encrypt_continue
  - crypto/gcm.c:gcm_enc_copy_hash
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
  - crypto/gcm.c:gcm_hash_len_done
  - crypto/gcm.c:gcm_hash_update
  - crypto/gcm.c:crypto_gcm_init_common
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/seqiv.c (c076d6a4)
Location: include/crypto/internal/aead.h:63
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/gcm.c (c0778fac)
Location: include/crypto/internal/aead.h:63
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:gcm_encrypt_continue
  - crypto/gcm.c:gcm_enc_copy_hash
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
  - crypto/gcm.c:gcm_hash_len_done
  - crypto/gcm.c:gcm_hash_update
  - crypto/gcm.c:crypto_gcm_init_common
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/seqiv.c (c000000000747814)
Location: include/crypto/internal/aead.h:63
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/gcm.c (c00000000075829c)
Location: include/crypto/internal/aead.h:63
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:gcm_encrypt_continue
  - crypto/gcm.c:gcm_enc_copy_hash
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
  - crypto/gcm.c:gcm_hash_len_done
  - crypto/gcm.c:gcm_hash_update
  - crypto/gcm.c:crypto_gcm_init_common
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/seqiv.c (ffffffe000404b26)
Location: include/crypto/internal/aead.h:63
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/gcm.c (ffffffe000410b7c)
Location: include/crypto/internal/aead.h:63
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:gcm_encrypt_continue
  - crypto/gcm.c:gcm_enc_copy_hash
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
  - crypto/gcm.c:gcm_hash_len_done
  - crypto/gcm.c:gcm_hash_update
  - crypto/gcm.c:crypto_gcm_init_common
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/seqiv.c (ffffffff814bd479)
Location: include/crypto/internal/aead.h:63
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/gcm.c (ffffffff814c962a)
Location: include/crypto/internal/aead.h:63
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:gcm_encrypt_continue
  - crypto/gcm.c:gcm_enc_copy_hash
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
  - crypto/gcm.c:gcm_hash_len_done
  - crypto/gcm.c:gcm_hash_update
  - crypto/gcm.c:crypto_gcm_init_common
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/seqiv.c (ffffffff814ade99)
Location: include/crypto/internal/aead.h:63
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/gcm.c (ffffffff814ba04a)
Location: include/crypto/internal/aead.h:63
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:gcm_encrypt_continue
  - crypto/gcm.c:gcm_enc_copy_hash
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
  - crypto/gcm.c:gcm_hash_len_done
  - crypto/gcm.c:gcm_hash_update
  - crypto/gcm.c:crypto_gcm_init_common
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/seqiv.c (ffffffff814b9509)
Location: include/crypto/internal/aead.h:63
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/gcm.c (ffffffff814c56ba)
Location: include/crypto/internal/aead.h:63
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:gcm_encrypt_continue
  - crypto/gcm.c:gcm_enc_copy_hash
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
  - crypto/gcm.c:gcm_hash_len_done
  - crypto/gcm.c:gcm_hash_update
  - crypto/gcm.c:crypto_gcm_init_common
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/seqiv.c (ffffffff814d1fa9)
Location: include/crypto/internal/aead.h:63
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/gcm.c (ffffffff814de18a)
Location: include/crypto/internal/aead.h:63
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_decrypt
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:gcm_encrypt_continue
  - crypto/gcm.c:gcm_enc_copy_hash
  - crypto/gcm.c:gcm_hash
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
  - crypto/gcm.c:gcm_hash_len_done
  - crypto/gcm.c:gcm_hash_update
  - crypto/gcm.c:crypto_gcm_init_common
```
</details>
</li>
</ul>

## Differences
