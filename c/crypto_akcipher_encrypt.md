# Function: <code>crypto_akcipher_encrypt</code>

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
In crypto/rsa-pkcs1pad.c (ffffffff813e193d)
Location: include/crypto/akcipher.h:283
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
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
In crypto/rsa-pkcs1pad.c (ffffffff813fa0a0)
Location: include/crypto/akcipher.h:283
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
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
In crypto/rsa-pkcs1pad.c (ffffffff81406741)
Location: include/crypto/akcipher.h:284
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
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
In crypto/rsa-pkcs1pad.c (ffffffff8142f081)
Location: include/crypto/akcipher.h:284
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
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
In crypto/rsa-pkcs1pad.c (ffffffff81461ce1)
Location: include/crypto/akcipher.h:284
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
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
In crypto/rsa-pkcs1pad.c (ffffffff8147fc53)
Location: include/crypto/akcipher.h:284
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff8149369c)
Location: include/crypto/akcipher.h:284
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
In crypto/rsa-pkcs1pad.c (ffffffff814adff0)
Location: include/crypto/akcipher.h:285
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814c0b22)
Location: include/crypto/akcipher.h:285
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
In crypto/rsa-pkcs1pad.c (ffffffff814c8c9d)
Location: include/crypto/akcipher.h:285
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814d9976)
Location: include/crypto/akcipher.h:285
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
In crypto/rsa-pkcs1pad.c (ffffffff8152736e)
Location: include/crypto/akcipher.h:285
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff81539679)
Location: include/crypto/akcipher.h:285
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
In crypto/rsa-pkcs1pad.c (ffffffff815442ee)
Location: include/crypto/akcipher.h:285
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff81556469)
Location: include/crypto/akcipher.h:285
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
In crypto/rsa-pkcs1pad.c (ffffffff8154c95e)
Location: include/crypto/akcipher.h:287
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff8155ebe9)
Location: include/crypto/akcipher.h:287
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
In crypto/rsa-pkcs1pad.c (ffffffff815ad13e)
Location: include/crypto/akcipher.h:287
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff815bff44)
Location: include/crypto/akcipher.h:287
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
In crypto/rsa-pkcs1pad.c (ffffffff8165555c)
Location: include/crypto/akcipher.h:287
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff81669c4f)
Location: include/crypto/akcipher.h:287
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
In crypto/rsa-pkcs1pad.c (ffffffff8170f790)
Location: include/crypto/akcipher.h:288
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff81724b1d)
Location: include/crypto/akcipher.h:288
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
In crypto/akcipher.c (ffffffff81747756)
Location: include/crypto/akcipher.h:336
Inline: True
Inline callers:
  - crypto/akcipher.c:crypto_akcipher_sync_encrypt
```
```
In crypto/rsa-pkcs1pad.c (ffffffff8174a7fd)
Location: include/crypto/akcipher.h:336
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
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
In crypto/akcipher.c (ffffffff817895c6)
Location: include/crypto/akcipher.h:336
Inline: True
Inline callers:
  - crypto/akcipher.c:crypto_akcipher_sync_encrypt
```
```
In crypto/rsa-pkcs1pad.c (ffffffff8178c3bd)
Location: include/crypto/akcipher.h:336
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
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
In crypto/rsa-pkcs1pad.c (ffff8000105c3fa8)
Location: include/crypto/akcipher.h:285
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
```
```
In crypto/asymmetric_keys/public_key.c (ffff8000105d5e90)
Location: include/crypto/akcipher.h:285
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
In crypto/rsa-pkcs1pad.c (c07717dc)
Location: include/crypto/akcipher.h:285
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
```
```
In crypto/asymmetric_keys/public_key.c (c078332c)
Location: include/crypto/akcipher.h:285
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
In crypto/rsa-pkcs1pad.c (c00000000074d8f4)
Location: include/crypto/akcipher.h:285
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
```
```
In crypto/asymmetric_keys/public_key.c (c000000000764730)
Location: include/crypto/akcipher.h:285
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
In crypto/rsa-pkcs1pad.c (ffffffe0004083bc)
Location: include/crypto/akcipher.h:285
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
```
```
In crypto/asymmetric_keys/public_key.c (ffffffe00041a03c)
Location: include/crypto/akcipher.h:285
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
In crypto/rsa-pkcs1pad.c (ffffffff814c127d)
Location: include/crypto/akcipher.h:285
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814d1f56)
Location: include/crypto/akcipher.h:285
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
In crypto/rsa-pkcs1pad.c (ffffffff814b1c9d)
Location: include/crypto/akcipher.h:285
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814c2976)
Location: include/crypto/akcipher.h:285
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
In crypto/rsa-pkcs1pad.c (ffffffff814bd30d)
Location: include/crypto/akcipher.h:285
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814cdfe6)
Location: include/crypto/akcipher.h:285
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
In crypto/rsa-pkcs1pad.c (ffffffff814d5ddd)
Location: include/crypto/akcipher.h:285
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814e6ab6)
Location: include/crypto/akcipher.h:285
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
```
</details>
</li>
</ul>

## Differences
