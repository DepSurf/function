# Function: <code>crypto_register_alg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int crypto_register_alg(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff8139e380)
Location: crypto/algapi.c:355
Inline: True
Direct callers:
  - crypto/algapi.c:crypto_register_algs
  - crypto/aead.c:crypto_register_aead
  - crypto/ahash.c:crypto_register_ahash
  - crypto/shash.c:crypto_register_shash
  - crypto/pcompress.c:crypto_register_pcomp
  - crypto/akcipher.c:crypto_register_akcipher
  - crypto/aes_generic.c:aes_init
  - crypto/lzo.c:lzo_mod_init
  - crypto/rng.c:crypto_register_rngs
```
**Symbols:**

```
ffffffff8139e380-ffffffff8139e3e1: crypto_register_alg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int crypto_register_alg(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff813db2f0)
Location: crypto/algapi.c:354
Inline: True
Direct callers:
  - crypto/algapi.c:crypto_register_algs
  - crypto/aead.c:crypto_register_aead
  - crypto/skcipher.c:crypto_register_skcipher
  - crypto/ahash.c:crypto_register_ahash
  - crypto/shash.c:crypto_register_shash
  - crypto/akcipher.c:crypto_register_akcipher
  - crypto/kpp.c:crypto_register_kpp
  - crypto/aes_generic.c:aes_init
  - crypto/lzo.c:lzo_mod_init
  - crypto/rng.c:crypto_register_rngs
```
**Symbols:**

```
ffffffff813db2f0-ffffffff813db351: crypto_register_alg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int crypto_register_alg(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff813f2c30)
Location: crypto/algapi.c:354
Inline: True
Direct callers:
  - crypto/algapi.c:crypto_register_algs
  - crypto/aead.c:crypto_register_aead
  - crypto/skcipher.c:crypto_register_skcipher
  - crypto/ahash.c:crypto_register_ahash
  - crypto/shash.c:crypto_register_shash
  - crypto/akcipher.c:crypto_register_akcipher
  - crypto/kpp.c:crypto_register_kpp
  - crypto/acompress.c:crypto_register_acomp
  - crypto/scompress.c:crypto_register_scomp
  - crypto/aes_generic.c:aes_init
  - crypto/rng.c:crypto_register_rngs
```
**Symbols:**

```
ffffffff813f2c30-ffffffff813f2c98: crypto_register_alg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int crypto_register_alg(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff813fef50)
Location: crypto/algapi.c:354
Inline: True
Direct callers:
  - crypto/algapi.c:crypto_register_algs
  - crypto/aead.c:crypto_register_aead
  - crypto/skcipher.c:crypto_register_skcipher
  - crypto/ahash.c:crypto_register_ahash
  - crypto/shash.c:crypto_register_shash
  - crypto/akcipher.c:crypto_register_akcipher
  - crypto/kpp.c:crypto_register_kpp
  - crypto/acompress.c:crypto_register_acomps
  - crypto/scompress.c:crypto_register_scomp
  - crypto/aes_generic.c:aes_init
  - crypto/rng.c:crypto_register_rngs
```
**Symbols:**

```
ffffffff813fef50-ffffffff813fefb8: crypto_register_alg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int crypto_register_alg(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff81427510)
Location: crypto/algapi.c:366
Inline: True
Direct callers:
  - crypto/algapi.c:crypto_register_algs
  - crypto/aead.c:crypto_register_aead
  - crypto/skcipher.c:crypto_register_skcipher
  - crypto/ahash.c:crypto_register_ahash
  - crypto/shash.c:crypto_register_shash
  - crypto/akcipher.c:crypto_register_akcipher
  - crypto/kpp.c:crypto_register_kpp
  - crypto/acompress.c:crypto_register_acomps
  - crypto/scompress.c:crypto_register_scomps
  - crypto/aes_generic.c:aes_init
  - crypto/rng.c:crypto_register_rngs
```
**Symbols:**

```
ffffffff81427510-ffffffff81427578: crypto_register_alg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int crypto_register_alg(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff8145a210)
Location: crypto/algapi.c:375
Inline: True
Direct callers:
  - crypto/algapi.c:crypto_register_algs
  - crypto/aead.c:crypto_register_aead
  - crypto/skcipher.c:crypto_register_skcipher
  - crypto/ahash.c:crypto_register_ahash
  - crypto/shash.c:crypto_register_shash
  - crypto/akcipher.c:crypto_register_akcipher
  - crypto/kpp.c:crypto_register_kpp
  - crypto/acompress.c:crypto_register_acomps
  - crypto/scompress.c:crypto_register_scomps
  - crypto/aes_generic.c:aes_init
  - crypto/deflate.c:deflate_mod_init
  - crypto/lzo.c:lzo_mod_init
  - crypto/rng.c:crypto_register_rngs
```
**Symbols:**

```
ffffffff8145a210-ffffffff8145a27e: crypto_register_alg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int crypto_register_alg(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff81477820)
Location: crypto/algapi.c:384
Inline: True
Direct callers:
  - crypto/algapi.c:crypto_register_algs
  - crypto/aead.c:crypto_register_aead
  - crypto/skcipher.c:crypto_register_skcipher
  - crypto/ahash.c:crypto_register_ahash
  - crypto/shash.c:crypto_register_shash
  - crypto/akcipher.c:crypto_register_akcipher
  - crypto/kpp.c:crypto_register_kpp
  - crypto/acompress.c:crypto_register_acomps
  - crypto/scompress.c:crypto_register_scomps
  - crypto/aes_generic.c:aes_init
  - crypto/deflate.c:deflate_mod_init
  - crypto/lzo.c:lzo_mod_init
  - crypto/rng.c:crypto_register_rngs
```
**Symbols:**

```
ffffffff81477820-ffffffff8147788e: crypto_register_alg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int crypto_register_alg(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff814a54c0)
Location: crypto/algapi.c:365
Inline: True
Direct callers:
  - crypto/algapi.c:crypto_register_algs
  - crypto/aead.c:crypto_register_aead
  - crypto/skcipher.c:crypto_register_skcipher
  - crypto/ahash.c:crypto_register_ahash
  - crypto/shash.c:crypto_register_shash
  - crypto/akcipher.c:crypto_register_akcipher
  - crypto/kpp.c:crypto_register_kpp
  - crypto/acompress.c:crypto_register_acomps
  - crypto/scompress.c:crypto_register_scomps
  - crypto/aes_generic.c:aes_init
  - crypto/deflate.c:deflate_mod_init
  - crypto/lzo.c:lzo_mod_init
  - crypto/lzo-rle.c:lzorle_mod_init
  - crypto/rng.c:crypto_register_rngs
```
**Symbols:**

```
ffffffff814a54c0-ffffffff814a552b: crypto_register_alg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int crypto_register_alg(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff814c0170)
Location: crypto/algapi.c:383
Inline: True
Direct callers:
  - crypto/algapi.c:crypto_register_algs
  - crypto/aead.c:crypto_register_aead
  - crypto/skcipher.c:crypto_register_skcipher
  - crypto/ahash.c:crypto_register_ahash
  - crypto/shash.c:crypto_register_shash
  - crypto/akcipher.c:crypto_register_akcipher
  - crypto/kpp.c:crypto_register_kpp
  - crypto/acompress.c:crypto_register_acomps
  - crypto/scompress.c:crypto_register_scomps
  - crypto/aes_generic.c:aes_init
  - crypto/deflate.c:deflate_mod_init
  - crypto/lzo.c:lzo_mod_init
  - crypto/lzo-rle.c:lzorle_mod_init
  - crypto/rng.c:crypto_register_rngs
```
**Symbols:**

```
ffffffff814c0170-ffffffff814c01db: crypto_register_alg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int crypto_register_alg(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff81520cb0)
Location: crypto/algapi.c:412
Inline: True
Direct callers:
  - crypto/algapi.c:crypto_register_algs
  - crypto/aead.c:crypto_register_aeads
  - crypto/skcipher.c:crypto_register_skciphers
  - crypto/ahash.c:crypto_register_ahashes
  - crypto/shash.c:crypto_register_shashes
  - crypto/akcipher.c:crypto_register_akcipher
  - crypto/kpp.c:crypto_register_kpp
  - crypto/acompress.c:crypto_register_acomps
  - crypto/scompress.c:crypto_register_scomps
  - crypto/aes_generic.c:aes_init
  - crypto/deflate.c:deflate_mod_init
  - crypto/lzo.c:lzo_mod_init
  - crypto/lzo-rle.c:lzorle_mod_init
  - crypto/rng.c:crypto_register_rngs
```
**Symbols:**

```
ffffffff81520cb0-ffffffff81520d1b: crypto_register_alg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int crypto_register_alg(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff8153db40)
Location: crypto/algapi.c:412
Inline: True
Direct callers:
  - crypto/algapi.c:crypto_register_algs
  - crypto/aead.c:crypto_register_aeads
  - crypto/skcipher.c:crypto_register_skciphers
  - crypto/ahash.c:crypto_register_ahashes
  - crypto/shash.c:crypto_register_shashes
  - crypto/akcipher.c:crypto_register_akcipher
  - crypto/kpp.c:crypto_register_kpp
  - crypto/acompress.c:crypto_register_acomps
  - crypto/scompress.c:crypto_register_scomps
  - crypto/aes_generic.c:aes_init
  - crypto/deflate.c:deflate_mod_init
  - crypto/lzo.c:lzo_mod_init
  - crypto/lzo-rle.c:lzorle_mod_init
  - crypto/rng.c:crypto_register_rngs
```
**Symbols:**

```
ffffffff8153db40-ffffffff8153dbab: crypto_register_alg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int crypto_register_alg(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff81546220)
Location: crypto/algapi.c:412
Inline: True
Direct callers:
  - crypto/algapi.c:crypto_register_algs
  - crypto/aead.c:crypto_register_aeads
  - crypto/skcipher.c:crypto_register_skciphers
  - crypto/ahash.c:crypto_register_ahashes
  - crypto/shash.c:crypto_register_shashes
  - crypto/akcipher.c:crypto_register_akcipher
  - crypto/kpp.c:crypto_register_kpp
  - crypto/acompress.c:crypto_register_acomps
  - crypto/scompress.c:crypto_register_scomps
  - crypto/aes_generic.c:aes_init
  - crypto/deflate.c:deflate_mod_init
  - crypto/lzo.c:lzo_mod_init
  - crypto/lzo-rle.c:lzorle_mod_init
  - crypto/rng.c:crypto_register_rngs
```
**Symbols:**

```
ffffffff81546220-ffffffff8154628b: crypto_register_alg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int crypto_register_alg(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff815a69f0)
Location: crypto/algapi.c:412
Inline: True
Direct callers:
  - crypto/algapi.c:crypto_register_algs
  - crypto/aead.c:crypto_register_aeads
  - crypto/skcipher.c:crypto_register_skciphers
  - crypto/ahash.c:crypto_register_ahashes
  - crypto/shash.c:crypto_register_shashes
  - crypto/akcipher.c:crypto_register_akcipher
  - crypto/kpp.c:crypto_register_kpp
  - crypto/acompress.c:crypto_register_acomps
  - crypto/scompress.c:crypto_register_scomps
  - crypto/aes_generic.c:aes_init
  - crypto/deflate.c:deflate_mod_init
  - crypto/lzo.c:lzo_mod_init
  - crypto/lzo-rle.c:lzorle_mod_init
  - crypto/rng.c:crypto_register_rngs
```
**Symbols:**

```
ffffffff815a69f0-ffffffff815a6a5b: crypto_register_alg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int crypto_register_alg(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff8164cc70)
Location: crypto/algapi.c:423
Inline: True
Direct callers:
  - crypto/algapi.c:crypto_register_algs
  - crypto/aead.c:crypto_register_aeads
  - crypto/skcipher.c:crypto_register_skciphers
  - crypto/ahash.c:crypto_register_ahashes
  - crypto/shash.c:crypto_register_shashes
  - crypto/akcipher.c:crypto_register_akcipher
  - crypto/kpp.c:crypto_register_kpp
  - crypto/acompress.c:crypto_register_acomps
  - crypto/scompress.c:crypto_register_scomps
  - crypto/aes_generic.c:aes_init
  - crypto/deflate.c:deflate_mod_init
  - crypto/lzo.c:lzo_mod_init
  - crypto/lzo-rle.c:lzorle_mod_init
  - crypto/rng.c:crypto_register_rngs
```
**Symbols:**

```
ffffffff8164cc70-ffffffff8164cd1d: crypto_register_alg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int crypto_register_alg(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff81706a70)
Location: crypto/algapi.c:442
Inline: False
Direct callers:
  - crypto/algapi.c:crypto_register_algs
  - crypto/aead.c:crypto_register_aeads
  - crypto/skcipher.c:crypto_register_skciphers
  - crypto/ahash.c:crypto_register_ahashes
  - crypto/shash.c:crypto_register_shashes
  - crypto/akcipher.c:crypto_register_akcipher
  - crypto/kpp.c:crypto_register_kpp
  - crypto/acompress.c:crypto_register_acomps
  - crypto/scompress.c:crypto_register_scomps
  - crypto/aes_generic.c:aes_init
  - crypto/deflate.c:deflate_mod_init
  - crypto/lzo.c:lzo_mod_init
  - crypto/lzo-rle.c:lzorle_mod_init
  - crypto/rng.c:crypto_register_rngs
```
**Symbols:**

```
ffffffff81706a70-ffffffff81706b4c: crypto_register_alg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int crypto_register_alg(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff81740990)
Location: crypto/algapi.c:452
Inline: False
Direct callers:
  - crypto/algapi.c:crypto_register_algs
  - crypto/aead.c:crypto_register_aeads
  - crypto/skcipher.c:crypto_register_skciphers
  - crypto/ahash.c:crypto_register_ahashes
  - crypto/shash.c:crypto_register_shashes
  - crypto/akcipher.c:crypto_register_akcipher
  - crypto/kpp.c:crypto_register_kpp
  - crypto/acompress.c:crypto_register_acomps
  - crypto/scompress.c:crypto_register_scomps
  - crypto/aes_generic.c:aes_init
  - crypto/deflate.c:deflate_mod_init
  - crypto/lzo.c:lzo_mod_init
  - crypto/lzo-rle.c:lzorle_mod_init
  - crypto/rng.c:crypto_register_rng
```
**Symbols:**

```
ffffffff81740990-ffffffff81740a6c: crypto_register_alg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int crypto_register_alg(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff81781830)
Location: crypto/algapi.c:453
Inline: False
Direct callers:
  - crypto/algapi.c:crypto_register_algs
  - crypto/aead.c:crypto_register_aeads
  - crypto/lskcipher.c:crypto_register_lskciphers
  - crypto/skcipher.c:crypto_register_skcipher
  - crypto/ahash.c:crypto_register_ahashes
  - crypto/shash.c:crypto_register_shashes
  - crypto/akcipher.c:crypto_register_akcipher
  - crypto/kpp.c:crypto_register_kpp
  - crypto/acompress.c:crypto_register_acomps
  - crypto/scompress.c:crypto_register_scomps
  - crypto/aes_generic.c:aes_init
  - crypto/deflate.c:deflate_mod_init
  - crypto/lzo.c:lzo_mod_init
  - crypto/lzo-rle.c:lzorle_mod_init
  - crypto/rng.c:crypto_register_rng
```
**Symbols:**

```
ffffffff81781830-ffffffff8178190c: crypto_register_alg (STB_GLOBAL)
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
int crypto_register_alg(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffff8000105b97a0)
Location: crypto/algapi.c:383
Inline: True
Direct callers:
  - crypto/algapi.c:crypto_register_algs
  - crypto/aead.c:crypto_register_aead
  - crypto/skcipher.c:crypto_register_skcipher
  - crypto/ahash.c:crypto_register_ahash
  - crypto/shash.c:crypto_register_shash
  - crypto/akcipher.c:crypto_register_akcipher
  - crypto/kpp.c:crypto_register_kpp
  - crypto/acompress.c:crypto_register_acomps
  - crypto/scompress.c:crypto_register_scomps
  - crypto/aes_generic.c:aes_init
  - crypto/deflate.c:deflate_mod_init
  - crypto/lzo.c:lzo_mod_init
  - crypto/lzo-rle.c:lzorle_mod_init
  - crypto/rng.c:crypto_register_rngs
```
**Symbols:**

```
ffff8000105b97a0-ffff8000105b983c: crypto_register_alg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int crypto_register_alg(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (c076818c)
Location: crypto/algapi.c:383
Inline: True
Direct callers:
  - crypto/algapi.c:crypto_register_algs
  - crypto/aead.c:crypto_register_aead
  - crypto/skcipher.c:crypto_register_skcipher
  - crypto/ahash.c:crypto_register_ahash
  - crypto/shash.c:crypto_register_shash
  - crypto/akcipher.c:crypto_register_akcipher
  - crypto/kpp.c:crypto_register_kpp
  - crypto/acompress.c:crypto_register_acomps
  - crypto/scompress.c:crypto_register_scomps
  - crypto/aes_generic.c:aes_init
  - crypto/deflate.c:deflate_mod_init
  - crypto/lzo.c:lzo_mod_init
  - crypto/lzo-rle.c:lzorle_mod_init
  - crypto/rng.c:crypto_register_rngs
```
**Symbols:**

```
c076818c-c0768204: crypto_register_alg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int crypto_register_alg(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (c00000000073fb10)
Location: crypto/algapi.c:383
Inline: True
Direct callers:
  - crypto/algapi.c:crypto_register_algs
  - crypto/aead.c:crypto_register_aead
  - crypto/skcipher.c:crypto_register_skcipher
  - crypto/ahash.c:crypto_register_ahash
  - crypto/shash.c:crypto_register_shash
  - crypto/akcipher.c:crypto_register_akcipher
  - crypto/akcipher.c:crypto_register_akcipher
  - crypto/kpp.c:crypto_register_kpp
  - crypto/acompress.c:crypto_register_acomps
  - crypto/scompress.c:crypto_register_scomps
  - crypto/aes_generic.c:aes_init
  - crypto/deflate.c:deflate_mod_init
  - crypto/lzo.c:lzo_mod_init
  - crypto/lzo-rle.c:lzorle_mod_init
  - crypto/rng.c:crypto_register_rngs
```
**Symbols:**

```
c00000000073fb10-c00000000073fbec: crypto_register_alg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int crypto_register_alg(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffe0003ffc66)
Location: crypto/algapi.c:383
Inline: True
Direct callers:
  - crypto/algapi.c:crypto_register_algs
  - crypto/aead.c:crypto_register_aead
  - crypto/skcipher.c:crypto_register_skcipher
  - crypto/ahash.c:crypto_register_ahash
  - crypto/shash.c:crypto_register_shash
  - crypto/akcipher.c:crypto_register_akcipher
  - crypto/kpp.c:crypto_register_kpp
  - crypto/acompress.c:crypto_register_acomps
  - crypto/scompress.c:crypto_register_scomps
  - crypto/aes_generic.c:aes_init
  - crypto/deflate.c:deflate_mod_init
  - crypto/lzo.c:lzo_mod_init
  - crypto/lzo-rle.c:lzorle_mod_init
  - crypto/rng.c:crypto_register_rngs
```
**Symbols:**

```
ffffffe0003ffc66-ffffffe0003ffcf2: crypto_register_alg (STB_GLOBAL)
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
int crypto_register_alg(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff814b8750)
Location: crypto/algapi.c:383
Inline: True
Direct callers:
  - crypto/algapi.c:crypto_register_algs
  - crypto/aead.c:crypto_register_aead
  - crypto/skcipher.c:crypto_register_skcipher
  - crypto/ahash.c:crypto_register_ahash
  - crypto/shash.c:crypto_register_shash
  - crypto/akcipher.c:crypto_register_akcipher
  - crypto/kpp.c:crypto_register_kpp
  - crypto/acompress.c:crypto_register_acomps
  - crypto/scompress.c:crypto_register_scomps
  - crypto/aes_generic.c:aes_init
  - crypto/deflate.c:deflate_mod_init
  - crypto/lzo.c:lzo_mod_init
  - crypto/lzo-rle.c:lzorle_mod_init
  - crypto/rng.c:crypto_register_rngs
```
**Symbols:**

```
ffffffff814b8750-ffffffff814b87bb: crypto_register_alg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int crypto_register_alg(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff814a9170)
Location: crypto/algapi.c:383
Inline: True
Direct callers:
  - crypto/algapi.c:crypto_register_algs
  - crypto/aead.c:crypto_register_aead
  - crypto/skcipher.c:crypto_register_skcipher
  - crypto/ahash.c:crypto_register_ahash
  - crypto/shash.c:crypto_register_shash
  - crypto/akcipher.c:crypto_register_akcipher
  - crypto/kpp.c:crypto_register_kpp
  - crypto/acompress.c:crypto_register_acomps
  - crypto/scompress.c:crypto_register_scomps
  - crypto/aes_generic.c:aes_init
  - crypto/deflate.c:deflate_mod_init
  - crypto/lzo.c:lzo_mod_init
  - crypto/lzo-rle.c:lzorle_mod_init
  - crypto/rng.c:crypto_register_rngs
```
**Symbols:**

```
ffffffff814a9170-ffffffff814a91db: crypto_register_alg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int crypto_register_alg(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff814b47e0)
Location: crypto/algapi.c:383
Inline: True
Direct callers:
  - crypto/algapi.c:crypto_register_algs
  - crypto/aead.c:crypto_register_aead
  - crypto/skcipher.c:crypto_register_skcipher
  - crypto/ahash.c:crypto_register_ahash
  - crypto/shash.c:crypto_register_shash
  - crypto/akcipher.c:crypto_register_akcipher
  - crypto/kpp.c:crypto_register_kpp
  - crypto/acompress.c:crypto_register_acomps
  - crypto/scompress.c:crypto_register_scomps
  - crypto/aes_generic.c:aes_init
  - crypto/deflate.c:deflate_mod_init
  - crypto/lzo.c:lzo_mod_init
  - crypto/lzo-rle.c:lzorle_mod_init
  - crypto/rng.c:crypto_register_rngs
```
**Symbols:**

```
ffffffff814b47e0-ffffffff814b484b: crypto_register_alg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int crypto_register_alg(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff814cd260)
Location: crypto/algapi.c:383
Inline: True
Direct callers:
  - crypto/algapi.c:crypto_register_algs
  - crypto/aead.c:crypto_register_aead
  - crypto/skcipher.c:crypto_register_skcipher
  - crypto/ahash.c:crypto_register_ahash
  - crypto/shash.c:crypto_register_shash
  - crypto/akcipher.c:crypto_register_akcipher
  - crypto/kpp.c:crypto_register_kpp
  - crypto/acompress.c:crypto_register_acomps
  - crypto/scompress.c:crypto_register_scomps
  - crypto/aes_generic.c:aes_init
  - crypto/deflate.c:deflate_mod_init
  - crypto/lzo.c:lzo_mod_init
  - crypto/lzo-rle.c:lzorle_mod_init
  - crypto/rng.c:crypto_register_rngs
```
**Symbols:**

```
ffffffff814cd260-ffffffff814cd2cb: crypto_register_alg (STB_GLOBAL)
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
