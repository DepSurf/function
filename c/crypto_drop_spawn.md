# Function: <code>crypto_drop_spawn</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void crypto_drop_spawn(struct crypto_spawn *spawn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff8139d480)
Location: crypto/algapi.c:641
Inline: False
Direct callers:
  - crypto/aead.c:aead_geniv_free
  - crypto/aead.c:aead_geniv_alloc
  - crypto/blkcipher.c:skcipher_geniv_free
  - crypto/blkcipher.c:skcipher_geniv_alloc
  - crypto/ahash.c:ahash_free_instance
  - crypto/shash.c:shash_free_instance
  - crypto/ecb.c:crypto_ecb_free
  - crypto/cbc.c:crypto_cbc_free
```
**Symbols:**

```
ffffffff8139d480-ffffffff8139d4d9: crypto_drop_spawn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void crypto_drop_spawn(struct crypto_spawn *spawn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff813da340)
Location: crypto/algapi.c:640
Inline: False
Direct callers:
  - crypto/aead.c:aead_geniv_free
  - crypto/aead.c:aead_geniv_alloc
  - crypto/ahash.c:ahash_free_instance
  - crypto/shash.c:shash_free_instance
  - crypto/rsa-pkcs1pad.c:pkcs1pad_create
  - crypto/rsa-pkcs1pad.c:pkcs1pad_free
  - crypto/ecb.c:crypto_ecb_free
  - crypto/cbc.c:crypto_cbc_free
  - crypto/cts.c:crypto_cts_create
  - crypto/cts.c:crypto_cts_free
  - crypto/xts.c:free
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/ctr.c:crypto_rfc3686_free
  - crypto/ctr.c:crypto_ctr_free
```
**Symbols:**

```
ffffffff813da340-ffffffff813da399: crypto_drop_spawn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void crypto_drop_spawn(struct crypto_spawn *spawn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff813f1c80)
Location: crypto/algapi.c:641
Inline: False
Direct callers:
  - crypto/aead.c:aead_geniv_free
  - crypto/aead.c:aead_geniv_alloc
  - crypto/ahash.c:ahash_free_instance
  - crypto/shash.c:shash_free_instance
  - crypto/rsa-pkcs1pad.c:pkcs1pad_create
  - crypto/rsa-pkcs1pad.c:pkcs1pad_free
  - crypto/ecb.c:crypto_ecb_free
  - crypto/cbc.c:crypto_cbc_free
  - crypto/cts.c:crypto_cts_create
  - crypto/cts.c:crypto_cts_free
  - crypto/xts.c:create
  - crypto/xts.c:free
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/ctr.c:crypto_rfc3686_free
  - crypto/ctr.c:crypto_ctr_free
```
**Symbols:**

```
ffffffff813f1c80-ffffffff813f1cd9: crypto_drop_spawn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void crypto_drop_spawn(struct crypto_spawn *spawn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff813fedd0)
Location: crypto/algapi.c:641
Inline: True
Direct callers:
  - crypto/aead.c:aead_geniv_free
  - crypto/aead.c:aead_geniv_alloc
  - crypto/ahash.c:ahash_free_instance
  - crypto/shash.c:shash_free_instance
  - crypto/rsa-pkcs1pad.c:pkcs1pad_create
  - crypto/rsa-pkcs1pad.c:pkcs1pad_free
  - crypto/ecb.c:crypto_ecb_free
  - crypto/cbc.c:crypto_cbc_free
  - crypto/cts.c:crypto_cts_create
  - crypto/cts.c:crypto_cts_create
  - crypto/cts.c:crypto_cts_free
  - crypto/xts.c:create
  - crypto/xts.c:free
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/ctr.c:crypto_rfc3686_free
  - crypto/ctr.c:crypto_ctr_free
```
**Symbols:**

```
ffffffff813fedd0-ffffffff813fee26: crypto_drop_spawn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void crypto_drop_spawn(struct crypto_spawn *spawn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff81427390)
Location: crypto/algapi.c:653
Inline: True
Direct callers:
  - crypto/aead.c:aead_geniv_free
  - crypto/aead.c:aead_geniv_alloc
  - crypto/ahash.c:ahash_free_instance
  - crypto/shash.c:shash_free_instance
  - crypto/rsa-pkcs1pad.c:pkcs1pad_create
  - crypto/rsa-pkcs1pad.c:pkcs1pad_free
  - crypto/ecb.c:crypto_ecb_free
  - crypto/cbc.c:crypto_cbc_free
  - crypto/cts.c:crypto_cts_create
  - crypto/cts.c:crypto_cts_create
  - crypto/cts.c:crypto_cts_free
  - crypto/xts.c:create
  - crypto/xts.c:free
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/ctr.c:crypto_rfc3686_free
  - crypto/ctr.c:crypto_ctr_free
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_rfc4106_free
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_free
  - crypto/gcm.c:crypto_gcm_free
```
**Symbols:**

```
ffffffff81427390-ffffffff814273e6: crypto_drop_spawn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void crypto_drop_spawn(struct crypto_spawn *spawn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff8145a080)
Location: crypto/algapi.c:650
Inline: True
Direct callers:
  - crypto/aead.c:aead_geniv_free
  - crypto/aead.c:aead_geniv_alloc
  - crypto/ahash.c:ahash_free_instance
  - crypto/shash.c:shash_free_instance
  - crypto/rsa-pkcs1pad.c:pkcs1pad_create
  - crypto/rsa-pkcs1pad.c:pkcs1pad_free
  - crypto/ecb.c:crypto_ecb_free
  - crypto/cbc.c:crypto_cbc_free
  - crypto/cts.c:crypto_cts_create
  - crypto/cts.c:crypto_cts_create
  - crypto/cts.c:crypto_cts_free
  - crypto/xts.c:create
  - crypto/xts.c:free
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/ctr.c:crypto_rfc3686_free
  - crypto/ctr.c:crypto_ctr_free
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_rfc4106_free
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_free
  - crypto/gcm.c:crypto_gcm_free
```
**Symbols:**

```
ffffffff8145a080-ffffffff8145a0d5: crypto_drop_spawn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void crypto_drop_spawn(struct crypto_spawn *spawn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff81477240)
Location: crypto/algapi.c:659
Inline: True
Direct callers:
  - crypto/aead.c:aead_geniv_free
  - crypto/aead.c:aead_geniv_alloc
  - crypto/ahash.c:ahash_free_instance
  - crypto/shash.c:shash_free_instance
  - crypto/rsa-pkcs1pad.c:pkcs1pad_create
  - crypto/rsa-pkcs1pad.c:pkcs1pad_free
  - crypto/ecb.c:crypto_ecb_free
  - crypto/cbc.c:crypto_cbc_free
  - crypto/cts.c:crypto_cts_create
  - crypto/cts.c:crypto_cts_free
  - crypto/xts.c:create
  - crypto/xts.c:free
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/ctr.c:crypto_rfc3686_free
  - crypto/ctr.c:crypto_ctr_free
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_rfc4106_free
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_free
  - crypto/gcm.c:crypto_gcm_free
```
**Symbols:**

```
ffffffff81477240-ffffffff81477295: crypto_drop_spawn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void crypto_drop_spawn(struct crypto_spawn *spawn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff814a4f50)
Location: crypto/algapi.c:670
Inline: True
Direct callers:
  - crypto/aead.c:aead_geniv_free
  - crypto/aead.c:aead_geniv_alloc
  - crypto/skcipher.c:skcipher_free_instance_simple
  - crypto/ahash.c:ahash_free_instance
  - crypto/shash.c:shash_free_instance
  - crypto/rsa-pkcs1pad.c:pkcs1pad_create
  - crypto/rsa-pkcs1pad.c:pkcs1pad_free
  - crypto/cts.c:crypto_cts_create
  - crypto/cts.c:crypto_cts_free
  - crypto/xts.c:create
  - crypto/xts.c:free
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/ctr.c:crypto_rfc3686_free
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4543_free
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_rfc4106_free
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_free
  - crypto/gcm.c:crypto_gcm_free
```
**Symbols:**

```
ffffffff814a4f50-ffffffff814a4fa3: crypto_drop_spawn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void crypto_drop_spawn(struct crypto_spawn *spawn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff814bf280)
Location: crypto/algapi.c:688
Inline: False
Direct callers:
  - crypto/aead.c:aead_geniv_free
  - crypto/aead.c:aead_geniv_alloc
  - crypto/skcipher.c:skcipher_free_instance_simple
  - crypto/ahash.c:ahash_free_instance
  - crypto/shash.c:shash_free_instance
  - crypto/rsa-pkcs1pad.c:pkcs1pad_create
  - crypto/rsa-pkcs1pad.c:pkcs1pad_free
  - crypto/cts.c:crypto_cts_create
  - crypto/cts.c:crypto_cts_free
  - crypto/xts.c:create
  - crypto/xts.c:free
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/ctr.c:crypto_rfc3686_free
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4543_free
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_rfc4106_free
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_free
  - crypto/gcm.c:crypto_gcm_free
```
**Symbols:**

```
ffffffff814bf280-ffffffff814bf2d2: crypto_drop_spawn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void crypto_drop_spawn(struct crypto_spawn *spawn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff8151fd40)
Location: crypto/algapi.c:702
Inline: True
Direct callers:
  - crypto/geniv.c:aead_geniv_alloc
  - crypto/skcipher.c:skcipher_alloc_instance_simple
  - crypto/shash.c:shash_free_singlespawn_instance
  - crypto/rsa-pkcs1pad.c:pkcs1pad_create
  - crypto/cts.c:crypto_cts_create
  - crypto/xts.c:create
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_create_common
```
**Symbols:**

```
ffffffff8151fd40-ffffffff8151fdb1: crypto_drop_spawn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void crypto_drop_spawn(struct crypto_spawn *spawn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff8153cbb0)
Location: crypto/algapi.c:704
Inline: True
Direct callers:
  - crypto/geniv.c:aead_geniv_alloc
  - crypto/geniv.c:aead_geniv_alloc
  - crypto/skcipher.c:skcipher_alloc_instance_simple
  - crypto/shash.c:shash_free_singlespawn_instance
  - crypto/rsa-pkcs1pad.c:pkcs1pad_create
  - crypto/cts.c:crypto_cts_create
  - crypto/cts.c:crypto_cts_create
  - crypto/xts.c:xts_create
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_create_common
```
**Symbols:**

```
ffffffff8153cbb0-ffffffff8153cc21: crypto_drop_spawn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void crypto_drop_spawn(struct crypto_spawn *spawn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff81545290)
Location: crypto/algapi.c:704
Inline: True
Direct callers:
  - crypto/geniv.c:aead_geniv_alloc
  - crypto/geniv.c:aead_geniv_alloc
  - crypto/skcipher.c:skcipher_alloc_instance_simple
  - crypto/shash.c:shash_free_singlespawn_instance
  - crypto/rsa-pkcs1pad.c:pkcs1pad_create
  - crypto/rsa-pkcs1pad.c:pkcs1pad_create
  - crypto/cts.c:crypto_cts_create
  - crypto/cts.c:crypto_cts_create
  - crypto/xts.c:xts_create
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_create_common
```
**Symbols:**

```
ffffffff81545290-ffffffff81545301: crypto_drop_spawn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void crypto_drop_spawn(struct crypto_spawn *spawn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/algapi.c (ffffffff815a5a0a)
Location: crypto/algapi.c:704
Inline: True
Direct callers:
  - crypto/geniv.c:aead_geniv_alloc
  - crypto/geniv.c:aead_geniv_alloc
  - crypto/skcipher.c:skcipher_alloc_instance_simple
  - crypto/shash.c:shash_free_singlespawn_instance
  - crypto/rsa-pkcs1pad.c:pkcs1pad_create
  - crypto/rsa-pkcs1pad.c:pkcs1pad_create
  - crypto/cts.c:crypto_cts_create
  - crypto/cts.c:crypto_cts_create
  - crypto/xts.c:xts_create
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_create_common
```
**Symbols:**

```
ffffffff81cd75ff-ffffffff81cd7629: crypto_drop_spawn.cold (STB_LOCAL)
ffffffff815a59f0-ffffffff815a5a85: crypto_drop_spawn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void crypto_drop_spawn(struct crypto_spawn *spawn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/algapi.c (ffffffff8164cd3a)
Location: crypto/algapi.c:728
Inline: True
Direct callers:
  - crypto/geniv.c:aead_geniv_alloc
  - crypto/geniv.c:aead_geniv_alloc
  - crypto/geniv.c:aead_geniv_alloc
  - crypto/skcipher.c:skcipher_alloc_instance_simple
  - crypto/shash.c:shash_free_singlespawn_instance
  - crypto/dh.c:__dh_safe_prime_create
  - crypto/dh.c:__dh_safe_prime_create
  - crypto/rsa-pkcs1pad.c:pkcs1pad_create
  - crypto/cts.c:crypto_cts_create
  - crypto/cts.c:crypto_cts_create
  - crypto/xts.c:xts_create
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_create_common
```
**Symbols:**

```
ffffffff81e8a908-ffffffff81e8a932: crypto_drop_spawn.cold (STB_LOCAL)
ffffffff8164cd20-ffffffff8164cdd9: crypto_drop_spawn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void crypto_drop_spawn(struct crypto_spawn *spawn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/algapi.c (ffffffff81705aaa)
Location: crypto/algapi.c:747
Inline: True
Direct callers:
  - crypto/geniv.c:aead_geniv_alloc
  - crypto/geniv.c:aead_geniv_alloc
  - crypto/geniv.c:aead_geniv_alloc
  - crypto/skcipher.c:skcipher_alloc_instance_simple
  - crypto/shash.c:shash_free_singlespawn_instance
  - crypto/dh.c:__dh_safe_prime_create
  - crypto/dh.c:__dh_safe_prime_create
  - crypto/rsa-pkcs1pad.c:pkcs1pad_create
  - crypto/cts.c:crypto_cts_create
  - crypto/cts.c:crypto_cts_create
  - crypto/xts.c:xts_create
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_create_common
```
**Symbols:**

```
ffffffff820756de-ffffffff82075708: crypto_drop_spawn.cold (STB_LOCAL)
ffffffff81705a90-ffffffff81705b49: crypto_drop_spawn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void crypto_drop_spawn(struct crypto_spawn *spawn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/algapi.c (ffffffff8173fd3a)
Location: crypto/algapi.c:759
Inline: True
Direct callers:
  - crypto/geniv.c:aead_geniv_alloc
  - crypto/geniv.c:aead_geniv_alloc
  - crypto/geniv.c:aead_geniv_alloc
  - crypto/skcipher.c:skcipher_alloc_instance_simple
  - crypto/shash.c:shash_free_singlespawn_instance
  - crypto/dh.c:__dh_safe_prime_create
  - crypto/dh.c:__dh_safe_prime_create
  - crypto/rsa-pkcs1pad.c:pkcs1pad_create
  - crypto/cts.c:crypto_cts_create
  - crypto/cts.c:crypto_cts_create
  - crypto/xts.c:xts_create
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_create_common
```
**Symbols:**

```
ffffffff820f523f-ffffffff820f5269: crypto_drop_spawn.cold (STB_LOCAL)
ffffffff8173fd20-ffffffff8173fdd9: crypto_drop_spawn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void crypto_drop_spawn(struct crypto_spawn *spawn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/algapi.c (ffffffff81780bba)
Location: crypto/algapi.c:760
Inline: True
Direct callers:
  - crypto/geniv.c:aead_geniv_alloc
  - crypto/geniv.c:aead_geniv_alloc
  - crypto/geniv.c:aead_geniv_alloc
  - crypto/lskcipher.c:lskcipher_alloc_instance_simple
  - crypto/skcipher.c:skcipher_alloc_instance_simple
  - crypto/shash.c:shash_free_singlespawn_instance
  - crypto/dh.c:__dh_safe_prime_create
  - crypto/dh.c:__dh_safe_prime_create
  - crypto/rsa-pkcs1pad.c:pkcs1pad_create
  - crypto/ecb.c:lskcipher_alloc_instance_simple2
  - crypto/cts.c:crypto_cts_create
  - crypto/cts.c:crypto_cts_create
  - crypto/xts.c:xts_create
  - crypto/xts.c:xts_create
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_create_common
```
**Symbols:**

```
ffffffff821d2413-ffffffff821d243d: crypto_drop_spawn.cold (STB_LOCAL)
ffffffff81780ba0-ffffffff81780c59: crypto_drop_spawn (STB_GLOBAL)
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
void crypto_drop_spawn(struct crypto_spawn *spawn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffff8000105b86a0)
Location: crypto/algapi.c:688
Inline: False
Direct callers:
  - crypto/aead.c:aead_geniv_free
  - crypto/aead.c:aead_geniv_alloc
  - crypto/skcipher.c:skcipher_free_instance_simple
  - crypto/ahash.c:ahash_free_instance
  - crypto/shash.c:shash_free_instance
  - crypto/rsa-pkcs1pad.c:pkcs1pad_create
  - crypto/rsa-pkcs1pad.c:pkcs1pad_free
  - crypto/cts.c:crypto_cts_create
  - crypto/cts.c:crypto_cts_create
  - crypto/cts.c:crypto_cts_free
  - crypto/xts.c:create
  - crypto/xts.c:free
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/ctr.c:crypto_rfc3686_free
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_rfc4106_free
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_free
  - crypto/gcm.c:crypto_gcm_free
```
**Symbols:**

```
ffff8000105b86a0-ffff8000105b8704: crypto_drop_spawn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void crypto_drop_spawn(struct crypto_spawn *spawn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (c0767128)
Location: crypto/algapi.c:688
Inline: False
Direct callers:
  - crypto/aead.c:aead_geniv_free
  - crypto/aead.c:aead_geniv_alloc
  - crypto/skcipher.c:skcipher_free_instance_simple
  - crypto/ahash.c:ahash_free_instance
  - crypto/shash.c:shash_free_instance
  - crypto/rsa-pkcs1pad.c:pkcs1pad_create
  - crypto/rsa-pkcs1pad.c:pkcs1pad_free
  - crypto/cts.c:crypto_cts_create
  - crypto/cts.c:crypto_cts_free
  - crypto/xts.c:create
  - crypto/xts.c:free
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/ctr.c:crypto_rfc3686_free
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_rfc4106_free
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_free
  - crypto/gcm.c:crypto_gcm_free
```
**Symbols:**

```
c0767128-c0767184: crypto_drop_spawn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void crypto_drop_spawn(struct crypto_spawn *spawn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (c00000000073d4f0)
Location: crypto/algapi.c:688
Inline: False
Direct callers:
  - crypto/aead.c:aead_geniv_free
  - crypto/aead.c:aead_geniv_alloc
  - crypto/skcipher.c:skcipher_free_instance_simple
  - crypto/ahash.c:ahash_free_instance
  - crypto/shash.c:shash_free_instance
  - crypto/rsa-pkcs1pad.c:pkcs1pad_create
  - crypto/rsa-pkcs1pad.c:pkcs1pad_free
  - crypto/cts.c:crypto_cts_create
  - crypto/cts.c:crypto_cts_create
  - crypto/cts.c:crypto_cts_free
  - crypto/xts.c:create
  - crypto/xts.c:free
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/ctr.c:crypto_rfc3686_free
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4543_free
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_rfc4106_free
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_free
  - crypto/gcm.c:crypto_gcm_free
```
**Symbols:**

```
c00000000073d4f0-c00000000073d59c: crypto_drop_spawn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void crypto_drop_spawn(struct crypto_spawn *spawn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffe0003feddc)
Location: crypto/algapi.c:688
Inline: False
Direct callers:
  - crypto/aead.c:aead_geniv_free
  - crypto/aead.c:aead_geniv_alloc
  - crypto/skcipher.c:skcipher_free_instance_simple
  - crypto/ahash.c:ahash_free_instance
  - crypto/shash.c:shash_free_instance
  - crypto/rsa-pkcs1pad.c:pkcs1pad_create
  - crypto/rsa-pkcs1pad.c:pkcs1pad_free
  - crypto/cts.c:crypto_cts_create
  - crypto/cts.c:crypto_cts_free
  - crypto/xts.c:create
  - crypto/xts.c:free
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/ctr.c:crypto_rfc3686_free
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_rfc4106_free
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_free
  - crypto/gcm.c:crypto_gcm_free
```
**Symbols:**

```
ffffffe0003feddc-ffffffe0003fee34: crypto_drop_spawn (STB_GLOBAL)
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
void crypto_drop_spawn(struct crypto_spawn *spawn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff814b7860)
Location: crypto/algapi.c:688
Inline: False
Direct callers:
  - crypto/aead.c:aead_geniv_free
  - crypto/aead.c:aead_geniv_alloc
  - crypto/skcipher.c:skcipher_free_instance_simple
  - crypto/ahash.c:ahash_free_instance
  - crypto/shash.c:shash_free_instance
  - crypto/rsa-pkcs1pad.c:pkcs1pad_create
  - crypto/rsa-pkcs1pad.c:pkcs1pad_free
  - crypto/cts.c:crypto_cts_create
  - crypto/cts.c:crypto_cts_free
  - crypto/xts.c:create
  - crypto/xts.c:free
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/ctr.c:crypto_rfc3686_free
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4543_free
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_rfc4106_free
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_free
  - crypto/gcm.c:crypto_gcm_free
```
**Symbols:**

```
ffffffff814b7860-ffffffff814b78b2: crypto_drop_spawn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void crypto_drop_spawn(struct crypto_spawn *spawn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff814a8280)
Location: crypto/algapi.c:688
Inline: False
Direct callers:
  - crypto/aead.c:aead_geniv_free
  - crypto/aead.c:aead_geniv_alloc
  - crypto/skcipher.c:skcipher_free_instance_simple
  - crypto/ahash.c:ahash_free_instance
  - crypto/shash.c:shash_free_instance
  - crypto/rsa-pkcs1pad.c:pkcs1pad_create
  - crypto/rsa-pkcs1pad.c:pkcs1pad_free
  - crypto/cts.c:crypto_cts_create
  - crypto/cts.c:crypto_cts_free
  - crypto/xts.c:create
  - crypto/xts.c:free
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/ctr.c:crypto_rfc3686_free
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4543_free
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_rfc4106_free
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_free
  - crypto/gcm.c:crypto_gcm_free
```
**Symbols:**

```
ffffffff814a8280-ffffffff814a82d2: crypto_drop_spawn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void crypto_drop_spawn(struct crypto_spawn *spawn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff814b38f0)
Location: crypto/algapi.c:688
Inline: False
Direct callers:
  - crypto/aead.c:aead_geniv_free
  - crypto/aead.c:aead_geniv_alloc
  - crypto/skcipher.c:skcipher_free_instance_simple
  - crypto/ahash.c:ahash_free_instance
  - crypto/shash.c:shash_free_instance
  - crypto/rsa-pkcs1pad.c:pkcs1pad_create
  - crypto/rsa-pkcs1pad.c:pkcs1pad_free
  - crypto/cts.c:crypto_cts_create
  - crypto/cts.c:crypto_cts_free
  - crypto/xts.c:create
  - crypto/xts.c:free
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/ctr.c:crypto_rfc3686_free
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4543_free
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_rfc4106_free
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_free
  - crypto/gcm.c:crypto_gcm_free
```
**Symbols:**

```
ffffffff814b38f0-ffffffff814b3942: crypto_drop_spawn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void crypto_drop_spawn(struct crypto_spawn *spawn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff814cc370)
Location: crypto/algapi.c:688
Inline: False
Direct callers:
  - crypto/aead.c:aead_geniv_free
  - crypto/aead.c:aead_geniv_alloc
  - crypto/skcipher.c:skcipher_free_instance_simple
  - crypto/ahash.c:ahash_free_instance
  - crypto/shash.c:shash_free_instance
  - crypto/rsa-pkcs1pad.c:pkcs1pad_create
  - crypto/rsa-pkcs1pad.c:pkcs1pad_free
  - crypto/cts.c:crypto_cts_create
  - crypto/cts.c:crypto_cts_free
  - crypto/xts.c:create
  - crypto/xts.c:free
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/ctr.c:crypto_rfc3686_free
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4543_free
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_rfc4106_free
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_free
  - crypto/gcm.c:crypto_gcm_free
```
**Symbols:**

```
ffffffff814cc370-ffffffff814cc3c2: crypto_drop_spawn (STB_GLOBAL)
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
