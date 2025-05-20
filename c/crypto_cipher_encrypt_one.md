# Function: <code>crypto_cipher_encrypt_one</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff81782d05)
Location: include/linux/crypto.h:1557
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
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
In crypto/ctr.c (ffffffff813e8ac9)
Location: include/linux/crypto.h:1514
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/drbg.c (ffffffff813ec164)
Location: include/linux/crypto.h:1514
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (ffffffff817f0344)
Location: include/linux/crypto.h:1514
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
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
In crypto/cbc.c (ffffffff813fff6b)
Location: include/linux/crypto.h:1517
Inline: True
```
```
In crypto/xts.c (ffffffff814011b3)
Location: include/linux/crypto.h:1517
Inline: True
Inline callers:
  - crypto/xts.c:init_crypt
```
```
In crypto/ctr.c (ffffffff814020d9)
Location: include/linux/crypto.h:1517
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/drbg.c (ffffffff814059a4)
Location: include/linux/crypto.h:1517
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81820d83)
Location: include/linux/crypto.h:1517
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
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
In fs/crypto/crypto.c (ffffffff812ac33f)
Location: include/linux/crypto.h:1517
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
```
```
In crypto/cbc.c (ffffffff8140d27b)
Location: include/linux/crypto.h:1517
Inline: True
```
```
In crypto/xts.c (ffffffff8140e562)
Location: include/linux/crypto.h:1517
Inline: True
Inline callers:
  - crypto/xts.c:init_crypt
```
```
In crypto/ctr.c (ffffffff8140f977)
Location: include/linux/crypto.h:1517
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/drbg.c (ffffffff81413114)
Location: include/linux/crypto.h:1517
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81840fb7)
Location: include/linux/crypto.h:1517
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
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
In fs/crypto/crypto.c (ffffffff812cfb4f)
Location: include/linux/crypto.h:1565
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
```
```
In crypto/cbc.c (ffffffff81435ceb)
Location: include/linux/crypto.h:1565
Inline: True
```
```
In crypto/xts.c (ffffffff81437022)
Location: include/linux/crypto.h:1565
Inline: True
Inline callers:
  - crypto/xts.c:init_crypt
```
```
In crypto/ctr.c (ffffffff81438484)
Location: include/linux/crypto.h:1565
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/drbg.c (ffffffff8143d8ba)
Location: include/linux/crypto.h:1565
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (ffffffff818c09dd)
Location: include/linux/crypto.h:1565
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
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
In fs/crypto/crypto.c (ffffffff812fa431)
Location: include/linux/crypto.h:1578
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
```
```
In crypto/cbc.c (ffffffff81468875)
Location: include/linux/crypto.h:1578
Inline: True
```
```
In crypto/xts.c (ffffffff81469952)
Location: include/linux/crypto.h:1578
Inline: True
Inline callers:
  - crypto/xts.c:init_crypt
```
```
In crypto/ctr.c (ffffffff8146ae90)
Location: include/linux/crypto.h:1578
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/drbg.c (ffffffff814706ea)
Location: include/linux/crypto.h:1578
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819165fc)
Location: include/linux/crypto.h:1578
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
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
In fs/crypto/crypto.c (ffffffff8130f5aa)
Location: include/linux/crypto.h:1763
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_generate_iv
```
```
In crypto/cbc.c (ffffffff814864e5)
Location: include/linux/crypto.h:1763
Inline: True
```
```
In crypto/xts.c (ffffffff81487896)
Location: include/linux/crypto.h:1763
Inline: True
```
```
In crypto/ctr.c (ffffffff814886f0)
Location: include/linux/crypto.h:1763
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/drbg.c (ffffffff8148d87a)
Location: include/linux/crypto.h:1763
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81944d9c)
Location: include/linux/crypto.h:1763
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
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
In fs/crypto/crypto.c (ffffffff81336aca)
Location: include/linux/crypto.h:1760
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_generate_iv
```
```
In crypto/cbc.c (ffffffff814b4505)
Location: include/linux/crypto.h:1760
Inline: True
```
```
In crypto/xts.c (ffffffff814b556e)
Location: include/linux/crypto.h:1760
Inline: True
```
```
In crypto/ctr.c (ffffffff814b611f)
Location: include/linux/crypto.h:1760
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/drbg.c (ffffffff814bb1f3)
Location: include/linux/crypto.h:1760
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
In fs/crypto/crypto.c (ffffffff8134a642)
Location: include/linux/crypto.h:1760
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_generate_iv
```
```
In crypto/cbc.c (ffffffff814cd275)
Location: include/linux/crypto.h:1760
Inline: True
```
```
In crypto/xts.c (ffffffff814ce0d8)
Location: include/linux/crypto.h:1760
Inline: True
Inline callers:
  - crypto/xts.c:init_crypt
```
```
In crypto/ctr.c (ffffffff814cf31f)
Location: include/linux/crypto.h:1760
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/drbg.c (ffffffff814d3e83)
Location: include/linux/crypto.h:1760
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void crypto_cipher_encrypt_one(struct crypto_cipher *tfm, u8 *dst, const u8 *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cipher.c (ffffffff8151f280)
Location: crypto/cipher.c:79
Inline: False
Direct callers:
  - crypto/xts.c:decrypt
  - crypto/xts.c:encrypt
  - crypto/ctr.c:crypto_ctr_crypt
```
**Symbols:**

```
ffffffff8151f280-ffffffff8151f32b: crypto_cipher_encrypt_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void crypto_cipher_encrypt_one(struct crypto_cipher *tfm, u8 *dst, const u8 *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cipher.c (ffffffff8153c0e0)
Location: crypto/cipher.c:79
Inline: False
Direct callers:
  - crypto/xts.c:xts_decrypt
  - crypto/xts.c:xts_encrypt
  - crypto/ctr.c:crypto_ctr_crypt
```
**Symbols:**

```
ffffffff8153c0e0-ffffffff8153c18b: crypto_cipher_encrypt_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void crypto_cipher_encrypt_one(struct crypto_cipher *tfm, u8 *dst, const u8 *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cipher.c (ffffffff815447d0)
Location: crypto/cipher.c:80
Inline: False
Direct callers:
  - crypto/xts.c:xts_decrypt
  - crypto/xts.c:xts_encrypt
  - crypto/ctr.c:crypto_ctr_crypt
```
**Symbols:**

```
ffffffff815447d0-ffffffff8154487b: crypto_cipher_encrypt_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void crypto_cipher_encrypt_one(struct crypto_cipher *tfm, u8 *dst, const u8 *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cipher.c (ffffffff815a4f70)
Location: crypto/cipher.c:80
Inline: False
Direct callers:
  - crypto/xts.c:xts_decrypt
  - crypto/xts.c:xts_encrypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
```
**Symbols:**

```
ffffffff815a4f70-ffffffff815a501b: crypto_cipher_encrypt_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void crypto_cipher_encrypt_one(struct crypto_cipher *tfm, u8 *dst, const u8 *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cipher.c (ffffffff8164bcf0)
Location: crypto/cipher.c:80
Inline: False
Direct callers:
  - crypto/xts.c:xts_decrypt
  - crypto/xts.c:xts_encrypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
```
**Symbols:**

```
ffffffff8164bcf0-ffffffff8164bdce: crypto_cipher_encrypt_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void crypto_cipher_encrypt_one(struct crypto_cipher *tfm, u8 *dst, const u8 *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cipher.c (ffffffff81704ed0)
Location: crypto/cipher.c:80
Inline: False
Direct callers:
  - crypto/xts.c:xts_decrypt
  - crypto/xts.c:xts_encrypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
```
**Symbols:**

```
ffffffff81704ed0-ffffffff81704ef1: crypto_cipher_encrypt_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void crypto_cipher_encrypt_one(struct crypto_cipher *tfm, u8 *dst, const u8 *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cipher.c (ffffffff8173f1a0)
Location: crypto/cipher.c:80
Inline: False
Direct callers:
  - crypto/xts.c:xts_decrypt
  - crypto/xts.c:xts_encrypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
```
**Symbols:**

```
ffffffff8173f1a0-ffffffff8173f1c1: crypto_cipher_encrypt_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void crypto_cipher_encrypt_one(struct crypto_cipher *tfm, u8 *dst, const u8 *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/cipher.c (ffffffff81780020)
Location: crypto/cipher.c:80
Inline: False
Direct callers:
  - crypto/xts.c:xts_decrypt
  - crypto/xts.c:xts_encrypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
```
**Symbols:**

```
ffffffff81780020-ffffffff81780041: crypto_cipher_encrypt_one (STB_GLOBAL)
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
In fs/crypto/crypto.c (ffff80001040ae30)
Location: include/linux/crypto.h:1760
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_generate_iv
```
```
In crypto/cbc.c (ffff8000105c910c)
Location: include/linux/crypto.h:1760
Inline: True
```
```
In crypto/xts.c (ffff8000105c9ff0)
Location: include/linux/crypto.h:1760
Inline: True
Inline callers:
  - crypto/xts.c:init_crypt
```
```
In crypto/ctr.c (ffff8000105cb2c4)
Location: include/linux/crypto.h:1760
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/drbg.c (ffff8000105d099c)
Location: include/linux/crypto.h:1760
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
In fs/crypto/crypto.c (c05d7fbc)
Location: include/linux/crypto.h:1760
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_generate_iv
```
```
In crypto/cbc.c (c0776eb4)
Location: include/linux/crypto.h:1760
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_encrypt
  - crypto/cbc.c:crypto_cbc_encrypt
```
```
In crypto/xts.c (c0777b00)
Location: include/linux/crypto.h:1760
Inline: True
Inline callers:
  - crypto/xts.c:init_crypt
```
```
In crypto/ctr.c (c0778df4)
Location: include/linux/crypto.h:1760
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/drbg.c (c077eb50)
Location: include/linux/crypto.h:1760
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
In fs/crypto/crypto.c (c0000000005177ec)
Location: include/linux/crypto.h:1760
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_generate_iv
```
```
In crypto/cbc.c (c0000000007535f8)
Location: include/linux/crypto.h:1760
Inline: True
```
```
In crypto/xts.c (c0000000007549a4)
Location: include/linux/crypto.h:1760
Inline: True
Inline callers:
  - crypto/xts.c:init_crypt
```
```
In crypto/ctr.c (c0000000007562c4)
Location: include/linux/crypto.h:1760
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/drbg.c (c00000000075dc24)
Location: include/linux/crypto.h:1760
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
In fs/crypto/crypto.c (ffffffe0002b4b60)
Location: include/linux/crypto.h:1760
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_generate_iv
```
```
In crypto/cbc.c (ffffffe00040da40)
Location: include/linux/crypto.h:1760
Inline: True
```
```
In crypto/xts.c (ffffffe00040e61a)
Location: include/linux/crypto.h:1760
Inline: True
Inline callers:
  - crypto/xts.c:init_crypt
```
```
In crypto/ctr.c (ffffffe00040f43c)
Location: include/linux/crypto.h:1760
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/drbg.c (ffffffe000415daa)
Location: include/linux/crypto.h:1760
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
In fs/crypto/crypto.c (ffffffff81342c22)
Location: include/linux/crypto.h:1760
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_generate_iv
```
```
In crypto/cbc.c (ffffffff814c5855)
Location: include/linux/crypto.h:1760
Inline: True
```
```
In crypto/xts.c (ffffffff814c66b8)
Location: include/linux/crypto.h:1760
Inline: True
Inline callers:
  - crypto/xts.c:init_crypt
```
```
In crypto/ctr.c (ffffffff814c78ff)
Location: include/linux/crypto.h:1760
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/drbg.c (ffffffff814cc463)
Location: include/linux/crypto.h:1760
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
In fs/crypto/crypto.c (ffffffff81333902)
Location: include/linux/crypto.h:1760
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_generate_iv
```
```
In crypto/cbc.c (ffffffff814b6275)
Location: include/linux/crypto.h:1760
Inline: True
```
```
In crypto/xts.c (ffffffff814b70d8)
Location: include/linux/crypto.h:1760
Inline: True
Inline callers:
  - crypto/xts.c:init_crypt
```
```
In crypto/ctr.c (ffffffff814b831f)
Location: include/linux/crypto.h:1760
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/drbg.c (ffffffff814bce83)
Location: include/linux/crypto.h:1760
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
In fs/crypto/crypto.c (ffffffff813406f2)
Location: include/linux/crypto.h:1760
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_generate_iv
```
```
In crypto/cbc.c (ffffffff814c18e5)
Location: include/linux/crypto.h:1760
Inline: True
```
```
In crypto/xts.c (ffffffff814c2748)
Location: include/linux/crypto.h:1760
Inline: True
Inline callers:
  - crypto/xts.c:init_crypt
```
```
In crypto/ctr.c (ffffffff814c398f)
Location: include/linux/crypto.h:1760
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/drbg.c (ffffffff814c84f3)
Location: include/linux/crypto.h:1760
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
In fs/crypto/crypto.c (ffffffff813539f2)
Location: include/linux/crypto.h:1760
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_generate_iv
```
```
In crypto/cbc.c (ffffffff814da3b5)
Location: include/linux/crypto.h:1760
Inline: True
```
```
In crypto/xts.c (ffffffff814db218)
Location: include/linux/crypto.h:1760
Inline: True
Inline callers:
  - crypto/xts.c:init_crypt
```
```
In crypto/ctr.c (ffffffff814dc45f)
Location: include/linux/crypto.h:1760
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/drbg.c (ffffffff814e0fc3)
Location: include/linux/crypto.h:1760
Inline: True
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
