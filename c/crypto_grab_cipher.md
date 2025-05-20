# Function: <code>crypto_grab_cipher</code>

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
In crypto/skcipher.c (ffffffff81523048)
Location: include/crypto/algapi.h:196
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
In crypto/skcipher.c (ffffffff8153ffa5)
Location: include/crypto/algapi.h:196
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
In crypto/skcipher.c (ffffffff81548565)
Location: include/crypto/internal/cipher.h:183
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
In crypto/skcipher.c (ffffffff815a8d45)
Location: include/crypto/internal/cipher.h:183
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
In crypto/skcipher.c (ffffffff8165021a)
Location: include/crypto/internal/cipher.h:183
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
In crypto/skcipher.c (ffffffff8170998a)
Location: include/crypto/internal/cipher.h:183
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
In crypto/skcipher.c (ffffffff8174325a)
Location: include/crypto/internal/cipher.h:185
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
In crypto/skcipher.c (ffffffff8178554c)
Location: include/crypto/internal/cipher.h:185
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_alloc_instance_simple
```
```
In crypto/ecb.c (ffffffff81792719)
Location: include/crypto/internal/cipher.h:185
Inline: True
Inline callers:
  - crypto/ecb.c:lskcipher_alloc_instance_simple2
```
```
In crypto/xts.c (ffffffff81794686)
Location: include/crypto/internal/cipher.h:185
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
