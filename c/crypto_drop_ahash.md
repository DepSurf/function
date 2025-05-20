# Function: <code>crypto_drop_ahash</code>

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
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (ffffffff814398d0)
Location: include/crypto/internal/hash.h:99
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_free
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
In crypto/gcm.c (ffffffff8146c5bc)
Location: include/crypto/internal/hash.h:99
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_free
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
In crypto/gcm.c (ffffffff81489d2c)
Location: include/crypto/internal/hash.h:99
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_free
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
In crypto/gcm.c (ffffffff814b75f8)
Location: include/crypto/internal/hash.h:94
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_free
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
In crypto/gcm.c (ffffffff814d0818)
Location: include/crypto/internal/hash.h:94
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_free
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
In crypto/gcm.c (ffffffff8152fc12)
Location: include/crypto/internal/hash.h:111
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_create_common
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
In crypto/gcm.c (ffffffff8154cea4)
Location: include/crypto/internal/hash.h:98
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_create_common
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
In crypto/gcm.c (ffffffff81554e37)
Location: include/crypto/internal/hash.h:92
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_create_common
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
In crypto/gcm.c (ffffffff815b5e67)
Location: include/crypto/internal/hash.h:92
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_create_common
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
In crypto/gcm.c (ffffffff8165f0ee)
Location: include/crypto/internal/hash.h:92
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_create_common
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
In crypto/gcm.c (ffffffff8171907e)
Location: include/crypto/internal/hash.h:98
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_create_common
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
In crypto/gcm.c (ffffffff817549fe)
Location: include/crypto/internal/hash.h:98
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_create_common
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
In crypto/gcm.c (ffffffff8179672d)
Location: include/crypto/internal/hash.h:96
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_create_common
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
In crypto/gcm.c (ffff8000105cc080)
Location: include/crypto/internal/hash.h:94
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_free
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
In crypto/gcm.c (c07799f0)
Location: include/crypto/internal/hash.h:94
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_free
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
In crypto/gcm.c (c000000000758b20)
Location: include/crypto/internal/hash.h:94
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_free
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
In crypto/gcm.c (ffffffe000411348)
Location: include/crypto/internal/hash.h:94
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_free
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
In crypto/gcm.c (ffffffff814c8df8)
Location: include/crypto/internal/hash.h:94
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_free
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
In crypto/gcm.c (ffffffff814b9818)
Location: include/crypto/internal/hash.h:94
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_free
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
In crypto/gcm.c (ffffffff814c4e88)
Location: include/crypto/internal/hash.h:94
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_free
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
In crypto/gcm.c (ffffffff814dd958)
Location: include/crypto/internal/hash.h:94
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_free
```
</details>
</li>
</ul>

## Differences
