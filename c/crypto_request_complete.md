# Function: <code>crypto_request_complete</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/seqiv.c (ffffffff817441a7)
Location: include/crypto/algapi.h:271
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt_complete
```
```
In crypto/ahash.c (ffffffff817456e5)
Location: include/crypto/algapi.h:271
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_def_finup_done1
  - crypto/ahash.c:ahash_op_unaligned_done
```
```
In crypto/dh.c (ffffffff817481b5)
Location: include/crypto/algapi.h:271
Inline: True
Inline callers:
  - crypto/dh.c:dh_safe_prime_complete_req
```
```
In crypto/rsa-pkcs1pad.c (ffffffff81749fc9)
Location: include/crypto/algapi.h:271
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete_cb
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete_cb
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete_cb
```
```
In crypto/cts.c (ffffffff817519a1)
Location: include/crypto/algapi.h:271
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt_done
  - crypto/cts.c:crypto_cts_encrypt_done
  - crypto/cts.c:cts_cbc_crypt_done
```
```
In crypto/xts.c (ffffffff81752061)
Location: include/crypto/algapi.h:271
Inline: True
Inline callers:
  - crypto/xts.c:xts_decrypt_done
  - crypto/xts.c:xts_encrypt_done
  - crypto/xts.c:xts_cts_done
```
```
In crypto/gcm.c (ffffffff817540c1)
Location: include/crypto/algapi.h:271
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_decrypt_done
  - crypto/gcm.c:gcm_encrypt_done
  - crypto/gcm.c:gcm_hash_init_done
  - crypto/gcm.c:gcm_hash_assoc_done
  - crypto/gcm.c:gcm_hash_assoc_remain_done
  - crypto/gcm.c:gcm_hash_crypt_done
  - crypto/gcm.c:gcm_hash_crypt_remain_done
  - crypto/gcm.c:gcm_hash_len_done
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
In crypto/seqiv.c (ffffffff81786767)
Location: include/crypto/algapi.h:266
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt_complete
```
```
In crypto/ahash.c (ffffffff8178702e)
Location: include/crypto/algapi.h:266
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_def_finup_done1
```
```
In crypto/dh.c (ffffffff8178a025)
Location: include/crypto/algapi.h:266
Inline: True
Inline callers:
  - crypto/dh.c:dh_safe_prime_complete_req
```
```
In crypto/rsa-pkcs1pad.c (ffffffff8178be69)
Location: include/crypto/algapi.h:266
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete_cb
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete_cb
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete_cb
```
```
In crypto/cts.c (ffffffff81793821)
Location: include/crypto/algapi.h:266
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt_done
  - crypto/cts.c:crypto_cts_encrypt_done
  - crypto/cts.c:cts_cbc_crypt_done
```
```
In crypto/xts.c (ffffffff81793ee1)
Location: include/crypto/algapi.h:266
Inline: True
Inline callers:
  - crypto/xts.c:xts_decrypt_done
  - crypto/xts.c:xts_encrypt_done
  - crypto/xts.c:xts_cts_done
```
```
In crypto/gcm.c (ffffffff81795a31)
Location: include/crypto/algapi.h:266
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_decrypt_done
  - crypto/gcm.c:gcm_encrypt_done
  - crypto/gcm.c:gcm_hash_init_done
  - crypto/gcm.c:gcm_hash_assoc_done
  - crypto/gcm.c:gcm_hash_assoc_remain_done
  - crypto/gcm.c:gcm_hash_crypt_done
  - crypto/gcm.c:gcm_hash_crypt_remain_done
  - crypto/gcm.c:gcm_hash_len_done
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
