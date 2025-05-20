# Function: <code>crypto_spawn_cipher</code>

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
In crypto/ecb.c (ffffffff813a9066)
Location: include/crypto/algapi.h:264
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_init_tfm
```
```
In crypto/cbc.c (ffffffff813a9236)
Location: include/crypto/algapi.h:264
Inline: True
Inline callers:
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
In crypto/ecb.c (ffffffff813e7036)
Location: include/crypto/algapi.h:340
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_init_tfm
```
```
In crypto/cbc.c (ffffffff813e71f6)
Location: include/crypto/algapi.h:340
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_init_tfm
```
```
In crypto/xts.c (ffffffff813e85e6)
Location: include/crypto/algapi.h:340
Inline: True
Inline callers:
  - crypto/xts.c:init_tfm
  - crypto/xts.c:init_tfm
```
```
In crypto/ctr.c (ffffffff813e8c76)
Location: include/crypto/algapi.h:340
Inline: True
Inline callers:
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
In crypto/ecb.c (ffffffff813ffde6)
Location: include/crypto/algapi.h:270
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_init_tfm
```
```
In crypto/cbc.c (ffffffff813fffd6)
Location: include/crypto/algapi.h:270
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_init_tfm
```
```
In crypto/ctr.c (ffffffff81402286)
Location: include/crypto/algapi.h:270
Inline: True
Inline callers:
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
In crypto/ecb.c (ffffffff8140d0f6)
Location: include/crypto/algapi.h:286
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_init_tfm
```
```
In crypto/cbc.c (ffffffff8140d2e6)
Location: include/crypto/algapi.h:286
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_init_tfm
```
```
In crypto/ctr.c (ffffffff8140f3a6)
Location: include/crypto/algapi.h:286
Inline: True
Inline callers:
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
In crypto/ecb.c (ffffffff81435b66)
Location: include/crypto/algapi.h:305
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_init_tfm
```
```
In crypto/cbc.c (ffffffff81435d56)
Location: include/crypto/algapi.h:305
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_init_tfm
```
```
In crypto/ctr.c (ffffffff81437db6)
Location: include/crypto/algapi.h:305
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_init_tfm
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
In crypto/ecb.c (ffffffff814686d5)
Location: include/crypto/algapi.h:312
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_init_tfm
```
```
In crypto/cbc.c (ffffffff814688e5)
Location: include/crypto/algapi.h:312
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_init_tfm
```
```
In crypto/ctr.c (ffffffff8146a715)
Location: include/crypto/algapi.h:312
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_init_tfm
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
In crypto/ecb.c (ffffffff81486345)
Location: include/crypto/algapi.h:314
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_init_tfm
```
```
In crypto/cbc.c (ffffffff81486555)
Location: include/crypto/algapi.h:314
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_init_tfm
```
```
In crypto/ctr.c (ffffffff81487f75)
Location: include/crypto/algapi.h:314
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_init_tfm
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff814a91f5)
Location: include/crypto/algapi.h:308
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_init_tfm_simple
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff814c3e65)
Location: include/crypto/algapi.h:308
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_init_tfm_simple
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff81522d65)
Location: include/crypto/algapi.h:217
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_init_tfm_simple
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff8153fcb5)
Location: include/crypto/algapi.h:217
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_init_tfm_simple
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff81548225)
Location: include/crypto/internal/cipher.h:204
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_init_tfm_simple
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff815a8a05)
Location: include/crypto/internal/cipher.h:204
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_init_tfm_simple
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff8164fde5)
Location: include/crypto/internal/cipher.h:204
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_init_tfm_simple
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff817092b5)
Location: include/crypto/internal/cipher.h:204
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_init_tfm_simple
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff81742af5)
Location: include/crypto/internal/cipher.h:206
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_init_tfm_simple
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
In crypto/skcipher.c (ffffffff81784d35)
Location: include/crypto/internal/cipher.h:206
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_init_tfm_simple
```
```
In crypto/ecb.c (ffffffff81792535)
Location: include/crypto/internal/cipher.h:206
Inline: True
Inline callers:
  - crypto/ecb.c:lskcipher_init_tfm_simple2
```
```
In crypto/xts.c (ffffffff81794135)
Location: include/crypto/internal/cipher.h:206
Inline: True
Inline callers:
  - crypto/xts.c:xts_init_tfm
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffff8000105be968)
Location: include/crypto/algapi.h:308
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_init_tfm_simple
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (c076c5d4)
Location: include/crypto/algapi.h:308
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_init_tfm_simple
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (c000000000746210)
Location: include/crypto/algapi.h:308
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_init_tfm_simple
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffe000403cb6)
Location: include/crypto/algapi.h:308
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_init_tfm_simple
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff814bc445)
Location: include/crypto/algapi.h:308
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_init_tfm_simple
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff814ace65)
Location: include/crypto/algapi.h:308
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_init_tfm_simple
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff814b84d5)
Location: include/crypto/algapi.h:308
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_init_tfm_simple
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff814d0fb5)
Location: include/crypto/algapi.h:308
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_init_tfm_simple
```
</details>
</li>
</ul>

## Differences
