# Function: <code>crypto_aead_set_flags</code>

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
In crypto/gcm.c (ffffffff81438f0f)
Location: include/crypto/aead.h:263
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
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffff8145ace9)
Location: include/crypto/aead.h:263
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_init_tfm
```
```
In crypto/gcm.c (ffffffff8146b214)
Location: include/crypto/aead.h:263
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
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffff81478859)
Location: include/crypto/aead.h:260
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_init_tfm
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/gcm.c (ffffffff81488b14)
Location: include/crypto/aead.h:260
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
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffff814a6689)
Location: include/crypto/aead.h:255
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_init_tfm
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/gcm.c (ffffffff814b64b4)
Location: include/crypto/aead.h:255
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
In crypto/aead.c (ffffffff814c1329)
Location: include/crypto/aead.h:255
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_init_tfm
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/gcm.c (ffffffff814cf6d4)
Location: include/crypto/aead.h:255
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
In crypto/aead.c (ffffffff81521bd9)
Location: include/crypto/aead.h:271
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_init_tfm
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/gcm.c (ffffffff8152e90c)
Location: include/crypto/aead.h:271
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
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
In crypto/aead.c (ffffffff8153ea49)
Location: include/crypto/aead.h:276
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_init_tfm
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/gcm.c (ffffffff8154b88c)
Location: include/crypto/aead.h:276
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
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
In crypto/aead.c (ffffffff815470f9)
Location: include/crypto/aead.h:278
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_init_tfm
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/gcm.c (ffffffff81553e8c)
Location: include/crypto/aead.h:278
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
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
In crypto/aead.c (ffffffff815a78d9)
Location: include/crypto/aead.h:278
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_init_tfm
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/gcm.c (ffffffff815b4ebc)
Location: include/crypto/aead.h:278
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
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
In crypto/aead.c (ffffffff8164ec09)
Location: include/crypto/aead.h:280
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_init_tfm
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/gcm.c (ffffffff8165dedd)
Location: include/crypto/aead.h:280
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
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
In crypto/aead.c (ffffffff817080e9)
Location: include/crypto/aead.h:280
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_init_tfm
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/gcm.c (ffffffff81717ecd)
Location: include/crypto/aead.h:280
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
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
In crypto/aead.c (ffffffff81741809)
Location: include/crypto/aead.h:302
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_init_tfm
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/gcm.c (ffffffff817537ed)
Location: include/crypto/aead.h:302
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
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
In crypto/aead.c (ffffffff817826a9)
Location: include/crypto/aead.h:314
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_init_tfm
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/gcm.c (ffffffff817956bd)
Location: include/crypto/aead.h:314
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
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
In crypto/aead.c (ffff8000105bb644)
Location: include/crypto/aead.h:255
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_init_tfm
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/gcm.c (ffff8000105cb770)
Location: include/crypto/aead.h:255
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
In crypto/aead.c (c076989c)
Location: include/crypto/aead.h:255
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_init_tfm
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/gcm.c (c07791dc)
Location: include/crypto/aead.h:255
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
In crypto/aead.c (c000000000741f38)
Location: include/crypto/aead.h:255
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_init_tfm
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/gcm.c (c000000000756814)
Location: include/crypto/aead.h:255
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
In crypto/aead.c (ffffffe0004010a4)
Location: include/crypto/aead.h:255
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_init_tfm
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/gcm.c (ffffffe00040faa8)
Location: include/crypto/aead.h:255
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
In crypto/aead.c (ffffffff814b9909)
Location: include/crypto/aead.h:255
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_init_tfm
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/gcm.c (ffffffff814c7cb4)
Location: include/crypto/aead.h:255
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
In crypto/aead.c (ffffffff814aa329)
Location: include/crypto/aead.h:255
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_init_tfm
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/gcm.c (ffffffff814b86d4)
Location: include/crypto/aead.h:255
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
In crypto/aead.c (ffffffff814b5999)
Location: include/crypto/aead.h:255
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_init_tfm
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/gcm.c (ffffffff814c3d44)
Location: include/crypto/aead.h:255
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
In crypto/aead.c (ffffffff814ce439)
Location: include/crypto/aead.h:255
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_init_tfm
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/gcm.c (ffffffff814dc814)
Location: include/crypto/aead.h:255
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
