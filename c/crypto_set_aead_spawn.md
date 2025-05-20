# Function: <code>crypto_set_aead_spawn</code>

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
Location: include/crypto/internal/aead.h:83
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
Location: include/crypto/internal/aead.h:89
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
Location: include/crypto/internal/aead.h:89
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
Location: include/crypto/internal/aead.h:89
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
Location: include/crypto/internal/aead.h:89
Inline: True
```
```
In crypto/gcm.c (0)
Location: include/crypto/internal/aead.h:89
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
In crypto/aead.c (ffffffff8145b3f5)
Location: include/crypto/internal/aead.h:89
Inline: True
Inline callers:
  - crypto/aead.c:aead_geniv_alloc
```
```
In crypto/gcm.c (ffffffff8146be26)
Location: include/crypto/internal/aead.h:89
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
In crypto/aead.c (ffffffff81478f94)
Location: include/crypto/internal/aead.h:89
Inline: True
Inline callers:
  - crypto/aead.c:aead_geniv_alloc
```
```
In crypto/gcm.c (ffffffff814898c6)
Location: include/crypto/internal/aead.h:89
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
In crypto/aead.c (ffffffff814a6eca)
Location: include/crypto/internal/aead.h:84
Inline: True
Inline callers:
  - crypto/aead.c:aead_geniv_alloc
```
```
In crypto/gcm.c (ffffffff814b71bb)
Location: include/crypto/internal/aead.h:84
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
In crypto/aead.c (ffffffff814c1b3a)
Location: include/crypto/internal/aead.h:84
Inline: True
Inline callers:
  - crypto/aead.c:aead_geniv_alloc
```
```
In crypto/gcm.c (ffffffff814d03db)
Location: include/crypto/internal/aead.h:84
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In crypto/aead.c (ffff8000105bb92c)
Location: include/crypto/internal/aead.h:84
Inline: True
Inline callers:
  - crypto/aead.c:aead_geniv_alloc
```
```
In crypto/gcm.c (ffff8000105cbb48)
Location: include/crypto/internal/aead.h:84
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
In crypto/aead.c (c0769b04)
Location: include/crypto/internal/aead.h:84
Inline: True
Inline callers:
  - crypto/aead.c:aead_geniv_alloc
```
```
In crypto/gcm.c (c0779530)
Location: include/crypto/internal/aead.h:84
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
In crypto/aead.c (c000000000742c4c)
Location: include/crypto/internal/aead.h:84
Inline: True
Inline callers:
  - crypto/aead.c:aead_geniv_alloc
```
```
In crypto/gcm.c (c0000000007587c0)
Location: include/crypto/internal/aead.h:84
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
In crypto/aead.c (ffffffe000401968)
Location: include/crypto/internal/aead.h:84
Inline: True
Inline callers:
  - crypto/aead.c:aead_geniv_alloc
```
```
In crypto/gcm.c (ffffffe0004110fa)
Location: include/crypto/internal/aead.h:84
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
In crypto/aead.c (ffffffff814ba11a)
Location: include/crypto/internal/aead.h:84
Inline: True
Inline callers:
  - crypto/aead.c:aead_geniv_alloc
```
```
In crypto/gcm.c (ffffffff814c89bb)
Location: include/crypto/internal/aead.h:84
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
In crypto/aead.c (ffffffff814aab3a)
Location: include/crypto/internal/aead.h:84
Inline: True
Inline callers:
  - crypto/aead.c:aead_geniv_alloc
```
```
In crypto/gcm.c (ffffffff814b93db)
Location: include/crypto/internal/aead.h:84
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
In crypto/aead.c (ffffffff814b61aa)
Location: include/crypto/internal/aead.h:84
Inline: True
Inline callers:
  - crypto/aead.c:aead_geniv_alloc
```
```
In crypto/gcm.c (ffffffff814c4a4b)
Location: include/crypto/internal/aead.h:84
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
In crypto/aead.c (ffffffff814cec4a)
Location: include/crypto/internal/aead.h:84
Inline: True
Inline callers:
  - crypto/aead.c:aead_geniv_alloc
```
```
In crypto/gcm.c (ffffffff814dd51b)
Location: include/crypto/internal/aead.h:84
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
```
</details>
</li>
</ul>

## Differences
