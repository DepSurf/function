# Function: <code>crypto_alg_put</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void crypto_alg_put(struct crypto_alg *alg);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff8139c385)
Location: crypto/internal.h:113
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_larval_kill
  - crypto/api.c:crypto_destroy_tfm
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:__crypto_alg_lookup
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_has_alg
  - crypto/api.c:crypto_alloc_base
```
```
In crypto/algapi.c (ffffffff8139d0a4)
Location: crypto/internal.h:113
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_remove_final
```
```
In crypto/algboss.c (ffffffff813a4590)
Location: crypto/internal.h:113
Inline: True
Direct callers:
  - crypto/algboss.c:cryptomgr_probe
  - crypto/algboss.c:cryptomgr_notify
```
**Symbols:**

```
ffffffff813a4590-ffffffff813a45ac: crypto_alg_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void crypto_alg_put(struct crypto_alg *alg);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff813d997e)
Location: crypto/internal.h:116
Inline: True
Inline callers:
  - crypto/api.c:crypto_has_alg
  - crypto/api.c:crypto_destroy_tfm
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_base
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:crypto_larval_kill
  - crypto/api.c:__crypto_alg_lookup
```
```
In crypto/algapi.c (ffffffff813d9f72)
Location: crypto/internal.h:116
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_remove_final
```
```
In crypto/algboss.c (ffffffff813e1d50)
Location: crypto/internal.h:116
Inline: True
Direct callers:
  - crypto/algboss.c:cryptomgr_notify
  - crypto/algboss.c:cryptomgr_probe
```
**Symbols:**

```
ffffffff813e1d50-ffffffff813e1d6b: crypto_alg_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void crypto_alg_put(struct crypto_alg *alg);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff813f12ae)
Location: crypto/internal.h:113
Inline: True
Inline callers:
  - crypto/api.c:crypto_has_alg
  - crypto/api.c:crypto_destroy_tfm
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_base
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:crypto_larval_kill
  - crypto/api.c:__crypto_alg_lookup
```
```
In crypto/algapi.c (ffffffff813f18b2)
Location: crypto/internal.h:113
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_remove_final
```
```
In crypto/algboss.c (ffffffff813fadc0)
Location: crypto/internal.h:113
Inline: True
Direct callers:
  - crypto/algboss.c:cryptomgr_notify
  - crypto/algboss.c:cryptomgr_probe
```
**Symbols:**

```
ffffffff813fadc0-ffffffff813faddb: crypto_alg_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void crypto_alg_put(struct crypto_alg *alg);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff813fd54e)
Location: crypto/internal.h:113
Inline: True
Inline callers:
  - crypto/api.c:crypto_has_alg
  - crypto/api.c:crypto_destroy_tfm
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_base
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:crypto_larval_kill
  - crypto/api.c:__crypto_alg_lookup
```
```
In crypto/algapi.c (ffffffff813fdb34)
Location: crypto/internal.h:113
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_remove_final
```
```
In crypto/algboss.c (ffffffff814077e0)
Location: crypto/internal.h:113
Inline: True
Direct callers:
  - crypto/algboss.c:cryptomgr_notify
  - crypto/algboss.c:cryptomgr_probe
```
**Symbols:**

```
ffffffff814077e0-ffffffff814077fb: crypto_alg_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void crypto_alg_put(struct crypto_alg *alg);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff81425ace)
Location: crypto/internal.h:113
Inline: True
Inline callers:
  - crypto/api.c:crypto_has_alg
  - crypto/api.c:crypto_destroy_tfm
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_base
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:crypto_larval_kill
  - crypto/api.c:__crypto_alg_lookup
```
```
In crypto/algapi.c (ffffffff814260c4)
Location: crypto/internal.h:113
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_remove_final
```
```
In crypto/algboss.c (ffffffff81430130)
Location: crypto/internal.h:113
Inline: True
Direct callers:
  - crypto/algboss.c:cryptomgr_notify
  - crypto/algboss.c:cryptomgr_probe
```
**Symbols:**

```
ffffffff81430130-ffffffff8143014d: crypto_alg_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void crypto_alg_put(struct crypto_alg *alg);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff81458947)
Location: crypto/internal.h:108
Inline: True
Inline callers:
  - crypto/api.c:crypto_has_alg
  - crypto/api.c:crypto_destroy_tfm
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_base
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_alg_lookup
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:crypto_larval_kill
  - crypto/api.c:__crypto_alg_lookup
```
```
In crypto/algapi.c (ffffffff81458fc4)
Location: crypto/internal.h:108
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_remove_final
```
```
In crypto/algboss.c (ffffffff81462c70)
Location: crypto/internal.h:108
Inline: True
Direct callers:
  - crypto/algboss.c:cryptomgr_notify
  - crypto/algboss.c:cryptomgr_probe
```
**Symbols:**

```
ffffffff81462c70-ffffffff81462c93: crypto_alg_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void crypto_alg_put(struct crypto_alg *alg);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff81475e87)
Location: crypto/internal.h:100
Inline: True
Inline callers:
  - crypto/api.c:crypto_has_alg
  - crypto/api.c:crypto_has_alg
  - crypto/api.c:crypto_destroy_tfm
  - crypto/api.c:crypto_destroy_tfm
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_base
  - crypto/api.c:crypto_alloc_base
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_alg_lookup
  - crypto/api.c:crypto_alg_lookup
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:crypto_larval_kill
  - crypto/api.c:crypto_larval_kill
  - crypto/api.c:__crypto_alg_lookup
  - crypto/api.c:__crypto_alg_lookup
```
```
In crypto/algapi.c (ffffffff814781a8)
Location: crypto/internal.h:100
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_stats_rng_generate
  - crypto/algapi.c:crypto_stats_rng_generate
  - crypto/algapi.c:crypto_stats_rng_seed
  - crypto/algapi.c:crypto_stats_rng_seed
  - crypto/algapi.c:crypto_stats_kpp_compute_shared_secret
  - crypto/algapi.c:crypto_stats_kpp_compute_shared_secret
  - crypto/algapi.c:crypto_stats_kpp_generate_public_key
  - crypto/algapi.c:crypto_stats_kpp_generate_public_key
  - crypto/algapi.c:crypto_stats_kpp_set_secret
  - crypto/algapi.c:crypto_stats_kpp_set_secret
  - crypto/algapi.c:crypto_stats_ahash_final
  - crypto/algapi.c:crypto_stats_ahash_final
  - crypto/algapi.c:crypto_stats_ahash_update
  - crypto/algapi.c:crypto_stats_ahash_update
  - crypto/algapi.c:crypto_stats_decompress
  - crypto/algapi.c:crypto_stats_decompress
  - crypto/algapi.c:crypto_stats_compress
  - crypto/algapi.c:crypto_stats_compress
  - crypto/algapi.c:crypto_stats_akcipher_verify
  - crypto/algapi.c:crypto_stats_akcipher_verify
  - crypto/algapi.c:crypto_stats_akcipher_sign
  - crypto/algapi.c:crypto_stats_akcipher_sign
  - crypto/algapi.c:crypto_stats_akcipher_decrypt
  - crypto/algapi.c:crypto_stats_akcipher_decrypt
  - crypto/algapi.c:crypto_stats_akcipher_encrypt
  - crypto/algapi.c:crypto_stats_akcipher_encrypt
  - crypto/algapi.c:crypto_stats_aead_decrypt
  - crypto/algapi.c:crypto_stats_aead_decrypt
  - crypto/algapi.c:crypto_stats_aead_encrypt
  - crypto/algapi.c:crypto_stats_aead_encrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_decrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_decrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_encrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_encrypt
  - crypto/algapi.c:crypto_remove_final
  - crypto/algapi.c:crypto_remove_final
```
```
In crypto/algboss.c (ffffffff814808f0)
Location: crypto/internal.h:100
Inline: True
Direct callers:
  - crypto/algboss.c:cryptomgr_notify
  - crypto/algboss.c:cryptomgr_probe
```
**Symbols:**

```
ffffffff814808f0-ffffffff81480913: crypto_alg_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void crypto_alg_put(struct crypto_alg *alg);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff814a3c72)
Location: crypto/internal.h:95
Inline: True
Inline callers:
  - crypto/api.c:crypto_has_alg
  - crypto/api.c:crypto_has_alg
  - crypto/api.c:crypto_destroy_tfm
  - crypto/api.c:crypto_destroy_tfm
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_base
  - crypto/api.c:crypto_alloc_base
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_alg_lookup
  - crypto/api.c:crypto_alg_lookup
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:crypto_larval_kill
  - crypto/api.c:crypto_larval_kill
  - crypto/api.c:__crypto_alg_lookup
  - crypto/api.c:__crypto_alg_lookup
```
```
In crypto/algapi.c (ffffffff814a6077)
Location: crypto/internal.h:95
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_stats_skcipher_decrypt
  - crypto/algapi.c:crypto_stats_skcipher_decrypt
  - crypto/algapi.c:crypto_stats_skcipher_encrypt
  - crypto/algapi.c:crypto_stats_skcipher_encrypt
  - crypto/algapi.c:crypto_stats_rng_generate
  - crypto/algapi.c:crypto_stats_rng_generate
  - crypto/algapi.c:crypto_stats_rng_seed
  - crypto/algapi.c:crypto_stats_rng_seed
  - crypto/algapi.c:crypto_stats_kpp_compute_shared_secret
  - crypto/algapi.c:crypto_stats_kpp_compute_shared_secret
  - crypto/algapi.c:crypto_stats_kpp_generate_public_key
  - crypto/algapi.c:crypto_stats_kpp_generate_public_key
  - crypto/algapi.c:crypto_stats_kpp_set_secret
  - crypto/algapi.c:crypto_stats_kpp_set_secret
  - crypto/algapi.c:crypto_stats_ahash_final
  - crypto/algapi.c:crypto_stats_ahash_final
  - crypto/algapi.c:crypto_stats_ahash_update
  - crypto/algapi.c:crypto_stats_ahash_update
  - crypto/algapi.c:crypto_stats_decompress
  - crypto/algapi.c:crypto_stats_decompress
  - crypto/algapi.c:crypto_stats_compress
  - crypto/algapi.c:crypto_stats_compress
  - crypto/algapi.c:crypto_stats_akcipher_verify
  - crypto/algapi.c:crypto_stats_akcipher_verify
  - crypto/algapi.c:crypto_stats_akcipher_sign
  - crypto/algapi.c:crypto_stats_akcipher_sign
  - crypto/algapi.c:crypto_stats_akcipher_decrypt
  - crypto/algapi.c:crypto_stats_akcipher_decrypt
  - crypto/algapi.c:crypto_stats_akcipher_encrypt
  - crypto/algapi.c:crypto_stats_akcipher_encrypt
  - crypto/algapi.c:crypto_stats_aead_decrypt
  - crypto/algapi.c:crypto_stats_aead_decrypt
  - crypto/algapi.c:crypto_stats_aead_encrypt
  - crypto/algapi.c:crypto_stats_aead_encrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_decrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_decrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_encrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_encrypt
  - crypto/algapi.c:crypto_remove_final
  - crypto/algapi.c:crypto_remove_final
```
```
In crypto/algboss.c (ffffffff814af104)
Location: crypto/internal.h:95
Inline: True
Inline callers:
  - crypto/algboss.c:cryptomgr_probe
  - crypto/algboss.c:cryptomgr_probe
Direct callers:
  - crypto/algboss.c:cryptomgr_notify
```
**Symbols:**

```
ffffffff814aeae0-ffffffff814aeb04: crypto_alg_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void crypto_alg_put(struct crypto_alg *alg);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff814be8a2)
Location: crypto/internal.h:94
Inline: True
Inline callers:
  - crypto/api.c:crypto_has_alg
  - crypto/api.c:crypto_has_alg
  - crypto/api.c:crypto_destroy_tfm
  - crypto/api.c:crypto_destroy_tfm
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_base
  - crypto/api.c:crypto_alloc_base
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_alg_lookup
  - crypto/api.c:crypto_alg_lookup
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:crypto_larval_kill
  - crypto/api.c:crypto_larval_kill
  - crypto/api.c:__crypto_alg_lookup
  - crypto/api.c:__crypto_alg_lookup
```
```
In crypto/algapi.c (ffffffff814c09c7)
Location: crypto/internal.h:94
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_stats_skcipher_decrypt
  - crypto/algapi.c:crypto_stats_skcipher_decrypt
  - crypto/algapi.c:crypto_stats_skcipher_encrypt
  - crypto/algapi.c:crypto_stats_skcipher_encrypt
  - crypto/algapi.c:crypto_stats_rng_generate
  - crypto/algapi.c:crypto_stats_rng_generate
  - crypto/algapi.c:crypto_stats_rng_seed
  - crypto/algapi.c:crypto_stats_rng_seed
  - crypto/algapi.c:crypto_stats_kpp_compute_shared_secret
  - crypto/algapi.c:crypto_stats_kpp_compute_shared_secret
  - crypto/algapi.c:crypto_stats_kpp_generate_public_key
  - crypto/algapi.c:crypto_stats_kpp_generate_public_key
  - crypto/algapi.c:crypto_stats_kpp_set_secret
  - crypto/algapi.c:crypto_stats_kpp_set_secret
  - crypto/algapi.c:crypto_stats_ahash_final
  - crypto/algapi.c:crypto_stats_ahash_final
  - crypto/algapi.c:crypto_stats_ahash_update
  - crypto/algapi.c:crypto_stats_ahash_update
  - crypto/algapi.c:crypto_stats_decompress
  - crypto/algapi.c:crypto_stats_decompress
  - crypto/algapi.c:crypto_stats_compress
  - crypto/algapi.c:crypto_stats_compress
  - crypto/algapi.c:crypto_stats_akcipher_verify
  - crypto/algapi.c:crypto_stats_akcipher_verify
  - crypto/algapi.c:crypto_stats_akcipher_sign
  - crypto/algapi.c:crypto_stats_akcipher_sign
  - crypto/algapi.c:crypto_stats_akcipher_decrypt
  - crypto/algapi.c:crypto_stats_akcipher_decrypt
  - crypto/algapi.c:crypto_stats_akcipher_encrypt
  - crypto/algapi.c:crypto_stats_akcipher_encrypt
  - crypto/algapi.c:crypto_stats_aead_decrypt
  - crypto/algapi.c:crypto_stats_aead_decrypt
  - crypto/algapi.c:crypto_stats_aead_encrypt
  - crypto/algapi.c:crypto_stats_aead_encrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_decrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_decrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_encrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_encrypt
  - crypto/algapi.c:crypto_remove_final
  - crypto/algapi.c:crypto_remove_final
```
```
In crypto/algboss.c (ffffffff814c9d94)
Location: crypto/internal.h:94
Inline: True
Inline callers:
  - crypto/algboss.c:cryptomgr_probe
  - crypto/algboss.c:cryptomgr_probe
Direct callers:
  - crypto/algboss.c:cryptomgr_notify
```
**Symbols:**

```
ffffffff814c9770-ffffffff814c9794: crypto_alg_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void crypto_alg_put(struct crypto_alg *alg);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff8151e75a)
Location: crypto/internal.h:92
Inline: True
Inline callers:
  - crypto/api.c:crypto_larval_kill
  - crypto/api.c:crypto_larval_kill
  - crypto/api.c:crypto_mod_put
  - crypto/api.c:crypto_mod_put
```
```
In crypto/algapi.c (ffffffff815211eb)
Location: crypto/internal.h:92
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_stats_skcipher_decrypt
  - crypto/algapi.c:crypto_stats_skcipher_decrypt
  - crypto/algapi.c:crypto_stats_skcipher_encrypt
  - crypto/algapi.c:crypto_stats_skcipher_encrypt
  - crypto/algapi.c:crypto_stats_rng_generate
  - crypto/algapi.c:crypto_stats_rng_generate
  - crypto/algapi.c:crypto_stats_rng_seed
  - crypto/algapi.c:crypto_stats_rng_seed
  - crypto/algapi.c:crypto_stats_kpp_compute_shared_secret
  - crypto/algapi.c:crypto_stats_kpp_compute_shared_secret
  - crypto/algapi.c:crypto_stats_kpp_generate_public_key
  - crypto/algapi.c:crypto_stats_kpp_generate_public_key
  - crypto/algapi.c:crypto_stats_kpp_set_secret
  - crypto/algapi.c:crypto_stats_kpp_set_secret
  - crypto/algapi.c:crypto_stats_ahash_final
  - crypto/algapi.c:crypto_stats_ahash_final
  - crypto/algapi.c:crypto_stats_ahash_update
  - crypto/algapi.c:crypto_stats_ahash_update
  - crypto/algapi.c:crypto_stats_decompress
  - crypto/algapi.c:crypto_stats_decompress
  - crypto/algapi.c:crypto_stats_compress
  - crypto/algapi.c:crypto_stats_compress
  - crypto/algapi.c:crypto_stats_akcipher_verify
  - crypto/algapi.c:crypto_stats_akcipher_verify
  - crypto/algapi.c:crypto_stats_akcipher_sign
  - crypto/algapi.c:crypto_stats_akcipher_sign
  - crypto/algapi.c:crypto_stats_akcipher_decrypt
  - crypto/algapi.c:crypto_stats_akcipher_decrypt
  - crypto/algapi.c:crypto_stats_akcipher_encrypt
  - crypto/algapi.c:crypto_stats_akcipher_encrypt
  - crypto/algapi.c:crypto_stats_aead_decrypt
  - crypto/algapi.c:crypto_stats_aead_decrypt
  - crypto/algapi.c:crypto_stats_aead_encrypt
  - crypto/algapi.c:crypto_stats_aead_encrypt
  - crypto/algapi.c:crypto_spawn_alg
  - crypto/algapi.c:crypto_spawn_alg
  - crypto/algapi.c:crypto_remove_final
  - crypto/algapi.c:crypto_remove_final
```
```
In crypto/algboss.c (ffffffff81528b30)
Location: crypto/internal.h:92
Inline: True
Direct callers:
  - crypto/algboss.c:cryptomgr_schedule_probe
  - crypto/algboss.c:cryptomgr_probe
```
```
In crypto/rng.c (ffffffff81532eb9)
Location: crypto/internal.h:92
Inline: True
Inline callers:
  - crypto/rng.c:crypto_rng_reset
  - crypto/rng.c:crypto_rng_reset
Direct callers:
  - crypto/rng.c:crypto_rng_reset
```
**Symbols:**

```
ffffffff81528b30-ffffffff81528b6f: crypto_alg_put (STB_LOCAL)
ffffffff81532d40-ffffffff81532d7f: crypto_alg_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void crypto_alg_put(struct crypto_alg *alg);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff8153b4ea)
Location: crypto/internal.h:105
Inline: True
Inline callers:
  - crypto/api.c:crypto_larval_kill
  - crypto/api.c:crypto_larval_kill
  - crypto/api.c:crypto_mod_put
  - crypto/api.c:crypto_mod_put
```
```
In crypto/algapi.c (ffffffff8153e23b)
Location: crypto/internal.h:105
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_stats_skcipher_decrypt
  - crypto/algapi.c:crypto_stats_skcipher_decrypt
  - crypto/algapi.c:crypto_stats_skcipher_encrypt
  - crypto/algapi.c:crypto_stats_skcipher_encrypt
  - crypto/algapi.c:crypto_stats_rng_generate
  - crypto/algapi.c:crypto_stats_rng_generate
  - crypto/algapi.c:crypto_stats_rng_seed
  - crypto/algapi.c:crypto_stats_rng_seed
  - crypto/algapi.c:crypto_stats_kpp_compute_shared_secret
  - crypto/algapi.c:crypto_stats_kpp_compute_shared_secret
  - crypto/algapi.c:crypto_stats_kpp_generate_public_key
  - crypto/algapi.c:crypto_stats_kpp_generate_public_key
  - crypto/algapi.c:crypto_stats_kpp_set_secret
  - crypto/algapi.c:crypto_stats_kpp_set_secret
  - crypto/algapi.c:crypto_stats_ahash_final
  - crypto/algapi.c:crypto_stats_ahash_final
  - crypto/algapi.c:crypto_stats_ahash_update
  - crypto/algapi.c:crypto_stats_ahash_update
  - crypto/algapi.c:crypto_stats_decompress
  - crypto/algapi.c:crypto_stats_decompress
  - crypto/algapi.c:crypto_stats_compress
  - crypto/algapi.c:crypto_stats_compress
  - crypto/algapi.c:crypto_stats_akcipher_verify
  - crypto/algapi.c:crypto_stats_akcipher_verify
  - crypto/algapi.c:crypto_stats_akcipher_sign
  - crypto/algapi.c:crypto_stats_akcipher_sign
  - crypto/algapi.c:crypto_stats_akcipher_decrypt
  - crypto/algapi.c:crypto_stats_akcipher_decrypt
  - crypto/algapi.c:crypto_stats_akcipher_encrypt
  - crypto/algapi.c:crypto_stats_akcipher_encrypt
  - crypto/algapi.c:crypto_stats_aead_decrypt
  - crypto/algapi.c:crypto_stats_aead_decrypt
  - crypto/algapi.c:crypto_stats_aead_encrypt
  - crypto/algapi.c:crypto_stats_aead_encrypt
  - crypto/algapi.c:crypto_spawn_alg
  - crypto/algapi.c:crypto_spawn_alg
  - crypto/algapi.c:crypto_remove_final
  - crypto/algapi.c:crypto_remove_final
```
```
In crypto/algboss.c (ffffffff81545b00)
Location: crypto/internal.h:105
Inline: True
Direct callers:
  - crypto/algboss.c:cryptomgr_schedule_probe
  - crypto/algboss.c:cryptomgr_probe
```
```
In crypto/rng.c (ffffffff8154fe29)
Location: crypto/internal.h:105
Inline: True
Inline callers:
  - crypto/rng.c:crypto_rng_reset
  - crypto/rng.c:crypto_rng_reset
Direct callers:
  - crypto/rng.c:crypto_rng_reset
```
**Symbols:**

```
ffffffff81545b00-ffffffff81545b3f: crypto_alg_put (STB_LOCAL)
ffffffff8154fcb0-ffffffff8154fcef: crypto_alg_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void crypto_alg_put(struct crypto_alg *alg);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff81543bda)
Location: crypto/internal.h:105
Inline: True
Inline callers:
  - crypto/api.c:crypto_larval_kill
  - crypto/api.c:crypto_larval_kill
  - crypto/api.c:crypto_mod_put
  - crypto/api.c:crypto_mod_put
```
```
In crypto/algapi.c (ffffffff815469f8)
Location: crypto/internal.h:105
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_stats_rng_generate
  - crypto/algapi.c:crypto_stats_rng_generate
  - crypto/algapi.c:crypto_stats_rng_seed
  - crypto/algapi.c:crypto_stats_rng_seed
  - crypto/algapi.c:crypto_stats_kpp_compute_shared_secret
  - crypto/algapi.c:crypto_stats_kpp_compute_shared_secret
  - crypto/algapi.c:crypto_stats_kpp_generate_public_key
  - crypto/algapi.c:crypto_stats_kpp_generate_public_key
  - crypto/algapi.c:crypto_stats_kpp_set_secret
  - crypto/algapi.c:crypto_stats_kpp_set_secret
  - crypto/algapi.c:crypto_stats_ahash_final
  - crypto/algapi.c:crypto_stats_ahash_final
  - crypto/algapi.c:crypto_stats_ahash_update
  - crypto/algapi.c:crypto_stats_ahash_update
  - crypto/algapi.c:crypto_stats_decompress
  - crypto/algapi.c:crypto_stats_decompress
  - crypto/algapi.c:crypto_stats_compress
  - crypto/algapi.c:crypto_stats_compress
  - crypto/algapi.c:crypto_stats_akcipher_verify
  - crypto/algapi.c:crypto_stats_akcipher_verify
  - crypto/algapi.c:crypto_stats_akcipher_sign
  - crypto/algapi.c:crypto_stats_akcipher_sign
  - crypto/algapi.c:crypto_stats_akcipher_decrypt
  - crypto/algapi.c:crypto_stats_akcipher_decrypt
  - crypto/algapi.c:crypto_stats_akcipher_encrypt
  - crypto/algapi.c:crypto_stats_akcipher_encrypt
  - crypto/algapi.c:crypto_stats_aead_decrypt
  - crypto/algapi.c:crypto_stats_aead_decrypt
  - crypto/algapi.c:crypto_stats_aead_encrypt
  - crypto/algapi.c:crypto_stats_aead_encrypt
  - crypto/algapi.c:crypto_spawn_alg
  - crypto/algapi.c:crypto_spawn_alg
  - crypto/algapi.c:crypto_remove_final
  - crypto/algapi.c:crypto_remove_final
```
```
In crypto/algboss.c (ffffffff8154e180)
Location: crypto/internal.h:105
Inline: True
Direct callers:
  - crypto/algboss.c:cryptomgr_schedule_probe
  - crypto/algboss.c:cryptomgr_probe
```
**Symbols:**

```
ffffffff8154e180-ffffffff8154e1bf: crypto_alg_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void crypto_alg_put(struct crypto_alg *alg);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff815a437a)
Location: crypto/internal.h:117
Inline: True
Inline callers:
  - crypto/api.c:crypto_larval_kill
  - crypto/api.c:crypto_larval_kill
  - crypto/api.c:crypto_mod_put
  - crypto/api.c:crypto_mod_put
```
```
In crypto/algapi.c (ffffffff815a6fa8)
Location: crypto/internal.h:117
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_stats_rng_generate
  - crypto/algapi.c:crypto_stats_rng_generate
  - crypto/algapi.c:crypto_stats_rng_seed
  - crypto/algapi.c:crypto_stats_rng_seed
  - crypto/algapi.c:crypto_stats_kpp_compute_shared_secret
  - crypto/algapi.c:crypto_stats_kpp_compute_shared_secret
  - crypto/algapi.c:crypto_stats_kpp_generate_public_key
  - crypto/algapi.c:crypto_stats_kpp_generate_public_key
  - crypto/algapi.c:crypto_stats_kpp_set_secret
  - crypto/algapi.c:crypto_stats_kpp_set_secret
  - crypto/algapi.c:crypto_stats_ahash_final
  - crypto/algapi.c:crypto_stats_ahash_final
  - crypto/algapi.c:crypto_stats_ahash_update
  - crypto/algapi.c:crypto_stats_ahash_update
  - crypto/algapi.c:crypto_stats_akcipher_verify
  - crypto/algapi.c:crypto_stats_akcipher_verify
  - crypto/algapi.c:crypto_stats_akcipher_sign
  - crypto/algapi.c:crypto_stats_akcipher_sign
  - crypto/algapi.c:crypto_stats_akcipher_decrypt
  - crypto/algapi.c:crypto_stats_akcipher_decrypt
  - crypto/algapi.c:crypto_stats_akcipher_encrypt
  - crypto/algapi.c:crypto_stats_akcipher_encrypt
  - crypto/algapi.c:crypto_stats_aead_decrypt
  - crypto/algapi.c:crypto_stats_aead_decrypt
  - crypto/algapi.c:crypto_stats_aead_encrypt
  - crypto/algapi.c:crypto_stats_aead_encrypt
  - crypto/algapi.c:crypto_spawn_alg
  - crypto/algapi.c:crypto_spawn_alg
  - crypto/algapi.c:crypto_remove_final
  - crypto/algapi.c:crypto_remove_final
```
```
In crypto/algboss.c (ffffffff815ae9f0)
Location: crypto/internal.h:117
Inline: True
Direct callers:
  - crypto/algboss.c:cryptomgr_schedule_probe
  - crypto/algboss.c:cryptomgr_probe
```
**Symbols:**

```
ffffffff815ae9f0-ffffffff815aea2f: crypto_alg_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void crypto_alg_put(struct crypto_alg *alg);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff8164ad34)
Location: crypto/internal.h:122
Inline: True
Inline callers:
  - crypto/api.c:crypto_larval_kill
  - crypto/api.c:crypto_larval_kill
  - crypto/api.c:crypto_mod_put
  - crypto/api.c:crypto_mod_put
```
```
In crypto/algapi.c (ffffffff8164e108)
Location: crypto/internal.h:122
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_stats_rng_generate
  - crypto/algapi.c:crypto_stats_rng_generate
  - crypto/algapi.c:crypto_stats_rng_seed
  - crypto/algapi.c:crypto_stats_rng_seed
  - crypto/algapi.c:crypto_stats_kpp_compute_shared_secret
  - crypto/algapi.c:crypto_stats_kpp_compute_shared_secret
  - crypto/algapi.c:crypto_stats_kpp_generate_public_key
  - crypto/algapi.c:crypto_stats_kpp_generate_public_key
  - crypto/algapi.c:crypto_stats_kpp_set_secret
  - crypto/algapi.c:crypto_stats_kpp_set_secret
  - crypto/algapi.c:crypto_stats_ahash_final
  - crypto/algapi.c:crypto_stats_ahash_final
  - crypto/algapi.c:crypto_stats_ahash_update
  - crypto/algapi.c:crypto_stats_ahash_update
  - crypto/algapi.c:crypto_stats_decompress
  - crypto/algapi.c:crypto_stats_decompress
  - crypto/algapi.c:crypto_stats_compress
  - crypto/algapi.c:crypto_stats_compress
  - crypto/algapi.c:crypto_stats_akcipher_verify
  - crypto/algapi.c:crypto_stats_akcipher_verify
  - crypto/algapi.c:crypto_stats_akcipher_sign
  - crypto/algapi.c:crypto_stats_akcipher_sign
  - crypto/algapi.c:crypto_stats_akcipher_decrypt
  - crypto/algapi.c:crypto_stats_akcipher_decrypt
  - crypto/algapi.c:crypto_stats_akcipher_encrypt
  - crypto/algapi.c:crypto_stats_akcipher_encrypt
  - crypto/algapi.c:crypto_stats_aead_decrypt
  - crypto/algapi.c:crypto_stats_aead_decrypt
  - crypto/algapi.c:crypto_stats_aead_encrypt
  - crypto/algapi.c:crypto_stats_aead_encrypt
  - crypto/algapi.c:crypto_spawn_alg
  - crypto/algapi.c:crypto_spawn_alg
  - crypto/algapi.c:crypto_remove_final
  - crypto/algapi.c:crypto_remove_final
```
```
In crypto/algboss.c (ffffffff81657010)
Location: crypto/internal.h:122
Inline: True
Direct callers:
  - crypto/algboss.c:cryptomgr_schedule_probe
  - crypto/algboss.c:cryptomgr_probe
```
**Symbols:**

```
ffffffff81657010-ffffffff81657073: crypto_alg_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void crypto_alg_put(struct crypto_alg *alg);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff81703ef4)
Location: crypto/internal.h:140
Inline: True
Inline callers:
  - crypto/api.c:crypto_larval_kill
  - crypto/api.c:crypto_larval_kill
  - crypto/api.c:crypto_mod_put
  - crypto/api.c:crypto_mod_put
```
```
In crypto/algapi.c (ffffffff81707588)
Location: crypto/internal.h:140
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_stats_rng_generate
  - crypto/algapi.c:crypto_stats_rng_generate
  - crypto/algapi.c:crypto_stats_rng_seed
  - crypto/algapi.c:crypto_stats_rng_seed
  - crypto/algapi.c:crypto_stats_kpp_compute_shared_secret
  - crypto/algapi.c:crypto_stats_kpp_compute_shared_secret
  - crypto/algapi.c:crypto_stats_kpp_generate_public_key
  - crypto/algapi.c:crypto_stats_kpp_generate_public_key
  - crypto/algapi.c:crypto_stats_kpp_set_secret
  - crypto/algapi.c:crypto_stats_kpp_set_secret
  - crypto/algapi.c:crypto_stats_ahash_final
  - crypto/algapi.c:crypto_stats_ahash_final
  - crypto/algapi.c:crypto_stats_ahash_update
  - crypto/algapi.c:crypto_stats_ahash_update
  - crypto/algapi.c:crypto_stats_decompress
  - crypto/algapi.c:crypto_stats_decompress
  - crypto/algapi.c:crypto_stats_compress
  - crypto/algapi.c:crypto_stats_compress
  - crypto/algapi.c:crypto_stats_akcipher_verify
  - crypto/algapi.c:crypto_stats_akcipher_verify
  - crypto/algapi.c:crypto_stats_akcipher_sign
  - crypto/algapi.c:crypto_stats_akcipher_sign
  - crypto/algapi.c:crypto_stats_akcipher_decrypt
  - crypto/algapi.c:crypto_stats_akcipher_decrypt
  - crypto/algapi.c:crypto_stats_akcipher_encrypt
  - crypto/algapi.c:crypto_stats_akcipher_encrypt
  - crypto/algapi.c:crypto_stats_aead_decrypt
  - crypto/algapi.c:crypto_stats_aead_decrypt
  - crypto/algapi.c:crypto_stats_aead_encrypt
  - crypto/algapi.c:crypto_stats_aead_encrypt
  - crypto/algapi.c:crypto_spawn_alg
  - crypto/algapi.c:crypto_spawn_alg
  - crypto/algapi.c:crypto_remove_final
  - crypto/algapi.c:crypto_remove_final
```
```
In crypto/algboss.c (ffffffff817113c0)
Location: crypto/internal.h:140
Inline: True
Direct callers:
  - crypto/algboss.c:cryptomgr_schedule_probe
  - crypto/algboss.c:cryptomgr_probe
```
**Symbols:**

```
ffffffff817113c0-ffffffff81711423: crypto_alg_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void crypto_alg_put(struct crypto_alg *alg);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff8173e2d4)
Location: crypto/internal.h:167
Inline: True
Inline callers:
  - crypto/api.c:crypto_larval_kill
  - crypto/api.c:crypto_larval_kill
  - crypto/api.c:crypto_mod_put
  - crypto/api.c:crypto_mod_put
```
```
In crypto/algapi.c (ffffffff8173fea1)
Location: crypto/internal.h:167
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_spawn_alg
  - crypto/algapi.c:crypto_spawn_alg
  - crypto/algapi.c:crypto_remove_final
  - crypto/algapi.c:crypto_remove_final
```
```
In crypto/algboss.c (ffffffff8174beb0)
Location: crypto/internal.h:167
Inline: True
Direct callers:
  - crypto/algboss.c:cryptomgr_schedule_probe
  - crypto/algboss.c:cryptomgr_probe
```
**Symbols:**

```
ffffffff8174beb0-ffffffff8174bf13: crypto_alg_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void crypto_alg_put(struct crypto_alg *alg);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff8177f154)
Location: crypto/internal.h:167
Inline: True
Inline callers:
  - crypto/api.c:crypto_larval_kill
  - crypto/api.c:crypto_larval_kill
  - crypto/api.c:crypto_mod_put
  - crypto/api.c:crypto_mod_put
```
```
In crypto/algapi.c (ffffffff81780d21)
Location: crypto/internal.h:167
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_spawn_alg
  - crypto/algapi.c:crypto_spawn_alg
  - crypto/algapi.c:crypto_remove_final
  - crypto/algapi.c:crypto_remove_final
```
```
In crypto/algboss.c (ffffffff8178dd90)
Location: crypto/internal.h:167
Inline: True
Direct callers:
  - crypto/algboss.c:cryptomgr_schedule_probe
  - crypto/algboss.c:cryptomgr_probe
```
**Symbols:**

```
ffffffff8178dd90-ffffffff8178ddf3: crypto_alg_put (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void crypto_alg_put(struct crypto_alg *alg);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffff8000105b7900)
Location: crypto/internal.h:94
Inline: True
Inline callers:
  - crypto/api.c:crypto_has_alg
  - crypto/api.c:crypto_has_alg
  - crypto/api.c:crypto_destroy_tfm
  - crypto/api.c:crypto_destroy_tfm
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_base
  - crypto/api.c:crypto_alloc_base
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_alg_lookup
  - crypto/api.c:crypto_alg_lookup
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:crypto_larval_kill
  - crypto/api.c:crypto_larval_kill
  - crypto/api.c:__crypto_alg_lookup
  - crypto/api.c:__crypto_alg_lookup
```
```
In crypto/algapi.c (ffff8000105ba9bc)
Location: crypto/internal.h:94
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_stats_rng_generate
  - crypto/algapi.c:crypto_stats_rng_generate
  - crypto/algapi.c:crypto_stats_rng_seed
  - crypto/algapi.c:crypto_stats_rng_seed
  - crypto/algapi.c:crypto_stats_kpp_compute_shared_secret
  - crypto/algapi.c:crypto_stats_kpp_compute_shared_secret
  - crypto/algapi.c:crypto_stats_kpp_generate_public_key
  - crypto/algapi.c:crypto_stats_kpp_generate_public_key
  - crypto/algapi.c:crypto_stats_kpp_set_secret
  - crypto/algapi.c:crypto_stats_kpp_set_secret
  - crypto/algapi.c:crypto_stats_ahash_final
  - crypto/algapi.c:crypto_stats_ahash_final
  - crypto/algapi.c:crypto_stats_ahash_update
  - crypto/algapi.c:crypto_stats_ahash_update
  - crypto/algapi.c:crypto_stats_decompress
  - crypto/algapi.c:crypto_stats_decompress
  - crypto/algapi.c:crypto_stats_compress
  - crypto/algapi.c:crypto_stats_compress
  - crypto/algapi.c:crypto_stats_akcipher_verify
  - crypto/algapi.c:crypto_stats_akcipher_verify
  - crypto/algapi.c:crypto_stats_akcipher_sign
  - crypto/algapi.c:crypto_stats_akcipher_sign
  - crypto/algapi.c:crypto_stats_akcipher_decrypt
  - crypto/algapi.c:crypto_stats_akcipher_decrypt
  - crypto/algapi.c:crypto_stats_akcipher_encrypt
  - crypto/algapi.c:crypto_stats_akcipher_encrypt
  - crypto/algapi.c:crypto_stats_aead_decrypt
  - crypto/algapi.c:crypto_stats_aead_decrypt
  - crypto/algapi.c:crypto_stats_aead_encrypt
  - crypto/algapi.c:crypto_stats_aead_encrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_decrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_decrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_encrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_encrypt
  - crypto/algapi.c:crypto_remove_final
  - crypto/algapi.c:crypto_remove_final
```
```
In crypto/algboss.c (ffff8000105c5460)
Location: crypto/internal.h:94
Inline: True
Direct callers:
  - crypto/algboss.c:cryptomgr_notify
  - crypto/algboss.c:cryptomgr_probe
```
**Symbols:**

```
ffff8000105c5460-ffff8000105c549c: crypto_alg_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void crypto_alg_put(struct crypto_alg *alg);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/api.c (c0766570)
Location: crypto/internal.h:94
Inline: True
Inline callers:
  - crypto/api.c:crypto_has_alg
  - crypto/api.c:crypto_has_alg
  - crypto/api.c:crypto_destroy_tfm
  - crypto/api.c:crypto_destroy_tfm
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_base
  - crypto/api.c:crypto_alloc_base
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_alg_lookup
  - crypto/api.c:crypto_alg_lookup
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:crypto_larval_kill
  - crypto/api.c:crypto_larval_kill
  - crypto/api.c:__crypto_alg_lookup
  - crypto/api.c:__crypto_alg_lookup
```
```
In crypto/algapi.c (c0768cf8)
Location: crypto/internal.h:94
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_stats_rng_generate
  - crypto/algapi.c:crypto_stats_rng_generate
  - crypto/algapi.c:crypto_stats_rng_seed
  - crypto/algapi.c:crypto_stats_rng_seed
  - crypto/algapi.c:crypto_stats_kpp_compute_shared_secret
  - crypto/algapi.c:crypto_stats_kpp_compute_shared_secret
  - crypto/algapi.c:crypto_stats_kpp_generate_public_key
  - crypto/algapi.c:crypto_stats_kpp_generate_public_key
  - crypto/algapi.c:crypto_stats_kpp_set_secret
  - crypto/algapi.c:crypto_stats_kpp_set_secret
  - crypto/algapi.c:crypto_stats_ahash_final
  - crypto/algapi.c:crypto_stats_ahash_final
  - crypto/algapi.c:crypto_stats_ahash_update
  - crypto/algapi.c:crypto_stats_ahash_update
  - crypto/algapi.c:crypto_stats_decompress
  - crypto/algapi.c:crypto_stats_decompress
  - crypto/algapi.c:crypto_stats_compress
  - crypto/algapi.c:crypto_stats_compress
  - crypto/algapi.c:crypto_stats_akcipher_verify
  - crypto/algapi.c:crypto_stats_akcipher_verify
  - crypto/algapi.c:crypto_stats_akcipher_sign
  - crypto/algapi.c:crypto_stats_akcipher_sign
  - crypto/algapi.c:crypto_stats_akcipher_decrypt
  - crypto/algapi.c:crypto_stats_akcipher_decrypt
  - crypto/algapi.c:crypto_stats_akcipher_encrypt
  - crypto/algapi.c:crypto_stats_akcipher_encrypt
  - crypto/algapi.c:crypto_stats_aead_decrypt
  - crypto/algapi.c:crypto_stats_aead_decrypt
  - crypto/algapi.c:crypto_stats_aead_encrypt
  - crypto/algapi.c:crypto_stats_aead_encrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_decrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_decrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_encrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_encrypt
  - crypto/algapi.c:crypto_remove_final
  - crypto/algapi.c:crypto_remove_final
```
```
In crypto/algboss.c (c0772328)
Location: crypto/internal.h:94
Inline: True
Direct callers:
  - crypto/algboss.c:cryptomgr_notify
  - crypto/algboss.c:cryptomgr_probe
```
**Symbols:**

```
c0772328-c0772360: crypto_alg_put (STB_LOCAL)
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
In crypto/api.c (c00000000073c76c)
Location: crypto/internal.h:94
Inline: True
Inline callers:
  - crypto/api.c:crypto_has_alg
  - crypto/api.c:crypto_has_alg
  - crypto/api.c:crypto_destroy_tfm
  - crypto/api.c:crypto_destroy_tfm
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_base
  - crypto/api.c:crypto_alloc_base
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_alg_lookup
  - crypto/api.c:crypto_alg_lookup
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:crypto_larval_kill
  - crypto/api.c:crypto_larval_kill
  - crypto/api.c:crypto_larval_destroy
  - crypto/api.c:crypto_larval_destroy
  - crypto/api.c:__crypto_alg_lookup
  - crypto/api.c:__crypto_alg_lookup
```
```
In crypto/algapi.c (c0000000007413ac)
Location: crypto/internal.h:94
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_stats_skcipher_decrypt
  - crypto/algapi.c:crypto_stats_skcipher_decrypt
  - crypto/algapi.c:crypto_stats_skcipher_encrypt
  - crypto/algapi.c:crypto_stats_skcipher_encrypt
  - crypto/algapi.c:crypto_stats_rng_generate
  - crypto/algapi.c:crypto_stats_rng_generate
  - crypto/algapi.c:crypto_stats_rng_seed
  - crypto/algapi.c:crypto_stats_rng_seed
  - crypto/algapi.c:crypto_stats_kpp_compute_shared_secret
  - crypto/algapi.c:crypto_stats_kpp_compute_shared_secret
  - crypto/algapi.c:crypto_stats_kpp_generate_public_key
  - crypto/algapi.c:crypto_stats_kpp_generate_public_key
  - crypto/algapi.c:crypto_stats_kpp_set_secret
  - crypto/algapi.c:crypto_stats_kpp_set_secret
  - crypto/algapi.c:crypto_stats_ahash_final
  - crypto/algapi.c:crypto_stats_ahash_final
  - crypto/algapi.c:crypto_stats_ahash_update
  - crypto/algapi.c:crypto_stats_ahash_update
  - crypto/algapi.c:crypto_stats_decompress
  - crypto/algapi.c:crypto_stats_decompress
  - crypto/algapi.c:crypto_stats_compress
  - crypto/algapi.c:crypto_stats_compress
  - crypto/algapi.c:crypto_stats_akcipher_verify
  - crypto/algapi.c:crypto_stats_akcipher_verify
  - crypto/algapi.c:crypto_stats_akcipher_sign
  - crypto/algapi.c:crypto_stats_akcipher_sign
  - crypto/algapi.c:crypto_stats_akcipher_decrypt
  - crypto/algapi.c:crypto_stats_akcipher_decrypt
  - crypto/algapi.c:crypto_stats_akcipher_encrypt
  - crypto/algapi.c:crypto_stats_akcipher_encrypt
  - crypto/algapi.c:crypto_stats_aead_decrypt
  - crypto/algapi.c:crypto_stats_aead_decrypt
  - crypto/algapi.c:crypto_stats_aead_encrypt
  - crypto/algapi.c:crypto_stats_aead_encrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_decrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_decrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_encrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_encrypt
  - crypto/algapi.c:crypto_remove_final
  - crypto/algapi.c:crypto_remove_final
```
```
In crypto/algboss.c (c00000000074f014)
Location: crypto/internal.h:94
Inline: True
Inline callers:
  - crypto/algboss.c:cryptomgr_notify
  - crypto/algboss.c:cryptomgr_notify
  - crypto/algboss.c:cryptomgr_probe
  - crypto/algboss.c:cryptomgr_probe
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
In crypto/api.c (ffffffe0003fd8be)
Location: crypto/internal.h:94
Inline: True
Inline callers:
  - crypto/api.c:crypto_larval_kill
  - crypto/api.c:crypto_larval_kill
  - crypto/api.c:crypto_mod_put
  - crypto/api.c:crypto_mod_put
```
```
In crypto/algapi.c (ffffffe0004006a4)
Location: crypto/internal.h:94
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_stats_rng_generate
  - crypto/algapi.c:crypto_stats_rng_generate
  - crypto/algapi.c:crypto_stats_rng_seed
  - crypto/algapi.c:crypto_stats_rng_seed
  - crypto/algapi.c:crypto_stats_kpp_compute_shared_secret
  - crypto/algapi.c:crypto_stats_kpp_compute_shared_secret
  - crypto/algapi.c:crypto_stats_kpp_generate_public_key
  - crypto/algapi.c:crypto_stats_kpp_generate_public_key
  - crypto/algapi.c:crypto_stats_kpp_set_secret
  - crypto/algapi.c:crypto_stats_kpp_set_secret
  - crypto/algapi.c:crypto_stats_ahash_final
  - crypto/algapi.c:crypto_stats_ahash_final
  - crypto/algapi.c:crypto_stats_ahash_update
  - crypto/algapi.c:crypto_stats_ahash_update
  - crypto/algapi.c:crypto_stats_decompress
  - crypto/algapi.c:crypto_stats_decompress
  - crypto/algapi.c:crypto_stats_compress
  - crypto/algapi.c:crypto_stats_compress
  - crypto/algapi.c:crypto_stats_akcipher_verify
  - crypto/algapi.c:crypto_stats_akcipher_verify
  - crypto/algapi.c:crypto_stats_akcipher_sign
  - crypto/algapi.c:crypto_stats_akcipher_sign
  - crypto/algapi.c:crypto_stats_akcipher_decrypt
  - crypto/algapi.c:crypto_stats_akcipher_decrypt
  - crypto/algapi.c:crypto_stats_akcipher_encrypt
  - crypto/algapi.c:crypto_stats_akcipher_encrypt
  - crypto/algapi.c:crypto_stats_aead_decrypt
  - crypto/algapi.c:crypto_stats_aead_decrypt
  - crypto/algapi.c:crypto_stats_aead_encrypt
  - crypto/algapi.c:crypto_stats_aead_encrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_decrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_decrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_encrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_encrypt
  - crypto/algapi.c:crypto_remove_final
  - crypto/algapi.c:crypto_remove_final
```
```
In crypto/algboss.c (ffffffe000409a72)
Location: crypto/internal.h:94
Inline: True
Inline callers:
  - crypto/algboss.c:cryptomgr_notify
  - crypto/algboss.c:cryptomgr_notify
  - crypto/algboss.c:cryptomgr_probe
  - crypto/algboss.c:cryptomgr_probe
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void crypto_alg_put(struct crypto_alg *alg);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff814b6e82)
Location: crypto/internal.h:94
Inline: True
Inline callers:
  - crypto/api.c:crypto_has_alg
  - crypto/api.c:crypto_has_alg
  - crypto/api.c:crypto_destroy_tfm
  - crypto/api.c:crypto_destroy_tfm
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_base
  - crypto/api.c:crypto_alloc_base
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_alg_lookup
  - crypto/api.c:crypto_alg_lookup
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:crypto_larval_kill
  - crypto/api.c:crypto_larval_kill
  - crypto/api.c:__crypto_alg_lookup
  - crypto/api.c:__crypto_alg_lookup
```
```
In crypto/algapi.c (ffffffff814b8fa7)
Location: crypto/internal.h:94
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_stats_skcipher_decrypt
  - crypto/algapi.c:crypto_stats_skcipher_decrypt
  - crypto/algapi.c:crypto_stats_skcipher_encrypt
  - crypto/algapi.c:crypto_stats_skcipher_encrypt
  - crypto/algapi.c:crypto_stats_rng_generate
  - crypto/algapi.c:crypto_stats_rng_generate
  - crypto/algapi.c:crypto_stats_rng_seed
  - crypto/algapi.c:crypto_stats_rng_seed
  - crypto/algapi.c:crypto_stats_kpp_compute_shared_secret
  - crypto/algapi.c:crypto_stats_kpp_compute_shared_secret
  - crypto/algapi.c:crypto_stats_kpp_generate_public_key
  - crypto/algapi.c:crypto_stats_kpp_generate_public_key
  - crypto/algapi.c:crypto_stats_kpp_set_secret
  - crypto/algapi.c:crypto_stats_kpp_set_secret
  - crypto/algapi.c:crypto_stats_ahash_final
  - crypto/algapi.c:crypto_stats_ahash_final
  - crypto/algapi.c:crypto_stats_ahash_update
  - crypto/algapi.c:crypto_stats_ahash_update
  - crypto/algapi.c:crypto_stats_decompress
  - crypto/algapi.c:crypto_stats_decompress
  - crypto/algapi.c:crypto_stats_compress
  - crypto/algapi.c:crypto_stats_compress
  - crypto/algapi.c:crypto_stats_akcipher_verify
  - crypto/algapi.c:crypto_stats_akcipher_verify
  - crypto/algapi.c:crypto_stats_akcipher_sign
  - crypto/algapi.c:crypto_stats_akcipher_sign
  - crypto/algapi.c:crypto_stats_akcipher_decrypt
  - crypto/algapi.c:crypto_stats_akcipher_decrypt
  - crypto/algapi.c:crypto_stats_akcipher_encrypt
  - crypto/algapi.c:crypto_stats_akcipher_encrypt
  - crypto/algapi.c:crypto_stats_aead_decrypt
  - crypto/algapi.c:crypto_stats_aead_decrypt
  - crypto/algapi.c:crypto_stats_aead_encrypt
  - crypto/algapi.c:crypto_stats_aead_encrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_decrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_decrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_encrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_encrypt
  - crypto/algapi.c:crypto_remove_final
  - crypto/algapi.c:crypto_remove_final
```
```
In crypto/algboss.c (ffffffff814c2374)
Location: crypto/internal.h:94
Inline: True
Inline callers:
  - crypto/algboss.c:cryptomgr_probe
  - crypto/algboss.c:cryptomgr_probe
Direct callers:
  - crypto/algboss.c:cryptomgr_notify
```
**Symbols:**

```
ffffffff814c1d50-ffffffff814c1d74: crypto_alg_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void crypto_alg_put(struct crypto_alg *alg);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff814a78a2)
Location: crypto/internal.h:94
Inline: True
Inline callers:
  - crypto/api.c:crypto_has_alg
  - crypto/api.c:crypto_has_alg
  - crypto/api.c:crypto_destroy_tfm
  - crypto/api.c:crypto_destroy_tfm
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_base
  - crypto/api.c:crypto_alloc_base
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_alg_lookup
  - crypto/api.c:crypto_alg_lookup
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:crypto_larval_kill
  - crypto/api.c:crypto_larval_kill
  - crypto/api.c:__crypto_alg_lookup
  - crypto/api.c:__crypto_alg_lookup
```
```
In crypto/algapi.c (ffffffff814a99c7)
Location: crypto/internal.h:94
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_stats_skcipher_decrypt
  - crypto/algapi.c:crypto_stats_skcipher_decrypt
  - crypto/algapi.c:crypto_stats_skcipher_encrypt
  - crypto/algapi.c:crypto_stats_skcipher_encrypt
  - crypto/algapi.c:crypto_stats_rng_generate
  - crypto/algapi.c:crypto_stats_rng_generate
  - crypto/algapi.c:crypto_stats_rng_seed
  - crypto/algapi.c:crypto_stats_rng_seed
  - crypto/algapi.c:crypto_stats_kpp_compute_shared_secret
  - crypto/algapi.c:crypto_stats_kpp_compute_shared_secret
  - crypto/algapi.c:crypto_stats_kpp_generate_public_key
  - crypto/algapi.c:crypto_stats_kpp_generate_public_key
  - crypto/algapi.c:crypto_stats_kpp_set_secret
  - crypto/algapi.c:crypto_stats_kpp_set_secret
  - crypto/algapi.c:crypto_stats_ahash_final
  - crypto/algapi.c:crypto_stats_ahash_final
  - crypto/algapi.c:crypto_stats_ahash_update
  - crypto/algapi.c:crypto_stats_ahash_update
  - crypto/algapi.c:crypto_stats_decompress
  - crypto/algapi.c:crypto_stats_decompress
  - crypto/algapi.c:crypto_stats_compress
  - crypto/algapi.c:crypto_stats_compress
  - crypto/algapi.c:crypto_stats_akcipher_verify
  - crypto/algapi.c:crypto_stats_akcipher_verify
  - crypto/algapi.c:crypto_stats_akcipher_sign
  - crypto/algapi.c:crypto_stats_akcipher_sign
  - crypto/algapi.c:crypto_stats_akcipher_decrypt
  - crypto/algapi.c:crypto_stats_akcipher_decrypt
  - crypto/algapi.c:crypto_stats_akcipher_encrypt
  - crypto/algapi.c:crypto_stats_akcipher_encrypt
  - crypto/algapi.c:crypto_stats_aead_decrypt
  - crypto/algapi.c:crypto_stats_aead_decrypt
  - crypto/algapi.c:crypto_stats_aead_encrypt
  - crypto/algapi.c:crypto_stats_aead_encrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_decrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_decrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_encrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_encrypt
  - crypto/algapi.c:crypto_remove_final
  - crypto/algapi.c:crypto_remove_final
```
```
In crypto/algboss.c (ffffffff814b2d94)
Location: crypto/internal.h:94
Inline: True
Inline callers:
  - crypto/algboss.c:cryptomgr_probe
  - crypto/algboss.c:cryptomgr_probe
Direct callers:
  - crypto/algboss.c:cryptomgr_notify
```
**Symbols:**

```
ffffffff814b2770-ffffffff814b2794: crypto_alg_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void crypto_alg_put(struct crypto_alg *alg);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff814b2f12)
Location: crypto/internal.h:94
Inline: True
Inline callers:
  - crypto/api.c:crypto_has_alg
  - crypto/api.c:crypto_has_alg
  - crypto/api.c:crypto_destroy_tfm
  - crypto/api.c:crypto_destroy_tfm
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_base
  - crypto/api.c:crypto_alloc_base
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_alg_lookup
  - crypto/api.c:crypto_alg_lookup
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:crypto_larval_kill
  - crypto/api.c:crypto_larval_kill
  - crypto/api.c:__crypto_alg_lookup
  - crypto/api.c:__crypto_alg_lookup
```
```
In crypto/algapi.c (ffffffff814b5037)
Location: crypto/internal.h:94
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_stats_skcipher_decrypt
  - crypto/algapi.c:crypto_stats_skcipher_decrypt
  - crypto/algapi.c:crypto_stats_skcipher_encrypt
  - crypto/algapi.c:crypto_stats_skcipher_encrypt
  - crypto/algapi.c:crypto_stats_rng_generate
  - crypto/algapi.c:crypto_stats_rng_generate
  - crypto/algapi.c:crypto_stats_rng_seed
  - crypto/algapi.c:crypto_stats_rng_seed
  - crypto/algapi.c:crypto_stats_kpp_compute_shared_secret
  - crypto/algapi.c:crypto_stats_kpp_compute_shared_secret
  - crypto/algapi.c:crypto_stats_kpp_generate_public_key
  - crypto/algapi.c:crypto_stats_kpp_generate_public_key
  - crypto/algapi.c:crypto_stats_kpp_set_secret
  - crypto/algapi.c:crypto_stats_kpp_set_secret
  - crypto/algapi.c:crypto_stats_ahash_final
  - crypto/algapi.c:crypto_stats_ahash_final
  - crypto/algapi.c:crypto_stats_ahash_update
  - crypto/algapi.c:crypto_stats_ahash_update
  - crypto/algapi.c:crypto_stats_decompress
  - crypto/algapi.c:crypto_stats_decompress
  - crypto/algapi.c:crypto_stats_compress
  - crypto/algapi.c:crypto_stats_compress
  - crypto/algapi.c:crypto_stats_akcipher_verify
  - crypto/algapi.c:crypto_stats_akcipher_verify
  - crypto/algapi.c:crypto_stats_akcipher_sign
  - crypto/algapi.c:crypto_stats_akcipher_sign
  - crypto/algapi.c:crypto_stats_akcipher_decrypt
  - crypto/algapi.c:crypto_stats_akcipher_decrypt
  - crypto/algapi.c:crypto_stats_akcipher_encrypt
  - crypto/algapi.c:crypto_stats_akcipher_encrypt
  - crypto/algapi.c:crypto_stats_aead_decrypt
  - crypto/algapi.c:crypto_stats_aead_decrypt
  - crypto/algapi.c:crypto_stats_aead_encrypt
  - crypto/algapi.c:crypto_stats_aead_encrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_decrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_decrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_encrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_encrypt
  - crypto/algapi.c:crypto_remove_final
  - crypto/algapi.c:crypto_remove_final
```
```
In crypto/algboss.c (ffffffff814be404)
Location: crypto/internal.h:94
Inline: True
Inline callers:
  - crypto/algboss.c:cryptomgr_probe
  - crypto/algboss.c:cryptomgr_probe
Direct callers:
  - crypto/algboss.c:cryptomgr_notify
```
**Symbols:**

```
ffffffff814bdde0-ffffffff814bde04: crypto_alg_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void crypto_alg_put(struct crypto_alg *alg);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff814cb992)
Location: crypto/internal.h:94
Inline: True
Inline callers:
  - crypto/api.c:crypto_has_alg
  - crypto/api.c:crypto_has_alg
  - crypto/api.c:crypto_destroy_tfm
  - crypto/api.c:crypto_destroy_tfm
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_base
  - crypto/api.c:crypto_alloc_base
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_alg_lookup
  - crypto/api.c:crypto_alg_lookup
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:crypto_larval_kill
  - crypto/api.c:crypto_larval_kill
  - crypto/api.c:__crypto_alg_lookup
  - crypto/api.c:__crypto_alg_lookup
```
```
In crypto/algapi.c (ffffffff814cdab7)
Location: crypto/internal.h:94
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_stats_skcipher_decrypt
  - crypto/algapi.c:crypto_stats_skcipher_decrypt
  - crypto/algapi.c:crypto_stats_skcipher_encrypt
  - crypto/algapi.c:crypto_stats_skcipher_encrypt
  - crypto/algapi.c:crypto_stats_rng_generate
  - crypto/algapi.c:crypto_stats_rng_generate
  - crypto/algapi.c:crypto_stats_rng_seed
  - crypto/algapi.c:crypto_stats_rng_seed
  - crypto/algapi.c:crypto_stats_kpp_compute_shared_secret
  - crypto/algapi.c:crypto_stats_kpp_compute_shared_secret
  - crypto/algapi.c:crypto_stats_kpp_generate_public_key
  - crypto/algapi.c:crypto_stats_kpp_generate_public_key
  - crypto/algapi.c:crypto_stats_kpp_set_secret
  - crypto/algapi.c:crypto_stats_kpp_set_secret
  - crypto/algapi.c:crypto_stats_ahash_final
  - crypto/algapi.c:crypto_stats_ahash_final
  - crypto/algapi.c:crypto_stats_ahash_update
  - crypto/algapi.c:crypto_stats_ahash_update
  - crypto/algapi.c:crypto_stats_decompress
  - crypto/algapi.c:crypto_stats_decompress
  - crypto/algapi.c:crypto_stats_compress
  - crypto/algapi.c:crypto_stats_compress
  - crypto/algapi.c:crypto_stats_akcipher_verify
  - crypto/algapi.c:crypto_stats_akcipher_verify
  - crypto/algapi.c:crypto_stats_akcipher_sign
  - crypto/algapi.c:crypto_stats_akcipher_sign
  - crypto/algapi.c:crypto_stats_akcipher_decrypt
  - crypto/algapi.c:crypto_stats_akcipher_decrypt
  - crypto/algapi.c:crypto_stats_akcipher_encrypt
  - crypto/algapi.c:crypto_stats_akcipher_encrypt
  - crypto/algapi.c:crypto_stats_aead_decrypt
  - crypto/algapi.c:crypto_stats_aead_decrypt
  - crypto/algapi.c:crypto_stats_aead_encrypt
  - crypto/algapi.c:crypto_stats_aead_encrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_decrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_decrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_encrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_encrypt
  - crypto/algapi.c:crypto_remove_final
  - crypto/algapi.c:crypto_remove_final
```
```
In crypto/algboss.c (ffffffff814d6ed4)
Location: crypto/internal.h:94
Inline: True
Inline callers:
  - crypto/algboss.c:cryptomgr_probe
  - crypto/algboss.c:cryptomgr_probe
Direct callers:
  - crypto/algboss.c:cryptomgr_notify
```
**Symbols:**

```
ffffffff814d68b0-ffffffff814d68d4: crypto_alg_put (STB_LOCAL)
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
