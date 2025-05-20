# Function: <code>crypto_aead_clear_flags</code>

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
In crypto/gcm.c (ffffffff81438ef4)
Location: include/crypto/aead.h:268
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
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
In crypto/aead.c (ffffffff8145adad)
Location: include/crypto/aead.h:268
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/gcm.c (ffffffff8146b204)
Location: include/crypto/aead.h:268
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
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
In crypto/aead.c (ffffffff8147891b)
Location: include/crypto/aead.h:265
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/gcm.c (ffffffff81488b04)
Location: include/crypto/aead.h:265
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
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
In crypto/aead.c (ffffffff814a6c3b)
Location: include/crypto/aead.h:260
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/gcm.c (ffffffff814b64a4)
Location: include/crypto/aead.h:260
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
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
In crypto/aead.c (ffffffff814c18ab)
Location: include/crypto/aead.h:260
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/gcm.c (ffffffff814cf6c4)
Location: include/crypto/aead.h:260
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
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
In crypto/aead.c (0)
Location: include/crypto/aead.h:276
Inline: True
```
```
In crypto/gcm.c (ffffffff8152e8fb)
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
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/aead.c (0)
Location: include/crypto/aead.h:281
Inline: True
```
```
In crypto/gcm.c (ffffffff8154b87b)
Location: include/crypto/aead.h:281
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
In crypto/aead.c (0)
Location: include/crypto/aead.h:283
Inline: True
```
```
In crypto/gcm.c (ffffffff81553e7b)
Location: include/crypto/aead.h:283
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
In crypto/aead.c (0)
Location: include/crypto/aead.h:283
Inline: True
```
```
In crypto/gcm.c (ffffffff815b4eab)
Location: include/crypto/aead.h:283
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
In crypto/aead.c (0)
Location: include/crypto/aead.h:285
Inline: True
```
```
In crypto/gcm.c (ffffffff8165decb)
Location: include/crypto/aead.h:285
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
In crypto/aead.c (0)
Location: include/crypto/aead.h:285
Inline: True
```
```
In crypto/gcm.c (ffffffff81717ebb)
Location: include/crypto/aead.h:285
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
In crypto/aead.c (0)
Location: include/crypto/aead.h:307
Inline: True
```
```
In crypto/gcm.c (ffffffff817537db)
Location: include/crypto/aead.h:307
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
In crypto/aead.c (0)
Location: include/crypto/aead.h:319
Inline: True
```
```
In crypto/gcm.c (ffffffff817956ab)
Location: include/crypto/aead.h:319
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
In crypto/aead.c (ffff8000105bbf68)
Location: include/crypto/aead.h:260
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/gcm.c (ffff8000105cb764)
Location: include/crypto/aead.h:260
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
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
In crypto/aead.c (c076a030)
Location: include/crypto/aead.h:260
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/gcm.c (c07791cc)
Location: include/crypto/aead.h:260
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
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
In crypto/aead.c (c00000000074286c)
Location: include/crypto/aead.h:260
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/gcm.c (c000000000756808)
Location: include/crypto/aead.h:260
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
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
In crypto/aead.c (ffffffe00040173c)
Location: include/crypto/aead.h:260
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/gcm.c (ffffffe00040fa96)
Location: include/crypto/aead.h:260
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
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
In crypto/aead.c (ffffffff814b9e8b)
Location: include/crypto/aead.h:260
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/gcm.c (ffffffff814c7ca4)
Location: include/crypto/aead.h:260
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
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
In crypto/aead.c (ffffffff814aa8ab)
Location: include/crypto/aead.h:260
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/gcm.c (ffffffff814b86c4)
Location: include/crypto/aead.h:260
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
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
In crypto/aead.c (ffffffff814b5f1b)
Location: include/crypto/aead.h:260
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/gcm.c (ffffffff814c3d34)
Location: include/crypto/aead.h:260
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
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
In crypto/aead.c (ffffffff814ce9bb)
Location: include/crypto/aead.h:260
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_setkey
```
```
In crypto/gcm.c (ffffffff814dc804)
Location: include/crypto/aead.h:260
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_setkey
  - crypto/gcm.c:crypto_rfc4106_setkey
```
</details>
</li>
</ul>

## Differences
