# Function: <code>crypto_cipher_tfm</code>

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
In crypto/ecb.c (ffffffff813a9046)
Location: include/linux/crypto.h:1450
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_exit_tfm
```
```
In crypto/cbc.c (ffffffff813a9216)
Location: include/linux/crypto.h:1450
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_exit_tfm
```
```
In net/ipv4/tcp_fastopen.c (ffffffff817826cd)
Location: include/linux/crypto.h:1450
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_ctx_free
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
In crypto/ecb.c (ffffffff813e7016)
Location: include/linux/crypto.h:1407
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_exit_tfm
```
```
In crypto/cbc.c (ffffffff813e71d6)
Location: include/linux/crypto.h:1407
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_exit_tfm
```
```
In crypto/xts.c (ffffffff813e85bd)
Location: include/linux/crypto.h:1407
Inline: True
Inline callers:
  - crypto/xts.c:exit_tfm
  - crypto/xts.c:exit_tfm
  - crypto/xts.c:init_tfm
  - crypto/xts.c:init_tfm
```
```
In crypto/ctr.c (ffffffff813e8c36)
Location: include/linux/crypto.h:1407
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_exit_tfm
```
```
In crypto/drbg.c (0)
Location: include/linux/crypto.h:1407
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (ffffffff817efe73)
Location: include/linux/crypto.h:1407
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_reset_cipher
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_ctx_free
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
In crypto/ecb.c (ffffffff813ffdc6)
Location: include/linux/crypto.h:1410
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_exit_tfm
```
```
In crypto/cbc.c (ffffffff813fffb6)
Location: include/linux/crypto.h:1410
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_exit_tfm
```
```
In crypto/xts.c (ffffffff814011fa)
Location: include/linux/crypto.h:1410
Inline: True
Inline callers:
  - crypto/xts.c:exit_tfm
```
```
In crypto/ctr.c (ffffffff81402246)
Location: include/linux/crypto.h:1410
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_exit_tfm
```
```
In crypto/drbg.c (0)
Location: include/linux/crypto.h:1410
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81820883)
Location: include/linux/crypto.h:1410
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_reset_cipher
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_ctx_free
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
In fs/crypto/crypto.c (0)
Location: include/linux/crypto.h:1410
Inline: True
```
```
In fs/crypto/keyinfo.c (ffffffff812ad81a)
Location: include/linux/crypto.h:1410
Inline: True
```
```
In crypto/ecb.c (ffffffff8140d0d6)
Location: include/linux/crypto.h:1410
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_exit_tfm
```
```
In crypto/cbc.c (ffffffff8140d2c6)
Location: include/linux/crypto.h:1410
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_exit_tfm
```
```
In crypto/xts.c (ffffffff8140e68a)
Location: include/linux/crypto.h:1410
Inline: True
Inline callers:
  - crypto/xts.c:exit_tfm
```
```
In crypto/ctr.c (ffffffff8140f366)
Location: include/linux/crypto.h:1410
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_exit_tfm
```
```
In crypto/drbg.c (0)
Location: include/linux/crypto.h:1410
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81840d93)
Location: include/linux/crypto.h:1410
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_reset_cipher
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_ctx_free
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
In fs/crypto/crypto.c (0)
Location: include/linux/crypto.h:1458
Inline: True
```
```
In fs/crypto/keyinfo.c (ffffffff812d0d0a)
Location: include/linux/crypto.h:1458
Inline: True
```
```
In crypto/ecb.c (ffffffff81435b46)
Location: include/linux/crypto.h:1458
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_exit_tfm
```
```
In crypto/cbc.c (ffffffff81435d36)
Location: include/linux/crypto.h:1458
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_exit_tfm
```
```
In crypto/xts.c (ffffffff8143715a)
Location: include/linux/crypto.h:1458
Inline: True
Inline callers:
  - crypto/xts.c:exit_tfm
```
```
In crypto/ctr.c (ffffffff81437d76)
Location: include/linux/crypto.h:1458
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_exit_tfm
```
```
In crypto/drbg.c (0)
Location: include/linux/crypto.h:1458
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (ffffffff818c061a)
Location: include/linux/crypto.h:1458
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_reset_cipher
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_ctx_free
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
Location: include/linux/crypto.h:1471
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
```
```
In fs/crypto/keyinfo.c (ffffffff812fb85a)
Location: include/linux/crypto.h:1471
Inline: True
```
```
In crypto/ecb.c (ffffffff814686b5)
Location: include/linux/crypto.h:1471
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_exit_tfm
  - crypto/ecb.c:crypto_ecb_setkey
```
```
In crypto/cbc.c (ffffffff814688c5)
Location: include/linux/crypto.h:1471
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_exit_tfm
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_setkey
```
```
In crypto/xts.c (ffffffff8146998a)
Location: include/linux/crypto.h:1471
Inline: True
Inline callers:
  - crypto/xts.c:exit_tfm
  - crypto/xts.c:init_crypt
```
```
In crypto/ctr.c (ffffffff8146a6d5)
Location: include/linux/crypto.h:1471
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_exit_tfm
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_setkey
```
```
In crypto/drbg.c (ffffffff8146fc16)
Location: include/linux/crypto.h:1471
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819165fc)
Location: include/linux/crypto.h:1471
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_reset_cipher
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_reset_cipher
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_ctx_free
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
Location: include/linux/crypto.h:1656
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_generate_iv
```
```
In fs/crypto/keyinfo.c (ffffffff813110a7)
Location: include/linux/crypto.h:1656
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:put_crypt_info
```
```
In crypto/ecb.c (ffffffff81486325)
Location: include/linux/crypto.h:1656
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_exit_tfm
  - crypto/ecb.c:crypto_ecb_setkey
```
```
In crypto/cbc.c (ffffffff81486535)
Location: include/linux/crypto.h:1656
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_exit_tfm
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_setkey
```
```
In crypto/xts.c (ffffffff8148774a)
Location: include/linux/crypto.h:1656
Inline: True
Inline callers:
  - crypto/xts.c:exit_tfm
```
```
In crypto/ctr.c (ffffffff81487f35)
Location: include/linux/crypto.h:1656
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_exit_tfm
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_setkey
```
```
In crypto/drbg.c (ffffffff8148d5f6)
Location: include/linux/crypto.h:1656
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81944d9c)
Location: include/linux/crypto.h:1656
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_reset_cipher
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_reset_cipher
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_ctx_free
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
Location: include/linux/crypto.h:1653
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_generate_iv
```
```
In fs/crypto/keyinfo.c (ffffffff81338426)
Location: include/linux/crypto.h:1653
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:put_crypt_info
```
```
In crypto/skcipher.c (ffffffff814a8f35)
Location: include/linux/crypto.h:1653
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_exit_tfm_simple
  - crypto/skcipher.c:skcipher_setkey_simple
```
```
In crypto/ecb.c (0)
Location: include/linux/crypto.h:1653
Inline: True
```
```
In crypto/cbc.c (ffffffff814b466e)
Location: include/linux/crypto.h:1653
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
```
```
In crypto/xts.c (ffffffff814b543a)
Location: include/linux/crypto.h:1653
Inline: True
Inline callers:
  - crypto/xts.c:exit_tfm
```
```
In crypto/ctr.c (ffffffff814b611f)
Location: include/linux/crypto.h:1653
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/drbg.c (ffffffff814baf76)
Location: include/linux/crypto.h:1653
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
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
In fs/crypto/crypto.c (ffffffff8134a642)
Location: include/linux/crypto.h:1653
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_generate_iv
```
```
In fs/crypto/keysetup.c (ffffffff8134d6c0)
Location: include/linux/crypto.h:1653
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:put_crypt_info
  - fs/crypto/keysetup.c:fscrypt_set_derived_key
```
```
In crypto/skcipher.c (ffffffff814c3b95)
Location: include/linux/crypto.h:1653
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_exit_tfm_simple
  - crypto/skcipher.c:skcipher_setkey_simple
```
```
In crypto/ecb.c (0)
Location: include/linux/crypto.h:1653
Inline: True
```
```
In crypto/cbc.c (ffffffff814cd3de)
Location: include/linux/crypto.h:1653
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
```
```
In crypto/xts.c (ffffffff814ce68a)
Location: include/linux/crypto.h:1653
Inline: True
Inline callers:
  - crypto/xts.c:exit_tfm
  - crypto/xts.c:init_crypt
```
```
In crypto/ctr.c (ffffffff814cf31f)
Location: include/linux/crypto.h:1653
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/drbg.c (ffffffff814d3d46)
Location: include/linux/crypto.h:1653
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
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
In crypto/cipher.c (ffffffff8151f4a8)
Location: include/linux/crypto.h:759
Inline: True
Inline callers:
  - crypto/cipher.c:crypto_cipher_decrypt_one
  - crypto/cipher.c:crypto_cipher_encrypt_one
  - crypto/cipher.c:crypto_cipher_setkey
  - crypto/cipher.c:setkey_unaligned
```
```
In crypto/skcipher.c (ffffffff81522c25)
Location: include/linux/crypto.h:759
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_exit_tfm_simple
```
```
In crypto/ecb.c (ffffffff8152c599)
Location: include/linux/crypto.h:759
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_crypt
```
```
In crypto/xts.c (ffffffff8152da8a)
Location: include/linux/crypto.h:759
Inline: True
Inline callers:
  - crypto/xts.c:exit_tfm
```
```
In crypto/ctr.c (ffffffff8152e511)
Location: include/linux/crypto.h:759
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/drbg.c (ffffffff81533096)
Location: include/linux/crypto.h:759
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
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
In crypto/cipher.c (ffffffff8153c308)
Location: include/linux/crypto.h:795
Inline: True
Inline callers:
  - crypto/cipher.c:crypto_cipher_decrypt_one
  - crypto/cipher.c:crypto_cipher_encrypt_one
  - crypto/cipher.c:crypto_cipher_setkey
  - crypto/cipher.c:setkey_unaligned
```
```
In crypto/skcipher.c (ffffffff8153fb75)
Location: include/linux/crypto.h:795
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_exit_tfm_simple
```
```
In crypto/ecb.c (ffffffff81549589)
Location: include/linux/crypto.h:795
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_crypt
```
```
In crypto/cbc.c (ffffffff815499e7)
Location: include/linux/crypto.h:795
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt_inplace
  - crypto/cbc.c:crypto_cbc_decrypt_segment
```
```
In crypto/xts.c (ffffffff8154aa5a)
Location: include/linux/crypto.h:795
Inline: True
Inline callers:
  - crypto/xts.c:xts_exit_tfm
```
```
In crypto/ctr.c (ffffffff8154b4b1)
Location: include/linux/crypto.h:795
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/drbg.c (ffffffff8154ffe6)
Location: include/linux/crypto.h:795
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
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
In crypto/cipher.c (ffffffff815449f8)
Location: include/crypto/internal/cipher.h:66
Inline: True
Inline callers:
  - crypto/cipher.c:crypto_cipher_decrypt_one
  - crypto/cipher.c:crypto_cipher_encrypt_one
  - crypto/cipher.c:crypto_cipher_setkey
  - crypto/cipher.c:setkey_unaligned
```
```
In crypto/skcipher.c (ffffffff815480e5)
Location: include/crypto/internal/cipher.h:66
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_exit_tfm_simple
```
```
In crypto/ecb.c (ffffffff81551c84)
Location: include/crypto/internal/cipher.h:66
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_crypt
```
```
In crypto/cbc.c (ffffffff815520fd)
Location: include/crypto/internal/cipher.h:66
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
```
```
In crypto/xts.c (ffffffff8155307a)
Location: include/crypto/internal/cipher.h:66
Inline: True
Inline callers:
  - crypto/xts.c:xts_exit_tfm
```
```
In crypto/ctr.c (ffffffff81553ad0)
Location: include/crypto/internal/cipher.h:66
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/drbg.c (ffffffff815587e6)
Location: include/crypto/internal/cipher.h:66
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
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
In crypto/cipher.c (ffffffff815a5198)
Location: include/crypto/internal/cipher.h:66
Inline: True
Inline callers:
  - crypto/cipher.c:crypto_cipher_decrypt_one
  - crypto/cipher.c:crypto_cipher_encrypt_one
  - crypto/cipher.c:crypto_cipher_setkey
  - crypto/cipher.c:setkey_unaligned
```
```
In crypto/skcipher.c (ffffffff815a88c5)
Location: include/crypto/internal/cipher.h:66
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_exit_tfm_simple
```
```
In crypto/ecb.c (ffffffff815b2c84)
Location: include/crypto/internal/cipher.h:66
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_crypt
```
```
In crypto/cbc.c (ffffffff815b30fd)
Location: include/crypto/internal/cipher.h:66
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
```
```
In crypto/xts.c (ffffffff815b40aa)
Location: include/crypto/internal/cipher.h:66
Inline: True
Inline callers:
  - crypto/xts.c:xts_exit_tfm
```
```
In crypto/ctr.c (ffffffff815b4b00)
Location: include/crypto/internal/cipher.h:66
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/drbg.c (ffffffff815b9a96)
Location: include/crypto/internal/cipher.h:66
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
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
In crypto/cipher.c (ffffffff8164be87)
Location: include/crypto/internal/cipher.h:66
Inline: True
Inline callers:
  - crypto/cipher.c:crypto_cipher_decrypt_one
  - crypto/cipher.c:crypto_cipher_encrypt_one
  - crypto/cipher.c:crypto_cipher_setkey
  - crypto/cipher.c:setkey_unaligned
```
```
In crypto/skcipher.c (ffffffff8164fc65)
Location: include/crypto/internal/cipher.h:66
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_exit_tfm_simple
```
```
In crypto/ecb.c (ffffffff8165b7f6)
Location: include/crypto/internal/cipher.h:66
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_crypt
```
```
In crypto/cbc.c (ffffffff8165bd60)
Location: include/crypto/internal/cipher.h:66
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt_inplace
```
```
In crypto/xts.c (ffffffff8165ceea)
Location: include/crypto/internal/cipher.h:66
Inline: True
Inline callers:
  - crypto/xts.c:xts_exit_tfm
```
```
In crypto/ctr.c (ffffffff8165da41)
Location: include/crypto/internal/cipher.h:66
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/drbg.c (ffffffff81663066)
Location: include/crypto/internal/cipher.h:66
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
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
In crypto/cipher.c (ffffffff81704e8c)
Location: include/crypto/internal/cipher.h:66
Inline: True
Inline callers:
  - crypto/cipher.c:cipher_crypt_one
  - crypto/cipher.c:crypto_cipher_setkey
  - crypto/cipher.c:setkey_unaligned
```
```
In crypto/skcipher.c (ffffffff817090e5)
Location: include/crypto/internal/cipher.h:66
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_exit_tfm_simple
```
```
In crypto/ecb.c (ffffffff81714fc6)
Location: include/crypto/internal/cipher.h:66
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_crypt
```
```
In crypto/cbc.c (ffffffff817155ab)
Location: include/crypto/internal/cipher.h:66
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt_inplace
  - crypto/cbc.c:crypto_cbc_decrypt_segment
  - crypto/cbc.c:crypto_cbc_encrypt_inplace
  - crypto/cbc.c:crypto_cbc_encrypt_segment
```
```
In crypto/xts.c (ffffffff8171699a)
Location: include/crypto/internal/cipher.h:66
Inline: True
Inline callers:
  - crypto/xts.c:xts_exit_tfm
```
```
In crypto/ctr.c (ffffffff817175d1)
Location: include/crypto/internal/cipher.h:66
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/drbg.c (ffffffff8171d2b6)
Location: include/crypto/internal/cipher.h:66
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
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
In crypto/cipher.c (ffffffff8173f15c)
Location: include/crypto/internal/cipher.h:66
Inline: True
Inline callers:
  - crypto/cipher.c:cipher_crypt_one
  - crypto/cipher.c:cipher_crypt_one
  - crypto/cipher.c:crypto_cipher_setkey
  - crypto/cipher.c:setkey_unaligned
```
```
In crypto/skcipher.c (ffffffff81742935)
Location: include/crypto/internal/cipher.h:66
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_exit_tfm_simple
```
```
In crypto/ecb.c (ffffffff81750876)
Location: include/crypto/internal/cipher.h:66
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_crypt
```
```
In crypto/cbc.c (ffffffff81750e5b)
Location: include/crypto/internal/cipher.h:66
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt_inplace
  - crypto/cbc.c:crypto_cbc_decrypt_segment
  - crypto/cbc.c:crypto_cbc_encrypt_inplace
  - crypto/cbc.c:crypto_cbc_encrypt_segment
```
```
In crypto/xts.c (ffffffff8175224a)
Location: include/crypto/internal/cipher.h:66
Inline: True
Inline callers:
  - crypto/xts.c:xts_exit_tfm
```
```
In crypto/ctr.c (ffffffff81752ef1)
Location: include/crypto/internal/cipher.h:66
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/drbg.c (ffffffff81758b46)
Location: include/crypto/internal/cipher.h:66
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
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
In crypto/cipher.c (ffffffff8177ffdc)
Location: include/crypto/internal/cipher.h:66
Inline: True
Inline callers:
  - crypto/cipher.c:cipher_crypt_one
  - crypto/cipher.c:cipher_crypt_one
  - crypto/cipher.c:crypto_cipher_setkey
  - crypto/cipher.c:setkey_unaligned
```
```
In crypto/skcipher.c (ffffffff81784c25)
Location: include/crypto/internal/cipher.h:66
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_exit_tfm_simple
```
```
In crypto/ecb.c (ffffffff81792505)
Location: include/crypto/internal/cipher.h:66
Inline: True
Inline callers:
  - crypto/ecb.c:lskcipher_exit_tfm_simple2
  - crypto/ecb.c:crypto_ecb_decrypt2
  - crypto/ecb.c:crypto_ecb_encrypt2
```
```
In crypto/xts.c (ffffffff817940ca)
Location: include/crypto/internal/cipher.h:66
Inline: True
Inline callers:
  - crypto/xts.c:xts_exit_tfm
```
```
In crypto/ctr.c (ffffffff81794e91)
Location: include/crypto/internal/cipher.h:66
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/drbg.c (ffffffff8179aa46)
Location: include/crypto/internal/cipher.h:66
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
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
Location: include/linux/crypto.h:1653
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_generate_iv
```
```
In fs/crypto/keysetup.c (ffff80001040e734)
Location: include/linux/crypto.h:1653
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:put_crypt_info
  - fs/crypto/keysetup.c:fscrypt_set_derived_key
```
```
In crypto/skcipher.c (ffff8000105be538)
Location: include/linux/crypto.h:1653
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_exit_tfm_simple
  - crypto/skcipher.c:skcipher_setkey_simple
```
```
In crypto/ecb.c (0)
Location: include/linux/crypto.h:1653
Inline: True
```
```
In crypto/cbc.c (ffff8000105c927c)
Location: include/linux/crypto.h:1653
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
```
```
In crypto/xts.c (ffff8000105ca524)
Location: include/linux/crypto.h:1653
Inline: True
Inline callers:
  - crypto/xts.c:exit_tfm
  - crypto/xts.c:init_crypt
```
```
In crypto/ctr.c (ffff8000105cb2c4)
Location: include/linux/crypto.h:1653
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/drbg.c (ffff8000105d07d8)
Location: include/linux/crypto.h:1653
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
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
In fs/crypto/crypto.c (c05d7fbc)
Location: include/linux/crypto.h:1653
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_generate_iv
```
```
In fs/crypto/keysetup.c (c05db20c)
Location: include/linux/crypto.h:1653
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:put_crypt_info
  - fs/crypto/keysetup.c:fscrypt_set_derived_key
```
```
In crypto/skcipher.c (c076c2a0)
Location: include/linux/crypto.h:1653
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_exit_tfm_simple
  - crypto/skcipher.c:skcipher_setkey_simple
```
```
In crypto/ecb.c (0)
Location: include/linux/crypto.h:1653
Inline: True
```
```
In crypto/cbc.c (c0776fec)
Location: include/linux/crypto.h:1653
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_encrypt
  - crypto/cbc.c:crypto_cbc_encrypt
```
```
In crypto/xts.c (c0778154)
Location: include/linux/crypto.h:1653
Inline: True
Inline callers:
  - crypto/xts.c:exit_tfm
  - crypto/xts.c:init_crypt
```
```
In crypto/ctr.c (c0778df4)
Location: include/linux/crypto.h:1653
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/drbg.c (c077e170)
Location: include/linux/crypto.h:1653
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
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
In fs/crypto/crypto.c (c0000000005177ec)
Location: include/linux/crypto.h:1653
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_generate_iv
```
```
In fs/crypto/keysetup.c (c00000000051bd08)
Location: include/linux/crypto.h:1653
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:put_crypt_info
  - fs/crypto/keysetup.c:fscrypt_set_derived_key
```
```
In crypto/skcipher.c (c000000000745cfc)
Location: include/linux/crypto.h:1653
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_exit_tfm_simple
  - crypto/skcipher.c:skcipher_setkey_simple
```
```
In crypto/ecb.c (0)
Location: include/linux/crypto.h:1653
Inline: True
```
```
In crypto/cbc.c (c0000000007537c8)
Location: include/linux/crypto.h:1653
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
```
```
In crypto/xts.c (c0000000007550b4)
Location: include/linux/crypto.h:1653
Inline: True
Inline callers:
  - crypto/xts.c:exit_tfm
  - crypto/xts.c:init_crypt
```
```
In crypto/ctr.c (c0000000007562c4)
Location: include/linux/crypto.h:1653
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/drbg.c (c00000000075cb74)
Location: include/linux/crypto.h:1653
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
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
In fs/crypto/crypto.c (ffffffe0002b4b60)
Location: include/linux/crypto.h:1653
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_generate_iv
```
```
In fs/crypto/keysetup.c (ffffffe0002b77d6)
Location: include/linux/crypto.h:1653
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:put_crypt_info
  - fs/crypto/keysetup.c:fscrypt_set_derived_key
```
```
In crypto/skcipher.c (ffffffe00040394a)
Location: include/linux/crypto.h:1653
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_exit_tfm_simple
  - crypto/skcipher.c:skcipher_setkey_simple
```
```
In crypto/ecb.c (0)
Location: include/linux/crypto.h:1653
Inline: True
```
```
In crypto/cbc.c (ffffffe00040db56)
Location: include/linux/crypto.h:1653
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
```
```
In crypto/xts.c (ffffffe00040ea80)
Location: include/linux/crypto.h:1653
Inline: True
Inline callers:
  - crypto/xts.c:exit_tfm
  - crypto/xts.c:init_crypt
```
```
In crypto/ctr.c (ffffffe00040f44c)
Location: include/linux/crypto.h:1653
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/drbg.c (ffffffe00041542c)
Location: include/linux/crypto.h:1653
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
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
In fs/crypto/crypto.c (ffffffff81342c22)
Location: include/linux/crypto.h:1653
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_generate_iv
```
```
In fs/crypto/keysetup.c (ffffffff81345ca0)
Location: include/linux/crypto.h:1653
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:put_crypt_info
  - fs/crypto/keysetup.c:fscrypt_set_derived_key
```
```
In crypto/skcipher.c (ffffffff814bc175)
Location: include/linux/crypto.h:1653
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_exit_tfm_simple
  - crypto/skcipher.c:skcipher_setkey_simple
```
```
In crypto/ecb.c (0)
Location: include/linux/crypto.h:1653
Inline: True
```
```
In crypto/cbc.c (ffffffff814c59be)
Location: include/linux/crypto.h:1653
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
```
```
In crypto/xts.c (ffffffff814c6c6a)
Location: include/linux/crypto.h:1653
Inline: True
Inline callers:
  - crypto/xts.c:exit_tfm
  - crypto/xts.c:init_crypt
```
```
In crypto/ctr.c (ffffffff814c78ff)
Location: include/linux/crypto.h:1653
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/drbg.c (ffffffff814cc326)
Location: include/linux/crypto.h:1653
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
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
In fs/crypto/crypto.c (ffffffff81333902)
Location: include/linux/crypto.h:1653
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_generate_iv
```
```
In fs/crypto/keysetup.c (ffffffff81336980)
Location: include/linux/crypto.h:1653
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:put_crypt_info
  - fs/crypto/keysetup.c:fscrypt_set_derived_key
```
```
In crypto/skcipher.c (ffffffff814acb95)
Location: include/linux/crypto.h:1653
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_exit_tfm_simple
  - crypto/skcipher.c:skcipher_setkey_simple
```
```
In crypto/ecb.c (0)
Location: include/linux/crypto.h:1653
Inline: True
```
```
In crypto/cbc.c (ffffffff814b63de)
Location: include/linux/crypto.h:1653
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
```
```
In crypto/xts.c (ffffffff814b768a)
Location: include/linux/crypto.h:1653
Inline: True
Inline callers:
  - crypto/xts.c:exit_tfm
  - crypto/xts.c:init_crypt
```
```
In crypto/ctr.c (ffffffff814b831f)
Location: include/linux/crypto.h:1653
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/drbg.c (ffffffff814bcd46)
Location: include/linux/crypto.h:1653
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
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
In fs/crypto/crypto.c (ffffffff813406f2)
Location: include/linux/crypto.h:1653
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_generate_iv
```
```
In fs/crypto/keysetup.c (ffffffff81343770)
Location: include/linux/crypto.h:1653
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:put_crypt_info
  - fs/crypto/keysetup.c:fscrypt_set_derived_key
```
```
In crypto/skcipher.c (ffffffff814b8205)
Location: include/linux/crypto.h:1653
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_exit_tfm_simple
  - crypto/skcipher.c:skcipher_setkey_simple
```
```
In crypto/ecb.c (0)
Location: include/linux/crypto.h:1653
Inline: True
```
```
In crypto/cbc.c (ffffffff814c1a4e)
Location: include/linux/crypto.h:1653
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
```
```
In crypto/xts.c (ffffffff814c2cfa)
Location: include/linux/crypto.h:1653
Inline: True
Inline callers:
  - crypto/xts.c:exit_tfm
  - crypto/xts.c:init_crypt
```
```
In crypto/ctr.c (ffffffff814c398f)
Location: include/linux/crypto.h:1653
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/drbg.c (ffffffff814c83b6)
Location: include/linux/crypto.h:1653
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
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
In fs/crypto/crypto.c (ffffffff813539f2)
Location: include/linux/crypto.h:1653
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_generate_iv
```
```
In fs/crypto/keysetup.c (ffffffff81356a0e)
Location: include/linux/crypto.h:1653
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:put_crypt_info
  - fs/crypto/keysetup.c:fscrypt_set_derived_key
```
```
In crypto/skcipher.c (ffffffff814d0ce5)
Location: include/linux/crypto.h:1653
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_exit_tfm_simple
  - crypto/skcipher.c:skcipher_setkey_simple
```
```
In crypto/ecb.c (0)
Location: include/linux/crypto.h:1653
Inline: True
```
```
In crypto/cbc.c (ffffffff814da51e)
Location: include/linux/crypto.h:1653
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
```
```
In crypto/xts.c (ffffffff814db7ca)
Location: include/linux/crypto.h:1653
Inline: True
Inline callers:
  - crypto/xts.c:exit_tfm
  - crypto/xts.c:init_crypt
```
```
In crypto/ctr.c (ffffffff814dc45f)
Location: include/linux/crypto.h:1653
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
```
```
In crypto/drbg.c (ffffffff814e0e86)
Location: include/linux/crypto.h:1653
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
  - crypto/drbg.c:drbg_ctr_df
  - crypto/drbg.c:drbg_ctr_df
```
</details>
</li>
</ul>

## Differences
