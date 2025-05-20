# Function: <code>crypto_akcipher_sign</code>

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
In crypto/rsa-pkcs1pad.c (ffffffff813e16f3)
Location: include/crypto/akcipher.h:319
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
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
In crypto/rsa-pkcs1pad.c (ffffffff813f9e73)
Location: include/crypto/akcipher.h:319
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
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
In crypto/rsa-pkcs1pad.c (ffffffff814068e3)
Location: include/crypto/akcipher.h:320
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
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
In crypto/rsa-pkcs1pad.c (ffffffff8142f223)
Location: include/crypto/akcipher.h:320
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
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
In crypto/rsa-pkcs1pad.c (ffffffff81461e99)
Location: include/crypto/akcipher.h:320
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
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
In crypto/rsa-pkcs1pad.c (ffffffff8147fa9f)
Location: include/crypto/akcipher.h:332
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_sign
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff81493726)
Location: include/crypto/akcipher.h:332
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/public_key.c (ffffffff814c0bf1)
Location: include/crypto/akcipher.h:333
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/public_key.c (ffffffff814d9a33)
Location: include/crypto/akcipher.h:333
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/public_key.c (ffffffff815396fa)
Location: include/crypto/akcipher.h:333
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/public_key.c (ffffffff815564ea)
Location: include/crypto/akcipher.h:333
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/public_key.c (ffffffff8155ec6a)
Location: include/crypto/akcipher.h:335
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/public_key.c (ffffffff815bffbd)
Location: include/crypto/akcipher.h:335
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/public_key.c (ffffffff81669d0d)
Location: include/crypto/akcipher.h:335
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/public_key.c (ffffffff81724bf1)
Location: include/crypto/akcipher.h:336
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/sig.c (ffffffff81747cda)
Location: include/crypto/akcipher.h:422
Inline: True
Inline callers:
  - crypto/sig.c:crypto_sig_sign
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
In crypto/sig.c (ffffffff81789b4a)
Location: include/crypto/akcipher.h:422
Inline: True
Inline callers:
  - crypto/sig.c:crypto_sig_sign
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/public_key.c (ffff8000105d5f50)
Location: include/crypto/akcipher.h:333
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/public_key.c (c07833b8)
Location: include/crypto/akcipher.h:333
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/public_key.c (c000000000764830)
Location: include/crypto/akcipher.h:333
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/public_key.c (ffffffe00041a0e2)
Location: include/crypto/akcipher.h:333
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/public_key.c (ffffffff814d2013)
Location: include/crypto/akcipher.h:333
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/public_key.c (ffffffff814c2a33)
Location: include/crypto/akcipher.h:333
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/public_key.c (ffffffff814ce0a3)
Location: include/crypto/akcipher.h:333
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/public_key.c (ffffffff814e6b73)
Location: include/crypto/akcipher.h:333
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
```
</details>
</li>
</ul>

## Differences
