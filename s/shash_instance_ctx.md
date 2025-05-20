# Function: <code>shash_instance_ctx</code>

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
In crypto/hmac.c (ffffffff813a5048)
Location: include/crypto/internal/hash.h:218
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
In crypto/hmac.c (ffffffff813e2842)
Location: include/crypto/internal/hash.h:211
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
In crypto/hmac.c (ffffffff813fb862)
Location: include/crypto/internal/hash.h:211
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
In crypto/hmac.c (ffffffff814082e9)
Location: include/crypto/internal/hash.h:221
Inline: True
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
In crypto/hmac.c (ffffffff81430d30)
Location: include/crypto/internal/hash.h:233
Inline: True
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
In crypto/hmac.c (ffffffff814638ab)
Location: include/crypto/internal/hash.h:228
Inline: True
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
In crypto/hmac.c (ffffffff8148152b)
Location: include/crypto/internal/hash.h:228
Inline: True
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
In crypto/hmac.c (ffffffff814af70a)
Location: include/crypto/internal/hash.h:217
Inline: True
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
In crypto/hmac.c (ffffffff814ca3aa)
Location: include/crypto/internal/hash.h:217
Inline: True
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
In crypto/shash.c (ffffffff815254e5)
Location: include/crypto/internal/hash.h:236
Inline: True
Inline callers:
  - crypto/shash.c:shash_free_singlespawn_instance
```
```
In crypto/hmac.c (ffffffff815292f2)
Location: include/crypto/internal/hash.h:236
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
In crypto/shash.c (ffffffff81542415)
Location: include/crypto/internal/hash.h:229
Inline: True
Inline callers:
  - crypto/shash.c:shash_free_singlespawn_instance
```
```
In crypto/hmac.c (ffffffff81546304)
Location: include/crypto/internal/hash.h:229
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
In crypto/shash.c (ffffffff8154aab5)
Location: include/crypto/internal/hash.h:223
Inline: True
Inline callers:
  - crypto/shash.c:shash_free_singlespawn_instance
```
```
In crypto/hmac.c (ffffffff8154e99a)
Location: include/crypto/internal/hash.h:223
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
In crypto/shash.c (ffffffff815ab295)
Location: include/crypto/internal/hash.h:223
Inline: True
Inline callers:
  - crypto/shash.c:shash_free_singlespawn_instance
```
```
In crypto/hmac.c (ffffffff815af2ea)
Location: include/crypto/internal/hash.h:223
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
In crypto/shash.c (ffffffff81652a35)
Location: include/crypto/internal/hash.h:223
Inline: True
Inline callers:
  - crypto/shash.c:shash_free_singlespawn_instance
```
```
In crypto/hmac.c (ffffffff81657a2e)
Location: include/crypto/internal/hash.h:223
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
In crypto/shash.c (ffffffff8170c235)
Location: include/crypto/internal/hash.h:251
Inline: True
Inline callers:
  - crypto/shash.c:shash_free_singlespawn_instance
```
```
In crypto/hmac.c (ffffffff81711c7e)
Location: include/crypto/internal/hash.h:251
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
In crypto/shash.c (ffffffff81745b85)
Location: include/crypto/internal/hash.h:261
Inline: True
Inline callers:
  - crypto/shash.c:shash_free_singlespawn_instance
```
```
In crypto/hmac.c (ffffffff8174c83e)
Location: include/crypto/internal/hash.h:261
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
In crypto/shash.c (ffffffff817884f5)
Location: include/crypto/internal/hash.h:259
Inline: True
Inline callers:
  - crypto/shash.c:shash_free_singlespawn_instance
```
```
In crypto/hmac.c (ffffffff8178e90d)
Location: include/crypto/internal/hash.h:259
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
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/hmac.c (ffff8000105c60c8)
Location: include/crypto/internal/hash.h:217
Inline: True
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
In crypto/hmac.c (c0772db4)
Location: include/crypto/internal/hash.h:217
Inline: True
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
In crypto/hmac.c (c00000000074fbac)
Location: include/crypto/internal/hash.h:217
Inline: True
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
In crypto/hmac.c (ffffffe00040a132)
Location: include/crypto/internal/hash.h:217
Inline: True
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
In crypto/hmac.c (ffffffff814c298a)
Location: include/crypto/internal/hash.h:217
Inline: True
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
In crypto/hmac.c (ffffffff814b33aa)
Location: include/crypto/internal/hash.h:217
Inline: True
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
In crypto/hmac.c (ffffffff814bea1a)
Location: include/crypto/internal/hash.h:217
Inline: True
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
In crypto/hmac.c (ffffffff814d74ea)
Location: include/crypto/internal/hash.h:217
Inline: True
```
</details>
</li>
</ul>

## Differences
