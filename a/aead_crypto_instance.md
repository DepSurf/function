# Function: <code>aead_crypto_instance</code>

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
In crypto/aead.c (ffffffff8139f4ca)
Location: include/crypto/internal/aead.h:47
Inline: True
Inline callers:
  - crypto/aead.c:aead_register_instance
  - crypto/aead.c:aead_geniv_alloc
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
In crypto/aead.c (ffffffff813dc28a)
Location: include/crypto/internal/aead.h:47
Inline: True
Inline callers:
  - crypto/aead.c:aead_register_instance
  - crypto/aead.c:aead_geniv_alloc
```
```
In crypto/seqiv.c (0)
Location: include/crypto/internal/aead.h:47
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
In crypto/aead.c (ffffffff813f3b6a)
Location: include/crypto/internal/aead.h:47
Inline: True
Inline callers:
  - crypto/aead.c:aead_register_instance
  - crypto/aead.c:aead_geniv_alloc
```
```
In crypto/seqiv.c (0)
Location: include/crypto/internal/aead.h:47
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
In crypto/aead.c (ffffffff813ffeca)
Location: include/crypto/internal/aead.h:47
Inline: True
Inline callers:
  - crypto/aead.c:aead_register_instance
  - crypto/aead.c:aead_geniv_alloc
```
```
In crypto/seqiv.c (0)
Location: include/crypto/internal/aead.h:47
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
In crypto/aead.c (ffffffff814284ba)
Location: include/crypto/internal/aead.h:47
Inline: True
Inline callers:
  - crypto/aead.c:aead_register_instance
  - crypto/aead.c:aead_geniv_alloc
```
```
In crypto/seqiv.c (0)
Location: include/crypto/internal/aead.h:47
Inline: True
```
```
In crypto/gcm.c (ffffffff8143966f)
Location: include/crypto/internal/aead.h:47
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_gcm_create_common
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
In crypto/aead.c (ffffffff8145b2e7)
Location: include/crypto/internal/aead.h:47
Inline: True
Inline callers:
  - crypto/aead.c:aead_register_instance
  - crypto/aead.c:aead_init_geniv
  - crypto/aead.c:aead_geniv_free
  - crypto/aead.c:aead_geniv_alloc
  - crypto/aead.c:aead_geniv_alloc
```
```
In crypto/gcm.c (ffffffff8146be1f)
Location: include/crypto/internal/aead.h:47
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_rfc4106_free
  - crypto/gcm.c:crypto_rfc4106_init_tfm
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_free
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
In crypto/aead.c (ffffffff81478da7)
Location: include/crypto/internal/aead.h:47
Inline: True
Inline callers:
  - crypto/aead.c:aead_register_instance
  - crypto/aead.c:aead_init_geniv
  - crypto/aead.c:aead_geniv_free
  - crypto/aead.c:aead_geniv_alloc
  - crypto/aead.c:aead_geniv_alloc
```
```
In crypto/gcm.c (ffffffff814898bf)
Location: include/crypto/internal/aead.h:47
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_rfc4106_free
  - crypto/gcm.c:crypto_rfc4106_init_tfm
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_free
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
In crypto/aead.c (ffffffff814a6ba7)
Location: include/crypto/internal/aead.h:42
Inline: True
Inline callers:
  - crypto/aead.c:aead_register_instance
  - crypto/aead.c:aead_init_geniv
  - crypto/aead.c:aead_geniv_free
  - crypto/aead.c:aead_geniv_alloc
  - crypto/aead.c:aead_geniv_alloc
```
```
In crypto/gcm.c (ffffffff814b71b4)
Location: include/crypto/internal/aead.h:42
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4543_free
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_rfc4106_free
  - crypto/gcm.c:crypto_rfc4106_init_tfm
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_free
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
In crypto/aead.c (ffffffff814c1817)
Location: include/crypto/internal/aead.h:42
Inline: True
Inline callers:
  - crypto/aead.c:aead_register_instance
  - crypto/aead.c:aead_init_geniv
  - crypto/aead.c:aead_geniv_free
  - crypto/aead.c:aead_geniv_alloc
  - crypto/aead.c:aead_geniv_alloc
```
```
In crypto/gcm.c (ffffffff814d03d4)
Location: include/crypto/internal/aead.h:42
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4543_free
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_rfc4106_free
  - crypto/gcm.c:crypto_rfc4106_init_tfm
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_free
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
In crypto/aead.c (ffffffff815220ad)
Location: include/crypto/internal/aead.h:42
Inline: True
Inline callers:
  - crypto/aead.c:aead_register_instance
```
```
In crypto/geniv.c (ffffffff8152235d)
Location: include/crypto/internal/aead.h:42
Inline: True
Inline callers:
  - crypto/geniv.c:aead_init_geniv
  - crypto/geniv.c:aead_geniv_alloc
  - crypto/geniv.c:aead_geniv_alloc
  - crypto/geniv.c:aead_geniv_alloc
```
```
In crypto/gcm.c (ffffffff8152f69d)
Location: include/crypto/internal/aead.h:42
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_rfc4106_init_tfm
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_create_common
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
In crypto/aead.c (ffffffff8153ef8d)
Location: include/crypto/internal/aead.h:42
Inline: True
Inline callers:
  - crypto/aead.c:aead_register_instance
```
```
In crypto/geniv.c (ffffffff8153f23d)
Location: include/crypto/internal/aead.h:42
Inline: True
Inline callers:
  - crypto/geniv.c:aead_init_geniv
  - crypto/geniv.c:aead_geniv_alloc
  - crypto/geniv.c:aead_geniv_alloc
  - crypto/geniv.c:aead_geniv_alloc
```
```
In crypto/gcm.c (ffffffff8154c774)
Location: include/crypto/internal/aead.h:42
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_rfc4106_init_tfm
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_create_common
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
In crypto/aead.c (ffffffff8154760e)
Location: include/crypto/internal/aead.h:42
Inline: True
Inline callers:
  - crypto/aead.c:aead_register_instance
```
```
In crypto/geniv.c (ffffffff815478bd)
Location: include/crypto/internal/aead.h:42
Inline: True
Inline callers:
  - crypto/geniv.c:aead_init_geniv
  - crypto/geniv.c:aead_geniv_alloc
  - crypto/geniv.c:aead_geniv_alloc
  - crypto/geniv.c:aead_geniv_alloc
```
```
In crypto/gcm.c (ffffffff81554a3a)
Location: include/crypto/internal/aead.h:42
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_rfc4106_init_tfm
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_create_common
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
In crypto/aead.c (ffffffff815a7dee)
Location: include/crypto/internal/aead.h:42
Inline: True
Inline callers:
  - crypto/aead.c:aead_register_instance
```
```
In crypto/geniv.c (ffffffff815a809d)
Location: include/crypto/internal/aead.h:42
Inline: True
Inline callers:
  - crypto/geniv.c:aead_init_geniv
  - crypto/geniv.c:aead_geniv_alloc
  - crypto/geniv.c:aead_geniv_alloc
  - crypto/geniv.c:aead_geniv_alloc
```
```
In crypto/gcm.c (ffffffff815b5c3a)
Location: include/crypto/internal/aead.h:42
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_rfc4106_init_tfm
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_create_common
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
In crypto/aead.c (ffffffff8164f13e)
Location: include/crypto/internal/aead.h:42
Inline: True
Inline callers:
  - crypto/aead.c:aead_register_instance
```
```
In crypto/geniv.c (ffffffff8164f56b)
Location: include/crypto/internal/aead.h:42
Inline: True
Inline callers:
  - crypto/geniv.c:aead_geniv_alloc
```
```
In crypto/gcm.c (ffffffff8165eebf)
Location: include/crypto/internal/aead.h:42
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_gcm_create_common
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
In crypto/aead.c (ffffffff817085ae)
Location: include/crypto/internal/aead.h:47
Inline: True
Inline callers:
  - crypto/aead.c:aead_register_instance
```
```
In crypto/geniv.c (ffffffff81708b7b)
Location: include/crypto/internal/aead.h:47
Inline: True
Inline callers:
  - crypto/geniv.c:aead_geniv_alloc
```
```
In crypto/gcm.c (ffffffff81718c3f)
Location: include/crypto/internal/aead.h:47
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_gcm_create_common
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
In crypto/aead.c (ffffffff81741d32)
Location: include/crypto/internal/aead.h:47
Inline: True
Inline callers:
  - crypto/aead.c:aead_register_instance
```
```
In crypto/geniv.c (ffffffff8174234b)
Location: include/crypto/internal/aead.h:47
Inline: True
Inline callers:
  - crypto/geniv.c:aead_geniv_alloc
```
```
In crypto/gcm.c (ffffffff817547af)
Location: include/crypto/internal/aead.h:47
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_gcm_create_common
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
In crypto/aead.c (ffffffff81782c12)
Location: include/crypto/internal/aead.h:47
Inline: True
Inline callers:
  - crypto/aead.c:aead_register_instance
```
```
In crypto/geniv.c (ffffffff8178325a)
Location: include/crypto/internal/aead.h:47
Inline: True
Inline callers:
  - crypto/geniv.c:aead_geniv_alloc
```
```
In crypto/gcm.c (ffffffff81795f3e)
Location: include/crypto/internal/aead.h:47
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_gcm_create_common
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
In crypto/aead.c (ffff8000105bbe6c)
Location: include/crypto/internal/aead.h:42
Inline: True
Inline callers:
  - crypto/aead.c:aead_register_instance
  - crypto/aead.c:aead_init_geniv
  - crypto/aead.c:aead_geniv_free
  - crypto/aead.c:aead_geniv_alloc
  - crypto/aead.c:aead_geniv_alloc
```
```
In crypto/gcm.c (ffff8000105cbb3c)
Location: include/crypto/internal/aead.h:42
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_rfc4106_free
  - crypto/gcm.c:crypto_rfc4106_init_tfm
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_free
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
In crypto/aead.c (c0769f9c)
Location: include/crypto/internal/aead.h:42
Inline: True
Inline callers:
  - crypto/aead.c:aead_register_instance
  - crypto/aead.c:aead_init_geniv
  - crypto/aead.c:aead_geniv_free
  - crypto/aead.c:aead_geniv_alloc
  - crypto/aead.c:aead_geniv_alloc
```
```
In crypto/gcm.c (c0779520)
Location: include/crypto/internal/aead.h:42
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_rfc4106_free
  - crypto/gcm.c:crypto_rfc4106_init_tfm
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_free
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
In crypto/aead.c (c00000000074275c)
Location: include/crypto/internal/aead.h:42
Inline: True
Inline callers:
  - crypto/aead.c:aead_register_instance
  - crypto/aead.c:aead_init_geniv
  - crypto/aead.c:aead_geniv_free
  - crypto/aead.c:aead_geniv_alloc
  - crypto/aead.c:aead_geniv_alloc
```
```
In crypto/gcm.c (c0000000007587b8)
Location: include/crypto/internal/aead.h:42
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4543_free
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_rfc4106_free
  - crypto/gcm.c:crypto_rfc4106_init_tfm
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_free
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
In crypto/aead.c (ffffffe00040162e)
Location: include/crypto/internal/aead.h:42
Inline: True
Inline callers:
  - crypto/aead.c:aead_register_instance
  - crypto/aead.c:aead_init_geniv
  - crypto/aead.c:aead_geniv_free
  - crypto/aead.c:aead_geniv_alloc
  - crypto/aead.c:aead_geniv_alloc
```
```
In crypto/gcm.c (ffffffe0004110f6)
Location: include/crypto/internal/aead.h:42
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_rfc4106_free
  - crypto/gcm.c:crypto_rfc4106_init_tfm
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_free
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
In crypto/aead.c (ffffffff814b9df7)
Location: include/crypto/internal/aead.h:42
Inline: True
Inline callers:
  - crypto/aead.c:aead_register_instance
  - crypto/aead.c:aead_init_geniv
  - crypto/aead.c:aead_geniv_free
  - crypto/aead.c:aead_geniv_alloc
  - crypto/aead.c:aead_geniv_alloc
```
```
In crypto/gcm.c (ffffffff814c89b4)
Location: include/crypto/internal/aead.h:42
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4543_free
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_rfc4106_free
  - crypto/gcm.c:crypto_rfc4106_init_tfm
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_free
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
In crypto/aead.c (ffffffff814aa817)
Location: include/crypto/internal/aead.h:42
Inline: True
Inline callers:
  - crypto/aead.c:aead_register_instance
  - crypto/aead.c:aead_init_geniv
  - crypto/aead.c:aead_geniv_free
  - crypto/aead.c:aead_geniv_alloc
  - crypto/aead.c:aead_geniv_alloc
```
```
In crypto/gcm.c (ffffffff814b93d4)
Location: include/crypto/internal/aead.h:42
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4543_free
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_rfc4106_free
  - crypto/gcm.c:crypto_rfc4106_init_tfm
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_free
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
In crypto/aead.c (ffffffff814b5e87)
Location: include/crypto/internal/aead.h:42
Inline: True
Inline callers:
  - crypto/aead.c:aead_register_instance
  - crypto/aead.c:aead_init_geniv
  - crypto/aead.c:aead_geniv_free
  - crypto/aead.c:aead_geniv_alloc
  - crypto/aead.c:aead_geniv_alloc
```
```
In crypto/gcm.c (ffffffff814c4a44)
Location: include/crypto/internal/aead.h:42
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4543_free
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_rfc4106_free
  - crypto/gcm.c:crypto_rfc4106_init_tfm
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_free
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
In crypto/aead.c (ffffffff814ce927)
Location: include/crypto/internal/aead.h:42
Inline: True
Inline callers:
  - crypto/aead.c:aead_register_instance
  - crypto/aead.c:aead_init_geniv
  - crypto/aead.c:aead_geniv_free
  - crypto/aead.c:aead_geniv_alloc
  - crypto/aead.c:aead_geniv_alloc
```
```
In crypto/gcm.c (ffffffff814dd514)
Location: include/crypto/internal/aead.h:42
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4543_free
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_rfc4106_free
  - crypto/gcm.c:crypto_rfc4106_init_tfm
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_free
  - crypto/gcm.c:crypto_gcm_init_tfm
```
</details>
</li>
</ul>

## Differences
