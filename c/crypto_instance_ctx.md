# Function: <code>crypto_instance_ctx</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff8139e6d1)
Location: include/crypto/algapi.h:224
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_alloc_instance
```
```
In crypto/aead.c (0)
Location: include/crypto/algapi.h:224
Inline: True
```
```
In crypto/blkcipher.c (0)
Location: include/crypto/algapi.h:224
Inline: True
```
```
In crypto/ahash.c (ffffffff813a308d)
Location: include/crypto/algapi.h:224
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_free_instance
```
```
In crypto/shash.c (ffffffff813a3f2d)
Location: include/crypto/algapi.h:224
Inline: True
Inline callers:
  - crypto/shash.c:shash_free_instance
```
```
In crypto/hmac.c (ffffffff813a5048)
Location: include/crypto/algapi.h:224
Inline: True
```
```
In crypto/ecb.c (ffffffff813a8e9d)
Location: include/crypto/algapi.h:224
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_free
  - crypto/ecb.c:crypto_ecb_init_tfm
```
```
In crypto/cbc.c (ffffffff813a91ed)
Location: include/crypto/algapi.h:224
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_free
  - crypto/cbc.c:crypto_cbc_init_tfm
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff813db611)
Location: include/crypto/algapi.h:300
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_alloc_instance
```
```
In crypto/aead.c (0)
Location: include/crypto/algapi.h:300
Inline: True
```
```
In crypto/seqiv.c (0)
Location: include/crypto/algapi.h:300
Inline: True
```
```
In crypto/ahash.c (ffffffff813df28d)
Location: include/crypto/algapi.h:300
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_free_instance
```
```
In crypto/shash.c (ffffffff813dfded)
Location: include/crypto/algapi.h:300
Inline: True
Inline callers:
  - crypto/shash.c:shash_free_instance
```
```
In crypto/rsa-pkcs1pad.c (0)
Location: include/crypto/algapi.h:300
Inline: True
```
```
In crypto/hmac.c (ffffffff813e2842)
Location: include/crypto/algapi.h:300
Inline: True
```
```
In crypto/ecb.c (ffffffff813e6e6d)
Location: include/crypto/algapi.h:300
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_free
  - crypto/ecb.c:crypto_ecb_init_tfm
```
```
In crypto/cbc.c (ffffffff813e71ad)
Location: include/crypto/algapi.h:300
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_free
  - crypto/cbc.c:crypto_cbc_init_tfm
```
```
In crypto/cts.c (ffffffff813e7ea5)
Location: include/crypto/algapi.h:300
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff813e858d)
Location: include/crypto/algapi.h:300
Inline: True
Inline callers:
  - crypto/xts.c:free
  - crypto/xts.c:init_tfm
```
```
In crypto/ctr.c (ffffffff813e8eaf)
Location: include/crypto/algapi.h:300
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/ctr.c:crypto_ctr_free
  - crypto/ctr.c:crypto_ctr_init_tfm
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff813f2f51)
Location: include/crypto/algapi.h:230
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_alloc_instance
```
```
In crypto/aead.c (0)
Location: include/crypto/algapi.h:230
Inline: True
```
```
In crypto/seqiv.c (0)
Location: include/crypto/algapi.h:230
Inline: True
```
```
In crypto/ahash.c (ffffffff813f781d)
Location: include/crypto/algapi.h:230
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_free_instance
```
```
In crypto/shash.c (ffffffff813f837d)
Location: include/crypto/algapi.h:230
Inline: True
Inline callers:
  - crypto/shash.c:shash_free_instance
```
```
In crypto/rsa-pkcs1pad.c (0)
Location: include/crypto/algapi.h:230
Inline: True
```
```
In crypto/hmac.c (ffffffff813fb862)
Location: include/crypto/algapi.h:230
Inline: True
```
```
In crypto/ecb.c (ffffffff813ffc1d)
Location: include/crypto/algapi.h:230
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_free
  - crypto/ecb.c:crypto_ecb_init_tfm
```
```
In crypto/cbc.c (ffffffff813fffe4)
Location: include/crypto/algapi.h:230
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_init_tfm
```
```
In crypto/cts.c (ffffffff81400cd5)
Location: include/crypto/algapi.h:230
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (0)
Location: include/crypto/algapi.h:230
Inline: True
```
```
In crypto/ctr.c (ffffffff814024c0)
Location: include/crypto/algapi.h:230
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/ctr.c:crypto_ctr_free
  - crypto/ctr.c:crypto_ctr_init_tfm
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
In crypto/algapi.c (ffffffff813ff2b5)
Location: include/crypto/algapi.h:246
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_alloc_instance
```
```
In crypto/aead.c (0)
Location: include/crypto/algapi.h:246
Inline: True
```
```
In crypto/seqiv.c (0)
Location: include/crypto/algapi.h:246
Inline: True
```
```
In crypto/ahash.c (ffffffff81403e6d)
Location: include/crypto/algapi.h:246
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_free_instance
```
```
In crypto/shash.c (ffffffff8140489d)
Location: include/crypto/algapi.h:246
Inline: True
Inline callers:
  - crypto/shash.c:shash_free_instance
```
```
In crypto/rsa-pkcs1pad.c (0)
Location: include/crypto/algapi.h:246
Inline: True
```
```
In crypto/hmac.c (ffffffff814082e9)
Location: include/crypto/algapi.h:246
Inline: True
```
```
In crypto/ecb.c (ffffffff8140cf0d)
Location: include/crypto/algapi.h:246
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_free
  - crypto/ecb.c:crypto_ecb_init_tfm
```
```
In crypto/cbc.c (ffffffff8140d2f4)
Location: include/crypto/algapi.h:246
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_init_tfm
```
```
In crypto/cts.c (ffffffff8140dc7d)
Location: include/crypto/algapi.h:246
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (0)
Location: include/crypto/algapi.h:246
Inline: True
```
```
In crypto/ctr.c (ffffffff8140f5ec)
Location: include/crypto/algapi.h:246
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/ctr.c:crypto_ctr_free
  - crypto/ctr.c:crypto_ctr_init_tfm
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
In crypto/algapi.c (ffffffff81427875)
Location: include/crypto/algapi.h:265
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_alloc_instance
```
```
In crypto/aead.c (0)
Location: include/crypto/algapi.h:265
Inline: True
```
```
In crypto/seqiv.c (0)
Location: include/crypto/algapi.h:265
Inline: True
```
```
In crypto/ahash.c (ffffffff8142c6ed)
Location: include/crypto/algapi.h:265
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_free_instance
```
```
In crypto/shash.c (ffffffff8142d19d)
Location: include/crypto/algapi.h:265
Inline: True
Inline callers:
  - crypto/shash.c:shash_free_instance
```
```
In crypto/rsa-pkcs1pad.c (0)
Location: include/crypto/algapi.h:265
Inline: True
```
```
In crypto/hmac.c (ffffffff81430d30)
Location: include/crypto/algapi.h:265
Inline: True
```
```
In crypto/ecb.c (ffffffff8143597d)
Location: include/crypto/algapi.h:265
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_free
  - crypto/ecb.c:crypto_ecb_init_tfm
```
```
In crypto/cbc.c (ffffffff81435d64)
Location: include/crypto/algapi.h:265
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_init_tfm
```
```
In crypto/cts.c (ffffffff8143671d)
Location: include/crypto/algapi.h:265
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (0)
Location: include/crypto/algapi.h:265
Inline: True
```
```
In crypto/ctr.c (ffffffff814380ec)
Location: include/crypto/algapi.h:265
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/ctr.c:crypto_ctr_free
  - crypto/ctr.c:crypto_ctr_init_tfm
```
```
In crypto/gcm.c (ffffffff81439468)
Location: include/crypto/algapi.h:265
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_create
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
In crypto/algapi.c (ffffffff8145a571)
Location: include/crypto/algapi.h:272
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_alloc_instance
```
```
In crypto/aead.c (0)
Location: include/crypto/algapi.h:272
Inline: True
```
```
In crypto/ahash.c (ffffffff8145f355)
Location: include/crypto/algapi.h:272
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_free_instance
```
```
In crypto/shash.c (ffffffff8145fdf5)
Location: include/crypto/algapi.h:272
Inline: True
Inline callers:
  - crypto/shash.c:shash_free_instance
```
```
In crypto/rsa-pkcs1pad.c (0)
Location: include/crypto/algapi.h:272
Inline: True
```
```
In crypto/hmac.c (ffffffff814638ab)
Location: include/crypto/algapi.h:272
Inline: True
```
```
In crypto/ecb.c (ffffffff81468505)
Location: include/crypto/algapi.h:272
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_free
  - crypto/ecb.c:crypto_ecb_init_tfm
```
```
In crypto/cbc.c (ffffffff814688e5)
Location: include/crypto/algapi.h:272
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_init_tfm
```
```
In crypto/cts.c (ffffffff81469298)
Location: include/crypto/algapi.h:272
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (0)
Location: include/crypto/algapi.h:272
Inline: True
```
```
In crypto/ctr.c (ffffffff8146aa80)
Location: include/crypto/algapi.h:272
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/ctr.c:crypto_ctr_free
  - crypto/ctr.c:crypto_ctr_init_tfm
```
```
In crypto/gcm.c (ffffffff8146c00f)
Location: include/crypto/algapi.h:272
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_create
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
In crypto/algapi.c (ffffffff814774f1)
Location: include/crypto/algapi.h:274
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_alloc_instance
```
```
In crypto/aead.c (0)
Location: include/crypto/algapi.h:274
Inline: True
```
```
In crypto/ahash.c (ffffffff8147cd85)
Location: include/crypto/algapi.h:274
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_free_instance
```
```
In crypto/shash.c (ffffffff8147d855)
Location: include/crypto/algapi.h:274
Inline: True
Inline callers:
  - crypto/shash.c:shash_free_instance
```
```
In crypto/rsa-pkcs1pad.c (0)
Location: include/crypto/algapi.h:274
Inline: True
```
```
In crypto/hmac.c (ffffffff8148152b)
Location: include/crypto/algapi.h:274
Inline: True
```
```
In crypto/ecb.c (ffffffff81486175)
Location: include/crypto/algapi.h:274
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_free
  - crypto/ecb.c:crypto_ecb_init_tfm
```
```
In crypto/cbc.c (ffffffff81486555)
Location: include/crypto/algapi.h:274
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_init_tfm
```
```
In crypto/cts.c (ffffffff81486c67)
Location: include/crypto/algapi.h:274
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (0)
Location: include/crypto/algapi.h:274
Inline: True
```
```
In crypto/ctr.c (ffffffff81488301)
Location: include/crypto/algapi.h:274
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/ctr.c:crypto_ctr_free
  - crypto/ctr.c:crypto_ctr_init_tfm
```
```
In crypto/gcm.c (ffffffff81489abf)
Location: include/crypto/algapi.h:274
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_create
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
In crypto/aead.c (0)
Location: include/crypto/algapi.h:268
Inline: True
```
```
In crypto/skcipher.c (ffffffff814a9304)
Location: include/crypto/algapi.h:268
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_alloc_instance_simple
  - crypto/skcipher.c:skcipher_free_instance_simple
  - crypto/skcipher.c:skcipher_init_tfm_simple
```
```
In crypto/ahash.c (ffffffff814aad25)
Location: include/crypto/algapi.h:268
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_free_instance
```
```
In crypto/shash.c (ffffffff814abb35)
Location: include/crypto/algapi.h:268
Inline: True
Inline callers:
  - crypto/shash.c:shash_free_instance
```
```
In crypto/rsa-pkcs1pad.c (0)
Location: include/crypto/algapi.h:268
Inline: True
```
```
In crypto/hmac.c (ffffffff814af70a)
Location: include/crypto/algapi.h:268
Inline: True
```
```
In crypto/cts.c (ffffffff814b4d7d)
Location: include/crypto/algapi.h:268
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (0)
Location: include/crypto/algapi.h:268
Inline: True
```
```
In crypto/ctr.c (ffffffff814b5d4a)
Location: include/crypto/algapi.h:268
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffffffff814b73a4)
Location: include/crypto/algapi.h:268
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_create
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
In crypto/aead.c (0)
Location: include/crypto/algapi.h:268
Inline: True
```
```
In crypto/skcipher.c (ffffffff814c3f74)
Location: include/crypto/algapi.h:268
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_alloc_instance_simple
  - crypto/skcipher.c:skcipher_free_instance_simple
  - crypto/skcipher.c:skcipher_init_tfm_simple
```
```
In crypto/ahash.c (ffffffff814c59e5)
Location: include/crypto/algapi.h:268
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_free_instance
```
```
In crypto/shash.c (ffffffff814c6815)
Location: include/crypto/algapi.h:268
Inline: True
Inline callers:
  - crypto/shash.c:shash_free_instance
```
```
In crypto/rsa-pkcs1pad.c (0)
Location: include/crypto/algapi.h:268
Inline: True
```
```
In crypto/hmac.c (ffffffff814ca3aa)
Location: include/crypto/algapi.h:268
Inline: True
```
```
In crypto/cts.c (ffffffff814cd84d)
Location: include/crypto/algapi.h:268
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (0)
Location: include/crypto/algapi.h:268
Inline: True
```
```
In crypto/ctr.c (ffffffff814cef4a)
Location: include/crypto/algapi.h:268
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffffffff814d05c4)
Location: include/crypto/algapi.h:268
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_create
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
In crypto/geniv.c (ffffffff8152242d)
Location: include/crypto/algapi.h:187
Inline: True
Inline callers:
  - crypto/geniv.c:aead_geniv_alloc
```
```
In crypto/skcipher.c (0)
Location: include/crypto/algapi.h:187
Inline: True
```
```
In crypto/shash.c (ffffffff815254e5)
Location: include/crypto/algapi.h:187
Inline: True
Inline callers:
  - crypto/shash.c:shash_free_singlespawn_instance
```
```
In crypto/rsa-pkcs1pad.c (0)
Location: include/crypto/algapi.h:187
Inline: True
```
```
In crypto/hmac.c (ffffffff815292f2)
Location: include/crypto/algapi.h:187
Inline: True
```
```
In crypto/cbc.c (0)
Location: include/crypto/algapi.h:187
Inline: True
```
```
In crypto/cts.c (ffffffff8152cc62)
Location: include/crypto/algapi.h:187
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (0)
Location: include/crypto/algapi.h:187
Inline: True
```
```
In crypto/ctr.c (ffffffff8152e239)
Location: include/crypto/algapi.h:187
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffffffff8152f4c2)
Location: include/crypto/algapi.h:187
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_create
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
In crypto/geniv.c (ffffffff8153f31d)
Location: include/crypto/algapi.h:187
Inline: True
Inline callers:
  - crypto/geniv.c:aead_geniv_alloc
```
```
In crypto/skcipher.c (0)
Location: include/crypto/algapi.h:187
Inline: True
```
```
In crypto/shash.c (ffffffff81542415)
Location: include/crypto/algapi.h:187
Inline: True
Inline callers:
  - crypto/shash.c:shash_free_singlespawn_instance
```
```
In crypto/rsa-pkcs1pad.c (0)
Location: include/crypto/algapi.h:187
Inline: True
```
```
In crypto/hmac.c (ffffffff81546304)
Location: include/crypto/algapi.h:187
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_create
```
```
In crypto/cbc.c (0)
Location: include/crypto/algapi.h:187
Inline: True
```
```
In crypto/cts.c (ffffffff81549ceb)
Location: include/crypto/algapi.h:187
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (0)
Location: include/crypto/algapi.h:187
Inline: True
```
```
In crypto/ctr.c (ffffffff8154b214)
Location: include/crypto/algapi.h:187
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffffffff8154c934)
Location: include/crypto/algapi.h:187
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_create
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
In crypto/geniv.c (ffffffff8154799d)
Location: include/crypto/algapi.h:187
Inline: True
Inline callers:
  - crypto/geniv.c:aead_geniv_alloc
```
```
In crypto/skcipher.c (0)
Location: include/crypto/algapi.h:187
Inline: True
```
```
In crypto/shash.c (ffffffff8154aab5)
Location: include/crypto/algapi.h:187
Inline: True
Inline callers:
  - crypto/shash.c:shash_free_singlespawn_instance
```
```
In crypto/rsa-pkcs1pad.c (0)
Location: include/crypto/algapi.h:187
Inline: True
```
```
In crypto/hmac.c (ffffffff8154e99a)
Location: include/crypto/algapi.h:187
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_create
```
```
In crypto/cbc.c (0)
Location: include/crypto/algapi.h:187
Inline: True
```
```
In crypto/cts.c (ffffffff8155232b)
Location: include/crypto/algapi.h:187
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (0)
Location: include/crypto/algapi.h:187
Inline: True
```
```
In crypto/ctr.c (ffffffff8155383a)
Location: include/crypto/algapi.h:187
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffffffff81554c0a)
Location: include/crypto/algapi.h:187
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_create
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
In crypto/geniv.c (ffffffff815a817d)
Location: include/crypto/algapi.h:195
Inline: True
Inline callers:
  - crypto/geniv.c:aead_geniv_alloc
```
```
In crypto/skcipher.c (0)
Location: include/crypto/algapi.h:195
Inline: True
```
```
In crypto/shash.c (ffffffff815ab295)
Location: include/crypto/algapi.h:195
Inline: True
Inline callers:
  - crypto/shash.c:shash_free_singlespawn_instance
```
```
In crypto/rsa-pkcs1pad.c (0)
Location: include/crypto/algapi.h:195
Inline: True
```
```
In crypto/hmac.c (ffffffff815af2ea)
Location: include/crypto/algapi.h:195
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_create
```
```
In crypto/cbc.c (0)
Location: include/crypto/algapi.h:195
Inline: True
```
```
In crypto/cts.c (ffffffff815b332b)
Location: include/crypto/algapi.h:195
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (0)
Location: include/crypto/algapi.h:195
Inline: True
```
```
In crypto/ctr.c (ffffffff815b486a)
Location: include/crypto/algapi.h:195
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffffffff815b5a6a)
Location: include/crypto/algapi.h:195
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_create
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
In crypto/geniv.c (ffffffff8164f543)
Location: include/crypto/algapi.h:204
Inline: True
Inline callers:
  - crypto/geniv.c:aead_geniv_alloc
```
```
In crypto/skcipher.c (0)
Location: include/crypto/algapi.h:204
Inline: True
```
```
In crypto/shash.c (ffffffff81652a35)
Location: include/crypto/algapi.h:204
Inline: True
Inline callers:
  - crypto/shash.c:shash_free_singlespawn_instance
```
```
In crypto/dh.c (0)
Location: include/crypto/algapi.h:204
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (0)
Location: include/crypto/algapi.h:204
Inline: True
```
```
In crypto/hmac.c (ffffffff81657a2e)
Location: include/crypto/algapi.h:204
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_create
```
```
In crypto/cbc.c (0)
Location: include/crypto/algapi.h:204
Inline: True
```
```
In crypto/cts.c (ffffffff8165c32e)
Location: include/crypto/algapi.h:204
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (0)
Location: include/crypto/algapi.h:204
Inline: True
```
```
In crypto/ctr.c (ffffffff8165d75e)
Location: include/crypto/algapi.h:204
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffffffff8165ecae)
Location: include/crypto/algapi.h:204
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_create
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
In crypto/geniv.c (ffffffff81708b53)
Location: include/crypto/algapi.h:241
Inline: True
Inline callers:
  - crypto/geniv.c:aead_geniv_alloc
```
```
In crypto/skcipher.c (0)
Location: include/crypto/algapi.h:241
Inline: True
```
```
In crypto/shash.c (ffffffff8170c235)
Location: include/crypto/algapi.h:241
Inline: True
Inline callers:
  - crypto/shash.c:shash_free_singlespawn_instance
```
```
In crypto/dh.c (0)
Location: include/crypto/algapi.h:241
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (0)
Location: include/crypto/algapi.h:241
Inline: True
```
```
In crypto/hmac.c (ffffffff81711c7e)
Location: include/crypto/algapi.h:241
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_create
```
```
In crypto/cbc.c (0)
Location: include/crypto/algapi.h:241
Inline: True
```
```
In crypto/cts.c (ffffffff81715d0e)
Location: include/crypto/algapi.h:241
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (0)
Location: include/crypto/algapi.h:241
Inline: True
```
```
In crypto/ctr.c (ffffffff817172de)
Location: include/crypto/algapi.h:241
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffffffff81718e1e)
Location: include/crypto/algapi.h:241
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_create
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
In crypto/geniv.c (ffffffff81742323)
Location: include/crypto/algapi.h:224
Inline: True
Inline callers:
  - crypto/geniv.c:aead_geniv_alloc
```
```
In crypto/skcipher.c (0)
Location: include/crypto/algapi.h:224
Inline: True
```
```
In crypto/shash.c (ffffffff81745b85)
Location: include/crypto/algapi.h:224
Inline: True
Inline callers:
  - crypto/shash.c:shash_free_singlespawn_instance
```
```
In crypto/dh.c (0)
Location: include/crypto/algapi.h:224
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (0)
Location: include/crypto/algapi.h:224
Inline: True
```
```
In crypto/hmac.c (ffffffff8174c83e)
Location: include/crypto/algapi.h:224
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_create
```
```
In crypto/cbc.c (0)
Location: include/crypto/algapi.h:224
Inline: True
```
```
In crypto/cts.c (ffffffff817515be)
Location: include/crypto/algapi.h:224
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (0)
Location: include/crypto/algapi.h:224
Inline: True
```
```
In crypto/ctr.c (ffffffff81752bee)
Location: include/crypto/algapi.h:224
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffffffff8175457e)
Location: include/crypto/algapi.h:224
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_create
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
In crypto/geniv.c (ffffffff81783232)
Location: include/crypto/algapi.h:219
Inline: True
Inline callers:
  - crypto/geniv.c:aead_geniv_alloc
```
```
In crypto/lskcipher.c (0)
Location: include/crypto/algapi.h:219
Inline: True
```
```
In crypto/skcipher.c (0)
Location: include/crypto/algapi.h:219
Inline: True
```
```
In crypto/shash.c (ffffffff817884f5)
Location: include/crypto/algapi.h:219
Inline: True
Inline callers:
  - crypto/shash.c:shash_free_singlespawn_instance
```
```
In crypto/dh.c (0)
Location: include/crypto/algapi.h:219
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (0)
Location: include/crypto/algapi.h:219
Inline: True
```
```
In crypto/hmac.c (ffffffff8178e90d)
Location: include/crypto/algapi.h:219
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_create
```
```
In crypto/ecb.c (0)
Location: include/crypto/algapi.h:219
Inline: True
```
```
In crypto/cts.c (ffffffff8179343d)
Location: include/crypto/algapi.h:219
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (0)
Location: include/crypto/algapi.h:219
Inline: True
```
```
In crypto/ctr.c (ffffffff81794b8d)
Location: include/crypto/algapi.h:219
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffffffff8179615d)
Location: include/crypto/algapi.h:219
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_create
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
In crypto/aead.c (0)
Location: include/crypto/algapi.h:268
Inline: True
```
```
In crypto/skcipher.c (ffff8000105bea84)
Location: include/crypto/algapi.h:268
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_alloc_instance_simple
  - crypto/skcipher.c:skcipher_free_instance_simple
  - crypto/skcipher.c:skcipher_init_tfm_simple
```
```
In crypto/ahash.c (ffff8000105c0808)
Location: include/crypto/algapi.h:268
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_free_instance
```
```
In crypto/shash.c (ffff8000105c1bd8)
Location: include/crypto/algapi.h:268
Inline: True
Inline callers:
  - crypto/shash.c:shash_free_instance
```
```
In crypto/rsa-pkcs1pad.c (0)
Location: include/crypto/algapi.h:268
Inline: True
```
```
In crypto/hmac.c (ffff8000105c60c8)
Location: include/crypto/algapi.h:268
Inline: True
```
```
In crypto/cts.c (ffff8000105c9720)
Location: include/crypto/algapi.h:268
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (0)
Location: include/crypto/algapi.h:268
Inline: True
```
```
In crypto/ctr.c (ffff8000105cadc0)
Location: include/crypto/algapi.h:268
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffff8000105cbd54)
Location: include/crypto/algapi.h:268
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_create
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
In crypto/aead.c (0)
Location: include/crypto/algapi.h:268
Inline: True
```
```
In crypto/skcipher.c (c076c6c8)
Location: include/crypto/algapi.h:268
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_alloc_instance_simple
  - crypto/skcipher.c:skcipher_free_instance_simple
  - crypto/skcipher.c:skcipher_init_tfm_simple
```
```
In crypto/ahash.c (c076e288)
Location: include/crypto/algapi.h:268
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_free_instance
```
```
In crypto/shash.c (c076f204)
Location: include/crypto/algapi.h:268
Inline: True
Inline callers:
  - crypto/shash.c:shash_free_instance
```
```
In crypto/rsa-pkcs1pad.c (0)
Location: include/crypto/algapi.h:268
Inline: True
```
```
In crypto/hmac.c (c0772db4)
Location: include/crypto/algapi.h:268
Inline: True
```
```
In crypto/cts.c (c07772b4)
Location: include/crypto/algapi.h:268
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (0)
Location: include/crypto/algapi.h:268
Inline: True
```
```
In crypto/ctr.c (c0778980)
Location: include/crypto/algapi.h:268
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (c0779708)
Location: include/crypto/algapi.h:268
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_create
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
In crypto/aead.c (0)
Location: include/crypto/algapi.h:268
Inline: True
```
```
In crypto/skcipher.c (c000000000746dd8)
Location: include/crypto/algapi.h:268
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_alloc_instance_simple
  - crypto/skcipher.c:skcipher_free_instance_simple
  - crypto/skcipher.c:skcipher_init_tfm_simple
```
```
In crypto/ahash.c (c0000000007489e0)
Location: include/crypto/algapi.h:268
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_free_instance
```
```
In crypto/shash.c (c00000000074a1a0)
Location: include/crypto/algapi.h:268
Inline: True
Inline callers:
  - crypto/shash.c:shash_free_instance
```
```
In crypto/rsa-pkcs1pad.c (0)
Location: include/crypto/algapi.h:268
Inline: True
```
```
In crypto/hmac.c (c00000000074fbac)
Location: include/crypto/algapi.h:268
Inline: True
```
```
In crypto/cts.c (c000000000753e24)
Location: include/crypto/algapi.h:268
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (0)
Location: include/crypto/algapi.h:268
Inline: True
```
```
In crypto/ctr.c (c000000000755dc8)
Location: include/crypto/algapi.h:268
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (c0000000007584d8)
Location: include/crypto/algapi.h:268
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_create
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
In crypto/aead.c (0)
Location: include/crypto/algapi.h:268
Inline: True
```
```
In crypto/skcipher.c (ffffffe000403f00)
Location: include/crypto/algapi.h:268
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_alloc_instance_simple
  - crypto/skcipher.c:skcipher_free_instance_simple
  - crypto/skcipher.c:skcipher_init_tfm_simple
```
```
In crypto/ahash.c (ffffffe0004056c2)
Location: include/crypto/algapi.h:268
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_free_instance
```
```
In crypto/shash.c (ffffffe00040679c)
Location: include/crypto/algapi.h:268
Inline: True
Inline callers:
  - crypto/shash.c:shash_free_instance
```
```
In crypto/rsa-pkcs1pad.c (0)
Location: include/crypto/algapi.h:268
Inline: True
```
```
In crypto/hmac.c (ffffffe00040a132)
Location: include/crypto/algapi.h:268
Inline: True
```
```
In crypto/cts.c (ffffffe00040e410)
Location: include/crypto/algapi.h:268
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (0)
Location: include/crypto/algapi.h:268
Inline: True
```
```
In crypto/ctr.c (ffffffe00040f4f4)
Location: include/crypto/algapi.h:268
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffffffe000410f0c)
Location: include/crypto/algapi.h:268
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_create
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
In crypto/aead.c (0)
Location: include/crypto/algapi.h:268
Inline: True
```
```
In crypto/skcipher.c (ffffffff814bc554)
Location: include/crypto/algapi.h:268
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_alloc_instance_simple
  - crypto/skcipher.c:skcipher_free_instance_simple
  - crypto/skcipher.c:skcipher_init_tfm_simple
```
```
In crypto/ahash.c (ffffffff814bdfc5)
Location: include/crypto/algapi.h:268
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_free_instance
```
```
In crypto/shash.c (ffffffff814bedf5)
Location: include/crypto/algapi.h:268
Inline: True
Inline callers:
  - crypto/shash.c:shash_free_instance
```
```
In crypto/rsa-pkcs1pad.c (0)
Location: include/crypto/algapi.h:268
Inline: True
```
```
In crypto/hmac.c (ffffffff814c298a)
Location: include/crypto/algapi.h:268
Inline: True
```
```
In crypto/cts.c (ffffffff814c5e2d)
Location: include/crypto/algapi.h:268
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (0)
Location: include/crypto/algapi.h:268
Inline: True
```
```
In crypto/ctr.c (ffffffff814c752a)
Location: include/crypto/algapi.h:268
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffffffff814c8ba4)
Location: include/crypto/algapi.h:268
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_create
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
In crypto/aead.c (0)
Location: include/crypto/algapi.h:268
Inline: True
```
```
In crypto/skcipher.c (ffffffff814acf74)
Location: include/crypto/algapi.h:268
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_alloc_instance_simple
  - crypto/skcipher.c:skcipher_free_instance_simple
  - crypto/skcipher.c:skcipher_init_tfm_simple
```
```
In crypto/ahash.c (ffffffff814ae9e5)
Location: include/crypto/algapi.h:268
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_free_instance
```
```
In crypto/shash.c (ffffffff814af815)
Location: include/crypto/algapi.h:268
Inline: True
Inline callers:
  - crypto/shash.c:shash_free_instance
```
```
In crypto/rsa-pkcs1pad.c (0)
Location: include/crypto/algapi.h:268
Inline: True
```
```
In crypto/hmac.c (ffffffff814b33aa)
Location: include/crypto/algapi.h:268
Inline: True
```
```
In crypto/cts.c (ffffffff814b684d)
Location: include/crypto/algapi.h:268
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (0)
Location: include/crypto/algapi.h:268
Inline: True
```
```
In crypto/ctr.c (ffffffff814b7f4a)
Location: include/crypto/algapi.h:268
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffffffff814b95c4)
Location: include/crypto/algapi.h:268
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_create
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
In crypto/aead.c (0)
Location: include/crypto/algapi.h:268
Inline: True
```
```
In crypto/skcipher.c (ffffffff814b85e4)
Location: include/crypto/algapi.h:268
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_alloc_instance_simple
  - crypto/skcipher.c:skcipher_free_instance_simple
  - crypto/skcipher.c:skcipher_init_tfm_simple
```
```
In crypto/ahash.c (ffffffff814ba055)
Location: include/crypto/algapi.h:268
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_free_instance
```
```
In crypto/shash.c (ffffffff814bae85)
Location: include/crypto/algapi.h:268
Inline: True
Inline callers:
  - crypto/shash.c:shash_free_instance
```
```
In crypto/rsa-pkcs1pad.c (0)
Location: include/crypto/algapi.h:268
Inline: True
```
```
In crypto/hmac.c (ffffffff814bea1a)
Location: include/crypto/algapi.h:268
Inline: True
```
```
In crypto/cts.c (ffffffff814c1ebd)
Location: include/crypto/algapi.h:268
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (0)
Location: include/crypto/algapi.h:268
Inline: True
```
```
In crypto/ctr.c (ffffffff814c35ba)
Location: include/crypto/algapi.h:268
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffffffff814c4c34)
Location: include/crypto/algapi.h:268
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_create
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
In crypto/aead.c (0)
Location: include/crypto/algapi.h:268
Inline: True
```
```
In crypto/skcipher.c (ffffffff814d10c4)
Location: include/crypto/algapi.h:268
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_alloc_instance_simple
  - crypto/skcipher.c:skcipher_free_instance_simple
  - crypto/skcipher.c:skcipher_init_tfm_simple
```
```
In crypto/ahash.c (ffffffff814d2b05)
Location: include/crypto/algapi.h:268
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_free_instance
```
```
In crypto/shash.c (ffffffff814d3935)
Location: include/crypto/algapi.h:268
Inline: True
Inline callers:
  - crypto/shash.c:shash_free_instance
```
```
In crypto/rsa-pkcs1pad.c (0)
Location: include/crypto/algapi.h:268
Inline: True
```
```
In crypto/hmac.c (ffffffff814d74ea)
Location: include/crypto/algapi.h:268
Inline: True
```
```
In crypto/cts.c (ffffffff814da98d)
Location: include/crypto/algapi.h:268
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (0)
Location: include/crypto/algapi.h:268
Inline: True
```
```
In crypto/ctr.c (ffffffff814dc08a)
Location: include/crypto/algapi.h:268
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffffffff814dd704)
Location: include/crypto/algapi.h:268
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4106_create
```
</details>
</li>
</ul>

## Differences
