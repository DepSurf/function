# Function: <code>crypto_cipher_clear_flags</code>

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
In crypto/ecb.c (ffffffff813a8e63)
Location: include/linux/crypto.h:1519
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_setkey
```
```
In crypto/cbc.c (ffffffff813a91b3)
Location: include/linux/crypto.h:1519
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
In crypto/ecb.c (ffffffff813e6e33)
Location: include/linux/crypto.h:1476
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_setkey
```
```
In crypto/cbc.c (ffffffff813e7173)
Location: include/linux/crypto.h:1476
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_setkey
```
```
In crypto/xts.c (ffffffff813e80e6)
Location: include/linux/crypto.h:1476
Inline: True
Inline callers:
  - crypto/xts.c:setkey
  - crypto/xts.c:setkey
```
```
In crypto/ctr.c (ffffffff813e87e3)
Location: include/linux/crypto.h:1476
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
In crypto/ecb.c (ffffffff813ffbe3)
Location: include/linux/crypto.h:1479
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_setkey
```
```
In crypto/cbc.c (ffffffff813fff23)
Location: include/linux/crypto.h:1479
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_setkey
```
```
In crypto/xts.c (ffffffff81401305)
Location: include/linux/crypto.h:1479
Inline: True
```
```
In crypto/ctr.c (ffffffff81401df3)
Location: include/linux/crypto.h:1479
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
In crypto/ecb.c (ffffffff8140ced3)
Location: include/linux/crypto.h:1479
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_setkey
```
```
In crypto/cbc.c (ffffffff8140d233)
Location: include/linux/crypto.h:1479
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_setkey
```
```
In crypto/xts.c (ffffffff8140e5bf)
Location: include/linux/crypto.h:1479
Inline: True
Inline callers:
  - crypto/xts.c:setkey
```
```
In crypto/ctr.c (ffffffff8140f1e3)
Location: include/linux/crypto.h:1479
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
In crypto/ecb.c (ffffffff81435933)
Location: include/linux/crypto.h:1527
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_setkey
```
```
In crypto/cbc.c (ffffffff81435ca3)
Location: include/linux/crypto.h:1527
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_setkey
```
```
In crypto/xts.c (ffffffff8143707f)
Location: include/linux/crypto.h:1527
Inline: True
Inline callers:
  - crypto/xts.c:setkey
```
```
In crypto/ctr.c (ffffffff81437cd3)
Location: include/linux/crypto.h:1527
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
In crypto/ecb.c (ffffffff814684c3)
Location: include/linux/crypto.h:1540
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_setkey
```
```
In crypto/cbc.c (ffffffff81468833)
Location: include/linux/crypto.h:1540
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_setkey
```
```
In crypto/xts.c (ffffffff81469aaa)
Location: include/linux/crypto.h:1540
Inline: True
```
```
In crypto/ctr.c (ffffffff8146a633)
Location: include/linux/crypto.h:1540
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
In crypto/ecb.c (ffffffff81486133)
Location: include/linux/crypto.h:1725
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_setkey
```
```
In crypto/cbc.c (ffffffff814864a3)
Location: include/linux/crypto.h:1725
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_setkey
```
```
In crypto/xts.c (ffffffff8148797a)
Location: include/linux/crypto.h:1725
Inline: True
```
```
In crypto/ctr.c (ffffffff81487e93)
Location: include/linux/crypto.h:1725
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
In crypto/skcipher.c (ffffffff814a8880)
Location: include/linux/crypto.h:1722
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
```
```
In crypto/xts.c (ffffffff814b568e)
Location: include/linux/crypto.h:1722
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
In crypto/skcipher.c (ffffffff814c34e0)
Location: include/linux/crypto.h:1722
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
```
```
In crypto/xts.c (ffffffff814ce88e)
Location: include/linux/crypto.h:1722
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
In crypto/skcipher.c (ffffffff81522dad)
Location: include/linux/crypto.h:823
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
```
```
In crypto/xts.c (ffffffff8152db96)
Location: include/linux/crypto.h:823
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
In crypto/skcipher.c (ffffffff8153fcfd)
Location: include/linux/crypto.h:859
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
```
```
In crypto/xts.c (ffffffff8154ab66)
Location: include/linux/crypto.h:859
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
In crypto/skcipher.c (ffffffff8154826d)
Location: include/crypto/internal/cipher.h:130
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
```
```
In crypto/xts.c (ffffffff81553186)
Location: include/crypto/internal/cipher.h:130
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
In crypto/skcipher.c (ffffffff815a8a4d)
Location: include/crypto/internal/cipher.h:130
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
```
```
In crypto/xts.c (ffffffff815b41b6)
Location: include/crypto/internal/cipher.h:130
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
In crypto/skcipher.c (ffffffff8164fe3d)
Location: include/crypto/internal/cipher.h:130
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
```
```
In crypto/xts.c (ffffffff8165d014)
Location: include/crypto/internal/cipher.h:130
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
In crypto/skcipher.c (ffffffff8170931d)
Location: include/crypto/internal/cipher.h:130
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
```
```
In crypto/xts.c (ffffffff81716af4)
Location: include/crypto/internal/cipher.h:130
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
In crypto/skcipher.c (ffffffff81742b5d)
Location: include/crypto/internal/cipher.h:130
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
```
```
In crypto/xts.c (ffffffff817523a4)
Location: include/crypto/internal/cipher.h:130
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
In crypto/skcipher.c (ffffffff81784d9d)
Location: include/crypto/internal/cipher.h:130
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
```
```
In crypto/ecb.c (ffffffff8179259d)
Location: include/crypto/internal/cipher.h:130
Inline: True
Inline callers:
  - crypto/ecb.c:lskcipher_setkey_simple2
```
```
In crypto/xts.c (ffffffff81794234)
Location: include/crypto/internal/cipher.h:130
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
In crypto/skcipher.c (ffff8000105bdd10)
Location: include/linux/crypto.h:1722
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
```
```
In crypto/xts.c (ffff8000105caa84)
Location: include/linux/crypto.h:1722
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
In crypto/skcipher.c (c076bb4c)
Location: include/linux/crypto.h:1722
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
```
```
In crypto/xts.c (c077866c)
Location: include/linux/crypto.h:1722
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
In crypto/skcipher.c (c000000000745200)
Location: include/linux/crypto.h:1722
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
```
```
In crypto/xts.c (c00000000075540c)
Location: include/linux/crypto.h:1722
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
In crypto/skcipher.c (ffffffe000403222)
Location: include/linux/crypto.h:1722
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
```
```
In crypto/xts.c (ffffffe00040ec8c)
Location: include/linux/crypto.h:1722
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
In crypto/skcipher.c (ffffffff814bbac0)
Location: include/linux/crypto.h:1722
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
```
```
In crypto/xts.c (ffffffff814c6e6e)
Location: include/linux/crypto.h:1722
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
In crypto/skcipher.c (ffffffff814ac4e0)
Location: include/linux/crypto.h:1722
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
```
```
In crypto/xts.c (ffffffff814b788e)
Location: include/linux/crypto.h:1722
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
In crypto/skcipher.c (ffffffff814b7b50)
Location: include/linux/crypto.h:1722
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
```
```
In crypto/xts.c (ffffffff814c2efe)
Location: include/linux/crypto.h:1722
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
In crypto/skcipher.c (ffffffff814d0630)
Location: include/linux/crypto.h:1722
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
```
```
In crypto/xts.c (ffffffff814db9ce)
Location: include/linux/crypto.h:1722
Inline: True
```
</details>
</li>
</ul>

## Differences
