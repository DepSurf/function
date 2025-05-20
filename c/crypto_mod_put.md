# Function: <code>crypto_mod_put</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void crypto_mod_put(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff8139c37e)
Location: crypto/api.c:45
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_destroy_tfm
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:__crypto_alg_lookup
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_has_alg
  - crypto/api.c:crypto_alloc_base
Direct callers:
  - crypto/algapi.c:crypto_grab_spawn
  - crypto/algapi.c:crypto_register_instance
  - crypto/algapi.c:crypto_spawn_tfm
  - crypto/algapi.c:crypto_spawn_tfm2
  - crypto/ablkcipher.c:crypto_givcipher_default
  - crypto/ablkcipher.c:crypto_givcipher_default
  - crypto/ablkcipher.c:crypto_lookup_skcipher
  - crypto/ablkcipher.c:crypto_lookup_skcipher
  - crypto/ablkcipher.c:crypto_grab_skcipher
  - crypto/ablkcipher.c:crypto_alloc_ablkcipher
  - crypto/blkcipher.c:skcipher_geniv_alloc
  - crypto/shash.c:crypto_init_shash_ops
  - crypto/shash.c:crypto_init_shash_ops_async
```
**Symbols:**

```
ffffffff8139c410-ffffffff8139c44b: crypto_mod_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void crypto_mod_put(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff813d9977)
Location: crypto/api.c:45
Inline: True
Inline callers:
  - crypto/api.c:crypto_has_alg
  - crypto/api.c:crypto_destroy_tfm
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_base
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:__crypto_alg_lookup
Direct callers:
  - crypto/algapi.c:crypto_type_has_alg
  - crypto/algapi.c:crypto_spawn_tfm2
  - crypto/algapi.c:crypto_spawn_tfm
  - crypto/algapi.c:crypto_grab_spawn
  - crypto/algapi.c:crypto_register_instance
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/shash.c:crypto_init_shash_ops_async
```
**Symbols:**

```
ffffffff813d9310-ffffffff813d9340: crypto_mod_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void crypto_mod_put(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff813f12a7)
Location: crypto/api.c:45
Inline: True
Inline callers:
  - crypto/api.c:crypto_has_alg
  - crypto/api.c:crypto_destroy_tfm
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_base
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:__crypto_alg_lookup
Direct callers:
  - crypto/algapi.c:crypto_type_has_alg
  - crypto/algapi.c:crypto_spawn_tfm2
  - crypto/algapi.c:crypto_spawn_tfm
  - crypto/algapi.c:crypto_grab_spawn
  - crypto/algapi.c:crypto_register_instance
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/scompress.c:crypto_init_scomp_ops_async
```
**Symbols:**

```
ffffffff813f0c20-ffffffff813f0c50: crypto_mod_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void crypto_mod_put(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff813fd547)
Location: crypto/api.c:45
Inline: True
Inline callers:
  - crypto/api.c:crypto_has_alg
  - crypto/api.c:crypto_destroy_tfm
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_base
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:__crypto_alg_lookup
Direct callers:
  - crypto/algapi.c:crypto_type_has_alg
  - crypto/algapi.c:crypto_spawn_tfm2
  - crypto/algapi.c:crypto_spawn_tfm
  - crypto/algapi.c:crypto_grab_spawn
  - crypto/algapi.c:crypto_register_instance
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/scompress.c:crypto_init_scomp_ops_async
```
**Symbols:**

```
ffffffff813fceb0-ffffffff813fcee0: crypto_mod_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void crypto_mod_put(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff81425ac7)
Location: crypto/api.c:46
Inline: True
Inline callers:
  - crypto/api.c:crypto_has_alg
  - crypto/api.c:crypto_destroy_tfm
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_base
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:__crypto_alg_lookup
Direct callers:
  - crypto/algapi.c:crypto_type_has_alg
  - crypto/algapi.c:crypto_spawn_tfm2
  - crypto/algapi.c:crypto_spawn_tfm
  - crypto/algapi.c:crypto_grab_spawn
  - crypto/algapi.c:crypto_register_instance
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/scompress.c:crypto_init_scomp_ops_async
  - crypto/gcm.c:crypto_gcm_create_common
```
**Symbols:**

```
ffffffff81425400-ffffffff81425433: crypto_mod_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void crypto_mod_put(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff81458940)
Location: crypto/api.c:46
Inline: True
Inline callers:
  - crypto/api.c:crypto_has_alg
  - crypto/api.c:crypto_destroy_tfm
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_base
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_alg_lookup
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:__crypto_alg_lookup
Direct callers:
  - crypto/algapi.c:crypto_type_has_alg
  - crypto/algapi.c:crypto_spawn_tfm2
  - crypto/algapi.c:crypto_spawn_tfm
  - crypto/algapi.c:crypto_grab_spawn
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/scompress.c:crypto_init_scomp_ops_async
  - crypto/gcm.c:crypto_gcm_create_common
```
**Symbols:**

```
ffffffff81458240-ffffffff81458279: crypto_mod_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void crypto_mod_put(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff81475e80)
Location: crypto/api.c:46
Inline: True
Inline callers:
  - crypto/api.c:crypto_has_alg
  - crypto/api.c:crypto_destroy_tfm
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_base
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_alg_lookup
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:__crypto_alg_lookup
Direct callers:
  - crypto/algapi.c:crypto_type_has_alg
  - crypto/algapi.c:crypto_spawn_tfm2
  - crypto/algapi.c:crypto_spawn_tfm
  - crypto/algapi.c:crypto_grab_spawn
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/scompress.c:crypto_init_scomp_ops_async
  - crypto/gcm.c:crypto_gcm_create_common
```
**Symbols:**

```
ffffffff81475680-ffffffff814756b9: crypto_mod_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void crypto_mod_put(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff814a3c72)
Location: crypto/api.c:41
Inline: True
Inline callers:
  - crypto/api.c:crypto_has_alg
  - crypto/api.c:crypto_destroy_tfm
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_base
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_alg_lookup
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:__crypto_alg_lookup
Direct callers:
  - crypto/algapi.c:crypto_type_has_alg
  - crypto/algapi.c:crypto_spawn_tfm2
  - crypto/algapi.c:crypto_spawn_tfm
  - crypto/algapi.c:crypto_grab_spawn
  - crypto/skcipher.c:skcipher_alloc_instance_simple
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/scompress.c:crypto_init_scomp_ops_async
  - crypto/ecb.c:crypto_ecb_create
  - crypto/cbc.c:crypto_cbc_create
  - crypto/ctr.c:crypto_ctr_create
  - crypto/gcm.c:crypto_gcm_create_common
```
**Symbols:**

```
ffffffff814a33a0-ffffffff814a33e7: crypto_mod_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void crypto_mod_put(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff814be8a2)
Location: crypto/api.c:41
Inline: True
Inline callers:
  - crypto/api.c:crypto_has_alg
  - crypto/api.c:crypto_destroy_tfm
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_base
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_alg_lookup
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:__crypto_alg_lookup
Direct callers:
  - crypto/algapi.c:crypto_type_has_alg
  - crypto/algapi.c:crypto_spawn_tfm2
  - crypto/algapi.c:crypto_spawn_tfm
  - crypto/algapi.c:crypto_grab_spawn
  - crypto/skcipher.c:skcipher_alloc_instance_simple
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/scompress.c:crypto_init_scomp_ops_async
  - crypto/ecb.c:crypto_ecb_create
  - crypto/cbc.c:crypto_cbc_create
  - crypto/ctr.c:crypto_ctr_create
  - crypto/gcm.c:crypto_gcm_create_common
```
**Symbols:**

```
ffffffff814bdfb0-ffffffff814bdff7: crypto_mod_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void crypto_mod_put(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff8151e820)
Location: crypto/api.c:41
Inline: False
Direct callers:
  - crypto/api.c:crypto_has_alg
  - crypto/api.c:crypto_destroy_tfm
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_base
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_alg_lookup
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:__crypto_alg_lookup
  - crypto/algapi.c:crypto_type_has_alg
  - crypto/algapi.c:crypto_spawn_tfm2
  - crypto/algapi.c:crypto_spawn_tfm
  - crypto/algapi.c:crypto_grab_spawn
  - crypto/algapi.c:crypto_register_instance
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/scompress.c:crypto_init_scomp_ops_async
```
**Symbols:**

```
ffffffff8151e820-ffffffff8151e891: crypto_mod_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void crypto_mod_put(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff8153b5e0)
Location: crypto/api.c:41
Inline: False
Direct callers:
  - crypto/api.c:crypto_has_alg
  - crypto/api.c:crypto_destroy_tfm
  - crypto/api.c:crypto_alloc_tfm_node
  - crypto/api.c:crypto_alloc_base
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_alg_lookup
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:__crypto_alg_lookup
  - crypto/algapi.c:crypto_type_has_alg
  - crypto/algapi.c:crypto_spawn_tfm2
  - crypto/algapi.c:crypto_spawn_tfm
  - crypto/algapi.c:crypto_grab_spawn
  - crypto/algapi.c:crypto_register_instance
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/scompress.c:crypto_init_scomp_ops_async
```
**Symbols:**

```
ffffffff8153b5e0-ffffffff8153b651: crypto_mod_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void crypto_mod_put(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff81543cd0)
Location: crypto/api.c:41
Inline: False
Direct callers:
  - crypto/api.c:crypto_has_alg
  - crypto/api.c:crypto_alloc_tfm_node
  - crypto/api.c:crypto_alloc_base
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_alg_lookup
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:__crypto_alg_lookup
  - crypto/algapi.c:crypto_type_has_alg
  - crypto/algapi.c:crypto_spawn_tfm2
  - crypto/algapi.c:crypto_spawn_tfm
  - crypto/algapi.c:crypto_grab_spawn
  - crypto/algapi.c:crypto_register_instance
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/scompress.c:crypto_init_scomp_ops_async
```
**Symbols:**

```
ffffffff81543cd0-ffffffff81543d41: crypto_mod_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void crypto_mod_put(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff815a4470)
Location: crypto/api.c:41
Inline: False
Direct callers:
  - crypto/api.c:crypto_has_alg
  - crypto/api.c:crypto_alloc_tfm_node
  - crypto/api.c:crypto_alloc_base
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_alg_lookup
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:crypto_larval_destroy
  - crypto/api.c:__crypto_alg_lookup
  - crypto/algapi.c:crypto_type_has_alg
  - crypto/algapi.c:crypto_spawn_tfm2
  - crypto/algapi.c:crypto_spawn_tfm
  - crypto/algapi.c:crypto_grab_spawn
  - crypto/algapi.c:crypto_register_instance
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/scompress.c:crypto_init_scomp_ops_async
```
**Symbols:**

```
ffffffff815a4470-ffffffff815a44e1: crypto_mod_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void crypto_mod_put(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff8164ae60)
Location: crypto/api.c:45
Inline: False
Direct callers:
  - crypto/api.c:crypto_has_alg
  - crypto/api.c:crypto_destroy_tfm
  - crypto/api.c:crypto_alloc_tfm_node
  - crypto/api.c:crypto_alloc_base
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_alg_lookup
  - crypto/api.c:crypto_alg_lookup
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:crypto_larval_destroy
  - crypto/api.c:__crypto_alg_lookup
  - crypto/algapi.c:crypto_type_has_alg
  - crypto/algapi.c:crypto_spawn_tfm2
  - crypto/algapi.c:crypto_spawn_tfm
  - crypto/algapi.c:crypto_grab_spawn
  - crypto/algapi.c:crypto_register_instance
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/scompress.c:crypto_init_scomp_ops_async
```
**Symbols:**

```
ffffffff8164ae60-ffffffff8164aef4: crypto_mod_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void crypto_mod_put(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff81704050)
Location: crypto/api.c:47
Inline: False
Direct callers:
  - crypto/api.c:crypto_has_alg
  - crypto/api.c:crypto_destroy_tfm
  - crypto/api.c:crypto_alloc_tfm_node
  - crypto/api.c:crypto_alloc_base
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_alg_lookup
  - crypto/api.c:crypto_alg_lookup
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:crypto_larval_destroy
  - crypto/api.c:__crypto_alg_lookup
  - crypto/algapi.c:crypto_type_has_alg
  - crypto/algapi.c:crypto_spawn_tfm2
  - crypto/algapi.c:crypto_spawn_tfm
  - crypto/algapi.c:crypto_grab_spawn
  - crypto/algapi.c:crypto_register_instance
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/scompress.c:crypto_init_scomp_ops_async
```
**Symbols:**

```
ffffffff81704050-ffffffff817040e4: crypto_mod_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void crypto_mod_put(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff8173e170)
Location: crypto/api.c:47
Inline: False
Direct callers:
  - crypto/api.c:crypto_has_alg
  - crypto/api.c:crypto_alloc_tfm_node
  - crypto/api.c:crypto_clone_tfm
  - crypto/api.c:crypto_alloc_base
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_alg_lookup
  - crypto/api.c:crypto_alg_lookup
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:crypto_larval_destroy
  - crypto/api.c:__crypto_alg_lookup
  - crypto/cipher.c:crypto_clone_cipher
  - crypto/algapi.c:crypto_type_has_alg
  - crypto/algapi.c:crypto_spawn_tfm2
  - crypto/algapi.c:crypto_spawn_tfm
  - crypto/algapi.c:crypto_grab_spawn
  - crypto/algapi.c:crypto_register_instance
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/akcipher.c:crypto_init_akcipher_ops_sig
  - crypto/scompress.c:crypto_init_scomp_ops_async
```
**Symbols:**

```
ffffffff8173e170-ffffffff8173e204: crypto_mod_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void crypto_mod_put(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff8177eff0)
Location: crypto/api.c:47
Inline: False
Direct callers:
  - crypto/api.c:crypto_has_alg
  - crypto/api.c:crypto_alloc_tfm_node
  - crypto/api.c:crypto_clone_tfm
  - crypto/api.c:crypto_alloc_base
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_alg_lookup
  - crypto/api.c:crypto_alg_lookup
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:crypto_larval_destroy
  - crypto/api.c:__crypto_alg_lookup
  - crypto/cipher.c:crypto_clone_cipher
  - crypto/algapi.c:crypto_type_has_alg
  - crypto/algapi.c:crypto_spawn_tfm2
  - crypto/algapi.c:crypto_spawn_tfm
  - crypto/algapi.c:crypto_grab_spawn
  - crypto/algapi.c:crypto_register_instance
  - crypto/lskcipher.c:crypto_init_lskcipher_ops_sg
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/akcipher.c:crypto_init_akcipher_ops_sig
  - crypto/scompress.c:crypto_init_scomp_ops_async
```
**Symbols:**

```
ffffffff8177eff0-ffffffff8177f084: crypto_mod_put (STB_GLOBAL)
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
void crypto_mod_put(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffff8000105b78f8)
Location: crypto/api.c:41
Inline: True
Inline callers:
  - crypto/api.c:crypto_has_alg
  - crypto/api.c:crypto_destroy_tfm
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_base
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_alg_lookup
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:__crypto_alg_lookup
Direct callers:
  - crypto/algapi.c:crypto_type_has_alg
  - crypto/algapi.c:crypto_spawn_tfm2
  - crypto/algapi.c:crypto_spawn_tfm
  - crypto/algapi.c:crypto_grab_spawn
  - crypto/skcipher.c:skcipher_alloc_instance_simple
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/scompress.c:crypto_init_scomp_ops_async
  - crypto/ecb.c:crypto_ecb_create
  - crypto/cbc.c:crypto_cbc_create
  - crypto/ctr.c:crypto_ctr_create
  - crypto/gcm.c:crypto_gcm_create_common
```
**Symbols:**

```
ffff8000105b6f38-ffff8000105b6f88: crypto_mod_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void crypto_mod_put(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/api.c (c0766568)
Location: crypto/api.c:41
Inline: True
Inline callers:
  - crypto/api.c:crypto_has_alg
  - crypto/api.c:crypto_destroy_tfm
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_base
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_alg_lookup
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:__crypto_alg_lookup
Direct callers:
  - crypto/algapi.c:crypto_type_has_alg
  - crypto/algapi.c:crypto_spawn_tfm2
  - crypto/algapi.c:crypto_spawn_tfm
  - crypto/algapi.c:crypto_grab_spawn
  - crypto/skcipher.c:skcipher_alloc_instance_simple
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/scompress.c:crypto_init_scomp_ops_async
  - crypto/ecb.c:crypto_ecb_create
  - crypto/cbc.c:crypto_cbc_create
  - crypto/ctr.c:crypto_ctr_create
  - crypto/gcm.c:crypto_gcm_create_common
```
**Symbols:**

```
c0765e48-c0765e94: crypto_mod_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void crypto_mod_put(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/api.c (c00000000073c764)
Location: crypto/api.c:41
Inline: True
Inline callers:
  - crypto/api.c:crypto_has_alg
  - crypto/api.c:crypto_destroy_tfm
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_base
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_alg_lookup
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:crypto_larval_destroy
  - crypto/api.c:__crypto_alg_lookup
Direct callers:
  - crypto/algapi.c:crypto_type_has_alg
  - crypto/algapi.c:crypto_spawn_tfm2
  - crypto/algapi.c:crypto_spawn_tfm
  - crypto/algapi.c:crypto_grab_spawn
  - crypto/skcipher.c:skcipher_alloc_instance_simple
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/scompress.c:crypto_init_scomp_ops_async
  - crypto/ecb.c:crypto_ecb_create
  - crypto/cbc.c:crypto_cbc_create
  - crypto/ctr.c:crypto_ctr_create
  - crypto/gcm.c:crypto_gcm_create_common
```
**Symbols:**

```
c00000000073b620-c00000000073b6a8: crypto_mod_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void crypto_mod_put(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffe0003fda32)
Location: crypto/api.c:41
Inline: False
Direct callers:
  - crypto/api.c:crypto_has_alg
  - crypto/api.c:crypto_destroy_tfm
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_base
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_alg_lookup
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:__crypto_alg_lookup
  - crypto/algapi.c:crypto_type_has_alg
  - crypto/algapi.c:crypto_spawn_tfm2
  - crypto/algapi.c:crypto_spawn_tfm
  - crypto/algapi.c:crypto_grab_spawn
  - crypto/skcipher.c:skcipher_alloc_instance_simple
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/scompress.c:crypto_init_scomp_ops_async
  - crypto/ecb.c:crypto_ecb_create
  - crypto/cbc.c:crypto_cbc_create
  - crypto/ctr.c:crypto_ctr_create
  - crypto/gcm.c:crypto_gcm_create_common
```
**Symbols:**

```
ffffffe0003fda32-ffffffe0003fda82: crypto_mod_put (STB_GLOBAL)
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
void crypto_mod_put(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff814b6e82)
Location: crypto/api.c:41
Inline: True
Inline callers:
  - crypto/api.c:crypto_has_alg
  - crypto/api.c:crypto_destroy_tfm
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_base
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_alg_lookup
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:__crypto_alg_lookup
Direct callers:
  - crypto/algapi.c:crypto_type_has_alg
  - crypto/algapi.c:crypto_spawn_tfm2
  - crypto/algapi.c:crypto_spawn_tfm
  - crypto/algapi.c:crypto_grab_spawn
  - crypto/skcipher.c:skcipher_alloc_instance_simple
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/scompress.c:crypto_init_scomp_ops_async
  - crypto/ecb.c:crypto_ecb_create
  - crypto/cbc.c:crypto_cbc_create
  - crypto/ctr.c:crypto_ctr_create
  - crypto/gcm.c:crypto_gcm_create_common
```
**Symbols:**

```
ffffffff814b6590-ffffffff814b65d7: crypto_mod_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void crypto_mod_put(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff814a78a2)
Location: crypto/api.c:41
Inline: True
Inline callers:
  - crypto/api.c:crypto_has_alg
  - crypto/api.c:crypto_destroy_tfm
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_base
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_alg_lookup
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:__crypto_alg_lookup
Direct callers:
  - crypto/algapi.c:crypto_type_has_alg
  - crypto/algapi.c:crypto_spawn_tfm2
  - crypto/algapi.c:crypto_spawn_tfm
  - crypto/algapi.c:crypto_grab_spawn
  - crypto/skcipher.c:skcipher_alloc_instance_simple
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/scompress.c:crypto_init_scomp_ops_async
  - crypto/ecb.c:crypto_ecb_create
  - crypto/cbc.c:crypto_cbc_create
  - crypto/ctr.c:crypto_ctr_create
  - crypto/gcm.c:crypto_gcm_create_common
```
**Symbols:**

```
ffffffff814a6fb0-ffffffff814a6ff7: crypto_mod_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void crypto_mod_put(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff814b2f12)
Location: crypto/api.c:41
Inline: True
Inline callers:
  - crypto/api.c:crypto_has_alg
  - crypto/api.c:crypto_destroy_tfm
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_base
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_alg_lookup
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:__crypto_alg_lookup
Direct callers:
  - crypto/algapi.c:crypto_type_has_alg
  - crypto/algapi.c:crypto_spawn_tfm2
  - crypto/algapi.c:crypto_spawn_tfm
  - crypto/algapi.c:crypto_grab_spawn
  - crypto/skcipher.c:skcipher_alloc_instance_simple
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/scompress.c:crypto_init_scomp_ops_async
  - crypto/ecb.c:crypto_ecb_create
  - crypto/cbc.c:crypto_cbc_create
  - crypto/ctr.c:crypto_ctr_create
  - crypto/gcm.c:crypto_gcm_create_common
```
**Symbols:**

```
ffffffff814b2620-ffffffff814b2667: crypto_mod_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void crypto_mod_put(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff814cb992)
Location: crypto/api.c:41
Inline: True
Inline callers:
  - crypto/api.c:crypto_has_alg
  - crypto/api.c:crypto_destroy_tfm
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_base
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_alg_lookup
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:__crypto_alg_lookup
Direct callers:
  - crypto/algapi.c:crypto_type_has_alg
  - crypto/algapi.c:crypto_spawn_tfm2
  - crypto/algapi.c:crypto_spawn_tfm
  - crypto/algapi.c:crypto_grab_spawn
  - crypto/skcipher.c:skcipher_alloc_instance_simple
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/scompress.c:crypto_init_scomp_ops_async
  - crypto/ecb.c:crypto_ecb_create
  - crypto/cbc.c:crypto_cbc_create
  - crypto/ctr.c:crypto_ctr_create
  - crypto/gcm.c:crypto_gcm_create_common
```
**Symbols:**

```
ffffffff814cb0a0-ffffffff814cb0e7: crypto_mod_put (STB_GLOBAL)
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
