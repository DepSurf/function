# Function: <code>crypto_free_cipher</code>

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
Location: include/linux/crypto.h:1459
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_exit_tfm
```
```
In crypto/cbc.c (ffffffff813a9216)
Location: include/linux/crypto.h:1459
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_exit_tfm
```
```
In net/ipv4/tcp_fastopen.c (ffffffff817826cd)
Location: include/linux/crypto.h:1459
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
Location: include/linux/crypto.h:1416
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_exit_tfm
```
```
In crypto/cbc.c (ffffffff813e71d6)
Location: include/linux/crypto.h:1416
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_exit_tfm
```
```
In crypto/xts.c (ffffffff813e85bd)
Location: include/linux/crypto.h:1416
Inline: True
Inline callers:
  - crypto/xts.c:exit_tfm
  - crypto/xts.c:exit_tfm
  - crypto/xts.c:init_tfm
  - crypto/xts.c:init_tfm
  - crypto/xts.c:init_tfm
  - crypto/xts.c:init_tfm
```
```
In crypto/ctr.c (ffffffff813e8c36)
Location: include/linux/crypto.h:1416
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_exit_tfm
```
```
In crypto/drbg.c (ffffffff813eb776)
Location: include/linux/crypto.h:1416
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
```
```
In net/ipv4/tcp_fastopen.c (ffffffff817efe73)
Location: include/linux/crypto.h:1416
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
Location: include/linux/crypto.h:1419
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_exit_tfm
```
```
In crypto/cbc.c (ffffffff813fffb6)
Location: include/linux/crypto.h:1419
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_exit_tfm
```
```
In crypto/xts.c (ffffffff814011fa)
Location: include/linux/crypto.h:1419
Inline: True
Inline callers:
  - crypto/xts.c:exit_tfm
```
```
In crypto/ctr.c (ffffffff81402246)
Location: include/linux/crypto.h:1419
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_exit_tfm
```
```
In crypto/drbg.c (ffffffff81404ec6)
Location: include/linux/crypto.h:1419
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81820883)
Location: include/linux/crypto.h:1419
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
In fs/crypto/keyinfo.c (ffffffff812ad81a)
Location: include/linux/crypto.h:1419
Inline: True
```
```
In crypto/ecb.c (ffffffff8140d0d6)
Location: include/linux/crypto.h:1419
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_exit_tfm
```
```
In crypto/cbc.c (ffffffff8140d2c6)
Location: include/linux/crypto.h:1419
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_exit_tfm
```
```
In crypto/xts.c (ffffffff8140e68a)
Location: include/linux/crypto.h:1419
Inline: True
Inline callers:
  - crypto/xts.c:exit_tfm
```
```
In crypto/ctr.c (ffffffff8140f366)
Location: include/linux/crypto.h:1419
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_exit_tfm
```
```
In crypto/drbg.c (ffffffff81412696)
Location: include/linux/crypto.h:1419
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81840d93)
Location: include/linux/crypto.h:1419
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
In fs/crypto/keyinfo.c (ffffffff812d0d0a)
Location: include/linux/crypto.h:1467
Inline: True
```
```
In crypto/ecb.c (ffffffff81435b46)
Location: include/linux/crypto.h:1467
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_exit_tfm
```
```
In crypto/cbc.c (ffffffff81435d36)
Location: include/linux/crypto.h:1467
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_exit_tfm
```
```
In crypto/xts.c (ffffffff8143715a)
Location: include/linux/crypto.h:1467
Inline: True
Inline callers:
  - crypto/xts.c:exit_tfm
```
```
In crypto/ctr.c (ffffffff81437d76)
Location: include/linux/crypto.h:1467
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_exit_tfm
```
```
In crypto/drbg.c (ffffffff8143ce26)
Location: include/linux/crypto.h:1467
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
```
```
In net/ipv4/tcp_fastopen.c (ffffffff818c061a)
Location: include/linux/crypto.h:1467
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
In fs/crypto/keyinfo.c (ffffffff812fb85a)
Location: include/linux/crypto.h:1480
Inline: True
```
```
In crypto/ecb.c (ffffffff814686b5)
Location: include/linux/crypto.h:1480
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_exit_tfm
```
```
In crypto/cbc.c (ffffffff814688c5)
Location: include/linux/crypto.h:1480
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_exit_tfm
```
```
In crypto/xts.c (ffffffff8146998a)
Location: include/linux/crypto.h:1480
Inline: True
Inline callers:
  - crypto/xts.c:exit_tfm
```
```
In crypto/ctr.c (ffffffff8146a6d5)
Location: include/linux/crypto.h:1480
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_exit_tfm
```
```
In crypto/drbg.c (ffffffff8146fc16)
Location: include/linux/crypto.h:1480
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81916af4)
Location: include/linux/crypto.h:1480
Inline: True
Inline callers:
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
In fs/crypto/keyinfo.c (ffffffff813110a7)
Location: include/linux/crypto.h:1665
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:put_crypt_info
```
```
In crypto/ecb.c (ffffffff81486325)
Location: include/linux/crypto.h:1665
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_exit_tfm
```
```
In crypto/cbc.c (ffffffff81486535)
Location: include/linux/crypto.h:1665
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_exit_tfm
```
```
In crypto/xts.c (ffffffff8148774a)
Location: include/linux/crypto.h:1665
Inline: True
Inline callers:
  - crypto/xts.c:exit_tfm
```
```
In crypto/ctr.c (ffffffff81487f35)
Location: include/linux/crypto.h:1665
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_exit_tfm
```
```
In crypto/drbg.c (ffffffff8148d5f6)
Location: include/linux/crypto.h:1665
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819452a4)
Location: include/linux/crypto.h:1665
Inline: True
Inline callers:
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
In fs/crypto/keyinfo.c (ffffffff81338426)
Location: include/linux/crypto.h:1662
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:put_crypt_info
```
```
In crypto/skcipher.c (ffffffff814a8f35)
Location: include/linux/crypto.h:1662
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_exit_tfm_simple
```
```
In crypto/xts.c (ffffffff814b543a)
Location: include/linux/crypto.h:1662
Inline: True
Inline callers:
  - crypto/xts.c:exit_tfm
```
```
In crypto/drbg.c (ffffffff814baf76)
Location: include/linux/crypto.h:1662
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
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
In fs/crypto/keysetup.c (ffffffff8134d6c0)
Location: include/linux/crypto.h:1662
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:put_crypt_info
```
```
In crypto/skcipher.c (ffffffff814c3b95)
Location: include/linux/crypto.h:1662
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_exit_tfm_simple
```
```
In crypto/xts.c (ffffffff814ce68a)
Location: include/linux/crypto.h:1662
Inline: True
Inline callers:
  - crypto/xts.c:exit_tfm
```
```
In crypto/drbg.c (ffffffff814d3d46)
Location: include/linux/crypto.h:1662
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
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
In crypto/skcipher.c (ffffffff81522c25)
Location: include/linux/crypto.h:768
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_exit_tfm_simple
```
```
In crypto/xts.c (ffffffff8152da8a)
Location: include/linux/crypto.h:768
Inline: True
Inline callers:
  - crypto/xts.c:exit_tfm
```
```
In crypto/drbg.c (ffffffff81533096)
Location: include/linux/crypto.h:768
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
In crypto/skcipher.c (ffffffff8153fb75)
Location: include/linux/crypto.h:804
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_exit_tfm_simple
```
```
In crypto/xts.c (ffffffff8154aa5a)
Location: include/linux/crypto.h:804
Inline: True
Inline callers:
  - crypto/xts.c:xts_exit_tfm
```
```
In crypto/drbg.c (ffffffff8154ffe6)
Location: include/linux/crypto.h:804
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
In crypto/skcipher.c (ffffffff815480e5)
Location: include/crypto/internal/cipher.h:75
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_exit_tfm_simple
```
```
In crypto/xts.c (ffffffff8155307a)
Location: include/crypto/internal/cipher.h:75
Inline: True
Inline callers:
  - crypto/xts.c:xts_exit_tfm
```
```
In crypto/drbg.c (ffffffff815587e6)
Location: include/crypto/internal/cipher.h:75
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
In crypto/skcipher.c (ffffffff815a88c5)
Location: include/crypto/internal/cipher.h:75
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_exit_tfm_simple
```
```
In crypto/xts.c (ffffffff815b40aa)
Location: include/crypto/internal/cipher.h:75
Inline: True
Inline callers:
  - crypto/xts.c:xts_exit_tfm
```
```
In crypto/drbg.c (ffffffff815b9a96)
Location: include/crypto/internal/cipher.h:75
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
In crypto/skcipher.c (ffffffff8164fc65)
Location: include/crypto/internal/cipher.h:75
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_exit_tfm_simple
```
```
In crypto/xts.c (ffffffff8165ceea)
Location: include/crypto/internal/cipher.h:75
Inline: True
Inline callers:
  - crypto/xts.c:xts_exit_tfm
```
```
In crypto/drbg.c (ffffffff81663066)
Location: include/crypto/internal/cipher.h:75
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
In crypto/skcipher.c (ffffffff817090e5)
Location: include/crypto/internal/cipher.h:75
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_exit_tfm_simple
```
```
In crypto/xts.c (ffffffff8171699a)
Location: include/crypto/internal/cipher.h:75
Inline: True
Inline callers:
  - crypto/xts.c:xts_exit_tfm
```
```
In crypto/drbg.c (ffffffff8171d2b6)
Location: include/crypto/internal/cipher.h:75
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
In crypto/skcipher.c (ffffffff81742935)
Location: include/crypto/internal/cipher.h:75
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_exit_tfm_simple
```
```
In crypto/xts.c (ffffffff8175224a)
Location: include/crypto/internal/cipher.h:75
Inline: True
Inline callers:
  - crypto/xts.c:xts_exit_tfm
```
```
In crypto/drbg.c (ffffffff81758b46)
Location: include/crypto/internal/cipher.h:75
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
In crypto/skcipher.c (ffffffff81784c25)
Location: include/crypto/internal/cipher.h:75
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_exit_tfm_simple
```
```
In crypto/ecb.c (ffffffff81792505)
Location: include/crypto/internal/cipher.h:75
Inline: True
Inline callers:
  - crypto/ecb.c:lskcipher_exit_tfm_simple2
```
```
In crypto/xts.c (ffffffff817940ca)
Location: include/crypto/internal/cipher.h:75
Inline: True
Inline callers:
  - crypto/xts.c:xts_exit_tfm
```
```
In crypto/drbg.c (ffffffff8179aa46)
Location: include/crypto/internal/cipher.h:75
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
In fs/crypto/keysetup.c (ffff80001040e734)
Location: include/linux/crypto.h:1662
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:put_crypt_info
```
```
In crypto/skcipher.c (ffff8000105be538)
Location: include/linux/crypto.h:1662
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_exit_tfm_simple
```
```
In crypto/xts.c (ffff8000105ca524)
Location: include/linux/crypto.h:1662
Inline: True
Inline callers:
  - crypto/xts.c:exit_tfm
```
```
In crypto/drbg.c (ffff8000105d07d8)
Location: include/linux/crypto.h:1662
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
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
In fs/crypto/keysetup.c (c05db20c)
Location: include/linux/crypto.h:1662
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:put_crypt_info
```
```
In crypto/skcipher.c (c076c2a0)
Location: include/linux/crypto.h:1662
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_exit_tfm_simple
```
```
In crypto/xts.c (c0778154)
Location: include/linux/crypto.h:1662
Inline: True
Inline callers:
  - crypto/xts.c:exit_tfm
```
```
In crypto/drbg.c (c077e170)
Location: include/linux/crypto.h:1662
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
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
In fs/crypto/keysetup.c (c00000000051bd08)
Location: include/linux/crypto.h:1662
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:put_crypt_info
```
```
In crypto/skcipher.c (c000000000745cfc)
Location: include/linux/crypto.h:1662
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_exit_tfm_simple
```
```
In crypto/xts.c (c0000000007550b4)
Location: include/linux/crypto.h:1662
Inline: True
Inline callers:
  - crypto/xts.c:exit_tfm
```
```
In crypto/drbg.c (c00000000075cb74)
Location: include/linux/crypto.h:1662
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
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
In fs/crypto/keysetup.c (ffffffe0002b77d6)
Location: include/linux/crypto.h:1662
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:put_crypt_info
```
```
In crypto/skcipher.c (ffffffe00040394a)
Location: include/linux/crypto.h:1662
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_exit_tfm_simple
```
```
In crypto/xts.c (ffffffe00040ea80)
Location: include/linux/crypto.h:1662
Inline: True
Inline callers:
  - crypto/xts.c:exit_tfm
```
```
In crypto/drbg.c (ffffffe00041542c)
Location: include/linux/crypto.h:1662
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
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
In fs/crypto/keysetup.c (ffffffff81345ca0)
Location: include/linux/crypto.h:1662
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:put_crypt_info
```
```
In crypto/skcipher.c (ffffffff814bc175)
Location: include/linux/crypto.h:1662
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_exit_tfm_simple
```
```
In crypto/xts.c (ffffffff814c6c6a)
Location: include/linux/crypto.h:1662
Inline: True
Inline callers:
  - crypto/xts.c:exit_tfm
```
```
In crypto/drbg.c (ffffffff814cc326)
Location: include/linux/crypto.h:1662
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
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
In fs/crypto/keysetup.c (ffffffff81336980)
Location: include/linux/crypto.h:1662
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:put_crypt_info
```
```
In crypto/skcipher.c (ffffffff814acb95)
Location: include/linux/crypto.h:1662
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_exit_tfm_simple
```
```
In crypto/xts.c (ffffffff814b768a)
Location: include/linux/crypto.h:1662
Inline: True
Inline callers:
  - crypto/xts.c:exit_tfm
```
```
In crypto/drbg.c (ffffffff814bcd46)
Location: include/linux/crypto.h:1662
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
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
In fs/crypto/keysetup.c (ffffffff81343770)
Location: include/linux/crypto.h:1662
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:put_crypt_info
```
```
In crypto/skcipher.c (ffffffff814b8205)
Location: include/linux/crypto.h:1662
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_exit_tfm_simple
```
```
In crypto/xts.c (ffffffff814c2cfa)
Location: include/linux/crypto.h:1662
Inline: True
Inline callers:
  - crypto/xts.c:exit_tfm
```
```
In crypto/drbg.c (ffffffff814c83b6)
Location: include/linux/crypto.h:1662
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
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
In fs/crypto/keysetup.c (ffffffff81356a0e)
Location: include/linux/crypto.h:1662
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:put_crypt_info
```
```
In crypto/skcipher.c (ffffffff814d0ce5)
Location: include/linux/crypto.h:1662
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_exit_tfm_simple
```
```
In crypto/xts.c (ffffffff814db7ca)
Location: include/linux/crypto.h:1662
Inline: True
Inline callers:
  - crypto/xts.c:exit_tfm
```
```
In crypto/drbg.c (ffffffff814e0e86)
Location: include/linux/crypto.h:1662
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_sym_kernel
```
</details>
</li>
</ul>

## Differences
