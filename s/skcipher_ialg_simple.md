# Function: <code>skcipher_ialg_simple</code>

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
In crypto/cbc.c (ffffffff8152c720)
Location: include/crypto/internal/skcipher.h:214
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_create
```
```
In crypto/ctr.c (ffffffff8152e145)
Location: include/crypto/internal/skcipher.h:214
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_create
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
In crypto/cbc.c (ffffffff815496f0)
Location: include/crypto/internal/skcipher.h:214
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_create
```
```
In crypto/ctr.c (ffffffff8154b115)
Location: include/crypto/internal/skcipher.h:214
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_create
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
In crypto/cbc.c (ffffffff81551de0)
Location: include/crypto/internal/skcipher.h:214
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_create
```
```
In crypto/ctr.c (ffffffff81553735)
Location: include/crypto/internal/skcipher.h:214
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_create
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
In crypto/cbc.c (ffffffff815b2de0)
Location: include/crypto/internal/skcipher.h:214
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_create
```
```
In crypto/ctr.c (ffffffff815b4765)
Location: include/crypto/internal/skcipher.h:214
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_create
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
In crypto/cbc.c (ffffffff8165b96f)
Location: include/crypto/internal/skcipher.h:214
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_create
```
```
In crypto/ctr.c (ffffffff8165d644)
Location: include/crypto/internal/skcipher.h:214
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_create
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
In crypto/cbc.c (ffffffff8171517f)
Location: include/crypto/internal/skcipher.h:244
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_create
```
```
In crypto/ctr.c (ffffffff81717094)
Location: include/crypto/internal/skcipher.h:244
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_create
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
In crypto/cbc.c (ffffffff81750a2f)
Location: include/crypto/internal/skcipher.h:244
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_create
```
```
In crypto/ctr.c (ffffffff81752994)
Location: include/crypto/internal/skcipher.h:244
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_create
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/ctr.c (ffffffff81794904)
Location: include/crypto/internal/skcipher.h:275
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_create
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
