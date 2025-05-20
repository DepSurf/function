# Function: <code>crypto_akcipher_decrypt</code>

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
In crypto/rsa-pkcs1pad.c (ffffffff813e1439)
Location: include/crypto/akcipher.h:301
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
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
In crypto/rsa-pkcs1pad.c (ffffffff813fa3a7)
Location: include/crypto/akcipher.h:301
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
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
In crypto/rsa-pkcs1pad.c (ffffffff81406ba7)
Location: include/crypto/akcipher.h:302
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/rsa-pkcs1pad.c (ffffffff8142f4e7)
Location: include/crypto/akcipher.h:302
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/rsa-pkcs1pad.c (ffffffff81462187)
Location: include/crypto/akcipher.h:302
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
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
In crypto/rsa-pkcs1pad.c (ffffffff8147f3f2)
Location: include/crypto/akcipher.h:308
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff81493769)
Location: include/crypto/akcipher.h:308
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
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
In crypto/rsa-pkcs1pad.c (ffffffff814ade23)
Location: include/crypto/akcipher.h:309
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814c0c31)
Location: include/crypto/akcipher.h:309
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
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
In crypto/rsa-pkcs1pad.c (ffffffff814c8ad3)
Location: include/crypto/akcipher.h:309
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814d9a61)
Location: include/crypto/akcipher.h:309
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
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
In crypto/rsa-pkcs1pad.c (ffffffff81527d23)
Location: include/crypto/akcipher.h:309
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff81539725)
Location: include/crypto/akcipher.h:309
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
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
In crypto/rsa-pkcs1pad.c (ffffffff81544c93)
Location: include/crypto/akcipher.h:309
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff81556515)
Location: include/crypto/akcipher.h:309
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
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
In crypto/rsa-pkcs1pad.c (ffffffff8154d333)
Location: include/crypto/akcipher.h:311
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff8155ec95)
Location: include/crypto/akcipher.h:311
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
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
In crypto/rsa-pkcs1pad.c (ffffffff815adb13)
Location: include/crypto/akcipher.h:311
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff815bffe8)
Location: include/crypto/akcipher.h:311
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
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
In crypto/rsa-pkcs1pad.c (ffffffff8165600d)
Location: include/crypto/akcipher.h:311
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff81669d3c)
Location: include/crypto/akcipher.h:311
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
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
In crypto/rsa-pkcs1pad.c (ffffffff817103b1)
Location: include/crypto/akcipher.h:312
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff81724c32)
Location: include/crypto/akcipher.h:312
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
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
In crypto/akcipher.c (ffffffff81747846)
Location: include/crypto/akcipher.h:361
Inline: True
Inline callers:
  - crypto/akcipher.c:crypto_akcipher_sync_decrypt
```
```
In crypto/rsa-pkcs1pad.c (ffffffff8174ab97)
Location: include/crypto/akcipher.h:361
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
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
In crypto/akcipher.c (ffffffff817896b6)
Location: include/crypto/akcipher.h:361
Inline: True
Inline callers:
  - crypto/akcipher.c:crypto_akcipher_sync_decrypt
```
```
In crypto/rsa-pkcs1pad.c (ffffffff8178ca67)
Location: include/crypto/akcipher.h:361
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
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
In crypto/rsa-pkcs1pad.c (ffff8000105c4278)
Location: include/crypto/akcipher.h:309
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
```
```
In crypto/asymmetric_keys/public_key.c (ffff8000105d5f7c)
Location: include/crypto/akcipher.h:309
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
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
In crypto/rsa-pkcs1pad.c (c077167c)
Location: include/crypto/akcipher.h:309
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
```
```
In crypto/asymmetric_keys/public_key.c (c07833e4)
Location: include/crypto/akcipher.h:309
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
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
In crypto/rsa-pkcs1pad.c (c00000000074d6e8)
Location: include/crypto/akcipher.h:309
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
```
```
In crypto/asymmetric_keys/public_key.c (c000000000764870)
Location: include/crypto/akcipher.h:309
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
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
In crypto/rsa-pkcs1pad.c (ffffffe000408628)
Location: include/crypto/akcipher.h:309
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
```
```
In crypto/asymmetric_keys/public_key.c (ffffffe00041a10a)
Location: include/crypto/akcipher.h:309
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
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
In crypto/rsa-pkcs1pad.c (ffffffff814c10b3)
Location: include/crypto/akcipher.h:309
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814d2041)
Location: include/crypto/akcipher.h:309
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
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
In crypto/rsa-pkcs1pad.c (ffffffff814b1ad3)
Location: include/crypto/akcipher.h:309
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814c2a61)
Location: include/crypto/akcipher.h:309
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
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
In crypto/rsa-pkcs1pad.c (ffffffff814bd143)
Location: include/crypto/akcipher.h:309
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814ce0d1)
Location: include/crypto/akcipher.h:309
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
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
In crypto/rsa-pkcs1pad.c (ffffffff814d5c13)
Location: include/crypto/akcipher.h:309
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814e6ba1)
Location: include/crypto/akcipher.h:309
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
```
</details>
</li>
</ul>

## Differences
