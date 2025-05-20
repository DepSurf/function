# Function: <code>crypto_skcipher_alg_min_keysize</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/cts.c (ffffffff813e7fbe)
Location: include/crypto/internal/skcipher.h:147
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/ctr.c (ffffffff813e8fe2)
Location: include/crypto/internal/skcipher.h:147
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
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
In crypto/cts.c (ffffffff81400dee)
Location: include/crypto/internal/skcipher.h:184
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff8140178e)
Location: include/crypto/internal/skcipher.h:184
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (ffffffff81402603)
Location: include/crypto/internal/skcipher.h:184
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
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
In crypto/cts.c (ffffffff8140dda7)
Location: include/crypto/internal/skcipher.h:184
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff8140eb47)
Location: include/crypto/internal/skcipher.h:184
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (ffffffff8140f72f)
Location: include/crypto/internal/skcipher.h:184
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
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
In crypto/cts.c (ffffffff81436847)
Location: include/crypto/internal/skcipher.h:184
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff81437617)
Location: include/crypto/internal/skcipher.h:184
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (ffffffff8143822f)
Location: include/crypto/internal/skcipher.h:184
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
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
In crypto/cts.c (ffffffff814693a3)
Location: include/crypto/internal/skcipher.h:184
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff81469f40)
Location: include/crypto/internal/skcipher.h:184
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (ffffffff8146abc4)
Location: include/crypto/internal/skcipher.h:184
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
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
In crypto/cts.c (ffffffff81486d7c)
Location: include/crypto/internal/skcipher.h:182
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff81487c2c)
Location: include/crypto/internal/skcipher.h:182
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (ffffffff8148843a)
Location: include/crypto/internal/skcipher.h:182
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
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
In crypto/cts.c (ffffffff814b4e6b)
Location: include/crypto/internal/skcipher.h:177
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff814b5998)
Location: include/crypto/internal/skcipher.h:177
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (ffffffff814b5e8c)
Location: include/crypto/internal/skcipher.h:177
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
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
In crypto/cts.c (ffffffff814cd93b)
Location: include/crypto/internal/skcipher.h:182
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff814ceb98)
Location: include/crypto/internal/skcipher.h:182
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (ffffffff814cf08c)
Location: include/crypto/internal/skcipher.h:182
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
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
In crypto/cts.c (ffffffff8152cd38)
Location: include/crypto/internal/skcipher.h:164
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff8152ddfd)
Location: include/crypto/internal/skcipher.h:164
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (ffffffff8152e342)
Location: include/crypto/internal/skcipher.h:164
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
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
In crypto/cts.c (ffffffff81549dc0)
Location: include/crypto/internal/skcipher.h:164
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff8154adda)
Location: include/crypto/internal/skcipher.h:164
Inline: True
Inline callers:
  - crypto/xts.c:xts_create
```
```
In crypto/ctr.c (ffffffff8154b2f0)
Location: include/crypto/internal/skcipher.h:164
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
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
In crypto/cts.c (ffffffff81552402)
Location: include/crypto/internal/skcipher.h:164
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff81553405)
Location: include/crypto/internal/skcipher.h:164
Inline: True
Inline callers:
  - crypto/xts.c:xts_create
```
```
In crypto/ctr.c (ffffffff81553915)
Location: include/crypto/internal/skcipher.h:164
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
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
In crypto/cts.c (ffffffff815b3402)
Location: include/crypto/internal/skcipher.h:164
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff815b4435)
Location: include/crypto/internal/skcipher.h:164
Inline: True
Inline callers:
  - crypto/xts.c:xts_create
```
```
In crypto/ctr.c (ffffffff815b4945)
Location: include/crypto/internal/skcipher.h:164
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
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
In crypto/cts.c (ffffffff8165c411)
Location: include/crypto/internal/skcipher.h:164
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff8165d2cc)
Location: include/crypto/internal/skcipher.h:164
Inline: True
Inline callers:
  - crypto/xts.c:xts_create
```
```
In crypto/ctr.c (ffffffff8165d83b)
Location: include/crypto/internal/skcipher.h:164
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
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
In crypto/cts.c (ffffffff81715df1)
Location: include/crypto/internal/skcipher.h:194
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff81716dbc)
Location: include/crypto/internal/skcipher.h:194
Inline: True
Inline callers:
  - crypto/xts.c:xts_create
```
```
In crypto/ctr.c (ffffffff817173bb)
Location: include/crypto/internal/skcipher.h:194
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
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
In crypto/cts.c (ffffffff817516aa)
Location: include/crypto/internal/skcipher.h:194
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff8175268d)
Location: include/crypto/internal/skcipher.h:194
Inline: True
Inline callers:
  - crypto/xts.c:xts_create
```
```
In crypto/ctr.c (ffffffff81752cd4)
Location: include/crypto/internal/skcipher.h:194
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
</details>
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
In crypto/cts.c (ffff8000105c984c)
Location: include/crypto/internal/skcipher.h:182
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffff8000105ca808)
Location: include/crypto/internal/skcipher.h:182
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (ffff8000105caf24)
Location: include/crypto/internal/skcipher.h:182
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
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
In crypto/cts.c (c07773d4)
Location: include/crypto/internal/skcipher.h:182
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (c077841c)
Location: include/crypto/internal/skcipher.h:182
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (c0778aac)
Location: include/crypto/internal/skcipher.h:182
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
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
In crypto/cts.c (c000000000753f9c)
Location: include/crypto/internal/skcipher.h:182
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (c00000000075572c)
Location: include/crypto/internal/skcipher.h:182
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (c000000000755f98)
Location: include/crypto/internal/skcipher.h:182
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
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
In crypto/cts.c (ffffffe00040e51a)
Location: include/crypto/internal/skcipher.h:182
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffe00040ef54)
Location: include/crypto/internal/skcipher.h:182
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (ffffffe00040f628)
Location: include/crypto/internal/skcipher.h:182
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
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
In crypto/cts.c (ffffffff814c5f1b)
Location: include/crypto/internal/skcipher.h:182
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff814c7178)
Location: include/crypto/internal/skcipher.h:182
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (ffffffff814c766c)
Location: include/crypto/internal/skcipher.h:182
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
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
In crypto/cts.c (ffffffff814b693b)
Location: include/crypto/internal/skcipher.h:182
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff814b7b98)
Location: include/crypto/internal/skcipher.h:182
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (ffffffff814b808c)
Location: include/crypto/internal/skcipher.h:182
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
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
In crypto/cts.c (ffffffff814c1fab)
Location: include/crypto/internal/skcipher.h:182
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff814c3208)
Location: include/crypto/internal/skcipher.h:182
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (ffffffff814c36fc)
Location: include/crypto/internal/skcipher.h:182
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
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
In crypto/cts.c (ffffffff814daa7b)
Location: include/crypto/internal/skcipher.h:182
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff814dbcd8)
Location: include/crypto/internal/skcipher.h:182
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (ffffffff814dc1cc)
Location: include/crypto/internal/skcipher.h:182
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
</details>
</li>
</ul>

## Differences
