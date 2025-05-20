# Function: <code>get_random_bytes_wait</code>

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
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/big_key.c (ffffffff813bc180)
Location: include/linux/random.h:85
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_preparse
```
```
In crypto/rng.c (ffffffff8143c96c)
Location: include/linux/random.h:85
Inline: True
Inline callers:
  - crypto/rng.c:crypto_rng_reset
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
In security/keys/big_key.c (ffffffff813ed09b)
Location: include/linux/random.h:85
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_preparse
```
```
In crypto/rng.c (ffffffff8146f778)
Location: include/linux/random.h:85
Inline: True
Inline callers:
  - crypto/rng.c:crypto_rng_reset
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
In security/keys/big_key.c (ffffffff8140827b)
Location: include/linux/random.h:86
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_preparse
```
```
In crypto/rng.c (ffffffff8148d13a)
Location: include/linux/random.h:86
Inline: True
Inline callers:
  - crypto/rng.c:crypto_rng_reset
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
In security/keys/big_key.c (ffffffff814353f9)
Location: include/linux/random.h:87
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_preparse
```
```
In crypto/rng.c (ffffffff814baaaa)
Location: include/linux/random.h:87
Inline: True
Inline callers:
  - crypto/rng.c:crypto_rng_reset
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
In security/keys/big_key.c (ffffffff8144f179)
Location: include/linux/random.h:88
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_preparse
```
```
In crypto/rng.c (ffffffff814d387a)
Location: include/linux/random.h:88
Inline: True
Inline callers:
  - crypto/rng.c:crypto_rng_reset
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
In crypto/rng.c (ffffffff81532e9e)
Location: include/linux/random.h:90
Inline: True
Inline callers:
  - crypto/rng.c:crypto_rng_reset
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
In crypto/rng.c (ffffffff8154fe0e)
Location: include/linux/random.h:90
Inline: True
Inline callers:
  - crypto/rng.c:crypto_rng_reset
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
In crypto/rng.c (ffffffff81558314)
Location: include/linux/random.h:90
Inline: True
Inline callers:
  - crypto/rng.c:crypto_rng_reset
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
In crypto/rng.c (ffffffff815b95c4)
Location: include/linux/random.h:90
Inline: True
Inline callers:
  - crypto/rng.c:crypto_rng_reset
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
In security/keys/trusted-keys/trusted_core.c (ffffffff815b0353)
Location: include/linux/random.h:81
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_core.c:kernel_get_random
```
```
In crypto/rng.c (ffffffff81662b40)
Location: include/linux/random.h:81
Inline: True
Inline callers:
  - crypto/rng.c:crypto_rng_reset
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
In security/keys/trusted-keys/trusted_core.c (ffffffff8165ac23)
Location: include/linux/random.h:126
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_core.c:kernel_get_random
```
```
In crypto/rng.c (ffffffff8171ccf0)
Location: include/linux/random.h:126
Inline: True
Inline callers:
  - crypto/rng.c:crypto_rng_reset
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
In security/keys/trusted-keys/trusted_core.c (ffffffff81693523)
Location: include/linux/random.h:126
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_core.c:kernel_get_random
```
```
In crypto/rng.c (ffffffff8175848d)
Location: include/linux/random.h:126
Inline: True
Inline callers:
  - crypto/rng.c:crypto_rng_reset
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
In security/keys/trusted-keys/trusted_core.c (ffffffff816cfaf3)
Location: include/linux/random.h:126
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_core.c:kernel_get_random
```
```
In crypto/rng.c (ffffffff8179a38d)
Location: include/linux/random.h:126
Inline: True
Inline callers:
  - crypto/rng.c:crypto_rng_reset
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
In security/keys/big_key.c (ffff800010539ce4)
Location: include/linux/random.h:88
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_preparse
```
```
In crypto/rng.c (ffff8000105d0234)
Location: include/linux/random.h:88
Inline: True
Inline callers:
  - crypto/rng.c:crypto_rng_reset
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
In security/keys/big_key.c (c06f0314)
Location: include/linux/random.h:88
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_preparse
```
```
In crypto/rng.c (c077dcc8)
Location: include/linux/random.h:88
Inline: True
Inline callers:
  - crypto/rng.c:crypto_rng_reset
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
In security/keys/big_key.c (c000000000688b78)
Location: include/linux/random.h:88
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_preparse
```
```
In crypto/rng.c (c00000000075c420)
Location: include/linux/random.h:88
Inline: True
Inline callers:
  - crypto/rng.c:crypto_rng_reset
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
In security/keys/big_key.c (ffffffe0003982b2)
Location: include/linux/random.h:88
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_preparse
```
```
In crypto/rng.c (ffffffe000414f8c)
Location: include/linux/random.h:88
Inline: True
Inline callers:
  - crypto/rng.c:crypto_rng_reset
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
In security/keys/big_key.c (ffffffff81447759)
Location: include/linux/random.h:88
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_preparse
```
```
In crypto/rng.c (ffffffff814cbe5a)
Location: include/linux/random.h:88
Inline: True
Inline callers:
  - crypto/rng.c:crypto_rng_reset
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
In security/keys/big_key.c (ffffffff814381a9)
Location: include/linux/random.h:88
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_preparse
```
```
In crypto/rng.c (ffffffff814bc87a)
Location: include/linux/random.h:88
Inline: True
Inline callers:
  - crypto/rng.c:crypto_rng_reset
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
In security/keys/big_key.c (ffffffff814437f9)
Location: include/linux/random.h:88
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_preparse
```
```
In crypto/rng.c (ffffffff814c7eea)
Location: include/linux/random.h:88
Inline: True
Inline callers:
  - crypto/rng.c:crypto_rng_reset
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
In security/keys/big_key.c (ffffffff8145ab29)
Location: include/linux/random.h:88
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_preparse
```
```
In crypto/rng.c (ffffffff814e09ba)
Location: include/linux/random.h:88
Inline: True
Inline callers:
  - crypto/rng.c:crypto_rng_reset
```
</details>
</li>
</ul>

## Differences
