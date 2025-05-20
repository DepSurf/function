# Function: <code>crypto_drop_cipher</code>

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
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff81523065)
Location: include/crypto/algapi.h:206
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_alloc_instance_simple
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff8153ffb9)
Location: include/crypto/algapi.h:206
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_alloc_instance_simple
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff81548579)
Location: include/crypto/internal/cipher.h:193
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_alloc_instance_simple
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff815a8d59)
Location: include/crypto/internal/cipher.h:193
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_alloc_instance_simple
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff816502a6)
Location: include/crypto/internal/cipher.h:193
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_alloc_instance_simple
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff81709a16)
Location: include/crypto/internal/cipher.h:193
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_alloc_instance_simple
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff817432f6)
Location: include/crypto/internal/cipher.h:195
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_alloc_instance_simple
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
In crypto/skcipher.c (ffffffff817855e8)
Location: include/crypto/internal/cipher.h:195
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_alloc_instance_simple
```
```
In crypto/ecb.c (ffffffff817927b5)
Location: include/crypto/internal/cipher.h:195
Inline: True
Inline callers:
  - crypto/ecb.c:lskcipher_alloc_instance_simple2
```
```
In crypto/xts.c (ffffffff8179454f)
Location: include/crypto/internal/cipher.h:195
Inline: True
Inline callers:
  - crypto/xts.c:xts_create
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
