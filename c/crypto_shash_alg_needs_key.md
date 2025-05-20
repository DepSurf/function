# Function: <code>crypto_shash_alg_needs_key</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff81525535)
Location: include/crypto/internal/hash.h:99
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:shash_async_setkey
```
```
In crypto/hmac.c (ffffffff81529323)
Location: include/crypto/internal/hash.h:99
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
In crypto/shash.c (ffffffff81542465)
Location: include/crypto/internal/hash.h:86
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:shash_async_setkey
```
```
In crypto/hmac.c (ffffffff81546337)
Location: include/crypto/internal/hash.h:86
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_create
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
In crypto/shash.c (ffffffff8154ab05)
Location: include/crypto/internal/hash.h:80
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:shash_async_setkey
```
```
In crypto/hmac.c (ffffffff8154e9d0)
Location: include/crypto/internal/hash.h:80
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_create
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
In crypto/shash.c (ffffffff815ab2e5)
Location: include/crypto/internal/hash.h:80
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:shash_async_setkey
```
```
In crypto/hmac.c (ffffffff815af320)
Location: include/crypto/internal/hash.h:80
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_create
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
In crypto/shash.c (ffffffff81652ae1)
Location: include/crypto/internal/hash.h:80
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:shash_async_setkey
```
```
In crypto/hmac.c (ffffffff81657a62)
Location: include/crypto/internal/hash.h:80
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_create
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
In crypto/shash.c (ffffffff8170c721)
Location: include/crypto/internal/hash.h:86
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:shash_async_setkey
```
```
In crypto/hmac.c (ffffffff81711cb2)
Location: include/crypto/internal/hash.h:86
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_create
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
In crypto/shash.c (ffffffff81746231)
Location: include/crypto/internal/hash.h:86
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:shash_async_setkey
```
```
In crypto/hmac.c (ffffffff8174c875)
Location: include/crypto/internal/hash.h:86
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_create
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
In crypto/shash.c (ffffffff81788871)
Location: include/crypto/internal/hash.h:84
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/hmac.c (ffffffff8178e944)
Location: include/crypto/internal/hash.h:84
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_create
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
