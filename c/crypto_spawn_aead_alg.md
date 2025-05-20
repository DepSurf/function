# Function: <code>crypto_spawn_aead_alg</code>

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
Location: include/crypto/internal/aead.h:97
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/aead.c (0)
Location: include/crypto/internal/aead.h:103
Inline: True
```
```
In crypto/seqiv.c (0)
Location: include/crypto/internal/aead.h:103
Inline: True
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
In crypto/aead.c (0)
Location: include/crypto/internal/aead.h:103
Inline: True
```
```
In crypto/seqiv.c (0)
Location: include/crypto/internal/aead.h:103
Inline: True
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
In crypto/aead.c (0)
Location: include/crypto/internal/aead.h:103
Inline: True
```
```
In crypto/seqiv.c (0)
Location: include/crypto/internal/aead.h:103
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
Location: include/crypto/internal/aead.h:103
Inline: True
```
```
In crypto/seqiv.c (0)
Location: include/crypto/internal/aead.h:103
Inline: True
```
```
In crypto/gcm.c (0)
Location: include/crypto/internal/aead.h:103
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
In crypto/aead.c (ffffffff8145b412)
Location: include/crypto/internal/aead.h:103
Inline: True
Inline callers:
  - crypto/aead.c:aead_geniv_alloc
```
```
In crypto/gcm.c (ffffffff8146be59)
Location: include/crypto/internal/aead.h:103
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
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
In crypto/aead.c (ffffffff81478fb9)
Location: include/crypto/internal/aead.h:103
Inline: True
Inline callers:
  - crypto/aead.c:aead_geniv_alloc
```
```
In crypto/gcm.c (ffffffff814898f9)
Location: include/crypto/internal/aead.h:103
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
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
In crypto/aead.c (ffffffff814a6ee7)
Location: include/crypto/internal/aead.h:98
Inline: True
Inline callers:
  - crypto/aead.c:aead_geniv_alloc
```
```
In crypto/gcm.c (ffffffff814b71ef)
Location: include/crypto/internal/aead.h:98
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
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
In crypto/aead.c (ffffffff814c1b57)
Location: include/crypto/internal/aead.h:98
Inline: True
Inline callers:
  - crypto/aead.c:aead_geniv_alloc
```
```
In crypto/gcm.c (ffffffff814d040f)
Location: include/crypto/internal/aead.h:98
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
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
In crypto/geniv.c (ffffffff8152247d)
Location: include/crypto/internal/aead.h:93
Inline: True
Inline callers:
  - crypto/geniv.c:aead_geniv_alloc
```
```
In crypto/gcm.c (ffffffff8152f6c9)
Location: include/crypto/internal/aead.h:93
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
In crypto/geniv.c (ffffffff8153f355)
Location: include/crypto/internal/aead.h:93
Inline: True
Inline callers:
  - crypto/geniv.c:aead_geniv_alloc
```
```
In crypto/gcm.c (ffffffff8154c7a0)
Location: include/crypto/internal/aead.h:93
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
In crypto/geniv.c (ffffffff815479d5)
Location: include/crypto/internal/aead.h:93
Inline: True
Inline callers:
  - crypto/geniv.c:aead_geniv_alloc
```
```
In crypto/gcm.c (ffffffff81554a69)
Location: include/crypto/internal/aead.h:93
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
In crypto/geniv.c (ffffffff815a81b5)
Location: include/crypto/internal/aead.h:93
Inline: True
Inline callers:
  - crypto/geniv.c:aead_geniv_alloc
```
```
In crypto/gcm.c (ffffffff815b5c69)
Location: include/crypto/internal/aead.h:93
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
In crypto/geniv.c (ffffffff8164f57b)
Location: include/crypto/internal/aead.h:93
Inline: True
Inline callers:
  - crypto/geniv.c:aead_geniv_alloc
```
```
In crypto/gcm.c (ffffffff8165eecd)
Location: include/crypto/internal/aead.h:93
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
In crypto/geniv.c (ffffffff81708b8b)
Location: include/crypto/internal/aead.h:108
Inline: True
Inline callers:
  - crypto/geniv.c:aead_geniv_alloc
```
```
In crypto/gcm.c (ffffffff81718c4d)
Location: include/crypto/internal/aead.h:108
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
In crypto/geniv.c (ffffffff8174235b)
Location: include/crypto/internal/aead.h:108
Inline: True
Inline callers:
  - crypto/geniv.c:aead_geniv_alloc
```
```
In crypto/gcm.c (ffffffff817547bd)
Location: include/crypto/internal/aead.h:108
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
In crypto/geniv.c (ffffffff8178326a)
Location: include/crypto/internal/aead.h:108
Inline: True
Inline callers:
  - crypto/geniv.c:aead_geniv_alloc
```
```
In crypto/gcm.c (ffffffff81795f4c)
Location: include/crypto/internal/aead.h:108
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
In crypto/aead.c (ffff8000105bb978)
Location: include/crypto/internal/aead.h:98
Inline: True
Inline callers:
  - crypto/aead.c:aead_geniv_alloc
```
```
In crypto/gcm.c (ffff8000105cbb78)
Location: include/crypto/internal/aead.h:98
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
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
In crypto/aead.c (c0769b4c)
Location: include/crypto/internal/aead.h:98
Inline: True
Inline callers:
  - crypto/aead.c:aead_geniv_alloc
```
```
In crypto/gcm.c (c0779558)
Location: include/crypto/internal/aead.h:98
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
In crypto/aead.c (c000000000742ca4)
Location: include/crypto/internal/aead.h:98
Inline: True
Inline callers:
  - crypto/aead.c:aead_geniv_alloc
```
```
In crypto/gcm.c (c0000000007587fc)
Location: include/crypto/internal/aead.h:98
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
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
In crypto/aead.c (ffffffe0004019a8)
Location: include/crypto/internal/aead.h:98
Inline: True
Inline callers:
  - crypto/aead.c:aead_geniv_alloc
```
```
In crypto/gcm.c (ffffffe000411126)
Location: include/crypto/internal/aead.h:98
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
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
In crypto/aead.c (ffffffff814ba137)
Location: include/crypto/internal/aead.h:98
Inline: True
Inline callers:
  - crypto/aead.c:aead_geniv_alloc
```
```
In crypto/gcm.c (ffffffff814c89ef)
Location: include/crypto/internal/aead.h:98
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
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
In crypto/aead.c (ffffffff814aab57)
Location: include/crypto/internal/aead.h:98
Inline: True
Inline callers:
  - crypto/aead.c:aead_geniv_alloc
```
```
In crypto/gcm.c (ffffffff814b940f)
Location: include/crypto/internal/aead.h:98
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
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
In crypto/aead.c (ffffffff814b61c7)
Location: include/crypto/internal/aead.h:98
Inline: True
Inline callers:
  - crypto/aead.c:aead_geniv_alloc
```
```
In crypto/gcm.c (ffffffff814c4a7f)
Location: include/crypto/internal/aead.h:98
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
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
In crypto/aead.c (ffffffff814cec67)
Location: include/crypto/internal/aead.h:98
Inline: True
Inline callers:
  - crypto/aead.c:aead_geniv_alloc
```
```
In crypto/gcm.c (ffffffff814dd54f)
Location: include/crypto/internal/aead.h:98
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
```
</details>
</li>
</ul>

## Differences
