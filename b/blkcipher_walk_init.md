# Function: <code>blkcipher_walk_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/crypto_null.c (ffffffff813a52a8)
Location: include/crypto/algapi.h:296
Inline: True
Inline callers:
  - crypto/crypto_null.c:skcipher_null_crypt
```
```
In crypto/ecb.c (ffffffff813a8f8a)
Location: include/crypto/algapi.h:296
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_decrypt
  - crypto/ecb.c:crypto_ecb_encrypt
```
```
In crypto/cbc.c (ffffffff813a92a3)
Location: include/crypto/algapi.h:296
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_encrypt
  - crypto/cbc.c:crypto_cbc_decrypt
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
In crypto/crypto_null.c (ffffffff813e2a88)
Location: include/crypto/algapi.h:354
Inline: True
Inline callers:
  - crypto/crypto_null.c:skcipher_null_crypt
```
```
In crypto/ecb.c (ffffffff813e6f5a)
Location: include/crypto/algapi.h:354
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_decrypt
  - crypto/ecb.c:crypto_ecb_encrypt
```
```
In crypto/cbc.c (ffffffff813e73f8)
Location: include/crypto/algapi.h:354
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_encrypt
```
```
In crypto/xts.c (ffffffff813e81ab)
Location: include/crypto/algapi.h:354
Inline: True
Inline callers:
  - crypto/xts.c:xts_crypt
  - crypto/xts.c:decrypt
  - crypto/xts.c:encrypt
```
```
In crypto/ctr.c (ffffffff813e89b3)
Location: include/crypto/algapi.h:354
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
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
In crypto/crypto_null.c (ffffffff813fbaa8)
Location: include/crypto/algapi.h:284
Inline: True
Inline callers:
  - crypto/crypto_null.c:skcipher_null_crypt
```
```
In crypto/ecb.c (ffffffff813ffd0a)
Location: include/crypto/algapi.h:284
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_decrypt
  - crypto/ecb.c:crypto_ecb_encrypt
```
```
In crypto/xts.c (ffffffff81400f2b)
Location: include/crypto/algapi.h:284
Inline: True
Inline callers:
  - crypto/xts.c:xts_crypt
```
```
In crypto/ctr.c (ffffffff81401fc3)
Location: include/crypto/algapi.h:284
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
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
In crypto/crypto_null.c (ffffffff81408553)
Location: include/crypto/algapi.h:300
Inline: True
Inline callers:
  - crypto/crypto_null.c:skcipher_null_crypt
```
```
In crypto/ecb.c (ffffffff8140cfef)
Location: include/crypto/algapi.h:300
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_decrypt
  - crypto/ecb.c:crypto_ecb_encrypt
```
```
In crypto/xts.c (ffffffff8140e256)
Location: include/crypto/algapi.h:300
Inline: True
Inline callers:
  - crypto/xts.c:xts_crypt
```
```
In crypto/ctr.c (ffffffff8140f873)
Location: include/crypto/algapi.h:300
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
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
In crypto/crypto_null.c (ffffffff81430f73)
Location: include/crypto/algapi.h:319
Inline: True
Inline callers:
  - crypto/crypto_null.c:skcipher_null_crypt
```
```
In crypto/ecb.c (ffffffff81435a5f)
Location: include/crypto/algapi.h:319
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_decrypt
  - crypto/ecb.c:crypto_ecb_encrypt
```
```
In crypto/xts.c (ffffffff81436d06)
Location: include/crypto/algapi.h:319
Inline: True
Inline callers:
  - crypto/xts.c:xts_crypt
```
```
In crypto/ctr.c (ffffffff81438373)
Location: include/crypto/algapi.h:319
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
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
In crypto/crypto_null.c (ffffffff81463afb)
Location: include/crypto/algapi.h:326
Inline: True
Inline callers:
  - crypto/crypto_null.c:skcipher_null_crypt
```
```
In crypto/ecb.c (ffffffff8146860b)
Location: include/crypto/algapi.h:326
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_decrypt
  - crypto/ecb.c:crypto_ecb_encrypt
```
```
In crypto/ctr.c (ffffffff8146ad1d)
Location: include/crypto/algapi.h:326
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
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
In crypto/crypto_null.c (ffffffff8148176b)
Location: include/crypto/algapi.h:328
Inline: True
Inline callers:
  - crypto/crypto_null.c:skcipher_null_crypt
```
```
In crypto/ecb.c (ffffffff8148627b)
Location: include/crypto/algapi.h:328
Inline: True
Inline callers:
  - crypto/ecb.c:crypto_ecb_decrypt
  - crypto/ecb.c:crypto_ecb_encrypt
```
```
In crypto/ctr.c (ffffffff8148857d)
Location: include/crypto/algapi.h:328
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_ctr_crypt
```
</details>
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
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
