# Function: <code>crypto_akcipher_maxsize</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/rsa-pkcs1pad.c (ffffffff813e1a41)
Location: include/crypto/akcipher.h:266
Inline: True
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff813f0711)
Location: include/crypto/akcipher.h:266
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
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
In crypto/rsa-pkcs1pad.c (ffffffff813f9991)
Location: include/crypto/akcipher.h:266
Inline: True
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff81409f90)
Location: include/crypto/akcipher.h:266
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
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
In crypto/rsa-pkcs1pad.c (ffffffff81405d2c)
Location: include/crypto/akcipher.h:267
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_set_priv_key
  - crypto/rsa-pkcs1pad.c:pkcs1pad_set_pub_key
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff81417a56)
Location: include/crypto/akcipher.h:267
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
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
In crypto/rsa-pkcs1pad.c (ffffffff8142e632)
Location: include/crypto/akcipher.h:267
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_set_priv_key
  - crypto/rsa-pkcs1pad.c:pkcs1pad_set_pub_key
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff81442490)
Location: include/crypto/akcipher.h:267
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
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
In crypto/rsa-pkcs1pad.c (ffffffff81461652)
Location: include/crypto/akcipher.h:267
Inline: True
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814753c3)
Location: include/crypto/akcipher.h:267
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
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
In crypto/rsa-pkcs1pad.c (ffffffff8147f2b2)
Location: include/crypto/akcipher.h:267
Inline: True
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff8149324c)
Location: include/crypto/akcipher.h:267
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_query
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
In crypto/rsa-pkcs1pad.c (ffffffff814ad432)
Location: include/crypto/akcipher.h:268
Inline: True
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814c08a6)
Location: include/crypto/akcipher.h:268
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:software_key_query
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
In crypto/rsa-pkcs1pad.c (ffffffff814c80e2)
Location: include/crypto/akcipher.h:268
Inline: True
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814d96f6)
Location: include/crypto/akcipher.h:268
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:software_key_query
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
In crypto/rsa-pkcs1pad.c (ffffffff815276c2)
Location: include/crypto/akcipher.h:268
Inline: True
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff81538fe8)
Location: include/crypto/akcipher.h:268
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:software_key_query
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
In crypto/rsa-pkcs1pad.c (ffffffff81544632)
Location: include/crypto/akcipher.h:268
Inline: True
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff81555dc8)
Location: include/crypto/akcipher.h:268
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:software_key_query
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
In crypto/rsa-pkcs1pad.c (ffffffff8154ccb2)
Location: include/crypto/akcipher.h:270
Inline: True
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff8155e548)
Location: include/crypto/akcipher.h:270
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:software_key_query
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
In crypto/rsa-pkcs1pad.c (ffffffff815ad492)
Location: include/crypto/akcipher.h:270
Inline: True
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff815bf887)
Location: include/crypto/akcipher.h:270
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:software_key_query
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
In crypto/rsa-pkcs1pad.c (ffffffff81655902)
Location: include/crypto/akcipher.h:270
Inline: True
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff81669900)
Location: include/crypto/akcipher.h:270
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:software_key_query
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
In crypto/rsa-pkcs1pad.c (ffffffff8170fae2)
Location: include/crypto/akcipher.h:271
Inline: True
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff817241b7)
Location: include/crypto/akcipher.h:271
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:software_key_query
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
In crypto/sig.c (ffffffff817478ca)
Location: include/crypto/akcipher.h:298
Inline: True
Inline callers:
  - crypto/sig.c:crypto_sig_maxsize
```
```
In crypto/rsa-pkcs1pad.c (ffffffff8174a392)
Location: include/crypto/akcipher.h:298
Inline: True
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff81760d20)
Location: include/crypto/akcipher.h:298
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_query
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
In crypto/sig.c (ffffffff8178973a)
Location: include/crypto/akcipher.h:298
Inline: True
Inline callers:
  - crypto/sig.c:crypto_sig_maxsize
```
```
In crypto/rsa-pkcs1pad.c (ffffffff8178c232)
Location: include/crypto/akcipher.h:298
Inline: True
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff817a2680)
Location: include/crypto/akcipher.h:298
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_query
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
In crypto/rsa-pkcs1pad.c (ffff8000105c3e0c)
Location: include/crypto/akcipher.h:268
Inline: True
```
```
In crypto/asymmetric_keys/public_key.c (ffff8000105d58c4)
Location: include/crypto/akcipher.h:268
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:software_key_query
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
In crypto/rsa-pkcs1pad.c (c0770ff0)
Location: include/crypto/akcipher.h:268
Inline: True
```
```
In crypto/asymmetric_keys/public_key.c (c07830f8)
Location: include/crypto/akcipher.h:268
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:software_key_query
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
In crypto/rsa-pkcs1pad.c (c00000000074c878)
Location: include/crypto/akcipher.h:268
Inline: True
```
```
In crypto/asymmetric_keys/public_key.c (c000000000764044)
Location: include/crypto/akcipher.h:268
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:software_key_query
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
In crypto/rsa-pkcs1pad.c (ffffffe0004082a4)
Location: include/crypto/akcipher.h:268
Inline: True
```
```
In crypto/asymmetric_keys/public_key.c (ffffffe000419ab0)
Location: include/crypto/akcipher.h:268
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:software_key_query
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
In crypto/rsa-pkcs1pad.c (ffffffff814c06c2)
Location: include/crypto/akcipher.h:268
Inline: True
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814d1cd6)
Location: include/crypto/akcipher.h:268
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:software_key_query
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
In crypto/rsa-pkcs1pad.c (ffffffff814b10e2)
Location: include/crypto/akcipher.h:268
Inline: True
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814c26f6)
Location: include/crypto/akcipher.h:268
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:software_key_query
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
In crypto/rsa-pkcs1pad.c (ffffffff814bc752)
Location: include/crypto/akcipher.h:268
Inline: True
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814cdd66)
Location: include/crypto/akcipher.h:268
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:software_key_query
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
In crypto/rsa-pkcs1pad.c (ffffffff814d5222)
Location: include/crypto/akcipher.h:268
Inline: True
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814e6836)
Location: include/crypto/akcipher.h:268
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:software_key_query
```
</details>
</li>
</ul>

## Differences
