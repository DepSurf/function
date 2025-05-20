# Function: <code>crypto_shash_blocksize</code>

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
In crypto/hmac.c (ffffffff813a4be8)
Location: include/crypto/hash.h:675
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_setkey
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
In crypto/hmac.c (ffffffff813e23e8)
Location: include/crypto/hash.h:713
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_setkey
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
In crypto/hmac.c (ffffffff813fb408)
Location: include/crypto/hash.h:713
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_setkey
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
In crypto/hmac.c (ffffffff81407ed8)
Location: include/crypto/hash.h:719
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_setkey
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/hmac.c (ffffffff81430858)
Location: include/crypto/hash.h:727
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_setkey
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/hmac.c (ffffffff814633b8)
Location: include/crypto/hash.h:726
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_setkey
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/hmac.c (ffffffff8148104b)
Location: include/crypto/hash.h:738
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_setkey
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/hmac.c (ffffffff814af25b)
Location: include/crypto/hash.h:737
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_setkey
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/hmac.c (ffffffff814c9eeb)
Location: include/crypto/hash.h:737
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_setkey
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/hmac.c (0)
Location: include/crypto/hash.h:750
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_setkey
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
In crypto/hmac.c (0)
Location: include/crypto/hash.h:758
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_setkey
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
In crypto/hmac.c (0)
Location: include/crypto/hash.h:762
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_setkey
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
In crypto/hmac.c (0)
Location: include/crypto/hash.h:762
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_setkey
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
In crypto/hmac.c (0)
Location: include/crypto/hash.h:762
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_setkey
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
In crypto/hmac.c (ffffffff81711dff)
Location: include/crypto/hash.h:764
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_setkey
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
In fs/verity/hash_algs.c (ffffffff8153c1aa)
Location: include/crypto/hash.h:816
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In crypto/hmac.c (ffffffff8174c9cf)
Location: include/crypto/hash.h:816
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_setkey
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
In fs/verity/hash_algs.c (ffffffff8157148a)
Location: include/crypto/hash.h:742
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In crypto/hmac.c (0)
Location: include/crypto/hash.h:742
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_setkey
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/hmac.c (ffff8000105c5b64)
Location: include/crypto/hash.h:737
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_setkey
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/hmac.c (c077290c)
Location: include/crypto/hash.h:737
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_setkey
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/hmac.c (c00000000074f458)
Location: include/crypto/hash.h:737
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_setkey
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/hmac.c (ffffffe000409c92)
Location: include/crypto/hash.h:737
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_setkey
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/hmac.c (ffffffff814c24cb)
Location: include/crypto/hash.h:737
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_setkey
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/hmac.c (ffffffff814b2eeb)
Location: include/crypto/hash.h:737
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_setkey
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/hmac.c (ffffffff814be55b)
Location: include/crypto/hash.h:737
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_setkey
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/hmac.c (ffffffff814d702b)
Location: include/crypto/hash.h:737
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_setkey
```
</details>
</li>
</ul>

## Differences
