# Function: <code>crypto_free_akcipher</code>

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
In crypto/rsa-pkcs1pad.c (ffffffff813e19bd)
Location: include/crypto/akcipher.h:178
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_exit_tfm
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff813f06b2)
Location: include/crypto/akcipher.h:178
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
In crypto/rsa-pkcs1pad.c (ffffffff813f990d)
Location: include/crypto/akcipher.h:178
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_exit_tfm
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff81409f31)
Location: include/crypto/akcipher.h:178
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
In crypto/rsa-pkcs1pad.c (ffffffff8140620d)
Location: include/crypto/akcipher.h:178
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_exit_tfm
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff81417b74)
Location: include/crypto/akcipher.h:178
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
In crypto/rsa-pkcs1pad.c (ffffffff8142eb4d)
Location: include/crypto/akcipher.h:178
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_exit_tfm
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814425a9)
Location: include/crypto/akcipher.h:178
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
In crypto/rsa-pkcs1pad.c (ffffffff814615aa)
Location: include/crypto/akcipher.h:178
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_exit_tfm
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814754c8)
Location: include/crypto/akcipher.h:178
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
In crypto/rsa-pkcs1pad.c (ffffffff8147f20a)
Location: include/crypto/akcipher.h:178
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_exit_tfm
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff8149336f)
Location: include/crypto/akcipher.h:178
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
In crypto/rsa-pkcs1pad.c (ffffffff814ad38a)
Location: include/crypto/akcipher.h:178
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_exit_tfm
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814c0f9c)
Location: include/crypto/akcipher.h:178
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
In crypto/rsa-pkcs1pad.c (ffffffff814c803a)
Location: include/crypto/akcipher.h:178
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_exit_tfm
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814d9dcc)
Location: include/crypto/akcipher.h:178
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
In crypto/rsa-pkcs1pad.c (ffffffff8152760a)
Location: include/crypto/akcipher.h:178
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_exit_tfm
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff81539366)
Location: include/crypto/akcipher.h:178
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
In crypto/rsa-pkcs1pad.c (ffffffff8154457a)
Location: include/crypto/akcipher.h:178
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_exit_tfm
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff8155614d)
Location: include/crypto/akcipher.h:178
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
In crypto/rsa-pkcs1pad.c (ffffffff8154cbfa)
Location: include/crypto/akcipher.h:180
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_exit_tfm
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff8155e8c0)
Location: include/crypto/akcipher.h:180
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
In crypto/rsa-pkcs1pad.c (ffffffff815ad3da)
Location: include/crypto/akcipher.h:180
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_exit_tfm
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff815bfc19)
Location: include/crypto/akcipher.h:180
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
In crypto/rsa-pkcs1pad.c (ffffffff8165584a)
Location: include/crypto/akcipher.h:180
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_exit_tfm
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff8166a16f)
Location: include/crypto/akcipher.h:180
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
In crypto/rsa-pkcs1pad.c (ffffffff8170f9fa)
Location: include/crypto/akcipher.h:181
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_exit_tfm
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff8172473a)
Location: include/crypto/akcipher.h:181
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
In crypto/akcipher.c (ffffffff8174744a)
Location: include/crypto/akcipher.h:208
Inline: True
Inline callers:
  - crypto/akcipher.c:crypto_exit_akcipher_ops_sig
```
```
In crypto/rsa-pkcs1pad.c (ffffffff8174a2aa)
Location: include/crypto/akcipher.h:208
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_exit_tfm
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff81760e17)
Location: include/crypto/akcipher.h:208
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
In crypto/akcipher.c (ffffffff817892ba)
Location: include/crypto/akcipher.h:208
Inline: True
Inline callers:
  - crypto/akcipher.c:crypto_exit_akcipher_ops_sig
```
```
In crypto/rsa-pkcs1pad.c (ffffffff8178c14a)
Location: include/crypto/akcipher.h:208
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_exit_tfm
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff817a2777)
Location: include/crypto/akcipher.h:208
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
In crypto/rsa-pkcs1pad.c (ffff8000105c3a74)
Location: include/crypto/akcipher.h:178
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_exit_tfm
```
```
In crypto/asymmetric_keys/public_key.c (ffff8000105d5bc4)
Location: include/crypto/akcipher.h:178
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
In crypto/rsa-pkcs1pad.c (c0770c98)
Location: include/crypto/akcipher.h:178
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_exit_tfm
```
```
In crypto/asymmetric_keys/public_key.c (c078357c)
Location: include/crypto/akcipher.h:178
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
In crypto/rsa-pkcs1pad.c (c00000000074c730)
Location: include/crypto/akcipher.h:178
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_exit_tfm
```
```
In crypto/asymmetric_keys/public_key.c (c0000000007643dc)
Location: include/crypto/akcipher.h:178
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
In crypto/rsa-pkcs1pad.c (ffffffe0004081e0)
Location: include/crypto/akcipher.h:178
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_exit_tfm
```
```
In crypto/asymmetric_keys/public_key.c (ffffffe000419d7e)
Location: include/crypto/akcipher.h:178
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
In crypto/rsa-pkcs1pad.c (ffffffff814c061a)
Location: include/crypto/akcipher.h:178
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_exit_tfm
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814d23ac)
Location: include/crypto/akcipher.h:178
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
In crypto/rsa-pkcs1pad.c (ffffffff814b103a)
Location: include/crypto/akcipher.h:178
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_exit_tfm
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814c2dcc)
Location: include/crypto/akcipher.h:178
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
In crypto/rsa-pkcs1pad.c (ffffffff814bc6aa)
Location: include/crypto/akcipher.h:178
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_exit_tfm
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814ce43c)
Location: include/crypto/akcipher.h:178
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
In crypto/rsa-pkcs1pad.c (ffffffff814d517a)
Location: include/crypto/akcipher.h:178
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_exit_tfm
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814e6f0c)
Location: include/crypto/akcipher.h:178
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
