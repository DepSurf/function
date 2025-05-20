# Function: <code>skcipher_request_complete</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/cts.c (ffffffff813e7ae6)
Location: include/crypto/internal/skcipher.h:57
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt_done
  - crypto/cts.c:crypto_cts_encrypt_done
  - crypto/cts.c:cts_cbc_crypt_done
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
In crypto/cts.c (ffffffff81400916)
Location: include/crypto/internal/skcipher.h:93
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt_done
  - crypto/cts.c:crypto_cts_encrypt_done
  - crypto/cts.c:cts_cbc_crypt_done
```
```
In crypto/xts.c (ffffffff81401c9e)
Location: include/crypto/internal/skcipher.h:93
Inline: True
Inline callers:
  - crypto/xts.c:decrypt_done
  - crypto/xts.c:encrypt_done
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
In crypto/cts.c (ffffffff8140e1d2)
Location: include/crypto/internal/skcipher.h:93
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt_done
  - crypto/cts.c:crypto_cts_encrypt_done
  - crypto/cts.c:cts_cbc_crypt_done
```
```
In crypto/xts.c (ffffffff8140f075)
Location: include/crypto/internal/skcipher.h:93
Inline: True
Inline callers:
  - crypto/xts.c:decrypt_done
  - crypto/xts.c:encrypt_done
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
In crypto/cts.c (ffffffff81436c82)
Location: include/crypto/internal/skcipher.h:93
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt_done
  - crypto/cts.c:crypto_cts_encrypt_done
  - crypto/cts.c:cts_cbc_crypt_done
```
```
In crypto/xts.c (ffffffff81437b55)
Location: include/crypto/internal/skcipher.h:93
Inline: True
Inline callers:
  - crypto/xts.c:decrypt_done
  - crypto/xts.c:encrypt_done
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
In crypto/cts.c (ffffffff81469852)
Location: include/crypto/internal/skcipher.h:93
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt_done
  - crypto/cts.c:crypto_cts_encrypt_done
  - crypto/cts.c:cts_cbc_crypt_done
```
```
In crypto/xts.c (ffffffff8146a495)
Location: include/crypto/internal/skcipher.h:93
Inline: True
Inline callers:
  - crypto/xts.c:decrypt_done
  - crypto/xts.c:encrypt_done
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
In crypto/cts.c (ffffffff814873b2)
Location: include/crypto/internal/skcipher.h:91
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt_done
  - crypto/cts.c:crypto_cts_encrypt_done
  - crypto/cts.c:cts_cbc_crypt_done
```
```
In crypto/xts.c (ffffffff814876f2)
Location: include/crypto/internal/skcipher.h:91
Inline: True
Inline callers:
  - crypto/xts.c:crypt_done
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
In crypto/cts.c (ffffffff814b52a2)
Location: include/crypto/internal/skcipher.h:86
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt_done
  - crypto/cts.c:crypto_cts_encrypt_done
  - crypto/cts.c:cts_cbc_crypt_done
```
```
In crypto/xts.c (ffffffff814b53e2)
Location: include/crypto/internal/skcipher.h:86
Inline: True
Inline callers:
  - crypto/xts.c:crypt_done
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
In crypto/cts.c (ffffffff814ce032)
Location: include/crypto/internal/skcipher.h:86
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt_done
  - crypto/cts.c:crypto_cts_encrypt_done
  - crypto/cts.c:cts_cbc_crypt_done
```
```
In crypto/xts.c (ffffffff814ce5b2)
Location: include/crypto/internal/skcipher.h:86
Inline: True
Inline callers:
  - crypto/xts.c:decrypt_done
  - crypto/xts.c:encrypt_done
  - crypto/xts.c:cts_done
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
In crypto/cts.c (ffffffff8152d3e2)
Location: include/crypto/internal/skcipher.h:86
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt_done
  - crypto/cts.c:crypto_cts_encrypt_done
  - crypto/cts.c:cts_cbc_crypt_done
```
```
In crypto/xts.c (ffffffff8152d9a2)
Location: include/crypto/internal/skcipher.h:86
Inline: True
Inline callers:
  - crypto/xts.c:decrypt_done
  - crypto/xts.c:encrypt_done
  - crypto/xts.c:cts_done
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
In crypto/cts.c (ffffffff8154a452)
Location: include/crypto/internal/skcipher.h:86
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt_done
  - crypto/cts.c:crypto_cts_encrypt_done
  - crypto/cts.c:cts_cbc_crypt_done
```
```
In crypto/xts.c (ffffffff8154a8d2)
Location: include/crypto/internal/skcipher.h:86
Inline: True
Inline callers:
  - crypto/xts.c:xts_decrypt_done
  - crypto/xts.c:xts_encrypt_done
  - crypto/xts.c:xts_cts_done
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
In crypto/cts.c (ffffffff81552a82)
Location: include/crypto/internal/skcipher.h:87
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt_done
  - crypto/cts.c:crypto_cts_encrypt_done
  - crypto/cts.c:cts_cbc_crypt_done
```
```
In crypto/xts.c (ffffffff81552ef2)
Location: include/crypto/internal/skcipher.h:87
Inline: True
Inline callers:
  - crypto/xts.c:xts_decrypt_done
  - crypto/xts.c:xts_encrypt_done
  - crypto/xts.c:xts_cts_done
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
In crypto/cts.c (ffffffff815b3922)
Location: include/crypto/internal/skcipher.h:87
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt_done
  - crypto/cts.c:crypto_cts_encrypt_done
  - crypto/cts.c:cts_cbc_crypt_done
```
```
In crypto/xts.c (ffffffff815b3f22)
Location: include/crypto/internal/skcipher.h:87
Inline: True
Inline callers:
  - crypto/xts.c:xts_decrypt_done
  - crypto/xts.c:xts_encrypt_done
  - crypto/xts.c:xts_cts_done
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
In crypto/cts.c (ffffffff8165c692)
Location: include/crypto/internal/skcipher.h:87
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt_done
  - crypto/cts.c:crypto_cts_encrypt_done
  - crypto/cts.c:cts_cbc_crypt_done
```
```
In crypto/xts.c (ffffffff8165cd32)
Location: include/crypto/internal/skcipher.h:87
Inline: True
Inline callers:
  - crypto/xts.c:xts_decrypt_done
  - crypto/xts.c:xts_encrypt_done
  - crypto/xts.c:xts_cts_done
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
In crypto/cts.c (ffffffff817160a2)
Location: include/crypto/internal/skcipher.h:95
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt_done
  - crypto/cts.c:crypto_cts_encrypt_done
  - crypto/cts.c:cts_cbc_crypt_done
```
```
In crypto/xts.c (ffffffff81716792)
Location: include/crypto/internal/skcipher.h:95
Inline: True
Inline callers:
  - crypto/xts.c:xts_decrypt_done
  - crypto/xts.c:xts_encrypt_done
  - crypto/xts.c:xts_cts_done
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
In crypto/cts.c (ffffffff817519a1)
Location: include/crypto/internal/skcipher.h:95
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt_done
  - crypto/cts.c:crypto_cts_encrypt_done
  - crypto/cts.c:cts_cbc_crypt_done
```
```
In crypto/xts.c (ffffffff81752061)
Location: include/crypto/internal/skcipher.h:95
Inline: True
Inline callers:
  - crypto/xts.c:xts_decrypt_done
  - crypto/xts.c:xts_encrypt_done
  - crypto/xts.c:xts_cts_done
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
In crypto/cts.c (ffffffff81793821)
Location: include/crypto/internal/skcipher.h:128
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt_done
  - crypto/cts.c:crypto_cts_encrypt_done
  - crypto/cts.c:cts_cbc_crypt_done
```
```
In crypto/xts.c (ffffffff81793ee1)
Location: include/crypto/internal/skcipher.h:128
Inline: True
Inline callers:
  - crypto/xts.c:xts_decrypt_done
  - crypto/xts.c:xts_encrypt_done
  - crypto/xts.c:xts_cts_done
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
In crypto/cts.c (ffff8000105c9f4c)
Location: include/crypto/internal/skcipher.h:86
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt_done
  - crypto/cts.c:crypto_cts_encrypt_done
  - crypto/cts.c:cts_cbc_crypt_done
```
```
In crypto/xts.c (ffff8000105ca404)
Location: include/crypto/internal/skcipher.h:86
Inline: True
Inline callers:
  - crypto/xts.c:decrypt_done
  - crypto/xts.c:encrypt_done
  - crypto/xts.c:cts_done
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
In crypto/cts.c (c0777a6c)
Location: include/crypto/internal/skcipher.h:86
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt_done
  - crypto/cts.c:crypto_cts_encrypt_done
  - crypto/cts.c:cts_cbc_crypt_done
```
```
In crypto/xts.c (c0778050)
Location: include/crypto/internal/skcipher.h:86
Inline: True
Inline callers:
  - crypto/xts.c:decrypt_done
  - crypto/xts.c:encrypt_done
  - crypto/xts.c:cts_done
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
In crypto/cts.c (c0000000007548dc)
Location: include/crypto/internal/skcipher.h:86
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt_done
  - crypto/cts.c:crypto_cts_encrypt_done
  - crypto/cts.c:cts_cbc_crypt_done
```
```
In crypto/xts.c (c000000000754f4c)
Location: include/crypto/internal/skcipher.h:86
Inline: True
Inline callers:
  - crypto/xts.c:decrypt_done
  - crypto/xts.c:encrypt_done
  - crypto/xts.c:cts_done
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
In crypto/cts.c (ffffffe00040e0a2)
Location: include/crypto/internal/skcipher.h:86
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt_done
  - crypto/cts.c:crypto_cts_encrypt_done
  - crypto/cts.c:cts_cbc_crypt_done
```
```
In crypto/xts.c (ffffffe00040e984)
Location: include/crypto/internal/skcipher.h:86
Inline: True
Inline callers:
  - crypto/xts.c:decrypt_done
  - crypto/xts.c:encrypt_done
  - crypto/xts.c:cts_done
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
In crypto/cts.c (ffffffff814c6612)
Location: include/crypto/internal/skcipher.h:86
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt_done
  - crypto/cts.c:crypto_cts_encrypt_done
  - crypto/cts.c:cts_cbc_crypt_done
```
```
In crypto/xts.c (ffffffff814c6b92)
Location: include/crypto/internal/skcipher.h:86
Inline: True
Inline callers:
  - crypto/xts.c:decrypt_done
  - crypto/xts.c:encrypt_done
  - crypto/xts.c:cts_done
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
In crypto/cts.c (ffffffff814b7032)
Location: include/crypto/internal/skcipher.h:86
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt_done
  - crypto/cts.c:crypto_cts_encrypt_done
  - crypto/cts.c:cts_cbc_crypt_done
```
```
In crypto/xts.c (ffffffff814b75b2)
Location: include/crypto/internal/skcipher.h:86
Inline: True
Inline callers:
  - crypto/xts.c:decrypt_done
  - crypto/xts.c:encrypt_done
  - crypto/xts.c:cts_done
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
In crypto/cts.c (ffffffff814c26a2)
Location: include/crypto/internal/skcipher.h:86
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt_done
  - crypto/cts.c:crypto_cts_encrypt_done
  - crypto/cts.c:cts_cbc_crypt_done
```
```
In crypto/xts.c (ffffffff814c2c22)
Location: include/crypto/internal/skcipher.h:86
Inline: True
Inline callers:
  - crypto/xts.c:decrypt_done
  - crypto/xts.c:encrypt_done
  - crypto/xts.c:cts_done
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
In crypto/cts.c (ffffffff814db172)
Location: include/crypto/internal/skcipher.h:86
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt_done
  - crypto/cts.c:crypto_cts_encrypt_done
  - crypto/cts.c:cts_cbc_crypt_done
```
```
In crypto/xts.c (ffffffff814db6f2)
Location: include/crypto/internal/skcipher.h:86
Inline: True
Inline callers:
  - crypto/xts.c:decrypt_done
  - crypto/xts.c:encrypt_done
  - crypto/xts.c:cts_done
```
</details>
</li>
</ul>

## Differences
