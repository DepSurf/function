# Function: <code>crypto_cipher_setkey</code>

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
In crypto/ecb.c (ffffffff813a8e6e)
Location: include/linux/crypto.h:1541
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_setkey
```
```
In crypto/cbc.c (ffffffff813a91be)
Location: include/linux/crypto.h:1541
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_setkey
```
```
In net/ipv4/tcp_fastopen.c (ffffffff8178274a)
Location: include/linux/crypto.h:1541
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_reset_cipher
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
In crypto/ecb.c (ffffffff813e6e3f)
Location: include/linux/crypto.h:1498
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_setkey
```
```
In crypto/cbc.c (ffffffff813e717f)
Location: include/linux/crypto.h:1498
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_setkey
```
```
In crypto/xts.c (ffffffff813e80e1)
Location: include/linux/crypto.h:1498
Inline: True
Inline callers:
  - crypto/xts.c:setkey
  - crypto/xts.c:setkey
```
```
In crypto/ctr.c (ffffffff813e87ef)
Location: include/linux/crypto.h:1498
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_setkey
```
```
In crypto/drbg.c (ffffffff813ed2fb)
Location: include/linux/crypto.h:1498
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
```
```
In net/ipv4/tcp_fastopen.c (ffffffff817efdda)
Location: include/linux/crypto.h:1498
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_reset_cipher
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
In crypto/ecb.c (ffffffff813ffbef)
Location: include/linux/crypto.h:1501
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_setkey
```
```
In crypto/cbc.c (ffffffff813fff30)
Location: include/linux/crypto.h:1501
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_setkey
```
```
In crypto/xts.c (ffffffff814012ff)
Location: include/linux/crypto.h:1501
Inline: True
```
```
In crypto/ctr.c (ffffffff81401dff)
Location: include/linux/crypto.h:1501
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_setkey
```
```
In crypto/drbg.c (ffffffff81406b3b)
Location: include/linux/crypto.h:1501
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
```
```
In net/ipv4/tcp_fastopen.c (ffffffff818207ea)
Location: include/linux/crypto.h:1501
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_reset_cipher
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
In fs/crypto/keyinfo.c (ffffffff812adfd5)
Location: include/linux/crypto.h:1501
Inline: True
```
```
In crypto/ecb.c (ffffffff8140cedf)
Location: include/linux/crypto.h:1501
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_setkey
```
```
In crypto/cbc.c (ffffffff8140d240)
Location: include/linux/crypto.h:1501
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_setkey
```
```
In crypto/xts.c (ffffffff8140e5bc)
Location: include/linux/crypto.h:1501
Inline: True
Inline callers:
  - crypto/xts.c:setkey
```
```
In crypto/ctr.c (ffffffff8140f1ef)
Location: include/linux/crypto.h:1501
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_setkey
```
```
In crypto/drbg.c (ffffffff814143b8)
Location: include/linux/crypto.h:1501
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81840cfa)
Location: include/linux/crypto.h:1501
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_reset_cipher
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
In fs/crypto/keyinfo.c (ffffffff812d14b9)
Location: include/linux/crypto.h:1549
Inline: True
```
```
In crypto/ecb.c (ffffffff8143593f)
Location: include/linux/crypto.h:1549
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_setkey
```
```
In crypto/cbc.c (ffffffff81435cb0)
Location: include/linux/crypto.h:1549
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_setkey
```
```
In crypto/xts.c (ffffffff8143707c)
Location: include/linux/crypto.h:1549
Inline: True
Inline callers:
  - crypto/xts.c:setkey
```
```
In crypto/ctr.c (ffffffff81437cdf)
Location: include/linux/crypto.h:1549
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_setkey
```
```
In crypto/drbg.c (ffffffff8143eb65)
Location: include/linux/crypto.h:1549
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
```
```
In net/ipv4/tcp_fastopen.c (ffffffff818c055b)
Location: include/linux/crypto.h:1549
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_reset_cipher
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
In fs/crypto/keyinfo.c (ffffffff812fbef3)
Location: include/linux/crypto.h:1562
Inline: True
```
```
In crypto/ecb.c (ffffffff814684db)
Location: include/linux/crypto.h:1562
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_setkey
```
```
In crypto/cbc.c (ffffffff8146884c)
Location: include/linux/crypto.h:1562
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_setkey
```
```
In crypto/xts.c (ffffffff81469acf)
Location: include/linux/crypto.h:1562
Inline: True
```
```
In crypto/ctr.c (ffffffff8146a64b)
Location: include/linux/crypto.h:1562
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_setkey
```
```
In crypto/drbg.c (ffffffff81471a10)
Location: include/linux/crypto.h:1562
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819160ab)
Location: include/linux/crypto.h:1562
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_reset_cipher
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
In fs/crypto/keyinfo.c (ffffffff81311746)
Location: include/linux/crypto.h:1747
Inline: True
```
```
In crypto/ecb.c (ffffffff8148614b)
Location: include/linux/crypto.h:1747
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_setkey
```
```
In crypto/cbc.c (ffffffff814864bc)
Location: include/linux/crypto.h:1747
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_setkey
```
```
In crypto/xts.c (ffffffff8148799f)
Location: include/linux/crypto.h:1747
Inline: True
```
```
In crypto/ctr.c (ffffffff81487eab)
Location: include/linux/crypto.h:1747
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_setkey
```
```
In crypto/drbg.c (ffffffff8148eba0)
Location: include/linux/crypto.h:1747
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
```
```
In net/ipv4/tcp_fastopen.c (ffffffff8194484b)
Location: include/linux/crypto.h:1747
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_reset_cipher
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
In fs/crypto/keyinfo.c (ffffffff81338a14)
Location: include/linux/crypto.h:1744
Inline: True
```
```
In crypto/skcipher.c (ffffffff814a88a2)
Location: include/linux/crypto.h:1744
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
```
```
In crypto/xts.c (ffffffff814b56b3)
Location: include/linux/crypto.h:1744
Inline: True
```
```
In crypto/drbg.c (ffffffff814bc4fa)
Location: include/linux/crypto.h:1744
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
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
In fs/crypto/keysetup.c (ffffffff8134d98a)
Location: include/linux/crypto.h:1744
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_set_derived_key
```
```
In crypto/skcipher.c (ffffffff814c3502)
Location: include/linux/crypto.h:1744
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
```
```
In crypto/xts.c (ffffffff814ce8b3)
Location: include/linux/crypto.h:1744
Inline: True
```
```
In crypto/drbg.c (ffffffff814d518a)
Location: include/linux/crypto.h:1744
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int crypto_cipher_setkey(struct crypto_cipher *tfm, const u8 *key, unsigned int keylen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cipher.c (ffffffff8151f3e0)
Location: crypto/cipher.c:42
Inline: False
Direct callers:
  - crypto/skcipher.c:skcipher_setkey_simple
  - crypto/drbg.c:drbg_ctr_df
```
**Symbols:**

```
ffffffff8151f3e0-ffffffff8151f420: crypto_cipher_setkey (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int crypto_cipher_setkey(struct crypto_cipher *tfm, const u8 *key, unsigned int keylen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cipher.c (ffffffff8153c240)
Location: crypto/cipher.c:42
Inline: False
Direct callers:
  - crypto/skcipher.c:skcipher_setkey_simple
  - crypto/drbg.c:drbg_ctr_df
```
**Symbols:**

```
ffffffff8153c240-ffffffff8153c280: crypto_cipher_setkey (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int crypto_cipher_setkey(struct crypto_cipher *tfm, const u8 *key, unsigned int keylen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cipher.c (ffffffff81544930)
Location: crypto/cipher.c:43
Inline: False
Direct callers:
  - crypto/skcipher.c:skcipher_setkey_simple
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
```
**Symbols:**

```
ffffffff81544930-ffffffff81544970: crypto_cipher_setkey (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int crypto_cipher_setkey(struct crypto_cipher *tfm, const u8 *key, unsigned int keylen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cipher.c (ffffffff815a50d0)
Location: crypto/cipher.c:43
Inline: False
Direct callers:
  - crypto/skcipher.c:skcipher_setkey_simple
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
```
**Symbols:**

```
ffffffff815a50d0-ffffffff815a5110: crypto_cipher_setkey (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int crypto_cipher_setkey(struct crypto_cipher *tfm, const u8 *key, unsigned int keylen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cipher.c (ffffffff8164bc80)
Location: crypto/cipher.c:43
Inline: False
Direct callers:
  - crypto/skcipher.c:skcipher_setkey_simple
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
```
**Symbols:**

```
ffffffff8164bc80-ffffffff8164bce4: crypto_cipher_setkey (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int crypto_cipher_setkey(struct crypto_cipher *tfm, const u8 *key, unsigned int keylen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cipher.c (ffffffff81705010)
Location: crypto/cipher.c:43
Inline: False
Direct callers:
  - crypto/skcipher.c:skcipher_setkey_simple
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
```
**Symbols:**

```
ffffffff81705010-ffffffff81705074: crypto_cipher_setkey (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int crypto_cipher_setkey(struct crypto_cipher *tfm, const u8 *key, unsigned int keylen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cipher.c (ffffffff8173f2e0)
Location: crypto/cipher.c:43
Inline: False
Direct callers:
  - crypto/skcipher.c:skcipher_setkey_simple
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
```
**Symbols:**

```
ffffffff8173f2e0-ffffffff8173f344: crypto_cipher_setkey (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int crypto_cipher_setkey(struct crypto_cipher *tfm, const u8 *key, unsigned int keylen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cipher.c (ffffffff81780160)
Location: crypto/cipher.c:43
Inline: False
Direct callers:
  - crypto/skcipher.c:skcipher_setkey_simple
  - crypto/ecb.c:lskcipher_setkey_simple2
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
```
**Symbols:**

```
ffffffff81780160-ffffffff817801c4: crypto_cipher_setkey (STB_GLOBAL)
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
In fs/crypto/keysetup.c (ffff80001040ec60)
Location: include/linux/crypto.h:1744
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_set_derived_key
```
```
In crypto/skcipher.c (ffff8000105bdd3c)
Location: include/linux/crypto.h:1744
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
```
```
In crypto/xts.c (ffff8000105caab0)
Location: include/linux/crypto.h:1744
Inline: True
```
```
In crypto/drbg.c (ffff8000105d2680)
Location: include/linux/crypto.h:1744
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
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
In fs/crypto/keysetup.c (c05db774)
Location: include/linux/crypto.h:1744
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_set_derived_key
```
```
In crypto/skcipher.c (c076bb80)
Location: include/linux/crypto.h:1744
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
```
```
In crypto/xts.c (c07786a8)
Location: include/linux/crypto.h:1744
Inline: True
```
```
In crypto/drbg.c (c077edb8)
Location: include/linux/crypto.h:1744
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
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
In fs/crypto/keysetup.c (c00000000051c2d0)
Location: include/linux/crypto.h:1744
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_set_derived_key
```
```
In crypto/skcipher.c (c000000000745228)
Location: include/linux/crypto.h:1744
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
```
```
In crypto/xts.c (c000000000755434)
Location: include/linux/crypto.h:1744
Inline: True
```
```
In crypto/drbg.c (c00000000075df58)
Location: include/linux/crypto.h:1744
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
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
In fs/crypto/keysetup.c (ffffffe0002b7a9a)
Location: include/linux/crypto.h:1744
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_set_derived_key
```
```
In crypto/skcipher.c (ffffffe00040323e)
Location: include/linux/crypto.h:1744
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
```
```
In crypto/xts.c (ffffffe00040ecaa)
Location: include/linux/crypto.h:1744
Inline: True
```
```
In crypto/drbg.c (ffffffe000416f78)
Location: include/linux/crypto.h:1744
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
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
In fs/crypto/keysetup.c (ffffffff81345f6a)
Location: include/linux/crypto.h:1744
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_set_derived_key
```
```
In crypto/skcipher.c (ffffffff814bbae2)
Location: include/linux/crypto.h:1744
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
```
```
In crypto/xts.c (ffffffff814c6e93)
Location: include/linux/crypto.h:1744
Inline: True
```
```
In crypto/drbg.c (ffffffff814cd76a)
Location: include/linux/crypto.h:1744
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
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
In fs/crypto/keysetup.c (ffffffff81336c4a)
Location: include/linux/crypto.h:1744
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_set_derived_key
```
```
In crypto/skcipher.c (ffffffff814ac502)
Location: include/linux/crypto.h:1744
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
```
```
In crypto/xts.c (ffffffff814b78b3)
Location: include/linux/crypto.h:1744
Inline: True
```
```
In crypto/drbg.c (ffffffff814be18a)
Location: include/linux/crypto.h:1744
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
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
In fs/crypto/keysetup.c (ffffffff81343a3a)
Location: include/linux/crypto.h:1744
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_set_derived_key
```
```
In crypto/skcipher.c (ffffffff814b7b72)
Location: include/linux/crypto.h:1744
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
```
```
In crypto/xts.c (ffffffff814c2f23)
Location: include/linux/crypto.h:1744
Inline: True
```
```
In crypto/drbg.c (ffffffff814c97fa)
Location: include/linux/crypto.h:1744
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
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
In fs/crypto/keysetup.c (ffffffff81356d1a)
Location: include/linux/crypto.h:1744
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_set_derived_key
```
```
In crypto/skcipher.c (ffffffff814d0652)
Location: include/linux/crypto.h:1744
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_simple
```
```
In crypto/xts.c (ffffffff814db9f3)
Location: include/linux/crypto.h:1744
Inline: True
```
```
In crypto/drbg.c (ffffffff814e22ca)
Location: include/linux/crypto.h:1744
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
