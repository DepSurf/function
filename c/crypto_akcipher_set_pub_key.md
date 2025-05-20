# Function: <code>crypto_akcipher_set_pub_key</code>

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
In crypto/rsa-pkcs1pad.c (ffffffff813e1a88)
Location: include/crypto/akcipher.h:357
Inline: True
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff813f0691)
Location: include/crypto/akcipher.h:357
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
In crypto/rsa-pkcs1pad.c (ffffffff813f99d8)
Location: include/crypto/akcipher.h:357
Inline: True
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff81409f11)
Location: include/crypto/akcipher.h:357
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
In crypto/rsa-pkcs1pad.c (ffffffff81405cca)
Location: include/crypto/akcipher.h:358
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_set_pub_key
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff81417a3a)
Location: include/crypto/akcipher.h:358
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
In crypto/rsa-pkcs1pad.c (ffffffff8142e5ba)
Location: include/crypto/akcipher.h:358
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_set_pub_key
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff81442471)
Location: include/crypto/akcipher.h:358
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
In crypto/rsa-pkcs1pad.c (ffffffff814617da)
Location: include/crypto/akcipher.h:358
Inline: True
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814753ab)
Location: include/crypto/akcipher.h:358
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
In crypto/rsa-pkcs1pad.c (ffffffff8147f5da)
Location: include/crypto/akcipher.h:380
Inline: True
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814933e8)
Location: include/crypto/akcipher.h:380
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
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
In crypto/rsa-pkcs1pad.c (ffffffff814ad41a)
Location: include/crypto/akcipher.h:386
Inline: True
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814c0dee)
Location: include/crypto/akcipher.h:386
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
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
In crypto/rsa-pkcs1pad.c (ffffffff814c80ca)
Location: include/crypto/akcipher.h:386
Inline: True
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814d9c1e)
Location: include/crypto/akcipher.h:386
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
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
In crypto/rsa-pkcs1pad.c (ffffffff8152783a)
Location: include/crypto/akcipher.h:386
Inline: True
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff8153918c)
Location: include/crypto/akcipher.h:386
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
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
In crypto/rsa-pkcs1pad.c (ffffffff815447aa)
Location: include/crypto/akcipher.h:386
Inline: True
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff81555f70)
Location: include/crypto/akcipher.h:386
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
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
In crypto/rsa-pkcs1pad.c (ffffffff8154ce3a)
Location: include/crypto/akcipher.h:388
Inline: True
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff8155e6e3)
Location: include/crypto/akcipher.h:388
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
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
In crypto/rsa-pkcs1pad.c (ffffffff815ad47a)
Location: include/crypto/akcipher.h:388
Inline: True
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff815bfa3d)
Location: include/crypto/akcipher.h:388
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
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
In crypto/rsa-pkcs1pad.c (ffffffff816558ea)
Location: include/crypto/akcipher.h:388
Inline: True
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff81669f97)
Location: include/crypto/akcipher.h:388
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
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
In crypto/rsa-pkcs1pad.c (ffffffff8170fc7a)
Location: include/crypto/akcipher.h:389
Inline: True
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff81724564)
Location: include/crypto/akcipher.h:389
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
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
In crypto/sig.c (ffffffff8174790a)
Location: include/crypto/akcipher.h:471
Inline: True
Inline callers:
  - crypto/sig.c:crypto_sig_set_pubkey
```
```
In crypto/rsa-pkcs1pad.c (ffffffff8174a8ea)
Location: include/crypto/akcipher.h:471
Inline: True
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff81760cf3)
Location: include/crypto/akcipher.h:471
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
In crypto/sig.c (ffffffff8178977a)
Location: include/crypto/akcipher.h:471
Inline: True
Inline callers:
  - crypto/sig.c:crypto_sig_set_pubkey
```
```
In crypto/rsa-pkcs1pad.c (ffffffff8178c4aa)
Location: include/crypto/akcipher.h:471
Inline: True
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff817a2653)
Location: include/crypto/akcipher.h:471
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
In crypto/rsa-pkcs1pad.c (ffff8000105c43ec)
Location: include/crypto/akcipher.h:386
Inline: True
```
```
In crypto/asymmetric_keys/public_key.c (ffff8000105d5c08)
Location: include/crypto/akcipher.h:386
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
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
In crypto/rsa-pkcs1pad.c (c0770fd8)
Location: include/crypto/akcipher.h:386
Inline: True
```
```
In crypto/asymmetric_keys/public_key.c (c078353c)
Location: include/crypto/akcipher.h:386
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
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
In crypto/rsa-pkcs1pad.c (c00000000074c858)
Location: include/crypto/akcipher.h:386
Inline: True
```
```
In crypto/asymmetric_keys/public_key.c (c000000000764440)
Location: include/crypto/akcipher.h:386
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
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
In crypto/rsa-pkcs1pad.c (ffffffe000408292)
Location: include/crypto/akcipher.h:386
Inline: True
```
```
In crypto/asymmetric_keys/public_key.c (ffffffe000419da6)
Location: include/crypto/akcipher.h:386
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
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
In crypto/rsa-pkcs1pad.c (ffffffff814c06aa)
Location: include/crypto/akcipher.h:386
Inline: True
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814d21fe)
Location: include/crypto/akcipher.h:386
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
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
In crypto/rsa-pkcs1pad.c (ffffffff814b10ca)
Location: include/crypto/akcipher.h:386
Inline: True
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814c2c1e)
Location: include/crypto/akcipher.h:386
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
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
In crypto/rsa-pkcs1pad.c (ffffffff814bc73a)
Location: include/crypto/akcipher.h:386
Inline: True
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814ce28e)
Location: include/crypto/akcipher.h:386
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
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
In crypto/rsa-pkcs1pad.c (ffffffff814d520a)
Location: include/crypto/akcipher.h:386
Inline: True
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814e6d5e)
Location: include/crypto/akcipher.h:386
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_query
```
</details>
</li>
</ul>

## Differences
