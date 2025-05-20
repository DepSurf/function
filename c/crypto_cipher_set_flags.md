# Function: <code>crypto_cipher_set_flags</code>

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
In crypto/ecb.c (ffffffff813a8e6c)
Location: include/linux/crypto.h:1513
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_setkey
```
```
In crypto/cbc.c (ffffffff813a91bc)
Location: include/linux/crypto.h:1513
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_setkey
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
In crypto/ecb.c (ffffffff813e6e47)
Location: include/linux/crypto.h:1470
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_setkey
```
```
In crypto/cbc.c (ffffffff813e7187)
Location: include/linux/crypto.h:1470
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_setkey
```
```
In crypto/xts.c (ffffffff813e80fc)
Location: include/linux/crypto.h:1470
Inline: True
Inline callers:
  - crypto/xts.c:setkey
  - crypto/xts.c:setkey
```
```
In crypto/ctr.c (ffffffff813e87f7)
Location: include/linux/crypto.h:1470
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_setkey
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
In crypto/ecb.c (ffffffff813ffbf7)
Location: include/linux/crypto.h:1473
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_setkey
```
```
In crypto/cbc.c (ffffffff813fff38)
Location: include/linux/crypto.h:1473
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_setkey
```
```
In crypto/xts.c (ffffffff8140131e)
Location: include/linux/crypto.h:1473
Inline: True
```
```
In crypto/ctr.c (ffffffff81401e07)
Location: include/linux/crypto.h:1473
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_setkey
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
In crypto/ecb.c (ffffffff8140cee7)
Location: include/linux/crypto.h:1473
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_setkey
```
```
In crypto/cbc.c (ffffffff8140d248)
Location: include/linux/crypto.h:1473
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_setkey
```
```
In crypto/xts.c (ffffffff8140e5d8)
Location: include/linux/crypto.h:1473
Inline: True
Inline callers:
  - crypto/xts.c:setkey
```
```
In crypto/ctr.c (ffffffff8140f1f7)
Location: include/linux/crypto.h:1473
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_setkey
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
In crypto/ecb.c (ffffffff81435947)
Location: include/linux/crypto.h:1521
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_setkey
```
```
In crypto/cbc.c (ffffffff81435cb8)
Location: include/linux/crypto.h:1521
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_setkey
```
```
In crypto/xts.c (ffffffff81437098)
Location: include/linux/crypto.h:1521
Inline: True
Inline callers:
  - crypto/xts.c:setkey
```
```
In crypto/ctr.c (ffffffff81437ce7)
Location: include/linux/crypto.h:1521
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_setkey
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
In crypto/ecb.c (ffffffff814684cd)
Location: include/linux/crypto.h:1534
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_setkey
```
```
In crypto/cbc.c (ffffffff8146883d)
Location: include/linux/crypto.h:1534
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_setkey
```
```
In crypto/xts.c (ffffffff81469abe)
Location: include/linux/crypto.h:1534
Inline: True
```
```
In crypto/ctr.c (ffffffff8146a63d)
Location: include/linux/crypto.h:1534
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_setkey
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
In crypto/ecb.c (ffffffff8148613d)
Location: include/linux/crypto.h:1719
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_setkey
```
```
In crypto/cbc.c (ffffffff814864ad)
Location: include/linux/crypto.h:1719
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_setkey
```
```
In crypto/xts.c (ffffffff8148798e)
Location: include/linux/crypto.h:1719
Inline: True
```
```
In crypto/ctr.c (ffffffff81487e9d)
Location: include/linux/crypto.h:1719
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_setkey
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
In crypto/skcipher.c (ffffffff814a8891)
Location: include/linux/crypto.h:1716
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
```
```
In crypto/xts.c (ffffffff814b56a2)
Location: include/linux/crypto.h:1716
Inline: True
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
In crypto/skcipher.c (ffffffff814c34f1)
Location: include/linux/crypto.h:1716
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
```
```
In crypto/xts.c (ffffffff814ce8a2)
Location: include/linux/crypto.h:1716
Inline: True
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
In crypto/skcipher.c (ffffffff81522dbd)
Location: include/linux/crypto.h:817
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
```
```
In crypto/xts.c (ffffffff8152dba3)
Location: include/linux/crypto.h:817
Inline: True
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
In crypto/skcipher.c (ffffffff8153fd0d)
Location: include/linux/crypto.h:853
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
```
```
In crypto/xts.c (ffffffff8154ab73)
Location: include/linux/crypto.h:853
Inline: True
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
In crypto/skcipher.c (ffffffff8154827a)
Location: include/crypto/internal/cipher.h:124
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
```
```
In crypto/xts.c (ffffffff81553193)
Location: include/crypto/internal/cipher.h:124
Inline: True
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
In crypto/skcipher.c (ffffffff815a8a5a)
Location: include/crypto/internal/cipher.h:124
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
```
```
In crypto/xts.c (ffffffff815b41c3)
Location: include/crypto/internal/cipher.h:124
Inline: True
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
In crypto/skcipher.c (ffffffff8164fe4a)
Location: include/crypto/internal/cipher.h:124
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
```
```
In crypto/xts.c (ffffffff8165d021)
Location: include/crypto/internal/cipher.h:124
Inline: True
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
In crypto/skcipher.c (ffffffff8170932a)
Location: include/crypto/internal/cipher.h:124
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
```
```
In crypto/xts.c (ffffffff81716b01)
Location: include/crypto/internal/cipher.h:124
Inline: True
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
In crypto/skcipher.c (ffffffff81742b6c)
Location: include/crypto/internal/cipher.h:124
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
```
```
In crypto/xts.c (ffffffff817523b3)
Location: include/crypto/internal/cipher.h:124
Inline: True
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
In crypto/skcipher.c (ffffffff81784dac)
Location: include/crypto/internal/cipher.h:124
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
```
```
In crypto/ecb.c (ffffffff817925ac)
Location: include/crypto/internal/cipher.h:124
Inline: True
Inline callers:
  - crypto/ecb.c:lskcipher_setkey_simple2
```
```
In crypto/xts.c (ffffffff81794243)
Location: include/crypto/internal/cipher.h:124
Inline: True
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
In crypto/skcipher.c (ffff8000105bdd2c)
Location: include/linux/crypto.h:1716
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
```
```
In crypto/xts.c (ffff8000105caaa0)
Location: include/linux/crypto.h:1716
Inline: True
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
In crypto/skcipher.c (c076bb70)
Location: include/linux/crypto.h:1716
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
```
```
In crypto/xts.c (c0778698)
Location: include/linux/crypto.h:1716
Inline: True
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
In crypto/skcipher.c (c000000000745218)
Location: include/linux/crypto.h:1716
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
```
```
In crypto/xts.c (c000000000755424)
Location: include/linux/crypto.h:1716
Inline: True
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
In crypto/skcipher.c (ffffffe00040323c)
Location: include/linux/crypto.h:1716
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
```
```
In crypto/xts.c (ffffffe00040eca8)
Location: include/linux/crypto.h:1716
Inline: True
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
In crypto/skcipher.c (ffffffff814bbad1)
Location: include/linux/crypto.h:1716
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
```
```
In crypto/xts.c (ffffffff814c6e82)
Location: include/linux/crypto.h:1716
Inline: True
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
In crypto/skcipher.c (ffffffff814ac4f1)
Location: include/linux/crypto.h:1716
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
```
```
In crypto/xts.c (ffffffff814b78a2)
Location: include/linux/crypto.h:1716
Inline: True
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
In crypto/skcipher.c (ffffffff814b7b61)
Location: include/linux/crypto.h:1716
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
```
```
In crypto/xts.c (ffffffff814c2f12)
Location: include/linux/crypto.h:1716
Inline: True
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
In crypto/skcipher.c (ffffffff814d0641)
Location: include/linux/crypto.h:1716
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
```
```
In crypto/xts.c (ffffffff814db9e2)
Location: include/linux/crypto.h:1716
Inline: True
```
</details>
</li>
</ul>

## Differences
