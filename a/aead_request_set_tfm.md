# Function: <code>aead_request_set_tfm</code>

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
In crypto/seqiv.c (ffffffff813de7d7)
Location: include/crypto/aead.h:395
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/seqiv.c (ffffffff813f6d77)
Location: include/crypto/aead.h:395
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/seqiv.c (ffffffff81403157)
Location: include/crypto/aead.h:395
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
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
In security/keys/big_key.c (ffffffff813bbfb5)
Location: include/crypto/aead.h:395
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_crypt
```
```
In crypto/seqiv.c (ffffffff8142b837)
Location: include/crypto/aead.h:395
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/gcm.c (ffffffff81439073)
Location: include/crypto/aead.h:395
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
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
In security/keys/big_key.c (ffffffff813ecd72)
Location: include/crypto/aead.h:403
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_crypt
```
```
In crypto/seqiv.c (ffffffff8145e542)
Location: include/crypto/aead.h:403
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/gcm.c (ffffffff8146b387)
Location: include/crypto/aead.h:403
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
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
In security/keys/big_key.c (ffffffff81407f12)
Location: include/crypto/aead.h:411
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_crypt
```
```
In crypto/seqiv.c (ffffffff8147be02)
Location: include/crypto/aead.h:411
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/gcm.c (ffffffff814896bf)
Location: include/crypto/aead.h:411
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
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
In security/keys/big_key.c (ffffffff81435209)
Location: include/crypto/aead.h:376
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_crypt
```
```
In crypto/seqiv.c (ffffffff814aa1fa)
Location: include/crypto/aead.h:376
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/gcm.c (ffffffff814b631d)
Location: include/crypto/aead.h:376
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
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
In security/keys/big_key.c (ffffffff8144ef89)
Location: include/crypto/aead.h:376
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_crypt
```
```
In crypto/seqiv.c (ffffffff814c4eba)
Location: include/crypto/aead.h:376
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/gcm.c (ffffffff814cf51d)
Location: include/crypto/aead.h:376
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
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
In crypto/seqiv.c (ffffffff81523dce)
Location: include/crypto/aead.h:392
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/gcm.c (ffffffff8152e75d)
Location: include/crypto/aead.h:392
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
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
In crypto/seqiv.c (ffffffff81540c4e)
Location: include/crypto/aead.h:397
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/gcm.c (ffffffff8154b6dd)
Location: include/crypto/aead.h:397
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
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
In crypto/seqiv.c (ffffffff815492a3)
Location: include/crypto/aead.h:399
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/gcm.c (ffffffff81553ced)
Location: include/crypto/aead.h:399
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
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
In crypto/seqiv.c (ffffffff815a9a83)
Location: include/crypto/aead.h:399
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/gcm.c (ffffffff815b4d1d)
Location: include/crypto/aead.h:399
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
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
In crypto/seqiv.c (ffffffff81650f46)
Location: include/crypto/aead.h:401
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/gcm.c (ffffffff8165dccd)
Location: include/crypto/aead.h:401
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
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
In crypto/seqiv.c (ffffffff8170a776)
Location: include/crypto/aead.h:401
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/gcm.c (ffffffff81717d0d)
Location: include/crypto/aead.h:401
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
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
In crypto/seqiv.c (ffffffff81743fc6)
Location: include/crypto/aead.h:423
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/gcm.c (ffffffff8175362d)
Location: include/crypto/aead.h:423
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
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
In crypto/seqiv.c (ffffffff81786586)
Location: include/crypto/aead.h:435
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/gcm.c (ffffffff817954fd)
Location: include/crypto/aead.h:435
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
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
In security/keys/big_key.c (ffff80001053997c)
Location: include/crypto/aead.h:376
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_crypt
```
```
In crypto/seqiv.c (ffff8000105bfa64)
Location: include/crypto/aead.h:376
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/gcm.c (ffff8000105cb51c)
Location: include/crypto/aead.h:376
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
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
In security/keys/big_key.c (c06f0140)
Location: include/crypto/aead.h:376
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_crypt
```
```
In crypto/seqiv.c (c076d6b8)
Location: include/crypto/aead.h:376
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/gcm.c (c077901c)
Location: include/crypto/aead.h:376
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
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
In security/keys/big_key.c (c000000000688938)
Location: include/crypto/aead.h:376
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_crypt
```
```
In crypto/seqiv.c (c000000000747854)
Location: include/crypto/aead.h:376
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/gcm.c (c00000000075658c)
Location: include/crypto/aead.h:376
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
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
In security/keys/big_key.c (ffffffe000398030)
Location: include/crypto/aead.h:376
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_crypt
```
```
In crypto/seqiv.c (ffffffe000404b36)
Location: include/crypto/aead.h:376
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/gcm.c (ffffffe00040f8b6)
Location: include/crypto/aead.h:376
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
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
In security/keys/big_key.c (ffffffff81447569)
Location: include/crypto/aead.h:376
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_crypt
```
```
In crypto/seqiv.c (ffffffff814bd49a)
Location: include/crypto/aead.h:376
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/gcm.c (ffffffff814c7afd)
Location: include/crypto/aead.h:376
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
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
In security/keys/big_key.c (ffffffff81437fb9)
Location: include/crypto/aead.h:376
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_crypt
```
```
In crypto/seqiv.c (ffffffff814adeba)
Location: include/crypto/aead.h:376
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/gcm.c (ffffffff814b851d)
Location: include/crypto/aead.h:376
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
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
In security/keys/big_key.c (ffffffff81443609)
Location: include/crypto/aead.h:376
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_crypt
```
```
In crypto/seqiv.c (ffffffff814b952a)
Location: include/crypto/aead.h:376
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/gcm.c (ffffffff814c3b8d)
Location: include/crypto/aead.h:376
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
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
In security/keys/big_key.c (ffffffff8145a939)
Location: include/crypto/aead.h:376
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_crypt
```
```
In crypto/seqiv.c (ffffffff814d1fca)
Location: include/crypto/aead.h:376
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/gcm.c (ffffffff814dc65d)
Location: include/crypto/aead.h:376
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_crypt
```
</details>
</li>
</ul>

## Differences
