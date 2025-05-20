# Function: <code>crypto_unregister_alg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int crypto_unregister_alg(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff8139e270)
Location: crypto/algapi.c:390
Inline: True
Direct callers:
  - crypto/algapi.c:crypto_unregister_algs
  - crypto/algapi.c:crypto_register_algs
  - crypto/aead.c:crypto_register_aeads
  - crypto/aead.c:crypto_unregister_aeads
  - crypto/ahash.c:crypto_unregister_ahash
  - crypto/shash.c:crypto_register_shashes
  - crypto/shash.c:crypto_unregister_shashes
  - crypto/pcompress.c:crypto_unregister_pcomp
  - crypto/akcipher.c:crypto_unregister_akcipher
  - crypto/aes_generic.c:aes_fini
  - crypto/lzo.c:lzo_mod_fini
  - crypto/rng.c:crypto_register_rngs
  - crypto/rng.c:crypto_unregister_rngs
```
**Symbols:**

```
ffffffff8139e270-ffffffff8139e315: crypto_unregister_alg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int crypto_unregister_alg(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff813db1d0)
Location: crypto/algapi.c:389
Inline: True
Direct callers:
  - crypto/algapi.c:crypto_unregister_algs
  - crypto/algapi.c:crypto_register_algs
  - crypto/aead.c:crypto_unregister_aeads
  - crypto/aead.c:crypto_register_aeads
  - crypto/skcipher.c:crypto_unregister_skciphers
  - crypto/skcipher.c:crypto_register_skciphers
  - crypto/ahash.c:crypto_unregister_ahash
  - crypto/shash.c:crypto_unregister_shashes
  - crypto/shash.c:crypto_register_shashes
  - crypto/akcipher.c:crypto_unregister_akcipher
  - crypto/kpp.c:crypto_unregister_kpp
  - crypto/aes_generic.c:aes_fini
  - crypto/lzo.c:lzo_mod_fini
  - crypto/rng.c:crypto_unregister_rngs
  - crypto/rng.c:crypto_register_rngs
```
**Symbols:**

```
ffffffff813db1d0-ffffffff813db273: crypto_unregister_alg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int crypto_unregister_alg(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff813f2b10)
Location: crypto/algapi.c:390
Inline: True
Direct callers:
  - crypto/algapi.c:crypto_unregister_algs
  - crypto/algapi.c:crypto_register_algs
  - crypto/aead.c:crypto_unregister_aeads
  - crypto/aead.c:crypto_register_aeads
  - crypto/skcipher.c:crypto_unregister_skciphers
  - crypto/skcipher.c:crypto_register_skciphers
  - crypto/ahash.c:crypto_unregister_ahash
  - crypto/shash.c:crypto_unregister_shashes
  - crypto/shash.c:crypto_register_shashes
  - crypto/akcipher.c:crypto_unregister_akcipher
  - crypto/kpp.c:crypto_unregister_kpp
  - crypto/acompress.c:crypto_unregister_acomp
  - crypto/scompress.c:crypto_unregister_scomp
  - crypto/aes_generic.c:aes_fini
  - crypto/lzo.c:lzo_mod_fini
  - crypto/rng.c:crypto_unregister_rngs
  - crypto/rng.c:crypto_register_rngs
```
**Symbols:**

```
ffffffff813f2b10-ffffffff813f2bb3: crypto_unregister_alg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int crypto_unregister_alg(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff813fee30)
Location: crypto/algapi.c:390
Inline: True
Direct callers:
  - crypto/algapi.c:crypto_unregister_algs
  - crypto/algapi.c:crypto_register_algs
  - crypto/aead.c:crypto_unregister_aeads
  - crypto/aead.c:crypto_register_aeads
  - crypto/skcipher.c:crypto_unregister_skciphers
  - crypto/skcipher.c:crypto_register_skciphers
  - crypto/ahash.c:crypto_unregister_ahash
  - crypto/shash.c:crypto_unregister_shashes
  - crypto/shash.c:crypto_register_shashes
  - crypto/akcipher.c:crypto_unregister_akcipher
  - crypto/kpp.c:crypto_unregister_kpp
  - crypto/acompress.c:crypto_unregister_acomps
  - crypto/acompress.c:crypto_register_acomps
  - crypto/scompress.c:crypto_unregister_scomp
  - crypto/aes_generic.c:aes_fini
  - crypto/lzo.c:lzo_mod_fini
  - crypto/rng.c:crypto_unregister_rngs
  - crypto/rng.c:crypto_register_rngs
```
**Symbols:**

```
ffffffff813fee30-ffffffff813feed3: crypto_unregister_alg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int crypto_unregister_alg(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff814273f0)
Location: crypto/algapi.c:402
Inline: True
Direct callers:
  - crypto/algapi.c:crypto_unregister_algs
  - crypto/algapi.c:crypto_register_algs
  - crypto/aead.c:crypto_unregister_aeads
  - crypto/aead.c:crypto_register_aeads
  - crypto/skcipher.c:crypto_unregister_skciphers
  - crypto/skcipher.c:crypto_register_skciphers
  - crypto/ahash.c:crypto_unregister_ahashes
  - crypto/ahash.c:crypto_register_ahashes
  - crypto/shash.c:crypto_unregister_shashes
  - crypto/shash.c:crypto_register_shashes
  - crypto/akcipher.c:crypto_unregister_akcipher
  - crypto/kpp.c:crypto_unregister_kpp
  - crypto/acompress.c:crypto_unregister_acomps
  - crypto/acompress.c:crypto_register_acomps
  - crypto/scompress.c:crypto_unregister_scomps
  - crypto/scompress.c:crypto_register_scomps
  - crypto/aes_generic.c:aes_fini
  - crypto/lzo.c:lzo_mod_fini
  - crypto/rng.c:crypto_unregister_rngs
  - crypto/rng.c:crypto_register_rngs
```
**Symbols:**

```
ffffffff814273f0-ffffffff81427496: crypto_unregister_alg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int crypto_unregister_alg(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff8145a0e0)
Location: crypto/algapi.c:410
Inline: True
Direct callers:
  - crypto/algapi.c:crypto_unregister_algs
  - crypto/algapi.c:crypto_register_algs
  - crypto/aead.c:crypto_unregister_aeads
  - crypto/aead.c:crypto_register_aeads
  - crypto/skcipher.c:crypto_unregister_skciphers
  - crypto/skcipher.c:crypto_register_skciphers
  - crypto/ahash.c:crypto_unregister_ahashes
  - crypto/ahash.c:crypto_register_ahashes
  - crypto/shash.c:crypto_unregister_shashes
  - crypto/shash.c:crypto_register_shashes
  - crypto/akcipher.c:crypto_unregister_akcipher
  - crypto/kpp.c:crypto_unregister_kpp
  - crypto/acompress.c:crypto_unregister_acomps
  - crypto/acompress.c:crypto_register_acomps
  - crypto/scompress.c:crypto_unregister_scomps
  - crypto/scompress.c:crypto_register_scomps
  - crypto/aes_generic.c:aes_fini
  - crypto/deflate.c:deflate_mod_fini
  - crypto/deflate.c:deflate_mod_init
  - crypto/lzo.c:lzo_mod_fini
  - crypto/lzo.c:lzo_mod_init
  - crypto/rng.c:crypto_unregister_rngs
  - crypto/rng.c:crypto_register_rngs
```
**Symbols:**

```
ffffffff8145a0e0-ffffffff8145a1ac: crypto_unregister_alg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int crypto_unregister_alg(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff81477960)
Location: crypto/algapi.c:419
Inline: True
Direct callers:
  - crypto/algapi.c:crypto_unregister_algs
  - crypto/algapi.c:crypto_register_algs
  - crypto/aead.c:crypto_unregister_aeads
  - crypto/aead.c:crypto_register_aeads
  - crypto/skcipher.c:crypto_unregister_skciphers
  - crypto/skcipher.c:crypto_register_skciphers
  - crypto/ahash.c:crypto_unregister_ahashes
  - crypto/ahash.c:crypto_register_ahashes
  - crypto/shash.c:crypto_unregister_shashes
  - crypto/shash.c:crypto_register_shashes
  - crypto/akcipher.c:crypto_unregister_akcipher
  - crypto/kpp.c:crypto_unregister_kpp
  - crypto/acompress.c:crypto_unregister_acomps
  - crypto/acompress.c:crypto_register_acomps
  - crypto/scompress.c:crypto_unregister_scomps
  - crypto/scompress.c:crypto_register_scomps
  - crypto/aes_generic.c:aes_fini
  - crypto/deflate.c:deflate_mod_fini
  - crypto/deflate.c:deflate_mod_init
  - crypto/lzo.c:lzo_mod_fini
  - crypto/lzo.c:lzo_mod_init
  - crypto/rng.c:crypto_unregister_rngs
  - crypto/rng.c:crypto_register_rngs
```
**Symbols:**

```
ffffffff81477960-ffffffff81477a2c: crypto_unregister_alg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int crypto_unregister_alg(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff814a5600)
Location: crypto/algapi.c:400
Inline: True
Direct callers:
  - crypto/algapi.c:crypto_unregister_algs
  - crypto/algapi.c:crypto_register_algs
  - crypto/aead.c:crypto_unregister_aeads
  - crypto/aead.c:crypto_register_aeads
  - crypto/skcipher.c:crypto_unregister_skciphers
  - crypto/skcipher.c:crypto_register_skciphers
  - crypto/ahash.c:crypto_unregister_ahashes
  - crypto/ahash.c:crypto_register_ahashes
  - crypto/shash.c:crypto_unregister_shashes
  - crypto/shash.c:crypto_register_shashes
  - crypto/akcipher.c:crypto_unregister_akcipher
  - crypto/kpp.c:crypto_unregister_kpp
  - crypto/acompress.c:crypto_unregister_acomps
  - crypto/acompress.c:crypto_register_acomps
  - crypto/scompress.c:crypto_unregister_scomps
  - crypto/scompress.c:crypto_register_scomps
  - crypto/aes_generic.c:aes_fini
  - crypto/deflate.c:deflate_mod_fini
  - crypto/deflate.c:deflate_mod_init
  - crypto/lzo.c:lzo_mod_fini
  - crypto/lzo.c:lzo_mod_init
  - crypto/lzo-rle.c:lzorle_mod_fini
  - crypto/lzo-rle.c:lzorle_mod_init
  - crypto/rng.c:crypto_unregister_rngs
  - crypto/rng.c:crypto_register_rngs
```
**Symbols:**

```
ffffffff814a5600-ffffffff814a56d8: crypto_unregister_alg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int crypto_unregister_alg(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff814c02b0)
Location: crypto/algapi.c:418
Inline: True
Direct callers:
  - crypto/algapi.c:crypto_unregister_algs
  - crypto/algapi.c:crypto_register_algs
  - crypto/aead.c:crypto_unregister_aeads
  - crypto/aead.c:crypto_register_aeads
  - crypto/skcipher.c:crypto_unregister_skciphers
  - crypto/skcipher.c:crypto_register_skciphers
  - crypto/ahash.c:crypto_unregister_ahashes
  - crypto/ahash.c:crypto_register_ahashes
  - crypto/shash.c:crypto_unregister_shashes
  - crypto/shash.c:crypto_register_shashes
  - crypto/akcipher.c:crypto_unregister_akcipher
  - crypto/kpp.c:crypto_unregister_kpp
  - crypto/acompress.c:crypto_unregister_acomps
  - crypto/acompress.c:crypto_register_acomps
  - crypto/scompress.c:crypto_unregister_scomps
  - crypto/scompress.c:crypto_register_scomps
  - crypto/aes_generic.c:aes_fini
  - crypto/deflate.c:deflate_mod_fini
  - crypto/deflate.c:deflate_mod_init
  - crypto/lzo.c:lzo_mod_fini
  - crypto/lzo.c:lzo_mod_init
  - crypto/lzo-rle.c:lzorle_mod_fini
  - crypto/lzo-rle.c:lzorle_mod_init
  - crypto/rng.c:crypto_unregister_rngs
  - crypto/rng.c:crypto_register_rngs
```
**Symbols:**

```
ffffffff814c02b0-ffffffff814c0388: crypto_unregister_alg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void crypto_unregister_alg(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff81520900)
Location: crypto/algapi.c:447
Inline: False
Direct callers:
  - crypto/algapi.c:crypto_unregister_algs
  - crypto/algapi.c:crypto_register_algs
  - crypto/aead.c:crypto_unregister_aeads
  - crypto/aead.c:crypto_register_aeads
  - crypto/skcipher.c:crypto_unregister_skciphers
  - crypto/skcipher.c:crypto_register_skciphers
  - crypto/ahash.c:crypto_unregister_ahashes
  - crypto/ahash.c:crypto_register_ahashes
  - crypto/shash.c:crypto_unregister_shashes
  - crypto/shash.c:crypto_register_shashes
  - crypto/akcipher.c:crypto_unregister_akcipher
  - crypto/kpp.c:crypto_unregister_kpp
  - crypto/acompress.c:crypto_unregister_acomps
  - crypto/acompress.c:crypto_register_acomps
  - crypto/scompress.c:crypto_unregister_scomps
  - crypto/scompress.c:crypto_register_scomps
  - crypto/aes_generic.c:aes_fini
  - crypto/deflate.c:deflate_mod_fini
  - crypto/deflate.c:deflate_mod_init
  - crypto/lzo.c:lzo_mod_fini
  - crypto/lzo.c:lzo_mod_init
  - crypto/lzo-rle.c:lzorle_mod_fini
  - crypto/lzo-rle.c:lzorle_mod_init
  - crypto/rng.c:crypto_unregister_rngs
  - crypto/rng.c:crypto_register_rngs
```
**Symbols:**

```
ffffffff81520900-ffffffff815209e7: crypto_unregister_alg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void crypto_unregister_alg(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff8153d790)
Location: crypto/algapi.c:447
Inline: False
Direct callers:
  - crypto/algapi.c:crypto_unregister_algs
  - crypto/algapi.c:crypto_register_algs
  - crypto/aead.c:crypto_unregister_aeads
  - crypto/aead.c:crypto_register_aeads
  - crypto/skcipher.c:crypto_unregister_skciphers
  - crypto/skcipher.c:crypto_register_skciphers
  - crypto/ahash.c:crypto_unregister_ahashes
  - crypto/ahash.c:crypto_register_ahashes
  - crypto/shash.c:crypto_unregister_shashes
  - crypto/shash.c:crypto_register_shashes
  - crypto/akcipher.c:crypto_unregister_akcipher
  - crypto/kpp.c:crypto_unregister_kpp
  - crypto/acompress.c:crypto_unregister_acomps
  - crypto/acompress.c:crypto_register_acomps
  - crypto/scompress.c:crypto_unregister_scomps
  - crypto/scompress.c:crypto_register_scomps
  - crypto/aes_generic.c:aes_fini
  - crypto/deflate.c:deflate_mod_fini
  - crypto/deflate.c:deflate_mod_init
  - crypto/lzo.c:lzo_mod_fini
  - crypto/lzo.c:lzo_mod_init
  - crypto/lzo-rle.c:lzorle_mod_fini
  - crypto/lzo-rle.c:lzorle_mod_init
  - crypto/rng.c:crypto_unregister_rngs
  - crypto/rng.c:crypto_register_rngs
```
**Symbols:**

```
ffffffff8153d790-ffffffff8153d877: crypto_unregister_alg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void crypto_unregister_alg(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff81545e70)
Location: crypto/algapi.c:447
Inline: False
Direct callers:
  - crypto/algapi.c:crypto_unregister_algs
  - crypto/algapi.c:crypto_register_algs
  - crypto/aead.c:crypto_unregister_aeads
  - crypto/aead.c:crypto_register_aeads
  - crypto/skcipher.c:crypto_unregister_skciphers
  - crypto/skcipher.c:crypto_register_skciphers
  - crypto/ahash.c:crypto_unregister_ahashes
  - crypto/ahash.c:crypto_register_ahashes
  - crypto/shash.c:crypto_unregister_shashes
  - crypto/shash.c:crypto_register_shashes
  - crypto/akcipher.c:crypto_unregister_akcipher
  - crypto/kpp.c:crypto_unregister_kpp
  - crypto/acompress.c:crypto_unregister_acomps
  - crypto/acompress.c:crypto_register_acomps
  - crypto/scompress.c:crypto_unregister_scomps
  - crypto/scompress.c:crypto_register_scomps
  - crypto/aes_generic.c:aes_fini
  - crypto/deflate.c:deflate_mod_fini
  - crypto/deflate.c:deflate_mod_init
  - crypto/lzo.c:lzo_mod_fini
  - crypto/lzo.c:lzo_mod_init
  - crypto/lzo-rle.c:lzorle_mod_fini
  - crypto/lzo-rle.c:lzorle_mod_init
  - crypto/rng.c:crypto_unregister_rngs
  - crypto/rng.c:crypto_register_rngs
```
**Symbols:**

```
ffffffff81545e70-ffffffff81545f57: crypto_unregister_alg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void crypto_unregister_alg(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff815a62f0)
Location: crypto/algapi.c:447
Inline: False
Direct callers:
  - crypto/algapi.c:crypto_unregister_algs
  - crypto/algapi.c:crypto_register_algs
  - crypto/aead.c:crypto_unregister_aeads
  - crypto/aead.c:crypto_register_aeads
  - crypto/skcipher.c:crypto_unregister_skciphers
  - crypto/skcipher.c:crypto_register_skciphers
  - crypto/ahash.c:crypto_unregister_ahashes
  - crypto/ahash.c:crypto_register_ahashes
  - crypto/shash.c:crypto_unregister_shashes
  - crypto/shash.c:crypto_register_shashes
  - crypto/akcipher.c:crypto_unregister_akcipher
  - crypto/kpp.c:crypto_unregister_kpp
  - crypto/acompress.c:crypto_unregister_acomps
  - crypto/acompress.c:crypto_register_acomps
  - crypto/scompress.c:crypto_unregister_scomps
  - crypto/scompress.c:crypto_register_scomps
  - crypto/aes_generic.c:aes_fini
  - crypto/deflate.c:deflate_mod_fini
  - crypto/deflate.c:deflate_mod_init
  - crypto/lzo.c:lzo_mod_fini
  - crypto/lzo.c:lzo_mod_init
  - crypto/lzo-rle.c:lzorle_mod_fini
  - crypto/lzo-rle.c:lzorle_mod_init
  - crypto/rng.c:crypto_unregister_rngs
  - crypto/rng.c:crypto_register_rngs
```
**Symbols:**

```
ffffffff815a62f0-ffffffff815a63d7: crypto_unregister_alg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void crypto_unregister_alg(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff8164d6e0)
Location: crypto/algapi.c:463
Inline: False
Direct callers:
  - crypto/algapi.c:crypto_unregister_algs
  - crypto/algapi.c:crypto_register_algs
  - crypto/aead.c:crypto_unregister_aeads
  - crypto/aead.c:crypto_register_aeads
  - crypto/skcipher.c:crypto_unregister_skciphers
  - crypto/skcipher.c:crypto_register_skciphers
  - crypto/ahash.c:crypto_unregister_ahashes
  - crypto/ahash.c:crypto_register_ahashes
  - crypto/shash.c:crypto_unregister_shashes
  - crypto/shash.c:crypto_register_shashes
  - crypto/akcipher.c:crypto_unregister_akcipher
  - crypto/kpp.c:crypto_unregister_kpp
  - crypto/acompress.c:crypto_unregister_acomps
  - crypto/acompress.c:crypto_register_acomps
  - crypto/scompress.c:crypto_unregister_scomps
  - crypto/scompress.c:crypto_register_scomps
  - crypto/aes_generic.c:aes_fini
  - crypto/deflate.c:deflate_mod_fini
  - crypto/deflate.c:deflate_mod_init
  - crypto/lzo.c:lzo_mod_fini
  - crypto/lzo.c:lzo_mod_init
  - crypto/lzo-rle.c:lzorle_mod_fini
  - crypto/lzo-rle.c:lzorle_mod_init
  - crypto/rng.c:crypto_unregister_rngs
  - crypto/rng.c:crypto_register_rngs
```
**Symbols:**

```
ffffffff8164d6e0-ffffffff8164d7c6: crypto_unregister_alg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void crypto_unregister_alg(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff81706780)
Location: crypto/algapi.c:484
Inline: False
Direct callers:
  - crypto/algapi.c:crypto_unregister_algs
  - crypto/algapi.c:crypto_register_algs
  - crypto/aead.c:crypto_unregister_aeads
  - crypto/aead.c:crypto_register_aeads
  - crypto/skcipher.c:crypto_unregister_skciphers
  - crypto/skcipher.c:crypto_register_skciphers
  - crypto/ahash.c:crypto_unregister_ahashes
  - crypto/ahash.c:crypto_register_ahashes
  - crypto/shash.c:crypto_unregister_shashes
  - crypto/shash.c:crypto_register_shashes
  - crypto/akcipher.c:crypto_unregister_akcipher
  - crypto/kpp.c:crypto_unregister_kpp
  - crypto/acompress.c:crypto_unregister_acomps
  - crypto/acompress.c:crypto_register_acomps
  - crypto/scompress.c:crypto_unregister_scomps
  - crypto/scompress.c:crypto_register_scomps
  - crypto/aes_generic.c:aes_fini
  - crypto/deflate.c:deflate_mod_fini
  - crypto/deflate.c:deflate_mod_init
  - crypto/lzo.c:lzo_mod_fini
  - crypto/lzo.c:lzo_mod_init
  - crypto/lzo-rle.c:lzorle_mod_fini
  - crypto/lzo-rle.c:lzorle_mod_init
  - crypto/rng.c:crypto_unregister_rngs
  - crypto/rng.c:crypto_register_rngs
```
**Symbols:**

```
ffffffff81706780-ffffffff81706866: crypto_unregister_alg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void crypto_unregister_alg(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff81740830)
Location: crypto/algapi.c:494
Inline: False
Direct callers:
  - crypto/algapi.c:crypto_unregister_algs
  - crypto/algapi.c:crypto_register_algs
  - crypto/aead.c:crypto_unregister_aeads
  - crypto/aead.c:crypto_register_aeads
  - crypto/skcipher.c:crypto_unregister_skciphers
  - crypto/skcipher.c:crypto_register_skciphers
  - crypto/ahash.c:crypto_unregister_ahashes
  - crypto/ahash.c:crypto_register_ahashes
  - crypto/shash.c:crypto_unregister_shashes
  - crypto/shash.c:crypto_register_shashes
  - crypto/akcipher.c:crypto_unregister_akcipher
  - crypto/kpp.c:crypto_unregister_kpp
  - crypto/acompress.c:crypto_unregister_acomps
  - crypto/acompress.c:crypto_register_acomps
  - crypto/scompress.c:crypto_unregister_scomps
  - crypto/scompress.c:crypto_register_scomps
  - crypto/aes_generic.c:aes_fini
  - crypto/deflate.c:deflate_mod_fini
  - crypto/deflate.c:deflate_mod_init
  - crypto/lzo.c:lzo_mod_fini
  - crypto/lzo.c:lzo_mod_init
  - crypto/lzo-rle.c:lzorle_mod_fini
  - crypto/lzo-rle.c:lzorle_mod_init
  - crypto/rng.c:crypto_unregister_rngs
  - crypto/rng.c:crypto_register_rngs
```
**Symbols:**

```
ffffffff81740830-ffffffff81740918: crypto_unregister_alg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void crypto_unregister_alg(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff817816d0)
Location: crypto/algapi.c:495
Inline: False
Direct callers:
  - crypto/algapi.c:crypto_unregister_algs
  - crypto/algapi.c:crypto_register_algs
  - crypto/aead.c:crypto_unregister_aeads
  - crypto/aead.c:crypto_register_aeads
  - crypto/lskcipher.c:crypto_unregister_lskciphers
  - crypto/lskcipher.c:crypto_register_lskciphers
  - crypto/skcipher.c:crypto_unregister_skciphers
  - crypto/skcipher.c:crypto_register_skciphers
  - crypto/ahash.c:crypto_unregister_ahashes
  - crypto/ahash.c:crypto_register_ahashes
  - crypto/shash.c:crypto_unregister_shashes
  - crypto/shash.c:crypto_register_shashes
  - crypto/akcipher.c:crypto_unregister_akcipher
  - crypto/kpp.c:crypto_unregister_kpp
  - crypto/acompress.c:crypto_unregister_acomps
  - crypto/acompress.c:crypto_register_acomps
  - crypto/scompress.c:crypto_unregister_scomps
  - crypto/scompress.c:crypto_register_scomps
  - crypto/aes_generic.c:aes_fini
  - crypto/deflate.c:deflate_mod_fini
  - crypto/deflate.c:deflate_mod_init
  - crypto/lzo.c:lzo_mod_fini
  - crypto/lzo.c:lzo_mod_init
  - crypto/lzo-rle.c:lzorle_mod_fini
  - crypto/lzo-rle.c:lzorle_mod_init
  - crypto/rng.c:crypto_unregister_rngs
  - crypto/rng.c:crypto_register_rngs
```
**Symbols:**

```
ffffffff817816d0-ffffffff817817b8: crypto_unregister_alg (STB_GLOBAL)
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
int crypto_unregister_alg(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffff8000105b9928)
Location: crypto/algapi.c:418
Inline: True
Direct callers:
  - crypto/algapi.c:crypto_unregister_algs
  - crypto/algapi.c:crypto_register_algs
  - crypto/aead.c:crypto_unregister_aeads
  - crypto/aead.c:crypto_register_aeads
  - crypto/skcipher.c:crypto_unregister_skciphers
  - crypto/skcipher.c:crypto_register_skciphers
  - crypto/ahash.c:crypto_unregister_ahashes
  - crypto/ahash.c:crypto_register_ahashes
  - crypto/shash.c:crypto_unregister_shashes
  - crypto/shash.c:crypto_register_shashes
  - crypto/akcipher.c:crypto_unregister_akcipher
  - crypto/kpp.c:crypto_unregister_kpp
  - crypto/acompress.c:crypto_unregister_acomps
  - crypto/acompress.c:crypto_register_acomps
  - crypto/scompress.c:crypto_unregister_scomps
  - crypto/scompress.c:crypto_register_scomps
  - crypto/aes_generic.c:aes_fini
  - crypto/deflate.c:deflate_mod_fini
  - crypto/deflate.c:deflate_mod_init
  - crypto/lzo.c:lzo_mod_fini
  - crypto/lzo.c:lzo_mod_init
  - crypto/lzo-rle.c:lzorle_mod_fini
  - crypto/lzo-rle.c:lzorle_mod_init
  - crypto/rng.c:crypto_unregister_rngs
  - crypto/rng.c:crypto_register_rngs
```
**Symbols:**

```
ffff8000105b9928-ffff8000105b9a14: crypto_unregister_alg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int crypto_unregister_alg(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (c07682c0)
Location: crypto/algapi.c:418
Inline: True
Direct callers:
  - crypto/algapi.c:crypto_unregister_algs
  - crypto/algapi.c:crypto_register_algs
  - crypto/aead.c:crypto_unregister_aeads
  - crypto/aead.c:crypto_register_aeads
  - crypto/skcipher.c:crypto_unregister_skciphers
  - crypto/skcipher.c:crypto_register_skciphers
  - crypto/ahash.c:crypto_unregister_ahashes
  - crypto/ahash.c:crypto_register_ahashes
  - crypto/shash.c:crypto_unregister_shashes
  - crypto/shash.c:crypto_register_shashes
  - crypto/akcipher.c:crypto_unregister_akcipher
  - crypto/kpp.c:crypto_unregister_kpp
  - crypto/acompress.c:crypto_unregister_acomps
  - crypto/acompress.c:crypto_register_acomps
  - crypto/scompress.c:crypto_unregister_scomps
  - crypto/scompress.c:crypto_register_scomps
  - crypto/aes_generic.c:aes_fini
  - crypto/deflate.c:deflate_mod_fini
  - crypto/deflate.c:deflate_mod_init
  - crypto/lzo.c:lzo_mod_fini
  - crypto/lzo.c:lzo_mod_init
  - crypto/lzo-rle.c:lzorle_mod_fini
  - crypto/lzo-rle.c:lzorle_mod_init
  - crypto/rng.c:crypto_unregister_rngs
  - crypto/rng.c:crypto_register_rngs
```
**Symbols:**

```
c07682c0-c07683bc: crypto_unregister_alg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int crypto_unregister_alg(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (c00000000073fde0)
Location: crypto/algapi.c:418
Inline: False
Direct callers:
  - crypto/algapi.c:crypto_unregister_algs
  - crypto/algapi.c:crypto_register_algs
  - crypto/aead.c:crypto_unregister_aeads
  - crypto/aead.c:crypto_register_aeads
  - crypto/skcipher.c:crypto_unregister_skciphers
  - crypto/skcipher.c:crypto_register_skciphers
  - crypto/ahash.c:crypto_unregister_ahashes
  - crypto/ahash.c:crypto_register_ahashes
  - crypto/shash.c:crypto_unregister_shashes
  - crypto/shash.c:crypto_register_shashes
  - crypto/akcipher.c:crypto_unregister_akcipher
  - crypto/kpp.c:crypto_unregister_kpp
  - crypto/acompress.c:crypto_unregister_acomps
  - crypto/acompress.c:crypto_register_acomps
  - crypto/scompress.c:crypto_unregister_scomps
  - crypto/scompress.c:crypto_register_scomps
  - crypto/aes_generic.c:aes_fini
  - crypto/deflate.c:deflate_mod_fini
  - crypto/deflate.c:deflate_mod_init
  - crypto/lzo.c:lzo_mod_fini
  - crypto/lzo.c:lzo_mod_init
  - crypto/lzo-rle.c:lzorle_mod_fini
  - crypto/lzo-rle.c:lzorle_mod_init
  - crypto/rng.c:crypto_unregister_rngs
  - crypto/rng.c:crypto_register_rngs
```
**Symbols:**

```
c00000000073fde0-c00000000073ff1c: crypto_unregister_alg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int crypto_unregister_alg(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffe0003ffdb8)
Location: crypto/algapi.c:418
Inline: True
Direct callers:
  - crypto/algapi.c:crypto_unregister_algs
  - crypto/algapi.c:crypto_register_algs
  - crypto/aead.c:crypto_unregister_aeads
  - crypto/aead.c:crypto_register_aeads
  - crypto/skcipher.c:crypto_unregister_skciphers
  - crypto/skcipher.c:crypto_register_skciphers
  - crypto/ahash.c:crypto_unregister_ahashes
  - crypto/ahash.c:crypto_register_ahashes
  - crypto/shash.c:crypto_unregister_shashes
  - crypto/shash.c:crypto_register_shashes
  - crypto/akcipher.c:crypto_unregister_akcipher
  - crypto/kpp.c:crypto_unregister_kpp
  - crypto/acompress.c:crypto_unregister_acomps
  - crypto/acompress.c:crypto_register_acomps
  - crypto/scompress.c:crypto_unregister_scomps
  - crypto/scompress.c:crypto_register_scomps
  - crypto/aes_generic.c:aes_fini
  - crypto/deflate.c:deflate_mod_fini
  - crypto/deflate.c:deflate_mod_init
  - crypto/lzo.c:lzo_mod_fini
  - crypto/lzo.c:lzo_mod_init
  - crypto/lzo-rle.c:lzorle_mod_fini
  - crypto/lzo-rle.c:lzorle_mod_init
  - crypto/rng.c:crypto_unregister_rngs
  - crypto/rng.c:crypto_register_rngs
```
**Symbols:**

```
ffffffe0003ffdb8-ffffffe0003ffe6e: crypto_unregister_alg (STB_GLOBAL)
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
int crypto_unregister_alg(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff814b8890)
Location: crypto/algapi.c:418
Inline: True
Direct callers:
  - crypto/algapi.c:crypto_unregister_algs
  - crypto/algapi.c:crypto_register_algs
  - crypto/aead.c:crypto_unregister_aeads
  - crypto/aead.c:crypto_register_aeads
  - crypto/skcipher.c:crypto_unregister_skciphers
  - crypto/skcipher.c:crypto_register_skciphers
  - crypto/ahash.c:crypto_unregister_ahashes
  - crypto/ahash.c:crypto_register_ahashes
  - crypto/shash.c:crypto_unregister_shashes
  - crypto/shash.c:crypto_register_shashes
  - crypto/akcipher.c:crypto_unregister_akcipher
  - crypto/kpp.c:crypto_unregister_kpp
  - crypto/acompress.c:crypto_unregister_acomps
  - crypto/acompress.c:crypto_register_acomps
  - crypto/scompress.c:crypto_unregister_scomps
  - crypto/scompress.c:crypto_register_scomps
  - crypto/aes_generic.c:aes_fini
  - crypto/deflate.c:deflate_mod_fini
  - crypto/deflate.c:deflate_mod_init
  - crypto/lzo.c:lzo_mod_fini
  - crypto/lzo.c:lzo_mod_init
  - crypto/lzo-rle.c:lzorle_mod_fini
  - crypto/lzo-rle.c:lzorle_mod_init
  - crypto/rng.c:crypto_unregister_rngs
  - crypto/rng.c:crypto_register_rngs
```
**Symbols:**

```
ffffffff814b8890-ffffffff814b8968: crypto_unregister_alg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int crypto_unregister_alg(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff814a92b0)
Location: crypto/algapi.c:418
Inline: True
Direct callers:
  - crypto/algapi.c:crypto_unregister_algs
  - crypto/algapi.c:crypto_register_algs
  - crypto/aead.c:crypto_unregister_aeads
  - crypto/aead.c:crypto_register_aeads
  - crypto/skcipher.c:crypto_unregister_skciphers
  - crypto/skcipher.c:crypto_register_skciphers
  - crypto/ahash.c:crypto_unregister_ahashes
  - crypto/ahash.c:crypto_register_ahashes
  - crypto/shash.c:crypto_unregister_shashes
  - crypto/shash.c:crypto_register_shashes
  - crypto/akcipher.c:crypto_unregister_akcipher
  - crypto/kpp.c:crypto_unregister_kpp
  - crypto/acompress.c:crypto_unregister_acomps
  - crypto/acompress.c:crypto_register_acomps
  - crypto/scompress.c:crypto_unregister_scomps
  - crypto/scompress.c:crypto_register_scomps
  - crypto/aes_generic.c:aes_fini
  - crypto/deflate.c:deflate_mod_fini
  - crypto/deflate.c:deflate_mod_init
  - crypto/lzo.c:lzo_mod_fini
  - crypto/lzo.c:lzo_mod_init
  - crypto/lzo-rle.c:lzorle_mod_fini
  - crypto/lzo-rle.c:lzorle_mod_init
  - crypto/rng.c:crypto_unregister_rngs
  - crypto/rng.c:crypto_register_rngs
```
**Symbols:**

```
ffffffff814a92b0-ffffffff814a9388: crypto_unregister_alg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int crypto_unregister_alg(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff814b4920)
Location: crypto/algapi.c:418
Inline: True
Direct callers:
  - crypto/algapi.c:crypto_unregister_algs
  - crypto/algapi.c:crypto_register_algs
  - crypto/aead.c:crypto_unregister_aeads
  - crypto/aead.c:crypto_register_aeads
  - crypto/skcipher.c:crypto_unregister_skciphers
  - crypto/skcipher.c:crypto_register_skciphers
  - crypto/ahash.c:crypto_unregister_ahashes
  - crypto/ahash.c:crypto_register_ahashes
  - crypto/shash.c:crypto_unregister_shashes
  - crypto/shash.c:crypto_register_shashes
  - crypto/akcipher.c:crypto_unregister_akcipher
  - crypto/kpp.c:crypto_unregister_kpp
  - crypto/acompress.c:crypto_unregister_acomps
  - crypto/acompress.c:crypto_register_acomps
  - crypto/scompress.c:crypto_unregister_scomps
  - crypto/scompress.c:crypto_register_scomps
  - crypto/aes_generic.c:aes_fini
  - crypto/deflate.c:deflate_mod_fini
  - crypto/deflate.c:deflate_mod_init
  - crypto/lzo.c:lzo_mod_fini
  - crypto/lzo.c:lzo_mod_init
  - crypto/lzo-rle.c:lzorle_mod_fini
  - crypto/lzo-rle.c:lzorle_mod_init
  - crypto/rng.c:crypto_unregister_rngs
  - crypto/rng.c:crypto_register_rngs
```
**Symbols:**

```
ffffffff814b4920-ffffffff814b49f8: crypto_unregister_alg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int crypto_unregister_alg(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff814cd3a0)
Location: crypto/algapi.c:418
Inline: True
Direct callers:
  - crypto/algapi.c:crypto_unregister_algs
  - crypto/algapi.c:crypto_register_algs
  - crypto/aead.c:crypto_unregister_aeads
  - crypto/aead.c:crypto_register_aeads
  - crypto/skcipher.c:crypto_unregister_skciphers
  - crypto/skcipher.c:crypto_register_skciphers
  - crypto/ahash.c:crypto_unregister_ahashes
  - crypto/ahash.c:crypto_register_ahashes
  - crypto/shash.c:crypto_unregister_shashes
  - crypto/shash.c:crypto_register_shashes
  - crypto/akcipher.c:crypto_unregister_akcipher
  - crypto/kpp.c:crypto_unregister_kpp
  - crypto/acompress.c:crypto_unregister_acomps
  - crypto/acompress.c:crypto_register_acomps
  - crypto/scompress.c:crypto_unregister_scomps
  - crypto/scompress.c:crypto_register_scomps
  - crypto/aes_generic.c:aes_fini
  - crypto/deflate.c:deflate_mod_fini
  - crypto/deflate.c:deflate_mod_init
  - crypto/lzo.c:lzo_mod_fini
  - crypto/lzo.c:lzo_mod_init
  - crypto/lzo-rle.c:lzorle_mod_fini
  - crypto/lzo-rle.c:lzorle_mod_init
  - crypto/rng.c:crypto_unregister_rngs
  - crypto/rng.c:crypto_register_rngs
```
**Symbols:**

```
ffffffff814cd3a0-ffffffff814cd478: crypto_unregister_alg (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
