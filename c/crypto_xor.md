# Function: <code>crypto_xor</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void crypto_xor(u8 *dst, const u8 *src, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff8139d1b0)
Location: crypto/algapi.c:972
Inline: False
Direct callers:
  - crypto/cbc.c:crypto_cbc_encrypt
  - crypto/cbc.c:crypto_cbc_encrypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
```
**Symbols:**

```
ffffffff8139d1b0-ffffffff8139d215: crypto_xor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void crypto_xor(u8 *dst, const u8 *src, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff813da080)
Location: crypto/algapi.c:981
Inline: False
Direct callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
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
ffffffff813da080-ffffffff813da0de: crypto_xor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void crypto_xor(u8 *dst, const u8 *src, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff813f19c0)
Location: crypto/algapi.c:982
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
```
**Symbols:**

```
ffffffff813f19c0-ffffffff813f1a1e: crypto_xor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/seqiv.c (ffffffff814033bd)
Location: include/crypto/algapi.h:197
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cbc.c (ffffffff8140d735)
Location: include/crypto/algapi.h:197
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
```
```
In crypto/cts.c (ffffffff8140df38)
Location: include/crypto/algapi.h:197
Inline: True
Inline callers:
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
```
```
In crypto/ctr.c (ffffffff8140f902)
Location: include/crypto/algapi.h:197
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
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
In crypto/seqiv.c (ffffffff8142bab3)
Location: include/crypto/algapi.h:197
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cbc.c (ffffffff814361b8)
Location: include/crypto/algapi.h:197
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
```
```
In crypto/cts.c (ffffffff814369d9)
Location: include/crypto/algapi.h:197
Inline: True
Inline callers:
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
```
```
In crypto/ctr.c (ffffffff81438405)
Location: include/crypto/algapi.h:197
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/gcm.c (ffffffff81439261)
Location: include/crypto/algapi.h:197
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:gcm_enc_copy_hash
```
```
In crypto/ghash-generic.c (ffffffff814413e7)
Location: include/crypto/algapi.h:197
Inline: True
Inline callers:
  - crypto/ghash-generic.c:ghash_update
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
In crypto/seqiv.c (ffffffff8145e7c3)
Location: include/crypto/algapi.h:204
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cbc.c (ffffffff81468b89)
Location: include/crypto/algapi.h:204
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
```
```
In crypto/cts.c (ffffffff8146958a)
Location: include/crypto/algapi.h:204
Inline: True
Inline callers:
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
```
```
In crypto/ctr.c (ffffffff8146ad84)
Location: include/crypto/algapi.h:204
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/gcm.c (ffffffff8146bbfd)
Location: include/crypto/algapi.h:204
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:gcm_enc_copy_hash
```
```
In crypto/ghash-generic.c (0)
Location: include/crypto/algapi.h:204
Inline: True
Inline callers:
  - crypto/ghash-generic.c:ghash_update
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
In crypto/seqiv.c (ffffffff8147c0ec)
Location: include/crypto/algapi.h:206
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cbc.c (ffffffff81486809)
Location: include/crypto/algapi.h:206
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
```
```
In crypto/cts.c (ffffffff8148726a)
Location: include/crypto/algapi.h:206
Inline: True
Inline callers:
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
```
```
In crypto/ctr.c (ffffffff814885e4)
Location: include/crypto/algapi.h:206
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/gcm.c (ffffffff8148915d)
Location: include/crypto/algapi.h:206
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:gcm_enc_copy_hash
```
```
In crypto/ghash-generic.c (0)
Location: include/crypto/algapi.h:206
Inline: True
Inline callers:
  - crypto/ghash-generic.c:ghash_update
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
In crypto/seqiv.c (ffffffff814aa451)
Location: include/crypto/algapi.h:200
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cbc.c (ffffffff814b467a)
Location: include/crypto/algapi.h:200
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
```
```
In crypto/cts.c (ffffffff814b5001)
Location: include/crypto/algapi.h:200
Inline: True
Inline callers:
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
```
```
In crypto/ctr.c (ffffffff814b6015)
Location: include/crypto/algapi.h:200
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/gcm.c (ffffffff814b6dfd)
Location: include/crypto/algapi.h:200
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:gcm_enc_copy_hash
```
```
In crypto/ghash-generic.c (0)
Location: include/crypto/algapi.h:200
Inline: True
Inline callers:
  - crypto/ghash-generic.c:ghash_update
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
In crypto/seqiv.c (ffffffff814c5111)
Location: include/crypto/algapi.h:200
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cbc.c (ffffffff814cd3ea)
Location: include/crypto/algapi.h:200
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
```
```
In crypto/cts.c (ffffffff814cdd86)
Location: include/crypto/algapi.h:200
Inline: True
Inline callers:
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
```
```
In crypto/ctr.c (ffffffff814cf215)
Location: include/crypto/algapi.h:200
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/gcm.c (ffffffff814d001d)
Location: include/crypto/algapi.h:200
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:gcm_enc_copy_hash
```
```
In crypto/ghash-generic.c (0)
Location: include/crypto/algapi.h:200
Inline: True
Inline callers:
  - crypto/ghash-generic.c:ghash_update
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
In crypto/seqiv.c (ffffffff81524021)
Location: include/crypto/algapi.h:139
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cbc.c (ffffffff8152ca70)
Location: include/crypto/algapi.h:139
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
```
```
In crypto/cts.c (ffffffff8152d135)
Location: include/crypto/algapi.h:139
Inline: True
Inline callers:
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
```
```
In crypto/ctr.c (ffffffff8152e52d)
Location: include/crypto/algapi.h:139
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/gcm.c (ffffffff8152f1fd)
Location: include/crypto/algapi.h:139
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:gcm_enc_copy_hash
```
```
In crypto/ghash-generic.c (0)
Location: include/crypto/algapi.h:139
Inline: True
Inline callers:
  - crypto/ghash-generic.c:ghash_update
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
In crypto/seqiv.c (ffffffff81540f30)
Location: include/crypto/algapi.h:139
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cbc.c (ffffffff81549a32)
Location: include/crypto/algapi.h:139
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt_inplace
  - crypto/cbc.c:crypto_cbc_decrypt_inplace
  - crypto/cbc.c:crypto_cbc_decrypt_segment
  - crypto/cbc.c:crypto_cbc_encrypt
  - crypto/cbc.c:crypto_cbc_encrypt
```
```
In crypto/cts.c (ffffffff8154a1a5)
Location: include/crypto/algapi.h:139
Inline: True
Inline callers:
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
```
```
In crypto/ctr.c (ffffffff8154b4cd)
Location: include/crypto/algapi.h:139
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/gcm.c (ffffffff8154c17d)
Location: include/crypto/algapi.h:139
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:gcm_enc_copy_hash
```
```
In crypto/ghash-generic.c (0)
Location: include/crypto/algapi.h:139
Inline: True
Inline callers:
  - crypto/ghash-generic.c:ghash_update
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
In crypto/seqiv.c (ffffffff81549591)
Location: include/crypto/algapi.h:139
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cbc.c (ffffffff81552139)
Location: include/crypto/algapi.h:139
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_encrypt
  - crypto/cbc.c:crypto_cbc_encrypt
```
```
In crypto/cts.c (ffffffff815527e5)
Location: include/crypto/algapi.h:139
Inline: True
Inline callers:
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
```
```
In crypto/ctr.c (ffffffff81553ae5)
Location: include/crypto/algapi.h:139
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/gcm.c (ffffffff8155476d)
Location: include/crypto/algapi.h:139
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:gcm_enc_copy_hash
```
```
In crypto/ghash-generic.c (0)
Location: include/crypto/algapi.h:139
Inline: True
Inline callers:
  - crypto/ghash-generic.c:ghash_update
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
In crypto/seqiv.c (ffffffff815a9d71)
Location: include/crypto/algapi.h:147
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cbc.c (ffffffff815b3139)
Location: include/crypto/algapi.h:147
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_encrypt
  - crypto/cbc.c:crypto_cbc_encrypt
```
```
In crypto/cts.c (ffffffff815b37e5)
Location: include/crypto/algapi.h:147
Inline: True
Inline callers:
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
```
```
In crypto/ctr.c (ffffffff815b4b15)
Location: include/crypto/algapi.h:147
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/gcm.c (ffffffff815b579d)
Location: include/crypto/algapi.h:147
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:gcm_enc_copy_hash
```
```
In crypto/ghash-generic.c (0)
Location: include/crypto/algapi.h:147
Inline: True
Inline callers:
  - crypto/ghash-generic.c:ghash_update
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
In crypto/seqiv.c (ffffffff81651262)
Location: include/crypto/algapi.h:152
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cbc.c (ffffffff8165bd7f)
Location: include/crypto/algapi.h:152
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt_inplace
  - crypto/cbc.c:crypto_cbc_decrypt_inplace
  - crypto/cbc.c:crypto_cbc_decrypt_inplace
  - crypto/cbc.c:crypto_cbc_decrypt_inplace
  - crypto/cbc.c:crypto_cbc_encrypt
  - crypto/cbc.c:crypto_cbc_encrypt
  - crypto/cbc.c:crypto_cbc_encrypt
  - crypto/cbc.c:crypto_cbc_encrypt
```
```
In crypto/cts.c (ffffffff8165c55c)
Location: include/crypto/algapi.h:152
Inline: True
Inline callers:
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
```
```
In crypto/ctr.c (ffffffff8165da5b)
Location: include/crypto/algapi.h:152
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/gcm.c (ffffffff8165e94d)
Location: include/crypto/algapi.h:152
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:gcm_enc_copy_hash
```
```
In crypto/ghash-generic.c (0)
Location: include/crypto/algapi.h:152
Inline: True
Inline callers:
  - crypto/ghash-generic.c:ghash_update
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
In crypto/seqiv.c (ffffffff8170aae2)
Location: include/crypto/algapi.h:161
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cbc.c (ffffffff817155f5)
Location: include/crypto/algapi.h:161
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt_inplace
  - crypto/cbc.c:crypto_cbc_decrypt_inplace
  - crypto/cbc.c:crypto_cbc_decrypt_inplace
  - crypto/cbc.c:crypto_cbc_decrypt_inplace
  - crypto/cbc.c:crypto_cbc_decrypt_segment
  - crypto/cbc.c:crypto_cbc_decrypt_segment
  - crypto/cbc.c:crypto_cbc_encrypt_inplace
  - crypto/cbc.c:crypto_cbc_encrypt_inplace
  - crypto/cbc.c:crypto_cbc_encrypt_segment
  - crypto/cbc.c:crypto_cbc_encrypt_segment
```
```
In crypto/cts.c (ffffffff81715f4c)
Location: include/crypto/algapi.h:161
Inline: True
Inline callers:
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
```
```
In crypto/ctr.c (ffffffff817175eb)
Location: include/crypto/algapi.h:161
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/gcm.c (ffffffff817186dd)
Location: include/crypto/algapi.h:161
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:gcm_enc_copy_hash
```
```
In crypto/ghash-generic.c (0)
Location: include/crypto/algapi.h:161
Inline: True
Inline callers:
  - crypto/ghash-generic.c:ghash_update
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
In crypto/seqiv.c (ffffffff81744332)
Location: include/crypto/utils.h:16
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cbc.c (ffffffff81750ea5)
Location: include/crypto/utils.h:16
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt_inplace
  - crypto/cbc.c:crypto_cbc_decrypt_inplace
  - crypto/cbc.c:crypto_cbc_decrypt_inplace
  - crypto/cbc.c:crypto_cbc_decrypt_inplace
  - crypto/cbc.c:crypto_cbc_decrypt_segment
  - crypto/cbc.c:crypto_cbc_decrypt_segment
  - crypto/cbc.c:crypto_cbc_encrypt_inplace
  - crypto/cbc.c:crypto_cbc_encrypt_inplace
  - crypto/cbc.c:crypto_cbc_encrypt_segment
  - crypto/cbc.c:crypto_cbc_encrypt_segment
```
```
In crypto/cts.c (ffffffff8175180c)
Location: include/crypto/utils.h:16
Inline: True
Inline callers:
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
```
```
In crypto/ctr.c (ffffffff81752f0b)
Location: include/crypto/utils.h:16
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/gcm.c (ffffffff8175404d)
Location: include/crypto/utils.h:16
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:gcm_enc_copy_hash
```
```
In crypto/ghash-generic.c (0)
Location: include/crypto/utils.h:16
Inline: True
Inline callers:
  - crypto/ghash-generic.c:ghash_update
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
In crypto/seqiv.c (ffffffff817868f2)
Location: include/crypto/utils.h:16
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cbc.c (ffffffff81792d5a)
Location: include/crypto/utils.h:16
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt_inplace
  - crypto/cbc.c:crypto_cbc_decrypt_inplace
  - crypto/cbc.c:crypto_cbc_decrypt_inplace
  - crypto/cbc.c:crypto_cbc_decrypt_inplace
  - crypto/cbc.c:crypto_cbc_decrypt_segment
  - crypto/cbc.c:crypto_cbc_decrypt_segment
  - crypto/cbc.c:crypto_cbc_encrypt_inplace
  - crypto/cbc.c:crypto_cbc_encrypt_inplace
  - crypto/cbc.c:crypto_cbc_encrypt_segment
  - crypto/cbc.c:crypto_cbc_encrypt_segment
```
```
In crypto/cts.c (ffffffff8179368c)
Location: include/crypto/utils.h:16
Inline: True
Inline callers:
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
```
```
In crypto/ctr.c (ffffffff81794eab)
Location: include/crypto/utils.h:16
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/gcm.c (ffffffff817959bd)
Location: include/crypto/utils.h:16
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:gcm_enc_copy_hash
```
```
In crypto/ghash-generic.c (0)
Location: include/crypto/utils.h:16
Inline: True
Inline callers:
  - crypto/ghash-generic.c:ghash_update
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
In crypto/seqiv.c (ffff8000105bfc7c)
Location: include/crypto/algapi.h:200
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cbc.c (ffff8000105c9290)
Location: include/crypto/algapi.h:200
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
```
```
In crypto/cts.c (ffff8000105c9cc0)
Location: include/crypto/algapi.h:200
Inline: True
Inline callers:
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
```
```
In crypto/ctr.c (ffff8000105cb1b0)
Location: include/crypto/algapi.h:200
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/gcm.c (ffff8000105cc4c0)
Location: include/crypto/algapi.h:200
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:gcm_enc_copy_hash
```
```
In crypto/ghash-generic.c (0)
Location: include/crypto/algapi.h:200
Inline: True
Inline callers:
  - crypto/ghash-generic.c:ghash_update
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
In crypto/seqiv.c (c076d8c8)
Location: include/crypto/algapi.h:200
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cbc.c (c0777000)
Location: include/crypto/algapi.h:200
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_encrypt
  - crypto/cbc.c:crypto_cbc_encrypt
```
```
In crypto/cts.c (c07777f8)
Location: include/crypto/algapi.h:200
Inline: True
Inline callers:
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
```
```
In crypto/ctr.c (c0778d04)
Location: include/crypto/algapi.h:200
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/gcm.c (c077a3c8)
Location: include/crypto/algapi.h:200
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:gcm_enc_copy_hash
```
```
In crypto/ghash-generic.c (c0781bb8)
Location: include/crypto/algapi.h:200
Inline: True
Inline callers:
  - crypto/ghash-generic.c:ghash_update
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
In crypto/seqiv.c (c000000000747ae0)
Location: include/crypto/algapi.h:200
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cbc.c (c0000000007537e4)
Location: include/crypto/algapi.h:200
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
```
```
In crypto/cts.c (c000000000754548)
Location: include/crypto/algapi.h:200
Inline: True
Inline callers:
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
```
```
In crypto/ctr.c (c000000000756150)
Location: include/crypto/algapi.h:200
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/gcm.c (c000000000757834)
Location: include/crypto/algapi.h:200
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:gcm_enc_copy_hash
```
```
In crypto/ghash-generic.c (0)
Location: include/crypto/algapi.h:200
Inline: True
Inline callers:
  - crypto/ghash-generic.c:ghash_update
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
In crypto/seqiv.c (ffffffe000404cbe)
Location: include/crypto/algapi.h:200
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cbc.c (ffffffe00040db62)
Location: include/crypto/algapi.h:200
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
```
```
In crypto/cts.c (ffffffe00040de70)
Location: include/crypto/algapi.h:200
Inline: True
Inline callers:
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
```
```
In crypto/ctr.c (ffffffe00040f366)
Location: include/crypto/algapi.h:200
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/gcm.c (ffffffe0004101da)
Location: include/crypto/algapi.h:200
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:gcm_enc_copy_hash
```
```
In crypto/ghash-generic.c (ffffffe00041860a)
Location: include/crypto/algapi.h:200
Inline: True
Inline callers:
  - crypto/ghash-generic.c:ghash_update
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
In crypto/seqiv.c (ffffffff814bd6f1)
Location: include/crypto/algapi.h:200
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cbc.c (ffffffff814c59ca)
Location: include/crypto/algapi.h:200
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
```
```
In crypto/cts.c (ffffffff814c6366)
Location: include/crypto/algapi.h:200
Inline: True
Inline callers:
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
```
```
In crypto/ctr.c (ffffffff814c77f5)
Location: include/crypto/algapi.h:200
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/gcm.c (ffffffff814c85fd)
Location: include/crypto/algapi.h:200
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:gcm_enc_copy_hash
```
```
In crypto/ghash-generic.c (0)
Location: include/crypto/algapi.h:200
Inline: True
Inline callers:
  - crypto/ghash-generic.c:ghash_update
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
In crypto/seqiv.c (ffffffff814ae111)
Location: include/crypto/algapi.h:200
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cbc.c (ffffffff814b63ea)
Location: include/crypto/algapi.h:200
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
```
```
In crypto/cts.c (ffffffff814b6d86)
Location: include/crypto/algapi.h:200
Inline: True
Inline callers:
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
```
```
In crypto/ctr.c (ffffffff814b8215)
Location: include/crypto/algapi.h:200
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/gcm.c (ffffffff814b901d)
Location: include/crypto/algapi.h:200
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:gcm_enc_copy_hash
```
```
In crypto/ghash-generic.c (0)
Location: include/crypto/algapi.h:200
Inline: True
Inline callers:
  - crypto/ghash-generic.c:ghash_update
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
In crypto/seqiv.c (ffffffff814b9781)
Location: include/crypto/algapi.h:200
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cbc.c (ffffffff814c1a5a)
Location: include/crypto/algapi.h:200
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
```
```
In crypto/cts.c (ffffffff814c23f6)
Location: include/crypto/algapi.h:200
Inline: True
Inline callers:
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
```
```
In crypto/ctr.c (ffffffff814c3885)
Location: include/crypto/algapi.h:200
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/gcm.c (ffffffff814c468d)
Location: include/crypto/algapi.h:200
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:gcm_enc_copy_hash
```
```
In crypto/ghash-generic.c (0)
Location: include/crypto/algapi.h:200
Inline: True
Inline callers:
  - crypto/ghash-generic.c:ghash_update
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
In crypto/seqiv.c (ffffffff814d2221)
Location: include/crypto/algapi.h:200
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/cbc.c (ffffffff814da52a)
Location: include/crypto/algapi.h:200
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
```
```
In crypto/cts.c (ffffffff814daec6)
Location: include/crypto/algapi.h:200
Inline: True
Inline callers:
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_decrypt
```
```
In crypto/ctr.c (ffffffff814dc355)
Location: include/crypto/algapi.h:200
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/gcm.c (ffffffff814dd15d)
Location: include/crypto/algapi.h:200
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_verify
  - crypto/gcm.c:gcm_enc_copy_hash
```
```
In crypto/ghash-generic.c (0)
Location: include/crypto/algapi.h:200
Inline: True
Inline callers:
  - crypto/ghash-generic.c:ghash_update
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
</ul>
