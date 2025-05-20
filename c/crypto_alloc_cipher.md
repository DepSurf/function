# Function: <code>crypto_alloc_cipher</code>

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
In net/ipv4/tcp_fastopen.c (ffffffff81782725)
Location: include/linux/crypto.h:1440
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
In crypto/drbg.c (ffffffff813eec96)
Location: include/linux/crypto.h:1397
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
```
```
In net/ipv4/tcp_fastopen.c (ffffffff817efdb5)
Location: include/linux/crypto.h:1397
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
In crypto/xts.c (ffffffff8140124d)
Location: include/linux/crypto.h:1400
Inline: True
Inline callers:
  - crypto/xts.c:init_tfm
```
```
In crypto/drbg.c (ffffffff814084d6)
Location: include/linux/crypto.h:1400
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
```
```
In net/ipv4/tcp_fastopen.c (ffffffff818207c5)
Location: include/linux/crypto.h:1400
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
In fs/crypto/keyinfo.c (ffffffff812adf2d)
Location: include/linux/crypto.h:1400
Inline: True
```
```
In crypto/xts.c (ffffffff8140e6dd)
Location: include/linux/crypto.h:1400
Inline: True
Inline callers:
  - crypto/xts.c:init_tfm
```
```
In crypto/drbg.c (ffffffff81415b96)
Location: include/linux/crypto.h:1400
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81840cd5)
Location: include/linux/crypto.h:1400
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
In fs/crypto/keyinfo.c (ffffffff812d1411)
Location: include/linux/crypto.h:1448
Inline: True
```
```
In crypto/xts.c (ffffffff814371ad)
Location: include/linux/crypto.h:1448
Inline: True
Inline callers:
  - crypto/xts.c:init_tfm
```
```
In crypto/drbg.c (ffffffff81440366)
Location: include/linux/crypto.h:1448
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
```
```
In net/ipv4/tcp_fastopen.c (ffffffff818c0532)
Location: include/linux/crypto.h:1448
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
In fs/crypto/keyinfo.c (ffffffff812fbe1d)
Location: include/linux/crypto.h:1461
Inline: True
```
```
In crypto/xts.c (ffffffff814699e0)
Location: include/linux/crypto.h:1461
Inline: True
Inline callers:
  - crypto/xts.c:init_tfm
```
```
In crypto/drbg.c (ffffffff81473275)
Location: include/linux/crypto.h:1461
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81916096)
Location: include/linux/crypto.h:1461
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
In fs/crypto/keyinfo.c (ffffffff81311553)
Location: include/linux/crypto.h:1646
Inline: True
```
```
In crypto/xts.c (ffffffff814877a0)
Location: include/linux/crypto.h:1646
Inline: True
Inline callers:
  - crypto/xts.c:init_tfm
```
```
In crypto/drbg.c (ffffffff8148f7f1)
Location: include/linux/crypto.h:1646
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81944836)
Location: include/linux/crypto.h:1646
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
In fs/crypto/keyinfo.c (ffffffff813389e4)
Location: include/linux/crypto.h:1643
Inline: True
```
```
In crypto/xts.c (ffffffff814b5485)
Location: include/linux/crypto.h:1643
Inline: True
Inline callers:
  - crypto/xts.c:init_tfm
```
```
In crypto/drbg.c (ffffffff814be181)
Location: include/linux/crypto.h:1643
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
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
In fs/crypto/keysetup.c (ffffffff8134d94f)
Location: include/linux/crypto.h:1643
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_set_derived_key
```
```
In crypto/xts.c (ffffffff814ce6d5)
Location: include/linux/crypto.h:1643
Inline: True
Inline callers:
  - crypto/xts.c:init_tfm
```
```
In crypto/drbg.c (ffffffff814d6fd1)
Location: include/linux/crypto.h:1643
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
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
In crypto/xts.c (ffffffff8152dad5)
Location: include/linux/crypto.h:749
Inline: True
Inline callers:
  - crypto/xts.c:init_tfm
```
```
In crypto/drbg.c (0)
Location: include/linux/crypto.h:749
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
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
In crypto/xts.c (ffffffff8154aaa5)
Location: include/linux/crypto.h:785
Inline: True
Inline callers:
  - crypto/xts.c:xts_init_tfm
```
```
In crypto/drbg.c (0)
Location: include/linux/crypto.h:785
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
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
In crypto/xts.c (ffffffff815530c5)
Location: include/crypto/internal/cipher.h:56
Inline: True
Inline callers:
  - crypto/xts.c:xts_init_tfm
```
```
In crypto/drbg.c (0)
Location: include/crypto/internal/cipher.h:56
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
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
In crypto/xts.c (ffffffff815b40f5)
Location: include/crypto/internal/cipher.h:56
Inline: True
Inline callers:
  - crypto/xts.c:xts_init_tfm
```
```
In crypto/drbg.c (0)
Location: include/crypto/internal/cipher.h:56
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
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
In crypto/xts.c (ffffffff8165cf45)
Location: include/crypto/internal/cipher.h:56
Inline: True
Inline callers:
  - crypto/xts.c:xts_init_tfm
```
```
In crypto/drbg.c (ffffffff81663273)
Location: include/crypto/internal/cipher.h:56
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
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
In crypto/xts.c (ffffffff81716a05)
Location: include/crypto/internal/cipher.h:56
Inline: True
Inline callers:
  - crypto/xts.c:xts_init_tfm
```
```
In crypto/drbg.c (ffffffff8171d503)
Location: include/crypto/internal/cipher.h:56
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
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
In crypto/xts.c (ffffffff817522b5)
Location: include/crypto/internal/cipher.h:56
Inline: True
Inline callers:
  - crypto/xts.c:xts_init_tfm
```
```
In crypto/drbg.c (ffffffff81758de3)
Location: include/crypto/internal/cipher.h:56
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/drbg.c (ffffffff8179ace3)
Location: include/crypto/internal/cipher.h:56
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
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
In fs/crypto/keysetup.c (ffff80001040ec20)
Location: include/linux/crypto.h:1643
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_set_derived_key
```
```
In crypto/xts.c (ffff8000105ca578)
Location: include/linux/crypto.h:1643
Inline: True
Inline callers:
  - crypto/xts.c:init_tfm
```
```
In crypto/drbg.c (ffff8000105d149c)
Location: include/linux/crypto.h:1643
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
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
In fs/crypto/keysetup.c (c05db734)
Location: include/linux/crypto.h:1643
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_set_derived_key
```
```
In crypto/xts.c (c0778198)
Location: include/linux/crypto.h:1643
Inline: True
Inline callers:
  - crypto/xts.c:init_tfm
```
```
In crypto/drbg.c (c0780418)
Location: include/linux/crypto.h:1643
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
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
In fs/crypto/keysetup.c (c00000000051c288)
Location: include/linux/crypto.h:1643
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_set_derived_key
```
```
In crypto/xts.c (c000000000755140)
Location: include/linux/crypto.h:1643
Inline: True
Inline callers:
  - crypto/xts.c:init_tfm
```
```
In crypto/drbg.c (c00000000075fc10)
Location: include/linux/crypto.h:1643
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
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
In fs/crypto/keysetup.c (ffffffe0002b7a68)
Location: include/linux/crypto.h:1643
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_set_derived_key
```
```
In crypto/xts.c (ffffffe00040eacc)
Location: include/linux/crypto.h:1643
Inline: True
Inline callers:
  - crypto/xts.c:init_tfm
```
```
In crypto/drbg.c (ffffffe000416228)
Location: include/linux/crypto.h:1643
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
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
In fs/crypto/keysetup.c (ffffffff81345f2f)
Location: include/linux/crypto.h:1643
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_set_derived_key
```
```
In crypto/xts.c (ffffffff814c6cb5)
Location: include/linux/crypto.h:1643
Inline: True
Inline callers:
  - crypto/xts.c:init_tfm
```
```
In crypto/drbg.c (ffffffff814cf5b1)
Location: include/linux/crypto.h:1643
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
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
In fs/crypto/keysetup.c (ffffffff81336c0f)
Location: include/linux/crypto.h:1643
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_set_derived_key
```
```
In crypto/xts.c (ffffffff814b76d5)
Location: include/linux/crypto.h:1643
Inline: True
Inline callers:
  - crypto/xts.c:init_tfm
```
```
In crypto/drbg.c (ffffffff814bffd1)
Location: include/linux/crypto.h:1643
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
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
In fs/crypto/keysetup.c (ffffffff813439ff)
Location: include/linux/crypto.h:1643
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_set_derived_key
```
```
In crypto/xts.c (ffffffff814c2d45)
Location: include/linux/crypto.h:1643
Inline: True
Inline callers:
  - crypto/xts.c:init_tfm
```
```
In crypto/drbg.c (ffffffff814cb641)
Location: include/linux/crypto.h:1643
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
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
In fs/crypto/keysetup.c (ffffffff81356cdf)
Location: include/linux/crypto.h:1643
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_set_derived_key
```
```
In crypto/xts.c (ffffffff814db815)
Location: include/linux/crypto.h:1643
Inline: True
Inline callers:
  - crypto/xts.c:init_tfm
```
```
In crypto/drbg.c (ffffffff814e4111)
Location: include/linux/crypto.h:1643
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
```
</details>
</li>
</ul>

## Differences
