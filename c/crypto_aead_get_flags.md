# Function: <code>crypto_aead_get_flags</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (0)
Location: include/crypto/aead.h:258
Inline: True
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
In security/keys/big_key.c (0)
Location: include/crypto/aead.h:258
Inline: True
```
```
In crypto/seqiv.c (ffffffff8145e5a1)
Location: include/crypto/aead.h:258
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/gcm.c (ffffffff8146b3dd)
Location: include/crypto/aead.h:258
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_decrypt
  - crypto/gcm.c:crypto_rfc4106_encrypt
  - crypto/gcm.c:crypto_rfc4106_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/gcm.c:crypto_gcm_setkey
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
In security/keys/big_key.c (ffffffff81408011)
Location: include/crypto/aead.h:255
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_crypt
  - security/keys/big_key.c:big_key_crypt
```
```
In crypto/seqiv.c (ffffffff8147be7a)
Location: include/crypto/aead.h:255
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
```
```
In crypto/gcm.c (ffffffff81489724)
Location: include/crypto/aead.h:255
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_decrypt
  - crypto/gcm.c:crypto_rfc4106_encrypt
  - crypto/gcm.c:crypto_rfc4106_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/gcm.c:crypto_gcm_setkey
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
In crypto/aead.c (ffffffff814a67a7)
Location: include/crypto/aead.h:250
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_decrypt
  - crypto/aead.c:crypto_aead_encrypt
```
```
In crypto/gcm.c (ffffffff814b64b4)
Location: include/crypto/aead.h:250
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/gcm.c:crypto_gcm_setkey
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
In crypto/aead.c (ffffffff814c1417)
Location: include/crypto/aead.h:250
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_decrypt
  - crypto/aead.c:crypto_aead_encrypt
```
```
In crypto/gcm.c (ffffffff814cf6d4)
Location: include/crypto/aead.h:250
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/gcm.c:crypto_gcm_setkey
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
In crypto/aead.c (ffffffff81521de7)
Location: include/crypto/aead.h:266
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_decrypt
  - crypto/aead.c:crypto_aead_encrypt
```
```
In crypto/gcm.c (ffffffff8152e90c)
Location: include/crypto/aead.h:266
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/gcm.c:crypto_gcm_setkey
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
In crypto/aead.c (ffffffff8153ec37)
Location: include/crypto/aead.h:271
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_decrypt
  - crypto/aead.c:crypto_aead_encrypt
```
```
In crypto/gcm.c (ffffffff8154b88c)
Location: include/crypto/aead.h:271
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/gcm.c:crypto_gcm_setkey
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
In crypto/aead.c (ffffffff815472d7)
Location: include/crypto/aead.h:273
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_decrypt
  - crypto/aead.c:crypto_aead_encrypt
```
```
In crypto/gcm.c (ffffffff81553e8c)
Location: include/crypto/aead.h:273
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/gcm.c:crypto_gcm_setkey
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
In crypto/aead.c (ffffffff815a7ab7)
Location: include/crypto/aead.h:273
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_decrypt
  - crypto/aead.c:crypto_aead_encrypt
```
```
In crypto/gcm.c (ffffffff815b4ebc)
Location: include/crypto/aead.h:273
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/gcm.c:crypto_gcm_setkey
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
In crypto/aead.c (ffffffff8164ee18)
Location: include/crypto/aead.h:275
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_decrypt
  - crypto/aead.c:crypto_aead_encrypt
```
```
In crypto/gcm.c (ffffffff8165dedd)
Location: include/crypto/aead.h:275
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/gcm.c:crypto_gcm_setkey
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
In crypto/aead.c (ffffffff81708228)
Location: include/crypto/aead.h:275
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_decrypt
  - crypto/aead.c:crypto_aead_encrypt
```
```
In crypto/gcm.c (ffffffff81717ecd)
Location: include/crypto/aead.h:275
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/gcm.c:crypto_gcm_setkey
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
In crypto/aead.c (ffffffff81741eaf)
Location: include/crypto/aead.h:297
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_decrypt
  - crypto/aead.c:crypto_aead_encrypt
```
```
In crypto/gcm.c (ffffffff817537ed)
Location: include/crypto/aead.h:297
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/gcm.c:crypto_gcm_setkey
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
In crypto/aead.c (ffffffff81782d8f)
Location: include/crypto/aead.h:309
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_decrypt
  - crypto/aead.c:crypto_aead_encrypt
```
```
In crypto/gcm.c (ffffffff817956bd)
Location: include/crypto/aead.h:309
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/gcm.c:crypto_gcm_setkey
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
In crypto/aead.c (ffff8000105bb768)
Location: include/crypto/aead.h:250
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_decrypt
  - crypto/aead.c:crypto_aead_encrypt
```
```
In crypto/gcm.c (ffff8000105cb770)
Location: include/crypto/aead.h:250
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/gcm.c:crypto_gcm_setkey
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
In crypto/aead.c (c076999c)
Location: include/crypto/aead.h:250
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_decrypt
  - crypto/aead.c:crypto_aead_encrypt
```
```
In crypto/gcm.c (c07791dc)
Location: include/crypto/aead.h:250
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/gcm.c:crypto_gcm_setkey
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
In crypto/aead.c (c0000000007420dc)
Location: include/crypto/aead.h:250
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_decrypt
  - crypto/aead.c:crypto_aead_encrypt
```
```
In crypto/gcm.c (c000000000756814)
Location: include/crypto/aead.h:250
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/gcm.c:crypto_gcm_setkey
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
In crypto/aead.c (ffffffe0004011b0)
Location: include/crypto/aead.h:250
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_decrypt
  - crypto/aead.c:crypto_aead_encrypt
```
```
In crypto/gcm.c (ffffffe00040faa8)
Location: include/crypto/aead.h:250
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/gcm.c:crypto_gcm_setkey
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
In crypto/aead.c (ffffffff814b99f7)
Location: include/crypto/aead.h:250
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_decrypt
  - crypto/aead.c:crypto_aead_encrypt
```
```
In crypto/gcm.c (ffffffff814c7cb4)
Location: include/crypto/aead.h:250
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/gcm.c:crypto_gcm_setkey
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
In crypto/aead.c (ffffffff814aa417)
Location: include/crypto/aead.h:250
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_decrypt
  - crypto/aead.c:crypto_aead_encrypt
```
```
In crypto/gcm.c (ffffffff814b86d4)
Location: include/crypto/aead.h:250
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/gcm.c:crypto_gcm_setkey
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
In crypto/aead.c (ffffffff814b5a87)
Location: include/crypto/aead.h:250
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_decrypt
  - crypto/aead.c:crypto_aead_encrypt
```
```
In crypto/gcm.c (ffffffff814c3d44)
Location: include/crypto/aead.h:250
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/gcm.c:crypto_gcm_setkey
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
In crypto/aead.c (ffffffff814ce527)
Location: include/crypto/aead.h:250
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_decrypt
  - crypto/aead.c:crypto_aead_encrypt
```
```
In crypto/gcm.c (ffffffff814dc814)
Location: include/crypto/aead.h:250
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/gcm.c:crypto_gcm_setkey
```
</details>
</li>
</ul>

## Differences
