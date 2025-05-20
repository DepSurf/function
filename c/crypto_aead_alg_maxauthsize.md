# Function: <code>crypto_aead_alg_maxauthsize</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/aead.c (0)
Location: include/crypto/internal/aead.h:115
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/aead.c (0)
Location: include/crypto/internal/aead.h:121
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
In crypto/aead.c (0)
Location: include/crypto/internal/aead.h:121
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
In crypto/aead.c (0)
Location: include/crypto/internal/aead.h:121
Inline: True
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
In crypto/aead.c (0)
Location: include/crypto/internal/aead.h:121
Inline: True
```
```
In crypto/gcm.c (0)
Location: include/crypto/internal/aead.h:121
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
In crypto/aead.c (0)
Location: include/crypto/internal/aead.h:121
Inline: True
```
```
In crypto/gcm.c (0)
Location: include/crypto/internal/aead.h:121
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
In crypto/aead.c (0)
Location: include/crypto/internal/aead.h:121
Inline: True
```
```
In crypto/gcm.c (0)
Location: include/crypto/internal/aead.h:121
Inline: True
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
In crypto/aead.c (0)
Location: include/crypto/internal/aead.h:116
Inline: True
```
```
In crypto/gcm.c (0)
Location: include/crypto/internal/aead.h:116
Inline: True
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
In crypto/aead.c (0)
Location: include/crypto/internal/aead.h:116
Inline: True
```
```
In crypto/gcm.c (0)
Location: include/crypto/internal/aead.h:116
Inline: True
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
In crypto/aead.c (ffffffff81521b7c)
Location: include/crypto/aead.h:236
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_setauthsize
```
```
In crypto/geniv.c (0)
Location: include/crypto/aead.h:236
Inline: True
```
```
In crypto/gcm.c (ffffffff8152f79d)
Location: include/crypto/aead.h:236
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
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
In crypto/aead.c (ffffffff8153e9e9)
Location: include/crypto/aead.h:241
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_setauthsize
  - crypto/aead.c:crypto_aead_setauthsize
```
```
In crypto/geniv.c (0)
Location: include/crypto/aead.h:241
Inline: True
```
```
In crypto/gcm.c (ffffffff8154c850)
Location: include/crypto/aead.h:241
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
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
In crypto/aead.c (ffffffff8154709c)
Location: include/crypto/aead.h:243
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_setauthsize
```
```
In crypto/geniv.c (0)
Location: include/crypto/aead.h:243
Inline: True
```
```
In crypto/gcm.c (ffffffff81554b15)
Location: include/crypto/aead.h:243
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
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
In crypto/aead.c (ffffffff815a787c)
Location: include/crypto/aead.h:243
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_setauthsize
```
```
In crypto/geniv.c (0)
Location: include/crypto/aead.h:243
Inline: True
```
```
In crypto/gcm.c (ffffffff815b5d15)
Location: include/crypto/aead.h:243
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
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
In crypto/aead.c (ffffffff8164eb7c)
Location: include/crypto/aead.h:245
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_setauthsize
```
```
In crypto/geniv.c (0)
Location: include/crypto/aead.h:245
Inline: True
```
```
In crypto/gcm.c (ffffffff8165ef85)
Location: include/crypto/aead.h:245
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
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
In crypto/aead.c (ffffffff8170803c)
Location: include/crypto/aead.h:245
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_setauthsize
```
```
In crypto/geniv.c (0)
Location: include/crypto/aead.h:245
Inline: True
```
```
In crypto/gcm.c (ffffffff81718d05)
Location: include/crypto/aead.h:245
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
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
In crypto/aead.c (ffffffff8174175c)
Location: include/crypto/aead.h:267
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_setauthsize
```
```
In crypto/geniv.c (0)
Location: include/crypto/aead.h:267
Inline: True
```
```
In crypto/gcm.c (ffffffff81754881)
Location: include/crypto/aead.h:267
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
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
In crypto/aead.c (ffffffff817825fc)
Location: include/crypto/aead.h:279
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_setauthsize
```
```
In crypto/geniv.c (0)
Location: include/crypto/aead.h:279
Inline: True
```
```
In crypto/gcm.c (ffffffff81796010)
Location: include/crypto/aead.h:279
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
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
In crypto/aead.c (0)
Location: include/crypto/internal/aead.h:116
Inline: True
```
```
In crypto/gcm.c (0)
Location: include/crypto/internal/aead.h:116
Inline: True
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
In crypto/aead.c (0)
Location: include/crypto/internal/aead.h:116
Inline: True
```
```
In crypto/gcm.c (c0779630)
Location: include/crypto/internal/aead.h:116
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
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
In crypto/aead.c (0)
Location: include/crypto/internal/aead.h:116
Inline: True
```
```
In crypto/gcm.c (0)
Location: include/crypto/internal/aead.h:116
Inline: True
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
In crypto/aead.c (0)
Location: include/crypto/internal/aead.h:116
Inline: True
```
```
In crypto/gcm.c (0)
Location: include/crypto/internal/aead.h:116
Inline: True
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
In crypto/aead.c (0)
Location: include/crypto/internal/aead.h:116
Inline: True
```
```
In crypto/gcm.c (0)
Location: include/crypto/internal/aead.h:116
Inline: True
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
In crypto/aead.c (0)
Location: include/crypto/internal/aead.h:116
Inline: True
```
```
In crypto/gcm.c (0)
Location: include/crypto/internal/aead.h:116
Inline: True
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
In crypto/aead.c (0)
Location: include/crypto/internal/aead.h:116
Inline: True
```
```
In crypto/gcm.c (0)
Location: include/crypto/internal/aead.h:116
Inline: True
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
In crypto/aead.c (0)
Location: include/crypto/internal/aead.h:116
Inline: True
```
```
In crypto/gcm.c (0)
Location: include/crypto/internal/aead.h:116
Inline: True
```
</details>
</li>
</ul>

## Differences
