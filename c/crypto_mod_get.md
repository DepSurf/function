# Function: <code>crypto_mod_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct crypto_alg *crypto_mod_get(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff8139c130)
Location: crypto/api.c:39
Inline: False
Direct callers:
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:__crypto_alg_lookup
  - crypto/algapi.c:__crypto_register_alg
  - crypto/algapi.c:crypto_alg_tested
  - crypto/algapi.c:crypto_register_instance
  - crypto/shash.c:crypto_init_shash_ops
  - crypto/shash.c:crypto_init_shash_ops_async
```
**Symbols:**

```
ffffffff8139c130-ffffffff8139c15c: crypto_mod_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct crypto_alg *crypto_mod_get(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff813d9020)
Location: crypto/api.c:39
Inline: False
Direct callers:
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:__crypto_alg_lookup
  - crypto/algapi.c:crypto_register_instance
  - crypto/algapi.c:crypto_alg_tested
  - crypto/algapi.c:__crypto_register_alg
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/shash.c:crypto_init_shash_ops_async
```
**Symbols:**

```
ffffffff813d9020-ffffffff813d904c: crypto_mod_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct crypto_alg *crypto_mod_get(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff813f0970)
Location: crypto/api.c:39
Inline: False
Direct callers:
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:__crypto_alg_lookup
  - crypto/algapi.c:crypto_register_instance
  - crypto/algapi.c:crypto_alg_tested
  - crypto/algapi.c:__crypto_register_alg
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/scompress.c:crypto_init_scomp_ops_async
```
**Symbols:**

```
ffffffff813f0970-ffffffff813f099c: crypto_mod_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct crypto_alg *crypto_mod_get(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff813fcc10)
Location: crypto/api.c:39
Inline: False
Direct callers:
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:__crypto_alg_lookup
  - crypto/algapi.c:crypto_register_instance
  - crypto/algapi.c:crypto_alg_tested
  - crypto/algapi.c:__crypto_register_alg
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/scompress.c:crypto_init_scomp_ops_async
```
**Symbols:**

```
ffffffff813fcc10-ffffffff813fcc3b: crypto_mod_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct crypto_alg *crypto_mod_get(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff81425140)
Location: crypto/api.c:40
Inline: False
Direct callers:
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:__crypto_alg_lookup
  - crypto/algapi.c:crypto_register_instance
  - crypto/algapi.c:crypto_alg_tested
  - crypto/algapi.c:__crypto_register_alg
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/scompress.c:crypto_init_scomp_ops_async
```
**Symbols:**

```
ffffffff81425140-ffffffff8142516b: crypto_mod_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct crypto_alg *crypto_mod_get(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff81457f10)
Location: crypto/api.c:40
Inline: False
Direct callers:
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:__crypto_alg_lookup
  - crypto/algapi.c:crypto_alg_tested
  - crypto/algapi.c:__crypto_register_alg
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/scompress.c:crypto_init_scomp_ops_async
```
**Symbols:**

```
ffffffff81457f10-ffffffff81457f42: crypto_mod_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct crypto_alg *crypto_mod_get(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff81475400)
Location: crypto/api.c:40
Inline: False
Direct callers:
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:__crypto_alg_lookup
  - crypto/algapi.c:crypto_alg_tested
  - crypto/algapi.c:__crypto_register_alg
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/scompress.c:crypto_init_scomp_ops_async
```
**Symbols:**

```
ffffffff81475400-ffffffff81475432: crypto_mod_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct crypto_alg *crypto_mod_get(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff814a3110)
Location: crypto/api.c:35
Inline: False
Direct callers:
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:__crypto_alg_lookup
  - crypto/algapi.c:crypto_alg_tested
  - crypto/algapi.c:__crypto_register_alg
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/scompress.c:crypto_init_scomp_ops_async
```
**Symbols:**

```
ffffffff814a3110-ffffffff814a3143: crypto_mod_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct crypto_alg *crypto_mod_get(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff814bdd50)
Location: crypto/api.c:35
Inline: False
Direct callers:
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:__crypto_alg_lookup
  - crypto/algapi.c:crypto_alg_tested
  - crypto/algapi.c:__crypto_register_alg
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/scompress.c:crypto_init_scomp_ops_async
```
**Symbols:**

```
ffffffff814bdd50-ffffffff814bdd83: crypto_mod_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct crypto_alg *crypto_mod_get(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff8151e7b0)
Location: crypto/api.c:35
Inline: False
Direct callers:
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:__crypto_alg_lookup
  - crypto/algapi.c:crypto_spawn_alg
  - crypto/algapi.c:crypto_alg_tested
  - crypto/algapi.c:__crypto_register_alg
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/scompress.c:crypto_init_scomp_ops_async
```
**Symbols:**

```
ffffffff8151e7b0-ffffffff8151e813: crypto_mod_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct crypto_alg *crypto_mod_get(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/api.c (ffffffff8153ba6e)
Location: crypto/api.c:35
Inline: True
Inline callers:
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:__crypto_alg_lookup
Direct callers:
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:__crypto_alg_lookup
  - crypto/algapi.c:crypto_spawn_alg
  - crypto/algapi.c:crypto_alg_tested
  - crypto/algapi.c:__crypto_register_alg
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/scompress.c:crypto_init_scomp_ops_async
```
**Symbols:**

```
ffffffff8153b540-ffffffff8153b598: crypto_mod_get.part.0 (STB_LOCAL)
ffffffff8153b5a0-ffffffff8153b5d2: crypto_mod_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct crypto_alg *crypto_mod_get(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/api.c (ffffffff8154415e)
Location: crypto/api.c:35
Inline: True
Inline callers:
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:__crypto_alg_lookup
Direct callers:
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:__crypto_alg_lookup
  - crypto/algapi.c:crypto_spawn_alg
  - crypto/algapi.c:crypto_alg_tested
  - crypto/algapi.c:__crypto_register_alg
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/scompress.c:crypto_init_scomp_ops_async
```
**Symbols:**

```
ffffffff81543c30-ffffffff81543c88: crypto_mod_get.part.0 (STB_LOCAL)
ffffffff81543c90-ffffffff81543cc2: crypto_mod_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct crypto_alg *crypto_mod_get(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/api.c (ffffffff815a48fe)
Location: crypto/api.c:35
Inline: True
Inline callers:
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:__crypto_alg_lookup
Direct callers:
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:__crypto_alg_lookup
  - crypto/algapi.c:crypto_spawn_alg
  - crypto/algapi.c:crypto_alg_tested
  - crypto/algapi.c:__crypto_register_alg
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/scompress.c:crypto_init_scomp_ops_async
```
**Symbols:**

```
ffffffff815a43d0-ffffffff815a4428: crypto_mod_get.part.0 (STB_LOCAL)
ffffffff815a4430-ffffffff815a4462: crypto_mod_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct crypto_alg *crypto_mod_get(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/api.c (ffffffff8164b732)
Location: crypto/api.c:39
Inline: True
Inline callers:
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:__crypto_alg_lookup
Direct callers:
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:__crypto_alg_lookup
  - crypto/algapi.c:crypto_spawn_alg
  - crypto/algapi.c:crypto_alg_tested
  - crypto/algapi.c:__crypto_register_alg
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/scompress.c:crypto_init_scomp_ops_async
```
**Symbols:**

```
ffffffff8164ada0-ffffffff8164ae13: crypto_mod_get.part.0 (STB_LOCAL)
ffffffff8164ae20-ffffffff8164ae57: crypto_mod_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct crypto_alg *crypto_mod_get(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/api.c (ffffffff817047e3)
Location: crypto/api.c:41
Inline: True
Inline callers:
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:__crypto_alg_lookup
Direct callers:
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:__crypto_alg_lookup
  - crypto/algapi.c:crypto_spawn_alg
  - crypto/algapi.c:crypto_alg_finish_registration
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/scompress.c:crypto_init_scomp_ops_async
```
**Symbols:**

```
ffffffff81703f70-ffffffff81703fe3: crypto_mod_get.part.0 (STB_LOCAL)
ffffffff81704000-ffffffff81704037: crypto_mod_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct crypto_alg *crypto_mod_get(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/api.c (ffffffff8173e59c)
Location: crypto/api.c:41
Inline: True
Inline callers:
  - crypto/api.c:crypto_clone_tfm
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:__crypto_alg_lookup
Direct callers:
  - crypto/api.c:crypto_clone_tfm
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:__crypto_alg_lookup
  - crypto/cipher.c:crypto_clone_cipher
  - crypto/algapi.c:crypto_spawn_alg
  - crypto/algapi.c:crypto_alg_finish_registration
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/akcipher.c:crypto_init_akcipher_ops_sig
  - crypto/scompress.c:crypto_init_scomp_ops_async
```
**Symbols:**

```
ffffffff8173df00-ffffffff8173df73: crypto_mod_get.part.0 (STB_LOCAL)
ffffffff8173df90-ffffffff8173dfc7: crypto_mod_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct crypto_alg *crypto_mod_get(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/api.c (ffffffff8177f41c)
Location: crypto/api.c:41
Inline: True
Inline callers:
  - crypto/api.c:crypto_clone_tfm
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:__crypto_alg_lookup
Direct callers:
  - crypto/api.c:crypto_clone_tfm
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:__crypto_alg_lookup
  - crypto/cipher.c:crypto_clone_cipher
  - crypto/algapi.c:crypto_spawn_alg
  - crypto/algapi.c:crypto_alg_finish_registration
  - crypto/lskcipher.c:crypto_init_lskcipher_ops_sg
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/akcipher.c:crypto_init_akcipher_ops_sig
  - crypto/scompress.c:crypto_init_scomp_ops_async
```
**Symbols:**

```
ffffffff8177ed60-ffffffff8177edd3: crypto_mod_get.part.0 (STB_LOCAL)
ffffffff8177edf0-ffffffff8177ee27: crypto_mod_get (STB_GLOBAL)
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
struct crypto_alg *crypto_mod_get(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffff8000105b6c38)
Location: crypto/api.c:35
Inline: False
Direct callers:
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:__crypto_alg_lookup
  - crypto/algapi.c:crypto_alg_tested
  - crypto/algapi.c:__crypto_register_alg
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/scompress.c:crypto_init_scomp_ops_async
```
**Symbols:**

```
ffff8000105b6c38-ffff8000105b6c88: crypto_mod_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct crypto_alg *crypto_mod_get(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (c0765bf0)
Location: crypto/api.c:35
Inline: False
Direct callers:
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:__crypto_alg_lookup
  - crypto/algapi.c:crypto_spawn_alg
  - crypto/algapi.c:crypto_alg_tested
  - crypto/algapi.c:__crypto_register_alg
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/scompress.c:crypto_init_scomp_ops_async
```
**Symbols:**

```
c0765bf0-c0765c28: crypto_mod_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct crypto_alg *crypto_mod_get(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/api.c (c00000000073be40)
Location: crypto/api.c:35
Inline: True
Inline callers:
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:__crypto_alg_lookup
Direct callers:
  - crypto/algapi.c:crypto_alg_tested
  - crypto/algapi.c:__crypto_register_alg
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/scompress.c:crypto_init_scomp_ops_async
```
**Symbols:**

```
c00000000073b2d0-c00000000073b358: crypto_mod_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct crypto_alg *crypto_mod_get(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffe0003fdcbe)
Location: crypto/api.c:35
Inline: True
Inline callers:
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:__crypto_alg_lookup
Direct callers:
  - crypto/algapi.c:crypto_alg_tested
  - crypto/algapi.c:__crypto_register_alg
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/scompress.c:crypto_init_scomp_ops_async
```
**Symbols:**

```
ffffffe0003fd780-ffffffe0003fd7c6: crypto_mod_get (STB_GLOBAL)
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
struct crypto_alg *crypto_mod_get(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff814b6330)
Location: crypto/api.c:35
Inline: False
Direct callers:
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:__crypto_alg_lookup
  - crypto/algapi.c:crypto_alg_tested
  - crypto/algapi.c:__crypto_register_alg
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/scompress.c:crypto_init_scomp_ops_async
```
**Symbols:**

```
ffffffff814b6330-ffffffff814b6363: crypto_mod_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct crypto_alg *crypto_mod_get(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff814a6d50)
Location: crypto/api.c:35
Inline: False
Direct callers:
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:__crypto_alg_lookup
  - crypto/algapi.c:crypto_alg_tested
  - crypto/algapi.c:__crypto_register_alg
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/scompress.c:crypto_init_scomp_ops_async
```
**Symbols:**

```
ffffffff814a6d50-ffffffff814a6d83: crypto_mod_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct crypto_alg *crypto_mod_get(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff814b23c0)
Location: crypto/api.c:35
Inline: False
Direct callers:
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:__crypto_alg_lookup
  - crypto/algapi.c:crypto_alg_tested
  - crypto/algapi.c:__crypto_register_alg
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/scompress.c:crypto_init_scomp_ops_async
```
**Symbols:**

```
ffffffff814b23c0-ffffffff814b23f3: crypto_mod_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct crypto_alg *crypto_mod_get(struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff814cae40)
Location: crypto/api.c:35
Inline: False
Direct callers:
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:__crypto_alg_lookup
  - crypto/algapi.c:crypto_alg_tested
  - crypto/algapi.c:__crypto_register_alg
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/scompress.c:crypto_init_scomp_ops_async
```
**Symbols:**

```
ffffffff814cae40-ffffffff814cae73: crypto_mod_get (STB_GLOBAL)
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
