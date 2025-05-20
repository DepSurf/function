# Function: <code>crypto_alloc_tfm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *crypto_alloc_tfm(const char *alg_name, const struct crypto_type *frontend, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff8139c2f0)
Location: crypto/api.c:540
Inline: False
Direct callers:
  - crypto/aead.c:crypto_alloc_aead
  - crypto/skcipher.c:crypto_alloc_skcipher
  - crypto/ahash.c:crypto_alloc_ahash
  - crypto/shash.c:crypto_alloc_shash
  - crypto/pcompress.c:crypto_alloc_pcomp
  - crypto/akcipher.c:crypto_alloc_akcipher
  - crypto/rng.c:crypto_get_default_rng
```
**Symbols:**

```
ffffffff8139c2f0-ffffffff8139c40a: crypto_alloc_tfm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *crypto_alloc_tfm(const char *alg_name, const struct crypto_type *frontend, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff813d91f0)
Location: crypto/api.c:540
Inline: False
Direct callers:
  - crypto/aead.c:crypto_alloc_aead
  - crypto/skcipher.c:crypto_alloc_skcipher
  - crypto/ahash.c:crypto_alloc_ahash
  - crypto/shash.c:crypto_alloc_shash
  - crypto/akcipher.c:crypto_alloc_akcipher
  - crypto/kpp.c:crypto_alloc_kpp
  - crypto/rng.c:crypto_get_default_rng
```
**Symbols:**

```
ffffffff813d91f0-ffffffff813d9310: crypto_alloc_tfm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *crypto_alloc_tfm(const char *alg_name, const struct crypto_type *frontend, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff813f0b00)
Location: crypto/api.c:524
Inline: False
Direct callers:
  - crypto/aead.c:crypto_alloc_aead
  - crypto/skcipher.c:crypto_alloc_skcipher
  - crypto/ahash.c:crypto_alloc_ahash
  - crypto/shash.c:crypto_alloc_shash
  - crypto/akcipher.c:crypto_alloc_akcipher
  - crypto/kpp.c:crypto_alloc_kpp
  - crypto/acompress.c:crypto_alloc_acomp
  - crypto/rng.c:crypto_get_default_rng
```
**Symbols:**

```
ffffffff813f0b00-ffffffff813f0c18: crypto_alloc_tfm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *crypto_alloc_tfm(const char *alg_name, const struct crypto_type *frontend, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff813fcd90)
Location: crypto/api.c:524
Inline: False
Direct callers:
  - crypto/aead.c:crypto_alloc_aead
  - crypto/skcipher.c:crypto_alloc_skcipher
  - crypto/ahash.c:crypto_alloc_ahash
  - crypto/shash.c:crypto_alloc_shash
  - crypto/akcipher.c:crypto_alloc_akcipher
  - crypto/kpp.c:crypto_alloc_kpp
  - crypto/acompress.c:crypto_alloc_acomp
  - crypto/rng.c:crypto_get_default_rng
```
**Symbols:**

```
ffffffff813fcd90-ffffffff813fcea4: crypto_alloc_tfm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *crypto_alloc_tfm(const char *alg_name, const struct crypto_type *frontend, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff814252f0)
Location: crypto/api.c:525
Inline: False
Direct callers:
  - crypto/aead.c:crypto_alloc_aead
  - crypto/skcipher.c:crypto_alloc_skcipher
  - crypto/ahash.c:crypto_alloc_ahash
  - crypto/shash.c:crypto_alloc_shash
  - crypto/akcipher.c:crypto_alloc_akcipher
  - crypto/kpp.c:crypto_alloc_kpp
  - crypto/acompress.c:crypto_alloc_acomp
  - crypto/rng.c:crypto_get_default_rng
```
**Symbols:**

```
ffffffff814252f0-ffffffff814253ff: crypto_alloc_tfm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *crypto_alloc_tfm(const char *alg_name, const struct crypto_type *frontend, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff81458b40)
Location: crypto/api.c:528
Inline: False
Direct callers:
  - crypto/aead.c:crypto_alloc_aead
  - crypto/skcipher.c:crypto_alloc_skcipher
  - crypto/ahash.c:crypto_alloc_ahash
  - crypto/shash.c:crypto_alloc_shash
  - crypto/akcipher.c:crypto_alloc_akcipher
  - crypto/kpp.c:crypto_alloc_kpp
  - crypto/acompress.c:crypto_alloc_acomp
  - crypto/rng.c:crypto_get_default_rng
```
**Symbols:**

```
ffffffff81458b40-ffffffff81458c32: crypto_alloc_tfm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *crypto_alloc_tfm(const char *alg_name, const struct crypto_type *frontend, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff81475d60)
Location: crypto/api.c:528
Inline: False
Direct callers:
  - crypto/aead.c:crypto_alloc_aead
  - crypto/skcipher.c:crypto_alloc_sync_skcipher
  - crypto/skcipher.c:crypto_alloc_skcipher
  - crypto/ahash.c:crypto_alloc_ahash
  - crypto/shash.c:crypto_alloc_shash
  - crypto/akcipher.c:crypto_alloc_akcipher
  - crypto/kpp.c:crypto_alloc_kpp
  - crypto/acompress.c:crypto_alloc_acomp
  - crypto/rng.c:crypto_get_default_rng
```
**Symbols:**

```
ffffffff81475d60-ffffffff81475e52: crypto_alloc_tfm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *crypto_alloc_tfm(const char *alg_name, const struct crypto_type *frontend, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff814a3d90)
Location: crypto/api.c:523
Inline: False
Direct callers:
  - crypto/aead.c:crypto_alloc_aead
  - crypto/skcipher.c:crypto_alloc_sync_skcipher
  - crypto/skcipher.c:crypto_alloc_skcipher
  - crypto/ahash.c:crypto_alloc_ahash
  - crypto/shash.c:crypto_alloc_shash
  - crypto/akcipher.c:crypto_alloc_akcipher
  - crypto/kpp.c:crypto_alloc_kpp
  - crypto/acompress.c:crypto_alloc_acomp
  - crypto/rng.c:crypto_get_default_rng
```
**Symbols:**

```
ffffffff814a3d90-ffffffff814a3e96: crypto_alloc_tfm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *crypto_alloc_tfm(const char *alg_name, const struct crypto_type *frontend, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff814be9c0)
Location: crypto/api.c:524
Inline: False
Direct callers:
  - crypto/aead.c:crypto_alloc_aead
  - crypto/skcipher.c:crypto_alloc_sync_skcipher
  - crypto/skcipher.c:crypto_alloc_skcipher
  - crypto/ahash.c:crypto_alloc_ahash
  - crypto/shash.c:crypto_alloc_shash
  - crypto/akcipher.c:crypto_alloc_akcipher
  - crypto/kpp.c:crypto_alloc_kpp
  - crypto/acompress.c:crypto_alloc_acomp
  - crypto/rng.c:crypto_get_default_rng
```
**Symbols:**

```
ffffffff814be9c0-ffffffff814beac6: crypto_alloc_tfm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *crypto_alloc_tfm(const char *alg_name, const struct crypto_type *frontend, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff8151f190)
Location: crypto/api.c:512
Inline: False
Direct callers:
  - crypto/aead.c:crypto_alloc_aead
  - crypto/skcipher.c:crypto_alloc_sync_skcipher
  - crypto/skcipher.c:crypto_alloc_skcipher
  - crypto/ahash.c:crypto_alloc_ahash
  - crypto/shash.c:crypto_alloc_shash
  - crypto/akcipher.c:crypto_alloc_akcipher
  - crypto/kpp.c:crypto_alloc_kpp
  - crypto/acompress.c:crypto_alloc_acomp
  - crypto/rng.c:crypto_get_default_rng
```
**Symbols:**

```
ffffffff8151f190-ffffffff8151f256: crypto_alloc_tfm (STB_GLOBAL)
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
In crypto/aead.c (ffffffff8153ee98)
Location: crypto/internal.h:86
Inline: True
Inline callers:
  - crypto/aead.c:crypto_alloc_aead
```
```
In crypto/skcipher.c (ffffffff8153fb25)
Location: crypto/internal.h:86
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_alloc_sync_skcipher
  - crypto/skcipher.c:crypto_alloc_skcipher
```
```
In crypto/ahash.c (ffffffff81541808)
Location: crypto/internal.h:86
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_alloc_ahash
```
```
In crypto/shash.c (ffffffff81542308)
Location: crypto/internal.h:86
Inline: True
Inline callers:
  - crypto/shash.c:crypto_alloc_shash
```
```
In crypto/akcipher.c (ffffffff81542e68)
Location: crypto/internal.h:86
Inline: True
Inline callers:
  - crypto/akcipher.c:crypto_alloc_akcipher
```
```
In crypto/kpp.c (ffffffff81543098)
Location: crypto/internal.h:86
Inline: True
Inline callers:
  - crypto/kpp.c:crypto_alloc_kpp
```
```
In crypto/acompress.c (ffffffff81545228)
Location: crypto/internal.h:86
Inline: True
Inline callers:
  - crypto/acompress.c:crypto_alloc_acomp
```
```
In crypto/rng.c (ffffffff8154ff12)
Location: crypto/internal.h:86
Inline: True
Inline callers:
  - crypto/rng.c:crypto_get_default_rng
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
In crypto/aead.c (ffffffff81547518)
Location: crypto/internal.h:86
Inline: True
Inline callers:
  - crypto/aead.c:crypto_alloc_aead
```
```
In crypto/skcipher.c (ffffffff81548095)
Location: crypto/internal.h:86
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_alloc_sync_skcipher
  - crypto/skcipher.c:crypto_alloc_skcipher
```
```
In crypto/ahash.c (ffffffff81549e38)
Location: crypto/internal.h:86
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_alloc_ahash
```
```
In crypto/shash.c (ffffffff8154a9a8)
Location: crypto/internal.h:86
Inline: True
Inline callers:
  - crypto/shash.c:crypto_alloc_shash
```
```
In crypto/akcipher.c (ffffffff8154b508)
Location: crypto/internal.h:86
Inline: True
Inline callers:
  - crypto/akcipher.c:crypto_alloc_akcipher
```
```
In crypto/kpp.c (ffffffff8154b738)
Location: crypto/internal.h:86
Inline: True
Inline callers:
  - crypto/kpp.c:crypto_alloc_kpp
```
```
In crypto/acompress.c (ffffffff8154d8b8)
Location: crypto/internal.h:86
Inline: True
Inline callers:
  - crypto/acompress.c:crypto_alloc_acomp
```
```
In crypto/rng.c (ffffffff81558542)
Location: crypto/internal.h:86
Inline: True
Inline callers:
  - crypto/rng.c:crypto_get_default_rng
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
In crypto/aead.c (ffffffff815a7cf8)
Location: crypto/internal.h:98
Inline: True
Inline callers:
  - crypto/aead.c:crypto_alloc_aead
```
```
In crypto/skcipher.c (ffffffff815a8875)
Location: crypto/internal.h:98
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_alloc_sync_skcipher
  - crypto/skcipher.c:crypto_alloc_skcipher
```
```
In crypto/ahash.c (ffffffff815aa618)
Location: crypto/internal.h:98
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_alloc_ahash
```
```
In crypto/shash.c (ffffffff815ab188)
Location: crypto/internal.h:98
Inline: True
Inline callers:
  - crypto/shash.c:crypto_alloc_shash
```
```
In crypto/akcipher.c (ffffffff815abce8)
Location: crypto/internal.h:98
Inline: True
Inline callers:
  - crypto/akcipher.c:crypto_alloc_akcipher
```
```
In crypto/kpp.c (ffffffff815abf18)
Location: crypto/internal.h:98
Inline: True
Inline callers:
  - crypto/kpp.c:crypto_alloc_kpp
```
```
In crypto/acompress.c (ffffffff815ae098)
Location: crypto/internal.h:98
Inline: True
Inline callers:
  - crypto/acompress.c:crypto_alloc_acomp
```
```
In crypto/rng.c (ffffffff815b97f2)
Location: crypto/internal.h:98
Inline: True
Inline callers:
  - crypto/rng.c:crypto_get_default_rng
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
In crypto/aead.c (ffffffff8164f028)
Location: crypto/internal.h:103
Inline: True
Inline callers:
  - crypto/aead.c:crypto_alloc_aead
```
```
In crypto/skcipher.c (ffffffff8164fbf5)
Location: crypto/internal.h:103
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_alloc_sync_skcipher
  - crypto/skcipher.c:crypto_alloc_skcipher
```
```
In crypto/ahash.c (ffffffff81651aa8)
Location: crypto/internal.h:103
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_alloc_ahash
```
```
In crypto/shash.c (ffffffff816528f8)
Location: crypto/internal.h:103
Inline: True
Inline callers:
  - crypto/shash.c:crypto_alloc_shash
```
```
In crypto/akcipher.c (ffffffff81653648)
Location: crypto/internal.h:103
Inline: True
Inline callers:
  - crypto/akcipher.c:crypto_alloc_akcipher
```
```
In crypto/kpp.c (ffffffff816538b8)
Location: crypto/internal.h:103
Inline: True
Inline callers:
  - crypto/kpp.c:crypto_alloc_kpp
```
```
In crypto/acompress.c (ffffffff816565a8)
Location: crypto/internal.h:103
Inline: True
Inline callers:
  - crypto/acompress.c:crypto_alloc_acomp
```
```
In crypto/rng.c (ffffffff81662d6d)
Location: crypto/internal.h:103
Inline: True
Inline callers:
  - crypto/rng.c:crypto_get_default_rng
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
In crypto/aead.c (ffffffff81708468)
Location: crypto/internal.h:121
Inline: True
Inline callers:
  - crypto/aead.c:crypto_alloc_aead
```
```
In crypto/skcipher.c (ffffffff81709065)
Location: crypto/internal.h:121
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_alloc_sync_skcipher
  - crypto/skcipher.c:crypto_alloc_skcipher
```
```
In crypto/ahash.c (ffffffff8170b068)
Location: crypto/internal.h:121
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_alloc_ahash
```
```
In crypto/shash.c (ffffffff8170c068)
Location: crypto/internal.h:121
Inline: True
Inline callers:
  - crypto/shash.c:crypto_alloc_shash
```
```
In crypto/akcipher.c (ffffffff8170d458)
Location: crypto/internal.h:121
Inline: True
Inline callers:
  - crypto/akcipher.c:crypto_alloc_akcipher
```
```
In crypto/kpp.c (ffffffff8170d778)
Location: crypto/internal.h:121
Inline: True
Inline callers:
  - crypto/kpp.c:crypto_alloc_kpp
```
```
In crypto/acompress.c (ffffffff81710808)
Location: crypto/internal.h:121
Inline: True
Inline callers:
  - crypto/acompress.c:crypto_alloc_acomp
```
```
In crypto/rng.c (ffffffff8171cf4d)
Location: crypto/internal.h:121
Inline: True
Inline callers:
  - crypto/rng.c:crypto_get_default_rng
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
In crypto/aead.c (ffffffff81741be8)
Location: crypto/internal.h:148
Inline: True
Inline callers:
  - crypto/aead.c:crypto_alloc_aead
```
```
In crypto/skcipher.c (ffffffff817428b5)
Location: crypto/internal.h:148
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_alloc_sync_skcipher
  - crypto/skcipher.c:crypto_alloc_skcipher
```
```
In crypto/ahash.c (ffffffff81744778)
Location: crypto/internal.h:148
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_alloc_ahash
```
```
In crypto/shash.c (ffffffff81745a68)
Location: crypto/internal.h:148
Inline: True
Inline callers:
  - crypto/shash.c:crypto_alloc_shash
```
```
In crypto/akcipher.c (ffffffff817472c8)
Location: crypto/internal.h:148
Inline: True
Inline callers:
  - crypto/akcipher.c:crypto_alloc_akcipher
```
```
In crypto/sig.c (ffffffff81747b28)
Location: crypto/internal.h:148
Inline: True
Inline callers:
  - crypto/sig.c:crypto_alloc_sig
```
```
In crypto/kpp.c (ffffffff81747ff8)
Location: crypto/internal.h:148
Inline: True
Inline callers:
  - crypto/kpp.c:crypto_alloc_kpp
```
```
In crypto/acompress.c (ffffffff8174b2b8)
Location: crypto/internal.h:148
Inline: True
Inline callers:
  - crypto/acompress.c:crypto_alloc_acomp
```
```
In crypto/rng.c (ffffffff8175879d)
Location: crypto/internal.h:148
Inline: True
Inline callers:
  - crypto/rng.c:crypto_get_default_rng
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
In crypto/aead.c (ffffffff81782a88)
Location: crypto/internal.h:148
Inline: True
Inline callers:
  - crypto/aead.c:crypto_alloc_aead
```
```
In crypto/lskcipher.c (ffffffff81783738)
Location: crypto/internal.h:148
Inline: True
Inline callers:
  - crypto/lskcipher.c:crypto_alloc_lskcipher
```
```
In crypto/skcipher.c (ffffffff81784ba5)
Location: crypto/internal.h:148
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_alloc_sync_skcipher
  - crypto/skcipher.c:crypto_alloc_skcipher
```
```
In crypto/ahash.c (ffffffff81786cd8)
Location: crypto/internal.h:148
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_alloc_ahash
```
```
In crypto/shash.c (ffffffff817883d8)
Location: crypto/internal.h:148
Inline: True
Inline callers:
  - crypto/shash.c:crypto_alloc_shash
```
```
In crypto/akcipher.c (ffffffff81789138)
Location: crypto/internal.h:148
Inline: True
Inline callers:
  - crypto/akcipher.c:crypto_alloc_akcipher
```
```
In crypto/sig.c (ffffffff81789998)
Location: crypto/internal.h:148
Inline: True
Inline callers:
  - crypto/sig.c:crypto_alloc_sig
```
```
In crypto/kpp.c (ffffffff81789e68)
Location: crypto/internal.h:148
Inline: True
Inline callers:
  - crypto/kpp.c:crypto_alloc_kpp
```
```
In crypto/acompress.c (ffffffff8178d188)
Location: crypto/internal.h:148
Inline: True
Inline callers:
  - crypto/acompress.c:crypto_alloc_acomp
```
```
In crypto/rng.c (ffffffff8179a69d)
Location: crypto/internal.h:148
Inline: True
Inline callers:
  - crypto/rng.c:crypto_get_default_rng
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
void *crypto_alloc_tfm(const char *alg_name, const struct crypto_type *frontend, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffff8000105b7a28)
Location: crypto/api.c:524
Inline: False
Direct callers:
  - crypto/aead.c:crypto_alloc_aead
  - crypto/skcipher.c:crypto_alloc_sync_skcipher
  - crypto/skcipher.c:crypto_alloc_skcipher
  - crypto/ahash.c:crypto_alloc_ahash
  - crypto/shash.c:crypto_alloc_shash
  - crypto/akcipher.c:crypto_alloc_akcipher
  - crypto/kpp.c:crypto_alloc_kpp
  - crypto/acompress.c:crypto_alloc_acomp
  - crypto/rng.c:crypto_get_default_rng
```
**Symbols:**

```
ffff8000105b7a28-ffff8000105b7b34: crypto_alloc_tfm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *crypto_alloc_tfm(const char *alg_name, const struct crypto_type *frontend, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (c07665a8)
Location: crypto/api.c:524
Inline: False
Direct callers:
  - crypto/aead.c:crypto_alloc_aead
  - crypto/skcipher.c:crypto_alloc_sync_skcipher
  - crypto/skcipher.c:crypto_alloc_skcipher
  - crypto/ahash.c:crypto_alloc_ahash
  - crypto/shash.c:crypto_alloc_shash
  - crypto/akcipher.c:crypto_alloc_akcipher
  - crypto/kpp.c:crypto_alloc_kpp
  - crypto/acompress.c:crypto_alloc_acomp
  - crypto/rng.c:crypto_get_default_rng
```
**Symbols:**

```
c07665a8-c07666c8: crypto_alloc_tfm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *crypto_alloc_tfm(const char *alg_name, const struct crypto_type *frontend, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (c00000000073c580)
Location: crypto/api.c:524
Inline: False
Direct callers:
  - crypto/aead.c:crypto_alloc_aead
  - crypto/skcipher.c:crypto_alloc_sync_skcipher
  - crypto/skcipher.c:crypto_alloc_skcipher
  - crypto/ahash.c:crypto_alloc_ahash
  - crypto/shash.c:crypto_alloc_shash
  - crypto/akcipher.c:crypto_alloc_akcipher
  - crypto/kpp.c:crypto_alloc_kpp
  - crypto/acompress.c:crypto_alloc_acomp
  - crypto/rng.c:crypto_get_default_rng
```
**Symbols:**

```
c00000000073c580-c00000000073c72c: crypto_alloc_tfm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *crypto_alloc_tfm(const char *alg_name, const struct crypto_type *frontend, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffe0003fe00a)
Location: crypto/api.c:524
Inline: False
Direct callers:
  - crypto/aead.c:crypto_alloc_aead
  - crypto/skcipher.c:crypto_alloc_sync_skcipher
  - crypto/skcipher.c:crypto_alloc_skcipher
  - crypto/ahash.c:crypto_alloc_ahash
  - crypto/shash.c:crypto_alloc_shash
  - crypto/akcipher.c:crypto_alloc_akcipher
  - crypto/kpp.c:crypto_alloc_kpp
  - crypto/acompress.c:crypto_alloc_acomp
  - crypto/rng.c:crypto_get_default_rng
```
**Symbols:**

```
ffffffe0003fe00a-ffffffe0003fe0cc: crypto_alloc_tfm (STB_GLOBAL)
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
void *crypto_alloc_tfm(const char *alg_name, const struct crypto_type *frontend, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff814b6fa0)
Location: crypto/api.c:524
Inline: False
Direct callers:
  - crypto/aead.c:crypto_alloc_aead
  - crypto/skcipher.c:crypto_alloc_sync_skcipher
  - crypto/skcipher.c:crypto_alloc_skcipher
  - crypto/ahash.c:crypto_alloc_ahash
  - crypto/shash.c:crypto_alloc_shash
  - crypto/akcipher.c:crypto_alloc_akcipher
  - crypto/kpp.c:crypto_alloc_kpp
  - crypto/acompress.c:crypto_alloc_acomp
  - crypto/rng.c:crypto_get_default_rng
```
**Symbols:**

```
ffffffff814b6fa0-ffffffff814b70a6: crypto_alloc_tfm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *crypto_alloc_tfm(const char *alg_name, const struct crypto_type *frontend, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff814a79c0)
Location: crypto/api.c:524
Inline: False
Direct callers:
  - crypto/aead.c:crypto_alloc_aead
  - crypto/skcipher.c:crypto_alloc_sync_skcipher
  - crypto/skcipher.c:crypto_alloc_skcipher
  - crypto/ahash.c:crypto_alloc_ahash
  - crypto/shash.c:crypto_alloc_shash
  - crypto/akcipher.c:crypto_alloc_akcipher
  - crypto/kpp.c:crypto_alloc_kpp
  - crypto/acompress.c:crypto_alloc_acomp
  - crypto/rng.c:crypto_get_default_rng
```
**Symbols:**

```
ffffffff814a79c0-ffffffff814a7ac6: crypto_alloc_tfm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *crypto_alloc_tfm(const char *alg_name, const struct crypto_type *frontend, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff814b3030)
Location: crypto/api.c:524
Inline: False
Direct callers:
  - crypto/aead.c:crypto_alloc_aead
  - crypto/skcipher.c:crypto_alloc_sync_skcipher
  - crypto/skcipher.c:crypto_alloc_skcipher
  - crypto/ahash.c:crypto_alloc_ahash
  - crypto/shash.c:crypto_alloc_shash
  - crypto/akcipher.c:crypto_alloc_akcipher
  - crypto/kpp.c:crypto_alloc_kpp
  - crypto/acompress.c:crypto_alloc_acomp
  - crypto/rng.c:crypto_get_default_rng
```
**Symbols:**

```
ffffffff814b3030-ffffffff814b3136: crypto_alloc_tfm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *crypto_alloc_tfm(const char *alg_name, const struct crypto_type *frontend, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff814cbab0)
Location: crypto/api.c:524
Inline: False
Direct callers:
  - crypto/aead.c:crypto_alloc_aead
  - crypto/skcipher.c:crypto_alloc_sync_skcipher
  - crypto/skcipher.c:crypto_alloc_skcipher
  - crypto/ahash.c:crypto_alloc_ahash
  - crypto/shash.c:crypto_alloc_shash
  - crypto/akcipher.c:crypto_alloc_akcipher
  - crypto/kpp.c:crypto_alloc_kpp
  - crypto/acompress.c:crypto_alloc_acomp
  - crypto/rng.c:crypto_get_default_rng
```
**Symbols:**

```
ffffffff814cbab0-ffffffff814cbbb6: crypto_alloc_tfm (STB_GLOBAL)
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
