# Function: <code>crypto_drop_aead</code>

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
In crypto/aead.c (ffffffff8139f09d)
Location: include/crypto/internal/aead.h:92
Inline: True
Inline callers:
  - crypto/aead.c:aead_geniv_free
  - crypto/aead.c:aead_geniv_alloc
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
In crypto/aead.c (ffffffff813dbe3d)
Location: include/crypto/internal/aead.h:98
Inline: True
Inline callers:
  - crypto/aead.c:aead_geniv_free
  - crypto/aead.c:aead_geniv_alloc
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
In crypto/aead.c (ffffffff813f371d)
Location: include/crypto/internal/aead.h:98
Inline: True
Inline callers:
  - crypto/aead.c:aead_geniv_free
  - crypto/aead.c:aead_geniv_alloc
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
In crypto/aead.c (ffffffff813ffa3d)
Location: include/crypto/internal/aead.h:98
Inline: True
Inline callers:
  - crypto/aead.c:aead_geniv_free
  - crypto/aead.c:aead_geniv_alloc
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
In crypto/aead.c (ffffffff8142802d)
Location: include/crypto/internal/aead.h:98
Inline: True
Inline callers:
  - crypto/aead.c:aead_geniv_free
  - crypto/aead.c:aead_geniv_alloc
```
```
In crypto/gcm.c (ffffffff814396b8)
Location: include/crypto/internal/aead.h:98
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_rfc4106_free
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
In crypto/aead.c (ffffffff8145ae65)
Location: include/crypto/internal/aead.h:98
Inline: True
Inline callers:
  - crypto/aead.c:aead_geniv_free
  - crypto/aead.c:aead_geniv_alloc
```
```
In crypto/gcm.c (ffffffff8146be65)
Location: include/crypto/internal/aead.h:98
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_rfc4106_free
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
In crypto/aead.c (ffffffff814789e5)
Location: include/crypto/internal/aead.h:98
Inline: True
Inline callers:
  - crypto/aead.c:aead_geniv_free
  - crypto/aead.c:aead_geniv_alloc
```
```
In crypto/gcm.c (ffffffff8148990e)
Location: include/crypto/internal/aead.h:98
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_rfc4106_free
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
In crypto/aead.c (ffffffff814a6805)
Location: include/crypto/internal/aead.h:93
Inline: True
Inline callers:
  - crypto/aead.c:aead_geniv_free
  - crypto/aead.c:aead_geniv_alloc
```
```
In crypto/gcm.c (ffffffff814b71fb)
Location: include/crypto/internal/aead.h:93
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4543_free
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_rfc4106_free
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
In crypto/aead.c (ffffffff814c1475)
Location: include/crypto/internal/aead.h:93
Inline: True
Inline callers:
  - crypto/aead.c:aead_geniv_free
  - crypto/aead.c:aead_geniv_alloc
```
```
In crypto/gcm.c (ffffffff814d041b)
Location: include/crypto/internal/aead.h:93
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4543_free
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_rfc4106_free
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
In crypto/geniv.c (ffffffff81522492)
Location: include/crypto/internal/aead.h:88
Inline: True
Inline callers:
  - crypto/geniv.c:aead_geniv_alloc
```
```
In crypto/gcm.c (ffffffff8152f6dc)
Location: include/crypto/internal/aead.h:88
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
In crypto/geniv.c (ffffffff8153f36a)
Location: include/crypto/internal/aead.h:88
Inline: True
Inline callers:
  - crypto/geniv.c:aead_geniv_alloc
```
```
In crypto/gcm.c (ffffffff8154c7e4)
Location: include/crypto/internal/aead.h:88
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
In crypto/geniv.c (ffffffff815479f2)
Location: include/crypto/internal/aead.h:88
Inline: True
Inline callers:
  - crypto/geniv.c:aead_geniv_alloc
```
```
In crypto/gcm.c (ffffffff81554aa9)
Location: include/crypto/internal/aead.h:88
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
In crypto/geniv.c (ffffffff815a81d2)
Location: include/crypto/internal/aead.h:88
Inline: True
Inline callers:
  - crypto/geniv.c:aead_geniv_alloc
```
```
In crypto/gcm.c (ffffffff815b5ca9)
Location: include/crypto/internal/aead.h:88
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
In crypto/geniv.c (ffffffff8164f597)
Location: include/crypto/internal/aead.h:88
Inline: True
Inline callers:
  - crypto/geniv.c:aead_geniv_alloc
```
```
In crypto/gcm.c (ffffffff8165ef0f)
Location: include/crypto/internal/aead.h:88
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
In crypto/geniv.c (ffffffff81708ba7)
Location: include/crypto/internal/aead.h:103
Inline: True
Inline callers:
  - crypto/geniv.c:aead_geniv_alloc
```
```
In crypto/gcm.c (ffffffff81718c8f)
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
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/geniv.c (ffffffff81742377)
Location: include/crypto/internal/aead.h:103
Inline: True
Inline callers:
  - crypto/geniv.c:aead_geniv_alloc
```
```
In crypto/gcm.c (ffffffff817547ff)
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
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/geniv.c (ffffffff81783286)
Location: include/crypto/internal/aead.h:103
Inline: True
Inline callers:
  - crypto/geniv.c:aead_geniv_alloc
```
```
In crypto/gcm.c (ffffffff81795f8e)
Location: include/crypto/internal/aead.h:103
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
In crypto/aead.c (ffff8000105bb7e0)
Location: include/crypto/internal/aead.h:93
Inline: True
Inline callers:
  - crypto/aead.c:aead_geniv_free
  - crypto/aead.c:aead_geniv_alloc
```
```
In crypto/gcm.c (ffff8000105cbb88)
Location: include/crypto/internal/aead.h:93
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_rfc4106_free
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
In crypto/aead.c (c0769a08)
Location: include/crypto/internal/aead.h:93
Inline: True
Inline callers:
  - crypto/aead.c:aead_geniv_free
  - crypto/aead.c:aead_geniv_alloc
```
```
In crypto/gcm.c (c077956c)
Location: include/crypto/internal/aead.h:93
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_rfc4106_free
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
In crypto/aead.c (c000000000742190)
Location: include/crypto/internal/aead.h:93
Inline: True
Inline callers:
  - crypto/aead.c:aead_geniv_free
  - crypto/aead.c:aead_geniv_alloc
```
```
In crypto/gcm.c (c00000000075880c)
Location: include/crypto/internal/aead.h:93
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4543_free
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_rfc4106_free
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
In crypto/aead.c (ffffffe000401210)
Location: include/crypto/internal/aead.h:93
Inline: True
Inline callers:
  - crypto/aead.c:aead_geniv_free
  - crypto/aead.c:aead_geniv_alloc
```
```
In crypto/gcm.c (ffffffe000411132)
Location: include/crypto/internal/aead.h:93
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_rfc4106_free
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
In crypto/aead.c (ffffffff814b9a55)
Location: include/crypto/internal/aead.h:93
Inline: True
Inline callers:
  - crypto/aead.c:aead_geniv_free
  - crypto/aead.c:aead_geniv_alloc
```
```
In crypto/gcm.c (ffffffff814c89fb)
Location: include/crypto/internal/aead.h:93
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4543_free
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_rfc4106_free
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
In crypto/aead.c (ffffffff814aa475)
Location: include/crypto/internal/aead.h:93
Inline: True
Inline callers:
  - crypto/aead.c:aead_geniv_free
  - crypto/aead.c:aead_geniv_alloc
```
```
In crypto/gcm.c (ffffffff814b941b)
Location: include/crypto/internal/aead.h:93
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4543_free
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_rfc4106_free
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
In crypto/aead.c (ffffffff814b5ae5)
Location: include/crypto/internal/aead.h:93
Inline: True
Inline callers:
  - crypto/aead.c:aead_geniv_free
  - crypto/aead.c:aead_geniv_alloc
```
```
In crypto/gcm.c (ffffffff814c4a8b)
Location: include/crypto/internal/aead.h:93
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4543_free
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_rfc4106_free
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
In crypto/aead.c (ffffffff814ce585)
Location: include/crypto/internal/aead.h:93
Inline: True
Inline callers:
  - crypto/aead.c:aead_geniv_free
  - crypto/aead.c:aead_geniv_alloc
```
```
In crypto/gcm.c (ffffffff814dd55b)
Location: include/crypto/internal/aead.h:93
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4543_free
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_rfc4106_free
```
</details>
</li>
</ul>

## Differences
