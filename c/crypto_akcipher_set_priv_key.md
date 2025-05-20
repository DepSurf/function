# Function: <code>crypto_akcipher_set_priv_key</code>

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
In crypto/rsa-pkcs1pad.c (ffffffff813e1ab8)
Location: include/crypto/akcipher.h:378
Inline: True
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
In crypto/rsa-pkcs1pad.c (ffffffff813f9a08)
Location: include/crypto/akcipher.h:378
Inline: True
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
In crypto/rsa-pkcs1pad.c (ffffffff81405d1a)
Location: include/crypto/akcipher.h:379
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_set_priv_key
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
In crypto/rsa-pkcs1pad.c (ffffffff8142e61a)
Location: include/crypto/akcipher.h:379
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_set_priv_key
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
In crypto/rsa-pkcs1pad.c (ffffffff8146163a)
Location: include/crypto/akcipher.h:379
Inline: True
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
In crypto/rsa-pkcs1pad.c (ffffffff8147f29a)
Location: include/crypto/akcipher.h:401
Inline: True
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff81493238)
Location: include/crypto/akcipher.h:401
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
In crypto/rsa-pkcs1pad.c (ffffffff814ad47a)
Location: include/crypto/akcipher.h:408
Inline: True
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814c0fd0)
Location: include/crypto/akcipher.h:408
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
In crypto/rsa-pkcs1pad.c (ffffffff814c812a)
Location: include/crypto/akcipher.h:408
Inline: True
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814d9e00)
Location: include/crypto/akcipher.h:408
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
In crypto/rsa-pkcs1pad.c (ffffffff815276aa)
Location: include/crypto/akcipher.h:408
Inline: True
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff8153939e)
Location: include/crypto/akcipher.h:408
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
In crypto/rsa-pkcs1pad.c (ffffffff8154461a)
Location: include/crypto/akcipher.h:408
Inline: True
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff81556185)
Location: include/crypto/akcipher.h:408
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
In crypto/rsa-pkcs1pad.c (ffffffff8154cc9a)
Location: include/crypto/akcipher.h:410
Inline: True
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff8155e8fa)
Location: include/crypto/akcipher.h:410
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
In crypto/rsa-pkcs1pad.c (ffffffff815ad61a)
Location: include/crypto/akcipher.h:410
Inline: True
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff815bfc53)
Location: include/crypto/akcipher.h:410
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
In crypto/rsa-pkcs1pad.c (ffffffff81655aca)
Location: include/crypto/akcipher.h:410
Inline: True
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff8166a1b5)
Location: include/crypto/akcipher.h:410
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
In crypto/rsa-pkcs1pad.c (ffffffff8170faca)
Location: include/crypto/akcipher.h:411
Inline: True
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff81724784)
Location: include/crypto/akcipher.h:411
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
In crypto/sig.c (ffffffff8174794a)
Location: include/crypto/akcipher.h:493
Inline: True
Inline callers:
  - crypto/sig.c:crypto_sig_set_privkey
```
```
In crypto/rsa-pkcs1pad.c (ffffffff8174a37a)
Location: include/crypto/akcipher.h:493
Inline: True
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff81760dd1)
Location: include/crypto/akcipher.h:493
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
In crypto/sig.c (ffffffff817897ba)
Location: include/crypto/akcipher.h:493
Inline: True
Inline callers:
  - crypto/sig.c:crypto_sig_set_privkey
```
```
In crypto/rsa-pkcs1pad.c (ffffffff8178c21a)
Location: include/crypto/akcipher.h:493
Inline: True
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff817a2731)
Location: include/crypto/akcipher.h:493
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
In crypto/rsa-pkcs1pad.c (ffff8000105c3dec)
Location: include/crypto/akcipher.h:408
Inline: True
```
```
In crypto/asymmetric_keys/public_key.c (ffff8000105d5ab8)
Location: include/crypto/akcipher.h:408
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
In crypto/rsa-pkcs1pad.c (c0771184)
Location: include/crypto/akcipher.h:408
Inline: True
```
```
In crypto/asymmetric_keys/public_key.c (c078353c)
Location: include/crypto/akcipher.h:408
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
In crypto/rsa-pkcs1pad.c (c00000000074c8f8)
Location: include/crypto/akcipher.h:408
Inline: True
```
```
In crypto/asymmetric_keys/public_key.c (c000000000764284)
Location: include/crypto/akcipher.h:408
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
In crypto/rsa-pkcs1pad.c (ffffffe000408718)
Location: include/crypto/akcipher.h:408
Inline: True
```
```
In crypto/asymmetric_keys/public_key.c (ffffffe000419c56)
Location: include/crypto/akcipher.h:408
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
In crypto/rsa-pkcs1pad.c (ffffffff814c070a)
Location: include/crypto/akcipher.h:408
Inline: True
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814d23e0)
Location: include/crypto/akcipher.h:408
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
In crypto/rsa-pkcs1pad.c (ffffffff814b112a)
Location: include/crypto/akcipher.h:408
Inline: True
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814c2e00)
Location: include/crypto/akcipher.h:408
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
In crypto/rsa-pkcs1pad.c (ffffffff814bc79a)
Location: include/crypto/akcipher.h:408
Inline: True
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814ce470)
Location: include/crypto/akcipher.h:408
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
In crypto/rsa-pkcs1pad.c (ffffffff814d526a)
Location: include/crypto/akcipher.h:408
Inline: True
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814e6f40)
Location: include/crypto/akcipher.h:408
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
