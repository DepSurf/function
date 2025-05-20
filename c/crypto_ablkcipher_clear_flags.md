# Function: <code>crypto_ablkcipher_clear_flags</code>

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
In fs/ext4/crypto_key.c (0)
Location: include/linux/crypto.h:843
Inline: True
```
```
In crypto/skcipher.c (ffffffff813a1b53)
Location: include/linux/crypto.h:843
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
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
In crypto/skcipher.c (ffffffff813de003)
Location: include/linux/crypto.h:801
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
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
In crypto/skcipher.c (ffffffff813f58d3)
Location: include/linux/crypto.h:804
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
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
In crypto/skcipher.c (ffffffff81401b73)
Location: include/linux/crypto.h:804
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
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
In crypto/skcipher.c (ffffffff8142a1a3)
Location: include/linux/crypto.h:852
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
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
In crypto/skcipher.c (ffffffff8145cee3)
Location: include/linux/crypto.h:865
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
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
In crypto/skcipher.c (ffffffff8147a790)
Location: include/linux/crypto.h:1036
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
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
In crypto/skcipher.c (ffffffff814a8940)
Location: include/linux/crypto.h:1033
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
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
In crypto/skcipher.c (ffffffff814c35a0)
Location: include/linux/crypto.h:1033
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
```
</details>
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
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffff8000105bde28)
Location: include/linux/crypto.h:1033
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
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
In crypto/skcipher.c (c076bc3c)
Location: include/linux/crypto.h:1033
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
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
In crypto/skcipher.c (c000000000745354)
Location: include/linux/crypto.h:1033
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
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
In crypto/skcipher.c (ffffffe00040330e)
Location: include/linux/crypto.h:1033
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
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
In crypto/skcipher.c (ffffffff814bbb80)
Location: include/linux/crypto.h:1033
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
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
In crypto/skcipher.c (ffffffff814ac5a0)
Location: include/linux/crypto.h:1033
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
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
In crypto/skcipher.c (ffffffff814b7c10)
Location: include/linux/crypto.h:1033
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
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
In crypto/skcipher.c (ffffffff814d06f0)
Location: include/linux/crypto.h:1033
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
```
</details>
</li>
</ul>

## Differences
