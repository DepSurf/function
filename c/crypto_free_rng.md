# Function: <code>crypto_free_rng</code>

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
In crypto/rng.c (ffffffff813abcc2)
Location: include/crypto/rng.h:120
Inline: True
Inline callers:
  - crypto/rng.c:crypto_get_default_rng
  - crypto/rng.c:crypto_del_default_rng
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
In security/keys/big_key.c (ffffffff81fc2d53)
Location: include/crypto/rng.h:120
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_crypto_init
```
```
In crypto/rng.c (ffffffff813eb547)
Location: include/crypto/rng.h:120
Inline: True
Inline callers:
  - crypto/rng.c:crypto_del_default_rng
  - crypto/rng.c:crypto_get_default_rng
```
```
In crypto/drbg.c (ffffffff813ee256)
Location: include/crypto/rng.h:120
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_uninstantiate
  - crypto/drbg.c:drbg_async_seed
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
In security/keys/big_key.c (ffffffff81fff7a8)
Location: include/crypto/rng.h:120
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_init
```
```
In crypto/rng.c (ffffffff81404c97)
Location: include/crypto/rng.h:120
Inline: True
Inline callers:
  - crypto/rng.c:crypto_del_default_rng
  - crypto/rng.c:crypto_get_default_rng
```
```
In crypto/drbg.c (ffffffff81407a96)
Location: include/crypto/rng.h:120
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_uninstantiate
  - crypto/drbg.c:drbg_async_seed
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
In security/keys/big_key.c (ffffffff820e2a7b)
Location: include/crypto/rng.h:120
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_init
```
```
In crypto/rng.c (ffffffff814123f7)
Location: include/crypto/rng.h:120
Inline: True
Inline callers:
  - crypto/rng.c:crypto_del_default_rng
  - crypto/rng.c:crypto_get_default_rng
```
```
In crypto/drbg.c (ffffffff814151c6)
Location: include/crypto/rng.h:120
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_uninstantiate
  - crypto/drbg.c:drbg_async_seed
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
In crypto/rng.c (ffffffff8143cb87)
Location: include/crypto/rng.h:120
Inline: True
Inline callers:
  - crypto/rng.c:crypto_del_default_rng
  - crypto/rng.c:crypto_get_default_rng
```
```
In crypto/drbg.c (ffffffff8143f996)
Location: include/crypto/rng.h:120
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_uninstantiate
  - crypto/drbg.c:drbg_async_seed
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
In crypto/rng.c (ffffffff8146f9b7)
Location: include/crypto/rng.h:120
Inline: True
Inline callers:
  - crypto/rng.c:crypto_del_default_rng
  - crypto/rng.c:crypto_get_default_rng
```
```
In crypto/drbg.c (ffffffff814727c6)
Location: include/crypto/rng.h:120
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_uninstantiate
  - crypto/drbg.c:drbg_async_seed
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
In crypto/rng.c (ffffffff8148d397)
Location: include/crypto/rng.h:120
Inline: True
Inline callers:
  - crypto/rng.c:crypto_del_default_rng
  - crypto/rng.c:crypto_get_default_rng
```
```
In crypto/drbg.c (ffffffff8148fc16)
Location: include/crypto/rng.h:120
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_uninstantiate
  - crypto/drbg.c:drbg_async_seed
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
In crypto/rng.c (ffffffff814bad1a)
Location: include/crypto/rng.h:115
Inline: True
Inline callers:
  - crypto/rng.c:crypto_del_default_rng
  - crypto/rng.c:crypto_get_default_rng
```
```
In crypto/drbg.c (ffffffff814bd106)
Location: include/crypto/rng.h:115
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_uninstantiate
  - crypto/drbg.c:drbg_async_seed
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
In crypto/rng.c (ffffffff814d3aea)
Location: include/crypto/rng.h:115
Inline: True
Inline callers:
  - crypto/rng.c:crypto_del_default_rng
  - crypto/rng.c:crypto_get_default_rng
```
```
In crypto/drbg.c (ffffffff814d5da6)
Location: include/crypto/rng.h:115
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_uninstantiate
  - crypto/drbg.c:drbg_async_seed
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
In crypto/rng.c (ffffffff81532c6a)
Location: include/crypto/rng.h:115
Inline: True
Inline callers:
  - crypto/rng.c:crypto_del_default_rng
  - crypto/rng.c:crypto_get_default_rng
```
```
In crypto/drbg.c (ffffffff81534754)
Location: include/crypto/rng.h:115
Inline: True
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
In crypto/rng.c (ffffffff8154fbda)
Location: include/crypto/rng.h:115
Inline: True
Inline callers:
  - crypto/rng.c:crypto_del_default_rng
  - crypto/rng.c:crypto_get_default_rng
```
```
In crypto/drbg.c (ffffffff815516a4)
Location: include/crypto/rng.h:115
Inline: True
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
In crypto/rng.c (ffffffff815585ca)
Location: include/crypto/rng.h:117
Inline: True
Inline callers:
  - crypto/rng.c:crypto_del_default_rng
  - crypto/rng.c:crypto_get_default_rng
```
```
In crypto/drbg.c (ffffffff81559e94)
Location: include/crypto/rng.h:117
Inline: True
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
In crypto/rng.c (ffffffff815b987a)
Location: include/crypto/rng.h:117
Inline: True
Inline callers:
  - crypto/rng.c:crypto_del_default_rng
  - crypto/rng.c:crypto_get_default_rng
```
```
In crypto/drbg.c (ffffffff815bb114)
Location: include/crypto/rng.h:117
Inline: True
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
In crypto/rng.c (ffffffff81662df7)
Location: include/crypto/rng.h:117
Inline: True
Inline callers:
  - crypto/rng.c:crypto_del_default_rng
  - crypto/rng.c:crypto_get_default_rng
```
```
In crypto/drbg.c (ffffffff81664b12)
Location: include/crypto/rng.h:117
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
In crypto/rng.c (ffffffff8171cfe7)
Location: include/crypto/rng.h:117
Inline: True
Inline callers:
  - crypto/rng.c:crypto_del_default_rng
  - crypto/rng.c:crypto_get_default_rng
```
```
In crypto/drbg.c (ffffffff8171ee82)
Location: include/crypto/rng.h:117
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
In crypto/rng.c (ffffffff81758837)
Location: include/crypto/rng.h:142
Inline: True
Inline callers:
  - crypto/rng.c:crypto_del_default_rng
  - crypto/rng.c:crypto_get_default_rng
```
```
In crypto/drbg.c (ffffffff8175a792)
Location: include/crypto/rng.h:142
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
In crypto/rng.c (ffffffff8179a737)
Location: include/crypto/rng.h:142
Inline: True
Inline callers:
  - crypto/rng.c:crypto_del_default_rng
  - crypto/rng.c:crypto_get_default_rng
```
```
In crypto/drbg.c (ffffffff8179c692)
Location: include/crypto/rng.h:142
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
In crypto/rng.c (ffff8000105d0544)
Location: include/crypto/rng.h:115
Inline: True
Inline callers:
  - crypto/rng.c:crypto_del_default_rng
  - crypto/rng.c:crypto_get_default_rng
```
```
In crypto/drbg.c (ffff8000105d189c)
Location: include/crypto/rng.h:115
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_uninstantiate
  - crypto/drbg.c:drbg_async_seed
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
In crypto/rng.c (c077df60)
Location: include/crypto/rng.h:115
Inline: True
Inline callers:
  - crypto/rng.c:crypto_del_default_rng
  - crypto/rng.c:crypto_get_default_rng
```
```
In crypto/drbg.c (c077f528)
Location: include/crypto/rng.h:115
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_uninstantiate
  - crypto/drbg.c:drbg_async_seed
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
In crypto/rng.c (c00000000075c7c4)
Location: include/crypto/rng.h:115
Inline: True
Inline callers:
  - crypto/rng.c:crypto_del_default_rng
  - crypto/rng.c:crypto_get_default_rng
```
```
In crypto/drbg.c (c00000000075e9e0)
Location: include/crypto/rng.h:115
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_uninstantiate
  - crypto/drbg.c:drbg_async_seed
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
In crypto/rng.c (ffffffe0004151ec)
Location: include/crypto/rng.h:115
Inline: True
Inline callers:
  - crypto/rng.c:crypto_del_default_rng
  - crypto/rng.c:crypto_get_default_rng
```
```
In crypto/drbg.c (ffffffe0004165b0)
Location: include/crypto/rng.h:115
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_uninstantiate
  - crypto/drbg.c:drbg_async_seed
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
In crypto/rng.c (ffffffff814cc0ca)
Location: include/crypto/rng.h:115
Inline: True
Inline callers:
  - crypto/rng.c:crypto_del_default_rng
  - crypto/rng.c:crypto_get_default_rng
```
```
In crypto/drbg.c (ffffffff814ce386)
Location: include/crypto/rng.h:115
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_uninstantiate
  - crypto/drbg.c:drbg_async_seed
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
In crypto/rng.c (ffffffff814bcaea)
Location: include/crypto/rng.h:115
Inline: True
Inline callers:
  - crypto/rng.c:crypto_del_default_rng
  - crypto/rng.c:crypto_get_default_rng
```
```
In crypto/drbg.c (ffffffff814beda6)
Location: include/crypto/rng.h:115
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_uninstantiate
  - crypto/drbg.c:drbg_async_seed
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
In crypto/rng.c (ffffffff814c815a)
Location: include/crypto/rng.h:115
Inline: True
Inline callers:
  - crypto/rng.c:crypto_del_default_rng
  - crypto/rng.c:crypto_get_default_rng
```
```
In crypto/drbg.c (ffffffff814ca416)
Location: include/crypto/rng.h:115
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_uninstantiate
  - crypto/drbg.c:drbg_async_seed
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
In crypto/rng.c (ffffffff814e0c2a)
Location: include/crypto/rng.h:115
Inline: True
Inline callers:
  - crypto/rng.c:crypto_del_default_rng
  - crypto/rng.c:crypto_get_default_rng
```
```
In crypto/drbg.c (ffffffff814e2ee6)
Location: include/crypto/rng.h:115
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_uninstantiate
  - crypto/drbg.c:drbg_async_seed
```
</details>
</li>
</ul>

## Differences
