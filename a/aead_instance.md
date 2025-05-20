# Function: <code>aead_instance</code>

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
Location: include/crypto/internal/aead.h:53
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
Location: include/crypto/internal/aead.h:53
Inline: True
```
```
In crypto/seqiv.c (ffffffff813de796)
Location: include/crypto/internal/aead.h:53
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_free
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
Location: include/crypto/internal/aead.h:53
Inline: True
```
```
In crypto/seqiv.c (ffffffff813f6d36)
Location: include/crypto/internal/aead.h:53
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_free
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
In crypto/aead.c (ffffffff813fff02)
Location: include/crypto/internal/aead.h:53
Inline: True
```
```
In crypto/seqiv.c (ffffffff81403116)
Location: include/crypto/internal/aead.h:53
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_free
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
In crypto/aead.c (ffffffff814284f2)
Location: include/crypto/internal/aead.h:53
Inline: True
```
```
In crypto/seqiv.c (ffffffff8142b7f6)
Location: include/crypto/internal/aead.h:53
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_free
```
```
In crypto/gcm.c (0)
Location: include/crypto/internal/aead.h:53
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
In crypto/aead.c (ffffffff8145aea5)
Location: include/crypto/internal/aead.h:53
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
```
```
In crypto/seqiv.c (ffffffff8145e4f5)
Location: include/crypto/internal/aead.h:53
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_free
```
```
In crypto/gcm.c (ffffffff8146b4f5)
Location: include/crypto/internal/aead.h:53
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4106_init_tfm
  - crypto/gcm.c:crypto_gcm_init_tfm
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
In crypto/aead.c (ffffffff81478e09)
Location: include/crypto/internal/aead.h:53
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
```
```
In crypto/seqiv.c (ffffffff8147bdb5)
Location: include/crypto/internal/aead.h:53
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_free
```
```
In crypto/gcm.c (ffffffff81488b75)
Location: include/crypto/internal/aead.h:53
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4106_init_tfm
  - crypto/gcm.c:crypto_gcm_init_tfm
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
In crypto/aead.c (ffffffff814a6d29)
Location: include/crypto/internal/aead.h:48
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
```
```
In crypto/seqiv.c (ffffffff814aa1b5)
Location: include/crypto/internal/aead.h:48
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_free
```
```
In crypto/gcm.c (ffffffff814b65d5)
Location: include/crypto/internal/aead.h:48
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4106_init_tfm
  - crypto/gcm.c:crypto_gcm_init_tfm
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
In crypto/aead.c (ffffffff814c1999)
Location: include/crypto/internal/aead.h:48
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
```
```
In crypto/seqiv.c (ffffffff814c4e75)
Location: include/crypto/internal/aead.h:48
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_free
```
```
In crypto/gcm.c (ffffffff814cf7f5)
Location: include/crypto/internal/aead.h:48
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4106_init_tfm
  - crypto/gcm.c:crypto_gcm_init_tfm
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
In crypto/aead.c (ffffffff81521c15)
Location: include/crypto/internal/aead.h:48
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_free_instance
```
```
In crypto/geniv.c (ffffffff815222d9)
Location: include/crypto/internal/aead.h:48
Inline: True
Inline callers:
  - crypto/geniv.c:aead_init_geniv
```
```
In crypto/gcm.c (ffffffff8152e9f5)
Location: include/crypto/internal/aead.h:48
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4106_init_tfm
  - crypto/gcm.c:crypto_gcm_init_tfm
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
In crypto/aead.c (ffffffff8153ea85)
Location: include/crypto/internal/aead.h:48
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_free_instance
```
```
In crypto/geniv.c (ffffffff8153f1b9)
Location: include/crypto/internal/aead.h:48
Inline: True
Inline callers:
  - crypto/geniv.c:aead_init_geniv
```
```
In crypto/gcm.c (ffffffff8154b975)
Location: include/crypto/internal/aead.h:48
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4106_init_tfm
  - crypto/gcm.c:crypto_gcm_init_tfm
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
In crypto/aead.c (ffffffff81547135)
Location: include/crypto/internal/aead.h:48
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_free_instance
```
```
In crypto/geniv.c (ffffffff81547839)
Location: include/crypto/internal/aead.h:48
Inline: True
Inline callers:
  - crypto/geniv.c:aead_init_geniv
```
```
In crypto/gcm.c (ffffffff81553f75)
Location: include/crypto/internal/aead.h:48
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4106_init_tfm
  - crypto/gcm.c:crypto_gcm_init_tfm
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
In crypto/aead.c (ffffffff815a7915)
Location: include/crypto/internal/aead.h:48
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_free_instance
```
```
In crypto/geniv.c (ffffffff815a8019)
Location: include/crypto/internal/aead.h:48
Inline: True
Inline callers:
  - crypto/geniv.c:aead_init_geniv
```
```
In crypto/gcm.c (ffffffff815b4fa5)
Location: include/crypto/internal/aead.h:48
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4106_init_tfm
  - crypto/gcm.c:crypto_gcm_init_tfm
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
In crypto/aead.c (ffffffff8164ec55)
Location: include/crypto/internal/aead.h:48
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_free_instance
```
```
In crypto/geniv.c (0)
Location: include/crypto/internal/aead.h:48
Inline: True
```
```
In crypto/gcm.c (0)
Location: include/crypto/internal/aead.h:48
Inline: True
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
In crypto/aead.c (ffffffff81708145)
Location: include/crypto/internal/aead.h:53
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_free_instance
```
```
In crypto/geniv.c (0)
Location: include/crypto/internal/aead.h:53
Inline: True
```
```
In crypto/gcm.c (0)
Location: include/crypto/internal/aead.h:53
Inline: True
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
In crypto/aead.c (ffffffff81741865)
Location: include/crypto/internal/aead.h:53
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_free_instance
```
```
In crypto/geniv.c (0)
Location: include/crypto/internal/aead.h:53
Inline: True
```
```
In crypto/gcm.c (0)
Location: include/crypto/internal/aead.h:53
Inline: True
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
In crypto/aead.c (ffffffff81782705)
Location: include/crypto/internal/aead.h:53
Inline: True
Inline callers:
  - crypto/aead.c:crypto_aead_free_instance
```
```
In crypto/geniv.c (0)
Location: include/crypto/internal/aead.h:53
Inline: True
```
```
In crypto/gcm.c (0)
Location: include/crypto/internal/aead.h:53
Inline: True
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
In crypto/aead.c (ffff8000105bc09c)
Location: include/crypto/internal/aead.h:48
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
```
```
In crypto/seqiv.c (ffff8000105bfa18)
Location: include/crypto/internal/aead.h:48
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_free
```
```
In crypto/gcm.c (ffff8000105cb904)
Location: include/crypto/internal/aead.h:48
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4106_init_tfm
  - crypto/gcm.c:crypto_gcm_init_tfm
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
In crypto/aead.c (c076a0fc)
Location: include/crypto/internal/aead.h:48
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
```
```
In crypto/seqiv.c (c076d674)
Location: include/crypto/internal/aead.h:48
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_free
```
```
In crypto/gcm.c (c077932c)
Location: include/crypto/internal/aead.h:48
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4106_init_tfm
  - crypto/gcm.c:crypto_gcm_init_tfm
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
In crypto/aead.c (c0000000007429d0)
Location: include/crypto/internal/aead.h:48
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
```
```
In crypto/seqiv.c (c0000000007477dc)
Location: include/crypto/internal/aead.h:48
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_free
```
```
In crypto/gcm.c (c000000000756a38)
Location: include/crypto/internal/aead.h:48
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4106_init_tfm
  - crypto/gcm.c:crypto_gcm_init_tfm
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
In crypto/aead.c (ffffffe000401824)
Location: include/crypto/internal/aead.h:48
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
```
```
In crypto/seqiv.c (ffffffe000404af6)
Location: include/crypto/internal/aead.h:48
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_free
```
```
In crypto/gcm.c (ffffffe00040fc4e)
Location: include/crypto/internal/aead.h:48
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4106_init_tfm
  - crypto/gcm.c:crypto_gcm_init_tfm
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
In crypto/aead.c (ffffffff814b9f79)
Location: include/crypto/internal/aead.h:48
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
```
```
In crypto/seqiv.c (ffffffff814bd455)
Location: include/crypto/internal/aead.h:48
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_free
```
```
In crypto/gcm.c (ffffffff814c7dd5)
Location: include/crypto/internal/aead.h:48
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4106_init_tfm
  - crypto/gcm.c:crypto_gcm_init_tfm
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
In crypto/aead.c (ffffffff814aa999)
Location: include/crypto/internal/aead.h:48
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
```
```
In crypto/seqiv.c (ffffffff814ade75)
Location: include/crypto/internal/aead.h:48
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_free
```
```
In crypto/gcm.c (ffffffff814b87f5)
Location: include/crypto/internal/aead.h:48
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4106_init_tfm
  - crypto/gcm.c:crypto_gcm_init_tfm
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
In crypto/aead.c (ffffffff814b6009)
Location: include/crypto/internal/aead.h:48
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
```
```
In crypto/seqiv.c (ffffffff814b94e5)
Location: include/crypto/internal/aead.h:48
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_free
```
```
In crypto/gcm.c (ffffffff814c3e65)
Location: include/crypto/internal/aead.h:48
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4106_init_tfm
  - crypto/gcm.c:crypto_gcm_init_tfm
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
In crypto/aead.c (ffffffff814ceaa9)
Location: include/crypto/internal/aead.h:48
Inline: True
Inline callers:
  - crypto/aead.c:aead_init_geniv
```
```
In crypto/seqiv.c (ffffffff814d1f85)
Location: include/crypto/internal/aead.h:48
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_free
```
```
In crypto/gcm.c (ffffffff814dc935)
Location: include/crypto/internal/aead.h:48
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4106_init_tfm
  - crypto/gcm.c:crypto_gcm_init_tfm
```
</details>
</li>
</ul>

## Differences
