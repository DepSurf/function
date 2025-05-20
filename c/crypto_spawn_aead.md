# Function: <code>crypto_spawn_aead</code>

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
In crypto/aead.c (ffffffff8139f12e)
Location: include/crypto/internal/aead.h:103
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
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
In crypto/aead.c (ffffffff813dbece)
Location: include/crypto/internal/aead.h:109
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
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
In crypto/aead.c (ffffffff813f37ae)
Location: include/crypto/internal/aead.h:109
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
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
In crypto/aead.c (ffffffff813fface)
Location: include/crypto/internal/aead.h:109
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
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
In crypto/aead.c (ffffffff814280c4)
Location: include/crypto/internal/aead.h:109
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
```
```
In crypto/gcm.c (ffffffff814391c3)
Location: include/crypto/internal/aead.h:109
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4106_init_tfm
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
In crypto/aead.c (ffffffff8145af11)
Location: include/crypto/internal/aead.h:109
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
```
```
In crypto/gcm.c (ffffffff8146b4f5)
Location: include/crypto/internal/aead.h:109
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4106_init_tfm
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
In crypto/aead.c (ffffffff81478e99)
Location: include/crypto/internal/aead.h:109
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
```
```
In crypto/gcm.c (ffffffff81488b75)
Location: include/crypto/internal/aead.h:109
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4106_init_tfm
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
In crypto/aead.c (ffffffff814a6dad)
Location: include/crypto/internal/aead.h:104
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
```
```
In crypto/gcm.c (ffffffff814b65d5)
Location: include/crypto/internal/aead.h:104
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4106_init_tfm
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
In crypto/aead.c (ffffffff814c1a1d)
Location: include/crypto/internal/aead.h:104
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
```
```
In crypto/gcm.c (ffffffff814cf7f5)
Location: include/crypto/internal/aead.h:104
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4106_init_tfm
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
In crypto/geniv.c (ffffffff8152235d)
Location: include/crypto/internal/aead.h:99
Inline: True
Inline callers:
  - crypto/geniv.c:aead_init_geniv
```
```
In crypto/gcm.c (ffffffff8152e9f5)
Location: include/crypto/internal/aead.h:99
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4106_init_tfm
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
In crypto/geniv.c (ffffffff8153f23d)
Location: include/crypto/internal/aead.h:99
Inline: True
Inline callers:
  - crypto/geniv.c:aead_init_geniv
```
```
In crypto/gcm.c (ffffffff8154b975)
Location: include/crypto/internal/aead.h:99
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4106_init_tfm
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
In crypto/geniv.c (ffffffff815478bd)
Location: include/crypto/internal/aead.h:99
Inline: True
Inline callers:
  - crypto/geniv.c:aead_init_geniv
```
```
In crypto/gcm.c (ffffffff81553f75)
Location: include/crypto/internal/aead.h:99
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4106_init_tfm
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
In crypto/geniv.c (ffffffff815a809d)
Location: include/crypto/internal/aead.h:99
Inline: True
Inline callers:
  - crypto/geniv.c:aead_init_geniv
```
```
In crypto/gcm.c (ffffffff815b4fa5)
Location: include/crypto/internal/aead.h:99
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4106_init_tfm
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
In crypto/geniv.c (ffffffff8164f449)
Location: include/crypto/internal/aead.h:99
Inline: True
Inline callers:
  - crypto/geniv.c:aead_init_geniv
```
```
In crypto/gcm.c (ffffffff8165e025)
Location: include/crypto/internal/aead.h:99
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4106_init_tfm
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
In crypto/geniv.c (ffffffff81708a49)
Location: include/crypto/internal/aead.h:114
Inline: True
Inline callers:
  - crypto/geniv.c:aead_init_geniv
```
```
In crypto/gcm.c (ffffffff81717975)
Location: include/crypto/internal/aead.h:114
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4106_init_tfm
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
In crypto/geniv.c (ffffffff81742214)
Location: include/crypto/internal/aead.h:114
Inline: True
Inline callers:
  - crypto/geniv.c:aead_init_geniv
```
```
In crypto/gcm.c (ffffffff81753355)
Location: include/crypto/internal/aead.h:114
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4106_init_tfm
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
In crypto/geniv.c (ffffffff817830f4)
Location: include/crypto/internal/aead.h:114
Inline: True
Inline callers:
  - crypto/geniv.c:aead_init_geniv
```
```
In crypto/gcm.c (ffffffff81795225)
Location: include/crypto/internal/aead.h:114
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4106_init_tfm
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
In crypto/aead.c (ffff8000105bc128)
Location: include/crypto/internal/aead.h:104
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
```
```
In crypto/gcm.c (ffff8000105cb904)
Location: include/crypto/internal/aead.h:104
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4106_init_tfm
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
In crypto/aead.c (c076a18c)
Location: include/crypto/internal/aead.h:104
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
```
```
In crypto/gcm.c (c077932c)
Location: include/crypto/internal/aead.h:104
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4106_init_tfm
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
In crypto/aead.c (c000000000742aa8)
Location: include/crypto/internal/aead.h:104
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
```
```
In crypto/gcm.c (c000000000756a38)
Location: include/crypto/internal/aead.h:104
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4106_init_tfm
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
In crypto/aead.c (ffffffe0004018a2)
Location: include/crypto/internal/aead.h:104
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
```
```
In crypto/gcm.c (ffffffe00040fc4e)
Location: include/crypto/internal/aead.h:104
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4106_init_tfm
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
In crypto/aead.c (ffffffff814b9ffd)
Location: include/crypto/internal/aead.h:104
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
```
```
In crypto/gcm.c (ffffffff814c7dd5)
Location: include/crypto/internal/aead.h:104
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4106_init_tfm
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
In crypto/aead.c (ffffffff814aaa1d)
Location: include/crypto/internal/aead.h:104
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
```
```
In crypto/gcm.c (ffffffff814b87f5)
Location: include/crypto/internal/aead.h:104
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4106_init_tfm
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
In crypto/aead.c (ffffffff814b608d)
Location: include/crypto/internal/aead.h:104
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
```
```
In crypto/gcm.c (ffffffff814c3e65)
Location: include/crypto/internal/aead.h:104
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4106_init_tfm
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
In crypto/aead.c (ffffffff814ceb2d)
Location: include/crypto/internal/aead.h:104
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
```
```
In crypto/gcm.c (ffffffff814dc935)
Location: include/crypto/internal/aead.h:104
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4106_init_tfm
```
</details>
</li>
</ul>

## Differences
